<!-- Animated wave header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24c6dc&height=220&section=header&text=Daniel%20Canlapan&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-stack%20%C2%B7%20Creative%20Web%20%C2%B7%20AI%20Engineering&descAlignY=58&descSize=18" alt="Daniel Canlapan header" />
</p>

<!-- Typing banner -->
<p align="center">
  <a href="https://danielcanlapan.vercel.app">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=24C6DC&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Daniel+%F0%9F%91%8B;4th-year+Computer+Science+student+%F0%9F%87%B5%F0%9F%87%AD;I+build+interactive+3D+web+experiences;Full-stack%3A+React+%C2%B7+Node+%C2%B7+PostgreSQL;Shipping+with+Claude+Code%2C+one+phase+at+a+time;Now%3A+Vue.js+%2B+a+multimodal+RAG+system" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://danielcanlapan.vercel.app"><img src="https://img.shields.io/badge/Portfolio-danielcanlapan.vercel.app-24c6dc?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/daniel-martin-canlapan-1b2760380"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:danielcanlapan0402@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-302b63?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=dncnl&color=302b63&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />
</p>

---

## 🧭 About me

```ts
const daniel = {
  role: "BS Computer Science Student",
  basedIn: "Philippines 🇵🇭",
  focus: ["Full-stack web", "Interactive 3D & motion", "AI integrations"],
  currentlyLearning: "Vue.js",
  currentlyBuilding: "My first multimodal RAG system",
  workflow: "Claude Code + phased plans + tests before shipping",
  offline: ["graphic design", "digital art", "web design"],
  openTo: "remote freelance & part-time roles",
};
```

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,vite,vue,threejs,nodejs,express,postgres,supabase&perline=12" alt="Web stack" />
  <br/>
  <img src="https://skillicons.dev/icons?i=python,tensorflow,flutter,dart,figma,git,github,vercel,vscode&perline=12" alt="AI, mobile and tools" />
</p>

<details>
<summary><b>🔍 Click for the full breakdown</b></summary>
<br/>

| Area | What I use |
|------|-----------|
| **Frontend** | React, TypeScript, Vite, Three.js, GSAP, custom shaders, HTML/CSS |
| **Backend** | Node.js, Express, REST APIs, Vercel serverless, JWT auth |
| **Data** | PostgreSQL, Supabase |
| **AI / ML** | Gemini API, TensorFlow.js, pandas, NumPy, scikit-learn |
| **Mobile** | Flutter, Dart |
| **Testing** | Vitest, Playwright |
| **Design** | Figma, Canva |
| **Workflow** | Git, GitHub, Claude Code |

</details>

---

## 🚀 Featured projects

> Click a project to expand it.

<details open>
<summary><b>🖐️ Handoff</b>: an interactive 3D portfolio you shake hands with &nbsp;·&nbsp; <i>solo</i></summary>
<br/>

A rigged 3D hand reaches out. Hold to shake it, and about 120 fragments assemble into a screen with five sections, each with its own pose.

- Three.js, custom shaders, lazy-loaded bloom, GSAP, strict TypeScript on Vite
- Performance tier that steps down on slower devices
- Touch, keyboard and reduced-motion support
- Built with Claude Code in planned phases

