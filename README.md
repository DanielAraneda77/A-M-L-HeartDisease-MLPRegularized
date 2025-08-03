# ❤️ HeartDisease-MLPRegularized

## Clasificación de enfermedad cardíaca con MLP regularizado

Este proyecto implementa una red neuronal MLP avanzada para predecir la presencia de enfermedad cardíaca utilizando el dataset [Heart Disease UCI – Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci).  
Se incorporan técnicas de regularización como **Dropout** y **Early Stopping** para evitar el sobreajuste y mejorar la capacidad de generalización.

---

## Técnicas utilizadas

- Normalización de variables clínicas con `StandardScaler`
- Arquitectura MLP con dos capas ocultas y activación ReLU
- Dropout (20–30%) para reducir sobreajuste entre capas ocultas
- Early Stopping (paciencia de 5 épocas) para detener entrenamiento preventivo
- Optimización con `Adam` y función de pérdida `binary_crossentropy`
- Visualización de curvas de aprendizaje (pérdida y precisión)
- Evaluación con `accuracy`, `precision`, `recall`, `f1_score` y matriz de confusión

---

## Resultados

### Métricas de evaluación

| Métrica      | Valor     |
|--------------|-----------|
| Accuracy     | 0.8478    |
| Precision    | 0.8426    |
| Recall       | 0.8922    |
| F1-score     | 0.8667    |

- **Precision**: El 84.26% de los pacientes predichos como enfermos realmente tenían la enfermedad.
- **Recall**: El modelo identificó correctamente el 89.22% de los casos positivos, mostrando alta sensibilidad.
- **F1-score**: Buen balance entre precisión y recall, modelo sólido.

### Matriz de confusión

| Predicción          | Casos |
|---------------------|-------|
| Verdaderos Positivos| 91    |
| Verdaderos Negativos| 65    |
| Falsos Positivos    | 17    |
| Falsos Negativos    | 11    |

> El modelo está optimizado para detectar pacientes con enfermedad cardíaca (recall elevado), minimizando errores críticos.

---

## Análisis de curvas

- **Curva de precisión**: Validación estable entre 83–85%, sin grandes fluctuaciones.
- **Curva de pérdida**: Se estabiliza sin mostrar señales claras de sobreajuste.

---

## Conclusión

El uso de **Dropout** y **Early Stopping** ha fortalecido el modelo frente al sobreajuste, mejorando la estabilidad y generalización comparado con una MLP básica.

Esta red neuronal permite realizar una clasificación confiable en contextos médicos, detectando de forma precisa la enfermedad y minimizando errores graves como falsos negativos.

---

## 👤 Conéctate conmigo

[![Conectar en LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin&style=flat-square)](https://www.linkedin.com/in/daniel-araneda-yasic)

¿Eres reclutador o profesional del sector interesado en proyectos aplicados de Data Science, visualización de datos o inteligencia artificial eficiente?  
Este proyecto refleja mi enfoque técnico y comunicativo, y estoy abierto a oportunidades laborales, colaboración en equipos multidisciplinarios y desarrollo de soluciones prácticas y reproducibles.

📫 No dudes en contactarme para conversar sobre cómo puedo aportar valor desde la intersección entre análisis técnico, creatividad visual y documentación didáctica.


