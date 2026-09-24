# interview-prep

Interview Prep 2026 — flashcards, voice answers and live interviewer role-play for the **London Inside IR35 contract market**.

Live: **https://rifaterdemsahin.github.io/interview-prep/**

## Tracks

| Track | Created | Questions | Focus |
| --- | --- | --- | --- |
| **Software Developer** | 18 Sep 2026 | 18 | Recruiter screen, IR35/commercials, technical depth, behavioural |
| **AI Architect** | 18 Sep 2026 | 18 | Enterprise LLM architecture, RAG, agents, evals, governance, commercials |
| **AI Engineer (Morgan Stanley & TCS)** | 24 Sep 2026 | **20 (Quiz) + 8 (Decks)** | **Tier-1 Banking AI, 10M+ RAG, LangGraph Agentics, Benchmarks (-60% latency, 300% deploy), UK SC & NATO** |

## ⚡ Animated 2-Option Quiz Mode (`quiz.html`)

Interactive rapid-fire 2-option flashcards designed specifically for the **Morgan Stanley & TCS AI Engineer Portfolio**:
- **Binary Choice (Strictly 2 options per card)**: Tests precise architectural discrimination (e.g. Hybrid BM25 vs pure vector, cyclic LangGraph vs linear chains, precision vs recall re-ranking).
- **Live Scoring & Streak Multipliers**: Dynamic score tracking, accuracy percentage, and flame streaks.
- **Instant Animated Feedback**: 3D perspective flip card transitions, shake animations, and synthesized Web Audio sound FX (chimes & haptics).
- **Portfolio Evidence & Slide Deep Dives**: Displays exact slide citations and click-to-enlarge slide graphics from the briefing document.
- **Review Missed Cards Mode**: Retest missed questions to guarantee 100% mastery before the live panel.

## 📊 Post-Interview Feedback & Self-Scoring Portal (`feedback.html`)

Ingest interview transcripts and evaluate performance against London Inside IR35 & Tier-1 Banking rules:
- **Auto-Ingestion from Local Storage**: 1-click import of all saved answers and transcripts from practice sessions.
- **The 5 Evaluation Rules Engine**: Automatic audit tracking IR35 framing, quantification density, technical accuracy, 90-second brevity, and security clearances.
- **Interactive Self-Scoring Rubric**: Calibrate sliders across 5 dimensions (0–20 pts each, 100 max) with automated tier rating.
- **Actionable Feedback Report**: Identifies key candidate strengths and targeted improvement areas with 1-click Markdown download.

## 🗺️ Enterprise AI Tech Stack Mindmap (`mindmap.html`)

Support document for the **Morgan Stanley & TCS AI Engineer** role covering the 5 core pillars of enterprise banking AI:
1. **Retrieval & Vector DBs**: Hybrid Search (Dense + BM25), Context-Aware Chunking, Cross-Encoder Re-Ranking, and Vector DB Stack (Pinecone, Qdrant, Milvus, Weaviate, FAISS).
2. **Autonomous Systems**: LangGraph Cyclic State Graphs with checkpointing, CrewAI routing, ReAct Pydantic schema-enforced tool calling, and MCP integration.
3. **Developer Acceleration**: GitHub Copilot Enterprise (`.github/copilot-instructions`, test synthesis, review agents) and Claude Code terminal agentics.
4. **Evaluation & Observability**: RAGAS faithfulness/relevancy tracking, LangSmith telemetry traces/cost audits, and LoRA/QLoRA parameter-efficient adaptation.
5. **Security & Compliance**: PII regex/NER sanitization, 95% prompt injection defense, and active UK SC (2028) & NATO (2029) clearances.
- **Architectural Rationale Comments**: Each pillar contains deep commentary explaining why these standards are enforced in Tier-1 banking.

## Features

- **Role selection** at the top — switch between Software Developer and AI Architect decks.
- **Memory-card flashcards** — question on the front, interviewer intent, strong-answer points, key terms and a spoken-style model answer on the back.
- **Voice answers** — record with the mic (Web Speech API, en-GB, Chrome/Edge) and get a live transcription saved as your answer. Nothing is uploaded.
- **Role-play interviewer** — submit your answer and the interviewer acknowledges it, checks the key terms you hit, pushes back with real follow-up probes, then gives a score and verdict. Questions and replies can be spoken aloud.
- **Progress tracking** — answered count, average score, per-question dots and a saved answers list.
- **Export** — download all answers, feedback and model answers as Markdown or JSON.
- Keyboard: `←`/`→` navigate, `F` flip, `M` toggle mic.

## Local use

Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8080
```

Answers persist in browser localStorage under `interviewPrep2026.v1`.
