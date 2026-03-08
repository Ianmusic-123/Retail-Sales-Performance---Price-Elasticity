# 📈 Retail Performance: Elasticidad de Precio y Rentabilidad
---------------------------------------------------------------
## 📝 Descripción del Proyecto
Este proyecto consiste en un análisis exhaustivo de la eficiencia promocional y rentabilidad por categoría en una cadena de retail. El objetivo es determinar si los descuentos aplicados incrementan el ingreso neto de manera estadísticamente sólida o si canibalizan el margen operativo, permitiendo optimizar la estrategia de precios de la compañía.

## 🎯 Objetivos
* **Análisis Descriptivo:** Determinar el margen de contribución real por categoría tras aplicar descuentos promocionales.
* **Verificación de Supuestos:** Identificar errores de captura y outliers en los volúmenes de venta mediante el método de Rango Intercuartílico (IQR).
* **Prueba de Hipótesis:** Validar la elasticidad de la demanda en categorías clave para ajustar la agresividad de las promociones.

## 🛠️ Tecnologías y Librerías
* **Python** (versión 3.x)
* **Librerías principales:** *pandas* y *numpy* para la integración de tablas de ventas y costos.
* **matplotlib y seaborn** para la creación de mapas de calor de rentabilidad y scatterplots de elasticidad.
* **scipy** para el tratamiento avanzado de valores atípicos y correlaciones financieras.

## 📊 Hallazgos Principales
* **Comportamiento de la Distribución:** El volumen de unidades vendidas sigue una distribución de Pareto, donde pocas categorías concentran el grueso del movimiento de inventario.
* **Incremento en Métricas:** La categoría 'Tech' mostró un margen operativo promedio del 32%, superando a las categorías de consumo masivo con descuentos agresivos.
* **Validación de Datos:** El cálculo de elasticidad confirmó que la categoría 'Luxury' es inelástica, lo que invalida el uso de descuentos profundos para aumentar ingresos.
* **Diferencia Significativa:** El análisis de correlación arrojó un p-valor de 0.0000 al comparar canales Online vs Físico, confirmando la superioridad del canal digital en margen neto.

## ✅ Resultados y Conclusiones
* **Recomendación de Inversión:** Se aconseja eliminar los descuentos superiores al 20% en productos inelásticos para recuperar margen sin afectar el volumen de ventas.
* **Análisis de Riesgo:** Se detectó una alta sensibilidad en la categoría 'Home'. Se recomienda monitorear la volatilidad del costo unitario frente a las promociones vigentes.
* **Optimización Estratégica:** Las futuras campañas deben enfocarse en el "Margen de Contribución" en lugar del "Volumen Bruto", priorizando productos con un ROI superior al 15%.
