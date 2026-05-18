# Banco de Retos
# Programming Battle 2026
---

## 1. ¿ES UN ANAGRAMA?

- Escribe una función que reciba dos palabras (String) y retorne verdadero o falso (Bool) según sean o no anagramas.
- Un Anagrama consiste en formar una palabra reordenando TODAS las letras de otra palabra inicial.
- NO hace falta comprobar que ambas palabras existan.
- Dos palabras exactamente iguales no son anagrama.

---

## 2. SUCESION FIBONACCI

- Escribe un programa que imprima los 50 primeros números de la sucesión de Fibonacci empezando en 0.
- La serie Fibonacci se compone por una sucesión de números en la que el siguiente siempre es la suma de los dos anteriores.  **`0, 1, 1, 2, 3, 5, 8, 13...`**

---

## 3. CONTADOR DE PALABRAS

- Crea un programa que cuente cuantas veces se repite cada palabra y que muestre el recuento final de todas ellas. 
- Los signos de puntuación no forman parte de la palabra. 
- Una palabra es la misma aunque aparezca en mayúsculas y minúsculas. 
- No se pueden utilizar funciones propias del lenguaje que   lo resuelvan automáticamente.

---

## 4. CODIGO MORSE

- Crea un programa que sea capaz de transformar texto natural a código morse y viceversa. 
- Debe detectar automáticamente de qué tipo se trata y realizar la conversión. 
- En morse se soporta raya **`—`**, punto **`.`**, un espacio `" "` entre letras   o símbolos y dos espacios entre palabras **`"  "`**. 
- El alfabeto morse soportado será el mostrado en   https://es.wikipedia.org/wiki/Código_morse./

---

## 5. EXPRESIONES EQUILIBRADAS

- Crea un programa que comprueba si los paréntesis, llaves y corchetes de una expresión están equilibrados.
- Equilibrado significa que estos delimitadores se abren y cieran en orden y de forma correcta.
- Paréntesis, llaves y corchetes son igual de prioritarios.
- No hay uno más importante que otro.
- Expresión balanceada: **`{ [ a * ( c + d ) ] - 5 }`**
- Expresión no balanceada: **`{ a * ( c + d ) ] - 5 }`**

---

## 6. ELIMINACION DE CARACTERES

- Crea una función que reciba dos cadenas como parámetro (str1, str2) e imprima otras dos cadenas como salida (out1, out2).
- **out1** contendrá todos los caracteres presentes en la str1 pero NO estén presentes en str2.
- **out2** contendrá todos los caracteres presentes en la str2 pero NO estén presentes en str1.


---

## 7. NUMERO DE DIAS

- Crea una función que calcule y retorne cuántos días hay entre dos cadenas de texto que representen fechas.
- Una cadena de texto que representa una fecha tiene el formato **`dd/MM/yyyy`**.
- La función recibirá dos String y retornará un Int.
- La diferencia en días será absoluta (no importa el orden de las fechas).
- Si una de las dos cadenas de texto no representa una fecha correcta se lanzará una excepción.

---

## 8. CARRERA DE OBSTACULOS 

- Crea una función que evalúe si un/a atleta ha superado correctamente una carrera de obstáculos.
- La función recibirá dos parámetros:
- Un array que sólo puede contener String con las palabras "run" o "jump"
- Un String que represente la pista y sólo puede contener "_" (suelo) o "|" (valla)
- La función imprimirá cómo ha finalizado la carrera:
- Si el/a atleta hace "run" en "_" (suelo) y "jump" en "|" (valla) será correcto y no variará el símbolo de esa parte de la pista.
- Si hace "jump" en "_" (suelo), se variará la pista por "x".
- Si hace "run" en "|" (valla), se variará la pista por "/".
- La función retornará un Boolean que indique si ha superado la carrera.
- Para ello tiene que realizar la opción correcta en cada tramo de la pista.

---

## 9. TRES Y RAYA 

