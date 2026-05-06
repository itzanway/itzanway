<div align="center">

```
 █████╗ ███╗   ██╗██╗    ██╗ █████╗ ██╗   ██╗
██╔══██╗████╗  ██║██║    ██║██╔══██╗╚██╗ ██╔╝
███████║██╔██╗ ██║██║ █╗ ██║███████║ ╚████╔╝ 
██╔══██║██║╚██╗██║██║███╗██║██╔══██║  ╚██╔╝  
██║  ██║██║ ╚████║╚███╔███╔╝██║  ██║   ██║   
╚═╝  ╚═╝╚═╝  ╚═══╝ ╚══╝╚══╝ ╚═╝  ╚═╝   ╚═╝  
```

### Software Engineer · AI/ML Engineer · Open Source Builder

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/anway-durge-5b47051b3/)
[![Gmail](https://img.shields.io/badge/Email-durgeanway%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:durgeanway@gmail.com)
[![Portfolio](https://img.shields.io/badge/GitHub-itzanway-181717?style=flat-square&logo=github)](https://github.com/itzanway)
![Profile Views](https://komarev.com/ghpvc/?username=itzanway&style=flat-square&color=blueviolet)

</div>

---

## 👨‍💻 About Me

I'm a **B.Tech CSE student at IIIT Surat** who builds AI-integrated, production-grade systems — not just demos.

- 🔬 Deep interest in **ML systems, NLP pipelines, and LLM application development**
- 🏗 I build **real tools** — job automation bots, collaborative editors, scraping engines
- 🌐 Full-stack capable: from REST APIs and WebSockets to React frontends
- 🔁 20+ open-source contributions with **70%+ PR merge rate**
- 🎯 Looking for: **SWE / AI-ML Engineer roles** (internship or full-time)

---
## Featured Projects
 
### ⚡ [Mini-vLLM — LLM Inference Engine from Scratch](https://github.com/itzanway/Mini-vLLM)
 
> Built a miniature version of vLLM to understand production LLM serving at the systems level. No `model.generate()` used anywhere.
 
```
┌─────────────────────────────────────────────────────────┐
│                   docker-compose stack                   │
│                                                          │
│   React Dashboard ──REST──▶ FastAPI :8000                │
│   • GPU memory gauge        POST /generate (SSE)         │
│   • TPS sparkline           GET  /stats                  │
│   • Batch slot viz          WS   /ws/stats               │
│                                    │                     │
│                             Inference Engine             │
│                             • Custom token loop          │
│                             • Continuous batching        │
│                             • Temperature + top-p        │
│                                    │                     │
│                          GPT-2 / TinyLlama weights       │
└─────────────────────────────────────────────────────────┘
```
 
**What I built:**
- **Custom generation loop** — tokenize → forward pass → logits → temperature scaling → top-p nucleus sampling → decode, fully hand-written in PyTorch
- **Continuous batching scheduler** — when any sequence hits `<EOS>`, its slot is immediately freed and the next queued request fills it without pausing other active sequences (3–5x more GPU-efficient than naive batching)
- **FastAPI + SSE streaming** — tokens stream to the client one-by-one as generated, exactly like ChatGPT's interface
- **React live metrics dashboard** — GPU memory gauge, tokens/sec sparkline, queue depth, batch slot visualizer, all updating every second
**Stack:** `Python` `PyTorch` `FastAPI` `React` `Vite` `Docker` `CUDA` `HuggingFace Transformers` `WebSocket` `SSE`
 
---
 
### 🧠 [CodeColab — Real-Time AI Collaborative Editor](https://github.com/itzanway/DevHeat-CodeColab)
 
> Hackathon-winning real-time collaborative coding platform with AI-powered code suggestions
 
- Built **room-based live collaboration** using Django Channels + WebSockets
- Integrated **Hugging Face inference API** for context-aware code suggestions
- Handles concurrent users with real-time sync and conflict-free editing
**Stack:** `Django` `WebSockets` `JavaScript` `Hugging Face API`
 
---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

**Web & Backend**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Tools & DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=itzanway&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

</div>

---

## 📈 Contribution Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itzanway/itzanway/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itzanway/itzanway/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/itzanway/itzanway/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

## 🏆 Open Source

- ✅ Contributed to **20+ repositories** across ML, DevTools, and Web categories
- 🔀 **70%+ PR merge rate** — focused on meaningful, well-scoped contributions
- 🐛 Contributions include: bug fixes, feature additions, docs improvements, test coverage

---

## 💡 What I'm Currently Working On

- 📚 Deepening expertise in **transformer architectures and fine-tuning workflows**
- 🔧 Building more **LLM-powered developer tools**
- 🤝 Open to **collaborations, internships, and full-time SWE/ML roles**

---

<div align="center">

### 📬 Open to Opportunities

I'm actively looking for **Software Engineer** and **AI/ML Engineer** roles.  
If my work aligns with what your team is building — let's talk.

[![LinkedIn](https://img.shields.io/badge/Reach_out_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anway-durge-5b47051b3/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:durgeanway@gmail.com)

*B.Tech CSE · IIIT Surat · Available for internships & full-time*

</div>
