# Sleep_health
Implementación en Machine Learning para predicciones de enfermedades o desordenes en el sueño.

El objetivo principal es construir un modelo predictivo para identificar desórdenes del sueño basado en un conjunto de características 
de salud y estilo de vida, optimizando el modelo y evaluando su rendimiento para asegurarse de que sea efectivo. El propósito 
fundamental de esta notebook es  predecir desórdenes del sueño basándose en datos de salud y estilo de vida. En el desarrollo se 
realizarán procesos como:

1. Carga y Exploración de Datos:

Importar el conjunto de datos de salud y estilo de vida desde Google Drive.
Realizar una exploración inicial de los datos para entender su estructura y contenido, identificar la cantidad de datos faltantes y la distribución de la variable objetivo ('Sleep Disorder').

2. Preprocesamiento de Datos:

Limpiar y preparar los datos para el modelado.
Convertir las variables categóricas en variables numéricas utilizando técnicas como one-hot encoding.
Manejar los datos faltantes mediante la imputación de valores.

3. Selección y Transformación de Características:

Crear pipelines de preprocesamiento para las variables numéricas y categóricas.
Escalar las variables numéricas y convertir las categóricas en formato adecuado para el modelo.

4. División de Datos en Conjuntos de Entrenamiento y Prueba:

Dividir los datos en conjuntos de entrenamiento y prueba para evaluar el rendimiento del modelo.

5. Definición y Entrenamiento del Modelo:

Configurar un modelo de ExtraTreesClassifier y usar GridSearchCV para encontrar los mejores hiperparámetros.
Entrenar el modelo utilizando el conjunto de entrenamiento.

6. Evaluación del Modelo:

Evaluar el rendimiento del modelo en el conjunto de prueba utilizando métricas como el informe de clasificación (classification_report).
