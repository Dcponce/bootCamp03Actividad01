# Proyecto de Predicción de Enfermedades Cardíacas

Elección del Conjunto de Datos
    He seleccionado el conjunto de datos "Heart Disease UCI" de Kaggle. Este dataset contiene información sobre diferentes atributos de pacientes y la presencia o ausencia de enfermedades cardíacas. Es adecuado para un problema de clasificación y cuenta con más de 300 filas y varias columnas relevantes.

•	Fuente: Kaggle - https://www.kaggle.com/code/mragpavank/heart-disease-uci/input?select=heart.csv
•	Formato: CSV
•	Columnas clave: age, sex, cp (tipo de dolor de pecho), trestbps (presión arterial en reposo), chol (colesterol sérico), fbs (azúcar en sangre en ayunas), restecg (resultados del electrocardiograma en reposo),    thalach (frecuencia cardíaca máxima alcanzada), exang (angina inducida por el ejercicio), oldpeak (depresión del ST inducida por el ejercicio en relación con el reposo), slope (la pendiente del segmento ST máximo del ejercicio), ca (número de vasos principales coloreados por fluoroscopia), thal (talasemia), target (presencia de enfermedad cardíaca - 0=no, 1=sí).

Observaciones clave del EDA:
•	target: El dataset tiene una distribución relativamente balanceada entre la presencia y ausencia de enfermedad cardíaca.
•	Correlación: Observamos que algunas variables como cp (tipo de dolor de pecho), thalach (frecuencia cardíaca máxima) y exang (angina inducida por el ejercicio) tienen una correlación más fuerte con la variable target.
•	age: Las personas más jóvenes tienden a tener una menor incidencia de enfermedad cardíaca, mientras que la incidencia aumenta con la edad.
•	sex: Hay más hombres en el dataset y la proporción de enfermedad cardíaca es diferente entre sexos.
•	cp: Los tipos de dolor de pecho atípicos (valores más altos) parecen estar más asociados con la presencia de enfermedad cardíaca.
