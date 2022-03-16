Las transformaciones realizadas en estacion_bicicleta.csv han sido:

· Se han convertido las letras mayúsculas en minúsculas, y la separación de palabras se han sustituido por el subrayado. Esto hace referencia a los encabezados, donde títulos como "estadoEstacion" se han sustituido por "estado_estacion".

· Se ha separado la columna "address" en "tipo_via_1", "address_1", "tipo_via_2" y "address_2". Un ejemplo de ello, "C/ Corona de Aragón - C/ Lorente" que pertenecía a "address", ha quedado como "Calle" en "tipo_via_1", "Corona de Aragón" en "address_1", "Calle" en "tipo_via_2" y "Lorente" en "address_2". Cabe destacar que si alguna celda se ha quedado vacía al realizar la separación, se ha completado como "desconocido".

· Se ha dividido la columna "geometry" en "longitud" y "latitud", siguiendo el sistema de coordenadas WGS84. Así, la columna "geometry" que contenía valores como "-0.8979132352053497,41.64401875747108" quedan divididos en "-0.8979132352053497" como "longitud" y "41.64401875747108" como "latitud".