# **📄 #1: Arrays y Métodos**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. He logrado crear arrays simples y agregar elementos, pero no comprendo bien cómo funcionan los métodos como push, pop, shift, unshift, y cuándo debo usar cada uno. También me confunde la diferencia entre métodos que modifican el array original y los que crean uno nuevo.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const fruits = ["manzana", "banana"];

fruits.push("naranja");
console.log(fruits);

const last = fruits.pop();
console.log(last);
console.log(fruits);
```

En donde:

1. Se crea un array y se manipula con diferentes métodos.
2. Algunos métodos modifican el array original.
3. Se visualizan los cambios en consola.

---

## **Pregunta #1**

¿Cómo funcionan los métodos básicos de arrays en JavaScript y cuándo debo usar cada uno?

---

---

# **📄 #2: Funciones Flecha vs Funciones Tradicionales**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está trabajando con JavaScript Vanilla. He visto que existen dos formas de declarar funciones y las uso indistintamente, pero no entiendo realmente cuál es la diferencia entre ellas. Me confunde especialmente el comportamiento del "this" en cada caso y cuándo debería elegir una sobre la otra en situaciones específicas.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  normalFunction: function() {
    return this.name;
  },
  arrowFunction: () => {
    return this.name;
  }
};

console.log(user.normalFunction());
console.log(user.arrowFunction());
```

En donde:

1. Se crea un objeto con dos métodos diferentes.
2. Ambos intentan acceder a la propiedad `name`.
3. Los resultados en consola son distintos.

---

## **Pregunta #2**

¿Cuál es la diferencia entre funciones flecha y funciones tradicionales, y cuándo debo usar cada una?

---

---

# **📄 #3: Scope y Hoisting**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. A menudo encuentro errores en mi código relacionados con variables que no puedo acceder o que parecen existir antes de ser declaradas. He escuchado los términos "scope" y "hoisting" pero no logro comprender cómo afectan realmente la ejecución de mi código y por qué a veces puedo acceder a variables y otras veces no.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
console.log(a);
var a = 5;
console.log(a);

console.log(b);
let b = 10;

function outer() {
  let x = 1;
  function inner() {
    console.log(x);
  }
  inner();
}
```

En donde:

1. Se intenta acceder a variables en diferentes momentos.
2. El comportamiento varía según el tipo de declaración.
3. El alcance determina la visibilidad de las variables.

---

## **Pregunta #3**

¿Qué son el scope y el hoisting en JavaScript y cómo afectan el comportamiento de mis variables?

---

---

# **📄 #4: Callbacks y Asincronía Básica**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He notado que algunas operaciones en mi código no se ejecutan en el orden que espero, especialmente cuando uso setTimeout o cuando intento cargar datos. He escuchado sobre callbacks pero no entiendo qué son exactamente, cómo funcionan, ni por qué JavaScript necesita este mecanismo para manejar operaciones que toman tiempo.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
console.log("Inicio");

setTimeout(() => {
  console.log("Operación completada");
}, 2000);

console.log("Fin");

function processData(data, callback) {
  console.log("Procesando:", data);
  callback();
}
```

En donde:

1. Se ejecutan operaciones en secuencia.
2. Una operación se retrasa mientras otras continúan.
3. Se pasa una función como argumento a otra función.

---

## **Pregunta #4**

¿Qué son los callbacks en JavaScript y cómo me ayudan a manejar operaciones asíncronas?

---

---

# **📄 #5: Manipulación del DOM**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Puedo crear páginas HTML básicas, pero no sé cómo hacer que JavaScript interactúe con ellas de manera dinámica. He intentado cambiar contenido, agregar elementos y modificar estilos, pero no tengo claro cuáles son los métodos correctos para hacerlo ni cuál es la forma más eficiente de seleccionar y modificar elementos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const title = document.getElementById("title");
title.textContent = "Nuevo título";
title.style.color = "blue";