[![Live demo](https://img.shields.io/badge/Live-demo-24c6dc?style=flat-square&logo=vercel)](https://handoff-kappa-one.vercel.app) [![Repo](https://img.shields.io/badge/Repo-handoff-181717?style=flat-square&logo=github)](https://github.com/dncnl/handoff)
</details>

<details>
<summary><b>📄 Stackly</b>: merge images, PDFs and Word files into one PDF, fully in the browser &nbsp;·&nbsp; <i>solo</i></summary>
<br/>

Your files never leave your device. A test checks that the app makes zero outside requests.

- React 19, TypeScript, Vite
- Strict Content-Security-Policy, file detection by content (not extension), sanitised Word rendering
- Vitest + Playwright tests
- Calm, typography-led design: ink, warm paper and one oxblood accent

[![Live demo](https://img.shields.io/badge/Live-demo-24c6dc?style=flat-square&logo=vercel)](https://pdf-compile.vercel.app) [![Repo](https://img.shields.io/badge/Repo-pdf--compile-181717?style=flat-square&logo=github)](https://github.com/dncnl/pdf-compile)
</details>

<details>
<summary><b>🍚 Kain</b>: a price-optimized nutrition planner for Filipino families &nbsp;·&nbsp; <i>team · 🏆 Top 30 of 200+ schools, Enactus PH 2026</i></summary>
<br/>

An offline-first PWA. A bounded-knapsack solver picks the most nutritious meal plan within a family's budget, then builds the shopping list and a nutrition chart.

- My role: frontend and backend development, planning and documentation
- Recipe data regenerated from price sources with a build script, plus a Node test suite

[![Live demo](https://img.shields.io/badge/Live-demo-24c6dc?style=flat-square&logo=vercel)](https://kain-enactus.vercel.app) [![Repo](https://img.shields.io/badge/Repo-kain--enactus--2026-181717?style=flat-square&logo=github)](https://github.com/dncnl/kain-enactus-2026)
</details>

<details>
<summary><b>🗺️ MAPA-Sarap</b>: a food directory with an AI assistant &nbsp;·&nbsp; <i>team · I led backend & deployment</i></summary>
<br/>

- PostgreSQL schema and migrations, REST API on Vercel serverless functions
- JWT + bcrypt auth with server-side admin checks
- SarapBot: a Gemini-powered assistant grounded in the app's own database, with retry and fallback model

[![Live demo](https://img.shields.io/badge/Live-demo-24c6dc?style=flat-square&logo=vercel)](https://sen02-mapa-sarap.vercel.app) [![Repo](https://img.shields.io/badge/Repo-mapa--sarap-181717?style=flat-square&logo=github)](https://github.com/dncnl/sen02_mapa-sarap)
</details>

<details>
<summary><b>➕ More projects</b></summary>
<br/>

| Project | What it is | My role |
|---------|-----------|---------|
| [**Kalinga**](https://github.com/dncnl/kalinga) | Multilingual, offline-first Flutter care companion for migrant caregivers (Taiwan Presidential Hackathon, International Track) | Frontend & planning |
| [**AUF EnrollAssist**](https://auf-enrollassist.vercel.app) | Enrollment guide with an in-browser MobileBERT Q&A that answers only from official guidelines | Main developer |
| [**Portfolio**](https://danielcanlapan.vercel.app) | My personal site, designed in Figma, built in React | Solo |

</details>

---

## ⚙️ How I build

```mermaid
flowchart LR
    A[💡 Idea] --> B[📝 Phased plan<br/>+ CLAUDE.md]
    B --> C[🤖 Build with<br/>Claude Code]
    C --> D[🧪 Test<br/>Vitest · Playwright]
    D --> E{Passes?}
    E -- no --> C
    E -- yes --> F[🚀 Ship on Vercel]
```

---

## 📊 GitHub activity

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=dncnl&show_icons=true&hide_border=true&bg_color=00000000&title_color=24c6dc&icon_color=24c6dc&text_color=8b949e&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dncnl&layout=compact&hide_border=true&bg_color=00000000&title_color=24c6dc&text_color=8b949e" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=dncnl&hide_border=true&background=00000000&ring=24C6DC&fire=24C6DC&currStreakLabel=24C6DC&sideLabels=8b949e&dates=8b949e&currStreakNum=c9d1d9&sideNums=c9d1d9" alt="GitHub streak" />
</p>

<!-- Contribution snake (generated by .github/workflows/snake.yml) -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dncnl/dncnl/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dncnl/dncnl/output/github-snake.svg" />
    <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/dncnl/dncnl/output/github-snake.svg" />
  </picture>
</p>

---

## 🤝 Let's connect

I'm open to remote freelance and part-time work in full-stack, front-end and AI-assisted development. The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/daniel-martin-canlapan-1b2760380) or [email](mailto:danielcanlapan0402@gmail.com).

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24c6dc,50:302b63,100:0f0c29&height=120&section=footer" alt="footer wave" />
</p>
