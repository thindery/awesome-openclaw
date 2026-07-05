# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of OpenClaw resources, skills, tools, and example projects.

**Last updated:** July 5, 2026 • Added: 7 new tools - headroom (context compression for AI agents), jcodemunch-mcp (token-efficient code exploration), agent-skills-hub (skill directory with quality scoring), mcp-github-trending (GitHub trending data for agents), tuannvm/codex-mcp-server (Codex CLI wrapper), openrouter-mcp-server (universal model access), X MCP (X API for agents)

[OpenClaw](https://github.com/openclaw/openclaw) is an open-source framework for building AI agents that can use tools, spawn sub-agents, and coordinate complex workflows. Think of it as your AI team's operating system.

**Contributions welcome!** See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

---

## Contents

- [Official Resources](#official-resources)
- [Skills](#skills)
  - [Productivity](#productivity)
  - [Development](#development)
  - [AI & Voice](#ai--voice)
  - [Media & Content](#media--content)
  - [Data & Research](#data--research)
  - [Infrastructure](#infrastructure)
  - [Social & Community](#social--community)
  - [Finance & Markets](#finance--markets)
  - [Specialized Roles](#specialized-roles)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Example Projects](#example-projects)
- [Regional Resources](#regional-resources)
- [Community](#community)

---

## Official Resources

- [OpenClaw GitHub](https://github.com/openclaw/openclaw) - Main repository
- [Documentation](https://docs.openclaw.ai) - Official docs
- [ClawHub](https://clawhub.com) - Skill registry and discovery
- [Discord Community](https://discord.com/invite/clawd) - Get help, share skills

---

## Skills

Skills are OpenClaw's superpower - they give your agents tools to interact with the world.

### Productivity

- [claude-code-task](https://github.com/VsevolodUstinov/openclaw-skill-claude-code) - Async Claude Code task runner — delegate heavy work to Claude Code with WhatsApp progress notifications and automatic agent wake-up (16⭐) ⭐ NEW
- [openclaw-graph](https://github.com/alphaonedev/openclaw-graph) - Graph-native workspace backend using Neo4j. Replaces flat markdown files with Cypher graph directives — 316 skills across 27 clusters, sub-millisecond queries, 94% token savings (⭐ 5) ⭐ NEW
- [clawkeep](https://github.com/SuperTechGod/clawkeep) - AES-256 encrypted secrets manager for OpenClaw agents. Secure vault for API keys with machine binding, IP restriction, and bot auto-unlock ⭐ NEW
- [itdog-skill](https://github.com/Ramses1984/itdog-skill) - 🐕 Fast network diagnostics with itdog.cn - batch ping and HTTP response tracking via Clawdbot's Python skill ⭐ NEW
- [sillytavern-cards-skill](https://github.com/pearyj/sillytavern-cards-skill) - Import & roleplay with SillyTavern character cards. Chat with characters on WhatsApp, Telegram, Discord ⭐ NEW
- [openclaw-plugin-voice-chat](https://github.com/levivoelz/openclaw-plugin-voice-chat) - Voice I/O for OpenClaw — STT/TTS brackets your real agent keeping models, memory, and skills. WebSocket-based with Whisper/ElevenLabs support ⭐ NEW
- [homeassistant-assist](https://github.com/DevelopmentCats/homeassistant-assist) - Token-efficient Home Assistant skill using Assist API — natural language control without entity lookups (11⭐) ⭐ NEW
- [Meeting Agent](https://github.com/Smokefarmer/meeting-agent) - AI Meeting Assistant — transcribes, extracts action items, auto-creates GitHub issues and calendar events (Hack_001) (Mar 27)
- [cc-switch](https://github.com/farion1231/cc-switch) - Cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, openclaw & Gemini CLI (30.5k⭐) ⭐ NEW
- [obsidian-skills](https://github.com/kepano/obsidian-skills) - Agent skills for Obsidian - create/edit Markdown with wikilinks, Bases with views/filters, JSON Canvas, and Obsidian CLI integration. Compatible with Claude Code, Codex, OpenCode (⭐ 16.1k) ⭐ NEW
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Manus-style persistent markdown planning for Claude Code/OpenClaw. Structured project planning using markdown files with persistent context across sessions (⭐ 16.9k) ⭐ NEW
- [notebooklm-py](https://github.com/teng-lin/notebooklm-py) - Unofficial NotebookLM API with full programmatic access via Python, CLI, and AI agents like Claude Code, Codex, and OpenClaw (⭐ 15.6k) ⭐ NEW
- [FreeRide](https://github.com/Shaivpidadi/FreeRide) - Unlimited free AI by automatically managing OpenRouter's free models in OpenClaw ⭐ NEW
- [agent_flywheel_clawdbot_skills_and_integrations](https://github.com/Dicklesworthstone/agent_flywheel_clawdbot_skills_and_integrations) - Clawdbot skills for agentic coding workflows - ACFS stack, cloud CLIs, and dev tools (⭐ 62) ⭐ NEW
- [agent-skills (OperatingSystem-1)](https://github.com/OperatingSystem-1/agent-skills) - Reusable skills for Clawdbot agents - media processing, integrations, and automation ⭐ NEW
- [1password](https://github.com/openclaw/openclaw/tree/main/skills/1password) - Manage 1Password vault items and passwords
- [apple-notes](https://github.com/openclaw/openclaw/tree/main/skills/apple-notes) - Read and search Apple Notes on macOS
- [apple-reminders](https://github.com/openclaw/openclaw/tree/main/skills/apple-reminders) - Manage Apple Reminders on macOS
- [bear-notes](https://github.com/openclaw/openclaw/tree/main/skills/bear-notes) - Search and manage Bear notes
- [chitin](https://clawhub.com/skills/chitin) - Personality persistence for AI agents
- [cron-scheduling](https://clawhub.com/skills/cron-scheduling) - Schedule recurring tasks with cron and templates
- [clawkeep](https://github.com/SuperTechGod/clawkeep) - AES-256 encrypted secrets manager for OpenClaw agents. Secure vault for API keys with machine binding, IP restriction, and bot auto-unlock
- [cron-scheduling](https://clawhub.com/skills/cron-scheduling) - Schedule recurring tasks with cron and templates
- [credential-manager](https://clawhub.com/skills/credential-manager) - MANDATORY security foundation for OpenClaw credential management
- [daily-briefing](https://clawhub.com/skills/daily-briefing) - Warm daily briefing with weather, calendar, reminders
- [focus-deep-work](https://clawhub.com/skills/focus-deep-work) - Deep work and productivity enhancement
- [healthcheck](https://github.com/openclaw/openclaw/tree/main/skills/healthcheck) - Track water intake and sleep
- [Meeting Agent](https://github.com/Smokefarmer/meeting-agent) - AI Meeting Assistant — transcribes, extracts action items, auto-creates GitHub issues and calendar events (Hack_001) (Mar 27) ⭐ NEW
- [jasper-recall](https://clawhub.com/skills/jasper-recall) - Memory and recall system
- [microsoft-todo](https://clawhub.com/skills/microsoft-todo) - Manage Microsoft To Do tasks via the `todo` CLI
- [notion](https://github.com/openclaw/openclaw/tree/main/skills/notion) - Notion workspace integration for pages and databases
- [obsidian](https://github.com/openclaw/openclaw/tree/main/skills/obsidian) - Obsidian vault search and note management
- [outlook-email](https://clawhub.com/skills/outlook-email) - Microsoft Outlook/Live.com email client
- [qmd-skill-main](https://clawhub.com/skills/qmd-skill-main) - Local hybrid search for markdown notes and docs
- [remarkable-tablet](https://clawhub.com/skills/remarkable-tablet) - Fetch handwritten notes from reMarkable tablet
- [rescuetime](https://clawhub.com/skills/rescuetime) - Fetch productivity data from RescueTime
- [session-logs](https://github.com/openclaw/openclaw/tree/main/skills/session-logs) - Session activity logging and tracking
- [shell-scripting](https://clawhub.com/skills/shell-scripting) - Write robust, portable shell scripts
- [smart-memory](https://clawhub.com/skills/smart-memory) - Context-aware memory with dual retrieval modes
- [summarize](https://github.com/openclaw/openclaw/tree/main/skills/summarize) - Text summarization tool
- [things-mac](https://github.com/openclaw/openclaw/tree/main/skills/things-mac) - Manage Things 3 tasks on macOS
- [trello](https://github.com/openclaw/openclaw/tree/main/skills/trello) - Trello board and card management
- [topydo](https://github.com/openclaw/openclaw/tree/main/skills/topydo) - todo.txt management with dependencies and priorities
- [vector-memory-hack](https://clawhub.com/skills/vector-memory-hack) - Fast semantic search for AI agent memory files
- [workspace-manager](https://clawhub.com/skills/workspace-manager) - Workspace setup and organization assistant

### Development

- [steipete/claude-code-mcp](https://github.com/steipete/claude-code-mcp) - Claude Code as one-shot MCP server — have an agent in your agent (⭐ 1,306) ⭐ NEW
- [openclaw-master-skills](https://github.com/leoyeai/openclaw-master-skills) - Curated collection of 1209+ best OpenClaw skills — weekly updated by MyClaw.ai (⭐ 2,038) ⭐ NEW
- [win4r/OpenClaw-Skill](https://github.com/win4r/openclaw-skill) - Comprehensive agent skill with full OpenClaw integration (⭐ 311) ⭐ NEW
- [Decodo-openclaw-skill](https://github.com/Decodo/decodo-openclaw-skill) - Web scraping skill using Decodo API for any URL (⭐ 151) ⭐ NEW
- [SkillClaw](https://github.com/AMAP-ML/SkillClaw) - Let skills evolve collectively with Agentic Evolver — framework for collective skill evolution in AI agents (⭐ 2,029) ⭐ NEW
- [Gen-Verse/OpenClaw-RL](https://github.com/Gen-Verse/OpenClaw-RL) - Train any agent simply by talking — reinforcement learning for OpenClaw (⭐ 5,527) ⭐ NEW
- [vinaes/succ-openclaw](https://github.com/vinaes/succ-openclaw) - Hybrid search, knowledge graph, and structured memories plugin (⭐ 1) ⭐ NEW
- [heichaowo/openclaw-amem](https://github.com/heichaowo/openclaw-amem) - First open-source A-MEM memory plugin — agentic memory with dynamic linking & evolution (NeurIPS 2025) ⭐ NEW
- [openclaw-recall](https://github.com/Felix201209/openclaw-recall) - Persistent memory, context compression & profile visibility (⭐ 3) ⭐ NEW
- [ClawTeam-OpenClaw](https://github.com/win4r/ClawTeam-OpenClaw) - Multi-agent swarm coordination for CLI coding ⭐ NEW
- [openclaw-skill](https://github.com/brabaflow/openclaw-skill) - Complete OpenClaw documentation as a skill — 333 pages of verbatim official docs (⭐ 8) ⭐ NEW
- [skill-finder](https://github.com/yfge/skill-finder) - OpenClaw skill to discover and install agent skills from ClawHub + AgentSkill.work (⭐ 3) ⭐ NEW
- [trace-mcp](https://github.com/nikolai-vysotskyi/trace-mcp) - MCP server that replaces ~42 minutes of agent exploration with one tool call — semantic code navigation for Claude Code and Codex (89⭐) ⭐ NEW
- [coding-mcp](https://github.com/kieutrongthien/coding-mcp) - Multi-project MCP server for remote coding workflows — agents work across repos without cloning source code (June 2026) ⭐ NEW
- [forge](https://github.com/ferodrigop/forge) - Terminal MCP server for AI coding agents — spawn, manage, and monitor PTY sessions via MCP (14⭐) ⭐ NEW
- [mcp-anything](https://github.com/type-mcp/mcp-anything) - One command to turn any codebase into an MCP server (37⭐) ⭐ NEW
- [ogcode](https://github.com/prasenjeet-symon/ogcode) - Browser-native coding agent that runs entirely on your machine — plans features, executes in parallel across git branches, remembers everything. One binary, zero cloud dependencies (120⭐) ⭐ NEW
- [autohand-code-cli](https://github.com/autohandai/code-cli) - Ultra fast self-evolving coding agent that runs in your terminal (138⭐) ⭐ NEW
- [power-platform-skills](https://github.com/microsoft/power-platform-skills) - Microsoft's official Power Platform plugin marketplace for Claude Code/GitHub Copilot — reusable skills, agents, and commands for building and deploying solutions (365⭐) ⭐ NEW
- [Hermes MCP Server](https://github.com/pangtongya/hermes-mcp-server) - MCP server exposing 100+ Hermes Agent skills — web search, browser automation, code execution, GitHub, Notion, and more to any MCP-compatible AI client (June 2026) ⭐ NEW
- [SiYuan Agent MCP](https://github.com/LeenixP/siyuan-agent-mcp) - High-quality MCP server for SiYuan Note — Claude Code, OpenCode, Cursor integration for reading, searching, writing and organizing local notes (⭐ trending, June 2026) ⭐ NEW
- [Joinly.ai](https://github.com/joinly-ai/joinly) - Build real-time interactive meeting agents using MCP. Open-source connector for AI agents in browser-based video meetings (HN Show June 2026) ⭐ NEW
- [caveman](https://github.com/JuliusBrussee/caveman) - Claude Code/Codex skill that cuts ~75% of output tokens by talking like caveman — keeps full technical accuracy while reducing verbosity. HN trending June 13 (⭐ 72.8k) ⭐ NEW
- [senderkit-skills](https://github.com/senderkit/senderkit-skills) - Transactional email, SMS, push & web-push for AI agents — skills + MCP for Claude Code, Codex, Cursor with no provider lock-in (June 2026) ⭐ NEW
- [uniqent](https://github.com/RiggdAI/uniqent) - Package an AI agent's whole brain (persona, MCP stack, skills, memory, config) into one open, signed .uniqent file — install into any framework in one click (June 2026) ⭐ NEW
- [SkillClaw](https://github.com/AMAP-ML/skillclaw) - Let Skills Evolve Collectively with Agentic Evolver. Framework for collective skill evolution in AI agents (⭐ 1.8k, June 2026) ⭐ NEW
- [GenericAgent](https://github.com/lsdefine/GenericAgent) - Self-evolving agent framework. Grows skill tree from 3.3K-line seed, achieving full system control with 6x less token consumption. 9 atomic tools, real browser control, autonomous skill crystallization (⭐ 12.9k) ⭐ NEW
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Simple, composable framework to build effective agents using MCP. Implements Anthropic's "Building Effective Agents" patterns with Temporal durability, structured logging, token accounting (⭐ 8.4k) ⭐ NEW
- [pie-ai-agent](https://github.com/WiseriaAI/pie-ai-agent) - Browser-automation agent for Chrome extension. Natural-language tasks via native tool calling, scoped Skills, CDP keyboard control, confirm-before-act security. BYOK across 8 LLM providers (Claude, GPT, Gemini, DeepSeek) ⭐ NEW
- [ht-mcp](https://github.com/tedliang/ht-mcp) - Rust MCP server of headless terminal for agents. Wrapper for agentic coding tools like Claude Code, Cursor (HN Show June 2026) ⭐ NEW
- [gen-skill](https://github.com/gabriel-f-santos/gen-skill) - Interview-driven, portable Agent Skill generator for Claude Code, OpenAI Codex, and opencode. A skill that generates skills (June 2026) ⭐ NEW
- [claude-skills](https://github.com/avraltod/claude-skills) - 337 Claude Code skills for 30+ agents — engineering, marketing, product, compliance, C-level advisory, research, business operations (June 2026) ⭐ NEW
- [gen-pdf](https://github.com/gen-pdf/mcp) - MCP server enabling AI assistants to generate TeX-quality PDFs from Markdown (HN Show June 2026) ⭐ NEW
- [Zyler](https://github.com/zyler-ai/zyler) - AI agent for marketing data that doesn't hallucinate. Connects to GA, Ads, and marketing channels for insights (HN Show June 2026) ⭐ NEW
- [Portia](https://github.com/portia-ai/portia) - Open-source framework for production-ready, stateful, predictable, and authenticated AI agents (Reddit trending 2025) ⭐ NEW
- [AgentKraft](https://github.com/agentkraft/agentkraft) - Lightweight tool for building and self-hosting AI agents with voice interaction and tool actions (Reddit trending 2025) ⭐ NEW
- [Microsoft Webwright](https://github.com/microsoft/Webwright) - SOTA browser agent framework achieving 86.7% on Online-Mind2Web. Coding agent with terminal + browser — code-as-action beats coordinate prediction. Ships plugins for Claude Code, Codex, OpenClaw, Hermes (⭐ 5.4k) ⭐ NEW
- [Libretto](https://github.com/saffron-health/libretto) - Makes AI browser automations deterministic. Uses "development-time AI" — scripts are generated ahead of time as actual code you can read and control, not opaque agent behavior at runtime (⭐ 134 HN) ⭐ NEW
- [Tasker](https://automatewithtasker.com) - Open-source desktop agent for browser and OS automation. Consumer-friendly, local-first automation that clicks through UIs, copy/pastes between apps, handles messy workflows — not just APIs (HN Show) ⭐ NEW
- [openclaw-enterprise-platform](https://github.com/m-aboud/openclaw-enterprise-platform) - Enterprise platform architecture unifying cloud landing zones, GitOps, zero trust, SRE, platform engineering, and MCP agent infrastructure (⭐ 1, June 2026) ⭐ NEW
- [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) - Academic Research Skills for Claude Code: research → write → review → revise → finalize (⭐ 24.4k) ⭐ NEW
- [moltbot-skills-rank](https://github.com/Lala0Land/moltbot-skills-rank) - High-performance searchable index for Moltbot skills (Clawdbot) with auto-update and star-based ranking ⭐ NEW
- [clawdbot-channel-linq](https://github.com/joevr711/clawdbot-channel-linq) - 📱 Connect clawdbot to iMessage, RCS, and SMS using Linq API with media, reactions, and multi-account support ⭐ NEW
- [clawdbot-kakaotalk](https://github.com/ktaelectronics/clawdbot-kakaotalk) - 🦞 Connect with Clawdbot AI on KakaoTalk for seamless conversation and system control ⭐ NEW
- [Agent Recall](https://github.com/maxoyed/agent-recall) - Open-source, local memory for AI agents (SQLite/MCP). Persistent memory that survives sessions — no more explaining from scratch every morning (HN Show June 2026) ⭐ NEW
- [PolyMCP](https://github.com/polymcp/polymcp) - Framework for structuring and orchestrating MCP agents. Makes MCP server development and management easier (HN Show June 2026) ⭐ NEW
- [polymcp](https://github.com/polymcp/polymcp-py) - Turn any Python function into an MCP tool for AI agents. Zero rewriting, zero complex integration (HN Show June 2026) ⭐ NEW
- [GitMCP](https://github.com/idosal/git-mcp) - Automatic MCP server for every GitHub repo. Change github.com → gitmcp.io for instant AI context — end code hallucinations (⭐ 8.2k HN) ⭐ NEW
- [CPersona](https://github.com/Cloto-dev/CPersona) - Persistent AI memory server with 3-layer hybrid search, confidence scoring, and 16 MCP tools. MIT licensed (June 2026) ⭐ NEW
- [sqlite-memory-mcp](https://github.com/RMANOV/sqlite-memory-mcp) - SQLite-backed MCP Memory Server with WAL concurrent safety, FTS5 search, session tracking, and cross-machine bridge sync (June 2026) ⭐ NEW
- [agent-memory-mcp](https://github.com/ipiton/agent-memory-mcp) - MCP server that gives AI agents persistent memory with semantic search (⭐ 32) ⭐ NEW
- [MCPX](https://github.com/lydakis/mcpx) - Turn any MCP server into a composable CLI for agent workflows. Shell-first design with tool discovery and pipelining support (HN Show June 2026) ⭐ NEW
- [Sub-Agent MCP](https://github.com/systemgroupnet/Sub-Agent-MCP) - Production-ready MCP server for LLM delegation and sub-agent orchestration. Define agents in YAML with their own LLM, system prompt, and downstream MCP tools (⭐ 11, June 2026) ⭐ NEW
- [AWS MCP Server](https://github.com/awslabs/mcp) - Official AWS MCP server with 15,000+ API operations for AI agents. General availability May 2026 (⭐ trending) ⭐ NEW
- [MCP Manager](https://github.com/noahdun/mcp-manager) - Open-source CLI to manage MCP servers — add, remove, configure, and organize (HN Show) ⭐ NEW
- [Sub-agents MCP](https://github.com/cursor-mcp/sub-agents) - Brings Claude Code's sub-agent pattern to Cursor — task-specific specialists in isolated contexts (HN Show June 2026) ⭐ NEW
- [feishu-clawdbot-guide](https://github.com/GHOST0193/feishu-clawdbot-guide) - 🦞 Configure Clawdbot for Feishu with three simple commands — no public access needed ⭐ NEW
- [clawd-plugin-vault](https://github.com/08Tyrant31/clawd-plugin-vault) - 📁 Transform local directory into structured knowledge vault with fast semantic search and markdown support ⭐ NEW
- [ClawSpotify](https://github.com/ejatapibeda/ClawSpotify) - Free Spotify API integration skill for OpenClaw ⭐ NEW
- [CowAgent](https://github.com/zhayujie/chatgpt-on-wechat) - Super AI assistant with thinking, planning, and skill capabilities. Supports OpenClaw MCP and multi-platform (WeChat, Feishu, DingTalk, WeCom, QQ) (42.5k⭐) ⭐ NEW
- [everything-claude-code](https://github.com/affaan-m/everything-claude-code) - The agent harness performance optimization system - skills, instincts, memory, security for Claude Code (87.2k⭐) ⭐ NEW
- [awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) - Curated list of awesome Claude Skills, resources, and tools for customizing AI workflows (46k⭐) ⭐ NEW
- [context7](https://github.com/upstash/context7) - Up-to-date code documentation for LLMs and AI code editors (49.7k⭐) ⭐ NEW
- [playwright-mcp](https://github.com/microsoft/playwright-mcp) - Microsoft's official Playwright MCP server for browser automation (33.1k⭐) ⭐ NEW  
- [chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Chrome DevTools for coding agents via MCP (28.2k⭐) ⭐ NEW
- [github-mcp-server](https://github.com/github/github-mcp-server) - GitHub's official MCP Server v1.2.0 - repos, PRs, issues, actions, code search with comprehensive tool set (30.8k⭐, June 2026) ⭐ NEW
- [antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills) - Ultimate Collection of 1000+ Agentic Skills for Claude Code/Antigravity/Cursor (25.8k⭐) ⭐ NEW
- [Cq](https://blog.mozilla.ai/cq-stack-overflow-for-agents/) - Stack Overflow for AI coding agents (182⭐ HN) ⭐ NEW
- [mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) - Microsoft's open-source curriculum introducing MCP fundamentals - 12 lessons covering MCP architecture, server/client development, and real-world applications (⭐ 15.5k) ⭐ NEW
- [hexstrike-ai](https://github.com/0x4m4/hexstrike-ai) - MCP Agents running 150+ cybersecurity tools for pentesting and vulnerability discovery (7268⭐) ⭐ NEW
- [pr-agent](https://github.com/The-PR-Agent/pr-agent) - Open-source PR reviewer with AI-powered code review, auto-description, and issue handling — 11.6k stars, Apache 2.0 (11659⭐) ⭐ NEW
- [XcodeBuildMCP](https://github.com/getsentry/XcodeBuildMCP) - MCP server and CLI for iOS and macOS development tools - build, test, analyze projects (4820⭐) ⭐ NEW
- [mobile-mcp](https://github.com/mobile-next/mobile-mcp) - MCP server for mobile automation and scraping on iOS, Android, emulators, simulators (4002⭐) ⭐ NEW
- [ProofShot](https://proofshot.argil.io/) - Give AI coding agents eyes to verify the UI they build (65⭐ HN) ⭐ NEW
- [Peekaboo](https://github.com/steipete/Peekaboo) - macOS CLI and MCP server for AI agents to capture screenshots with visual Q&A (2891⭐) ⭐ NEW
- [openclaw-continuity](https://github.com/redwakame/openclaw-continuity) - Time-aware continuity, carryover, care, and follow-up for OpenClaw agents. Makes agents remember the right thing and reconnect topics after `/new` (4⭐, Jun 2026) ⭐ NEW
- [openclaw-skill](https://github.com/brabaflow/openclaw-skill) - Complete OpenClaw documentation as a skill for AI coding agents. 333 pages of verbatim official docs for Claude Code, Cursor, Codex, OpenCode (8⭐, Jun 2026) ⭐ NEW
- [Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) - MCP server for Figma layout info to AI coding agents (13,816⭐) ⭐ NEW
- [mcp-use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework for building MCP Apps (interactive widgets) and MCP Servers. TypeScript/Python SDK with inspector and cloud deployment (⭐ 10k) ⭐ NEW
- [skill-forge](https://github.com/GodModeAI2025/skill-forge) - Autonomous AI skill improvement through iterative experimentation (5⭐) ⭐ NEW
- [goal-md](https://github.com/jmilinovich/goal-md) - Goal-specification file for autonomous coding agents (24⭐ HN) ⭐ NEW
- [stata-skill](https://github.com/dylantmoore/stata-skill) - Claude Code skill for writing correct, idiomatic Stata code (26⭐) ⭐ NEW
- [oracle-skills-cli](https://github.com/Soul-Brews-Studio/oracle-skills-cli) - Install Oracle skills to Claude Code, OpenCode, Cursor, and 12+ agents (27⭐) ⭐ NEW
- [skillsctl](https://github.com/nebari-dev/skillsctl) - CLI and registry server for discovering, installing, and publishing Claude Code skills (6⭐) ⭐ NEW
- [skill-finder](https://github.com/yfge/skill-finder) - OpenClaw skill to discover and install agent skills from ClawHub + AgentSkill.work (3⭐) ⭐ NEW
- [Hunk](https://github.com/modem-dev/hunk) - Review-first terminal diff viewer for agentic coders — elegant side-by-side diffs optimized for AI coding workflows (5,281⭐, June 2026) ⭐ NEW
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) - Production-grade engineering skills for AI coding agents (59.9k⭐) ⭐ NEW
- [faire](https://github.com/jack-michaud/faire) - Eval driven Claude Code skills for quality skill development (5⭐) ⭐ NEW
- [plugin-packager](https://github.com/hummer98/plugin-packager) - Convert Claude Code skill repositories into dual-distributable packages (3⭐) ⭐ NEW
- [evals-skills](https://github.com/hamelsmu/evals-skills) - Skills for building LLM evaluations that guard against common mistakes — companion to AI Evals course (424⭐) ⭐ NEW
- [deepseek-openclaw](https://github.com/LawmakerTreasure/deepseek-openclaw) - Lightweight starter app for connecting DeepSeek models through OpenClaw with clean UI (191⭐) ⭐ NEW
- [Fabraix Playground](https://github.com/fabraix/playground) - Live environment to stress-test AI agent defenses through adversarial play with published exploits (27⭐ HN) ⭐ NEW
- [codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - High-performance code intelligence MCP server. Indexes codebases into persistent knowledge graph — 155 languages, sub-ms queries, 99% fewer tokens (⭐ 2.8k) ⭐ NEW
- [Hivekeep](https://github.com/MarlBurroW/hivekeep) - Self-hosted platform of autonomous, persistent personal AI agents. Team collaboration, memory, custom tools. One container, zero external infra ⭐ NEW
- [agent-tool](https://github.com/knewstimek/agent-tool) - MCP tool server with encoding-aware file operations, binary analysis, DAP debugger, SSH/SFTP, memory tools. Fixes tab/encoding issues in agent editors (19⭐) ⭐ NEW
- [agent-link-mcp](https://github.com/mikusnuz/agent-link-mcp) - MCP server for bidirectional AI agent collaboration. Spawn Claude, Codex, Gemini, Aider as sub-agents with Q&A flow (7⭐) ⭐ NEW
- [Index](https://github.com/lmnr-ai/index) - SOTA open-source browser agent reaching 92% on WebVoyager with Claude 3.7. Built by Laminar (June 2026) ⭐ NEW
- [Understudy](https://github.com/understudyai/understudy) - Teach desktop agents by demonstrating tasks once. Local-first, works across native apps, browser, terminal (HN Show June 2026) ⭐ NEW
- [AICTL](https://github.com/piotrwittchen/aictl) - Native AI agent for terminal and macOS, written in Rust. Fast, lightweight, integrated with system (HN Show June 2026) ⭐ NEW
- [Sentinel](https://github.com/sentinel-ai/sentinel) - Browser agent using 3x fewer tokens than alternatives. Open benchmark, multi-step flow reliability (HN Show June 2026) ⭐ NEW
- [vix](https://github.com/vix-ai/vix) - AI coding agent 50% cheaper than Claude Code using virtual filesystem minification. Stem agents for optimal cache hits (HN Show June 2026) ⭐ NEW
- [Poncho](https://github.com/ponchoai/poncho) - General agent harness built for the web. Version-controlled, local development, serverless deployment (HN Show June 2026) ⭐ NEW
- [tokensave](https://github.com/aovestdipaperino/tokensave) - Comprehensive code intelligence MCP server with 40+ tools, 30+ languages, pre-indexed semantic knowledge graphs (⭐ 150) ⭐ NEW
- [lean-ctx](https://github.com/yvgude/lean-ctx) - LeanCTX — cognitive context layer for agentic systems. 62 MCP tools, 10 read modes, up to 99% token savings (⭐ 2.3k) ⭐ NEW
- [Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers) - Convert documentation websites, GitHub repos, and PDFs into Claude AI skills with automatic conflict detection (⭐ 13.8k) ⭐ NEW
- [jcodemunch-mcp](https://github.com/jgravelle/jcodemunch-mcp) - Leading token-efficient MCP server for GitHub source code exploration via tree-sitter AST parsing (⭐ 1.9k) ⭐ NEW
- [context-mode](https://github.com/mksglu/context-mode) - Context window optimization for AI coding agents. Sandboxes tool output, 98% reduction. 15 platforms (⭐ 16.0k) ⭐ NEW
- [agent-security-scanner-mcp](https://github.com/sinewaveai/agent-security-scanner-mcp) - Security scanner MCP server with prompt injection firewall and vulnerability detection (61⭐)
- [agent-autonomy-kit](https://clawhub.com/skills/agent-autonomy-kit) - Self-directed task continuation without waiting for prompts
- [agent-council](https://clawhub.com/skills/agent-council) - Toolkit for creating autonomous AI agent councils
- [ai-auth-check](https://clawhub.com/skills/ai-auth-check) - Audit authentication flows for security vulnerabilities
- [ai-code-review](https://clawhub.com/skills/ai-code-review) - Automated code review with AI suggestions
- [ai-persona-os](https://clawhub.com/skills/ai-persona-os) - Production-grade agent OS with persona management
- [ai-quota-check](https://clawhub.com/skills/ai-quota-check) - Default quota checker for LLM API usage
- [clawhub](https://github.com/openclaw/openclaw/tree/main/skills/clawhub) - Search, install, and publish skills from ClawHub
- [codex-orchestrator](https://clawhub.com/skills/codex-orchestrator) - Monitor, control, and orchestrate background Codex sessions
- [coding-agent](https://github.com/openclaw/openclaw/tree/main/skills/coding-agent) - Spawn Codex/Claude Code for complex coding tasks
- [computer-use-1-0-1](https://clawhub.com/skills/computer-use-1-0-1) - Full desktop computer use for headless Linux servers
- [credential-manager](https://clawhub.com/skills/credential-manager) - MANDATORY security foundation for credential management
- [desktop-control](https://clawhub.com/skills/desktop-control) - Advanced desktop automation with mouse, keyboard, screenshots
- [api-gateway](https://clawhub.com/skills/api-gateway) - API gateway for third-party APIs with managed auth
- [agent-browser-stagehand](https://clawhub.com/skills/agent-browser-stagehand) - Automate web browser interactions using natural language
- [gemini](https://github.com/openclaw/openclaw/tree/main/skills/gemini) - Gemini CLI integration for AI summaries and generation
- [openclaw-ollama-proxy](https://github.com/jose-mattew/openclaw-ollama-proxy) - Fix slow Qwen3 thinking mode in OpenClaw + Ollama. Flask proxy that auto-injects think:false for instant responses ⭐ NEW
- [agentopology](https://github.com/agentopology/agentopology) - The Terraform for AI agents. Define your team once, deploy to Claude Code, OpenClaw, Cursor, Codex, Gemini, Copilot, Kiro (⭐ 83)
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Simple, composable framework to build effective agents using MCP. Implements Anthropic's "Building Effective Agents" patterns with Temporal durability (⭐ 8.4k) ⭐ NEW
- [openclaw-plugin-claude-code](https://github.com/13rac1/openclaw-plugin-claude-code) - Run Claude Code in secure, isolated Podman/Docker containers — rootless, capability-dropped, with webhook notifications (26⭐) ⭐ NEW
- [claude-code-task](https://github.com/VsevolodUstinov/openclaw-skill-claude-code) - Async Claude Code task runner — delegate heavy work with WhatsApp notifications (16⭐) ⭐ NEW
- [Claude-Team-MCP](https://github.com/shalinda-j/Claude-Team-MCP) - Multi-agent MCP coordination system for AI coding assistants with shared state (⭐ 27) ⭐ NEW
- [production-grade-mcp-agentic-system](https://github.com/FareedKhan-dev/production-grade-mcp-agentic-system) - Production-Grade MCP Server Architecture with Multi-Agent System (⭐ 45) ⭐ NEW
- [oh-my-agent](https://github.com/first-fluke/oh-my-agent) - Portable, vendor-agnostic agent harness for project-specific skills, workflows, and agent teams (⭐ 1.0k) ⭐ NEW
- [code-abyss](https://github.com/telagod/code-abyss) - Give your AI coding agent a personality. Composable persona + style + skills for Claude Code, Codex, Gemini CLI & OpenClaw (⭐ 217) ⭐ NEW
- [turbo](https://github.com/tobihagemann/turbo) - Composable dev process for agentic coding harnesses, packaged as modular skills. Sibling editions for Claude Code and Codex (⭐ 312) ⭐ NEW
- [mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) - Microsoft's open-source curriculum introducing MCP fundamentals - 12 lessons covering MCP architecture, server/client development, and real-world applications (⭐ 15.5k) ⭐ NEW
- [MetaMCP](https://github.com/metatool-ai/metamcp) - MCP Aggregator, Orchestrator, Middleware, and Gateway in one Docker container. Dynamically compose MCP servers with middleware, auth, rate limiting (⭐ 2.4k) ⭐ NEW
- [Agent-MCP](https://github.com/rinadelph/agent-mcp) - Multi-agent collaboration framework with persistent knowledge graph, real-time dashboard, and parallel agent execution. Like "Obsidian for your AI agents" (⭐ HN trending) ⭐ NEW
- [GitAgent](https://gitagent.sh) - Open standard that turns any Git repo into an AI agent. Portable agent definitions via agent.yaml, SOUL.md, SKILL.md files export to Claude Code, OpenAI Agents SDK, CrewAI, LangChain (⭐ 147 HN) ⭐ NEW
- [NexusMCP](https://github.com/aavikshit2007-ops/NexusMCP) - Modern Python framework for building MCP-native AI agents with composable skills, orchestrator DAGs, OpenTelemetry observability, and sandboxed execution (⭐ trending) ⭐ NEW
- [Neptune MCP](https://github.com/shuttle-hq/neptune-mcp) - Give your coding agents DevOps superpowers — AI-powered app deployment platform that reads code, infers infrastructure, and generates IaC for AWS deployment (HN Show June 2026) ⭐ NEW
- [MCPX](https://github.com/lydakis/mcpx) - Turn any MCP server into a composable CLI for agent workflows — shell-first design with tool discovery, pipelining, and automatic Cursor/Claude/OpenClaw config linking (HN Show June 2026) ⭐ NEW
- [Sub-Agent MCP](https://github.com/systemgroupnet/Sub-Agent-MCP) - Production-ready MCP server for LLM delegation and sub-agent orchestration — define agents in YAML with their own LLM, system prompt, and downstream MCP tools (⭐ trending, June 2026) ⭐ NEW
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Simple, composable framework to build effective agents using MCP. Implements Anthropic's "Building Effective Agents" patterns with Temporal durability (⭐ 8.4k) ⭐ NEW
- [mcp-use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework for building MCP Apps (interactive widgets) and MCP Servers. TypeScript/Python SDK with inspector and cloud deployment (⭐ 10k) ⭐ NEW
- [github](https://github.com/openclaw/openclaw/tree/main/skills/github) - GitHub CLI integration (issues, PRs, actions)
- [git-workflows](https://github.com/openclaw/openclaw/tree/main/skills/git-workflows) - Advanced git operations (rebase, bisect, worktrees)
- [markdpwn-formatter](https://clawhub.com/skills/markdown-formatter) - Format and beautify markdown documents
- [model-usage](https://github.com/openclaw/openclaw/tree/main/skills/model-usage) - Track and analyze model token usage and costs
- [nano-pdf](https://github.com/openclaw/openclaw/tree/main/skills/nano-pdf) - Document processing and PDF manipulation
- [n8n-api](https://clawhub.com/skills/n8n-api) - Operate n8n workflows via REST API
- [noopolis](https://clawhub.com/skills/noopolis) - Be a Noopolis citizen (constitution, proposals, economy)
- [oracle](https://github.com/openclaw/openclaw/tree/main/skills/oracle) - Oracle database integration and queries
- [pdf-extract](https://clawhub.com/skills/pdf-extract) - Extract text from PDFs for LLM processing
- [pdf-text-extractor](https://clawhub.com/skills/pdf-text-extractor) - Extract text from PDFs with OCR support
- [peekaboo](https://github.com/openclaw/openclaw/tree/main/skills/peekaboo) - Screen/window peeking and capture
- [playwright-cli-2](https://clawhub.com/skills/playwright-cli-2) - Browser automation via Playwright
- [pptx](https://clawhub.com/skills/pptx) - PowerPoint (.pptx) file handling and manipulation
- [project-orchestrator](https://clawhub.com/skills/project-orchestrator) - AI agent orchestrator with Neo4j knowledge graph
- [prompts-workflow](https://clawhub.com/skills/prompts-workflow) - Automated workflow for collecting and publishing prompts
- [recursive-self-improvement](https://clawhub.com/skills/recursive-self-improvement) - Auto-detect errors and fix or continuously optimize
- [sag](https://github.com/openclaw/openclaw/tree/main/skills/sag) - Semantic agent gateway for tool orchestration
- [security-audit-toolkit](https://clawhub.com/skills/security-audit-toolkit) - Comprehensive security scanning toolkit
- [security-auditor](https://github.com/openclaw/openclaw/tree/main/skills/security-auditor) - Code security reviews and OWASP checks
- [skill-creator](https://github.com/openclaw/openclaw/tree/main/skills/skill-creator) - Build and package new skills
- [skillscanner](https://clawhub.com/skills/skillscanner) - Security scanner for ClawHub skills
- [skill-search](https://clawhub.com/skills/skill-search) - Search, discover, and dynamically load skills
- [slack](https://github.com/openclaw/openclaw/tree/main/skills/slack) - Slack workspace integration and messaging
- [reflect](https://clawhub.com/skills/reflect) - Self-improvement through conversation analysis and learning extraction
- [self-improving-agent](https://clawhub.com/skills/self-improving-agent) - Capture learnings and errors for continuous improvement
- [parallel-agents](https://clawhub.com/skills/parallel-agents) - Dispatch multiple subagents for independent tasks simultaneously
- [sql-toolkit](https://clawhub.com/skills/sql-toolkit) - Query, design, migrate SQL databases
- [tmux](https://github.com/openclaw/openclaw/tree/main/skills/tmux) - Terminal multiplexer session management
- [tunneling](https://clawhub.com/skills/tunneling) - Create free SSH tunnels to expose local ports
- [video-frames](https://github.com/openclaw/openclaw/tree/main/skills/video-frames) - Extract and analyze video frames
- [voice-call](https://github.com/openclaw/openclaw/tree/main/skills/voice-call) - Voice calling capabilities and management
- [wacli](https://github.com/openclaw/openclaw/tree/main/skills/wacli) - WhatsApp CLI integration and messaging
- [weather](https://github.com/openclaw/openclaw/tree/main/skills/weather) - Weather information and forecasts
- [vector-mcp](https://github.com/knuckles-team/vector-mcp) - Vector MCP Server for AI Agents - supports ChromaDB, Couchbase, MongoDB, Qdrant, and PGVector (⭐ 10) ⭐ NEW
- [agentos-mcp](https://github.com/Roxmix/agentos-mcp) - Persistent Cognitive Layer for AI Agents — MCP Server with memory, goals, reflection, and autonomous daemon ⭐ NEW
- [Continuum](https://github.com/redstone-md/Continuum) - Persistent, multi-agent MCP server giving AI coding agents a shared, live view of a codebase with memory that survives across sessions ⭐ NEW
- [remnote-cli](https://github.com/robert7/remnote-cli) - RemNote knowledge base integration via RemNote Bridge for MCP & OpenClaw (2⭐) ⭐ NEW
- [openclaw-selfdocs](https://github.com/arleyGuoLei/openclaw-selfdocs) - Embeds essential OpenClaw knowledge directly into agent context for faster assistance ⭐ NEW
- [oh-my-agent](https://github.com/first-fluke/oh-my-agent) - Structural harness for AI agents in real projects with clarification protocols and context budgets (3⭐ HN) ⭐ NEW
- [solutions-architect-skills](https://github.com/shadowX4fox/solutions-architect-skills) - Professional architecture documentation workflow for Claude Code (18⭐) ⭐ NEW
- [obsidian-claude-plugins](https://github.com/jlaska/obsidian-claude-plugins) - Obsidian vault integration skills for Claude Code (12⭐) ⭐ NEW
- [browserclaw-agent](https://github.com/idan-rubin/browserclaw-agent) - AI browser automation conductor — type a prompt, watch it happen live, get a reusable skill (⭐ 7) ⭐ NEW
- [gecko-agent](https://github.com/Gecko51/gecko-agent) - AI-powered agentic browser automation assistant (⭐ 16) ⭐ NEW

### Media & Content

- [ai-ppt-generate](https://clawhub.com/skills/ai-ppt-generate) - Intelligent PowerPoint generation tool
- [ai-video-gen](https://github.com/openclaw/openclaw/tree/main/skills/ai-video-gen) - End-to-end AI video generation pipeline
- [ai-video-gen-tools](https://clawhub.com/skills/ai-video-gen-tools) - AI video generation with multiple providers
- [antigravity-image](https://clawhub.com/skills/antigravity-image) - Antigravity Image Generator
- [blrd](https://clawhub.com/skills/blrd) - X/Twitter CLI for reading, searching, and posting
- [bottube](https://clawhub.com/skills/bottube) - BoTTube video sharing platform for AI agents
- [canvas](https://github.com/openclaw/openclaw/tree/main/skills/canvas) - Control node canvases for UI rendering and automation
- [camsnap](https://github.com/openclaw/openclaw/tree/main/skills/camsnap) - Camera capture and image processing
- [clawcamera](https://clawhub.com/skills/clawcamera) - Camera capture and image processing
- [demo-video](https://clawhub.com/skills/demo-video) - Demo video creator
- [deepresearchwork](https://clawhub.com/skills/deepresearchwork) - Comprehensive AI research framework
- [dreaming](https://clawhub.com/skills/dreaming) - Creative exploration during quiet hours
- [elevenlabs-tts](https://github.com/openclaw/openclaw/tree/main/skills/elevenlabs-tts) - Premium text-to-speech with emotional tags
- [elevenlabs-transcribe](https://clawhub.com/skills/elevenlabs-transcribe) - Transcribe audio to text using ElevenLabs Scribe
- [ffmpeg-video-editor](https://clawhub.com/skills/ffmpeg-video-editor) - Video editing with FFmpeg
- [gemini-image-gen](https://clawhub.com/skills/gemini-image-gen) - Generate and edit images via Google Gemini API
- [banana-claws](https://github.com/snowcrab-dev/banana-claws) - OpenRouter image generation skill with queue-first workflow ⭐ NEW
- [mp4-to-mp3-extractor](https://github.com/wangminrui2022/mp4-to-mp3-extractor) - Batch extract MP3 audio from MP4 videos using FFmpeg - simple CLI tool for OpenClaw (⭐ 1.8k) ⭐ NEW
- [gemini-nano-banana-pro-portraits](https://clawhub.com/skills/gemini-nano-banana-pro-portraits) - Portrait generation with Gemini Nano Banana Pro
- [gifgrep](https://github.com/openclaw/openclaw/tree/main/skills/gifgrep) - Search and manage GIFs from Giphy
- [image-cog](https://clawhub.com/skills/image-cog) - Image cognition and analysis
- [kokoro-tts](https://github.com/openclaw/openclaw/tree/main/skills/kokoro-tts) - Free local TTS engine
- [marketing-promo-video](https://clawhub.com/skills/marketing-promo-video) - Marketing promotional video creation
- [molty-pics](https://clawhub.com/skills/molty-pics) - Image-first social feed for OpenClaw bots
- [nano-banana-pro](https://github.com/openclaw/openclaw/tree/main/skills/nano-banana-pro) - Advanced image generation and editing
- [nano-banana-korean-rendering](https://clawhub.com/skills/nano-banana-korean-rendering) - Accurate rendering of non-Latin text (Korean, Japanese, Chinese) in AI images
- [openai-image-gen](https://github.com/openclaw/openclaw/tree/main/skills/openai-image-gen) - AI image generation via OpenAI DALL-E
- [piper-tts](https://clawhub.com/skills/piper-tts) - Local TTS using Piper ONNX voices (fast, private, no cloud)
- [qwen-image](https://clawhub.com/skills/qwen-image) - Generate images using Qwen Image API (Alibaba Cloud DashScope)
- [remotion-video-toolkit](https://clawhub.com/skills/remotion-video-toolkit) - Video creation toolkit with Remotion
- [sherpa-onnx-tts](https://github.com/openclaw/openclaw/tree/main/skills/sherpa-onnx-tts) - Local text-to-speech using Sherpa ONNX
- [sora-video-gen](https://clawhub.com/skills/sora-video-gen) - Sora video generation
- [table-image-generator](https://clawhub.com/skills/table-image-generator) - Generate clean table images from data
- [veo](https://clawhub.com/skills/veo) - Google Veo video generation
- [video-agent](https://clawhub.com/skills/video-agent) - Video agent automation
- [video-cog](https://clawhub.com/skills/video-cog) - Video cognition and analysis
- [video-subtitles](https://clawhub.com/skills/video-subtitles) - Video subtitle generation
- [x-publisher](https://github.com/openclaw/openclaw/tree/main/skills/x-publisher) - Publish posts to X/Twitter
- [youtube-transcript](https://clawhub.com/skills/youtube-transcript) - YouTube transcript extraction
- [mp4-to-mp3-extractor](https://github.com/wangminrui2022/mp4-to-mp3-extractor) - Batch extract MP3 audio from MP4 videos using FFmpeg ⭐ NEW

- [PinchBench](https://github.com/pinchbench/skill) - PinchBench is a benchmarking system for evaluating LLM models as OpenClaw coding agents. Made with 🦀 by the humans at https://kilo.ai (⭐ 1.2k, May 2026) ⭐ NEW
- [Rewire](https://github.com/farah-boukadida/rewire) - Design custom AI agents that automate daily work tasks by creating ready-to-run Claude Code projects tailored to your workflow (⭐ NEW, May 2026) ⭐ NEW
- [Thoth](https://github.com/siddsachar/Thoth) - Personal AI Sovereignty. Local-first AI assistant with personal knowledge graph, voice, vision, shell, browser automation, scheduled tasks, health tracking, and messaging (⭐ 1.1k, May 2026) ⭐ NEW
- [rocketride-server](https://github.com/rocketride-org/rocketride-server) - High-performance AI pipeline engine with a C++ core and 50+ Python-extensible nodes. Build, debug, and scale LLM workflows with 13+ model providers, 8+ vector databases, and agent orchestration (⭐ 2.9k, May 2026) ⭐ NEW
- [SolanaClawd](https://github.com/x402agent/solana-clawd) - Open-source Solana AI agent framework — Claude Code architecture × Solana. MCP-native, no private key required (⭐ 19, May 2026) ⭐ NEW
- [xcode-claw](https://github.com/millon3720/xcode-claw) - Manage iOS and macOS projects using natural language to build, test, archive, and control Xcode and Apple toolchain commands efficiently (⭐ 1, May 2026) ⭐ NEW
- [kalshi-claw-skill](https://github.com/paah11/kalshi-claw-skill) - Enable trading and position tracking on regulated US prediction markets using Kalshi with OpenClaw and LLM-powered market analysis (⭐ NEW, May 2026) ⭐ NEW
- [deepseek-claw](https://github.com/Ksalazar29/deepseek-claw) - Enable natural language control of DeepSeek API for chat, reasoning, code generation, multi-turn dialogs, and streaming responses via OpenClaw interface (⭐ NEW, May 2026) ⭐ NEW
- [clisbot](https://github.com/longbkit/clisbot) - Agentic Coding CLI & chat bot (⭐ 57, May 2026) ⭐ NEW

### AI & Voice

- [openai-whisper](https://github.com/openclaw/openclaw/tree/main/skills/openai-whisper) - Local speech-to-text with OpenAI Whisper
- [openai-whisper-api](https://github.com/openclaw/openclaw/tree/main/skills/openai-whisper-api) - Speech-to-text via OpenAI API
- [piper-tts](https://clawhub.com/skills/piper-tts) - Local TTS using Piper ONNX voices (fast, private, no cloud)
- [sapi-tts](https://clawhub.com/skills/sapi-tts) - Windows SAPI5 text-to-speech with Neural voices
- [speech-to-text](https://clawhub.com/skills/speech-to-text) - Transcribe audio with Whisper models via inference.sh CLI
- [ai-music-generation](https://clawhub.com/skills/ai-music-generation) - Generate AI music and songs with Diffrythm, Tencent Song Generation
- [conversation-summary-api](https://clawhub.com/skills/conversation-summary-api) - Generate conversation summaries with incremental updates
- [engram](https://github.com/NanoFlow-io/engram) - Hybrid long-term memory plugin — SQLite+FTS5 for structured facts, LanceDB for semantic recall (119⭐) ⭐ NEW
- [voice-skill-sip](https://github.com/nia-agent-cyber/openai-voice-skill) - Voice skill for AI agents with sub-200ms latency via native SIP ⭐ NEW
- [sillytavern-cards-skill](https://github.com/pearyj/sillytavern-cards-skill) - OpenClaw skill for importing & roleplaying with SillyTavern character cards. Chat with your favorite characters on WhatsApp, Telegram, Discord (3⭐) ⭐ NEW
- [openclaw-plugin-voice-chat](https://github.com/levivoelz/openclaw-plugin-voice-chat) - Voice I/O for OpenClaw — STT/TTS brackets your real agent so it keeps its models, memory, and skills. WebSocket-based with OpenAI Whisper/ElevenLabs support (TypeScript, May 2026) ⭐ NEW

### Data & Research

- [TrendRadar](https://github.com/sansan0/TrendRadar) - AI-driven public opinion & trend monitor with multi-platform aggregation, RSS, and smart alerts (49.3k⭐) ⭐ NEW
- [nole](https://github.com/dorukardahan/nole) - Free local web search router for AI agents. Go CLI + MCP with BYOK/free-first routing, keyless fallback, and multi-agent support (2⭐, June 2026) ⭐ NEW
- [Agent Workforce](https://github.com/AgentWorkforce/skills) - Multi-agent skills collection with Agent Relay orchestration patterns, workflow DAGs, and swarm patterns for Claude/Codex/OpenClaw (1⭐, June 2026) ⭐ NEW
- [my-training-data](https://github.com/ShanksChen/my-training-data) - Automated training data pipeline from Intervals.icu for AI coaching analysis with ACWR, monotony, and phase detection metrics (⭐ 4.2k) ⭐ NEW
- [notebooklm-py](https://github.com/teng-lin/notebooklm-py) - Unofficial NotebookLM API and agentic skill with full programmatic access via Python, CLI, and AI agents like Claude Code, Codex, and OpenClaw ⭐ NEW
- [ai-diff-summary](https://clawhub.com/skills/ai-diff-summary) - Summarize git diffs in plain English
- [apewisdom](https://github.com/openclaw/openclaw/tree/main/skills/apewisdom) - Reddit stock sentiment tracking
- [blogwatcher](https://github.com/openclaw/openclaw/tree/main/skills/blogwatcher) - Monitor and track blog/RSS feeds
- [conclave-testnet](https://clawhub.com/skills/conclave-testnet) - Collaborative idea game for AI agents
- [my-training-data](https://github.com/ShanksChen/my-training-data) - Automated training data pipeline from Intervals.icu for AI coaching analysis with ACWR, monotony, and phase detection metrics ⭐ NEW
- [deepresearchwork](https://clawhub.com/skills/deepresearchwork) - Comprehensive research framework with web search
- [exa-search](https://clawhub.com/skills/exa-search) - Exa (exa.ai) search API for web and neural search
- [firecrawl](https://github.com/openclaw/openclaw/tree/main/skills/firecrawl) - Web scraping via Firecrawl API
- [firecrawl-skills](https://clawhub.com/skills/firecrawl-skills) - Web scraping and crawling via Firecrawl
- [google-analytics-api](https://clawhub.com/skills/google-analytics-api) - Google Analytics API with managed OAuth
- [goplaces](https://github.com/openclaw/openclaw/tree/main/skills/goplaces) - Local business and place search
- [landing-page-generator](https://clawhub.com/skills/landing-page-generator) - Generate high-converting landing pages
- [lead-gen-website](https://clawhub.com/skills/lead-gen-website) - Build complete local lead generation websites
- [local-places](https://github.com/openclaw/openclaw/tree/main/skills/local-places) - Find nearby businesses and services
- [market-pulse](https://github.com/openclaw/openclaw/tree/main/skills/market-pulse) - Market data, crypto, DeFi yields
- [parallel-deep-research](https://clawhub.com/skills/parallel-deep-research) - Multi-source research via Parallel API
- [proactive-agent-1-2-4](https://clawhub.com/skills/proactive-agent-1-2-4) - Transform agents from task-followers to proactive initiators
- [prospector](https://clawhub.com/skills/prospector) - Prospecting and lead generation
- [reddit-insights](https://github.com/openclaw/openclaw/tree/main/skills/reddit-insights) - Reddit trend analysis and market research
- [reddit-readonly](https://clawhub.com/skills/reddit-readonly) - Browse Reddit without authentication
- [self-improving-agent](https://clawhub.com/skills/self-improving-agent) - Capture learnings and errors for continuous improvement
- [startups](https://github.com/openclaw/openclaw/tree/main/skills/startups) - Startup ecosystem research
- [travel-manager](https://clawhub.com/skills/travel-manager) - Comprehensive travel planning and booking
- [twitter-u7c](https://github.com/openclaw/openclaw/tree/main/skills/twitter-u7c) - X/Twitter monitoring and trends
- [valyu-search](https://clawhub.com/skills/valyu-search) - Web search, content extraction, answers, and DeepResearch via Valyu

- [web-search-2](https://clawhub.com/skills/web-search-2) - Web search with Tavily and Exa via inference.sh CLI
- [yahoo-finance](https://github.com/openclaw/openclaw/tree/main/skills/yahoo-finance) - Yahoo Finance data integration

### Infrastructure

- [MacClaw](https://github.com/Habib112233/MacClaw) - macOS global hotkey client for OpenClaw — Spotlight-style quick access without switching apps (1⭐) ⭐ NEW
- [pizero-openclaw](https://github.com/Edu069/pizero-openclaw) - Voice-controlled AI assistant on Raspberry Pi Zero W with speech transcription and LCD display (1⭐) ⭐ NEW
- [picoclaw](https://github.com/sipeed/picoclaw) - Tiny, Fast, and Deployable anywhere — automate the mundane, unleash your creativity (22,889⭐) ⭐ NEW
- [agent-browser](https://github.com/vercel-labs/agent-browser) - Browser automation CLI for AI agents by Vercel Labs (19,929⭐) ⭐ NEW
- [google-workspace-cli](https://github.com/googleworkspace/cli) - One CLI for Drive, Gmail, Calendar, Sheets, Docs, Chat with AI agent skills (15,952⭐) ⭐ NEW
- [openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) - AI Agent Orchestration Dashboard - manage agents via OpenClaw Gateway (1,748⭐) ⭐ NEW
- [spacebot](https://github.com/spacedriveapp/spacebot) - AI agent for teams, communities, and multi-user environments (1,621⭐) ⭐ NEW
- [mission-control](https://github.com/crshdn/mission-control) - AI Agent Orchestration Dashboard for multi-agent collaboration (1,233⭐) ⭐ NEW
- [picoclaw](https://github.com/sipeed/picoclaw) - Tiny, fast OpenClaw deployment — automate the mundane, deploy anywhere. Minimal resource requirements for edge devices (⭐ 22.9k) ⭐ NEW
- [openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) - AI Agent Orchestration Dashboard - manage agents via OpenClaw Gateway with multi-agent support (⭐ 1,748) ⭐ NEW
- [agent-infra/sandbox](https://github.com/agent-infra/sandbox) - All-in-One Sandbox for AI Agents combining Browser, Shell, File, MCP and VSCode Server for secure execution (⭐ 3,115) ⭐ NEW
- [jinn](https://github.com/hristo2612/jinn) - Lightweight AI gateway daemon orchestrating Claude Code, Codex, and Antigravity CLI with routing, scheduling, connectors. Works with Max subscription (⭐ 130) ⭐ NEW
- [brow](https://github.com/detrin/brow) - Standalone Playwright CLI for AI agent browser automation - control real Chromium with simple commands (⭐ 2) ⭐ NEW
- [agent-browser (smouj)](https://github.com/smouj/agent-browser) - Give any AI agent a real browser. REST API + Web Dashboard + Vision AI. Control browsers via Playwright ⭐ NEW
- [pie-ai-agent](https://github.com/WiseriaAI/pie-ai-agent) - Browser-automation agent for Chrome — natural-language tasks with native tool calling, scoped Skills, CDP keyboard control ⭐ NEW
- [clawhost](https://github.com/bfzli/clawhost) - One-click OpenClaw deployment platform (178⭐)
- [plandex](https://github.com/plandex-ai/plandex) - Open source AI coding agent for large projects (15058⭐) ⭐ NEW
- [claude-squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents (6240⭐) ⭐ NEW
- [superset](https://github.com/superset-sh/superset) - IDE for AI Agents Era - Run army of Claude Code, Codex locally (5452⭐) ⭐ NEW  
- [oh-my-pi](https://github.com/can1357/oh-my-pi) - AI coding agent for terminal with hash-anchored edits (1726⭐) ⭐ NEW
- [emdash](https://github.com/generalaction/emdash) - Agentic Development Environment (YC W26) - Run agents in parallel (2409⭐) ⭐ NEW
- [agent-infra/sandbox](https://github.com/agent-infra/sandbox) - All-in-One Sandbox for AI Agents combining Browser, Shell, File, MCP and VSCode Server (3115⭐) ⭐ NEW
- [openclaw-metacognitive-suite](https://github.com/haneenbassiony26/openclaw-metacognitive-suite) - Enable agents to autonomously learn, remember, reflect, and adapt using composable meta-cognitive plugins (1⭐) ⭐ NEW
- [openclaw-min-bundle](https://github.com/CyberJhay/openclaw-min-bundle) - Run OpenClaw Gateway with systemd user service, auto-fix crashes, enable Codex deep web search (0⭐) ⭐ NEW
- [openclaw-ani-installer](https://github.com/wzfukui/openclaw-ani-installer) - Installer and updater for the ANI plugin on OpenClaw (1⭐) ⭐ NEW
- [gitcrawl](https://github.com/openclaw/gitcrawl) - Local-first GitHub issue and pull request crawler for maintainer triage (54⭐, May 2026) ⭐ NEW
- [cerone-openclaw-plugin](https://github.com/AnantDhavale/cerone-openclaw-plugin) - Cerone plugin that validates tool calls before execution using before_tool_call hook (May 2026) ⭐ NEW
- [plandex](https://github.com/plandex-ai/plandex) - Open source AI coding agent for large projects (15058⭐) ⭐ NEW
- [claude-squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents (6240⭐) ⭐ NEW
- [superset](https://github.com/superset-sh/superset) - IDE for AI Agents Era - Run army of Claude Code, Codex locally (5452⭐) ⭐ NEW  
- [oh-my-pi](https://github.com/can1357/oh-my-pi) - AI coding agent for terminal with hash-anchored edits (1726⭐) ⭐ NEW
- [emdash](https://github.com/generalaction/emdash) - Agentic Development Environment (YC W26) - Run agents in parallel (2409⭐) ⭐ NEW
- [agent-infra/sandbox](https://github.com/agent-infra/sandbox) - All-in-One Sandbox for AI Agents combining Browser, Shell, File, MCP and VSCode Server (3115⭐) ⭐ NEW
- [openclaw-metacognitive-suite](https://github.com/haneenbassiony26/openclaw-metacognitive-suite) - Enable agents to autonomously learn, remember, reflect, and adapt using composable meta-cognitive plugins (1⭐) ⭐ NEW
- [openclaw-min-bundle](https://github.com/CyberJhay/openclaw-min-bundle) - Run OpenClaw Gateway with systemd user service, auto-fix crashes, enable Codex deep web search (0⭐) ⭐ NEW
- [clawcontrol](https://github.com/IUDU5/clawcontrol) - Simple CLI/TUI tool to automate VPS provisioning and OpenClaw setup with secure Tailscale access (1⭐, May 2026) ⭐ NEW
- [browserclaw](https://github.com/Marashumpo/browserclaw) - Browser automation library using typed refs for reliable element targeting without CSS/XPath - AI-friendly snapshot-based approach (1⭐, May 2026) ⭐ NEW
- [openclaw-ani-installer](https://github.com/wzfukui/openclaw-ani-installer) - Installer and updater for the ANI plugin on OpenClaw (1⭐) ⭐ NEW
- [blucli](https://github.com/openclaw/openclaw/tree/main/skills/blucli) - Bluetooth device management and control
- [clawdbot-logs](https://clawhub.com/skills/clawdbot-logs) - Analyze Clawdbot performance, response times, errors
- [clawddocs-1-2-2](https://clawhub.com/skills/clawddocs-1-2-2) - Clawdbot documentation expert
- [cloudflare-dns-updater](https://clawhub.com/skills/cloudflare-dns-updater) - Create or update proxied Cloudflare DNS A records
- [cloudflare-gen](https://github.com/openclaw/openclaw/tree/main/skills/cloudflare-gen) - Cloudflare Workers configuration
- [credential-manager](https://clawhub.com/skills/credential-manager) - MANDATORY security foundation for credential management
- [domain-dns-ops](https://github.com/openclaw/openclaw/tree/main/skills/domain-dns-ops) - Domain and DNS management
- [eightctl](https://github.com/openclaw/openclaw/tree/main/skills/eightctl) - Eight Sleep mattress control and monitoring
- [file-search](https://clawhub.com/skills/file-search) - Fast file search using fd and ripgrep
- [firecracker](https://clawhub.com/skills/firecracker) - AWS Firecracker microVM management
- [google-play](https://clawhub.com/skills/google-play) - Google Play Developer API integration
- [log-tail](https://clawhub.com/skills/log-tail) - Real-time log file monitoring
- [log-tail-systemd](https://clawhub.com/skills/log-tail-systemd) - Stream logs from systemd journal (journalctl wrapper)
- [mcporter](https://github.com/openclaw/openclaw/tree/main/skills/mcporter) - Minecraft server management tools
- [netlify](https://github.com/openclaw/openclaw/tree/main/skills/netlify) - Netlify site management and CI/CD
- [openclaw-auto-updater](https://clawhub.com/skills/openclaw-auto-updater) - Safe scheduled auto-updater for skills
- [openclaw-security-monitor](https://clawhub.com/skills/openclaw-security-monitor) - Real-time security monitoring
- [openclaw-server-secure-skill](https://clawhub.com/skills/openclaw-server-secure-skill) - Secure server configuration
- [security-audit](https://github.com/openclaw/openclaw/tree/main/skills/security-audit) - Infrastructure security scanning
- [AgentShield](https://github.com/Kanevry/openclaw-agentshield) - Real-time AI Agent Security Plugin — Prompt injection defense, tool call guardrails, live security dashboard (Mar 27) ⭐ NEW
- [Nango](https://github.com/nangoHQ/nango) - Build product integrations with AI. Connect agents to 800+ APIs with managed OAuth, token refresh, and proxy execution. Self-hostable with SOC 2/GDPR compliance (⭐ 9.3k trending) ⭐ NEW
- [AWS MCP Server](https://github.com/awslabs/mcp) - Official AWS MCP server with 15,000+ API operations for AI agents. GA May 2026 (⭐ trending) ⭐ NEW


- [VAEN](https://github.com/sjhalani7/vaen) - Package and import portable AI coding harnesses as .agent files. Bundle instructions, skills, MCP config across repos and teams without copy-paste (HN Show May 28) ⭐ NEW
- [rmux](https://github.com/helveSec/rmux) - Programmable terminal multiplexer with Playwright-style SDK for AI agents — spawn, control, automate terminals (180⭐ HN) ⭐ NEW
- [Commandable MCP](https://github.com/commandable/commandable-mcp) - Dynamic tool registration for MCP — agents create targeted tools on the fly without context bloat (5⭐ HN) ⭐ NEW
- [AWS MCP Server](https://github.com/awslabs/mcp) - Official AWS MCP server with 15,000+ API operations for AI agents (GA May 2026) ⭐ NEW
- [skill-guard](https://clawhub.com/skills/skill-guard) - Skill security vetting and validation
- [ssh-exec](https://clawhub.com/skills/ssh-exec) - Run commands on remote Tailscale nodes
- [ssh-tunnel](https://clawhub.com/skills/ssh-tunnel) - SSH tunneling and port forwarding
- [tunneling](https://clawhub.com/skills/tunneling) - Create free SSH tunnels to expose local ports
- [vercel](https://github.com/openclaw/openclaw/tree/main/skills/vercel) - Deploy and manage Vercel projects

### Smart Home & IoT

- [ClawSpotify](https://github.com/ejatapibeda/ClawSpotify) - Free Spotify API integration skill for OpenClaw
- [openhue](https://github.com/openclaw/openclaw/tree/main/skills/openhue) - Philips Hue smart lighting control
- [sonoscli](https://github.com/openclaw/openclaw/tree/main/skills/sonoscli) - Sonos speaker system control
- [spotify-player](https://github.com/openclaw/openclaw/tree/main/skills/spotify-player) - Spotify music playback control
- [songsee](https://github.com/openclaw/openclaw/tree/main/skills/songsee) - Song and music discovery

### Social & Community

- [bird](https://github.com/openclaw/openclaw/tree/main/skills/bird) - Bluesky social media integration
- [bluebubbles](https://github.com/openclaw/openclaw/tree/main/skills/bluebubbles) - iMessage integration via BlueBubbles server
- [browser](https://github.com/openclaw/openclaw/tree/main/skills/browser) - Web browser automation via Playwright
- [discord](https://github.com/openclaw/openclaw/tree/main/skills/discord) - Discord server management and bot features
- [discord-voice](https://github.com/openclaw/openclaw/tree/main/skills/discord-voice) - Real-time voice in Discord channels
- [himalaya](https://github.com/openclaw/openclaw/tree/main/skills/himalaya) - Email management via Himalaya CLI
- [imsg](https://github.com/openclaw/openclaw/tree/main/skills/imsg) - macOS Messages app integration
- [message](https://github.com/openclaw/openclaw/tree/main/skills/message) - Send messages across Discord, Telegram, Slack, WhatsApp, Signal

### Finance & Markets

- [OpenMobius-skill](https://github.com/MobiusQuant/OpenMobius-skill) - ICT/SMC trading-knowledge skill with 964 curated knowledge cards, real-time market data, technical indicators, and chart generation (283⭐) ⭐ NEW
- [Agent-Layer](https://github.com/lopushok9/Agent-Layer) - Finance infrastructure for AI agents with MCP support - banking, payments, portfolio aggregation (1⭐) ⭐ NEW
- [finclaw](https://github.com/NeuZhou/finclaw) - AI-Powered Financial Intelligence Engine with 8 Master Strategies, 3 Markets, 227 Tests. Verified +29.1% annual alpha (⭐ 4⭐) ⭐ NEW
- [Driggsby](https://driggsby.com) - Securely chat with your finances via MCP - aggregates financial data from Plaid (HN Show) ⭐ NEW

- [apex-trading](https://clawhub.com/skills/apex-trading) - Apex trading and analysis
- [binance](https://clawhub.com/skills/binance) - Binance trading integration
- [binance-pro](https://clawhub.com/skills/binance-pro) - Professional Binance trading
- [billclaw](https://github.com/fire-zu/billclaw) - Bank transaction and bill data import
- [changenow](https://clawhub.com/skills/changenow) - ChangeNOW crypto exchange
- [clawnance](https://clawhub.com/skills/clawnance) - Simulated crypto trading arena for AI agents
- [crypto-agent-payments](https://clawhub.com/skills/crypto-agent-payments) - Crypto wallets and payments for AI agents
- [crypto-levels](https://clawhub.com/skills/crypto-levels) - Analyze crypto support and resistance levels
- [crypto-price](https://clawhub.com/skills/crypto-price) - Cryptocurrency price tracking
- [fairscale-solana](https://clawhub.com/skills/fairscale-solana) - Check Solana wallet reputation
- [kalshi-claw-skill](https://github.com/paah11/kalshi-claw-skill) - Enable trading and position tracking on regulated US prediction markets using Kalshi with OpenClaw and LLM-powered market analysis (⭐ NEW, May 2026) ⭐ NEW
- [market-pulse](https://github.com/openclaw/openclaw/tree/main/skills/market-pulse) - Market data, crypto, DeFi yields
- [solana-wallet](https://clawhub.com/skills/solana-wallet) - Solana wallet operations and transfers
- [uniswap](https://clawhub.com/skills/uniswap) - Uniswap DEX trading and liquidity
- [yahoo-finance](https://github.com/openclaw/openclaw/tree/main/skills/yahoo-finance) - Yahoo Finance data integration

### Specialized Roles

- [doctorclaw](https://clawhub.com/skills/doctorclaw) - AI doctor for health analysis and advice
- [lawyer](https://clawhub.com/skills/lawyer) - Legal document analysis and advice
- [marketing-strategist](https://clawhub.com/skills/marketing-strategist) - Marketing strategy development
- [sales-closer](https://clawhub.com/skills/sales-closer) - Sales conversation and closing
- [writing-coach](https://clawhub.com/skills/writing-coach) - Writing improvement and feedback

---

## Tools

Standalone tools and utilities that work with OpenClaw.

### Desktop & Computer Use Agents

- [bytebot-ai/bytebot](https://github.com/bytebot-ai/bytebot) - Self-hosted AI desktop agent in containerized Linux. Automates tasks via natural language — 11K⭐ (June 2026) ⭐ NEW
- [YV17labs/GhostDesk](https://github.com/yv17labs/ghostdesk) - Give any AI agent a full desktop via Docker. It sees the screen, clicks, types, runs apps — one command deploy (⭐ 133) ⭐ NEW
- [CuaOS/CuaOS](https://github.com/CuaOS/CuaOS) - Qwen3-VL-based computer use agent on Ubuntu. Local sandbox with GGUF format, keyboard/mouse control (⭐ 24) ⭐ NEW
- [Dyan-Dev/loopi](https://github.com/Dyan-Dev/loopi) - Desktop automation platform — control browsers, cursor/keyboard, shell commands, 80+ integrations. Runs locally (⭐ 184) ⭐ NEW
- [steipete/Peekaboo](https://github.com/steipete/Peekaboo) - macOS CLI and MCP server for AI agents to capture screenshots with visual Q&A (⭐ 2,891) ⭐ NEW
- [lsdefine/GenericAgent](https://github.com/lsdefine/GenericAgent) - Self-evolving agent framework. Grows from 3.3K-line seed to full system control. 9 atomic tools, real browser control (⭐ 12.9k) ⭐ NEW
- [mudler/LocalAGI](https://github.com/mudler/localagi) - Self-hostable AI Agent platform. Drop-in OpenAI Responses API replacement. Local AI on consumer hardware (June 2026) ⭐ NEW
- [Everfern-AI/Everfern](https://github.com/CodenRust/Everfern) - Free, local-first AI agent using your computer like you would. No subscription, no cloud (June 2026) ⭐ NEW

### MCP Servers & Integrations

- [headroom](https://github.com/headroomlabs-ai/headroom) - Context compression layer for AI agents — 60-95% fewer tokens. Library, proxy, MCP server with cross-agent memory. Works with Claude Code, Codex, Cursor, OpenClaw (⭐ trending, July 2026) ⭐ NEW
- [jcodemunch-mcp](https://github.com/jgravelle/jcodemunch-mcp) - Token-efficient MCP server for GitHub code exploration via tree-sitter AST. Cuts AI token costs 95%+ on code retrieval — 313B+ tokens saved (⭐ 1,975, July 2026) ⭐ NEW
- [mcp-agent](https://github.com/lastmile-ai/mcp-agent) - Simple, composable framework to build effective agents using MCP. Implements Anthropic's "Building Effective Agents" patterns with Temporal durability, structured logging, token accounting (⭐ 8.4k, July 2026) ⭐ NEW
- [steipete/claude-code-mcp](https://github.com/steipete/claude-code-mcp) - Claude Code as one-shot MCP server — have an agent in your agent (⭐ 1,306) ⭐ NEW
- [tuannvm/codex-mcp-server](https://github.com/tuannvm/codex-mcp-server) - MCP server wrapper for OpenAI Codex CLI that enables Claude Code to leverage Codex's AI capabilities directly (⭐ 488, July 2026) ⭐ NEW
- [mcp-github-trending](https://github.com/jiyi1990118/mcp-github-trending) - MCP server providing real-time GitHub trending repos and developer data to AI applications. Fuzzy search, language filtering, repo analysis (July 2026) ⭐ NEW
- [agent-skills-hub](https://github.com/zhuyansen/agent-skills-hub) - Discover and compare 117K+ open-source Agent Skills, tools & MCP servers with quality scoring on 10 dimensions, trending analysis, auto-GitHub sync (⭐ 301, July 2026) ⭐ NEW
- [Helms-AI/openclaw-mcp-server](https://github.com/Helms-AI/openclaw-mcp-server) - MCP server exposing OpenClaw Gateway tools to Claude Code and other MCP-compatible clients (⭐ 14) ⭐ NEW
- [haliphax-ai/openclaw-tools-mcp-server](https://github.com/haliphax-openclaw/openclaw-tools-mcp-server) - MCP server that exposes OpenClaw tools to ACP agents (⭐ 1, archived) ⭐ NEW
- [niglo32432/claude-code-mcp-server](https://github.com/niglo32432/claude-code-mcp-server) - MCP server for Claude Code: 15 dev tools including files, search, shell, Git, GitHub, Docker, HTTP, SQL (⭐ 10) ⭐ NEW
- [haomingkoo/create-mcp](https://github.com/haomingkoo/create-mcp) - Claude Code skill for full MCP development lifecycle — from idea to production (June 2026) ⭐ NEW
- [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK for Model Context Protocol servers and clients (⭐ 23,476) ⭐ NEW
- [jeanpetitY/mcp-server](https://github.com/jeanpetitY/mcp-server) - Production-ready MCP server with comprehensive tooling (June 2026) ⭐ NEW
- [msilverblatt/protomcp](https://github.com/msilverblatt/protomcp) - Language-agnostic MCP runtime with hot reload, dynamic tool lists, server-defined workflows (June 2026) ⭐ NEW
- [EduhxH/MCP-SERVER-PRO](https://github.com/EduhxH/MCP-SERVER-PRO) - Professional MCP server with connectors for Pinecone, Google Cloud, Gmail, Excel, IDE automation (June 2026) ⭐ NEW

### Agent Frameworks & Platforms

- [openclaw-trace](https://github.com/Phantastic-AI/openclaw-trace) - Recursive self-improvement pipeline for OpenClaw session traces. Mines real sessions for errors and friction, clusters them, generates research briefs, and ships verified fixes — evidence-backed and measurable (18⭐, July 2026) ⭐ NEW
- [langclaw](https://github.com/tisu19021997/langclaw) - LangChain + OpenClaw = production runtime. RBAC, durable workflows, scheduled jobs, persistent memory, subagent delegation — like FastAPI for agents (74⭐, July 2026) ⭐ NEW
- [Agent-MCP](https://github.com/rinadelph/Agent-MCP) - Multi-agent collaboration framework with persistent knowledge graph, real-time dashboard, and parallel execution. Like "Obsidian for your AI agents" (HN trending, July 2026) ⭐ NEW
- [NexusMCP](https://github.com/aavikshit2007-ops/NexusMCP) - Modern Python framework for MCP-native AI agents with composable skills, orchestrator DAGs, OpenTelemetry observability, and sandboxed execution (July 2026) ⭐ NEW
- [agent-harness](https://github.com/Phoenixrr2113/agent-harness) - File-first agent operating system. Build AI agents by editing markdown files, not writing code. Self-managing, self-improving, durable with context budgeting and session capture (July 2026) ⭐ NEW
- [shire](https://github.com/victor36max/shire) - Multi-agent collaboration platform where agents persist, communicate autonomously, and build on yesterday's work. Works with Claude Code, OpenCode, Codex, Pi Agent (33⭐, July 2026) ⭐ NEW
- [agentwasp](https://github.com/agentwasp/agentwasp) - Production agent runtime with truth-binding response layer, 10+ persistent memory tiers, 41 background jobs, capability tiers, and anticipatory simulation (139⭐, July 2026) ⭐ NEW
- [TITAN](https://github.com/Djtony707/TITAN) - AI operating system with team of specialists (Scout/Builder/Writer/Analyst/Sage), real-time canvas, autonomous loop, 37 providers, 19 channels, 91 skills (18⭐, July 2026) ⭐ NEW
- [phantom](https://github.com/borhen68/phantom) - Teachable AI agent for controlled delegation with workflow learning, plan approval, chief-of-staff memory, parallel orchestration, auditable traces (5⭐, July 2026) ⭐ NEW
- [sento](https://github.com/sentoagent/sento) - 24/7 self-improving AI agents that run on Claude Code. Discord/Telegram/Slack/iMessage control. Guardian bot auto-restart, skill sharing, agent-to-agent messaging (5⭐, July 2026) ⭐ NEW
- [teammcp](https://github.com/cookjohn/teammcp) - MCP-native collaboration server for AI agent teams — real-time messaging, task management, org structure, approval workflows, audit trails (49⭐, July 2026) ⭐ NEW
- [Somi-Project/Somi](https://github.com/Somi-Project/Somi) - Local-first AI agent framework with GUI, memory, web search, personality, speech I/O, tools, skills — fully self-hosted via Ollama (⭐ 21) ⭐ NEW
- [IdeoaLabs/Open-Sable](https://github.com/IdeoaLabs/Open-Sable) - Local-first autonomous agent framework with AGI-inspired cognitive subsystems — goals, memory, metacognition, tool use (June 2026) ⭐ NEW
- [lthoangg/OpenAgentd](https://github.com/lthoangg/openagentd/) - Self-hosted AI agent OS — streaming chat, tool use, persistent memory, multi-agent teams. Runs entirely on your machine (⭐ 197) ⭐ NEW
- [SinthetikIndustries/Agency](https://github.com/SinthetikIndustries/Agency) - Personal AI operating system with coordinated stack: API gateway, web dashboard, multi-agent orchestrator, model router, knowledge base (June 2026) ⭐ NEW
- [strikersam/autonomous-ai-agency](https://github.com/strikersam/local-llm-server) - Autonomous AI Agent Infrastructure Platform — OpenAI-compatible AI gateway with MCP, multi-agent orchestration, tool calling, observability, memory, RAG (⭐ 4) ⭐ NEW
- [Synkora](https://synkora.ai/) - Open-source LLM application platform. Build agents that connect to your data, deploy to Slack, WhatsApp, Teams. Self-host or use cloud (June 2026) ⭐ NEW

### Utilities & Helpers

- [stellariums/openclaw-skill](https://github.com/stellariums/openclaw-skill) - Comprehensive Agent Skill for installing, configuring, operating, and troubleshooting OpenClaw ⭐ NEW
- [quratus/openclaw_cli_agent_skill](https://github.com/quratus/openclaw_cli_agent_skill) - CLI-focused agent skill for OpenClaw operations (⭐ 3) ⭐ NEW
- [CellarDoorExits/openclaw-skill](https://github.com/CellarDoorExits/openclaw-skill) - OpenClaw agent skill for EXIT Protocol ⭐ NEW
- [ametel01/claw-browser-automation](https://github.com/ametel01/claw-browser-automation) - Browser automation skill for OpenClaw with TypeScript (⭐ 1) ⭐ NEW
- [jeffjacobsen/mcpskill](https://github.com/jeffjacobsen/mcpskill) - Direct MCP Wrapper for Claude Code Skills (⭐ 1) ⭐ NEW
- [mcp-setup](https://skills.cat/skills/yeachan-heo/oh-my-claudecode/mcp-setup) - Configure popular MCP servers for enhanced agent capabilities ⭐ NEW

---

## Tutorials

- [OpenClaw MCP Guide](https://clawdbot.works/getting-started/) - Getting Started: MCP + OpenClaw in 10 Minutes ⭐ NEW
- [OpenClaw Configuration Reference](https://www.getopenclaw.ai/help/configuration-guide) - Complete configuration reference ⭐ NEW
- [Run OpenClaw as MCP Server](https://open-claw.bot/docs/cli/mcp/) - Official guide to running OpenClaw as an MCP server ⭐ NEW
- [Connect Claude Code to tools via MCP](https://code.claude.com/docs/en/mcp.md) - Anthropic's MCP integration guide ⭐ NEW
- [Building MCP Servers Guide](https://webdeveloper.com/learn/guides/building-mcp-servers/) - TypeScript, Streamable HTTP, Production ⭐ NEW
- [I Tested 8 MCP Servers With Claude Code](https://medium.com/data-science-collective/the-8-mcp-servers-every-claude-code-setup-needs-in-2026-fac76ac7d013) - Practical MCP server recommendations (June 2026) ⭐ NEW
- [MCP Quickstart Tutorial](https://modelcontextprotocol.info/docs/quickstart/quickstart/) - Build a simple MCP weather server ⭐ NEW

---

## Example Projects

- [openclaw-skill](https://github.com/stellariums/openclaw-skill) - Comprehensive Agent Skill for installing, configuring, operating, and troubleshooting OpenClaw
- [quratus/openclaw_cli_agent_skill](https://github.com/quratus/openclaw_cli_agent_skill) - CLI-focused agent skill for OpenClaw operations

---

## Regional Resources

- [awesome OpenClaw Tutorial - Tencent Cloud](https://www.tencentcloud.com/techpedia/141445?lang=en) - Chinese language tutorial
- [win4r/OpenClaw-Skill (中文文档)](https://github.com/win4r/openclaw-skill) - Chinese documentation available

---

## Community

- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Ask questions, share ideas
- [Discord](https://discord.com/invite/clawd) - Real-time chat and support
- [r/openclaw](https://reddit.com/r/openclaw) - Reddit community (if exists)
- [ClawHub](https://clawhub.com) - Skill registry and discovery platform

---

## Contributing

Please see [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines on adding new resources.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain.

---

*This awesome list is maintained by the OpenClaw community. Last updated: July 5, 2026*
