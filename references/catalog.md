# Pattern catalog

Research snapshot: 2026-10-15. The source is [Impeccable's Slop catalog](https://impeccable.style/slop/#catalog), not an instruction set or a claim that DSLOPIFY implements its detector. The page labels rules **AI slop**, **Quality**, or **Your design system**, and describes a source, browser, or design-review check. Those are *source-site* classifications and layers, not automatic capabilities of these skills. Its navigation says 65 rules, while 67 rule cards were present in the page DOM at access time (4 + 8 + 11 + 7 + 12 + 6 + 5 + 4 + 10). Preserve that discrepancy instead of quietly dropping two cards. The linked rule names below are short identifiers; diagnosis and possible response are our paraphrases. A pattern is not a violation merely because a keyword occurs: context, product identity, semantics, and rendered behavior matter.

## Your design system (4)

Compare implemented values against the project's *actual* documented tokens, if any; absence of `DESIGN.md` is not a defect. [Detector guide](https://impeccable.style/docs/detector#check-against-your-design-system).

- [Font outside DESIGN.md](https://impeccable.style/slop/#rule-design-system-font) — A typeface departs from the documented set; use an existing face or record an intentional addition.
- [Color outside DESIGN.md](https://impeccable.style/slop/#rule-design-system-color) — A color falls outside the palette; use a token or establish a justified new one.
- [Radius outside DESIGN.md](https://impeccable.style/slop/#rule-design-system-radius) — A corner shape differs from the scale; align it or document its special role.
- [Font size outside DESIGN.md](https://impeccable.style/slop/#rule-design-system-font-size) — A size bypasses the type scale; reuse a step or justify a new one.

## Visual details (8)

Sources: [layout](https://impeccable.style/docs/layout), [polish](https://impeccable.style/docs/polish), [critique](https://impeccable.style/docs/critique); illustrative pages [side tabs](https://impeccable.style/antipattern-examples/thick-border-cards.html), [glass/glow](https://impeccable.style/antipattern-examples/lazy-cool.html).

- [Decorative grid-line background](https://impeccable.style/slop/#rule-codex-grid-background) — Grid marks add texture but no spatial task; keep them for measuring, mapping, or canvases.
- [Border accent on rounded element](https://impeccable.style/slop/#rule-border-accent-on-rounded) — A vivid thick outline overwhelms a rounded card; quiet the edge when it carries no meaning.
- [Glassmorphism everywhere](https://impeccable.style/slop/#rule-glassmorphism) — Blur and glow accumulate without communicating layers; reserve translucency for a real depth relationship.
- [Side-tab accent border](https://impeccable.style/slop/#rule-side-tab) — An alert-like stripe decorates ordinary content; keep it only when it denotes status.
- [Hairline border with wide shadow](https://impeccable.style/slop/#rule-gpt-thin-border-wide-shadow) — Two competing edge treatments frame the same card; simplify one, not every shadow in the app.
- [Repeating-gradient stripes](https://impeccable.style/slop/#rule-repeating-stripes-gradient) — Repeated bands fill space with noise; prefer a plain or purposeful surface.
- [Extreme border-radius on cards](https://impeccable.style/slop/#rule-over-round) — Oversized curves squeeze content or make cards interchangeable; size radii to the component.
- [Rough SVG illustrations](https://impeccable.style/slop/#rule-sketchy-svg) — Crude invented mascots or scenes undermine the visual language; use fitting assets or no illustration.

## Typography (11)

Sources: [typeset](https://impeccable.style/docs/typeset), example [Inter everywhere](https://impeccable.style/antipattern-examples/inter-everywhere.html), [oversized icon tiles](https://impeccable.style/antipattern-examples/massive-icons.html).

- [Label above a heading](https://impeccable.style/slop/#rule-kicker-above-heading) — Repeated little preludes contribute nothing beyond the heading; retain labels with navigational meaning.
- [Tiny interface text](https://impeccable.style/slop/#rule-undersized-ui-text) — Controls or supporting labels become difficult to read; increase their usable size.
- [Flat type hierarchy](https://impeccable.style/slop/#rule-flat-type-hierarchy) — Heading, label, and body look indistinguishable; separate roles with scale, weight, or spacing.
- [Icon tile stacked above heading](https://impeccable.style/slop/#rule-icon-tile-stack) — Generic icon boxes take priority over section meaning; remove or subordinate them.
- [Italic serif display headline](https://impeccable.style/slop/#rule-italic-serif-display) — A fashionable accent is repeated without brand purpose; keep intentional editorial typography.
- [Badge above the main headline](https://impeccable.style/slop/#rule-hero-eyebrow-chip) — Decorative hero pills displace useful information; retain a badge when it communicates status or category.
- [Oversized hero headline](https://impeccable.style/slop/#rule-oversized-h1) — Display text crowds the first viewport or wraps awkwardly; balance it against content and viewport.
- [Crushed letter spacing](https://impeccable.style/slop/#rule-extreme-negative-tracking) — Negative tracking makes display type collide; restore readable spacing.
- [Overused font](https://impeccable.style/slop/#rule-overused-font) — An unconsidered default font dominates everything; evaluate voice rather than automatically replace a brand font.
- [Single font for everything](https://impeccable.style/slop/#rule-single-font) — Uniform styling can flatten roles; a single family is fine if its weights, sizes, and layout make a hierarchy.
- [All-caps body text](https://impeccable.style/slop/#rule-all-caps-body) — Extended uppercase passages impede reading; use sentence case for prose.

## Color and contrast (7)

Sources: [colorize](https://impeccable.style/docs/colorize), [contrast audit](https://impeccable.style/docs/audit), examples [purple gradients](https://impeccable.style/antipattern-examples/purple-gradients.html), [bad contrast](https://impeccable.style/antipattern-examples/bad-contrast.html).

- [Radial-gradient background halo](https://impeccable.style/slop/#rule-radial-halo) — A decorative aura substitutes for hierarchy; simplify unless it reinforces the visual direction.
- [Soft spotlight behind content](https://impeccable.style/slop/#rule-radial-spotlight-glow) — A glow spot draws focus without explaining anything; give attention to the actual task.
- [AI color palette](https://impeccable.style/slop/#rule-ai-color-palette) — Familiar purple/blue gradients spread across surfaces; evaluate whether those colors belong to the brand.
- [Dark mode with glowing accents](https://impeccable.style/slop/#rule-dark-glow) — Neon on dark overwhelms interface content; constrain emphasis, but retain deliberate brand lighting.
- [Gradient text](https://impeccable.style/slop/#rule-gradient-text) — Decorative gradient lettering can hurt legibility; choose a readable solid treatment if no intent supports it.
- [Gray text on colored background](https://impeccable.style/slop/#rule-gray-on-color) — Muted text loses contrast on a tinted surface; test computed foreground/background and improve it.
- [Cream / beige palette](https://impeccable.style/slop/#rule-cream-palette) — A fashionable neutral palette can be a template tell; do not reject a documented brand or editorial palette on hue alone.

## Layout and space (12)

Sources: [layout](https://impeccable.style/docs/layout), [harden](https://impeccable.style/docs/harden), [typeset](https://impeccable.style/docs/typeset), [critique](https://impeccable.style/docs/critique); examples [nested cards](https://impeccable.style/antipattern-examples/cardocalypse.html), [template layouts](https://impeccable.style/antipattern-examples/layout-templates.html), [crowded dialog](https://impeccable.style/antipattern-examples/modal-abuse.html).

- [Tiny numbered section labels](https://impeccable.style/slop/#rule-numbered-section-labels) — Decorative numbers repeat section headings; keep numbers only if they establish sequence or navigation.
- [Cards flush against the scroller edge](https://impeccable.style/slop/#rule-edge-flush-cards) — Scroll content lacks breathing room at the viewport edge; add safe side spacing.
- [Text covered by another element](https://impeccable.style/slop/#rule-text-occlusion) — Overlap hides content; fix stacking or flow at the failing viewport.
- [Unbalanced opening columns](https://impeccable.style/slop/#rule-first-viewport-column-overflow) — Hero columns compete or overrun the first screen; rebalance for actual content.
- [Heading closer to the previous section](https://impeccable.style/slop/#rule-heading-rhythm) — Spacing suggests a heading belongs above rather than below; correct grouping.
- [Hero metric layout](https://impeccable.style/slop/#rule-hero-metric-layout) — Decorative hero KPIs impersonate evidence; use verified relevant metrics or drop them.
- [Identical card grids](https://impeccable.style/slop/#rule-identical-card-grids) — The same grid repeats regardless of content; let content determine arrangement.
- [Monotonous spacing](https://impeccable.style/slop/#rule-monotonous-spacing) — All gaps share a value, flattening hierarchy; distinguish related and unrelated items.
- [Nested cards](https://impeccable.style/slop/#rule-nested-cards) — Boxed surfaces pile up and waste room; remove a wrapper where grouping survives without it.
- [Line length too long](https://impeccable.style/slop/#rule-line-length) — Long prose lines tax reading; constrain measure without shrinking the page indiscriminately.
- [Content overflowing its container](https://impeccable.style/slop/#rule-text-overflow) — Long values escape or clip; wrap, resize, or offer access to the full value.
- [Clipped menus and popovers](https://impeccable.style/slop/#rule-clipped-overflow-container) — An ancestor clips interactive overlays; repair stacking/portal behavior and keyboard reachability.

## Motion (6)

Sources: [animate](https://impeccable.style/docs/animate), [optimize](https://impeccable.style/docs/optimize), example [excess motion](https://impeccable.style/antipattern-examples/lazy-impact.html).

- [Pulsing status dot](https://impeccable.style/slop/#rule-pulsing-dot) — Continuous pulse decorates a state that could be static; retain only if temporal information matters.
- [Decorative blinking cursor](https://impeccable.style/slop/#rule-blinking-cursor) — A fake cursor implies editable text; remove misleading decoration.
- [Auto-scrolling marquee](https://impeccable.style/slop/#rule-marquee) — Moving content demands attention and may be hard to pause; show content without forced motion.
- [Bounce or elastic easing](https://impeccable.style/slop/#rule-bounce-easing) — Springy movement on every control distracts; reserve expressive motion for meaningful moments.
- [Animation that changes layout](https://impeccable.style/slop/#rule-layout-transition) — Animating geometry causes reflow or instability; use cheaper properties when equivalent, preserving interaction feedback.
- [Images that move on hover](https://impeccable.style/slop/#rule-image-hover-transform) — Image movement adds novelty without meaning; keep a stable image or purposeful affordance.

## Copy (5)

Sources: [clarify](https://impeccable.style/docs/clarify), example [redundant writing](https://impeccable.style/antipattern-examples/redundant-ux-writing.html).

- [Same text repeated inside one container](https://impeccable.style/slop/#rule-repeated-container-text) — Duplicate hints add reading cost; keep the instruction where it is needed.
- [Em-dash overuse](https://impeccable.style/slop/#rule-em-dash-overuse) — Repeated dramatic punctuation overwhelms prose; vary sentence structure without banning dashes.
- [Generic marketing claims](https://impeccable.style/slop/#rule-marketing-buzzword) — Vague superlatives avoid product facts; explain a real capability or outcome without inventing claims.
- [Forced contrast](https://impeccable.style/slop/#rule-aphoristic-cadence) — Repeated slogan-like oppositions obscure meaning; state the actual distinction.
- [Calling things “theater”](https://impeccable.style/slop/#rule-theater-slop-phrase) — A dismissive label replaces a reason; explain the concrete failure instead.

## Imagery (4)

Sources: [critique](https://impeccable.style/docs/critique), [polish](https://impeccable.style/docs/polish), [harden](https://impeccable.style/docs/harden).

- [Placeholder-style illustrations](https://impeccable.style/slop/#rule-shape-assembled-illustration) — Arbitrary basic shapes offer no product information; use relevant imagery or omit it.
- [Jagged image masks](https://impeccable.style/slop/#rule-organic-clip-path) — Rough CSS crops imitate a torn edge poorly; use a prepared asset when that treatment matters.
- [Images hidden under overlays](https://impeccable.style/slop/#rule-buried-raster) — Heavy overlays bury the image's contribution; lighten the overlay or drop the image.
- [Broken or placeholder image](https://impeccable.style/slop/#rule-broken-image) — Missing assets leave an unfinished surface; supply the intended image or remove the element.

## General quality (10)

Sources: [harden](https://impeccable.style/docs/harden), [layout](https://impeccable.style/docs/layout), [typeset](https://impeccable.style/docs/typeset), [audit](https://impeccable.style/docs/audit).

- [JavaScript errors on load](https://impeccable.style/slop/#rule-script-error) — An uncaught load error may disable UI; resolve it and test the affected flow.
- [Content stuck waiting to appear](https://impeccable.style/slop/#rule-content-hidden-at-rest) — Entrance effects can leave content invisible; make essential content visible without animation.
- [Cramped padding](https://impeccable.style/slop/#rule-cramped-padding) — Content touches its control or card edges; use the established spacing scale.
- [Body text touching the page edge](https://impeccable.style/slop/#rule-body-text-viewport-edge) — Reading at small widths needs side gutters; add them without shrinking usable content excessively.
- [Justified text](https://impeccable.style/slop/#rule-justified-text) — Uneven word gaps impair prose; use start alignment unless tested hyphenation solves it.
- [Low-contrast text](https://impeccable.style/slop/#rule-low-contrast) — Text blends with its surface; assess WCAG AA, ordinarily 4.5:1 or 3:1 for large text.
- [Subsection (h3), skipped h2](https://impeccable.style/slop/#rule-skipped-heading) — Heading levels miss a structural step; correct hierarchy without choosing levels for appearance alone.
- [Tight line height](https://impeccable.style/slop/#rule-tight-leading) — Prose lines crowd one another; tune leading for the font and measure.
- [Tiny body text](https://impeccable.style/slop/#rule-tiny-text) — Small paragraphs are hard to read; use a comfortable size, approximately 16px as a starting point.
- [Wide letter spacing on body text](https://impeccable.style/slop/#rule-wide-tracking) — Excess tracking impairs continuous reading; reserve it for short labels.

## Access record and interpretation

- Accessed the live [Slop page](https://impeccable.style/slop/) in Chrome via `chrome-devtools-axi` (DOM catalog and the 2022/2025/2026 embedded fictional-product examples) and via HTTP/1.1 on 2026-10-15. Initial browser navigation timed out but the loaded tab was subsequently inspected. Initial HTTP/2 fetch failed; HTTP/1.1 succeeded.
- Fetched and read HTML from all eleven linked examples: [purple-gradients](https://impeccable.style/antipattern-examples/purple-gradients.html), [lazy-cool](https://impeccable.style/antipattern-examples/lazy-cool.html), [lazy-impact](https://impeccable.style/antipattern-examples/lazy-impact.html), [thick-border-cards](https://impeccable.style/antipattern-examples/thick-border-cards.html), [cardocalypse](https://impeccable.style/antipattern-examples/cardocalypse.html), [layout-templates](https://impeccable.style/antipattern-examples/layout-templates.html), [inter-everywhere](https://impeccable.style/antipattern-examples/inter-everywhere.html), [massive-icons](https://impeccable.style/antipattern-examples/massive-icons.html), [bad-contrast](https://impeccable.style/antipattern-examples/bad-contrast.html), [redundant-ux-writing](https://impeccable.style/antipattern-examples/redundant-ux-writing.html), and [modal-abuse](https://impeccable.style/antipattern-examples/modal-abuse.html). These are deliberately exaggerated demonstrations, not independent evidence that any target project has a defect.
- Fetched and inspected the linked guides: [detector](https://impeccable.style/docs/detector), [critique](https://impeccable.style/docs/critique), [layout](https://impeccable.style/docs/layout), [polish](https://impeccable.style/docs/polish), [typeset](https://impeccable.style/docs/typeset), [colorize](https://impeccable.style/docs/colorize), [animate](https://impeccable.style/docs/animate), [clarify](https://impeccable.style/docs/clarify), [audit](https://impeccable.style/docs/audit), [harden](https://impeccable.style/docs/harden), and [optimize](https://impeccable.style/docs/optimize). The detector guide distinguishes source checks from rendered-page checks and says a clean scan does not replace design critique; the workflow guides emphasize context and checking changes. We did **not** access every page linked anywhere on the site, inspect proprietary detector implementation, or run Impeccable's detector; no claims here depend on those actions.