- Crea una función que analice una matriz 3x3 compuesta por "X" y "O" y retorne lo siguiente:
- "X" si han ganado las "X"
- "O" si han ganado los "O"
- "Empate" si ha habido un empate
- "Nulo" si la proporción de "X", de "O", o de la matriz no es correcta.
O si han ganado los 2.
***`Nota:`*** ***`La matriz puede no estar totalmente cubierta.`***
- Se podría representar con un vacío "", por ejemplo.

---

## 10. PARANDO EL TIEMPO

- Crea una función que sume 2 números y retorne su resultado pasados unos segundos.
- Recibirá por parámetros los 2 números a sumar y los segundos que debe tardar en finalizar su ejecución.
- Si el lenguaje lo soporta, deberá retornar el resultado de forma asíncrona, es decir, sin detener la ejecución del programa principal.
- Se podría ejecutar varias veces al mismo tiempo.

---

## 11. CALCULADORA .TXT

- Lee el fichero "Challenge21.txt" incluido en el proyecto, calcula su resultado e imprímelo.
- El .txt se corresponde con las entradas de una calculadora.
- Cada línea tendrá un número o una operación representada por un símbolo (alternando ambos).
- Soporta números enteros y decimales.
- Soporta las operaciones suma "+", resta "-", multiplicación "*" y división "/".
- El resultado se muestra al finalizar la lectura de la última línea (si el .txt es correcto).
- Si el formato del .txt no es correcto, se indicará que no se han podido resolver las operaciones.

---

## 12. MAXIMO COMUN DIVISOR Y MINIMO COMUN MULTIPLO

- Crea dos funciones, una que calcule el máximo común divisor (MCD) y otra que calcule el mínimo común múltiplo (mcm) de dos números enteros.
- No se pueden utilizar operaciones del lenguaje que lo resuelvan directamente.

---

## 13.  PIEDRA PAPEL O TIJERAS

- Crea un programa que calcule quien gana más partidas al piedra, papel, tijera.
- El resultado puede ser: "Player 1", "Player 2", "Tie" (empate)
- La función recibe un listado que contiene pares, representando cada jugada.
- El par puede contener combinaciones de "R" (piedra), "P" (papel) o "S" (tijera).
- Ejemplo. Entrada: `[("R","S"), ("S","R"), ("P","S")]`. 
- Resultado: "Player 2".

---

## 14. MAQUINA EXPENDEDORA

- Simula el funcionamiento de una máquina expendedora creando una operación que reciba dinero (array de monedas) y un número que indique la selección del producto.
- El programa retornará el nombre del producto y un array con el dinero de vuelta (con el menor número de monedas).
- Si el dinero es insuficiente o el número de producto no existe, deberá indicarse con un mensaje y retornar todas las monedas.
- Si no hay dinero de vuelta, el array se retornará vacío.
- Para que resulte más simple, trabajaremos en céntimos con monedas de 5, 10, 50, 100 y 200.
- Debemos controlar que las monedas enviadas estén dentro de las soportadas.

---

## 15. LOS NUMEROS PERDIDOS

- Dado un array de enteros ordenado y sin repetidos, crea una función que calcule y retorne todos los que faltan entre el mayor y el menor.
- Lanza un error si el array de entrada no es correcto.

---

## 16. BATLLA POKEMON

- Crea un programa que calcule el daño de un ataque durante una batalla Pokémon.
- La fórmula será la siguiente: daño = 50 * (ataque / defensa) * efectividad
- Efectividad: x2 (súper efectivo), x1 (neutral), x0.5 (no es muy efectivo)
- Sólo hay 4 tipos de Pokémon: Agua, Fuego, Planta y Eléctrico (buscar su efectividad)
- El programa recibe los siguientes parámetros:
    - Tipo del Pokémon atacante.
    - Tipo del Pokémon defensor.
    - Ataque: Entre 1 y 100.
    - Defensa: Entre 1 y 100.

--

## 17. BINARIO A DECIMAL

- Crea un programa se encargue de transformar un número binario a decimal sin utilizar funciones propias del lenguaje quelo hagan directamente.

---

## 18. TRUCO O TRATO 

