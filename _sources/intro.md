# 1. Introducción

Nos encontramos con un dataset que contiene información de ventas de casas, donde se incluye el precio de venta, información relacionada a la venta como el año y la condición y características de cada casa como el area del lote, forma del lote, entre otras.

Este dataset contiene 2930 observaciones y 82 variables que se refieren a aspectos de diversa índole, de tipo estructural (tamaño, antiguedad, materiales), de calidad  (acabados interiores/exteriores), ubicación (vecindario, zonificación), y condiciones de venta. Todo esto de casas de la ciudad Ames, Iowa (EE.UU.), durante el periodo de 2006-2010.

Mediante la información de este dataset, se puede obtener las variables que pueden ser relevante al precio de venta de forma que, tanto vendedores como compradores, puedan hacer un estimado del valor esperado de venta de una determinada casa, para tomar decisiones mejor informadas en este tipo de transacciones comerciales.

## 1.1 Preguntas de Investigación

En base a lo expùesto anteriormente, se realizan las siguientes preguntas:
- ¿Cuales son las variables más relevante para determinar el precio de venta de una casa?
- ¿Son estás variables predictores rigurosos, es decir, su coeficiente afecta significativamente el precio de venta?

## 1.2 Objetivos
### 1.2.1 Objetivo General
El objetivo de este proyecto será dar una respuesta a las preguntas de investigación, elaborando un modelo de regresión lineal que nos permita hacer predicciones sobre el comportamiento del precio de casas similares, usando como base el material compartido en clase y el conocimiento adquirido a lo largo de la maestría.

### 1.2.2 Objetivos Específicos
* Depurar y preparar los datos utilizando herramientas de limpieza de datos en el lenguaje de programación Python.
* Realizar análisis exploratorio de los datos para sacar conclusiones.
* Realizar un módelo de regresión lineal utilizando la forma matricial de mínimos cuadrados.
* Realizar inferencias sobre el módelo obtenido.
* Evaluar los supuestos necesarios para la realización de inferencias en módelo lineal de mínimos cuadrados.
* Análizar cambios en los resultados tras utilizar métodos más robustos para la presencia de heterocedasticidad.
* Comparar resultados de módelos más compleajos utilizando Ridge y Lasso.
* Seleccionar un modelo en base los resultados obtenidos.
