<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 3

<!-- Su documentación aquí -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

4. Imagenes
5. Videos
6. Audios
7. Inline Frame

- Utiliza encabezados para títulos en cada elemento
  ` (<h1>...<h6>).`

- Crea una descripción para cada elemento utilizando párrafos (`<p>`).

- Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa `<strong>` para resaltar texto importante.
  Utiliza `<br>` para insertar saltos de línea si es necesario.

- Agrega `<span>` para aplicar estilos específicos a porciones de texto.

- Emplea `<i>` para enfatizar o dar énfasis a palabras o frases.

- Utiliza `<u>` para subrayar texto cuando sea necesario.

- Considera el uso de `<div>` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

**Plantilla Inicial**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
      body {
        font-family: Arial, sans-serif;
      }

      header {
        background-color: #333333;
        color: white;
        padding: 20px;
        text-align: center;
      }

      section {
        border: 1px solid #ddd;
        padding: 20px;
        margin-bottom: 20px;
      }

      h2 {
        color: blue;
      }

      footer {
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>

  <body>
    <header>
      <h1>Etiquetas Multimedia HTML5</h1>
      <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
      <h2>Imágenes</h2>
      <p>Contenido sobre imágenes...</p>
    </section>

    <section>
      <h2>Videos</h2>
      <p>Contenido sobre videos...</p>
    </section>

    <section>
      <h2>Audios</h2>
      <p>Contenido sobre audios...</p>
    </section>

    <section>
      <h2>iFrames</h2>
      <p>Contenido sobre iframes...</p>
    </section>

    <footer>
      Nombre Completo
      <br />
      <br />
      CESDE
      <br />
      <br />
      &copy;2023
    </footer>
  </body>
</html>
```

Semántica y Estructura de la Plantilla
El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

`<!DOCTYPE html>`: Esto define el tipo de documento como HTML5.

`<html>`: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

`<head>`: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque `<style>` para agregar reglas de estilo CSS.

`<title>`: Establece el título de la página en la pestaña del navegador.

`<style>`: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

`<body>`: Aquí se coloca el contenido principal visible de la página.

`<header>`: Sección de encabezado que contiene el título principal y un subtítulo.

`<h1> y <h3>`: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

`<section>`: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

`<h2>`: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

`<p>`: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

`<footer>`: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea `<br>` para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.

El encabezado (`<header>`) tiene un fondo oscuro, texto blanco y un espacio de relleno.
Cada sección (`<section`) tiene un borde, un espacio de relleno y un margen inferior.

Los encabezados de nivel 1 y 3 están centrados.
Los encabezados de nivel 2 (`<h2>`) tienen color azul.

El pie de página (`<footer>`) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido.

El estilo CSS proporciona una apariencia visual coherente y agradable.



## **Solucion:**

```html
<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2,h3,h4,h5,h6 {
            color: rgb(117, 212, 70);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Motor</h2>
        <p>Un motor es la parte sistemática de una máquina capaz de hacer funcionar el sistema, transformando algún tipo
            de energía (eléctrica, de combustibles fósiles, etc.), en energía mecánica capaz de realizar un trabajo. <a
                href="http://es.wikipedia.org/wiki/Motor" target="_blank" rel="noopener noreferrer">mas informacion</a>
        </p>
        <img src="Imagen1.webp" alt="Imagen de motor" width="800">

        <h3>Cigueñal</h3>
        <p>Un cigüeñal o cigoña <strong>es un eje acodado con contrapesos</strong> presente en ciertas máquinas que, aplicando el
            principio del mecanismo de biela-manivela, transforma el movimiento rectilíneo alternativo en circular
            uniforme y viceversa. <a href="http://es.wikipedia.org/wiki/Cigüeñal " target="_blank"
                rel="noopener noreferrer">mas informacion</a>
        </p>
        <img src="Imagen2.webp" alt="Imagen de cigueñal" width="800">

        <h4>Piston</h4>
        <p>En los motores de combustión <strong>el pistón es la parte móvil dentro del cilindro</strong> por lo que constituye la pared
            móvil de la cámara de combustión. La función principal del pistón es transmitir la energía de los gases de
            la combustión al cigüeñal mediante un movimiento alternativo dentro del cilindro. <a
                href="http://es.wikipedia.org/wiki/Pistón" target="_blank" rel="noopener noreferrer">Mas informacion</a>
        </p>
        <img src="Imagen3.png" alt="Imagen de piston" width="800">

        <h5>Culata</h5>
        <p>La culata es la pieza que asegura el cierre de los cilindro(s) por su parte superior, y agrupa ciertas
            funciones en un motor de pistón alternativo. En muchos tipos de motores, las válvulas de admisión y de
            escape se alojan aquí. <a href="http://es.wikipedia.org/wiki/Culata_(motor)" target="_blank"
                rel="noopener noreferrer">Mas informacion</a></p>
        <img src="Imagen4.jpg" alt="culata de motor" width="800">




    </section>

    <section>
        <h2>Funcionamiento del motor</h2>
        <p>Un motor es la parte sistemática de una máquina capaz de hacer funcionar el sistema, transformando algún tipo
            de energía (eléctrica, de combustibles fósiles, etc.), en energía mecánica capaz de realizar un trabajo. <a
                href="http://es.wikipedia.org/wiki/Motor" target="_blank" rel="noopener noreferrer">mas informacion</a>
        </p>
        <video src="Video1.mp4" controls></video>

        <h3>Los cuatro tiempos del motor de combustión interna</h3>
        <p>Los motores que dominan el mercado de vehículos particulares son los de cuatro tiempos como lo mencionamos.
           <u> Se les denominan tiempos a las fases mediante las cuales los componentes convierten el combustible en
            energía calórica  luego mecánica para mover al auto.</u> Estas son:

        <h6>Admisión:</h6> En esta fase el pistón se encuentra arriba y las válvulas de admisión se abren para dejar
        entrar la mezcla de combustible que se atrae por vacío a la cámara de combustión a medida que el pistón
        desciende y con la ayuda de los inyectores. <br>
        <h6>Compresión: </h6>Las válvulas se cierran y el pistón empieza a ascender hasta llegar al extremo y
        comprimiendo la mezcla entre aire y gasolina. <br>
        <h6>Explosión:</h6> Con las válvulas cerradas, la cámara de combustión llena de mezcla y el pistón arriba se
        genera una detonación iniciada por una chispa eléctrica producida por la bujía en los motores de gasolina y por
        autodetonación en los motores de diésel. En este punto la fuerza generada por la explosión obliga a bajar al
        pistón. <br>
        <h6>Escape:</h6> en este último momento se abren las válvulas de escape en el motor de combustión interna y los
        gases de producidos en la detonación se evacúan del vehículo empujados por la subida del pistón que queda en
        posición para empezar un nuevo ciclo. <a
            href="http://mitsubishi-motors.com.co/blog/motor-de-combustion-interna-funcionamiento/" target="_blank"
            rel="noopener noreferrer">Mas informacion</a></p>
        <video src="Video2.mp4" controls></video>

    </section>

    <section>
        <h2>sonido del encendido del motor</h2>
        <p>El encendido del motor es un sistema de producción y distribución, en el caso de más de un cilindro, de la
            chispa de alta tensión necesaria en la bujía para producir el encendido provocado en un motor de explosión,
            ya sea de dos tiempos o de cuatro tiempos. <a href="http://es.wikipedia.org/wiki/Encendido_del_motor"
                target="_blank" rel="noopener noreferrer">Mas informacion</a></p>
        <audio src="encendido.mp3" controls></audio>

        <h3>Sonido aceleracion</h3>
        <p>El acelerador es un mecanismo usado en los motores de combustión interna de ciclo Otto mediante el cual se
            regula el flujo de la mezcla aire/combustible en el caso de motores de carburador o del aire en los motores
            de inyección de combustible por medio de constricción y obstrucción del conducto de admisión. <a
                href="http://es.wikipedia.org/wiki/Acelerador" target="_blank" rel="noopener noreferrer">Mas
                informacion</a></p>
        <audio src="aceleracion.mp3" controls></audio>

        <h4>Sonido auto-apagado del motor.</h4>
        <p>Es un sistema que automáticamente apaga el motor cuando el automóvil se frena hasta detenerse, y lo enciende
            de nuevo al momento de quitar el pie del freno. Sin embargo el audio, control de clima y las luces del
            vehículo no se ven afectadas. <a
                href="http://www.pruebaderuta.com/sistema-de-auto-apagado-auto-encendido.php" target="_blank"
                rel="noopener noreferrer">Mas informacion</a></p>
        <audio src="apagado.mp3" controls></audio>

        <h5>Sonido motor tractor</h5>
        <p>El motor de un tractor tiene un uso y funcionamiento distintos al de un auto común. Los caballos de fuerza no
            tienen la misma importancia en un tractor que en un auto, o por lo menos no de la forma en que se relacionan
            usualmente con velocidad y aceleración. En el motor de un tractor tienen como objetivo principal mantener el
            vehículo en movimiento por largas y pesadas jornadas, a una velocidad constante y lenta. <a
                href="http://www.bardahl.com.mx/funciona-motor-tractor/" target="_blank" rel="noopener noreferrer">Mas
                informacion</a></p>
        <audio src="tractor.mp3" controls></audio>



    </section>

    <section>
        <h2>Revista motor</h2>
        <p>Motor es la revista de prensa más leída del país y en muchísimas ocasiones y estudios ha estado por encima de
            todas las generales como las de opinión, farándula, cómics, femeninas o especializadas, y es un comprobado
            “motor”</p>
        <iframe src="https://www.motor.com.co/seccion/revista/" width="1300" height="1000"></iframe>

        <h3>Historia del motor</h3>
        <p>La historia del motor de combustión interna o “a explosión” comienza luego de la invención de la máquina a
            vapor que funcionaba mediante la generación de combustión externa. En cambio, el motor a gasolina obtenía su
            funcionamiento mediante la combustión interna que se da por la mezcla de aire con el combustible.</p>
        <iframe src="https://patiodeautos.com/general/la-historia-del-motor-de-combustion-interna/" width="1300"
            height="1000"></iframe>


    </section>

    <footer>
        Nombre Completo
        <br><br>
        Juan camilo hernandez lopera
        <br><br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```
