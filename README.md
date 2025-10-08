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

## 📂 Estructura del repositorio
📦 Proyecto-prueba
┣ 📂 notebooks # Notebooks de cada ejercicio
┃ ┣ ejercicio1_datos_estructurados.ipynb
┃ ┣ ejercicio2_pandas_vs_dask.ipynb
┃ ┣ ejercicio3_pandas_vs_pyspark.ipynb
┃ ┣ ejercicio4_visualizacion.ipynb
┃ ┗ ejercicio5_perceptron.ipynb
┣ 📂 informe # Informe en LaTeX
┃ ┣ main.tex
┃ ┗ main.pdf
┣ 📂 data # Datasets pequeños o enlaces
┃ ┗ README.md
┣ README.md # Este archivo
┗ requirements.txt # Librerías necesarias

---

## 🚀 Flujo de trabajo en Git
- Se trabajó en una sola rama (`main`) dado que el desarrollo fue individual.
- Commits descriptivos (ejemplo: `add limpieza dataset ejercicio1`).

---

## 🛠️ Instalación y ejecución

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

Ejercicio 1: Dataset CSV (Iris) + Dataset JSON/texto.

Ejercicio 2: Dataset >200MB desde Kaggle/UTEM Drive.

Ejercicio 3: Dataset de ejemplo (se definirá).

Ejercicio 4: Subconjunto del dataset anterior para visualización.

Ejercicio 5: Subconjunto linealmente separable de Iris.



