---
name: webcore-analyzer
description: Analyzes websites for 2000s web revival / webcore / neo-geocities aesthetics. Use when the user wants to evaluate a site's old-web characteristics, generate a revival-style design audit, build a 2000s-inspired website, or understand the technical patterns of the webcore movement. Triggers on keywords like "webcore", "2000s web", "old web", "geocities style", "neo-geocities", "retro web", "y2k web", "blinkies", "webrings", "marquee".
---

# SKILL: Webcore Analyzer — 2000s Web Revival Design Audit

## 1. Skill Meta
**Name:** Webcore Analyzer
**Description:** Advanced proficiency in analyzing, auditing, and recreating websites that embody the 2000s web revival aesthetic (also called "webcore," "neo-geocities," "old web revival"). This skill covers the full spectrum of early-web design patterns — from GeoCities-era chaos to Y2K maximalism — and provides actionable frameworks for building or evaluating revival-style sites.

## 2. When to Use This Skill
- Analyzing an existing website for 2000s web revival characteristics
- Generating a detailed design audit of a retro-styled site
- Building a new website with 2000s web revival aesthetics
- Understanding the technical patterns of the webcore movement
- Comparing a site against the webcore feature taxonomy
- Creating a recreation guide for revival-style development

## 3. The Webcore Feature Taxonomy

When analyzing any website, check for these features and count their prevalence:

| Feature | Description | Common Implementations |
|---------|-------------|------------------------|
| **Marquee/Scrolling Text** | Animated scrolling text elements | `<marquee>` tag, CSS `@keyframes` animations, JS-driven marquees |
| **Blinkies** | Small animated GIF badges expressing identity | Sourced from blinkies.cafe, adriansblinkiecollection, pixelsafari |
| **Stamps** | Larger decorative badges (100-200px) | Interest/fandom badges, often in scrolling marquees |
| **88x31 Buttons** | Pixel-perfect site exchange buttons | The original "link exchange" system from the 2000s |
| **Webrings** | Interconnected site networks | onionring system, custom JS widgets |
| **Virtual Pets** | Interactive pet widgets | GifyPet, TamaNOTchi, Pokemon Adoption, custom implementations |
| **Guestbooks** | Public comment/message systems | Atabook, SmartGB, Cbox |
| **Custom Cursors** | Replaced mouse pointer images | PNG/CUR files, cursor-effects libraries |
| **Music Players** | Embedded audio playback | HTML5 audio, Bandcamp embeds, YouTube iframe API, custom iPod replicas |
| **Status Widgets** | Real-time status displays | iMood, Status.cafe, custom "currently" sections |
| **Chatboxes** | Live chat widgets | Cbox (cbox.ws), custom implementations |
| **Dark Mode Toggle** | Theme switching | JavaScript-based, CSS custom properties |
| **Calendar Widgets** | Date displays | JavaScript-generated calendars |
| **Weather Widgets** | Weather information | weatherwidget.io embeds |
| **3D CSS Effects** | Three-dimensional transforms | `transform: rotateX/Y/Z`, `perspective`, `transform-style: preserve-3d` |
| **Sparkle Cursor Trails** | Mouse-following particle effects | mf2fm.com scripts, custom particle systems |
| **Window Chrome** | Desktop OS-inspired frames | Windows 95/XP titlebars, macOS traffic lights |
| **Loading Screens** | Pre-content display | Full-screen overlays with animations |
| **Virtual Dogs/Pets** | Interactive pet games | GinaCities Doggy (Godot-built), custom implementations |
| **Polls** | Interactive questionnaires | Pollcode, custom implementations |
| **Identity Badges** | Personal identification | Pronouns, interests, personality types |
| **Flag Counters** | Visitor country tracking | Flag counter widgets |
| **RSS Feeds** | Content syndication | Custom RSS parsers, Surfing Waves service |
| **Image Maps** | Clickable image regions | `<map>` / `<area>` HTML elements |

## 4. Technical Analysis Framework

When analyzing a website's construction, examine these dimensions:

### 4.1 HTML Structure
- **DOCTYPE:** HTML5 (`<!DOCTYPE html>`), XHTML, HTML4, or Blogger XML
- **Semantic HTML:** Use of `<header>`, `<nav>`, `<main>`, `<article>` vs. `<div>` soup
- **Deprecated Tags:** `<marquee>`, `<blink>`, `<center>`, `<font>`, `<table>` for layout
- **Custom Elements:** Non-standard tags like `<qna>`, `<blog>`, `<normaldiv>`

### 4.2 CSS Approaches
- **Inline Styles:** Heavy `style=""` attributes (authentic to early web)
- **External Stylesheets:** `.css` file organization
- **CSS Variables:** `--custom-properties` for theming
- **Layout Methods:** Floats, Flexbox, Grid, or table-based
- **Fixed Widths:** Non-responsive design (deliberate aesthetic choice)
- **Image Rendering:** `image-rendering: pixelated` for pixel art
- **3D Transforms:** `perspective`, `rotateX/Y/Z`, `transform-style`

