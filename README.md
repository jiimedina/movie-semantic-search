# movie-semantic-search
Semantic movie search using TF-IDF and multilingual embeddings

# Movie Semantic Search (NLP Project)

## Descripción

Este proyecto implementa un sistema de búsqueda de películas basado en el significado (semantic search), utilizando embeddings multilingües.

Se compara su desempeño con un enfoque tradicional basado en coincidencia de términos (TF-IDF).

---

## Objetivos

* Implementar un buscador de películas usando TF-IDF (baseline léxico)
* Implementar un sistema de búsqueda semántica con embeddings
* Comparar ambos enfoques
* Evaluar resultados con métricas como Precision@K

---

## Metodología

1. Obtención de datos desde la API de TMDB
2. Preprocesamiento de texto
3. Baseline con TF-IDF
4. Búsqueda semántica con embeddings
5. Cálculo de similitud (cosine similarity)
6. Evaluación de resultados

---

## Estructura del proyecto

```
movie-semantic-search/
│
├── notebooks/
│   ├── 01_extraccion_y_exploracion_tmdb.ipynb
│
└── README.md
```

---

## Tecnologías

* Python
* pandas, numpy
* scikit-learn
* sentence-transformers

---

## Estado del proyecto

🔄 En desarrollo
