<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090979,50:0057B8,100:00D4FF&height=230&section=header&text=Talha%20Rehman&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20Aspiring%20AI%20Researcher&descSize=15&descAlignY=57" width="100%" alt="Talha Rehman banner"/>

<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=00D4FF&center=true&vCenter=true&width=800&lines=Multi-Agent+Systems+with+LangGraph;Agentic+RAG+%2B+FastAPI;Computer+Vision+for+Healthcare;Full-Stack+%7C+MERN+%7C+PERN" alt="Introduction"/>
</a>

<br/>

<a href="https://github.com/TalhaRehman-KHT"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://huggingface.co/TalhaRehman-KHT"><img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/></a>
<a href="https://www.linkedin.com/in/talha-rehman-460014218"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://talha-five.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="mailto:talharehmankht@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

</div>

---

## 👋 About Me

I'm Talha, a CS graduate from Kohat University of Science and Technology (KUST), currently working as a software engineer at **LiveTalk** in Islamabad.

I came into AI from the web side. I spent my first couple of years building MERN and PERN apps, including three full products during my internship at Brandora. Then I added an LLM to my pharmacy store project, and it started answering medicine questions with total confidence and no sources. That pushed me into LangChain, LangGraph and RAG, because I wanted to understand why it happened and how to build systems that don't do it.

Since then I've built several LangChain and LangGraph projects (all on my GitHub), including multi-agent systems with Streamlit front-ends and LangSmith tracing, and an agentic backend in FastAPI that now runs inside my pharmacy store.

The area I care about most is **AI for healthcare**, especially **computer vision on medical images**. I'm preparing for a research-oriented master's and want to spend it on problems where you can actually measure whether the model helps.

---

## 🔬 Research Interests

### 1. Computer Vision for Healthcare *(primary interest)*

Medical images hold patterns that are hard and slow for people to spot consistently. I want to work on models that can find those patterns reliably, and on the less glamorous part: proving they work.

What I'd like to dig into:
- Classification and segmentation of medical images (X-rays, CT, MRI)
- Representation learning and feature extraction for small, imbalanced medical datasets
- Honest evaluation, meaning dataset bias, generalization to new hospitals, and failure cases
- Responsible use of vision models in clinical settings

### 2. Agentic RAG for Healthcare Information

In medicine, a plausible-sounding wrong answer is worse than no answer. I'm interested in retrieval systems that pull from trusted drug and medical sources, refine their own queries when the first retrieval is weak, ground every answer in what they retrieved, and admit when the sources don't cover a question.

### 3. Multi-Agent Systems

Building multi-agent workflows in LangGraph showed me how quickly they get messy: agents passing bad context to each other, tools called with wrong arguments, loops that never end. I want to study how to coordinate specialized agents, keep humans in the loop at the right points, and measure reliability instead of eyeballing a few outputs.

**Broader interests:** Deep Learning · Medical Image Analysis · Multimodal AI · LLMs · AI Evaluation

---

## 💊 Featured Project: Multi-Agent Pharmacy Assistant

This started as a pharmacy store management system and turned into my main AI project. The agentic part is a separate **FastAPI** service that the store calls into.

**What it does**
- Answers medicine and prescription questions through LangGraph agents that retrieve before they respond
- Uses Groq and Gemini models for prescription-related features
- Includes a supplier-email agent that drafts restock emails and **waits for human approval** before anything gets sent
- Runs in Docker, with Supabase (PostgreSQL) for data and auth

**What I'm still working on**
- Better retrieval relevance on drug-related queries
- Building a proper test set of tricky and unsupported questions
- Making the system's limits obvious to users instead of hiding them

`Python` `FastAPI` `LangGraph` `LangChain` `Groq` `Gemini` `Supabase` `Docker` `React`

