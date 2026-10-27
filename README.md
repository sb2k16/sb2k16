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

Two loops, same operation count, same `O(n)`. One of them is thirty to sixty times slower — because of the *order* in which it touches memory. Most data structures books stop at Big-O. This one keeps going: cache lines, prefetchers, memory layout, false sharing, B-trees, LSM-trees, concurrency — and how production systems like Redis, Postgres and OpenSearch put them to work.

> ### → **[data-structures-on-systems.vercel.app](https://data-structures-on-systems.vercel.app)**

- **Live benchmarks that run on _your_ CPU.** The [memory hierarchy chapter](https://data-structures-on-systems.vercel.app/chapters/memory-hierarchy) measures your machine while you read it — latency at every cache level, the real cost of a miss, what array-of-structures charges you. No screenshots of someone else's laptop.
- **"Watch it run" visualizations.** Step through two-sum, Kadane's, a BST search, a B-tree split, an LSM flush/compaction, a thread race vs. a mutex, a BFS traversal — animated, at your pace.
- **Runnable problems in four languages.** C++, Python, Java, Go — compiled and judged in the browser, including the [practice set](https://data-structures-on-systems.vercel.app/practice).

`Astro` · `MDX` · `React islands` · MIT licensed → **[sb2k16/data-structures-book](https://github.com/sb2k16/data-structures-book)**

---

## 🚀 Things I've built

### 🔭 [Siddhanta](https://siddhantaresearch.com) — understand where you stand in science
Bring a paper, a draft or an abstract. Siddhanta shows the real researchers whose published work genuinely overlaps yours, what to read to reach the frontier, and the open directions near your work — for grad-school applicants choosing advisors and researchers choosing a next problem, across **six STEM fields**.

The rule is that every result traces to a real, cited source: no invented professors, no invented papers. Underneath is a seeded faculty corpus built from OpenAlex, matched with **pgvector** embeddings and a reranker, NSF grant data on each lab, and an accuracy eval run against a frozen set of 260 papers with citation-derived answer keys. The current R&D thread is a **theorem index** — ~700k statements parsed straight from arXiv LaTeX source, numbered, with proofs and citations attached — so it can answer "which known result does this step need, and who proved it?"

`Express` · `TypeScript` · `React` · `Neon Postgres + pgvector` · `Clerk` · `Anthropic` · `Fly.io` · `S3` · `Stripe` · `Vercel`

### 📐 [Lemma](https://lemmamath.vercel.app) — your working, checked
Solve a problem on paper, snap a photo, and Lemma checks the **reasoning, not just the answer** — it points at the first line that breaks, nudges without giving the fix away, and accepts any correct method. Proofs too.

Behind it: a library of **65,000+ problems across 17 subjects**, from arithmetic to abstract algebra, drawn from open textbooks and classics (Hall & Knight, OpenStax, Strang's *Calculus*, Dudeney) plus generated practice. Auto-check keys are kept only when the judge, an independent solve and a strictness test all agree. Placement quiz, chapter mastery, spaced review that brings problems back as fresh variants, and a checker accuracy set that every change is measured against.

`Next.js 16` · `React 19` · `KaTeX` · `MathLive` · `AI SDK` · `Clerk` · `Neon` · `Stripe` · `Playwright`

### 🧮 [AlgoTutor](https://algo-tutor-six.vercel.app) — watch the algorithm, not the slide
The companion app to the book. **70 algorithms** implemented in **C++** — not simulated in JavaScript. The engine runs the real code and emits one NDJSON event per step; the browser replays that trace, so the animation you scrub through *is* the execution, line-synced with the source.

Around the player: ~500 problems judged by a data-driven judge in six languages, an AI tutor grounded in the book (RAG over the chapter text), a mock-interview mode, a weekly themed problem marathon with a leaderboard, and a mastery model over a knowledge graph of 19 topics that diagnoses what's actually weak.

`C++` · `Express` · `React` · `Vite` · `Expo` · `Clerk` · `Neon` · `Anthropic` · `Vercel`

### 🚗 [Commute Pulse](https://commute-pulse-gamma.vercel.app) — know exactly when to leave
Maps tells you traffic *right now*. Commute Pulse shows you **the whole week** — the same route at every departure time, on only the days you actually drive — so you pick when to leave instead of taking whatever you get.

Departure alarms back-calculate `departBy = arrival − liveDuration − buffer` on a cron and push "leave now" while you can still act on it. Multi-stop mornings time every leg against live traffic; toll vs. toll-free shows what the fast route costs in money and the free one in time; transit, bike and rideshare sit alongside. A Copilot briefing narrates numbers the server has already computed, never its own. There's an SMS bot for `status`, too.

`Next.js` · `Expo` · `Google Routes API` · `Upstash Redis` · `Clerk` · `Stripe` · `Twilio` · `Vercel Cron` · `Anthropic`

---

<p align="center">
  <sub>Most of the product repos above are private while they're in flight — the live links are the real thing, not screenshots.</sub>
</p>
