Las transformaciones realizadas en parada_taxi.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "lastUpdated" se han sustituido por "last_updated".

· Se ha separado la columna "title" en "tipo_via", "nombre_via" y "numero". Un ejemplo de ello, "CALLE ALCALDE GOMEZ LAGUNA, 25" que pertenecía a "title", ha quedado como "CALLE" en "tipo_via", "ALCALDE GOMEZ LAGUNA" en "nombre_via" y "25" en "numero".

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.9097477711138128,41.64174414911776" quedan divididos en "-0.9097477711138128" como "longitud" y "41.6417441491176" como "latitud".