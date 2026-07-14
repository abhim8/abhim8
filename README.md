# Hi there 👋, I'm Abhilash Movva
<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=850&lines=Software+Engineer;Backend+Engineering+%E2%80%A2+Java+%E2%80%A2+Spring+Boot;Distributed+Systems+%26+Platform+Engineering;Cloud-Native+Applications;Applied+AI+%E2%80%A2+RAG+%E2%80%A2+MCP+%E2%80%A2+Spring+AI;Building+Scalable+Enterprise+Platforms;Open+Source+Contributor" alt="Typing SVG" />
  
[![Location](https://img.shields.io/badge/Location-Bengaluru,_India-6D28D9?style=for-the-badge&logo=googlemaps&logoColor=E9D5FF)](https://www.google.com/maps/place/Bengaluru)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-5B21B6?style=for-the-badge&logo=linkedin&logoColor=E9D5FF)](https://linkedin.com/in/abhilashmovva)
[![Email](https://img.shields.io/badge/Email-Reach_Out-4C1D95?style=for-the-badge&logo=gmail&logoColor=E9D5FF)](mailto:abhilash.movva@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-2E1065?style=for-the-badge&logo=github&logoColor=E9D5FF)](https://github.com/abhim8)
[![Resume](https://img.shields.io/badge/Resume-View-4C1D95?style=for-the-badge&logo=googledrive&logoColor=E9D5FF)](https://drive.google.com/file/d/1GfdAarF0xn25CvhAsTtUqGhy0F8kxX1w/view)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=abhim8&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS)
![Followers](https://img.shields.io/github/followers/abhim8?style=for-the-badge&color=6d28d9&labelColor=1a0033&logo=github&logoColor=E9D5FF)
![Stars](https://img.shields.io/github/stars/abhim8?style=for-the-badge&color=8b5cf6&labelColor=1a0033&logo=github&logoColor=E9D5FF)

</div>

---

## <img src="https://media.giphy.com/media/WFZvB7VIXBgiz3oDXE/giphy.gif" width="30"> About Me

```yaml
Software Engineer with 4+ years of experience building scalable backend systems,
distributed services, and cloud-native applications.

Currently working at Serko building platform services and AI-powered developer
tools, with hands-on experience in:

- Java & Spring Boot
- Microservices & Distributed Systems
- AWS & Azure
- Event-Driven Architecture
- RAG & LLM Applications
- Model Context Protocol (MCP)
```
---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![Skills](https://skillicons.dev/icons?i=java,py,js,ts,bash&theme=dark)

**Backend & Frameworks**

![Skills](https://skillicons.dev/icons?i=spring,kafka,redis,postgres,graphql,nodejs&theme=dark)

**Cloud, DevOps & Tooling**

![Skills](https://skillicons.dev/icons?i=aws,azure,docker,kubernetes,git,githubactions,grafana&theme=dark)

**Applied AI & LLMs**

![Gemini](https://img.shields.io/badge/Gemini-8B5CF6?style=flat-square&logo=googlegemini&logoColor=white)
![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-7C3AED?style=flat-square&logo=microsoftazure&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-6D28D9?style=flat-square&logo=spring&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-5B21B6?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-6D28D9?style=flat-square)
![AI_Agents](https://img.shields.io/badge/AI_Agents-7E22CE?style=flat-square)

</div>

---

## 🚀 Featured Projects

<details>
<summary><b>🔔 Notification Platform - Event-Driven Multi-Channel Delivery System</b></summary>
<br/>

A production-grade, event-driven notification platform supporting **email, SMS, push, and webhook** delivery channels, built on a **hexagonal architecture** for clean separation between domain logic and infrastructure.

| Aspect | Details |
|---|---|
| **Stack** | Java 23, Spring Boot, Apache Kafka, Redis, PostgreSQL, Docker Compose |
| **Scale** | 5-topic Kafka design for multi-channel event routing and delivery orchestration |
| **Performance** | Asynchronous, non-blocking event consumption with channel-level isolation |
| **Security** | Domain-isolated hexagonal boundaries; provider credentials externalized |
| **Impact** | Reusable, provider-agnostic notification core adaptable to any messaging backend |
| **Repository** | [github.com/abhim8/notification-platform](https://github.com/abhim8/notification-platform) |

Designed around ports-and-adapters principles, the platform decouples core notification logic from third-party providers (SendGrid, Twilio, FCM), enabling clean testability and provider interchangeability without touching business logic. Kafka topics are structured to support retries, dead-letter handling, and channel-specific throughput tuning, with Redis used for idempotency and delivery-state caching.

</details>

<details>
<summary><b>🧠 AI Orchestration Platform - Multi-Agent Planning & Execution Engine</b></summary>
<br/>

An AI orchestration platform built with **Spring AI** and **MCP**, capable of generating, validating, and executing multi-step AI-driven execution plans with dependency-aware parallelism.

| Aspect | Details |
|---|---|
| **Stack** | Java, Spring Boot, Spring AI, Gemini, Model Context Protocol (MCP), Multi-Module Maven |
| **Scale** | Multi-module architecture isolating planning, tooling, and execution concerns |
| **Performance** | Parallel execution derived purely from step-level `dependsOn` graph resolution |
| **Security** | Isolated `planner/` sub-package boundary around all Spring AI integration surfaces |
| **Impact** | Reusable execution-plan validator with cycle detection & confidence thresholding |
| **Repository** | [github.com/abhim8/ai-orchestration-platform](https://github.com/abhim8/ai-orchestration-platform) |

The platform wraps generated plans in a `PlanGenerationResult` envelope around a structured `ExecutionPlan`, with an `ExecutionPlanValidator` performing cycle detection and confidence-based gating before execution. Partial failures are handled gracefully with an inline `executionTrace`, and custom tools (e.g. `ResolveRelativeDateTool`) are exposed to the model via Spring AI's `@Tool` annotation - keeping all LLM-specific logic cleanly isolated from the rest of the system.

</details>

---

## 💼 Experience
- **Software Engineer 2, Serko** `Jul 2025 — Present`
- **Senior Software Engineer, LeadSquared** `Apr 2025 – Jul 2025`
- **Software Engineer, LeadSquared** `Apr 2024 – Mar 2025`
- **Associate Software Engineer, LeadSquared** `Aug 2023 – Mar 2024`
- **SDE Intern, LeadSquared** `Jul 2022 – Jul 2023`

---
  
## 🎓 Education

<div align="center">

| Degree | Institution | Year |
|---|---|:---:|
| **B.Tech, Computer Science & Engineering** | [CMR Technical Campus, Hyderabad](https://cmrtc.ac.in) | 2023 |

</div>

---

## 🚀 Beyond Code
- 💬 Happy to discuss Java, Spring Boot, distributed systems, and backend architecture
- 🧠 Passionate about scalable and reliable production systems
- 🏍️ Motorcycle enthusiast & adventure seeker - always up for a road trip!  
- 🎮 Enjoy hackathons and building practical side projects
- ⚡ Fun fact: I believe there are only two ways to write error-free programs; only the third one works 😄

---

## 📊 GitHub Stats
<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=abhim8&theme=dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=abhim8&theme=dark&utcOffset=5.5" />
</p>

---

## 🔥 Streak
[![GitHub Streak](https://streak-stats.demolab.com?user=abhim8)](https://git.io/streak-stats)

---

## 📈 Contribution Graph
<img align="left" width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=abhim8&theme=react-dark&area=true&hide_border=true&bg_color=000000&color=ffffff&line=00ffff&point=ffffff" />

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6d28d9,50:4c1d95,100:1a0033&height=150&section=footer" width="100%"/>
</div>







<!-- OLD_2 -->
<!-- 
<p align="center">
  <img src="https://dynamic.brandcrowd.com/asset/logo/85f42d8f-d011-495b-86d6-13a7ed367e06/logo-search-grid-1x?v=637861100082100000&text=Abhilash+Movva&colorpalette=red" alt="Abhilash Movva" />
</p> 
-->

<!-- 
# Hi there 👋, I'm Abhilash Movva

## 👨‍💻 About Me
Software Engineer with 4+ years of experience building scalable backend systems,
distributed services, and cloud-native applications.

Currently working at Serko building platform services and AI-powered developer
tools, with hands-on experience in:

- Java & Spring Boot
- Microservices & Distributed Systems
- AWS & Azure
- Event-Driven Architecture
- RAG & LLM Applications
- Model Context Protocol (MCP)


## 🚀 Featured Projects
- 🤖 AI Orchestration Platform – AI agent orchestration using Spring Boot and MCP
- 🔔 Distributed Notification Platform – Event-driven notification system with Kafka and Redis


## 🔗 Connect
- 📄 [Resume](https://drive.google.com/file/d/1GfdAarF0xn25CvhAsTtUqGhy0F8kxX1w/view?usp=drive_link)
- 💼 [Linkedin](https://www.linkedin.com/in/abhilashmovva)
- 🌐 [Portfolio](https://github.com/abhim8)
- 📧 [Email](mailto:abhilash.movva@gmail.com)

## 💼 Experience
- **Software Engineer 2, Serko** (Jul 2025 – Present)
- **Senior Software Engineer, LeadSquared** (Apr 2025 – Jul 2025)
- **Software Engineer, LeadSquared** (Apr 2024 – Mar 2025)
- **Associate Software Engineer, LeadSquared** (Aug 2023 – Mar 2024)
- **SDE Intern, LeadSquared** (Jul 2022 – Jul 2023)

## 🛠️ Tech Stack
- 👨‍💻 Languages: Java, Python, Go, Kotlin, JavaScript, C#, C/C++
- ⚙️ Backend: Spring Boot, REST APIs, JPA/Hibernate, Node.js, Apache Kafka
- ☁️ Cloud & DevOps: AWS, Azure, Docker, CI/CD
- 🗄️ Databases: PostgreSQL, MySQL, Redis, DynamoDB, MongoDB
- 🧠 AI & LLM: RAG, LLM integrations, Azure OpenAI, Google Gemini, MCP Gateway/Servers/Clients & Service orchestration
- 🏗️ Architecture: Microservices, Distributed Systems, API design, Event-Driven Systems, Hexagonal Architecture, Caching & Performance Optimization
  
## Education
- 🎓 **B.Tech in Computer Science & Engineering** (2023) @ [CMRTC, Hyderabad, India](https://cmrtc.ac.in)

## 🚀 Beyond Code
- 💬 Happy to discuss Java, Spring Boot, distributed systems, and backend architecture
- 🧠 Passionate about scalable and reliable production systems
- 🏍️ Motorcycle enthusiast & adventure seeker - always up for a road trip!  
- 🎮 Enjoy hackathons and building practical side projects
- ⚡ Fun fact: I believe there are only two ways to write error-free programs; only the third one works 😄


## 📊 GitHub Stats
<p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=abhim8&theme=dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=abhim8&theme=dark&utcOffset=5.5" />
</p>
-->

<!-- <p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=abhim8&theme=dark" />
</p> -->

<!-- <p align="left">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=abhim8&theme=dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=abhim8&theme=dark" />
</p> -->

<!-- 
## 🔥 Streak
[![GitHub Streak](https://streak-stats.demolab.com?user=abhim8)](https://git.io/streak-stats)

## 📈 Contribution Graph
<img align="left" width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=abhim8&theme=react-dark&area=true&hide_border=true&bg_color=000000&color=ffffff&line=00ffff&point=ffffff" />
-->


<!-- ### Hey! 👋
I'm Abhilash Movva, a software engineer from India.

- 👥 SDE @LeadSquared, Bangalore

## Skills
- 👨‍💻 Java, C++, C, JavaScript, Kotlin, Python, PHP, HTML/CSS
- ⚙️ SpringBoot Framework, Node.js, React.js, Electron.js
- ⚙️ Web Full stack development, familar with Android development
- 💽 MySQL, SQL, Mongo

## Contact
- [abhilashmovva.tech](https://abhilashmovva.tech)
- [@abhilashmovva](https://www.linkedin.com/in/abhilash-movva-b979791a1) on LinkedIn
- [@abhilashmovva](https://www.instagram.com/abhilashmovva) on Instagram
- reach me on **abhilash.movva@gmail.com**

## About
- 🌱 I’m currently learning **AWS**.
- 💬 Ask me about **Java, **C++, and DSA**
- ⚡ Fun fact: I believe there are only two ways to write error-free programs; only the third one works 😄 
<be>
-->


<!-- <img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/saimanoharhm/saimanoharhm/main/coding.webp"> -->
<!-- 👯 I’m looking to collaborate on -->
<!-- - 🤝 I’m looking for help with agd -->

<!-- <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abhim8&show_icons=true&locale=en&layout=compact" alt="abhim8"/> -->

<!-- <img align="center" src="https://github-readme-stats.vercel.app/api?username=abhim8&show_icons=true&locale=en" alt="abhim8" /> -->
<!-- ## Stats -->
<!-- ![](https://roadmap.sh/card/wide/67702caa70129741a8c8e989?variant=dark) -->
<!-- ![](https://github-readme-stats.vercel.app/api/top-langs?username=abhim8&show_icons=true&locale=en&layout=donut) -->
<!-- ![](https://github-readme-stats.vercel.app/api?username=abhim8&show_icons=true&locale=en) -->

<!-- <p> <img src="https://github-readme-stats.vercel.app/api?username=abhim8&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=191919"> </p> -->

<!-- <p> <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abhim8&" alt="abhim8" /></p> -->
<!-- <br> -->














<!-- OLD_1 -->
<!-- ### Hey! 👋
I'm Abhilash Movva, a software engineer from India.

- 👥 SDE @LeadSquared, Bangalore

## Skills
- 👨‍💻 Java, C++, C, JavaScript, Kotlin, Python, PHP, HTML/CSS
- ⚙️ SpringBoot Framework, Node.js, React.js, Electron.js
- ⚙️ Web Full stack development, familar with Android development
- 💽 MySQL, SQL, Mongo

## Contact
- [abhilashmovva.tech](https://abhilashmovva.tech)
- [@abhilashmovva](https://www.linkedin.com/in/abhilash-movva-b979791a1) on LinkedIn
- [@abhilashmovva](https://www.instagram.com/abhilashmovva) on Instagram
- reach me on **abhilash.movva@gmail.com**

## About
- 🌱 I’m currently learning **AWS**.
- 💬 Ask me about **Java, **C++, and DSA**
- ⚡ Fun fact: I believe there are only two ways to write error-free programs; only the third one works 😄 
<be>
-->


<!-- <img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/saimanoharhm/saimanoharhm/main/coding.webp"> -->
<!-- 👯 I’m looking to collaborate on -->
<!-- - 🤝 I’m looking for help with agd -->

<!-- <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=abhim8&show_icons=true&locale=en&layout=compact" alt="abhim8"/> -->

<!-- <img align="center" src="https://github-readme-stats.vercel.app/api?username=abhim8&show_icons=true&locale=en" alt="abhim8" /> -->
<!-- ## Stats -->
<!-- ![](https://roadmap.sh/card/wide/67702caa70129741a8c8e989?variant=dark) -->
<!-- ![](https://github-readme-stats.vercel.app/api/top-langs?username=abhim8&show_icons=true&locale=en&layout=donut) -->
<!-- ![](https://github-readme-stats.vercel.app/api?username=abhim8&show_icons=true&locale=en) -->

<!-- <p> <img src="https://github-readme-stats.vercel.app/api?username=abhim8&&show_icons=true&title_color=ffffff&icon_color=bb2acf&text_color=daf7dc&bg_color=191919"> </p> -->

<!-- <p> <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=abhim8&" alt="abhim8" /></p> -->
<!-- <br> -->


