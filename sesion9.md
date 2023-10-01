<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->
# Actividad: Propiedades de espaciado y unidades de medida
**Objetivo:** 

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:
```html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

En el archivo CSS, agrega el siguiente código:
```css
.contenedor
 {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```
Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

Practicar el uso de las propiedades de espaciado.

Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
```css
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
```css
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
Border: Agrega un borde de 5 píxeles de color rojo.
```css
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```

Border-radius: Agrega un radio de esquina de 10 píxeles.

```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}
```
Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
```css
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```
Preguntas:
¿Qué es la propiedad margin?
¿Qué es la propiedad padding?
¿Qué es la propiedad border?
¿Qué es la propiedad border-radius?
¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?

# Solucion:
* inserto imagen de como quedo la pagina aplicando distintas unidades de medida y el codigo.

index.html
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```
style.css
```css
.contenedor {
  width: 200px;
  height: 200px;
  background-color: dimgrey;
}
.elemento {
  width: 100px;
  height: 100px;
  margin: 20px;
  background-color: steelblue;
  padding: 10px;
  border: 5px solid red;
  border-radius: 10px;
}
```
![imagen de captura pantalla pagina web](https://firebasestorage.googleapis.com/v0/b/logica-de-progrmacion.appspot.com/o/Captura%20de%20pantalla%20(69).png?alt=media&token=7643a1bc-ea93-4c98-9bd2-7d54db81a2e6&_gl=1*177gy1e*_ga*MTMwNzIxNTExNS4xNjk0OTE0Mjc3*_ga_CW55HF8NVT*MTY5NjE3NzY5OC42LjEuMTY5NjE3ODE3NC40LjAuMA..)

## Solucion de la preguntas.

**Margin (Margen):** La propiedad margin en CSS se utiliza para controlar el espacio en blanco alrededor de un elemento en relación con otros elementos en la página. Puedes definir valores positivos o negativos para el margen, estableciendo así la distancia entre el elemento y sus vecinos.

**Padding (Relleno):** La propiedad padding en CSS se utiliza para controlar el espacio en blanco alrededor del contenido dentro de un elemento. Este espacio en blanco se encuentra dentro del borde del elemento y permite separar el contenido de los bordes.

**Border (Borde):** La propiedad border en CSS se utiliza para establecer el borde de un elemento. Puedes especificar el ancho del borde, el estilo (como sólido, punteado, etc.) y el color del borde. Esto ayuda a definir los límites visuales de un elemento.

**Border Radius (Radio del Borde):** La propiedad border-radius en CSS se utiliza para suavizar las esquinas de un elemento, creando bordes redondeados en lugar de esquinas afiladas. Puedes especificar un valor para controlar el radio de curvatura de las esquinas.

**Unidades de Medida para Espaciado:** Las unidades de medida que se pueden utilizar para las propiedades de espaciado incluyen:

*Píxeles (px):* Una unidad de medida fija, adecuada para controlar el espaciado con precisión.
*Porcentajes (%):* Permite establecer el espaciado relativo al tamaño del elemento padre.

*Em (em) y Rem (rem):* Relacionadas con el tamaño del texto, lo que facilita el diseño escalable.

*Puntos (pt), Pulgadas (in), Centímetros (cm), Milímetros (mm):* Unidades de medida absolutas útiles para el espaciado en impresión y diseño detallado.







