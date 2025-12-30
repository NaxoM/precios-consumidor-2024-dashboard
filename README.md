Análisis de Precios al Consumidor – Chile 2024
 Objetivo del panel

El objetivo de este dashboard es analizar el comportamiento del precio promedio de productos alimenticios en Chile durante el año 2024, identificando diferencias por región, grupo de alimentos y su evolución temporal.

El panel busca responder preguntas como:

¿Cuál es el precio promedio nacional?

¿Qué regiones presentan los precios más altos?

¿Qué productos tienen los mayores precios promedio?

¿Cómo evolucionaron los precios a lo largo del año  2024?


Fuentes de datos

Fuente: Archivo CSV de precios al consumidor 2024

Formato: CSV

Contenido: Regiones, productos, grupos de alimentos, precios mínimos, máximos y promedio, periodo mensual.


 Proceso de limpieza y preparación de datos

Se utilizó el archivo CSV original sin modificaciones estructurales.

Los datos fueron explorados para verificar tipos de campos, valores nulos y consistencia general.


Nota sobre la interpretación de los valores de precios

Es importante señalar que, debido al formato original del archivo CSV y a la forma en que Looker Studio interpreta automáticamente los campos numéricos, algunos valores de precios se visualizan en escalas de millones o billones dentro de los gráficos.

Sin embargo, para efectos del análisis realizado en este panel:

Los valores deben interpretarse como pesos chilenos (CLP).

Por ejemplo, un valor visualizado como 4.000 millones corresponde en realidad a un precio promedio aproximado de CLP 4.000 o tambien con 40 B el cual significaria 40.000 millones, el cual corresponde a CLP 40.000.

Esta convención se mantiene de forma consistente en todo el dashboard para asegurar coherencia en la interpretación comparativa de los datos.

La decisión de no modificar los valores originales se tomó con el fin de preservar la integridad de la fuente de datos, priorizando la transparencia del proceso analítico por sobre ajustes manuales que alteren la información original.


Decisiones de diseño del panel

Se utilizó Looker Studio para permitir visualización interactiva sin requerir licencias de pago.

Se incluyeron filtros por Región y Grupo de alimentos para facilitar el análisis exploratorio.

Se priorizaron gráficos claros:

KPI de precio promedio nacional

Barras por región

Top 10 productos por precio promedio

Evolucion del precio promedio por region

Evolucion del precio promedio por grupo

La interpretación de valores considera la escala mostrada por la herramienta, manteniendo consistencia en todo el panel.

🔗 Dashboard interactivo

El panel completo se encuentra disponible en el siguiente enlace:

 https://lookerstudio.google.com/XXXX
