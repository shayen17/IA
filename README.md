# README - Red de Hopfield





## Presentación de la Red de Hopfield

La red de Hopfield es un modelo de red neuronal recurrente que se utiliza para almacenar y recuperar patrones binarios. Se entrena con un conjunto de patrones y es capaz de reconstruir estos patrones, incluso si se presentan patrones parciales o con ruido.



## Informe de Corridas y Evaluación de Resultados

### Corridas con Dataset 1

Ejecutamos el programa con el Dataset 1, que contiene datos binarios representados en el archivo `datos.csv`. Los resultados de las corridas incluyen:

- Después de entrenar la red de Hopfield con el Dataset 1, realizamos consultas con patrones de entrada y obtuvimos resultados satisfactorios. La red fue capaz de recuperar patrones almacenados incluso cuando se presentaron patrones parciales o con ruido.

- Observamos que la red de Hopfield es efectiva para recuperar patrones almacenados en condiciones ideales y con patrones de entrada similares a los patrones almacenados en el dataset.

### Corridas con Dataset 2

Repetimos el proceso anterior utilizando el Dataset 2, que contiene datos binarios representados en el archivo `datos2.csv`. Los resultados de las corridas incluyen:

- Al igual que con el Dataset 1, después de entrenar la red de Hopfield con el Dataset 2, obtuvimos resultados satisfactorios en las consultas. La red demostró su capacidad para recuperar patrones almacenados incluso en presencia de patrones parciales o con ruido.

- En comparación con el Dataset 1, observamos que la red de Hopfield sigue siendo eficaz en la recuperación de patrones con el Dataset 2, lo que demuestra su robustez.

### Evaluación de Resultados

En general, los resultados obtenidos con ambos datasets indican que la red de Hopfield es una herramienta eficaz para el almacenamiento y recuperación de patrones binarios. La red muestra una buena capacidad para recuperar patrones almacenados, incluso en condiciones desafiantes. Sin embargo, es importante tener en cuenta que su rendimiento puede depender de la calidad de los patrones almacenados y la similitud de los patrones de entrada.

---


