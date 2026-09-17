<!-- SECTION G: VISITOR COUNTER -->
<p align="left">
  <img src="https://komarev.com/ghpvc/?username=speri99&label=Profile%20Views&color=0e75b6&style=flat" alt="speri99 profile views" />
</p>

<!-- SECTION A: HEADER -->
<div align="center">
  <h1>Hey, I'm Sarma Peri 👋</h1>

  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=00D9FF&center=true&vCenter=true&width=650&lines=12%2B+years+shipping+Java%2FSpring+%26+Angular%2FReact+systems;Lately%3A+React+Native+%2B+AI+agents+for+test+automation;I+build+the+thing%2C+then+I+build+the+thing+that+checks+it" alt="Typing SVG" />
  </a>
</div>

---

<!-- SECTION B: ABOUT ME -->
## 🚀 About Me

12+ years building backend systems in **Java/Spring Boot** and front ends in **Angular** and **React/Next.js**, mostly on enterprise workflows — reconciliation, case management, multi-tenant admin platforms. The repos below are a real cross-section of that: an Angular reconciliation UI, a Next.js emergency-response case tracker, a React school-admin console.

More recently I've moved into two areas outside that day job:

- **React Native** — a geofencing attendance tracker (see [Time Tracker](#-time-tracker) below) that does its own GPS-jitter filtering and hysteresis logic, fully offline
- **AI agents for test automation** — exploring whether an LLM-driven agent can execute and validate a QA scenario from a plain-English description instead of a hand-scripted test

Outside of code, I write/record about this stuff on YouTube and Medium.

---

<!-- SECTION B2: FEATURED PROJECTS -->
## 💼 Featured Projects

### 📍 Time Tracker
**[speri99/time-tracker](https://github.com/speri99/time-tracker)** · React Native (Expo), TypeScript

Detects office check-in/out automatically by GPS geofencing — no manual clock-in, no server, no account. The interesting part is the detector, not the UI:

- Tracks signed perpendicular distance from a "gate" line and latches which side you're on, with a ±15m dead band so GPS jitter on the boundary can't fire false crossings (a Schmitt trigger, basically)
- Layers an accuracy filter, a proximity check, an along-track check, a 90s debounce, and a staleness flag before any crossing is written
- Direction comes purely from which half-plane a fix lands in — never compass heading, so it's correct regardless of which way you're facing
- Core detection logic (`crossingEngine`, `geo`, `sessions`) is pure and fully unit-tested with no device required

### 🛡️ SafeSignal
**[speri99/gaied-f-b-i](https://github.com/speri99/gaied-f-b-i)** · Next.js, TypeScript, AWS (Bedrock, DynamoDB, Pinpoint)

A panic-button case management platform for domestic violence emergency response — one tap creates a case record with victim/location/incident details and notifies authorities in real time, no typing or calling required in the moment.

### 🏫 School OS
**[speri99/school-plaform-ui](https://github.com/speri99/school-plaform-ui)** · React, Tailwind, Radix UI

Front end for a multi-tenant school administration platform — org/school onboarding, super-admin and admin dashboards, role-based views for managing staff and student lifecycle.

### 🤖 AI Testing Agent
VS Code extension prototype — not yet public — that takes a QA requirement in plain English and executes/validates it instead of me hand-scripting every step.

- Built on the **VS Code Language Model API** (a standardized interface to the model, similar in spirit to how JDBC standardizes access to different databases) rather than being tightly coupled to one model implementation
- Orchestrates **MCP** for backend/database validation and **Playwright** for UI automation and evidence capture
- Demonstrated end-to-end on a real enterprise workflow — enrolling a customer into a payment plan across a legacy account system, the core servicing app, and a downstream payment processor — validating UI completion, DB state, transaction success, and cross-system logging from one instruction

> The idea: AI already accelerated how fast I can write code. This is about using it to accelerate how fast I can validate it.

---

<!-- SECTION C: TECH STACK -->
## 🛠️ Tech Stack

### 🎨 Frontend
<p>
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
</p>

### ⚙️ Backend
<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/REST_API-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Microservices-FF6B6B?style=for-the-badge&logo=apacheairflow&logoColor=white" />
</p>

### 🗄️ Data, Cloud & Tools
<p>
  <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" />
</p>

---

<!-- SECTION D: SOCIAL MEDIA LINKS -->
## 📲 Find Me Online

<p align="left">
  <a href="https://www.youtube.com/@speri99" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  <a href="https://medium.com/@sarmaperi" target="_blank">
    <img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" />
  </a>
  <a href="https://www.instagram.com/speri99" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://www.linkedin.com/in/sharma-peri-8788b769/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/speri99" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

<!-- SECTION E: GITHUB STATS -->
## 📊 GitHub Stats

<div align="center">

  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=speri99&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="Sarma's GitHub Stats" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=speri99&theme=tokyonight&hide_border=true" alt="Sarma's Streak Stats" width="49%" />

  <br/>

  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=speri99&layout=compact&theme=tokyonight&hide_border=true&langs_count=10" alt="Top Languages" width="50%" />

</div>

---

<!-- SECTION H: FOOTER -->
## 🤝 Let's Connect!

Open to collaborations, freelance work, or just a good conversation about testing, agents, or whatever I'm mid-debugging. Reach out.

<p align="center">
  <a href="https://www.linkedin.com/in/sharma-peri-8788b769/" target="_blank">
    <img src="https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.youtube.com/@speri99" target="_blank">
    <img src="https://img.shields.io/badge/Subscribe_on_YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://medium.com/@sarmaperi" target="_blank">
    <img src="https://img.shields.io/badge/Read_on_Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" />
  </a>
</p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" width="100%" />
</div>
