# Proyecto-Data-Analysis
Proyecto EDA para el bootcamp de data sicience
# Impacto del turismo en los residentes de Euskadi

Los residentes de las zonas turísticas pueden experimentar efectos positivos y negativos del turismo como un aumento en los servicios y la oferta cultural, pero también problemas el aumento del costo de vida, la generación de empleo de baja
calidad y aumento de emisiones a la atmosfera

## HIPÓTESIS

### PRINCIPAL HIPÓTESIS

> #### El aumento del turismo afecta negativamente a la población de Euskadi

### HIPÓTESIS PARA LA OBTENCIÓN DE DATOS

Para la recolección de datos, se han tenido en cuenta las siguientes hipótesis:

> 1 - Hay un aumento del turismo en Euskadi\
> 2 - Por el aumento del turismo, se incrementa el precio de a vivienda\
> 3 - No es viable para la calidad de vida de los residentes una economia basada en el turismo(sector servicios)\
> 4 - El aumento del turismo afecta a las emisiones de CO2\

### ADQUISICIÓN DE DATOS

La recopilación de datos se ha realizado en las siguientes fuentes
> INE (Instituto Nacionakl de Esradística)\
> EUSTAT (Instituto Vasco de Estadística)\
> SEPE (Servicio Publico de Empleo Estatal)\
> OPEN DATA EUSKADI\
> IDEALISTA\
> OURWORLINDATA\
> STATS OEDC

### LIMPIEZA Y TRATAMIENTO DE DATOS

Para la limpieza y el tratamiento de datos, se ha utilizado Python y las librerias Pandas, Numpy, Sklearn y pickle. Para la visualización de datos se ha utilizado Flourish y para la presentación Canva

#### Resumen de datos

> ## Aumento del turismo en Euskadi

![Turismo Euskadi](./img/Turismo%20en%20euskadi.png)

La gráfica muestra claramente que el turismo en Euskadi estaba en aumento antes de la pandemia y que después de la misma, se han vuelto a alcanzar niveles similares.

> ## Aumento del precio de la vivienda

Comparación de datos con Madrid por su crisis de la vivienda con el aumento del turismo

Precio por m2 en venta

![Precio Venta](./img/Venta.png)

Precio por m2 en alquiler

![Precio alquiler](./img/Alquiler.png)

En los graficos podemos apreciar el crecimiento de precios en alquiler y venta de vivienda tanto en Madrid como en Euskadi.
El aumento puede ser debido a muchas causas, no sólo el aumento del turismo.

> ## No es viable para la calidad de vida de los residentes una economia basada en el turismo(sector servicios)

Para analizar como puede afectar a la calidad de vida se han tenido en cuenta varios factores: 
 - Que días y que temporada del año se trabaja más
 - Como de estable es el empleo en este sector
 - Remuneración media

### ¿Qué días se tarbaja más?

![Pernoctaciones dias de la semana](./img/dias%20semana.png)

Según los datos presentados, se observa que la diferencia en el porcentaje de días trabajados entre los días laborables y los fines de semana es de alrededor del 10%. A partir de esta información, se podría concluir que los horarios de trabajo no están equilibrados para permitir un equilibrio entre la vida laboral y personal.

### ¿Qué periodo del año se trabaja más?

![Entradas durante el año](./img/Entradas%20en%20el%20a%C3%B1o.png)

A partir de la gráfica, se puede observar que este trabajo es altamente estacional, con su pico en la temporada de primavera-verano y una disminución en otras épocas del año. Además, se puede apreciar que durante una crisis, como ocurrió en el 2020, las entradas y el empleo disminuyen significativamente.

### ¿Como evoluciona el paro?

![Evolución del paro](./img/Evolucion%20del%20paro%20por%20sector.png)

La gráfica muestra que el sector de servicios tiene un alto nivel de empleo, sin embargo, también se observa una tendencia de picos en los niveles de empleo que varían a lo largo del tiempo.

### Estabilidad por sector

La variabilidad se puede medir mediante la desviación estándar o la varianza de los valores de empleo en cada sector. Los sectores con una desviación estándar o una varianza más baja tendrán una evolución del empleo más estable.

![STD por sector](./img/Desviacion%20std.png)

Como se mencionó previamente, cuanto mayor sea la desviación estándar, mayor será la inestabilidad en el empleo de un sector. En la gráfica anterior, se observa una tendencia de picos en el sector de servicios, lo que se refleja en una desviación estándar más alta en comparación con los demás sectores.

### Salario medio

![Salario medio](./img/salario%20medio.png)

La gráfica muestra que el salario medio ha experimentado un ligero aumento en el transcurso de varios años, sin embargo, sigue siendo uno de los salarios más bajos en comparación con otros sectores.

> ## El aumento del turismo afecta a las emisiones de CO2

A medida que se intensifican las campañas para reducir los niveles de emisiones en la atmósfera, se están implementando medidas para obstaculizar el uso de vehículos en nuestras actividades diarias, como ir al trabajo o hacer compras. Sin embargo, estas medidas entran en conflicto con las campañas para fomentar el turismo, ya que el aumento del turismo puede resultar en un aumento en el uso de vehículos, como aviones y otros medios de transporte, para trasladar a los turistas.

![Emisiones CO2](./img/co2.png)

La gráfica muestra claramente que las emisiones de CO2 están en aumento, con picos que corresponden a la temporada de primavera-verano. Esta tendencia va en contra de las campañas que buscan reducir las emisiones a la atmósfera, y podría ser exacerbada por el aumento del turismo, lo que a su vez podría aumentar el uso de vehículos y los niveles de emisiones de CO2.

## Conclusiones

El aumento del turismo puede contribuir al incremento en los precios de la vivienda, lo que puede resultar en una mayor dificultad para encontrar alojamiento asequible.

Es posible que el turismo no esté generando empleos de calidad debido a la naturaleza de los horarios, la temporalidad y los bajos salarios se asocian con este sector.

El incremento del turismo también puede contribuir al aumento de los niveles de emisiones a la atmósfera, lo que va en contra de las campañas para reducir los niveles de emisiones.
