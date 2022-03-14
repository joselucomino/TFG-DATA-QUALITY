Las transformaciones realizadas en cuenta_bancaria.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "fechaContable" se han sustituido por "fecha_contable".

· Se han eliminado las columnas vacías y la columna "fecha_contable", puesto que es redundante con fecha solo que con otro formato. "31/12/2021" y "20211231".
A su vez, la fecha que se ha dejado, se ha cambiado al formato ISO8601, quedando como "YYYY-MM-DD", "2021-12-31".

· Se han eliminado los 3 primeros dígitos de "title", porque pertenecen a "code" y estarían duplicados.
Por ejemplo, la columna "code" tenía como valor "B014", y "title" empezaba por "014-BANCO SANTANDER". Esto se ha reducido a la columna valor tal y como está, y a "title" empezando directamente con "BANCO SANTANDER".

· Para cumplir la recomendación de que las unidades de medida y los valores deben indicarse por separado, se ha creado una nueva columna "unidades_saldo" que contiene la unidad en la que se mide la columna "saldo".
