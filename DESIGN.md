---
name: "Tumu Coffee Trading — Brand baseline"
description: "Design tokens extracted from https://zorah11.github.io/gekamu-coffee-mixed-farm (Dembrandt extraction, 2026-09-19). This is the design system the Tumu Coffee Trading website is built against."
colors:
  primary: "#2C211B"
  secondary: "#426442"
  surface: "#BCC5A8"
  on-surface: "#2C211B"
  background: "#F3ECDC"
  paper: "#FAF6EC"
  tan: "#D8C7AB"
  clay: "#67584E"
typography:
  display:
    fontFamily: "Newsreader"
    fontSize: "clamp(4.4rem, 10vw, 10rem)"
    fontWeight: 400
    lineHeight: 0.75
    letterSpacing: "-0.065em"
  heading-2:
    fontFamily: "Newsreader"
    fontSize: "clamp(2.7rem, 5.5vw, 5.8rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.045em"
  heading-3:
    fontFamily: "Newsreader"
    fontSize: "1.65rem"
    fontWeight: 400
  body:
    fontFamily: "DM Sans"
    fontSize: "16px"
    fontWeight: 400
  text-serif:
    fontFamily: "Newsreader"
    fontSize: "clamp(1.05rem, 1.5vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.55
  caption:
    fontFamily: "DM Sans"
    fontSize: "0.62–0.68rem"
    fontWeight: 600
    letterSpacing: "0.13–0.16em"
    transform: "uppercase"
spacing:
  base: "4px"
  sm: "8px"
  md: "12.8px"
  lg: "16px"
  xl: "24px"
  xxl: "32px"
  xxxl: "48px"
  xxxxl: "64px"
  section: "clamp(5rem, 10vw, 10rem)"
rounded:
  arch: "50% 50% 0 0"
  leaf: "100% 0 100% 0"
  circle: "50%"
components:
  button-observed:
    backgroundColor: "{colors.primary}"
    textColor: "#FFFFFF"
    rounded: "0px"
    padding: "12px"
---

# Design System — Tumu Coffee Trading

## Overview
The Tumu Coffee Trading site is built on a brand baseline extracted from the Gekamu Coffee And Mixed Farm concept site with Dembrandt (extraction date 2026-09-19). The YAML front matter contains machine-readable values observed by Dembrandt when available; the sections below summarize the extracted evidence. The new site extends this system with photography (arch-shaped `50% 50% 0 0` masks, circular product thumbs) while keeping every core token.

## Colors
- **Primary / Espresso** (#2C211B): text, wordmark, dark "products" section background, skip-link button
- **Background / Cream** (#F3ECDC): page background
- **Secondary / Leaf** (#426442): kickers, `em` accents in display headings, leaf glyph, focus outline
- **Surface / Sage** (#BCC5A8): captions and lot labels on dark sections
- **Paper** (#FAF6EC): sourcing section background
- **Tan** (#D8C7AB): contact section background
- **Clay** (#67584E): muted body copy on light sections, hairline borders on dark sections
- Hairline borders: `1px solid rgba(44, 33, 27, .35)` on light surfaces, `1px solid #67584E` on dark surfaces

## Typography
- **Display**: Newsreader, clamp(4.4rem, 10vw, 10rem), line-height 0.75, letter-spacing −0.065em; emphasized word in Leaf green
- **Heading 2**: Newsreader, clamp(2.7rem, 5.5vw, 5.8rem), line-height 0.98, letter-spacing −0.045em
- **Heading 3**: Newsreader, 1.65rem, regular
- **Body**: DM Sans, 16px, regular (line-height ~1.55–1.7)
- **Serif copy**: Newsreader, clamp(1.05rem, 1.5vw, 1.3rem), line-height 1.55 (hero note)
- **Caption / kicker**: DM Sans, 0.62–0.68rem, weight 600, uppercase, letter-spacing 0.13–0.16em
- **Font source**: Google Fonts (DM Sans, Newsreader)
- **Font URL**: https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600&family=Newsreader:opsz,wght@6..72,400;6..72,500&display=swap

## Layout
Observed spacing scale: 4px base.
- **Spacing tokens**: 8, 12.8, 16, 24, 32, 48, 64px; section padding clamp(5rem, 10vw, 10rem)
- **Responsive breakpoint**: 760px (mobile menu becomes a toggle panel, grids collapse to one column)
- Container gutters: clamp(1.25rem, 6vw, 6rem)

## Shapes
- **Arch image mask**: 50% 50% 0 0 (top-rounded photo panels)
- **Circular thumbs**: 50% (product lot images)
- **Leaf glyph**: 100% 0 100% 0 radius, rotated −25°, leaf green (wordmark accent)
- Buttons and cards: 0 radius (sharp corners)

## Components
- **Buttons**: radius 0px, background #2C211B, text #FFFFFF, padding 12px (skip-link)
- **Arrow links**: flex space-between, 1px bottom border, 0.9rem sans; contact variant scaled to clamp(1rem, 2vw, 1.4rem)
- **Nav links**: 0.78rem sans; contact link boxed with 1px border
- **Article rows**: 1px top/bottom hairlines; uppercase DM Sans span + Newsreader 1.65rem h3 + muted body copy
- **Footer**: 3-column grid, 0.62rem uppercase, letter-spacing 0.12em, credits row beneath

## Photography
- 11 images sourced from Wikimedia Commons (CC BY / CC BY-SA / CC0 / public domain), credited in the footer
- Sizes: hero 1000px, wide band 1600px, arch trio 900px, product thumbs 520px square, process band 1000px

<!-- dembrandt v0.34.2 -->
