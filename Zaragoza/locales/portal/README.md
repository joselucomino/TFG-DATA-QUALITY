Las transformaciones realizadas en portal.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "idVia" se han sustituido por "id_via".

· Se ha dividido la columna "geometry" en "coordenada_x_utm" y "coordenada_y_utm", a pesar de que se recomienda utilizar el sistema de coordenadas WGS84. Así, valores como "674483.0 4613258.0" de la columna "geometry" quedan divididos con "674483.0" en "coordenada_x_utm" y "4613258.0" en "coordenada_y_utm".

· Se ha añadido una columna "tipo_via" para "title", para distinguir el nombre de la vía con el tipo de la vía. "CALLE PREDICADORES" quedaría dividida en "CALLE" como "tipo_via" y "PREDICADORES" como "title".