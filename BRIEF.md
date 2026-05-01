# Mavio — Design Brief

## Brand Synopsis

Mavio is an AI-powered tennis ball machine and companion app, founded March 2025 in Redwood City by Sophie Luo (UPenn CS, ex-product-lead at an AI + AR-glasses unicorn) with hardware lead Ray Shen (20yr embedded systems). Originally named Rallie; rebranded to Mavio in July 2025 after the original name was already taken.

The product positioning: *"Tennis meets real AI."* The competitive edge is being AI-native from day one — most competitors (Tenniix, PongBot, Acemate) bolt AI onto otherwise-conventional ball machines. Mavio is hardware + software co-designed: dual brushless DC motors, computer vision, adaptive ML drills that respond to the player mid-rally.

A Kickstarter campaign is planned for Q3 2026. Beta program is live now via the survey ($100 incentive). Sophie is the public face of the brand — credibility comes from her unicorn-startup track record taking hardware from prototype to mass production with Foxconn / Flex partners. The audience is serious adult tennis players — recreational-to-club level — who want better practice between lessons but find current ball machines feel like "relics from the 90s" (Sophie's own words).

The mockup is being shown to Sophie as a portfolio pitch by Banana Bytes. Goal: get hired to design and build the production brand site for the Kickstarter launch. Photography services are a deliberate part of the pitch — every AI-generated image carries a "Future shoot" tag indicating Banana Bytes will shoot the real thing.

---

## Design Decisions

### Direction A — Atelier
- **Mood**: Editorial Vogue / Kinfolk on a warm dark canvas. Sophie's narrative as the spine, clay-court atmosphere as the texture, cobalt as a cool AI accent against warm clay. *Premium tech with soul.*
- **Fonts**: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display, opsz 96–144, italic for emphasis) + [Outfit](https://fonts.google.com/specimen/Outfit) (body, 300–600) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (labels)
- **Colors**: `#0E0E0C` ink (canvas), `#F5F0E8` cream (text), `#B8451C` clay (warm accent), `#2540F0` cobalt (cool AI accent), `#2A2826` charcoal (cards)
- **Layout**: Editorial column-based — wide hero with full-bleed clay-court image, narrow founder origin chapter (image left / text right), 4 pillars in alternating image-text rhythm, atmospheric break, progress timeline cards, 8-stat strip, twin workshop image break, centered CTA, footer
- **Signature element**: Full-bleed cinematic hero with editorial pull-quote treatment from Sophie — large serif italic with cobalt typographic quote marks. The dark canvas + warm clay + cool cobalt creates a deliberate temperature tension.
- **Logo used**: **Echo v1** — geometric Outfit lowercase wordmark with cobalt sensor-pulse i-dot. The cobalt accent links the AI tech identity to the brand's premium positioning.
- **Trends used**: scroll-triggered reveals (IntersectionObserver), oversized editorial typography, magazine-grade pull-quote treatment, full-bleed cinematic hero with veil gradient.

### Direction B — Specimen
- **Mood**: Engineered Apple / Teenage Engineering / Leica precision. Off-white industrial, hairline grids, oversized numerics, motor-as-hero. The spec sheet, made physical. *Built for the Kickstarter campaign page itself.*
- **Fonts**: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) (display + body, 700–800, opsz 72–96, tight `-0.045em` kerning) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (all metadata, labels, callouts)
- **Colors**: `#F4F4F1` paper (canvas), `#0A0A0A` ink (text), `#FF5A1F` sport orange (single accent), `#9CA39A` graphite (muted), `#E8E5DD` chalk (cards)
- **Layout**: Engineering-document feel. Hairline 48px grid backdrop, corner crosshairs at every section edge, brushless motor as oversized hero with floating spec callouts, 8-tile bento spec sheet (mixing inverted ink card, sport-orange highlight, chalk fills, outlined card), knolled teardown image, real wheels comparison strip, Capture/Analyze/Adapt/Improve 4-card row, studio product hero with spec inventory, real prototype + chronology, team section, oversized typographic footer wordmark.
- **Signature element**: The 8-tile bento spec sheet that mixes oversized numerics ("30 lb", "150", "10–80 MPH", "6600 RPM") across inverted cards / orange highlights / chalk fills / outlined cards — feels like flipping through a Hasselblad manual. Plus the massive footer "mavıo." wordmark at clamp(7rem, 28vw, 22rem) with sport-orange period.
- **Logo used**: **Spec** — Bricolage Grotesque 800 wordmark with sport-orange pilot-light i-dot and small M-in-circle spec mark beside.
- **Trends used**: bento grids with mixed weights, oversized numerics, hairline grid background, corner crosshairs, monospace metadata, full-bleed product photography on seamless backdrop, oversized typographic footer.

