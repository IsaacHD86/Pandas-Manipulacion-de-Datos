# Pandas-Manipulacion-de-Datos
Pandas; Dataframes, lectura y exportación de archivos.

# Análisis de Datos - Iris Dataset

Este proyecto utiliza el conjunto de datos "Iris" para realizar un análisis de estadísticas descriptivas y manipulación de datos. 
En particular, se realiza una serie de pasos para calcular la media, desviación estándar y mediana del ancho del pétalo por cada tipo de flor, así como la estandarización de los valores de dicho ancho.

## Descripción

La práctica implica importar el archivo CSV "Iris.csv" en Python, filtrar los datos según ciertas condiciones, calcular estadísticas descriptivas (media, desviación estándar y mediana) para el ancho del pétalo de diferentes tipos de flores, y luego realizar una estandarización de los valores del ancho del pétalo.

## Pasos Realizados

1. **Carga del archivo CSV**:
   Se importa el archivo "Iris.csv" y se prepara para su análisis.

2. **Filtrado de registros**:
   Se seleccionan solo aquellos registros cuyo ancho del sépalo es mayor o igual a 3.5 y el largo del sépalo es mayor que 5.

3. **Cálculo de estadísticas**:
   Para cada tipo de flor, se calculan la media, la desviación estándar y la mediana (percentil 50) del ancho del pétalo.

4. **Conteo de registros**:
   Se calcula el número de registros que se utilizaron para obtener los resultados del paso anterior.

5. **Estandarización de los datos**:
   Se agrega una nueva columna al DataFrame que contiene los valores estandarizados del ancho del pétalo. La estandarización se realiza utilizando la fórmula:
   
   \[
   \text{petal.width.st} = \text{petal.width} - \text{Media(petal.width)}
   \]

## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
