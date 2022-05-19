Necesitamos crear un formulario para el registro rápido del portal web de un cliente, el mismo debe tener los siguientes campos:

- Nombre
- Apellido
- DNI
- Email
- Contraseña
- Términos y condiciones de uso

Cada input deberá tener:

- su correspondiente `label` y debe ser del tipo adecuado;
- un `placeholder` que con un ejemplo del lo que se espera que se complete en dicho `input`. Por ejemplo, el `placeholder` para `email` puede ser `adalovelace@gmail.com`;
- un id con el mismo nombre del campo por ejemplo `id= "Nombre"`

:warning: Consideraciones:

- para el input de DNI nos aseguraremos que solo puedan ingresar números. En esta oportunidad solo se podrán registrar un DNI Argentino por lo que su máximo será de 8 caracteres.
- la contraseña debe ser mayor a 8 caracteres pero no puede exceder los 16.
- se debe colocar un check para aceptar los términos de uso de el portal.

**No es necesario agregarles estilos**

> Creá el código HTML que acabamos de describir.