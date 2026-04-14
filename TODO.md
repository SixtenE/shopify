# SEO Fixes - Post-Deploy Todos

## Shopify Admin: Footer Schema Settings

Fill in the new "Local business schema (SEO)" fields in the Footer section of the theme editor.

- [ ] Street address
- [ ] City
- [ ] Postal code
- [ ] Phone number (E.164 format, e.g. `+46701234567`)
- [ ] Email address
- [ ] Latitude / Longitude (defaults to central Gothenburg, update to exact gallery location)

### Opening Hours (Schema)

Use English day names and 24h time format. Each row needs day(s), opens, and closes.

- [ ] Row 1 — e.g. `Thursday, Friday` / `12:00` / `18:00`
- [ ] Row 2 — e.g. `Saturday, Sunday` / `12:00` / `16:00`
- [ ] Add more rows as needed

## Validation

After deploying the theme:

- [ ] Test product page with [Google Rich Results Test](https://search.google.com/test/rich-results)
- [ ] Test collection page with Rich Results Test
- [ ] Test article page with Rich Results Test
- [ ] Test homepage with Rich Results Test
- [ ] Run OG image through [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/)
- [ ] Inspect product page source — confirm only one `<h1>` tag
- [ ] Verify breadcrumbs display correctly on product, collection, article, blog, and page templates
- [ ] Check structured data with [Schema.org Validator](https://validator.schema.org/)

## Content Recommendations

- [ ] Update homepage banner heading from "Browse our latest products" to something keyword-rich (e.g. "Contemporary Graffiti Art & Street Art Prints")
- [ ] Verify footer business name/address matches Google Business Profile (NAP consistency)
- [ ] Ensure blog articles have author bylines enabled
