<!-- ============ ANIMATED HERO ============ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:36D1DC,45:5B86E5,100:9D50BB&height=230&section=header&text=Mansi%20Patil&fontSize=58&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Forward%20Deployed%20Engineer%20%E2%80%A2%20Building%20AI%20systems%20that%20actually%20work%20in%20production&descSize=18&descAlignY=54" width="100%" alt="Mansi Patil — Forward Deployed Engineer" />
</p>

<!-- ============ ANIMATED TAGLINE ============ -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=5B86E5&center=true&vCenter=true&width=760&lines=GenAI+%7C+Full-Stack+%7C+Deployment;I+ship+production+AI+systems+with+customers;Understand+the+problem+%E2%86%92+ship+fast+%E2%86%92+make+it+reliable;Full-stack%3A+API%2C+infra%2C+frontend%2C+the+glue+in+between" alt="typing" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🚀%20Open%20to-Forward%20Deployed%20Engineer%20roles-5B86E5?style=for-the-badge" alt="open to roles" />
</p>

<p align="center">
  <a href="mailto:mansianilpatil2425@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/mansipatil22"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Mansi2221"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=Mansi2221&label=Profile%20views&color=38BDAE&style=for-the-badge" />
</p>

---

## Forward Deployed Engineer

I work directly on the front lines—shipping production AI systems with customers, understanding their problems deeply, and building solutions that actually work in their environment.

---

## How I Work

**Understand First**
I spend time understanding the real problem—not just the technical requirements. What's actually blocking your customer? What does success look like? This shapes everything.

**Ship Fast**
Full-stack capability means I can move quickly. API design, infrastructure, frontend—I own the whole stack so nothing becomes a blocker. From problem to deployed solution in weeks, not months.

**Customer Focused**
Working directly with your customers. Understanding their workflows. Making sure the system works *for them*, not just in theory. That's where the real problems surface.

---

## 📌 Featured on GitHub

The forward-deployed loop in three projects: **scope the problem → retrieve & reason over real data → ship a governed production system.**

| Project | What it is | Stack |
|---|---|---|
| 🏥 **[Eligible](https://github.com/Mansi2221/eligible)** | Patient-to-trial matching on harmonized clinical data — OMOP harmonization, agentic eligibility matching, PHI redaction, tamper-evident audit chain, FHIR output, and a human-in-the-loop review UI. Built end to end. | Python · LangGraph · dbt · FastAPI · Next.js |
| 📋 **[Clarify](https://github.com/Mansi2221/clarify)** | AI Business Analyst agent — brief in, a full BA pack out (requirements, RTM, test cases, RACI register). It asks clarifying questions instead of inventing details. | Next.js 16 · React 19 · TS · Vercel AI SDK |
| 🔎 **[Talent-RAG](https://github.com/Mansi2221/talent-rag)** | Production-grade RAG for talent intelligence — hybrid retrieval, cross-encoder reranking, ensemble generation with a judge, async job-based indexing, and an evaluation suite. | Python · FastAPI · FAISS · Streamlit · Docker |

---

## What Else I've Built

**Travelmind** — Real-time AI Travel Agent
Deployed with travel teams to generate structured briefings in seconds. Multi-model orchestration with parallel API calls, built to handle real-world latency requirements.

```typescript
// Customer-facing reliability: parallel search → structured output in <10s
const travelAgent = async (destination: string) => {
  const searches = await Promise.all([
    tavily.search(`${destination} weather forecast`),
    tavily.search(`${destination} local events`),
    tavily.search(`${destination} transportation options`),
    tavily.search(`${destination} accommodation deals`),
    tavily.search(`${destination} cultural tips`),
  ]);

  return await claude.generateBriefing(searches);
};
```

**Demand Sensing & Inventory Optimization**
Built for real supply chain operations. Forecasting engine that improves with actual business data. Works with messy real-world data, not clean datasets. Deployed to handle production demand patterns.

```python
# Production forecasting with ensemble methods
def forecast_demand(historical_data, external_factors):
    # ARIMA for trend + seasonality
    arima_forecast = arima_model.predict(historical_data)

    # Gradient boosting for feature interactions
    ml_forecast = gradient_boosting.predict(external_factors)

    # Ensemble: better than any single model
    return weighted_average([arima_forecast, ml_forecast])
```

---

## I Can Help With

**GenAI Product Development** — Taking AI from research to production. LLM integration, RAG pipelines, multi-model orchestration. Building the infrastructure that makes AI reliable and scalable.

**Customer Deployment & Integration** — Understanding how your AI system fits into customer workflows. Handling integration challenges. Making sure it works at their scale and in their environment.

**Full-Stack Architecture** — From understanding requirements to deploying infrastructure. Frontend, API design, database optimization, monitoring—I own the end-to-end experience.

**Production Reliability** — Systems that work at 3am. Proper logging, monitoring, alert handling. Building for operational reality, not just technical correctness.

---

## 🛠️ Tech Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

---

## 📊 GitHub Activity

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=Mansi2221&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mansi2221&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top langs" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Mansi2221&theme=tokyonight&hide_border=true" alt="streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mansi2221&theme=tokyo-night&hide_border=true&area=true&bg_color=0D1117&color=5B86E5&line=9D50BB&point=36D1DC" alt="activity graph" width="95%" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Mansi2221&theme=algolia&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="trophies" />
</p>

---

## What I'm Looking For

Forward deployed roles where I can work directly with customers. Building real solutions to real problems. The kind of work where you ship to production every week and talk to customers about how it's actually working.

Strong interest in: **AI product deployment · Startup customer integration · Building customer-facing systems · Real-time problem solving on site**

---

**Let's ship something with your customers.**

📧 [mansianilpatil2425@gmail.com](mailto:mansianilpatil2425@gmail.com)  &nbsp;·&nbsp;  💼 [LinkedIn](https://www.linkedin.com/in/mansipatil22)  &nbsp;·&nbsp;  🔗 [GitHub](https://github.com/Mansi2221)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" width="100%" />
