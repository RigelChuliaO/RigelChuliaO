# Rigel Chuliá Ortega

**IA aplicada y datos · Entrega de proyectos técnicos de principio a fin**

Ingeniero de telecomunicaciones. Diecinueve años dirigiendo proyectos técnicos  y su alcance,
plazos, economía, equipo y cliente y los tres últimos, en Accenture, construyendo y
manteniendo soluciones de datos e inteligencia artificial en entorno corporativo:
un modelo predictivo en producción en Vertex AI, una integración propia entre BigQuery
y modelos de lenguaje, y cuadros de mando sobre los que se tomaban decisiones.

Ahora finalizo el Máster Universitario en Inteligencia Artificial (VIU), con un TFM
experimental en visión por computador, y construyo en abierto los proyectos que hay
aquí abajo.

📍 Zaragoza · Abierto a oportunidades como **AI Delivery Lead**, **AI Engineer** o
**Data / AI Consultant**, en remoto o híbrido.

---

## Proyectos

### ✨ [Análisis astrométrico del catálogo HYG v4.2](https://github.com/USUARIO/hyg-star-catalog-analysis)
*Proyecto de máster (VIU) — calificación: sobresaliente.*
Derivación de cuatro propiedades físicas que el catálogo no contiene —temperatura
superficial por la relación de Ballesteros, color visual por la ley de Wien, radio estelar
por Stefan-Boltzmann y conversión de distancias con **validación contra casos de control**:
el Sol sale con menos de un 0,3 % de error y el ranking de magnitud reproduce el cielo real.

Análisis propios sobre la cohesión física de las constelaciones y sobre el sesgo
observacional del catálogo, y una sección de limitaciones que delimita dónde el método
deja de ser fiable y por qué.

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` ·

### 🔧 eng-spec-agent · *en desarrollo*
Agente que compone la documentación técnica de proyectos de instalaciones a partir de la
descripción del arquitecto y de un corpus de memorias ya validadas. Detecta datos que
faltan, comprueba la normativa aplicable y redacta solo a partir de texto con trazabilidad.

Principio de diseño: **el modelo no calcula ni inventa normativa**. Las reglas de
aplicabilidad son código con tests; el texto sale de memorias reales; nada se afirma sin cita.

`Python` · `LangGraph` · `RAG` · `embeddings` · `Chroma` · `Pydantic` · `FastAPI` · `pytest` · `GitHub Actions`

### 👁️ Face-PAD — Detección de ataques de presentación facial
*Trabajo Fin de Máster (VIU, 2026). Defensa en septiembre de 2026.*
Clasificación *live* vs *spoof* sobre CelebA-Spoof. CNN diseñada desde cero en PyTorch y
rediseñada después contra el sobreajuste detectado en las curvas de validación: BatchNorm,
dropout espacial y *global average pooling*. Particiones con semilla fija, bucle de
entrenamiento propio con *early stopping* implementado a mano y demostrador en Gradio.

`PyTorch` · `torchvision` · `Hugging Face Datasets` · `Gradio` · `CUDA`

### Otros

- **Aprendizaje por refuerzo profundo (Atari)** — DQN, Double DQN y Dueling DQN sobre
  Space Invaders, 800.000 pasos de entrenamiento y evaluación sobre 100 episodios con
  semillas fijas. Proyecto de máster en equipo.
- **Aplicación educativa de matemáticas con IA generativa** — App Android con generación
  dinámica de problemas mediante la API de Gemini. Proyecto Fin de Ciclo DAM, calificación 10.

---

## Tecnologías

Las separo por dónde las he usado, porque no es lo mismo:

| | |
|---|---|
| **En entorno profesional** | Python · SQL · BigQuery · Vertex AI · Azure OpenAI Service · ETL/ELT · Looker Studio · Power BI (DAX) · Power Platform · Git |
| **En proyectos y formación** | PyTorch · torchvision · Hugging Face Datasets · Gymnasium · Gradio · Pandas · NumPy · Matplotlib · Seaborn · LangChain · Kotlin y Jetpack Compose · Java · Firebase · API de Gemini |

---

## Formación

- **Máster Universitario en Inteligencia Artificial** — [VIU](https://www.universidadviu.com/es/master-inteligencia-artificial), 2025–2026
- **Técnico Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)** — ILERNA, 2026 · nota final 8,8
- **Ingeniero Técnico de Telecomunicaciones** — Universidad de Zaragoza, 2008
- **Técnico Superior en Prevención de Riesgos Laborales** — IMF, 2009

Actualmente preparando la certificación **Google Cloud Professional Machine Learning Engineer**.

---

## Contacto

📫 [rigelchulia@gmail.com](mailto:rigelchulia@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/rigel-chuliá-ortega)

<details>
<summary><b>In English</b></summary>

Telecommunications engineer based in Zaragoza, Spain. Nineteen years leading technical
projects end to end scope, schedule, budget, team and client and, for the last three
at Accenture, building and running data and AI solutions in a corporate environment:
a predictive model in production on Vertex AI, an in-house BigQuery-to-LLM integration
processing up to 10,000 customer surveys per night, and the dashboards behind operational
decisions.

Currently completing an MSc in Artificial Intelligence (VIU) with an experimental thesis
on face presentation attack detection, and building open-source projects in applied AI.

Open to **AI Delivery Lead**, **AI Engineer** and **Data / AI Consultant** roles,
remote or hybrid.

</details>
