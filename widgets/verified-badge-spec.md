# USS.EU.COM Verified Business Badge Specification

Listed companies in the [USS.EU.COM US–EU Business Directory](https://uss.eu.com/all-listings/) can embed a zero-JavaScript, zero-tracker verification badge linking back to their public directory profile.

Customize colors and copy directly via [https://uss.eu.com/verified-badge/](https://uss.eu.com/verified-badge/).

## Minimal Static HTML Snippet

```html
<a href="https://uss.eu.com/business-directory/your-company-slug/" target="_blank" rel="noopener"
   style="display:inline-flex;align-items:center;gap:8px;padding:8px 14px;border-radius:8px;background:#0f172a;color:#f8fafc;font:600 13px/1.2 system-ui,sans-serif;text-decoration:none;border:1px solid #f7821b">
  <span style="color:#f7821b">★</span>
  <span>Verified on USS.EU.COM</span>
</a>
```

- **Zero third-party JS:** No cookies, no tracking pixels, zero Core Web Vitals CLS/INP impact.