### 4.3 JavaScript Patterns
- **Vanilla JS:** No frameworks (100% authentic to 2000s)
- **jQuery:** Common in late 2000s (now rare in revival sites)
- **External Libraries:** Cursor effects, Tippy.js, theme-change
- **Inline Scripts:** `<script>` blocks in HTML (authentic chaos)
- **Module Systems:** ES modules (modern) vs. global scripts (retro)

### 4.4 Hosting & Platform
- **Neocities:** Modern GeoCities successor (most common)
- **Nekoweb:** Alternative retro hosting
- **Blogger/Blogspot:** Google's blogging platform
- **Custom Domain:** Self-hosted or VPS (full control)
- **Netlify/Vercel:** Modern static hosting (least authentic)

## 5. Visual Design Analysis

### 5.1 Color Palette Patterns
| Style | Hex Codes | Example Sites |
|-------|-----------|---------------|
| **Hot Pink/Black** | `#ff00cc` + `#000000` | Orchid's Gumbo |
| **Green Terminal** | `#00FF41` + `#000000` | Rusty Bytes |
| **Pastel Pink** | `#d97fa3` + `#fff5f9` | GinaCities |
| **Dark Red/Gothic** | `#83242a` + `#000000` | Cady's Diary |
| **Rainbow Chaos** | No consistent palette | Kaizocore, MIDIfreak |
| **Nature Green** | `#E0FFEB` + `#9DE0AD` | M. Chamomilla |
| **Warm Cream** | `#f5f0e1` + `#8b7355` | The Butler's Desk |
| **Neon RGB** | `#ff00ff` + `#00ffff` + `#ffff00` | Kaizocore |

### 5.2 Typography Choices
| Font | Era | Vibe | Usage |
|------|-----|------|-------|
| **MS Gothic** | Windows XP | Authentic retro | Body text, headers |
| **Comic Sans MS** | Windows 98 | Playful, casual | Informal content |
| **Trebuchet MS** | Windows 2000 | Quirky, readable | Body text |
| **Press Start 2P** | Pixel art | Gaming, retro | Headings |
| **Pixelify Sans** | Modern pixel | Neo-retro | Headings, labels |
| **IM Fell DW Pica** | Historical | Vintage, elegant | Special text |
| **Times New Roman** | Default | Classic, formal | Formal content |

### 5.3 Layout Archetypes
1. **Three-Column:** Sidebar + Main + Sidebar (most common)
2. **Windowed Bento Grid:** Multiple floating windows (desktop metaphor)
3. **Scattered Absolute:** Everything positioned absolutely (maximum chaos)
4. **Full-Screen Atmospheric:** Layered backgrounds with centered content
5. **Single-Column Tabbed:** Tab-switched content (SPA-like)

## 6. Analysis Workflow

When analyzing a website, follow this procedure:

### Step 1: Fetch Source Code
```
Use webfetch with format: "html" to get raw source
Analyze HTML structure, inline styles, and script tags
```

### Step 2: Identify Features
Check for each item in the Feature Taxonomy (Section 3)
Count occurrences and note implementations

### Step 3: Analyze Construction
Examine HTML DOCTYPE, CSS approach, JS patterns, hosting platform
Note modern vs. authentic techniques

### Step 4: Evaluate Visual Design
Document color palette, typography, layout archetype
Identify the "vibe" (gothic, cottagecore, cyberpunk, etc.)

### Step 5: Assess Feel & Experience
Describe the emotional impact and user journey
Note unique or standout elements

### Step 6: Generate Report
Structure findings using the report template (Section 7)

## 7. Report Template

```markdown
# [Site Name] — Webcore Analysis

**URL:** [url]
**Platform:** [Neocities/Nekoweb/Blogger/Custom]
**Webmaster:** [name if known]

## Visual Design

### Color Palette
- **Background:** [hex/code]
- **Primary Accent:** [hex/code]
- **Secondary Accent:** [hex/code]
- **Overall Vibe:** [description]

### Typography
- **Primary Font:** [font name]
- **Body Size:** [px/rem]
- **Special Effects:** [glow, shadow, etc.]

### Layout
- **Archetype:** [Three-column/Windowed/Scattered/Atmospheric/Tabbed]
- **Width:** [fixed/Responsive]
- **Modern Techniques:** [Flexbox/Grid/Floats]

## Features

### [Feature Name]
- **Implementation:** [how it's built]
- **Authenticity:** [modern/retro/hybrid]
- **Notable Details:** [specifics]

## Construction Technique

### HTML
- **DOCTYPE:** [HTML5/XHTML/HTML4]
- **Semantic Elements:** [yes/no/partial]
- **Deprecated Tags:** [list if any]

### CSS
- **Approach:** [inline/external/mixed]
- **Variables:** [yes/no]
- **Layout Method:** [float/flex/grid]

### JavaScript
- **Framework:** [none/jQuery/other]
- **External Libraries:** [list]
- **Inline Scripts:** [yes/no]

### Hosting
- **Platform:** [name]
- **Control Level:** [full/shared/limited]

## Feel & Experience

[2-3 paragraphs describing the emotional impact, user journey, and unique characteristics]

## Webcore Score

| Category | Score (1-10) | Notes |
|----------|--------------|-------|
| Marquee/Scrolling | | |
| Blinkies/Stamps | | |
| 88x31 Buttons | | |
| Webrings | | |
| Virtual Pets | | |
| Guestbook/Chat | | |
| Custom Cursor | | |
| Music Player | | |
| Visual Chaos | | |
| Authenticity | | |
| **Overall** | **/100** | |
```

