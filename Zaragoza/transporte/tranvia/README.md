Las transformaciones realizadas en parada_tranvia.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "lastUpdated" se han sustituido por "last_updated".

· Se ha eliminado la columna "destinos", que estaba vacía.

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.8707787699110215,41.687216424958216" quedan divididos en "-0.8707787699110215" como "longitud" y "41.687216424958216" como "latitud".