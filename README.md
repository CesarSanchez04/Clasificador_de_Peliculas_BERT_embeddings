# Clasificador_de_Peliculas_BERT_embeddings

## Descripción del problema  

En el procesamiento del lenguaje natural (NLP), transformar texto en representaciones numéricas significativas es esencial para tareas como clasificación, análisis de sentimientos, búsqueda semántica o detección de similitud entre frases.  
Sin embargo, los métodos tradicionales como **TF-IDF** o **Bag of Words** pierden contexto y relaciones semánticas profundas entre palabras.  

Este proyecto aborda ese problema implementando una función personalizada que convierte textos en *embeddings* utilizando el modelo **BERT (Bidirectional Encoder Representations from Transformers)**, con soporte para procesamiento por lotes y aceleración con GPU.  
El objetivo es obtener representaciones vectoriales contextuales y robustas que mejoren el rendimiento en distintas aplicaciones de NLP.  

---

## Objetivos del proyecto  

- **Implementar** una función en Python para transformar textos en *embeddings* mediante **BERT-base-uncased** de Hugging Face.  
- **Optimizar** el procesamiento por lotes y la compatibilidad con GPU/CPU para mejorar la eficiencia computacional.  
- **Capturar** el significado contextual de las palabras y frases a través de representaciones vectoriales profundas.  
- **Reutilizar** los *embeddings* en tareas de NLP como clasificación, búsqueda semántica o análisis de similitud.  
- **Comparar** el rendimiento frente a métodos tradicionales de representación de texto como TF-IDF o Bag of Words.  
