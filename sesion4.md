<!-- No borrar o modificar -->

[Inicio](./index.md)

## Sesión 4

<!-- Su documentación aquí -->

# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.
![Imagen de una tabla](https://firebasestorage.googleapis.com/v0/b/cesde-7fe22.appspot.com/o/IP%2FIPS4-1.png?alt=media&token=b46ee6fd-97c8-400e-af16-cc88c3819d00)

## Solucion:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tablas en html5</title>

    <style>
      /* Estilos generales */

      h1 {
        text-align: center;
        font-size: 24px;
        font-weight: bold;
        margin-top: 40px;
        margin-bottom: 10px;
        color: white;
      }

      tr {
        text-align: center;
      }

      footer {
        background-color: #333;
        color: white;
        padding: 20px;
        text-align: center;
      }

      section {
        border: 1px solid #ddd;
        padding: 20px;
        margin-bottom: 20px;
        background-color: #f5f8f8;
      }
      div {
        border: 1px solid #ddd;
        padding: 20px;
        margin-bottom: 20px;
        background-color: #cac8c8e5;
      }
    </style>
  </head>

  <body>
    <div>
      <h1>Tablas en HTML5</h1>
    </div>

    <section>
      <table border="3" cellpadding="2" cellspacing="1">
        <thead>
          <tr>
            <th colspan="6">Base de datos motos Yamaha</th>
          </tr>
          <tr>
            <th>Codigo</th>
            <th>Nombre</th>
            <th>Descripcion</th>
            <th>Precio</th>
            <th>Stock</th>
            <th>Fecha de crecion</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td rowspan="2">1040</td>
            <td rowspan="2">XTZ 125</td>
            <td>
              La XTZ 125, con el diseño y confort que sólo puede entregarte una
              moto de verdad, tiene encendido eléctrico para una mayor
              comodidad. Sus gráficos y colores la hacen más deportiva.
            </td>
            <td>10.500.000$</td>
            <td>100</td>
            <td>22-08-2023</td>
          </tr>
          <tr>
            <td>
              Con motor 4 tiempos, balanceador de cigüeñal, el cual evita
              vibraciones en el motor y SOHC que genera menor ruido y es más
              eficiente. Suspensión trasera monocross para mayor confort en
              terrenos destapados.para mayor confort en terrenos destapados.
            </td>
            <td>2625 USD</td>
          </tr>

          <tr>
            <td rowspan="2">1041</td>
            <td rowspan="2">XTZ 150</td>
            <td>
              El modelo llega con un carácter utilitario-deportivo, cómodo y
              agresivo.
            </td>
            <td>12.900.000$</td>
            <td>75</td>
            <td>23-08-2023</td>
          </tr>
          <tr>
            <td>
              El asiento biplaza está diseñado para garantizar una buena
              sensación para el piloto y una mayor comodidad para el pasajero,
              el asiento trasero es 95 mm más alto que el asiento del conductor
              para proporcionarle al pasajero una buena visibilidad hacia
              adelante.
            </td>
            <td>3225 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1042</td>
            <td rowspan="2">XTZ 250</td>
            <td>
              La XTZ 250 posee un motor de 249 cc, 4 tiempos, un cilindro, SOHC
              refrigerado por aire y aceite, el cual alcanza 20,7 HP a 8.000 rpm
              y 20,5 Nm de torque a 6.500 rpm.
            </td>
            <td>25.500.000$</td>
            <td>30</td>
            <td>24-08-2023</td>
          </tr>
          <tr>
            <td>
              Adopta un pistón liviano de aluminio forjado y un cilindro con
              recubrimiento plateado que permite una óptima disipación de calor.
              Además, incorpora un balanceador para reducir las vibraciones
              percibidas por el conductor.
            </td>
            <td>6375 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1043</td>
            <td rowspan="2">SZ-RR</td>
            <td>
              La nueva SZ-RR llega con un nuevo concepto de desarrollo. Su motor
              cuenta con la tecnología Blue Core que le permite tener mayor
              eficiencia de combustible y una relación amigable con el medio
              ambiente.
            </td>
            <td>9.500.000$</td>
            <td>120</td>
            <td>25-08-2023</td>
          </tr>
          <tr>
            <td>
              Con la nueva tecnología en motores Yamaha, mejor eficiencia de
              combustible, nuevo diseño de tablero y los comandos del manubrio
              característicos de otros modelos como la FZ, la SZ-RR se convierte
              en un modelo completo que satisface todas tus necesidades.
            </td>
            <td>2375 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1044</td>
            <td rowspan="2">FZ-S 2.0</td>
            <td>
              La FZ versión 2.0 es una evolución, no solo en desempeño, sino
              también en diseño y tecnología gracias a su motor con filosofía de
              diseño BLUE CORE, Inyección electrónica y Euro3.
            </td>
            <td>10.600.000$</td>
            <td>90</td>
            <td>26-08-2023</td>
          </tr>
          <tr>
            <td>
              El motor de la FZ versión 2.0 se destaca por su respuesta
              inmediata al acelerar, al arrancar o al adelantar, brindando
              seguridad en su conducción. Es un motor 4 tiempos SOHC,
              refrigerado por aire, 149 c.c., su desempeño, diseño, tecnología y
              potencia son los beneficios que nos permitirán disfrutar de esta
              gran moto.
            </td>
            <td>2650 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1045</td>
            <td rowspan="2">FZ- 250</td>
            <td>
              La Yamaha FZ25 es una motocicleta llena de tecnología para que
              disfrutes en el día a día:
            </td>
            <td>15.450.000$</td>
            <td>20</td>
            <td>27-08-2023</td>
          </tr>
          <tr>
            <td>
              motor liviano Blue Core con recubrimiento de níquel, inyección
              electrónica, chasis tipo diamante, luces LED (principal y stop),
              doble freno de disco con ABS, tablero digital y suspensión mono
              cross para mayor estabilidad.
            </td>
            <td>3862 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1046</td>
            <td rowspan="2">SUPER TENERÉ 1200ZE</td>
            <td>
              Queríamos crear la motocicleta de aventuras inteligente.
              Comenzamos con un motor potente, con 2 cilindros en línea y un
              cigüeñal de 270 grados para entregar una respuesta excelente en el
              acelerador.
            </td>
            <td>80.000.000$</td>
            <td>5</td>
            <td>28-08-2023</td>
          </tr>
          <tr>
            <td>
              El resultado fue una motocicleta compacta y estrecha, que se mueve
              ágil y fácilmente en cualquier circunstancia.
            </td>
            <td>20.000 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1047</td>
            <td rowspan="2">XSR900</td>
            <td>
              Esta motocicleta cuenta con un motor en V (bicilíndrico) a 60
              grados, de 942 cc, cuatro válvulas, refrigerado por aire e
              inyección electrónica. Además tiene un tubo de escape del cilindro
              trasero hacia la parte frontal, un filtro de aire compacto, un
              catalizador de tres vías, tipo panal y sensor de oxígeno.
            </td>
            <td>59.000.000$</td>
            <td>8</td>
            <td>29-08-2023</td>
          </tr>
          <tr>
            <td>
              La Bolt combina todos estos atributos en un diseño retro, que te
              permiten hacer realidad el placer de disfrutar la potencia en cada
              salida.
            </td>
            <td>14.750 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1048</td>
            <td rowspan="2">NMAX-CONNECTED</td>
            <td>
              Confía en su motor de 155 cc, 4 tiempos, 4 válvulas, refrigeración
              líquida e inyección electrónica, que entrega 15.15 HP a 8000 rpm y
              13.9 Nm a 6500 rpm.
            </td>
            <td>16.100.000$</td>
            <td>167</td>
            <td>30-08-2023</td>
          </tr>
          <tr>
            <td>
              Mantiene el sistema de válvulas de apertura variable (VVA) que le
              da ese rendimiento sobresaliente en todo el rango de revoluciones.
            </td>
            <td>4.025 USD</td>
          </tr>
          <tr>
            <td rowspan="2">1049</td>
            <td rowspan="2">R1</td>
            <td>
              Con la tecnología de la YZR-M1 que compite en MotoGP, llega la R1
              de última generación.
            </td>
            <td>100.000.000$</td>
            <td>2</td>
            <td>31-08-2023</td>
          </tr>
          <tr>
            <td>
              Con un nuevo motor crossplane, chasis de corta distancia entre
              ejes y electrónica de alta tecnología, la nueva R1 está lista para
              conectarse a tu cuerpo y llevar tu forma de rodar a un nuevo
              nivel.
            </td>
            <td>25.000 USD</td>
          </tr>
        </tbody>
      </table>
    </section>

    <footer>
      Nombre Completo
      <br /><br />
      Juan camilo hernandez lopera
      <br /><br />
      CESDE
      <br />
      <br />
      &copy;2023
    </footer>
  </body>
</html>
```
