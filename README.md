# 🚀 Pipeline Integrado: Evaluación de Formaciones y Monitoreo de Producción
Este repositorio contiene dos herramientas clave para la gestión de activos petroleros, cubriendo desde la caracterización geológica del subsuelo hasta el monitoreo del rendimiento operativo en superficie.


----


## 1. Módulo de Caracterización: Correlación Estratigráfica
Notebook para visualizar y comparar registros de pozo.

Este componente implementa una solución de Arquitectura de Datos orientada a la ingeniería petrolera. El sistema automatiza la lectura de datos crudos de sensores de fondo de pozo (archivos CSV), ejecuta un control de calidad para eliminar ruido y genera una visualización estratigráfica estandarizada bajo normativas de la industria.

**📊 Características del Sistema**
1. Ingesta de Datos: Lectura eficiente de flujos estructurados desde archivos de texto plano.
2. Transformación y Clasificación: Segmentación matemática para diferenciar litologías (Arenas vs. Arcillas) con base en una línea de corte API.
3. Visualización Técnica: Renderizado modular aplicando convenciones petrofísicas (eje vertical invertido y escala horizontal superior).

## 2. Módulo de Gestión: Dashboard de Producción Petrolera
Herramienta de monitoreo operativo y diagnóstico de activos.

Este módulo complementa la caracterización geológica al trasladar el análisis a la superficie. Permite a los ingenieros de producción evaluar el comportamiento mensual de los pozos, calcular el impacto acumulado y diagnosticar el rendimiento mediante indicadores visuales.

**📊 Capacidades del Dashboard**
1. Análisis de Desempeño: Visualización de producción mensual mediante diagramas de barras apiladas.
2. Tendencia Temporal: Monitoreo del volumen de producción acumulada anual.
3. Distribución de Activos: Gráficos de pastel para identificar la participación proporcional de cada pozo en el rendimiento total del campo.

Diagnóstico Operativo: Implementación de lógica condicional para clasificar pozos en niveles de rendimiento (Bajo, Normal, Crítico), facilitando la toma de decisiones para intervenciones técnicas.


## 💡 Flujo de Trabajo (Arquitectura del Pipeline)
La integración de ambos módulos representa el ciclo de vida del dato:

1. Exploración: Identificación de reservorios mediante correlación estratigráfica.

2. Explotación: Monitoreo de la rentabilidad a través del Dashboard de producción.

Este enfoque permite a los profesionales pasar de la visualización de datos geológicos crudos a la toma de decisiones estratégicas de negocio.


## 🛠️ Tecnologías Utilizadas

1. Entorno de Desarrollo: `VS Code / Python 3`
2. Librerías Principales: `Matplotlib (Visualización avanzada), CSV & OS (Módulos nativos para procesamiento de archivos).`

📈 Resultados Visuales
El pipeline genera de manera automática un reporte visual en alta definición (.png) listo para la toma de decisiones geológicas:



## 🚀 Cómo Ejecutar el Proyecto Localmente

Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/clubdeprogramacionez-coder/Well-Tech-Data-Pipeline.com
```
Asegúrate de tener instalado Matplotlib:
```bash
pip install matplotlib
```
Ejecuta el script principal desde tu terminal o VS Code:
```bash
python src/Analisis_y_Correlacion.ipynb.py
```
Copyright (c) 2026 Club de Programación Esime Zacatenco y AeroScript-DYGM
