Las transformaciones realizadas en aparcamiento_bicicleta.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "lastUpdated" se han sustituido por "last_updated".

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.8611007934151447,41.66017411919716" quedan divididos en "-0.8611007934151447" como "longitud" y "41.66017411919716" como "latitud".