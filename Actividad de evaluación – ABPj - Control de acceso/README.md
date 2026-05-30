# Proyecto 2: ABPj - Sistema de Control de Acceso e Identificación Biométrica

## Descripción
Este proyecto consiste en un sistema de control de acceso automatizado que integra **Python** para la lógica de autenticación y **PHP** para la visualización de un monitor de seguridad en tiempo real. El sistema simula la lectura de tarjetas de identificación, valida los permisos de los empleados contra una base de datos en formato **JSON** y registra cada evento en un archivo de auditoría.

## Características Principales
* **Autenticación Multi-lenguaje:** Uso de Python para el procesamiento de datos y PHP para la interfaz web.
* **Base de Datos NoSQL (JSON):** Gestión de usuarios, departamentos y niveles de seguridad mediante un archivo `usuarios.json`.
* **Registro de Auditoría (Logging):** Generación automática de un historial detallado en `auditoria.txt`, incluyendo marcas de tiempo y el estado del acceso (PERMITIDO/DENEGADO).
* **Monitor Web Dinámico:** Interfaz visual que clasifica los registros por colores (verde para accesos permitidos y rojo para denegados) para facilitar la supervisión.

## Tecnologías Utilizadas
* **Python 3.x:** Encargado de la lógica de entrada y validación de ID de tarjetas.
* **PHP 8.x:** Utilizado para la lectura del archivo de auditoría y renderizado de la tabla web.
* **JSON:** Formato de intercambio de datos para la lista de personal.
* **CSS3:** Diseño personalizado con degradados y estilos condicionales para el monitor.

## Estructura de Archivos en /src
* `control.py`: Script principal en Python que gestiona la entrada de datos y valida a los usuarios.
* `usuarios.json`: Almacén de datos con información de empleados como ID de tarjeta, nombre, departamento y nivel.
* `auditoria.txt`: Archivo plano donde se guardan cronológicamente los intentos de acceso.
* `index.php`: Monitor de seguridad que muestra de forma gráfica quién ha intentado ingresar al sistema.

## Instrucciones de Uso
1. Ejecutar el script `control.py` e ingresar un ID de tarjeta (ej. 1032).
2. El sistema validará si el usuario existe en `usuarios.json` y escribirá el resultado en `auditoria.txt`.
3. Abrir `index.php` en el navegador (vía Localhost) para visualizar el monitor de seguridad actualizado con los últimos registros.