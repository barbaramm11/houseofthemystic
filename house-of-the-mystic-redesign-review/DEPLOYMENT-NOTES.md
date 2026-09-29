# House of the Mystic — review package

This is a locally previewable static website package. It is not published. Extract the ZIP before opening index.html.

## Current payment and scheduling
All eight services link to their respective Cal.com booking pages through Book & pay buttons. Public booking pages showed the specified durations and prices on September 27, 2026; selecting a slot on each revealed a Pay to book button. No card was charged, so successful Stripe capture, receipt, and booking confirmation are still untested. The standalone Stripe Payment Links supplied by Barbara are recorded in build_site.py but are not exposed to visitors: both links together could result in two payments. Confirm Cal.com confirmation messages direct clients to the correct intake form. Zodiacal Releasing and 13th Octave LaHoChi are the only Coming soon cards and have no purchase or booking links.

## Search and responsive layout
The build has page-specific titles and descriptions, canonical URLs including the homepage, a robots.txt and sitemap.xml, semantic headings, English/Spanish hreflang pairs, five new guides, and noindex directives on intake and thank-you pages. Search terms and Google Trends context are in SEARCH-STRATEGY.md. Check the deployed domain and use Search Console to validate indexing after publishing. The original supplied logo is an opaque RGB with a baked-in checkerboard around the circle; CSS clips this fringe on the website, but a true transparent source would be preferable for use outside the site. The smaller hero and image respond at tablet and phone widths.

## Before publishing
- Configure and test Netlify Forms and email notifications for English and Spanish contact/intake forms; file:// previews cannot submit.
- Confirm the selected logo, prices, session languages, professional background, cancellation and privacy language, and live social links.
- Review redirects against the current live site. Keep upcoming offers closed until ready to deliver.
- Cal.com booking screens and the policy page remain in English. Spanish session pages ask clients to specify Spanish in booking notes. Review the Spanish wording and bilingual intake flow before launch.
