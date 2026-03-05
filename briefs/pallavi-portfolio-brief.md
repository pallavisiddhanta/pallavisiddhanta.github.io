# Portfolio Redesign Brief — Pallavi Siddhanta
**For: Claude Code Orchestrator**
**Source site:** https://ps-test.carrd.co/
**Status:** Skeleton approved. Ready for full build.

---

## 1. OVERVIEW & POSITIONING

**Name:** Pallavi Siddhanta
**Role:** Policy & Communications
**Core positioning line:** *"Building the public narratives that make policy action possible."*
**Anchor credentials:** City of Chicago (Chicago Dept. of Public Health) · SEWA Bharat (India)

**What makes her distinct:**
She is not just a communications professional — she builds the entire communications infrastructure that turns contested policy into public understanding. This spans: visual identity design → billboard/OOH campaigns → earned media strategy → crisis communications → press releases. Policy in, public narrative out. This through-line must be visible in every section.

---

## 2. DESIGN SYSTEM

### Color Palette
```
--terracotta:       #C97B5A   (primary accent, CTAs, labels)
--terracotta-light: #E8C4A8   (hero subtitle, warm highlights)
--cream:            #FAF7F2   (page background)
--dark:             #1C1C1C   (hero background, proof strip)
--mid:              #5A5550   (body text, secondary text)
--placeholder:      #EDE8E0   (placeholder blocks)
--border:           #D4C9BB   (dividers, borders)
--white:            #FFFFFF   (campaign cards background)
```

### Typography
```
Headings/body:  Georgia, serif
Labels/mono:    'Courier New', monospace (for section labels, tags, pills)
```

### Type Scale (mobile-first, max-width: 430px)
```
Hero name:          34px, letter-spacing: 0.06em, line-height: 1.15
Hero positioning:   15px italic
Section label:      9px, Courier New, letter-spacing: 0.18em, uppercase, opacity 0.7
Campaign title:     21px, normal weight
Body/arc text:      13–15px, line-height: 1.65–1.8
Pills/tags:         9–11px, Courier New
```

### Spacing
```
Section padding:    44px 28px (top/bottom, left/right)
Campaign padding:   34px 28px
```

---

## 3. SITE ARCHITECTURE — 6 SECTIONS (single scroll)

```
1. HERO          → Dark bg, portrait photo, name, positioning line, credentials
2. PHILOSOPHY    → Cream bg, mission statement, bridge sentence
3. CAMPAIGNS     → White bg, 3 case studies with full arc + images + coverage pills
4. PROOF STRIP   → Dark bg, 8 outlet names in 2-col grid
5. ABOUT         → Cream bg, portrait photo (cropped/intimate), placeholder bio text
6. CONTACT       → Terracotta bg, CTA, email + LinkedIn buttons
```

**NO separate pages. NO tabs. NO "Work" / "Projects" split nav. Pure single scroll.**

---

## 4. SECTION SPECS

### SECTION 1: HERO
- Full-width portrait photo (top half of screen), gradient fade to dark at bottom
- Text block on dark background below photo
- Name: "Pallavi / Siddhanta" (two lines)
- Positioning: *"Building the public narratives that make policy action possible."*
- Credential strip (small caps, muted): `Policy & Communications · City of Chicago · SEWA Bharat`
- **Photo source:** https://ps-test.carrd.co/assets/images/image01.jpg
  *(Note: This may require auth — user has confirmed the portrait photo exists on current site. Fallback: use the uploaded screenshot image at `/mnt/user-data/uploads/Screenshot_20260304_163240_Chrome.jpg` — crop to face/portrait area)*

### SECTION 2: PHILOSOPHY
- Label: "Belief"
- Pull quote (italic, 17px): *"In a world so mired in chaos, I believe that intentional policy action combined with transparent public dialogue will pave the way for a more inclusive, more sustainable future."*
- Bridge sentence (Courier New, terracotta): *"I build the communications infrastructure that makes that possible — from visual identity to earned media to crisis response."*

### SECTION 3: CAMPAIGNS

