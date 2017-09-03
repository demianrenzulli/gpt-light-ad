# Glade Ad Polymer Element
Web Component wrapper for Glade library code using Polymer.

# Usage

1. Load the Glade library at the header of your root page:

```html
<script src='https://securepubads.g.doubleclick.net/static/glade.js' async></script>
```

3. Import and use the gpt-ad element inside any Web Component:

```html
<link rel="import" href="glade-ad.html">
```
```html
<glade-ad ad-slot-id="ad_slot_example" data-ad-unit-path="ad_unit_path" width='XXX' height='YYY'></glade-ad>
```