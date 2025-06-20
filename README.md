# EraBot – Clasificador de Época Visual con IA

EraBot es un bot de Discord que utiliza inteligencia artificial para analizar imágenes y clasificarlas según la **época histórica o visual** que representan. ¿La imagen parece del siglo XIX, de los años 80 o de un futuro distópico? Este bot lo adivina por ti.

## 📌 Descripción

Erabot permite a los usuarios enviar imágenes en un canal de Discord y recibir una respuesta automática indicando a qué época visual pertenece la imagen, basada en elementos como:

- Estilo de vestimenta
- Arquitectura
- Paleta de colores
- Composición artística
- Elementos tecnológicos o simbólicos

Este bot es ideal para servidores de arte, historia, roleplay, diseño, cultura pop o simplemente para divertirse adivinando la “epoca probable” de una imagen.

### ⚙️ ¿Cómo funciona?

1. Los usuarios envían una imagen en un canal habilitado.
2. El bot extrae características visuales y las analiza usando un modelo de visión por computadora (CNN + clasificadores entrenados).
3. Devuelve un mensaje con la época estimada (ej. “90s”, “80s”, “70s”) junto con una puntuación de confianza.

### 🔍 Tecnologías utilizadas

- Python + discord.py
- TensorFlow/Keras
- Modelos preentrenados 
- PIL para preprocesamiento
