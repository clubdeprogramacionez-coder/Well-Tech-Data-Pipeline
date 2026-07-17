# Analisis-Estratigrafico-Python
Correlación Estratigráfica de Pozos Notebook para visualizar y comparar registros de pozo. Carga datos desde archivos CSV, genera gráficos comparativos entre pozos y realiza análisis litológico mediante líneas de corte en el registro Gamma Ray.

-----

## Descripción del Proyecto
Este proyecto implementa una solución de Arquitectura de Datos (80%) y Software (20%) orientada a la ingeniería petrolera. El sistema automatiza la lectura de datos crudos provenientes de sensores de fondo de pozo (archivos CSV), ejecuta un control de calidad para eliminar ruido de las herramientas de medición y genera una visualización estratigráfica estandarizada bajo las normativas de la industria energética.

## 📊 Arquitectura del Sistema
Ingesta de Datos (Data Ingestion): Lectura eficiente de flujos de datos estructurados directamente desde archivos de texto plano sin dependencias pesadas.
Control de Calidad (Data Quality): Filtrado automatizado de anomalías de lectura (valores fuera de rango o errores comunes de calibración del sensor como valores nulos o negativos).
Transformación y Clasificación (Data Transformation): Segmentación matemática en tiempo de ejecución para diferenciar litologías (Arenas vs. Arcillas) con base en una línea de corte API.
Visualización Técnica (Data Visualization): Renderizado modular en Matplotlib aplicando las convenciones internacionales de la petrofísica (eje vertical invertido para profundidad y escala horizontal en la parte superior).


## 🛠️ Tecnologías Utilizadas

1. Entorno de Desarrollo: `VS Code / Python 3`
2. Librerías Principales: `Matplotlib (Visualización avanzada), CSV & OS (Módulos nativos para procesamiento de archivos).`

📈 Resultados Visuales
El pipeline genera de manera automática un reporte visual en alta definición (.png) listo para la toma de decisiones geológicas:



## 🚀 Cómo Ejecutar el Proyecto Localmente

Clona este repositorio en tu máquina local:
```bash
git clone https://github/turutagithub.com
```
Asegúrate de tener instalado Matplotlib:
```bash
pip install matplotlib
```
Ejecuta el script principal desde tu terminal o VS Code:
```bash
python src/tuproyecto.py
```
Copyright (c) 2026 Club de Programación Esime Zacatenco y AeroScript-DYGM
