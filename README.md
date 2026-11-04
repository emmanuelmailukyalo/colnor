# Colnor — women’s suit store prototype

A standalone storefront prototype for Colnor’s women’s suit collection. This is a self-contained project folder, separate from the Clad and Shine storefront in `Project Recreate`. The Sumissura research notes are included here as `SUMISSURA-INVESTIGATION-NOTES.txt`.

## Preview

Open `index.html` for the landing page or `collection.html` for the suit collection. Open `admin.html` on the same origin for the local administration panel. For local navigation and browser storage, run a static server from this folder, for example:

```powershell
py -m http.server 8010
```

Then open `http://127.0.0.1:8010/`.

## Included

- Colnor branding, women’s suits navigation, full-viewport hero carousel, categories, product catalog, sticky shopping bar, and responsive layout.
- A 35-item sample catalog priced in KSh 6,500–12,000, with product detail pages, galleries, color swatches, sizes XS–XXL, and quantities.
- Local shopping bag, checkout preview with card/M-Pesa choices, and browser-local order records.
- An administration page for catalog management with short custom SKUs, opening stock by size, per-size inventory adjustments, received-stock records with notes, order status, homepage copy/images, contact messages, and JSON backup export.
- About, contact, and demo order lookup pages, plus working footer destinations.
- Suit campaign images downloaded to `assets/` for offline rendering. See `assets/SOURCES.txt` for source URLs and rights status. Most product-card imagery currently uses these sample suit photos; replace them with licensed, product-specific Colnor photography before launch.

Catalog edits, stock, homepage content, contact form submissions, orders, and the bag are saved only in this browser. The admin page has no authentication and is not a secure shared production back office. Email delivery, inventory, order fulfillment, card processing, and M-Pesa are not connected.

