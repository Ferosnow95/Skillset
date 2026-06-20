# Skillset

**Ali Zafar's personal skill pack** — a curated, verified collection of Claude Code skills I keep updated as I experiment with projects and refine my workflows. Vendored from their original public sources, organized by theme, and documented so each entry can later become a Notion page.

This is a living repo: I add, swap, and prune skills as my work evolves. The initial catalog is adapted from Flora Ghnassia's [Claude Code Skills for Product Designers who want to build](https://floraghnassia.notion.site/Claude-Code-Skills-for-Product-Designers-who-want-to-build-3742aec4753680bf89f9c8bd51b318d8), with sources independently verified and full skill folders vendored where the source is openly licensed.

## How this repo is organized

```
Skillset/
├─ thinking-and-strategy/
├─ design-systems-and-ui-architecture/
├─ design-to-build/
└─ figma-plugin-development/
```

Each skill lives in its own folder containing:
- a **`README.md`** with the full description (What it does · When to use it · Why it matters · Curator's take · Source);
- the **vendored skill content** (`SKILL.md` / command `.md` + any `references`, `examples`, `templates`) when the source is openly available;
- the source **`LICENSE`** where applicable.

**Status legend:** ✅ Vendored (content included) · 🔗 Catalog-only (linked; install from source).

---

## 🧠 Thinking & Strategy

| Skill | What it does | Source | Status |
|---|---|---|---|
| [📋 /prd-generator](./thinking-and-strategy/prd-generator) | Turns a rough idea into a structured PRD via targeted clarifying questions. | [dredozubov/prd-generator](https://github.com/dredozubov/prd-generator) | ✅ |
| [📊 /benchmark](./thinking-and-strategy/benchmark) | Structured competitive analysis of UX patterns, features, strengths, gaps. | [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills/tree/main/ux-strategy) | ✅ |
| [🎯 /strategize](./thinking-and-strategy/strategize) | Develops a complete UX strategy for a product or feature area. | [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills/tree/main/ux-strategy) | ✅ |
| [🧠 /layers-user-needs](./thinking-and-strategy/layers-user-needs) | Separates functional, emotional, and social needs from motivations. | [jamiemill/layers-skills](https://github.com/jamiemill/layers-skills) | ✅ |
| [🔭 /discover](./thinking-and-strategy/discover) | Structured discovery and opportunity mapping for 0→1 work. | [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills/tree/main/design-research) | ✅ |
| [🧩 /impeccable shape](./thinking-and-strategy/impeccable-shape) | Discovery interview that produces a design brief before any UI. | [impeccable.style](https://impeccable.style/docs/shape) | 🔗 |

## 🎨 Design Systems & UI Architecture

| Skill | What it does | Source | Status |
|---|---|---|---|
| [📄 /impeccable document](./design-systems-and-ui-architecture/impeccable-document) | Scans a codebase and generates a structured `DESIGN.md`. | [impeccable.style](https://impeccable.style/docs/document) | 🔗 |
| [🎨 /tailwind-design-system](./design-systems-and-ui-architecture/tailwind-design-system) | Evaluates tokens, theming, dark mode, and component variants. | [wshobson/agents](https://github.com/wshobson/agents) | ✅ |
| [🔎 /audit-system](./design-systems-and-ui-architecture/audit-system) | Audits consistency, completeness, a11y, and token usage. | [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills/tree/main/design-systems) | ✅ |
| [🧩 /extract-design-system](./design-systems-and-ui-architecture/extract-design-system) | Extracts tokens, patterns, and foundations from a codebase/site. | [arvindrk/extract-design-system](https://github.com/arvindrk/extract-design-system) | ✅ |

## 🛠️ Design → Build

| Skill | What it does | Source | Status |
|---|---|---|---|
| [👩🏼‍💻 /frontend-design](./design-to-build/frontend-design) | Beats the generic AI look by forcing an explicit aesthetic direction. | [anthropics/skills](https://github.com/anthropics/skills/tree/main/skills/frontend-design) | ✅ |
| [🧩 /shadcn](./design-to-build/shadcn) | Accessible copy-don't-install components (Radix + Tailwind). | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | 🔗 |
| [🔗 Figma Implement Design](./design-to-build/figma-implement-design) | Converts Figma designs into implementation-ready code via MCP. | [figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) | 🔗 |
| [⚡ /interaction-design](./design-to-build/interaction-design) | Creates flows, states, transitions, and interaction logic. | [cuellarfr/design-skills](https://github.com/cuellarfr/design-skills) | ✅ |
| [🌀 /impeccable live](./design-to-build/impeccable-live) | Iterates on production UI and writes variants back into code. | [impeccable.style](https://impeccable.style/tutorials/iterate-live) | 🔗 |
| [🔌 Figma Code Connect](./design-to-build/figma-code-connect) | Connects Figma components directly to production code. | [figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) | 🔗 |

## 🧰 Figma Plugin Development

| Skill | What it does | Source | Status |
|---|---|---|---|
| [🧰 figma-plugin-builder](./figma-plugin-development/luma-figma-plugin-skill) | Battle-tested playbook for building any Figma plugin in TypeScript. | Original (Luma plugin) | ✅ |

---

## Using a vendored skill

Most ✅ entries are standard Claude Code skills or command plugins. Copy the skill folder into your project's `.claude/skills/` (for `SKILL.md`-based skills) or install the originating plugin/command from its source repo. Each folder's `README.md` lists the exact invocation.

## Attribution & licenses

Every vendored skill keeps its original `LICENSE` (where the source ships one) and links back to its source repository. All credit belongs to the original authors. This repository is a curation/index for personal use; if you are an author and would prefer your skill be linked rather than vendored, please open an issue.

Catalog curated from [Flora Ghnassia's Notion collection](https://floraghnassia.notion.site/Claude-Code-Skills-for-Product-Designers-who-want-to-build-3742aec4753680bf89f9c8bd51b318d8).
