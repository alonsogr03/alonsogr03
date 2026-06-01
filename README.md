<div align="center">
  <h1>👋 ¡Hola! Soy Alonso González Romero</h1>
  <h3><i>Data Scientist & AI Specialist en Sports Analytics</i></h3>
</div>

---

🎓 **Graduado en Matemáticas** por la Universidad Rey Juan Carlos (URJC) | 🏆 **Matrícula de Honor en TFG**.  
🎯 Especializándome con el **Máster en Análisis de Datos Deportivos (MUSA - URJC)**.

Mi objetivo es combinar la **matemática aplicada**, la **Inteligencia Artificial** y la **Ingeniería de Datos** para aportar ventajas competitivas en el ámbito deportivo. Busco desarrollarme como un perfil integral (Full-Stack Data Scientist), abarcando desde la arquitectura e ingesta de datos y el diseño de agentes LLM, hasta la modelización predictiva y la visualización interactiva.

---

## 🧠 Áreas de Especialización
- 🤖 **IA Generativa & Sistemas Multi-Agente** (LLMs, RAG, LangGraph)
- ⚙️ **Data Engineering & Streaming** (Spark, Kafka, Docker)
- 📊 **Ciencia de Datos & ML Predictivo** (Clustering, Random Forest, Regresión)
- 🏃‍♂️ **Análisis de Rendimiento Deportivo (Sports Analytics)**

---

## 💻 Stack Tecnológico

**IA, LLMs & Machine Learning** <br>
<img src="https://img.shields.io/badge/LangGraph-005073?style=for-the-badge&logo=openai&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/LLMs_%26_GenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="GenAI" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />

**Data Engineering, Streaming & DevOps** <br>
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Spark" />
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
<img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />

**Data Viz & BI** <br>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
<img src="https://img.shields.io/badge/Shiny-004D40?style=for-the-badge&logo=r&logoColor=white" alt="Shiny" />
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />

---

## 📂 Proyectos Destacados

### 🎙️ [Sistema de Narración de Carreras en Tiempo Real con IA y Streaming](#)
Arquitectura *end-to-end* orquestada en **Docker** para procesar telemetría deportiva en directo y generar comentarios automáticos:
*   **Ingesta y Procesamiento Stateful:** Simulación de datos de carrera en directo vía **Kafka**, consumidos por **Apache Spark**. Diseño de dos tuberías paralelas: una para calcular y persistir el último parcial de un corredor específico usando gestión de estados, y otra que utiliza *timeouts* de 5s para calcular grupos de carrera y roturas (escapadas), enviando las actualizaciones a una base de datos ligera.
*   **Sistema Multi-Agente:** Interfaz en **Streamlit** que realiza *polling* a la BBDD cada 3s y envía las nuevas métricas a dos agentes LLM concurrentes (uno de flujo lineal y otro condicional).
*   **RAG Contextual:** El agente "Coach" utiliza RAG para comparar el rendimiento con la estrategia ideal del corredor, mientras que el agente "Narrador" se apoya en datos históricos de roturas de otras carreras para vitaminar la retransmisión con un enfoque analítico.

### 🏊 [TFM: SwimData Spain](#) *(En desarrollo)*
Arquitectura integral de datos y modelado avanzado para el análisis del rendimiento en natación:
*   **Extracción (Generative AI):** Uso de **LLMs** para extraer datos estructurados (JSON) a partir de reportes y textos deportivos no estructurados.
*   **Almacenamiento Documental:** Ingesta y gestión de la información procesada utilizando **MongoDB**.
*   **Machine Learning Avanzado:** Implementación de **Clustering Simbólico** para descubrir patrones y agrupar a los nadadores en función de sus resultados y perfiles de rendimiento histórico.

### 🏃‍♂️ [Modelado Predictivo Avanzado en Maratón](#)
*   Desarrollo *from scratch* de un algoritmo de **Random Forest** con validación cruzada para optimizar hiperparámetros y predecir el riesgo de rotura física ("el muro") en maratonianos.
*   Entrenamiento de modelos de **Regresión Lineal Múltiple** evaluando interacciones de variables para proyectar con alta precisión los tiempos finales de maratón basándose en los parciales hasta el kilómetro 35.

### 🥇 [TFG: Clustering Dinámico y Análisis de Pacing](#)
*Matrícula de Honor.* Implementación de una nueva aproximación para algoritmos de *clustering* en *streaming* y análisis de estrategias de carrera en nadadores utilizando **K-Means** y **distancia DTW**.

### 🎓 [Proyectos del Máster MUSA](#)
Colección de repositorios enfocados en analítica avanzada aplicada al deporte: desarrollo de métricas espaciales en fútbol (StatsBomb) y creación de cuadros de mando y aplicaciones analíticas *Head-to-Head* en BI.

---

## 🌐 Conecta conmigo
<div align="center">
  <a href="https://www.linkedin.com/in/alonsogr03"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:alonsogonro@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</div>

<br>
