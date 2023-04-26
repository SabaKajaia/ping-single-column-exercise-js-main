# Abrimos pronto

Debes implementar todo el ejercicio en el fichero _main.js_
No es necesario modificar index.html.

REVISA el fichero index.html para ver la estructura general del documento, sobretodo, de aquellas partes con las que vamos a interactuar

## Ejercicio 1

Implementa el JavaScript necesario para que, tras escribir una dirección de correo en el formulario y hagamos click en el botón, desaparezca el formulario y salga el mensaje de confirmación.

DE MOMENTO no hay que hacer nada con la variable _registeredEmails_

<details>
  <summary>Pasos y pistas</summary>
  <ol>
	<li>Selecciona el botón identificado con el id 'notify-me'</li>
	<li>Asocia el evento click a dicho boton. Por ejemplo, con addEventListener</li>
	<li>En la función de ese listener, debes recuperar dos nodos: el nodo del formulario y el nodo del DIV con el mensaje de confirmación</li>
	<li>Añade la clase _hidden_ al nodo del formulario</li>
	<li>Elimina la clase _hidden_ del nodo del DIV con el mensaje de confirmación</li>
  </ol>
</details>

## Ejercicio 2

Modifica tu script para que, en el caso que el mail introducido este contenido en la variable _registeredEmails_ , todo funciona igual que en el Ejercicio 1, pero además, el texto que debe aparecer es otro: 'El usuario con el email {el email que ha introducido el usuaroi} ya existe en nuestro sistema.'

¿Cómo obtener el valor de un objeto de tipo _input_? : https://www.w3schools.com/jsref/prop_text_value.asp

# ping-single-column-exercise-js-main
