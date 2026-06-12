---
name: TimDesign Light Architectural Creative System
version: 2.0
status: canonical
purpose: Single source of truth for bright, expressive, architectural TimDesign homepage and Webflow design work.
brand_positioning: Premium Webflow websites for high-end real estate, architecture, beautiful homes, property developers, brokers, and remarkable places in French-speaking Switzerland.
visual_thesis: Bright architectural minimalism with a visible creative signature.

colors:
  background:
    ivory: '#F6F0E6'
    warm_paper: '#FFFDF8'
    limestone: '#E8DED0'
    plaster: '#DDD2C3'
    chalk: '#FAF7F1'
  text:
    charcoal: '#171512'
    graphite: '#2B2925'
    muted: 'rgba(23, 21, 18, .68)'
    soft: 'rgba(23, 21, 18, .46)'
  accent:
    clay: '#C77653'
    sand: '#B99468'
    olive: '#6E735F'
    blue_grey: '#7E8A90'
  border:
    subtle: 'rgba(23, 21, 18, .12)'
    medium: 'rgba(23, 21, 18, .22)'
    warm: 'rgba(199, 118, 83, .30)'
  dark_contrast:
    night: '#07111B'
    ink: '#080706'
    cream: '#F6EEDF'

typography:
  display:
    role: Large expressive editorial headlines
    stack: 'RCL Prime Serif, Abigail, Runalto, Cormorant Garamond, Georgia, serif'
    weight: '300-700 depending on font'
    tracking: '-0.055em to -0.025em on large headings'
    line_height: '.88-1.05'
  text:
    role: Body, navigation, forms, UI
    stack: 'IF Bosch, Neue Haas Grotesk Text, Helvetica Neue, Arial, sans-serif'
    weight: '400-520'
    tracking: '-0.012em to 0'
    line_height: '1.55-1.85'
  label:
    role: Micro-labels, section markers, metadata, coordinates
    stack: 'IF Bosch, Helvetica Neue, Arial, sans-serif'
    transform: uppercase
    tracking: '.11em-.18em'
    size: '.62rem-.78rem'

spacing:
  base: 8
  scale_px: [0, 8, 16, 24, 32, 48, 64, 88, 120, 160]
  sections: 'clamp(6rem, 12vw, 12rem)'
  container: 'min(100% - clamp(2rem, 6vw, 7rem), 1640px)'
  narrow_container: 'min(100% - clamp(2rem, 6vw, 7rem), 1120px)'

layout:
  grid: 12 columns desktop, 6 tablet, 4 mobile
  principle: Preserve Swiss precision, then introduce one deliberate asymmetry per major section.
  rhythm: Alternate dense editorial moments with generous silence.
  mobile: Designed composition, not simple stacking.

radii:
  none: 0
  xs: 2
  sm: 4
  md: 10
  pill: 999

motion:
  easing:
    soft: 'cubic-bezier(.19, 1, .22, 1)'
    precise: 'cubic-bezier(.16, 1, .3, 1)'
    editorial: 'cubic-bezier(.77, 0, .175, 1)'
  duration:
    hover: '220ms-420ms'
    reveal: '700ms-1100ms'
    image_settle: '1000ms-1600ms'
    parallax: 'scroll-linked, subtle, transform only'
  roles:
    word_reveal: Split large headings into words or lines with staggered mask reveal.
    image_mask: Reveal images through inset/clip-path or translate mask.
    line_draw: Draw rules, coordinates, and section dividers.
    card_stagger: Stagger editorial modules with varied x/y origins.
    parallax_layers: Use slight image depth on hero and showcase only.
  reduced_motion: Disable parallax, large transforms, blur, and stagger. Preserve content and hierarchy.

shadows:
  almost_none: '0 1px 2px rgba(23, 21, 18, .04)'
  soft_blue_grey: '0 28px 80px rgba(70, 88, 106, .12)'
  image_depth: '0 34px 90px rgba(23, 21, 18, .16)'

component_principles:
  buttons: Quiet, precise, tactile. Use line, fill inversion, slight lift, or arrow movement.
  cards: Avoid SaaS card grids. Use editorial modules with varied proportions.
  images: Treat as art direction, not decoration. Crop for light, geometry, material, silence.
  forms: Minimal, labelled, calm, premium. No placeholder-only labels.
  footer: Structured, calm, slightly deeper contrast. Should feel like a closing architectural plaque.
