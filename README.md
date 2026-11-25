![header](https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=180&section=header&text=Tejas%20Lamba&fontColor=ffffff&fontSize=36&fontAlignY=38&desc=backend%20%2B%20ai%20engineer&descAlignY=58&descSize=16)

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=22&duration=2500&pause=800&color=7C3AED&center=true&vCenter=true&width=520&lines=Backend+and+AI+engineer;Forward+Deployed+Engineer+%40+CallKaro;Reverse-engineering+AI+agent+runtimes;I+ship+things+that+work)](https://git.io/typing-svg)

[![Profile views](https://komarev.com/ghpvc/?username=TejasLamba2006&color=7c3aed&style=flat-square&label=profile+views)](https://github.com/TejasLamba2006)

</div>

I build backend systems, edge AI pipelines, and developer tooling. Currently a Forward Deployed Engineer intern at CallKaro AI, where I build and debug multilingual voice agents handling live calls in 20+ languages (awarded the CEO Spot Award in Nov 2026). Before that, I wrote embedded AI firmware on STM32U5 microcontrollers and real-time NPU computer vision pipelines on the STM32MP257 at STMicroelectronics, and shipped fintech backend APIs at Rudescore. Finishing a B.Tech in CSE (AI/ML specialization, class of 2027).

I care more about knowing things deeply than having a long list of logos on my profile. That said, here are the logos.

## What I work with

<div align="center">

[![TypeScript](https://skillicons.dev/icons?i=ts)](https://www.typescriptlang.org)
[![Python](https://skillicons.dev/icons?i=py)](https://python.org)
[![C++](https://skillicons.dev/icons?i=cpp)](https://isocpp.org)
[![C](https://skillicons.dev/icons?i=c)](https://en.cppreference.com/w/c)
[![Java](https://skillicons.dev/icons?i=java)](https://www.java.com)
[![Rust](https://skillicons.dev/icons?i=rust)](https://www.rust-lang.org)
[![FastAPI](https://skillicons.dev/icons?i=fastapi)](https://fastapi.tiangolo.com)
[![NodeJS](https://skillicons.dev/icons?i=nodejs)](https://nodejs.org)
[![React](https://skillicons.dev/icons?i=react)](https://react.dev)
[![Next.js](https://skillicons.dev/icons?i=nextjs)](https://nextjs.org)
[![PyTorch](https://skillicons.dev/icons?i=pytorch)](https://pytorch.org)
[![TensorFlow](https://skillicons.dev/icons?i=tensorflow)](https://www.tensorflow.org)
[![OpenCV](https://skillicons.dev/icons?i=opencv)](https://opencv.org)
[![PostgreSQL](https://skillicons.dev/icons?i=postgres)](https://www.postgresql.org)
[![Redis](https://skillicons.dev/icons?i=redis)](https://redis.io)
[![Prisma](https://skillicons.dev/icons?i=prisma)](https://www.prisma.io)
[![Docker](https://skillicons.dev/icons?i=docker)](https://www.docker.com)
[![Linux](https://skillicons.dev/icons?i=linux)](https://www.linux.org)
[![Git](https://skillicons.dev/icons?i=git)](https://git-scm.com)

</div>

## Stuff I've built

**[swarm-page-builder](https://github.com/TejasLamba2006/swarm-page-builder)** is a Claude Code skill and zero-dependency Shadow DOM engine that snapshots a live page and deploys multiplayer LLM cursors to redraw every box, border, text node, and image from a blank screen.

**[Clementine](https://github.com/TejasLamba2006/clementine)** is a zero-click radial file converter and 29-tool offline AI/media suite written in pure Rust and Win32 (`~7.5 MB` RAM, no Electron or WebView2). Runs 275 format conversions, pure-Rust `tract-onnx` background removal, and offline WinRT OCR/redaction. Won the WeMakeDevs x Wispr Flow Challenge.

**[cc-context-diet](https://github.com/TejasLamba2006/cc-context-diet)** is a Bun PE binary patcher for Claude Code (`claude.exe`) that cuts Turn-1 prompt context bloat by 89% (from 211,672 down to 22,433 tokens) across 14 MCP servers and 454 skills without deleting a single plugin. Unpacks the embedded `.bun` modules and wires in client-side `ToolSearch` and `SkillSearch`.
[![npm](https://img.shields.io/npm/dt/cc-context-diet?style=flat-square&color=7c3aed)](https://www.npmjs.com/package/cc-context-diet)

**[cc-subagent-models](https://github.com/TejasLamba2006/cc-subagent-models)** patches Claude Code's `Agent` tool to unlock arbitrary gateway model IDs (OpenCode, DeepSeek, Qwen, GLM, Gemini) and per-call context window tags (`oc/exo-free[1m]`, `deepseek-reasoner[500k]`) so non-Claude subagents stop thrashing at the 200k autocompact fallback.
[![npm](https://img.shields.io/npm/dt/cc-subagent-models?style=flat-square&color=7c3aed)](https://www.npmjs.com/package/cc-subagent-models)

**[STM32 Edge NPU Vision & MLOps](https://github.com/TejasLamba2006/tic-tac-toe-yolo)** runs real-time YOLOv8n board perception on an STM32MP257F-DK 1.35 TOPS NPU (40.4 ms INT8 latency, 0.995 mAP@0.5, 100% cell accuracy across 449 test cells), paired with a resumable 11-stage MLOps dashboard for calibration, ST Edge AI Cloud compilation, and SSH board deployment.

**[DiabetesGuard AI](https://github.com/TejasLamba2006/DiabetesGuard-AI)** is a clinical decision support system achieving 97.78% ROC-AUC with an XGBoost classifier, SHAP explainability, and a DeepSeek V3 + FAISS RAG pipeline over clinical literature.

**[Lok Sabha Tracker](https://github.com/TejasLamba2006/lok-sabha-tracker)** is a daily LLM-verified accountability docket for all 543 Indian MPs, tracking attendance, questions asked, debates, and legislative activity.

**[depdoctor](https://github.com/TejasLamba2006/depdoctor)** checks which dependencies you can safely update. Handles npm, yarn, pnpm, and bun. Semantic versioning, major version warnings, the works. I got tired of doing this by hand so I wrote a tool for it.
[![npm](https://img.shields.io/npm/dt/depdoctor?style=flat-square&color=7c3aed)](https://www.npmjs.com/package/depdoctor)

**[discord-lavalink](https://github.com/TejasLamba2006/discord-lavalink)** is a type-safe library connecting Discord.js to Lavalink audio servers. Wrote it in 2 hours because every existing option was either untyped or overengineered. 180+ stars.

**[PokeClassifier](https://github.com/TejasLamba2006/PokeClassfier)** analyzes your face and matches you with a Pokemon. Google Cloud Vision for expression detection, Gemini for personality inference. Has Stripe integration because someone asked for premium.

**[musicxmatch-api](https://github.com/TejasLamba2006/musicxmatch-api)** is an npm wrapper for the MusixMatch API. Someone had to do it.
[![npm](https://img.shields.io/npm/dt/musicxmatch-api?style=flat-square&color=7c3aed)](https://www.npmjs.com/package/musicxmatch-api)

## Open source

Merged upstream fixes and features across AI/ML infrastructure, security, and developer tooling (60+ PRs merged in November 2026 alone):

**RAG, research, and agent runtimes (merged)**
- [LearningCircuit/local-deep-research](https://github.com/LearningCircuit/local-deep-research) (9.7k stars): 20 merged PRs (plus 46 approved in queue) across downloader egress enforcement, toast/path secret redaction, multi-header `X-Real-IP` rate limiting, CSRF disconnect handling, SQLCipher rekey skip diagnostics, 34-engine cleanup invariants, and deterministic linear-scan tests.
- [microsoft/TokenEconomizer](https://github.com/microsoft/TokenEconomizer) (8.1k stars): 10 merged PRs cutting 12,279 false loop-guard errors across 964 session traces, plus Hermes gateway/cron CWD isolation, JSONL tail-read filtering, `absent_tool` learning, and Windows launcher fixes.
- [deepset-ai/haystack](https://github.com/deepset-ai/haystack) (27.1k stars): Added danda (`U+0964`, `U+0965`) sentence boundary support so Hindi, Marathi, and Bengali documents actually split into chunks.
- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) (61k stars): Fixed stale FAQ anchor links after the Enterprise-to-AMP rename.

**SDKs, CLIs, and MCP servers (merged)**
- [marimo-team/marimo](https://github.com/marimo-team/marimo) (23.7k stars): Rejected out-of-range `--port` CLI values outside `0-65535` up front.
- [huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub) (4.1k stars): Added `diff_url` to `DiscussionWithDetails` and updated `hf discussions diff` to fetch it when inline diffs are omitted.
- [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) (6.1k stars): Stripped raw Confluence macro parameter tags from exported Markdown.
- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) (3.5k stars): Fixed Shared Drive to My Drive root copies in `copy_drive_file`.
- [haziqahmedqasmi/PeakCut](https://github.com/haziqahmedqasmi/PeakCut) (1.9k stars): 4 merged PRs covering Gemini model discovery filtering, speech-model download timeouts, live ingest slot leaks, and `X-Forwarded-For` IP spoofing.
- [heymrun/heym](https://github.com/heymrun/heym) (1.8k stars), [BistaDinesh03/critique](https://github.com/BistaDinesh03/critique) (20 merged PRs), [pgalko/BambooAI](https://github.com/pgalko/BambooAI).

**Open PRs under review**
- [vllm-project/vllm](https://github.com/vllm-project/vllm), [huggingface/transformers](https://github.com/huggingface/transformers), [Aider-AI/aider](https://github.com/Aider-AI/aider), [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy), [microsoft/TypeChat](https://github.com/microsoft/TypeChat), [Flagsmith/flagsmith](https://github.com/Flagsmith/flagsmith), [payloadcms/payload](https://github.com/payloadcms/payload), [getsentry/sentry-python](https://github.com/getsentry/sentry-python), [strands-agents/harness-sdk](https://github.com/strands-agents/harness-sdk), [dlt-hub/dlt](https://github.com/dlt-hub/dlt), [reflex-dev/reflex](https://github.com/reflex-dev/reflex), [sandbox-quantum/switch](https://github.com/sandbox-quantum/switch), [simonw/llm](https://github.com/simonw/llm), [decolua/9router](https://github.com/decolua/9router).

**Earlier**
- [Wurst7](https://github.com/Wurst-Imperium/Wurst7) (1.4k stars): 4 merged feature and bugfix PRs.

## Minecraft stuff

I run a decent chunk of my life on Minecraft servers. These are actually running in production:

- **[StopESP](https://github.com/TejasLamba2006/StopESP)**: Server-side anti-xray and anti-ESP for Paper, Folia, and Bukkit. Hidden blocks and players never leave your server.
- **[AdminWatchdog](https://github.com/TejasLamba2006/AdminWatchdog)**: Staff monitoring. Logs admin commands, gamemode changes, creative item pulls, sends alerts to Discord.
- **[AuthMeUI](https://github.com/TejasLamba2006/AuthMeUI)**: Modern popup dialogs for AuthMe authentication. No more typing passwords in chat.
- **[ChatColor3](https://github.com/TejasLamba2006/ChatColor3)**: Hex, rainbow, gradients, custom colours for Paper 26+. Fork of ChatColor2.
- **[vanilla-core](https://github.com/TejasLamba2006/vanilla-core)**: SMP plugin for PvP balance, custom mechanics, server management. Paper/Spigot 1.21.1+.
- **[InfuseSMPReloaded](https://github.com/TejasLamba2006/InfuseSMPReloaded)**: Custom SMP core.

## Awards

- CallKaro AI CEO Spot Award ("Hacking Things Up", Nov 2026) for rapid voice-agent deployments and internal security engineering.
- WeMakeDevs x Wispr Flow Challenge (Oct 2026). Winner ($100 daily prize) for Clementine.
- Fintechstico V7.0, NSUT Delhi (Consilium'26). 1st place out of 3,093 registrations (Two Strands: unified payment scam and loan default risk engine).
- CodeSlayer 2k25, NIT Delhi. 1st place out of 10,562+ teams (Due Diligence Copilot on Pathway AI + FAISS).
- Smart India Hackathon. 2nd place.
- Hack For Green Bharat. Grand finale at Microsoft.

## Certifications

<details>
<summary>Click to expand</summary>

- Cybersecurity: Threat Landscape, Foundations, Security Copilot (LinkedIn Learning)
- HackerRank: JavaScript, Node.js
- IBM: Project-based learning courses

</details>

## Stats

<div align="center">

[![GitHub Stats](https://github-stats-extended.vercel.app/api?username=TejasLamba2006&show_icons=true&theme=dark&hide_border=true&title_color=7C3AED&text_color=c9d1d9&icon_color=7C3AED&count_private=true)](https://github.com/stats-organization/github-stats-extended)

[![GitHub Streak](https://streak-stats.demolab.com?user=TejasLamba2006&theme=dark&hide_border=true&ring=7C3AED&fire=7C3AED&currStreakLabel=7C3AED)](https://git.io/streak-stats)

[![Top Langs](https://github-stats-extended.vercel.app/api/top-langs/?username=TejasLamba2006&layout=compact&theme=dark&hide_border=true&title_color=7C3AED&text_color=c9d1d9&langs_count=8)](https://github.com/stats-organization/github-stats-extended)

[![Trophies](https://github-profile-trophy.vercel.app/?username=TejasLamba2006&theme=darkhub&no-bg=true&column=4&row=2)](https://github.com/ryo-ma/github-profile-trophy)

</div>

## Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=TejasLamba2006&theme=react-dark&color=7C3AED&line=7C3AED&point=ffffff&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

## What I'm into

Open source maintenance, hackathon culture, reverse-engineering runtimes, and building tools I actually use. Lately I have been reading through AI agent runtimes and LLM tooling codebases, finding real bugs, and shipping fixes upstream. Currently exploring Rust for backend because the compiler is harsh but honest, and digging deeper into system design and database internals.

## Get in touch

<div align="center">

[![Portfolio](https://img.shields.io/badge/portfolio-tejas.is--a.dev-7c3aed?style=flat-square&logo=vercel&logoColor=white)](https://tejas.is-a.dev)
[![Email](https://img.shields.io/badge/email-tejas22feb@gmail.com-7c3aed?style=flat-square&logo=gmail&logoColor=white)](mailto:tejas22feb@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-tejaslamba-7c3aed?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tejaslamba)

</div>

---

```
$ whoami
tejas, backend + ai engineer

$ currently
FDE intern @ CallKaro AI, building & shipping

$ status
open to backend & AI roles
```

<div align="center">

![snake](https://raw.githubusercontent.com/TejasLamba2006/TejasLamba2006/output/github-snake-dark.svg#gh-dark-mode-only)
![snake](https://raw.githubusercontent.com/TejasLamba2006/TejasLamba2006/output/github-snake-light.svg#gh-light-mode-only)

</div>

![footer](https://capsule-render.vercel.app/api?type=waving&color=7C3AED&height=120&section=footer)
