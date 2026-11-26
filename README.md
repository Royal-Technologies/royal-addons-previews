# Royal Addons Previews

Preview thumbnails for **Royal Addons for Elementor** widgets, layout builder widgets, extensions, and template library items.

## Directory Structure

- `widgets/` — 186 Free & Pro Widgets (`<slug>.webp`, `600x375`)
- `layout/` — 59 WooCommerce & Single Post Layout Widgets (`<slug>.webp`, `600x375`)
- `extensions/` — 27 Free & Pro Extensions (`<slug>.webp`, `600x375`)
- `templates/free/` — 9 Free Elementor Templates (`<id>.jpg`)
- `templates/pro/` — 60 Pro Elementor Templates & Sections (`<id>.jpg`)
- `manifest.json` — Complete catalog & template preview index

## CDN Usage

Serve via jsDelivr:

```text
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/widgets/<slug>.webp
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/layout/<slug>.webp
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/extensions/<slug>.webp
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/templates/free/<id>.jpg
https://cdn.jsdelivr.net/gh/Royal-Technologies/royal-addons-previews@main/templates/pro/<id>.jpg
```

To replace any generated preview with a live screenshot, overwrite the matching file in the appropriate directory keeping the same lowercase filename.