---

# TimDesign Light Architectural Creative System

This file replaces the earlier safe light design system. The previous direction produced a clean but generic result. This version is intentionally more opinionated: it should help AI agents, Lovable, Codex, Webflow builds, and design iterations generate work that feels like a creative senior web designer with a real visual signature.

## Core identity

TimDesign should not look like a generic premium agency template. The visual language is bright, minimal, architectural, and commercial, but it must carry a distinct artistic hand.

The desired reaction is:

> This person is not just assembling Webflow sections. He has an eye, rhythm, taste, and creative direction.

The site should feel like a refined architecture magazine, a property monograph, a gallery wall, and a designer portfolio. It should be useful and commercially clear, while still creating a memorable visual experience.

## Creative tension

Every major composition should balance these tensions:

- Minimal, but not empty.
- Premium, but not generic luxury.
- Architectural, but not cold.
- Commercial, but not salesy.
- Artistic, but still readable.
- Swiss precise, but not rigid.
- Light and airy, but not bland.

When an AI agent must choose between safe symmetry and a more memorable editorial composition, prefer the editorial composition as long as readability, responsive behavior, and conversion remain strong.

## Anti-template rules

Avoid default landing-page patterns:

- Centered hero with text above a generic image.
- Equal cards in a predictable 3-column grid as the main design device.
- Repeated fade-up animations everywhere.
- Generic “premium” words without proof of taste.
- Sterile white/grey palettes.
- Decorative icons that do not add meaning.
- Hero sections that could belong to a SaaS, consultant, or generic agency.

Use instead:

- Asymmetric editorial grids.
- Large expressive headlines with intentional line breaks.
- Image layers and crops that feel curated.
- Thin rules, section numbers, coordinates, and designer annotations.
- Alternating silence and intensity.
- Micro-interactions that feel crafted.
- Narrative progression between sections.

## Homepage narrative

The homepage should unfold like a visit through a remarkable place.

1. First impression: an iconic visual moment.
2. Orientation: what TimDesign does and for whom.
3. Perception: why premium real estate needs better digital direction.
4. Expertise: what Tim sees before designing.
5. Services: what can be built.
6. Showcase: how the visual language treats places and projects.
7. Process: how the work becomes concrete.
8. Contact: a quiet, confident invitation.

The page should not feel like a list of sections. Each section should create a reason to continue.

## Hero system

The hero is the most important proof of taste. It must not be conventional.

Recommended hero direction:

- Full first viewport or near-full first viewport.
- Large fragmented editorial headline.
- One dominant architectural image crop.
- One secondary detail crop, offset or partially overlapping.
- One small metadata panel with project-like information.
- Thin grid lines or measurement marks.
- CTA area that feels integrated, not pasted below text.

Suggested hero headline:

> Des sites lumineux pour des lieux qui ne devraient jamais paraître ordinaires.

Suggested supporting text:

> TimDesign conçoit des expériences Webflow premium pour l’immobilier haut de gamme, l’architecture et les propriétés remarquables en Suisse romande.

Hero details may include:

- `Webflow premium`
- `Immobilier haut de gamme`
- `Architecture & lieux remarquables`
- `Suisse romande`

Composition guidance:

- Use headline scale as the main visual force.
- Let at least one word or line behave differently through italic serif, lighter weight, or offset alignment.
- Keep text readable and emotionally direct.
- Use images to create atmosphere, not to fill space.
- Use one restrained parallax or image-settle effect.

## Typography direction

Typography should carry more personality than the first generated version.

Use a strong contrast:

- Large expressive serif for display headlines.
- Clean grotesk/sans for body and UI.
- Uppercase micro-labels for architecture-like annotations.

Large headings:

- Can be huge.
- Should use intentional line breaks.
- May break symmetry.
- Should feel composed like a poster or editorial spread.
- Use tight tracking, but protect readability.

Body copy:

- Calm and readable.
- Generous line height.
- Avoid corporate filler.
- Prefer short, precise, confident paragraphs.

Labels:

