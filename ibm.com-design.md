---
version: alpha
name: IBM Light Editorial
description: A clean enterprise system with restrained blue accents, open spacing, and pragmatic card-based hierarchy.
colors:
  primary: "#0062FE"
  secondary: "#161616"
  tertiary: "#C6C6C6"
  neutral: "#FFFFFF"
  surface: "#FFFFFF"
  on-surface: "#161616"
  error: "#DA1E28"
  border: "#C6C6C6"
  muted: "#8D8D8D"
  link: "#0F62FE"
typography:
  headline-display:
    fontFamily: "IBM Plex Sans"
    fontSize: "40px"
    fontWeight: 300
    lineHeight: "49.1241px"
    letterSpacing: "0px"
  headline-lg:
    fontFamily: "IBM Plex Sans"
    fontSize: "34px"
    fontWeight: 300
    lineHeight: "49.1241px"
    letterSpacing: "0px"
  headline-md:
    fontFamily: "IBM Plex Sans"
    fontSize: "28px"
    fontWeight: 300
    lineHeight: "39.2403px"
    letterSpacing: "0px"
  headline-sm:
    fontFamily: "IBM Plex Sans"
    fontSize: "24px"
    fontWeight: 300
    lineHeight: "29px"
    letterSpacing: "0px"
  body-lg:
    fontFamily: "IBM Plex Sans"
    fontSize: "20px"
    fontWeight: 300
    lineHeight: "28px"
    letterSpacing: "0px"
  body-md:
    fontFamily: "IBM Plex Sans"
    fontSize: "16px"
    fontWeight: 300
    lineHeight: "24px"
    letterSpacing: "0px"
  body-sm:
    fontFamily: "IBM Plex Sans"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "20px"
    letterSpacing: "0px"
  label-lg:
    fontFamily: "IBM Plex Sans"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: "24px"
    letterSpacing: "0px"
  label-md:
    fontFamily: "IBM Plex Sans"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "20px"
    letterSpacing: "0px"
  label-sm:
    fontFamily: "IBM Plex Sans"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: "16px"
    letterSpacing: "0px"
  navigation:
    fontFamily: "IBM Plex Sans"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: "20px"
    letterSpacing: "0px"
  caption:
    fontFamily: "IBM Plex Sans"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: "16px"
    letterSpacing: "0px"
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 16px
  xl: 24px
  full: 9999px
spacing:
  xs: 2px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 48px
  gutter: 24px
  margin: 140px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.neutral}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: "14px 16px"
    height: "40px"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.on-surface}"
    typography: "{typography.label-md}"
    rounded: "{rounded.sm}"
    padding: "14px 16px"
    height: "40px"
  button-tertiary:
    backgroundColor: "transparent"
    textColor: "{colors.link}"
    typography: "{typography.label-md}"
    rounded: "{rounded.none}"
    padding: "0px"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: "16px"
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: "12px 16px"
  chip:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.full}"
    padding: "4px 12px"
---

# IBM Light Editorial

## Overview
This interface feels professional, restrained, and highly legible, with a calm enterprise tone rather than a playful one. The layout is spacious and editorial, using a strong hero area, compact navigation, and a right-rail news column to balance depth with clarity. Blue accents provide energy and interactivity without overpowering the neutral base.

