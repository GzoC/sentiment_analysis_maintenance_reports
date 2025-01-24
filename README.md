# Análisis de Sentimientos en Comentarios de Mantenimiento 🛠️

## Descripción del Proyecto 📋
Este proyecto utiliza técnicas de **Procesamiento de Lenguaje Natural (NLP)** para analizar comentarios de mantenimiento y determinar si el sentimiento expresado en ellos es **positivo**, **negativo** o **neutral**. Es una solución que permite identificar rápidamente posibles áreas de mejora o evaluar el estado general de los equipos y procesos desde la perspectiva de los operarios.

---

## Objetivo 🎯
El objetivo principal es aplicar herramientas de análisis de texto y visualización para transformar datos no estructurados en información útil, que pueda ayudar en la toma de decisiones dentro del ámbito de mantenimiento industrial.

---

## Tecnologías Utilizadas 💻
- **Python** 🐍
- **pandas**: Manipulación de datos.
- **nltk**: Procesamiento de lenguaje natural (VADER para análisis de sentimientos).
- **deep-translator**: Traducción automática para mejorar la precisión del análisis.
- **matplotlib**: Visualización de datos.

---

## Flujo del Proyecto 🔄
1. **Creación del DataFrame**:
   - Comentarios simulados representativos del ámbito industrial.
   
2. **Preprocesamiento del Texto**:
   - Limpieza de datos: Conversión a minúsculas, eliminación de caracteres especiales y puntuación.

3. **Traducción de Textos**:
   - Traducción de los comentarios al inglés usando `deep-translator` para optimizar el análisis con VADER.

4. **Análisis de Sentimientos**:
   - Clasificación de los textos en `Positivo`, `Negativo` o `Neutral` utilizando **VADER**.

5. **Visualización**:
   - Creación de gráficos de barras para analizar la distribución de sentimientos.

---

## Instalación ⚙️
Sigue estos pasos para ejecutar el proyecto en tu entorno local:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/sentiment-analysis-maintenance.git
