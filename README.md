# El Sherif Supplies — الشريف للتوريدات الفندقية

Website for El Sherif Supplies, hospitality supplies for hotels, restaurants and cafés in Egypt since 2004.

**Live site:** https://philoelgen771-lgtm.github.io/purifex-1/

## What the site does
- Arabic / English catalog of 378 items in 6 categories (data from Supabase).
- **No prices are shown.** Customers build a request list and send a **quote request**; the sales team replies with prices.
- Contact form for custom quotes (saved as leads).
- Branches: Cairo head office (Gesr El Suez), Downtown Cairo, Sharm El Sheikh, Hurghada, Marsa Alam — plus our own factories.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole public website (single page, Arabic first, English toggle) |
| `admin.html` | Staff page to see quote requests and leads and edit products (login required) |
| `products.html` | Short link that redirects to the catalog section |
| `404.html` | "Page not found" page |
| `el-sherif-logo-nav.webp` | Full crest logo (black outline) used in the top bar |
| `el-sherif-logo*.webp`, `el-sherif-crest*.webp` | Other logo sizes / versions |
| `bg-office-navy.jpg`, `bg-warehouse-navy.jpg`, `bg-fleet-navy.jpg` | Navy illustrations used as section backgrounds |
| `favicon*`, `og-image.jpg` | Browser icon and social-sharing image |
| `robots.txt`, `sitemap.xml` | Search-engine files |

## Backend
Supabase project `dsyupeuejmeehjrpvvaw` — tables `products`, `orders` (quote requests, `payment_method = 'quote'`), `leads`.
The public key in the page is the publishable (anon) key; row-level security only lets visitors read active products and add new requests.

## Contact
Phone / WhatsApp 01227342967 · Elsherifsupply@yahoo.com
