# Actividad 4 – Análisis técnico de cada ejemplo

## Ejemplo 1

1. Se define la clase `Punto`.
2. Se sobrecarga el operador `+`.
3. Utiliza dos operandos: `p1` y `p2`.
4. Devuelve un objeto de tipo `Punto`.
5. Crea un objeto nuevo con la suma de las coordenadas.
6. Sí, porque permite sumar puntos usando `p1 + p2` en lugar de llamar una función.
7. Ayuda a evitar hacer sumas manuales de `x` y `y` por separado.

## Ejemplo 2

1. Se define la clase `Libro`.
2. Se sobrecarga el operador `==`.
3. Utiliza dos operandos: `a` y `b`.
4. Devuelve un valor booleano, `true` o `false`.
5. No modifica el objeto actual, solo compara los títulos.
6. Sí, porque permite comparar libros directamente con `a == b`.
7. Ayuda a evitar comparar manualmente los atributos de cada libro.

## Ejemplo 3

1. Se define la clase `Persona`.
2. Se sobrecarga el operador `<<`.
3. Utiliza dos operandos: `cout` y el objeto `Persona`.
4. Devuelve un `ostream&`.
5. No modifica el objeto, solo permite imprimirlo.
6. Sí, porque permite imprimir una persona directamente con `cout << p`.
7. Ayuda a evitar escribir repetidamente el formato de impresión.

## Ejemplo 4

1. Se define la clase `Contador`.
2. Se sobrecarga el operador `++` en post-incremento.
3. Utiliza un operando: el objeto `c`.
4. Devuelve un objeto de tipo `Contador`.
5. Modifica el objeto actual aumentando su valor en 1.
6. Sí, porque permite usar `c++` de forma natural.
7. Ayuda a evitar modificar el contador manualmente con métodos extra.

## Ejemplo 5

1. Se define la clase `Cadena`.
2. Se sobrecarga el operador `=`.
3. Utiliza dos operandos: el objeto actual y el objeto `otra`.
4. Devuelve una referencia de tipo `Cadena&`.
5. Modifica el objeto actual copiando el texto de otra cadena.
6. Sí, porque permite asignar cadenas con `a = b`.
7. Ayuda a evitar errores de memoria al copiar texto dinámico.

## Ejemplo 6

1. Se define la clase `Temperatura`.
2. Se sobrecarga el operador de conversión a `double`.
3. Utiliza un operando: el objeto `t`.
4. Devuelve un valor de tipo `double`.
5. No modifica el objeto, solo devuelve su valor en Celsius.
6. Sí, porque permite convertir una temperatura directamente a número.
7. Ayuda a evitar tener que acceder manualmente al atributo privado `celsius`.
