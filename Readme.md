# Skills

**A curated collection of agent skills for OpenCode, spanning design systems, frontend engineering, image generation, and workflow utilities.**

[![License: Proprietary](https://img.shields.io/badge/license-proprietary-lightgrey)]()
[![Skills](https://img.shields.io/badge/skills-17-blueviolet)]()
[![Status](https://img.shields.io/badge/status-active-brightgreen)]()

---

## Overview

This repository is a structured library of `SKILL.md` definitions built to extend the capabilities of AI coding agents operating within OpenCode. Each skill encapsulates a distinct discipline, ranging from taste driven frontend design to image only generation pipelines, giving agents the precision, consistency, and craft that raw prompting cannot reliably deliver on its own.

The goal of this collection is simple: eliminate generic, templated output and replace it with deliberate, high quality results across design, code, and visual generation.

---

## Table of Contents

- [Design and Frontend Skills](#design-and-frontend-skills)
- [Image Generation Skills](#image-generation-skills)
- [Utility Skills](#utility-skills)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Contributing](#contributing)
- [License](#license)

---

## Design and Frontend Skills

| Skill | Description |
|---|---|
| **taste-skill** | The default design skill, currently in its second experimental generation. Reads a creative brief, infers the underlying design language, and tunes three dials, Variance, Motion, and Density, to ship landing pages, portfolios, and redesigns that avoid a templated look. Includes brief inference, design system mapping, an em dash ban, GSAP code skeletons, and a hard rules pre flight check. |
| **taste-skill-v1** | The original version of taste-skill, preserved for projects that depend on its exact prior behavior. The active default is now taste-skill. |
| **gpt-tasteskill** | An elite, Awwwards level frontend design and GSAP motion skill engineered for premium, deterministic, anti slop UI generation. |
| **image-to-code-skill** | An image first frontend skill that generates premium website design references, analyzes them in depth, and implements matching code. |
| **redesign-skill** | Purpose built for upgrading existing projects through systematic auditing and correction of design problems. |
| **soft-skill** | Cultivates an expensive, soft UI aesthetic defined by premium typography, generous whitespace, layered depth, and smooth motion. |
| **minimalist-skill** | Enforces clean, editorial style interfaces in the spirit of Notion and Linear, governed by strict monochrome palettes. |
| **brutalist-skill** *(Beta)* | Delivers raw, mechanical interfaces built on Swiss typography and extreme scale contrast. |
| **stitch-skill** | Provides Google Stitch compatible semantic design rules for premium AI driven UI generation. |
| **design-language** | Applies a named UI design language, including glassmorphism, neumorphism, brutalism, Material 3, cyberpunk, Y2K, Bauhaus, and over two hundred and twenty additional styles, consistently across a codebase. A tokens first workflow backed by a catalog of one hundred and ninety nine implementation specs across two hundred and twenty four deep specifications, complete with WCAG contrast checks, Tailwind fragments, starter themes, and a consistency drift audit. Sourced from the claude-artisan repository. |
| **laws-of-ux** | Applies established laws and principles of user experience design to guide interface decisions. |
| **webcore-analyzer** | Analyzes web projects against core performance and quality benchmarks. |

## Image Generation Skills

| Skill | Description |
|---|---|
| **imagegen-frontend-web** | An image generation only skill for producing premium website design reference imagery. Does not write code. |
| **imagegen-frontend-mobile** | An image generation only skill for producing premium mobile app screen concepts and flows. Does not write code. |
| **brandkit** | An image generation only skill for producing premium brand kit overview imagery, including logo concepts, identity systems, color palettes, typography, and mockups. Does not write code. |

## Utility Skills

| Skill | Description |
|---|---|
| **output-skill** | Prevents an agent from being lazy, skipping code blocks, or relying on placeholder comments in its output. |

---

## Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/nithilan-alt-f4/skills.git
   ```

2. **Select a skill** relevant to your task from the tables above.

3. **Reference the skill's `SKILL.md`** within your OpenCode agent configuration to make its instructions available at runtime.

4. **Combine skills where appropriate.** Several skills, such as a design language skill paired with output-skill, are designed to complement one another.

---

## Repository Structure

```
skills/
├── brandkit/
├── brutalist-skill/
├── design-language/
├── gpt-tasteskill/
├── image-to-code-skill/
├── imagegen-frontend-mobile/
├── imagegen-frontend-web/
├── laws-of-ux/
├── minimalist-skill/
├── output-skill/
├── redesign-skill/
├── soft-skill/
├── stitch-skill/
├── taste-skill/
├── taste-skill-v1/
├── web-designer/
├── webcore-analyzer/
└── llms.txt
```

Each directory contains a self contained `SKILL.md` definition along with any supporting assets the skill requires.

---

## Contributing

This collection is under active iteration, most notably with taste-skill progressing toward a stable v2.0.0 release. Suggestions, refinements, and new skill proposals are welcome through issues and pull requests.

---

## License

Proprietary. All rights reserved by the repository owner.
