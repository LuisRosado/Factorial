# Factorial
Como sacar el factorial de un numero de manera rudimentaria

El código que proporcionas calcula el factorial de un número ingresado por el usuario. A continuación, te explico cómo funciona:

numero = int(input('Ingrese un numero(Positivo): ')): Solicita al usuario que ingrese un número y lo almacena en la variable numero.

if numero >= 0:: Verifica si el número ingresado es no negativo. Si el número es negativo, se mostrará "Valor Invalido" y el programa finalizará. Si el número es no negativo, continuará con el cálculo del factorial.

Se inicializa la variable factorial con el valor de 1.

if numero == 0 or numero == 1:: Verifica si el número es 0 o 1. Si es así, el factorial es 1 y se asigna este valor a la variable factorial.

Si el número no es 0 o 1, entra en el bloque else, donde se utiliza un bucle for para calcular el factorial del número.

El bucle for i in range(1, numero+1): recorre los números desde 1 hasta el número ingresado por el usuario (incluyendo el número).

Dentro del bucle, se multiplica el valor actual de factorial por el valor de i, actualizando así el valor del factorial en cada iteración.

Finalmente, se muestra el resultado del factorial calculado.

En resumen, este código calcula y muestra el factorial del número ingresado por el usuario siempre que sea no negativo. Si el número es negativo, muestra "Valor Invalido". El factorial de un número entero positivo n es el producto de todos los enteros positivos desde 1 hasta n. Por ejemplo, el factorial de 5 (5!) es igual a 5 * 4 * 3 * 2 * 1 = 120.
