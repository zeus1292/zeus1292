
<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════════
     T H E   B U I L D E R ' S   N O T E B O O K
     ═══════════════════════════════════════════════════════════════════════════ -->

```
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║                                                                            ║
  ║     █████╗ ██╗  ██╗███████╗██╗  ██╗ █████╗ ██╗   ██╗                       ║
  ║    ██╔══██╗██║ ██╔╝██╔════╝██║  ██║██╔══██╗╚██╗ ██╔╝                       ║
  ║    ███████║█████╔╝ ███████╗███████║███████║ ╚████╔╝                        ║
  ║    ██╔══██║██╔═██╗ ╚════██║██╔══██║██╔══██║  ╚██╔╝                         ║
  ║    ██║  ██║██║  ██╗███████║██║  ██║██║  ██║   ██║                          ║
  ║    ╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝                          ║
  ║                                                                            ║
  ║              AI Product Manager  ·  Builder  ·  Polymath                   ║
  ║                                                                            ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
```

<br>

<a href="https://akshay-io.vercel.app"><img src="https://img.shields.io/badge/🌐_Portfolio-akshay--io.vercel.app-1a1e24?style=for-the-badge&labelColor=0d1117" alt="Portfolio"/></a>&nbsp;
<a href="https://linkedin.com/in/akshaykumar-92"><img src="https://img.shields.io/badge/LinkedIn-akshaykumar--92-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn"/></a>&nbsp;
<a href="mailto:"><img src="https://img.shields.io/badge/Open_to-Opportunities-2ea44f?style=for-the-badge&labelColor=0d1117" alt="Open to Opportunities"/></a>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

## `> whoami`

```yaml
name:       Akshay Kumar
location:   San Francisco Bay Area, CA
education:  M.S. Business Analytics — Columbia University
focus:      Turning complex AI into products people actually use
experience: 10+ years shipping AI products at S&P Global, C3 AI, Capital One & beyond
philosophy: "The best AI products disappear into the workflow."
```

I'm a **Senior AI Product Manager** who doesn't just write PRDs — I build the prototypes, architect the pipelines, and ship the product. My career has been a journey through the intersection of **enterprise AI**, **financial data**, and **product craft**, from launching RAG-powered search at S&P Global to building multi-agent systems from scratch.

I believe the next wave of AI products won't come from bigger models — they'll come from **better product thinking applied to AI capabilities**.

<br>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         T H E   P O R T F O L I O                         │
│                                                                             │
│          "I have been impressed with the urgency of doing.                  │
│           Knowing is not enough; we must apply."  — Da Vinci               │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

### 🔬 `InvestorLens` — Persona-Driven Company Intelligence

> *What if the same search query returned fundamentally different results based on who you are?*

A knowledge graph-powered company intelligence engine for the Enterprise AI & Data Infrastructure sector. A Value Investor, PE Firm, Growth VC, Strategic Acquirer, and Enterprise Buyer all get tailored, persona-specific results from the same query — powered by **Neo4j knowledge graphs** and **multi-agent orchestration**.

<table>
<tr>
<td>

**Stack:** `LangGraph` · `Neo4j` · `FastAPI` · `GPT-4o` · `React` · `LangSmith` · `SEC EDGAR API`

**What it demonstrates:**
- Graph-based reasoning over structured financial data
- Multi-persona agent architecture
- Real-time SEC filing ingestion

</td>
<td width="200" align="center">

```
    ┌──────┐
    │ User │
    └──┬───┘
       │ query
  ┌────▼────┐
  │ Persona │
  │ Router  │
  └────┬────┘
       │
  ┌────▼────┐
  │ Neo4j   │
  │ Graph   │──── Tailored
  └────┬────┘     Insights
       │
  ┌────▼────┐
  │ LLM     │
  │ Synth   │
  └─────────┘
```

</td>
</tr>
</table>

<br>

---

### 🛒 `Retail Right` — Multi-Agent Product Matching

> *Text, URL, or image — find the best price, every time.*

