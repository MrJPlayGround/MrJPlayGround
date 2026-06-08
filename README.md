<h1 align="center">Practical AI systems, not shiny demos</h1>

<p align="center">
  <b>Agent workflows · integration architecture · local LLM tools · MCP/context systems · products with real users</b>
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

focus:        practical AI systems and end-to-end integrations
building:     agent tooling, context infrastructure, local-first AI apps
operating:    connectors, ETL workflows, APIs, production debugging
using:        OpenAI Codex, Cursor, Claude/Anthropic, MCP, Ollama, Whisper
stack:        TypeScript, Bun, Python, React, Supabase, SQLite
preference:   useful systems that survive real users
```

## I like building the layer between LLMs and actual work

The interesting part is not the chatbot. It is everything around it:

- queues, routing, state, retries, and progress visibility
- scoped tools, approval gates, and safe execution boundaries
- context systems that know what to include and what to leave out
- local-first workflows that do not burn money for no reason
- integrations that survive real APIs, bad data, and production edge cases
- products that are useful when the demo ends

## Things I have built

<table>
<tr>
<td width="50%" valign="top">

### NyxLabs

Live app: [nyxlabs.app](https://nyxlabs.app)

A full-stack workflow product with daily users, hundreds of accounts, and thousands of trade entries.

Built around structured records, notes, screenshots, analytics, sync workflows, user feedback loops, and an AI-readable context layer.

`React` `TypeScript` `Supabase` `Vercel` `product operations`

</td>
<td width="50%" valign="top">

### NyxHive

Repo: [NyxHive](https://github.com/MrJPlayGround/NyxHive)

An experimental local-first multi-agent workflow runtime.

Explored queue-backed workflows, lead-agent delegation, specialist workers, approval gates, memory, traces, scoped tools, and reviewable outputs.

`TypeScript` `Bun` `SQLite` `Hono` `MCP` `Claude/Anthropic`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### TLDW

Repo: [TLDW](https://github.com/MrJPlayGround/TLDW)

A local-first video-to-summary app and model-routing experiment.

Takes video URLs, extracts audio/captions, transcribes speech, and tests local model/routing strategies for cleaner summaries, transcripts, and condensed outputs.

`Bun` `TypeScript` `Hono` `Whisper` `Ollama` `yt-dlp`

</td>
<td width="50%" valign="top">

### NyxLabs MCP

Repo: [nyxlabs-mcp](https://github.com/MrJPlayGround/nyxlabs-mcp)

A read-only MCP bridge for NyxLabs.

Lets local AI clients like Claude Desktop and Cursor query structured user context without write actions or credential exposure.

`Node.js` `MCP SDK` `Zod` `stdio` `scoped tokens`

</td>
</tr>
</table>

## Current work shape

```text
AI workflows          integration architecture      production debugging
MCP servers           local LLM apps                human-reviewed tooling
agent runtimes        context infrastructure        SQLite-backed state
Cursor / Claude       OpenAI Codex                  TypeScript / Bun / Python
```

## Short CV

- Integrations Developer / AI Workflow Builder at Optiply since 2023.
- Own integration work end to end: discovery, client context, data flows, connector architecture, delivery plans, and operational handoff.
- Build AI-assisted support and debugging workflows around docs, ETL evidence, logs, API state, investigation notes, and escalation packets.
- Develop and maintain Singer/Meltano-style connectors across REST/SOAP APIs, schemas, OAuth/API errors, state/bookmarks, product/order streams, and sync reliability.
- Debug production integrations across API behavior, job state, logs, configuration, source data, and application state.
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
- Integrations are mostly reliability work wearing an API badge.

</details>

<p align="center">
  <i>Build the boring rails. Then let the AI run on them.</i>
</p>
