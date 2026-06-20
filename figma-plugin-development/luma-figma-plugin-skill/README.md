# 🧰 figma-plugin-builder

> Part of the **Figma Plugin Development** collection — an original skill from this repo's author.

| | |
|---|---|
| **Source** | Original — extracted from shipping the **Luma** presentation toolbox plugin |
| **Invoke** | Auto-activates when building a Figma plugin |
| **Status** | ✅ Vendored (original skill) |

## What it does
Hard-won, battle-tested knowledge for building **any** Figma plugin in TypeScript. Covers project scaffolding, the esbuild bundling requirement, the main-thread/UI split and message passing, the prototyping/reactions API, the dynamic-page document model, coordinate-system rules (the #1 source of bugs), fonts, thumbnails, node tagging, live document watchers, the Figma UI3 design system, and a long list of gotchas that each cost real debugging time.

## When to use it
Read this **before** writing a new Figma plugin so you start from working patterns instead of rediscovering the traps.

## Why it matters
Figma's plugin runtime has sharp edges — coordinate systems, the sandbox/UI split, font loading — that aren't obvious from the docs and routinely cost hours. This skill captures verified, real-runtime behavior.

## Curator's take
> Every rule marked **GOTCHA** in the skill caused an actual bug. This is the playbook I wish I'd had before building Luma.

## Source
Authored by the maintainer of this repo. Entry point: [`SKILL.md`](./SKILL.md).
