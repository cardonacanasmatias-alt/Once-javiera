# 📝Etiquetas del Formulario

¡Hola! Aquí tienes un repaso rápido, al grano y sin palabras raras sobre qué hace cada etiqueta dentro de nuestro archivo `Formulario.html`. Básicamente, estas son las piezas de Lego con las que armamos la interacción:

- **`<form>`**:  
  ¡Es el jefe del área! Funciona como una gran caja invisible que envuelve y agrupa todos los datos que el usuario va a llenar. Sin esta etiqueta, el botón de "Enviar" no sabría qué información agarrar.

- **`<label>`**:  
  Es el famoso "letrerito" o etiqueta de texto que le indica al usuario qué tiene que escribir. Tiene un truco genial: al estar enlazado a su campo usando el atributo `for="..."`, ¡si el usuario hace clic en el texto se activa la caja para escribir!

- **`<input>`**:  
  El caballo de batalla, el campo todoterreno. Cambia de comportamiento según qué `type` le pongamos:
  - `type="text"`, `"email"`, `"tel"` o `"number"`: Para las típicas cajas donde escribes datos cortos (como tu nombre, un número o un correo).
  - `type="radio"`: Para las opciones donde *solo puedes elegir una* a la vez (por ejemplo, cómo prefieren que los contactemos).
  - `type="checkbox"`: Las casillas cuadraditas que marcas con un "check" (para aceptar los términos o suscribirte al newsletter).

- **`<select>`, `<optgroup>` y `<option>`**:  
  El increíble equipo de los menús desplegables:
  - `<select>` es la caja del menú.
  - `<optgroup>` agrupa varias opciones bajo un título ("Soporte", "Información") para no tener una lista eterna y desordenada.
  - `<option>` es cada uno de los ítems que el usuario puede elegir dentro del desplegable.

- **`<textarea>`**:  
  Imagínalo como un `<input>` gigante y con mucha más libertad. Es una caja de texto grande diseñada para que el usuario escriba párrafos largos sin sentirse asfixiado (como el "Mensaje" principal de la consulta).

- **`<button>`**:  
  ¡Los ejecutores finales! 
  - El que tiene `type="submit"` recoge todo lo que el usuario llenó en el `<form>` y lo despacha.
  - El que tiene `type="reset"` es el botón del pánico: borra todo de golpe para empezar de cero si la persona se equivocó.

¡Y eso es todo! Con estas pocas etiquetas haces magia y armas formularios increíbles. 🚀
