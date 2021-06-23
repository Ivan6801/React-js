![Mesa de trabajo 1-8](https://user-images.githubusercontent.com/60527338/123014682-9e95fd00-d37b-11eb-968d-f6cdd0b2557d.png)
# React-js 
Hola soy Ivan Gonzalez :) Una biblioteca de JavaScript para crear interfaces de usuario 🚀 (pero, son sólo para ti 🤫).

# ¿Qué es React.js? 
**React** cumple su función como biblioteca ya que para utilizar su código se debe importar. También es un *Framework* aunque las convenciones de cómo debe ser organizado todo no son estrictas.
En este curso aprenderás las prácticas que la comunidad ha decidido que son buenas.

**React es declarativo**, lo que quiere decir que se le indica qué debe hacer pero no cómo debe hacerse, ahorrando de esta manera muchos pasos.

**JSX** es HTML dentro de Javascript, esto se verá más adelante en detalle.

React está estructurado por **componentes** que son como pequeños bloques de lego que al ser unidos forman aplicaciones de React. Estos componentes pueden tener estilos, ser enlazados a eventos y sus estados pueden ser modificados.

Con React también se tiene la ventaja de que será escrito una sola vez y podrá ser utilizado en aplicaciones web, móviles, entre otras.

# ReactDOM.render 
* **React** y **ReactDOM** trabajarán en conjunto.
  * React como análogo a **createElement**
  * ReactDOM a **appendChild**
* **ReactDOM.render()** toma dos argumentos: Qué queremos renderizar y dónde lo queremos renderizar.

Siempre que escribas **JSX** es requisito importar React.
![ReactDOM render](https://user-images.githubusercontent.com/60527338/123010298-30e5d300-d373-11eb-9527-534005b7c595.jpg)

# JSX
JSX es una extensión de JavaScript creada por Facebook para el uso con la biblioteca React. Sirve de preprocesador (como Sass o Stylus a CSS) y transforma el código generado con React a JavaScript.

JSX tiene su alternativa que es **React.createElement** pero es preferible JSX porque es mucho más legible y expresivo. Ambos tienen el mismo poder y la misma capacidad.
![React createElement](https://user-images.githubusercontent.com/60527338/123017175-e9feda00-d380-11eb-9211-76c69c867a81.jpg)

**React.createElement** recibe 3 argumentos:

* El tipo de elemento que estamos creando
* sus atributos o props
* y el children que es el contenido.
Ejemplo:

```bash
React.createElement(‘a’, { href: ‘https://es.reactjs.org/’, target: '_blank'  }, ‘Ir a React.js’);
```
![href](https://user-images.githubusercontent.com/60527338/123017551-aa84bd80-d381-11eb-8fe5-433c78e346ef.jpg)

En JSX se utilizan las llaves para introducir variables o expresiones de Javascript. Lo que sea que esté adentro se va a evaluar y su resultado se mostrará en pantalla.

Las expresiones pueden ser llamadas a otras funciones, cálculos matemáticos, etc. Si las expresiones son false, 0, null, undefined, entre otros, no se verán.

