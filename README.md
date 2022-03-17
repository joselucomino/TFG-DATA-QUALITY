# Proceso de chequeo de la calidad de los datos abiertos publicados por ciudades españolas
Este repositorio está relacionado con un Trabajo Fin de Grado (TFG) realizado en el contexto del Grado de Ingeniería Informática de la Escuela Técnica Superior de Ingenieros Informáticos de la Universidad Politécnica de Madrid. 

En este TFG se aborda la comprobación de la calidad de varios de los conjuntos de datos disponibles en los portales de datos abiertos de varias ciudades españolas. Para ello, en el proyecto se aplicará una checklist como guía de comprobación de calidad de los datos abiertos publicados y se realizarán modificaciones sobre los datos ya publicados, con el objetivo de ofrecer recomendaciones a los proveedores de datos (generalmente, los responsables de datos abiertos de las ciudades o sus departamentos) sobre cómo publicar sus datos con mayores garantías de calidad.

El repositorio se organiza de la siguiente manera: 
* Una checklist 'referencias_checklist.pdf' y la plantilla para rellenar en cada conjunto de datos, también en formatos MS Word y Markdown. Esta checklist se obtiene de la siguiente fuente: Corcho, Oscar, & De Pablo, Vicky. (2022). Adaptación de estructuras de conjuntos de datos para asegurar su calidad y anonimización. Informe técnico del proyecto Ciudades Abiertas (1.0). Zenodo. https://doi.org/10.5281/zenodo.5942552
* Un directorio por cada ciudad analizada
* Dentro de cada directorio de cada ciudad, se encuentra por cada conjunto de datos el CSV original, el modificado, el JSON y la checklist con los cambios.

## Procedimiento
El primer paso ha sido el de crear una checklist, o guía de comprobación, la cual sirve como proceso de automatización a la hora de analizar un dataset y revisar su calidad.

Una vez está la checklist creada, el siguiente paso es el de aplicar el proceso de limpieza del dataset, siguiendo las recomendaciones de la checklist. Así, se obtiene el nuevo dataset CSV junto con el JSON generado con los cambios, además de conservar el antiguo CSV por si se necesitara consultar o fuera de interés.

Por último, se creará un informe final de recomendaciones para publicaciones de futuros datasets, de acuerdo a los errores encontrados más comunes.

## Referencias
En el siguiente enlace se encuentra información de utilidad que ha sido recopilada para la creación de la checklist: https://ciudades-abiertas.es/
