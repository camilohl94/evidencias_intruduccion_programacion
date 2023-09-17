<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 2

<!-- Su documentación aquí -->

# Actividad: Creando mi primer sitio web

Crea un sitio web
compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

## Soloucion:

### index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi primer sitio web</title>
  </head>

  <body>
    <header>
      <h1>
        <i><u>Mi Mundo Verde</u></i>
      </h1>
    </header>
    <nav>
      <a href="about.html">Acerca</a>
      <a href="contact.html">contacto</a>
    </nav>
    <main>
      <p>
        Bienvenido a la mejor plataforma de reciclje
        <strong>ayudanos a contruir un mundo mejor </strong>
      </p>
      <p>Aqui encontraras informacion sobre nuestro servicios y productos</p>
      <p>
        El reciclaje es un proceso cuyo objetivo es convertir residuos sssssen
        nuevos productos o en materia prima para su posterior utilización. Se
        previene el desuso de materiales potencialmente útiles, se reduce el
        consumo de nueva materia prima y el uso de energía. Adicionalmente, se
        previene la contaminación del aire
      </p>
    </main>
    <h2><i>Materiales Reciclables</i></h2>
    <ol>
      <li>Botellas de plastico</li>
      <li>Las bolsas de patatas.</li>
      <li>Tapas y tapones de plástico.</li>
    </ol>
    <h2><i>Materiales No Reciclables</i></h2>
    <ul>
      <li>servilletas y papel higiénico.</li>
      <li>latas oxidadas</li>
      <li>Papeles plastificados</li>
    </ul>
    <footer>
      <p>Copyright 2023 - Camilo Hernandez</p>
      <p>juancamilohernandezhl@gmail.com</p>
    </footer>
  </body>
</html>
```

### about.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sobre nosotros</title>
  </head>

  <body>
    <header>
      <h1>Sobre Nosotros</h1>
    </header>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="contact.html">Contacto</a>
    </nav>
    <br />
    <section>
      <h2>historia</h2>
      <p>
        plataforma digital fundada en el 2023 con el fin de educar al mundo
        sobre el tema del reciclaje con la meta de contruir un mundo mejor.
      </p>
      <article>
        <h3>mision y Vision</h3>
        <p>
          Ser una empresa consolidada en el mercado digital en el área de
          reciclaje ampliando nuestra gama de servicios y productos, cuidando
          nuestro entorno ecológico a través de nuestro personal calificado.
        </p>
      </article>
    </section>
    <footer>
      <p>Copyright 2023 - Camilo Hernandez</p>
    </footer>
  </body>
</html>
```

### contact.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Contacto</title>
  </head>

  <body>
    <header>
      <h1>Contacto</h1>
    </header>
    <nav>
      <a href="index.html">Inicio </a>
      <a href="about.html">Acerca</a>
    </nav>
    <br />
    <main>
      <form>
        <label for="Nombre">Primer Nombre:</label>
        <input type="text" id="Nombre" /><br />

        <label for="Nombre">Segundo Nombre:</label>
        <input type="text" id="Nombre" /><br />

        <label for="Nombre">Primer Apellido:</label>
        <input type="text" id="Nombre" /><br />

        <label for="Nombre"> Segundo Apellido:</label>
        <input type="text" id="Nombre" /><br />

        <label for="email">Email:</label>
        <input type="email" id="email" /><br />

        <label for="mensaje">Mensaje</label><br />
        <textarea id="mensaje"></textarea><br />

        <input type="submit" value="Enviar" />
      </form>
      <aside>
        <h3>Ubicacion</h3>
        <p>calle Falsa 123</p>
      </aside>
    </main>
    <footer>
      <p>Copyright 2023 - Camilo Hernandez</p>
    </footer>
  </body>
</html>
```
