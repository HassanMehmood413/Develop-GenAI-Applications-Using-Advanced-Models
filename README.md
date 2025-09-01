# 🚀 Develop GenAI Applications Using Advanced Models

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nCH9cCNYlahcYxmngQNuYjxzCXUgttb4?usp=sharing)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Made with ❤️ in Pakistan](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F-Pakistan-1f8b4c.svg)](#)

> Complete hands-on workshop repo for building GenAI apps (Text ✕ RAG ✕ Image) in **~2 hours**.

---

## 👨‍🏫 Instructors

<table>
<tr>
<td align="center">
<a href="https://github.com/muhammadibrahim313">
<img src="https://github.com/muhammadibrahim313.png" width="100px;" alt="Muhammad Ibrahim"/>
<br />
<sub><b>Muhammad Ibrahim</b></sub>
</a>
<br />
<a href="https://www.linkedin.com/in/ibrahimqasmi313/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="20"/>
</a>
<br />
<a href="https://github.com/muhammadibrahim313">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" height="20"/>
</a>
</td>
<td align="center">
<a href="https://github.com/HassanMehmood413">
<img src="https://github.com/HassanMehmood413.png" width="100px;" alt="Hassan Mehmood"/>
<br />
<sub><b>Hassan Mehmood</b></sub>
</a>
<br />
<a href="https://www.linkedin.com/in/hassan-mehmood413/">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="20"/>
</a>
<br />
<a href="https://github.com/HassanMehmood413">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" height="20"/>
</a>
</td>
</tr>
</table>

---

## 🧭 Table of Contents

- [Quickstart (Colab & Local)](#-quickstart-colab--local)
- [Project Structure](#-project-structure)
- [Secrets & Environment](#-secrets--environment)
- [1) Text Generation (Groq & Gemini)](#1-text-generation-groq--gemini)
- [2) Image Generation (Diffusers / Stability AI)](#2-image-generation-diffusers--stability-ai)
- [3) Mini-RAG Pipeline (PDF ➜ FAISS ➜ LLM)](#3-mini-rag-pipeline-pdf--faiss--llm)
- [4) Data Cleaning Essentials (Pandas)](#4-data-cleaning-essentials-pandas)
- [5) Optional: Lightweight Fine-Tuning (Stability AI + OpenJourney)](#5-optional-lightweight-fine-tuning-flan-t5--lora)
- [6) Gradio Demo UI (Chat + Image)](#6-gradio-demo-ui-chat--image)
- [Results You’ll Achieve](#-results-youll-achieve)
- [Learning Path](#-learning-path)
- [Real-World Applications](#-real-world-applications)
- [License](#-license)
- [Connect](#-connect)

---

## ⚡ Quickstart (Colab & Local)

### 🟨 Colab GPU
```python
# ✅ Runtime -> Change runtime type -> T4 / L4 GPU recommended
!nvidia-smi
pip install -U pip wheel
```

```
# Core
pip install -U google-genai google-generativeai groq python-dotenv
pip install -U torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121  # (CPU? remove index-url)
pip install -U diffusers==0.30.0 accelerate==0.33.0 transformers==4.44.2 safetensors pillow
pip install -U sentence-transformers faiss-cpu pypdf langchain-community
pip install -U pandas numpy scikit-learn matplotlib
pip install -U gradio
```

---

```
genai-workshop/
├─ README.md
├─ .env.example
├─ data/
│  ├─ docs/                 # PDFs for RAG
│  └─ samples/              # toy datasets
├─ models/
│  └─ faiss_index/          # saved vector index
├─ app/
│  ├─ chat_text_groq.py
│  ├─ chat_text_gemini.py
│  ├─ image_sdxl.py
│  ├─ rag_minipipeline.py
│  ├─ data_cleaning.py
│  ├─ finetune_flan_t5_lora.py
│  └─ gradio_demo.py
└─ Makefile
```



## 📬 Connect With Us

We're always happy to help with your AI journey!

**Muhammad Ibrahim**
- 🔗 [LinkedIn](https://www.linkedin.com/in/ibrahimqasmi313/)
- 💻 [GitHub](https://github.com/muhammadibrahim313)

**Hassan Mehmood**
- 🔗 [LinkedIn](https://www.linkedin.com/in/hassan-mehmood413/)
- 💻 [GitHub](https://github.com/HassanMehmood413)

---

<p align="center">
<b>⭐ Star this repo if you found it helpful!</b><br>
<b>🔄 Fork to create your own version!</b><br>
<b>📢 Share with your network!</b>
</p>

---

**Built with ❤️ by Muhammad Ibrahim & Hassan Mehmood for the Pakistani AI Community**


- **Looks visually appealing** with the instructor table
- **Maintains professional tone** while being engaging