const items = document.querySelectorAll(".item");
items.forEach(item => {
  item.classList.add("active");
});
```

En donde:

1. Se seleccionan elementos del documento HTML.
2. Se modifican propiedades y estilos.
3. Se aplican cambios dinámicos a múltiples elementos.

---

## **Pregunta #5**

¿Cómo puedo seleccionar y manipular elementos del DOM usando JavaScript de forma efectiva?

---

---

# **📄 #6: Event Listeners y Eventos**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He logrado crear botones y elementos interactivos en HTML, pero no comprendo bien cómo hacer que respondan a las acciones del usuario. He visto código con addEventListener y onclick, pero no entiendo la diferencia entre ellos, ni cómo manejar diferentes tipos de eventos como clicks, teclas presionadas o movimientos del mouse de manera profesional.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const button = document.getElementById("myButton");

button.addEventListener("click", () => {
  console.log("Botón clickeado");
});

document.addEventListener("keydown", (e) => {
  console.log("Tecla presionada:", e.key);
});
```

En donde:

1. Se seleccionan elementos del DOM.
2. Se agregan escuchadores para diferentes eventos.
3. Se ejecutan acciones cuando ocurren esos eventos.

---

## **Pregunta #6**

¿Cómo funcionan los event listeners en JavaScript y cuál es la mejor forma de manejar eventos del usuario?

---

---

# **📄 #7: Objetos y Propiedades**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. He trabajado con variables simples y arrays, pero ahora necesito organizar información más compleja y he escuchado sobre los objetos. No entiendo bien cómo crearlos, cómo acceder a sus propiedades, cómo agregar o modificar información dentro de ellos, ni cuándo debería usar objetos en lugar de otras estructuras de datos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  age: 21,
  country: "Colombia",
  greet: function() {
    console.log(`Hola, soy ${this.name}`);
  }
};

console.log(user.name);
user.greet();
user.email = "vale@example.com";
```

En donde:

1. Se crea un objeto con propiedades y métodos.
2. Se accede a las propiedades de diferentes formas.
3. Se agregan nuevas propiedades dinámicamente.

---

## **Pregunta #7**

¿Cómo funcionan los objetos en JavaScript y cómo puedo trabajar con sus propiedades y métodos?

---

---

# **📄 #8: Promises y Async/Await**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He usado callbacks para operaciones asíncronas, pero mi código se está volviendo muy anidado y difícil de leer. He escuchado sobre Promises y async/await como soluciones más modernas, pero no comprendo cómo funcionan, cómo convertir mi código actual a estas nuevas formas, ni cuáles son las ventajas reales de usarlas en lugar de callbacks simples.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Con Promises
fetch("https://api.example.com/data")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));

// Con async/await
async function getData() {
  const response = await fetch("https://api.example.com/data");
  const data = await response.json();
  console.log(data);
}
```

En donde:

1. Se realizan operaciones asíncronas de dos formas diferentes.
2. El código con async/await es más legible.
3. Ambos métodos manejan operaciones que toman tiempo.

---

## **Pregunta #8**

¿Qué son las Promises y async/await, y cómo simplifican el manejo de código asíncrono en JavaScript?

---

---

# **📄 #9: Destructuring y Spread Operator**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. He visto código que usa una sintaxis extraña con llaves y tres puntos para trabajar con arrays y objetos, pero no entiendo qué significan ni para qué sirven. Actualmente extraigo valores de objetos y arrays de forma tradicional, pero me han dicho que hay formas más modernas y eficientes de hacerlo que debería aprender.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Destructuring
const user = { name: "Vale", age: 21, country: "Colombia" };
const { name, age } = user;
console.log(name, age);

// Spread operator
const numbers = [1, 2, 3];
const moreNumbers = [...numbers, 4, 5];
console.log(moreNumbers);

const updatedUser = { ...user, email: "vale@example.com" };
```

En donde:

1. Se extraen valores de objetos de forma concisa.
2. Se copian y expanden arrays y objetos.
3. El código es más limpio y expresivo.

---

## **Pregunta #9**

¿Qué son la destructuración y el operador spread en JavaScript y cómo me ayudan a escribir código más limpio?

---

---

# **📄 #10: Métodos de Array Avanzados (map, filter, reduce)**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. Actualmente uso bucles for para recorrer y transformar arrays, pero he visto que existen métodos como map, filter y reduce que parecen hacer lo mismo de forma más concisa. No entiendo bien cómo funcionan estos métodos, cuándo debo usar cada uno, ni por qué son considerados mejores que los bucles tradicionales que ya conozco.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const numbers = [1, 2, 3, 4, 5];

// map: transforma cada elemento
const doubled = numbers.map(num => num * 2);

// filter: selecciona elementos que cumplen condición
const evens = numbers.filter(num => num % 2 === 0);

// reduce: reduce array a un solo valor
const sum = numbers.reduce((acc, num) => acc + num, 0);

console.log(doubled, evens, sum);
```

