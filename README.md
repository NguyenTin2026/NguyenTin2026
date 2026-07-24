<!-- ===================== HEADER ===================== -->       
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00A5FF&center=true&vCenter=true&width=780&lines=%F0%9F%91%8B+Hello%2C+I'm+Nguyen+Tin+Tin+Do;LLM+Fine-Tuning+%7C+RAG+%7C+Computer+Vision;Undergraduate+Researcher+%40+Drew+University;Welcome+to+my+GitHub+Profile!">
</p>     

<!--   my-header-img -->
![](./src/header_.png)
<a href="https://www.python.org/"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" align="right" height="48" width="48" ></a>

<p align="center">
  <a href="https://www.linkedin.com/in/nguyen-tin-tin-do/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/NguyenTin2026"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:ndo1@drew.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.kaggle.com/nguyentintindo"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" /></a>
  <a href="https://huggingface.co/TinTinDo"><img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" /></a>
  <a href="https://app-tutorial-buiding-cv-tintin.streamlit.app/"><img src="https://img.shields.io/badge/Live%20Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" /></a>
</p>

<p align="center">
  <a href="https://tryhackme.com/p/ndo1"><img src="https://img.shields.io/badge/TryHackMe-ndo1-red?logo=tryhackme&logoColor=white" /></a>
  <a href="https://www.hackerrank.com/nguyentintindo"><img src="https://img.shields.io/badge/HackerRank-Profile-brightgreen?logo=hackerrank&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=NguyenTin2026&label=Profile+Views&color=blue"/>
</p>

---

## 🚀 Professional Summary

I am a **Computer Science undergraduate (Data Science minor) at Drew University**, working at the
intersection of **Large Language Models, Retrieval-Augmented Generation, and Computer Vision**.

My focus is narrow on purpose: I build **domain-specific AI systems that actually ship** — crawled
corpora, fine-tuned models, retrieval pipelines, and deployed apps that a non-technical person can
open in a browser and use.

| | |
|---|---|
| 🔬 **Currently** | Undergraduate Researcher, Drew Summer Science Institute — Fermilab physics Q&A with RAG + QLoRA |
| 🎯 **Core focus** | LLM fine-tuning (QLoRA/PEFT) · Hybrid retrieval (BM25 + dense) · Computer Vision · MLOps |
| 🛠️ **I like building** | AI agents, retrieval systems, automation tools, security-testing utilities |
| 🌎 **Based in** | Madison, New Jersey, USA |
| 🎓 **Graduating** | May 2027 · Open to Data Science / ML Engineering internships |
| 📚 **Always** | learning, improving, and experimenting |

---

## 🏅 Quick Highlights

| Achievement | Detail |
|---|---|
| 🥇 **DSSI Research Fellow, 2026** | Selected for a competitive **8-week funded** summer research fellowship (full scholarship + 4 academic credits) |
| 🎤 **Day of Scholars, Spring 2027** | Selected to present research at Drew University's annual scholarship showcase *(scheduled)* |
| 🤖 **936 pages → 8,847 chunks → fine-tuned LLM** | Built a full domain-specific RAG stack end-to-end, from crawler to deployed UI |
| 📈 **+19 pts token accuracy** | Raised fine-tuned model token-level accuracy from 56% → ~75% with no overfitting |
| 🎓 **GPA 3.75 / 4.0** | Merit Scholarship $15,000 (Fall 2025 – Spring 2026) |
| 👨‍🏫 **CRLA Level I Certified Tutor** | Peer Subject Tutor in CS & Data Science at Drew's Center for Academic Excellence |

---

## 🏆 Honors & Awards

### 🥇 Drew Summer Science Institute (DSSI) Research Fellowship — 2026
- Selected for a **competitive, 8-week funded summer research fellowship** under direct faculty mentorship.
- Award package: **full scholarship + 4 academic credits**.
- Placed on a live LLM research project (Fermilab physics Q&A) rather than a coursework-style assignment.

### 🎤 Drew University Day of Scholars — Spring 2027
- **Selected to present** DSSI research at Drew's annual university-wide scholarship showcase *(scheduled)*.
- Selection is based on the strength and completeness of the summer research output.

### 💰 Drew University Merit Scholarship — $15,000
- Awarded for academic performance, **Fall 2025 – Spring 2026**.

