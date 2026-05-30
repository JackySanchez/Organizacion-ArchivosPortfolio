# Proyecto 3: Actividad Integradora - Análisis de Ventas con Python

## Descripción
Este proyecto representa la integración de conocimientos de programación y ciencia de datos. Consiste en una aplicación de análisis financiero que procesa un archivo CSV de ventas tecnológicas, realiza cálculos de rentabilidad y genera una visualización gráfica de los resultados para facilitar la toma de decisiones empresariales.

## Objetivos de la Práctica
* **Manipulación de DataFrames:** Uso de la librería **Pandas** para leer, filtrar y agrupar datos complejos.
* **Cálculos Matemáticos Automatizados:** Creación de columnas calculadas (Ingresos = Cantidad × Precio) para determinar el valor real de las ventas.
* **Visualización de Datos:** Implementación de **Matplotlib** para generar gráficas de barras que comparan el rendimiento por producto y por mes.
* **Inteligencia de Negocios:** Programación de una jerarquía de decisiones que identifica automáticamente el producto más rentable y el menos vendido.

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías de Datos:** Pandas (Estructuras de datos y análisis).
* **Librerías Gráficas:** Matplotlib (Generación de diagramas y visualización).
* **Almacenamiento:** CSV (Valores separados por comas).

## Estructura de Archivos en /src
* `analisis_ventas.py`: Script principal que contiene la lógica de procesamiento, la generación de la gráfica y las conclusiones automáticas.
* `ventas_tecnologia.csv`: Base de datos con el historial de ventas (mes, producto, cantidad, precio).

## Conclusiones del Análisis
El sistema está programado para identificar:
1. **Producto Estrella:** Basado en el mayor impacto financiero.
2. **Optimización de Inventario:** Identificación del producto con menor rotación para sugerir promociones.
3. **Tendencia Mensual:** Determinación del mes con mayor flujo de ingresos.