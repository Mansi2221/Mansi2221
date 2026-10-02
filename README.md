![Mansi Patil - Forward Deployed Engineer](assets/profile-banner.png)

---

## What I Do

I build production-grade GenAI systems. LLM integration, RAG pipelines, full-stack development—I handle the entire stack from concept to deployed product that actually works at scale.

---

## Current Work

**Travelmind** — AI Travel Intelligence Agent  
Real-time travel briefings powered by LLMs. Parallel API orchestration with structured output.

```typescript
// Real-time web search with structured results
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
Forecasting system that predicts demand patterns and optimizes inventory levels. Real-time analytics pipeline.

```python
# Demand forecasting with multiple time-series models
def forecast_demand(historical_data, external_factors):
    # ARIMA for trend analysis
    arima_forecast = arima_model.predict(historical_data)
    
    # ML model for external factor influence
    ml_forecast = gradient_boosting.predict(external_factors)
    
    # Ensemble approach for accuracy
    return weighted_average([arima_forecast, ml_forecast])
```

[View Full Projects](https://github.com/Mansi2221?tab=repositories)

---

## Technical Expertise

**AI & LLMs**  
Multi-model orchestration, RAG systems, semantic search, prompt optimization, cost-efficient inference

**Backend & Infrastructure**  
Node.js, Python, PostgreSQL, Supabase, Docker, GitHub Actions, production deployments

**Frontend**  
Next.js, React, Expo (mobile), TypeScript, real-time UI updates

**What matters to me:** Building systems that don't fall apart at 3am. Proper logging. Monitoring. The unglamorous stuff that makes the difference between "it works" and "it works reliably."

---

## Stack

**Languages:** TypeScript · Python · JavaScript · SQL

**Frontend:** Next.js 14 · React · Expo · Tailwind

**AI/ML:** Claude API · OpenAI · LangChain · HuggingFace · Vector DBs

**Backend:** Node.js · Supabase · PostgreSQL · Python

**DevOps:** Docker · GitHub Actions · Vercel

---

## Available For

Contract work on GenAI projects · Full-time roles building AI products · Technical partnerships

Interested in: Production AI systems · Startup scaling · System architecture · Real-world AI challenges

---

**Let's build something that matters.**

📧 mansi@example.com  
💼 [LinkedIn](https://linkedin.com)  
🔗 [My GitHub](https://github.com/Mansi2221)
