# Welcome to my World, Chandrahaas

Computer Science student building practical AI and workflow automation tools focused on **GenAI apps, decision intelligence, identity workflows, and data-rich dashboards**.

I build with a mix of hands-on coding, AI-assisted development, and strong product thinking. My focus is understanding what the project should do, why the workflow matters, and how the pieces fit together.

I like projects that turn messy real-world inputs into structured, useful systems: workplace notes into decision records, identity requests into auditable workflows, weather data into interactive interfaces, and operational data into cleaner dashboards.

## Current Focus

I'm building around one main direction:

> **GenAI apps + workflow automation + practical product thinking**

My current work focuses on:

- GenAI applications that extract structure from messy text, files, chats, emails, and notes
- Python and JavaScript applications with clear business logic
- Human-in-the-loop review workflows for AI-generated outputs
- Agentic AI pipelines with real-time voice, function calling, and tool use
- Local-first and desktop-style app experiences
- Workflow automation, audit trails, approvals, and searchable operational memory
- Learning how to structure larger projects with cleaner modules, tests, and UI/UX

## Featured Projects

### [WikiBot — Real-time Voice Agent](https://github.com/chandra23225/wikibot-pipecat) ⭐ New

A real-time voice assistant built with **Pipecat** that answers factual questions by searching Wikipedia live during conversation.

Pipeline: `Mic → Whisper STT → Gemini 2.0 Flash (+ Wikipedia tool call) → Kokoro TTS → Speaker`

- **Pipecat** framework wires the streaming STT→LLM→TTS pipeline with VAD and WebRTC transport
- **Gemini function calling** fires a Wikipedia lookup mid-conversation and speaks back the result
- Whisper and Kokoro run locally — only the LLM call hits the network
- Custom tutorial landing page + 6-step interactive UI guide overlay
- Deployment config ready for Render + Hugging Face Spaces

### [DecisionVault AI](https://github.com/chandra23225/DecisionVault_AI)

GenAI-powered decision memory workspace that converts messy workplace communication into structured, reviewable decision records.

Recent updates:

- Migrated from a Streamlit-only app to a custom **Flask + HTML/CSS** interface
- Added a desktop app launcher using `pywebview`
- Added smarter Ask behavior that uses reviewed records first and raw source text as backup
- Added structured Ask results with direct answers, key points, supporting records, source references, information gaps, and next steps
- Added editable review workflows before saving records, including save-ready and save-all flows
- Added Vault search, filtering, statuses, inline editing, safer delete/clear confirmations, CSV/Excel exports, and duplicate prevention
- Improved review UX with friendlier missing-field handling, AI confidence, completeness signals, and clearer user guidance
- Added Gemini overload retry handling and cleaner user-facing errors
- Added unit tests for validation, storage, confidence scoring, extraction helpers, Flask routes, and UI view-model logic

### Outbox

Personal outbound email workspace for scheduling, tracking, and monitoring email campaigns.

Focus areas:

- Next.js, React, TypeScript, and Tailwind CSS
- Express API with PostgreSQL persistence
- Redis and BullMQ background workers
- Rate limiting, retries, idempotency, and queue monitoring
- Google OAuth, Slack alerts, and Elasticsearch search

### [IdentityFlow](https://github.com/chandra23225/IdentityFlow)

Self-service identity lifecycle automation demo for Joiner, Mover, and Leaver workflows.

Focus areas:

- role-based access request flows
- approval and review logic
- audit-friendly identity lifecycle operations
- Flask/Python backend workflow design

### [Atmosfera](https://github.com/chandra23225/Atmosfera)

Interactive 3D weather globe built with Three.js, Open-Meteo, and OpenStreetMap geocoding.

Focus areas:

- browser-based 3D interaction
- live weather and geocoding APIs
- frontend state and user experience
- GitHub Pages deployment

### [F1 Multiviewer](https://github.com/chandra23225/f1-multiviewer)

Live Formula 1 dashboard for timing, standings, telemetry, and weather data.

Focus areas:

- real-time sports dashboard UI
- telemetry and session data
- JavaScript data visualization
- OpenF1-powered workflows

## Tech Stack

**Languages:** Python, JavaScript, TypeScript, SQL
**Backend:** Flask, Express, FastAPI, PostgreSQL
**Frontend:** React, Next.js, HTML, CSS, Tailwind CSS, Three.js
**AI:** Gemini API, structured extraction, decision intelligence, prompt design
**Agentic AI:** Pipecat, LLM function calling, real-time voice pipelines, VAD, WebRTC
**Data and infrastructure:** Redis, BullMQ, Elasticsearch, pandas, openpyxl, CSV/Excel workflows
**Tools:** Git, GitHub, Docker, unit testing, local development, desktop wrappers

## What I'm Building Toward

I want my work to show that I can think clearly about useful AI-backed software, not just generate small experiments.

My current direction is building systems for:

- decision memory
- workflow clarity
- enterprise automation
- local-first AI tools
- agentic voice and tool-use pipelines
- practical human review around AI outputs

The common thread across my projects is turning scattered information into something structured, searchable, and useful.

I'm still growing as an engineer, but I care a lot about understanding the problem, shaping the workflow, and building projects that make sense end-to-end.
