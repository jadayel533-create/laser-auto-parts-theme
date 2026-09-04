# Laser Auto Parts — Zid Vitrin Theme

Custom RTL-first storefront theme for Laser Auto Parts, built on Zid Vitrin.

## Development status

Development checkpoint: core storefront, homepage sections, product details, cart, responsive styling, Arabic locale support, region/language dialog, store messages, and current Zid payment/checkout integrations are implemented in the repository.

**Live activation is intentionally not performed by this repository workflow.**

## Compatibility work included

- Vitrin base layout with `vitrin_head` and `vitrin_body`
- RTL-first Arabic storefront presentation
- Optimized `image_url` usage for storefront imagery
- Configurable homepage sections and section heading macro
- Product cards with sale pricing and badges
- Product details route with variants, custom inputs, grouped products, bank discounts, payment widgets, loyalty points, Apple Pay quick checkout, and metafields
- Cart route with products list, bank discounts, progressive discounts, customer wallet progress, gift cards, payment widgets, Apple Pay quick checkout, and checkout action
- Region/language modal and store messages integration
- Arabic translations for theme-owned UI strings
- Responsive product and cart layouts

## Structure

- `layout.jinja` — global storefront shell
- `layout.schema.json` — merchant-editable global settings
- `header.jinja` / `footer.jinja` — shared chrome
- `templates/` — route templates
- `sections/` — configurable homepage sections
- `components/` — reusable theme components
- `assets/` — CSS/JS source
- `locale/` — translations
- `preview/` — static visual development preview

The architecture follows Zid's current Vitrin documentation and reference themes.
