# Portfolio Website — Claude Instructions

## What this is
Single-file portfolio website for Yue Guo (PM & TPgM). Everything lives in `index.html` — HTML, CSS, and JS are all inline. No build step, no framework.

## Key design decisions
- **Fonts**: Playfair Display (serif, headings) + DM Sans (sans, body)
- **Accent color**: `#E8650A` (orange), referenced as `var(--accent)`
- **Background grid**: 80px × 80px subtle grid on body
- **Layout**: Tabbed SPA — About / Superpowers / Featured Works / Tech Stack / Contact

## When making changes
- Edit `index.html` only
- CSS is in `<style>` at the top; JS is in `<script>` at the bottom
- After editing, commit and push to deploy (GitHub Pages auto-rebuilds in ~1 min)
- A backup exists at `/Users/yue/Desktop/Yue Guo — PM & TPgM_11_backup.htm`

## Content source
Pull case study details, metrics, and story data from `/Users/yue/Desktop/My_Career_Brain/` — see `CLAUDE.md` there for full instructions.

## Deployment
- Repo: https://github.com/yueg18/Yue-Guo-Portfolio-Website
- Live: https://yueg18.github.io/Yue-Guo-Portfolio-Website
- Contact form: Formspree (`xykbdoqz`) → forwards to jane.guoyue@gmail.com
