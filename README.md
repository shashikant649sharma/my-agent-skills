# ⚡ Agent Skills Hub

A curated, production-grade collection of **31 specialized AI Agent Skills** for Google Antigravity, Claude Code, Codex, and any AI agent tool implementing the open `skills` standard.

---

## 🚀 Quick Install

### Install Entire Skills Pack
Install all skills from this repository into any project:
```bash
npx skills add <your-github-username>/my-agent-skills
```

Or install **globally** across your computer (available in every workspace):
```bash
npx skills add <your-github-username>/my-agent-skills -g
```

### Install a Single Skill
You can also install individual skills from this repository:
```bash
npx skills add <your-github-username>/my-agent-skills --skill design-taste-frontend
```

---

## 📚 Included Skills (31 Curated Skills)

### 🎨 1. High-End UI & Design Engineering
| Skill | Description |
| :--- | :--- |
| **`design-taste-frontend`** | Anti-slop frontend engineering for web applications, landing pages, and redesigns. Enforces bespoke typography and distinct palettes. |
| **`design-taste-frontend-v1`** | Legacy v1 taste skill for exact backward compatibility. |
| **`emil-design-eng`** | Emil Kowalski's design philosophy on micro-interactions, layout polish, component rhythm, and invisible details. |
| **`apple-design`** | Apple's interface design philosophy: fluid gesture UI, spring dynamics, translucent materials, and typography. |
| **`high-end-visual-design`** | Agency-level design principles, card structures, shadows, and tokens that make websites feel expensive. |
| **`stitch-design-taste`** | Semantic Design System generator for Google Stitch creating anti-generic DESIGN.md specs. |
| **`redesign-existing-projects`** | Upgrades existing websites to premium quality without breaking layout or functional logic. |
| **`pick-ui-library`** | Decision framework for selecting the right component library based on performance and customization requirements. |

### 🎬 2. Motion, Physics & Animations
| Skill | Description |
| :--- | :--- |
| **`animate`** | Scratch-built web animations with spring physics, purposeful duration curves, and exit transitions. |
| **`animate-expo`** | React Native and Expo fluid animations utilizing Reanimated, Gesture Handler, and haptics. |
| **`animation-vocabulary`** | Reverse-lookup glossary translating vague descriptions into exact technical animation terminology. |
| **`find-animation-opportunities`** | Codebase scanner identifying key UI moments that lack motion and would benefit from subtle transitions. |
| **`improve-animations`** | Senior motion advisor that audits existing motion code and plans performance/feel improvements. |
| **`review-animations`** | Critical review and diff-checker for motion implementations. |
| **`gpt-taste`** | Advanced GSAP Motion Engineer enforcing scroll-triggered scrubbing, pinning, and timeline sequences. |

### 🏛️ 3. Aesthetic Design Directions
| Skill | Description |
| :--- | :--- |
| **`minimalist-ui`** | Clean editorial interfaces with warm monochrome palettes, stark typography, and flat bento grids. |
| **`industrial-brutalist-ui`** | Mechanical interfaces fusing Swiss typography with military/terminal blueprints and rigid grids. |
| **`brandkit`** | Premium brand-identity boards, typography hierarchy, and logo system guidelines. |

### 🖼️ 4. Visual Comps & Image Generation
| Skill | Description |
| :--- | :--- |
| **`image-to-code`** | High-fidelity image-to-code workflow translating visual comps into responsive HTML/CSS/JS. |
| **`imagegen-frontend-web`** | Section-by-section frontend image direction for landing page references. |
| **`imagegen-frontend-mobile`** | Mobile app screen concept art and UI flow generation within realistic phone mockups. |

### ✂️ 5. Ponytail (Anti-Overengineering & Simplicity)
| Skill | Description |
| :--- | :--- |
| **`ponytail`** | Senior dev philosophy enforcing the simplest, cleanest solution (native stdlib over bloat dependencies). |
| **`ponytail-review`** | Code review focused exclusively on finding dead complexity, speculative abstractions, and bloat. |
| **`ponytail-audit`** | Whole-repo scanner producing a ranked deletion and simplification roadmap. |
| **`ponytail-debt`** | Tracks deferred shortcuts and technical debt tags in a structured ledger. |
| **`ponytail-gain`** | Scoreboard measuring saved code lines, reduced bundle size, and execution speedups. |
| **`ponytail-help`** | Quick-reference cheat sheet for all Ponytail modes and directives. |

### 🛠️ 6. Specialized Development
| Skill | Description |
| :--- | :--- |
| **`ask-sonner`** | Definitive guide to implementing and styling the Sonner React toast library. |
| **`full-output-enforcement`** | Overrides LLM output truncation, banning code placeholders and ensuring complete file emissions. |
| **`prototype`** | Fast, high-fidelity interactive prototyping workflow for validating product concepts. |
| **`write-swift`** | Modern Swift 6 development patterns (value types, data-race safety, concurrency, actors). |

---

## 🛠️ Repository Structure

```text
my-agent-skills/
├── README.md
├── .gitignore
└── skills/
    ├── animate/
    │   └── SKILL.md
    ├── apple-design/
    │   └── SKILL.md
    ├── design-taste-frontend/
    │   └── SKILL.md
    ├── ... (31 skill directories)
```

Each skill folder contains a `SKILL.md` file featuring YAML frontmatter (`name`, `description`) and comprehensive instructions for AI agents.

---

## 📄 License
MIT License. Created for AI agent developers.
