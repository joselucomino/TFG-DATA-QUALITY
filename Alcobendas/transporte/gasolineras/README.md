Las transformaciones realizadas en gasolineras.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se ha sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "Código postal" se han sustituido por "codigo_postal".

· Se han sustituido las celdas vacías por "desconocido", para cumplir con la recomendación de que todas las filas tengan el mismo número de columnas.

· Se ha separado la columna "direccion" en "tipo_via", "nombre_via" y "numero_via". Así, "AVENIDA MONTE DE VALDELATAS, 5" quedaría con "AVENIDA" como "tipo_via", "MONTE DE VALDELATAS" como "nombre_via" y "5" como "numero_via".

· Se ha añadido una primera columna "id" para asignar a cada fila un ID único.

· Se ha añadido una columna por cada columna "gases_licuados_petroleo", "gasoleo_A", "gasolina_95", "gasolina_98" y "nuevo_gasoleo_A" con la unidad de medida de cada una de ellas.