Each campaign card contains:
1. Tag line (e.g. "Campaign 01 · 2024–2025")
2. Title (2-line, large)
3. Client name (small, muted)
4. Image strip (3 slots, 88px tall, flex row) — use real images where available, styled placeholders otherwise
5. Story arc (3 rows: Challenge / Approach / Outcome)
6. Coverage pills (outlet names, pill-shaped tags)

---

#### CAMPAIGN 01 — Harm Reduction is Public Health
**Tag:** Campaign 01 · 2024–2025
**Client:** Chicago Department of Public Health

**Images to source (from current site — many are broken SVGs, use what loads):**
- Gun safety visual: `https://ps-test.carrd.co/assets/images/gallery02/3e168c1c.jpg`
- Visual branding for arts therapy (currently broken — use placeholder)
- Behavioral Health Event Calendar screenshot (currently broken — use placeholder)
- Billboard/OOH assets (currently broken — use placeholder)

**Story arc:**
- **Challenge:** Chicago needed to shift public narrative around harm reduction — a politically contested approach — while building durable infrastructure for ongoing seasonal crisis response.
- **Approach:** Built the full communications stack: visual identity for arts therapy clinics at City-run mental health facilities; billboard campaigns using City-owned advertising assets; proactive and reactive media strategy for opioid spike events including Health Alert Network (HAN) response.
- **Outcome:** Chicago opioid overdose deaths fell (continued drop from 2023). $18M in Illinois funding secured for overdose prevention sites. National and local media coverage.

**Coverage links:**
```
Chicago Tribune: https://www.chicagotribune.com/2024/10/03/chicago-sees-steep-drop-in-number-of-deaths-tied-to-opioid-overdoses/
Crain's Chicago Business: https://www.chicagobusiness.com/health-care/chicagos-opioid-efforts-show-early-promise
Chicago Sun-Times (funding): https://chicago.suntimes.com/the-watchdogs/2025/01/30/illinois-overdose-prevention-sites-18-million-dollars
Fox32 (arts therapy): https://www.fox32chicago.com/video/1659027
WGN9 (mental health resources): https://wgntv.com/health/free-and-low-cost-mental-health-resources-available-in-chicago/
ABC7 (heatwave spike): https://abc7chicago.com/post/increase-opioid-drug-overdose-incidents-during-hot-chicago-weather-triggers-citys-spike-alert-system/16839955/
NBC Chicago (heatwave): https://www.nbcchicago.com/news/local/chicago-sees-weekend-spike-in-opioid-overdoses-during-heatwave/3776364/
Sun-Times (heatwave): https://chicago.suntimes.com/news/2025/06/23/health-experts-see-link-between-weekend-heat-wave-and-spike-in-opioid-overdoses
The Guardian: https://www.theguardian.com/us-news/2025/jul/22/trump-cuts-overdose-deaths
```

**Coverage pills to display:** Chicago Tribune · The Guardian · Crain's · NBC · ABC7 · Sun-Times · Fox32

---

#### CAMPAIGN 02 — Violence Prevention, Chicago 2025
**Tag:** Campaign 02 · 2025
**Client:** Chicago Department of Public Health

**Images:** No visual branding assets identified for this campaign. Use styled placeholder tiles or embed press release screenshots.

**Story arc:**
- **Challenge:** Chicago recorded a historic drop in homicides and nonfatal shootings in 2025. The story needed telling — carefully, credibly, without overpromising — while simultaneously managing reactive opioid crisis messaging during summer heatwaves.
- **Approach:** Designed a proactive media plan for Summer 2025 ICS (Incident Command System) covering both violence prevention and opioids. Pitched the July 4th violence reduction story to The Trace. Managed transparent messaging around opioid spike alerts (2 SDs over mean). Leveraged wins to address looming federal funding cuts via The Guardian.
- **Outcome:** 33% reduction in violence over July 4th weekend reported nationally. Opioid spike handled transparently. Federal funding threat elevated to national conversation.

