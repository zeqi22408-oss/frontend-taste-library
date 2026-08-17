---
name: frontend-taste-library
description: Build and reuse this user's persistent frontend design reference library. Use when the user shares a website and asks Codex to study, remember, collect, or add it to their design library; when the user approves or rejects a visual direction; or when Codex builds, redesigns, or visually polishes a website and should apply the user's saved frontend taste.
---

# Frontend Taste Library

Preserve useful design principles from websites the user selects, then apply only the references relevant to the current product, audience, and content.

## Learn a reference

1. Inspect the live page at desktop and mobile sizes when access permits. Stop at login, password, MFA, consent, or CAPTCHA boundaries that require the user.
2. Record the source URL, inspection date, page purpose, and observable patterns in `references/catalog.md`.
3. Separate observation from preference:
   - `observed`: studied but not confirmed as the user's taste.
   - `approved`: explicitly liked or accepted by the user.
   - `rejected`: explicitly disliked; retain the reason as a guardrail.
4. Analyze only reusable principles: information hierarchy, grid, type scale, spacing, color, imagery, components, interaction, motion, responsive behavior, accessibility, and performance.
5. Do not copy proprietary text, source code, branding, or assets. Preserve the design logic, not the website.
6. Update the catalog only when the user explicitly asks to learn, remember, save, approve, reject, or add the reference.

## Apply the library

1. Read `references/catalog.md` before choosing a visual direction for frontend work.
2. Filter references by product type, audience, content density, and interaction needs. Prefer approved references; use observed entries only as optional inspiration.
3. Select at most three compatible references. Do not mix unrelated styles into a collage.
4. Translate principles into project-native typography, tokens, layout, components, and motion. Reuse the project's existing design system when present.
5. Treat accessibility, responsive behavior, and performance as requirements even when a reference scores poorly in those areas.
6. Verify the implemented result with browser screenshots at relevant viewport sizes before claiming visual completion.

## Catalog maintenance

Keep entries concise and evidence-based. Add a new entry instead of rewriting historical observations. Update an entry's status and preference notes when the user provides feedback.

