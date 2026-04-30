---
name: spandan-patil-design
description: Use this skill to generate well-branded interfaces and assets for Spandan Patil's portfolio (spandanpatil.com) and his future company dsrptoid, either for production or throwaway prototypes/mocks/etc. Contains essential design guidelines, colors, type, fonts, assets, and UI kit components for prototyping. Editorial-quant aesthetic — navy + cream + gold, classical serifs, mono labels, geometric line art, hard corners.
user-invocable: true
---

Read the README.md file within this skill, and explore the other available files.

If creating visual artifacts (slides, mocks, throwaway prototypes, etc), copy assets out of `assets/` and reference `colors_and_type.css` from new HTML files for the user to view. If working on production code, you can copy assets and read the rules here to become an expert in designing with this brand.

If the user invokes this skill without any other guidance, ask them what they want to build or design, ask some questions, and act as an expert designer who outputs HTML artifacts _or_ production code, depending on the need.

Key constraints to enforce:
- Hard corners only (`border-radius: 0`) except the single timeline dot.
- Four font families: Cormorant Garamond (display), Cinzel (uppercase headings/brand), Crimson Pro (body), Courier Prime (mono labels). No system-font fallbacks for hero text.
- No emoji in production. The site's Markdown fallback uses them; that is NOT canon.
- Glow effects only on gold; no neon, no rainbow gradients, no glassmorphism beyond the nav blur.
- Section labels are ALL CAPS mono with tracking ≥ 0.20em.
- Diamond `◆` is the divider mark; mid-dot `·` separates metadata.

Files in this skill:
- `README.md` — full brand guidelines (content, visual, iconography)
- `colors_and_type.css` — canonical CSS variables and semantic element styles
- `assets/` — logo, divider ornament, corner brackets, geometric backdrop SVG
- `preview/` — design-system tab cards (color, type, spacing, components, brand)
- `ui_kits/portfolio/` — JSX recreation of spandanpatil.com with `index.html` demo
