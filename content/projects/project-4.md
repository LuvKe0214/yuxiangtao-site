---
title: "Meridian (Career Intelligence SaaS)"
summary: "A technical foundation for a career pathing platform designed to solve the 'structural mismatch' in the labor market using Next.js 15 and AI-driven parsing.."
tags: ["project"]
---

## Overview
The project is currently a "Server-First" skeleton. The focus has been on building a solid technical foundation—handling data flow and security rather than polishing a UI that doesn't have a brain yet. It’s more of a functional prototype than a finished product

## What I did
- Hardcoded the "AI Constitution": Created a strict .cursorrules file for the IDE. This forces the AI to stop using outdated React patterns and follow Next.js 15’s specific rules (like async cookie handling and functional logic) so the codebase doesn't turn into "vibe coding" spaghetti.

- Built the Plumbing: Connected Next.js 15 with Supabase. I set up Row Level Security (RLS) and Postgres triggers so that user profiles and permissions are created and secured automatically the moment someone signs up.

- Resume Parsing Pipeline: Prototyped a working "digital factory" line. It takes a PDF, extracts the raw text with pdf-parse, and uses Claude 3.5 Sonnet to force that mess into a clean, standardized JSON Resume format.

- Market Logic Research: Deep-dived into 2025 labor trends, specifically "degree inflation" and "skill adjacency."This provided the theoretical basis for the scoring system, even though the code for it isn't finished yet
## Still need to finish
The "Intelligence" is missing: The Risk Score algorithm is just a collection of research notes and math formulas; I haven't actually written the backend logic to calculate it yet.
No Visuals: The interactive career maps (React Flow) mentioned in the plan haven't been touched. There are zero charts or roadmaps in the current build.
I'm keep doing it!