<!-- Add links here, e.g.
**[Repository](https://github.com/TalhaRehman-KHT/REPO-NAME)** · **[Demo](LINK)**
-->

> An informational software project, not a medical tool or a replacement for a doctor or pharmacist.

---

## 🤖 LangChain & LangGraph Projects

**Multi-Agent Blog Writer.** Researcher, writer, and editor agents built in LangGraph, with human review between steps. A Streamlit UI shows each agent's output, and LangSmith traces every run, so I can see exactly where a draft went wrong.
`LangGraph` `Streamlit` `LangSmith`
<!-- [Repository](https://github.com/TalhaRehman-KHT/REPO-NAME) -->

**FlightAI.** An airline assistant chatbot with tool calling. I moved it from the OpenAI API to local models on **Ollama** to see how far I could get without paid APIs.
`Python` `Ollama` `OpenAI API`
<!-- [Repository](https://github.com/TalhaRehman-KHT/REPO-NAME) -->

<!-- Add your other LangChain/LangGraph repos here in the same format -->

---

## 🧠 AI & LLM Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,fastapi&theme=dark" alt="Python, PyTorch, FastAPI"/>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" alt="LangChain"/>
<img src="https://img.shields.io/badge/LangGraph-2F6B4F?style=for-the-badge" alt="LangGraph"/>
<img src="https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge" alt="LangSmith"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>

<br/>

<img src="https://img.shields.io/badge/Ollama-Local%20Models-111111?style=for-the-badge" alt="Ollama"/>
<img src="https://img.shields.io/badge/Groq-LLM%20API-F55036?style=for-the-badge" alt="Groq"/>
<img src="https://img.shields.io/badge/Gemini-API-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>

</div>

Day to day this means wiring LLMs into real apps through APIs, building LangGraph workflows with tools and human-in-the-loop steps, setting up embeddings and vector search for RAG, tracing runs in LangSmith, and swapping between hosted and local models depending on cost and privacy.

Evaluation is the part I'm trying to get better at. Right now I compare models on the same question set, inspect what the retriever actually returned, and log failure cases. Next I want to turn that into repeatable test suites rather than one-off checks.

---

## 🌐 Full-Stack & Automation

The AI parts of my projects only work because the rest of the app works too. I'm comfortable building frontends, REST APIs, auth, and databases, and connecting services with **n8n** workflows and webhooks.

<div align="center">

<img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,tailwind,nodejs,express,postgres,mongodb,mysql,supabase,firebase&theme=dark" alt="Web stack"/>

<br/>

<img src="https://skillicons.dev/icons?i=git,github,docker,postman,vercel,vscode&theme=dark" alt="Tools"/>
<img src="https://img.shields.io/badge/n8n-Automation-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n"/>

</div>

---

## 🚀 Other Projects

**🍽️ Zaiqa: taste-based restaurant discovery.** Matches users to restaurants by taste profile using cosine similarity, with PostGIS handling location-aware "near me" queries.
`React` `Vite` `Tailwind` `Supabase` `MongoDB Atlas`
<!-- [Repository](LINK) -->

**📋 JobHunting: application tracker.** Tracks job applications and fires n8n webhooks for follow-up reminders, with Gemini drafting the follow-up emails.
`MERN` `n8n` `Gemini API` `SMTP`
<!-- [Repository](LINK) -->

**💬 QuickGPT.** A chatbot interface I built to learn LLM API integration on the frontend.
<!-- [Repository](LINK) -->

**🛒 Shop-It.** A MERN e-commerce app with authentication, product listings, and a cart and checkout flow.
<!-- [Repository](LINK) -->

---

## 🎓 Education

**BS Computer Science**, Kohat University of Science and Technology (KUST), Pakistan
**CGPA:** 3.23 / 4.00

---

## 🌱 What I'm Learning Now

- **PyTorch and CNNs:** working toward my first medical image classification project
- **Deep learning fundamentals:** the math behind what I've mostly used as libraries
- **Fine-tuning:** LoRA and other parameter-efficient methods
- **Research method:** designing experiments that someone else could reproduce

---

## 📈 GitHub Stats

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=TalhaRehman-KHT&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
<img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=TalhaRehman-KHT&theme=tokyonight&hide_border=true" alt="Streak"/>

</div>

---

<div align="center">

### 🤝 Let's talk

If you work on medical imaging, healthcare AI, or agent systems, or you're running a lab that does, I'd love to hear from you.

<a href="https://www.linkedin.com/in/talha-rehman-460014218"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:talharehmankht@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20Hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://talha-five.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:090979,50:0057B8,100:00D4FF&height=120&section=footer" width="100%" alt="Footer"/>

</div>
