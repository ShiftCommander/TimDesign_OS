---
name: TimDesign Light Architectural Creative System
version: 2.1
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
    sand: '#B99468'
    clay: '#C58E73'
    brass: '#C2A36D'
    olive_shadow: '#777866'
  line:
    subtle: 'rgba(23, 21, 18, .10)'
    visible: 'rgba(23, 21, 18, .18)'
    accent: 'rgba(185, 148, 104, .42)'
  shadow:
    blue_grey_soft: 'rgba(55, 68, 78, .10)'
    warm_depth: 'rgba(91, 72, 52, .12)'

typography:
  display:
    role: large editorial serif for iconic headlines
    family: 'RCL Prime Serif, Abigail, Cormorant Garamond, Georgia, serif'
    weight: '300-800 depending on contrast'
    letter_spacing: '-0.055em to -0.025em'
    line_height: '0.88-1.04'
  body:
    role: precise Swiss grotesk / clean system sans for clarity
    family: 'IF Bosch, Helvetica Neue, Inter, Arial, sans-serif'
    weight: '400-500'
    letter_spacing: '-0.01em to 0.01em'
    line_height: '1.55-1.85'
  micro:
    role: architectural labels, coordinates, section numbers, metadata
    family: 'IF Bosch, Helvetica Neue, Inter, Arial, sans-serif'
    weight: '500-650'
    letter_spacing: '0.10em-0.18em'
    text_transform: uppercase

spacing:
  base: 8
  section_desktop: '112px-184px'
  section_mobile: '72px-112px'
  page_margin_desktop: 'clamp(32px, 5vw, 88px)'
  page_margin_mobile: '20px-28px'
  grid_gap: '24px-80px'
  hero_min_height: '92svh-100svh'

layout:
  max_width: '1680px'
  grid: '12-column editorial grid on desktop, 4-column logic on tablet, single-column but art-directed rhythm on mobile'
  composition: 'asymmetric, image-led, precise, with intentional negative space'
  alignment_rule: 'every unusual layout choice must still align to an invisible grid'

motion:
  easing:
    editorial: 'cubic-bezier(.19, 1, .22, 1)'
    snap: 'cubic-bezier(.16, 1, .3, 1)'
    soft: 'cubic-bezier(.4, 0, .2, 1)'
  duration:
    fast: '160ms'
    medium: '420ms'
    slow: '900ms'
    cinematic: '1200ms-1800ms'
  roles:
    hero_word_reveal: 'staggered word or line reveal, light blur, upward rotation, no cheap fade-only entrance'
    image_mask_reveal: 'clip-path or scale/mask reveal for architectural images'
    line_draw: 'thin rules draw horizontally/vertically for labels and section transitions'
    parallax_depth: 'very subtle layered image movement, 2-6%, never distracting'
    card_stagger: 'service/project modules enter with alternating x/y motion'
    hover_refinement: 'line expansion, metadata reveal, slight image scale, controlled shadow change'
  reduced_motion: 'provide still, elegant equivalents for all animation systems'

radius:
  small: 4
  medium: 8
  large: 16
  principle: 'use radius sparingly; architectural imagery can remain sharp or nearly sharp'
---

# TimDesign Light Architectural Creative System

This file is the canonical design reference for a bright, expressive TimDesign direction. It replaces generic light minimalism with a stronger creative identity: architectural, editorial, image-led, precise, and memorable.

It should guide AI agents, Lovable, Codex, Webflow builds, prototype generation, and future homepage explorations.

## 1. Core creative thesis

TimDesign should not feel like a polite premium landing page. It should feel like a designer with taste, rhythm, and an architectural eye shaped the experience.

The visual language is bright and airy, but never bland. It should sit somewhere between:

- an architecture magazine spread;
- a property monograph;
- a Swiss editorial portfolio;
- a refined Webflow studio homepage;
- a cinematic visit through a remarkable place.

The homepage must communicate commercial clarity while also proving creative expertise through layout, rhythm, typography, image treatment, and interaction detail.

## 2. What the design must make people feel

A visitor should think:

> This person is not just building websites. He sees proportion, atmosphere, hierarchy, and perception.

The experience should feel:

- bright;
- spacious;
- crafted;
- artistic;
- precise;
- architectural;
- calm but distinctive;
- premium without dark luxury clichés;
- expressive without becoming decorative noise.

## 3. Anti-template rules

Avoid safe default homepage patterns when they create a generic result.

Do not use a conventional hero with a left text block, right image block, four cards, three projects, and a normal footer unless the composition is heavily art-directed.

Prefer:

