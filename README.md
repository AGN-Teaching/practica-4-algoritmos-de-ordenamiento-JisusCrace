[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ke8zCzPd)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-7f7980b617ed060a017424585567c406b6ee15c891e84e1186181d67ecf80aa0.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=13627531)
![logo-uam](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-JisusCrace/assets/125590988/193089ae-92be-49bb-b1c7-85aed94e956d)


# *PRÁCTICA 4: ALGORITMOS DE ORDENAMIENTO*

### *CARRERA: INGENIERÍA EN COMPUTACIÓN*

### *MATERIA: ESTRUCTURA DE DATOS LINEALES*

### *ALUMNO: RAMIREZ AGUILERA JESUS EMMANUEL *
### * MATRICULA : 2223068873 * 
### *DOCENTE: ABEL GARCÍA NÁJERA*
-------------------------------------------

# :loudspeaker: *DESCRIPCIÓN DEL PROBLEMA*
El problema se centra en el ordenamiento de una secuencia de números. Se busca comparar experimentalmente el tiempo de ejecución de cinco algoritmos de ordenamiento: insertion sort, selection sort, bubblesort, merge sort y quicksort.

Se implementó un programa de control denominado ordenamiento.cpp, capaz de recibir por línea de comando el tamaño del arreglo (n) y el número de arreglos a generar y ordenar (m). En cada iteración, se generaron arreglos con números aleatorios y se aplicaron los cinco algoritmos de ordenamiento, registrando los tiempos de ejecución en un archivo de salida estructurado.

# :bar_chart: *RESULTADOS Y ANÁLISIS*

La experimentación arrojó datos valiosos sobre el desempeño de los algoritmos de ordenamiento en diversos escenarios. A continuación, se presentan los resultados en una tabla estructurada, proporcionando una visión completa de las ejecuciones y tiempos registrados para cada algoritmo y tamaño de arreglo.

## Tabla de resultados: 

![image](https://github.com/AGN-Teaching/practica-4-algoritmos-de-ordenamiento-JisusCrace/assets/125590988/e21054db-e1c1-422e-be03-a080896e1916)

### - Cálculos Estadísticos

Para cada tamaño de arreglo y algoritmo, se calcularon el promedio  y la desviación estándar de los tiempos de ejecución. Estos valores proporcionan una medida más robusta de la eficiencia de cada algoritmo.


### - Análisis de Tendencias

Observando los resultados, se destacan algunas tendencias interesantes. En los casos de arreglos pequeños (n = 5, 10), insertion sort y selection sort pueden mostrar un rendimiento comparable, mientras que en tamaños más grandes, la brecha de eficiencia entre los algoritmos cuadráticos y los de complejidad n * log(n) se vuelve más evidente.

La eficiencia de merge sort y quicksort se destaca especialmente en arreglos de gran tamaño, confirmando su superioridad teórica en términos de tiempo de ejecución. Sin embargo, es crucial tener en cuenta que estos resultados pueden variar según la implementación y las características específicas de la máquina utilizada.

## Gráficos de Rendimiento:

Se adjuntan gráficos que visualizan la eficiencia de cada algoritmo en función del tamaño del arreglo. Estas representaciones gráficas ofrecen una comprensión más intuitiva de las diferencias de rendimiento y permiten identificar patrones o puntos de inflexión en el comportamiento de los algoritmos.


# :trophy: *CONCLUSIONES*  

