<h1 align="center">Souvik Bose</h1>

<p align="center">
  Senior Software Engineer at <b>AWS — Search Services</b> · Data Prepper, OpenSearch Ingestion.<br>
  I build systems that have to be fast, and products that have to be honest about <i>why</i> they say what they say.
</p>

<p align="center">
  <a href="https://data-structures-on-systems.vercel.app"><img alt="Book" src="https://img.shields.io/badge/📖_Data_Structures_on_Systems-read_free-2a78d6?style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/souvik-bose-65b9485/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

---

## 📖 Data Structures on Systems

**A free, interactive book about data structures as the machine actually runs them.**

Two loops, same operation count, same `O(n)`. One of them is thirty to sixty times slower — because of the *order* in which it touches memory. Most data structures books stop at Big-O. This one keeps going: cache lines, prefetchers, memory layout, false sharing, B-trees, LSM-trees, concurrency. That's where the performance of real systems is actually decided.

> ### → **[data-structures-on-systems.vercel.app](https://data-structures-on-systems.vercel.app)**

- **Live benchmarks that run on _your_ CPU.** The [memory hierarchy chapter](https://data-structures-on-systems.vercel.app/chapters/memory-hierarchy) measures your machine while you read it — latency at every cache level, the real cost of a miss, what array-of-structures charges you. No screenshots of someone else's laptop.
- **"Watch it run" visualizations.** Step through two-sum, Kadane's, a BST search, a B-tree split, an LSM flush/compaction, a thread race vs. a mutex, a BFS traversal — animated, at your pace.
- **Runnable problems in four languages.** C++, Python, Java, Go — compiled and judged in the browser, including the [practice set](https://data-structures-on-systems.vercel.app/practice).

`Astro` · `MDX` · `WebAssembly` · MIT licensed → **[sb2k16/data-structures-book](https://github.com/sb2k16/data-structures-book)**

---

## 🚀 Things I've built

### 🔭 [Siddhanta](https://siddhantaresearch.com) — graduate research launchpad
Automates the grad-school outreach pipeline for prospective **Mathematics** and **Computer Science** applicants. It ingests a student's manuscript, extracts its mathematical footprint into a semantic research vector, matches that vector against thousands of active faculty, flags reviewer-risk gaps in the work, and drafts precise cold outreach.

Behind it: an OpenAlex-backed corpus of ~2k faculty and ~70k papers per discipline, embedded and searched with **pgvector** centroids, plus an NSF grant pipeline that scores each lab's funding health.

`Express` · `TypeScript` · `Neon Postgres + pgvector` · `Clerk` · `Anthropic` · `Fly.io` · `Vercel`

### 🧠 [Codexa](https://codexa-rose.vercel.app) — engineering intelligence platform
Learns *how* an engineer thinks across three pillars — **Algorithms**, **System Design**, **AI Engineering** — and continuously answers one question: *what is the single best thing I should learn next?*

Built around a knowledge graph and a three-tier skill detector, so it shows the **why** behind a score, not just the score. Design closer to Linear/Cursor than to Coursera.

`React` · `Express` · `Neon Postgres` · `Clerk` · `Anthropic`

### 📐 [Lemma](https://lemmamath.vercel.app) — a home for mathematical thinkers
A community-first math app: curated problems worth thinking about, rather than an endless drill feed. Ships with procedural generators (~7,700 problems) behind a hand-built design system, on web and native.

`Next.js 16` · `React 19` · `Expo` · `KaTeX` · `Clerk` · `Neon`

### 🚗 [Commute Pulse](https://commute-pulse-gamma.vercel.app) — live traffic, three ways
One-tap live drive times, target-arrival alarms that back-calculate *when to leave* (`departBy = arrival − liveDuration − buffer`) on a 10-minute cron, and an SMS bot that answers `status` with your current commute. Multi-stop optimizer deep-links straight into Google Maps.

`Next.js` · `Expo` · `Google Routes API` · `Twilio` · `Vercel Cron`

### 🌿 [Willow](https://willow-six-ashen.vercel.app) — AI recovery companion
Presence at the vulnerable moment, not streak-counting. Starts with nicotine/vaping.

The architecture is a product argument: **safety is the spine, not the ER.** Every inbound message is screened for crisis language before anything else runs, and every word the model produces passes an output guard that can never assert a reassuring risk verdict as fact. All intelligence is server-side, so the guard cannot be bypassed by a client.

`Express` · `Expo` · `Clerk` · `Neon` · `Anthropic`

### 🕯️ [Solace](https://solace-web-pied.vercel.app) — voice-first companion for loneliness and low mood
A 24/7 conversational companion, wellness and companionship rather than treatment, with the same non-bypassable safety spine intercepting crisis on every turn and routing to real help. Runs end-to-end keyless in mock mode — no API keys, no database — so the full loop is testable by anyone.

`Express` · `Expo` · `TypeScript`

### 🍽️ [Meal Planner AI](https://meal-planner-ai-gilt.vercel.app) — meal plans and calorie math
Preference-aware meal planning with a shopping cart and calorie calculator on a Go + Node backend.

`Go` · `Node` · `React` · `Docker`

### 🧪 AI Test Kit — a test harness for AI applications
Scenario-driven, YAML-defined evaluation for LLM apps, as a CLI (`aitest`) and a dashboard. Because "it looked right when I tried it" is not a test suite.

`TypeScript` · `Anthropic SDK` · `Zod` · `Express`

---

<p align="center">
  <sub>Most of the product repos above are private while they're in flight — the live links are the real thing, not screenshots.</sub>
</p>
