## Nuestro Quiz

Tenéis que crear un quiz interactivo usando JavaScript.

Pedir el nombre del usuario y comprobar que funciona mediante `console.log`;

```js
const userName = prompt("What's your name?");
```

Crear una colección de preguntas y respuestas para el quiz:

```js
const questionOne = "What is white and falls from the sky when it snows?";

const answerOne = "snow";
```

Pedir las respuestas del usuario a cada pregunta:

```js
const userAnswerOne = prompt(questionOne);
```

Comprobar las respuestas del usuario, sumar un punto si es correcto:

```js
if (userAnswer === answer) {
  points = points + 1;
}
```

Muestra un mensaje amigable al usuario con su nombre y el total de puntos acumulados:

```js
alert("Well done," ...)
```

TIP:
Comenta los promps y los alerts añadiendo `//` en cada línea con un prompt y un alert para que no os salgan tantas veces.