### 📈 Academic Standing
- **GPA 3.75 / 4.0** in B.S. Computer Science (Data Science minor).
- Selected as a **Peer Subject Tutor** by the Center for Academic Excellence on the basis of coursework
  performance across Intro to Python, Artificial Intelligence, Web Application Development, and
  Computer Networks & Security.

---

## 🔬 Research Experience

### 🧪 Fermilab Physics Q&A Assistant — RAG + QLoRA Fine-Tuned LLM
**Undergraduate Research Assistant · Drew Summer Science Institute (DSSI)**
*May 2026 – July 2026 · Advised by Prof. Alexander Rudniy, Drew University*

> **The problem:** general-purpose LLMs hallucinate on specialised particle-physics questions because
> Fermilab's technical knowledge is thinly represented in their training data. I built a complete
> pipeline to fix that — data collection, model adaptation, retrieval, and evaluation.

**1️⃣ Corpus construction**
- Built a **BFS web crawler** in Python (`Requests` + `BeautifulSoup`) that harvested **936 of 1,000**
  public Fermilab pages — a **93.6% success rate**, ~**1.1 GB** raw.
- Cleaned and chunked the corpus into **8,847 passages**, using **document-level train/test splitting**
  so no chunk from a test document could leak into training.

**2️⃣ Synthetic supervision**
- Generated **438 grounded question–answer pairs** using **Gemini 2.5 Flash** as a teacher model.
- Applied **8-gram decontamination** and quality filtering so the evaluation set stayed honest.

**3️⃣ Model adaptation**
- Fine-tuned **Qwen3-4B-Instruct** with **QLoRA** (4-bit NF4 quantization, LoRA rank 32) via
  **Hugging Face TRL**.
- Trained on the **Purdue Anvil HPC cluster** with **SLURM** job scheduling.
- **Result:** training loss down **~58%**, token-level accuracy **56% → ~75%**, with no overfitting
  signal in the validation curve.

**4️⃣ Retrieval & delivery**
- Shipped a **Streamlit RAG application** with **hybrid retrieval** — sparse **BM25** and dense
  embeddings fused through **Reciprocal Rank Fusion (RRF)** over the 8,847-chunk index.
- Added a **base-vs-fine-tuned comparison mode** so reviewers can see the delta side by side.
- Built a **Recall@k / MRR evaluation harness** to measure retrieval quality quantitatively rather
  than by vibes.

**📊 Results at a glance**

| Metric | Value | Why it matters |
|---|---|---|
| Crawl success rate | **936 / 1,000 pages (93.6%)** | Robust BFS crawler with retry and error handling, not a toy script |
| Raw corpus size | **~1.1 GB** | Real-scale data engineering, not a sample notebook |
| Indexed passages | **8,847 chunks** | Chunking strategy tuned for retrieval, not arbitrary splits |
| Synthetic QA pairs | **438 grounded pairs** | Teacher-model supervision with provenance back to source text |
| Contamination control | **8-gram decontamination** | Evaluation results are trustworthy, not inflated by leakage |
| Training loss reduction | **~58%** | Fine-tuning genuinely converged |
| Token-level accuracy | **56% → ~75%** | +19 points, with **no overfitting** in validation |
| Quantization | **4-bit NF4, LoRA rank 32** | A 4B model fine-tuned within realistic VRAM limits |
| Retrieval evaluation | **Recall@k, MRR** | Retrieval quality is measured, not assumed |

**🧭 Research competencies demonstrated**

| Area | Evidence from this project |
|---|---|
| Data engineering | BFS crawler, HTML cleaning, chunking, document-level train/test splitting |
| Experimental rigor | Leakage prevention, 8-gram decontamination, held-out evaluation set |
| Model adaptation | QLoRA / PEFT, 4-bit quantization, LoRA rank selection, loss-curve monitoring |
| Information retrieval | BM25 sparse + dense embeddings, Reciprocal Rank Fusion, Recall@k / MRR harness |
| HPC & tooling | SLURM job scripts, batch scheduling, multi-hour training runs on Purdue Anvil |
| Communication | Base-vs-fine-tuned comparison UI; presenting at Day of Scholars, Spring 2027 |

`Python` `PyTorch` `Hugging Face Transformers` `TRL` `PEFT` `bitsandbytes` `sentence-transformers` `BM25` `Streamlit` `Requests` `BeautifulSoup` `SLURM` `Gemini 2.5 Flash`

