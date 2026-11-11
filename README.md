# Resumen_Unidad_1_Diseño_de_Circuitos

# Unidad 1: Análisis de lógica combinacional con diseño clásico

## Descripción general

En esta unidad se estudian los fundamentos de la lógica digital y el diseño de circuitos combinacionales. Aprendemos cómo representar información mediante valores binarios, cómo funcionan las compuertas lógicas y cómo utilizar el álgebra de Boole para diseñar y simplificar circuitos.

A lo largo de las primeras cuatro semanas se trabaja desde conceptos básicos hasta la construcción de circuitos capaces de realizar operaciones aritméticas. También se utilizan herramientas de simulación para comprobar los diseños y verificar que funcionen correctamente.

## Contenidos por semana

<details>
<summary><strong>SEMANA 1: Introducción a la lógica combinacional</strong></summary>

Se estudian los conceptos básicos de los sistemas digitales y la forma en que una computadora representa la información mediante dos estados: 0 y 1.

### Temas principales

- Sistemas numéricos: binario, octal y hexadecimal.
- Conversión entre sistemas numéricos.
- Aritmética binaria.
- Representación de números negativos mediante complemento a dos.
- Códigos digitales: BCD, Gray y ASCII.
- Compuertas lógicas: AND, OR, NOT, NAND, NOR, XOR y XNOR.
- Tablas de verdad y funcionamiento de las compuertas.

### Actividad práctico-experimental (APE)

Reconocer el entorno de simulación Logisim-evolution y comprobar el funcionamiento de las compuertas lógicas mediante sus tablas de verdad.

</details>

<details>
<summary><strong>SEMANA 2: Álgebra de Boole y formas canónicas</strong></summary>

Se aprende a representar el funcionamiento de un circuito mediante expresiones booleanas. A partir de un problema, se identifican las entradas y salidas, se construye una tabla de verdad y se obtiene la función lógica correspondiente.

### Temas principales

- Postulados y teoremas del álgebra de Boole.
- Leyes de De Morgan.
- Simplificación algebraica.
- Suma de productos (SOP) y producto de sumas (POS).
- Minitérminos y maxitérminos.
- Formas canónicas y notación compacta.

### Actividad práctico-experimental (APE)

Traducir un requerimiento a una tabla de verdad, obtener sus formas canónicas y simplificar la expresión booleana. Después, construir y simular ambas versiones del circuito para comprobar que producen los mismos resultados y comparar la cantidad de compuertas utilizadas.

</details>

<details>
<summary><strong>SEMANA 3: Mapas de Karnaugh y optimización de circuitos</strong></summary>

Se estudia cómo simplificar funciones booleanas mediante mapas de Karnaugh. Este método permite organizar los valores de una tabla de verdad y encontrar expresiones más sencillas, reduciendo la cantidad de compuertas necesarias para construir un circuito.

### Temas principales

- Mapas de Karnaugh de tres y cuatro variables.
- Agrupación de unos y ceros.
- Condiciones indiferentes (Don't Care).
- Obtención de expresiones mínimas en SOP y POS.
- Universalidad de las compuertas NAND y NOR.
- Implementación de circuitos utilizando una sola familia de compuertas.

### Actividad práctico-experimental (APE)

Simplificar una función lógica de cuatro variables mediante mapas de Karnaugh, incluyendo condiciones indiferentes. Luego, simular el circuito original y el simplificado, implementar la versión mínima con compuertas NAND y comparar el ahorro de componentes.

</details>

<details>
<summary><strong>SEMANA 4: Circuitos aritméticos combinacionales</strong></summary>

Se estudia cómo construir circuitos digitales capaces de realizar operaciones matemáticas, principalmente sumas y restas binarias. También se analiza cómo se conectan varios bloques para trabajar con números de más bits y cómo se comparan sus valores.

### Temas principales

- Semisumador (Half Adder).
- Sumador completo (Full Adder).
- Sumadores paralelos de cuatro bits.
- Propagación del acarreo (Carry).
- Resta mediante complemento a dos.
- Comparadores de magnitud.
- Retardo de propagación de los circuitos.

### Actividad práctico-experimental (APE)

Construir y simular un semisumador y un sumador completo utilizando compuertas lógicas. Después, conectar varios sumadores para formar un sumador paralelo de cuatro bits, comprobar operaciones binarias y verificar el funcionamiento de la resta mediante complemento a dos.

</details>

## Herramientas de trabajo utilizadas en la Unidad

Durante estas semanas se utiliza principalmente:

- **Logisim-evolution:** para diseñar, construir y simular circuitos digitales.
- **Compuertas lógicas:** para representar las operaciones del circuito.
- **Hojas de datos de circuitos integrados:** para consultar las características de los componentes de la familia 74LS.
- **Tablas de verdad y mapas de Karnaugh:** para analizar y simplificar funciones lógicas.

## Declaración de uso de inteligencia artificial

Para la elaboración de este documento se utilizó ChatGPT como herramienta de apoyo para organizar la información, resumir los contenidos de la Unidad 1 y mejorar la redacción de los temas correspondientes a las semanas 1, 2, 3 y 4.

La información generada fue revisada y contrastada con el sílabo de la asignatura y las guías de actividades práctico-experimentales (APE). La inteligencia artificial se utilizó como apoyo y no como sustituto del estudio, análisis y comprensión de los contenidos por parte del estudiante.
