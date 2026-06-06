# Portfolio Website — Project Reference

## Overview
Personal portfolio for Mohd Hammad Yousuf. Single-page HTML site hosted on GitHub Pages.
**File:** `index.html` (all CSS inline, no build step, no frameworks)

---

## Positioning

**Identity:** Marketing analyst first. GA4/GTM implementation is the foundation that makes the analysis trustworthy — not the primary identity.

**One-line pitch:** I build the measurement layer that tells you what your marketing is actually doing — then the analysis to act on it.

**Primary audience:** Small businesses, ecommerce brands, and founders running paid ads without visibility into what's converting. Also agencies needing a freelance measurement specialist.

**Secondary audience:** Hiring managers at small/mid-size companies (<500 people) looking for a marketing analyst. No enterprise.

**Do not target:** Companies 500+ in size.

**Differentiator:** EDHEC Grande École business school background means commercial thinking, not just technical. The GA4/GTM work is in service of decisions, not dashboards. Plus public proof of work (Google Ads Measurement Library).

**Long-term goal:** Marketing attribution modelling. Current positioning bridges toward it without overclaiming.

---

## Design Decisions

### Direction
Primary: Frida Wiig (fridawiig.xyz) — strict, clean, Swiss Modernist
Secondary: Friederike Hornung — generous vertical rhythm, magazine-like project presentation

### Typography
- **Font:** Space Grotesk only (single font, multiple weights)
- Dropped: Syne (display) and Inter (body)
- Google Fonts: `family=Space+Grotesk:wght@300;400;500;600;700`

### Layout
- Full viewport width — no `max-width` container
- `padding-inline: clamp(2rem, 7vw, 8rem)` for horizontal breathing room
- Generous vertical padding per section (8–10rem)

### Colour
- Background: `#f2ede4` (warm cream — keep as is, intentional differentiator)
- Text: `#0d0c0a`
- Muted: `#6b6560`
- Accent: `#d4291a` (red — very Swiss, used on hero em, ticker separators, cert dot, skill col titles)

### Navigation
- Horizontal top nav, 4 links: About, Projects, Skills, Contact
- Transparent background until 40px scroll, then frosted glass (`backdrop-filter: blur`)
- No bottom border

### Decorative Elements
- **Grain overlay:** kept at `opacity: 0.038`
- **Skills ticker:** kept
- **Section border dividers:** removed — whitespace separates sections
- **Eyebrow labels (ABOUT, WORK, etc.):** removed everywhere. Projects only show name + year.

### About Section
- Two-column: photo ~42% width (portrait ratio 4:5), large type on right
- Photo placeholder text: "Photo coming soon"

### Projects Section
- Frida Wiig pattern: project name (left) + year (right) → full-width image grid → description + tags + links
- No numbered rows, no borders
- Image aspect ratio: 16:9

### Skills Section
- 3-column grid, no decorative bullets
- Rows with light `border-top`/`border-bottom` per item

### Contact Form
- Underline-only input fields (no bordered boxes)
- Enquiry type dropdown handles freelance vs full-time silently

---

## Copy Principles

- **Voice:** First person, direct, specific. Frida Wiig register — confident, no credential-opening, no "passionate about data."
- **Frame:** "I help you" not "hire me." Avoid sounding like a CV.
- **EDHEC:** Mention it, but earn it first — lead with what you do and who you help, then EDHEC explains *why* you think differently.
- **Full-time jobs:** Not mentioned explicitly in the copy. Hiring managers self-select via the enquiry dropdown.

### Key copy (current)

**Hero headline:** Marketing / Analytics / & Measurement

**Hero subtext:**
> I build the measurement layer that tells you what your marketing is actually doing — then the analysis to act on it. GA4, GTM, Google Ads.

**About para 1:**
> I help small businesses, ecommerce brands, and founders stop flying blind on their marketing spend. Most come to me because they're running paid ads without knowing what's actually converting — or because their GA4 setup is broken. I fix the measurement layer, build the tracking architecture, then do the analysis that tells you where the money should actually go.

**About para 2:**
> I studied business at EDHEC Grande École before moving into analytics. That's why I think about data in terms of the commercial decision it needs to support, not the dashboard it fills. Most people split this into two jobs. I keep them together — because the analysis is only as good as what you're tracking.

**Contact copy:**
> If your tracking is broken, your attribution is guesswork, or you just need someone to make the data useful — tell me what you're working with.

---

## Projects (current)

| # | Title | Year | Links |
|---|-------|------|-------|
| 01 | Google Ads Measurement Library | 2025 | Live Site + GitHub |
| 02 | Marketing ROAS Optimization | 2024 | GitHub |
| 03 | Ecommerce Customer Lifetime Value | 2024 | GitHub |
| 04 | Hotel Revenue & Demand Analysis | 2024 | GitHub |
| 05 | F&B Store Product Mix Analysis | 2023 | GitHub |

Screenshots live in `/assets/screenshots/`. Project 01 still uses a placeholder.

---

## Still To Do

- [ ] Add profile photo to `/assets/profile.jpg`
- [ ] Add screenshot for Project 01 (Google Ads Measurement Library) to `/assets/screenshots/measurement-library.png`
- [ ] Push changes to GitHub Pages
- [ ] Consider adding a Services or Availability section as the freelance positioning solidifies
- [ ] Revisit copy when attribution modelling becomes a sellable service (reframe positioning then)

---

## Reference Sites

- **Frida Wiig:** https://fridawiig.xyz — primary design reference
- **Friederike Hornung:** Dog physiotherapist site — secondary reference for vertical rhythm and warmth

---

## Key Design Variables (quick reference)

```css
--bg:     #f2ede4;
--text:   #0d0c0a;
--muted:  #6b6560;
--accent: #d4291a;
--font:   "Space Grotesk";
--pad:    clamp(2rem, 7vw, 8rem);
--nav-h:  64px;
```