---

## 🎓 Education

**Drew University** — Madison, NJ
- **B.S. Computer Science, Minor in Data Science** — GPA: **3.75 / 4.0**
- Expected Graduation: **May 2027**
- Merit Scholarship **$15,000** (Fall 2025 – Spring 2026)
- Previously completed two years at **Ho Chi Minh City University of Technology and Education**, Vietnam
- **Key Courses:** Artificial Intelligence · Data Science · Software Engineering · Database Systems and
  Management · Statistics & Probability · Web Application Development · Computer Networks and Security

---

## 👨‍🏫 Experience

### Peer Subject Tutor — Computer Science & Data Science
**Drew University, Center for Academic Excellence** · *February 2026 – Present · Madison, NJ*
- Selected as a Peer Subject Tutor on the strength of academic performance across CS coursework —
  Intro to Python, Artificial Intelligence, Web Application Development, and Computer Networks & Security.
- Deliver **one-on-one and small-group** tutoring in programming, algorithms, and data science concepts.
- Guide students through **debugging, problem decomposition, and computational thinking** rather than
  handing over answers.
- Also serve as a **Foreign Language Tutor** and **Peer Academic Coach** within the same center.

---

## 💻 Projects

> Ordered by technical depth. Each entry answers three questions: *what it does, how it was built,
> and why it mattered.*

### 🚀 Portfolio Website with AI Chatbox (MCP + NLWeb)
**Nov 2025 – Present**

An interactive portfolio where visitors ask questions in natural language instead of scrolling.

- Built and deployed a **responsive multi-page portfolio website** using **HTML, CSS, and JavaScript**.
- Integrated an **AI-powered interactive Chatbox** so visitors can explore my background and projects
  conversationally.
- Implemented **MCP (Model Context Protocol)** for structured context passing and controlled,
  grounded AI responses.
- Applied the **NLWeb protocol** to expose site content as machine-readable knowledge for dynamic
  retrieval and reasoning.
- Managed project data through **structured JSON schemas**, making updates and scaling trivial.

🔗 **Live:** https://nguyentin2026.github.io/Project-Portfolio-Chatbox/
📁 **Repo:** https://github.com/NguyenTin2026/Project-Portfolio-Chatbox

---

### 🔍 Real-Time Face Detection — Webcam, Images & Video
**Aug 2025 – Oct 2025**

A multi-source computer vision pipeline that runs live on consumer hardware.

- Built a real-time face detection pipeline with **Python, OpenCV, and Haar Cascade classifiers**,
  reaching **~95% detection accuracy** on a custom labeled dataset.
- Engineered a **live webcam inference system** with on-frame annotation, holding **30 FPS on CPU**
  and **60 FPS on GPU**.
- Optimized frame processing and inference, cutting latency **~25%** through preprocessing efficiency
  and performance tuning.
- Implemented **multi-source input** (webcam / image / video) behind a single interface.

📁 **Repo:** https://github.com/NguyenTin2026/Mini-Project-Computer-Vision-in-Deep-Learning

---

### 🎯 Object Detection with YOLOv5 (Freelance)
**Aug 2025 – Present**

- Real-time multi-class object detection using **YOLOv5 + OpenCV**.
- Data cleaning, exploratory analysis, and result visualization with **Pandas, Seaborn, Matplotlib**.
- Delivered as a client-facing freelance engagement.

📁 **Repo:** https://github.com/NguyenTin2026/Mini-Project-Computer-Vision-in-Deep-Learning

---

### 🖥️ Streamlit CV Builder — Deployed Web App (Freelance)
**Oct 2025 – Present**

- Built a full **Streamlit web application** for generating, previewing, and exporting a Curriculum Vitae.
- Developed in **Python** with a modular library structure for layout, data, and export logic.
- **Deployed on Streamlit Cloud** and publicly accessible — no login, no setup.

🔗 **Live App:** https://app-tutorial-buiding-cv-tintin.streamlit.app/

---

### 🚢 Titanic Survival Prediction — End-to-End ML (Freelance)
**Oct 2025 – Present** *(originally explored Jun 2023 – Feb 2024)*

- Applied data cleaning and preprocessing to handle **missing values and outliers**.
- Engineered meaningful features (**family size, title extraction from names**) that measurably lifted
  model performance.
