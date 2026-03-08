# 📈 Retail Performance: Price Elasticity & Profitability
--------------------------------------------------------------------
## 📝 Descripción del Proyecto
¿Los descuentos agresivos siempre generan más dinero? Este proyecto demuestra que no. Utilizando análisis de elasticidad y cálculos de margen neto, auditamos 5,000 transacciones para encontrar el equilibrio perfecto entre volumen de ventas y rentabilidad.

## 🛠️ Tecnologías Utilizadas
* **Python** (Data Wrangling y Cálculos Financieros).
* **Seaborn/Matplotlib** (Visualización de Correlaciones).
* **Scipy** (Detección de Outliers).

## 🚀 Pipeline del Proyecto (11 Etapas)
1. **Arquitectura:** Diseño de datos relacionales (Ventas + Productos).
2. **Merging:** Integración de fuentes mediante llaves primarias.
3. **Tipado:** Optimización de memoria con categorías.
4. **Cálculos:** Implementación de fórmulas de Margen Neto y ROI.
5. **Sanitización:** Eliminación de registros con margen negativo.
6. **Elasticidad:** Cálculo de la variación de demanda ante cambios de precio.
7. **Pivot Tables:** Resumen ejecutivo por categoría.
8. **Outliers:** Limpieza mediante el método IQR (Rango Intercuartílico).
9. **Heatmaps:** Análisis de correlación de variables financieras.
10. **Resultados:** Cálculo del Profit Total del periodo.
11. **Business Insights:** Recomendaciones para la gerencia comercial.

## 📉 Resultados Clave
* **Elasticidad Inelástica:** La categoría 'Luxury' no requiere descuentos para mantener su volumen de ventas.
* **Fuga de Margen:** Se identificó un 8% de error en reportes debido a datos atípicos no filtrados previamente.



## 💡 Recomendación Estratégica
Eliminar promociones automáticas en productos de alta gama y establecer un "precio piso" para asegurar que ninguna venta genere pérdida operativa.
