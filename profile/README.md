<div align="center">
  <br>
  <img src="./assets/distillery-512.png" width="140" alt="Distillery" />
  <h1>Distillery</h1>
  <p><strong>Distill thoughts into aged knowledge.</strong></p>
  <p><a href="./lang_readme/README.ko.md">한국어</a></p>
  <br>
</div>

Knowledge doesn't arrive organized. It comes in fragments — a sudden insight during a walk, a decision made in a meeting, a question that keeps nagging.

**Distillery** captures these raw thoughts and transforms them into a living knowledge graph. The entire system borrows the vocabulary and process of whiskey-making: each stage has purpose, each step adds clarity.

<br>

## The Process

```
Malting          capture raw thoughts — decisions, problems, insights, questions
   ↓
Still            curate and select what matters
   ↓
Distillation     AI embeds meaning, discovers hidden relationships
   ↓
Cask             knowledge matures into a connected graph
   ↓
Blending Room    explore, refine, and connect with human judgment
```

<br>

## Projects

### [Moonshine](https://github.com/Cognito-Distillery/moonshine)

The unified standalone edition. Everything in one app — capture, curate, distill, and explore — with no server required. A single SQLite file holds your entire knowledge graph. Semantic search, automatic relationship discovery, and a floating memo for quick capture.

`Tauri 2` `Svelte 5` `Rust` `SQLite` `Cytoscape.js` `OpenAI` `Gemini`

### [Moonshine MCP](https://github.com/Cognito-Distillery/Moonshine-MCP)

An MCP server that lets AI assistants — Claude, ChatGPT, Gemini — directly access your Moonshine knowledge graph. Search, browse, and edit your mashes and relationships through natural conversation. Works independently of the Moonshine app.

`MCP` `TypeScript` `better-sqlite3`

---

### [Distillery Desktop](https://github.com/Cognito-Distillery/Distillery-desktop)

The original client. A desktop app for capturing and curating your thoughts. Quick-capture with a global shortcut, full-text search, and a distillation queue that syncs with the server.

`Tauri` `Svelte 5` `Rust` `SQLite`

### [Distillery Server](https://github.com/Cognito-Distillery/Distillery-server)

The engine. Receives queued thoughts, generates embeddings, extracts relationships with AI, and builds the knowledge graph. Runs distillation at noon and midnight. A weekly backfill prevents knowledge from sitting in isolation.

`Elysia` `PostgreSQL + pgvector` `Neo4j` `OpenAI`

<br>

## License

MIT
