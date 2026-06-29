# AI Working Session — Landing Page

Single-file sales page for **The 4-Hour AI Working Session** ($250, done-with-you AI automation). Hormozi-style structure (offer, value stack, guarantee, scarcity, one CTA), André's clean voice, brand palette, inline SVG illustrations. Mobile-responsive.

**Model:** the page sells a **free 15-minute call**, not the paid session directly. You close the $250 on the call. Lower friction and more trust for a cold-ish newsletter audience.

## Before you publish (3 things)

1. **Booking link.** Set to the free-call page on all CTAs: `https://calendar.app.google/b5LfiKt2GxHvTqr4A`. Update here if it ever changes.
2. **Guarantee.** The page uses a "no result, no pay" guarantee on the paid session (Hormozi-style risk reversal). Keep it only if you're comfortable honouring it. If not, soften the guarantee section.
3. **Social proof.** There is a commented-out testimonials block. Add 2-3 **real** quotes once you have them. Do not invent any.

## Deploy on GitHub Pages

1. Create a repo (e.g. `ai-working-session`) and add this `index.html` to the root.
2. Repo → Settings → Pages → Source: `main` branch, `/root`.
3. Your page goes live at `https://<username>.github.io/ai-working-session/`.
4. Optional: point a custom domain in the same Pages settings.

That's it. No build step, no dependencies.
