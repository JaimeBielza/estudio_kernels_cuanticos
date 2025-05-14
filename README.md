# Estudio kernels cuanticos
Este repositorio contiene el código completo desarrollado para el Trabajo Fin de Grado de **Jaime Bielza Poza**, titulado “Estudio de kernels cuánticos para máquinas de soporte vectorial”. Aquí encontrarás todo lo necesario para reproducir los experimentos comparativos entre clasificadores SVM clásicos y cuánticos.

**Resumen del Proyecto**
En un contexto donde el volumen de datos y la complejidad de los modelos de machine learning
crecen sin cesar, encontrar soluciones eficientes para tareas clásicas como la clasificación supervisada
se vuelve cada vez más desafiante. Esto es especialmente cierto cuando trabajamos con datos de alta
dimensionalidad o con estructuras que no son lineales de forma evidente.
Ante este panorama, la computación cuántica surge como una alternativa prometedora. Gracias a
los principios de la mecánica cuántica, ofrece nuevas formas de representar la información y descubrir
patrones complejos que podrían quedar fuera del alcance de los algoritmos clásicos. Uno de los enfo-
ques más interesantes en este campo es la Quantum Kernel Estimation (QKE), una técnica que busca
mejorar modelos clásicos mediante el uso de kernels cuánticos construidos a partir de la fidelidad entre
estados cuánticos codificados a partir de los datos de entrada.
Este trabajo se centra en analizar el comportamiento, la capacidad de generalización y el ren-
dimiento de estos modelos cuánticos basados en kernels. Para ello, se ha desarrollado un pipeline
completo y modular que permite comparar diferentes configuraciones de circuitos cuánticos con mo-
delos clásicos de referencia —como SVM o regresión logística— aplicados a conjuntos de datos tanto
sintéticos como reales.
El objetivo del trabajo es doble:
Didáctico, al presentar una implementación clara y reutilizable del flujo de trabajo híbrido cuántico-
clásico, adaptable a distintos dominios de datos.
Experimental y estadístico, al evaluar rigurosamente, mediante múltiples réplicas y pruebas,
cómo se comportan los modelos cuánticos en comparación con los clásicos en escenarios de
distinta complejidad.
Palabras clave: Computación cuántica, aprendizaje automático, clasificación binaria, Quantum Kernel
Estimation, Fidelity Quantum Kernel, feature maps cuánticos, comparación cuántico-clásica, regresión
logística, máquinas de vectores soporte, reducción de dimensionalidad, análisis estadístico.
