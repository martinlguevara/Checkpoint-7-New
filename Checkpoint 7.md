**CHECKPOINT 7**

# > ****¿Qué diferencia a Javascript de cualquier otro lenguaje de programación?****



1. **Lenguaje de programación interpretado y de alto nivel**: JavaScript se destaca por ser un lenguaje interpretado, lo que significa que el código puede ejecutarse sin necesidad de ser compilado previamente. Esta característica agiliza el proceso de desarrollo al permitir pruebas rápidas y depuración más eficiente. Además, al ser de alto nivel, JavaScript está diseñado para ser fácilmente comprensible y escribible para los programadores, lo que lo hace muy accesible incluso para aquellos que están empezando en la programación.
1. **Lenguaje orientado a eventos y asíncrono**: Una de las características más distintivas de JavaScript es su modelo de ejecución asíncrona y orientada a eventos. Esto significa que JavaScript puede manejar múltiples tareas simultáneamente sin bloquear la ejecución del código. Por ejemplo, puede realizar operaciones de entrada/salida (E/S) como solicitudes de red o manipulación de archivos sin detener la ejecución del resto del programa. Esta capacidad es fundamental en el desarrollo web moderno, donde la interactividad y la capacidad de respuesta son esenciales para una experiencia de usuario fluida.
1. **Amplio uso en el desarrollo web**: JavaScript es el lenguaje principal para el desarrollo de aplicaciones web interactivas. Desde la validación de formularios hasta la creación de animaciones y la manipulación del DOM (Document Object Model), JavaScript permite agregar interactividad y dinamismo a las páginas web. Además, JavaScript es fundamental en el desarrollo de aplicaciones de una sola página (SPA) y en la creación de interfaces de usuario modernas y receptivas.
1. **Soporte multiplataforma y de lado del cliente**: Una de las ventajas clave de JavaScript es que se ejecuta en el navegador del cliente, lo que significa que no requiere ninguna configuración especial del servidor. Esto hace que las aplicaciones web construidas con JavaScript sean altamente portátiles y puedan ejecutarse en una amplia variedad de dispositivos y plataformas. Además, JavaScript se ha expandido más allá del navegador y ahora se utiliza en entornos de servidor (Node.js) y en el desarrollo de aplicaciones de escritorio y móviles (usando frameworks como React Native).
1. **Extensibilidad y ecosistema vibrante**: JavaScript cuenta con una gran cantidad de bibliotecas y marcos de trabajo que facilitan el desarrollo de aplicaciones complejas de manera eficiente. Frameworks como React, Angular y Vue.js son ampliamente utilizados en el desarrollo web moderno, proporcionando herramientas y patrones de diseño que aceleran el proceso de desarrollo y mejoran la calidad del software resultante. Además, la comunidad de JavaScript es muy activa, lo que significa que siempre hay nuevas herramientas, bibliotecas y recursos disponibles para los desarrolladores.
1. **Tipado dinámico y débil**: A diferencia de otros lenguajes que son tipados estática o fuertemente tipados, JavaScript es dinámico y débilmente tipado. Esto significa que las variables no están asociadas a ningún tipo específico y pueden cambiar de tipo durante la ejecución del programa. Si bien esta flexibilidad puede llevar a errores de tipo, también permite una mayor agilidad en el desarrollo al no requerir una definición estricta de tipos de datos. Sin embargo, esta flexibilidad también puede requerir un cuidado adicional por parte del desarrollador para garantizar la integridad y la robustez del código.

En resumen, JavaScript es único por su naturaleza interpretada, orientada a eventos, amplio uso en el desarrollo web, soporte multiplataforma, extensibilidad y tipado dinámico. Estas características lo convierten en una herramienta poderosa y versátil para el desarrollo de aplicaciones web modernas, y su continua evolución y adopción lo mantienen en el centro del panorama tecnológico actual.

# >  **¿Cuáles son algunos tipos de datos JS?**



JavaScript es un lenguaje de programación dinámico que admite varios tipos de datos para almacenar y manipular información. Aquí tienes algunos de los tipos de datos más comunes en JavaScript:

