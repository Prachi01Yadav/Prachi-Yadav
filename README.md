<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:6a5acd,100:00c2cb&height=160&text=Prachi%20Yadav&fontSize=42&fontColor=ffffff&fontAlignY=40&desc=Software%20Developer%20%7C%20Distributed%20Systems%20%26%20AI&descAlignY=68&descSize=18&descColor=f0f0f0" alt="Header" width="100%" />
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/prachiyadav01/)
[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prachi.ydv1104@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Prachi01Yadav)

</div>

<br/>

```go
type Developer struct {
    Name       string   // "Prachi Yadav"
    Role       string   // "B.Tech CSE @ IIIT Agartala"
    Focus      []string // Distributed Systems, Backend, Applied AI
    Building   []string // Service Meshes, AI Agents, API Gateways
    OpenSource string   // "Contributor @ Kuadrant Operator (CNCF)"
    Goal       string   // "Build resilient, large-scale systems"
}
```

---

## 🚀 About Me

- 🎓 B.Tech in Computer Science @ **Indian Institute of Information Technology, Agartala** (2024 – 2028)
- 🛰️ I build **distributed systems, backend infrastructure, and AI-driven applications** — from service meshes to fine-tuned LLM agents
- 🌱 Currently exploring **AI, Blockchain, and Go**
- 🤝 Open source contributor at **Kuadrant Operator (CNCF)** — working on Kubernetes-native API gateways
- 🎯 **Aspiring to build large-scale, resilient systems** that sit at the intersection of distributed infrastructure and applied AI, and to keep growing as an open-source maintainer
- 🏆 Competitive programmer — LeetCode Knight (1850+), Codeforces Pupil (1300+), 1000+ problems solved
- 💬 Looking to collaborate on **open source infrastructure and AI tooling projects**

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend & Architecture**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Gin](https://img.shields.io/badge/Gin-00ADD8?style=flat-square&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Envoy](https://img.shields.io/badge/Envoy%20Proxy-AC6199?style=flat-square&logo=envoyproxy&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**AI / ML**

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Llama 3.1](https://img.shields.io/badge/Llama%203.1-0467DF?style=flat-square&logo=meta&logoColor=white)
![Anthropic Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![LoRA/GRPO](https://img.shields.io/badge/LoRA%20%2F%20GRPO-6E56CF?style=flat-square)

**Databases, Cloud & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 💡 Featured Projects

### 🔗 [Distributed Resilience Control Plane](#)
A Layer-7 service mesh control system that monitors microservices in real time, auto-detects SLA violations, and trips circuit breakers to reroute traffic away from unhealthy services — with every incident permanently logged on-chain.
- Built a high-throughput pipeline ingesting **10,000+ network events/sec** via a concurrent Go consumer over persistent TCP streams, Redis sliding windows, and OPA policy evaluation in **sub-2ms**
- Used `go-ethereum` for a tamper-proof, immutable audit trail of security breaches
- **Stack:** Go · PostgreSQL · Gin · Envoy Proxy (xDS) · gRPC · TLS · Redis · Docker · go-ethereum

### 🤖 Enterprise AP Environment
Built for the **Meta × Hugging Face OpenEnv Hackathon** — an AI training environment simulating a company's invoice-processing workflow, where an agent validates invoices against an ERP system to catch fraud, duplicates, and pricing errors.
- Co-designed 5 progressively harder challenges and fine-tuned **Llama-3.1-8B** with LoRA + GRPO
- Achieved **+238% accuracy** on standard tasks and **+333%** on expert vendor-negotiation tasks
- **Stack:** Python · FastAPI · Docker · Llama-3.1 · HuggingFace TRL · Google Colab

---

## 🏅 Achievements

- 🏆 **Finalist — Meta × Hugging Face OpenEnv Hackathon (2026):** Top 800 out of 60,000+ teams
- 🥈 **Finalist — AtomQuest Hackathon '26:** Top 10 nationwide, presented the solution at Atomberg Technologies HQ, Pune
- 💼 **PayPal Career Academy 2.0:** 1 of 48 scholars nationwide, mentored by PayPal in the global payments space
- 🎓 **AlgoUniversity Scholar:** 1 of 200 selected from 100,000+ applicants for advanced DSA & CP mentorship
- 🌟 **Amazon Future Engineer Scholar:** 1 of 400 selected nationally for a ₹40k grant and professional development
- 💻 **Competitive Programming:** LeetCode Knight (1850+) · Codeforces Pupil (1300+) · AtCoder 7 Kyu · 1000+ problems solved

---

## 🌍 Open Source & Leadership

- **Open Source Contributor — Kuadrant Operator (CNCF):** Debugged controller reconciliation failures, improved fault tolerance, and submitted PRs with test coverage incorporated through maintainer review
- **Programming Team Member — NIT Agartala Dev & Coders Club, IIIT Agartala GDG:** Led weekly technical sessions and coding contests, driving a 15% growth in CP participation while mentoring juniors in DSA
- **Team Leader — Smart India Hackathon 2025:** Directed cross-functional development and end-to-end technical execution for rapid, high-quality delivery

---

## 📈 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Prachi01Yadav&show_icons=true&theme=radical&include_all_commits=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Prachi01Yadav&theme=radical" width="48%" alt="GitHub Streak" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Prachi01Yadav&layout=compact&theme=radical&langs_count=6" width="48%" alt="Top Languages" />
  <img src="https://github-profile-trophy.vercel.app/?username=Prachi01Yadav&theme=radical&no-frame=true&row=2&column=4&margin-w=10&margin-h=10" width="48%" alt="Trophies" />
</div>

---

<div align="center">
  <i>"Code is like humor. When you have to explain it, it's bad." — Cory House</i>
</div>
