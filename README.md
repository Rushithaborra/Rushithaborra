<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,35:1E1B4B,70:4C1D95,100:7C3AED&height=230&section=header&text=Rushitha%20Borra&fontSize=56&fontColor=E9D5FF&fontAlignY=36&desc=AI%2FML%20Engineer%20%7C%20LLM%20Systems%20%7C%20Full%20Stack%20Developer&descSize=17&descAlignY=58&descAlign=50&animation=fadeIn" width="100%" alt="header"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=A78BFA&center=true&vCenter=true&width=720&lines=Fine-tuning+LLMs+with+LoRA+and+Unsloth;Shipping+local+inference+with+GGUF+%2B+Ollama;Building+grounded+AI+that+cites+its+sources;B.Tech+CSE+(AI+%26+ML)+%40+ANITS" alt="Typing SVG"/></a>

<br/>

<img src="https://img.shields.io/badge/B.Tech-CSE%20(AI%20%26%20ML)-7C3AED?style=flat-square&labelColor=1E1B4B" alt="Degree"/>
<img src="https://img.shields.io/badge/ANITS-Visakhapatnam-6D28D9?style=flat-square&labelColor=1E1B4B" alt="Institute"/>
<img src="https://img.shields.io/badge/Class%20of-2028-8B5CF6?style=flat-square&labelColor=1E1B4B" alt="Graduation"/>
<img src="https://img.shields.io/badge/Location-Visakhapatnam%2C%20India-4F46E5?style=flat-square&logo=googlemaps&logoColor=white&labelColor=1E1B4B" alt="Location"/>

<br/><br/>

<a href="https://github.com/Rushithaborra"><img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=A78BFA" alt="GitHub"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Rushithaborra&color=7c3aed&style=flat-square&label=PROFILE+VIEWS" alt="Profile views"/>
<a href="https://github.com/Rushithaborra?tab=followers"><img src="https://img.shields.io/github/followers/Rushithaborra?style=flat-square&color=6D28D9&labelColor=1E1B4B&logo=github&label=Followers" alt="Followers"/></a>
<a href="https://github.com/Rushithaborra?tab=repositories"><img src="https://img.shields.io/github/stars/Rushithaborra?style=flat-square&color=8B5CF6&labelColor=1E1B4B&logo=github&label=Stars" alt="Stars"/></a>

</div>

---

## About

I am an AI/ML engineering student who treats models as one component of a product, not the product itself. My work sits at the boundary between machine learning and software engineering: preparing instruction datasets, fine-tuning small language models with parameter-efficient methods, packaging them for local inference, and wiring them into applications people can actually use.

My current focus is **grounded generation** — building LLM systems that answer from verifiable data instead of improvising. Alongside that, I build and ship production websites for small businesses, which keeps my full-stack fundamentals sharp and my product instincts tied to real users.

I care about reproducible pipelines, honest evaluation, and systems that degrade gracefully when the model is wrong.

**Open To**

- AI/ML engineering internships
- LLM, RAG, and applied NLP projects
- Hackathon collaborations
- Open-source contributions in the LLM tooling ecosystem

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=python,c,java,js,html,css&theme=dark" alt="Languages"/>

**Frontend**

<img src="https://skillicons.dev/icons?i=html,css,js,tailwind,react&theme=dark" alt="Frontend"/>

**Backend & Databases**

<img src="https://skillicons.dev/icons?i=py,flask,fastapi,nodejs,mysql,sqlite&theme=dark" alt="Backend and Databases"/>

**Cloud, DevOps & Tooling**

<img src="https://skillicons.dev/icons?i=linux,git,github,docker,aws,vscode&theme=dark" alt="Cloud DevOps and Tooling"/>

**AI / ML**

<img src="https://skillicons.dev/icons?i=pytorch,sklearn,tensorflow&theme=dark" alt="AI ML"/>

</div>

---

## AI / ML Expertise

<div align="center">