## 8. Recreation Guide

### Essential Elements (Must-Have)
1. At least one `<marquee>` tag or CSS-animated scrolling element
2. A collection of blinkies (10+ recommended)
3. 88x31 site buttons (create your own, collect from friends)
4. A guestbook (Atabook or SmartGB)
5. A virtual pet (GifyPet iframe or TamaNOTchi widget)
6. Webring participation (3+ rings via onionring system)
7. A background image (tiled or fixed, pixel art preferred)

### Nice-to-Have Elements
8. Custom cursor (PNG or CUR file)
9. Stamp collection (10+ in scrolling marquee)
10. Music player (HTML5 audio or Bandcamp embed)
11. Status widget (iMood or Status.cafe)
12. Site button with copy-paste HTML code
13. Animated GIF decorations (scattered across page)
14. Sparkle cursor trail (mf2fm.com script)

### Technical Recommendations
- Use system fonts: MS Gothic, Comic Sans MS, Trebuchet MS
- Set `image-rendering: pixelated` on background images
- Use `position: absolute` for scattered elements
- Avoid responsive design — fixed widths are part of the aesthetic
- Use `#` links with `target="_blank"` for external links
- Include a "best viewed in" badge (ironic or sincere)

### Authenticity Levels
| Level | Description | Techniques |
|-------|-------------|------------|
| **Museum Piece** | Professional recreation of old web | Modern build tools, authentic output |
| **Hybrid** | Modern stack, retro aesthetics | Flexbox/Grid + retro chrome |
| **Authentic Chaos** | Hand-coded, inline styles | `<marquee>`, absolute positioning |
| **Maximum Chaos** | Every element moves/flashes | Multiple animations, cursor effects |

## 9. Common Pitfalls to Avoid

1. **Over-polishing:** The charm is in the imperfection
2. **Too much whitespace:** Old web was dense, not airy
3. **Responsive design:** Fixed widths are intentional
4. **Modern fonts:** System fonts are more authentic
5. **Clean code:** Inline styles and `<div>` soup are period-accurate
6. **Accessibility:** Old web wasn't accessible (but revival sites can be)

## 10. Reference Sites

| Site | Platform | Style | Key Features |
|------|----------|-------|--------------|
| knoxstation.neocities.org | Neocities | Tropical/vaporwave | Stamps, webrings, virtual pet |
| cinnamoon444.blogspot.com | Blogger | Gothic lolita | CD gallery, blinkies, sparkle cursor |
| peachyvoid.com | Custom | Cottagecore | iPod player, 12+ webrings, nature docs |
| rusty-bytes.neocities.org | Neocities | Cute hacker | Terminal aesthetic, Diet Coke counter |
| ginacities.com | Custom | Pastel desktop | Virtual dog, window chrome, dark mode |
| mchamomilla.nekoweb.org | Nekoweb | Magical garden | Tab navigation, custom cursor, polls |
| kaizocore.neocities.org | Neocities | Maximum chaos | SVG creature, bouncing screensaver, blobs |
| orchidsgumbo.neocities.org | Neocities | Hot pink cyberpunk | 3D locker, 1594 dollz, loading screen |
| betapopsicle.neocities.org | Neocities | Windowed desktop | Dantendo, interactive pet, theme toggle |
| thebutlersdesk.neocities.org | Neocities | Victorian study | 50+ blinkies, butler mascot, Cbox |
| thesnailgarden.nekoweb.org | Nekoweb | Nature terrarium | Plural system, journal, headmate pages |
| melonking.net | Custom | Dream world | Layered atmosphere, iMac video, S3M audio |
| midifreak.online | Custom | Hypnospace | Expression Web 4, 10000px height, image maps |
| cameronsworld.net | Custom | Museum piece | GeoCities archive, professional production |

---

*Skill based on analysis of 14 webcore websites, September 2026*
