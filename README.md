<div align="center">

# <img src="https://api.iconify.design/lucide:square-terminal.svg?color=%235b2a8c" width="28" height="28" alt="" /> The SuperClaude Field Guide

### Commands · Specialists · Modes · MCP Tools · Recipes for Claude Code

**24 Chapters · 30 Commands · 19 Specialists · 7 Modes · 10 MCP Tools · 59 Recipes · 8 Cheat Sheets**

[![Version](https://img.shields.io/badge/edition-4.0-5b2a8c?style=flat-square)](https://Made-in-Jurgistan.github.io/superclaude-field-guide/)
[![License](https://img.shields.io/badge/license-CC%20BY--SA%204.0-5b2a8c?style=flat-square)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Accessibility](https://img.shields.io/badge/WCAG-2.2%20AA-5b2a8c?style=flat-square)](https://www.w3.org/TR/WCAG22/)
[![Print Ready](https://img.shields.io/badge/print-A4%20ready-5b2a8c?style=flat-square)](https://Made-in-Jurgistan.github.io/superclaude-field-guide/)
[![Covers](https://img.shields.io/badge/covers-SuperClaude%20v4.3.0-5b2a8c?style=flat-square)](https://pypi.org/project/superclaude/4.3.0/)
[![Cheat Sheets](https://img.shields.io/badge/companion-8%20cheat%20sheets-5b2a8c?style=flat-square)](https://Made-in-Jurgistan.github.io/superclaude-field-guide/cheat-sheets.html)

</div>

---

> **From first install to expert recipes** — a friendly, complete handbook for SuperClaude, the free
> community add-on that gives Claude Code ready-made working methods. Every command name, flag and
> installer option was checked against the SuperClaude source, and every technical word is explained
> in plain language for readers who have never typed a slash command.

---

## <img src="https://api.iconify.design/lucide:book-open.svg?color=%235b2a8c" width="20" height="20" alt="" /> Table of Contents

| # | Section | Group | Focus |
|---|---------|-------|-------|
| 00 | How to Use This Guide | Orientation | Reading paths, safety and level labels, how commands are shown |
| 01 | What SuperClaude Is | Get Started | The five building blocks, what happens when you type a command |
| 02 | Install and Set Up | Get Started | Python 3.10+, `pipx`, `superclaude install`, MCP add-ons, updating, Windows |
| 03 | Your First Session | Get Started | A safe twenty-minute walk-through and a daily routine |
| 04 | The 30 Commands | The Toolkit | Purpose, effect label, syntax, example and next step for every `/sc:` command |
| 05 | The Safety Ladder | The Toolkit | Look only · Plans only · Memory · Changes files, and where each command stops |
| 06 | The Specialists (Agents) | The Toolkit | 19 expert roles, what each is good for, deliberate hand-offs |
| 07 | The Seven Modes | The Toolkit | Brainstorming, Introspection, Deep Research, Task Management and more |
| 08 | Helper Tools (MCP Servers) | The Toolkit | Context7, Sequential, Magic, Playwright, Serena, Tavily and four others |
| 09 | Flags: The Fine-Tuning Dials | The Toolkit | Thinking depth, tool switches, execution control, precedence rules |
| 10 | The House Rules | The Toolkit | Git safety, root-cause fixes, scope discipline, professional honesty |
| 11 | Find the Right Recipe | Recipes | Situation finder: “I want to…” → the recipe that fits |
| 12 | Starting and Planning | Recipes | P1–P6: new projects, specs, go/no-go checks, MVP scoping |
| 13 | Building Features | Recipes | B1–B10: full-stack features, APIs, components, migrations, tests |
| 14 | Fixing Problems | Recipes | F1–F11: bugs, production incidents, broken builds, slow pages, leaks |
| 15 | Improving Existing Code | Recipes | I1–I9: refactoring, legacy clean-up, security and accessibility audits |
| 16 | Understanding and Documenting | Recipes | L1–L8: onboarding, explanations, READMEs, API docs, code review prep |
| 17 | Shipping and Working Across Days | Recipes | S1–S6: daily routine, hand-overs, commits, release checklists |
| 18 | Research, Business and Specifications | Recipes | R1–R5: cited research, competitor analysis, spec quality gates, ADRs |
| 19 | Special Set-Ups | Recipes | X1–X4: small token budgets, no MCP tools, maximum caution, maximum depth |
| 20 | Troubleshooting | Help & Reference | Symptom → likely cause → exact fix |
| 21 | Frequently Asked Questions | Help & Reference | Cost, safety, licensing, versions, what comes next |
| 22 | Glossary | Help & Reference | Every technical term in everyday words |
| 23 | Pocket Reference Cards | Help & Reference | The eight daily commands, key flags, terminal commands, all 30 at a glance |
| 24 | How This Guide Was Verified | Help & Reference | Sources, corrections to revision 3.0, known gaps |

### Companion Cheat Sheets

Eight A4 landscape pages designed to be printed and kept beside the keyboard: [`cheat-sheets.html`](cheat-sheets.html) · [PDF](pdf/SuperClaude_Cheat_Sheets.pdf)

| Page | Sheet | Contents |
|------|-------|----------|
| 1 | All 30 Commands | One colour-coded note per command, grouped Start · Plan · Build · Check + fix · Explain · Memory · Experts |
| 2 | All 19 Specialists | The `@agent-…` name, what each one does and when to call it |
| 3 | Modes · MCP Tools · Flags | The 7 modes, 10 helper tools with requirements, and every flag by category |
| 4–6 | Power Combos | 24 fast, targeted command sequences (dark mode, accessibility sweep, incidents, RAG, releases…) |
| 7–8 | Nuclear Combos | 8 maximum-depth sequences with every tool, for audits, rebuilds and impossible bugs |

---

## <img src="https://api.iconify.design/lucide:key-round.svg?color=%235b2a8c" width="20" height="20" alt="" /> Key Technologies

| Category | Technologies |
|----------|-------------|
| **Framework** | SuperClaude v4.3.0 (MIT), Claude Code, Markdown instruction files in `~/.claude/` |
| **Installer CLI** | `pipx` / `pip`, `superclaude install`, `update`, `doctor`, `version`, `install-skill`, `mcp` |
| **Commands** | `/sc:pm`, `/sc:agent`, `/sc:brainstorm`, `/sc:design`, `/sc:implement`, `/sc:troubleshoot`, `/sc:research` and 23 more |
| **Specialists** | `backend-architect`, `security-engineer`, `root-cause-analyst`, `deep-research-agent`, `pm-agent` and 14 more |
| **Modes** | Brainstorming, Introspection, Deep Research, Task Management, Orchestration, Token Efficiency, Business Panel |
| **MCP Servers** | Context7, Sequential, Magic, Playwright, Chrome DevTools, Serena, Morphllm, Tavily, Airis Agent, MindBase |
| **Flags** | `--think` / `--think-hard` / `--ultrathink`, `--c7`, `--seq`, `--serena`, `--safe-mode`, `--delegate`, `--uc` |
| **Requirements** | Python 3.10+, Node.js 18+ (most MCP tools), `uv` (Serena), Docker (AIRIS gateway) |

---

## <img src="https://api.iconify.design/lucide:sparkles.svg?color=%235b2a8c" width="20" height="20" alt="" /> Guide Features

- **<img src="https://api.iconify.design/lucide:ruler.svg?color=%235b2a8c" width="16" height="16" alt="" /> Print-Ready** — Designed print-first on A4: running headers per part, page numbers, part dividers, and break rules that never split a step; ships as a tagged PDF with bookmarks
- **<img src="https://api.iconify.design/lucide:accessibility.svg?color=%235b2a8c" width="16" height="16" alt="" /> WCAG 2.2 AA** — Skip link, `:focus-visible` outlines, reduced-motion support, text labels on every colour cue, keyboard-scrollable tables, reflow at 320 px; zero axe-core violations
- **<img src="https://api.iconify.design/lucide:search.svg?color=%235b2a8c" width="16" height="16" alt="" /> SEO Optimized** — Open Graph and social card, JSON-LD `TechArticle` structured data, canonical URL
- **<img src="https://api.iconify.design/lucide:palette.svg?color=%235b2a8c" width="16" height="16" alt="" /> Editorial Design** — Lora (display) · DM Sans (body) · JetBrains Mono (code); warm paper palette with royal purple accent (`#5b2a8c`)
- **<img src="https://api.iconify.design/lucide:smartphone.svg?color=%235b2a8c" width="16" height="16" alt="" /> Responsive** — Sticky sidebar with live chapter filter, mobile menu, one-click copy buttons on every code block
- **<img src="https://api.iconify.design/lucide:shield-check.svg?color=%235b2a8c" width="16" height="16" alt="" /> Verified Against Source** — Checked against `SuperClaude-Org/SuperClaude_Framework` at commit `fe68862` and the v4.3.0 PyPI package
- **<img src="https://api.iconify.design/lucide:list-checks.svg?color=%235b2a8c" width="16" height="16" alt="" /> Companion Cheat Sheets** — Eight printable A4 landscape sheets covering every command, specialist, mode, tool, flag and combo

---

## <img src="https://api.iconify.design/lucide:rocket.svg?color=%235b2a8c" width="20" height="20" alt="" /> Getting Started

### Read Online

Visit the hosted guide: **[Made-in-Jurgistan.github.io/superclaude-field-guide](https://Made-in-Jurgistan.github.io/superclaude-field-guide/)**

Cheat sheets: **[Made-in-Jurgistan.github.io/superclaude-field-guide/cheat-sheets.html](https://Made-in-Jurgistan.github.io/superclaude-field-guide/cheat-sheets.html)**

### Read Locally

```bash
git clone https://github.com/Made-in-Jurgistan/superclaude-field-guide.git
cd superclaude-field-guide
open index.html            # the field guide (Linux: xdg-open, Windows: start)
open cheat-sheets.html     # the companion cheat sheets
# or serve locally:
python -m http.server 8000
# navigate to http://localhost:8000
```

### Download the PDFs

Ready-made print editions are in [`pdf/`](pdf/): [`SuperClaude_Field_Guide.pdf`](pdf/SuperClaude_Field_Guide.pdf) (58 pages, A4 portrait) and [`SuperClaude_Cheat_Sheets.pdf`](pdf/SuperClaude_Cheat_Sheets.pdf) (8 pages, A4 landscape).

### Print to PDF

Open the HTML file in Chrome/Edge 131 or newer → `Ctrl+P` → set paper size to A4 → enable background graphics → print to PDF. Running headers and page numbers use CSS `@page` margin boxes, which need Chromium 131+.

### Repository Layout

```text
superclaude-field-guide/
├── index.html            The SuperClaude Field Guide (published by GitHub Pages)
├── cheat-sheets.html     The eight companion cheat sheets
├── pdf/
│   ├── SuperClaude_Field_Guide.pdf
│   └── SuperClaude_Cheat_Sheets.pdf
├── cover.png             Social preview image (1200 × 630)
├── CITATION.cff          Citation metadata for GitHub's "Cite this repository"
├── LICENSE.md            License summary and attribution guidance
├── LICENSE               Full CC BY-SA 4.0 legal code
└── README.md
```

---

## <img src="https://api.iconify.design/lucide:workflow.svg?color=%235b2a8c" width="20" height="20" alt="" /> SuperClaude at a Glance

```text
  ┌──────────┐    ┌───────────┐    ┌─────────────┐    ┌──────────┐    ┌──────────┐
  │   You    │ ─▶ │  Command  │ ─▶ │ Specialists │ ─▶ │  Tools   │ ─▶ │  Result  │
  │ /sc:...  │    │ the job   │    │ the experts │    │ MCP add- │    │ plan,    │
  │ or goal  │    │           │    │             │    │ ons      │    │ report,  │
  └──────────┘    └───────────┘    └─────────────┘    └──────────┘    │ or code  │
                                                                       └──────────┘
  The safety ladder: every command sits on one rung

  ┌───────────────┬──────────────────────────────────────────────────────────────┐
  │ Look only     │ recommend · help · analyze · test · troubleshoot · explain … │
  │ Plans only    │ brainstorm · design · workflow · spawn · research · panels   │
  │ Memory        │ load · save                                                  │
  │ Changes files │ pm · agent · task · implement · build · improve · git …      │
  └───────────────┴──────────────────────────────────────────────────────────────┘
```

---

## <img src="https://api.iconify.design/lucide:library.svg?color=%235b2a8c" width="20" height="20" alt="" /> Related Guides

| Guide | Focus |
|-------|-------|
| **[Debugging Field Manual](https://Made-in-Jurgistan.github.io/debugging-field-manual/)** | Cross-platform debugging, AI-augmented workflows, 30 sections |
| **[Mobile STT Engineering Guide](https://Made-in-Jurgistan.github.io/mobile-stt-engineering-guide/)** | On-device speech-to-text: audio capture, VAD, model inference, post-processing |
| **[Android Keyboard Design Guide](https://Made-in-Jurgistan.github.io/android-keyboard-design-guide/)** | Production IME development, API 30–36, Material You 3.0 |
| **[Android Keyboard: 3D & Personalization](https://Made-in-Jurgistan.github.io/android-keyboard-design-guide-3d-personalization/)** | 3D rendering, PBR materials, custom themes, game engine bridges |

---

## <img src="https://api.iconify.design/lucide:file-text.svg?color=%235b2a8c" width="20" height="20" alt="" /> Metadata

| Field | Value |
|-------|-------|
| **Author** | Made in Jurgistan |
| **Version** | Edition 4.0 |
| **Covers** | SuperClaude v4.3.0 (released 2026-03-22) |
| **Published** | 2026-10-03 |
| **Updated** | 2026-10-07 |
| **License** | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| **Accessibility** | WCAG 2.2 AA |
| **Canonical URL** | `https://Made-in-Jurgistan.github.io/superclaude-field-guide/` |
| **Theme Color** | `#5b2a8c` (Royal Purple) |
| **Fonts** | Lora · DM Sans · JetBrains Mono |
| **Verified Against** | `SuperClaude-Org/SuperClaude_Framework` @ `fe68862` (2026-09-27) |

---

## <img src="https://api.iconify.design/lucide:git-pull-request.svg?color=%235b2a8c" width="20" height="20" alt="" /> Contributing

Report issues or suggest improvements: [github.com/Made-in-Jurgistan/superclaude-field-guide/issues](https://github.com/Made-in-Jurgistan/superclaude-field-guide/issues)

When SuperClaude releases a new version, corrections that cite the relevant source file and commit are especially welcome.

---

## <img src="https://api.iconify.design/lucide:scale.svg?color=%235b2a8c" width="20" height="20" alt="" /> License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — Free to share and adapt with attribution. See [`LICENSE.md`](LICENSE.md) for details and [`LICENSE`](LICENSE) for the full legal code.

> **Note:** SuperClaude is an independent, MIT-licensed community project by its own authors. It is not made, endorsed or supported by Anthropic, and this guide is not affiliated with either. The guide's license covers the guide only, not the software it describes.

---

## <img src="https://api.iconify.design/lucide:quote.svg?color=%235b2a8c" width="20" height="20" alt="" /> How to Cite

If you reference this guide in academic work, documentation, or project READMEs, please use one of the formats below. Both are consistent with the output generated by GitHub's "Cite this repository" button and the [`cffconvert`](https://github.com/citation-file-format/cffconvert) tool from the repository's `CITATION.cff` file.

### APA (7th Edition)

```text
Made in Jurgistan. (2026). The SuperClaude Field Guide (Version 4.0) [Computer software]. https://Made-in-Jurgistan.github.io/superclaude-field-guide/
```

### BibTeX

```bibtex
@software{Made_in_Jurgistan_The_SuperClaude_2026,
  author = {Made in Jurgistan},
  month = {10},
  title = {{The SuperClaude Field Guide}},
  url = {https://Made-in-Jurgistan.github.io/superclaude-field-guide/},
  version = {4.0},
  year = {2026}
}
```

> **Note:** A `CITATION.cff` file at the repository root also enables GitHub's built-in "Cite this repository" button (right sidebar on the repo page), which auto-generates APA and BibTeX citations from the same metadata.

---

<div align="center">

**Made in Jurgistan** — Complete Edition · 2026

</div>
