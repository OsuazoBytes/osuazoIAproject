# Osman Suazo

# 📊 Análisis y Clasificación de Comentarios con Machine Learning  

Este proyecto tiene como propósito analizar comentarios de usuarios, encontrar tendencias y clasificar los comentarios en diferentes categorías. Esto permitirá identificar los temas más frecuentes y brindar oportunidades de coaching y mejora en la experiencia del usuario.  

## 🚀 Características  

✅ Traducción automática de comentarios a inglés para mejorar la clasificación.  
✅ Limpieza de texto eliminando caracteres innecesarios y palabras irrelevantes (stopwords).  
✅ Uso de **Naïve Bayes** para clasificar comentarios en categorías como problemas técnicos, felicitaciones, quejas, etc.  
✅ Reentrenamiento continuo del modelo sin perder el aprendizaje previo.  
✅ Generación de un archivo con las clasificaciones y niveles de confianza.  

## 🛠️ Tecnologías utilizadas  

- Python  
- `scikit-learn` (para el modelo de Machine Learning)  
- `pandas` (para el manejo de datos)  
- `nltk` (para limpieza de texto)  
- `googletrans` (para traducción automática)  
- `joblib` (para guardar y cargar el modelo)  

## 📂 Archivos clave  

| Archivo | Descripción |
|---------|------------|
| `entrenamiento.py` | Script para entrenar y mejorar el modelo con nuevos datos. |
| `clasificacion.py` | Script que clasifica nuevos comentarios y asigna una categoría con nivel de confianza. |
| `comentarios_nuevos.csv` | Archivo de entrada con comentarios a clasificar. |
| `comentarios_clasificados.csv` | Resultados con categorías y niveles de confianza. |
| `modelo_comentarios.pkl` | Modelo entrenado y guardado para futuras predicciones. |
| `vectorizador.pkl` | Vectorizador de texto para transformar comentarios en datos utilizables por el modelo. |

## 🔧 Instalación y Uso  

1️⃣ Clonar el repositorio:  
```bash
git clone https://github.com/tu-usuario/nombre-del-repo.git
cd nombre-del-repo
