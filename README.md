# Resumen de la Unidad 1 – Diseño de Circuitos

# ⚡ Unidad 1: Análisis de lógica combinacional con diseño clásico

## 📝 Descripción general

En esta unidad se estudiaron los fundamentos de la lógica digital y el diseño de circuitos combinacionales. Se aprendió cómo representar información mediante sistemas numéricos, interpretar los valores binarios y utilizar las compuertas lógicas para realizar diferentes operaciones.

Durante las cuatro semanas se trabajó con el álgebra de Boole, las formas canónicas y los mapas de Karnaugh para diseñar y simplificar funciones lógicas. Finalmente, se abordó la construcción de circuitos aritméticos capaces de realizar operaciones de suma y resta binaria.

Las actividades práctico-experimentales permitieron aplicar los conocimientos adquiridos mediante el diseño, construcción y simulación de circuitos en Logisim-evolution, verificando su funcionamiento y comparando diferentes formas de implementación.

---

## 📂 Contenidos por semana (Click en cada semana para ver el contenido)

<details>
<summary><strong>🔵 SEMANA 1: Introducción a la lógica combinacional</strong></summary>

###  Desarrollo de los contenidos

Durante esta semana se estudiaron los fundamentos de los sistemas digitales y la manera en que los dispositivos electrónicos representan y procesan información mediante dos estados lógicos: 0 y 1.

Se trabajó con los sistemas numéricos binario, octal, decimal y hexadecimal, aprendiendo a realizar conversiones entre sus diferentes bases y operaciones aritméticas binarias. También se estudió la representación de números negativos mediante complemento a dos y algunos códigos digitales utilizados para representar información, como BCD, Gray y ASCII.

Además, se analizaron las siete compuertas lógicas fundamentales: AND, OR, NOT, NAND, NOR, XOR y XNOR. Se comprendió su funcionamiento mediante expresiones booleanas y tablas de verdad, identificando las condiciones necesarias para obtener cada resultado.

###  Temas principales

- Fundamentos de la lógica combinacional.
- Sistemas numéricos: binario, octal, decimal y hexadecimal.
- Conversión entre sistemas numéricos.
- Operaciones aritméticas binarias.
- Representación de números negativos mediante complemento a dos.
- Códigos digitales: BCD, Gray y ASCII.
- Compuertas lógicas: AND, OR, NOT, NAND, NOR, XOR y XNOR.
- Tablas de verdad y niveles lógicos.

###  Actividad práctico-experimental (APE 01)

En esta semana se trabajó con el simulador Logisim-evolution para reconocer su entorno de desarrollo y aprender a utilizar sus principales herramientas, como pines de entrada, fuentes de nivel lógico, sondas y LED.

Se construyeron y comprobaron las siete compuertas lógicas, comparando sus tablas de verdad predichas con los resultados obtenidos durante la simulación. También se analizaron los circuitos integrados 74LS08 (AND) y 74LS02 (NOR), consultando sus hojas de datos para identificar la distribución de sus pines y verificar su funcionamiento.

Finalmente, se experimentó con una entrada sin conectar para observar cómo se representa un estado lógico indefinido. Con esta actividad se comprendió la importancia de verificar las conexiones y evitar entradas flotantes en los circuitos digitales.

###  Imagenes de la actividad
<img width="548" height="210" alt="Captura de pantalla 2026-11-10 200642" src="https://github.com/user-attachments/assets/26f64784-367f-41d2-8261-058af9fc4ccc" />
<img width="670" height="258" alt="Captura de pantalla 2026-11-10 201133" src="https://github.com/user-attachments/assets/4f3496d5-233b-4f59-ac31-48fa29ad1697" />
<img width="442" height="284" alt="Captura de pantalla 2026-11-10 201201" src="https://github.com/user-attachments/assets/9585c57a-020c-48a3-827f-6469b80fd105" />
<img width="593" height="134" alt="Captura de pantalla 2026-11-10 201220" src="https://github.com/user-attachments/assets/a6065a88-5e42-4c50-bc45-34dcd58ba745" />

</details>

<details>
<summary><strong>🟢 SEMANA 2: Álgebra de Boole y formas canónicas</strong></summary>

###  Desarrollo de los contenidos

Durante esta semana se estudió el álgebra de Boole como herramienta matemática para representar y simplificar el comportamiento de los circuitos digitales. Se analizaron sus postulados, propiedades y principales teoremas, aprendiendo a transformar expresiones booleanas sin modificar su funcionamiento lógico.

Se trabajó con las leyes de De Morgan, la propiedad distributiva, la absorción y otras reglas de simplificación. También se aprendió a representar funciones mediante las formas canónicas de suma de productos (SOP) y producto de sumas (POS), utilizando minitérminos y maxitérminos obtenidos a partir de una tabla de verdad.

