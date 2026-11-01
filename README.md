# Solución de la Guía de Aprendizaje No. 1 — Procesamiento de Datos para Modelos de IA

Este repositorio contiene la solución técnica a la Guía de Aprendizaje No. 1 del programa **Procesamiento de Datos para Modelos de Inteligencia Artificial** (SENA — Centro de Materiales y Ensayos). 

El proyecto abarca el ciclo completo de análisis sobre el dataset de criminalidad en Colombia: estructuración del diccionario de variables, procesos de limpieza y transformación de datos (ETL en Python con Pandas), Análisis Exploratorio de Datos (EDA) e integración con motores relacionales (MySQL) para la resolución de preguntas de negocio mediante consultas SQL.

---

## 🚀 Entorno de Ejecución Recomendado

Se recomienda ejecutar los cuadernos Jupyter (`.ipynb`) directamente en **Google Colab**.

* **Conexión con Google Drive:** El flujo de trabajo está optimizado para conectarse directamente con Google Drive para la lectura y exportación de la ficha de caracterización (`.json` / `.xlsx`) y el dataset procesado.
* **Entorno Preconfigurado:** Facilita el montaje rápido del entorno de ejecución, librerías de visualización y la inicialización del servidor local de MySQL sin conflictos de dependencias locales.

---

## 📦 Obtención de la Base de Datos

> **Nota importante:** Los archivos de datos planos originales (`.csv`) **no están subidos a este repositorio de GitHub** debido a las restricciones de almacenamiento para archivos de gran tamaño (*file size limits*).

Para ejecutar los cuadernos y reproducir el proceso de ETL y análisis, debes descargar el dataset original directamente desde Kaggle:

🔗 **Enlace de descarga:** [Crimen Colombia 2020-2026: Eventos Geo Depurados (Kaggle)](https://www.kaggle.com/datasets/williamajg/crimen-colombia-2020-2026-eventos-geo-depurados)

### Estructura de archivos esperada

Una vez descargado el dataset, colócalo en la misma carpeta del cuaderno o en la ruta de tu Google Drive configurada:

```text
├── crimen_colombia_2020_2026_eventos_geo.csv  <-- Descargado de Kaggle
├── cuaderno_proyecto_integrador.ipynb
└── outputs/
    ├── crimen_colombia_limpio.csv
    ├── diccionario_variables.json
    └── diccionario_variables.xlsx
```

---

## 📊 Resumen de Entregables

1. **Diccionario de datos técnico:** 14 variables clasificadas estadísticamente y mapeadas a tipos de datos en Pandas.
2. **Proceso ETL & EDA:** Imputación de nulos, reducción de memoria RAM en un 34.6%, limpieza léxica y gráficos multivariados.
3. **Modelado y Consultas SQL:** Respuestas analíticas a las preguntas de negocio mediante expresiones CTE y funciones de ventana (`ROW_NUMBER()`).

---

## 👤 Información del Autor

* **Autor:** Diego Esteban González Urrea
* **Ficha:** 3533558
* **Programa:** Procesamiento de Datos para Modelos de Inteligencia Artificial
* **Institución:** Servicio Nacional de Aprendizaje (SENA) — Centro de Materiales y Ensayos
* **Docente:** Ing. Nathalia Martinez Vargas
* **Fecha:** Octubre 2026