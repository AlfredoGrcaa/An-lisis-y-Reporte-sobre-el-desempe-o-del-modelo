# Analisis-y-Reporte-sobre-el-desempeño-del-modelo
Análisis y Reporte sobre el desempeño del modelo

## En la carpeta final se encuentran los archivos finales de la actividad

### En modelo.ipynb;
- Se encuentra el entrenamiento y la evaluación del desempeño del modelo
- Se ecnuentras las respuestas de la actividad

### En reporte.md
- Reporte de la actividad y resultados

### train.csv - test.csv
- Son los archivos que se usaron para entrenar y evaluar el modelo

### En 'contexto y normatividad.pdf'
- Es la explicación para el requisito de la subcompetencia SEG0403

## En la carpeta retro se encuentran los archivos de la actividad de retroalimentación

### En modelo.ipynb;
- Se encuentra el entrenamiento y la evaluación del desempeño del modelo
- Se ecnuentras las respuestas de la actividad

### En modelo.pdf
- Reporte de la actividad y resultados

### train.csv - test.csv
- Son los archivos que se usaron para entrenar y evaluar el modelo

## Regresión logística

Claro, puedo darte una explicación y resumen de cómo funciona la regresión logística.

**Regresión Logística: Resumen**

La regresión logística es un método estadístico utilizado principalmente para problemas de clasificación binaria, es decir, cuando quieres predecir si un evento o resultado pertenece a una de dos categorías, como sí/no, 1/0, o positivo/negativo. Aunque el nombre contiene la palabra "regresión", en realidad se trata de un algoritmo de clasificación.

**Cómo funciona:**

1. **Definición de variables independientes:** Comienza reuniendo datos y definiendo tus variables independientes (predictoras) y la variable dependiente (la que quieres predecir o clasificar). Por ejemplo, si deseas predecir si un estudiante aprobará o no un examen, las variables independientes podrían ser horas de estudio y calificaciones previas, y la variable dependiente sería si el estudiante aprobó (1) o no (0).

2. **Transformación logística:** La regresión logística utiliza una función logística (también conocida como función sigmoide) para transformar la combinación lineal de las variables independientes en un valor entre 0 y 1, que se interpreta como la probabilidad de que el resultado pertenezca a la categoría positiva (1). La función logística tiene la forma:

   $\[P(Y=1) = \frac{1}{1 + e^{-(b_0 + b_1X_1 + b_2X_2 + \ldots + b_nX_n)}}\]$

   Donde:
   - $\(P(Y=1)\)$ es la probabilidad de que el resultado sea 1.
   - $\(b_0, b_1, b_2, \ldots, b_n\)$ son los coeficientes de la regresión que se ajustan durante el entrenamiento.
   - $\(X_1, X_2, \ldots, X_n\)$ son los valores de las variables independientes.

3. **Entrenamiento del modelo:** El objetivo es encontrar los mejores valores para los coeficientes \(b_0, b_1, b_2, \ldots, b_n\) que minimicen el error en las predicciones. Esto se hace mediante técnicas de optimización, como la maximización de la verosimilitud.

4. **Umbral de decisión:** Para realizar una clasificación, debes definir un umbral de decisión, típicamente 0.5. Si la probabilidad predicha es mayor que el umbral, clasificas el resultado como 1; de lo contrario, lo clasificas como 0.

5. **Evaluación del modelo:** Para evaluar qué tan bien funciona el modelo, se utilizan métricas como precisión, exhaustividad, F1-score y la curva ROC, entre otras.

6. **Predicciones:** Con el modelo entrenado y evaluado, puedes usarlo para hacer predicciones en nuevos datos desconocidos.

En resumen, la regresión logística es una técnica de aprendizaje supervisado que se utiliza para problemas de clasificación binaria. Transforma la combinación lineal de las variables independientes en una probabilidad utilizando una función logística y ajusta los coeficientes para hacer predicciones y tomar decisiones de clasificación.

## Dataset del Titanic

*Nombre del Conjunto de Datos:* Titanic: Machine Learning from Disaster

*Descripción:*
Este conjunto de datos es uno de los conjuntos de datos más populares en la comunidad de aprendizaje automático. Contiene información sobre los pasajeros del famoso barco Titanic, incluyendo si sobrevivieron o no al naufragio. El conjunto de datos se utiliza comúnmente para tareas de aprendizaje automático de clasificación, donde el objetivo es predecir si un pasajero sobrevivió o no en función de diversas características.

*El conjunto de datos incluye las siguientes columnas (variables):*

- *PassengerId:* Identificación única del pasajero.
- *Survived:* Variable objetivo (0 = No sobrevivió, 1 = Sobrevivió).
- *Pclass:* Clase del billete (1 = Primera clase, 2 = Segunda clase, 3 = Tercera clase).
- *Name:* Nombre del pasajero.
- *Sex:* Género del pasajero.
- *Age:* Edad del pasajero.
- *SibSp:* Cantidad de hermanos/cónyuges a bordo.
- *Parch:* Cantidad de padres/hijos a bordo.
- *Ticket:* Número de boleto.
- *Fare:* Tarifa del billete.
- *Cabin:* Número de cabina.
- *Embarked:* Puerto de embarque (C = Cherbourg, Q = Queenstown, S = Southampton).

URL del Conjunto de Datos en Kaggle:
Puedes acceder al conjunto de datos del Titanic en Kaggle a través de la siguiente URL: [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)