# Prompt: One-Page Credibility Site for Expert Advisory Service

## Context & Business Model

I run a curated expert advisory service for biotech, pharma, and healthtech founders and teams. I arrange paid one-on-one expert calls for people making decisions around licensing, valuations, commercial strategy, business development, and market/partnership decisions.

My name is Jabir Nur. My service operates as PartnerBridge Advisory. I do not have a registered company — this is a solo advisory service under my own name.

**How the business works:** This is a hands-on service business. I personally scope each engagement, identify the right expert, brief them, and manage the call. It is not a marketplace, not a SaaS platform, and not a self-serve directory.

**Traffic context:** My primary source of introductions is Boardy AI (warm intros). This website exists for credibility and trust — people who've already been introduced to me will visit it to understand what I do and decide whether to engage. This is not designed for cold traffic, SEO, or broad lead generation.

---

## What I Want Built

A single-page static website. Production-ready, deployable, fully responsive.

---

## Design Direction

**The site should feel like:** a private, high-trust advisory firm — closer to a boutique consultancy or private banking site than a startup landing page or SaaS product.

**Tone keywords:** calm, clear, curated, professional, minimal, private, confident.

**It should NOT feel like:** a marketplace, a SaaS landing page, a corporate enterprise site, a flashy startup, or an open expert directory.

**Visual direction:**
- Light, warm palette — off-white or cream background with dark text (charcoal or near-black). One muted accent color for CTAs and subtle highlights (e.g., a muted teal, warm terracotta, or deep olive — not bright blue, not purple). No bright gradients. No purple-on-white. No stark white (#fff) backgrounds — use a warm off-white or light cream instead.
- Typography should feel editorial and refined — not techy, not playful. Pair a distinctive serif or elegant sans-serif heading font with a clean body font. Do not use Inter, Roboto, or system defaults.
- Generous whitespace. Let content breathe. No dense grids, no card overload.
- Motion: gentle fade-in on scroll for each section (opacity 0→1, slight upward shift). Keep the hero static and immediately readable — no staggered text reveal. No bouncing elements, no parallax, no animated counters. Button hover: subtle color shift only, no scale or bounce.
- No stock photography, no abstract illustrations, no decorative icons. If imagery is used, it should be minimal and purposeful (e.g., a simple line or divider).

---

## Page Sections (in order)

### 1. Hero
- Clear, direct headline — not clever, not hypey. State what the service is.
- Short subheadline (1–2 sentences) explaining who it's for and the core value.
- Primary CTA button: "Request a Call"
- Secondary text link: "See How It Works" (smooth scroll to that section)

### 2. What This Is
- 2–3 short paragraphs or a concise block explaining the service.
- Emphasize: this is a curated, managed service. I do the matchmaking and scoping. Clients get focused, experience-based insight from a relevant expert in one efficient call.

### 3. Who It's For
- Biotech, pharma, and healthtech founders and leadership teams.
- Especially small and mid-sized companies navigating high-stakes decisions without large internal teams.
- Keep this tight — 3–5 bullet points max.

### 4. Areas of Focus
Present as a clean, scannable list (not a feature grid, not icon cards):
- Licensing & deal structuring
- Valuation & pricing strategy
- Commercial strategy & launch planning
- Business development & partnerships
- Market landscape & competitive positioning

### 5. How It Works
Three clear steps, presented simply (not as a flashy visual timeline):
1. **Share your question or decision** — Tell me what you're working through and what kind of expertise would help.
2. **I identify and brief the right expert** — I find someone with direct, relevant experience and prepare them on your context.
3. **You get a focused advisory call** — A structured, efficient call designed to give you actionable, experience-based insight.

### 6. The Approach (replaces "Trust / Compliance")
Frame this as a value proposition, not a legal disclaimer:
- Experts participate in a personal capacity, sharing experience-based (not confidential) insight.
- Every engagement is carefully scoped — I manage the process so you get signal, not noise.
- This is not a marketplace where you browse profiles. I do the curation so you don't have to.

### 7. Contact / Request a Call
This section should NOT contain an embedded form. Instead:
- A short line like: "Tell me about the decision you're working through, and I'll get back to you within one business day."
- A prominent CTA button: "Request a Call" — this links out to an external Google Form (URL: [GOOGLE_FORM_URL] — I will replace this with my real Google Form link).
- Below the button, show the email address partnerbridge7@gmail.com as a plain text alternative for people who prefer email.

### 8. Footer
- One line: "PartnerBridge Advisory — Curated expert advisory for life sciences and healthtech."
- Contact email: partnerbridge7@gmail.com
- No social links, no blog link, no sitemap, no newsletter signup.

---

## Content Rules

**Do not invent:**
- Testimonials, reviews, or endorsements
- Client logos or named clients
- Metrics, numbers, or case studies
- Expert names or profiles

**Do not use language like:**
- "Revolutionize," "cutting-edge," "unlock value," "world-class," "game-changing"
- "Trusted by leading companies" (unless real logos are provided)
- Any hype-driven or SaaS marketing language

**Voice & tone:**
- Direct, confident, understated
- Speaks like a knowledgeable person, not a marketing page
- Short sentences. No filler. Every line should earn its place.

---

## Technical Requirements

**Stack:** Single HTML file with Tailwind CSS (via CDN). No framework needed — this is a static one-pager with no routing, no SSR, no API calls.

**Hosting:** Vercel. The output should be deployable to Vercel as a static site. A single `index.html` file in the root is all that's needed — Vercel will serve it automatically. Do not scaffold a Next.js project for this.

**Requirements:**
- Fully mobile responsive — the CTA and form should be easily accessible on mobile since many visitors will open this from a phone after a warm intro.
- Semantic HTML
- Smooth scroll to sections from nav/CTA links
- No form on the page — the "Request a Call" CTA links out to an external Google Form. Use a placeholder URL (`https://forms.google.com/PLACEHOLDER`) that I will replace with my real form link.
- Include proper `<title>`, meta description, and Open Graph tags (og:title, og:description) so the link previews well when shared in messages. Use: "PartnerBridge Advisory — Curated Expert Advisory for Biotech, Pharma & Healthtech"
- Favicon: use a simple text-based favicon or a minimal monogram. Do not use a placeholder icon.

**Do NOT include:**
- Multiple pages or routing
- A database or backend
- Authentication or login
- Payment processing
- A CMS or admin panel
- A blog
- Client dashboards
- Expert profile directory
- Complex animation libraries
- Analytics tracking (can be added later)

---

## Done When

- I can open the file in a browser and everything works — nav links scroll smoothly, the "Request a Call" button links to the Google Form placeholder, the layout looks good on both desktop and mobile.
- The design feels like a boutique advisory firm, not a SaaS landing page or a generic template.
- No placeholder content anywhere — no "Lorem ipsum," no TODO comments, no "[insert here]" text (the Google Form URL placeholder is the one exception — I will replace it myself).
- A non-technical person visiting from a warm intro can understand what I do within 10 seconds of landing on the page.

---

## Deliverable

A single production-ready file (or minimal file set) that I can deploy immediately. Clean, well-structured code. No TODOs, no placeholder "Lorem ipsum," no commented-out sections.
