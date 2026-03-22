<div align="center">

<!-- Header: rounded gradient only — no subtitle inside the image (avoids blob overlap & tiny unreadable text) -->
<img src="https://capsule-render.vercel.app/api?type=rounded&color=0:0d0d12,50:1a1033,100:2d1b69&height=210&section=header&text=Lohith%20M&fontSize=76&fontColor=ffffff&fontAlignY=50&animation=fadeIn" width="100%" alt="Lohith M"/>

<br/>

<h3 align="center">Software engineer · Systems · Real-time · AI tooling</h3>
<p align="center">
  <strong>Hassan, Karnataka</strong> · he/him · <em>Open-source contributor (Apache Airflow)</em>
</p>

<!-- Wider canvas + shorter lines = nothing gets clipped mid-word -->
<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=C4B5FD&center=true&vCenter=true&width=980&height=55&lines=Real-time+collab+%C2%B7+WebSockets+%C2%B7+Docker+sandboxes;Apache+Airflow+%C2%B7+merged+PRs+%C2%B7+production-scale+OSS;RAG+%C2%B7+LangChain+%C2%B7+FAISS+%C2%B7+sub-15ms+retrieval;Building+products+that+stay+fast+under+load" alt="Rotating focus areas"/>
</a>

<br/><br/>

[![GitHub](https://img.shields.io/badge/GitHub-Lohith625-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Lohith625)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lohith-m-601021391/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF6B35?style=for-the-badge&logo=firefox-browser&logoColor=white)](https://mlohith.netlify.app)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/Lohith-625)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mlohith25@gmail.com)

<br/>

![Profile views](https://komarev.com/ghpvc/?username=Lohith625&style=for-the-badge&color=6366f1&label=VIEWS)

</div>

---

## What I do

<table>
<tr>
<td width="55%" valign="top">

I build **low-latency, production-minded systems**: real-time collaboration, **Docker-sandboxed** execution, and **RAG** pipelines that stay predictable when data grows.

**Highlights**

- **Apache Airflow** — merged PRs into widely used production OSS  
- **DevCollab** — multi-user coding, **~1–5ms** sync, sandboxed runs  
- **Codebase RAG** — **4,300+** chunks indexed, **~11ms** retrieval (FAISS)  
- Ask me about **WebSockets · Docker · RAG · Airflow**

</td>
<td width="45%" valign="top" align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="260" alt=""/>

```javascript
const lohith = {
  location: "Hassan, Karnataka 🇮🇳",
  focus: ["real-time", "OSS", "RAG"],
  mantra: "Ship, measure, harden, repeat.",
};
```

</td>
</tr>
</table>

## Mental model

```mermaid
flowchart LR
  subgraph RT["Real-time"]
    A[WebSockets]
    B[Sandboxed runtimes]
  end
  subgraph AI["Data & AI"]
    C[RAG]
    D[Vector search]
  end
  subgraph Ops["Ship"]
    E[Docker]
    F[CI / Git]
  end
  RT --> Ops
  AI --> Ops
```

## Tech stack

**Languages**

<p align="center">
<img src="https://skillicons.dev/icons?i=python,js,java,c&perline=8" alt="Languages"/>
</p>

**Frontend**

<p align="center">
<img src="https://skillicons.dev/icons?i=react,html,css,tailwind&perline=8" alt="Frontend"/>
</p>

**Backend & real-time**

<p align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi&perline=8" alt="Backend"/>
</p>
<p align="center">
<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white" alt="Socket.io"/>
</p>

**Data, AI & search**

<p align="center">
<img src="https://skillicons.dev/icons?i=mongodb,mysql,firebase&perline=8" alt="Data"/>
</p>
<p align="center">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/FAISS-FF6F00?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS"/>
</p>

**DevOps**

<p align="center">
<img src="https://skillicons.dev/icons?i=docker,github,git,linux&perline=8" alt="DevOps"/>
</p>
<p align="center">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
</p>

## Signature work

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### ⚡ DevCollab
> Real-time collaborative coding — Docker-sandboxed, built for speed.

Multi-user sync with sandboxed execution so nobody nukes the host.

```
10+ concurrent users
1–5ms sync latency
~1.3s sandbox execution
```

![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Socket.IO](https://img.shields.io/badge/-Socket.IO-010101?style=flat-square&logo=socketdotio)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

</td>
<td width="50%" valign="top">

### 🧠 Codebase RAG
> Ask your codebase anything — answers in milliseconds.

Chunk, embed, retrieve with FAISS + LangChain.

```
4,300+ code chunks indexed
~11ms query latency (FAISS)
100% test pass rate
```

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)
![FAISS](https://img.shields.io/badge/-FAISS-FF6F00?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖼️ Pixora
> Images with auth and CDN delivery that holds up.

Google OAuth, JWT, Cloudinary — wired properly.

```
Google OAuth + JWT auth
Cloudinary CDN delivery
Tailwind responsive UI
```

![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/-Cloudinary-3448C5?style=flat-square)

</td>
<td width="50%" valign="top">

### 🌊 Apache Airflow
> OSS used at serious scale — real reviews, real merges.

```
50,000+ GitHub stars
Multiple merged PRs
UI · Docs · Import fixes
```

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/-Apache_Airflow-017CEE?style=flat-square&logo=Apache+Airflow&logoColor=white)

[View merged PRs →](https://github.com/pulls?q=is%3Apr+author%3ALohith625+is%3Amerged)

</td>
</tr>
</table>
</div>

## GitHub activity

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Lohith625&theme=dracula&no-frame=true&row=1&column=7&margin-w=10&no-bg=true" width="100%" alt="GitHub trophies"/>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=Lohith625&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c4b5fd&icon_color=a78bfa&text_color=c9d1d9&rank_icon=github" height="180" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lohith625&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=c4b5fd&text_color=c9d1d9&langs_count=8" height="180" alt="Top languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Lohith625&theme=tokyonight&hide_border=true&background=0d1117&ring=c4b5fd&fire=ff6b6b&currStreakLabel=c4b5fd&sideLabels=c9d1d9&dates=c9d1d9" width="88%" alt="Contribution streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Lohith625&bg_color=0d1117&color=c4b5fd&line=a78bfa&point=ff6b6b&area=true&area_color=6366f133&hide_border=true&custom_title=Contribution%20activity" width="100%" alt="Activity graph"/>

<br/><br/>

<img src="https://raw.githubusercontent.com/Lohith625/Lohith625/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake"/>

</div>

---

<div align="center">

<sub>Refresh the page for a new quote.</sub>

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" width="82%" alt="Quote"/>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0d12,50:1a1033,100:2d1b69&height=115&section=footer&fontSize=16&fontColor=c4b5fd&text=Let%27s%20build%20something%20that%20survives%20production&fontAlignY=70" width="100%" alt="Footer"/>

</div>
