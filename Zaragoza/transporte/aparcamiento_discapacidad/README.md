Las transformaciones realizadas en aparcamiento_personas_discapacidad.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "lastUpdated" se han sustituido por "last_updated".

· Se ha separado la columna "description" en "tipo_via", "nombre_via" y "numero_via". Así, "CALLE EDUARDO JESUS TABOADA, 11" quedaría con "CALLE" como "tipo_via", "JEAN PAUL SARTRE" como "nombre_via" y "11" como "numero_via".

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.8736905991777034,41.678752821843005" quedan divididos en "-0.8736905991777034" como "longitud" y "41.678752821843005" como "latitud".