# Interacción Home Page

La interacción permite controlar la rotación de la vista 3D mediante el clic y el arrastre del mouse.

## Modo WEBGL

Función que permite renderizar gráficos 2D y 3D de alto rendimiento utilizando la **API WebGL del navegador**

Para habilitar el modo WebGL en p5.js se debe especificar como tercer parámetro en la función `createCanvas()`

El punto de origen se considera en el centro del lienzo, no en la esquina superior derecha.

## angleMode(DEGREES)

Configura el modo de ángulo para trabajar en grados, de esta manera se facilita las rotaciones.

## describe()

Describe la interacción para mejorar la accesibilidad y entender el comportamiento.

## orbitControl()

Permite el uso del mouse para rotar la escena, al hacer click y arrastrar.

La función `map()` ajusta el valor de `mouseX`
