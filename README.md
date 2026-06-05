<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                   ANIMATED NEURAL BANNER                       -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<svg width="900" height="220" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0a0a0f;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#0d1117;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#0a0a1a;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#7b2fff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff006e;stop-opacity:1" />
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#7b2fff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff006e;stop-opacity:0" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Background -->
  <rect width="900" height="220" fill="url(#bgGrad)" rx="16"/>

  <!-- Grid lines (cyberpunk) -->
  <g opacity="0.08" stroke="#00d4ff" stroke-width="0.5">
    <line x1="0" y1="40" x2="900" y2="40"/>
    <line x1="0" y1="80" x2="900" y2="80"/>
    <line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="160" x2="900" y2="160"/>
    <line x1="0" y1="200" x2="900" y2="200"/>
    <line x1="100" y1="0" x2="100" y2="220"/>
    <line x1="200" y1="0" x2="200" y2="220"/>
    <line x1="300" y1="0" x2="300" y2="220"/>
    <line x1="400" y1="0" x2="400" y2="220"/>
    <line x1="500" y1="0" x2="500" y2="220"/>
    <line x1="600" y1="0" x2="600" y2="220"/>
    <line x1="700" y1="0" x2="700" y2="220"/>
    <line x1="800" y1="0" x2="800" y2="220"/>
  </g>

  <!-- Neural network nodes (left side) -->
  <g filter="url(#glow)">
    <!-- Input layer -->
    <circle cx="60" cy="60" r="5" fill="#00d4ff" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="60" cy="100" r="5" fill="#00d4ff" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="60" cy="140" r="5" fill="#00d4ff" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.4;0.9" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="60" cy="180" r="5" fill="#00d4ff" opacity="0.6">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
    </circle>
    <!-- Hidden layer 1 -->
    <circle cx="120" cy="75" r="5" fill="#7b2fff" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.2;0.8" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="120" r="5" fill="#7b2fff" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.5;0.9" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="120" cy="165" r="5" fill="#7b2fff" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2.8s" repeatCount="indefinite"/>
    </circle>
    <!-- Hidden layer 2 -->
    <circle cx="180" cy="85" r="5" fill="#ff006e" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="130" r="5" fill="#ff006e" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.4;0.9" dur="1.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="180" cy="175" r="5" fill="#ff006e" opacity="0.6">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2.3s" repeatCount="indefinite"/>
    </circle>
    <!-- Output node -->
    <circle cx="240" cy="120" r="7" fill="#00ffaa" opacity="0.9">
      <animate attributeName="r" values="7;10;7" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.9;0.5;0.9" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Neural connections -->
  <g stroke="#00d4ff" stroke-width="0.5" opacity="0.2">
    <line x1="65" y1="60" x2="115" y2="75"/>
    <line x1="65" y1="60" x2="115" y2="120"/>
    <line x1="65" y1="100" x2="115" y2="75"/>
    <line x1="65" y1="100" x2="115" y2="120"/>
    <line x1="65" y1="100" x2="115" y2="165"/>
    <line x1="65" y1="140" x2="115" y2="120"/>
    <line x1="65" y1="140" x2="115" y2="165"/>
    <line x1="65" y1="180" x2="115" y2="165"/>
    <line x1="125" y1="75" x2="175" y2="85"/>
    <line x1="125" y1="75" x2="175" y2="130"/>
    <line x1="125" y1="120" x2="175" y2="85"/>
    <line x1="125" y1="120" x2="175" y2="130"/>
    <line x1="125" y1="120" x2="175" y2="175"/>
    <line x1="125" y1="165" x2="175" y2="130"/>
    <line x1="125" y1="165" x2="175" y2="175"/>
    <line x1="185" y1="85" x2="233" y2="120"/>
    <line x1="185" y1="130" x2="233" y2="120"/>
    <line x1="185" y1="175" x2="233" y2="120"/>
  </g>

  <!-- Neural connections (right side mirror) -->
  <g stroke="#ff006e" stroke-width="0.5" opacity="0.2">
    <line x1="835" y1="60" x2="785" y2="75"/>
    <line x1="835" y1="60" x2="785" y2="120"/>
    <line x1="835" y1="100" x2="785" y2="75"/>
    <line x1="835" y1="100" x2="785" y2="120"/>
    <line x1="835" y1="140" x2="785" y2="120"/>
    <line x1="835" y1="140" x2="785" y2="165"/>
    <line x1="835" y1="180" x2="785" y2="165"/>
    <line x1="775" y1="75" x2="725" y2="85"/>
    <line x1="775" y1="75" x2="725" y2="130"/>
    <line x1="775" y1="120" x2="725" y2="85"/>
    <line x1="775" y1="120" x2="725" y2="130"/>
    <line x1="775" y1="165" x2="725" y2="175"/>
    <line x1="715" y1="85" x2="667" y2="120"/>
    <line x1="715" y1="130" x2="667" y2="120"/>
    <line x1="715" y1="175" x2="667" y2="120"/>
  </g>

  <!-- Right neural nodes -->
  <g filter="url(#glow)">
    <circle cx="660" cy="120" r="7" fill="#00ffaa" opacity="0.9">
      <animate attributeName="r" values="7;10;7" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="720" cy="85" r="5" fill="#ff006e" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.3;0.8" dur="2.1s" repeatCount="indefinite"/>
    </circle>
    <circle cx="720" cy="130" r="5" fill="#ff006e" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="1.9s" repeatCount="indefinite"/>
    </circle>
    <circle cx="720" cy="175" r="5" fill="#ff006e" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.4;0.9" dur="2.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="75" r="5" fill="#7b2fff" opacity="0.7">
      <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="120" r="5" fill="#7b2fff" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="780" cy="165" r="5" fill="#7b2fff" opacity="0.8">
      <animate attributeName="opacity" values="0.8;0.5;0.8" dur="2.4s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="60" r="5" fill="#00d4ff" opacity="0.6">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="2.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="100" r="5" fill="#00d4ff" opacity="0.9">
      <animate attributeName="opacity" values="0.9;0.3;0.9" dur="1.8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="140" r="5" fill="#00d4ff" opacity="0.7">
      <animate attributeName="opacity" values="0.7;0.4;0.7" dur="2.7s" repeatCount="indefinite"/>
    </circle>
    <circle cx="840" cy="180" r="5" fill="#00d4ff" opacity="0.8">
      <animate attributeName="opacity" values="0.8;1;0.8" dur="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Floating particles -->
  <g fill="#00d4ff" opacity="0.6">
    <circle cx="300" cy="30" r="2">
      <animateMotion dur="8s" repeatCount="indefinite" path="M0,0 Q50,-20 100,0 Q50,20 0,0"/>
    </circle>
    <circle cx="500" cy="190" r="1.5">
      <animateMotion dur="6s" repeatCount="indefinite" path="M0,0 Q-40,15 -80,0 Q-40,-15 0,0"/>
    </circle>
    <circle cx="600" cy="40" r="2" fill="#7b2fff">
      <animateMotion dur="10s" repeatCount="indefinite" path="M0,0 Q30,-10 60,0 Q30,10 0,0"/>
    </circle>
  </g>

  <!-- Data flow line -->
  <line x1="0" y1="210" x2="900" y2="210" stroke="url(#lineGrad)" stroke-width="1.5" opacity="0.7">
    <animate attributeName="opacity" values="0.7;0.2;0.7" dur="3s" repeatCount="indefinite"/>
  </line>

  <!-- Main title -->
  <text x="450" y="90" text-anchor="middle" font-family="'Courier New', monospace" font-size="36" font-weight="bold" fill="url(#textGrad)" filter="url(#softGlow)">
    ANKIT 
  </text>

  <!-- Subtitle -->
  <text x="450" y="125" text-anchor="middle" font-family="'Courier New', monospace" font-size="14" fill="#a0aec0" letter-spacing="3">
    AI/ML ENGINEER  ·  DEEP LEARNING  ·  LLM DEVELOPER
  </text>

  <!-- Tag line -->
  <text x="450" y="155" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#00d4ff" opacity="0.8">
    &lt; Building Intelligent Systems for Tomorrow /&gt;
  </text>

  <!-- Corner accents -->
  <g stroke="#00d4ff" stroke-width="1.5" fill="none" opacity="0.5">
    <path d="M 10 10 L 10 30 L 30 10 Z" fill="#00d4ff" opacity="0.3"/>
    <path d="M 870 10 L 890 10 L 890 30" />
    <path d="M 10 190 L 10 210 L 30 210" />
    <path d="M 870 210 L 890 210 L 890 190" />
  </g>
