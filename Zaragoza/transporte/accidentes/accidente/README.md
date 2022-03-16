Las transformaciones realizadas en accidente.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "firstAddress" se han sustituido por "first_address".

· Se ha eliminado la columna vacía "accident_type" y las celdas vacías se han sustituido por "DESCONOCIDO", para cumplir la recomendación de que todas las filas tengan el mismo número de columnas.

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.8818527060979306,41.649027473051156" quedan divididos en "-0.8818527060979306" como "longitud" y "41.649027473051156" como "latitud".

· Falta añadir una columna "tipo_via_first_address" para "first_address" y otra columna "tipo_via_second_address" para "second_address" para identificar el tipo de la vía.