- asymmetric editorial compositions;
- large typographic scale shifts;
- layered images;
- sectional numbering;
- quiet architectural annotation details;
- strong image cropping;
- tension between empty space and visual density;
- components that vary by role instead of repeating identical cards.

A page can be minimal and still have personality. The personality comes from proportion, composition, motion, detail, and restraint.

## 4. Visual signature system

Use small, refined markers inspired by architecture, publishing, and design documentation.

Allowed signature details:

- section numbers: 01, 02, 03;
- coordinate-style metadata: Suisse romande · Webflow · Immobilier premium;
- crop labels near images;
- thin vertical or horizontal rules;
- measurement-like captions;
- image index labels;
- quiet grid overlays in selected hero/transition moments;
- small diamond or square marks used sparingly;
- caption systems that feel like editorial notes.

These details must feel useful and composed, not decorative clutter.

## 5. Color direction

Use warm light, material-inspired colors. The page should feel like natural light on plaster, stone, paper, and linen.

Main palette:

- warm ivory background;
- paper white surfaces;
- pale limestone sections;
- plaster grey/beige secondary blocks;
- charcoal text;
- muted graphite secondary text;
- sand, clay, or brass accents;
- subtle blue-grey or warm shadows.

Avoid sterile pure white with neutral grey as the dominant mood. Avoid black/gold luxury clichés except for tiny contrast accents when justified.

## 6. Typography direction

Typography is one of the main identity drivers.

Display typography:

- very large editorial serif headlines;
- strong line breaks;
- expressive contrast between words;
- occasional italic or lighter-weight word as a signature gesture;
- tight tracking but readable rhythm;
- headlines should feel composed, not merely typed.

Body typography:

- clean Swiss grotesk/system sans;
- generous line-height;
- calm and readable;
- short paragraphs with strong editorial pacing.

Micro typography:

- uppercase labels;
- refined tracking;
- small metadata blocks;
- consistent section labels;
- used as a quiet architectural layer.

## 7. Hero rules

The hero is the most important identity proof. It must be iconic.

A strong TimDesign hero should include:

- a large fragmented editorial headline;
- intentional line breaks;
- one visual surprise or composition tension;
- one large architectural crop;
- one secondary image/detail or offset panel;
- a small metadata module;
- clear CTAs;
- a feeling of light, proportion, and creative direction.

Recommended hero headline:

> Des sites lumineux pour des lieux qui ne devraient jamais paraître ordinaires.

Recommended supporting copy:

> TimDesign conçoit des expériences Webflow premium pour l’immobilier haut de gamme, l’architecture et les propriétés remarquables en Suisse romande.

Hero composition patterns:

- oversized text crossing image boundaries;
- vertical metadata rail on one side;
- image stack with a main crop and detail crop;
- partial grid lines that frame the visual field;
- asymmetrical negative space;
- CTA block treated like editorial caption, not SaaS button group.

## 8. Page narrative

The homepage should read like a designed visit, not a list of sections.

Suggested flow:

1. Iconic hero: establishes taste and positioning.
2. Editorial statement: explains perception, trust, rhythm, and desire.
3. Expert eye section: shows how Tim thinks before designing.
4. Services as editorial modules: clear offer without generic cards.
5. Showcase: image-led, cinematic, architectural project previews.
6. Process: precise, calm, high-trust structure.
7. Final CTA: poetic but concrete invitation.
8. Footer: calm, structured, memorable.

Each section should visually answer a question:

- Why does this feel premium?
- What does Tim see that others miss?
- How does the process reduce risk?
- Why should a premium real estate actor trust him?

## 9. Expert eye module

Include a signature section called:

> Ce que je vois avant de designer.

This section demonstrates design expertise rather than listing services.

Use four observations:

### La hiérarchie perçue
What the visitor understands first, second, and third.

### Le rythme de lecture
How text, images, spacing, and pauses create progression.

### La tension image / texte
How photography and copy should support each other instead of competing.

### Le chemin vers le contact
How the page creates clarity, desire, trust, and action before the form.

This section should feel like opening the designer’s eye to the visitor.

## 10. Services as editorial modules

Avoid uniform SaaS cards. Services should be modular, varied, and editorial.

Use a mix of:

- one large statement block;
- one narrow vertical text module;
- one image-backed module;
- one technical clarity module;
- one short checklist or observation block.

Possible service labels:

- Sites Webflow premium;
- Refonte de présence digitale;
- Pages projet et propriétés;
- Direction visuelle et conversion;
- Systèmes CMS simples à gérer.

The tone should be calm, concrete, and premium. No inflated agency jargon.

## 11. Showcase direction

Project previews should feel cinematic and architectural.

Use varied aspect ratios:

