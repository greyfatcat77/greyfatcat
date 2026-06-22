# Greyfatcat Design System
Generated from Figma source CSS

## CSS Variables
```css
:root {
  /* Colors */
  --color-bg: #FFFFFF;
  --color-primary: #1D56CF;
  --color-text: #0D0D0D;
  --color-muted: #AEABA5;
  --color-black: #000000;
  --color-separator: #C2C2C2;

  /* Typography */
  --font-family: 'Inter', sans-serif;

  /* Font sizes */
  --font-size-hero: 40px;
  --font-size-body: 20px;
  --font-size-works-heading: 40px;
  --font-size-card-title: 24px;
  --font-size-card-meta: 12px;
  --font-size-nav: 14px;
  --font-size-logo: 18px;
  --font-size-footer: 12px;

  /* Line heights */
  --line-height-hero: 48px;
  --line-height-body: 32px;
  --line-height-card-title: 32px;
  --line-height-meta: 20px;
  --line-height-nav: 17px;

  /* Font weights */
  --font-weight-regular: 300;
  --font-weight-medium: 400;
  --font-weight-semibold: 500;

  /* Layout */
  --content-width: 900px;
  --page-width: 1440px;
  --nav-height: 60px;
  --footer-height: 72px;
  --nav-padding: 0px 120px;
  --content-padding: 72px 0px;
  --content-top: 60px;

  /* Spacing */
  --gap-section: 60px;
  --gap-about: 32px;
  --gap-card-internal: 32px;
  --gap-tag: 8px;
  --gap-icon-set: 24px;
  --gap-nav-links: 16px;

  /* Card */
  --card-image-width: 434px;
  --card-image-height: 272px;
  --card-total-width: 900px;

  /* Separator */
  --separator: 1px solid #C2C2C2;

  /* Logo */
  --logo-letter-spacing: 0.2em;
  --logo-text-transform: uppercase;
}
```

## Layout rules
- Page max width: 1440px
- Content max width: 900px, centered with `left: calc(50% - 900px/2)`
- Nav is sticky, full width, height 60px, background white
- Nav padding: 0px 120px outer, 0px 60px inner
- Content starts at top: 60px (below nav)
- Footer is absolute, bottom: 0, height 72px

## Navigation
- Logo: "JESSICA K", Inter, 500 weight, 18px, letter-spacing 0.2em, uppercase, color #1D56CF
- Nav links: "works", "about", "linkedin", Inter, 400 weight, 14px, color #0D0D0D
- Nav bottom border: 1px solid #C2C2C2

## Hero section
- Heading: Inter, 300 weight, 40px, line-height 48px, color #0D0D0D
- "thoughtful products" and "solutions" colored #1D56CF, 400 weight
- Body text: Inter, 300 weight, 20px, line-height 32px, color #0D0D0D
- Max width: 668px

## Works section
- "works." heading: Inter, 400 weight, 40px, color #1D56CF
- Section gap: 60px
- Separator between cards: 1px solid #C2C2C2

## Project cards
- Layout: row, gap 32px between image and details
- Image: 434px × 272px
- Year: Inter, 400 weight, 12px, color #000000
- Title: Inter, 400 weight, 24px, line-height 32px, color #0D0D0D
- Client: Inter, 400 weight, 12px, color #000000
- Tags: Inter, 400 weight, 12px, color #1D56CF, separated by " • "

## Footer
- Height: 72px, background white
- Left: arrow icon + "linkedin" link
- Right: "© 2026 Jessica Kr", Inter, 400 weight, 12px, color #AEABA5
