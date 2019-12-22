# XNN

Extendiendo la Semántica de los datos en Aprendizaje Supervisado

Resumen. En este trabajo, centrado en el área del aprendizaje supervisado, pretendemos extender la información que proporcionan los datos etiquetados. Basándonos en la técnica de los vecinos más cercanos, se amplía la información contenida en las etiquetas discretas de las instancias, fortaleciendo su semántica y perfeccionando una clasificación posterior. Para ello, por cada instancia del conjunto de entrenamiento se obtiene información acerca de las distancias a las instancias más cercanas de clase contraria. Mediante un modelo geométrico se transforma cada etiqueta y es extendida y representada por un punto en Rn-1 (donde n es el número de valores distintos de la clase discreta). Utilizando el conjunto de datos de UCI, hemos realizado dos experimentos para validar nuestra propuesta y verificar que no existe pérdida de información y que es posible nuevas prestaciones al reemplazar una clase discreta por una continua.

## Instalación

a) Abrir Package Manager de Weka
b) Pulsar el botón File/URL
c) Escribir la dirección: https://github.com/gualbe/XNN/raw/master/XNN.zip
d) Pulsar el botón OK
e) Reiniciar Weka
f) Usar el filtro "unsupervised/attribute/XNNFilter" y el clasificador "lazy/XNN".