</svg>

<!-- ═══════════════════════════════════════ -->
<!--         ANIMATED TYPING HEADER         -->
<!-- ═══════════════════════════════════════ -->

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&random=false&width=700&lines=🤖+AI+%26+ML+Engineer+%7C+Deep+Learning+Builder;🧠+LLM+Developer+%7C+RAG+%26+LangChain+Expert;⚡+NLP+%7C+Computer+Vision+%7C+Transformers;🔬+Researching+Next-Gen+AI+Systems;🚀+Open+to+AI+Roles+%40+Top+Labs+%26+Startups)](https://git.io/typing-svg)

<!-- Profile views + social badges -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ankit1207yadav&label=Profile+Views&color=00d4ff&style=for-the-badge" alt="Profile Views"/>
  &nbsp;
  <a href="https://www.linkedin.com/in/ankit-y-a467112b5/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:ay9899407@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  &nbsp;
  <a href="https://github.com/ankit1207yadav">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Open_to_Work-00C853?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Open to Work"/>
</p>

</div>

---

<!-- ═══════════════════════════════════════ -->
<!--          SVG WAVE SEPARATOR            -->
<!-- ═══════════════════════════════════════ -->

<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00d4ff;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#7b2fff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ff006e;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 C150,5 300,35 450,20 C600,5 750,35 900,20" stroke="url(#waveGrad1)" stroke-width="2" fill="none">
    <animate attributeName="d" values="M0,20 C150,5 300,35 450,20 C600,5 750,35 900,20;M0,20 C150,35 300,5 450,20 C600,35 750,5 900,20;M0,20 C150,5 300,35 450,20 C600,5 750,35 900,20" dur="4s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

<!-- ═══════════════════════════════════════ -->
<!--          ABOUT ME SECTION              -->
<!-- ═══════════════════════════════════════ -->

## `> whoami`

```python
class Ankit:
    """
    AI/ML Engineer | Deep Learning | LLMs | NLP | Computer Vision
    Final Year B.Tech CSE (AI & ML)
    """

    def __init__(self):
        self.name         = "Ankit "
        self.role         = "AI/ML Engineer & LLM Developer"
        self.education    = "B.Tech CSE (AI & ML) — Final Year"
        self.location     = "India 🇮🇳"
        self.focus        = ["LLMs", "RAG Systems", "Deep Learning", "NLP", "MLOps"]
        self.stack        = ["Python", "PyTorch", "LangChain", "HuggingFace", "AWS"]
        self.dream_roles  = ["OpenAI", "Google DeepMind", "Anthropic", "NVIDIA", "Meta AI"]

    def current_work(self):
        return [
            "🔭 Building production-grade RAG pipelines with LangGraph & ChromaDB",
            "🧠 Fine-tuning LLMs for domain-specific NLP tasks",
            "⚡ Exploring Agentic AI and multi-step reasoning systems",
            "📚 Deep-diving into Diffusion Models & Multimodal AI",
        ]

    def ask_me_about(self):
        return ["Deep Learning", "Transformers", "LangChain", "CV", "NLP", "MLOps"]

    def reach_me(self):
        return "ay9899407@gmail.com"

ankit = Ankit()
print(ankit.current_work())
```

<div align="center">
<svg width="900" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="waveGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff006e;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#ff006e;stop-opacity:1"/>
      <stop offset="70%" style="stop-color:#7b2fff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#00d4ff;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <path d="M0,20 C150,35 300,5 450,20 C600,35 750,5 900,20" stroke="url(#waveGrad2)" stroke-width="2" fill="none">
    <animate attributeName="d" values="M0,20 C150,35 300,5 450,20 C600,35 750,5 900,20;M0,20 C150,5 300,35 450,20 C600,5 750,35 900,20;M0,20 C150,35 300,5 450,20 C600,35 750,5 900,20" dur="4s" repeatCount="indefinite"/>
  </path>
</svg>
</div>

---

## `> tech_arsenal --all`

<!-- Core AI/ML -->
<div align="center">

**⚡ Core AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)

**🦜 LLMs / NLP / GenAI**

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=for-the-badge&logo=databricks&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

**🛠️ Languages & Systems**

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

**☁️ Cloud / MLOps / DevOps**

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

</div>

---

## `> ls projects/`

<!-- Project Cards -->

### 🌿 Plant Disease Detection via CNN

<img align="right" src="https://img.shields.io/badge/Status-Active-0080FF?style=flat-square"/>

> **Deep learning computer vision system** that diagnoses crop diseases from leaf images with high precision — enabling early intervention for precision agriculture.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CNN](https://img.shields.io/badge/-CNN-FF6F00?style=flat-square)
![Transfer Learning](https://img.shields.io/badge/-Transfer_Learning-7b2fff?style=flat-square)

**Highlights:** Multi-class classification · Data augmentation pipeline · ResNet backbone · REST API with FastAPI

---

### 📰 Fake News Detection System

<img align="right" src="https://img.shields.io/badge/Status-Active-0080FF?style=flat-square"/>

> **NLP-powered misinformation classifier** using transformer-based text representations to identify and flag unreliable news content at scale.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HuggingFace](https://img.shields.io/badge/-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![BERT](https://img.shields.io/badge/-BERT-FF6B35?style=flat-square)
![NLP](https://img.shields.io/badge/-NLP-7b2fff?style=flat-square)
![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Highlights:** BERT fine-tuning · TF-IDF + semantic embeddings · 95%+ accuracy · Real-time inference pipeline

---

### 🎤 InterviewPrep AI Platform

<img align="right" src="https://img.shields.io/badge/Status-Active-0080FF?style=flat-square"/>

> **LLM-powered interview preparation platform** that generates role-specific questions, evaluates responses, and delivers intelligent feedback using RAG-enhanced retrieval.

![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-00C853?style=flat-square)
![RAG](https://img.shields.io/badge/-RAG-FF006E?style=flat-square)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-FF6B35?style=flat-square)
![OpenAI](https://img.shields.io/badge/-OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)

**Highlights:** Agentic multi-step workflow · Vector-store Q&A retrieval · Adaptive difficulty scoring · Containerized with Docker

---

### 🏥 Digital Health Record System

<img align="right" src="https://img.shields.io/badge/Status-Active-0080FF?style=flat-square/>

> **Secure, AI-assisted healthcare record management system** with smart search, summarization, and structured storage of patient data.

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![NLP](https://img.shields.io/badge/-NLP_Summarization-7b2fff?style=flat-square)

**Highlights:** Role-based access control · Medical NLP summarization · HIPAA-aware data design · CI/CD via GitHub Actions

---

## `> cat research_interests.md`

<div align="center">

<svg width="800" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#161b22;stop-opacity:1"/>
    </linearGradient>
  </defs>
  <rect width="800" height="200" rx="12" fill="url(#cardBg)" stroke="#30363d" stroke-width="1"/>
  <rect x="0" y="0" width="800" height="3" rx="2" fill="url(#textGrad)"/>

  <!-- Research bubbles -->
  <g font-family="'Courier New', monospace" font-size="12" fill="#00d4ff">
    <rect x="20" y="30" width="160" height="32" rx="16" fill="#00d4ff" fill-opacity="0.1" stroke="#00d4ff" stroke-width="1"/>
    <text x="100" y="51" text-anchor="middle" fill="#00d4ff">🔬 LLM Fine-tuning</text>

    <rect x="200" y="30" width="160" height="32" rx="16" fill="#7b2fff" fill-opacity="0.1" stroke="#7b2fff" stroke-width="1"/>
    <text x="280" y="51" text-anchor="middle" fill="#a78bfa">🧠 Agentic AI</text>

    <rect x="380" y="30" width="180" height="32" rx="16" fill="#ff006e" fill-opacity="0.1" stroke="#ff006e" stroke-width="1"/>
    <text x="470" y="51" text-anchor="middle" fill="#f472b6">🤖 RAG Optimization</text>

    <rect x="580" y="30" width="200" height="32" rx="16" fill="#00ffaa" fill-opacity="0.1" stroke="#00ffaa" stroke-width="1"/>
    <text x="680" y="51" text-anchor="middle" fill="#6ee7b7">⚡ Multimodal Models</text>

    <rect x="20" y="90" width="200" height="32" rx="16" fill="#7b2fff" fill-opacity="0.1" stroke="#7b2fff" stroke-width="1"/>
    <text x="120" y="111" text-anchor="middle" fill="#a78bfa">📊 Neural Scaling Laws</text>

    <rect x="240" y="90" width="180" height="32" rx="16" fill="#00d4ff" fill-opacity="0.1" stroke="#00d4ff" stroke-width="1"/>
    <text x="330" y="111" text-anchor="middle" fill="#00d4ff">🎯 RLHF / Alignment</text>

    <rect x="440" y="90" width="160" height="32" rx="16" fill="#ff006e" fill-opacity="0.1" stroke="#ff006e" stroke-width="1"/>
    <text x="520" y="111" text-anchor="middle" fill="#f472b6">🌐 Graph Neural Nets</text>

    <rect x="620" y="90" width="160" height="32" rx="16" fill="#00ffaa" fill-opacity="0.1" stroke="#00ffaa" stroke-width="1"/>
    <text x="700" y="111" text-anchor="middle" fill="#6ee7b7">🔭 Diffusion Models</text>

    <rect x="100" y="150" width="200" height="32" rx="16" fill="#ff006e" fill-opacity="0.1" stroke="#ff006e" stroke-width="1"/>
    <text x="200" y="171" text-anchor="middle" fill="#f472b6">💡 Efficient Transformers</text>

    <rect x="320" y="150" width="200" height="32" rx="16" fill="#00d4ff" fill-opacity="0.1" stroke="#00d4ff" stroke-width="1"/>
    <text x="420" y="171" text-anchor="middle" fill="#00d4ff">🧬 Mixture of Experts</text>

    <rect x="540" y="150" width="220" height="32" rx="16" fill="#7b2fff" fill-opacity="0.1" stroke="#7b2fff" stroke-width="1"/>
    <text x="650" y="171" text-anchor="middle" fill="#a78bfa">🚀 Model Quantization</text>
  </g>
</svg>

</div>

---

## `> tail -f building_in_public.log`

```
[INFO]  🔨 Architecting multi-agent systems using LangGraph for complex reasoning
[INFO]  📡 Integrating vector stores (ChromaDB / FAISS) into production RAG pipelines
[INFO]  🧪 Experimenting with prompt engineering & structured output techniques
[INFO]  🐳 Containerizing ML services with Docker & deploying to AWS EC2
[INFO]  🔁 Setting up CI/CD automation for model training pipelines
[INFO]  📝 Writing technical breakdowns of Attention, LoRA, and PEFT methods
[INFO]  🤗 Contributing to open-source HuggingFace & LangChain repositories
[NEXT]  🌐 Building a multi-modal AI assistant with vision + language understanding
[NEXT]  📦 Publishing a personal Python library for RAG pipeline utilities
```

---



## `> github-stats --verbose`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=ankit1207yadav&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&icon_color=7B2FFF&text_color=A0AEC0&count_private=true" alt="GitHub Stats"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ankit1207yadav&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00D4FF&text_color=A0AEC0&langs_count=8" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ankit1207yadav&theme=tokyonight&hide_border=true&background=0D1117&stroke=7B2FFF&ring=00D4FF&fire=FF006E&currStreakLabel=00D4FF&sideLabels=A0AEC0&dates=A0AEC0" alt="GitHub Streak"/>

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ankit1207yadav&theme=tokyo-night&bg_color=0D1117&color=00D4FF&line=7B2FFF&point=FF006E&area=true&hide_border=true" alt="Contribution Graph"/>

</div>

---


## `> connect --network`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankit-y-a467112b5/)
[![Email](https://img.shields.io/badge/Gmail-Drop_a_Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ay9899407@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow_Me-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ankit1207yadav)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Models-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)

</div>

---

<!-- FOOTER -->
<div align="center">

<svg width="900" height="80" viewBox="0 0 900 80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerBg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0a0a0f;stop-opacity:1"/>
      <stop offset="50%" style="stop-color:#0d1117;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#0a0a1a;stop-opacity:1"/>
    </linearGradient>
  </defs>
  <rect width="900" height="80" rx="10" fill="url(#footerBg)"/>
  <rect x="0" y="0" width="900" height="2" fill="url(#lineGrad)"/>

  <!-- Animated dots -->
  <circle cx="50" cy="40" r="3" fill="#00d4ff">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="70" cy="40" r="3" fill="#7b2fff">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="90" cy="40" r="3" fill="#ff006e">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </circle>

  <text x="450" y="35" text-anchor="middle" font-family="'Courier New', monospace" font-size="13" fill="#00d4ff">
    ⚡ Powered by Curiosity · Built with Python · Deployed by Ambition ⚡
  </text>
  <text x="450" y="58" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#4a5568">
    © 2026 Ankit   ·  AI/ML Engineer  ·  India
  </text>

  <!-- Right dots -->
  <circle cx="810" cy="40" r="3" fill="#ff006e">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="830" cy="40" r="3" fill="#7b2fff">
    <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="850" cy="40" r="3" fill="#00d4ff">
    <animate attributeName="opacity" values="1;0.2;1" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </circle>
</svg>

![Wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer&animation=twinkling)

</div>
