# 🧠 Detección Automática de Idiomas: EuroParl

Este proyecto implementa un sistema completo de **identificación automática de idiomas** utilizando distintas técnicas de procesamiento de lenguaje natural (NLP), tanto tradicionales como basadas en Deep Learning. El objetivo es comparar el rendimiento de diferentes enfoques para determinar cuál es el más eficaz en esta tarea.

Se utiliza el **Europarl Parallel Corpus**, un conjunto de datos multilingüe compuesto por intervenciones parlamentarias traducidas a varios idiomas oficiales de la Unión Europea.

---

## 📁 Estructura del Proyecto

El proyecto sigue una estructura modular, desde la carga de datos hasta la construcción de un pipeline de clasificación. Las etapas son las siguientes:

1. **Carga y preparación de los datos**  
   - Proceso ETL (Extract, Transform and Load) del corpus multilingüe.

2. **Exploración de los datos**  
   - Análisis de la distribución de idiomas.  
   - Visualización de estadísticas y vocabulario por idioma.

3. **Preprocesamiento textual**  
   - Tokenización y limpieza avanzada.  
   - Consideraciones sobre stopwords y normalización del texto.

4. **Representación vectorial**  
   - Aplicación de técnicas de vectorización como **TF-IDF**.  
   - Análisis de alternativas y su impacto en el rendimiento.

5. **Entrenamiento de clasificadores**  
   - Implementación de modelos clásicos como **Naive Bayes**, **SVM** y **Random Forest**.  
   - Entrenamiento de modelos LSTM (unidireccional y bidireccional) con TensorFlow/Keras.  
   - Evaluación comparativa.

6. **Conclusiones y pipeline final**  
   - Discusión sobre el rendimiento de los modelos.  
   - Justificación del modelo final escogido.  
   - Descripción del pipeline completo de detección automática.

