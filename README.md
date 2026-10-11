# 👋 Hi, I'm Saugata Roy Arghya!

**AI & Automation Developer | Machine Learning, NLP, and Agent Systems**

I build AI applications—from training and evaluating models to serving them through APIs and integrating them into workflows.

## 🚀 About Me

- I work mainly with **Python, TypeScript, SQL, and C++**.
- My projects span **NLP, model serving, AI agents, and automation**.
- I'm interested in multilingual NLP, bias in language models, and the infrastructure that makes AI systems useful in practice.

## 🏆 Featured Projects
### 📝 IELTS Scoring — writing, speaking and inference

[Writing Scoring](https://github.com/saugataroyarghya/ielts-writing-scoring) · [Speaking Scorer](https://github.com/saugataroyarghya/ielts-speaking-scorer) · [Inference API](https://github.com/saugataroyarghya/ielts-inference-api) · [Writing Model](https://huggingface.co/saugataroy/ielts-task2-modernbert-base-moe/tree/ad150d954cc9af7fa848fedeafeef6c28c71e2c6) · [Speaking Model](https://huggingface.co/saugataroy/ielts-speaking-scorer)

- **Built:** An experimental IELTS scoring project covering **model training, evaluation, publication, and API serving**.
- **Model engineering:** ModernBERT transfer learning with MLP and dense MoE heads; a **LoRA-adapted audio encoder and frozen text encoder** for speaking.
- **Writing:** **1.1289 macro MAE** on **450 Writing9-labeled holdout essays** for the API-pinned checkpoint, predicting **4 Task 2 criteria**.
- **Speaking:** **0.8721 mock-band MAE** on **43 recordings** — **47% lower** than the training-median baseline.
- **Serving:** **2 authenticated BentoML endpoints** with input validation, audio preprocessing, pinned artifacts, and separate adaptive batching workers.
- **Reproducibility:** Grouped data splits, baseline comparisons, published training/evaluation source, model provenance, and source-check CI.

*Experimental scores; independent IELTS examiner validation has not been established.*


### 🧠 [NLP Serving](https://github.com/saugataroyarghya/nlp-serving)

A **BentoML playground for specialized NLP models**, including GLiNER, Laya, and KeyBERT.

- APIs for entity and relation extraction, classification, structured extraction, and closed-set decisions.
- Isolated environments for conflicting dependencies, with API tests and documented model limitations.

### 🔐 OpenClaw Agent Middleware
[Credential Vault](https://github.com/saugataroyarghya/openclaw-credential-vault) · [File Guard](https://github.com/saugataroyarghya/openclaw-file-guard)

Two plugins for authentication and permission management in shared AI agents.

- **Credential Vault:** per-user OAuth/API-key handling, encrypted storage, token refresh, channel policies, and audit logging.
- **File Guard:** file ownership and access grants, with middleware checks before supported file-modification tools execute.

### 📚 [AI Research Radar](https://github.com/saugataroyarghya/ai-research-radar)

An event-driven pipeline for discovering and organizing AI research papers using **Airflow, Kafka, Ollama embeddings, and PostgreSQL**.

### 🕒 [Analog Clock Reader](https://github.com/saugataroyarghya/Analog-Clock-Reader)

Reads time from clock images using **classical image processing**, including contour detection and Hough transforms. Includes intermediate visualizations, a project report, and documented failure cases.

## 🛠️ Tools I Work With

| Area | Technologies |
|---|---|
| Languages | Python, TypeScript, SQL, C++ |
| ML & NLP | PyTorch, scikit-learn, Hugging Face Transformers, OpenCV, UnSloth ONNX |
| APIs & Agents | BentoML, FastAPI, LangChain, LangGraph, MCP, OAuth2 |
| Infrastructure & Automation | Docker, PostgreSQL, Kafka, Airflow, n8n |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21F?style=flat-square&logo=huggingface&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Unsloth](https://img.shields.io/badge/Unsloth-%2310B981?style=flat-square&logo=python&logoColor=white)

## 🔬 Research Interests

I'm investigating **bias in large language models**, with interests in multilingual NLP, fairness, and model evaluation. I enjoy exploring how models behave beyond their aggregate benchmark scores.

## 🤝 Open to Collaboration

Interested in working together on **applied ML, NLP, or agent systems**? Feel free to reach out.

## ⚽ Beyond Code

I enjoy learning about different cultures and history. Football is my sport of choice—on the field and in gaming!

## 📫 Get in Touch

[Email](mailto:saugataroyarghya@gmail.com) · [Hugging Face](https://huggingface.co/saugataroy) . [LinkedIn](https://www.linkedin.com/in/saugataroyarghya)