En donde:

1. Se procesan arrays de diferentes formas.
2. Cada método tiene un propósito específico.
3. El código es más declarativo y legible.

---

## **Pregunta #10**

¿Cómo funcionan map, filter y reduce en JavaScript y cuándo debo usar cada uno en lugar de bucles tradicionales?

---

---

# **📄 #11: Closures y Ámbito Léxico**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. He notado que las funciones dentro de otras funciones pueden acceder a variables de la función externa incluso después de que esta ha terminado de ejecutarse, pero no comprendo por qué sucede esto. He escuchado el término "closure" pero me parece un concepto abstracto y no veo aplicaciones prácticas claras de por qué necesitaría usar esto en mis proyectos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
function createCounter() {
  let count = 0;
  
  return function() {
    count++;
    return count;
  };
}

const counter1 = createCounter();
const counter2 = createCounter();

console.log(counter1()); // 1
console.log(counter1()); // 2
console.log(counter2()); // 1
```

En donde:

1. Una función interna accede a variables de la función externa.
2. La variable persiste incluso después de que la función externa termina.
3. Cada instancia mantiene su propio estado privado.

---

## **Pregunta #11**

¿Qué son los closures en JavaScript y para qué casos prácticos son útiles en la programación?

---

---

# **📄 #12: Clases y Programación Orientada a Objetos**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He trabajado con objetos literales y funciones, pero ahora necesito crear múltiples objetos con la misma estructura y comportamiento. He escuchado sobre las clases en JavaScript pero no entiendo bien cómo funcionan, cuál es la diferencia con los objetos normales, ni conceptos como constructor, métodos, herencia e instancias que veo mencionados frecuentemente.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
  
  greet() {
    console.log(`Hola, soy ${this.name}`);
  }
}

class Student extends Person {
  constructor(name, age, grade) {
    super(name, age);
    this.grade = grade;
  }
}

const student1 = new Student("Vale", 21, "A");
student1.greet();
```

En donde:

1. Se define una plantilla con constructor y métodos.
2. Se crean múltiples instancias con sus propios valores.
3. Se implementa herencia para extender funcionalidad.

---

## **Pregunta #12**

¿Cómo funcionan las clases en JavaScript y cómo puedo usar programación orientada a objetos en mis proyectos?

---

---

# **📄 #13: Template Literals y String Methods**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Actualmente concateno strings usando el operador + pero he visto código que usa backticks con una sintaxis diferente. También necesito manipular texto frecuentemente, como convertir a mayúsculas, buscar palabras, dividir frases o reemplazar contenido, pero no conozco bien los métodos disponibles ni cuál es la forma moderna y eficiente de trabajar con strings en JavaScript.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const name = "Vale";
const age = 21;

// Template literals
const message = `Hola, soy ${name} y tengo ${age} años`;

// String methods
const text = "JavaScript es genial";
console.log(text.toUpperCase());
console.log(text.includes("Script"));
console.log(text.split(" "));
console.log(text.replace("genial", "increíble"));
```

En donde:

1. Se utilizan template literals para interpolación.
2. Se aplican diversos métodos de manipulación de strings.
3. El código es más legible y expresivo.

---

## **Pregunta #13**

¿Qué son los template literals y cuáles son los métodos más útiles para manipular strings en JavaScript?

---

---

# **📄 #14: Try-Catch y Manejo de Errores**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. A menudo mi código se detiene completamente cuando algo sale mal, y solo veo errores rojos en la consola sin saber cómo prevenirlos o manejarlos. He escuchado sobre try-catch pero no entiendo exactamente qué errores debo capturar, cómo hacerlo sin afectar el rendimiento, ni cómo crear mensajes de error útiles para el usuario cuando algo falla en mi aplicación.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
try {
  const data = JSON.parse('{"name": "Vale"}');
  console.log(data.name);
  
  const invalid = JSON.parse("invalid json");
} catch (error) {
  console.error("Error al parsear:", error.message);
} finally {
  console.log("Operación completada");
}

console.log("El programa continúa");
```

En donde:

1. Se ejecuta código que puede fallar dentro de try.
2. Si hay un error, se captura en catch.
3. El programa no se detiene y continúa ejecutándose.

---

## **Pregunta #14**