- one large landscape image;
- one tall vertical image;
- one compact detail crop;
- optional text rail or caption block.

Project-style labels:

- Villa contemporaine;
- Promotion résidentielle;
- Maison de caractère;
- Résidence privée;
- Architecture intérieure.

Interactions:

- slight image scale;
- metadata reveal;
- thin line movement;
- caption shift;
- cursor/hover detail only if subtle.

The showcase should not feel like a stock portfolio grid.

## 12. Motion choreography

Avoid one repeated fade-up animation everywhere. Motion must have roles.

Use different motion patterns:

- hero headline word reveal;
- image mask reveal;
- line draw for section labels;
- alternating card stagger;
- subtle parallax on image layers;
- hover line expansion;
- metadata reveal;
- footer column reveal.

Motion should feel like editorial choreography, not a plugin preset.

Reduced motion must keep all content visible and elegant.

## 13. Photography and image art direction

Images should do more than fill rectangles.

Preferred imagery:

- unusual architectural angles;
- material details;
- shadows from windows;
- staircases, facades, terraces, stone, wood, glass;
- beautiful houses without cliché real estate smiles;
- calm luxury interiors;
- Swiss or European architectural mood;
- natural light, not overproduced stock glow.

Cropping rules:

- crop intentionally;
- allow partial views;
- use negative space;
- mix wide and vertical ratios;
- captions should make images feel curated.

Avoid generic business people, cliché keys, handshake photos, fake luxury interiors, and bland stock villas.

## 14. 3D and immersive guidance

3D is optional, not mandatory. Use it only if it adds architectural value.

Good uses:

- subtle rotating plan fragment;
- abstract architectural wireframe;
- soft spatial depth layer;
- cursor-reactive model detail;
- 360/VR concept placeholder for property experiences.

Bad uses:

- decorative 3D blobs;
- heavy gaming-style scenes;
- gimmicky rotating houses;
- performance-heavy animations that hurt mobile.

If used, 3D should feel like an architectural study, not a tech demo.

## 15. Interaction details

Micro-interactions should communicate care.

Buttons:

- subtle line sweep;
- small text shift;
- understated background change;
- refined focus state;
- no loud bounces.

Links:

- line draw from left or right;
- metadata movement;
- visible focus state.

Cards/modules:

- image scale 1.02-1.06;
- metadata reveal;
- slight border/accent shift;
- controlled shadow or elevation;
- never over-animated.

Forms:

- calm labels;
- clear focus states;
- generous spacing;
- premium but frictionless.

## 16. Mobile rules

Mobile must feel designed, not collapsed.

Mobile priorities:

- preserve dramatic typography;
- keep image rhythm;
- use strong vertical spacing;
- avoid cramped card stacks;
- keep metadata and section numbers readable;
- use fewer but stronger visual gestures;
- maintain CTA clarity;
- make the first screen memorable.

Mobile compositions can stack, but should still feel editorial.

## 17. Accessibility and performance

The design may be expressive, but it must remain commercially usable.

Requirements:

- semantic HTML;
- accessible labels;
- visible focus states;
- readable contrast;
- sensible heading hierarchy;
- reduced motion support;
- optimized images;
- no inaccessible text-over-image combinations;
- no animation required to understand content.

## 18. Webflow implementation guidance

Design must remain Webflow-friendly.

Use reusable class logic:

- section;
- container;
- grid;
- editorial-heading;
- micro-label;
- image-frame;
- image-caption;
- service-module;
- project-panel;
- motion-mask;
- line-draw;
- cta-row;
- form-field.

Avoid fragile one-off hacks unless they create a signature hero moment and can be isolated.

## 19. AI generation instructions

When an AI agent uses this file, it should not produce a generic minimal website.

The agent must:

1. create a strong hero composition;
2. use expressive editorial typography;
3. vary section layouts;
4. add architectural annotation details;
5. use image-led storytelling;
6. include a designer expertise section;
7. choreograph motion by role;
8. preserve mobile quality;
9. keep commercial clarity;
10. make the site memorable.

A successful output should feel like a TimDesign creative direction, not a clean template.

## 20. Lovable homepage prompt seed

Use this seed when generating or refactoring a homepage:

Create a bright, expressive, architectural homepage for TimDesign. It must feel like a refined architecture magazine, an art-directed property monograph, and a senior web designer portfolio. Keep it spacious, minimal, premium, and commercially clear, but make it visually distinctive through bold editorial typography, asymmetrical layouts, layered architectural imagery, quiet annotation details, cinematic project previews, and motion choreography. The result should prove that TimDesign has a real creative eye for high-end real estate and remarkable places in French-speaking Switzerland.
