<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 5

<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto

**Objetivo:**

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

**Instrucciones:**

- Crear un nuevo documento HTML.
- Crear un formulario con los siguientes campos:

  - Nombre del producto
  - Cantidad
  - Precio unitario
  - Precio total
  - Dirección de envío

- Información de contacto (nombre, correo electrónico, número de teléfono)

- Agregar los siguientes campos relacionados al formulario:

- Método de pago
- Fecha de entrega
- Comentarios

- Utilizar las etiquetas HTML apropiados para cada campo.

### Solucion:
 ```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario pedido de productos</title>
    <style>
        form{text-align: center;
             border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
            background-color: #307c6d;}
       
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
       
    </style>
</head>
<body>
    <form action="" method="">
        <header>
            <h1>Formato para pedido de productos</h1>
        </header>
        <div>
            <label for="idnomproducto">Nombre del producto</label><br>
            <input type="text" id="idnomproducto" name="nproducto" placeholder="Nombre del producto" required>
        </div>
        <br>
        <div>
            <label for="idcantidad">Cantidad</label><br>
            <input type="number" id="idcantidad" name="cantidad" placeholder="Cantidad" required>
        </div>
        <br>
        <div>
            <label for="Idpunitario">Precio unitario</label><br>
            <input type="number" id="Idpunitario" name="precio_unitario" placeholder="Valor unitario">
        </div>
        <br>
        <div>
            <label for="Idptotal">Precio total</label><br>
            <input type="number" id="Idptotal" name="precio_total" placeholder="Valor total">
        </div>
        <br>
        <div>
            <label for="Iddireccion">Direccion de envio</label><br>
            <input type="text" id="Iddireccion" name="direccion"required placeholder="Direccion">
        </div>
        <br>
        <h2>Informacion de contacto</h2>
        <div>
            <label for="idnombre">Nombre</label><br>
            <input type="text" id="idnombre" name="nombre"required placeholder="Ingresa su nombre">
        </div>
        <br>      
        <div>
            <label for="idcorreo">Correo electronico</label><br>
            <input type="email" id="idcorreo" name="correo"required placeholder="Ingresa su correo electronico">
        </div>
        <br>
        <div>
            <label for="idnumero">Numero de telefono</label><br>
            <input type="number" id="idnumero" name="numero" placeholder="Numero de celular">

        </div>
        <br>
        <div>
        <label for="idforpago">Formas de pago</label><br>
        <select name="Forma_pago" id="idforpago"required>
            <option value="">Targeta debito</option>
            <option value="" selected>Targeta credito</option>
            <option value="">PSE</option>
          </select>
        </div>
          <br>
          <div>
            <label for="idfentrega">Fecha de entrega</label><br>
            <input type="datetime-local" id="idfentrega" name="fecha_entrega" required>
          </div>
          <br>
          <div>
            <label for="idcomentarios">Comentarios</label><br>
            <textarea name="" id="idcomentarios" cols="30" rows="10" placeholder="Si tienes alguna sugerencia sobre nuestros productos."></textarea>
          </div>
          <br>
          <div>
            <button type="submit" id="idenviar" value="Enviar">Enviar</button>
          </div>

    </form>
    <footer >
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
