# Video Scripts — "Simplified by Mahendra Gajera"

Four ready-to-record voiceover scripts, one per RangerAI project. Each is timed to ~45 seconds, matching the animated reels in `reels.html`. Read at a natural pace with brief pauses between sentences. Tone: confident, conversational, technically precise — never marketing-y.

---

## How to record

**Option 1 — Screen recording over the animated reel (recommended)**
1. Open `reels.html` in fullscreen.
2. Start screen recording (Loom, OBS Studio, QuickTime, or your phone).
3. Hit play on the reel and read the matching script aloud.
4. Export as MP4 → upload to LinkedIn / YouTube / your portfolio.

**Option 2 — Talking head**
Record yourself talking with the script visible off-camera. Cut to brief screenshots or the reel between sections.

**Recording tips**
- Quiet room, decent mic (phone earbuds work fine).
- Speak slightly slower than feels natural — clarity beats speed.
- Pause one beat after each metric.
- Keep your hands free for natural breath.

---

## Project 01 — Troubleshoot with RangerAI
**Runtime: ~45 seconds**

> [Title — 5s]
> Troubleshoot with RangerAI. Intelligent job diagnostics for enterprise automation. I'm Mahendra Gajera.

> [Problem — 7s]
> When a job fails in a distributed system, finding *why* shouldn't take hours. Developers were sifting through massive raw logs, jumping across screens, hypothesising fixes. Every minute of mean-time-to-resolution is a minute the business runs degraded.

> [Approach — 9s]
> My approach was to bridge raw infrastructure data to developer action. The prompt layer only activates on a terminal Error state, so there's no noise. The AI is focused on the stderror stream — the actual failure point. And the output is tri-fold: raw evidence, a plain-English explanation, and a proposed remedy.

> [Architecture — 7s]
> Under the hood: a fine-tuned GPT-4o-class model for stack traces. A log engine that fetches from S3 or Azure only on demand. Structured JSON prompts for consistency. And conditional React UI that validates job state before exposing the entry point.

> [My role — 8s]
> I defined the end-to-end architecture, designed the prompts to stop hallucinated fixes for hardware failures, built the API bridge to the LLM endpoint, and wrote the graceful fallback when error logs aren't available.

> [Impact — 5s]
> The result: a sixty-five percent reduction in debugging time, automated log parsing, and a one-click diagnostic workflow.

> [Outro — 4s]
> Shipped in Redwood RunMyJobs 2026, Modern UI, in production today.

---

## Project 02 — RangerAI Product Assistant
**Runtime: ~45 seconds**

> [Title — 5s]
> RangerAI Product Assistant. A conversational documentation engine for the RunMyJobs platform. I'm Mahendra Gajera.

> [Problem — 7s]
> Enterprise platforms have thousands of pages of dense technical documentation. Traditional search returns fragments — and users are forced to manually synthesize answers. People need answers, not links.

> [Approach — 9s]
> My approach was information at the point of need. An in-product overlay surfaces the entire knowledge base from any screen. A thirty-minute session memory lets users ask follow-up questions while implementing. Sample prompts lower the barrier to entry. And the assistant is grounded — scoped strictly to the RunMyJobs docs to eliminate hallucinations.

> [Architecture — 7s]
> Under the hood: a high-fidelity RAG pipeline over a vector store of crawled, chunked docs. A custom session caching layer that clears context after thirty minutes idle. A Python microservice for NLP and retrieval. And hybrid search — keyword matching for command syntax, semantic embeddings for concepts.

> [My role — 8s]
> I drove the AI strategy, designed the memory persistence and RAG ingestion architecture, engineered the system prompts for a professional technical tone, and aligned with the Documentation and UX teams on a shared information model.

> [Impact — 5s]
> The result: a forty percent support-ticket deflection, thirty minutes of conversational context, and one hundred percent documentation grounding.

