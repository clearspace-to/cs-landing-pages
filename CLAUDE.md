# ABM Campaign Landing Pages

## What This Project Is

A set of standalone HTML landing pages built for Clearspace's 2026 ABM campaign. Each page targets a specific persona or vertical and sits adjacent to the main clearspace.to website. Pages are used in outbound sequences — recipients land here after an email, LinkedIn ad, or direct outreach.

Each landing page is a **single self-contained HTML file** (HTML + CSS + JS all inline). No build tools, no framework, no dependencies beyond Google Fonts.

---

## Pages Built

| File | Persona / Vertical | Status |
|------|-------------------|--------|
| `clearspace-law-landing-page.html` | Law Firm Partner | Complete |

More pages will be added as the campaign expands to new verticals.

---

## Brand & Design Standards

**Colors (CSS variables defined in every file):**
```
--dark:      #2F3F52
--blue:      #3BABFF
--white:     #FFFFFF
--off-white: #F6F6F4
--charcoal:  #1A1D20
--muted:     #6B7A8A
--divider:   #E4E4E0
```

**Typography:** DM Sans (Google Fonts) — weights 300, 400, 500. Body is weight 300. Headlines vary.

**Voice:** Honest, human, relatable. Lead with the business problem. No design-magazine language. No corporate buzzwords. Executive-ready.

**Design-build positioning:** Always reinforce Strategy → Design → Build, one contract, one accountable partner, no surprises.

---

## Persona Reference (for new pages)

**Law Firm Partner** — Reputation, confidentiality, prestige finishes, controlled delivery, minimal disruption. Private offices, acoustics, high-end materials.

**Economic Buyer (CEO/CFO/COO)** — Budget certainty, risk mitigation, ROI, speed to occupancy.

**Project Sponsor (CPO / Head of Workplace)** — Employee experience, culture, talent retention, hybrid alignment.

**Operational Lead** — Timeline clarity, single point of contact, reduced coordination burden.

**High-Growth Tech Operator** — Speed, scalability, flexible layouts.

**Finance Risk Controller** — Cost certainty, clear financial visibility, conservative execution.

See the `brand-context` skill for full persona detail and messaging angles.

---

## Asset Conventions

- Logo files live in persona-specific subfolders (e.g., `Law Logos/`)
- Hero images are placed in the project root alongside the HTML file they belong to
- Reference assets using relative paths from the HTML file

---

## Building a New Landing Page

1. Copy the structure of `clearspace-law-landing-page.html` as a starting point — it has the nav, hero, social proof, CTA, and footer pattern established
2. Swap the persona-specific copy, logos, hero image, and headline
3. Adjust messaging angle to match the target persona's primary pain (see Persona Reference above)
4. Keep the same CSS variable system and DM Sans font
5. Name the file descriptively: `clearspace-[vertical]-landing-page.html`

---

## What Not to Do

- Do not add a build system, bundler, or framework — pages must stay as single HTML files
- Do not introduce new fonts or a different color palette
- Do not write copy that sounds like a design magazine or uses corporate buzzwords
- Do not create shared CSS/JS files — each page is self-contained for portability
