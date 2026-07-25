---
title: "Contact"
permalink: /contact/
layout: single
author_profile: false
excerpt: "Get in touch."
---

We'd love to hear from you.

**Email:** [hello@yourdomain.com](mailto:hello@yourdomain.com)
**Phone:** (555) 555-5555
**Address:** 123 Main Street, Washington, DC 20001

---

### Send us a message

Jekyll is a static site generator, so there's no built-in form backend. The simplest options:

- **Formspree** (free tier available) — point a plain HTML `<form>` at their endpoint, no backend code needed.
- **Netlify Forms** — only works if you host on Netlify instead of GitHub Pages.
- **A `mailto:` link** — simplest option, no setup required, just less polished.

Example using Formspree once you have an endpoint:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
  <label>Name <input type="text" name="name"></label>
  <label>Email <input type="email" name="email"></label>
  <label>Message <textarea name="message"></textarea></label>
  <button type="submit">Send</button>
</form>
```
