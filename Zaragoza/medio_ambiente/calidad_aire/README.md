Las transformaciones realizadas en listado.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "creationDate" se han sustituido por "creation_date".

· Se han eliminado las columnas vacías, y se han sustituido las celdas vacías por "desconocido" para cumplir con que todas las filas tengan el mismo número de columnas.

· Se han creado columnas "unidad_distancia", "unidad_via" y "unidad_altitud" a partir de "distancia", "via" y "altitud", separando el valor numérico de la unidad para respetar las recomendaciones de tener solo un tipo de dato por columna, y que una columna sea la del valor y otra la de la unidad. Así, la columna inicial "distancia" que contenía "25 m", ahora la columna "distancia" contendrá "25", y "unidad_distancia" contedrá "m".

· Se ha añadido una columna con el tipo de vía de cada dirección, para distinguir el nombre de la vía con el tipo de la vía. "calle Cineasta Carlos Saura" quedaría dividida en "Calle" como "tipo_direccion" y "Cineasta Carlos Saura" como "nombre_direccion".

· Se han representado todos los decimales con punto (.). Valores en como "5,2" se han modificado a "5.2".