Se comprendió que un requerimiento expresado en lenguaje natural puede convertirse en una función lógica mediante la identificación de sus entradas, salidas y condiciones de funcionamiento. A partir de esta representación es posible diseñar un circuito y simplificarlo para reducir su complejidad.

###  Temas principales

- Postulados y teoremas del álgebra de Boole.
- Leyes de De Morgan.
- Propiedades de identidad, complemento, absorción y distributividad.
- Simplificación algebraica de funciones booleanas.
- Tablas de verdad y funciones lógicas.
- Minitérminos y maxitérminos.
- Formas canónicas: suma de productos (SOP) y producto de sumas (POS).
- Notación compacta mediante Σm y ΠM.

###  Actividad práctico-experimental (APE 02)

En esta semana se trabajó con el diseño de un circuito comparador de magnitud, cuyo objetivo era determinar si un número binario de dos bits era mayor que otro número representado con un bit.

Primero se identificaron las variables de entrada y la salida, y se construyó la tabla de verdad correspondiente al requerimiento. A partir de ella se obtuvieron las formas canónicas SOP y POS, utilizando minitérminos y maxitérminos. Posteriormente, se realizó la simplificación algebraica de la función, registrando los postulados y teoremas aplicados en cada paso.

Después, se construyeron en Logisim-evolution dos versiones del circuito: una utilizando la expresión canónica y otra con la expresión simplificada. Se comprobaron las ocho combinaciones posibles de entrada y se verificó que ambas versiones produjeran los mismos resultados.

Finalmente, se comparó la cantidad de compuertas, circuitos integrados y niveles lógicos necesarios para cada implementación. Con esta actividad se comprendió cómo pasar de un problema a una función booleana y cómo la simplificación permite construir circuitos menos complejos y con menor cantidad de componentes.

</details>

<details>
<summary><strong>🟡 SEMANA 3: Mapas de Karnaugh y optimización de circuitos</strong></summary>

###  Desarrollo de los contenidos

Durante esta semana se estudiaron los mapas de Karnaugh como un método gráfico para simplificar funciones booleanas. Se aprendió a organizar los valores de una tabla de verdad en mapas de tres y cuatro variables, utilizando agrupaciones de unos o ceros para obtener expresiones lógicas más sencillas.

Se analizaron las reglas de agrupación, considerando grupos de 1, 2, 4, 8 o más celdas, y se comprendió cómo identificar las variables que permanecen constantes dentro de cada agrupación para obtener los términos de la expresión simplificada.

