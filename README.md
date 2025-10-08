# Primera Prueba - Herramientas para Ciencia de Datos
**UTEM - Ingeniería Civil en Ciencia de Datos**  
**Asignatura:** INFB6052 - Herramientas para Ciencia de Datos  
**Profesor:** Michael Miranda Sandoval  
**Segundo Semestre 2025**

---

## 📌 Integrante del Grupo
- **Helen Maureira Barrenechea:** Ejercicio 1, Anteproyecto (LaTeX) e Informe final.
- **Renato Fernandez:** Ejercicios 2, 3, 4 y 5.

---

## Estructura del repositorio
Proyecto-prueba
┣ notebooks # Notebooks de cada ejercicio
┃ ┣ ejercicio1_datos_estructurados.ipynb
┃ ┣ ejercicio2_pandas_vs_dask.ipynb
┃ ┣ ejercicio3_pandas_vs_pyspark.ipynb
┃ ┣ ejercicio4_visualizacion.ipynb
┃ ┗ ejercicio5_perceptron.ipynb
┣ informe # Informe en LaTeX
┃ ┣ main.tex
┃ ┗ main.pdf
┣ data # Datasets pequeños o enlaces
┃ ┗ README.md
┣ README.md # Este archivo
┗ requirements.txt # Librerías necesarias

---

## Flujo de trabajo en Git
- Se trabajó en una sola rama (`main`).

---

## Instalación y ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/hmaureira-byte/Proyecto-prueba.git
cd Proyecto-prueba

python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
pdflatex main.tex

Datasets usados

# Datasets usados

**Ejercicio 1:**  
- **Iris (CSV):** dataset clásico de flores con medidas de sépalo y pétalo, disponible en [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris).  
- **JSON/Text:** ejemplo de datos no estructurados para comparar con CSV.

**Ejercicio 2:**  
- **AirQualityUCI (>200MB):** dataset de calidad del aire obtenido desde Kaggle/UTEM Drive. Contiene mediciones de contaminantes y variables meteorológicas.

**Ejercicio 3:**  
- **Dataset de ejemplo:** se utilizará un dataset tabular para comparar Pandas y PySpark. Puede ser un subconjunto del dataset de calidad del aire o uno similar disponible públicamente.

**Ejercicio 4:**  
- **Subconjunto del dataset anterior:** se extrae un subconjunto para generar visualizaciones con Matplotlib, Seaborn y Plotly, facilitando análisis gráfico y comparación de librerías.

**Ejercicio 5:**  
- **Subconjunto linealmente separable de Iris:** se seleccionan algunas clases de Iris para entrenar y visualizar un perceptrón binario.



