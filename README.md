# Izan Villarejo

Backend Developer & AI Engineer. Construyo sistemas que integran IA en producción — no demos, no notebooks sueltos.

> *"La IA no es el producto. El sistema que la integra correctamente, sí."*

---

## Lo que hago

Diseño e implemento el backend que rodea a los modelos: pipelines de datos, APIs, automatizaciones. El modelo es una pieza más del sistema, no el objetivo final.

Me especialicé en IA y Big Data después de DAM porque quería entender qué pasa realmente dentro de los modelos antes de ponerlos detrás de una API. Creo que esa base marca la diferencia cuando algo falla en producción.

Si una tarea se repite, la automatizo. Si un proceso falla, lo instrumentalizo. Si un modelo no llega a producción, no sirve.

---

## Stack

**Backend & APIs**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**IA / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Agentes & Orquestación LLM**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)

**Datos & Observabilidad**

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

**Bases de datos**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)

---

## Proyectos

### 🎙️ [AudioSmart](https://github.com/Izanvz/AudioSmart)
Toma un audio y devuelve quién habló, cuándo y de qué. Diarización + transcripción + análisis semántico en un solo pipeline. Elegí WhisperX sobre Whisper estándar porque el alineamiento a nivel de palabra era necesario para que la diarización tuviera sentido real.  
`WhisperX` · `pyannote` · `FastAPI` · `LLMs`

---

### 👁️ [VisuCheck](https://github.com/Izanvz/VisuCheck)
Detecta productos y lee precios en imágenes de lineales de tienda. El mayor reto fue manejar la variabilidad de iluminación sin reentrenar cada vez — al final lo resolví con preprocesado adaptativo antes del OCR.  
`YOLOv8` · `OCR` · `FastAPI` · `SQL`

---

### 🤖 [MeetingAgent](https://github.com/Izanvz/MeetingAgent)
Le das la grabación de una reunión y te saca el resumen, los puntos de acción y quién se comprometió a qué. El flujo está orquestado con LangGraph: cada nodo del grafo maneja una fase del procesado (transcripción, extracción, síntesis), lo que permite controlar el estado entre pasos y reintentar nodos concretos sin reejecutar todo el pipeline.  
`LangGraph` · `LangChain` · `Python` · `FastAPI`

---

### 📈 [BTC-Pred](https://github.com/Izanvz/BTC-Pred)
Forecasting de precio de Bitcoin con LSTM. Proyecto de aprendizaje — el modelo predice razonablemente bien en backtesting, pero en producción real es otra historia. Lo dejé así a propósito.  
`PyTorch` · `LSTM` · `Python`

---

### 🎮 [Aprendiendo-RL](https://github.com/Izanvz/Aprendiendo-RL)
DQN desde cero, sin usar librerías que te escondan lo que pasa. Lo hice así para entender qué falla cuando falla, no solo cuándo funciona.  
`PyTorch` · `DQN` · `Python`

---

## Experiencia

**Desarrollador Backend — TESI** *(julio 2024 – julio 2025 · Valencia, híbrido)*

- Automaticé el pipeline de análisis de audio de principio a fin: transcripción → resúmenes → extracción de keywords con LLMs
- Diseñé las APIs REST en Python, con autenticación por tokens y gestión de sesiones
- Integré los modelos en el sistema de producción con MySQL como capa de persistencia
- Trabajé con el equipo de frontend para que los modelos fueran consumibles como servicios reales, no scripts internos

---

## Formación & Certificaciones

- 🎓 Grado de Especialización en IA y Big Data — IES Jaume II el Just (2023–2024)
- 🎓 Técnico Superior en DAM — IES Jaume II el Just (2020–2022)
- 📜 Machine Learning Specialization — DeepLearning.AI / Stanford (2025)
- 📜 Unsupervised Learning, Recommenders & RL — DeepLearning.AI / Stanford (2025)

---

## Contacto

Busco equipo donde construir sistemas de IA con impacto real. Remoto en España o híbrido en Valencia/Safor.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/izan-villarejo-ai/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://portfolio-izanv.vercel.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:izan.villarejo.ai@gmail.com)