| Domain | Proficiency | Details |
|:--|:--:|:--|
| **LLM Fine-Tuning** | <img src="https://img.shields.io/badge/-Intermediate-7C3AED?style=flat-square"/> | LoRA fine-tuning of Phi-3-mini with Unsloth on Colab GPUs |
| **Local LLM Deployment** | <img src="https://img.shields.io/badge/-Intermediate-7C3AED?style=flat-square"/> | GGUF export, custom Modelfiles, Ollama serving on Linux |
| **Dataset Engineering** | <img src="https://img.shields.io/badge/-Intermediate-7C3AED?style=flat-square"/> | Instruction–response pair construction in JSON for domain tuning |
| **Retrieval-Augmented Generation** | <img src="https://img.shields.io/badge/-Developing-6D28D9?style=flat-square"/> | Grounded answering over structured catalogs, refusal over fabrication |
| **Spatio-Temporal ML** | <img src="https://img.shields.io/badge/-Exploring-4F46E5?style=flat-square"/> | Anomaly tracking across medium-range weather forecast fields |
| **MLOps** | <img src="https://img.shields.io/badge/-Learning-4F46E5?style=flat-square"/> | Reproducible environments, model packaging, deployment workflows |

</div>

---

## Featured Projects

<details>
<summary><b>GroundTruth Shop Assistant</b> — Conversational shopping assistant that does not lie</summary>

<br/>

A conversational commerce assistant built for the R3 problem statement, *"The Conversational Shopping Assistant That Doesn't Lie."* Every product claim the assistant makes is grounded in catalog data; when the data does not support an answer, the assistant says so instead of inventing one.