1. **Número (Number)**: Representa valores numéricos, ya sean enteros o de punto flotante. Por ejemplo:

let edad = 25;

let precio = 10.99;


2. **Cadena de texto (String)**: Representa una secuencia de caracteres encerrados entre comillas simples o dobles. Por ejemplo:

let nombre = "Juan";

let mensaje = '¡Hola mundo!';

3. **Booleano (Boolean)**: Representa un valor verdadero (true) o falso (false). Se utiliza para evaluar condiciones en las estructuras de control. Por ejemplo:

let esMayorDeEdad = true;

let tieneDescuento = false;

4. **Arreglo (Array)**: Representa una colección ordenada de elementos. Los elementos pueden ser de cualquier tipo de datos, incluidos otros arreglos. Por ejemplo:

let numeros = [1, 2, 3, 4, 5];

let colores = ["rojo", "verde", "azul"];

5. **Objeto (Object)**: Representa una colección de pares clave-valor. Cada valor se accede mediante su clave correspondiente. Por ejemplo:

let persona = {

`    `nombre: "María",

`    `edad: 30,

`    `ciudad: "Madrid"

};

6. **Undefined**: Representa un valor indefinido. Se asigna automáticamente a las variables que no han sido inicializadas o a las funciones que no tienen una declaración de retorno. Por ejemplo:

let direccion;

7. **Null**: Representa la ausencia intencional de cualquier valor o referencia a un objeto. Por ejemplo:

let resultado = null;

8. **Símbolo (Symbol)**: Introducido en ECMAScript 6, representa un identificador único e inmutable. Se utiliza principalmente como propiedades de objetos para evitar colisiones de nombres. Por ejemplo:

const simbolo = Symbol('descripcion');

Estos son algunos de los tipos de datos más utilizados en JavaScript. Comprender cómo trabajar con ellos es fundamental para desarrollar aplicaciones web eficientes y sólidas.



# >  **¿Cuáles son las tres funciones de String en JS?**



En JavaScript, las cadenas de texto (strings) son primitivas que representan secuencias de caracteres. Existen muchas funciones integradas en JavaScript que pueden utilizarse para manipular cadenas de texto. Aquí tienes tres funciones de cadena comunes:

1. **length**:   La propiedad **length** de las cadenas de texto en JavaScript devuelve la cantidad de caracteres que contiene una cadena. Esta propiedad es extremadamente útil para determinar la longitud de una cadena dinámicamente, lo que puede ser crucial en situaciones donde se necesite verificar la validez de una entrada de usuario o calcular la longitud de una cadena para realizar alguna operación específica. Por ejemplo, al validar la longitud de una contraseña en un formulario de registro, podemos usar **password.length** para asegurarnos de que cumpla con ciertos requisitos mínimos de longitud.

   Por ejemplo:

   let password = "contraseña123";

   if (password.length >= 8) {

   `    `console.log("La contraseña cumple con los requisitos mínimos de longitud.");

   } else {

   `    `console.log("La contraseña debe tener al menos 8 caracteres.");

   }


2. **toUpperCase()**: El método **toUpperCase()** devuelve una nueva cadena de texto con todos los caracteres de la cadena original convertidos a mayúsculas. Esto es útil cuando necesitamos comparar cadenas sin importar si están escritas en mayúsculas o minúsculas, o cuando queremos asegurarnos de que ciertos datos estén estandarizados en un formato específico. Por ejemplo, al procesar nombres de usuario en un formulario de registro, podemos usar **nombre.toUpperCase()** para garantizar que todos los nombres de usuario se almacenen en la misma convención de capitalización.

`      `Por ejemplo:

`           `let nombreUsuario = "juan123";

`           `let nombreUsuarioEstándar = nombreUsuario.toUpperCase();

`           `console.log("Nombre de usuario estándar:", nombreUsuarioEstándar);


