# Evaluación de Ventas por Tienda - Colab

## Resumen
Este proyecto realiza un análisis comparativo de ventas entre cuatro tiendas distintas. El propósito es identificar cuál tienda ofrece el mayor potencial para concentrar esfuerzos de venta, teniendo en cuenta ingresos, satisfacción del cliente, productos con mayor y menor demanda, y costos asociados al envío.

El análisis se implementa en **Google Colab** usando Python, con soporte de librerías como `pandas`, `matplotlib` y `seaborn`. Se incluyen métricas clave y gráficos que facilitan la interpretación de los resultados.

## Propósitos del proyecto
- Determinar los **ingresos totales** por cada tienda.  
- Analizar la **distribución de productos vendidos por categoría**.  
- Calcular la **satisfacción promedio del cliente** por tienda.  
- Identificar los **productos más y menos demandados**.  
- Calcular el **promedio del costo de envío** en cada tienda.  
- Generar **visualizaciones gráficas** para resumir tendencias y patrones.  
- Sugerir la tienda con mayor potencial para concentrar ventas.

## Flujo del Colab
1. **Importación de datos:** Lectura de los CSV de cada tienda desde URLs públicas.  
2. **Ingresos totales:** Cálculo de la suma de precios de ventas por tienda.  
3. **Ventas por categoría:** Conteo de productos por tipo o categoría.  
4. **Promedio de calificación:** Evaluación de la satisfacción del cliente mediante calificaciones promedio.  
5. **Análisis de productos:** Identificación de los artículos más y menos vendidos.  
6. **Costo de envío:** Cálculo del promedio de costo de envío por tienda.  
7. **Visualización de datos:**  
   - Gráfico de barras para los ingresos totales.  
   - Diagramas de barras o pastel para las categorías de productos.  
   - Gráficos de dispersión para analizar relación entre precio y calificación.  
8. **Informe final:** Resumen de hallazgos y recomendación basada en los datos analizados.

## Instrucciones de uso
1. Abre el archivo en **Google Colab**.  
2. Ejecuta las celdas de forma secuencial para procesar los datos y generar resultados.  
3. Revisa los resultados y gráficos generados.  
4. Consulta la sección de **Informe Final** para ver el análisis resumido y la recomendación sobre la tienda más favorable.

## Librerías empleadas
- `pandas`  
- `matplotlib`  
- `seaborn`  

## Origen de los datos
Los datos se obtienen de archivos CSV alojados en GitHub, correspondientes a las cuatro tiendas:  
- Tienda 1  
- Tienda 2  
- Tienda 3  
- Tienda 4  

## Conclusión
Después de examinar todas las métricas y visualizaciones, se recomienda concentrar esfuerzos de venta en **Tienda 1**, debido a su mayor volumen de ingresos y productos con alta demanda. Una alternativa secundaria es **Tienda 3**, destacada por su alta calificación promedio y buen desempeño de ventas, mostrando un equilibrio sólido entre rentabilidad y satisfacción del cliente.
