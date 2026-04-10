# Solid Digital — Website Architecture Project Context

## Background
Solid Digital is a 19-year-old web design and development agency (team of 6) repositioning from B2B web/marketing to an AI transformation partner for mid-market companies. This file contains the full context from our strategy and architecture discussions.

## Team
- **Jesse McCabe** — Creative Director (you're working with Derek, the other owner)
- **Derek Lauritzen** — Co-owner, developer background
- **Travis McHattie** — Lead developer/engineer
- **Diana Martinez** — Account/project manager
- **Mara (Marla Aistrope)** — Digital marketing strategist
- **Peter Ajtai** — Developer

## Key Strategic Decisions (from multiple leadership meetings)

### Brand → Innovation Framework (Unanimously Endorsed)
The customer journey has 4 stages:
1. **Brand** — Identity, web presence, foundational marketing
2. **Performance** — SEO/GEO, PPC, software that works, measurable outcomes
3. **Integration** — Custom software, AI tools, connected systems, compliance
4. **Innovation** — AI transformation, new capability creation, competitive leadership

### Positioning
- Moving away from B2B SaaS as primary ICP
- Target: mid-market companies ($5M–$100M revenue, 20–500 employees)
- Buyer is CEO/COO/founder, NOT marketing directors
- Lead with pain points, not capabilities
- "Implemented right" is the core differentiator — knowing when to use AI and when not to
- Human-first approach is unanimous across the team

### 4 Messaging Pillars (Intent)
1. **Strategy** — Helping through the mess, building pipeline, showing ongoing value
2. **We build what you always wanted** — Custom solutions that were out of reach
3. **Human first, expertise-driven implementation** — Maximizing efficiency with AI
4. **Warm blanket** — Support, ongoing value, partnership, protection

### Products vs Services (Critical Distinction)
Travis was emphatic: there are things you do FOR people (services) and things you give TO people (products). Products need their own home separate from services.
- **Products:** Path Pilot (analytics), Sites (static site builder), The Hub (client collaboration platform), AI Readiness Assessment
- **Services:** AI Transformation, Software & Integration, Web & Digital Presence, Marketing & Performance, Support & Protection

### Three Client Tiers
1. **Transactional** — Defined scope, single practice, price-sensitive
2. **Mid-Level** — Project + retainer, 2-3 practices, recurring relationship
3. **Full-Service** — Strategic partner, all practices, CEO/CTO level engagement

### What the Team Does NOT Want
- "Full spectrum" language (too vague)
- "Software craftsmanship" (sounds outdated)
- Flourish words — keep it tactical and value-centric
- Leading with "AI" as the headline — lead with pain points instead
- Replacing client systems (entry point should be "we work with what you have")
- Innovation = generating marketing ideas (it's technical/operational, not Don Draper)
- A team page (use "Our Story" instead)
- Careers page
- Client Roundtables (not ready yet)

## Website Architecture

### Navigation Pattern (All Options)
Inspired by directiveconsulting.com — focused primary nav (3-4 items) + hamburger menu for secondary content + persistent CTA(s).

### The 4 Architecture Options

#### Option A: "The Balanced Authority"
**Primary Nav:** Services ▾ · Products ▾ · Methodology + ☰ hamburger
**CTAs:** See Our Work + Start a Project (dual)
**Hamburger:** Resources (AI Labs, Case Studies, Blog, Research) · Frameworks (Brand → Innovation Journey, How We Work, AI Readiness Assessment) · Company (About Us, Our Story, Awards, Client Portal)

#### Option B: "The Proof-First Launch"
**Primary Nav:** What We Do ▾ · Our Tech ▾ · AI Lab · Work + ☰ hamburger
**CTA:** Start a Project (single)
**Hamburger:** Resources (Blog, Research) · Learn More (Our Approach, Brand → Innovation Journey, How We Work, AI Readiness Assessment) · Company (About Us, Our Story, Awards)
**Note:** "What We Do" has a mega-dropdown with journey stages + "Not sure where to start?" CTA

#### Option C: "The Full Picture"
**Primary Nav:** What We Do ▾ · How We Work · Platforms ▾ · Work + ☰ hamburger
**CTA:** Start a Project (single)
**Hamburger:** Resources (AI Labs, Blog, Research) · Learn More (Brand → Innovation Journey, AI Readiness Assessment, FAQ) · Company (About Us, Our Story, Awards)

#### Option D: "The Conversion Engine"
**Primary Nav:** Services ▾ · Industries ▾ · Products ▾ · Our Approach + ☰ hamburger
**CTAs:** See Our Work + Start a Project (dual)
**Industries dropdown:** Manufacturing & Industrial, Professional Services, Healthcare & Life Sciences, Financial Services, Associations & Nonprofits, B2B E-Commerce & Distribution, Real Estate & Property Management, Education & Higher Ed
**Hamburger:** Frameworks (How We Work, Brand → Innovation Journey, AI Readiness Assessment) · Resources (Blog, Research) · Company (About Us, Our Story, Awards, Client Portal)

### How We Work Page Content
- 3 client tiers explained
- Engagement process: Discovery → Strategy → Build → Support
- Brand → Innovation framework
- 4 pillars / our approach

## Design Tokens (from soliddigital.com/ai-lab)
- **Background:** #080F1A (dark navy)
- **Surface:** #0F1D30, #142438
- **SD Red:** #E41E26 (buttons/CTAs)
- **SD Blue:** #50BAEE / #5EC4F5 (accents, links)
- **SD Teal:** #5FD9D0
- **SD Gold:** #E0B84E
- **Fonts:** adobe-caslon-pro (serif headlines), neuzeit-grotesk (sans body) — using Source Serif 4 + Source Sans 3 as Google Font alternatives
- **Body text:** rgba(255,255,255,0.78) on dark backgrounds
- **All text passes WCAG AA contrast ratios**

## File Structure
- `index.html` — The interactive architecture presentation with all 4 options, hover dropdowns, clickable hamburger menus, wireframe hero sections, and sitemap breakdowns
- Hosted via GitHub Pages at: https://dereklauritzen.github.io/solid-website-architecture/

## What's Next
- Team needs to review and pick a direction (or hybrid)
- Then: wireframe the actual homepage, build out page templates
- Enable GitHub Pages (Settings → Pages → Source: main → Save)
