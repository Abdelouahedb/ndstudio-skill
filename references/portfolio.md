# Portfolio reference

Research date: September 30, 2026. Source sites are public references for inspiration. This document records an observed portfolio snapshot, not official NDS specifications. Sites, assets, and content may change. Reinspect a relevant live page for close matching.

## Scope and evidence

[National Design Studio's home page](https://ndstudio.gov/) listed these eight selected projects at research time: America.gov, TrumpRX, Real Food, Genesis Mission, Trump Accounts, Tech Force, NASA Force, and OPM Retirements. This gives a primary-source basis for attribution. The studio home and all eight public entry pages were opened; NASA Force provided readable DOM content and styles but its screenshot remained blank in this browser session. That page's visual composition and animations are unverified.

The other pages were examined using screenshots and/or visible DOM content. The studio homepage was specifically compared at 1440 x 900 and 390 x 844. The portfolio review did not audit every route, complete applications, test backends, or establish accessibility conformance. Font names below describe computed CSS families, not proof of font licensing or successful loading of every face. Sizes are sampled at particular viewports and are not reusable design tokens.

## Quiet editorial: National Design Studio

Source: [ndstudio.gov](https://ndstudio.gov/).

**Observed:** Near-white/light gray opening surface and dark text. A small mark and restrained navigation sit above substantial open space. On desktop the mission statement occupies the right half, balanced against an almost empty left half. Broad photographic/video media follows. Large editorial paragraphs, selected work, news, and a substantial footer continue the page. A Roman-numeral section label introduces selected work. Computed type family was `ppNueMontreal`; an initial desktop h1 sample was 44px and editorial paragraph samples were 30px. On the narrow viewport the statement becomes a single left-aligned column and navigation becomes a Menu control.

**Adaptation:** Use compositional confidence instead of sheer headline size: offset statement, consistent margins, image-led proof, open lists. Suits foundations, cultural organizations, studios, portfolios, and institutional narratives. Neue Montreal is not assumed to be available; choose a suitable accessible font supplied by the project or an available alternative.

## Monumental campaign: Real Food

Source: [realfood.gov](https://realfood.gov/).

**Observed:** A near-black/brown opening with pale cream type, oversized centered statement, short supporting explanation, and video content. Other scenes use isolated food imagery and stronger color fields. The document transitions to a cream background with large education headings, food groups, downloadable resources, and FAQs. Computed display family was `Die Grotesk D`, with `Die Grotesk B` for some smaller labels. A wider-view h1 sample was 170px; later narrower capture wrapped the headline onto two lines.

**Adaptation:** Build a clear sequence from claim to evidence to guidance to action. Use large typographic statements and coherent subject imagery to carry the campaign. A public-health page's claims are content, not reusable design facts: do not transfer them to another site. Numbers, categories, and download links should come from the user's actual content.

## Technical mission: Genesis Mission and Tech Force

Sources: [genesis.energy.gov](https://genesis.energy.gov/), [techforce.gov](https://techforce.gov/).

**Observed, Genesis:** Dark background, light type, compact identity/utility information and a clock in the opening area, a large left-aligned mission heading, and prominent cinematic media. Energy, discovery science, and national security are subsequent major subjects, followed by information and a closing invitation. Computed heading family was `Geist`; a heading sample was 64px.

**Observed, Tech Force:** Black/light-text recruitment direction, compact header actions, ample opening space, large left-aligned recruitment statement, thin rule, explanatory content, a renewed application invitation, FAQs, contact information, and a final apply action. Computed family was `Inter`. Narrower samples included a 64px h1 and 48px invitation heading.

**Adaptation:** Use strong mission language, relevant technical imagery, exact information, and a prominent action. Choose sparse sans typography for grounded technical credibility. A utility clock is an isolated motif, not a requirement for science websites. Recruitment flows need requirements, timeline, and application context; decorative ambition cannot substitute for that information.

## NASA Force: content and typography evidence only

Source: [nasaforce.gov](https://nasaforce.gov/).

**Observed:** DOM content exposed the heading "Build the Future of Humanity" and subsequent recruitment information. Computed h1 family was `Microgramma D Extended`, with a 52px sample; a secondary heading used `Geist` at 28px. The page was linked from NDS's selected work.

**Limit:** Rendered screenshots stayed blank. Do not infer a full layout, imagery, colors, or motion from this inspection. An extended technical display role can be considered for appropriate recruitment work, but a faithful NASA Force treatment requires a fresh visual reference.

## Warm service: America.gov

Source: [america.gov](https://america.gov/).

**Observed:** A friendly serif greeting on a pale cool surface, compact identity and Menu control, and a large natural-language input near the start. The input includes attachment, voice, and send controls. Photographic example prompts support discovery; explanations, source/privacy information, and previews of future capabilities follow. The DOM distinguishes future previews from currently offered functions. Computed h1 family was `Rhymes Text` at a 48px sample; information headings used `Helvetica Now Display` at 28px.

**Adaptation:** Put the user's question or task at the center, then explain what happens and why results can be trusted. The service input and reassuring hierarchy transfer to directories and help portals. Chat, uploads, and voice are functional requirements only if requested and implemented. Rounded input surfaces and blue are this project's choices, not portfolio-wide rules.

## Warm service: TrumpRX

Source: [trumprx.gov](https://trumprx.gov/).

**Observed:** Warm off-white background, expressive serif headline, floating pill imagery, compact search/location/browse controls, and a prominent medication search area. Narrative price comparisons, a product listing, and audience-specific FAQs continue the page. Computed heading family was `Instrument Serif`; sampled opening size was about 110px and section headings 48px. Rounded containers and subtle shadows occur in this service experience.

**Adaptation:** Pair an expressive introduction with clear browsing, predictable result rows, and transparent comparisons. Keep the lookup task reachable. Use genuine user data for prices or claims; the reference's figures and statements are not validation of those facts for another product.

## Human service: OPM Retirements

Source: [retire.opm.gov](https://retire.opm.gov/).

**Observed:** Human-centered full-bleed photography, a serif retirement heading over the image, explanatory sans body copy, and two clearly differentiated entry actions. The public page explains the process and contains interface previews, an interactive planning estimate with sliders, and FAQs. The inspected page included three concise process stages and visible labels for retirement age, service years, and salary. No sign-in or application was completed.

**Adaptation:** Use relatable imagery to connect a bureaucratic task to the person's life. Give users the right entry path and enough information to proceed confidently. Progressive disclosure, clear estimates, and step explanation can improve service UX. Do not describe the authenticated application's usability as verified by this landing-page inspection.

## Product narrative: Trump Accounts

Source: [trumpaccounts.gov](https://trumpaccounts.gov/).

**Observed:** A warm pale surface, large serif heading, app-download action, and imagery including an app icon, coins, glass objects, and phone interface previews. Sections demonstrate account management, explain benefits, illustrate growth scenarios, and group FAQs by audience. Computed heading family was `Instrument Serif`; opening sample was approximately 51px and subsequent section samples 54px. The opening screenshot was captured during a blur transition, so it is not evidence of the settled hero's complete composition.

**Adaptation:** Tell the product story using authentic interface previews and short explanations of meaningful tasks. Match any illustrations in material, lighting, and scale. Financial projections require supplied assumptions and clear labeling; do not invent growth outcomes for decorative impact.

## Synthesis, not an official system

Across the inspected examples, useful recurring decisions include strong headline hierarchy, limited navigation, meaningful large images, clear separation between major subjects, and prominent user actions. Their palettes, type families, card shapes, and hero arrangements differ substantially. The reusable lesson is to connect visual confidence to the user's actual task; there is no single NDS font, palette, hero, or layout to reproduce everywhere.
