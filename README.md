# Vladislav Korchagin

**Backend engineer · Python & PHP.** I build LLM assistants, Telegram bots, API integrations and the automation around them. Rust for desktop tooling.

[korindustries.ru](https://korindustries.ru) · [Telegram @VLAD_K0R](https://t.me/VLAD_K0R) · Russia · open to remote work

---

### How I build

- **The model writes text, the code makes decisions.** Prices, permissions and actions come from the database. Every LLM draft passes automated checks before a person sees it.
- **Measure first.** Serving pre-rendered HTML instead of rendering on each request cut TTFB from 2.7 s to 10 ms on slow 4G.
- **Small, reversible steps.** Tests before refactoring, migrations with backups, features in thin slices.
- **AI agents as a team.** I work with Claude Code every day and review every diff myself.

### Selected work

| Project | What it does | Result | Stack |
|---|---|---|---|
| [**KORE**](https://github.com/Vladislav-Kor/kore) | Windows load console. Caps runaway background processes with Job Objects instead of killing them; live CPU/GPU/RAM charts; RAM module report with an overclock warning | v1.0, no telemetry | Rust, egui, wgpu, Win32 |
| **AI manager for Avito chats** · client work, code private | Polls marketplace chats every 30 s, drafts two reply options; the owner sends one with a single tap in Telegram | RAG over 12,000+ dialogs, voice messages via Whisper, every draft auto-checked | Python, OpenAI API, Whisper, SQLite |
| **Lead-intake bot with a local LLM** · code private | Takes requests, quotes, hands the client to the owner; skills exposed through an MCP server | Passes a 45-question automated exam before each release | aiogram 3, Ollama, MCP |
| **korindustries.ru** · code private | Business site with an admin panel, React SSR, pre-rendered pages served without PHP | First Contentful Paint 5–6 s → 1.0–1.3 s on slow 4G | Laravel 13, React 19, Docker |
| **Orbita e-lock platform** · SVIFT LLC, 2021–2025 | Web app that issues lock keys through the manufacturer's server; DPD and Yandex.Market integrations | 90 % of key operations automated, defects per release 20 → 11 | Vue 3, Yii2, MySQL, Codeception |
| [**jade-archive**](https://github.com/Vladislav-Kor/jade-archive) | Personal archive and CRM with 12+ entities | REST API + SPA, CI, architecture decision records | FastAPI, SQLAlchemy, Alembic, Vue 3, TypeScript |
| [**ttlock-api**](https://github.com/Vladislav-Kor/ttlock-api) | Smart-lock backend over the TTLock cloud API | OAuth2 tokens, passcodes, DTO and Value Objects | PHP 8, Yii2 |

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram_3-26A5E4?logo=telegram&logoColor=white)
![PHP](https://img.shields.io/badge/PHP_8-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Yii2](https://img.shields.io/badge/Yii2-0073BB)
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)

LLM: RAG with hybrid search (embeddings + word stems), tool calling, MCP servers, Ollama, Whisper.
Integrations: Avito, DPD, Yandex.Market, TTLock, Telegram Bot API, YouTube Data API.

### По-русски

Backend-разработчик на Python и PHP: AI-ассистенты, Telegram-боты, интеграции API, парсеры и автоматизация.
4+ года коммерческой разработки, с 2026 года — проекты под брендом KOR INDUSTRIES.
Сайт и портфолио — [korindustries.ru](https://korindustries.ru), связь — [Telegram @VLAD_K0R](https://t.me/VLAD_K0R).
