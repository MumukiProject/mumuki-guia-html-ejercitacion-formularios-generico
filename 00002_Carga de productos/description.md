Crearemos un formulario para la carga rápida de productos para una empresa de bicicletas :bike:. Para eso mostraremos los siguientes campos:

- Título de producto (input de texto)
- Marca (`select` con `options`):
  - _Klatter_
  - _Top Mega_
  - _Fierce_
  - _Shimano_
  - _Lamborghini_
  - _Aurora_
  - _GT_
- Rodado (input numérico)
- Categoría de producto (radio button):
  - _Mountain Bike_
  - _Paseo_
  - _Plegable_
  - _Carrera_
- Descripción del producto (`textarea`)
- Botón que diga _Cargar_ (de tipo `submit`)

:warning: Considerá que tanto el `select` como los `radio` deben tener un id y el atributo `value` con el mismo valor que tienen en el texto. Por ejemplo, si tuviésemos un `radio` para seleccionar turnos se podría hacer:

`<input type="radio" name="turno" value="Tarde" id= "Tarde"> Tarde`

**No es necesario agregarles estilos**

> Creá el código HTML que acabamos de describir.
