# AI Interior Professional Prototype

## Included
- Responsive English/Urdu front-end concept
- Furniture categories and adjustable dimensions
- CSS-based rotatable concept preview (demonstration only, not production-grade CAD)
- Indicative cost calculator
- Material catalogue with price ranges, units, source links and status labels
- No build step required for static hosting

## Deploy
Upload the contents of this folder to a GitHub repository and connect it to Netlify. Publish directory: `.`. Build command: none.

## Important before launch
- Rates in `materials.json` are research-based indicative planning ranges, not guaranteed current Karachi supplier quotes. The page labels them as estimates and includes source links.
- `edgeBand` is explicitly a temporary estimate because no sufficiently reliable comparable public price was found.
- Images/video: this starter uses lightweight material swatches and supplier/source links rather than copying third-party product photos. Add supplier-authorized images or your own images and short clips to `assets/` before public launch.
- There is NO secure cloud admin panel/database in this static prototype. A real multi-user admin panel requires authentication + database (e.g. Supabase) and server-side validation. Do not store passwords or secrets in front-end code.
- Do not present the estimate as a final quote until sheet yield/cutlist, thickness, wastage, hardware specs, labour, delivery and Karachi supplier prices have been verified.


## Multi-brand selection
The material section includes a brand selector (ZRK, other Pakistani brand, imported brand, customer-specified brand, or customer-supplied material) plus a custom brand-name field. The chosen brand appears in the material detail and copied estimate. This is a prototype selector only: it does not verify supplier stock or automatically fetch brand-specific pricing; enter/confirm the exact brand, series, thickness and Karachi supplier quote before customer quotation.
