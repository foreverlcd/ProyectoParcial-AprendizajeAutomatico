# Estudio de los Factores Determinantes en la Frecuencia de Visitas a las Áreas Naturales Protegidas del Perú

## Descripción del Proyecto

Este proyecto analiza los factores que influyen en la frecuencia de visitas a las Áreas Naturales Protegidas (ANP) del Perú, utilizando técnicas de machine learning para identificar patrones y relaciones significativas en los datos proporcionados por el Servicio Nacional de Áreas Naturales Protegidas por el Estado (SERNANP).

El estudio busca responder a la pregunta: **¿Cuáles son los principales factores que influyen en la frecuencia de visitas a las Áreas Naturales Protegidas del Perú?**

## Objetivo General

Identificar los factores clave que influyen en la frecuencia de las visitas turísticas en las Áreas Naturales Protegidas del Perú, utilizando los datos proporcionados por SERNANP y técnicas de machine learning.

## Dataset

El dataset utilizado contiene información sobre:
- Datos de Área Natural Protegida: Nombre, Sector, Departamento, Provincia y Distrito
- Datos de turista: Procedencia, grupo de edad
- Frecuencia de visitas: Fecha de la visita, Estadía 1 día, de 2 a 3 días, y 3 a 30 días

Fuente: [SERNANP - Datos Abiertos](https://www.datosabiertos.gob.pe/dataset/frecuencia-de-visitas-tur%C3%ADsticas-en-las-%C3%A1reas-naturales-protegidas-por-el-estado-%E2%80%93-servicio)

## Técnicas utilizadas

El proyecto implementa diversos algoritmos de machine learning para análisis de regresión, incluyendo:
- Regresión Lineal
- Ridge Regression
- Lasso Regression
- ElasticNet
- Random Forest Regressor
- Gradient Boosting Regressor

También se aplican técnicas de:
- Preprocesamiento de datos
- Análisis exploratorio de datos (EDA)
- Escalado de características
- Optimización de hiperparámetros
- Análisis de componentes principales (PCA)
- Evaluación de modelos (R², RMSE)

## Instrucciones para la Ejecución en Google Colab

Para ejecutar este proyecto en Google Colab, sigue estos pasos:

1. **Accede a Google Colab**: Visita [Google Colab](https://colab.research.google.com/) e inicia sesión con tu cuenta de Google.

2. **Sube el notebook**: 
   - Selecciona `Archivo` > `Subir notebook`
   - Sube el archivo `EstudioANP_v1_ML.ipynb` desde tu dispositivo

3. **Sube el dataset**:
   - En el panel izquierdo de Colab, haz clic en el icono de carpeta para abrir el explorador de archivos
   - Haz clic en el icono "Subir" y selecciona el archivo `SERNANPdataset_Turismo.csv`

4. **Ejecuta el notebook**: 
   - Puedes ejecutar todo el notebook seleccionando `Entorno de ejecución` > `Ejecutar todas` 
   - O puedes ejecutar las celdas una por una presionando Shift+Enter en cada celda

5. **Instalación de dependencias**:
   - El notebook ya incluye las celdas necesarias para instalar todas las dependencias requeridas
   - Asegúrate de ejecutar la celda que contiene `!pip install optuna` para la optimización de hiperparámetros

6. **Entorno recomendado**:
   - Si Colab lo solicita, acepta la ejecución en entorno de GPU para acelerar el entrenamiento de los modelos
   - Para habilitar la GPU manualmente: `Entorno de ejecución` > `Cambiar tipo de entorno de ejecución` > Selecciona `GPU` en el desplegable de acelerador

7. **Tiempo estimado de ejecución**:
   - El notebook completo puede tardar entre 15-30 minutos en ejecutarse completamente, dependiendo de las optimizaciones de hiperparámetros
   - Puedes saltar secciones específicas si solo te interesan ciertos análisis

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

- `EstudioANP_v1_ML.ipynb`: Notebook principal con todo el análisis y modelado
- `SERNANPdataset_Turismo.csv`: Dataset con información de visitas a ANP del Perú
- `ML_ANP.pdf`: Documento complementario con información adicional del proyecto
- `README.md`: Este archivo con información sobre el proyecto e instrucciones

## Resultados Principales

El análisis permite identificar los factores más influyentes en la frecuencia de visitas a las ANP del Perú, ofreciendo insights valiosos para:

- Mejorar la gestión turística sostenible de las ANP
- Optimizar estrategias de conservación y promoción
- Informar políticas públicas basadas en evidencia
- Equilibrar el desarrollo turístico con la conservación ambiental

## Contacto

Para más información sobre este proyecto, puedes contactar con los autores a través de los datos proporcionados en el notebook o directamente al SERNANP.