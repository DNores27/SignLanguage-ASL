# Proyecto SignRecon-V1: Reconocimiento de Lenguaje de Señas (ASL)

## Descripción del Proyecto
Este proyecto utiliza técnicas de Visión por Computadora y Machine Learning (MediaPipe + Clasificadores Scikit-learn) para detectar e interpretar el Alfabeto del Lenguaje de Señas Americano (ASL) en tiempo real a través de una webcam.

El objetivo es cerrar la brecha de comunicación permitiendo que la cámara traduzca las señas a texto y voz.

---

## 🛠️ Requisitos e Instalación

### 1. Entorno de Desarrollo
Se recomienda encarecidamente trabajar dentro de un **Entorno Virtual** (`venv`) para aislar las dependencias del sistema operativo.



```bash
# Crear el entorno virtual
python -m venv venv

# Activar el entorno (Windows PowerShell)
.\venv\Scripts\activate
# Si usas Git Bash, usa: source venv/Scripts/activate

## Librerias necesarias para el proyecto
pip install opencv-python mediapipe scikit-learn numpy joblib pyttsx3 tqdm

´´´bash

###