> [Outro — 4s]
> Shipped in Redwood RunMyJobs 2026, in production for SaaS customers worldwide.

---

## Project 03 — RangerAI Automation Co-pilot
**Runtime: ~45 seconds**

> [Title — 5s]
> RangerAI Automation Co-pilot. AI-powered scripting, backed by a RAGAS quality gate. I'm Mahendra Gajera.

> [Problem — 7s]
> Scaling enterprise automation requires specialised scripting — RedwoodScript — and that becomes a bottleneck when only platform experts can write it. Manual script creation is slow, error-prone, and heavy on documentation lookup.

> [Approach — 9s]
> So I built a co-pilot, and evaluated it on four dimensions. Syntactical correctness: does the generated code compile. API adherence: does it use proprietary platform classes, or invent generic libraries. Safety guardrails: destructive operations come with proper warnings. And context continuity across multi-turn refinements.

> [Architecture — 7s]
> Pipeline: a dual-engine RAG ingests thousands of RedwoodScript examples and Java API docs. A RAGAS quality gate runs every update against a Golden Script Set to catch regressions. A stateful conversation bridge enables iterative debugging. And specialised prompts handle Java, Shell, and RedwoodScript runtimes.

> [My role — 8s]
> I architected the code-generation logic, built the RAGAS evaluation suite with Code Faithfulness metrics, led the backend-to-frontend bridge for Insert Code, and hand-curated two hundred plus complex automation scenarios for the RAGAS baseline.

> [Impact — 5s]
> The result: a fifty percent lift in developer velocity, ninety-two percent syntactical accuracy, and zero-shot code generation.

> [Outro — 4s]
> Shipped in Redwood RunMyJobs 2026, raising the floor for non-expert script authoring.

---

## Project 04 — Generate with RangerAI
**Runtime: ~45 seconds**

> [Title — 5s]
> Generate with RangerAI. A self-documenting automation engine. I'm Mahendra Gajera.

> [Problem — 7s]
> In enterprise automation, *documentation debt* is a silent killer of productivity. Engineers build complex nested workflows but never document the logic. Maintenance grinds to a halt. Audits become risky. The cost compounds every quarter.

> [Approach — 9s]
> My approach was zero-friction documentation at the editor — generation lives where work happens. The system ingests holistically: not just scripts, but metadata, dependencies, and execution parameters. AI insights append after human notes, so institutional knowledge is preserved. And graphical workflows are transformed into semantic prompts an LLM can interpret.

> [Architecture — 7s]
> Under the hood: a graph serialization layer flattens multi-step workflow hierarchies into coherent text. Token-aware inference detects Large Definition edge cases and prevents truncation. Prompt architecture tuned for RedwoodScript and Java. And a stateful React injection updates the Documentation tab without a page refresh.

> [My role — 8s]
> I led the architectural vision for the shift from manual docs to AI-assisted generation, wrote the core Python that converts workflow objects into LLM-readable descriptions, solved the Large Definition problem with hierarchical summaries, and defined the one-click UX with clear AI-vs-human attribution.

> [Impact — 5s]
> The result: an eighty percent reduction in manual documentation effort, instant context synthesis, and logic-to-text on save.

> [Outro — 4s]
> Shipped in Redwood RunMyJobs 2026. Documentation debt, paid down at scale.

---

## Recording checklist

- [ ] Quiet room, mic tested
- [ ] `reels.html` open in fullscreen
- [ ] Script printed or on a second screen
- [ ] Practice run-through before recording
- [ ] Record in landscape if posting to LinkedIn / YouTube
- [ ] Record in portrait if posting to LinkedIn video posts / Instagram
- [ ] Trim trailing silence in post

## Distribution

- LinkedIn video post (native upload — best reach)
- YouTube short or unlisted video linked from the portfolio
- Embed the recorded MP4 in the Featured Work tabs (replace the "Watch the reel" link with an inline `<video>` tag)
- Loom links for recruiters / interviews
