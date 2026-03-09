# Axiom Landing/Brand Guardrail Skill

## Purpose
Use this skill whenever editing Axiom marketing pages, landing copy, or UI structure. It preserves brand consistency and decision quality across future agent sessions.

## Always Apply
1. Keep the visual direction dark, minimal, and premium with restrained green/teal glow accents.
2. Maintain conversion-first layout order: Hero -> Trust/Positioning -> Process -> Services -> CTA.
3. Keep copy concrete and operational; avoid vague hype and generic AI wording.
4. Prefer reusable UI patterns and consistent spacing/radius/shadow tokens.
5. Validate mobile readability and interaction targets before finalizing.

## Content Rules
- Headlines must communicate business outcome, not only technology.
- Subtext should explain what is automated and the practical benefit.
- Process steps must stay actionable and sequential.
- Services should map to user pains (response time, call handling, scheduling).

## Design Rules
- Base palette: near-black + emerald/teal glow + high-contrast text.
- Motion should be subtle and purposeful (hover, pulse, state).
- Glassmorphism should support hierarchy, not reduce clarity.
- Keep visual density balanced; do not overcrowd card content.

## Engineering Rules
- In Astro projects, favor componentization for repeated sections.
- In Tailwind projects, use utility classes for layout/spacing and keep custom CSS for unique effects.
- Keep docs in sync when structural decisions change.

## Reference Docs
- `docs/design-principles.md`
- `docs/considerations.md`
- `docs/idea-concept.md`

## Completion Checklist
- Brand tone aligned with outcome-driven automation positioning.
- CTA prominence preserved on all breakpoints.
- No section breaks conversion flow.
- Any new UI pattern is reusable and documented.
