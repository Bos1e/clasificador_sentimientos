# Clasificador de Sentimientos con BERT

Este proyecto utiliza el modelo pre-entrenado **DistilBERT** de **Hugging Face** para realizar una tarea de clasificación de sentimientos. El modelo puede analizar textos y clasificarlos en dos categorías: **Positivo** o **Negativo**, según el sentimiento expresado.

## Características
- Clasificación automática de sentimientos utilizando **DistilBERT**.
- Análisis de textos de comentarios, reseñas o publicaciones.
- Interfaz simple para clasificar sentimientos en Google Colab.

## Tecnologías Utilizadas
- **Python**
- **Transformers** de **Hugging Face** para interactuar con modelos preentrenados de NLP.
- **Google Colab** para ejecutar el código sin necesidad de infraestructura local.

## Instalación
1. Clona o descarga este repositorio.
2. Instala las dependencias ejecutando el siguiente comando:

```bash
!pip install transformers torch
```
## 3. Ejecuta el código en Google Colab o tu entorno local.
Ejemplo de Uso
Ingresa un texto en la variable text y el modelo clasificará el sentimiento en Positivo o Negativo.
Puedes cambiar el texto a cualquier comentario, reseña o frase que desees analizar.
## 4. Contribuciones
Si deseas mejorar este proyecto, puedes hacer un fork y enviar un pull request. Las contribuciones son bienvenidas.