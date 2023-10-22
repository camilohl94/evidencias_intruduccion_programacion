<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->
# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11.

## Solucion:
**Codigo html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesion11</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="div1">
        <h1>Estilos para la sesion 11</h1>
    </div>
    <div class="div2">
     <img src="fondo de pantalla2.jpg" alt="">   
    </div>
   <p>Este es un ejemplo de pseudoclease con parrafo en el que la letras se agrandan y el fondo cambia</p>
    
   <p class="parrafo1">Este es un ejemplo de un pseudoelemento </p>
</body>
</html>
```

**Codigo css**
```css
.div1{
    width: 100%;
    height: 100px;
    padding: 10px;
    margin: 10px;
    position: static;
    color: green;
    text-align: center;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 20px;
    background-image: url(https://th.bing.com/th/id/R.ee26380eda18647b49cee8a240ebdb84?rik=m%2bSofJ%2bWji5CgQ&riu=http%3a%2f%2fk32.kn3.net%2ftaringa%2fA%2fF%2fB%2fA%2f2%2f7%2fgonzaa9614%2f56E.jpg&ehk=zQGs%2b3pRnhydM03%2bA34Yo%2fWx2kmz6%2fYmgD3tNFhFyvI%3d&risl=&pid=ImgRaw&r=0);

}
.div1:hover{
    background-image: url(https://th.bing.com/th/id/R.4a30ce87e18acb3fa0c08a028315892b?rik=0O8uMm5jIJ1mMg&pid=ImgRaw&r=0);
}
.div2 img{
    border-radius: 10px;
    margin: 10px;
    background-position: center;

}
p{
    font-size: 16px;
    color:black;
}
p:hover{
    background-color: red;
    font-size: 25px;
    text-shadow: 2px 2px 4px forestgreen;
}
.parrafo1::first-letter {
    font-weight: bold;
    color: rgb(117, 20, 220);
    font-size: 60px;
    
}

```