## Colors
- **Primary (#0062FE):** A vivid IBM blue used for key actions, active states, and prominent links. It supplies the brand’s strongest sense of interaction and confidence.
- **Secondary (#161616):** A near-black ink used for body copy, navigation, and structural text. It anchors the page with strong readability and an authoritative tone.
- **Tertiary (#C6C6C6):** A cool neutral gray used for borders, subtle button treatments, and card outlines. It separates content without adding visual noise.
- **Neutral / Surface (#FFFFFF):** Pure white background and card surfaces keep the experience bright, open, and uncluttered. This supports the site’s editorial spacing and content-heavy structure.
- **On-surface (#161616):** The main text color on white surfaces, ensuring high contrast and a measured enterprise feel.
- **Link (#0F62FE):** A slightly deeper link blue used for text links and tertiary actions, reinforcing recognizability as interactive content.
- **Muted (#8D8D8D):** A subdued gray for secondary metadata and supporting UI text. It helps hierarchy remain clear without introducing additional color complexity.
- **Error (#DA1E28):** A cautionary red reserved for alerts or destructive states, even though it is not prominent in the screenshot.

## Typography
IBM Plex Sans is the defining type family: modern, technical, and highly readable. Headings use a very light 300 weight, which gives the interface a refined editorial presence while still feeling distinctly corporate and precise.

The hierarchy is built from size rather than heavy weight. `headline-display`, `headline-lg`, and `headline-md` create the hero and section structure, while `body-lg` and `body-md` handle supporting copy with generous line height. `body-sm`, `label-md`, and `label-sm` support navigation, metadata, and utility text.

Letter spacing is visually neutral and stays at 0px, with no strong uppercase treatment visible in the source. This keeps the tone straightforward and avoids decorative emphasis.

## Layout
The layout uses a wide, fixed-max-width editorial grid with substantial outer margins, leaving large areas of white space around the central content. The hero is asymmetrical: text on the left, a large media panel in the center, and a narrow news rail on the right.

Spacing follows a clean enterprise rhythm based on small increments for internal gaps and larger jumps between sections. Use 2px for micro-adjustments, 12px for compact text grouping, 16px for card padding and common control spacing, 24px for standard separation, and 48px or more for section breaks. The page feels spacious overall, with a large `margin` token of 140px defining the broad content framing.

## Elevation & Depth
The system is mostly flat, relying on contrast, borders, and whitespace instead of heavy shadows. Cards and modules use 1px gray borders to define boundaries, while the hero media introduces depth through dark tonal imagery and internal glow effects.

Because the surface language is restrained, elevation should be subtle and functional. Avoid large shadow stacks; use borders and tonal contrast to separate regions. The UI reads as layered through composition rather than through pronounced z-depth.

## Shapes
The shape language is modest and architectural. Corners are softly rounded at 4px on buttons and cards, which keeps the system approachable without becoming pill-shaped or playful.

Use `rounded.sm` for most interactive elements and content containers. Reserve `rounded.full` only for chips or status pills when needed. Overall, the geometry should feel crisp, linear, and enterprise-oriented.

## Components
Buttons are the clearest interactive pattern. `button-primary` is a filled blue action with white text, compact 40px height, and 14px/16px internal rhythm; it should be used for the main call to action. `button-secondary` is a transparent button with a dark border and dark text, suitable for secondary actions that still need clear affordance. `button-tertiary` is link-like, borderless, and best for lightweight navigation or inline actions.

Buttons in this system should remain rectangular with 4px corners and moderate padding. Their visual distinction comes from fill, border, and color rather than from size or shape changes.

Cards are simple white containers with 1px borders and minimal decoration. Use `card` for product teasers, recommendation modules, and content previews. Keep padding restrained so cards feel compact and content-led, not promotional.

Inputs should follow the same light-bordered, white-surface treatment as cards. They should be calm and legible, with no strong shadow and only a small radius. Focus states should rely on the primary blue rather than on elaborate outlines.

Chips should be subtle capsules with a full radius and minimal color separation. They are best for filters, status labels, or small contextual tags.

Navigation links and utility actions should remain lightweight and typographic. The primary visual language is text-first, with interaction indicated by blue color and simple arrow or icon treatment rather than by heavy button chrome.

## Do's and Don'ts
- Do keep the page bright, airy, and content-driven with strong whitespace.
- Do use IBM Plex Sans across headings, body, and navigation for a unified brand voice.
- Do reserve the blue accent for primary actions, links, and active states.
- Do prefer borders and tonal contrast over deep shadows for separation.
- Don't introduce playful, rounded, or highly saturated UI treatments.
- Don't use large corner radii on standard cards or buttons.
- Don't overuse gray fills when a white surface and border will preserve clarity.
- Don't make typography heavy; the system depends on light, elegant weights and clear spacing.