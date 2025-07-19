# 🎨 Vibe Project Generator

> A web tool that helps developers and creatives generate a visual design vibe for their project or brand, powered by natural language input.

## 🚀 Overview

The Vibe Project Generator helps users describe the kind of project or brand they’re building — and outputs aesthetic recommendations including **color palettes**, **styles**, **fonts**, and **images** to create a compelling design identity.

Ideal for solo devs, startups, hackathon teams, and anyone struggling with early-stage UI inspiration.

---

## 🧠 Problem Statement

Many creators know *what* they want to build, but not *how it should look*. They struggle to translate project ideas into UI aesthetics. This tool bridges that gap by auto-generating design guidance based on plain English descriptions.

---

## 🎯 Target Audience

- Indie developers and solo makers
- Startups validating ideas
- Hackathon participants
- UI/UX beginners
- Internal teams at Vibe Coders

---

## 💡 Use Cases

- "Mental health journal app for Gen Z" → Soothing, modern UI with calming colors.
- "Portfolio for a backend dev who loves minimalism" → Clean lines, monospace fonts, dark/light toggle.
- "Landing page for eco-friendly reusable bottles" → Earthy tones, crisp visuals, eco-conscious vibes.

---

## 🧭 User Flow

1. **Landing Page**: Intro to the tool → CTA: "Describe your project"
2. **Input Form**:
   - Free text input: “Describe your project”
   - Optional: Target audience, emotion keywords
3. **Generation**:
   - Backend maps description to visual attributes
   - AI-enhanced style suggestions (colors, fonts, imagery)
4. **Results Page**:
   - Color palette
   - Mood board / design direction
   - Suggested fonts
   - Exportable assets (JSON, share links)
5. **Save/Share**:
   - Supabase-authenticated profiles
   - Save design boards, generate permalinks

---

## 🛠 Tech Stack

- **Frontend**: React + TailwindCSS
- **Framework**: Next.js (with App Router)
- **Backend**: Supabase (Auth, Database, Edge Functions)
- **APIs** (optional):
  - OpenAI for prompt-to-style logic
  - Unsplash / Pexels for images
  - Google Fonts for typography

---

## ⚙️ Features

- ✏️ Describe your idea with natural language
- 🎨 Get an automatically generated aesthetic
- 🖼️ View mood boards and palette suggestions
- 📁 Export design tokens or assets
- 🔐 Save ideas to your profile (Supabase Auth)

---

## 🧱 Folder Structure (Coming Soon)


---

## ⚠️ Risks & Mitigations

| Risk | Impact | Mitigation |
|------|--------|------------|
| Vague or unclear input | Poor results | Input examples, placeholder text |
| Repetitive output | Bland user experience | Use diverse APIs and feedback data |
| Inappropriate AI suggestions | UX & reputation issues | Prompt tuning, content filters |
| Performance bottlenecks | Slower generation | Cache results, use Supabase Edge Functions |
| Low adoption | Wasted effort | Start with internal team use, iterate based on feedback |

---

## 🧪 Future Features

- 🎨 Full UI mockup generation (HTML/CSS/Figma)
- 🧩 Figma plugin integration
- 🧑‍🤝‍🧑 Team collaboration mode
- 🧾 Auto-generate branding documentation

---

## ✅ Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/yourname/vibe-project-generator

# 2. Install dependencies
npm install

# 3. Set up Supabase project
# - Create project at supabase.com
# - Add env vars in `.env.local`

# 4. Start dev server
npm run dev
