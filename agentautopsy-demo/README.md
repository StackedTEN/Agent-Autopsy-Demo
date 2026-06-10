# AgentAutopsy — Live Demo

Self-contained interactive demo of **AgentAutopsy**: independent, retrospective forensics
for AI agent incidents — DFIR for the agentic workforce.

`index.html` is a single file with **no backend, no build step, and zero external resources**.
Open it in a browser, or deploy it as a static site.

## Deploy to Vercel
1. Import this repo at [vercel.com/new](https://vercel.com/new)
2. Framework Preset: **Other** · Build Command: **none** · Root Directory: **leave default**
3. Deploy. The `index.html` at the repo root is served directly.

## What it shows
A scrubable replay of a realistic multi-source AI agent incident — timeline reconstruction,
agent delegation cascade, attack-chain correlation, the memory-poisoning time-gap (OWASP ASI06),
the detection-rule catalog, and engine-generated evidence-grade report previews. The incident is
synthetic; the reconstruction is produced by the real AgentAutopsy engine.

Full source: the AgentAutopsy engine repository.