3. **toLowerCase()**: El método **toLowerCase()** es el inverso de **toUpperCase()**, devuelve una nueva cadena de texto con todos los caracteres de la cadena original convertidos a minúsculas. Al igual que **toUpperCase()**, **toLowerCase()** es útil para estandarizar datos y para comparaciones sin distinción entre mayúsculas y minúsculas. Por ejemplo, al verificar si una dirección de correo electrónico ya está registrada en un sistema, podemos convertir la dirección de correo electrónico proporcionada por el usuario a minúsculas usando **correoElectronico.toLowerCase()** y luego compararla con las direcciones de correo electrónico existentes en la base de datos.

`      `Por ejemplo:

let correoElectronicoExistente = "ejemplo@correo.com";

let correoElectronicoUsuario = "EJEMPLO@CORREO.COM";

if (correoElectronicoUsuario.toLowerCase() === correoElectronicoExistente.toLowerCase()) {

`    `console.log("La dirección de correo electrónico ya está registrada.");

} else {

`    `console.log("La dirección de correo electrónico está disponible para registro.");

}


Estas son solo tres de las muchas funciones y métodos disponibles para manipular cadenas de texto en JavaScript. Las cadenas de texto son muy versátiles y es posible realizar una amplia variedad de operaciones con ellas, como concatenación, búsqueda, reemplazo, entre otras.



# >  **¿Qué es un condicional?**


**Condicionales en Programación: Tomando Decisiones Dinámicamente**

Los condicionales son estructuras fundamentales en la programación que permiten que un programa tome decisiones dinámicamente en función de condiciones específicas. Estas condiciones pueden variar desde simples comparaciones de valores hasta evaluaciones complejas de expresiones booleanas.

**Importancia de los Condicionales: Flexibilidad y Adaptabilidad**

La importancia de los condicionales radica en su capacidad para proporcionar flexibilidad y adaptabilidad a un programa. Permiten que el flujo de ejecución del programa se bifurque en diferentes direcciones según las condiciones que se cumplan en tiempo de ejecución. Esta capacidad es esencial para escribir programas que puedan manejar una amplia variedad de situaciones y escenarios, lo que los hace más robustos y poderosos.

**Expresiones Booleanas: El Corazón de los Condicionales**

En el núcleo de los condicionales se encuentran las expresiones booleanas, que son expresiones que pueden evaluarse como verdaderas o falsas. Estas expresiones pueden ser simples comparaciones de valores, como **edad >= 18**, o pueden ser más complejas, involucrando múltiples condiciones combinadas con operadores lógicos, como **edad >= 18 && edad <= 65**.

**Estructura Básica de un Condicional: if...else**

La estructura más común de un condicional en la mayoría de los lenguajes de programación es la declaración **if...else**. Esta declaración evalúa una expresión condicional y ejecuta un bloque de código si la expresión es verdadera y otro bloque si es falsa. Por ejemplo:

let edad = 20;

if (edad >= 18) {

`    `console.log("Eres mayor de edad.");

} else {

`    `console.log("Eres menor de edad.");

}

**Anidamiento de Condicionales: Manejando Casos Complejos**

Los condicionales pueden anidarse dentro de otros condicionales para manejar casos más complejos. Este anidamiento permite construir lógica condicional más sofisticada para manejar una variedad más amplia de situaciones. Por ejemplo, en un programa de gestión de usuarios, podemos tener condicionales anidados para determinar diferentes niveles de permisos de usuario.

**Operador Ternario: Una Forma Concisa de Escribir Condicionales**

Además de la estructura **if...else**, muchos lenguajes de programación, incluido JavaScript, ofrecen el operador ternario como una forma más concisa de escribir condicionales simples. Este operador permite evaluar una expresión y devolver un valor basado en si la expresión es verdadera o falsa. Por ejemplo:

let esMayor = (edad >= 18) ? "Eres mayor de edad." : "Eres menor de edad.";

console.log(esMayor);

**Aplicaciones Prácticas de los Condicionales**

Los condicionales tienen aplicaciones prácticas en una amplia variedad de situaciones en la programación. Desde la validación de entradas de usuario en formularios hasta la creación de algoritmos complejos, los condicionales permiten que los programas tomen decisiones dinámicamente en función de los datos disponibles en tiempo de ejecución.

**En Resumen**

