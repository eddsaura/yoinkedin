# Frontend Skill - Old Corporate Aesthetic

You are creating old corporate-style user interfaces that evoke the aesthetic of enterprise software from the 1990s and early 2000s. Avoid generic modern "AI slop" aesthetics and instead embrace the distinctive, nostalgic character of vintage business applications.

## Core Principles

Focus on:

- **Typography**: Choose fonts that evoke corporate nostalgia. Embrace classic choices like:
  - Serif fonts: Georgia, Times New Roman, Palatino, Baskerville
  - Monospace: Courier New, IBM Plex Mono, Consolas
  - Classic sans-serif: Verdana, Tahoma, MS Sans Serif
  - Avoid modern fonts like Inter, Roboto, or contemporary geometric sans-serifs

- **Color & Theme**: Commit to muted, professional corporate palettes:
  - Classic grays, blues, and greens reminiscent of IBM, Microsoft, Oracle
  - Windows 95/98/2000 inspired colors (teal, navy, gray)
  - Subtle gradients mimicking old Windows chrome/silver interfaces
  - Beige/tan backgrounds evoking aging CRT monitors
  - Use CSS variables for consistency
  - Draw inspiration from: Windows 2000, Office 97, Lotus Notes, early SAP/Oracle interfaces

- **Motion**: Subtle, professional animations:
  - Simple fade-ins and slide transitions
  - Avoid bouncy, playful easing functions
  - Use linear or ease-in-out timing for corporate professionalism
  - Loading bars that feel deliberate and measured
  - CSS-only solutions preferred; Motion library for React when needed

- **Backgrounds**: Create depth with corporate textures:
  - Subtle noise/grain textures mimicking CRT displays
  - Soft linear gradients (gray to silver, subtle blues)
  - Geometric patterns like subtle grids or dot matrices
  - "Brushed metal" or "chrome" effects
  - Avoid solid flat colors; add subtle texture

- **Layout & Components**:
  - Boxy, grid-based layouts with clear hierarchy
  - Generous borders (1-2px solid borders on containers)
  - Inset/outset borders for 3D button effects
  - Table-heavy designs for data presentation
  - Tabbed interfaces with clear visual tabs
  - Status bars at bottom of windows
  - Skeuomorphic elements (beveled buttons, recessed inputs)

## Avoid Generic Modern Aesthetics

DO NOT use:
- Modern sans-serif fonts (Inter, Space Grotesk, Poppins, Montserrat)
- Trendy color schemes (purple gradients, neon accents, pastel palettes)
- Rounded corners everywhere (prefer sharp corners or subtle rounding)
- Glassmorphism, neumorphism, or other modern design trends
- Oversized typography and excessive whitespace
- Minimal flat design without texture or depth

## Examples of Old Corporate Style

Draw inspiration from:
- Windows 95/98/2000/XP interfaces
- Microsoft Office 97-2003
- Lotus Notes, IBM products
- Early web portals (Yahoo, MSN, corporate intranets)
- Enterprise software: SAP, Oracle, PeopleSoft
- CRT monitor color limitations
- Intranet dashboards from the early 2000s

## Implementation Details

- Use semantic HTML with clear structure
- Implement tables for tabular data (embrace the table!)
- Create chrome/beveled effects with CSS gradients and box-shadows
- Add subtle scan lines or noise overlays for CRT effect
- Include functional but retro UI elements: dropdown menus, status bars, toolbars
- Make it look like serious business software, not a toy

Remember: The goal is to create interfaces that feel purposefully nostalgic and distinctive, not accidentally dated. Celebrate the corporate aesthetic with intention and creativity.
