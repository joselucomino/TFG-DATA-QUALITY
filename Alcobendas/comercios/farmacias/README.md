Las transformaciones realizadas en farmacias.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se ha sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "tipoActividadEconomica" se han sustituido por "tipo_actividad_economica".

· Se han sustituido las celdas vacías por "desconocido", para cumplir con la recomendación de que todas las filas tengan el mismo número de columnas.

· Se ha separado la columna "street_address" en "tipo_via", "nombre_via" y "numero_via". Así, "PASEO CHOPERA (DE LA) 71" quedaría con "PASEO" como "tipo_via", "CHOPERA (DE LA)" como "nombre_via" y "71" como "numero_via". La columna "nombre_titular" se ha separado en "nombre_titular", "apellido1_titular" y "apellido2_titular". De esta manera, "LAURA MARTINEZ GAITE" queda con "LAURA" como "nombre_titular", "MARTINEZ" como "apellido1_titular" y "GAITE" como "apellido2_titular".