- Built and evaluated **Logistic Regression** and **Random Forest** classifiers.
- Achieved **~85% accuracy** on held-out test data.
- Queried and joined source data with **PostgreSQL**; visualized findings with **Pandas, Matplotlib, Seaborn**.

📁 **Repo:** https://github.com/NguyenTin2026/Data-Science-Tutorial-Step-By-Step-

---

### 🌐 API Testing & Backend Development
**Aug 2024 – Sep 2024**

- Built REST APIs with **FastAPI**, including request validation and structured error responses.
- Tested endpoints systematically with **Postman** collections.
- Managed source control across **Git, GitHub, and Bitbucket**.

📁 **Bitbucket:** https://bitbucket.org/tintin_2026/workspace/overview

---

## 🔝 Featured Projects

| Project | What it demonstrates | Stack | Link |
|---|---|---|---|
| **Fermilab RAG + QLoRA Assistant** | Full LLM lifecycle: crawl → chunk → synthesize → fine-tune → retrieve → evaluate | Qwen3-4B, TRL, PEFT, BM25+dense, SLURM | *DSSI research — repo on request* |
| **Portfolio Website with AI Chatbox** | Applied MCP + NLWeb for grounded, structured AI responses on a live site | HTML/CSS/JS, MCP, NLWeb, JSON | [Live](https://nguyentin2026.github.io/Project-Portfolio-Chatbox/) |
| **Real-Time Face Detection** | Latency-aware CV engineering on CPU and GPU | OpenCV, Haar Cascade | [Repo](https://github.com/NguyenTin2026/Mini-Project-Computer-Vision-in-Deep-Learning) |
| **Object Detection (YOLOv5)** | Modern detector deployment for a real client | YOLOv5, OpenCV | [Repo](https://github.com/NguyenTin2026/Mini-Project-Computer-Vision-in-Deep-Learning) |
| **Streamlit CV Builder** | Shipping and maintaining a public production app | Streamlit, Python | [Live](https://app-tutorial-buiding-cv-tintin.streamlit.app/) |
| **Titanic Survival Prediction** | Feature engineering and honest model comparison | scikit-learn, Pandas | [Repo](https://github.com/NguyenTin2026/Data-Science-Tutorial-Step-By-Step-) |
| **API Testing & Backend** | Backend fundamentals and API contract testing | FastAPI, Postman | [Bitbucket](https://bitbucket.org/tintin_2026/workspace/overview) |

---

## 🎖️ Certifications

| Credential | Issuer | Date | What it covers |
|---|---|---|---|
| **Mastering Claude AI: Prompting, APIs, RAG, and MCP** | Edureka *(via Coursera)* | Jul 2026 | Prompt engineering, LLM API integration, retrieval-augmented generation, Model Context Protocol — directly applied in my portfolio chatbox and Fermilab RAG work |
| **Engineer AI Agents with Agent Development Kit (ADK)** <br>*Skill Badge — Intermediate* | Google Cloud | May 2026 | Building, orchestrating, and deploying multi-step AI agents on Google Cloud |
| **CRLA International Tutor Training Program (ITTPC), Level I** | Drew University *(CRLA-accredited)* | Spring 2026 | Internationally recognised peer-tutoring certification: learning theory, session structuring, active listening, ethics |

**🎯 Currently working toward:** deeper MLOps tooling (MLflow, Weights & Biases) and LLM evaluation
methodology beyond Recall@k / MRR.

---

# 🧠 Skills & Tech Stack

### 📋 Skills Matrix

> Text version first — recruiters and ATS parsers read this; badges below are for humans.

| Category | Skills |
|---|---|
| **Programming Languages** | Python · R · SQL (PostgreSQL) · Java · C++ · JavaScript · TypeScript · HTML · CSS |
| **LLM & Generative AI** | LLM fine-tuning (QLoRA / LoRA via PEFT) · 4-bit quantization (bitsandbytes) · Hugging Face Transformers & TRL · Retrieval-Augmented Generation (RAG) · Hybrid retrieval (BM25 + dense) · Reciprocal Rank Fusion · sentence-transformers · Prompt engineering · Model Context Protocol (MCP) · NLWeb |
| **Machine Learning** | PyTorch · TensorFlow · Keras · Scikit-learn · Feature engineering · Model evaluation (Recall@k, MRR, accuracy, loss curves) · Logistic Regression · Random Forest |
| **Computer Vision** | OpenCV · Haar Cascade classifiers · YOLOv5 · Real-time inference optimization · Multi-source input pipelines |
| **Data Science & Analysis** | NumPy · Pandas · SciPy · Matplotlib · Seaborn · Excel · Data cleaning · Outlier & missing-value handling · Exploratory data analysis |
| **Data Engineering** | Web crawling (Requests, BeautifulSoup, BFS traversal) · Corpus chunking · Document-level train/test splitting · Data decontamination (n-gram) |
| **Web & Backend** | Streamlit · FastAPI · REST API design · Postman testing · Responsive front-end (HTML/CSS/JS) · JSON schema design |
| **Cloud & Infrastructure** | Google Cloud Platform (GCP) · Microsoft Azure · Docker · SLURM (HPC job scheduling) · Streamlit Cloud · GitHub Pages |
| **Databases** | PostgreSQL · SQL querying & joins |
| **Cybersecurity** | Kali Linux · Burp Suite · TryHackMe practical labs |
| **Dev Environments** | Jupyter Notebook · Google Colab · VS Code · PyCharm · Anaconda · Sublime Text · Linux |
| **Version Control** | Git · GitHub · GitLab · Bitbucket |
| **Soft Skills** | Peer tutoring (CRLA Level I certified) · Technical explanation to non-experts · Research communication · Independent project ownership · Client-facing freelance delivery |

### 🏷️ Visual Stack

### **Languages**
<p>
  <img src="https://skillicons.dev/icons?i=python,r,java,cpp,javascript,typescript,html,css,postgres" />
</p>

### **AI / Machine Learning**
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/TRL-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/PEFT%20%2F%20QLoRA-6E40C9?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/bitsandbytes-4B32C3?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/sentence--transformers-0F9D58?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG%20%2F%20BM25-1F80E0?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
</p>

### **Computer Vision**
<p>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/YOLOv5-00FFFF?style=for-the-badge&logo=github&logoColor=black" />
  <img src="https://img.shields.io/badge/Haar%20Cascade-555555?style=for-the-badge&logoColor=white" />
</p>

### **Data Science**
<p>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/Seaborn-4E709D?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
</p>

### **Web, Backend & Deployment**
<p>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/SLURM%20(HPC)-2C3E50?style=for-the-badge&logoColor=white" />
</p>

### **Databases**
<p>
  <img src="https://skillicons.dev/icons?i=postgres" height="45" />
</p>

### **Cybersecurity**
<p>
  <a href="https://tryhackme.com/p/ndo1"><img src="https://img.shields.io/badge/TryHackMe-ndo1-red?style=for-the-badge&logo=tryhackme&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Kali%20Linux-268BEE?style=for-the-badge&logo=kalilinux&logoColor=white" />
  <img src="https://img.shields.io/badge/Burp%20Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white" />
</p>

### **Tools & Environments**
<p>
  <img src="https://skillicons.dev/icons?i=git,github,gitlab,bitbucket,linux,docker,postman,vscode,pycharm,figma" />
</p>
<p>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" />
  <img src="https://img.shields.io/badge/Sublime%20Text-FF9800?style=for-the-badge&logo=sublimetext&logoColor=white" />
  <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
</p>

---

## 🌟 Leadership & Community

### Founder & Volunteer English Instructor
*May 2023 – May 2025*
- Founded **2 free English-learning platforms** on Facebook, growing to **900+ followers**.
- Delivered weekly tutoring in **English and Math** and mentored learners one-on-one at no cost.

### Social Media Content Creator
*Jan 2021 – May 2025*
- Managed **TikTok (22K followers, 2M+ views)**, Instagram, and Facebook channels.
- Produced multimedia content and lifted **average view duration by 25%** through iterative
  format testing — the same measure-then-optimize instinct I apply to models.

---

## 📚 Learning & Roadmap

**Now**
- 🔭 **LangChain / LlamaIndex** — agentic and multi-step retrieval orchestration
- 🧪 **Advanced MLOps** — experiment tracking, model registries, reproducible training
- 📏 **LLM evaluation** — going beyond Recall@k/MRR toward faithfulness and groundedness metrics

**Next**
- 🌱 **Generative AI** at production scale — serving, caching, and cost control
- ⚙️ **Distributed training** and inference optimization on HPC
- 👯 Open to collaboration on **AI automation, production ML, and open-source** projects
- 💡 Planning technical write-ups on **Medium / Dev.to** — starting with the Fermilab RAG pipeline

---

## 📊 GitHub Statistics & Activity

[![NguyenTin GitHub Stats](https://github-readme-stats.vercel.app/api?username=NguyenTin2026&show_icons=true&theme=radical)](https://github.com/NguyenTin2026)
[![NguyenTin Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=NguyenTin2026&layout=compact&theme=radical)](https://github.com/NguyenTin2026)

<a href="https://github.com/NguyenTin2026">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=NguyenTin2026&theme=radical" alt="GitHub Streak" style="display:block;">
</a>

<img
  src="https://github-readme-activity-graph.vercel.app/graph?username=NguyenTin2026&theme=react-dark&hide_border=true&area=true&custom_title=Total%20Contribution%20Graph"
  width="100%"
/>

### 🐍 Contribution Snake
<p align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" />
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=NguyenTin2026" />
</p>

![Alt](https://repobeats.axiom.co/api/embed/fe577e8707a8984439604dc0992ac357afd34ccb.svg "Repobeats analytics image")

---

## ✅ Why Connect With Me

- **I finish things.** Every project listed above has a repo, a live URL, or measured results — not a
  half-finished notebook.
- **I measure what I build.** Recall@k, MRR, token-level accuracy, FPS, latency — I report numbers,
  not adjectives.
- **I work across the whole stack.** Crawler → dataset → fine-tune → retrieval → deployed UI, on both
  laptops and HPC clusters.
- **I teach.** As a CRLA-certified peer tutor, I explain complex ideas clearly — useful on any team.
- **I'm available.** Actively seeking **Data Science / ML Engineering internships** for 2026–2027.

---

## 📞 Contact & Professional Links

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ndo1@drew.edu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nguyen-tin-tin-do)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NguyenTin2026/Curriculum-Vitae---Mr.-Tin-Tin)
[![Resume](https://img.shields.io/badge/Resume-4CAF50?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/NguyenTin2026/Curriculum-Vitae---Mr.-Tin-Tin)

<details>
<summary><b>💻 Developer & Code Hosting Platforms</b></summary>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NguyenTin2026)
[![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/TinTinDo2026)
[![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white)](https://bitbucket.org/tintin_2026/workspace/overview)
[![Streamlit Cloud](https://img.shields.io/badge/Streamlit%20Cloud-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://app-tutorial-buiding-cv-tintin.streamlit.app/)
[![Replit](https://img.shields.io/badge/Replit-F26207?style=for-the-badge&logo=replit&logoColor=white)](https://replit.com/@tintindo)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/nguyentintindo)
[![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)](https://www.hackerrank.com/nguyentintindo)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/ndo1)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/)
[![Medium](https://img.shields.io/badge/Medium-00ab6c?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/)
[![Stack Overflow](https://img.shields.io/badge/Stack_Overflow-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white)](https://stackoverflow.com/)
[![JetBrains](https://img.shields.io/badge/JetBrains-000000?style=for-the-badge&logo=jetbrains&logoColor=white)](https://www.jetbrains.com/)
[![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)](https://code.visualstudio.com/)
[![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)](https://developer.apple.com/xcode/)

</details>

<details>
<summary><b>🤖 AI / ML Platforms I Work With</b></summary>

<br>

[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Anthropic Claude](https://img.shields.io/badge/Anthropic-000000?style=for-the-badge&logo=anthropic&logoColor=white)](https://www.anthropic.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Google DeepMind](https://img.shields.io/badge/Google_DeepMind-0F53FF?style=for-the-badge&logo=google&logoColor=white)](https://deepmind.google/)
[![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/vertex-ai)
[![SageMaker](https://img.shields.io/badge/AWS_SageMaker-FF9900?style=for-the-badge&logo=amazonsagemaker&logoColor=white)](https://aws.amazon.com/sagemaker/)
[![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)](https://mlflow.org/)
[![Weights & Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)](https://wandb.ai/)
[![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)](https://databricks.com/)
[![Cohere](https://img.shields.io/badge/Cohere-FFD21E?style=for-the-badge&logo=cohere&logoColor=black)](https://cohere.com/)
[![Meta AI](https://img.shields.io/badge/Meta_AI-0467DF?style=for-the-badge&logo=meta&logoColor=white)](https://ai.meta.com/)
[![NVIDIA AI](https://img.shields.io/badge/NVIDIA_AI-76B900?style=for-the-badge&logo=nvidia&logoColor=white)](https://www.nvidia.com/en-us/ai/)
[![IBM Watson](https://img.shields.io/badge/IBM_Watson-052FAD?style=for-the-badge&logo=ibm&logoColor=white)](https://www.ibm.com/watson)
[![Papers with Code](https://img.shields.io/badge/Papers_with_Code-1F80E0?style=for-the-badge&logo=paperswithcode&logoColor=white)](https://paperswithcode.com/)
[![Replicate](https://img.shields.io/badge/Replicate-0A0A0A?style=for-the-badge&logo=github&logoColor=white)](https://replicate.com/)

</details>

<details>
<summary><b>☁️ Cloud & Deployment Platforms</b></summary>

<br>

[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/)
[![Azure AI](https://img.shields.io/badge/Azure_AI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/en-us/products/ai-services/)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://hub.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)
[![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)](https://www.netlify.com/)
[![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://cloudflare.com/)
[![Heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)](https://www.heroku.com/)
[![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com/)
[![Fly.io](https://img.shields.io/badge/Fly.io-8A2BE2?style=for-the-badge&logo=flydotio&logoColor=white)](https://fly.io/)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=black)](https://supabase.com/)
[![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white)](https://www.digitalocean.com/)
[![Linode](https://img.shields.io/badge/Linode-00A95C?style=for-the-badge&logo=linode&logoColor=white)](https://linode.com/)
[![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/cloud/)
[![IBM Cloud](https://img.shields.io/badge/IBM_Cloud-1261FE?style=for-the-badge&logo=ibmcloud&logoColor=white)](https://www.ibm.com/cloud)
[![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)](https://sentry.io/)

</details>

<details>
<summary><b>🌐 Social Media</b></summary>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nguyen-tin-tin-do)
[![Threads](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=threads&logoColor=white)](https://www.threads.com/@tintindo.2k4)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/share/17pXo5exca/?mibextid=wwXIfr)
[![Instagram](https://img.shields.io/badge/Instagram-E1306C?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/tintindo.2k4/)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@tintindo2k4)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://telegram.org/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://www.whatsapp.com/)
[![Zalo](https://img.shields.io/badge/Zalo-0068FF?style=for-the-badge&logoColor=white)](https://zalo.me/)
[![WeChat](https://img.shields.io/badge/WeChat-07C160?style=for-the-badge&logo=wechat&logoColor=white)](https://www.wechat.com/)
[![Snapchat](https://img.shields.io/badge/Snapchat-FFFC00?style=for-the-badge&logo=snapchat&logoColor=black)](https://www.snapchat.com/)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/)
[![Pinterest](https://img.shields.io/badge/Pinterest-E60023?style=for-the-badge&logo=pinterest&logoColor=white)](https://pinterest.com/)
[![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://spotify.com/)
[![Behance](https://img.shields.io/badge/Behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/)
[![Bilibili](https://img.shields.io/badge/Bilibili-00A1D6?style=for-the-badge&logo=bilibili&logoColor=white)](https://www.bilibili.com/)
[![Amazon](https://img.shields.io/badge/Amazon-FF9900?style=for-the-badge&logo=amazon&logoColor=white)](https://www.amazon.com/)

</details>

<p align="left">
  <a href="https://www.linkedin.com/in/nguyen-tin-tin-do/" target="blank"><img align="center" src="https://raw.githubusercontent.com/BEPb/BEPb/master/assets/linkedin.svg" alt="TinTin" height="30" width="30" /></a>
  <a href="https://www.threads.com/@tintindo.2k4" target="blank"><img align="center" src="https://raw.githubusercontent.com/BEPb/BEPb/master/assets/twitter.svg" alt="TinTin" height="30" width="30" /></a>
</p>

📧 **Email:** ndo1@drew.edu
📱 **Phone:** available on request via email or LinkedIn

---

*Thanks for stopping by! Browse the repos, open an issue, or reach out — I'm always up for a good
AI/ML collaboration.* 😊
