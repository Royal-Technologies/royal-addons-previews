# Royal Addons Previews

Preview thumbnails (`600x375` WebP) for **Royal Addons for Elementor** widgets, layout builder widgets, and extensions.

## Directory Structure

- `widgets/` — 182 Free & Pro Widgets (`<slug>.webp`)
- `layout/` — 59 WooCommerce & Single Post Layout Widgets (`<slug>.webp`)
- `extensions/` — 27 Free & Pro Extensions (`<slug>.webp`)
- `manifest.json` — Complete catalog index (268 entries)

## CDN Usage

Serve via jsDelivr:

```text
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/widgets/<slug>.webp
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/layout/<slug>.webp
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/extensions/<slug>.webp
```

To replace any generated preview with a live screenshot, overwrite the matching `.webp` file in the appropriate directory keeping the same lowercase slug filename.
