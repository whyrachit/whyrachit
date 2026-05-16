<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Rachit%20Yadav&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20PM%20%C2%B7%20Agentic%20Systems%20%C2%B7%20Product%20%26%20Business%20Analysis&descAlignY=58&descColor=a78bfa" />

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/whyrachit-%230077B5.svg?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/whyrachit/)
[![Portfolio](https://img.shields.io/badge/portfolio-whyrachit.vercel.app-8b5cf6?style=flat-square&logo=vercel&logoColor=white)](https://whyrachit.vercel.app)
[![Profile Views](https://komarev.com/ghpvc/?username=whyrachit&style=flat-square&color=8b5cf6&label=visitors)](https://github.com/whyrachit)

</div>

---

## what i do

AI Product Manager and Business Analyst — I scope, spec, and ship AI-native products. I write PRDs for ML systems, design multi-agent workflows, and translate messy business problems into things that can actually be built and measured.

On the technical side: I build agentic pipelines, orchestrate LLM workflows, and maintain 50+ production-grade prompts across real automation use cases — documentation, data auditing, Excel pipelines.

---

## stack

**product & analysis**

![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white)
![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**data & scripting**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-%2307405e.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

**LLM & agentic**

![Claude](https://img.shields.io/badge/Claude-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Agno](https://img.shields.io/badge/Agno-6d28d9?style=for-the-badge&logoColor=white)
![AutoGen](https://img.shields.io/badge/Microsoft_AutoGen-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

**agentic coding**

![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![Claude Desktop](https://img.shields.io/badge/Claude_Desktop-CC785C?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Antigravity](https://img.shields.io/badge/Google_Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

---

## shipped

### 🎵 SargamAI — [GitHub](https://github.com/whyrachit/SargamAI) · [LinkedIn](https://www.linkedin.com/posts/whyrachit_aiagents-spotify-playlist-ugcPost-7303371882970456065-LBfT)

> mood-aware AI playlist generator for multilingual listeners

- **Problem:** Spotify's recommendation graph is English-first. Multilingual users get generic results.
- **Build:** mood input → live Spotify API query → custom ranking layer → ranked playlist output
- **Prompt layer:** 50+ prompt variants iterated to handle language, mood, and genre variance across 5+ languages
- **Outcome:** 30 active users · 200+ playlists generated · ~35% higher satisfaction vs static baselines

`Python` `Spotify API` `Prompt Engineering` `LLM Orchestration` `Ranking Logic`

---

### 🍹 tanhAI — [GitHub](https://github.com/whyrachit/tanhAI) · [LinkedIn](https://www.linkedin.com/posts/whyrachit_tanhai-swiggy-sarvamai-ugcPost-7459939151652630528-TMZe)

> conversational mixology agent — discover, pair, and order in one session

- **Problem:** Getting a drink delivered requires 3 apps, 3 context switches, 3 drop-off points.
- **Architecture:** single conversational flow with multi-step tool calling via Agno · intent-aware routing across APIs
- **Models:** Sarvam AI 105B for Indian language NLU · Swiggy MCP for real-time inventory + order handoff
- **Outcome:** ~65% reduction in time-to-order · 15+ test sessions · zero handoff failures

`Agno` `Sarvam AI 105B` `Swiggy MCP` `LangGraph` `Multi-Agent` `Tool Calling` `FastAPI`

---

## how I think about AI systems

```
given a new AI feature request:

  ├── is this actually an AI problem?
  │     └── no → solve it simply, ship faster
  │     └── yes ↓
  ├── what data exists / needs to exist?
  │     └── not enough → design collection first, build later
  │     └── enough ↓
  ├── define eval criteria before writing a single prompt
  │     └── what does good output look like? bad output?
  │     └── what's the acceptable failure rate?
  └── instrument everything → measure → iterate
```

---

## agentic workflow experience

```python
# what i've built and maintained in production:

workflows = {
    "documentation_automation": ["Claude Code", "Google Antigravity", "structured prompts"],
    "excel_data_entry_pipelines": ["Python", "OpenPyXL", "LLM extraction", "validation layer"],
    "audit_automation":          ["multi-step agents", "diff detection", "anomaly flagging"],
    "multi_agent_orchestration": ["Agno", "AutoGen", "LangGraph", "intent routing"],
    "mcp_integrations":          ["Swiggy MCP", "Autodesk MCP", "WhatsApp API"],
}

prompt_library_size = "50+ reusable, versioned prompts"
models_used = ["Claude", "GPT-4o", "Gemini", "Sarvam AI 105B"]
```

---

<div align="center">

*building at the intersection of AI systems and product thinking*

**[whyrachit →](https://www.linkedin.com/in/whyrachit/)**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" />

</div>
