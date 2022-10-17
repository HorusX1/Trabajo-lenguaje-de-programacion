# Trabajo-lenguaje-de-programacion
ayuda soy de la utem y necesito un 7 para relajarme en este ramo kl 

Con propósitos didácticos se le solicita desarrollar una aplicación que aporte a la comprensión de algunos de los conceptos tratados en la asignatura Lenguajes de Programación. Los conceptos seleccionados para este propósito son sintaxis mediante BNF, operaciones de desplazamiento de bits, linealización de estructuras dinámicas, referencias inválidas, linealización de arreglos bidimensionales y representación de conjuntos. En consecuencia, la referida aplicación debe contemplar un menú con las opciones atingentes a los conceptos indicados, a través de las siguientes acciones:
1)	Reconocimiento de secuencias, de longitud máxima 10, descritas mediante las siguientes reglas BNF:
<RUN> ::= <NN> - <DV>
<NN> ::= <DD> | <DD> <NN>
<DV> ::= <DD> | K
<DD> ::= 0 | 1 | 2 | … | 9

2)	Operaciones multiplicación y división por potencias mayores que dos utilizando shift.
3)	Operaciones creación y despliegue de una matriz triangular T, es decir, una matriz cuadrada en la cual los elementos situados sobre o bajo una de sus diagonales tienen el valor cero. Se debe considerar, en memoria, una representación unidimensional de T linealizada por columnas, la cual sólo contenga los elementos significativos, es decir, que omita aquellos predefinidos con el valor cero. El acceso a los elementos debe ser de manera bidimensional, es decir, referenciando elementos de índices [i][j] de modo que a partir de éstos se genere el correspondiente índice [k] de la representación unidimensional.
4)	Operaciones unión, intersección y diferencia referidas a un conjunto base T = {x / 0 ≤ x ≤ 15}.
En todos los casos, se debe incluir código relativo a la captura de datos y al despliegue de resultados, con la finalidad de validar el cumplimiento de lo solicitado.
5)	Implementación por programación, del esquema de contador de referencias para controlar y evitar el “Dangling Reference” de memoria, con un claro despliegue de las estructuras utilizadas para tal efecto en cada etapa de la asignación y la devolución de memoria.

 
REQUERIMIENTO
I.	Desarrollar la aplicación en lenguaje C++, cumpliendo los formalismos de la programación estructurada o de la programación orientada a objetos e incluyendo la auto documentación necesaria para describir el propósito de los datos declarados y el objetivo de las funciones o métodos utilizados.

II.	Redactar un informe (mediante procesador de textos, papel tamaño carta, interlineado 1.5, márgenes 3.0 y letra Calibri 12) con el siguiente contenido:
1.	Portada (con nombre y RUT de los autores).
2.	Índice.
3.	Introducción.
4.	Marco teórico.
5.	Análisis de los resultados de la ejecución (se debe incluir el código fuente de cada función).
6.	Conclusiones.
7.	Referencias.
8.	Anexos (incluir aquí el enlace a la plataforma Online GDB en la cual se debe encontrar el código de la aplicación).
III.	Grabar un video en el cual se explique claramente los conceptos tratados, el diseño de los respectivos algoritmos y la implementación de las correspondientes funciones. Debe tener una   duración de 15 a 20 minutos e incorporar todos los recursos necesarios para la claridad de la presentación incluyendo rostro y voz del o los participantes.

EVALUACIÓN
i.	Realizar este trabajo en grupos de, a lo más, dos personas de una misma sección.
ii.	Subir a la plataforma CANVAS el informe y el video, hasta las 23:59 horas del 30/11/2022.
iii.	La nota del trabajo será el promedio simple entre las notas del informe, del video y de la prueba del código.
