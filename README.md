# Tarea 3 de Inteligencia Artificial

El objetivo es entender conceptos y técnicas básicas de procesamiento de lenguaje natural
utilizando representaciones basadas en embeddings.

## Tareas

- [x] Cargar la colección de resúmenes (corpus) disponibles en Webcursos y convertirlos en un corpus.
- [ ] Limpiar el corpus (i.e., eliminar stopwords, lematizar)
- [ ] Utilizar _Word2Vec_ para entrenar un modelo vectorial para el corpus previo.
- [ ] Solicitar una consulta al usuario.
- [ ] Convertir la consulta a su respectivo vector según el modelo generado en (3).
- [ ] Comparar el vector de la consulta con cada uno de los vectores de los resúmenes utilizando la similitud coseno.
- [ ] Mostrar los _n_ mejores textos, ordenados de mayor a menor similitud junto con la ubicación real donde se encuentran (URL del Documento).
