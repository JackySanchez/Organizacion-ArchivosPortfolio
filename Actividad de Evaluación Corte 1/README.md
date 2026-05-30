# Proyecto 1: Sistema KLIK - Control de Inventarios (Corte 1)

## Descripción
**KLIK** es una aplicación web robusta desarrollada para la gestión eficiente de inventarios de gran volumen. El sistema permite administrar hasta 10,000 registros mediante la manipulación de archivos de texto planos (`maestro.txt`), simulando el comportamiento de una base de datos real mediante lógica de archivos en PHP.

## Características Principales
* **Control de Acceso:** Sistema de login seguro con manejo de sesiones (`session_start`).
* **Generación de Datos (Génesis):** Script automatizado para la creación masiva de productos con estados dinámicos (Agotado, Crítico, Disponible).
* **Gestión CRUD:** Capacidad para visualizar, filtrar, editar y eliminar productos.
* **Reportes Profesionales:** Generación de archivos PDF utilizando la librería **FPDF**, permitiendo obtener reportes generales o filtrados por estado de stock.

## Tecnologías Utilizadas
* **Lenguaje:** PHP 8.x
* **Interfaz:** HTML5, CSS3 (Diseño personalizado)
* **Librerías Externas:** FPDF para la exportación de documentos.
* **Arquitectura:** Gestión de archivos planos (`.txt`) con delimitadores.

## Instrucciones de Uso
1. Ejecutar `Genesis.php` para poblar el archivo `maestro.txt` con los 10,000 registros iniciales.
2. Acceder mediante `login.php`.
3. Navegar por el panel de control para gestionar el inventario o generar reportes PDF.