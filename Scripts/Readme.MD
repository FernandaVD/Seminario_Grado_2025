# 📊 Clasificación de Ingresos con Random Forest – Dataset *Adult (Census Income)*

## 🧾 Autor

**Nombre:** Lina Fernanda Vargas Daza  
**Fecha:** Noviembre de 2025  
**Institución / Proyecto:** Maestría en Estadística Aplicada — Trabajo práctico de modelación  
**Lenguaje:** R  
**Algoritmo:** Random Forest  
**Repositorio de datos:** UCI Machine Learning Repository  

---

## 🎯 Introducción

El conjunto de datos **Adult**, también conocido como *Census Income Dataset*, fue donado en abril de 1996 por **Barry Becker** y proviene de la base de datos del **Censo de los Estados Unidos de 1994**.  
Su propósito es predecir si los ingresos anuales de una persona **superan los \$50.000 USD** a partir de variables demográficas, educativas y laborales.

Este conjunto de datos se ha convertido en un referente clásico para ejercicios de **aprendizaje supervisado**, especialmente en tareas de **clasificación binaria**.  
Por su composición mixta (variables categóricas y numéricas), volumen de observaciones y presencia de valores faltantes, resulta un excelente caso de estudio para la aplicación de algoritmos de **árboles de decisión** y, en particular, del modelo **Random Forest**.

---

## 📘 Descripción general del dataset

- **Nombre:** Adult / Census Income  
- **Fuente:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult)  
- **Autor de la extracción:** Barry Becker (1996)  
- **Área temática:** Ciencias sociales y economía laboral  
- **Tarea asociada:** Clasificación supervisada  
- **Número de observaciones:** 48.842  
- **Número de variables:** 14 predictoras + 1 variable objetivo  
- **Tipo de variables:** Categóricas y numéricas  
- **Valores faltantes:** Sí (`workclass`, `occupation`, `native.country`)  

---

## 🧩 Objetivo del modelo

El objetivo del modelo es **clasificar individuos según su nivel de ingreso** (`<=50K` o `>50K`), utilizando características como edad, educación, tipo de trabajo, horas trabajadas, ganancia/pérdida de capital, entre otras.

Se implementa un modelo de **Random Forest** en R, el cual combina múltiples árboles de decisión para mejorar la precisión y reducir el sobreajuste, aprovechando la variabilidad del muestreo aleatorio de observaciones y predictores.

## 💡 Relevancia

El conjunto de datos *Adult* es ampliamente utilizado en la enseñanza y la investigación de modelos de clasificación.  
Permite analizar cómo variables socioeconómicas y laborales inciden en los ingresos, y sirve como ejemplo reproducible para el estudio de algoritmos de **aprendizaje automático interpretables**, como los basados en árboles de decisión.

---

## 📚 Referencia

Becker, B. & Kohavi, R. (1996). *Adult Data Set*.  
UCI Machine Learning Repository.  
Disponible en: [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult)
