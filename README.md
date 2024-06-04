# Proyecto de Análisis y Predicción de Precios de Bienes Raíces en Madrid

Este proyecto se centra en el análisis y la predicción de los precios de bienes raíces en Madrid utilizando datos recopilados de portales inmobiliarios populares. El objetivo es comprender mejor los factores que influyen en los precios de las propiedades y desarrollar modelos predictivos para estimar los precios futuros.

## Información del Dataset

El dataset utilizado es cortesía de [MIRBEK TOKTOGAEV](https://www.kaggle.com/datasets/mirbektoktogaraev/madrid-real-estate-markte) y contiene listados de propiedades inmobiliarias en Madrid. El dataset tiene las siguientes características:

- **Estructura de los datos:** 21742 filas y 58 columnas.
- **Variables clave:** El dataset incluye información sobre el tamaño de la propiedad, el número de habitaciones y baños, el precio de alquiler y compra, entre otros.

## Detalles del Proyecto

### Preprocesamiento de Datos

1. **Exploración de Datos:** Se realizó una exploración inicial para comprender la estructura del dataset y la distribución de los datos.

2. **Manejo de Valores Nulos:** Se identificaron y se decidió manejar los valores nulos en las columnas importantes para el análisis.

3. **Imputación de Valores Nulos:** Se imputaron los valores nulos utilizando estrategias como la mediana para variables numéricas importantes.

4. **Corrección de Datos Anómalos:** Se corrigieron valores anómalos, como años de construcción improbables.

### Análisis y Visualización

1. **Exploración de Variables:** Se analizaron las relaciones entre las variables para identificar patrones y tendencias.

2. **Visualización de Datos:** Se utilizó Matplotlib y Seaborn para crear visualizaciones informativas que ayudaron a entender mejor los datos.

### Modelado Predictivo

1. **Selección de Características:** Se utilizó RandomForest para seleccionar las características más relevantes para predecir los precios de las propiedades.

2. **Entrenamiento de Modelos:** Se entrenaron modelos de regresión lineal y Random Forest para predecir los precios de las propiedades.

3. **Validación del Modelo:** Se evaluaron los modelos utilizando métricas de evaluación como el error cuadrático medio (MSE) y el coeficiente de determinación (R^2).

### Implementación y Despliegue

1. **Guardado del Modelo:** El modelo final se guardó utilizando la biblioteca pickle para su uso futuro.

## Requerimientos del Proyecto

Los siguientes son los requerimientos necesarios para ejecutar el proyecto:

numpy==1.21.0
pandas==1.3.0
matplotlib==3.4.2
seaborn==0.11.1
boto3==1.18.5
scikit-learn==0.24.2


## Cómo Ejecutar el Proyecto

1. Instalar las bibliotecas necesarias utilizando `pip install -r requirements.txt`.
2. Descargar el dataset desde el enlace proporcionado y colocarlo en la carpeta correspondiente del proyecto.
3. Ejecutar el código proporcionado en un entorno de desarrollo compatible con Python.

## Contribuyentes

- Desarrollado por Manuel Luján
- Dataset cortesía de MIRBEK TOKTOGAEV

## Referencias

- [Kaggle: Madrid Real Estate Market](https://www.kaggle.com/datasets/mirbektoktogaraev/madrid-real-estate-markte)
