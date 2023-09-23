<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->
# Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

**Pasos:**

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado `<header>`
- Tres párrafos `<p>`
- Una imagen `<img>`
- Un pie de página `<footer>`
- Aplica los siguientes estilos usando - selectores de etiqueta:

Color rojo a los encabezados `<h1>`
Color azul a los párrafos `<p>`
Borde grueso negro a la imagen `<img>`

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"
. Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un `<div>`
- Centrar el contenido de la sección `<section>`

## Solucion:
Pagina index.html con css incopardo:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>estilos css</title>
    <link rel="stylesheet" href="index.css">
    <style>
       section{text-align: center;}
    </style>
</head>
<body background="color">
    <section>
    <header style="background-color: rgba(128, 128, 128, 0.726); top: 0%;left: 0%;"  >
    <h1 style="text-decoration: underline;">Historia y símbolos de Medellín</h1>
    <h2 id="principal">El potencial del valle es descubierto</h2>
</header >
<p class="grande">La ciudad de la eterna primavera fue fundada en 1675. Sin embargo, para que esto se lograra, tuvieron que suceder varios acontecimientos. Es necesario remontarse hasta agosto de 1541, el año en el que el valle donde actualmente se asienta Medellín, fue visto por los españoles por primera vez. Venían en una expedición al mando de Jerónimo Luis Téjelo, quien a su vez obedecía órdenes del Mariscal Jorge Robledo, en búsqueda de tierras y riquezas de oro.</p>
<div style="background-color: rgb(228, 223, 223);">
<p class="grande">En un principio estaba Santa Fe, nombrada capital de la provincia de Antioquia. Con el paso del tiempo, varios pobladores de este lugar, atraídos por los descubrimientos hídricos y mineros, se empezaron a trasladar hacia el valle. Esto despertó cierto recelo por parte de Santa Fe, pues se temía que, con una nueva población cercana, tuvieran que enfrentarse a fenómenos de empobrecimiento y despoblación.</p>
</div>

<p class="grande">A pesar de esto, en 1616, Herrero Campuzano fundó el poblado de San Lorenzo de Aburrá uno de los siete nuevos resguardos indígenas de la región, ubicado entre las quebradas La Poblada y La Presidenta. Una Cédula Real de la Reina Mariana de Austria, en 1674, le otorga el título de Villa y es así como llegado el 2 de noviembre de 1675, se establece la Villa de Nuestra Señora de la Candelaria de Medellín.</p>

<img src="https://firebasestorage.googleapis.com/v0/b/logica-de-progrmacion.appspot.com/o/plaza-berrio-1980.jpg?alt=media&token=c5b09c5d-3765-47df-b3ee-72becb33e6d2" alt="foto plaza de plaza-berrio-1980" id="sombras">

<footer class="destacado" style="background-color: black;">
    Nombre Completo
        <br><br>
        Juan camilo hernandez lopera
        <br><br>
        CESDE
        <br>
        <br>
        &copy;2023
</footer>
</section>
    
</body>
</html>
```

Pagina de index.css para darle estilo a la pagina principal:

```css
h1{
    color: red;
    font-size: 2.7em;
}
p{
    color: blue;
}
img{
    border: black 10px solid;
}
.destacado{
    color: green;
}
.grande{
    font-size: 1.9em;
}
#principal{
    color: yellow;
}
#sombras{
box-shadow: 5px 6px 70px rgb(199, 190, 190);

}
body{
    background-color: rgb(95, 196, 187);
}
```






