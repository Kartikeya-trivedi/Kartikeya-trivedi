<p align="center">
<img src="https://capsule-render.vercel.app/api?type=wave&color=0:7F7FD5,50:86A8E7,100:91EAE4&height=220&section=header" />
</p>

<div align="center">

# ⚡️ Kartikeya Trivedi
### **Generative AI Researcher • Agentic Systems • LLM Architect • MLOps**

<br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=600&size=18&duration=2500&pause=600&color=58A6FF&center=true&vCenter=true&width=550&lines=Generative+AI+Researcher+%7C+LLM+Architect;Architecting+KT_GPT%3A+992M+Sparse+MoE+Model;Building+realtime+AI+agents+%26+developer+tools;FastAPI+%7C+Agno+%7C+PyTorch+%7C+ChromaDB" />

<br/>

[📧 Email](mailto:kartikeyatrivedi@outlook.com) · [💼 LinkedIn](https://www.linkedin.com/in/kartikeyatrivedi) · [🐙 GitHub](https://github.com/Kartikeya-trivedi) · [🌐 Website](https://kartikeya.me) · 📍 Lucknow, India · ☎︎ +91 8957907776

<br/>

<img src="https://komarev.com/ghpvc/?username=Kartikeya-trivedi&style=flat-square&color=blue" alt="profile views" />

</div>

---

<p align="center">
  <a href="mailto:kartikeyatrivedi@outlook.com"><img src="https://img.shields.io/badge/Contact-Email-0A66C2?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/kartikeyatrivedi"><img src="https://img.shields.io/badge/Follow-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Kartikeya-trivedi"><img src="https://img.shields.io/badge/Star-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://kartikeya.me"><img src="https://img.shields.io/badge/Visit-Website-FF6B6B?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
  <img src="https://img.shields.io/github/followers/Kartikeya-trivedi?style=for-the-badge&logo=github&label=Followers" />
  <img src="https://img.shields.io/github/stars/Kartikeya-trivedi?style=for-the-badge&logo=github&label=Stars" />
</p>

---

## 🚀 Active Research & Building Focus

- **🔬 KT_GPT (Flagship LLM Research)** — Architecting a **992.68M parameter Sparse Mixture-of-Experts (MoE)** model with sub-200M active capacity (141.12M active parameters). Features low-rank **Multi-head Latent Attention (MLA)**, **SwiGLU experts**, and online bias-based load balancing. Deployed on **Modal** and aligned with a custom 94k SFT dataset for robust, hallucination-free RAG grounding.
- **💻 CodeShiftAI** — VS Code + FastAPI + Agno agent for realtime, context-aware coding; features WebSocket streaming, vector-based context retrieval, and incremental parsing.
- **🎥 Professor Peter** — AI Video Educator featuring FFmpeg-based lip-sync and ElevenLabs TTS narration (Hackathon Winning Project).
- **🎬 ForgeTube** — Script-to-video automation pipeline utilizing Stable Diffusion for scene generation, Kokoro TTS, and FFmpeg for automated MP4 rendering.

---

## 🛠️ Curated Research & Tech Stack

### 🧠 LLM & Deep Learning Research
`PyTorch` · `Transformers` · `MLA (Multi-head Latent Attention)` · `Mixture-of-Experts (MoE)` · `SwiGLU` · `LoRA Fine-Tuning` · `GRPO Reinforcement Learning` · `ChromaDB` · `Tokenizers`

### ⚙️ Agentic Systems & Backend
`FastAPI` · `Agno Agentic Framework` · `WebSockets` · `Python` · `AsyncIO` · `REST APIs` · `PostgreSQL` · `SQLite`

### 🎞️ Media & Automation Pipelines
`FFmpeg` · `Stable Diffusion (Prompt Generation)` · `ElevenLabs TTS` · `Kokoro TTS` · `Subprocess sandboxing` · `Media stitching`

### ☁️ MLOps & Infrastructure
`Modal Serverless` · `Docker` · `Weights & Biases (W&B)` · `UV Package Manager` · `Git/GitHub` · `VS Code` · `PyCharm`

---

## 🏆 Selected Milestones & Wins

- **🎓 LLM Research Breakthrough:** Successfully implemented and verified DeepSeek-style **MLA** (compressing KV cache by **8.8x**) and **Online Bias-Based Load Balancing** inside our 992M parameter KT_GPT model.
- **💰 Infrastructure Grant:** Secured a **$500 Modal research grant** + monthly credits to run scalable pretraining and reinforcement learning (GRPO).
- **🥇 Hackathon Champion:** Took 1st place with **Professor Peter** (FastAPI-driven FFmpeg lip-sync + ElevenLabs TTS).
- **🎙️ Community Leadership:** Conducted hands-on ML workshops on the **Agno agent framework** and hosted interactive tech events.

---

## 💎 Featured Projects

<details open>
<summary><b>🚀 KT_GPT</b> — Sparse Mixture-of-Experts LLM (PyTorch • MLA • SwiGLU • Modal)</summary>

<br/>

- **Compute & Capacity Decoupled:** 992.68M total parameters with only 141.12M active parameters per token via **37 Routed Experts + 1 Shared Expert**.
- **Latent KV Cache Compression:** Cutting KV cache per token per layer from **1,408 values to just 160 values** (an **8.8x reduction**), allowing ultra-long context inference on edge GPUs.
- **Robust Grounding Alignment:** Fine-tuned on a custom 94K-sample dataset to optimize no-info refusal (*"I don't have that information"*) and math parsing via external tool results.

<div>
  <img src="https://img.shields.io/badge/Architecture-MLA%20%2B%20SwiGLU%20MoE-ff6b6b?style=flat-square" />
  <img src="https://img.shields.io/badge/Total_Params-992.68M-blueviolet?style=flat-square" />
  <img src="https://img.shields.io/badge/Active_Params-141.12M-deepskyblue?style=flat-square" />
  <img src="https://img.shields.io/badge/Sparsity-85.8%25-emerald?style=flat-square" />
</div>

</details>

<details>
<summary><b>💻 CodeShiftAI</b> — Realtime AI coding assistant (VS Code • FastAPI • Agno)</summary>

<br/>

- **Instant UX:** WebSocket streaming suggestions with incremental parsing for lightning-fast latency.
- **Deep Codebase Awareness:** Vector-based context retrieval for multi-file knowledge and smarter completions.
- **Agentic Routing:** Multi-agent reasoning via Agno for task routing and complex code transformations.

<div>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/Agno-2D2D2D?logo=autonomous&logoColor=white&label=Agentic&style=flat-square" />
</div>

</details>

<details>
<summary><b>🎥 Professor Peter</b> — AI video educator (FastAPI • FFmpeg • ElevenLabs)</summary>

<br/>

- **Real-Time Lip Sync:** Text-to-video generation engine utilizing FFmpeg filters for audio-to-mouth alignment.
- **High Fidelity Narration:** Integrated ElevenLabs TTS API to render natural, high-fidelity lectures.
- **Clean Orchestration:** Designed simple REST APIs for rapid content generation queues.

<div>
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/FFmpeg-007808?logo=ffmpeg&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/ElevenLabs-TTS-111111&style=flat-square" />
</div>

</details>

<details>
<summary><b>🎬 ForgeTube</b> — Script‑to‑video pipeline (SD prompts • FFmpeg • Kokoro TTS)</summary>

<br/>

- **LLM Script Segmentation:** Translates raw scripts into individual scenes with custom-generated Stable Diffusion image prompts.
- **Dynamic Media Stitching:** Automated video stitching via FFmpeg with precise timestamp alignment for Kokoro TTS audio.
- **Automated Publishing:** Generates ready-to-upload YouTube MP4 files complete with background tracks.

<div>
  <img src="https://img.shields.io/badge/Stable%20Diffusion-222222?logo=stable%20diffusion&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/FFmpeg-007808?logo=ffmpeg&logoColor=white&style=flat-square" />
  <img src="https://img.shields.io/badge/Kokoro-TTS-222222&style=flat-square" />
</div>

</details>

---

### 📫 Let's Connect!

- **Email:** [kartikeyatrivedi@outlook.com](mailto:kartikeyatrivedi@outlook.com)
- **LinkedIn:** [linkedin.com/in/kartikeyatrivedi](https://www.linkedin.com/in/kartikeyatrivedi)
- **GitHub:** [github.com/Kartikeya-trivedi](https://github.com/Kartikeya-trivedi)
- **Website:** [kartikeya.me](https://kartikeya.me)

---

### 🏅 Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Kartikeya-trivedi&theme=onedark&no-frame=true&row=1&column=6" />
</p>

### 📊 GitHub Stats & Activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=Kartikeya-trivedi&show_icons=true&theme=radical&hide_title=true" />
  &nbsp;&nbsp;
  <img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=Kartikeya-trivedi&theme=radical" />
</p>

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kartikeya-trivedi&layout=compact&theme=radical&hide_title=true" />
</p>

### 📈 Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kartikeya-trivedi&theme=react-dark&hide_border=true" />
</p>

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=wave&color=0:91EAE4,50:86A8E7,100:7F7FD5&height=120&section=footer" />
</p>