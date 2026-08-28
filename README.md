# skoolHarbor Landing Page

Marketing site for **skoolHarbor** (store name: *skool Harbor: Downloader For Skool*), a Chrome and
Firefox extension that detects the video on a Skool, Vimeo, Loom or Wistia page and saves it as a
single MP4.

Static HTML/CSS, no build step or dependencies — open `index.html`, or serve the folder with any
static host (e.g. GitHub Pages).

## Pages

- `index.html` — home (features, how it works, pricing, FAQ, terms)
- `guide.html` — usage walkthrough + troubleshooting
- `releases.html` — what's shipped (v1.3.0) and the roadmap
- `privacy.html` — privacy policy
- `refund.html` — refund policy
- `404.html` — GitHub Pages custom not-found page

## SEO plumbing

`sitemap.xml`, `robots.txt`, `llms.txt`, per-page canonical + Open Graph + Twitter tags,
`assets/og.png` social image, and JSON-LD (`SoftwareApplication`, `FAQPage`, `HowTo`,
`BreadcrumbList`).

## Pricing

Free trial (first 3 downloads), then Monthly $7.99, Yearly $69.99, Lifetime $199 (one-time).
Billing via ExtensionPay (Stripe); AppSumo codes redeem in the extension popup.

## Publishing with GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
Live at <https://leksautomate.github.io/skoolharbor-landing/>.
