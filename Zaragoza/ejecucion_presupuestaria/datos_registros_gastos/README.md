Las transformaciones realizadas en datos_registros_gastos.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "creditoInicial" se han sustuido por "credito_inicial".

· Se han cambiado las fechas al formato ISO8601. Por ejemplo, la columna "fecha" tenía valores como "20111231" que se han modificado quedando como "YYYY-MM-DD", "2011-12-31".

· Se han añadido una nueva columna para las unidades de "credito_inicial", "credito_modificacion", "credito_definitivo", "gasto_comprometido", "obligacion_neta", "pago_neto", "obligacion_pendiente_pago" y "remanente_credito". Así, cumplen con la recomendación de tener una columna con el valor, y otra con la unidad.