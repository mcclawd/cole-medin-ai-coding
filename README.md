# Cole Medin — Best AI-Coding Videos (OKF Bundle)

A curated [Open Knowledge Format](https://github.com/GoogleCloudPlatform/knowledge-catalog) (OKF) bundle of Cole Medin's best videos on *principled agentic engineering*. It's plain markdown + YAML frontmatter — so **any** OKF-aware AI second brain can mount it and search it deeply, with zero integration.

## What's inside

- `index.md` — start here (progressive disclosure)
- `videos/` — one knowledge doc per video: summary, key ideas, tools, links
- `concepts/` — cross-cutting themes (context engineering, the PIV loop, the AI layer, the Archon harness builder, and MCP) that link the videos together
- `log.md` — update history

## Consume it

Any OKF consumer works. With the reference reader in this repo:

```bash
okf_consumer.py mount <this-repo-url> --name cole-ai-coding
okf_consumer.py index cole-ai-coding
okf_consumer.py find cole-ai-coding "the PIV loop"
```

## Data confidence (honest notes)

- **Titles and channel** are verified (real @ColeMedin uploads).
- **Summaries, key ideas, and tools are transcript-verified** for ALL five videos — rewritten directly against the full video transcripts (each doc is marked `source: transcript-verified`).
- **View counts are intentionally omitted** — third-party mirror numbers are stale/unreliable.
- **Publish dates are approximate** and flagged as such.

Channel: https://www.youtube.com/@ColeMedin
