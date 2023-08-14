# Análisis de datos para la optimización de producción en CEMEX

El objetivo de este proyecto es encontrar la combinación óptima de dos tipos de maquinarias para la producción de un día de soportes metálicos en CEMEX, de tal forma que se minimice el gasto energético. Como acercamiento de solución, se espera producir un modelo de regresión. Fue elaborado durante la clase de 2021 "Análisis de Ciencia de Datos" del Tecnológico de Monterrey.

## Contenidos 

El archivo [**datos.tec**](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/datos_tec.csv) contiene los datos utilizados, fueron provistos por CEMEX y por temas de privacidad no son los datos originales de la problemática. Lo anterior no es relevante puesto que se espera que la solución aplique de la misma forma para los datos reales.

En el documento [**Optimización_de_escenarios_de_producción.pdf**](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/Optimizaci_n_de_escenarios_de_producci_n.pdf) se elabora en la metodología del proyecto, incluyendo el entendimiento del negocio, el entendimiento de los datos, la preparación de datos, el modelado, la evaluación de modelos y el despliegue. 

Puede verse más información sobre el despliegue en el documento [*Aplicación Web en Flask.pdf*](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/Aplicaci%C3%B3n%20Web%20en%20Flask.pdf), que es en esencia una página web que recibe los parámetros de las características de los soportes y regresa la combinación óptima de maquinaria. Todo el código de dicha aplicación se encuentra en la carpeta [**WebApp**](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/tree/main/WebApp). Para una guía audiovisual, el [**Video explicativo**](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/Video%20Explicativo.mp4) resume el proyecto en 5 minutos. 

Finalmente en el cuaderno [optimizacion_produccion](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/optimizacion_produccion.ipynb) se encuentra el código del trabajo y en el [*Anexo código del reto*](https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/Anexo%20c%C3%B3digo%20del%20reto.pdf) una versión en pdf.

## Resumen de resultados

Se logró proponer una solución utilizando el modelo regresor random forest. Dicho modelo entrega la combinación de maquinaria óptima según los valores de duerza, calidad y tasa de producción de los soportes, y se encuentra en una aplicación web dinámica y fácil de usar. Al comparar la propuesta con los datos históricos se obtiene que el regresor ahorraría en promedio 18.5 unidades de costo por día. 

<p align="center">
  <img src="https://github.com/ShoyChoy/analisis-datos-optimizacion-produccion/blob/main/Aplicacion%20Web.jpg" />
</p>

