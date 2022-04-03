Las transformaciones realizadas en sepe.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se ha sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "Fecha de nacimiento" se han sustituido por "fecha_nacimiento".

· Se han sustituido las celdas vacías por "desconocido", para cumplir con la recomendación de que todas las filas tengan el mismo número de columnas.

· Se ha añadido una columna "id" para asignar a cada fila un ID único.

· Se han cambiado las fechas al formato ISO8601, quedando como "YYYY-MM-DD". Así, valores como "20211102" quedan como "2021-11-02", o "23/01/1964" como "1964-01-24".

· Se ha dividido la columna "periodo" en "mes" y "año", para cumplir con la recomendación de que si no se tiene información completa sobre una fecha, debe representarse en diversas columnas. "11/21" en "periodo" queda como "11" en "mes" y "2021" en "año".