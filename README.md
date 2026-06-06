<h1 align="center">Practical AI systems, not shiny demos</h1>

<p align="center">
  <b>Agent workflows · local LLM tools · MCP/context systems · products with real users</b>
</p>

<p align="center">
  <a href="https://nyxlabs.app">NyxLabs</a> ·
  <a href="https://github.com/MrJPlayGround/NyxHive">NyxHive</a> ·
  <a href="https://github.com/MrJPlayGround/TLDW">TLDW</a> ·
  <a href="https://github.com/MrJPlayGround/nyxlabs-mcp">NyxLabs MCP</a> ·
  <a href="https://linkedin.com/in/joaoraposo-dev">LinkedIn</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Bun-111827?style=flat-square&logo=bun&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-111827?style=flat-square&logo=supabase&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-111827?style=flat-square&logo=sqlite&logoColor=white" />
</p>

```text
booting profile...

focus:        full AI systems
building:     agent tooling, context infra, local-first AI apps
using:        Cursor, Claude/Anthropic, Claude Code, MCP, Ollama, Whisper
stack:        TypeScript, Bun, Python, React, Supabase, SQLite
preference:   useful systems that survive real users
```

## I like building the layer between LLMs and actual work

The interesting part is not the chatbot. It is everything around it:

- queues, routing, state, retries, and progress visibility
- scoped tools, approval gates, and safe execution boundaries
- context systems that know what to include and what to leave out
- local-first workflows that do not burn money for no reason
- products that are useful when the demo ends

## Things I have built

<table>
<tr>
<td width="50%" valign="top">

### NyxLabs

Live app: [nyxlabs.app](https://nyxlabs.app)

A workflow/data product with hundreds of live users and thousands of trade entries.

Built around structured records, notes, screenshots, analytics, sync workflows, and an AI-readable context layer.

`React` `TypeScript` `Supabase` `Vercel` `MCP design`

</td>
<td width="50%" valign="top">

### NyxHive

Repo: [NyxHive](https://github.com/MrJPlayGround/NyxHive)

An experimental local-first multi-agent runtime.

Explored queue-backed workflows, lead-agent delegation, specialist workers, approval gates, memory, traces, and MCP tools.

`TypeScript` `Bun` `SQLite` `Hono` `MCP` `Claude/Anthropic`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### TLDW

Repo: [TLDW](https://github.com/MrJPlayGround/TLDW)

A local-first video-to-summary app.

Takes video URLs, extracts audio/captions, transcribes speech, and produces cleaned summaries and transcripts.

`Bun` `TypeScript` `Hono` `Whisper` `Ollama` `yt-dlp`

</td>
<td width="50%" valign="top">

### NyxLabs MCP

Repo: [nyxlabs-mcp](https://github.com/MrJPlayGround/nyxlabs-mcp)

A read-only MCP bridge for NyxLabs.

Lets local AI clients like Claude Desktop and Cursor query structured user context without write actions or credential access.

`Node.js` `MCP SDK` `Zod` `stdio` `scoped tokens`

</td>
</tr>
</table>

## Current work shape

```text
AI workflows       agent runtimes       context infrastructure
MCP servers        local LLM apps       human-reviewed tooling
Cursor / Claude    TypeScript / Bun     SQLite-backed state
```

## Short CV

- Integrations Developer / AI Workflow Builder at Optiply.
- Built AI-assisted support and debugging workflows around docs, ETL evidence, logs, API state, and escalation packets.
- Built and maintained Singer/Meltano-style connectors across REST/SOAP APIs, schemas, OAuth/API errors, state/bookmarks, product/order streams, and sync reliability.
- Previously worked across kununu, Capgemini Engineering, and Capgemini internships.
- Formal software training plus a lot of self-directed AI systems work.

## Where I am heading

I want to move deeper into full AI systems: agent tooling, developer tools, context infrastructure, local-first AI apps, and products that survive contact with real users.

If the work sits between LLMs and real execution, I am interested.

<details>
<summary>Small operating opinions</summary>

- Agents need scope more than personality.
- Memory should be inspectable, not mystical.
- Human approval gates are product features, not bureaucracy.
- Local-first is underrated until the API bill arrives.
- The demo is where the work starts.

</details>

<p align="center">
  <i>Build the boring rails. Then let the AI run on them.</i>
</p>
