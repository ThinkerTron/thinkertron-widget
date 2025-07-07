# Official ThinkerTron Widget

**ThinkerTron requires an active paid subscription from [ThinkerTron.com](https://www.thinkertron.com)**

The ThinkerTron JavaScript widget is a compact (\~6KB gzipped) client-side module engineered for maximum compatibility and strict isolation. It is implemented as a self-invoking function (IIFE), encapsulating all logic and variables to avoid any leakage into the global namespace. This ensures that ThinkerTron does not interfere with existing JavaScript variables, functions, or DOM elements on your site.

All DOM elements created by ThinkerTron are uniquely prefixed to avoid collisions. It has no external dependencies and is written entirely in vanilla JavaScript. To mitigate XSS risks all user-generated content is fully sanitized server-side and inserted using `textContent` on the client.

The widget mounts itself dynamically to the document body and renders independently, maintaining full compatibility with modern CMS platforms and frontend architectures—including static sites, server-rendered apps, and SPAs.

In short, `thinkertron.js` is safe to drop in, robustly sandboxed, and deliberately non-intrusive by design.

**Versions are planned, but for now, please use the latest release:**

```
<script 
    src="https://cdn.jsdelivr.net/gh/ThinkerTron/thinkertron-widget@master/thinkertron.min.js" defer>
</script>
```

Full documentation can be found on the [ThinkerTron.com](https://www.thinkertron.com/docs) website.

---
