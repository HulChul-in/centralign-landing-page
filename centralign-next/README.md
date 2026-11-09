# CentrAlign AI landing page

Responsive static site. Deploy this folder to Vercel as a static project (no build command required).

## Analytics
The Google Analytics Measurement ID was not included in the message. To enable GA4, add this snippet to the `<head>` of `index.html` and replace `G-XXXXXXXXXX` with your real Measurement ID:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments)}
gtag('js', new Date());
gtag('config', 'G-XXXXXXXXXX');
</script>
```

## Production checklist
- Update `/login` and `/signup` to your real app URLs.
- The task dashboard and WhatsApp conversation are **illustrative UI**, not live integrations.
- Privacy and terms are starter pages; confirm they match actual operations before publishing.
- Add your GA4 Measurement ID when available.
