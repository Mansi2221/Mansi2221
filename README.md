![Mansi Patil - Forward Deployed Engineer](assets/profile-banner.png)

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

## What I've Built

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

**GenAI Product Development**  
Taking AI from research to production. LLM integration, RAG pipelines, multi-model orchestration. Building the infrastructure that makes AI reliable and scalable.

**Customer Deployment & Integration**  
Understanding how your AI system fits into customer workflows. Handling integration challenges. Making sure it works at their scale and in their environment.

**Full-Stack Architecture**  
From understanding requirements to deploying infrastructure. Frontend, API design, database optimization, monitoring—I own the end-to-end experience.

**Production Reliability**  
Systems that work at 3am. Proper logging, monitoring, alert handling. Building for operational reality, not just technical correctness.

---

## Tech Stack

**Languages:** TypeScript · Python · JavaScript · SQL

**Frontend:** Next.js 14 · React · Expo · Tailwind

**AI/ML:** Claude API · OpenAI · LangChain · HuggingFace · Vector DBs · RAG

**Backend:** Node.js · Supabase · PostgreSQL · Python

**DevOps & Deployment:** Docker · GitHub Actions · Vercel · AWS/Cloud

---

## What I'm Looking For

Forward deployed roles where I can work directly with customers. Building real solutions to real problems. The kind of work where you ship to production every week and talk to customers about how it's actually working.

Strong interest in: AI product deployment · Startup customer integration · Building customer-facing systems · Real-time problem solving on site

---

**Let's ship something with your customers.**

📧 [mansianilpatil2425@gmail.com](mailto:mansianilpatil2425@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/mansipatil22)  
🔗 [GitHub](https://github.com/Mansi2221)
