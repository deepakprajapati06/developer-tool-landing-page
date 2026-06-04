# Developer Tool Landing Page
> A pixel-accurate recreation of the [Cursor](https://cursor.com) website built with pure HTML and CSS.

🌐 **Live Site:** https://developer-tool-landing-page-19ccwl885.vercel.app/

---

## Sections Recreated

| # | Section | Description |
|---|---------|-------------|
| 1 | **Navigation Bar** | Sticky navbar with logo, nav links, Sign In and Download CTA |
| 2 | **Hero Section** | Large headline, description, CTA buttons, and a fully coded fake editor screenshot with syntax highlighting and AI chat panel |
| 3 | **Trusted By / Logos** | Row of company logos (OpenAI, Stripe, Shopify, Samsung, Slack, Replicate, Perplexity) |
| 4 | **Feature Sections (3 blocks)** | Two-column layout alternating text and image — Autocomplete, Chat, and Composer features |
| 5 | **Feature Cards** | 6-card grid covering Tab Autocomplete, AI Chat, Inline Edit, Codebase Search, Git Integration, Privacy Mode |
| 6 | **Testimonials** | 6 quote cards with star ratings, developer names, and roles |
| 7 | **Use Cases / Stories** | 3 cards for Startups, Enterprise, and Open Source with gradient images |
| 8 | **Changelog / Updates** | Dated list of 4 version updates with tags and descriptions |
| 9 | **Team / About** | Avatar grid + description + Join Us CTA |
| 10 | **Final CTA** | Large gradient heading with Download button and glow effect |
| 11 | **Footer** | 5-column layout with brand info, social links, and legal links |

---

## Fonts Used

| Font | Usage | Weight |
|------|-------|--------|
| **Inter** | All body text, headings, UI elements | 300, 400, 500, 600, 700, 800, 900 |
| **JetBrains Mono** (fallback: Fira Code, Cascadia Code) | Code blocks, syntax highlighting, file names | 400 |

Loaded via Google Fonts:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
```

---

## Colors Used

### Background Colors
| Variable | Hex | Usage |
|----------|-----|-------|
| `--bg` | `#0a0a0a` | Main page background |
| `--bg-card` | `#111111` | Card backgrounds |
| `--bg-card-2` | `#161616` | Nested card backgrounds |
| Editor bg | `#0d1117` | Code editor / screenshot areas |
| Editor topbar | `#161b22` | Editor tab bars |

### Text Colors
| Variable | Hex | Usage |
|----------|-----|-------|
| `--text` | `#ffffff` | Primary text |
| `--text-muted` | `#888888` | Secondary/description text |
| `--text-sub` | `#555555` | Tertiary/placeholder text |

### Border Colors
| Variable | Hex | Usage |
|----------|-----|-------|
| `--border` | `#1e1e1e` | Section borders |
| `--border-2` | `#2a2a2a` | Card borders, hover states |

### Accent Colors
| Color | Hex | Usage |
|-------|-----|-------|
| Blue | `#4d9eff` / `#3b82f6` | AI suggestions, links, active states |
| Green | `#22c55e` | Badge dot, success icons |
| Yellow | `#fbbf24` | Star ratings |

### Syntax Highlighting Colors
| Token | Hex | Usage |
|-------|-----|-------|
| Keywords | `#c792ea` | `function`, `const`, `async` |
| Functions | `#82aaff` | Function names |
| Strings | `#c3e88d` | String literals |
| Types | `#ffcb6b` | Type annotations |
| Imports | `#89ddff` | Import paths, operators |
| Line numbers | `#444c56` | Editor gutter |

### Gradient Text
All major headings use a CSS gradient:
```css
background: linear-gradient(180deg, #ffffff 60%, #666666 100%);
-webkit-background-clip: text;
-webkit-text-fill-color: transparent;
```

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, gradients
- No JavaScript
- No frameworks or libraries
- No TailwindCSS
- Desktop-only layout (min-width: 1200px)

---

## Project Structure

```
developer-tool-landing-page/
├── index.html        # Main HTML file with all sections
├── style.css         # All styles and CSS variables
└── README.md         # This file
```

---

## Screenshots

![Full Page Screenshot](screenshot.png)

---

*Built as part of a frontend assignment to recreate the Cursor.com landing page using only HTML and CSS.*
