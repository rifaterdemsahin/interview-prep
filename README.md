# interview-prep

Interview Prep 2026 — flashcards, voice answers and live interviewer role-play for the **London Inside IR35 contract market**.

Live: **https://rifaterdemsahin.github.io/interview-prep/**

## Tracks

| Track | Questions | Focus |
| --- | --- | --- |
| Software Developer | 18 | Recruiter screen, IR35/commercials, technical depth, behavioural |
| AI Architect | 18 | Enterprise LLM architecture, RAG, agents, evals, governance, commercials |

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
