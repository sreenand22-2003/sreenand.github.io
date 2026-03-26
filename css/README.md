# 🎨 css/ — Stylesheets README

## Files

### main.css
Core styles for every component:
- CSS variables (colors, fonts, spacing)
- Navbar, hero, about, projects, skills, blog, contact, footer
- Button styles, card styles, timeline, terminal window

**To change theme colors**, edit the `:root` block at the top:
```css
:root {
  --cyan: #00f5ff;       /* Change to any hex for a new accent */
  --purple: #a855f7;
  --bg-primary: #030712; /* Change for a different dark shade */
}
```

### animations.css
All keyframe animations and transition effects:
- Glitch effect on hero name hover
- Float animation on profile picture
- Neon flicker, ring pulse, scan line
- Card entrance animations, glow effects

**To disable a specific animation**, comment out or delete its `@keyframes` block.

### responsive.css
Breakpoint-specific overrides:
- `max-width: 1024px` — Tablet
- `max-width: 768px` — Mobile landscape / small tablet
- `max-width: 480px` — Mobile portrait
- `min-width: 1600px` — Ultra-wide
- Print styles
- Reduced motion (accessibility)

**To change a layout for mobile**, edit the relevant `@media` block.
