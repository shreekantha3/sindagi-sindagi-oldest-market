# TEST REPORT — Sindagi Oldest Market
> Tester: Senior Engg | Segment: Market | Tier-4/5

## Build
- [ ] `npm run build` (pending)

## Static QA (generator asserts)
- Phone: MISSING → no tel: links by design | Maps embed (lazy iframe) + JSON-LD ShoppingCenter schema + H1 + title<=60
- No lorem ipsum, no invented hours/prices/ratings

## Build result (2026-09-15)
- [x] `npm run build` PASS (vite 5.4.21, 0 warnings)
- dist: index 12.65 kB / CSS 11.94 kB / JS 1.17 kB — under perf budget

## Static QA (2026-09-15, all PASS)
- [x] title<=60, Maps embed iframe, JSON-LD schema, H1, no lorem, phone/WhatsApp rules per CSV

## Verdict: BUILT + STATIC QA PASS → gh-pages branch deploy