**Coverage links:**
```
The Trace (July 4th): https://www.thetrace.org/2025/07/chicago-shootings-july-fourth-holiday/
CDPH Press Release (violence reduction): https://www.chicago.gov/city/en/depts/cdph/provdrs/health_protection_and_response/news/2025/jul/cdph-weekly-media-brief-07-10-2025.html
CDPH Press Release (summer activations): https://www.chicago.gov/city/en/depts/cdph/provdrs/health_protection_and_response/news/2025/may/cdph-press-release-05-23-2025-summer-activations.html
South Side Weekly: https://southsideweekly.com/expiring-federal-funds-threaten-chicagos-alternative-crisis-response-effort/
Sun-Times (CARE program): https://chicago.suntimes.com/health/2025/07/25/mental-health-crisis-911-calls-care-programec-crisis-assistance-response-engagement-medill-investigative-lab-chicago-mindsite-news
MindSite News: https://mindsitenews.org/2025/07/25/chicago-crisis-response-program-at-tipping-point/
```

**Coverage pills to display:** The Trace · NBC Universal · Sun-Times · South Side Weekly · The Guardian

---

#### CAMPAIGN 03 — Centering Women Workers During COVID-19
**Tag:** Campaign 03 · 2020–2021
**Client:** SEWA Bharat, India

**Images:** Instagram/social content exists — use linked Instagram posts as visual reference tiles:
- https://www.instagram.com/p/CBlGRVfnQKk/?img_index=1
- https://www.instagram.com/p/CSdx0BLHMDZ/
- https://www.instagram.com/p/CBC60c7n0pA/?img_index=1
*(These are linked from current site. Fetch thumbnail previews or use styled placeholders with IG link.)*

**Story arc:**
- **Challenge:** During COVID-19, India's informal women workers — domestic workers, textile recyclers, street vendors — were invisible in the policy conversation. Their economic and social needs were unaddressed in mainstream media.
- **Approach:** Built a grassroots communications campaign centering workers' voices. Produced social media content and placed stories with feminist media, development sector publications, and national newspapers in India.
- **Outcome:** Coverage in national and sector-leading publications helped elevate policy visibility for domestic workers and textile recyclers. Stories published in Feminism in India, Times of India, and India Development Review.

**Coverage links:**
```
Feminism in India: https://feminisminindia.com/2021/04/08/women-collective-informal-sector/
Times of India: https://timesofindia.indiatimes.com/women-textile-recyclers-even-reuse-tiny-fragments-sustaining-ecology-and-economy/articleshow/84483375.cms
India Development Review: https://idronline.org/article/rights/securing-economic-and-social-rights-for-domestic-workers/
```

**Coverage pills to display:** Times of India · Feminism in India · India Dev Review

---

