# Proyecto de Reconocimiento de Vocales: Teoría de Señales de Comunicaciones
Proyecto para la identificación de vocales, se utilizó MATLAB y el modelo de Support Vector Machine para la 
clasificación de las 5 vocales en español. Utiliza la aplicación de Classification Learner de MATLAB para
generar un modelo tanto para el dataset de hombre como para el de mujer.

La precisión del modelo de hombre es del 98%, sin embargo, si se utiliza el SVM optimizable se puede lograr
el 100%, lamentablemente en el dataset de mujeres no tuvimos tantas muestras como en el de hombres, por lo
que se ve reflejado en la precisión de 90% en el modelo.

Está hecho en un Live Script para hacer sencillo su uso, para probarlo se requiere un audio de 1.5 segundos
en formato WAV a una frecuencia de muestreo de 7680 Hertz. O, utilizar la sección que graba audio desde el
ordenador del usuario.
