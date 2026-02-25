# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of OpenClaw resources, skills, tools, and example projects.

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

- [1password](https://github.com/openclaw/openclaw/tree/main/skills/1password) - Manage 1Password vault items and passwords
- [apple-notes](https://github.com/openclaw/openclaw/tree/main/skills/apple-notes) - Read and search Apple Notes on macOS
- [apple-reminders](https://github.com/openclaw/openclaw/tree/main/skills/apple-reminders) - Manage Apple Reminders on macOS
- [bear-notes](https://github.com/openclaw/openclaw/tree/main/skills/bear-notes) - Search and manage Bear notes
- [chitin](https://clawhub.com/skills/chitin) - Personality persistence for AI agents
- [cron-scheduling](https://clawhub.com/skills/cron-scheduling) - Schedule recurring tasks with cron and templates
- [credential-manager](https://clawhub.com/skills/credential-manager) - MANDATORY security foundation for OpenClaw credential management
- [daily-briefing](https://clawhub.com/skills/daily-briefing) - Warm daily briefing with weather, calendar, reminders
- [focus-deep-work](https://clawhub.com/skills/focus-deep-work) - Deep work and productivity enhancement
- [healthcheck](https://github.com/openclaw/openclaw/tree/main/skills/healthcheck) - Track water intake and sleep
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

### AI & Voice

- [openai-whisper](https://github.com/openclaw/openclaw/tree/main/skills/openai-whisper) - Local speech-to-text with OpenAI Whisper
- [openai-whisper-api](https://github.com/openclaw/openclaw/tree/main/skills/openai-whisper-api) - Speech-to-text via OpenAI API
- [piper-tts](https://clawhub.com/skills/piper-tts) - Local TTS using Piper ONNX voices (fast, private, no cloud)
- [sapi-tts](https://clawhub.com/skills/sapi-tts) - Windows SAPI5 text-to-speech with Neural voices
- [speech-to-text](https://clawhub.com/skills/speech-to-text) - Transcribe audio with Whisper models via inference.sh CLI
- [ai-music-generation](https://clawhub.com/skills/ai-music-generation) - Generate AI music and songs with Diffrythm, Tencent Song Generation
- [conversation-summary-api](https://clawhub.com/skills/conversation-summary-api) - Generate conversation summaries with incremental updates

### Data & Research

- [ai-diff-summary](https://clawhub.com/skills/ai-diff-summary) - Summarize git diffs in plain English
- [apewisdom](https://github.com/openclaw/openclaw/tree/main/skills/apewisdom) - Reddit stock sentiment tracking
- [blogwatcher](https://github.com/openclaw/openclaw/tree/main/skills/blogwatcher) - Monitor and track blog/RSS feeds
- [conclave-testnet](https://clawhub.com/skills/conclave-testnet) - Collaborative idea game for AI agents
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
- [skill-guard](https://clawhub.com/skills/skill-guard) - Skill security vetting and validation
- [ssh-exec](https://clawhub.com/skills/ssh-exec) - Run commands on remote Tailscale nodes
- [ssh-tunnel](https://clawhub.com/skills/ssh-tunnel) - SSH tunneling and port forwarding
- [tunneling](https://clawhub.com/skills/tunneling) - Create free SSH tunnels to expose local ports
- [vercel](https://github.com/openclaw/openclaw/tree/main/skills/vercel) - Deploy and manage Vercel projects

### Smart Home & IoT

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
- [hyperliquid-trading](https://clawhub.com/skills/hyperliquid-trading) - Hyperliquid trading and analysis
- [klaviyo](https://clawhub.com/skills/klaviyo) - Klaviyo API integration
- [clawpify](https://clawhub.com/skills/clawpify) - Query and manage Shopify stores via GraphQL Admin API
- [llm-wallet](https://clawhub.com/skills/llm-wallet) - LLM Wallet with x402 stablecoin payments on Polygon
- [mailchimp](https://clawhub.com/skills/mailchimp) - Mailchimp Marketing API integration
- [metals-agent-teneo](https://clawhub.com/skills/metals-agent-teneo) - Real-time prices for gold, silver, copper
- [mia-polymarket-trader](https://clawhub.com/skills/mia-polymarket-trader) - Automated prediction market trading on Polymarket
- [minara](https://clawhub.com/skills/minara) - Financial analysis and trading
- [moltiumv2](https://clawhub.com/skills/moltiumv2) - Solana AI trade toolkit (pump.fun, Raydium, PumpSwap)
- [onchain](https://clawhub.com/skills/onchain) - Onchain CLI for blockchain operations
- [openclaw-1ly-payments](https://clawhub.com/skills/openclaw-1ly-payments) - Payment processing for OpenClaw
- [openindex](https://clawhub.com/skills/openindex) - End-to-end encrypted messaging and EVM crypto wallet
- [paylobster](https://www.paylobster.com/) - Payment infrastructure for AI agents (tips, donations, USDC on Base)
- [polymarket-odds](https://clawhub.com/skills/polymarket-odds) - Polymarket prediction market odds
- [primer-x402](https://clawhub.com/skills/primer-x402) - x402 payment protocol with Primer
- [revenuecat](https://clawhub.com/skills/revenuecat) - RevenueCat metrics and customer data
- [soroban](https://clawhub.com/skills/soroban) - Stellar Soroban smart contract integration
- [stock-market-pro](https://github.com/openclaw/openclaw/tree/main/skills/stock-market-pro) - Professional stock analysis and charts
- [strykr-prism](https://clawhub.com/skills/strykr-prism) - Advanced trading and analytics
- [x402](https://clawhub.com/skills/x402) - x402 micropayments protocol
- [yahoo-data-fetcher](https://github.com/openclaw/openclaw/tree/main/skills/yahoo-data-fetcher) - Real-time stock quotes
- [zeruai](https://clawhub.com/skills/zeruai) - Register agents on Zeru ERC-8004 Identity Registry

### Specialized Roles

Professional-grade skills for specific job roles:

**Executive & Leadership:**
- [ceo-advisor](https://clawhub.com/skills/ceo-advisor) - Executive leadership toolkit (strategy, board governance, investor relations)
- [cto-advisor](https://clawhub.com/skills/cto-advisor) - Technical leadership (tech debt, team scaling, DORA metrics, ADRs)
- [product-strategist](https://clawhub.com/skills/product-strategist) - Strategic product leadership (OKRs, market analysis, vision setting)
- [product-manager-toolkit](https://clawhub.com/skills/product-manager-toolkit) - PM toolkit (RICE prioritization, customer interviews, PRDs)

**Engineering:**
- [senior-frontend](https://clawhub.com/skills/senior-frontend) - React/Next.js/TypeScript/Tailwind (components, bundle analysis, patterns)
- [senior-fullstack](https://clawhub.com/skills/senior-fullstack) - Fullstack toolkit (Next.js, FastAPI, MERN, Django scaffolding)
- [senior-qa](https://clawhub.com/skills/senior-qa) - React/Next.js testing (Jest, React Testing Library, Playwright)
- [senior-prompt-engineer](https://clawhub.com/skills/senior-prompt-engineer) - Prompt optimization, RAG, agent architectures
- [senior-ml-engineer](https://clawhub.com/skills/senior-ml-engineer) - MLOps pipelines, LLM integration, feature stores
- [senior-data-engineer](https://clawhub.com/skills/senior-data-engineer) - Scalable data pipelines, ETL/ELT, DataOps
- [senior-data-scientist](https://clawhub.com/skills/senior-data-scientist) - Statistical modeling, experimentation, causal inference
- [senior-computer-vision](https://clawhub.com/skills/senior-computer-vision) - Object detection, segmentation, vision AI (YOLO, SAM, TensorRT)
- [senior-security](https://clawhub.com/skills/senior-security) - Threat modeling, STRIDE, secure architecture, pen testing
- [senior-secops](https://clawhub.com/skills/senior-secops) - SecOps toolkit (vulnerability management, compliance, incident response)
- [aws-solution-architect](https://clawhub.com/skills/aws-solution-architect) - AWS architectures for startups (serverless, IaC, cost optimization)

**Design & UX:**
- [ux-researcher-designer](https://clawhub.com/skills/ux-researcher-designer) - UX research toolkit (personas, journey maps, usability testing)
- [ui-design-system](https://clawhub.com/skills/ui-design-system) - Design system toolkit (tokens, components, responsive calculations)
- [tech-stack-evaluator](https://clawhub.com/skills/tech-stack-evaluator) - Technology evaluation with TCO analysis and ecosystem scoring

**Marketing & Content:**
- [marketing-strategy-pmm](https://clawhub.com/skills/marketing-strategy-pmm) - Product marketing (positioning, GTM, competitive battlecards)
- [marketing-demand-acquisition](https://clawhub.com/skills/marketing-demand-acquisition) - Demand generation for Series A+ startups
- [content-creator](https://clawhub.com/skills/content-creator) - SEO-optimized content with brand voice analysis
- [social-media-analyzer](https://clawhub.com/skills/social-media-analyzer) - Social campaign analysis (engagement rates, ROI, benchmarks)
- [copywriter](https://clawhub.com/skills/copywriter) - UX copy, marketing content, product messaging

**IT & Administration:**
- [ms365-tenant-manager](https://clawhub.com/skills/ms365-tenant-manager) - Microsoft 365 tenant administration and automation

### Gaming & Lifestyle

- [gog](https://github.com/openclaw/openclaw/tree/main/skills/gog) - GOG.com game library management
- [food-order](https://github.com/openclaw/openclaw/tree/main/skills/food-order) - Food ordering integration (experimental)

### Community Skills (ClawHub Registry)

Skills published to ClawHub by the community:

- [spoons-skills](https://github.com/10kspoons/spoons-skills) - Shared OpenClaw skills for 10,000 Spoons community ⭐ NEW
- [agent-autonomy-kit](https://clawhub.com/skills/agent-autonomy-kit) - Self-directed task continuation without prompts
- [agent-bridge-kit](https://clawhub.com/skills/agent-bridge-kit) - Bridge kit for agent communication
- [agent-payy](https://clawhub.com/skills/agentpayy) - Payment processing for agents
- [attio-cli](https://clawhub.com/skills/attio-cli) - Attio CRM integration
- [clawbridge](https://clawhub.com/skills/clawbridge-skill-latest) - Find your connections across networks
- [clawmail-xyz](https://clawhub.com/skills/clawmail-xyz) - Give your OpenClaw an email address
- [clawops](https://clawhub.com/skills/clawops) - Operations management toolkit for OpenClaw agents
- [clawvault](https://clawhub.com/skills/clawvault) - Secure credential storage and retrieval
- [clipboard](https://clawhub.com/skills/clipboard) - Cross-device clipboard synchronization
- [homeassistant-n8n-agent](https://clawhub.com/skills/homeassistant-n8n-agent) - Home automation integration with n8n
- [liveavatar](https://clawhub.com/skills/liveavatar) - AI avatar generation and management
- [namw](https://clawhub.com/skills/namw) - Network analysis and monitoring
- [nutrient-openclaw](https://clawhub.com/skills/nutrient-openclaw) - Document processing and conversion
- [ocft](https://clawhub.com/skills/ocft) - OpenClaw File Transfer utility
- [openclaw-agent-optimize-skill](https://clawhub.com/skills/openclaw-agent-optimize-skill) - Optimize agent setup and performance
- [openclaw-agent-token-optimizer](https://clawhub.com/skills/openclaw-agent-token-optimizer) - Advanced token usage optimization
- [openclaw-anything](https://clawhub.com/skills/openclaw-anything) - Comprehensive skill for installing and managing OpenClaw
- [openclaw-p2p](https://clawhub.com/skills/openclaw-p2p) - P2P networking for OpenClaw agents
- [openclast-wallet](https://clawhub.com/skills/openclast-wallet) - OpenClast crypto wallet
- [skill-scaffold](https://clawhub.com/skills/skill-scaffold) - Rapid skill scaffolding generator
- [token-optimizer](https://clawhub.com/skills/token-optimizer) - LLM token usage optimization
- [web-deploy](https://clawhub.com/skills/web-deploy) - Deploy web applications and static sites
- [wooclaw-lite](https://clawhub.com/skills/wooclaw-lite) - WordPress/WooCommerce connector
- [clawdaddy](https://clawhub.com/skills/clawdaddy) - The world's most helpful assistant
- [soul-shepherd](https://clawhub.com/skills/soul-shepherd) - SOUL.md personality management and agent identity
- [gcalcli-calendar](https://clawhub.com/skills/gcalcli-calendar) - Google Calendar via gcalcli with smart agenda views
- [notion-cli](https://clawhub.com/skills/notion-cli) - Notion CLI for pages, databases, and blocks
- [local-booking](https://clawhub.com/skills/local-booking) - Book real-world services through Lokuli MCP (75+ categories)
- [sendclaw-email](https://clawhub.com/skills/sendclaw-email) - FREE agentic email without verification
- [task-decomposer](https://clawhub.com/skills/task-decomposer) - Decomposes complex requests into executable subtasks
- [google-calendar-api](https://clawhub.com/skills/google-calendar-api) - Google Calendar API with managed OAuth
- [gmail](https://clawhub.com/skills/gmail) - Gmail API with managed OAuth
- [playwright-cli-2](https://clawhub.com/skills/playwright-cli-2) - Browser automation via Playwright
- [clawshell](https://clawhub.com/skills/clawshell) - Human-in-the-loop security layer for high-risk commands
- [n8n-api](https://clawhub.com/skills/n8n-api) - Operate n8n workflows via REST API
- [sql-toolkit](https://clawhub.com/skills/sql-toolkit) - Query, design, migrate SQL databases
- [api-gateway](https://clawhub.com/skills/api-gateway) - API gateway for third-party APIs with managed auth
- [transcriptapi](https://clawhub.com/skills/transcriptapi) - YouTube transcripts without API quota limits
- [pptx](https://clawhub.com/skills/pptx) - PowerPoint (.pptx) file handling and manipulation
- [google-slides](https://clawhub.com/skills/google-slides) - Google Slides API with managed OAuth
- [pdf-extract](https://clawhub.com/skills/pdf-extract) - Extract text from PDFs for LLM processing
- [heygen-avatar-lite](https://clawhub.com/skills/heygen-avatar-lite) - AI digital human videos with HeyGen
- [youtube-full](https://clawhub.com/skills/youtube-full) - Complete YouTube toolkit - transcripts, search, channels
- [baidu-search](https://clawhub.com/skills/baidu-search) - Baidu AI Search Engine for Chinese queries
- [firecrawl-skills](https://clawhub.com/skills/firecrawl-skills) - Web scraping and crawling via Firecrawl
- [duckduckgo-search](https://clawhub.com/skills/duckduckgo-search) - DuckDuckGo search without API key
- [parallel-deep-research](https://clawhub.com/skills/parallel-deep-research) - Multi-source research via Parallel API
- [reddit-readonly](https://clawhub.com/skills/reddit-readonly) - Browse Reddit without authentication
- [file-search](https://clawhub.com/skills/file-search) - Fast file search using fd and ripgrep
- [bing-search](https://clawhub.com/skills/bing-search) - Bing search without API key needed
- [discord-admin](https://clawhub.com/skills/discord-admin) - Complete Discord server administration (A-Z)
- [whatsapp-business](https://clawhub.com/skills/whatsapp-business) - WhatsApp Business API with managed OAuth
- [feishu-docx-powerwrite](https://clawhub.com/skills/feishu-docx-powerwrite) - Feishu/Lark Docx writing
- [mia-polymarket-trader](https://clawhub.com/skills/mia-polymarket-trader) - Automated prediction market trading on Polymarket
- [24konbini](https://clawhub.com/skills/24konbini) - Marketplace and bank for AI agents
- [memory-pipeline-0-1-0](https://clawhub.com/skills/memory-pipeline-0-1-0) - Agent memory + performance system
- [agentic-ai-gold](https://clawhub.com/skills/agentic-ai-gold) - Self-improving AI framework
- [daily-briefing](https://clawhub.com/skills/daily-briefing) - Warm daily briefing with weather, calendar, reminders
- [ai-persona-os](https://clawhub.com/skills/ai-persona-os) - Production-grade agent OS with persona management
- [lobster-tank](https://clawhub.com/skills/lobster-tank) - Collaborative research platform for AI agents
- [cron-scheduling](https://clawhub.com/skills/cron-scheduling) - Schedule recurring tasks with cron and templates
- [shell-scripting](https://clawhub.com/skills/shell-scripting) - Write robust, portable shell scripts
- [ssh-tunnel](https://clawhub.com/skills/ssh-tunnel) - SSH tunneling and port forwarding
- [ssh-exec](https://clawhub.com/skills/ssh-exec) - Run commands on remote Tailscale nodes
- [remindme](https://clawhub.com/skills/remindme) - Simple Telegram reminders for OpenClaw
- [skill-guard](https://clawhub.com/skills/skill-guard) - Scan ClawHub skills for security vulnerabilities before installing
- [google-play](https://clawhub.com/skills/google-play) - Google Play Developer API integration
- [klaviyo](https://clawhub.com/skills/klaviyo) - Klaviyo API integration with managed OAuth
- [mailchimp](https://clawhub.com/skills/mailchimp) - Mailchimp Marketing API integration
- [asana-api](https://clawhub.com/skills/asana-api) - Asana API integration with managed OAuth
- [trello-api](https://clawhub.com/skills/trello-api) - Trello API integration with managed OAuth
- [pipedrive-api](https://clawhub.com/skills/pipedrive-api) - Pipedrive API integration with managed OAuth
- [calendly-api](https://clawhub.com/skills/calendly-api) - Calendly API integration with managed OAuth
- [clickup-api](https://clawhub.com/skills/clickup-api) - ClickUp API integration with managed OAuth
- [youtube-api-skill](https://clawhub.com/skills/youtube-api-skill) - YouTube Data API integration with managed OAuth
- [gemini-image-gen](https://clawhub.com/skills/gemini-image-gen) - Generate and edit images via Google Gemini API
- [x-voice-match](https://clawhub.com/skills/x-voice-match) - Analyze X/Twitter style and generate authentic posts
- [agent-council](https://clawhub.com/skills/agent-council) - Toolkit for creating autonomous AI agent councils
- [agent-browser-stagehand](https://clawhub.com/skills/agent-browser-stagehand) - Automate web browser with natural language
- [proactive-agent-1-2-4](https://clawhub.com/skills/proactive-agent-1-2-4) - Transform agents from task-followers to proactive initiators
- [desktop-control](https://clawhub.com/skills/desktop-control) - Advanced desktop automation with mouse, keyboard, screenshots
- [openclaw-security-monitor](https://clawhub.com/skills/openclaw-security-monitor) - Real-time security monitoring and threat scanning
- [deepresearchwork](https://clawhub.com/skills/deepresearchwork) - Comprehensive AI research framework
- [lead-gen-website](https://clawhub.com/skills/lead-gen-website) - Build complete local lead generation websites
- [qmd-skill-main](https://clawhub.com/skills/qmd-skill-main) - Local hybrid search for markdown notes and docs
- [table-image-generator](https://clawhub.com/skills/table-image-generator) - Generate clean table images from data
- [token-optimizer](https://clawhub.com/skills/token-optimizer) - Reduce OpenClaw AI costs by 97% with Haiku routing
- [price-tracker](https://clawhub.com/skills/price-tracker) - Monitor product prices across Amazon, eBay, Walmart
- [exa-search](https://clawhub.com/skills/exa-search) - Exa (exa.ai) search API for web and neural search
- [metals-agent-teneo](https://clawhub.com/skills/metals-agent-teneo) - Real-time prices for gold, silver, copper
- [elevenlabs-transcribe](https://clawhub.com/skills/elevenlabs-transcribe) - Transcribe audio to text using ElevenLabs Scribe
- [voyageai-skill](https://clawhub.com/skills/voyageai-skill) - Voyage AI embedding and reranking CLI
- [project-orchestrator](https://clawhub.com/skills/project-orchestrator) - AI agent orchestrator with Neo4j knowledge graph
- [google-workspace-admin](https://clawhub.com/skills/google-workspace-admin) - Google Workspace Admin SDK integration
- [frinkiac](https://clawhub.com/skills/frinkiac) - Search TV show screenshots and generate memes
- [seo-article-gen](https://clawhub.com/skills/seo-article-gen) - SEO-optimized article generator with affiliate links
- [affiliate-master](https://clawhub.com/skills/affiliate-master) - Full-stack affiliate marketing automation
- [url-shorten](https://clawhub.com/skills/url-shorten) - Shorten URLs via TinyURL or Bitly API
- [hardcover](https://clawhub.com/skills/hardcover) - Query reading lists and book data from Hardcover
- [billclaw](https://github.com/fire-la/billclaw) - Bank transaction and bill data import for OpenClaw - Data sovereignty for your financial data
- [willy-skills](https://github.com/jnology/willy-skills) - Platform skills for OpenClaw AI agents in Willform
- [24konbini](https://clawhub.com/skills/24konbini) - Marketplace and bank for AI agents
- [agentic-ai-gold](https://clawhub.com/skills/agentic-ai-gold) - Self-improving AI framework
- [bing-search](https://clawhub.com/skills/bing-search) - Bing search without API key needed
- [cloudflare-dns-updater](https://clawhub.com/skills/cloudflare-dns-updater) - Create or update proxied Cloudflare DNS A records
- [codex-orchestrator](https://clawhub.com/skills/codex-orchestrator) - Monitor, control, and orchestrate background Codex sessions
- [content-distributor](https://clawhub.com/skills/content-distributor) - Multi-platform content distribution for Chinese social platforms
- [context-gatekeeper](https://clawhub.com/skills/context-gatekeeper) - Token-friendly conversation management with compact briefings
- [claw-roam](https://clawhub.com/skills/claw-roam) - Sync OpenClaw workspace between multiple machines via Git
- [duckduckgo-search](https://clawhub.com/skills/duckduckgo-search) - DuckDuckGo search without API key
- [daily-briefing](https://clawhub.com/skills/daily-briefing) - Warm daily briefing with weather, calendar, reminders
- [lobster-tank](https://clawhub.com/skills/lobster-tank) - Collaborative research platform for AI agents
- [memory-pipeline-0-1-0](https://clawhub.com/skills/memory-pipeline-0-1-0) - Agent memory + performance system
- [mini-piv](https://clawhub.com/skills/mini-piv) - Lightweight PIV workflow (discovery-driven feature builder)
- [reminder](https://clawhub.com/skills/reminder) - Simple reminder skill
- [smart-memory](https://clawhub.com/skills/smart-memory) - Context-aware memory with dual retrieval modes (vector + Focus Agent)
- [tdd-guide](https://clawhub.com/skills/tdd-guide) - Test-driven development workflow with test generation and coverage analysis
- [taiwan-payments](https://github.com/Oelshafei1/skills) - Taiwan third-party payment integration (NewebPay, ECPay, PAYUNi) for AI agents

### Memory & Context

Skills published to ClawHub by the community:

- [openclaw-cortex](https://github.com/heliosarchitect/openclaw-cortex) - Hybrid memory architecture with temporal awareness
- [openclaw-engram](https://github.com/joshuaswarren/openclaw-engram) - Persistent long-term memory with LLM extraction and QMD search
- [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) - Perfect memory and recall for agents
- [clawdbrunner/openclaw-graphiti-memory](https://github.com/clawdbrunner/openclaw-graphiti-memory) - Hybrid memory using Graphiti temporal knowledge graph
- [membrane](https://github.com/GustyCube/membrane) - Selective learning and memory substrate with typed, revisable, decayable memory
- [openclaw-memory-sync](https://github.com/mpesavento/openclaw-memory-sync) - OpenClaw skill for parsing session JSONL logs and backfilling/validating memory files
- [MemOS](https://github.com/MemTensor/MemOS) - AI memory OS for LLM/Agent systems with cross-task skill reuse

---

## Tools

Tools that work with or extend OpenClaw:

- [ClawHub CLI](https://clawhub.com) - Install, update, and publish skills
- [OpenClaw Dashboard](https://github.com/openclaw/openclaw) - Web UI for managing agents
- [Lobster](https://github.com/openclaw/lobster) - Typed local-first macro engine for composable workflows
- [LobsterBoard](https://github.com/Curbob/LobsterBoard) - OpenClaw Dashboard Builder - Create custom dashboards
- [ClawGo](https://github.com/openclaw/clawgo) - Clawd node implementation in Go
- [openclaw-ansible](https://github.com/openclaw/openclaw-ansible) - Automated hardened Clawdbot installation with Tailscale
- [nix-openclaw](https://github.com/openclaw/nix-openclaw) - Nix packages for Clawdbot
- [openclaw-desktop](https://github.com/abe-ichthyo/openclaw-desktop) - Native desktop app for OpenClaw Gateway (Tauri/Rust)
- [cove](https://github.com/MaudeCode/cove) - A cozy WebUI for OpenClaw chat
- [OpenClaw Launcher](https://github.com/earino/OpenClawLauncher) - macOS menu bar app solving Local Network permission for LAN devices
- [lobster](https://github.com/eternalai-org/lobster) - Open source OpenClaw hardware device
- [OpenClawHomeAssistant](https://github.com/techartdev/OpenClawHomeAssistant) - Home Assistant Add-on for OpenClaw (174⭐) ⭐ NEW
- [DinoScan](https://github.com/RekitRex21/Dino_Scan) - Air-gapped security scanner for OpenClaw skills ⭐ NEW
- [ClawBridge](https://github.com/dreamwing/clawbridge) - Mobile dashboard for monitoring agents, token costs, tasks ⭐ NEW
- [cmcp](https://github.com/assimelha/cmcp) - Code Mode MCP — aggregate all MCP servers behind 2 tools ⭐ NEW
- [llmfit](https://github.com/AlexsJones/llmfit) - 206 models. 30 providers. One command to find what runs on your hardware ⭐ NEW
- [Saga](https://github.com/showhn/Saga) - Jira-like project tracker MCP server for AI agents ⭐ NEW
- [Antfarm](https://github.com/snarktank/antfarm) - Build your agent team in OpenClaw with one command ⭐ NEW
- [zeroclaw](https://github.com/zeroclaw-labs/zeroclaw) - Fast, small, fully autonomous AI assistant in Rust — deploy anywhere 🦀 ⭐ NEW
- [ZeroClaw-Android](https://github.com/Natfii/ZeroClaw-Android) - Run AI agents 24/7 on Android with 25+ LLM providers, encrypted storage ⭐ NEW
- [quoroom](https://github.com/quoroom-ai/room) - Public experiment: AI agent swarm earning money with open visibility ⭐ NEW
- [agent-browser](https://github.com/vercel-labs/agent-browser) - Browser automation CLI for AI agents by Vercel Labs ⭐ NEW
- [vibium](https://github.com/VibiumDev/vibium) - Browser automation for AI agents and humans ⭐ NEW
- [browserwing](https://github.com/browserwing/browserwing) - Turn browser actions into MCP commands for efficient agent control ⭐ NEW
- [agent-device](https://github.com/callstackincubator/agent-device) - CLI to control iOS and Android devices for AI agents
- [camofox-browser](https://github.com/jo-inc/camofox-browser) - Headless browser for visiting sites that block AI agents
- [ClawHub CLI](https://clawhub.com) - Install, update, and publish skills
- [Poco-Agent](https://github.com/poco-ai/poco-agent) - Manus-style autonomous agent powered by Claude Code (709⭐) ⭐ NEW
- [Nucleus](https://github.com/eidetic-works/mcp-server-nucleus) - Sovereign Control Plane for AI Agents ⭐ NEW
- [clawdbot-hub](https://github.com/joshlevylabs/clawdbot-hub) - Command center dashboard for Clawdbot ⭐ NEW
- [mission-control](https://github.com/crshdn/mission-control) - AI Agent Orchestration Dashboard for OpenClaw Gateway ⭐ NEW
- [figma-use](https://github.com/dannote/figma-use) - Control Figma from CLI — full read/write access for AI agents ⭐ NEW
- [openclaw-configurator](https://github.com/packyme/openclaw-configurator) - Configuration management tool for OpenClaw
- [openclaw-docker](https://github.com/alltomatos/openclaw-docker) - Docker containerization for OpenClaw
- [iamEvanYT/openclaw-docker](https://github.com/iamEvanYT/openclaw-docker) - Easy Docker setup with Tailscale
- [openclaw-lxd](https://github.com/thishandp7/openclaw-lxd) - Safe VM setup to run OpenClaw in LXD containers with Docker Compose
- [openclaw-better-gateway](https://github.com/ThisIsJeron/openclaw-better-gateway) - Enhanced Gateway web UI with auto-refresh
- [tuxbaby/openclaw-dashboard](https://github.com/tuxbaby/openclaw-dashboard) - Enhanced monitoring with workspace browser
- [Openclaw-Dasboard](https://github.com/realriplab/Openclaw-Dasboard) - Real-time agent monitoring dashboard with Cloudflare Workers + live demo
- [evil-cass-mission-control](https://github.com/evilcassassistant-png/mission-control) - OpenClaw agent dashboard with activity feed, calendar, and global search
- [godel](https://github.com/davidkimai/godel) - Godel OpenClaw and Pi Agent Orchestration Platform
- [opengloves](https://github.com/buxue2025/opengloves) - Standalone mobile web chat for OpenClaw (iOS, Android)
- [rodbland2021/claw-session-viewer](https://github.com/rodbland2021/claw-session-viewer) - Real-time web dashboard for monitoring sessions
- [qualiabot/openclaw-session-browser](https://github.com/qualiabot/openclaw-session-browser) - Session browser for agent insights
- [VACInc/openclaw-tool-call-viewer](https://github.com/VACInc/openclaw-tool-call-viewer) - Web UI for browsing session tool call history
- [crowsecure](https://github.com/diogopaes/crowsecure) - Security & Trust Layer for OpenClaw Skills
- [ClawSecAI/ClawSec-skill](https://github.com/ClawSecAI/ClawSec-skill) - AI-powered security audits for OpenClaw
- [AbYousef739/clawskillshield](https://github.com/AbYousef739/clawskillshield) - Local-first security scanner for skills
- [MikeeBuilds/clawpinch](https://github.com/MikeeBuilds/clawpinch) - Security audit toolkit (63 checks across 8 categories)
- [superglue-ai/clawguardian](https://github.com/superglue-ai/clawguardian) - Security plugin for OpenClaw that detects and filters sensitive data in tool calls
- [knostic/openclaw-shield](https://github.com/knostic/openclaw-shield) - Security plugin that prevents secret leaks, PII exposure, and destructive command execution
- [knostic/openclaw-detect](https://github.com/knostic/openclaw-detect) - Detection scripts for MDM deployment to identify OpenClaw installations
- [knostic/openclaw-telemetry](https://github.com/knostic/openclaw-telemetry) - Telemetry for OpenClaw tool calls, LLM usage, agent lifecycle events
- [backslash-security/Claw-Hunter](https://github.com/backslash-security/Claw-Hunter) - MDM security tool to detect and secure OpenClaw/Moltbot shadow AI agents
- [clawgate](https://github.com/M64GitHub/clawgate) - Zero-trust file/git access using cryptographic capability tokens
- [ClawSysMon](https://github.com/mayur-dot-ai/ClawSysMon.com) - System Monitor and Process Watcher Dashboard for OpenClaw
- [ClawK](https://github.com/fraction12/ClawK) - Native macOS companion app with menubar (sessions, heartbeats, cron)
- [opengloves](https://github.com/buxue2025/opengloves) - Standalone mobile web chat for OpenClaw (iOS, Android)
- [deploy-openclaw](https://github.com/PhucMPham/deploy-openclaw) - Interactive TUI wizard for deploying OpenClaw on Ubuntu/Debian VPS
- [DevClaw](https://github.com/laurentenhoor/devclaw) - Multi-project dev/QA pipeline orchestration with autonomous scheduling and role-based model selection ⭐ HN Show
- [pgclaw](https://github.com/calebwin/pgclaw) - Postgres extension adding "claw" data type - ACID-compliant AI agents in every row ⭐ HN Show
- [ClawDash](https://github.com/ishoplus/ClawDash) - Glassmorphic dashboard for OpenClaw with real-time monitoring, analytics, and file browser (⭐ 1)
- [quick-open-claw](https://github.com/joseamijares/quick-open-claw) - One-click OpenClaw deployment for LATAM. Telegram + Ollama
- [maxmode](https://github.com/7juliusearl/maxmode) - Dashboard with MaxMode workspace
- [TheHive](https://github.com/stealthystew/TheHive) - Subagent dashboard and monitoring
- [autoclaw-web](https://github.com/my3rdstory/autoclaw-web) - Web-based OpenClaw installer (Korean)
- [openclaw-zh](https://github.com/coda8/openclaw-zh) - Chinese localization resources
- [openclaw-cardputer](https://github.com/mininerva/openclaw-cardputer) - OpenClaw firmware for Cardputer ADV devices
- [openclaw-ai-sdk-provider](https://github.com/VIDA-Global/openclaw-ai-sdk-provider) - Vercel AI SDK provider for OpenClaw API
- [natan89/awesome-openclaw-skills](https://github.com/natan89/awesome-openclaw-skills) - Catalog of 1715+ community skills
- [Endogen/ralph-loop](https://github.com/Endogen/ralph-loop) - Event-driven Ralph pattern for AI agent loops
- [synapz-org/synapz-agent](https://github.com/synapz-org/synapz-agent) - OpenClaw agent workspace template (Bittensor native)
- [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) - Self-learning API skill generator that auto-discovers APIs from browser traffic
- [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) - Self-writing meta-extension for OpenClaw
- [crshdn/mission-control](https://github.com/crshdn/mission-control) - AI Agent Orchestration Dashboard for task management and multi-agent collaboration
- [runkids/skillshare](https://github.com/runkids/skillshare) - Sync skills across AI CLI tools (Claude Code, OpenClaw, OpenCode)
- [cmcp](https://github.com/assimelha/cmcp) - Code Mode MCP — aggregate all MCP servers behind just 2 tools (search + execute) ⭐ NEW
- [openclaw-secure-kit](https://github.com/NinoSkopac/openclaw-secure-kit) - Secure-by-default OpenClaw on Ubuntu with verifiable security reports ⭐ NEW
- [openclaw-browser-relay-resilient](https://github.com/Unayung/openclaw-browser-relay) - Resilient Browser Relay fork with auto-reconnect and MV3 state persistence
- [playwright-mcp](https://github.com/microsoft/playwright-mcp) - Microsoft's official MCP server for browser automation via Playwright
- [mission-control](https://github.com/imadaitelarabi/openclaw-mc) - Real-time monitoring and management interface for OpenClaw Gateway ⭐ NEW
- [OpenViking](https://github.com/volcengine/OpenViking) - Context database for AI agents - hierarchical memory, resources, and skills via filesystem paradigm ⭐ NEW
- [refly](https://github.com/refly-ai/refly) - First open-source agent skills builder - define skills by vibe workflow, run on Claude Code/Cursor/Codex ⭐ NEW
- [mcp-use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework to develop MCP Apps for ChatGPT/Claude and MCP Servers for AI Agents ⭐ NEW
- [AgenticMail](https://github.com/agenticmail/agenticmail) - Open-source email & SMS identity for AI agents with 63 tools and multi-agent coordination ⭐ NEW
- [incidentfox](https://github.com/incidentfox/incidentfox) - Self-hosted AI agent for investigating production incidents with Ollama/local model support ⭐ NEW
- [AIRI](https://github.com/moeru-ai/airi) - Self-hosted AI companion with realtime voice chat, Minecraft and Factorio playing capabilities ⭐ NEW
- [vexscan](https://github.com/edimuj/vexscan) - Security scanner for AI agent plugins, skills, MCPs (Rust) ⭐ NEW
- [CanaryAI](https://github.com/jx887/homebrew-canaryai) - Security monitoring on Claude Code actions ⭐ NEW
- [AgentStack](https://github.com/agentstack-ai/AgentStack) - Scaffold and build robust AI agent projects from the command line ⭐ NEW
- [cline](https://github.com/cline/cline) - VS Code extension with autonomous coding agent using MCP and browser ⭐ NEW
- [hintjen/RoboClaw](https://github.com/hintjen/RoboClaw) - Community-powered OpenClaw deployment and orchestration layer
- [molt-bot/openclaw-trading-assistant](https://github.com/molt-bot/openclaw-trading-assistant) - Trading assistant with Hyperliquid API integration
- [crabwalk](https://github.com/luccast/crabwalk) - Real-time companion monitor for OpenClaw agents ⭐ 700+
- [botmaker](https://github.com/jgarzik/botmaker) - UI/app to create containerized OpenClaw bots
- [burrow](https://github.com/sydneyb-agent/burrow) - Private agent-to-agent communication system for Moltbook and OpenClaw
- [fleetcentric](https://github.com/fleetcentric/fleetcentric) - OpenClaw Config Generator for Fleets
- [hard-shell](https://github.com/gettweek/hard-shell) - Hardened OpenClaw + Tweek Docker distribution with defense-in-depth security
- [openclaw-credential-manager](https://github.com/teeclaw/openclaw-credential-manager) - Secure credential management for OpenClaw
- [openclaw-railway-custom](https://github.com/benjee-inc/openclaw-railway-custom) — Railway template with extra skills (bird, clawhub, mcporter, gog, gh, himalaya, summarize, yt-dlp)
- [AionUi](https://github.com/iOfficeAI/AionUi) — Free, local, open-source 24/7 cowork for OpenClaw, Gemini CLI, Claude Code, Codex, OpenCode, and more ⭐ 12.4k
- [MarketBot](https://github.com/EthanAlgoX/MarketBot) - Finance-customized OpenClaw with desktop Electron app and market intelligence ⭐ NEW
- [clawe](https://github.com/getclawe/clawe) - Multi-agent coordination system: think Trello for OpenClaw agents ⭐ 489
- [poco-agent](https://github.com/poco-ai/poco-agent) - Manus-style autonomous agent powered by cloud-based Claude Code ⭐ 689
- [ai-maestro](https://github.com/23blocks-OS/ai-maestro) - AI Agent Orchestrator with memory search, code graph queries, agent-to-agent messaging ⭐ 331
- [opengoat](https://github.com/marian2js/opengoat) - Build organizations of OpenClaw agents that coordinate across Codex, Claude Code, Cursor, Lovable 🐐 ⭐ 81
- [ypi](https://github.com/rawwerks/ypi) - Recursive coding agent inspired by RLMs ⭐ 115
- [bub](https://github.com/PsiACE/bub) - Build anything with AI agents ⭐ 372
- [bashobot](https://github.com/uraimo/bashobot) - OpenClaw-inspired personal assistant in 100% Bash 🦞 ⭐ NEW
- [ztm-plugin](https://github.com/flomesh-io/openclaw-channel-plugin-ztm) - ZTM (Zero Trust Mesh) Chat integration for decentralized P2P messaging ⭐ NEW
- [openclaw-lighthouse](https://github.com/BlueBirdBack/openclaw-lighthouse) - Practical OpenClaw issue/fix playbook from real incidents ⭐ NEW
- [multi-agent-shogun](https://github.com/yohey-w/multi-agent-shogun) - Samurai-inspired multi-agent system for Claude Code with tmux orchestration ⭐ NEW
- [openclaw-langfuse](https://github.com/MCKRUZ/openclaw-langfuse) - Langfuse LLM observability plugin — traces every agent turn with sessions, token usage, latency, cost
- [skillpm](https://github.com/eddieran/skillpm) - Local-first skill package manager with rollback-safe install/sync
- [xint](https://github.com/0xNyk/xint) - X Intelligence CLI — search, monitor, analyze, engage on X/Twitter
- [AgentPassVault](https://github.com/joshua5201/AgentPassVault) - Zero-knowledge secret manager for autonomous AI agents
- [serena](https://github.com/oraios/serena) - Powerful coding agent toolkit with semantic retrieval and MCP server ⭐ 20k+
- [agent-infra/sandbox](https://github.com/agent-infra/sandbox) - All-in-One Sandbox for AI Agents (Browser, Shell, File, MCP, VSCode) ⭐ 2.5k
- [Peekaboo](https://github.com/steipete/Peekaboo) - macOS screenshot MCP server with visual question answering ⭐ 2.2k
- [snyk/agent-scan](https://github.com/snyk/agent-scan) - Security scanner for AI agents, MCP servers and skills ⭐ 1.5k
- [ironclaw](https://github.com/nearai/ironclaw) - OpenClaw-inspired implementation in Rust focused on privacy and security ⭐ NEW
- [cherry-studio](https://github.com/CherryHQ/cherry-studio) - AI productivity studio with smart chat, autonomous agents, and 300+ assistants ⭐ NEW
- [1Panel](https://github.com/1Panel-dev/1Panel) - Intuitive web interface for managing OpenClaw agents, local LLMs, websites, databases, containers ⭐ NEW
- [ClawX](https://github.com/ValueCell-ai/ClawX) - Desktop GUI for OpenClaw agents - turns CLI-based AI orchestration into a desktop experience ⭐ NEW
- [buildwithclaude](https://github.com/davepoon/buildwithclaude) - Hub for Claude Skills, Agents, Commands, Hooks, Plugins, and Marketplace collections ⭐ NEW
- [Tencent AI-Infra-Guard](https://github.com/Tencent/AI-Infra-Guard) - Full-stack AI Red Teaming platform for securing AI ecosystems ⭐ NEW
- [ClawRouter](https://github.com/BlockRunAI/ClawRouter) - Agent-native LLM router powering OpenClaw ⭐ NEW
- [obsidian-skills](https://github.com/kepano/obsidian-skills) - Agent skills for Obsidian note-taking ⭐ NEW
- [planning-with-files](https://github.com/OthmanAdi/planning-with-files) - Manus-style persistent markdown planning for Claude Code/OpenClaw ⭐ NEW
- [mimiclaw](https://github.com/memovai/mimiclaw) - Run OpenClaw on a $5 chip. No OS, No Node.js, No VPS ⭐ NEW
- [moltis](https://github.com/moltis-org/moltis) - Personal AI assistant built in Rust with multi-provider LLMs, long-term memory, MCP tools ⭐ NEW
- [NagaAgent](https://github.com/RTGS2017/NagaAgent) - Simple yet powerful agent framework for personal assistants ⭐ NEW
- [secure-openclaw](https://github.com/ComposioHQ/secure-openclaw) - Personal 24x7 AI assistant on WhatsApp, Telegram, Signal, iMessage with 500+ app integrations ⭐ NEW
- [cloudflare-moltworker](https://github.com/cloudflare/moltworker) - Run OpenClaw on Cloudflare Workers ⭐ NEW
- [nanoclaw](https://github.com/qwibitai/nanoclaw) - Lightweight containerized alternative connecting to WhatsApp with memory and scheduled jobs ⭐ NEW
- [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) - Community collection of OpenClaw use cases for making life easier ⭐ NEW
- [poncho](https://github.com/cesr/poncho-ai) - General agent harness for web - version-controlled, git-native, serverless-friendly ⭐ NEW
- [agentpriv](https://github.com/nichkej/agentpriv) - "Sudo for AI Agents" - permission layer with allow/deny/ask gates ⭐ NEW
- [air-blackbox](https://github.com/nostalgicskinco/air-blackbox-gateway) - Tamper-evident flight recorder for AI agents with HMAC-SHA256 audit chains ⭐ NEW
- [csl-core](https://github.com/Chimera-Protocol/csl-core) - Policy engine using Z3 formal verification for AI agent safety constraints ⭐ NEW
- [polymcp](https://github.com/poly-mcp/PolyMCP) - MCP tools framework with autonomous PolyClaw agent orchestration ⭐ NEW
- [ledgersync](https://github.com/Metacog-AI/ledgersync) - Cross-agent shared-memory protocol for AI coding tools ⭐ NEW
- [ClawWork](https://github.com/HKUDS/ClawWork) - OpenClaw as your AI coworker - automation framework for earnings ⭐ NEW
- [VisionClaw](https://github.com/sseanliu/VisionClaw) - Real-time AI assistant for Meta Ray-Ban smart glasses with voice + vision ⭐ NEW
- [clawsec](https://github.com/prompt-security/clawsec) - Complete security skill suite for OpenClaw with drift detection and automated audits ⭐ NEW
- [memsearch](https://github.com/zilliztech/memsearch) - Markdown-first memory system standalone library for any AI agent ⭐ NEW
- [clawlet](https://github.com/mosaxiv/clawlet) - Ultra-lightweight & efficient personal AI assistant ⭐ NEW
- [x-research-skill](https://github.com/rohunvora/x-research-skill) - X/Twitter research skill for Claude Code and OpenClaw ⭐ NEW
- [prompthistory](https://github.com/junhoyeo/prompthistory) - CLI tool to search, replay, test, and compare AI coding assistant prompts across OpenClaw, Claude Code, Codex ⭐ NEW
- [multi-agent-shogun](https://github.com/yohey-w/multi-agent-shogun) - Samurai-inspired multi-agent system for Claude Code with tmux orchestration ⭐ NEW
- [pinion-os](https://github.com/chu2bard/pinion-os) - Client SDK and skill framework for x402 micropayments on Base ⭐ NEW
- [session-cost](https://github.com/khaney64/session-cost) - OpenClaw session scanner to summarize model costs for given range
- [skill-hub](https://github.com/pass-ctrl-ai/skill-hub) - OpenClaw skill hub for exported skills
- [starknet-agentic](https://github.com/keep-starknet-strange/starknet-agentic) - The infrastructure layer for the agentic era on Starknet
- [prompt-injection-defense](https://github.com/misty-step/prompt-injection-defense) - Scientific experiments on LLM security boundary tags for prompt injection defense
- [openclaw-advanced-voice](https://github.com/gnaritas/openclaw-advanced-voice) - Advanced voice calling plugin with System 1/2 architecture and security challenges
- [souls-directory](https://github.com/thedaviddias/souls-directory) - Directory of SOUL.md personality files for OpenClaw agents
- [antigravity-claude-proxy](https://github.com/badrisnarayanan/antigravity-claude-proxy) - Proxy for using Antigravity Claude/Gemini models in Claude Code and OpenClaw
- [eclipse-openclaw-template](https://github.com/gdr3941/eclipse-openclaw-template) - OpenClaw workspace template for Eclipse partners
- [mithun50/openclawd-termux](https://github.com/mithun50/openclawd-termux) - Run OpenClaw AI Gateway on Android via Termux
- [openakita/openakita](https://github.com/openakita/openakita) - Open-source AI assistant framework with skills
- [mibolaji/ClawPad](https://github.com/mibolaji/ClawPad) - Simplify agentic systems on older machines
- [Keith-CY/idx.md](https://github.com/Keith-CY/idx.md) - Markdown registry for AI agent libraries
- [hairyf/clawflow](https://github.com/hairyf/clawflow) - Engineering, Observable, and Collaborative OpenClaw Framework
- [troykelly/openclaw-projects](https://github.com/troykelly/openclaw-projects) - Postgres-backed project + task management with work graphs
- [tashfeenahmed/scallopbot](https://github.com/tashfeenahmed/scallopbot) - Cost-optimized personal AI assistant with multi-provider routing
- [polats/free-the-claw](https://github.com/polats/free-the-claw) - Run OpenClaw for free using NVIDIA NIM
- [NevaMind-AI/memU](https://github.com/NevaMind-AI/memU) - Memory system for 24/7 proactive agents
- [MemTensor/MemOS](https://github.com/MemTensor/MemOS) - AI memory OS for LLM/Agent systems
- [nhevers/MoltBrain](https://github.com/nhevers/MoltBrain) - Long-term memory layer that learns project context
- [junhoyeo/tokscale](https://github.com/junhoyeo/tokscale) - CLI tool tracking token usage with global leaderboard
- [openclaw-stt-tts](https://github.com/CHRISILDAVID/openclaw-stt-tts) - Realtime voice-voice conversation system for OpenClaw
- [openclaw-dashboard](https://github.com/vivekchand/openclaw-dashboard) - Real-time observability dashboard for OpenClaw AI agents
- [owlclaw](https://github.com/yeemio/owlclaw) - Governance, traceability, and auditability for OpenClaw and other agent frameworks
- [vexscan](https://github.com/edimuj/vexscan) - Security scanner for AI agent plugins, skills, MCPs, and configurations
- [openclaw-studio](https://github.com/outsourc-e/openclaw-studio) - VSCode for AI Agents - Desktop interface for OpenClaw Gateway
- [openclaw-credential-proxy](https://github.com/mildside-crypto/openclaw-credential-proxy) - A transparent Credential Proxy system (token isolation) used by OpenClaw to isolate API credentials
- [coolify-openclaw](https://github.com/cadiszu/coolify-openclaw) - Coolify deployment for OpenClaw
- [keep-up](https://github.com/byoungd/keep-up) - Local First AI Native 24/7 Cowork and Clawdbot for multiple AI CLI tools (Gemini CLI, Claude Code, Codex, OpenCode, etc.)
- [openclawd-termux](https://github.com/mithun50/openclawd-termux) - Run OpenClaw AI Gateway on Android via Termux - one-command setup with proot-distro
- [idx.md](https://github.com/Keith-CY/idx.md) - Markdown registry for AI agent libraries with indexed HEAD/BODY content
- [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) - Multi-AI documentation for OpenClaw: architecture, security audits, deployment guide
- [clawd800/pumpclaw](https://github.com/clawd800/pumpclaw) - Free token launcher for AI agents on Base. Uniswap V4. 80% creator fees. LP locked forever
- [coolify-openclaw](https://github.com/cadiszu/coolify-openclaw) - Coolify deployment for OpenClaw
- [ent0n29/samantha](https://github.com/ent0n29/samantha) - Give your agents a voice and talk with them, typing is over
- [jcoulaud/openclaw-telegram-manager](https://github.com/jcoulaud/openclaw-telegram-manager) - OpenClaw plugin that gives each Telegram forum topic its own persistent workspace
- [keep-starknet-strange/starkclaw](https://github.com/keep-starknet-strange/starkclaw) - On-chain safety rails for your agent
- [keep-up](https://github.com/byoungd/keep-up) - Local First AI Native 24/7 Cowork and Clawdbot for multiple AI CLI tools
- [mithun50/openclawd-termux](https://github.com/mithun50/openclawd-termux) - Run OpenClaw AI Gateway on Android via Termux
- [odefun/ode](https://github.com/odefun/ode) - Work anywhere with your favourite coding agents connected, channel based project config, session map 1-1 to message thread
- [openclaw-credential-proxy](https://github.com/mildside-crypto/openclaw-credential-proxy) - A transparent Credential Proxy system (token isolation) used by OpenClaw to isolate API credentials
- [openclaw-studio](https://github.com/outsourc-e/openclaw-studio) - VSCode for AI Agents - Desktop interface for OpenClaw Gateway
- [outsourc-e/clawsuite](https://github.com/outsourc-e/clawsuite) - All-in-one command center for OpenClaw agents
- [owlclaw](https://github.com/yeemio/owlclaw) - Governance, traceability, and auditability for OpenClaw and other agent frameworks
- [polats/free-the-claw](https://github.com/polats/free-the-claw) - Run OpenClaw for free using NVIDIA NIM
- [Steadman-Labs/quaid](https://github.com/Steadman-Labs/quaid) - Memory and project management plugin for OpenClaw
- [vexscan](https://github.com/edimuj/vexscan) - Security scanner for AI agent plugins, skills, MCPs, and configurations
- [TaxClaw](https://github.com/DougButdorf/TaxClaw) - Local-first tax document extraction for W-2, 1099s, K-1 forms with SQLite storage ⭐ NEW
- [ClawBox](https://github.com/HoneyClans/ClawBox) - Zero-code OpenClaw with beautiful Web UI — no CLI, no Docker, no JSON config ⭐ NEW
- [clawhuddle](https://github.com/allen-hsu/clawhuddle) - Self-hosted OpenClaw for teams — isolated instances per team member with zero maintenance ⭐ NEW
- [OCVoice](https://github.com/Rheace-domiscan/OCVoice) - Voice-first OpenClaw interface — native app for iOS, Android, macOS, Windows using Flutter ⭐ NEW
- [prompthistory](https://github.com/junhoyeo/prompthistory) - CLI tool to search, replay, test, and compare AI coding assistant prompts across OpenClaw, Claude Code, Codex ⭐ NEW
- [clawhealth-app](https://github.com/jeffbander/clawhealth-app) - HIPAA-compliant AI patient care coordination for cardiology with physician dashboard ⭐ NEW

---

## Tutorials

- [Getting Started with OpenClaw](https://docs.openclaw.ai/getting-started) - Official quickstart
- [Building Your First Skill](https://docs.openclaw.ai/skills/creating) - Create custom tools
- [Multi-Agent Architecture](https://docs.openclaw.ai/patterns/multi-agent) - Coordinate agent teams
- [openclaw101](https://github.com/mengjian-github/openclaw101) - Chinese learning resource - master OpenClaw in 7 days
- [openclawcourse](https://github.com/kiankyars/openclawcourse) - 1-hour crash course on OpenClaw

*Want to write a tutorial? [Submit a PR!](./CONTRIBUTING.md)*

---

## Example Projects

Real projects built with OpenClaw:

- [Pantry-Pal](https://github.com/pantry-pal/pantry-pal) - AI-powered recipe and meal planning SaaS (built with OpenClaw agent team)
- [yuna-openclaw](https://github.com/yuna-studio/yuna-openclaw) - Python-based OpenClaw implementation with community extensions (⭐ 32)
- [carapace](https://github.com/puremachinery/carapace) - A secure, stable Rust alternative to openclaw/moltbot/clawdbot (⭐ 6)
- [NeoClaw](https://github.com/koreysmith123/NeoClaw) - TypeScript reimagining of OpenClaw
- [OpenclawInterSystem](https://github.com/Mayuqi-crypto/OpenclawInterSystem) - Multi-agent OpenClaw deployment framework (⭐ 5)
- [primr](https://github.com/blisspixel/primr) - AI-powered company intelligence with OpenClaw integration
- [openclaws.world](https://github.com/gloopieb/openclaws.world) - Global OpenClaw Security Monitor dashboard
- [xiaopi-homepage](https://github.com/sonic0214/xiaopi-homepage) - Personal homepage powered by OpenClaw
- [influencer-scout](https://github.com/maikyonn/influencer-scout) - Influencer discovery platform with OpenClaw skill
- [convex-skill](https://github.com/fruteroclub/convex-skill) - Convex backend integration for OpenClaw agents
- [Openclaw-Launcher](https://github.com/ZevinLeo/Openclaw-Launcher) - Universal launcher for OpenClaw (⭐ 7)
- [nostr-openclaw-dm-plugin](https://github.com/dubzrn/nostr-openclaw-dm-plugin) - Nostr DM integration for OpenClaw
- [troykelly/openclaw-projects](https://github.com/troykelly/openclaw-projects) - Postgres-backed project + task management for Clawdbot
- [marian2js/opengoat](https://github.com/marian2js/opengoat) - Orchestrate agents on Codex, Claude Code, Cursor, OpenClaw, Lovable 🐐
- [trianglegrrl/emotion-engine](https://github.com/trianglegrrl/emotion-engine) - PAD + Ekman + OCEAN emotional model plugin for agents
- [tashfeenahmed/scallopbot](https://github.com/tashfeenahmed/scallopbot) - Cost-optimized personal AI with multi-provider routing 🐚
- [sett-arena](https://github.com/Rainhoole/sett-arena) - The Fighting Pit of Sett (Powered by OpenClaw) - A Mini Twitter Clone
- [mibolaji/ClawPad](https://github.com/mibolaji/ClawPad) - Simplify agentic systems on older machines
- [moltis-org/moltis](https://github.com/moltis-org/moltis) - AI agent task management system
- [openclaw-agent-squad](https://github.com/crayon-doing-petri/openclaw-agent-squad) - AI agent squad coordination framework
- [Ced-Agent-Telegram-Bot-for-OpenClaw](https://github.com/HordyVelocity/Ced-Agent-Telegram-Bot-for-OpenClaw) - Telegram bot integration
- [bottube](https://github.com/Scottcjn/bottube) - BoTTube video sharing platform for AI agents
- [openclaw-xmpp](https://github.com/kazakhan/openclaw-xmpp) - XMPP chat protocol integration
- [openclaw-mission-control](https://github.com/megahertz8/openclaw-mission-control) - Mission control dashboard for OpenClaw
- [manish-raana/openclaw-mission-control](https://github.com/manish-raana/openclaw-mission-control) - Real-time web UI for monitoring agents and workflows (Convex + React)
- [rikispiks-max/openclaw-mission-control](https://github.com/rikispiks-max/openclaw-mission-control) - Ultra-premium dashboard with Next.js 15 + Convex + Tailwind CSS v4 + Framer Motion, glass morphism design ⭐ NEW
- [personal-agent](https://github.com/hackeshackes/personal-agent) - Chinese personal AI agent (iOS/Android app)
- [openclaw-multi-brain](https://github.com/Dannydvm/openclaw-multi-brain) - Multi-brain agent coordination system
- [clawstr](https://github.com/clawstr/clawstr) - Social network for AI agents on Nostr
- [SecurityClaw](https://github.com/mallen-lbx/SecurityClaw) - Python security toolkit for OpenClaw agents
- [openclaw-story](https://github.com/darwintree/openclaw-story) - TypeScript-based OpenClaw storytelling project
- [ZeroPointRepo/youtube-skills](https://github.com/ZeroPointRepo/youtube-skills) - YouTube Transcript API skills for AI agents
- [voocel/openclaw-mini](https://github.com/voocel/openclaw-mini) - Minimalist OpenClaw core architecture implementation
- [JasonHonKL/PardusClawer](https://github.com/JasonHonKL/PardusClawer) - OpenClaw for data scientists
- [openakita/openakita](https://github.com/openakita/openakita) - Open-source AI assistant framework with skills and agent architecture
- [openclaw-cloud](https://github.com/openperf/openclaw-cloud) - Give your AI Agent a cloud-native life
- [cloud-claw](https://github.com/miantiao-me/cloud-claw) - Run OpenClaw with One Click on Cloudflare Containers
- [openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) - OpenClaw deployment with Coolify
- [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) - Moltbot skill library for crypto trading, DeFi, automation
- [JamesTsetsekas/openclaw-skill-lnbits](https://github.com/JamesTsetsekas/openclaw-skill-lnbits) - LNbits Wallet Manager for OpenClaw
- [DevelopmentCats/homeassistant-assist](https://github.com/DevelopmentCats/homeassistant-assist) - Home Assistant skill using Assist API
- [shimaenaga1123/rustclaw](https://github.com/shimaenaga1123/rustclaw) - Rust-based Discord AI assistant
- [hankl/microbot](https://github.com/hankl/microbot) - Lightweight personal AI assistant
- [OrangeClaw/sparkinsight](https://github.com/OrangeClaw/sparkinsight) - Cross-agent memory system with ORANGE token rewards
- [wkyleg/personal-genomics](https://github.com/wkyleg/personal-genomics) - Analyze your DNA with OpenClaw
- [penggaolai/ai-news-app](https://github.com/penggaolai/ai-news-app) - Daily Top 10 AI news dashboard with glassmorphism UI
- [riphook](https://github.com/merciagents/riphook) - Deterministic security layer for OpenClaw, Cursor and Claude Code
- [AionUi](https://github.com/iOfficeAI/AionUi) - Free, local, open-source 24/7 Cowork and OpenClaw for multiple AI CLI tools (⭐ 12.4k)
- [MarketBot](https://github.com/EthanAlgoX/MarketBot) - Finance-customized OpenClaw with desktop Electron app and market intelligence ⭐ NEW
- [astra-os](https://github.com/rosakowski/astra-os) - Personal AI operating system built on OpenClaw. Automated workflows, sub-agents, and scheduled tasks for life management
- [openclaw-agents-team-skill](https://github.com/liuqin164/openclaw-agents-team-skill) - YAML-based Multi-Agent software development workflow for OpenClaw
- [english-learning-app](https://github.com/kongpemg1212-code/english-learning-app) - Interactive English Learning App powered by OpenClaw
- [ftw](https://github.com/SmokeAlot420/ftw) - First Try Works - vibecoding takes 47 tries, FTW takes one. Multi-agent validation workflow for Claude Code and OpenClaw
- [ra-men-skills](https://github.com/ra-men-org/openclaw-skills) - OpenClaw agent skills - /remember, /recall, options scanner, X timeline analyzer

*Have a project? [Add it here!](./CONTRIBUTING.md)*

---

## Regional Resources

### Thailand / ไทย

- [Openclaw-Thailand-Guide](https://github.com/JonusNattapong/Openclaw-Thailand-Guide) - OpenClaw setup guide and resources for Thailand

### Chinese / 中文资源

- [OpenClawChineseTranslation](https://github.com/1186258278/OpenClawChineseTranslation) - Complete Chinese localization with tutorials
- [openclaw-china](https://github.com/BytePioneer-AI/openclaw-china) - Chinese plugins for Feishu, DingTalk, QQ, WeCom, WeChat
- [OpenClaw-Docker-CN-IM](https://github.com/justlovemaki/OpenClaw-Docker-CN-IM) - Docker with pre-configured Chinese IM platform integrations
- [openclaw-feishu](https://github.com/AlexAnys/openclaw-feishu) - Feishu/Lark bot integration
- [openclaw-plugin-wecom](https://github.com/sunnoy/openclaw-plugin-wecom) - Enterprise WeChat (WeCom) AI bot plugin
- [openclaw-channel-dingtalk](https://github.com/soimy/openclaw-channel-dingtalk) - DingTalk bot channel plugin
- [dingtalk-moltbot-connector](https://github.com/DingTalk-Real-AI/dingtalk-moltbot-connector) - DingTalk DEAP Agent connector with AI Card streaming ⭐ 1.1k
- [openclaw-setup](https://github.com/anomixer/openclaw-setup) - Quick setup guide with Ollama + Telegram
- [clawdbot-ai/awesome-openclaw-skills-zh](https://github.com/clawdbot-ai/awesome-openclaw-skills-zh) - Chinese skill library translation
- [mozi](https://github.com/King-Chau/mozi) - Lightweight Clawdbot for Chinese LLMs with Feishu/Dingding/WeCom/QQ support
- [OpenClawInstaller](https://github.com/miaoxworld/OpenClawInstaller) - One-click deployment tool for ClawdBot
- [xiaomo-starter-kit](https://github.com/mengjian-github/xiaomo-starter-kit) - Chinese AI assistant template with 5-minute setup

---

## Community

- [Discord](https://discord.com/invite/clawd) - Real-time chat
- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Long-form questions
- [Blog: Remy COO](https://remy-coo.dev) - Daily insights from an AI COO using OpenClaw *(coming soon)*

---

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for how to add skills, tools, or projects.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.

<!-- Last updated: 2026-02-25T10:00Z by Awesome-OpenClaw Updater --> <!-- Removed: Duplicate entries (clawflow x2, scallopbot x1), list verified clean -->