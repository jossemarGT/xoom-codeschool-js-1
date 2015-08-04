# Javascript for non developers
## XOOM Code School // 2015-07-21
J. Jossemar Cordero R.

---

# ¿Quien es el expositor?

- Ingeniero de software*<!-- .element: class="fragment" -->
- Hackerpreneur<!-- .element: class="fragment" -->
- Developer, Inf eng, DevOps...<!-- .element: class="fragment" -->

---

<!-- .slide: data-background="#dd0000" -->

# Disclaimer

----

<!-- .slide: data-background="#C10C06" -->
![Keep calm](img/keep-calm.png)<!-- .element: style="margin-top: -20px; border:none" -->

---

## Pequeño repaso

[https://santatracker.google.com/#codelab](https://santatracker.google.com/#codelab)

---

# Aprendiendo lo esencial

----

<!-- .slide: data-background="img/code.png" -->

Note: Cualquier cosa que desconocemos se ve mal al principio, pero programar no debería ser tan malo

----

<!-- .slide: data-background="img/anyone-can-code.jpg" -->

Note: anyone can code.

----

<!-- .slide: data-background="img/talk-software.png" -->

Note: Programar es practicamente hablar, por supuesto algunos hablan muy bien y otros a duras penas se entiende que es español

---

# Variables

----

<!-- .slide: data-background="img/box.jpg" -->

----

<!-- .slide: data-background="img/kitty-box.jpg" -->

---

# Tipos de datos

----

##  Interger & Float

```javascript
var the_int = 5;
var another_int = -10000;

var the_float = 120.23;
var another_float = 100 - 0.5;
```

----

## String

```javascript
var the_string = 'Hello! ';
var another_string = 'Stranger';
var last_string = the_string + another_string + '? ' + 5;
```

----

## Boolean

```javascript
var the_truth = true;
var the_truth = 5 > 0;
```

----

## undefined and null

```javascript
var the_undefined_value;
var the_null_value = null;
```

----

## NaN

```javascript
var theNaN = Math.sqrt(-2);
theNaN = Math.log(-1);
theNaN = 0/0;
theNaN = parseFloat('foo');
```

---

#Arreglos

----

<!-- .slide: data-background="img/row-boxes.jpg" -->

----

```javascript
var theArray = ['Item 1','Item 2','Item 3'];

theArray[1];
```

---

# Objectos / Maps

----

![Octopus](img/octopus_blocks.png)

----

```javascript
var octo = {};

octo.uno = 1;
octo.dos = 2;

octo.hijo = {};
octo.hijo.nombre = 'el hijo';
octo.hijo.uno = 1.0;
octo.hijo.cajas = ['Item 1','Item 2','Item 3'];
```

---

# Statements

----

```javascript
console.log('Hola');
prompt('Algo que preguntar');
alert('Algo que desplegar');
```

---

#Practicando

----

Escriba un script en el cual se solicite su nombre y apellido por aparte, al igual
que su edad, si su edad es mayor a 20 años muestre el nombre completo en el caso contrario
solo diga hola.

---

#¿Dudas?
(Busquen los correos de los tutores en confluence)

---

#Gracias
