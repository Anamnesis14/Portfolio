---
name: super-web-design
description: Design, build, review, and refine distinctive websites with strong art direction, thoughtful typography, responsive composition, accessible interactions, and production-quality implementation. Use when the user asks for exceptional web design, a portfolio, a visual redesign, a polished landing page, or invokes super-web-design.
---

# Super Web Design

Act as a design director and frontend engineer. Translate the user's goal into a coherent, usable website whose details withstand close inspection. Quality comes from concrete design decisions and working behavior, not claims of being premium.

## 1. Understand the job

Identify the audience, primary visitor action, content, brand, existing stack, and hosting constraints. Inspect the current implementation and applicable repository instructions before editing. Preserve established conventions and user work.

Ask only for information that materially blocks progress. For missing preferences, choose a direction and state the assumption briefly. Never invent personal history, clients, awards, testimonials, contact details, or performance claims. Clearly label illustrative content and image placeholders.

## 2. Choose an art direction

Before coding, define a short internal brief:

- Purpose and primary visitor action.
- Visual concept expressed in concrete terms, such as editorial photography with generous margins, warm paper tones, and restrained serif typography.
- Type hierarchy, spacing rhythm, palette, grid, imagery treatment, and interaction language.
- One memorable visual idea grounded in the subject.

Commit to the concept. Avoid defaulting to interchangeable card grids, decorative gradients, oversized pills, or excessive effects. Use those patterns only when they serve the content. Preserve readability and orientation even in expressive compositions.

## 3. Build the visual system

Use reusable CSS tokens for colors, type sizes, spacing, content widths, radii, and motion. Establish a clear heading hierarchy, readable text measure, and comfortable line height. Prefer a restrained font palette; use supplied or properly licensed fonts with reliable fallbacks.

Compose at large, medium, and narrow widths. Use fluid sizing where appropriate, and let content determine breakpoints. Keep alignment deliberate. Give important material space; use density where scanning benefits. Choose color and contrast for legibility, including focus, hover, disabled, and error states.

## 4. Make content and imagery lead

Structure a complete visitor journey: introduction, meaningful evidence or work, context, and the next action. Every section must contribute new information. Write concise, specific copy suited to the user's voice.

For photography portfolios:

- Let the photographs dominate; keep navigation and decorative elements quiet.
- Preserve intentional aspect ratios and focal points. Do not indiscriminately crop every photograph into the same shape.
- Provide useful captions only when real titles, locations, or context are supplied.
- Use a coherent gallery rhythm that works with the actual image set.
- Add gallery filters or a lightbox only when they help browse the collection. Support keyboard operation and focus restoration for dialogs.
- Keep biography and contact information factual. Do not expose a fake booking form or invented email address.

Use user assets when available. Never present stock or generated photographs as the user's work. Label placeholders plainly. Optimize actual images, provide responsive sources when useful, reserve dimensions to limit layout shifts, and lazy-load images below the fold. Load the primary image promptly.

## 5. Implement complete interactions

Use semantic HTML and native controls whenever possible. Make visible controls functional. Avoid dead links and decorative buttons that imply missing functionality. Implement loading, empty, error, and success states where the feature requires them.

Support keyboard access, visible focus, meaningful labels, useful alt text, and adequate target sizes. Do not rely on color or hover alone. Honor reduced motion. For motion, use subtle transitions that communicate state; avoid scroll hijacking and unnecessary perpetual animation.

Use the simplest architecture that satisfies the task. Keep dependencies purposeful, avoid unrelated features, and never put credentials in source or browser code.

## 6. Review the result

When supported, inspect the rendered website at representative desktop and mobile sizes. Check:

- A clear first impression and primary action.
- Consistent typography, spacing, alignment, and image crops.
- No overflow, clipped content, broken assets, or console errors.
- Working navigation, forms, filters, and dialogs that exist in scope.
- Keyboard behavior, focus visibility, readable contrast, and reduced motion.
- Sensible page title, description, heading hierarchy, and image loading.

Run relevant existing checks and builds. Do not add tests that merely repeat CSS or static content. Use meaningful functional checks for complex behavior. If browser inspection is unavailable, state that limit honestly; parsing HTML alone does not establish visual quality.

Fix observed problems in focused passes. Do not add visual complexity just to make the page appear more designed.

## 7. Deliver and publish

Summarize what changed, what was verified, and any content still needed. Link the actual files or verified deployment URL. Distinguish a local draft, a GitHub commit, and a deployed website.

Follow the user's chosen hosting workflow. Respect other applicable skills and authorization requirements. For GitHub-connected Cloudflare Pages, use the repository's real production branch and output directory; do not claim automatic deployments until the integration is confirmed. Never claim an account is connected based solely on a login performed on a different machine.

Do not publish a skill or site merely because this skill exists. Apply the task's actual authorized scope.
