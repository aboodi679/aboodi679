<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0524,50:2d1b4e,100:4c1d95&height=220&section=header&text=Muhammad%20Abdullah&fontSize=48&fontColor=e9d5ff&animation=fadeIn&fontAlignY=38&desc=Cloud%20%26%20DevOps%20Engineer%20%7C%20AWS%20%7C%20Terraform%20%7C%20CI%2FCD&descAlignY=55&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=650&lines=Building+production-grade+AWS+infrastructure;Terraform+%7C+ECS+Fargate+%7C+CI%2FCD+with+OIDC;Software+Engineering+Graduate+%2C+2026;Targeting+Cloud%2FDevOps+roles+%E2%80%94+Europe+%26+Pakistan" alt="Typing SVG" />
</a>

<br/>

![Degree](https://img.shields.io/badge/BS_Software_Engineering-University_of_Lahore-4c1d95?style=flat-square&logo=googlescholar&logoColor=e9d5ff)
![GPA](https://img.shields.io/badge/GPA-3.47%2F4.00-6d28d9?style=flat-square)
![Location](https://img.shields.io/badge/Sargodha,_Pakistan-📍-3730a3?style=flat-square)

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-8b5cf6?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/aboodi679)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-6d28d9?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammadabdullah-b887272a5)
[![Email](https://img.shields.io/badge/Email-4c1d95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aaboodi679@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-1e1b4b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aboodi679)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=aboodi679&style=flat-square&color=8b5cf6&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/aboodi679?style=flat-square&color=6d28d9&label=Followers)
![Stars](https://img.shields.io/github/stars/aboodi679?style=flat-square&color=4c1d95&label=Stars)

</div>

<br/>

## 🟣 About Me

I'm a Software Engineering graduate who learns by shipping real, production-shaped infrastructure rather than tutorials. Over the past few months I designed and deployed two multi-service AWS platforms from a blank Terraform state, wiring together event-driven pipelines, containerized services, and zero-downtime CI/CD — the same patterns used in real production environments.

My core focus is **cloud infrastructure and DevOps engineering**: Infrastructure as Code, container orchestration, observability, and secure automated delivery. I also carry a foundation in **applied NLP** (fine-tuning transformer models on legal text classification) and full-stack basics from earlier academic projects, but infrastructure is where I go deep.

```yaml
role: Cloud / DevOps Engineer (Early Career)
focus: [AWS, Terraform, ECS Fargate, CI/CD, Observability]
mindset: "Automate it, monitor it, document why you built it that way"
```

**🎯 Open To:**
- Cloud Support / Cloud Engineer roles (AWS-focused)
- DevOps Engineer / Platform Engineer positions
- Opportunities in **Pakistan**, **Ireland**, **Germany**, and the **Netherlands**
- Long-term goal: **Solutions Architect**

<br/>

## 🟣 Tech Stack

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=python,java,cpp,bash,linux" />

**Backend & Databases**
<br/>
<img src="https://skillicons.dev/icons?i=flask,fastapi,postgres,dynamodb,redis" />

**Cloud, DevOps & Tooling**
<br/>
<img src="https://skillicons.dev/icons?i=aws,terraform,docker,githubactions,git,githubactions,vscode" />

</div>

<br/>

## 🟣 AI / ML Exposure

<div align="center">

| Domain | Proficiency | Details |
|---|---|---|
| NLP / Transformers | ●●●○○ | Fine-tuned Legal-BERT on LEDGAR & Supreme Court datasets for legal text classification, ~84–88% accuracy |
| LLM-Assisted Engineering | ●●●●○ | Used Claude (Amazon Bedrock & Claude Code) as an active pair-engineer across infrastructure builds |

</div>

<br/>

## 🟣 Featured Projects

<details open>
<summary><b>🔹 StatusNest — Multi-Tenant AWS Status Page & Monitoring Platform</b></summary>
<br/>

A production-grade, multi-tenant SaaS status page platform built end-to-end on AWS with full event-driven monitoring and zero manual infrastructure steps.

| Category | Detail |
|---|---|
| **Stack** | ECS Fargate, RDS PostgreSQL, ElastiCache Redis, Lambda + SQS, CloudFront + WAF, Terraform, GitHub Actions (OIDC) |
| **Scale** | Multi-tenant architecture, 3 containerized FastAPI microservices |
| **Performance** | Incident detection reduced to under 60 seconds via EventBridge → Lambda → SQS pipeline |
| **Security** | OIDC-based CI/CD (zero long-lived AWS credentials), WAF-protected CloudFront edge |
| **Impact** | 100% Terraform-driven IaC, 8 documented Architecture Decision Records, ~$94/month operating cost |
| **Repository** | [StatusNest-SAD-Documentation](https://github.com/aboodi679) |

Built across a series of focused sessions covering VPC/networking, ECS task orchestration, an SSM bastion for private RDS access, X-Ray instrumentation, and an SQS-driven Lambda processor — with every infrastructure decision documented rather than left implicit.

</details>

<details>
<summary><b>🔹 OrderFlow — Event-Driven Microservices Platform on AWS</b></summary>
<br/>

An event-driven microservices platform designed to close specific resume gaps: container orchestration, real CI/CD, and production observability.

| Category | Detail |
|---|---|
| **Stack** | 3 Flask microservices on ECS Fargate, ALB path-based routing, EventBridge + SQS + SNS, CloudWatch, X-Ray, Terraform |
| **Scale** | 3 independently deployable services behind a single ALB |
| **Performance** | Deployment time cut by 80% (15+ min manual → under 3 min) |
| **Security** | GitHub Actions CI/CD via OIDC — no static AWS credentials in the pipeline |
| **Impact** | 100% infrastructure reproducibility via modular Terraform state |
| **Repository** | [OrderFlow](https://github.com/aboodi679) |

</details>

<details>
<summary><b>🔹 AI Hitman — Cloud-Integrated Game Backend (Final Year Project)</b></summary>
<br/>

A Unity game's cloud backend, built and operated solo while a partner handled game logic — covering serverless deployment end-to-end.

| Category | Detail |
|---|---|
| **Stack** | Flask REST API deployed serverlessly via Zappa, AWS Lambda, DynamoDB, S3, API Gateway, Terraform + boto3 |
| **Scale** | 4 live API Gateway endpoints backing real-time game clients |
| **Performance** | Serverless, auto-scaling backend with no server management |
| **Security** | IAM least-privilege roles provisioned entirely via IaC |
| **Impact** | Scored 90/100 with Top 8 Runner-Up recognition at university exhibition |
| **Repository** | [ai-hitman-backend](https://github.com/aboodi679/ai-hitman-backend) |

</details>

<br/>

## 🟣 Experience

**DevOps Track — Independent Project-Based Training**
`Self-Directed` | 2025 – 2026

Completed a structured internship-style assessment covering the full DevOps toolchain, applied against a real multi-service codebase rather than isolated exercises.

- Containerized services with Docker and orchestrated deployment with HashiCorp Nomad
- Built GitHub Actions CI/CD pipelines from scratch, including automated testing gates
- Implemented centralized logging with Grafana Loki
- Practiced Git workflows (branching, PR review, conflict resolution) under production-like constraints

`Docker` `GitHub Actions` `Nomad` `Grafana Loki` `Git`

<br/>

## 🟣 Achievements

<div align="center">

| Recognition | Details |
|---|---|
| 🏆 Top 8 Runner-Up | AI Hitman FYP scored 90/100 at university exhibition |
| 🎓 Class Representative | Elected liaison for 60+ students across 4 academic years |
| 📊 GPA 3.47/4.00 | BS Software Engineering, University of Lahore |
| 🧾 8 ADRs Documented | StatusNest — full architectural decision trail across a production build |

</div>

<br/>

## 🟣 Certifications

**Anthropic**

![Claude Bedrock](https://img.shields.io/badge/Claude_with_Amazon_Bedrock_%26_Claude_Code_in_Action-Jun_2026-4c1d95?style=flat-square&logo=anthropic&logoColor=white)

**Amazon Web Services**

![AWS Forage](https://img.shields.io/badge/AWS_Solutions_Architecture_Job_Simulation-Forage_2025-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![AWS Educate](https://img.shields.io/badge/Introduction_to_Cloud_101-AWS_Educate_2025-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

**Project Management**

![Agile HP LIFE](https://img.shields.io/badge/Agile_Project_Management-HP_LIFE_2025-6d28d9?style=flat-square&logo=hp&logoColor=white)

<br/>

## 🟣 GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=aboodi679&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=8b5cf6&text_color=c4b5fd" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=aboodi679&theme=radical&hide_border=true&background=0d1117&ring=8b5cf6&fire=a78bfa&currStreakLabel=c4b5fd" width="48%" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aboodi679&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c4b5fd" width="55%" />

</div>

<br/>

## 🟣 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=aboodi679&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" />

</div>

<br/>

## 🟣 Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=aboodi679&theme=react-dark&bg_color=0d1117&color=a78bfa&line=8b5cf6&point=e9d5ff&hide_border=true" width="100%" />

</div>

<br/>

## 🟣 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/aboodi679/aboodi679/output/github-contribution-grid-snake-dark.svg" width="100%" />

</div>

<br/>

## 🟣 Current Focus

```yaml
learning:
  - Advanced Terraform module design & remote state strategies
  - AWS Solutions Architect–level networking & security patterns

building:
  - Packaging StatusNest into a polished, recruiter-facing case study

exploring:
  - EU cloud/DevOps job market (Ireland, Germany, Netherlands)
  - AWS Graduate Cloud Support & early-career Solutions Architect tracks

open_to:
  - Cloud Engineer / DevOps Engineer roles
  - Relocation to Europe or remote-first teams
```

<br/>

## 🟣 Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/aaboodi679@gmail.com-4c1d95?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aaboodi679@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Muhammad_Abdullah-6d28d9?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammadabdullah-b887272a5)
[![GitHub](https://img.shields.io/badge/aboodi679-1e1b4b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aboodi679)

</div>

<br/>

<div align="center">

*"Infrastructure that isn't documented is infrastructure you don't actually understand."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4c1d95,50:2d1b4e,100:0f0524&height=120&section=footer" width="100%"/>

</div>