### SECTION 4: PROOF STRIP
Dark background (#1C1C1C). Label: "As seen in"
2-column grid of outlet tiles (subtle white/6% background, Courier New text):

```
The Guardian      | Chicago Tribune
NBC Universal     | Crain's Chicago
ABC7              | The Trace
Times of India    | Sun-Times
```

### SECTION 5: ABOUT
- Label: "About"
- Portrait photo (same image as hero, or a cropped version) — full width, 220px height, object-fit: cover
- Name subheading: "Pallavi Siddhanta" (Courier New, small caps)
- Bio paragraph: **PLACEHOLDER — needs Pallavi's voice**
  - Prompt for her: 2–3 sentences, first person, answering: Who are you? Where do you come from? What drives this work?
  - Style: warm, human, not a resume. Example tone: *"I grew up believing that policy should serve people — but that it only does when people can see themselves in the story. I've spent my career at that intersection..."*

### SECTION 6: CONTACT
- Background: terracotta (#C97B5A)
- Label: "Get in touch"
- Headline: "Let's work together."
- Subtext: "Open to collaborations, consulting, and conversations."
- Two buttons:
  - Primary (white bg, terracotta text): "Send an email" → mailto link
  - Secondary (white border, white text): "Connect on LinkedIn" → https://www.linkedin.com/in/psiddhanta/

---

## 5. NAVIGATION

**Remove the current WORK / PROJECTS / CONTACT button nav entirely.**

Replace with a minimal sticky top bar (optional) OR rely on pure scroll. If nav is included, use anchor links to section IDs: `#campaigns`, `#about`, `#contact` — labeled simply as "Work", "About", "Contact".

---

## 6. ADDITIONAL CONTENT ASSETS

### Press Releases (can be linked from Campaign 01/02 cards as "source" links)
```
CDPH Jan 2025 (Shine Hope): https://www.chicago.gov/city/en/depts/cdph/provdrs/behavioral_health/news/2025/january/cdph-press-release-01-22-2025.html
CDPH Apr 2025 (GASC $20M): https://www.chicago.gov/city/en/depts/cdph/provdrs/health_protection_and_response/news/2025/apr/cdph-press-release-04-14-2025-gasc-comm-violence-intervention.html
CDPH Dec 2024 (Victim Advocates): https://www.chicago.gov/city/en/depts/cdph/provdrs/behavioral_health/news/2024/december/cdph-press-release-12-20-2024-victim-advocates-training-program-graduation.html
```

### SunPedal Ride (bonus/archival work — omit from main campaigns, can add as footnote or "earlier work" section if desired)
```
The Hindu: https://www.thehindu.com/life-and-style/travel/60-cities-in-60-days-in-a-solar-powered-auto/article28707202.ece
HEC Paris: https://www.hec.edu/en/school/news/sasi-student-aims-revolutionize-india-s-energy
```

### Chicago Policy Review Print Edition 2024
- Referenced on current site but no URL provided. Treat as placeholder or ask Pallavi for link.

---

## 7. SOCIAL / CONTACT LINKS
```
LinkedIn:  https://www.linkedin.com/in/psiddhanta/
Email:     Encoded on current site (anti-spam). Ask Pallavi for direct address.
```

---

## 8. IMAGES SUMMARY

| Image | Status | Source |
|-------|--------|--------|
| Hero portrait | ✅ Exists | https://ps-test.carrd.co/assets/images/image01.jpg (may need auth) OR crop from uploaded screenshot `/mnt/user-data/uploads/Screenshot_20260304_163240_Chrome.jpg` |
| Gun safety visual (Campaign 01) | ✅ Loads | https://ps-test.carrd.co/assets/images/gallery02/3e168c1c.jpg |
| Arts therapy branding (Campaign 01) | ❌ Broken SVG | Use placeholder |
| Billboard assets (Campaign 01) | ❌ Broken SVG | Use placeholder |
| Behavioral Health Calendar (Campaign 01) | ❌ Broken SVG | Use placeholder |
| SEWA Bharat social content | ⚠️ Instagram | Embed or placeholder with IG links |
| Campaign 02 visuals | ❌ None identified | Use styled placeholder or press release embed |

---

## 9. WHAT STILL NEEDS TO COME FROM PALLAVI

1. **About paragraph** — 2–3 sentences, first person, her voice
2. **Email address** — for contact CTA
3. **Recovered image assets** — the broken gallery images from the current Carrd site
4. **Optional:** A quote or pull stat she's proud of for any campaign (e.g. "The opioid overdose death rate fell X% in 2024")
5. **Optional:** Chicago Policy Review 2024 link

---

## 10. TECHNICAL NOTES

- **Platform:** Build as standalone HTML/CSS (mobile-first, max-width 430px, renders well on desktop too at centered layout)
- **No framework required** — pure HTML + CSS is appropriate for this single-scroll site
- **Font loading:** Georgia and Courier New are system fonts — no Google Fonts needed
- **Accessibility:** Use semantic HTML5 elements (`<section>`, `<article>`, `<h1>`–`<h3>`, `<nav>`)
- **Performance:** Lazy-load images. Keep total page weight light.
- **Contact form:** Current Carrd form can be replicated with Formspree or similar, or replaced with mailto link for simplicity

---

## 11. TONE REFERENCE

The site should feel like: **warm authority**. Not a government PR office. Not a freelancer portfolio. Someone who has done serious, meaningful public health work and wants you to understand why it mattered — not just what they did.

Writing voice throughout: direct, values-driven, human. No jargon. No bullet-pointed achievements. Stories with stakes.

---

*Brief compiled from: site audit of ps-test.carrd.co, design review of mobile screenshots, and narrative architecture session. — March 2026*
