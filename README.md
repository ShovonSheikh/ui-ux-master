# 🎨 UI/UX Pro Max - SaaS Design Intelligence

An advanced AI agent skill designed to stop "vibe-coded," amateur interfaces and enforce professional, production-ready SaaS design patterns. 

This skill merges a strict, mathematically driven **SaaS UI/UX Master Guide** (covering layout, 4-layer color systems, and dark mode contrast) with a **massive CLI-searchable design database** (50+ styles, 97 palettes, 57 font pairings, and 99 UX guidelines across 9 tech stacks).

## 🌟 Features

* **The 4-Layer Color System:** Rules for creating scalable SaaS color palettes using the OKLCH color space (Neutral Foundations, Functional Accents, Semantic Communication, and Theming Engines).
* **Mathematical Dark Mode:** Enforces specific contrast scaling (doubling lightness distances) and shifted accent colors for perfect dark mode legibility.
* **Component Architecture:** Mandates professional layout practices, such as consolidating navigation into Account Popovers, utilizing ellipsis menus for table actions, and using focused modals over massive flyouts.
* **CLI Search Engine:** A built-in Python search engine that allows the AI (or you) to query specific styles, palettes, and UX guidelines on the fly.

---

## 🙏 Credits & Attribution

**This project stands on the shoulders of giants.** The underlying CLI search engine, Python scripts (`search.py`), and foundational data arrays in this skill were originally created by the authors of the base `ui-ux-pro-max` skill. Full credit for the Python architecture and data scraping goes to them. 

This repository modifies and builds upon their excellent technical framework by injecting a strict, comprehensive **SaaS UI/UX Design philosophy** into the agent's instructions.

---

## 🚀 Installation

You can install this skill directly into your AI agent environment using [skills.sh](https://skills.sh/).

```bash
npx skills add ShovonSheikh/ui-ux-master
```

### Prerequisites

Because this skill utilizes a local search database, ensure Python 3 is installed on your system:

```bash
python3 --version || python --version
```

---

## 💻 How It Works

Once installed, your AI agent (whether in Cursor, Windsurf, or a CLI agent) will automatically trigger this skill whenever you ask it to design, code, review, or fix a user interface.

The agent will follow a two-step process:

1. **Apply Core SaaS Rules:** It will immediately apply the strict UI/UX Master Guide (e.g., swapping emojis for SVG icons, fixing background layer contrast, organizing layouts).
2. **Query the Database:** It will run terminal commands in the background to fetch specific hex codes, font pairings, or framework-specific rules (like React, Tailwind, or Vue best practices) to match your exact prompt.

### Example Prompt to Try:

```
*"I'm building a settings page for my healthcare SaaS app. The sidebar currently has: Dashboard, Profile, Security, Billing, Team, API Keys, Integrations, and Logout. It feels cluttered. Generate a new layout and a dark mode color palette using a professional green accent."*
```

The agent will consolidate your navigation, generate an OKLCH-based green theme, calculate the proper dark mode contrast steps, and write the code.
