# Open Canvas — responsive artist collective website

This is a static, responsive website starter with:
- A landing page with a photographic background
- An About page with a photographic background
- 40 individual artist pages (`artists/artist-01.html` through `artist-40.html`)
- A portrait, biography area, three artwork cards, prices, and purchase enquiry links on every artist page
- Responsive CSS for mobile, tablet and desktop

## Publish for free
**Netlify Drop (easiest):** sign up at https://app.netlify.com/drop and drag the unzipped `artist_collective_site` folder into the page. Netlify will publish a public URL. A custom domain costs extra; the provided Netlify subdomain is free.

**GitHub Pages:** create a repository, upload the contents of this folder, then enable Pages in the repository settings. It can serve static HTML/CSS for free on eligible public repositories.

## Important: replace demo content before launch
- Replace the generic artist names, placeholder portraits, artwork images, bios, titles, prices and contact email with approved real information.
- The image URLs are remote Unsplash demo images. Download/licence suitable images and store them in `assets/` for a more reliable production site.
- Change `Open Canvas` to your brand name in the HTML.
- Update SEO titles and descriptions, privacy/cookie notices as appropriate, accessibility alt text, and contact details.

## Online payments
This package does **not** collect card details or process payments by itself. Static hosting is free, but a payment provider charges transaction fees and needs a seller account. To take orders:
1. Create a Stripe account and create a Payment Link for each artwork (or use PayPal checkout links).
2. Replace each `mailto:` purchase link in the artist HTML with that artwork's hosted checkout URL.
3. Confirm whether shipping, tax, limited editions, inventory, refunds and artist payouts need to be handled.
4. Test a complete purchase before promoting the site.

For a multi-item cart, stock management, artist commissions/payouts and order administration, use a hosted commerce platform or a backend integration; this starter deliberately avoids pretending those features work before credentials and business rules are configured.
