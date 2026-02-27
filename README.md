# Hi, I'm Renato Catalán 👋

**Data Scientist | MLOps | AI Automation**  
📍 Santiago, Chile · 📧 renatogcatalan@gmail.com · 
[LinkedIn](https://linkedin.com/in/renato-catalán-muñoz)

---

## About me

Business Engineer from University of Chile with a focus on 
Data Science, MLOps and AI-powered automation. I combine 
business strategy with technical skills to build end-to-end 
data solutions that generate real impact.

Currently building my portfolio around:
- 🤖 ML pipelines with Azure ML Studio and Python SDK
- 📊 Predictive models applied to business problems
- ⚙️ Workflow automation with n8n, Python and LLMs


---

## 🛠️ Tech Stack

**Languages:** Python · SQL  
**ML & MLOps:** Scikit-learn · Hugging Face  
**Automation:** n8n · Make  
**BI & Data:** Power BI · Pandas · Matplotlib  
**Processes:** BPMN 2.0 · Bizagi  

---

## 📂 Featured Projects

| Project | Description | Stack |
|---|---|---|
| [n8n Accounting Automation][link](https://github.com/renatogcatalan/n8n-accounting-automation) | AI-powered personal finance workflow | n8n · Python · OpenAI |
| [Churn Prediction Pipeline](link) | End-to-end ML pipeline with experiment tracking | Scikit-learn · MLflow · FastAPI |
| [LLM Text Classifier](link) | Claims analysis using LLMs and structured outputs | Python · OpenAI API · Pandas |

---

## 📚 Currently learning
- MLOps with Python — Duke University (Coursera)
- Building production-ready AI agents

---

*Open to Data Science and MLOps opportunities in Chile and remotely.*
```

Crea el repo `tu-usuario/tu-usuario` en GitHub, pega esto adaptado con tus datos reales, y ya tienes una portada profesional.

---

## Paso 2 — Subir el proyecto de n8n (2–4 horas)

Este proyecto ya existe, solo hay que empaquetarlo bien para GitHub. La estructura del repositorio debería ser así:
```
n8n-accounting-automation/
│
├── README.md              ← Lo más importante
├── workflow/
│   └── accounting_flow.json   ← El export del workflow de n8n
├── scripts/
│   └── process_data.py        ← Los scripts Python que uses
├── docs/
│   └── workflow_diagram.png   ← Screenshot del workflow en n8n
└── requirements.txt
```

El README de este proyecto es clave. Tiene que responder estas preguntas en orden:

**¿Qué problema resuelve?** → "Manual personal accounting is time-consuming. This workflow automates transaction categorization and monthly reporting using AI."

**¿Cómo funciona?** → Diagrama o descripción del flujo paso a paso.

**¿Qué tecnologías usa y por qué?** → n8n para orquestación, Python para procesamiento, OpenAI para clasificación de categorías.

**¿Cómo se instala y corre?** → Instrucciones claras, aunque sean simples.

**¿Qué resultados da?** → Aunque sea un screenshot del output o del dashboard final.

El video o post que ya subiste a LinkedIn te puede servir de base para escribir el README. No tienes que reinventar, solo traducir ese contenido a formato técnico.

---

## Paso 3 — Proyecto de ML + MLOps (1–2 semanas)

Este es el proyecto más importante para las postulaciones a banca y consultoras. El tema: **predicción de churn bancario**, que es algo que Santander e Itaú hacen en la vida real y lo van a reconocer inmediatamente.

**Dataset:** usa el [Bank Customer Churn Dataset de Kaggle](https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction) — es público, limpio y perfecto para esto.

**La estructura técnica que tiene que tener:**
```
churn-prediction-mlops/
│
├── README.md
├── data/
│   └── raw/                  ← El CSV original
├── notebooks/
│   └── 01_exploration.ipynb  ← EDA inicial
│   └── 02_modeling.ipynb     ← Entrenamiento y comparación
├── src/
│   └── train.py              ← Script de entrenamiento con MLflow
│   └── predict.py            ← Función de inferencia
│   └── api.py                ← API con FastAPI (opcional pero poderoso)
├── mlruns/                   ← Experimentos de MLflow (gitignoreado)
├── requirements.txt
└── Makefile                  ← Comandos simples: make train, make serve