¿Cómo funciona try-catch en JavaScript y cuál es la forma correcta de manejar errores en mis aplicaciones?

---

---

# **📄 #15: Módulos ES6 (Import/Export)**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Actualmente todo mi código está en un solo archivo y se está volviendo muy largo y difícil de mantener. He escuchado que puedo dividir mi código en múltiples archivos usando módulos, pero no entiendo cómo funciona import y export, cuál es la diferencia entre export default y export named, ni cómo configurar mi proyecto para que los módulos funcionen correctamente.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// utils.js
export const sum = (a, b) => a + b;
export const multiply = (a, b) => a * b;
export default function greet(name) {
  return `Hola ${name}`;
}

// main.js
import greet, { sum, multiply } from './utils.js';

console.log(greet("Vale"));
console.log(sum(5, 3));
console.log(multiply(4, 2));
```

En donde:

1. Se exportan funciones desde un archivo.
2. Se importan en otro archivo para usarlas.
3. El código se organiza en módulos reutilizables.

---

## **Pregunta #15**

¿Cómo funcionan los módulos ES6 con import y export, y cómo puedo organizar mi código en múltiples archivos?

---

---

# **📄 #16: This y Context Binding**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He notado que "this" se comporta de manera extraña y diferente dependiendo de dónde lo use en mi código. A veces apunta al objeto que espero, otras veces es undefined, y en algunos casos apunta a window. También he visto métodos como bind, call y apply pero no entiendo cuándo ni por qué debería usarlos para controlar el valor de "this".

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  greet: function() {
    console.log(`Hola, soy ${this.name}`);
  }
};

user.greet(); // "Hola, soy Vale"

const greetFunc = user.greet;
greetFunc(); // Error o undefined

const boundGreet = user.greet.bind(user);
boundGreet(); // "Hola, soy Vale"
```

En donde:

1. El valor de "this" depende del contexto de ejecución.
2. Al extraer un método, "this" se pierde.
3. Se puede controlar "this" usando bind.

---

## **Pregunta #16**

¿Cómo funciona "this" en JavaScript y cómo puedo controlar su valor usando bind, call y apply?

---

---

# **📄 #17: LocalStorage y SessionStorage**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. He creado aplicaciones que funcionan bien, pero cuando recargo la página todos los datos se pierden. Necesito una forma de guardar información del usuario en el navegador para que persista entre sesiones. He escuchado sobre localStorage y sessionStorage pero no entiendo la diferencia entre ellos, cómo guardar y recuperar datos, ni qué tipo de información puedo almacenar.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Guardar datos
localStorage.setItem("username", "Vale");
localStorage.setItem("user", JSON.stringify({ name: "Vale", age: 21 }));

// Recuperar datos
const username = localStorage.getItem("username");
const user = JSON.parse(localStorage.getItem("user"));

console.log(username, user);

// Eliminar datos
localStorage.removeItem("username");
localStorage.clear(); // Elimina todo
```

En donde:

1. Se almacenan datos en el navegador.
2. Los datos persisten incluso después de cerrar el navegador.
3. Se pueden recuperar y eliminar cuando sea necesario.

---

## **Pregunta #17**

¿Cómo puedo usar localStorage y sessionStorage para guardar datos en el navegador del usuario?

---

---

# **📄 #18: Fetch API y Peticiones HTTP**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. Necesito traer datos de APIs externas para mis proyectos pero no sé cómo hacerlo. He escuchado sobre fetch pero no entiendo cómo funciona, cómo manejar las respuestas, cómo enviar datos al servidor, ni cómo trabajar con diferentes métodos HTTP como GET, POST, PUT o DELETE. También me confunde cómo manejar errores en las peticiones.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// GET request
fetch("https://api.example.com/users")
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error("Error:", error));

// POST request
fetch("https://api.example.com/users", {
  method: "POST",
  headers: { "Content-Type": "application/json" },
  body: JSON.stringify({ name: "Vale", age: 21 })
})
  .then(response => response.json())
  .then(data => console.log(data));
```

En donde:

1. Se realizan peticiones a un servidor externo.
2. Se procesan las respuestas recibidas.
3. Se manejan errores que puedan ocurrir.

---

## **Pregunta #18**

¿Cómo funciona la Fetch API para hacer peticiones HTTP y consumir APIs en JavaScript?

---

---

