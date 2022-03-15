Las transformaciones realizadas en ingreso_corriente.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "idCapitulo" se han sustituido por "id_capitulo".

· Se han cambiado las fechas al formato ISO8601. Por ejemplo, la columna "fecha" tenía valores como "20220128" que se han modificado quedando como "YYYY-MM-DD", "2022-01-28".

· Se han añadido una nueva columna para las unidades de "prevision_inicial", "prevision_modificacion", "prevision_definitivo", "derechos_reconocidos", "derechos_anulados_devoluciones", "derechos_cancelados", "derechos_reconocidos_netos", "recaudacion_neta", "derechos_pendientes_cobro" y "exceso_defecto_prevision". Así, cumplen con la recomendación de tener una columna con el valor, y otra con la unidad.