En resumen, los condicionales son una herramienta poderosa en la programación que permite que los programas tomen decisiones dinámicamente en función de las condiciones de los datos. Proporcionan flexibilidad y control sobre el flujo de ejecución del programa, lo que es fundamental para escribir programas robustos y adaptables a una variedad de situaciones y requisitos.
# >  **¿Qué es un operador ternario?**


Un operador ternario, también conocido como operador condicional, es un tipo especial de operador que toma tres operandos y se utiliza para realizar una evaluación condicional de manera concisa en una sola línea de código.

En JavaScript, el operador ternario tiene la siguiente sintaxis:

condición ? expresiónSiVerdadero : expresiónSiFalso

Donde:

- **condición** es la expresión que se evalúa.
- **expresiónSiVerdadero** es el valor que se devuelve si la condición es verdadera.
- **expresiónSiFalso** es el valor que se devuelve si la condición es falsa.

Por ejemplo, considera el siguiente código que utiliza un operador ternario para determinar si una persona es mayor o menor de edad:

let edad = 20;

let mensaje = (edad >= 18)  "Eres mayor de edad." : "Eres menor de edad.";

console.log(mensaje); // Output: Eres mayor de edad.

En este caso, la condición **edad >= 18** se evalúa como verdadera, por lo que se devuelve el valor de **expresiónSiVerdadero**, que es "Eres mayor de edad.". Si la condición fuera falsa, se devolvería el valor de **expresiónSiFalso**, que en este caso sería "Eres menor de edad.".

El uso de operadores ternarios puede hacer que el código sea más conciso y legible, especialmente para evaluaciones simples. Sin embargo, es importante usarlos con moderación para no sacrificar la claridad del código en favor de la brevedad.

# >  **¿Cuál es la diferencia entre una declaración de función y una expresión de función?**



La diferencia principal entre una declaración de función y una expresión de función en JavaScript radica en cómo son definidas y cómo se comportan en el código.

1. **Declaración de función (Function Declaration)**:
   1. Se define utilizando la palabra clave **function** seguida por el nombre de la función y su cuerpo.
   1. Puede ser invocada antes de su declaración, debido al concepto de elevación (hoisting) en JavaScript. Esto significa que una función declarada puede ser llamada en el código antes de que se haya declarado formalmente.
   1. Puede ser utilizada como un bloque de código independiente y su alcance está dentro del contexto en el que se define.

Ejemplo de declaración de función:

function suma(a, b) {

`    `return a + b;

}

1. **Expresión de función (Function Expression)**:
- Se define mediante una asignación de función a una variable (o a cualquier otro identificador).
- No puede ser invocada antes de su declaración, ya que no está sujeta al hoisting. Debe ser definida antes de ser invocada en el código.
- Puede ser anónima o tener un nombre, y su alcance está determinado por el contexto en el que se asigna.

Ejemplo de expresión de función:

let resta = function(a, b) {

`    `return a - b;

};

En resumen, una declaración de función se define con la palabra clave **function** y se puede invocar antes de su declaración debido al hoisting. Mientras que una expresión de función se define mediante asignación y no puede ser invocada antes de su declaración. Ambas formas tienen sus usos específicos en diferentes situaciones de programación

**¿Qué es la palabra clave "this" en JS?**

La palabra clave **this** en JavaScript es una variable especial que se refiere al objeto al que pertenece el contexto actual. El valor de **this** depende de cómo se llama la función y de dónde se utiliza.

**Métodos de objeto, "this"**

Los objetos son creados usualmente para representar entidades del mundo real, como usuarios, órdenes, etc.:

let user = {

`  `name: "John",

`  `age: 30

};

Y en el mundo real un usuario puede *actuar*: seleccionar algo del carrito de compras, hacer login, logout, etc.

Estas acciones se implementan asignando funciones a las propiedades del objeto.

