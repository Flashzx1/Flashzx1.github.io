# AGENTS.md

## Project overview
This repository is the Russian-language Flashzx1 portfolio published with GitHub Pages. It is a static HTML, CSS, and JavaScript site showcasing BookingFlow, ServiceFlow, and LeadFlowBot.

## Working rules
- Keep the site deployable directly through GitHub Pages without a build step.
- Preserve the editorial visual direction and Russian-language content.
- Prefer semantic HTML, progressive enhancement, and lightweight JavaScript.
- Keep project descriptions, demo links, screenshots, technology lists, and portfolio statistics accurate.
- Do not introduce a framework, package manager, or shadcn/ui unless explicitly requested.
- Do not commit personal secrets or private contact information.

## UI and accessibility
- Maintain responsive behavior at phone, tablet, and desktop widths.
- Check keyboard navigation, focus visibility, heading hierarchy, alternative text, color contrast, reduced-motion behavior, and link labels.
- Avoid generic template styling; keep typography, spacing, and visual hierarchy consistent across sections.
- Optimize images and avoid unnecessary network dependencies.

## Verification
Before finishing:
1. Serve the repository locally with `python -m http.server 8080`.
2. Check the page at narrow and wide viewport sizes.
3. Confirm that internal anchors, GitHub links, live demos, images, and the current-year script work.
4. Update `README.md` when local preview or publication steps change.
