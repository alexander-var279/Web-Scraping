# Web-Scraping
# Web-Scraping

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1p7ksw_tGP39OpAXO4GH7QkXtr0LqogvF#scrollTo=301b2dda)

---

## 📊 Web Scraping y Análisis de Texto

## 🧠 Descripción

En este proyecto se realiza la extracción y análisis de datos de libros desde Books to Scrape.

Se combinan técnicas de **web scraping** y **procesamiento de lenguaje natural (NLP)** para explorar cómo las palabras en los títulos pueden relacionarse con el precio de los libros.

---

## ⚙️ Metodología

### 🔹 Web Scraping
- Extracción de títulos y precios  
- Construcción de un DataFrame  

### 🔹 Limpieza de texto
- Conversión a minúsculas  
- Eliminación de stopwords, números y caracteres especiales  
- Resultado: `datos_limpios`  

### 🔹 Análisis de n-gramas
- Cálculo de frecuencias  
- Generación de nube de palabras  

### 🔹 Matriz TF
- Frecuencia de palabras por libro  
- Se añade el precio como variable  

### 🔹 Variables binarias
- Presencia (1) o ausencia (0) de palabras clave  
- Análisis del impacto en el precio  

### 🔹 Visualización
- Gráficos de barras  
- Comparación entre palabras y precios  

---

## 🛠️ Tecnologías

- Python  
- Pandas  
- BeautifulSoup  
- Requests  
- Matplotlib / Seaborn  
- WordCloud  

---

## 🎯 Objetivo

Identificar patrones en los títulos de libros y analizar si ciertas palabras están asociadas con precios más altos o más bajos.

---

## 🚀 Uso

1. Abrir el cuaderno en Colab (botón arriba)  
2. Ejecutar las celdas paso a paso  
3. Explorar resultados y visualizaciones  
