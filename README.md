# TFG
Este repositorio consiste en un Trabajo Fin de Grado, el cual consiste en un proyecto de comprobación de calidad de los datos abiertos de distintas ciudades españolas.
En el proyecto se aplicará una checklist como guía de comprobación de calidad de los datos abiertos publicados por el ayuntamiento de la ciudad y se realizarán modificaciones sobre los datos ya publicados, con el objetivo de ofrecer recomendaciones al propio ayuntamiento sobre cómo publicar sus datos y así potenciar el sistema de información al público sobre esta ciudad.
En cuanto a la organización del repositorio, al inicio se encuentra un directorio por cada ciudad analizada, además de la checklist 'referencias_checklist.pdf' y la plantilla para rellenar en cada conjunto de datos, tanto en formato .docx como .md. Dentro del directorio de cada ciudad, podemos encontrar el CSV original, el modificado, el JSON y la checklist con los cambios.

## Procedimiento
El primer paso es el de crear una checklist, o guía de comprobación, la cual sirve como proceso de automatización a la hora de analizar un dataset y revisar su calidad.
Una vez está la checklist creada, el siguiente paso es el de aplicar el proceso de limpieza del dataset, siguiendo las recomendaciones de la checklist. Así, obtendremos el nuevo dataset CSV junto con el JSON generado con los cambios, además de conservar el antiguo CSV por si se necesitara consultar o fuera de interés.
Por último, el objetivo es el de crear un informe final de recomendaciones para publicaciones de futuros datasets, de acuerdo a los errores encontrados más comunes.

## Referencias
Todo ello viene acompañado de lecturas de documentos que se han usado como referencia para realizar la checklist. En el siguiente enlace se encuentra información de utilidad que ha sido recopilada para la creación de la checklist: https://ciudades-abiertas.es/index.html