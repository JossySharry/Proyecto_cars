![Img](Img_cars.png)

# Proyecto: Análisis del mercado de automóviles

## Planteamiento del problema:

Nuestro cliente desea ingresar a nuestro mercado de automóviles, por lo que busca analizar las características de los vehículos presentes en el mercado actual. Dado que tienen en su catálogo una amplia colección de modelos de todo tipo, cuyo catálogo está estratificado en gamas según el gusto de cada región, desean saber qué características presentan los vehículos de gama alta y los de gama baja en nuestro mercado, para poder abarcar todo los públicos objetivos ajustándose a toda la demanda y poder cotizar correctamente los vehículos que ofrecerá. 

## Objetivos:
El objetivo principal es analizar y procesar los datos del mercado de automóviles para desarrollar dos modelos predictivos:

​1. Implementar un modelo de regresión supervisado: que permite predecir el precio final de los vehículos, utilizando los datos que se han puesto a su disposición.

2. Implementar un modelo de clasificación supervisado: que permite clasificar los vehículos en gama alta y gama baja usando la mediana de los precios como punto de corte, utilizando los datos que se han puesto a su disposición.

## Contenido del Análisis:
Para el logro de nuestros objetivos se ha realizado a través de tres bloques:
### 1. Exploración y preprocesamiento de datos:
En este punto se ha realizado la carga y exploración del dataset, se explora la calidad de los datos para realizar la limpieza y modificación de los datos.

### 2. Análisis exploratorio de datos (EDA):
En esta fase, se cargó el conjunto de datos y se realizó una exploración inicial para evaluar su calidad. Se aplicaron técnicas de limpieza y transformación de datos para garantizar que el conjunto estuviera listo para el análisis posterior.

### 3. Modelamiento y evaluación:
En esta etapa, se implementaron y evaluaron diferentes modelos tanto para la predicción del precio como para la clasificación de vehículos:

1. Predicción(regresión):
    - Regresión lineal
    - Random Forest Regressor
2. Clasificación:
    - Regresión logística.
    - K vecinos más cercanos 
    
Posterior al entrenamiento se realiza la evaluación de los modelos, realizando la comparación de las métricas, con el objetivo de seleccionar el modelo que mejor responda al planteamiento del problema.

Selección de los modelos:
Luego de evaluar las métricas de rendimiento y realizar una validación cruzada, se llevó a cabo un análisis comparativo para elegir el modelo más eficiente. Esto permite tomar decisiones informadas y asegurar que los resultados contribuyan efectivamente a resolver el problema planteado.

## Créditos:
Este estudio de mercado se ha realizado como parte de la formación académica de los estudiantes de "Henry".
