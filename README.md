# Cafe de Binyang

A responsive showcase website for Cafe de Binyang. It highlights the cafe, menu photography, atmosphere, location, opening hours, and social links.

## Pages

- `index.html` - Customer-facing cafe showcase
- `admin.html` - Staff promo manager
- `style.css` - Shared website and admin styling
- `img/` - Cafe images and logo assets

## Run locally

Open `index.html` in a browser to view the customer website.

Open `admin.html` to create, preview, publish, or remove a promo.

## Promo behavior

The admin page stores the active promo in the browser's `localStorage`. The promo remains after a page reload in the same browser and can be removed from the admin page.

This is a frontend-only demo. It does not yet use a shared online database, so promos are not synchronized across different browsers or devices. For production use, connect the admin page and customer site to a backend such as Firebase or Supabase.

## Links

The customer page includes links for:

- Google Maps: Cafe de Binyang, Binan, Laguna
- Instagram: `cafe.debinyang`
- Facebook: Cafe de Binyang page
