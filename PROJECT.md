# Portfolio Website

## Purpose
Personal portfolio for internship applications.
Focus on hands-on engineering, repair, and long-term technical growth.
Primary audience: recruiters and engineers.
Secondary audience: personal archive of work history.

## Core Principles
- Clean, professional first impression
- Optional depth (timeline is opt-in)
- No raw footage forced on viewers
- Easy to add / remove content
- No fragile or tangled code

## Stack
- Astro (static site)
- HTML + CSS
- Minimal JavaScript (only if necessary)
- Free static hosting (Netlify or Vercel)

## Site Structure
src/
 ├─ pages/
 │   ├─ index.astro
 │   ├─ timeline.astro
 │   └─ projects.astro
 ├─ components/
 │   ├─ Timeline.astro
 │   ├─ TimelineItem.astro
 │   └─ ProjectCard.astro
 ├─ data/
 │   ├─ timeline.js
 │   └─ projects.js
 └─ styles/
     └─ base.css

## Timeline Rules
- Timeline is NOT the homepage
- Timeline shows progression, not age
- Organized by eras, not specific ages
- Hover = grow
- Non-hover = shrink
- Details expand on hover
- Raw footage links are optional and clearly labeled

## Content Rules
- Featured projects come first
- Timeline supports credibility, not nostalgia
- Ongoing projects get their own section
- Everything should be skimmable in under 60 seconds

## Current State
- PROJECT.md created
- Astro not scaffolded yet

## Next Checkpoint
Checkpoint 1: Astro project scaffolded and running locally