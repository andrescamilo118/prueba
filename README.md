<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio 1 - Variables y Tipos de Datos</title>
</head>
<body>

<script>
    // Declaración de variables
    var numeroAntiguo = 5; // Esto usa "var", que era la forma tradicional de declarar variables.
    let numeroNuevo = 10; // Esto usa "let", que es la forma moderna y recomendada.
    const PI = 3.14159265359; // Esto es una constante. Su valor no puede cambiar.

    // Tipos de datos
    let nombre = "Juan"; // String o cadena de texto
    let edad = 30; // Number o número
    let estaCasado = false; // Boolean o booleano

    // Operadores aritméticos y de asignación
    let suma = numeroAntiguo + numeroNuevo; // Suma
    let resta = numeroNuevo - numeroAntiguo; // Resta
    let multiplicacion = numeroAntiguo * numeroNuevo; // Multiplicación
    let division = numeroNuevo / numeroAntiguo; // División

    numeroNuevo += 5; // Esto es lo mismo que decir numeroNuevo = numeroNuevo + 5;

    // Mostrar resultados en la consola
    console.log("El valor de PI es:", PI);
    console.log("Nombre:", nombre);
    console.log("Edad:", edad);
    console.log("¿Está casado?", estaCasado);
    console.log("Resultado de la suma:", suma);
    console.log("Resultado de la resta:", resta);
    console.log("Resultado de la multiplicación:", multiplicacion);
    console.log("Resultado de la división:", division);
    console.log("Nuevo valor de numeroNuevo:", numeroNuevo);
</script>

</body>
</html>