- Use as a visual system.
- Examples: `01 — Approche`, `Coord. 46.2044° N`, `Image crop / exterior light`, `Webflow · CMS · Motion`.
- Keep them meaningful or atmospheric.

## Architectural annotation system

Add a subtle visual signature inspired by architecture drawings and editorial production notes.

Use:

- Thin rules.
- Section numbers.
- Crop labels.
- Image coordinates.
- Small metadata lines.
- Measurement-like marks.
- Quiet grid overlays.
- Caption systems.

Do not overuse them. One or two per section is enough. They should feel intelligent and designed, not decorative clutter.

Examples:

- `01 / First impression`
- `Frame 04 — Morning light`
- `Built for Webflow CMS`
- `Editorial rhythm · Lead clarity · Premium perception`
- `Suisse romande / immobilier premium`

## Image direction

Photography is central. The site should feel like it understands houses, materials, and atmosphere.

Prefer:

- Natural light.
- Architectural shadows.
- Warm stone, plaster, wood, glass, concrete, landscape.
- Unusual but elegant angles.
- Details of materials.
- Wide crops with silence.
- Editorial interiors and facades.
- Beautiful homes that feel lived-in or aspirational without looking fake.

Avoid:

- Generic stock luxury interiors.
- Over-saturated villas.
- Fake-looking renders.
- Smiling corporate people.
- Random image sizes.
- Crops that ignore architecture.

Image layout rules:

- Use mixed aspect ratios intentionally.
- Each crop should have a reason.
- Pair wide atmosphere images with narrow detail images.
- Use captions and metadata to create editorial credibility.
- On hover, reveal a detail, label, or gentle motion.

## Motion choreography

Motion should prove craft. It should not be a universal fade-up.

Use different motion roles:

- Hero headline: word or line reveal.
- Hero images: mask reveal and subtle parallax.
- Section labels: line draw.
- Editorial modules: staggered reveal with varied directions.
- Project panels: image scale, metadata reveal, line expansion.
- Buttons: refined lift, arrow motion, or fill inversion.
- Footer: quiet column reveal.

Motion should feel like a magazine opening, light moving across a wall, or a designer laying out a page.

Technical rules:

- Prefer transform and opacity.
- Use clip-path/mask carefully.
- Avoid heavy scroll-jacking.
- Avoid bouncy easing.
- Avoid excessive blur on mobile.
- Always support `prefers-reduced-motion`.

## Component system

### Navigation

Light, integrated, precise. It should sit in the composition rather than float as a generic navbar.

Rules:

- Brand visible but quiet.
- Links minimal.
- CTA restrained.
- Consider a thin line, transparent background, or editorial top bar.
- Mobile menu must be simple and polished.

### Buttons

Buttons should feel tactile and refined.

Primary:

- Charcoal fill or clay/sand accent.
- Light text.
- Slight lift on hover.
- Optional arrow movement.

Secondary:

- Text link or outlined pill.
- Underline/rule reveal.

Avoid large generic rounded SaaS buttons unless the composition specifically needs softness.

### Editorial modules

Replace uniform cards with varied modules:

- Large statement block.
- Narrow vertical text block.
- Image-backed module.
- Quiet technical module.
- Numbered observation block.
- Split caption/image block.

Modules can reuse tokens, but they should not all look identical.

### Services

Service presentation should feel confident and editorial, not like a menu of commodities.

Possible services:

- Sites Webflow premium.
- Refonte de présence digitale.
- Pages projet & propriétés.
- Direction visuelle & conversion.
- CMS immobilier éditorial.
- Motion & interactions.

Each service should connect design quality to commercial perception.

### Expertise section

Include a section called:

> Ce que je vois avant de designer.

This section proves senior taste and strategic perception.

Use four observations:

1. La hiérarchie perçue.
2. Le rythme de lecture.
3. La tension image / texte.
4. Le chemin vers le contact.

Each observation should explain what TimDesign notices before production starts. This section should make the expertise tangible.

### Showcase

Use cinematic project-style panels, not generic portfolio cards.

Project placeholders:

- Villa contemporaine.
- Promotion résidentielle.
- Maison de caractère.

Rules:

- Use different aspect ratios.
- Use captions and project metadata.
- Use hover interactions that reveal detail.
- Avoid equal cards unless intentionally offset by typography or spacing.

