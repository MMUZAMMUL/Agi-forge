# 🔥 AgentForge

**217 AI specialists. Agent pipelines. Auto-built teams. All free. No PC.**

AgentForge is a mobile-first agentic AI platform that runs entirely in your browser — no server, no install, no cost. Powered by free Groq API (500 req/day) or local Ollama.

🌐 **Live app → [mmuzammul.github.io/Agi-forge](https://mmuzammul.github.io/Agi-forge/)**

---

## ✨ What makes AgentForge different

| Feature | AgentForge | Generic AI chat |
|---|---|---|
| 217 domain specialists | ✅ | ❌ |
| Auto-builds optimal team for your goal | ✅ | ❌ |
| Multi-agent pipelines (chained reasoning) | ✅ | ❌ |
| Agent vs Agent debate (refines answers) | ✅ | ❌ |
| LLM-judged benchmarker | ✅ | ❌ |
| Runs code it writes (70+ languages) | ✅ | ❌ |
| Works offline — all agents embedded | ✅ | ❌ |
| Voice input | ✅ | sometimes |
| File/doc attachment | ✅ | sometimes |
| Export deliverables as .md | ✅ | ❌ |
| 100% free, no PC needed | ✅ | ❌ |

---

## 🚀 Features

### 🤖 217 AI Specialists
Engineers, designers, security experts, marketers, finance analysts, GIS specialists, game developers, and more — each with a deep expert system prompt crafted for real-world tasks, not a generic chatbot personality.

**Divisions:**
- 🏗️ Engineering (Backend, Frontend, Mobile, DevOps, Cloud, Blockchain)
- 🎨 Design (UI/UX, Brand, Motion, 3D, Game Art)
- 🔐 Security (Architecture, AppSec, Pen Testing, Compliance, Forensics)
- 📊 Data & AI (ML Engineer, Data Scientist, NLP, Computer Vision, BI)
- 💼 Business (Strategy, Finance, Legal, Operations, HR)
- 📣 Marketing (Growth, SEO, Content, Social, Email, PR)
- 🔬 Research (Academia, Science Writing, Patent Analysis)
- 🏥 Healthcare (Clinical, Biotech, Medical Writing)
- 🗺️ GIS & Spatial (Geospatial Analysis, Remote Sensing)
- 🎮 Game Dev (Game Design, Narrative, Level Design)
- ⚖️ Legal (Contract, IP, Compliance, Privacy)
- 🌍 Sustainability (ESG, Climate, Green Tech)
- 🎓 Education (Curriculum, Instructional Design, EdTech)
- 🏛️ Government (Policy, Public Affairs, Grants)
- 🎬 Media & Entertainment (Screenwriting, Production, Podcast)
- 🏠 Real Estate (Valuation, Development, PropTech)
- 🔭 Deep Tech (Quantum, Robotics, Space, Bioengineering)

### ✨ Auto-Build Team
Describe your goal. The orchestrator reads all 217 agents and assembles the optimal team in the right order — you don't need to know which agents to pick.

### ⛓️ Agent Pipelines
Chain multiple specialists. Each agent receives all previous outputs as context and builds on them. Run a full product launch — Product Manager → Frontend Dev → Brand Guardian → Growth Hacker — in one tap.

### ⚔️ Agent Debate
Pick two specialists. They argue in rounds — Proposer builds, Critic challenges, Proposer refines — until a battle-tested answer emerges.

### 📊 LLM-Judged Benchmarker
Run the same prompt across multiple agents. An impartial judge model scores each answer on relevance, depth, and correctness — not word count. See which specialist actually performs best for your task.

### ▶️ Code Runner
Every code block the AI writes has a ▶ Run button. Executes instantly via the free Piston API (70+ languages — Python, JS, Go, Rust, Java, C++, and more). No setup.

### 🌐 Web Search
Agents can search the web for real-time information via Brave Search API (free, 2000 searches/month). Add your key in Settings.

### 🎤 Voice Input
Tap the mic, speak, message auto-fills. Built into Chrome and Safari — no API, no install.

### 📎 File Attachment
Attach code files, CSVs, documents, notes. The agent reads them as context. Fully client-side via FileReader — no upload, no server.

### 🧠 Memory
Save any chat or pipeline output to persistent memory. Review, copy, or delete anytime.

### ⬇️ Export
Download pipeline, debate, benchmark, or chat as a `.md` file.

### 🔄 Smart Rate Limit Handling
On Groq's free tier, if one model hits its token limit, AgentForge automatically waits the required time and rotates to a different model (4 model pool, each with its own bucket) — pipelines run to completion without manual retries.

---

## 📱 Getting started (mobile, 2 min)

1. Open **[mmuzammul.github.io/Agi-forge](https://mmuzammul.github.io/Agi-forge/)** on your phone
2. Get a **free Groq API key** at [console.groq.com](https://console.groq.com) (Google login, no card)
3. Paste the key in Settings → **Connect**
4. Pick any specialist and start building

**Add to Home Screen** for a full app-like experience.

---

## 🛠 Self-host (optional)

The entire app is a single HTML file — `index.html`. All 217 agent system prompts are embedded inside it — no server, no build, no external dependencies.

- Open `index.html` directly as a local file on any device
- Host on any static host (GitHub Pages, Netlify, Vercel — all free)
- No build step, no npm, no framework

### GitHub Pages deploy
Enable **Settings → Pages → Source: GitHub Actions** — the workflow auto-deploys on every push to `main`.

---

## 🤖 AI Providers

| Provider | Cost | Setup |
|---|---|---|
| **Groq** | Free (500 req/day) | Paste API key in app |
| **Ollama** | Free (local) | Run on same-network PC |
| **Demo** | Free | No AI, previews UI only |

---

## 📁 Project structure

```
Agi-forge/
├── index.html              # The entire app — self-contained, ~3MB
│                           # All 217 agent prompts embedded inside
├── agents/                 # Source .md files for all 217 specialists
│   ├── engineering/
│   ├── design/
│   ├── security/
│   ├── data/
│   ├── marketing/
│   └── ... (17 divisions total)
└── .github/workflows/
    └── deploy-pages.yml    # Auto-deploy to GitHub Pages on push
```

---

## 🔒 Privacy

- Your API key never leaves your device (stored in `localStorage`)
- No analytics, no tracking, no backend
- All agent content runs client-side
- Only network calls: Groq/Ollama (AI) + optional Brave (search) + Piston (code execution)

---

Built with ❤️ — free forever.