# **📄 #19: JSON y Serialización de Datos**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Cuando trabajo con APIs o almacenamiento local, veo que los datos están en un formato llamado JSON que parece similar a los objetos de JavaScript pero en texto. No entiendo bien qué es JSON, cómo convertir objetos JavaScript a JSON y viceversa, ni por qué necesito hacer estas conversiones cuando envío o recibo datos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
const user = {
  name: "Vale",
  age: 21,
  active: true
};

// Objeto a JSON (string)
const jsonString = JSON.stringify(user);
console.log(jsonString); // '{"name":"Vale","age":21,"active":true}'
console.log(typeof jsonString); // "string"

// JSON a objeto
const parsedUser = JSON.parse(jsonString);
console.log(parsedUser); // { name: "Vale", age: 21, active: true }
console.log(typeof parsedUser); // "object"
```

En donde:

1. Se convierte un objeto JavaScript a formato JSON.
2. El JSON es una cadena de texto estructurada.
3. Se puede convertir de vuelta a objeto cuando sea necesario.

---

## **Pregunta #19**

¿Qué es JSON y cómo puedo convertir entre objetos JavaScript y formato JSON para trabajar con APIs?

---

---

# **📄 #20: Regular Expressions Básicas**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. Necesito validar formularios, buscar patrones en texto y extraer información específica de strings, pero los métodos básicos de string no son suficientes. He escuchado sobre expresiones regulares pero parecen muy complejas con símbolos extraños. No entiendo la sintaxis básica, cómo crear patrones simples, ni cómo usar regex para validar emails, teléfonos u otros formatos comunes.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Validar email
const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
console.log(emailPattern.test("vale@example.com")); // true
console.log(emailPattern.test("invalid-email")); // false

// Buscar números en un texto
const text = "Tengo 21 años y vivo en el 2024";
const numbers = text.match(/\d+/g);
console.log(numbers); // ["21", "2024"]

// Reemplazar usando regex
const phone = "123-456-7890";
const formatted = phone.replace(/-/g, "");
console.log(formatted); // "1234567890"
```

En donde:

1. Se definen patrones para validar formatos específicos.
2. Se buscan y extraen datos que coinciden con el patrón.
3. Se realizan transformaciones basadas en patrones.

---

## **Pregunta #20**

¿Cómo funcionan las expresiones regulares básicas en JavaScript y cómo puedo usarlas para validar datos?

---

---

# **📄 #21: SetTimeout y SetInterval**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. Necesito ejecutar código después de cierto tiempo o de manera repetitiva, como mostrar notificaciones, crear animaciones simples o actualizar información periódicamente. He visto setTimeout y setInterval pero no entiendo bien la diferencia entre ellos, cómo detenerlos una vez iniciados, ni cómo evitar problemas comunes como crear múltiples intervalos accidentalmente.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// setTimeout: ejecuta una vez después del tiempo especificado
setTimeout(() => {
  console.log("Han pasado 2 segundos");
}, 2000);

// setInterval: ejecuta repetidamente cada cierto tiempo
let count = 0;
const intervalId = setInterval(() => {
  count++;
  console.log("Contador:", count);
  
  if (count === 5) {
    clearInterval(intervalId);
    console.log("Intervalo detenido");
  }
}, 1000);
```

En donde:

1. setTimeout ejecuta código una sola vez después de un retraso.
2. setInterval ejecuta código repetidamente en intervalos.
3. Se pueden detener usando clearTimeout y clearInterval.

---

## **Pregunta #21**

¿Cómo funcionan setTimeout y setInterval en JavaScript y cuándo debo usar cada uno para ejecutar código con retrasos?

---

---

# **📄 #22: Operadores Ternarios y Short-Circuit**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. Actualmente uso muchas estructuras if-else en mi código y se está volviendo muy extenso y difícil de leer. He visto código con símbolos como ?, :, && y || usados de formas que no entiendo completamente. Sé que son operadores pero no comprendo cómo funcionan como alternativa a las estructuras condicionales tradicionales ni cuándo es apropiado usarlos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Operador ternario
const age = 18;
const status = age >= 18 ? "Adulto" : "Menor";
console.log(status); // "Adulto"

// Short-circuit con &&
const user = { name: "Vale" };
user && console.log(user.name); // Imprime "Vale"

// Short-circuit con ||
const defaultName = null || "Usuario";
console.log(defaultName); // "Usuario"

// Combinado
const greeting = user ? `Hola ${user.name}` : "Hola invitado";
```

