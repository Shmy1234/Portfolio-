# Sahil Regonda — Interactive Portfolio

Personal portfolio built with Vite + React + TypeScript, styled with Tailwind and shadcn/ui primitives. The site pairs a painted-gallery visual style with WebGL particle weather themes and an interactive drawing canvas so visitors can explore projects, experience, and credentials in a playful way.

## Features
- Seasonal themes with animated particles: autumn leaves, night rain, and winter snow driven by React Three Fiber.
- Hero card with quick-contact links, skill carousel, and a canvas notebook that supports multiple tools, color/size controls, undo/redo, clear, and PNG download.
- Projects gallery with expandable highlights and GitHub links plus a “Show more” toggle for the full list.
- Timeline-style experience section with sub-roles, collapsible bullet points, and skill badges.
- Awards and certificates grid with framed cards.
- Contact form with Zod validation, toast feedback, and quick links for email, LinkedIn, and GitHub.

## Tech Stack
- React 18 + TypeScript, Vite bundler
- Tailwind CSS, shadcn/ui components, Framer Motion animations
- React Router for sections, TanStack Query provider ready for data fetching
- React Three Fiber for 3D particle effects
- Form validation with Zod and custom hooks for toasts/theme

## Getting Started
```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Production build and preview
npm run build
npm run preview

# Lint
npm run lint
```

## Project Structure
- `src/pages/Index.tsx` — page shell that wires the navbar, sections, intro animation, and theme-driven particle layers.
- `src/data/portfolio.ts` — single source of truth for profile info, projects, experience, awards, and chatbot copy.
- `src/components/` — UI sections (Hero, Projects, Experience, Awards, Contact) plus the painting canvas, navbar, and animated effects.
- `src/contexts/ThemeContext.tsx` — theme cycling between autumn/night/winter for the particle systems.

## Customizing Content
Update `src/data/portfolio.ts` to change profile details, projects, experience, awards, or chatbot prompts. The UI reads directly from this file, so edits appear immediately in the running app.

## Portfolio Recap
- **Who**: Sahil Regonda — CS & Math student at the University of Toronto (GPA 3.87), dual USA/Canada citizenship, based in Toronto; Dean’s List.
- **Focus**: Web/AI/ML builder with experience across React/Next.js, Java/Spring, Python, and cloud/DevOps tooling.
- **Flagship projects**: Trial of the Knight (Python/Pygame platformer), A* Pathfinding Visualizer (Java Swing), JavaFX Paint Program (MVC), SkillSnapAI (AI resume analysis), AccessiGo (accessibility mapper), Othello AI experiments.
- **Experience**: Software Developer at PashMotors (current); AI Extern at Outamation; Software Engineer at KenilWorth Square; multi-role tenure at Circle K; Full-Stack at Stickery; marketing/analytics roles at Youreka and research roles through Inspirit AI.
- **Awards/Certs**: AWS AI Practitioner, AWS Cloud Practitioner, Inspirit AI Scholar, Youreka Research Awards (1st & 3rd place).
- **Contact**: sahilregonda@mail.utoronto.ca · linkedin.com/in/sahilregonda · github.com/Shmy1234
