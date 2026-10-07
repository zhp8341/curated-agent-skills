# Curated Agent Skills

**English** | [简体中文](README.zh-CN.md)

[![Skills](https://img.shields.io/badge/skills-110-4f46e5)](https://aibars.net/en/skills)
[![License](https://img.shields.io/badge/list-MIT-green)](#license)

A hand-picked directory of **110 Skills** for Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI and other AI coding agents. Every Skill is checked before it is listed, most are tried for real with a recorded demo, and each one shows its source, license and risk notes. Anything we have not tried ourselves is clearly marked.

**Browse with demos and search: [aibars.net/en/skills](https://aibars.net/en/skills)**

> A Skill is a folder with a `SKILL.md` that teaches an AI agent how to do one kind of task well. This page is the index; each link opens the Skill's page with its demo, risk notes and install command.

## How we curate

1. **License checked.** Skills with no license, a proprietary license or an unclear one are not listed.
2. **Source read.** We read `SKILL.md` and every file that comes with it, scripts included, and look for anything that deletes, overwrites, reads secrets or downloads and runs code.
3. **Tried for real.** We run each Skill in a clean environment with a realistic request. The demo on its page is the recorded output, shown unmodified. Where a result was wrong or only partly checked, the page says so.
4. **Risk labeled.** Every Skill has a risk note, and many carry a level (low, medium, high). Skills that run scripts, need network access, credentials or control a real browser say so up front.
5. **Honest about gaps.** One Skill we could not try (for example because it needs a real GitHub account) is marked **⚠️ Not tried**.

AI models did the review and the trials, so please read the source and the risk notes before you use a Skill. Nothing here is a guarantee.

## Editor's picks

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Frontend Design](https://aibars.net/en/skills/894605620081332224) | Guidance for building distinctive, intentional UI instead of templated defaults: plan the design first, then build. | Anthropic | Apache-2.0 | — | ✅ |
| [Theme Factory](https://aibars.net/en/skills/894605634199359488) | Apply one of 10 ready-made color and font themes to slides, docs, reports or landing pages, or generate a new theme on the fly. | Anthropic | Apache-2.0 | — | ✅ |
| [E-commerce Unit Economics](https://aibars.net/en/skills/895611922827972608) · Original | Find out what one order really earns after product cost, shipping, fees, returns and ads, then get break-even and target ROAS or CPA, a price for a target margin, and a check on how deep a discount can go. | AIBars | MIT | Low | ✅ |
| [Image Prompt Writing](https://aibars.net/en/skills/895622597725917184) · Original | Turn a vague idea into a clear prompt for an AI image generator: subject, setting, composition, light, style and color in a sensible order, with a short version, a detailed version and variations. | AIBars | MIT | Low | ✅ |
| [Short Video Script](https://aibars.net/en/skills/895769885358166016) · Original | Write a script you can film today for TikTok, Reels or Shorts: three hook options, a beat sheet with visuals, on-screen text and spoken lines, a call to action, a caption and a shot list. | AIBars | MIT | Low | ✅ |
| [Social Reply Playbook](https://aibars.net/en/skills/895769901091000320) · Original | Answer comments, DMs and public reviews calmly and honestly: sort the message, pick a response pattern, get a short public reply plus a private follow-up, and know when not to reply without a decision first. | AIBars | MIT | Low | ✅ |
| [Internal Comms](https://aibars.net/en/skills/894605627295535104) | Write internal communications in fixed company formats: 3P updates, company newsletters, FAQ answers and general announcements. | Anthropic | Apache-2.0 | — | ✅ |
| [Security Threat Model](https://aibars.net/en/skills/895740488542588928) | Threat model a code repository: trust boundaries, assets, attacker capabilities, concrete abuse paths and mitigations tied to real files, written up as one concise Markdown report. | OpenAI | Apache-2.0 | Medium | ✅ |
| [Systematic Debugging](https://aibars.net/en/skills/895089901731844096) | Find the root cause before you fix anything: a four-phase process of evidence, patterns, one hypothesis at a time and a tested fix, with a stop rule after three failed attempts. | Jesse Vincent | MIT | Medium | ✅ |
| [Conversion Copywriting](https://aibars.net/en/skills/895074689435832320) | Write and rewrite marketing copy for homepages, landing, pricing and feature pages: clear headlines, strong CTAs, page structure, and a strict list of AI tells to avoid. | Corey Haines | MIT | Low | ✅ |
| [Conversion Rate Optimization (CRO)](https://aibars.net/en/skills/895074761183596544) | Analyse a marketing page or form and get ranked recommendations: value proposition, headline, CTA, trust signals, objections and friction, with test ideas and copy alternatives. | Corey Haines | MIT | Low | ✅ |

## All Skills by category

Legend: **Original** = written by AIBars (MIT) · **Risk**: Low / Medium / High, "—" means not rated yet (read the risk note on the page) · **Tried**: ✅ run for real with a recorded demo, ⚠️ not tried.

### Web & UI Design (14)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Frontend Design](https://aibars.net/en/skills/894605620081332224) | Guidance for building distinctive, intentional UI instead of templated defaults: plan the design first, then build. | Anthropic | Apache-2.0 | — | ✅ |
| [Theme Factory](https://aibars.net/en/skills/894605634199359488) | Apply one of 10 ready-made color and font themes to slides, docs, reports or landing pages, or generate a new theme on the fly. | Anthropic | Apache-2.0 | — | ✅ |
| [Algorithmic Art](https://aibars.net/en/skills/894631082325184512) | Turns a theme into a short generative-art manifesto, then builds an interactive p5.js piece with seed navigation, parameter sliders and PNG export. | Anthropic | Apache-2.0 | — | ✅ |
| [Design System (tokens and slides)](https://aibars.net/en/skills/894877786756616192) | Build a three-layer design token system (primitive, semantic, component), write component specs, and generate token-compliant HTML slide decks with Chart.js. | claudekit | MIT | Medium | ✅ |
| [Light and Dark Theme](https://aibars.net/en/skills/895472103242076160) · Original | Build light and dark mode that is correct in both: semantic color tokens, the system setting plus a manual toggle, no flash of the wrong theme on load, and contrast checked in both themes. | AIBars | MIT | Low | ✅ |
| [Penpot UI/UX Design (via Penpot MCP)](https://aibars.net/en/skills/894931597240045568) | Design web, mobile and desktop interfaces inside Penpot through its MCP server, with design-system checks, component and accessibility rules and platform sizes. | awesome-copilot community | MIT | Medium | ✅ |
| [Responsive Layout Debugging](https://aibars.net/en/skills/895472114449256448) · Original | Find the real cause of layout bugs at specific screen widths: sideways scrolling, overflow, flex items that will not shrink, sticky that does not stick, 100vh on phones, and fixed bars under the browser UI. | AIBars | MIT | Low | ✅ |
| [UI Internationalization (i18n)](https://aibars.net/en/skills/895472119838937088) · Original | Make an interface carry any language without redesign: message catalogs, locale-aware formatting, layouts that survive different text lengths, CJK and right-to-left support, and language switching with proper URLs. | AIBars | MIT | Low | ✅ |
| [UI States Checklist](https://aibars.net/en/skills/895472127283826688) · Original | List every state a screen or component needs: loading, empty, error, partial, disabled, offline, permission denied and extreme content, and decide what the user sees and can do in each. | AIBars | MIT | Low | ✅ |
| [UI Styling (shadcn/ui + Tailwind)](https://aibars.net/en/skills/894877751998418944) | Guidance for building accessible, responsive interfaces with shadcn/ui and Tailwind CSS, including dark mode, theming and a canvas-based visual design approach. | claudekit | MIT | Medium | ✅ |
| [UI/UX Pro Max](https://aibars.net/en/skills/894877714409066496) | A searchable design knowledge base for interfaces: styles, color palettes, font pairings, UX guidelines, charts and stack-specific tips, used to pick a visual direction before you build. | NextLevelBuilder | MIT | Medium | ✅ |
| [Web Accessibility Audit (WCAG 2.2 AA)](https://aibars.net/en/skills/895472135974424576) · Original | Audit a page or component against WCAG 2.2 level AA: keyboard, focus, contrast, names and labels, structure, forms, dialogs, dynamic updates, zoom and target size, with each finding tied to a success criterion. | AIBars | MIT | Low | ✅ |
| [Web Artifacts Builder](https://aibars.net/en/skills/894637271385640960) | Build complex, self-contained React web artifacts with TypeScript, Tailwind CSS, and shadcn/ui. | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [Web Design Reviewer](https://aibars.net/en/skills/894931631889190912) | Inspect a running website for layout, responsive, accessibility and consistency problems, then fix them in the source code with minimal changes and re-check. | awesome-copilot community | MIT | Medium | ✅ |

### E-commerce (7)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [E-commerce Unit Economics](https://aibars.net/en/skills/895611922827972608) · Original | Find out what one order really earns after product cost, shipping, fees, returns and ads, then get break-even and target ROAS or CPA, a price for a target margin, and a check on how deep a discount can go. | AIBars | MIT | Low | ✅ |
| [E-commerce Weekly Review](https://aibars.net/en/skills/895612367965261824) · Original | Turn store numbers into a short weekly or monthly report: which metrics to track and how they are defined, why revenue or conversion moved, what is signal and what is noise, and what to do next. | AIBars | MIT | Low | ✅ |
| [Inventory Replenishment Planning](https://aibars.net/en/skills/895612131565899776) · Original | Decide what to reorder, how much and when: reorder point, safety stock, lead time, days of cover, ABC classes, dead stock and cash limits, planned per SKU from real sales history. | AIBars | MIT | Low | ✅ |
| [Product Listing Optimization](https://aibars.net/en/skills/895612026951569408) · Original | Make a product listing easy to find and easy to trust: title, bullets, description, images, variants and keywords, built only from true, provable claims and written for the shopper rather than the algorithm. | AIBars | MIT | Low | ✅ |
| [Promotion Campaign Planning](https://aibars.net/en/skills/895612211542888448) · Original | Plan an online sale so it earns profit, not just orders: goal and margin floor, offer type, calendar, stock and support readiness, and a review against a baseline afterwards. | AIBars | MIT | Low | ✅ |
| [Returns and Refunds Playbook](https://aibars.net/en/skills/895612293981933568) · Original | Handle returns, refunds, damaged or lost parcels, chargebacks and angry messages fairly and with little loss: policy points, a case-handling process, reply drafts, escalation rules and a way to find why returns are high. | AIBars | MIT | Low | ✅ |
| [Shopify Review Triage](https://aibars.net/en/skills/894885799689195520) | Turn public low-star Shopify App Store reviews you paste in into a P0-P3 brief with owners, next actions and an explicit bucket for items a human must read. | Shopify App Review Brief (independent) | MIT | Low | ✅ |

### Image & Video (5)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Image Prompt Writing](https://aibars.net/en/skills/895622597725917184) · Original | Turn a vague idea into a clear prompt for an AI image generator: subject, setting, composition, light, style and color in a sensible order, with a short version, a detailed version and variations. | AIBars | MIT | Low | ✅ |
| [Image Prompt Debugging](https://aibars.net/en/skills/895622641216655360) · Original | Find out why an AI image prompt gives messy, wrong or inconsistent pictures and fix it with the fewest changes: contradictions, clutter, mixed styles, ignored details, bad hands and garbled text. | AIBars | MIT | Low | ✅ |
| [Image Series Consistency](https://aibars.net/en/skills/895622770577379328) · Original | Make a set of AI images look like one set: a reusable style sheet and character sheet, fixed and variable parts of every prompt, reference-image workflow and a check for drift across pages. | AIBars | MIT | Low | ✅ |
| [Poster and Design Prompts](https://aibars.net/en/skills/895622728336543744) · Original | Write prompts for posters, cards, covers and social graphics, and decide what the AI should draw and what to typeset yourself: layout, hierarchy, palette, empty areas for text and exact wording. | AIBars | MIT | Low | ✅ |
| [Product Image Prompts](https://aibars.net/en/skills/895622685193932800) · Original | Write prompts for AI product images that stay honest: plain-background hero shots, lifestyle scenes, flat lays, detail close-ups, scale shots and mockups, matched to the real product. | AIBars | MIT | Low | ✅ |

### Social Content (8)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Short Video Script](https://aibars.net/en/skills/895769885358166016) · Original | Write a script you can film today for TikTok, Reels or Shorts: three hook options, a beat sheet with visuals, on-screen text and spoken lines, a call to action, a caption and a shot list. | AIBars | MIT | Low | ✅ |
| [Social Reply Playbook](https://aibars.net/en/skills/895769901091000320) · Original | Answer comments, DMs and public reviews calmly and honestly: sort the message, pick a response pattern, get a short public reply plus a private follow-up, and know when not to reply without a decision first. | AIBars | MIT | Low | ✅ |
| [Content Repurposing](https://aibars.net/en/skills/895769896590512128) · Original | Turn one long piece (article, newsletter, transcript, talk) into platform-specific social posts without changing what it says: key points, exact quotes, format plan, drafts with a source map and a fidelity check. | AIBars | MIT | Low | ✅ |
| [Content Research Writer](https://aibars.net/en/skills/894706733459705856) | A writing partner for articles and newsletters: outlines, sharper hooks, research with citations and section-by-section feedback. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [LinkedIn Post Formatter](https://aibars.net/en/skills/894885868224122880) | Turn rough notes into a polished LinkedIn post with a strong hook, styled headings, clear structure and hashtags, ready to copy and paste. | awesome-copilot community | MIT | Low | ✅ |
| [Slack GIF Creator](https://aibars.net/en/skills/894637271385640961) | Create compact animated GIFs for Slack emoji and messages with Python and Pillow utilities. | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [Social Content Calendar](https://aibars.net/en/skills/895769879054127104) · Original | Plan a realistic posting calendar from your goal, audience and weekly time: a few content pillars, a rhythm per platform, a dated table of posts with hooks and calls to action, batching, and a review plan. | AIBars | MIT | Low | ✅ |
| [X Thread Writer](https://aibars.net/en/skills/895769892056469504) · Original | Write posts for X that say one thing clearly: a single sharp post, a thread, a quote post or a reply, with a standalone first post, one idea per post and an edit pass that cuts the filler. | AIBars | MIT | Low | ✅ |

### Office & Docs (11)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Internal Comms](https://aibars.net/en/skills/894605627295535104) | Write internal communications in fixed company formats: 3P updates, company newsletters, FAQ answers and general announcements. | Anthropic | Apache-2.0 | — | ✅ |
| [Convert Excel to Markdown](https://aibars.net/en/skills/894931862445887488) | Convert .xlsx workbooks into Markdown, with embedded images extracted and linked, so spreadsheet contents can be read, summarised and searched. | awesome-copilot community | MIT | Medium | ✅ |
| [File Organizer](https://aibars.net/en/skills/894706720520278016) | Analyses a messy folder, proposes a tidier structure and finds duplicates, then reorganises only after you approve the plan. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Invoice Organizer](https://aibars.net/en/skills/894706725737992192) | Reads a folder of invoices and receipts, renames them consistently, sorts them into folders and writes a CSV summary for your accountant. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [MarkItDown: Files to Markdown](https://aibars.net/en/skills/895740598513045504) | Convert PDF, Word, PowerPoint, Excel, HTML and other files to clean Markdown with Microsoft MarkItDown, for search, analysis and feeding documents to an AI, with safe local defaults. | K-Dense Inc. | MIT | Medium | ✅ |
| [Markdown to Word (.docx)](https://aibars.net/en/skills/894931730967040000) | Convert Markdown files into formatted Word documents with a title page, table of contents, styled tables and embedded PNG images, using a pure JavaScript script. | awesome-copilot community | MIT | Medium | ✅ |
| [Meeting Insights Analyzer](https://aibars.net/en/skills/894706738278961152) | Analyses your meeting transcripts for communication patterns such as conflict avoidance, hedging and speaking ratio, with timestamped examples and better phrasings. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Meeting Minutes](https://aibars.net/en/skills/894885833574977536) | Write concise, actionable minutes for internal meetings of up to an hour, with decisions and action items that always have an owner and a due date. | awesome-copilot community | MIT | Low | ✅ |
| [Slides (strategic HTML presentations)](https://aibars.net/en/skills/894881177427775488) | Plan and write persuasive HTML presentations: deck structure, a layout for each slide, copywriting formulas, and Chart.js charts, with keyboard navigation built in. | claudekit | MIT | Low | ✅ |
| [Spreadsheet Skill](https://aibars.net/en/skills/895740561389260800) | Create, edit, analyze and format Excel and CSV spreadsheets with Python: real formulas instead of pasted results, preserved formatting, sensible layouts, and checks before you rely on them. | OpenAI | Apache-2.0 | Medium | ✅ |
| [Tailored Resume Generator](https://aibars.net/en/skills/894706754812907520) | Tailors your resume to a specific job description, matching keywords and requirements to your real experience. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |

### Developer Productivity (37)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Security Threat Model](https://aibars.net/en/skills/895740488542588928) | Threat model a code repository: trust boundaries, assets, attacker capabilities, concrete abuse paths and mitigations tied to real files, written up as one concise Markdown report. | OpenAI | Apache-2.0 | Medium | ✅ |
| [Systematic Debugging](https://aibars.net/en/skills/895089901731844096) | Find the root cause before you fix anything: a four-phase process of evidence, patterns, one hypothesis at a time and a tested fix, with a stop rule after three failed attempts. | Jesse Vincent | MIT | Medium | ✅ |
| [Claude Academy Guide](https://aibars.net/en/skills/894633023834951681) | Add a relevant Claude Academy learning resource to answers about using Claude, only when there is a strong match. | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [Brainstorming (idea to approved design)](https://aibars.net/en/skills/895089866633908224) | Turn an idea into an approved design before any code is written: classify the task, ask one question at a time, compare approaches and get your sign-off at each stage. | Jesse Vincent | MIT | Medium | ✅ |
| [Caveman](https://aibars.net/en/skills/894685149437104128) | Makes your coding agent answer first and drop the filler, while keeping code, commands, paths and error messages exactly as they are. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman Commit](https://aibars.net/en/skills/894685158358388736) | Writes terse Conventional Commits messages that explain why, not what. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman Compress](https://aibars.net/en/skills/894685162250702848) | Shrinks memory files such as CLAUDE.md so they cost fewer input tokens, with validation and a backup of the original. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Caveman Review](https://aibars.net/en/skills/894685154373799936) | Turns code review into one line per finding: location, problem and fix, with an optional severity tag. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Changelog Generator](https://aibars.net/en/skills/894706715524861952) | Turns your git commits into a customer-friendly changelog, grouped by features, improvements, security and fixes. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Chrome DevTools Agent](https://aibars.net/en/skills/894931664827060224) | Control and inspect a live Chrome browser through the Chrome DevTools MCP: navigate, click, fill forms, take snapshots and screenshots, read the console and network, and profile performance. | awesome-copilot community | MIT | High | ✅ |
| [Diagnosing Bugs](https://aibars.net/en/skills/894699006293446656) | A six-phase loop for hard bugs: build a reproduction that fails on exactly this bug, minimise it, test ranked hypotheses, then fix with a regression test. | Matt Pocock | MIT | — | ✅ |
| [Domain Modeling](https://aibars.net/en/skills/894699033006968832) | Builds your project's shared vocabulary: challenges fuzzy terms, tests them with edge cases, and records them in GLOSSARY.md and ADRs. | Matt Pocock | MIT | — | ✅ |
| [Draw.io Diagram Generator](https://aibars.net/en/skills/894931796616286208) | Create, edit and validate draw.io diagram files with correct mxGraph XML: flowcharts, architecture, sequence, ER and UML class diagrams, with templates and helper scripts. | awesome-copilot community | MIT | Medium | ✅ |
| [Draw.io Diagrams and PNG Export](https://aibars.net/en/skills/894931763850383360) | Generate native .drawio diagrams and export them to PNG, SVG or PDF with the editable XML embedded, using a bundled Node.js export script. | awesome-copilot community | MIT | Medium | ✅ |
| [Excalidraw Diagram Generator](https://aibars.net/en/skills/894931829675790336) | Turn a plain-language description into an Excalidraw diagram file: flowcharts, mind maps, architecture, sequence, ER, class and swimlane diagrams, with templates and helper scripts. | awesome-copilot community | MIT | Medium | ✅ |
| [Fix Failing GitHub CI](https://aibars.net/en/skills/895740527281180672) | Debug a failing GitHub Actions check on a pull request: find the failing checks, pull the logs, summarize the cause, draft a fix plan, and change code only after you approve. | OpenAI | Apache-2.0 | Medium | ⚠️ Not tried |
| [Grilling](https://aibars.net/en/skills/894699000484335616) | Has your agent interview you in numbered rounds, with a recommended answer for each question, until every decision in your plan is settled. | Matt Pocock | MIT | — | ✅ |
| [Handoff](https://aibars.net/en/skills/894699014652694528) | Compacts the current conversation into a handoff document so a fresh agent session can pick the work up. | Matt Pocock | MIT | — | ✅ |
| [Incident Post-Mortem (blameless)](https://aibars.net/en/skills/894885971676631040) | Guide a team through a structured, blameless post-mortem: timeline, root cause with the 5 Whys, impact numbers and action items with owners and due dates. | awesome-copilot community | MIT | Medium | ✅ |
| [Investigate First](https://aibars.net/en/skills/894685166356926464) | Makes your agent find and prove the cause of a bug before it changes any code. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Markdown and Mermaid Writing](https://aibars.net/en/skills/895740636475691008) | Write Markdown documents with Mermaid diagrams for workflows, schemas, timelines and architecture: syntax guides for 21 diagram types, document templates, accessibility metadata and render checks. | Clayton Young / Superior Byte Works | Apache-2.0 | Medium | ✅ |
| [MCP Builder](https://aibars.net/en/skills/894625433763713024) | A guide for building high-quality MCP servers in TypeScript or Python: research, design, implementation, testing and evaluations. | Anthropic | Apache-2.0 | — | ✅ |
| [PR](https://aibars.net/en/skills/894699018884747264) | A pull request body template: the smallest diagram that explains the change, before and after evidence, and a merge-danger call. | Matt Pocock | MIT | — | ✅ |
| [Product Requirements Document (PRD)](https://aibars.net/en/skills/894886006292221952) | Write a PRD that links business goals to technical execution: problem, users, measurable requirements, non-goals, specs, risks and a phased roadmap. | awesome-copilot community | MIT | Low | ✅ |
| [Prototype](https://aibars.net/en/skills/894699023003553792) | Builds a throwaway prototype to answer one design question: a clickable HTML model for logic, or several UI variations to compare. | Matt Pocock | MIT | — | ✅ |
| [Receiving Code Review](https://aibars.net/en/skills/895090080384028672) | Handle review feedback with technical rigour: understand it, check it against the code, push back when it is wrong, clarify before acting and implement one item at a time. | Jesse Vincent | MIT | Medium | ✅ |
| [Requesting Code Review](https://aibars.net/en/skills/895090042102616064) | Hand a finished piece of work to a fresh reviewer: a code-reviewer prompt with the plan and the exact git range, graded findings, and rules for acting on them. | Jesse Vincent | MIT | Low | ✅ |
| [Security Review (AI code scanner)](https://aibars.net/en/skills/894885901493342208) | Review a codebase like a security researcher: trace user input to dangerous sinks, find injection, access-control and secrets problems, and get patches to review, never applied automatically. | awesome-copilot community | MIT | High | ✅ |
| [Skill Creator](https://aibars.net/en/skills/894631087484178432) | Guides you from an idea to a finished Agent Skill: intent capture, a SKILL.md draft, test prompts, optional eval runs and description tuning. | Anthropic | Apache-2.0 | — | ✅ |
| [Surgical Patch](https://aibars.net/en/skills/894685171004215296) | Fixes a bug at the narrowest layer that owns it, with a regression test and no unrelated cleanup. | Julius Brussee | Apache-2.0 | — | ✅ |
| [TDD](https://aibars.net/en/skills/894699010550665216) | Test-first development one thin slice at a time: write a failing test, make it pass, and test only at seams you agreed on. | Matt Pocock | MIT | — | ✅ |
| [Test-Driven Development (TDD)](https://aibars.net/en/skills/895089938880794624) | Write the failing test first, watch it fail, write the minimum code to pass, then refactor: the red-green-refactor loop with strict rules and a checklist. | Jesse Vincent | MIT | Medium | ✅ |
| [Verification Before Completion](https://aibars.net/en/skills/895090007650603008) | Evidence before claims: the model may not say work is done, fixed or passing until it has run the verification command in the same turn and read the output. | Jesse Vincent | MIT | Low | ✅ |
| [Verify and Stop](https://aibars.net/en/skills/894685175584395264) | Checks whether work meets its acceptance criteria and stops there, without adding scope. | Julius Brussee | Apache-2.0 | — | ✅ |
| [Web Application Testing](https://aibars.net/en/skills/894633023834951680) | Create Playwright automation for inspecting, testing, and debugging local web applications. | Anthropic, PBC | Apache-2.0 | — | ✅ |
| [Writing for Agents](https://aibars.net/en/skills/894699028359680000) | A reference for writing documents agents read, such as skills, CLAUDE.md and AGENTS.md, so they behave predictably. | Matt Pocock | MIT | — | ✅ |
| [Writing Implementation Plans](https://aibars.net/en/skills/895089973114703872) | Turn a spec into a step-by-step implementation plan another engineer can follow: exact files, interfaces, test-first steps with expected output and a self-review. | Jesse Vincent | MIT | Medium | ✅ |

### Brand & Marketing (26)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Conversion Copywriting](https://aibars.net/en/skills/895074689435832320) | Write and rewrite marketing copy for homepages, landing, pricing and feature pages: clear headlines, strong CTAs, page structure, and a strict list of AI tells to avoid. | Corey Haines | MIT | Low | ✅ |
| [Conversion Rate Optimization (CRO)](https://aibars.net/en/skills/895074761183596544) | Analyse a marketing page or form and get ranked recommendations: value proposition, headline, CTA, trust signals, objections and friction, with test ideas and copy alternatives. | Corey Haines | MIT | Low | ✅ |
| [A/B Testing and Experimentation](https://aibars.net/en/skills/895074798055723008) | Plan A/B tests that give valid results: hypothesis, sample size and duration, metrics, variants and analysis, plus a growth experimentation program with ICE scoring and a playbook. | Corey Haines | MIT | Low | ✅ |
| [Ad Campaign Analyzer](https://aibars.net/en/skills/894885732513222656) | Turn an ad performance export into clear decisions: what to pause, what to scale, what to test, and how to reallocate budget across channels. | GooseWorks | MIT | Medium | ✅ |
| [AI SEO](https://aibars.net/en/skills/894666349127929856) | Audit and improve how product content can be found, extracted, and cited in AI answers. | Corey Haines | MIT | — | ✅ |
| [Analytics Tracking](https://aibars.net/en/skills/894677603934539776) | Plan, audit, and troubleshoot GA4, GTM, UTM, conversion, and product-event tracking. | Corey Haines | MIT | — | ✅ |
| [Marketing Attribution](https://aibars.net/en/skills/895074935528230912) | Work out which marketing actually drives conversions: choose and read attribution models, reconcile conflicting numbers from ad platforms, analytics and CRM, and build first-party attribution. | Corey Haines | MIT | Low | ✅ |
| [Brand (voice, identity and consistency)](https://aibars.net/en/skills/894881226626961408) | Define and keep a brand consistent: voice and tone, visual identity, messaging, color and typography rules, asset naming and approval checklists, plus a starter brand guidelines template. | claudekit | MIT | Medium | ✅ |
| [Churn Prevention](https://aibars.net/en/skills/895074900270911488) | Reduce subscription churn: design cancel flows and save offers, predict at-risk customers, and recover failed payments with a dunning plan, retries and email sequences. | Corey Haines | MIT | Low | ✅ |
| [Cold Email Writing](https://aibars.net/en/skills/895074831769538560) | Write B2B cold emails and short follow-up sequences that read like a thoughtful human: personal, brief, one low-friction ask, with subject lines and benchmark data. | Corey Haines | MIT | Low | ✅ |
| [Competitor Ad Intelligence](https://aibars.net/en/skills/894885766411587584) | Study a competitor's public ads and landing pages to find their hooks, formats and weak spots, then turn the gaps into counter-play ideas. | GooseWorks | MIT | Medium | ✅ |
| [Content Strategy](https://aibars.net/en/skills/895074865365913600) | Plan what content to create and why: pillars and topic clusters, keyword research by buyer stage, idea sources, a scoring method for priorities and a 60/30/10 calendar. | Corey Haines | MIT | Low | ✅ |
| [Copy Editing (Seven Sweeps)](https://aibars.net/en/skills/895074725217439744) | Edit and improve existing marketing copy in seven focused passes: clarity, voice, so what, proof, specificity, emotion and risk, plus word-level checks and a content refresh routine. | Corey Haines | MIT | Low | ✅ |
| [Customer Research](https://aibars.net/en/skills/894677588361089024) | Synthesize interviews, surveys, support data, reviews, and public discussions into evidence-based customer insight. | Corey Haines | MIT | — | ✅ |
| [Domain Name Brainstormer](https://aibars.net/en/skills/894706749389672448) | Generates domain name ideas for your project across several extensions, and checks availability when your agent can look it up. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Positioning Strategy (go-to-market)](https://aibars.net/en/skills/894885590435368960) | Find a market position competitors cannot easily copy, and test the new wording with real buyers before you commit to a rebrand. | Smit Patel | MIT | Low | ✅ |
| [Product-Led Growth (go-to-market)](https://aibars.net/en/skills/894885625864654848) | Decide whether self-serve, sales-led or a hybrid fits your product, then measure channel economics, activation and growth with simple rules. | Smit Patel | MIT | Low | ✅ |
| [Technical Product Pricing](https://aibars.net/en/skills/894885661042282496) | Choose between seat-based, usage-based and hybrid pricing, set a freemium limit, handle enterprise price conversations and decide when to raise prices. | Smit Patel | MIT | Low | ✅ |
| [Landing Page Conversion Audit](https://aibars.net/en/skills/894885696479956992) | Audit a landing, sales or checkout page for conversion leaks and get a short fix list ranked by expected impact, with what you could not check stated up front. | awesome-copilot community | MIT | Medium | ✅ |
| [Launch Strategy](https://aibars.net/en/skills/895075006248390656) | Plan a product or feature launch: the ORB channel framework, a readiness gate, a five-phase rollout, Product Hunt tactics, post-launch actions and a checklist. | Corey Haines | MIT | Low | ✅ |
| [Lead Research Assistant](https://aibars.net/en/skills/894706744247455744) | Finds and ranks companies that fit your product, with the role to target and a tailored outreach approach for each. | ComposioHQ community contributors | Apache-2.0 | — | ✅ |
| [Offer Design](https://aibars.net/en/skills/895074971033014272) | Design or improve the thing you actually sell: value framing, bonus stacking, guarantee design and honest scarcity, with a value equation and a diagnostic loop. | Corey Haines | MIT | Low | ✅ |
| [Pricing Strategy](https://aibars.net/en/skills/894677614973947904) | Develop evidence-aware pricing, packaging, willingness-to-pay research, and pricing-page review plans. | Corey Haines | MIT | — | ✅ |
| [Programmatic SEO](https://aibars.net/en/skills/894677623232532480) | Plan scalable, data-backed SEO pages while protecting against thin content and indexation risk. | Corey Haines | MIT | — | ✅ |
| [SEO Audit](https://aibars.net/en/skills/894677560510910464) | Produce evidence-based technical, on-page, and multilingual SEO audits with prioritized fixes. | Corey Haines | MIT | — | ✅ |
| [Server-Side Conversion Tracking](https://aibars.net/en/skills/894931698423435264) | Fix under-reported ad conversions: capture click ids, carry them to the order, send purchases server-to-server to Facebook, TikTok, Google and Bing, dedupe and verify. | awesome-copilot community | MIT | Medium | ✅ |

### Research & Learning (2)

| Skill | What it does | Author | License | Risk | Tried |
|---|---|---|---|---|---|
| [Discernment Nudge](https://aibars.net/en/skills/894625433440751616) | After a substantive answer you may act on, adds 2-3 specific follow-up questions that help you check facts, probe the reasoning and notice missing context. | Anthropic | Apache-2.0 | — | ✅ |
| [Doublecheck (AI output verification)](https://aibars.net/en/skills/894885936842936320) | Check AI-written text: extract every verifiable claim, look for sources you can open yourself, and flag likely hallucinations in a structured report. | awesome-copilot community | MIT | Medium | ✅ |

## Install a Skill

Each Skill page has the exact command for your agent. For Claude Code, user level, it looks like this (replace `<skill-key>` with the Skill's key from its page, for example `frontend-design`):

```bash
curl -fsSL https://skill.aibars.net/skills/<skill-key>.zip -o skill.zip \
  && mkdir -p ~/.claude/skills/<skill-key> \
  && unzip -oq skill.zip -d ~/.claude/skills/<skill-key> \
  && rm skill.zip
```

Common folders (check your agent's documentation, they can change):

| Agent | User level | Project level |
|---|---|---|
| Claude Code | `~/.claude/skills/` | `.claude/skills/` |
| Codex | `~/.agents/skills/` | `.agents/skills/` |
| GitHub Copilot | `~/.copilot/skills/` | `.agents/skills/` |
| Cursor | `~/.cursor/skills/` | `.agents/skills/` |
| Gemini CLI | `~/.gemini/skills/` | `.agents/skills/` |
| Windsurf | `~/.codeium/windsurf/skills/` | `.windsurf/skills/` |

We have tested the install on Claude Code and GitHub Copilot CLI (user level). The other folders come from each agent's documentation or public lists. We have not tested this on Windows.

## Suggest a Skill or report a problem

Open an [issue](../../issues) with the Skill's link, what it does and why it is useful, or what went wrong. A Skill is only listed if its license allows it and we can read all of its files.

## License

The list and this README are released under the MIT License. **Each Skill keeps its own license**, shown in the table and on its page; the Skills marked Original are MIT, written by AIBars. Skills are third-party content provided as is, without warranty. Review a Skill before you let an agent run it.