En donde:

1. El operador ternario reemplaza if-else simples.
2. && y || evalúan expresiones de forma eficiente.
3. El código se vuelve más conciso y expresivo.

---

## **Pregunta #22**

¿Cómo funcionan los operadores ternarios y la evaluación de cortocircuito para escribir condicionales más concisas?

---

---

# **📄 #23: Event Bubbling y Event Delegation**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Cuando agrego event listeners a múltiples elementos similares, como items de una lista, mi código se vuelve repetitivo y pesado. He notado que a veces los eventos se disparan en elementos que no esperaba. He escuchado sobre event bubbling y event delegation pero no entiendo cómo funcionan estos mecanismos ni cómo puedo aprovecharlos para escribir código más eficiente.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Sin delegation: muchos listeners
const items = document.querySelectorAll(".item");
items.forEach(item => {
  item.addEventListener("click", () => {
    console.log("Item clickeado");
  });
});

// Con delegation: un solo listener
const list = document.getElementById("list");
list.addEventListener("click", (e) => {
  if (e.target.classList.contains("item")) {
    console.log("Item clickeado:", e.target.textContent);
  }
});
```

En donde:

1. Los eventos se propagan desde el elemento hijo hacia arriba.
2. Se puede capturar eventos de múltiples elementos con un solo listener.
3. El código es más eficiente y maneja elementos dinámicos.

---

## **Pregunta #23**

¿Qué son el event bubbling y event delegation en JavaScript y cómo puedo usarlos para optimizar mis event listeners?

---

---

# **📄 #24: Higher Order Functions**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He usado funciones básicas pero ahora veo código donde las funciones se pasan como argumentos a otras funciones o donde funciones retornan otras funciones. Esto me confunde porque no entiendo por qué alguien haría esto, qué ventajas tiene, ni cómo puedo aplicar este concepto de "higher order functions" en mis propios proyectos para hacer mi código más flexible y reutilizable.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Función que recibe otra función como argumento
function processArray(arr, callback) {
  return arr.map(callback);
}

const numbers = [1, 2, 3, 4];
const doubled = processArray(numbers, num => num * 2);
console.log(doubled); // [2, 4, 6, 8]

// Función que retorna otra función
function createMultiplier(factor) {
  return function(number) {
    return number * factor;
  };
}

const multiplyBy3 = createMultiplier(3);
console.log(multiplyBy3(5)); // 15
```

En donde:

1. Las funciones pueden recibir otras funciones como parámetros.
2. Las funciones pueden retornar nuevas funciones.
3. El código se vuelve más modular y reutilizable.

---

## **Pregunta #24**

¿Qué son las funciones de orden superior en JavaScript y cómo puedo usarlas para crear código más flexible?

---

---

# **📄 #25: Nullish Coalescing y Optional Chaining**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está estudiando JavaScript Vanilla. Constantemente encuentro errores cuando intento acceder a propiedades de objetos que podrían ser null o undefined, especialmente cuando trabajo con datos de APIs. Tengo que escribir muchas validaciones anidadas para evitar estos errores. He visto operadores como ?? y ?. pero no entiendo qué hacen ni cómo pueden simplificar mi código de validación.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Nullish coalescing (??)
const value1 = null ?? "default";
const value2 = 0 ?? "default";
const value3 = "" ?? "default";
console.log(value1); // "default"
console.log(value2); // 0
console.log(value3); // ""

// Optional chaining (?.)
const user = {
  name: "Vale",
  address: {
    city: "Bucaramanga"
  }
};

console.log(user?.address?.city); // "Bucaramanga"
console.log(user?.phone?.number); // undefined (no error)
```

En donde:

1. ?? devuelve el valor derecho solo si el izquierdo es null o undefined.
2. ?. permite acceder a propiedades anidadas sin errores.
3. El código maneja valores nulos de forma segura y elegante.

---

## **Pregunta #25**

¿Cómo funcionan el nullish coalescing (??) y optional chaining (?.) para manejar valores nulos de forma segura?

---

---

# **📄 #26: Map y Set Data Structures**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. Hasta ahora he usado principalmente objetos literales y arrays para almacenar datos, pero he escuchado que existen estructuras más especializadas como Map y Set. No entiendo qué son, en qué se diferencian de los objetos y arrays tradicionales, cuáles son sus ventajas, ni en qué situaciones específicas debería considerar usarlos en lugar de las estructuras que ya conozco.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Map: pares clave-valor con cualquier tipo de clave
const userMap = new Map();
userMap.set("name", "Vale");
userMap.set(1, "Uno");
userMap.set(true, "Verdadero");

console.log(userMap.get("name")); // "Vale"
console.log(userMap.size); // 3
console.log(userMap.has("name")); // true

// Set: colección de valores únicos
const numbers = new Set([1, 2, 3, 3, 4, 4, 5]);
console.log(numbers); // Set(5) {1, 2, 3, 4, 5}
numbers.add(6);
console.log(numbers.has(3)); // true
```

