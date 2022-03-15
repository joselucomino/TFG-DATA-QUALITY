Las transformaciones realizadas en electrolineras.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "tipoEquipamiento" se han sustituido por "tipo_equipamiento".

· Se han eliminado las columnas vacías como "email" o "telephone", entre otras.

· Se ha dividido la dirección en "tipo_via", "nombre_via" y "numero_via". De manera que "C/ Ramón Pignatelli, 102" quedaría dividida en "Calle" como "tipo_via", "Ramón Pignatelli" como "nombre_via" y "102" como "numero_via".

· Se han dejado únicamente las columnas "latitud" y "longitud", eliminando así las columnas "geometry", "xETRS89" e "yETRS89", ya que estas dos últimas estaban vacías, y el sistema recomendado es el usado en "latitud" y "longitud", no el de "geometry".