Las transformaciones realizadas en aparcamiento_moto.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "lastUpdated" se han sustituido por "last_updated".

· Se ha separado la columna "description" en "nombre_via" y "numero_via", faltando por añadir la columna "tipo_via". Así, "ARIAS, 24" quedaría con "ARIAS" como "nombre_via" y "24" como "numero_via".

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.9085080337297776,41.65396360947344" quedan divididos en "-0.9085080337297776" como "longitud" y "41.65396360947344" como "latitud".