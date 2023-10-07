<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->
# Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

**Instrucciones:**

Crea un nuevo archivo HTML y CSS.


En el archivo HTML, crea una estructura básica de página web con dos elementos div.
En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.
Ejemplo:
```java
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

**Preguntas:**

1. ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
2. ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

# Solucion:
Documento html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="elemento1"></div>
    
    <div class="elemento2"></div>
</body>
</html>
```
Documento css:
```css
.elemento1{
    
    position: absolute;
    width: 400px;
    height: 400px;
    top: 200px;
   left: 200px;
    background-color: red;
}
.elemento2{  
    position: relative;
    width: 400px;
   height: 400px;
   top: 200px;
   left: 200px;
    background-color:green;

}
```
imagen del resultado:
![imagen de position absolute, relative](https://firebasestorage.googleapis.com/v0/b/logica-de-progrmacion.appspot.com/o/position%20abre.png?alt=media&token=0e24ddb3-2aa9-4f0b-b6f8-92217afbacf2&_gl=1*ev0bpm*_ga*MTMwNzIxNTExNS4xNjk0OTE0Mjc3*_ga_CW55HF8NVT*MTY5NjY5OTI0Ny4xMS4xLjE2OTY2OTk1MTAuMzMuMC4w)


## Solucion a las preguntas.

1. La diferencia es que la position absolute posiciona un elemento en relación con un ancestro posicionado o el viewport, y saca al elemento del flujo normal del documento, no afectando la posición de otros elementos.
mientaras que la position  relative posiciona un elemento en relación con su posición normal en el flujo del documento, sin sacarlo de este, lo que significa que sigue ocupando espacio y puede ser desplazado sin afectar a otros elementos.
2. la propiedad  z-index  se puede usar para controlar el orden de apilamiento de elementos posicionados asignando valores numéricos positivos o negativos a esta propiedad. Los elementos con valores más altos se superpondrán a los elementos con valores más bajos en el mismo contexto de ancestro posicionado.
3. La propiedad display en CSS se utiliza para controlar cómo se muestra un elemento en una página web. se pueden  aplicar diferentes valores a display según cómo se desee.
**display: block;:** Este valor hace que el elemento se comporte como un bloque. Ocupará todo el ancho disponible y comenzará en una nueva línea. Es útil para elementos como párrafos, encabezados y divs..

**display: inline;:** Con este valor, el elemento se comportará como un elemento en línea, ocupando solo el espacio necesario y permitiendo que otros elementos compartan la misma línea. Es útil para elementos de texto, como enlaces o span.

**display: inline-block;:** Combina las propiedades de block e inline. El elemento ocupa solo el espacio necesario pero permite definir dimensiones y márgenes como si fuera un bloque en línea. Puede ser útil para crear elementos en línea que necesitan algún control de diseño adicional.

**display: none;:** Con este valor, el elemento se oculta por completo, no ocupará espacio en la página y no será visible para el usuario.

**display: flex;:** Transforma al elemento en un contenedor flexible, lo que permite organizar los elementos secundarios (hijos) de manera más flexible en filas o columnas. Es útil para crear diseños flexibles y alineados.

**display: grid;:** Convierte al elemento en un contenedor de cuadrícula, facilitando la creación de diseños de cuadrícula complejos y controlados.