### Direction C — Volley
- **Mood**: Nike / On Running / Stripe energy. Court navy canvas with optic-green tennis pulse and bright kinetic energy. *AI sport, sport-aware AI.*
- **Fonts**: [Outfit](https://fonts.google.com/specimen/Outfit) (display + body, 600–800, opsz 96, tight `-0.045em` kerning) + [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) (labels, stats)
- **Colors**: `#0B1F3A` court navy (canvas), `#0F2849` court (cards), `#FAFAF7` bone (text), `#C8E812` ball-green (primary accent), `#A8C812` green-soft, `#1F4FA0` baseline blue (secondary accent), `#5C6470` slate
- **Layout**: Full-bleed sunrise-baseline hero with animated pulsing echo dot, live-stats bento dashboard (847 shots / 87% FH / 2,140 RPM / 17 streak / court heatmap SVG), 4-card 2x2 OBSERVES/ANALYZES/ACTS/SUMMARIZES with image-on-top + text-below, 3-image athletic detail strip (feet / grip / silhouette), founder section, full-bleed Mavio-on-court image with overlaid copy, quick-spec strip on court navy, centered CTA, footer.
- **Signature element**: Animated `echo-dot` pulsing rings (CSS keyframe `pulse-ring`, 2.6s ease-out infinite) on the hero status indicator and CTA — the brand's AI signal becomes a live element on the page. Court-line grid background pattern at 96px gives every navy section a faint athletic infrastructure. SVG court heatmap inside the bento dashboard with green opacity dots.
- **Logo used**: **Echo v2** — Outfit wordmark with green tennis-ball-as-signal-pulse i-dot. The dot color matches the hero ball; the pulse rings link to the AI listening narrative.
- **Trends used**: bento data dashboard, pulsing CSS animation, court-line grid backdrop, SVG inline data visualization (court heatmap), athletic 3-image detail strip, full-bleed product image with text overlay.

---

## 21st.dev Component Provenance

| Mockup section | 21st.dev component | Search query | Source file | What we borrowed |
|---|---|---|---|---|
| Direction A · pull-quote section | Testimonials Two | `oversized typographic footer wordmark` | `21st-sources/testimonials-pull-quote.tsx` (referenced) | Large editorial pull quote with citation strip — adapted for Sophie's hook |
| Direction A · 4 pillars | Tailark Features 7 | `editorial dark hero serif` | `21st-sources/tailark-features-7.tsx` (referenced) | Editorial features grid framing — adapted for image+text alternating rhythm |
| Direction A · footer wordmark | Modem Animated Footer | `oversized typographic footer wordmark` | `21st-sources/modem-animated-footer.tsx` (referenced) | Oversized brand-name typography treatment |
| Direction B · 8-tile bento spec | BentoGridShowcase | `bento glass dashboard glow` | `21st-sources/bento-product-features.tsx` (referenced) | 6-slot bento with mixed-weight cards — extended to 8 tiles for spec sheet |
| Direction B · footer wordmark | Modem Animated Footer | `oversized typographic footer wordmark` | `21st-sources/modem-animated-footer.tsx` (referenced) | Massive brand wordmark treatment in footer |
| Direction C · 4-card OBSERVES grid | StickyFeatureSection | `scroll sticky feature steps` | `21st-sources/sticky-scroll-cards.tsx` (referenced) | 4 large cards with image-top text-below pattern |
| Direction C · live-stats bento | BentoGridShowcase | `bento glass dashboard glow` | `21st-sources/bento-product-features.tsx` (referenced) | Mixed-card bento with oversized numerics + small detail cards + court-heatmap visualization slot |

Vanilla HTML implementations live in the 3 direction files. **For HANDOFF MODE** (production React/Next.js rebuild): the original Tailwind/React components in `21st-sources/` are the starting point — drop them in, then re-apply Mavio's content from the current vanilla files.

(`21st-sources/` is intentionally minimal in this build — Inspiration searches surfaced patterns we adapted rather than cached. If Sophie picks a direction and wants the production rebuild, we'll re-fetch and cache the specific components for the chosen direction.)

---

## Content Inventory

**Real images used (from mavio.ai)**:
- `first_prototype.jpeg` — first Mavio prototype on hardcourt with exposed wires (Direction B)
- `worn-wheel.jpeg` — original PU wheel after field tests, visibly worn (Direction B)
- `new_wheels.jpg` — redesigned launch wheels v2 (Direction B)
- `field-test.gif` — kinetic motion of machine in action (Directions A and C)
- `sophie-founder-collage.png` — Sophie's life collage (available, unused in current build)

**Generated images used (Grok 2K + Nano Banana Pro 2K)**:
- `A-hero-01.jpg` — clay-court dust at dusk (Direction A hero)
- `B-hero-01.jpg` — brushless DC motor specimen (Direction B hero)
- `C-hero-02.jpg` — sunrise navy baseline with ball (Direction C hero)
- `founder-window-01.jpg` — Sophie-styled portrait in window light (Directions A and C)
- `founder-bench-01.jpg` — top-down workbench with parts and CAD laptop (Direction A)
- `founder-printer-01.jpg` — 3D printer mid-print at night (Direction A)
- `founder-sketchbook-01.jpg` — sketchbook with engineering schematics + coffee + motor (Direction A)
- `engineering-knolling-01.jpg` — top-down knolled component teardown (Direction B)
- `mavio-court-01.jpg` — production Mavio at court, golden hour (Direction C)
- `mavio-studio-01.jpg` — production Mavio on cream seamless backdrop (Direction B)
- `ai-overlay-01.jpg` — player silhouette with motion-tracking overlay (Directions A and C)
- `ai-trajectory-01.jpg` — yellow vector arc traced through air (Directions A and C)
- `app-dashboard-01.jpg` — phone mockup with dark-mode analytics (Directions A and C)
- `clay-dust-01.jpg` — clay dust burst (Direction A atmospheric break)
- `player-feet-01.jpg` — feet in ready stance (Direction C detail strip)
- `player-grip-01.jpg` — hand on racquet grip (Direction C detail strip)
- `player-silhouette-01.jpg` — sunset forehand silhouette (Direction C detail strip)
- Logos (NB Pro): `logo-trace-nb-02.jpg`, `logo-spec-nb.jpg`, `logo-echo-nb.jpg` (v1 cobalt), `logo-echo-nb-v2.jpg` (v2 green)

**Real links preserved**:
- All sub-page links route to live mavio.ai (`/brand-story`, `/updates`, `/faq`, `/contact`, `/survey`)
- All social links use real handles (X, TikTok, YouTube, Facebook group, LinkedIn)
- Address, email, location all verbatim from `/contact`

---

## Share Preview

Each page ships with full Open Graph + Twitter Card + favicon meta. Tested live (HTTP 200 verified post-push).

### Selector (`index.html`)
- **OG image**: `images/og.jpg` (1200×630, `A-hero-01` clay-dust-at-dusk crop)
- **OG title**: `Mavio — three brand directions, by Banana Bytes`
- **OG description**: `Three concept directions for Mavio's Kickstarter-bound brand site, by Banana Bytes. Atelier (editorial), Specimen (engineered), Volley (kinetic). Pick one.`
- **Theme color**: `#0A0A0A`
- **Type**: `website`

### Direction A — Atelier (`direction-atelier.html`)
- **OG image**: `images/og-direction-atelier.jpg` (1200×630, `A-hero-01` cropped)
- **OG title**: `Mavio — Meet your new tennis coach. AI-native. Always ready.`
- **OG description**: `An AI tennis coach that knows your game, adapts to your skill, and actually helps you level up. Beta program open. Kickstarter soon.`
- **Theme color**: `#0E0E0C`

### Direction B — Specimen (`direction-specimen.html`)
- **OG image**: `images/og-direction-specimen.jpg` (1200×630, `B-hero-01` cropped)
- **OG title**: `Mavio — Engineered to think. Built to last 10,000 sessions.`
- **OG description**: `30 lbs · 150 balls · dual brushless DC at 6600 RPM · 10–80 MPH · all spin types. AI-native tennis hardware. Beta open.`
- **Theme color**: `#F4F4F1`

### Direction C — Volley (`direction-volley.html`)
- **OG image**: `images/og-direction-volley.jpg` (1200×630, `C-hero-02` cropped)
- **OG title**: `Mavio — A coach that listens. Tennis training, finally on your side.`
- **OG description**: `The first AI tennis coach that adapts mid-rally. Real-time stance, swing, and trajectory tracking. Beta open.`
- **Theme color**: `#0B1F3A`

### Favicon
- `favicon.png` (64×64) and `favicon-512.png` (Apple touch icon, 512×512), both cropped from `mavio-studio-01.jpg`. **Replace with the locked logo's mark variant** once Sophie picks a direction.

### Sub-pages with their own OG
None in this build — each direction is a single landing page. Sub-page OG variants (e.g., individual case studies, founder profile, app page) get added during the production build.

---

## Image Generation — Cost Log

| Tier | Count | Cost each | Subtotal |
|---|---|---|---|
| Grok Imagine Standard 2K (atmospheric explorations) | 30 | $0.02 | $0.60 |
| Nano Banana Pro 2K (logo concepts) | 4 (1 retry) | $0.134 | $0.536 |
| **Total project art spend** | **34 generations** | | **$1.14** |

Full per-image log lives in `IMAGE_LOG.md` (next-step task — ready to write if Sophie picks a direction and Banana Bytes proceeds).

---

## Suggested Next Mockups
1. **Founder profile page** — long-form feature on Sophie's path from UPenn CS to AR-glasses unicorn to Mavio. Photo essay format. Use Direction A's editorial register.
2. **Kickstarter campaign page** — extended Direction B with reward tiers, stretch goals, pre-order pricing, FAQ. Built specifically for the Kickstarter funnel.
3. **Companion app product page** — focused on the iOS/Android app: live overlay, session history, drill library, coach feedback. Direction C's bento dashboard scales naturally here.
4. **Mavio Method · drill library** — a content-driven site section showing the actual drills (Forehand DTL Power, BH Topspin Build, Serve Targets, etc.) with video demos. Like Strava's segments page meets Peloton's class library.
5. **For coaches & clubs** — separate landing for the B2B angle (junior tennis academies, club pros, college programs) showing how Mavio fits into a multi-court training program.

---

## Production Notes

To build this into a real production site, use Claude Code (Opus, high effort) with **HANDOFF MODE**.

Recommended stack:
- **Next.js 15 (App Router)** + Tailwind CSS + shadcn/ui — matches the 21st.dev component library, supports OG image generation via `next/og`, easy Vercel deploy, fast iteration
- **Sanity** or **Notion-as-CMS** for editorial content (founder updates, blog posts, drill library) — Sophie can publish without engineering
- **Cloudinary** or **Vercel Image Optimization** for photo handling, responsive sizes, automatic WebP conversion — important once real shoot footage replaces the AI placeholders
- **Plausible** or **Vercel Analytics** for privacy-first traffic data (no cookies banner needed)
- **ConvertKit** or **Loops** for waitlist + Kickstarter pre-launch email capture, replacing the current `/survey` flow
- **Polar.sh** or **Stripe** for any pre-order or paid beta access

Budget estimate for production rebuild of one direction: 2–3 weeks for design refinement + build + Sanity content model + analytics + deploy. Photography shoot adds 1 week (booking, shoot day, edit, color grade). Add 1 week for Kickstarter campaign-page integration once Sophie has the campaign assets ready.

---

## Build Timing
| Phase | Duration |
|---|---|
| READ + research (mavio.ai + Sophie context + competitors) | ~6 min |
| DIRECTION (Pro-Max skill + 6 21st.dev Inspiration searches) | ~3 min |
| IMAGE GENERATION (30 Grok 2K) | ~12 min |
| LOGO GENERATION (4 NB Pro 2K, with iteration) | ~8 min |
| Selection page + lobby v1 | ~5 min |
| Logos page (3 iterations: v1 SVG → v2 SVG refined → v3 NB Pro renders → v3 SVG strip + Echo dual-display) | ~14 min |
| BUILD 3 directions + selector index | ~16 min |
| VERIFY + ACCURACY + BRIEF | ~5 min |
| **Total: prompt to live mockup** | **~70 min, asynchronous across multiple turns** |
