# Alura Store

<img src='https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54'>  

Análisis de caso hipotético en el que se evalúa el rendimiento de cuatro tiendas para determinar cuál debería venderse.  

## Proceso
El análisis se inicia con información dummy compartida en los enlaces dentro del notebook. Esta información se divide en las siguientes columnas.
* Categoría del producto: la categoría o departamento del producto _(object)_.
* Precio: precio en el que se vendió el producto _(float64)_.
* Costo de envío: el precio generado por el envío del producto _(float64)_.
* Fecha de Compra: día de la compra _(object)_.
* Vendedor: nombre del vendedor _(object)_.
* Lugar de compra: lugar donde se envío el producto _(object)_.
* Calificación: calificación dada por el cliente al recibir el producto _(int64)_.
* Método de pago: metodo de pago del cliente _(object)_.
* Cantidad de cuotas: mensualidades (cuotas) en las que el cliente pagará el producto _(object)_.
* lat: latitud donde se entregó el producto _(object)_.
* lon: longitud donde se entregó el producto _(object)_.

#### Tabla muestra

<div align="center">
  <img src="https://i.imgur.com/qOvwGoD.jpeg" alt="Tabla_muestra"/>
</div>

## Análisis
Dentro de los datos analizados, se realiza el cálculo de la facturación total, promedio del costo de envío, promedio de las calificaciones de los productos, top de categorías más vendidas y productos más y menos vendidos.  

Estas tablas se encuentran ya definidas en el proceso de análisis.  

## Informe y gráficas
En el segundo título dentro del índice del notebook, se encuentra el informe donde se abordan las razones sobre que tienda se tiene que vender, además de mostrar la información con distintas gráficas por medio de la librería Matplotlib. También, al final del informe, se coloca un mapa interactivo por medio de Folium para mostrar los distintos puntos en donde los productos fueron entregados.

<div align="center">
  <img src="https://i.imgur.com/HyqqDGw.jpeg" alt="Gráfica_pastel"/>
</div>  

<div align="center">
  <img src="https://i.imgur.com/FDfEt4X.jpeg" alt="Gráfica_horizontal"/>
</div>  

<div align="center">
  <img src="https://i.imgur.com/0AKRjul.jpeg" alt="Gráfica_grupo"/>
</div>  

<div align="center">
  <img src="https://i.imgur.com/e93giOI.jpeg" alt="Mapa_interactivo"/>
</div>

Al final del análisis se ha decidido que la tienda que se debería vender, es la número 4, debido a su baja facturación e indicadores menores. Esto se encuentra detallado en el informe dentro del notebook.
