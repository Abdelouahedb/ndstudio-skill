# Adaptable implementation recipes

These are proposed starting points for original work. They are not measured NDS tokens. Use the existing project system where applicable; make new tokens consistent with the chosen family. Read only the recipe relevant to the current brief.

## Quiet editorial

**Composition:** Compact horizontal navigation; an opening grid with purposeful empty space opposite a medium-to-large statement; expansive media; editorial explanation; an open work/program index; compact news or updates; clear closing contact/action. On a phone, collapse to one meaningful reading column and retain breathing room without an unnecessarily empty screen.

**Type:** A precise sans for display and body. Geist or a project-supplied grotesk can approximate the role without pretending to be Neue Montreal. Consider 36-64px display and 18-24px editorial body for new work; tune to content rather than copying sample sizes.

**Surfaces:** Near-white, charcoal, muted text, faint rules. Let photography supply most color. Use small labels sparingly. Avoid styling every paragraph as a display statement.

**Useful interaction:** Work/program filtering, clear links, contextual detail and readable navigation. Motion can be limited to gentle image or section entrances.

## Monumental campaign

**Composition:** One short opening claim; a coherent image scene; concrete evidence; plain-language guidance; resources or participatory action; FAQ. Change density and surface color as the subject changes. Do not pad the structure with unrelated feature cards.

**Type:** A bold grotesk with controlled tight leading. Aim for a large but readable statement; choose fluid sizing and semantic text instead of embedding the headline in an image. Use shorter mobile lines intentionally.

**Surfaces:** One deep ink, one warm light surface, one subject-related accent. For example, burgundy and cream can suit food or material themes, but choose colors for this user's brand.

**Useful interaction:** Anchored chapters, resource access, disclosures and actual participation. An image sequence should have a static fallback; never require prolonged scroll animation to reveal essential information.

## Technical mission

**Composition:** Compact identity and action; mission statement; documentary scientific or technical media; focus areas; role/opportunity detail; requirements or schedule; FAQ/contact; repeated contextual apply action. Scientific recruitment should connect ambition to what a candidate will actually do.

**Type:** Geist or Inter can carry a restrained mission direction. An available extended display face can be used for a short high-impact headline; keep paragraphs in a readable sans. Do not assume Microgramma is licensed or available.

**Surfaces:** Charcoal and pale text with one accent from the subject. Thin rules and concise labels can organize denser information. Use real maps, diagrams, or research images only when they communicate something meaningful.

**Useful interaction:** Section navigation, accessible FAQ disclosures, explicit application destination, deadline, and requirements. Keep deadline and primary action within the first meaningful mobile content when supplied. Never fabricate requirements or recruitment claims.

## Warm service

**Composition:** Friendly introduction beside or above the central task; search/application entry; short explanation; result/comparison area or process stages; relevant help; closing entry action. Existing result panels need improved scan order rather than an added marketing hero.

**Type:** An expressive serif for a few short headlines with neutral sans for controls and body. Instrument Serif and a project-supplied sans are possible alternatives; use fonts already available if changing them would disrupt the brand.

**Surfaces:** Warm white or a pale cool surface with dark text, one strong action color, quiet separators, and contained controls. Rounded inputs, cards, and useful shadows are compatible with this family when they signal containment or interactivity.

**Useful interaction:** Visible labels, query feedback, clear results, filter summaries, reversible choices, useful empty/error states, and readable next steps. Do not introduce voice, uploads, accounts, or chat simply because a reference has them.

## Product narrative

**Composition:** Clear benefit and entry action; authentic product preview; explanations of a few meaningful tasks; grounded benefits and assumptions; support by audience; final action. Feature previews should correspond to the user's real product or be explicitly labeled as mockups.

**Type and surfaces:** Consider a warm serif/sans pairing or an established product sans. Keep space around previews and controls generous. Use coherent product-related imagery instead of a miscellaneous set of decorative icons.

**Useful interaction:** Real demo state, accessible tabs/accordions if useful, clear install/action destination. A projection calculator must use supplied, documented assumptions and label illustrative results.

## Example brief transformation

Request: "Build a science fellowship page in NDS style."

Suitable direction: Technical mission, drawing on Genesis's mission hierarchy and Tech Force's recruitment path. Use a compact header with Apply; a short, left-aligned fellowship statement and one relevant laboratory image; a concise opportunity explanation; research themes; eligibility, funding, and timing from the user's content; accessible FAQ; a closing application action. Use existing typography or a restrained sans, dark/light surfaces chosen for the institution, and a single accent. On mobile put the opportunity and action early, stack themes and requirements, and crop imagery around its actual focal point. Unknown dates or funding should be flagged for content completion, not invented. This combines relevant principles without importing government branding or unrelated chat/financial features.

## Fluid tokens: warm service example

This small example shows the kind of system to define, not a required palette or structure. Change values and type to fit the chosen family and existing project.

```css
:root {
  --surface: #f6f3ea;
  --ink: #181a1b;
  --muted: #56595c;
  --accent: #173d36;
  --rule: #d0d0c7;
  --font-display: Georgia, serif;
  --font-body: system-ui, sans-serif;
  --gutter: clamp(1.25rem, 3vw, 3.5rem);
  --section-space: clamp(3rem, 7vw, 7rem);
  --display-size: clamp(2.5rem, 6vw, 6rem);
  --body-size: clamp(1rem, 0.95rem + 0.25vw, 1.2rem);
}
.hero-title {
  color: var(--ink);
  font-family: var(--font-display);
  font-size: var(--display-size);
  line-height: 1.03;
  letter-spacing: -0.035em;
  max-width: 14ch;
  overflow-wrap: break-word;
}
.content-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: var(--gutter);
}
.content-grid > * { min-width: 0; }
@media (max-width: 48rem) {
  .content-grid { grid-template-columns: minmax(0, 1fr); }
}
```

When adding motion, scope reduced-motion overrides to the animated components. Keep the default content visible, remove optional transitions and transforms under `prefers-reduced-motion`, and use a static substitute for animated media. Do not use overflow clipping to conceal layout bugs; fix their cause and inspect the rendered page.
