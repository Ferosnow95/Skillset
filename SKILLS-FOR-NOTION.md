# Ali Zafar's Skill Pack

A personal, continuously-updated collection of Claude Code skills I keep around as I experiment with projects and refine my workflows. Each entry is vendored from its original public source (or linked where it's a product/MCP workflow), organized by theme.

> **Legend** — ✅ Vendored (content lives in the repo) · 🔗 Catalog-only (install from source)
> **Repo** — [github.com/Ferosnow95/Skillset](https://github.com/Ferosnow95/Skillset)

---

## 🧠 Thinking & Strategy

### 📋 /prd-generator

- **What it does** — Transforms a rough product idea into a structured Product Requirements Document. Asks targeted clarifying questions to define goals, scope, user stories, acceptance criteria, and success metrics — then generates a complete Markdown PRD ready for engineering handoff.
- **When to use it** — Before a feature goes into design or development. When an idea exists but the requirements are still fuzzy and stakeholders aren't aligned on what "done" looks like.
- **Why it matters** — Most scope creep starts with an underdefined brief. A PRD forces the conversation upstream — before designs are made and before code is written.
- **My take** — The value isn't the document itself. It's the questions it forces you to answer. Running this before a project kicks off consistently surfaces assumptions that would have caused rework later.
- **Source** — [github.com/dredozubov/prd-generator](https://github.com/dredozubov/prd-generator) · ✅
- **Invoke** — `/create-prd`

### 📊 /benchmark

- **What it does** — Conducts a structured competitive analysis comparing UX patterns, features, strengths, and gaps.
- **When to use it** — Whenever I start working in a problem space / field / competitive landscape I'm not familiar with.
- **Why it matters** — Understanding what others are doing well or poorly often helps to understand constraints.
- **My take** — Good starting point.
- **Source** — [Owl-Listener/designer-skills · ux-strategy](https://github.com/Owl-Listener/designer-skills/tree/main/ux-strategy) · ✅
- **Invoke** — `/ux-strategy:benchmark`

### 🎯 /strategize

- **What it does** — Develops a complete UX strategy for a product or feature area.
- **When to use it** — Before committing to a design direction.
- **Why it matters** — Most design issues originate upstream.
- **My take** — The value is in surfacing assumptions. If everything looks obvious after running it, you probably didn't push it far enough.
- **Source** — [Owl-Listener/designer-skills · ux-strategy](https://github.com/Owl-Listener/designer-skills/tree/main/ux-strategy) · ✅
- **Invoke** — `/ux-strategy:strategize`

### 🧠 /layers-user-needs

- **What it does** — Identifies and structures user needs by separating functional, emotional, and social needs from underlying motivations.
- **When to use it** — After initial discovery, or whenever a problem statement starts to feel solution-focused rather than user-focused.
- **Why it matters** — Teams often jump from observations directly into features. This skill helps distinguish what users are actually trying to achieve.
- **My take** — It forces a shift from "What should we build?" to "What need are we serving?" The output is rarely the final answer, but it consistently reveals assumptions hiding inside product requirements.
- **Source** — [jamiemill/layers-skills](https://github.com/jamiemill/layers-skills) · [layers.jamiemill.com](https://layers.jamiemill.com/skills/user-needs) · ✅
- **Invoke** — `/layers-user-needs`

### 🔭 /discover

- **What it does** — Runs structured discovery and opportunity mapping.
- **When to use it** — At the start of ambiguous or 0→1 projects.
- **Why it matters** — Discovery is usually rushed and inconsistent.
- **My take** — Excellent for understanding the landscape. Not a substitute for judgment.
- **Source** — [Owl-Listener/designer-skills · design-research](https://github.com/Owl-Listener/designer-skills/tree/main/design-research) · ✅
- **Invoke** — `/design-research:discover`

### 🧩 /impeccable shape

- **What it does** — Runs a structured discovery interview before any UI work begins. Asks targeted questions about purpose, users, content, constraints, and intent — then produces a `brief.md` design brief that implementation skills can read before writing a single line of code.
- **When to use it** — Before a feature starts. When a ticket is vague, when the team is about to argue about UI before aligning on intent, or when you catch yourself writing code to figure out what the product should actually do.
- **Why it matters** — Most AI-generated UIs fail not because of bad code, but because of skipped thinking. The model jumps straight to "here is a card grid" without asking what the user is trying to accomplish. `/impeccable shape` inverts that order.
- **My take** — The interview is maybe 5 minutes. The rewrites it prevents are measured in hours. The brief it produces isn't a spec — it's a compass. That distinction matters: it captures intent, not UI, which leaves room for the implementation to be good.
- **Source** — [impeccable.style/docs/shape](https://impeccable.style/docs/shape) · 🔗
- **Invoke** — `/impeccable shape`

---

## 🎨 Design Systems & UI Architecture

### 📄 /impeccable document

- **What it does** — Scans a codebase and generates a structured `DESIGN.md` file documenting the system.
- **When to use it** — Once a visual language has started stabilizing.
- **Why it matters** — Documentation almost never keeps up with reality.
- **My take** — The most practical design-system documentation workflow I've seen.
- **Source** — [impeccable.style/docs/document](https://impeccable.style/docs/document) · 🔗
- **Invoke** — `/impeccable document`

### 🎨 /tailwind-design-system

- **What it does** — Evaluates tokens, theming, dark mode, and component variants.
- **When to use it** — When building systems tightly coupled to code.
- **Why it matters** — Design systems increasingly live in code, not Figma.
- **My take** — Especially useful for designers working directly with engineers.
- **Source** — [wshobson/agents](https://github.com/wshobson/agents) · [marketplace](https://claudemarketplaces.com/skills/wshobson/agents/tailwind-design-system) · ✅
- **Invoke** — Auto-activates (part of the `frontend-mobile-development` plugin)

### 🔎 /audit-system

- **What it does** — Audits consistency, completeness, accessibility, and token usage across a full design system.
- **When to use it** — Before scaling or redesigning a product.
- **Why it matters** — Design systems drift.
- **My take** — Usually confirms what you already suspect is broken.
- **Source** — [Owl-Listener/designer-skills · design-systems](https://github.com/Owl-Listener/designer-skills/tree/main/design-systems) · ✅
- **Invoke** — `/design-systems:audit-system`

### 🧩 /extract-design-system

- **What it does** — Extracts design tokens, component patterns, naming conventions, and visual foundations from an existing codebase (or any public website — colors, typography, spacing, border radius, shadows) and generates JSON / CSS custom properties.
- **When to use it** — When inheriting products or auditing mature systems.
- **Why it matters** — Most teams don't actually know the system they have.
- **My take** — One of the fastest ways to understand design debt.
- **Source** — [arvindrk/extract-design-system](https://github.com/arvindrk/extract-design-system) · [marketplace](https://claudemarketplaces.com/skills/arvindrk/extract-design-system/extract-design-system) · ✅
- **Invoke** — `/extract-design-system`

---

## 🛠️ Design → Build

### 👩🏼‍💻 /frontend-design

- **What it does** — Overcomes the generic AI look by banning overused fonts and forcing the model to commit to an explicit aesthetic direction up front.
- **When to use it** — When I want to prototype quickly without an existing design system.
- **Why it matters** — Actively prevents the homogenized look that plagues AI-aided outputs.
- **My take** — Anthropic's version has 277,000+ installs as of March 2026. OpenAI's parallel skill for Codex was published shortly thereafter. Enough said.
- **Source** — [anthropics/skills · frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) · ✅
- **Invoke** — Auto-activates (or `/frontend-design`)

### 🧩 /shadcn

- **What it does** — A collection of accessible, beautifully designed components built on Radix UI and Tailwind CSS. Unlike a traditional library, you copy components directly into your project — you own the code and can modify anything. Pick a style and download your base system at [ui.shadcn.com/create](https://ui.shadcn.com/create).
- **When to use it** — When I'm focused on testing or prototyping a system solution or infrastructure and I want a clean, ready-made UI without spending time on component design decisions that don't matter yet.
- **Why it matters** — Prototyping stalls when UI work becomes a distraction. shadcn gives you a complete, accessible component set you can drop in immediately — so the focus stays on the thing you're actually trying to validate.
- **My take** — The "copy, don't install" model is underrated. You're not locked into a package's opinions — you get the component, you own it, you modify it. That's the right tradeoff for design-adjacent prototyping.
- **Source** — [github.com/shadcn-ui/ui](https://github.com/shadcn-ui/ui) · [ui.shadcn.com](https://ui.shadcn.com) · 🔗
- **Invoke** — `npx shadcn@latest add <component>`

### 🔗 Figma Implement Design

- **What it does** — Converts Figma designs into implementation-ready code.
- **When to use it** — After design decisions are finalized.
- **Why it matters** — Design-to-code translation remains one of the largest sources of friction.
- **My take** — The most compelling Figma MCP workflow available today.
- **Source** — [github.com/figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) · 🔗
- **Invoke** — No command needed — works via natural language once the Figma MCP is installed.

### ⚡ /interaction-design

- **What it does** — Creates flows, states, transitions, and interaction logic.
- **When to use it** — Before designing screens.
- **Why it matters** — Most UX failures are interaction failures.
- **My take** — If the logic isn't working here, UI polish won't save it.
- **Source** — [cuellarfr/design-skills · interaction-design](https://github.com/cuellarfr/design-skills/tree/main/interaction-design) · ✅
- **Invoke** — `/interaction-design`

### 🌀 /impeccable live

- **What it does** — Iterates directly on production UI and writes variants back into code. Pick a real element in your dev server, annotate it, generate three variants, accept the one you want, and have it written back to source.
- **When to use it** — While refining existing interfaces.
- **Why it matters** — Collapses the gap between exploration and implementation.
- **My take** — Probably the closest thing to "designing in code" that feels natural today.
- **Source** — [impeccable.style/tutorials/iterate-live](https://impeccable.style/tutorials/iterate-live) · 🔗
- **Invoke** — `/impeccable live`

### 🔌 Figma Code Connect

- **What it does** — Connects Figma components directly to production code.
- **When to use it** — During implementation and handoff.
- **Why it matters** — Reduces divergence between design and engineering.
- **My take** — Less flashy than AI generation. Far more useful.
- **Source** — [github.com/figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) · [figma/code-connect](https://github.com/figma/code-connect) · 🔗
- **Invoke** — No command needed — works via natural language once the Figma MCP is installed.

---

## 🧰 Figma Plugin Development

### 🧰 figma-plugin-builder

- **What it does** — Hard-won, battle-tested knowledge for building any Figma plugin in TypeScript. Covers project scaffolding, the esbuild bundling requirement, the main-thread/UI split and message passing, the prototyping/reactions API, the dynamic-page document model, coordinate-system rules (the #1 source of bugs), fonts, thumbnails, node tagging, live document watchers, the Figma UI3 design system, and a long list of gotchas that each cost real debugging time.
- **When to use it** — Read this before writing a new Figma plugin so you start from working patterns instead of rediscovering the traps.
- **Why it matters** — Figma's plugin runtime has sharp edges — coordinate systems, the sandbox/UI split, font loading — that aren't obvious from the docs and routinely cost hours.
- **My take** — Every rule marked GOTCHA caused an actual bug. This is the playbook I wish I'd had before building Luma.
- **Source** — Original — extracted from shipping the Luma presentation toolbox plugin · ✅
- **Invoke** — Auto-activates when building a Figma plugin

---

*Catalog originally curated from [Flora Ghnassia's Notion collection](https://floraghnassia.notion.site/Claude-Code-Skills-for-Product-Designers-who-want-to-build-3742aec4753680bf89f9c8bd51b318d8); maintained and extended by Ali Zafar.*