También se estudiaron las condiciones indiferentes (Don't Care), representadas mediante X, que permiten aprovechar combinaciones de entrada que no se presentan en el funcionamiento normal del sistema. Estas condiciones pueden utilizarse como unos o ceros según convenga para obtener una expresión más sencilla.

Finalmente, se abordó la universalidad de las compuertas NAND y NOR, comprendiendo que cualquiera de ellas puede utilizarse para construir las demás funciones lógicas. Esto permite implementar circuitos utilizando una sola familia de compuertas.

###  Temas principales

- Mapas de Karnaugh de tres y cuatro variables.
- Organización de valores según el código Gray.
- Agrupación de unos y ceros.
- Obtención de expresiones mínimas SOP y POS.
- Condiciones indiferentes (Don't Care).
- Identificación de implicantes y agrupaciones esenciales.
- Universalidad de las compuertas NAND y NOR.
- Implementación de circuitos con una sola familia de compuertas.
- Optimización de componentes y niveles lógicos.

###  Actividad práctico-experimental (APE 03)

En esta semana se trabajó con el diseño de un circuito para identificar números primos del 0 al 9 representados mediante código BCD de cuatro bits. El objetivo era encender un LED cuando el número ingresado correspondiera a un número primo: 2, 3, 5 o 7.

Primero se elaboró la tabla de verdad y se identificaron las combinaciones válidas y las condiciones indiferentes correspondientes a los valores BCD que no representan dígitos decimales. Después, se construyeron mapas de Karnaugh para obtener expresiones mínimas con y sin utilizar las condiciones indiferentes.

Posteriormente, se implementaron y simularon diferentes versiones del circuito en Logisim-evolution: la expresión canónica, la expresión mínima mediante compuertas AND-OR y una implementación utilizando únicamente compuertas NAND del circuito integrado 74LS00.

También se incorporó una compuerta XOR para comparar las salidas de las versiones canónica y simplificada, identificando las combinaciones en las que sus resultados eran diferentes debido al uso de condiciones indiferentes.

Con esta actividad se comprendió cómo los mapas de Karnaugh permiten reducir la complejidad de las funciones lógicas y cómo las condiciones indiferentes pueden aprovecharse para disminuir la cantidad de componentes necesarios. Además, se comprobó que una función simplificada puede implementarse utilizando exclusivamente compuertas NAND.

</details>

<details>
<summary><strong>🔴 SEMANA 4: Circuitos aritméticos combinacionales</strong></summary>

###  Desarrollo de los contenidos

Durante esta semana se estudiaron los circuitos aritméticos combinacionales, encargados de realizar operaciones matemáticas mediante señales binarias. Se analizaron los semisumadores y sumadores completos, comprendiendo cómo se generan los bits de suma y los acarreos durante una operación.

Se aprendió a construir un semisumador a partir de las compuertas XOR y AND, y un sumador completo mediante la combinación de dos semisumadores y una compuerta OR. También se estudió cómo conectar varios sumadores completos para formar un sumador paralelo de cuatro bits, en el que el acarreo de una etapa se transmite a la siguiente.

Además, se abordó la resta mediante complemento a dos, utilizando compuertas XOR y una señal de control para permitir que un mismo circuito realice sumas o restas. Se estudió la diferencia entre acarreo (Carry) y desbordamiento (Overflow), así como la detección de este último en operaciones con números representados mediante complemento a dos.

Finalmente, se analizó el retardo de propagación, comprendiendo que el tiempo necesario para obtener un resultado depende de los niveles de compuertas y del recorrido del acarreo dentro del circuito.

###  Temas principales

- Semisumador (Half Adder).
- Sumador completo (Full Adder).
- Tablas de verdad y ecuaciones de suma y acarreo.
- Sumadores paralelos de cuatro bits.
- Propagación del acarreo (Carry).
- Circuito integrado 7483.
- Resta mediante complemento a dos.
- Circuitos sumadores/restadores.
- Diferencia entre Carry y Overflow.
- Detección de desbordamiento.
- Retardo de propagación.

###  Actividad práctico-experimental (APE 04)

En esta semana se trabajó con la implementación de circuitos sumadores en Logisim-evolution. Primero se construyó un semisumador utilizando una compuerta XOR para obtener la suma y una AND para generar el acarreo. Después, se diseñó un sumador completo mediante dos semisumadores y una compuerta OR, comprobando sus ocho combinaciones posibles de entrada.

Posteriormente, se conectaron cuatro sumadores completos para formar un sumador paralelo de cuatro bits. Su funcionamiento se verificó mediante diferentes operaciones binarias y se compararon sus resultados con los obtenidos utilizando el circuito integrado 7483.

También se adaptó el circuito para realizar operaciones de suma y resta mediante complemento a dos. Para ello se utilizaron compuertas XOR controladas por una señal M, que permite mantener o invertir los bits del segundo operando, y se conectó esta misma señal al acarreo de entrada inicial para completar la operación de resta.

Finalmente, se analizó la detección del desbordamiento mediante la expresión V = C3 ⊕ C4 y se estimó el retardo de propagación producido por la conexión en cadena de los sumadores.

Con esta actividad se comprendió cómo se construyen los circuitos aritméticos combinacionales, cómo se transmite el acarreo entre etapas y cómo un mismo circuito puede realizar sumas y restas mediante señales de control.

</details>

---

##  Herramientas de trabajo utilizadas

Durante estas semanas se utilizaron principalmente las siguientes herramientas y recursos:

- **Logisim-evolution:** para diseñar, construir y simular circuitos digitales, comprobar tablas de verdad y verificar el funcionamiento de las implementaciones.
- **Compuertas lógicas:** para construir circuitos combinacionales y representar las operaciones booleanas.
- **Circuitos integrados de la familia 74LS:** para estudiar sus funciones, distribución de pines y posibilidades de implementación.
- **Hojas de datos (Datasheets):** para consultar las características y conexiones de los circuitos integrados utilizados.
- **Tablas de verdad:** para representar y comprobar el comportamiento de las funciones lógicas.
- **Mapas de Karnaugh:** para simplificar expresiones booleanas y optimizar los circuitos.

## 🤖 Declaración de uso de inteligencia artificial

Para la elaboración de este documento se utilizó ChatGPT como herramienta de apoyo para organizar la información, un mejor manejo de GitHub y mejorar la REDACCIÓN de los temas correspondientes a las semanas 1, 2, 3 y 4.

La información generada fue revisada y contrastada con los temas tratados en la asignatura y las guías de actividades práctico-experimentales (APE). La inteligencia artificial se utilizó como apoyo y no como sustituto del estudio, análisis y comprensión de los contenidos por parte del estudiante.
