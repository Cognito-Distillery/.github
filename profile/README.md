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

### [Distillery Desktop](https://github.com/Cognito-Distillery/Distillery-desktop)

Where it all begins. A desktop app for capturing and curating your thoughts. Quick-capture with a global shortcut, full-text search, and a distillation queue that syncs with the server.

`Tauri` `Svelte 5` `Rust` `SQLite`

### [Distillery Server](https://github.com/Cognito-Distillery/Distillery-server)

The engine. Receives queued thoughts, generates embeddings, extracts relationships with AI, and builds the knowledge graph. Runs distillation at noon and midnight. A weekly backfill prevents knowledge from sitting in isolation.

`Elysia` `PostgreSQL + pgvector` `Neo4j` `OpenAI`

### [Blending Room](https://github.com/Cognito-Distillery/Distillery-web-dashboard)

The final stage. An interactive graph explorer where AI-casked knowledge meets human judgment. Browse, filter, and refine relationships — every human edit is tracked alongside AI-generated connections.

`SvelteKit` `Cytoscape.js` `Tailwind CSS`

<br>

## License

MIT
