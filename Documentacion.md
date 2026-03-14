# Documentacion
## Decision semantica
El uso de etiquetas semánticas permite que el contenido tenga un significado intrínseco más allá de su apariencia visual. Aquí el detalle de cada elección:

1. **!DOCTYPE html** y **html lang="en":** Define el tipo de documento y el idioma principal del contenido.
2. **header:** Se utilizó para agrupar el título principal y la introducción de la tarjeta, estableciendo el contexto inicial del perfil.
3. **h1 y h3:** Se empleó una jerarquía de títulos para organizar la importancia de la información, desde el propósito general hasta el nombre del autor.
4. **main:** Define el contenido principal y único del documento, separándolo del encabezado y el pie de página.
5. **section:** Organiza la información en bloques lógicos (Sobre mí y Contactos), permitiendo una estructura modular.
6. **ul y li:** Ideales para presentar habilidades y pasatiempos, ya que son listas de elementos donde el orden no altera el significado.
7. **time:** Se aplicó con el atributo datetime para que la fecha de nacimiento sea legible por máquinas (buscadores o calendarios).
8. **strong:** Utilizado para dar énfasis de importancia a datos clave como "ser feliz" o la ubicación.
9. **footer:** Contiene la información de cierre, marcando claramente dónde termina el cuerpo del perfil.
10. **address:** Proporciona información de contacto específica, lo cual es la práctica correcta para correos y teléfonos.
11. **a:** Define el hipervínculo para el correo electrónico, permitiendo la interacción directa del usuario.

## Arbol "DOM"
El árbol DOM representa la estructura jerárquica de los elementos. Visualmente, se despliega de la siguiente manera:

### DOM

```<html>

<head>

<meta> (Charset y Viewport)

<title> ("Targeta de presentacion digital")

<body>

<header>

<h1> ("Targeta digital")

<h3> ("Matías Cardona Cañas")

<p> → <strong> ("ser feliz")

<main>

<section>

<h2> ("Sobre mi")

<h3> ("Mis habilidades")

<ul> → <li> (x3)

<h3> ("Pasatiempos")

<ul> → <li> (x4)

<h3> ("Personal information")

<p> → <strong> ("Medellín")

<p> → <time> → <strong> ("17/junio/2009")

<p> → <strong> ("1")

<footer>

<section>

<h3> ("Contactos")

<address>

<p> → <a> → <span> (Email)

<p> (Teléfono)
```
