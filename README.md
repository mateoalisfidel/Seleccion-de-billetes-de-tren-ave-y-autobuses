# Web Scraping para Comparación de Precios de Transporte

## Descripción del Proyecto

Herramienta de web scraping desarrollada en Python que compara precios de billetes de transporte en tiempo real. La aplicación consulta automáticamente las páginas web de las principales compañías de transporte en España para encontrar las mejores opciones de viaje.

### Objetivo Principal
Facilitar la búsqueda y comparación de precios de billetes de tren (AVE) y autobús, encontrando automáticamente las opciones más económicas sin necesidad de consultar manualmente múltiples webs.

## Video Demostrativo

Ver demostración completa del proyecto:
https://drive.google.com/file/d/15yJuJ9hOED4ln7LmXZ_exbXp-qqb2pz4/view

## Autores
- Mateo Alís
- Manuel Caballero
- Vicente Llacer

## Características Principales

### Búsqueda Multiplataforma
- Consulta simultánea en RENFE (trenes/AVE)
- Consulta simultánea en OUIGO (trenes)
- Consulta simultánea en ALSA (autobuses)

### Optimización de Precios
- Identificación automática del viaje más económico
- Comparación de precios de ida y vuelta
- Análisis de relación calidad-precio

### Información Detallada
- Precios actualizados en tiempo real
- Duración exacta de los trayectos
- Horarios de salida y llegada
- Compañía operadora del servicio

### Flexibilidad Total
- Elección entre tren o autobús como transporte principal
- Opción de consultar el otro medio de transporte posteriormente
- Interfaz intuitiva y fácil de usar

## Tecnologías Utilizadas

- Python 3.7+
- Jupyter Notebook
- Selenium WebDriver
- WebDriver Manager

## Librerías Python Requeridas
- Selenium==4.15.0
- Webdriver-manager==4.0.1
- Time