| Attribute | Details |
|:--|:--|
| **Stack** | `Python` `LLM` `Retrieval` |
| **Impact** | Hackathon entry competing among ~1,000 registered teams |
| **Repository** | [Rushithaborra/groundtruth-shop-assistant](https://github.com/Rushithaborra/groundtruth-shop-assistant) |

The core engineering problem is not generation but verification: separating what the model says from what the catalog supports, and making the boundary visible to the user. The system is designed so that a missing fact produces an explicit "not available" rather than a plausible guess.

</details>

<details>
<summary><b>AlgoVerse</b> — AI-powered enhancement of an algorithm visualization platform</summary>

<br/>

A team-built learning platform that pairs algorithm visualizations with an AI tutor. I owned the model-adaptation pipeline: from raw DSA content to a fine-tuned model served locally and consumed by the team's application layer.

| Attribute | Details |
|:--|:--|
| **Stack** | `Python` `Unsloth` `LoRA` `Phi-3-mini` `GGUF` `Ollama` `Linux` `Google Colab` |
| **Performance** | End-to-end pipeline validated on a short training run |
| **Security** | Fully local inference — no student queries leave the host machine |
| **Impact** | Delivered the model endpoint consumed by the team's LangChain integration |

My contribution spanned four stages: provisioning the Linux and Ollama inference environment, building the instruction dataset, fine-tuning Phi-3-mini with LoRA through Unsloth, and exporting the result to GGUF for deployment through a custom Ollama Modelfile. The project demonstrated that a small model can be adapted and served on commodity hardware without external API dependencies.

</details>

<details>
<summary><b>Extreme Weather Anomaly Tracker</b> — Smart India Hackathon 2026 · Team ResQcrew</summary>

<br/>

A prototype for the MoES/NCMRWF problem statement *"AI-Driven Spatio-Temporal Tracking of Extreme Weather Anomalies in Medium-Range Forecasts."* The system detects anomalous regions in forecast fields and tracks how they evolve across forecast lead times.

| Attribute | Details |
|:--|:--|
| **Stack** | `Python` |
| **Impact** | Deployable prototype submitted for SIH 2026 shortlisting |

The challenge combines two hard problems: defining "anomalous" relative to a forecast baseline, and maintaining identity of a weather feature as it moves and deforms over time. The prototype focuses on a deployable pipeline that forecasters could inspect, rather than an opaque score.

</details>

<details>
<summary><b>Small Business Web Templates</b> — Production websites for local businesses</summary>

<br/>

A reusable website system for small businesses in Visakhapatnam, starting with a dental-clinic template designed to be adapted quickly for new clients.

| Attribute | Details |
|:--|:--|
| **Stack** | `HTML` `CSS` `JavaScript` |
| **Security** | HTTPS-only hosting, no client data stored server-side |
| **Impact** | Online presence for businesses without in-house technical staff |

Built as a template-first product: one well-structured base that can be re-themed per client, which keeps delivery time low and quality consistent. The work is client-facing, so the constraints are practical — load speed on mobile networks, easy content updates, and clear calls to action.

</details>

---

## Experience

### AI/ML Intern — AlgoVerse (Team Project)

Owned the model-adaptation track of a team building an AI tutor for an algorithm visualization platform, delivering a fine-tuned, locally served language model to the application layer.

- Provisioned a Linux and Ollama environment for local LLM inference
- Built a Python DSA instruction dataset as structured JSON instruction–response pairs
- Configured Unsloth and fine-tuned Phi-3-mini with LoRA on Colab GPUs
- Exported the model to GGUF and deployed it through a custom Ollama Modelfile
- Handed off a model endpoint integrated by teammates through LangChain

<img src="https://img.shields.io/badge/LoRA-1E1B4B?style=flat-square"/> <img src="https://img.shields.io/badge/Unsloth-1E1B4B?style=flat-square"/> <img src="https://img.shields.io/badge/Phi--3--mini-1E1B4B?style=flat-square"/> <img src="https://img.shields.io/badge/GGUF-1E1B4B?style=flat-square"/> <img src="https://img.shields.io/badge/Ollama-1E1B4B?style=flat-square"/> <img src="https://img.shields.io/badge/Linux-1E1B4B?style=flat-square&logo=linux&logoColor=A78BFA"/>

### Freelance Web Developer — Independent
`2026 – Present` · Visakhapatnam, India

Design and build websites for local small businesses, using a reusable template system to deliver consistent, fast, mobile-first sites.

- Built a dental-clinic site as the first reusable client template
- Handle requirements, design, build, and deployment end to end
- Optimize for mobile load performance and simple content updates

<img src="https://img.shields.io/badge/HTML-1E1B4B?style=flat-square&logo=html5&logoColor=A78BFA"/> <img src="https://img.shields.io/badge/CSS-1E1B4B?style=flat-square&logo=css3&logoColor=A78BFA"/> <img src="https://img.shields.io/badge/JavaScript-1E1B4B?style=flat-square&logo=javascript&logoColor=A78BFA"/> <img src="https://img.shields.io/badge/Client%20Delivery-1E1B4B?style=flat-square"/>

---

## Achievements

<div align="center">

| Recognition | Details |
|:--|:--|
| **Smart India Hackathon 2026** | Team ResQcrew · NCMRWF extreme weather anomaly tracking |
| **Seva First Innovation Challenge 2026** | Team Crew · ANITS IIC |
| **R3 Conversational Commerce Hackathon** | GroundTruth Shop Assistant · ~1,000 registered teams |

</div>

---

## GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Rushithaborra&show_icons=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&text_color=C9D1D9&border_color=2E1065&border_radius=10" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rushithaborra&layout=compact&langs_count=8&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9&border_color=2E1065&border_radius=10" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=Rushithaborra&background=0D1117&border=2E1065&ring=8B5CF6&fire=A78BFA&currStreakNum=E9D5FF&sideNums=E9D5FF&currStreakLabel=A78BFA&sideLabels=C4B5FD&dates=8B949E&border_radius=10" alt="GitHub streak"/>

</div>

---

## GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Rushithaborra&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7" alt="Trophies"/>

</div>

---

## Contribution Activity

<div align="center">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Rushithaborra&bg_color=0D1117&color=C4B5FD&line=8B5CF6&point=E9D5FF&area=true&area_color=7C3AED&hide_border=true&radius=10" alt="Activity graph"/>

</div>

---

## Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rushithaborra/Rushithaborra/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Rushithaborra/Rushithaborra/output/github-snake.svg"/>
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/Rushithaborra/Rushithaborra/output/github-snake-dark.svg"/>
</picture>

</div>

---

## Current Focus

```yaml
learning:
  - Deep Learning
  - Natural Language Processing
  - Generative AI
  - MLOps

building:
  - GroundTruth Shop Assistant
  - Reusable website templates for small businesses

exploring:
  - RAG assistant for Indian education-loan information
  - Evaluation methods for grounded LLM outputs
  - Spatio-temporal anomaly detection

open_to:
  - AI/ML engineering internships
  - LLM and RAG collaborations
  - Hackathon teams
  - Open-source contributions
```

---

## Connect

<div align="center">

<a href="https://github.com/Rushithaborra"><img src="https://img.shields.io/badge/GitHub-1E1B4B?style=for-the-badge&logo=github&logoColor=E9D5FF"/></a>

</div>

---

<div align="center">

*Ground every answer. Measure every claim.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,30:4C1D95,65:1E1B4B,100:0D1117&height=130&section=footer&reversal=true" width="100%" alt="footer"/>

</div>