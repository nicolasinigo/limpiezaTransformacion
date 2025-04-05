# 🛠️ Práctica de ETL con Python y Jupyter Notebook

Este proyecto es una práctica de un proceso **ETL (Extract, Transform, Load)** realizado con Python en un entorno de **Jupyter Notebook** dentro de **Visual Studio Code**.

---

## 📌 Objetivo

El objetivo de esta práctica fue:

- Extraer datos desde un archivo **CSV**.
- Realizar una limpieza y transformación de los datos.
- Visualizar parte de los resultados.
- Guardar el resultado final en un nuevo archivo procesado.

---

## 🔧 Tecnologías y librerías usadas

- **Visual Studio Code** como entorno de desarrollo.
- **Jupyter Notebook** para la ejecución de celdas interactivas.
- **Python** como lenguaje de programación.
- **pandas** para la manipulación de datos.
- **numpy** para operaciones numéricas.
- **matplotlib** para visualización de datos.

---

## 🔍 Descripción del proceso ETL

### 🧪 Extracción (Extract)

- Se importó un archivo `.csv` con datos crudos.
- Se cargó en un `DataFrame` utilizando `pandas.read_csv()`.

### 🧹 Transformación (Transform)

- Se revisaron valores nulos y se aplicó limpieza.
- Se corrigieron nombres de columnas.
- Se realizaron conversiones de tipos de datos.
- Se eliminaron o filtraron filas/columnas no necesarias.
- Se realizaron operaciones estadísticas o agregaciones simples.

### 💾 Carga (Load)

- Se exportaron los datos transformados a un nuevo archivo `.csv` con `pandas.to_csv()`.

---

## 📊 Visualizaciones

- Se generaron gráficos simples usando `matplotlib` para entender mejor los datos.

---

## 📁 Archivos

- `Etl.ipynb`: Notebook con todo el código del proceso ETL.
- `linkedin-jobs-usa.csv`: Archivo original de entrada.
- `./archivoFinal/datos_limpios.csv`: Archivo generado luego de las transformaciones.

---

## ✅ Conclusiones

Esta práctica me permitió reforzar conocimientos básicos de procesamiento de datos, uso de librerías fundamentales en Python para ciencia de datos y aplicar la lógica de un flujo ETL completo.

---
