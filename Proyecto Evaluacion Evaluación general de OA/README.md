# Proyecto 4: Evaluación General - Sistema de Gestión Hospitalaria

## Descripción
Este proyecto final representa la culminación de la materia, integrando la generación masiva de datos, la gestión de diferentes arquitecturas de archivos (CSV y JSON) y el análisis de rendimiento de software. El sistema simula la operación de un hospital, procesando expedientes médicos y signos vitales de pacientes para generar inteligencia de negocios.

## Objetivos de la Práctica
* **Arquitectura de Datos:** Comparar la eficiencia de almacenamiento y tiempos de respuesta entre archivos planos (CSV) y archivos estructurados (JSON).
* **Generación Sintética de Datos:** Uso de lógica en Python para crear miles de registros médicos con datos realistas (temperatura, presión arterial, especialidades).
* **Análisis de Rendimiento:** Implementación de `tracemalloc` y `time` para medir el consumo de memoria y la velocidad de procesamiento.
* **Visualización Avanzada:** Generación de un panel maestro de gráficas (Dashboard) que incluye histogramas de temperatura, distribución de especialidades y tendencias de carga.

## Componentes del Sistema
* **Fase de Generación:** Creación de archivos de gran volumen para pruebas de estrés.
* **Fase de Visualización:** Uso de `Matplotlib` para crear un reporte gráfico automático (`reporte_grafico_hospital.png`).
* **Fase de Interpretación:** Algoritmos de detección de tendencias (ej. identificar especialidades con mayor demanda o pacientes con cuadros febriles).

## Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Análisis de Datos:** Pandas
* **Gráficas:** Matplotlib
* **Formatos de Archivo:** CSV, JSON, TXT (Auditoría)

## Estructura de Archivos en /src
* `generador_y_sistema.py`: Script principal que construye los archivos de datos y mide el rendimiento del sistema.
* `visualizacion.py`: Módulo especializado en la creación de gráficas y análisis estadístico descriptivo.