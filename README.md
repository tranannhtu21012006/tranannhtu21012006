<h1 align="center">Billy · Tran Anh Tu</h1>

<p align="center">
  Building and operating AI systems, from the API layer to the cluster.<br/>
  IT undergraduate at UEH · Ho Chi Minh City, Vietnam 🇻🇳
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <br/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white" alt="Cisco" />
</p>

<p align="center">
  <a href="https://myportfolio-billy.vercel.app">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/billytran201/">LinkedIn</a> ·
  <a href="mailto:trananhtu21012000@gmail.com">Email</a> ·
  <a href="https://orcid.org/0009-0009-5494-7877">ORCID</a>
</p>

---

## 👋 About me

I'm an IT student passionate about solving practical problems at the intersection of technology, data, and security. I'm most curious about the unglamorous side of AI: keeping it **reliable, secure, and affordable to operate**.

I use AI every day to move faster and understand problems better. My goal is to grow into an engineer who can **both build and operate AI well**.

- 🎓 B.Sc. Information Technology at **UEH**, GPA **3.39 / 4.0**, Academic Encouragement Scholarship
- 🔭 Interested in **DevOps, backend engineering, and AI operations**
- 🔎 Currently looking for an **internship** (DevOps / AI Ops / Software Engineering)

---

## 🚀 Featured project: SecureAI Gateway

> A secure gateway that sits between your apps and LLM providers, so API keys, cost, and abuse are managed in one place.

```mermaid
flowchart LR
    A[Client app] --> B[Gateway API<br/>FastAPI]
    B --> C{Auth & limits<br/>JWT · RBAC · Rate limit}
    C --> D[Prompt Guard]
    D --> E[(Redis cache)]
    E --> F[OpenAI]
    E --> G[Gemini]
    E --> H[Ollama]
    B -.-> I[(PostgreSQL<br/>keys · usage logs)]
```

<sub>Simplified request flow.</sub>

**Highlights**

- One **OpenAI-compatible** endpoint (`/v1/chat/completions`) that routes to OpenAI, Gemini, or local Ollama, with real-time **SSE streaming**
- Gateway-owned API keys (hashed in PostgreSQL) plus **JWT** and **role-based access control**, so provider keys never reach clients
- Per-key **rate limiting** with a Redis Token Bucket and **response caching** to cut cost and latency
- **Prompt Guard** that rejects malicious prompts with HTTP 400
- Per-request logging of model, provider, tokens, latency, and cost, exposed through usage-summary APIs
- Deployable with **Docker Compose** locally or **Helm on k3d** (NGINX ingress) using a single bash script

🔗 [View the repository](https://github.com/tranannhtu21012006/SecureAI-Gateway)

---

## 🧩 Other projects

**🌐 [Personal portfolio](https://github.com/tranannhtu21012006/myportfolio)** · Next.js + TypeScript site with content managed in Sanity CMS, deployed on Vercel. [Live site](https://myportfolio-billy.vercel.app)

**🏫 UEH Campus N network design** · Designed a full campus network (servers, security, VLANs, wireless, CCTV) and configured routers, an ASA firewall, and core switches on Cisco IOS with inter-VLAN routing, plus Web, FTP, and Email servers. [![Google Drive](https://img.shields.io/badge/Google_Drive-Project_files-4285F4?style=flat-square&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1-l67kW7jyiOoOKJqzEUp0QM-4T0r0kBM/view?usp=drive_link)

---

## 🌱 Right now

| | |
| --- | --- |
| **Building** | SecureAI Gateway (more providers, stronger guardrails, analytics) |
| **Learning** | Kubernetes, and monitoring AI workloads with Prometheus and Grafana |
| **Looking for** | An internship where I can learn from experienced engineers and ship real projects |

---

## 📫 Let's connect

I'm happy to chat about backend systems, LLM infrastructure, DevOps, or internship opportunities.

<p>
  <a href="https://www.linkedin.com/in/billytran201/"><img src="https://img.shields.io/badge/LinkedIn-billytran201-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:trananhtu21012000@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://myportfolio-billy.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Visit-16A34A?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" /></a>
</p>