### Process

The process should be clear, but not visually boring.

Steps:

1. Clarifier.
2. Structurer.
3. Designer.
4. Construire.
5. Lancer.

Use section numbers, timeline lines, or editorial step rows. Keep copy concise.

### Contact

The contact section should feel like a quiet invitation, not a lead-gen trap.

Suggested headline:

> Votre prochain site devrait déjà faire sentir la qualité du lieu.

Use a minimal form with real labels:

- Nom.
- Email.
- Projet.
- Message.

Add a short note that TimDesign is best suited to premium real estate, architecture, and remarkable-property projects.

### Footer

The footer should feel like the final page of a monograph.

Use:

- Strong but calm structure.
- Deeper contrast if useful.
- Contact details.
- Location: Suisse romande.
- Offer reminder: Webflow premium for real estate and architecture.
- Simple navigation.

## Layout recipes

### Recipe A — Iconic hero

- 12-column grid.
- Headline spans 7-9 columns.
- Large image occupies right or background layer.
- Smaller image overlaps lower-right or mid-left.
- Metadata panel sits along a grid line.
- CTA below text but aligned to a rule.

### Recipe B — Editorial statement

- Left: section number + small label.
- Right: large serif statement.
- Below: two text columns with one pull quote.
- Add one thin horizontal rule.

### Recipe C — Expertise observations

- Four observations in an uneven grid.
- One observation larger than the others.
- Use numbers and short titles.
- Add a quiet architectural annotation.

### Recipe D — Cinematic showcase

- Mixed image ratios.
- One wide horizontal panel.
- Two smaller vertical/detail panels.
- Hover reveals metadata.
- Mobile becomes a strong vertical editorial sequence.

## Mobile rules

Mobile must not feel like a collapsed desktop.

Rules:

- Preserve a dramatic first impression.
- Keep large typography, but control line breaks.
- Use image rhythm instead of stacking everything equally.
- Keep CTAs visible and usable.
- Increase vertical spacing between conceptual sections.
- Remove excessive decorative annotations.
- Avoid cramped cards.
- Use fewer but stronger motion effects.
- Test at 360px width.

## Accessibility and performance

The expressive direction must remain usable.

Requirements:

- Maintain readable contrast on light backgrounds.
- Body text should generally be 16px or larger.
- Do not rely on color alone for states.
- Provide visible focus states.
- Use semantic HTML.
- Forms require labels.
- Images need meaningful alt text when content-relevant.
- Motion must respect `prefers-reduced-motion`.
- Avoid heavy JavaScript and scroll-jacking.
- Optimize images and avoid unnecessary 3D if it damages performance.

## Webflow implementation notes

Build for Webflow-friendly translation:

- Use reusable section components.
- Use clear class naming.
- Use CSS variables/tokens.
- Use combo classes for visual variants.
- Use CMS-ready structures for projects/showcases.
- Use `object-fit: cover` and controlled aspect ratios.
- Keep custom code isolated.
- Keep motion utilities reusable.

Suggested class naming:

- `.td-page`
- `.td-container`
- `.td-section`
- `.td-section.is-ivory`
- `.td-section.is-limestone`
- `.td-nav`
- `.td-hero`
- `.td-hero__headline`
- `.td-hero__media`
- `.td-annotation`
- `.td-eyebrow`
- `.td-heading-xl`
- `.td-copy`
- `.td-button`
- `.td-module`
- `.td-module.is-statement`
- `.td-module.is-image`
- `.td-observation`
- `.td-showcase`
- `.td-project-panel`
- `.td-process-step`
- `.td-form`
- `.td-footer`
- `.td-reveal`

## Lovable / AI agent instruction

When generating a homepage from this file, do not create a safe generic premium website. Create a distinctive artistic homepage that demonstrates TimDesign's creative expertise.

The output should be:

- Bright.
- Spacious.
- Architectural.
- Expressive.
- Editorial.
- Commercially clear.
- Mobile-polished.
- Webflow-transferable.
- More memorable than a standard template.

If the first result looks like it could belong to any design agency, revise toward stronger composition, bolder typography, more specific image direction, more varied modules, and more visible designer judgment.
