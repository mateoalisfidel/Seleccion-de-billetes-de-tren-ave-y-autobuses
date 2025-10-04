# Web Scraping para Comparación de Precios de Transporte

## Objetivo
El objetivo de este trabajo es realizar **web scraping** en las páginas web de las principales compañías de transporte en España para **comparar precios de billetes** de tren y autobús, encontrando automáticamente las opciones más económicas. Esto permite:

- Consultar múltiples compañías simultáneamente  
- Identificar el viaje más barato de ida y vuelta  
- Comparar duraciones y horarios entre diferentes opciones  
- Proporcionar una interfaz intuitiva para la búsqueda de viajes  

Además, se implementa un sistema flexible que permite al usuario **consultar ambos medios de transporte** en la misma sesión, facilitando la toma de decisiones sobre el transporte más conveniente.

---

## Datos
- **Fuentes de datos**: Páginas web oficiales de RENFE, OUIGO y ALSA  
- **Información extraída**: Precios, horarios, duración de trayectos, ciudades de origen y destino  
- **Formato de salida**: Comparativa de precios y opciones de viaje en tiempo real  

---

## Metodología
1. **Automatización del navegador**: Configuración de Selenium WebDriver  
2. **Extracción de datos**: Web scraping de las páginas web objetivo  
3. **Procesamiento de información**: Limpieza y estructuración de los datos obtenidos  
4. **Análisis comparativo**: Identificación del viaje más económico  
5. **Presentación de resultados**: Interfaz de usuario interactiva  

---

## Resultados
- Sistema funcional de comparación de precios en tiempo real  
- Identificación automática de las opciones más económicas  
- Interfaz intuitiva para la entrada de parámetros de búsqueda  
- Flexibilidad para consultar trenes y autobuses en la misma sesión  
- Ahorro de tiempo en la búsqueda manual de billetes  

---

## Tecnologías
- **Lenguajes y herramientas**: Python, Jupyter Notebook  
- **Librerías principales utilizadas en Python**:  
  - **Web scraping**: Selenium, WebDriver Manager  
  - **Procesamiento de datos**: Pandas  
  - **Entorno de desarrollo**: Jupyter  
- **Áreas de interés y práctica**: Web Scraping, Automatización, Procesamiento de Datos, Interfaz de Usuario  

---

## Cómo ejecutar
1. Abrir los archivos `.ipynb` en Jupyter Notebook  
2. Instalar las librerías necesarias (`requirements.txt`)  
3. Ejecutar el notebook principal: `1_TRABAJO_FINAL.ipynb`  
4. Seguir las instrucciones interactivas para realizar búsquedas  

---

## Estructura del proyecto
- `notebooks/1_TRABAJO_FINAL.ipynb` - Notebook principal con la interfaz de usuario  
- `notebooks/2_DEFINITIVO_RENFE.ipynb` - Scraping específico para RENFE  
- `notebooks/3_DEFINITIVO_OUIGO.ipynb` - Scraping específico para OUIGO  
- `notebooks/4_DEFINITIVO_ALSA.ipynb` - Scraping específico para ALSA  
- `docs/` - Documentación y presentación del proyecto  
- `requirements.txt` - Dependencias del proyecto
