#### Pantalla Elevation General View

##### Pantalla Elevation General View -- Current Move

Esta pantalla muestra y permite controlar los aspectos generales de elevación.

![Pantalla elevation general view - current move](../Resources/media/image23.png)

*Figura 2‑16. Pantalla elevation general view - current move.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPCIÓN</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td><p>Muestra el estado, la posición (en deg) y el setpoint (en deg) de la elevación.</p>
<p>Muestra el estado de cada motor de elevación y del encoder:</p>
<ul>
<li><p>Rojo: Significa que existe un fallo.</p></li>
<li><p>Verde: Significa que se encuentra encendido.</p></li>
<li><p>Gris: Significa que se encuentra apagado.</p></li>
</ul>
<p>El triángulo naranja junto con el texto “not homed” significa que falta hacer la referencia de los ejes.</p>
<p>Muestra el estado de los límites de recorrido. Siendo los límites de recorrido más restrictivos “opera. +” y “opera.
–”, y los límites de recorrido completo “travel +” y “travel –”. Se ilumina de color verde el recuadro correspondiente
al límite que se activa.</p>
<p>Muestra si el freno está activado o no. Representado mediante un recuadro rojo la opción “Engaged” cuando lo esté, o
con un recuadro verde en “Released” cuando no lo esté.</p>
<p>Se visualiza un gráfico con la posición y velocidad en tiempo real.</p>
<p>Softkey “FREEZE GRAPH”: permite congelar el gráfico.</p>
<p>Softkey “UPDATE GRAPH”: permite actualizar el gráfico, tras haber sido congelado.</p></td>
</tr>
<tr class="even">
<td>2</td>
<td><p>Softkey “ON”: Permite encender el eje, solamente si está en “Idle” y no hay ningún interlock activo.</p>
<p>Softkey “OFF”: Permite apagar el eje.</p>
<p>Softkey “RESET ALARM”: Permite resetear el sistema del estado de alarma en el que se encuentra o resetear el
interlock en caso de haberlo, mientras está en “Idle” para poder hacer “ON”.</p></td>
</tr>
<tr class="odd">
<td>3</td>
<td><p>Permite definir la posición (en deg), velocidad (en deg/s), aceleración (en deg/s<sup>2</sup>) y jerk (en
deg/s<sup>3</sup>) de la elevación.</p>
<p>Softkey “HOME”: Permite buscar la referencia de los ejes.</p>
<p>Softkeys “STOP”: Permiten detener el movimiento de los ejes.</p>
<p>Softkey “MOVE”: Permite realizar el movimiento de los ejes con las especificaciones previamente introducidas.</p>
<p>Softkeys “+” o “-”: Permiten hacer un movimiento a velocidad constante en dirección positiva o negativa
respectivamente. De esta manera, se ajusta el porcentaje de la velocidad por defecto definida en los parámetros con el
slider vertical.</p></td>
</tr>
<tr class="even">
<td>4</td>
<td><p>Permite acceder a la pantalla [“Locking Pins General View”](./004_PantallaLockingPins.md)</p>
<p>Muestra el estado de los pasadores, y activa el led con el color correspondiente:</p>
<ul>
<li><p>“FREE”: Significa que los pasadores se encuentran libres, y se ilumina de color verde.</p></li>
<li><p>“TEST”: Significa que los pasadores se encuentran en test, y se ilumina de color naranja.</p></li>
<li><p>“LOCK”: Significa que los pasadores se encuentran bloqueados, y se ilumina de color rojo.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td>5</td>
<td>Muestra el estado y permite acceder a la pantalla de [“OSS General View”](./008_PantallaOSSGeneralView.md)</td>
</tr>
<tr class="even">
<td>6</td>
<td>Muestra el estado y permite acceder a la pantalla de [“Power SupplyGeneral View”](./018_PantallaPowerSupply.md)</td>
</tr>
<tr class="odd">
<td>7</td>
<td><p>Softkey azul permite navegar entre los interlocks que se encuentran activos, en caso de haber más de uno.</p>
<p>Al haber algún interlock activo, el recuadro superior se visualiza de color rojo. Si no hay interlocks activos, el
recuadro se visualizará en verde y no se podrá pulsar el softkey azul.</p></td>
</tr>
</tbody>
</table>

##### Pantalla Elevation General View -- Move History

Esta pantalla muestra y permite cargar los últimos cinco movimientos de elevación, siendo el número 1 el último.

![Pantalla elevation general view - move history](../Resources/media/image24.png)

*Figura 2‑17. Pantalla elevation general view - move history.*

<table>
<colgroup>
<col style="width: 13%" />
<col style="width: 86%" />
</colgroup>
<thead>
<tr class="header">
<th>ITEM</th>
<th>DESCRIPCIÓN</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>1</td>
<td><p>Softkey “LOAD”: Permite cargar los últimos cinco movimientos.</p>
<p>Tras seleccionar el movimiento deseado, permite visualizarlo en el gráfico.</p></td>
</tr>
</tbody>
</table>
