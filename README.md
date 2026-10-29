<div align="center">

```
 _       ____  ____  __   ____  ___   ________  ____________
| |     / / / / /\ \/ /  / __ \/   | / ____/ / / /  _/_  __/
| | /| / / /_/ /  \  /  / /_/ / /| |/ /   / /_/ // /  / /   
| |/ |/ / __  /   / /  / _, _/ ___ / /___/ __  // /  / /    
|__/|__/_/ /_/   /_/  /_/ |_/_/  |_\____/_/ /_/___/ /_/     
```

### 🚦 The crossing at [whyrachit.in](https://whyrachit.in)
*Tap anything. Some of it talks back.*

<br>

<!-- REVOLVING ASCII SIGNAL & 360° GLOBE HERO -->
<p align="center">
  <a href="https://whyrachit.in">
    <img src="assets/revolving-signal-globe.svg" alt="whyrachit.in - 3D Kolkata Crossing & Revolving ASCII Globe" width="860">
  </a>
</p>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=3600&pause=1200&color=8B5CF6&center=true&vCenter=true&multiline=true&repeat=true&width=820&height=70&lines=AI+Product+Manager+%E2%80%A2+Founder's+Office+%40+hoichoi;%22I+get+agents+to+do+the+grunt+work+so+I+can+take+credit.%22;A+statistician+who+got+distracted+by+AI+%2B+a+habit+of+building+for+5+friends.;Colour+lives+at+the+crossing.+Everything+after+is+paper+and+ink.)](https://whyrachit.in)

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-whyrachit.in-7c3aed?style=for-the-badge&logo=safari&logoColor=white)](https://whyrachit.in)&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-whyrachit-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/whyrachit)&nbsp;
[![X / Twitter](https://img.shields.io/badge/X-@waitedforagi-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/waitedforagi)&nbsp;
[![Email](https://img.shields.io/badge/Email-whyrachit@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:whyrachit@gmail.com)&nbsp;
[![Resume](https://img.shields.io/badge/Resume-PDF-4F46E5?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1EyaapxXUmE5pg--U9NEP9eaPqoeRopPS/view?usp=sharing)

</div>

---

### 🐕 Shiro's TL;DR

> *"A small white dog from Kasukabe who took a job in Kolkata after one forgotten dinner too many. Host of the crossing, runs the inbox. Poke him four times quickly and he gets dizzy."*

```
┌─────────────────────────────────────────────────────────────────────────────┐
│  NAME         : Rachit Yadav (@whyrachit)                                   │
│  ROLE         : AI Product Manager · Founder's Office @ hoichoi             │
│  BASED IN     : Kolkata, India (22.5726° N, 88.3639° E)                     │
│  BACKGROUND   : B.Sc. Statistics (Hons.) · St. Xavier's College             │
│  THE HABIT    : Watch what people actually do, especially what they quietly │
│                 choose not to — and hand the slow repetitive hours to AI.   │
│  THE CARDINAL : Let the agent do the grunt work, keep people for judgment,  │
│  RULE           and make the result feel like it was always this simple.    │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 📐 THE DESIGN MANIFESTO & PHILOSOPHY
*(From the Colophon & System Architecture of [whyrachit.in](https://whyrachit.in/about#colophon))*

```
                 ┌──────────────────────────────────────────────┐
                 │          THE CROSSING PHILOSOPHY             │
                 └──────────────────────┬───────────────────────┘
                                        │
         ┌──────────────────────────────┼──────────────────────────────┐
         ▼                              ▼                              ▼
  [ TYPE OVER IMAGES ]       [ BLACK & WHITE ON PURPOSE ]     [ 30s THEN THE LONG READ ]
   No stock photography.      Colour lives only at the         Every project opens with
   Figures drawn live in      crossing (signal). Everything    a fast TL;DR. The deep
   ASCII characters & type.   after is paper and ink.          architectural spec underneath.
```

1. **Type over images**: There are no stock photographs. Every figure is drawn in characters, live: small 3D scenes set in type, turning as you read, and diagrams that decode from noise.
2. **Black and white, on purpose**: Colour lives at the crossing, in the 3D street signal on the home page. Everything after it is paper and ink, so the work is the only thing asking for attention.
3. **Thirty seconds, then the long read**: Every file opens with a TL;DR for people in a hurry. The full case study sits underneath for people who read.
4. **A grid and three voices**: Twelve columns and a lot of air. Precision in names, data in mono, warmth in serif.
5. **Aesthetics as a product requirement**: Aesthetics are part of the core specification, not cosmetic polish slapped on at the end.

---

## 🧩 HOW I SCOPE AI FEATURES

```
REQUEST
  │
  ├─ Is this actually an AI problem?
  │       └─ no  → solve simply. ship faster.
  │       └─ yes ↓
  │
  ├─ What does good output look like — exactly?
  │       └─ define eval criteria & edge-case thresholds before touching a prompt
  │
  ├─ What's the acceptable failure mode?
  │       └─ instrument fallback routes before it ever hits production
  │
  └─ Build · Instrument · Measure · Iterate

// Most AI products fail not because the underlying LLM is bad,
// but because success was never mathematically defined before building started.
```

---

## 🚀 PRODUCTS & LATE-NIGHT EXPERIMENTS

> *Honestly, I usually build these for like 5 of my friends thinking "surely nobody else will ever need this," only to realize way more people actually end up needing them.*

<table>
<tr>
<td width="50%" valign="top">

### 💊 [mydawAI](https://whyrachit.in/projects/mydawai) `Open Beta`
**Health & Agentic System** &nbsp;·&nbsp; *Kept by **chintu the koala** 🐨*  
*(Sleeps 20 hours a day and still never forgets a dose)*

Medicine reminders for the whole family on the WhatsApp they already have. One button: **Taken**.
- **No new apps**: Turns prescription photos or voice notes into schedules and asks about any ambiguous line.
- **Zero-Snooze UX**: A snooze turns a reminder into an endless negotiation. Here, there's only *Taken*.
- **Caretaker Escalation**: Checks in on missed doses and alerts caretakers only if it remains unanswered.
- **Privacy-first**: End-to-end encryption for prescriptions, schedules, and clinical notes.

`WhatsApp Native` · `Zero-Snooze UX` · `Family Refills`

</td>
<td width="50%" valign="top">

### 🍹 [tanhAI](https://whyrachit.in/projects/tanhai) `Active`
**Food & Mixology Agent** &nbsp;·&nbsp; *Kept by **Jaggu the monkey** 🐒*  
*(Speaks 11+ languages, most of them about bananas)*

Conversational food & craving agent that figures out what you *actually* want and turns saved reels into real orders.
- **Collapsed 3-app switching**: (discover on Instagram → check inventory → order on delivery app) unified into one fluid session.
- **NLU + MCP Stack**: **Sarvam AI 30B / 105B** for Indic language understanding + **Swiggy MCP** for real-time inventory, cart building, and checkout handoff across Food, Instamart & Dineout.

`Sarvam AI 105B` · `Swiggy MCP` · `~65% ↓ time-to-order`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ [sunAI](https://whyrachit.in/projects/sunai) `Shipped`
**Voice & Productivity Engine** &nbsp;·&nbsp; *Kept by **Hoot the owl** 🦉*  
*(Up all night listening. Repeats code correctly pronounced)*

Text-to-speech localization engine automating regional voiceovers while keeping technical code jargon intact.
- **Phonetic Preservation Dictionary**: Prevents TTS models from butchering technical tokens like `async/await`, `SQL`, `FastAPI`, or `REST API` when translating into Indic tongues.
- **Automated Pipeline**: Python & FastAPI around Sarvam's speech models for seamless developer documentation dubbing.

`Voice AI` · `Indic Speech` · `Phonetic Dictionary`

</td>
<td width="50%" valign="top">

### 🎧 [rihAI](https://whyrachit.in/projects/rihai) `Shipped`
**Music & Agentic Curation** &nbsp;·&nbsp; *Kept by **Lofi the cat** 🐱*  
*(Moody by default. Has a playlist for every one of them)*

Mood-driven music curator: write how your day felt, get a Spotify playlist in ~3 seconds.
- **Trilingual Sentiment Parsing**: Reads emotional nuance across Bengali, Hindi, and English.
- **Lyric Evaluator Agent**: Drops songs whose lyrics contradict your mood (e.g. upbeat melody with melancholic lyrics).

`Spotify API` · `Streamlit` · `Lyric Sentiment Audit`

</td>
</tr>
</table>

---

## 🏢 WHAT I ACTUALLY DO (DAY JOB)

### 🎬 **Senior Associate · Founder’s Office, hoichoi** (2026 – Present)
*Raising AI adoption across 20+ departments so everyday workflows get faster and simpler.*
- **AI Product Manager across 20+ departments**: Audited company-wide AI use-case registries team by team to separate what is build-ready from what is blocked on data or undocumented rules.
- **hoichoiOS**: Developing an internal AI assistant unifying knowledge bases, documentation, and workflows from 20+ departments into a single intelligence layer.
- **Legal OS**: Built end-to-end legal intelligence platform featuring high-precision RAG over 3,500+ contracts and a complete Contract Lifecycle Management (CLM) workflow.
- **Content Intelligence MVP**: Authored PRD and led MVP rollout for video embeddings and scene intelligence with external vendor teams.
- **Voice AI & Founder Special Projects**: Evaluating Indic voice models, automating board & leadership reporting, and executing founder-directed strategic initiatives.

### 🏗️ **Associate AI Product Manager · 5D VDC Services** (2025 – 2026)
*Enterprise workflow automation and SaaS integrations across construction-tech.*
- **etiS 6-product suite**: 0→1 scoping, market & competitor analysis, and enterprise integrations (Autodesk, Zoho); onboarded 2 enterprise clients and 200+ users in 3 months.
- **Autodesk–WhatsApp Multi-Agent System**: Built an intent-based routing system for issue tracking and blueprint retrieval, cutting document retrieval time by ~70% for 600+ daily users.
- **Nudge Alert System**: 4-tier alert system using behavioral usage analytics to eliminate 40K redundant submissions and reduce process error rates by 20%.
- **Tally ERP Pipeline**: Ingested 150K+ monthly ledger entries, saving 30+ analyst hrs/week and bringing inventory reconciliation accuracy to 96.4%.

---

## 🔬 CASE STUDIES (3 AM RABBIT HOLES)

> *Written at 3 AM fueled by dynamic code issues, existential questions, and an unhealthy amount of coffee.*

```
├── 🐧 Deterministic Inference for LLMs ──────── [Kept by Xerox the penguin]
│   └── "Looks exactly like every other penguin. Prefers it that way."
│   └── Deep-dive into floating-point non-determinism in parallel GPU architectures,
│       mathematical PPO variance in RLHF updates, and batch invariance engineering.
│
└── 🦥 Abandonment Issues ────────────────────── [Kept by Dheere the sloth]
    └── "Started this survey in 2019. Still on question four, and very much not abandoning it."
    └── Statistical diagnosis of dropout patterns in digital forms using regression models & NLP.
```

---

## ⚙️ TOOLBOX & CRAFT

```yaml
AI & Agents:
  daily_drivers: [Claude Desktop, Claude Code, Google Antigravity, Gemini 2.0 Flash]
  frameworks:    [LangChain, LangGraph, Agno, AutoGen]
  protocols:     [MCP (Model Context Protocol), WhatsApp Business API]
  models:        [Claude 3.7 / 3.5 Sonnet, GPT-4o, Sarvam AI 105B / 30B / Saaras]

Data & Math (The Statistics Degree):
  core:          [Python, SQL, Pandas, NumPy, scikit-learn, PyTorch, R]
  foundations:   [Large Sample Theory, Sampling & Inference, Linear Models, Survey Attrition]
  pipelines:     [Tally ERP automation, ETL pipelines, Vector DBs, RAG evaluation]

Product & Design:
  execution:     [0→1 Scoping, PRDs, Vendor Gap Analysis, Metrics & Nudge systems]
  design:        [Typography, ASCII plates, Blender 3D, three.js, Next.js, FastAPI]
```

---

## 🐾 RESIDENTS OF THE CROSSING

Every product, file, and case study on the portfolio has its own keeper watching your cursor:

| Resident | Looks After | Quirks |
| :--- | :--- | :--- |
| 🐕 **Shiro** | The Crossing (`whyrachit.in`) | A Kasukabe pup who took a Kolkata job. Poke him 4x and he gets dizzy. |
| 🐨 **chintu** | **mydawAI** | Sleeps 20 hrs/day; never misses a dose. No snooze button allowed. |
| 🐒 **Jaggu** | **tanhAI** | Speaks 11+ languages, negotiates group food orders & Swiggy carts. |
| 🦉 **Hoot** | **sunAI** | Up all night listening. Pronounces technical jargon without flinching. |
| 🐱 **Lofi** | **rihAI** | Moody by default. Has a Spotify playlist for every exact feeling. |
| 🐧 **Xerox** | **Deterministic LLMs** | Looks exactly like every other penguin. Prefers it that way. |
| 🦥 **Dheere** | **Abandonment Issues** | Still filling out the 2019 survey. Refuses to abandon it. |

---

## 🎲 A FEW THINGS ABOUT ME

```javascript
const rachit = {
  currentlyObsessedWith : "agentic workflows + MCP protocols + lightweight local tools",
  quote                 : "I get agents to do the grunt work so I can take credit.",
  askMeAbout            : ["AI product strategy", "WhatsApp agents", "why your PRD is wrong"],
  funFact               : "named my GitHub after the question I make every product answer",
  canNotLiveWithout     : ["SQL", "a tight prompt chain", "late-night chai / black coffee"],
  superpower            : "translating ML engineering chaos into a roadmap everyone understands",
  cocktailPhilosophy    : "great drinks and great products share one thing: balance > ingredients",
};
```

---

<div align="center">

### 🐍 GitHub Contribution Grid

![Snake animation](https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg)

---

```
when you ask "why rachit?" — the answer isn't a single line.
it's curiosity that questions everything before building it.
creativity that finds the angle no one else considered.
and the drive to keep shipping smarter, not just faster.

the name is a question. the work is the answer.
```

**[whyrachit.in](https://whyrachit.in)** &nbsp;·&nbsp; **[@waitedforagi](https://x.com/waitedforagi)** &nbsp;·&nbsp; **[whyrachit@gmail.com](mailto:whyrachit@gmail.com)**

</div>