- Deberemos crear un programa al que le indiquemos si queremos realizar "Truco o Trato" y un listado (array) de personas con las siguientes propiedades:
    - Nombre de la niña o niño
    - Edad
    - Altura en centímetros
 
- Si las personas han pedido truco, el programa retornará sustos (aleatorios) siguiendo estos criterios:
    - Un susto por cada 2 letras del nombre por persona
    - Dos sustos por cada edad que sea un número par
    - Tres sustos por cada 100 cm de altura entre todas las personas
    - Sustos: 🎃 👻 💀 🕷 🕸 🦇
- Si las personas han pedido trato, el programa retornará dulces (aleatorios) siguiendo estos criterios:
    - Un dulce por cada letra de nombre
    - Un dulce por cada 3 años cumplidos hasta un máximo de 10 años por persona
    - Dos dulces por cada 50 cm de altura hasta un máximo de 150 cm por persona
    - Dulces: 🍰 🍬 🍡 🍭 🍪 🍫 🧁 🍩
    - En caso contrario retornará un error.

---

## 19. CONTENEDOR DE AGUA.

- Dado un array de números enteros positivos, donde cada uno representa unidades de bloques apilados, debemos calcular cuantas unidades de agua quedarán atrapadas entre ellos.
- Ejemplo: Dado el array [4, 0, 3, 6, 1, 3].
```
      ⏹
      ⏹
⏹💧💧⏹
⏹💧⏹⏹💧⏹
⏹💧⏹⏹💧⏹
⏹💧⏹⏹⏹⏹
```
- Representando bloque con ⏹︎ y agua con 💧, quedarán atrapadas 7 unidades de agua. Suponemos que existe un suelo impermeable en la parte inferior que retiene el agua.

---

## 20. ¿DONDE ESTA EL ROBOT?

- Calcula dónde estará un robot (sus coordenadas finales) que se encuentra en una cuadrícula representada por los ejes "x" e "y".
- El robot comienza en la coordenada (0, 0).
- Para idicarle que se mueva, le enviamos un array formado por enteros (positivos o negativos) que indican la secuencia de pasos a dar.
- Por ejemplo: [10, 5, -2] indica que primero se mueve 10 pasos, se detiene, luego 5, se detiene, y finalmente 2. El resultado en este caso sería (x: -5, y: 12)
- Si el número de pasos es negativo, se desplazaría en sentido contrario al que está mirando.
- Los primeros pasos los hace en el eje "y". Interpretamos que está mirando hacia la parte positiva del eje "y".
- El robot tiene un fallo en su programación: cada vez que finaliza una secuencia de pasos gira 90 grados en el sentido contrario a las agujas del reloj.

---

## 21. LA CASA ENCANTADA (BOSS FINAL)

- Te encuentras explorando una mansión abandonada llena de habitaciones. E
- En cada habitación tendrás que resolver un acertijo para poder avanzar a la siguiente.
- Tu misión es encontrar la habitación de los dulces.
- Se trata de implementar un juego interactivo de preguntas y respuestas por terminal. (Tienes total libertad para ser creativo con los textos)
- 🏰 Casa: La mansión se corresponde con una estructura cuadrada 4 x 4 que deberás modelar. Las habitaciones de puerta y dulces no tienen enigma. (16 habitaciones, siendo una de entrada y otra donde están los dulces)
- Esta podría ser una representación:
```
   🚪⬜️⬜️⬜️
   ⬜️👻⬜️⬜️
   ⬜️⬜️⬜️👻
   ⬜️⬜️🍭⬜️
```
- ❓ Enigmas: Cada habitación propone un enigma aleatorio que deberás responder con texto. Si no lo aciertas no podrás desplazarte.
- 🧭 Movimiento: Si resuelves el enigma se te preguntará a donde quieres desplazarte. (Ejemplo: norte/sur/este/oeste. Sólo deben proporcionarse las opciones posibles)
- 🍭 Salida: Sales de la casa si encuentras la habitación de los dulces.
- 👻 (Bonus) Fantasmas: Existe un 10% de que en una habitación aparezca un fantasma y tengas que responder dos preguntas para salir de ella.