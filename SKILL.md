---
name: ndstudio
description: "Use when creating or refining website UI/UX inspired by National Design Studio (ndstudio.gov) or its portfolio, including editorial, campaign, recruitment, and service experiences. Applies to requests for NDS or ND Studio style; ordinary frontend work without this design intent does not need this skill."
---

# National Design Studio Inspired UI/UX

Create original websites with the clarity, typographic confidence, image direction, and purposeful interactions seen across National Design Studio's portfolio. The portfolio contains several visual languages; select one for the user's audience and task. This is an independent inspiration skill, not an official studio design system.

## Establish the direction

Read [the portfolio reference](references/portfolio.md) before choosing a direction. It separates live observations from suggested adaptations. Use the user's preferred reference when supplied; otherwise choose a family using the table below. Inspect the existing project, content, brand, routes, and main user action. Ask a focused question only when the missing answer would materially change the result; otherwise state a reasonable assumption and continue.

| Purpose | Starting family | Primary references |
| --- | --- | --- |
| Studio, culture, institution, portfolio | Quiet editorial | ndstudio.gov |
| Awareness, education, public campaign | Monumental campaign | realfood.gov |
| Science, research, recruitment | Technical mission | genesis.energy.gov, techforce.gov, nasaforce.gov |
| Search, discovery, task completion | Warm service | america.gov, trumprx.gov, retire.opm.gov |
| Consumer product explanation | Product narrative | trumpaccounts.gov |

For a new page, choose one family and one signature gesture: an offset statement, oversized headline, image sequence, or prominent service input. State the reference, why it suits the brief, and the proposed section rhythm in a short note. Avoid mixing every family's styling into one page. For a component or local redesign, inherit the surrounding design system and apply the relevant hierarchy or interaction pattern within the requested scope.

When a precise visual match is requested, inspect the live reference or user screenshot first. Verify font names through computed styles when possible. Without browsing, use the dated reference notes and identify their limits; do not invent exact studio tokens or claim a live inspection.

## Design the page

- **Hierarchy:** Give the first viewport one clear idea and an obvious next action. Use purposeful negative space and a coherent alignment grid. Sparse navigation, compact utility labels, and a large statement can establish authority without decorative clutter.
- **Typography:** Choose a display role appropriate to the family and a readable body face. Editorial pages can use a single precise sans; warm services can pair an expressive serif with a neutral sans; technical missions can use a controlled grotesk or extended display face. Use available, licensed fonts with sensible fallbacks. Set fluid sizes and deliberate line lengths; plan mobile wrapping separately.
- **Composition:** Let content determine the sequence. Alternate broad visual moments with compact explanations or useful controls. Use rules, aligned lists, or open sections where they convey relationships better than cards. Cards and rounded controls are appropriate for contained tasks and product information; they are not forbidden.
- **Color:** Establish named tokens for surfaces, text, accents, rules, and interaction states. Select a restrained palette for this project; sample values in the reference are suggestions, not universal NDS colors. Strong dark/light section changes should mark a change in subject or pace.
- **Imagery:** Use a few specific images with intentional scale, crop, lighting, and placement. Match the subject: documentary scenes for people, coherent cutouts for campaigns, real research imagery for science. Use user-owned, licensed, or newly generated assets. If assets are missing, use honest placeholders and disclose them. Avoid arbitrary stock images or generic abstract blobs as the signature gesture.
- **Copy:** Use concrete headlines, concise explanations, useful labels, and real evidence. Preserve the user's voice and facts. Do not inherit political slogans, official seals, government identity, or claims from the references. Do not invent endorsements, testimonials, metrics, prices, or eligibility details.

## Make the experience useful

Keep the main action reachable before long storytelling. Explain prerequisites, destination, and next steps where relevant. A service page should expose search or application entry early; a recruitment page should clarify opportunity and requirements before repeating its apply action. Use progressive disclosure for secondary detail, not critical eligibility or pricing information.

Implement the actual requested behavior: navigation, search/filter feedback, menus, disclosures, forms, loading, errors, empty results, and recovery as applicable. Reuse existing data and state handling. A prototype without a backend should identify simulated behavior; do not add inert controls that appear functional.

Motion should explain hierarchy or support a specific image sequence. Prefer brief transitions and a single intentional entrance over animation on every element. Keep content available when animation fails, preserve ordinary scrolling, support reduced motion, and provide controls for continuous moving media. Avoid making users wait through a cinematic introduction to perform their task.

## Implement and inspect

Use the project's existing framework and component ownership. Preserve working routes, data contracts, content intent, and brand constraints during redesigns. For new work, use reusable tokens and components where they help maintain consistency. Consult [implementation recipes](references/recipes.md) for a relevant family; their dimensions and palettes are adaptable starting points.

Inspect the rendered result at a narrow phone width, a mid-width layout, and desktop. Check headline wrapping, focal-point cropping, control reachability, document overflow, keyboard navigation, visible focus, readable contrast, meaningful headings and labels, and reduced-motion behavior. For long narratives inspect the beginning, transitions, and ending, not only the hero. Run relevant existing project checks and exercise changed interactions. If browser verification is unavailable, state what remains unverified.

Before delivery, compare against the selected reference principle: is the signature gesture visible, is the main task clear, and does the section rhythm fit this content? Fix material failures rather than claiming resemblance through colors alone. Report the delivered result, selected direction, verified behavior, and any material asset or functionality limitations. Do not deploy or publish unless the user requested it.