A multi-modal product matching system that accepts **any input format** and intelligently compares prices across retailers. Started at 30-second response times, optimized to **under 4 seconds** by replacing GPT-4 Vision with **CLIP embeddings** and hybrid vector search.

<table>
<tr>
<td width="200" align="center">

```
  📝 Text ─┐
  🔗 URL  ─┼─► CLIP ─► Vector
  📷 Image ─┘    ▼       Search
              Hybrid  ─► Ranked
              Match      Results
                │
           ⚡ 30s → 4s
```

</td>
<td>

**Stack:** `LangGraph` · `CLIP` · `FastAPI` · `ChromaDB` · `OpenAI` · `Tavily` · `LangSmith`

**What it demonstrates:**
- Multi-modal input processing (text/URL/image)
- 87% latency reduction through embedding optimization
- Agentic price comparison across live marketplaces

</td>
</tr>
</table>

<br>

---

### 📊 `Price Compare` — Multimodal Smart Shopping

> *Point your camera at any product. Get the best deal instantly.*

A consumer-facing price comparison app with multimodal inputs — snap a photo, paste a link, or type a query. Built with a focus on **real-time performance** and **practical AI** that saves people money.

**Stack:** `Python` · `CLIP Embeddings` · `Vector Search` · `FastAPI`

<br>

---

### 📡 `Research Lens` — AI Research Aggregator

> *Your personal radar for what matters in AI.*

An AI-powered research aggregator that scans **arXiv** and **TechCrunch**, synthesizes content, and surfaces the papers and startup news most relevant to your interests.

**Stack:** `Python` · `LangChain` · `OpenAI` · `arXiv API` · `Web Scraping`

<br>

---

### 📈 `Reddit Sentiment × BTC` — Social Signal Analysis

> *Can Reddit predict Bitcoin? Let's find out.*

Sentiment analysis pipeline on Reddit comments to identify correlations with BTC price movements. An exploration in **alternative data signals** for financial markets.

**Stack:** `Python` · `NLP` · `Sentiment Analysis` · `Data Visualization`

<br>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    T H E   T O O L K I T                                  │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

<div align="center">

#### 🧠 AI / ML
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Pipelines-FF6F00?style=flat-square&logoColor=white)
![CrewAI](https://img.shields.io/badge/crewAI-000000?style=flat-square&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![CLIP](https://img.shields.io/badge/CLIP-412991?style=flat-square&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-FF6F00?style=flat-square)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-FF6F00?style=flat-square)

#### ⚙️ Infrastructure
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![REST APIs](https://img.shields.io/badge/REST_APIs-009688?style=flat-square)

#### 📊 Data & Analytics
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

#### 🎨 Product & Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

</div>

<br>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                 W H A T   I   B E L I E V E                               │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

<table>
<tr>
<td width="50%" valign="top">

#### 🏗️ On Building AI Products
*The gap between a demo and a product is where most AI fails. I live in that gap.* Building with LangGraph, RAG, and multi-agent patterns isn't just about the tech — it's about understanding **what makes a user's life better** and engineering backwards from there.

</td>
<td width="50%" valign="top">

#### 🔭 On What's Next
*We're in the "electricity moment" of AI.* The winners won't be those with the best models — they'll be those who build the best **workflows, evaluations, and feedback loops** around them. I'm focused on agent evaluation frameworks and human-in-the-loop orchestration.

</td>
</tr>
</table>

<br>

<!-- ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                  L E T ' S   C O N N E C T                                │
│                                                                             │
│    I'm always up for conversations about AI products, agentic systems,     │
│    or the future of human-AI collaboration.                                │
│                                                                             │
│    🌐 akshay-io.vercel.app  ·  💼 linkedin.com/in/akshaykumar-92          │
└─────────────────────────────────────────────────────────────────────────────┘
```

</div>

<br>

<div align="center">
<i>"Simplicity is the ultimate sophistication." — Leonardo da Vinci</i>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:1a1e24&height=120&section=footer" width="100%"/>

</div>
