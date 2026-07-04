# TODO / Open Items — Maid Nice San Diego rebuild

Items below need client confirmation or data that was not available on the live site
(https://maidnicesandiego.com/) or in the supplied asset folders.

## Content to confirm / provide
- **Email address** — not published on the client site. No email is currently shown on the
  rebuilt pages (phone-only). Provide a business email if one should be added.
- **Business address** — JSON-LD `PostalAddress` uses locality "Carlsbad, CA" only (no street
  address was available). Add a street address if the business wants full local SEO markup.
- **Google review count & rating** — the template shipped with "4.9★ / 100+ reviews". We do NOT
  have the real aggregate. All numbers were changed to reflect the **65 Google reviews**
  supplied in `/reviews` (rating shown as **4.9**, count **65**). Update `aggregateRating`,
  the announce bar, hero badge, marquee stats, and coverage-trust rows if the true Google
  totals differ.
- **BBB accreditation / Thumbtack** — template claimed "BBB A+ Accredited" and "Top-Rated on
  Thumbtack". Neither is confirmed for Maid Nice, so these were replaced with truthful
  "Fully Insured & Vetted" / "Same Cleaner Every Visit" wording. Restore specific badges only
  if the business actually holds them.
- **Video reviews** — the template had 4 YouTube video testimonials (competitor's). No client
  videos were provided, so the video row was removed. Add embeds if the client has videos.

## Assets
- **Logo** — using client `icons/logo.png` (225×225). A larger / transparent / wide version and
  a proper social-share (OG) image (1200×630) would improve link previews. OG tags currently
  point at the square logo.
- **Favicon** — using `icons/logo.png`. A dedicated `.ico`/multi-size favicon is recommended.
- **Photography** — `images/house-cleaning-service.jpeg` (generic stock) is retained as the page
  background. Swap for real Maid Nice job photos if available (several reviews mention
  before/after photos).

## Pricing
- Rates shown match the live site: Weekly $169 / Biweekly $189 / Monthly $218 per visit;
  deep & move-out are flat-rate/custom-quote. Confirm these are current.

## Deployment
- Repo is configured for `https://philderev.github.io/maidnicesandiego/`. Verify GitHub Pages
  is enabled for that repo/branch. (Not committed or pushed per instructions.)
