# RISE

**Retrieval-Augmented Generation Enhanced Immersive System for Education**

*A Lightweight Web-Based Intelligent Learning System with RAG, MCP, and DH*

**📄 Paper**: [RISE: A Retrieval-Augmented Generation Enhanced Immersive System for Education](https://dl.acm.org/doi/10.1145/3774905.3793107)

**🎥 Demo Video**: [Google Drive](https://drive.google.com/file/d/1D_A7sqbZ1fhJclL1gU0vTYw1V8XS5pYb/view)

**💻 Code Release:** 

> The RISE system is fully implemented and demonstrated in the submitted video.
> The full codebase is currently undergoing internal review.
A partial or full release may be made in a later phase depending on institutional approval and licensing constraints.

---

## ✨ Overview

**RISE** is a next-generation intelligent education system that integrates:

* **Retrieval-Augmented Generation (RAG)** for curriculum-grounded learning
* **Model Context Protocol (MCP)** for multi-agent orchestration
* **Digital Human (DH)** technology for immersive teaching
* **360° virtual classrooms**, real-time student **attention monitoring**, and **adaptive Q&A**
* **Learning analytics**, **virtual home-visit summaries**, and **online assessment**

RISE is designed to run **fully on lightweight web-based infrastructure**, making high-quality intelligent education accessible even on **low-end devices** and in **resource-limited regions**.

---

## 🔍 Key Features

### 🧭 1. Immersive 360° Learning Environment

* Interactive panoramic scenes (e.g., virtual field trips, cultural learning scenarios)
* Digital human instructor narrating auto-generated lesson content
* Scene switching synchronized with educational narratives

### 👀 2. Real-Time Attention Detection

* Webcam-based head pose & gaze estimation
* Lightweight on-device inference
* Non-intrusive attention reminders to maintain engagement

### 🧠 3. Retrieval-Augmented Educational Q&A

* RAG-based retrieval grounded in textbooks, syllabi, or course documents
* Contextualized explanations aligned with curriculum and student level
* Supports adaptive questioning and misconception correction

### 🤝 4. Multi-Agent Coordination via MCP

* Unified context memory for digital human, RAG agent, and tool calls
* Transparent orchestration of teaching, retrieval, and assessment tasks
* Extensible architecture for new educational agents

### 📊 5. Intelligent Learning Management

* Multi-modal learner analytics
* Virtual home-visit summaries for parents
* LLM-powered exam generation, scoring, and personalized feedback

---

## 🏗️ System Architecture

RISE consists of two major layers:

```
1. Immersive Delivery Layer
   - Digital Human instructor
   - 360° classroom
   - Attention monitoring

2. Intelligent Processing Layer
   - Educational RAG module
   - LLM-based generation
   - MCP agent coordinator
```

The two layers form a **closed-loop learning workflow**, enabling continuous adaptation and personalized instruction.

---

## 🎬 Demo Video

👉 **[Watch the full demonstration](https://drive.google.com/file/d/1D_A7sqbZ1fhJclL1gU0vTYw1V8XS5pYb/view)**

The video includes:

* Immersive classroom tour
* Digital human live teaching
* Attention monitoring demo
* Learning analytics dashboard
* Online assessment generation

---

## 📦 Code Availability

The full implementation (frontend + backend + data pipeline) will be released soon.

**Planned release includes:**

* Web-based immersive classroom engine
* MCP multi-agent orchestration server
* RAG retrieval pipeline (OpenAI / Qwen / Llama compatible)
* Digital human rendering modules
* Attention estimation module (Lightweight)
* Demo scripts and teacher evaluation tools

**Current Status:**
✔ System implemented
✔ Demo video released
✔ Open-source release scheduled
✖ Repository undergoing cleanup & IP review

---

## 🔒 Ethical Use & Data Privacy

RISE adheres to **ACM’s policy on research involving human participants**.

* Webcam-based signals **never store biometric data**
* All data is anonymized or processed locally
* Users may opt out at any time
* Demo video uses synthetic or consented samples

---

## 🤝 Acknowledgments

This project is developed by members of our research lab.  
All work represents the effort of the authors and contributors only.

The system and its materials do not represent the views, policies, or official positions of any institution.  
No institutional endorsement is implied.

---

## 📖 Cite
```
@inproceedings{10.1145/3774905.3793107,
author = {Chen, Guo and Tang, Haowei and Wei, Yan and Wang, Yuming and Zhang, Haoyang and Hou, Yikang and Zheng, Maolin and Huang, Junjie},
title = {Rise: A Retrieval-Augmented Generation Enhanced Immersive System for Education},
year = {2026},
isbn = {9798400723087},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3774905.3793107},
doi = {10.1145/3774905.3793107},
booktitle = {Companion Proceedings of the ACM Web Conference 2026},
pages = {85–88},
numpages = {4},
keywords = {smart education, retrieval-augmented generation, model context protocol, digital human},
location = {United Arab Emirates},
series = {WWW Companion '26}
}
```

