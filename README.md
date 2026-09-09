# Hi there, I'm Viet! 👋

I'm a Full Stack & AI Engineer based in Oakland, CA. I build high-performance web applications and production-grade LLM features, focusing on low-latency streaming, deterministic outputs, and local-first architecture.

### 🚀 What I'm Up To
* **Co-Founding:** **ScheduleBud**, an AI-assisted academic management and calendar scheduling platform. Architecting structured inference pipelines, real-time response streaming, and document retrieval engines.
* **Maintaining:** **CardLedger.io**, a local-first inventory manager and collectible browser with automated pipelines handling 20,000+ daily price updates.
* **Focusing on:** Structured Outputs, RAG Architectures, Low-Latency LLM Streaming, and Local-First Web Applications.

### 🛠️ Tech Stack
* **Languages:** TypeScript, JavaScript, Python, SQL, HTML, CSS
* **AI & LLM Systems:** Structured Outputs & Schema Enforcement, Few-Shot Prompt Design, Low-Latency Streaming & Request Cancellation, Vector Embeddings & RAG
* **Frontend:** React, Next.js, Tailwind CSS, Zustand, IndexedDB, Service Workers (PWA)
* **Backend:** Node.js, tRPC, PostgreSQL, Prisma ORM, Server-Sent Events (SSE), REST APIs
* **DevOps & Tools:** Git, GitHub Actions (CI/CD), Docker/Docker Compose, Linux VPS/Nginx/PM2, Cloudflare R2, Jest/Vitest

### 🏆 Featured Projects

#### 📅 ScheduleBud — AI-Assisted Calendar & Academic Management
* Co-founding and leading the AI subsystem, turning uploaded course documents into automated calendar events and personalized study tools.
* Built a multi-pass flashcard generator using an Evaluator-Optimizer loop—combining local vector deduplication, strict schema validation, and an LLM judge to ensure cards are high-yield and non-repetitive.
* Engineered an AI Diagnostic Practice Exam backed by GraphRAG; traverses concept dependency trees (eg `is_prerequisite_of`) to trace failed test questions back to the underlying foundational topics students actually missed.
* Connected post-exam diagnostics straight into the app, letting students generate targeted flashcard decks or schedule study blocks on their calendar with a single click.
* Built real-time SSE streaming with responsive client-side cancellation, clean stream draining, and background token usage tracking across Deno edge functions.

#### 🃏 CardLedger.io — Local-First Collectible Tracking Platform
* Built a precomputing financial tracker with cost basis, acquisition dates, variant-level pricing, and ROI charting—cutting database queries by 90% for returning users.
* Implemented full offline support and cross-device sync via Service Workers, SSE, and PostgreSQL NOTIFY, utilizing LWW timestamps and tombstoned deletes to guarantee data integrity.
* Engineered a client-side search engine utilizing IndexedDB and optimized Set intersections for 0.3ms filter latency and sub-2ms full-text search.
* Restructured hosting to a Linux VPS and CDN, reducing infrastructure costs from $119-188/month to $2/month while optimizing 80,000+ AVIF images.

### ⛰️ Beyond the Keyboard
When I'm not mapping application architecture or tweaking prompts, you can find me running East Bay trails, backpacking, or staying consistent with high-intensity resistance training.

📫 **Reach out:** [LinkedIn](https://linkedin.com/in/vietle510) | [vietle.me](https://vietle.me)
