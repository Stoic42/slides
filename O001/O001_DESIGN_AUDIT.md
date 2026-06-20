# O001 Slides Design Audit

Scope: L01-L12 formal lesson decks, 116 slides total.

## Shared Rules

- SheNicest pink is the brand accent; lesson colors are secondary signals only.
- Every deck needs a branded cover, consistent content chrome, and a branded closing page.
- Every lesson should contain at least one `CASE`, one `DEMO` or evidence page, and one `PRACTICE`.
- Prefer real product evidence or classroom-redrawn UI over decorative illustration.
- One slide should communicate one teaching action.
- Page counts, course codes, duration, and price formatting must be consistent.

## Deck Review

| Deck | Current issue | Required visual evidence | Priority |
| --- | --- | --- | --- |
| L01 Deployment | Tool steps were too abstract | Vercel import, deploy, success URL | High |
| L02 Styling | Teaches visual quality without showing before/after UI | One interface before and after CRAP changes | High |
| L03 PRD | Strong concepts, weak document reality | Annotated PRD and user-flow artifact | Medium |
| L04 Debug | No real error surface | DevTools error, console trace, corrected result | High |
| L05 API | Code-heavy and abstract | API docs, request, JSON response, rendered output | High |
| L06 Vibe | Metaphors dominate | Human/AI responsibility board and generated artifact | Medium |
| L07 Prompt | Good first mock product screen | Add prompt iteration and output comparison | Medium |
| L08 Product | Cases remain text-only | Product screenshots and pain-point evidence | High |
| L09 Pitch | Good pitch board | Add product proof and audience-response evidence | Medium |
| L10 Edge Cases | Important cases lack visible evidence | Accessibility and inclusive-design comparisons | High |
| L11 Collaboration | GitHub is explained without GitHub UI | Pull request, review comment, merge state | High |
| L12 Commercialization | Separate visual system, M001 residue, emoji-heavy | Pricing, checkout, first-order and validation funnel | Critical |

## QA Findings

- L06 duplicated `07 / 09`; page 6 must be `06 / 09`.
- L09 contains 7 slides but labels use `/ 08`.
- L10 contains 8 slides but labels use `/ 09`.
- L12 still contains `M001`, has no standard O001 chrome, and is visually disconnected.
- Brand presence varies from every page to cover-only.
- No deck currently contains an actual bitmap screenshot.
- Google Fonts are referenced externally even though local Chaohua fonts exist.
