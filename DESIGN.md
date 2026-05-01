---
name: Lex Precedens
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#44474f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#445e92'
  primary: '#00204f'
  on-primary: '#ffffff'
  primary-container: '#1a3668'
  on-primary-container: '#87a0d9'
  inverse-primary: '#aec6ff'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#172333'
  on-tertiary: '#ffffff'
  tertiary-container: '#2d384a'
  on-tertiary-container: '#96a1b7'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#aec6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#2c4678'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#d8e3fa'
  tertiary-fixed-dim: '#bcc7dd'
  on-tertiary-fixed: '#111c2c'
  on-tertiary-fixed-variant: '#3c475a'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 32px
  section-padding: 120px
  element-gap: 24px
---

## Brand & Style

The design system is rooted in the concepts of **Heritage and Precision**. As a boutique Turkish law firm, the visual identity must balance the weight of legal tradition with a modern, agile service model. The aesthetic is strictly **Minimalist-Corporate**, utilizing vast whitespace to signal clarity of thought and institutional stability.

The emotional response is one of calm confidence. By avoiding aggressive marketing tactics and "loud" UI patterns, the system positions the firm as a trusted advisor rather than a service vendor. Every element is designed to feel permanent, deliberate, and authoritative, adhering to the dignified standards of professional legal associations.

## Colors

The palette is anchored by a **Deep Navy Blue** (extracted from the Tan Hukuk logo), representing intelligence and stability. This is complemented by **Charcoal** and **Slate Grey** to provide a neutral, formal structure. 

**Subtle Gold (Brass)** is used sparingly as an accent color. It is never used for large surfaces; instead, it appears in fine details like thin borders, icons, or specific text links to denote "boutique" quality and exclusivity. The background uses a slightly off-white "Paper" tint to reduce eye strain and feel more tactile than pure digital white.

## Typography

This design system employs a high-contrast typographic pairing. **Noto Serif** is used for all primary headlines to evoke the timelessness of legal documents and traditional publishing. 

For functional text and readability, **Manrope** provides a balanced, neutral sans-serif voice. Navigation and small metadata utilize **Work Sans** in uppercase tracking to create a sense of organized, professional labeling. Paragraph widths are strictly capped to ensure optimal line lengths for reading complex legal insights.

## Layout & Spacing

The layout follows a **Fixed Grid** model to maintain a disciplined, centered column of information. Generous vertical spacing is the hallmark of this system; sections are separated by significant "breathing room" (120px+) to prevent the interface from feeling cluttered or urgent.

A 12-column grid is used for desktop, but content often occupies only the center 8 columns to create wide margins that frame the text. This "editorial" approach focuses the user’s attention on the firm's expertise and narrative.

## Elevation & Depth

To maintain a formal and flat aesthetic, the design system avoids heavy drop shadows. Depth is achieved through **Tonal Layering** and **Low-Contrast Outlines**.

1.  **Surfaces:** Cards and containers use a subtle white surface against the light grey background, defined by a 1px border in Slate Grey (#E2E8F0).
2.  **Interaction:** On hover, elements may gain a very soft, high-diffusion "Ambient Shadow" (0% - 5% opacity) to indicate interactivity without breaking the minimalist plane.
3.  **Dividers:** Hairline strokes in Brass or Slate are used to separate content, mimicking the look of premium stationery.

## Shapes

The shape language is strictly **Sharp (0px)**. Rounded corners are associated with consumer apps and "friendliness"; a law firm requires the precision and rigidity of sharp geometry. Every button, input field, and image container features 90-degree angles to reinforce the firm's uncompromising attention to detail and structural integrity.

## Components

### Buttons
Buttons are understated and text-heavy. The primary button is a solid Navy block with white text. Secondary buttons are "Ghost" style—transparent with a 1px Slate border. "Call to action" language is replaced with "Inquiry" or "Professional Consult" to remain formal.

### Navigation
The navigation is a minimalist top bar. Links are set in `label-caps`. The "Active" state is indicated by a thin 1px Brass line underneath the text. No dropdowns are used unless absolutely necessary to keep the hierarchy flat.

### Input Fields
Inputs are simple bottom-border lines or fully outlined boxes with 0px radius. Labels sit above the field in `label-caps`. Focus states transition the border color from Slate to Navy.

### Cards
Cards for practice areas or lawyer profiles are background-less, separated only by generous white space or thin horizontal hairlines. They should feel like entries in a high-end directory.

### Legal Documentation
A specific "Document View" component is required, featuring indented lists, serif body text, and a distinct "Print" or "Download PDF" utility in the sidebar.