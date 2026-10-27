# RedlineMD landing page: design rationale

Redesign concept for the Foundey web designer assignment. These are design hypotheses based on the brief. None of them have been tested with real traffic.

## The problem

- 35% of traffic is mobile, but over 90% of revenue comes from desktop. The mobile journey is losing buyers.
- The current site lacks the polish needed to sell high-stakes legal technology to physicians.
- Traffic arrives from Google Ads, so the page has to confirm the search intent ("physician contract review") within a few seconds.

## Strategy

One page with one action. Every primary CTA goes to the same destination (redlinemd.ai), and the header has only two in-page links. The story moves from offer to risk to proof:

1. **Hero:** what it is, what it costs and what to do next.
2. **Contract risks:** why it matters, in physician-specific terms and dollar amounts.
3. **How it works:** a working demonstration of the product, followed by the final conversion block.

## Key UX and CRO decisions

**Message match and price visibility**
- The H1 and the eyebrow repeat the ad intent.
- The $199 vs $500+ comparison sits directly above the primary CTA. The price is part of the CTA label ("Review my contract — $199"), so there's no surprise at checkout.

**ROI narrative**
- A three-figure strip ($199 / $500+ / $10,000+) turns the cost-savings argument into something people can scan.
- The $10,000+ figure is qualified ("in some contracts", "depending on your policy") to avoid an unverifiable savings promise.

**Show the product**
- The sample report is interactive: choose a risk alert and see the redlined clause, why it matters and the suggested revision.
- This builds trust through evidence instead of testimonials or badges. None were invented.

**Lower upload friction**
- The final block includes an "Add your contract" drop zone, so committing feels like one small step.
- In this concept the file isn't transmitted. The production version should pass it to the existing checkout.

**Mobile-first fixes for the 35%**
- **Above the fold:** the H1, price, primary CTA and 24-hour reassurance all appear without excessive scrolling.
- **Sticky price bar:** a bar with $199 and "Review my contract" appears once the hero CTA scrolls away. It hides when the final pricing block is visible, so the two never duplicate.
- **Section shortcuts:** "How it works" and "Contract risks" sit under the header as large tap targets.
- **Sample report as a reader:** on mobile it shows one alert at a time, with chips and next/previous controls instead of a cramped three-pane view. The hero mockup also drops to the two most important clauses.
- **Tap targets and buttons:** all tap targets are at least 44px, and buttons never wrap to two lines.

## Visual decisions

**Brand**
- The original logo is kept. Its tagline was cropped because it contains a typo ("Reiew").
- Logo red (#D42A2F) is reserved for the CTA, risk annotations and the small "redline" rule before each eyebrow.

**Palette**
- Deep navy (#172B46) gives legal authority, soft blue-gray surfaces give clinical clarity, and a single warm accent keeps the page calm rather than alarming.

**Typography**
- Geist with tight tracking on headings, plus Geist Mono for clause numbers and interface labels, the way lawyers cite sections.
- Everything is in sentence case.

**Rhythm**
- Section backgrounds go light, then navy, then soft gray, so each step of the story feels distinct.
- Restrained radii (8–16px), hairline borders and one soft shadow depth.

**No decoration without function**
- No stock photos, 3D illustrations or gradients beyond a faint hero wash.

## Accessibility and SEO

- One H1, H2 per section and semantic `dl` / `ol` / `article` markup.
- Visible focus rings, reduced-motion support, and text contrast at WCAG AA or better.
- The page title, meta description and Open Graph tags follow the brief.

## Open items

- **Delivery time:** the PDF says "instant" redlining, but the approved copy says "within 24 hours". This needs confirmation.
- **Checkout and upload:** the real URL and upload hand-off still need to be wired.
- **Sample report content:** the clauses are illustrative. They should be replaced with a real sample report.
- **Proof of impact:** to validate the conversion uplift, A/B test the mobile sticky bar and the price-in-CTA label first.
