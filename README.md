# Cole Creative Events — Website

Official website for **Cole Creative Events** by Erica Cole.
Balloon Design · Full Planning · Décor · Atlanta, GA

---

## 📁 File Structure

```
cole-creative-events/
├── index.html          ← Main website (all pages in one file)
├── README.md           ← This file
└── images/
    ├── logo.png        ← Cole Creative Events logo
    ├── img_1.jpg       ← Gallery photo 1 (Birthday garland)
    ├── img_2.jpg       ← Gallery photo 2 (Boho setup)
    ├── img_3.jpg       ← Gallery photo 3 (Pink/red arch)
    ├── img_4.jpg       ← Gallery photo 4 (Baby in Bloom)
    ├── img_5.jpg       ← Gallery photo 5 (Dino birthday)
    └── img_6.jpg       ← Gallery photo 6 (Gender reveal)
```

---

## 🚀 Deploying with GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch and `/ (root)` folder
4. Click **Save** — your site will be live at:
   `https://yourusername.github.io/cole-creative-events/`

---

## 📝 To Update Content

| What to change | Where in index.html |
|---|---|
| Phone / Email | Search `678-925-2469` or `info@colecreativeevents.com` |
| About / Bio copy | Search `<!-- ABOUT -->` section |
| Services list | Search `<!-- SERVICES -->` section |
| Add gallery photos | Add `<img>` tags in `<!-- GALLERY -->` section, place images in `/images/` |
| Inquiry form backend | Replace `<button class="form-submit">` with a Formspree or Netlify form action |

---

## 📬 Connect the Inquiry Form (Required for Live Use)

The form is currently a placeholder UI. To make it functional, use one of these free options:

**Option A — Formspree (easiest):**
1. Sign up at [formspree.io](https://formspree.io)
2. Create a new form → copy your form ID (e.g. `xabcdefg`)
3. In `index.html`, find `<button class="form-submit">` and wrap the fields in:
   ```html
   <form action="https://formspree.io/f/xabcdefg" method="POST">
     <!-- existing fields here -->
   </form>
   ```

**Option B — Netlify Forms:**
1. Deploy to [netlify.com](https://netlify.com) instead of GitHub Pages
2. Add `netlify` attribute to the `<form>` tag — Netlify handles the rest for free

---

## 🎨 Brand Colors

| Name | Hex |
|---|---|
| Hot Pink | `#E8176A` |
| Deep Pink | `#C4004F` |
| Orange | `#F97316` |
| Coral | `#FB923C` |
| Gold | `#D4AF37` |
| Cream | `#FFF8F0` |

---

## 📞 Contact Info on Site

- **Phone:** (678) 925-2469
- **Email:** info@colecreativeevents.com
- **Instagram:** [@_colecreativeevents](https://www.instagram.com/_colecreativeevents/)
- **Location:** Atlanta, GA · Travel Available
