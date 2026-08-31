# Up2d8 — Technology Trends to Watch

> Evidence-led technology intelligence for engineering leaders. A new report every Monday at **[up2d8.com](https://up2d8.com)**.

This list is the machine-readable tail of Issue **2026-W36**. Every trend below was classified by
multi-day, multi-source consistency — never by a single spike — and every claim on the site
carries a source link and the measurement window it came from.

📄 **Read the full issue:** [Agent skill and plugin repos are the week's growth story — but star counts are doing all the talking](https://up2d8.com/report/2026-W36-agent-skill-and-plugin-repos-are-the-week-s-growth-story-but-star-counts-are-doing-all-the-talking)

| Ladder | Meaning |
|---|---|
| Durable shift | Sustained, structural change in the landscape backed by broad, lasting evidence. |
| Strong trend | Consistent, multi-source momentum with credible adoption evidence. |
| Emerging trend | Repeated signal across multiple days or source types; growing but unproven. |
| Early signal | A first credible indication worth watching; single source type or short window. |
| Noise | Isolated or vendor-driven signal with no corroboration; likely to fade. |

---

## DeepSeek harness and Ponytail: AI-agent skill/plugin repos post explosive multi-week star growth

**Strong trend** · Recommended action: **Experiment** · [Full analysis →](https://up2d8.com/trends/trend%3Adeepseek-harness-and-ponytail-ai-agent-skill-plugin-repos-post-explosive-multi-week-star-growth)

Both repos show sustained, multi-day GitHub deltas rather than one-off spikes: DeepSeek harness (dsh/CORDIS) grew from 169,431 to 196,035 stars (+26,604, ~4,434/day) over six days to 2026-08-26, and Ponytail grew from 92,538 to 115,615 stars (+23,077, ~+25%) over roughly 29 days to 2026-07-31; both are agent skill/plugin systems built for Claude Code and similar coding agents.

- [Ponytail](https://github.com/dietrichgebert/ponytail)
- [deepseek-ai/deepseek-harness — DeepSeek agent harness (dsh) / CORDIS workflow plugin system for LLM agents](https://github.com/deepseek-ai/deepseek-harness)

## AGENTS.md, Skills, and plugin conventions standardising how coding agents get instructions

**Emerging trend** · Recommended action: **Watch** · [Full analysis →](https://up2d8.com/trends/trend%3Aagents-md-skills-and-plugin-conventions-standardising-how-coding-agents-get-instructions)

A cluster of newly observed repos (each with first-observation star counts of 22k–27k within roughly a month of appearing) define or extend conventions for briefing AI coding agents — AGENTS.md spec, Anthropic's own knowledge-work plugins, agent skill/distillation tooling, and OpenAI's official skills repo — suggesting the ecosystem is converging on a shared configuration layer for agents rather than one-off vendor formats.

- [AgentSkills (agentskills/agentskills)](https://github.com/agentskills/agentskills)
- [JimLiu/baoyu-skills](https://github.com/jimliu/baoyu-skills)
- [agentsmd/agents.md — AGENTS.md specification and tooling for AI coding agents](https://github.com/agentsmd/agents.md)
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins)
- [claude-skills (alirezarezvani)](https://github.com/alirezarezvani/claude-skills)
- [i-have-adhd (ayghri)](https://github.com/ayghri/i-have-adhd)
- [openai/skills](https://github.com/openai/skills)
- [titanwings/distilly — agent skills/distillation library for AI coding agents (Claude Code, Codex, OpenCode, OpenClaw, Hermes; meta-skill, knowledge-distillation, digital-human, DSH plugin)](https://github.com/titanwings/distilly)

## Browser and GUI automation frameworks for AI agents gain parallel traction

**Emerging trend** · Recommended action: **Experiment** · [Full analysis →](https://up2d8.com/trends/trend%3Abrowser-and-gui-automation-frameworks-for-ai-agents-gain-parallel-traction)

Several independently maintained browser/GUI automation tools for AI agents (Stagehand, Skyvern, Obscura, Microsoft OmniParser) were each first observed this week with 22k–25k stars, spanning Playwright-based, vision-based, and headless-browser approaches — a repeated pattern across multiple projects and source types (GitHub plus limited Hacker News) rather than a single tool's spike.

- [Obscura (h4ckf0r0day/obscura)](https://github.com/h4ckf0r0day/obscura)
- [OmniParser](https://github.com/microsoft/omniparser)
- [Skyvern](https://github.com/skyvern-ai/skyvern)
- [Stagehand](https://github.com/browserbase/stagehand)

## MCP tooling continues to broaden beyond chat assistants into workflow and memory layers

**Emerging trend** · Recommended action: **Experiment** · [Full analysis →](https://up2d8.com/trends/trend%3Amcp-tooling-continues-to-broaden-beyond-chat-assistants-into-workflow-and-memory-layers)

Multiple independently-built MCP servers and MCP-adjacent memory layers were newly observed this week (each with 22k–25k first-seen stars), connecting agents to workflow automation (n8n), Python tooling (official MCP Python SDK), and long-term memory (TencentDB agent memory), indicating MCP is being adopted as connective tissue across categories rather than a single vendor feature.

- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)
- [TencentCloud/TencentDB-Agent-Memory — TencentDB-powered agent long-term memory / embedding layer (LLM, local-first, OpenClaw plugin, vector-search)](https://github.com/tencentcloud/tencentdb-agent-memory)
- [letta-ai/letta (formerly MemGPT)](https://github.com/letta-ai/letta)
- [n8n MCP Server (czlonkowski/n8n-mcp)](https://github.com/czlonkowski/n8n-mcp)

## RAG and long-context document/knowledge tooling remains a steady growth category

**Emerging trend** · Recommended action: **Watch** · [Full analysis →](https://up2d8.com/trends/trend%3Arag-and-long-context-document-knowledge-tooling-remains-a-steady-growth-category)

Multiple RAG-adjacent projects (MaxKB knowledgebase platform, RAG-Anything, Baidu's Unlimited OCR with a June HN post at 496 points/110 comments) were newly observed this week with 22k–24k stars each, indicating continued builder interest in retrieval and document-parsing infrastructure for LLM applications, though evidence per repo is still limited to single-day snapshots.

- [MaxKB](https://github.com/1panel-dev/maxkb)
- [RAG-Anything (HKUDS)](https://github.com/hkuds/rag-anything)
- [Unlimited OCR](https://github.com/baidu/unlimited-ocr)

## OpenAI Symphony orchestration spec emerges as a new agent-coordination standard contender

**Early signal** · Recommended action: **Watch** · [Full analysis →](https://up2d8.com/trends/trend%3Aopenai-symphony-orchestration-spec-emerges-as-a-new-agent-coordination-standard-contender)

Symphony, OpenAI's open-source orchestration spec announced via blog post (27 April 2026), has accumulated 26,933 stars and 2,761 forks with only 8 open issues, but evidence remains limited to two sources (blog announcement plus GitHub metrics) with no contributor, PR, or release data confirming real-world integration depth yet.

- [Symphony (OpenAI orchestration spec)](https://openai.com/index/open-source-codex-orchestration-symphony)

## Baseline sweep noise: single-day GitHub snapshots with no delta or corroborating evidence

**Noise** · Recommended action: **No strategic change** · [Full analysis →](https://up2d8.com/trends/trend%3Abaseline-sweep-noise-single-day-github-snapshots-with-no-delta-or-corroborating-evidence)

A large batch of mature, well-known repositories (Chalk, Doom Emacs, Ember.js, .NET MAUI, Iosevka, JHipster, and others) were observed for the first time this week with only a single static GitHub metrics point each and no release, PR, contributor, or community evidence, so no actual weekly movement can be established despite high absolute star counts.

- [.NET MAUI (dotnet/maui) — cross-platform UI framework](https://github.com/dotnet/maui)
- [A2ANet JS](https://github.com/a2anet/a2anet-js)
- [Angular Components (Angular Material)](https://github.com/angular/components)
- [Chalk](https://github.com/chalk/chalk)
- [DB Browser for SQLite (sqlitebrowser/sqlitebrowser) — cross-platform SQLite database GUI browser](https://github.com/sqlitebrowser/sqlitebrowser)
- [Doom Emacs](https://github.com/doomemacs/core)
- [Ember.js (emberjs/ember.js) — JavaScript application framework](https://github.com/emberjs/ember.js)
- [Go Micro (micro/go-micro) — Go microservices framework](https://github.com/micro/go-micro)
- [Gson](https://github.com/google/gson)
- [HandBrake — open-source video transcoder](https://github.com/handbrake/handbrake)
- [Hyper (vercel/hyper) — Electron-based terminal emulator built with React/JavaScript, cross-platform macOS/Linux/Windows](https://github.com/vercel/hyper)
- [Invidious — privacy-focused alternative YouTube frontend](https://github.com/iv-org/invidious)
- [Iosevka](https://github.com/be5invis/iosevka)
- [JHipster (generator-jhipster)](https://github.com/jhipster/generator-jhipster)
- [MagicMirror (MagicMirrorOrg/MagicMirror)](https://github.com/magicmirrororg/magicmirror)
- [Mocha (mochajs/mocha) — JavaScript test framework](https://github.com/mochajs/mocha)
- [NeoPass (Max-Eee/NeoPass)](https://github.com/max-eee/neopass)
- [Node-RED — flow-based low-code programming for event-driven applications and IoT](https://github.com/node-red/node-red)
- [Notable (notable/notable) — Markdown-based note-taking app (Linux, macOS, Windows)](https://github.com/notable/notable)
- [OpenManus](https://github.com/mannaandpoem/openmanus)
- [Pipenv](https://github.com/pypa/pipenv)
- [QuickLook (QL-Win)](https://github.com/ql-win/quicklook)
- [Ramda (functional programming library for JavaScript)](https://github.com/ramda/ramda)
- [React Navigation](https://github.com/react-navigation/react-navigation)
- [React-Bootstrap (React component library for Bootstrap)](https://github.com/react-bootstrap/react-bootstrap)
- [Tesseract.js](https://github.com/naptha/tesseract.js)
- [V8 (JavaScript/WebAssembly engine)](https://github.com/v8/v8)
- [Vonng/ddia — "Designing Data-Intensive Applications" Chinese translation / notes](https://github.com/vonng/ddia)
- [Winston](https://github.com/winstonjs/winston)
- [fastjson (Alibaba)](https://github.com/alibaba/fastjson)
- [felixrieseberg/windows95](https://github.com/felixrieseberg/windows95)
- [highlight.js (highlightjs) — JavaScript syntax highlighter](https://github.com/highlightjs/highlight.js)
- [hiring-without-whiteboards (poteto/hiring-without-whiteboards) — crowdsourced list of companies that hire without whiteboard-style coding interviews](https://github.com/poteto/hiring-without-whiteboards)
- [js-cookie (js-cookie/js-cookie) — lightweight JavaScript cookie library](https://github.com/js-cookie/js-cookie)
- [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/wand-enhancer)
- [keon/algorithms](https://github.com/keon/algorithms)
- [libGDX — cross-platform Java game development framework](https://github.com/libgdx/libgdx)
- [magic-wormhole/magic-wormhole](https://github.com/magic-wormhole/magic-wormhole)
- [redux-saga/redux-saga](https://github.com/redux-saga/redux-saga)
- [validator.js (validatorjs) — JavaScript string validation and sanitization library](https://github.com/validatorjs/validator.js)
- [zsh-syntax-highlighting (zsh-users/zsh-syntax-highlighting) — Fish-shell-like syntax highlighting for Zsh, enabling highlighting of commands, options, and arguments as they are typed](https://github.com/zsh-users/zsh-syntax-highlighting)

## ClawRAG and data-source mismatch noise in RAG/MCP tracking

**Noise** · Recommended action: **No strategic change** · [Full analysis →](https://up2d8.com/trends/trend%3Aclawrag-and-data-source-mismatch-noise-in-rag-mcp-tracking)

ClawRAG shows five consecutive days of flat metrics (153 stars, 28 forks, 1 open issue) with repeated evidence-source contamination from an unrelated repository (ultralytics/yolov5), indicating no genuine momentum behind the canonical project despite repeated observation.

- [ClawRAG](https://github.com/2dogsandanerd/clawrag)

---

## How this is produced

- A daily pipeline observes GitHub, Hacker News and the technical press.
- An analyst scores every signal 1-5 on each of 7 frozen dimensions: GitHub Momentum, Developer Adoption, Enterprise Relevance, Technical Maturity, Ecosystem Support, Differentiation, 6–12 Month Adoption Probability.
- A columnist writes only what that evidence supports.
- Classifications before 14 July 2026 are retrospective model estimates calculated from reconstructed repository data — they were not published or assessed at the time. Live classifications begin on 14 July 2026.

Machine-readable: [llms.txt](https://up2d8.com/llms.txt) · [RSS](https://up2d8.com/rss.xml)

_Updated weekly from Issue 2026-W36. Inclusion is an observation, not an endorsement._
