# Cole Medin — AI-Coding Knowledge Bundle

A portable knowledge base of my best videos on AI coding — **Claude Code, context engineering, the PIV loop, the AI layer, and the new Archon harness builder**. It's plain markdown that any AI coding agent can read, so you don't watch the videos — your AI does, and you just ask.

## How to use it

Give this repo's URL to your AI coding assistant (Claude Code, Cursor, Codex, Gemini CLI, …), tell it to clone the bundle, and start asking questions. Paste this to your agent:

```
Clone https://github.com/coleam00/cole-medin-ai-coding into this project, read its index.md,
and use the bundle to answer my questions about AI coding.
Start by telling me what's inside.
```

Then ask anything I cover — *"How does the PIV loop work?"*, *"What is the new Archon harness builder?"*, *"How do I use context engineering with PRPs?"* — and your agent will navigate the bundle and answer, pointing you to the exact video.

## What's inside

- `index.md` — start here; the table of contents
- `videos/` — one page per video (summary, key ideas, tools, link)
- `concepts/` — the cross-cutting themes that tie the videos together
- `log.md` — change history

---

<details>
<summary><b>🤖 Instructions for your AI agent — how to read this bundle</b></summary>

_The text below is for the AI assistant you handed this to, not for you. It explains the format and how to navigate it._

**What this is.** This repo is an [Open Knowledge Format (OKF)](https://github.com/GoogleCloudPlatform/knowledge-catalog) bundle — a directory of markdown files, each with a small YAML frontmatter block, that you read **directly**. No SDK, no database, no embeddings, no special tooling. If you can read a file, you can use this knowledge base.

**How to navigate it (progressive disclosure — do NOT load everything):**

1. Read `index.md` at the repo root first. It's the catalog.
2. From there, read `videos/index.md` and `concepts/index.md` to see what's available (each entry has a one-line description).
3. Open only the specific `videos/<slug>.md` or `concepts/<slug>.md` pages relevant to the user's question — not the whole bundle.
4. Pages cross-link with relative markdown links; follow them between a video and the concepts it teaches (and vice-versa).

**Reading a page.** Each page's frontmatter has a `type` (`video` or `concept`), a `title`, a `description`, `tags`, and — for videos — a `resource` field with the YouTube URL. When you answer, cite the source video by its title and `resource` URL.

**To answer a question:** read `index.md` → pick the relevant pages from the two index files → read those pages → answer, grounded in them, and link the video(s) you used. This is read-only reference knowledge — don't modify the bundle.

</details>

Channel: https://www.youtube.com/@ColeMedin
