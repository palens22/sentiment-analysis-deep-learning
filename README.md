# Análisis de Sentimiento con Deep Learning

**Trabajo Fin de Máster (TFM)** - Universidad de Valencia  
**Calificación:** 8.4/10  
**Año:** 2025

## 📋 Descripción

Sistema de análisis de sentimiento aplicado a reviews de series de anime, comparando el rendimiento de diferentes arquitecturas de Deep Learning: CNN, LSTM y Transformers (DistilBERT). El proyecto aborda el desafío de trabajar con datasets desbalanceados y compara tanto modelos entrenados desde cero como modelos preentrenados.

## 🎯 Objetivos

- Implementar y comparar arquitecturas CNN, LSTM y DistilBERT para análisis de sentimiento
- Desarrollar un sistema de scraping ético para recopilación de datos
- Gestionar datasets desbalanceados mediante técnicas de balanceo
- Crear modelos ensemble que combinen las fortalezas de diferentes arquitecturas
- Documentar el proceso experimental completo y analizar resultados

## 🗂️ Estructura del Proyecto
```
notebooks/
├── Scraping_MyAnimeList.ipynb           # Web scraping de reviews con rate limiting ético
├── Cleaning_Data.ipynb      # Limpieza y preprocesamiento de datos
├── TFM_CNN_v2.ipynb         # Implementación y entrenamiento de CNN
├── TFM_LTSM_v2.ipynb         # Implementación y entrenamiento de LSTM
├── TFM_Transformer_v2.ipynb  # Fine-tuning de DistilBERT
└── TFM_Ensemble.ipynb   # Modelos ensemble y análisis de resultados
```

## 🛠️ Tecnologías Utilizadas

- **Python 3.x**
- **Deep Learning:** TensorFlow, Keras
- **NLP:** Transformers (Hugging Face), DistilBERT
- **Data Processing:** Pandas, NumPy
- **Web Scraping:** BeautifulSoup, Selenium
- **Visualización:** Matplotlib, Seaborn
- **ML Tools:** Scikit-learn

## 📊 Dataset

- **Fuente:** MyAnimeList (scraping ético con rate limiting)
- **Tamaño:** 10,000+ reviews de series
- **Características:** Dataset desbalanceado
- **Clases:** Sentimiento positivo, neutral, negativo

## 🚀 Resultados Principales

El proyecto logró:
- Comparativa exhaustiva entre arquitecturas clásicas (CNN, LSTM) y modernas (Transformers)
- Implementación exitosa de técnicas de balanceo para datasets desbalanceados
- Desarrollo de modelos ensemble que mejoran el rendimiento individual
- Documentación completa del proceso experimental con análisis de resultados

## 📝 Metodología

1. **Recopilación de datos:** Web scraping con implementación de rate limiting ético
2. **Preprocesamiento:** Pipeline de limpieza, tokenización y feature engineering
3. **Modelado:** Entrenamiento de CNN, LSTM y fine-tuning de DistilBERT
4. **Balanceo:** Técnicas para manejar datasets desbalanceados
5. **Ensemble:** Combinación de modelos para mejorar predicciones
6. **Evaluación:** Análisis comparativo de métricas y resultados

## 🎓 Contexto Académico

Este proyecto fue desarrollado como Trabajo Fin de Máster del **Máster en Inteligencia Artificial y Bases de Datos** de la Universidad Católica de Valladolid, obteniendo una calificación de **8.4/10**.

## 👤 Autor

**Antonio Palencia Cañas**  
Ingeniero Multimedia | Máster en IA y Bases de Datos  
📧 apc.dpc.palens@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/antonio-palencia-7a242a328/)

## 📄 Licencia

Este proyecto es de carácter académico.

---

⭐ Si este proyecto te resulta útil o interesante, ¡no dudes en darle una estrella!