En donde:

1. Map almacena pares clave-valor con claves de cualquier tipo.
2. Set almacena valores únicos sin duplicados.
3. Ambas estructuras tienen métodos optimizados para sus casos de uso.

---

## **Pregunta #26**

¿Qué son Map y Set en JavaScript y cuándo debo usarlos en lugar de objetos y arrays tradicionales?

---

---

# **📄 #27: Symbols y Propiedades Privadas**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación que está aprendiendo JavaScript Vanilla. Cuando creo objetos o clases, todas las propiedades son públicas y accesibles desde cualquier lugar. He escuchado sobre Symbols y sobre formas de crear propiedades privadas, pero no entiendo qué son, cómo funcionan, ni por qué necesitaría ocultar ciertas propiedades o métodos dentro de mis objetos para mantener la integridad de los datos.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Symbols: identificadores únicos
const id = Symbol("id");
const user = {
  name: "Vale",
  [id]: 12345
};

console.log(user.name); // "Vale"
console.log(user[id]); // 12345
console.log(Object.keys(user)); // ["name"] - Symbol no aparece

// Propiedades privadas con #
class BankAccount {
  #balance = 0;
  
  deposit(amount) {
    this.#balance += amount;
  }
  
  getBalance() {
    return this.#balance;
  }
}

const account = new Account();
account.deposit(100);
console.log(account.getBalance()); // 100
// console.log(account.#balance); // Error: propiedad privada
```

En donde:

1. Symbols crean identificadores únicos para propiedades.
2. Las propiedades privadas (#) no son accesibles fuera de la clase.
3. Se protege la integridad de los datos internos.

---

## **Pregunta #27**

¿Qué son los Symbols en JavaScript y cómo puedo crear propiedades privadas en mis objetos y clases?

---

---

# **📄 #28: Generators e Iterators**

## **Instrucción:**

Vas a actuar como un docente de programación para estudiantes de 17-24 años con enfoque en JavaScript. A través de un sistema de pregunta y respuesta me ayudarás a comprender conceptos que aún no domino. Te entregaré un contexto, luego la entrada con mi pregunta, y finalmente me responderás siguiendo las indicaciones dadas.

---

## **Contexto:**

Soy un estudiante de programación trabajando con JavaScript Vanilla. He visto funciones con un asterisco (function*) y una palabra clave yield que nunca había encontrado antes. Parece que estas funciones pueden pausar y reanudar su ejecución, pero no comprendo cómo funciona esto, para qué sirven los generators e iterators, ni en qué casos prácticos sería útil usar esta funcionalidad en lugar de funciones normales.

---

## **Entrada:**

Voy a pasarte la pregunta puntual, con el fin de que me expliques a nivel de caso de estudio cómo funciona dicho concepto. Esta pregunta será de manera directa como mensaje del prompt.

---

## **Salida:**

Me responderás con una explicación pedagógica a nivel de caso de estudio, donde mezcles la explicación teórica, con ejemplos codificables y texto argumentativo, haciendo línea al código que se genera.

---

## **Ejemplo:**

```javascript
// Generator function
function* numberGenerator() {
  yield 1;
  yield 2;
  yield 3;
}

const gen = numberGenerator();
console.log(gen.next()); // { value: 1, done: false }
console.log(gen.next()); // { value: 2, done: false }
console.log(gen.next()); // { value: 3, done: false }
console.log(gen.next()); // { value: undefined, done: true }

// Generator infinito
function* idGenerator() {
  let id = 1;
  while (true) {
    yield id++;
  }
}

const ids = idGenerator();
console.log(ids.

---

## **Pregunta #28**

¿Qué son los Symbols en JavaScript y cómo puedo crear propiedades privadas en mis objetos y clases?

---