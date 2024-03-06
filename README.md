# experimento-de-la-doble-rendija
Este es un proyecto que contiene una serie de funciones y archivos relacionados con la simulación de experimentos cuánticos y clásicos, así como operaciones matriciales y vectoriales complejas en Python. A continuación, se describen los elementos clave de este proyecto y cómo utilizarlos.

### Historia:
Thomas Young, con el objetivo de apoyar la teoría de que la luz era una onda y rechazar la teoría de que la luz estaba formada por partículas.
hizo pasar un haz de luz por dos rendijas y vio que sobre una pantalla se producía un patrón de interferencias, una serie de franjas brillantes y oscuras alternadas.

Este resultado es inexplicable si la luz estuviera formada por partículas porque deberían observarse sólo dos franjas de luz frente a las rendijas, pero es fácilmente interpretable asumiendo que la luz es una onda y que sufre interferencias.

### Importancia:
El experimento de la doble rendija es de gran importancia en el campo de la física y la comprensión de la naturaleza fundamental de la materia y la luz por diversos motivos:
En primer lugar, demuestra la dualidad onda-partícula de las partículas subatómicas, como electrones y fotones, mostrando que las partículas pueden exhibir tanto comportamiento de partícula como de onda. Esto desafía la noción clásica de que las partículas son entidades sólidas y puntuales y nos lleva a una comprensión más profunda de la naturaleza cuántica de la realidad.
Este experimento es un pilar fundamental en la teoría cuántica, ayudando a establecer los conceptos fundamentales de la superposición, la interferencia y la probabilidad en el mundo subatómico. Además, proporciona evidencia experimental de que las partículas subatómicas no siguen las mismas reglas que los objetos macroscópicos y nos lleva a una nueva descripción de la realidad basada en las leyes cuánticas.
## Archivos y Funciones

### gitignore

Este archivo contiene patrones que se utilizan para excluir archivos y directorios específicos de un repositorio Git. Esto puede incluir archivos temporales, archivos generados por el sistema y otros archivos que no deben incluirse en el control de versiones.

### Clasico_a_Cuantico.py

Este archivo contiene tres funciones relacionadas con la simulación de sistemas cuánticos y clásicos:

1. simula_canicas(dinamica, inicialstate, clicks): Simula el experimento de las canicas. Toma una matriz dinamica que representa la dinámica del sistema, un vector inicialstate que representa el estado inicial y un número de clicks para simular la evolución del sistema. Devuelve el estado final.

2. probabilistico(dinamica, inicialstate, clicks): Simula un sistema de rendijas clásico probabilístico. Requiere que la matriz dinamica sea doblemente estocástica. Toma también un vector inicialstate y el número de clicks para simular. Devuelve el estado final.

3. cuantico(dinamica, inicialstate, clicks): Simula un sistema cuántico. Esta función trabaja con matrices que pueden contener valores complejos. Toma la matriz dinamica, el vector inicialstate y el número de clicks para simular. Devuelve el estado final.

4. grafica(estado): Muestra una gráfica de barras que representa las probabilidades en el estado dado.

### doble_rendija.py

Este archivo contiene una función main() que utiliza las funciones definidas en Clasico_a_Cuantico.py para simular un experimento de doble rendija cuántica. Define una matriz de dinámica, un estado inicial y el número de clics para la simulación. Luego, imprime el resultado.

### vec_and_mat.py

Este archivo contiene una serie de funciones para realizar operaciones vectoriales y matriciales complejas, incluyendo suma, resta, multiplicación por escalar, producto interno, norma, distancia, valores y vectores propios, y verificación de propiedades de matrices (unitariedad y hermiticidad).

## Como se usa

1. Tener instalado Python.

2. Clona el repositorio Git o descarga los archivos.

3. Utilizar las funciones definidas en Clasico_a_Cuantico.py y vec_and_mat.py importándolas como módulos.

4. Para ejecutar el experimento de doble rendija cuántica, ejecuta el archivo doble_rendija.py.

5. Tener las bibliotecas numpy y matplotlib instaladas en tu entorno de Python, ya que estas funciones las utilizan.

6. Personaliza los parámetros y matrices para simular diferentes experimentos cuánticos y clásicos.

## Fotos del experimento
   


## Explicación
### Experimento Clásico de la Doble Rendija:
En el experimento clásico de la doble rendija, se tiene una fuente de partículas (por ejemplo, partículas de luz o canicas) que se disparan hacia una barrera con dos rendijas. Detrás de la barrera, hay una pantalla receptora que registra las partículas que llegan.

- Una Rendija Abierta: En un primer experimento, solo se abre una de las dos rendijas, mientras que la otra permanece cerrada. Las partículas se disparan hacia la barrera y pasan a través de la rendija abierta. En la pantalla receptora, se forma un patrón de impacto que corresponde a la rendija abierta.

- Otra Rendija Abierta: En un segundo experimento, se cierra la rendija que estaba abierta previamente y se abre la otra rendija. Ahora, las partículas pasan a través de la segunda rendija y crean un patrón de impacto en la pantalla receptora que corresponde a la segunda rendija.

- Ambas Rendijas Abiertas: En el tercer experimento, ambas rendijas están abiertas al mismo tiempo. Aquí es donde ocurre algo interesante. En lugar de ver la suma de los patrones de impacto de los dos experimentos anteriores, se observa un patrón de interferencia, similar a las crestas y valles en una onda. Las partículas parecen comportarse como ondas y muestran una interferencia constructiva y destructiva en la pantalla receptora, lo que resulta en un patrón de franjas alternas brillantes y oscuras.
#AUTORAS
