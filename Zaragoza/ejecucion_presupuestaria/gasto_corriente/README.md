Las transformaciones realizadas en gasto_corriente.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "idOrgano" se han sustituido por "id_organo".

· Se han cambiado las fechas al formato ISO8601. Por ejemplo, la columna "fecha" tenía valores como "20220128" que se han modificado quedando como "YYYY-MM-DD", "2022-01-28".

· Se han añadido una nueva columna para las unidades de "credito_inicial", "credito_modificacion", "credito_definitivo", "gasto_comprometido", "obligacion_neta", "pago_neto", "obligacion_pendiente_pago" y "remanente_credito". Así, cumplen con la recomendación de tener una columna con el valor, y otra con la unidad.