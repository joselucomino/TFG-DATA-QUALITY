Las transformaciones realizadas en registro_licencia.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "codPortal" se han sustituido por "cod_portal".

· Se han sustituido las celdas vacías de "fecha_baja" por "abierto", y de "actividad" y "last_updated" por "DESCONOCIDO", para cumplir con que todas las filas tengan el mismo número de columnas.

· Se ha dividido la columna "geometry" en "coordenada_x_utm" y "coordenada_y_utm", a pesar de que se recomienda utilizar el sistema de coordenadas WGS84. Así, valores como "676464.0 4613998.0" de la columna "geometry" quedan divididos con "676464.0" en "coordenada_x_utm" y "4613998.0" en "coordenada_y_utm".

· Se ha añadido una columna "tipo_via" para "emplazamiento", para distinguir el nombre de la vía con el tipo de la vía. "CALLE MANIFESTACION, 2 (ZARAGOZA)" quedaría dividida en "CALLE" como "tipo_via" y "MANIFESTACION" como emplazamiento, ya que se ha eliminado "(ZARAGOZA)" porque todos los emplazamientos pertenecen a Zaragoza, y el número de la vía porque ya existe una columna "num_via" con ese dato.