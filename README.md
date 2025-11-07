# Alura Store

<img src='https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54'> ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)

Análisis de caso hipotético en el que se evalúa el rendimiento de cuatro tiendas para determinar cuál debería venderse.  

## 📄 Proceso
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

<figure style="text-align:center;">
  <img src="https://i.imgur.com/qOvwGoD.jpeg" alt="Tabla_muestra"/>
  <figcaption><u>Tabla muestra.</u></figcaption>
</figure>

## 🔍 Análisis
Dentro de los datos analizados, se realiza el cálculo de la facturación total, promedio del costo de envío, promedio de las calificaciones de los productos, top de categorías más vendidas y productos más y menos vendidos.  

Estas tablas se encuentran ya definidas en el proceso de análisis.  

## 📊 Informe y gráficas
En el segundo título dentro del índice del notebook, se encuentra el informe donde se abordan las razones sobre que tienda se tiene que vender, además de mostrar la información con distintas gráficas por medio de la librería Matplotlib. También, al final del informe, se coloca un mapa interactivo por medio de Folium para mostrar los distintos puntos en donde los productos fueron entregados.

<figure style="text-align:center;">
  <img src="https://i.imgur.com/HyqqDGw.jpeg" alt="Gráfica_pastel"/>
  <figcaption><u>Facturación total de las 4 tiendas.</u></figcaption>
</figure>  
<br>
<figure style="text-align:center;">
  <img src="https://i.imgur.com/FDfEt4X.jpeg" alt="Gráfica_horizontal"/>
  <figcaption><u>Calificación promedio de cada tienda.</u></figcaption>
</figure>  
<br>
<figure style="text-align:center;">
  <img src="https://i.imgur.com/0AKRjul.jpeg" alt="Gráfica_grupo"/>
  <figcaption><u>Ventas de todas las categorías en cada tienda.</u></figcaption>
</figure>  
<br>
<figure style="text-align:center;">
  <img src="https://i.imgur.com/e93giOI.jpeg" alt="Mapa_interactivo"/>
  <figcaption><u>Ubicaciones de las entregas realizadas.</u></figcaption>
</figure>  
<br>
Al final del análisis se ha decidido que la tienda que se debería vender, es la número 4, debido a su baja facturación e indicadores menores. Esto se encuentra detallado en el informe dentro del notebook.
