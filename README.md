# KML_Sales

## Sales by City
Dibuja un polígono de acuerdo a las ventas en una ciudad. Se sacan de la base de datos de Access. 

## Polígono en Baja Californias
Dibuja el área de los estados de Baja California y Baja California Sur. Los datos del área también salen de la base de datos. 

## Rutas
Dibuja rutas muy equis. 

## Consideraciones
El proyecto tiene 4 clases dentro de la carpeta de Utilidades. Las más importantes son:
* GeneraXML.java
* Punto.java
y, por supuesto, el <b>kml.java</b> en src/kml/sales/

El Main de kml.java invoca todos los métodos de las demás clases. Algo que es importante notar es que la clase punto tiene un override de toString()

entonces objetoPunto.toString() se convierte en Lon+","+Lat+","+Alt+" ";



