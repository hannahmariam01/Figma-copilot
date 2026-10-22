# 📋 GitHub Repository Setup & Description Guide

Use this guide when creating or updating your repository on GitHub. Everything is formatted for quick copy-pasting.

---

## 1. Short Repository Description (About Section)
*Paste this into the **About** / **Description** field of your GitHub repository (max 350 chars):*

> **A persistent AI sidebar copilot for Figma. Select layers, speak natural English, and execute canvas edits, auto-layout conversion, design audits, palette suggestions, and PowerPoint (.pptx) export in real time.**

---

## 2. GitHub Topics / Tags
*Add these into the **Topics** field on your GitHub repository to maximize discoverability:*

```
figma-plugin
ai-copilot
figma-api
typescript
esbuild
groq
llama-3
anthropic
claude
design-system
auto-layout
powerpoint-export
pptxgenjs
upstash-redis
generative-ui
```

---

## 3. Recommended Repository Settings
- **Repository Name**: `figma-copilot` or `ai-figma-copilot`
- **Visibility**: Public (or Private)
- **Primary Language**: TypeScript
- **License**: MIT License
- **Include in README**: Checked (the repo already includes the complete `README.md`)

---

## 4. Release Notes (for v1.0.0 Tag)

### **Title**: `v1.0.0 — Initial Release: AI Canvas Copilot, Autolayout & PPTX Export`

### **Description**:
```markdown
### 🚀 Welcome to Figma Copilot v1.0.0!

Figma Copilot is a persistent AI sidebar plugin that bridges natural language with direct canvas execution in Figma.

#### ✨ Key Features:
- 💬 **Natural Language Canvas Execution**: Edit visible text, rename layers, modify colors, adjust padding, set corner radiuses, and duplicate nodes directly from conversation.
- 📐 **Automated Auto-Layout Engine**: 1-click detection and conversion of frame layouts with inferred orientation, item gaps, and padding.
- 🌙 **One-Click Dark Mode**: Instant conversion of light UI templates into high-contrast dark modes.
- 🎨 **Smart Palette Generator**: Context-aware color recommendations for Enterprise, Light UI, and Dark UI themes.
- 📥 **Export to PowerPoint (.pptx)**: Convert selected Figma frames and slides into editable Microsoft PowerPoint presentations.
- ⚡ **Ultra-Fast LLM Backend**: Powered by Groq LLaMA 3.3 70B JSON mode with rate limiting via Upstash Redis.
- 💻 **Dual Hosting**: Run locally with zero-configuration Node.js server (`npm run dev`) or deploy serverless to Vercel.

#### 📦 Installation & Setup:
1. Clone the repo
2. Build plugin: `cd plugin && npm install && npm run build`
3. Import `plugin/manifest.json` into Figma Desktop App
4. Start backend: `cd backend && npm install && npm run dev`
```