<a name="ejemplos-de-metodos"></a>[**Ejemplos de métodos**](https://es.javascript.info/object-methods#ejemplos-de-metodos)

Para empezar, enseñemos al usuario user a decir hola:

let user = {

`  `name: "John",

`  `age: 30

};

user.sayHi = function() {

`  `alert("¡Hola!");

};

user.sayHi(); // ¡Hola!

Aquí simplemente usamos una expresión de función para crear la función y asignarla a la propiedad user.sayHi del objeto.

Entonces la llamamos con user.sayHi(). ¡El usuario ahora puede hablar!

Una función que es la propiedad de un objeto es denominada su *método*.

Así, aquí tenemos un método sayHi del objeto user.

Por supuesto, podríamos usar una función pre-declarada como un método, parecido a esto:

let user = {

`  `// ...

};

// primero, declara

function sayHi() {

`  `alert("¡Hola!");

};

// entonces la agrega como un método

user.sayHi = sayHi;

user.sayHi(); // ¡Hola!

**Programación orientada a objetos**

Cuando escribimos nuestro código usando objetos que representan entidades, eso es llamado [Programación Orientada a Objetos](https://es.wikipedia.org/wiki/Programaci%C3%B3n_orientada_a_objetos), abreviado: “POO”.

POO (OOP sus siglas en inglés) es una cosa grande, una ciencia interesante en sí misma. ¿Cómo elegir las entidades correctas? ¿Cómo organizar la interacción entre ellas? Eso es arquitectura, y hay muy buenos libros del tópico como “Patrones de diseño: Elementos de software orientado a objetos reutilizable” de E. Gamma, R. Helm, R. Johnson, J. Vissides o “Análisis y Diseño Orientado a Objetos” de G. Booch, y otros.

<a name="formas-abreviadas-para-los-metodos"></a>[**Formas abreviadas para los métodos**](https://es.javascript.info/object-methods#formas-abreviadas-para-los-metodos)

Existe una sintaxis más corta para los métodos en objetos literales:

// estos objetos hacen lo mismo

user = {

`  `sayHi: function() {

`    `alert("Hello");

`  `}

};

// la forma abreviada se ve mejor, ¿verdad?

user = {

`  `sayHi() {   // igual que "sayHi: function(){...}"

`    `alert("Hello");

`  `}

};

Como se demostró, podemos omitir "function" y simplemente escribir sayHi().

A decir verdad, las notaciones no son completamente idénticas. Hay diferencias sutiles relacionadas a la herencia de objetos (por cubrir más adelante) que por ahora no son relevantes. En casi todos los casos la sintaxis abreviada es la preferida.

<a name="this-en-metodos"></a>[**“this” en métodos**](https://es.javascript.info/object-methods#this-en-metodos)

Es común que un método de objeto necesite acceder a la información almacenada en el objeto para cumplir su tarea.

Por ejemplo, el código dentro de user.sayHi() puede necesitar el nombre del usuario user.

**Para acceder al objeto, un método puede usar la palabra clave this.**

El valor de this es el objeto “antes del punto”, el usado para llamar al método.

Por ejemplo:

let user = {

`  `name: "John",

`  `age: 30,

`  `sayHi() {

`    `// "this" es el "objeto actual"

`    `alert(this.name);

`  `}

};

user.sayHi(); // John

Aquí durante la ejecución de user.sayHi(), el valor de this será user.

Técnicamente, también es posible acceder al objeto sin this, haciendo referencia a él por medio de la variable externa:

let user = {

`  `name: "John",

`  `age: 30,

`  `sayHi() {

`    `alert(user.name); // "user" en vez de "this"

`  `}

};

…Pero tal código no es confiable. Si decidimos copiar user a otra variable, por ejemplo admin = user y sobrescribir user con otra cosa, entonces accederá al objeto incorrecto.

Eso queda demostrado en las siguientes lineas:

let user = {

`  `name: "John",

`  `age: 30,

`  `sayHi() {

`    `alert( user.name ); // lleva a un error

`  `}

};


let admin = user;

user = null; // sobrescribimos para hacer las cosas evidentes

admin.sayHi(); // TypeError: No se puede leer la propiedad 'name' de null

Si usamos this.name en vez de user.name dentro de alert, entonces el código funciona.

<a name="this-no-es-vinculado"></a>[**“this” no es vinculado**](https://es.javascript.info/object-methods#this-no-es-vinculado)

En JavaScript, la palabra clave this se comporta de manera distinta a la mayoría de otros lenguajes de programación. Puede ser usado en cualquier función, incluso si no es el método de un objeto.

No hay error de sintaxis en el siguiente ejemplo:

function sayHi() {

`  `alert( this.name );

}

El valor de this es evaluado durante el tiempo de ejecución, dependiendo del contexto.

Por ejemplo, aquí la función es asignada a dos objetos diferentes y tiene diferentes “this” en sus llamados:

let user = { name: "John" };

let admin = { name: "Admin" };

function sayHi() {

`  `alert( this.name );

}

// usa la misma función en dos objetos

user.f = sayHi;

admin.f = sayHi;

// estos llamados tienen diferente "this"

// "this" dentro de la función es el objeto "antes del punto"

user.f(); // John  (this == user)

admin.f(); // Admin  (this == admin)

admin['f'](); // Admin (punto o corchetes para acceder al método, no importa)

La regla es simple: si obj.f() es llamado, entonces this es obj durante el llamado de f. Entonces es tanto user o admin en el ejemplo anterior.

**Llamado sin un objeto: this == undefined**

Podemos incluso llamar la función sin un objeto en absoluto:

function sayHi() {

`  `alert(this);

}

sayHi(); // undefined

En este caso this es undefined en el modo estricto. Si tratamos de acceder a this.name, habrá un error.

En modo no estricto el valor de this en tal caso será el *objeto global* (window en un navegador, llegaremos a ello en el capítulo [Objeto Global](https://es.javascript.info/global-object)). Este es un comportamiento histórico que "use strict" corrige.

Usualmente tal llamado es un error de programa. Si hay this dentro de una función, se espera que sea llamada en un contexto de objeto.

**Las consecuencias de un this desvinculado**

Si vienes de otro lenguaje de programación, probablemente estés habituado a la idea de un "this vinculado", donde los método definidos en un objeto siempre tienen this referenciando ese objeto.

En JavaScript this es “libre”, su valor es evaluado al momento de su llamado y no depende de dónde fue declarado el método sino de cuál es el objeto “delante del punto”.

El concepto de this evaluado en tiempo de ejecución tiene sus pros y sus contras. Por un lado, una función puede ser reusada por diferentes objetos. Por otro, la mayor flexibilidad crea más posibilidades para equivocaciones.

Nuestra posición no es juzgar si la decisión del diseño de lenguaje es buena o mala. Vamos a entender cómo trabajar con ello, obtener beneficios y evitar problemas.

<a name="las-funciones-de-flecha-no-tienen-this"></a>[**Las funciones de flecha no tienen “this”**](https://es.javascript.info/object-methods#las-funciones-de-flecha-no-tienen-this)

Las funciones de flecha son especiales: ellas no tienen su “propio” this. Si nosotros hacemos referencia a this desde tales funciones, esta será tomada desde afuera de la función “normal”.

Por ejemplo, aquí arrow() usa this desde fuera del método user.sayHi():

let user = {

`  `firstName: "Ilya",

`  `sayHi() {

`    `let arrow = () => alert(this.firstName);

`    `arrow();

`  `}

};

user.sayHi(); // Ilya

Esto es una característica especial de las funciones de flecha, útil cuando no queremos realmente un this separado sino tomarlo de un contexto externo. Más adelante en el capítulo [Funciones de flecha revisadas](https://es.javascript.info/arrow-functions) las trataremos en profundidad.

<a name="resumen"></a>[**Resumen**](https://es.javascript.info/object-methods#resumen)

- Las funciones que son almacenadas en propiedades de objeto son llamadas “métodos”.
- Los método permiten a los objetos “actuar”, como object.doSomething().
- Los métodos pueden hacer referencia al objeto con this.

El valor de this es definido en tiempo de ejecución.

- Cuando una función es declarada, puede usar this, pero ese this no tiene valor hasta que la función es llamada.
- Una función puede ser copiada entre objetos.
- Cuando una función es llamada en la sintaxis de método: object.method(), el valor de this durante el llamado es object.

Ten en cuenta que las funciones de flecha son especiales: ellas no tienen this. Cuando this es accedido dentro de una función de flecha, su valor es tomado desde el exterior.



