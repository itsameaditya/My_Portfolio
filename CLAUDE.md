# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal portfolio website for Aditya Singh (Data Scientist & ML Engineer). Static site hosted on GitHub Pages at https://itsameaditya.github.io/My_Portfolio/.

## Tech Stack

Pure HTML/CSS/JS — no build tools, no frameworks, no package manager. Just three files:
- `index.html` — all content and structure
- `style.css` — dark theme, responsive layout, animations
- `script.js` — nav behavior, scroll reveals, particle canvas background, counter animations

## Deployment

Hosted via GitHub Pages from the `main` branch. Any push to `main` triggers automatic deployment. No build step required.

## Architecture

- **Design system**: CSS custom properties in `:root` for colors, fonts, spacing, transitions
- **Layout**: CSS Grid for major sections (about, skills, projects), Flexbox for components
- **Animations**: CSS keyframes for hero entrance, JS IntersectionObserver for scroll reveals
- **Hero background**: HTML5 Canvas with particle system and mouse interaction
- **Responsive**: Mobile-first breakpoints at 480px, 768px, 1024px with hamburger nav on mobile

## Key Sections

- Hero → About → Skills → Projects (2 featured: FitLake, SaaS Funnel) → Contact → Footer
- Contact links: email (aditya.s.singh2021@gmail.com), GitHub, LinkedIn, resume PDF
- Resume PDF (`ADITYA_RESUME.pdf`) is served directly from the repo root

## Important Constraints

- No AI-generation traces — do not add comments, meta tags, or attribution suggesting AI involvement
- Repo is public (required for free GitHub Pages)
- GitHub username: `itsameaditya`
