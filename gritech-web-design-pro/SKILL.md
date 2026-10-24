---
name: gritech-web-design-pro
description: Create, redesign and audit professional websites with premium visual design, responsive UX, practical SEO, accessibility, real dynamic functionality, security and quality assurance. Use for landing pages, business sites, e-commerce, SaaS and web applications.
---
# GRITECH WEB DESIGN PRO — Public Skill V2

A reusable agent skill for professional website creation. This is a **set of instructions**, not a prebuilt website, full-stack framework or production-ready deployment system.

## Activation
Use this skill when asked to design, build, redesign, audit or prepare a website for launch. Respect the user's selected technology, hosting, brand and language.

## Execution workflow
1. **Director / Product lead**: translate the request into an actionable brief: audience, business goal, sitemap, calls to action, content, constraints, scope, assumptions and acceptance criteria. Avoid unnecessary questions; note unresolved items.
2. **Designer / UX**: define premium but appropriate visual direction, a consistent token-based design system, responsive layouts, interaction states, readable typography, accessibility and meaningful micro-interactions. Avoid generic template aesthetics when the brief calls for a distinctive brand.
3. **Architect**: choose the minimum viable stack that matches hosting (e.g. static/PHP on compatible shared hosting; Node/containers only where actually supported). Define data models, API boundaries, routing and dependencies when needed.
4. **Developer**: create real source files in the available workspace. Dynamic features need a real backend, database or documented third-party integration. Never simulate live bookings, payment or email delivery as if connected.
5. **SEO**: create informative page titles and descriptions, semantic headings, canonical URLs where appropriate, robots.txt and sitemap for the real deployment URL, meaningful internal links, localized content, and verifiable structured data. Do not claim guaranteed ranking.
6. **Security / Privacy**: validate input server-side, protect secrets, apply least privilege, handle authentication/authorization, consider CSRF/XSS/SQL injection, protect personal data, document cookie and privacy requirements relevant to the deployment.
7. **QA / Release**: verify build, navigation, mobile layout, keyboard accessibility, form validation, error states, links and SEO metadata. Run available tests; identify what was not tested. Require user approval before any production deployment.

## Required principles
- Distinguish **concept**, **prototype**, **tested build**, and **deployed production site**.
- Never fabricate clients, testimonials, metrics, reviews, certifications, prices or API results.
- Prefer accessible semantic HTML, visible focus states, useful alt text, good contrast and reduced-motion support.
- Target Core Web Vitals (LCP ≤ 2.5s, INP ≤ 200ms, CLS ≤ 0.1), measured with real tools where available; do not report invented scores.
- Avoid exposed credentials, personal data, paid actions, emails or production edits without authorization.
- If external tools or local execution are unavailable, supply files or clear instructions and describe the limitation.
- Do not assume a contact form, payment, booking, CRM or e-commerce integration works without end-to-end evidence.

## Deliverable
Provide: (1) summary and assumptions; (2) design approach; (3) architecture; (4) actual code/files available; (5) SEO implementation; (6) test evidence and untested items; (7) deploy instructions with rollback and remaining configuration.

## Optional seven-role review
For major projects, internally review as: director, designer, architect, developer, SEO specialist, security reviewer and QA tester. These are **roles**, not seven independent running processes unless an actual orchestrator is configured.

## Integration with Claude Code
Place this file at `~/.claude/skills/gritech-web-design-pro/SKILL.md`. Claude Code can use the skill instructions during website tasks. This public Skill alone does **not** install Ollama, n8n, Python scripts or autonomous code-generation agents.

## Attribution
GRITECH WEB DESIGN PRO — team_gritechcreator.
