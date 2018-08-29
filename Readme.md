# Bootstrap 4

Clase 4
## ¿Qué es un Framework Frontend?
- También conocidos como Frameworks CSS

Son una base para empezar un proyecto web permitiendo **flexibilidad en el diseño**

**Organización y estructura** de nuestros __HTML, CSS Y JavaScript__

### ¿Qué trae un framework frontend? 

Ahorrar mucho tiempo, Componentes visuales, Responsive design, el código anda. 
- Grilla
- Estilos para las fuentes
- Componentes visuales pre-armados

### Algunos Frameworks Fron-End
- Bootstrap
- Fundation
- Bulma
- Flexbox Grid


Clase 5

## Nuestro Proyecto: Hola Mundo de Bootstrap

Vamos al sitio web oficial de Bootstrap en getbootstrap.com . Existen 2 formas para utiliza bootstrap:
~~~
1. Mediante el **CDN**: En este primer ejemplo se copia la plantilla de inicio que, contiene la referencia a los css y a 3 archivos javascript. Dentro de los cJS están:
- - a. La referencia a JQuery (Sí, utiliza JQuery para las funciones que css, por obvias razones no podría implementar)
- - b. Referencia a Popper.JS: Esta herramienta nos sirve para crear los popUps (esos mensajes flotantes que se muestran al posicionar el cursor en un lugar predeterminado)
- - c. Finalmente llama al JS de bootstrap.

Por otro lado, noten que cada referencia contiene un .min dentro de sus nombres (por ejemplo; bootstrap.min.css, …jquery-3.3.1.slim.min.js, etc) que no es más que la versión minificada(sin espacios) de
cada archivo de código.

2. Descargando todos los archivos comprimidos:
- - Otra de las opciones es descargando todos los archivos que componen Bootstrap, esta opción es interesante ya que te permite trabajar sin conexión a internet, cosa que no puedes hacer con laa opción anterior.
~~~
Al abrir la pagina nos dirigimos a el boton **Get started**, pinchamos y nos dirijimos a el apartado __Starter template__ y copiamos toda la plantilla de __HTML5__

```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```
