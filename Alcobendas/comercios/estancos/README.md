Las transformaciones realizadas en estancos.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se ha sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "postalCode" se han sustituido por "postal_code".

· Se ha separado la columna "street_address" en "tipo_via", "nombre_via" y "numero_via". Así, "CALLE CEUTA (DE) 12" quedaría con "CALLE" como "tipo_via", "CEUTA (DE)" como "nombre_via" y "12" como "numero_via". La columna "nombre_titular" se ha separado en "nombre_titular", "apellido1_titular" y "apellido2_titular". De esta manera, "ANA NOVILLO PEREA" queda con "ANA" como "nombre_titular", "NOVILLO" como "apellido1_titular" y "PEREA" como "apellido2_titular".