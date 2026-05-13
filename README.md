# 🌿 Md. Abid Hossain — Personal Portfolio

A premium, fully responsive personal portfolio website with a white + green modern professional design, featuring glassmorphism UI, smooth animations, and a static landing page paired with a full-portfolio section.

---

## 📁 Project Structure

```
portfolio/
├── index.html              ← Fast static landing page
├── 404.html                ← GitHub Pages SPA fallback
├── README.md               ← You're reading this!
├── css/
│   └── style.css           ← Shared premium stylesheet
├── images/
│   └── profile.jpg         ← Your profile photo
└── app/
    └── index.html          ← Full portfolio (all sections)
```

---

## 🚀 Local Development

No build tools needed. Just open in any browser:

```bash
# Option 1 — Python (recommended)
python3 -m http.server 8080
# Then visit: http://localhost:8080

# Option 2 — Node.js (npx)
npx serve .
# Then visit: http://localhost:3000

# Option 3 — VS Code Live Server extension
# Right-click index.html → Open with Live Server
```

---

## 🌐 GitHub Pages Deployment

### Step 1 — Create GitHub Repository

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

### Step 2 — Enable GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**: select `main` branch, `/ (root)` folder
4. Click **Save**
5. Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

### Step 3 — Update Links (Important!)

After deployment, update these in both HTML files:
- Replace all `https://github.com` with your actual GitHub profile URL
- Replace all `https://linkedin.com` with your LinkedIn URL
- Replace all `https://facebook.com` with your Facebook URL
- In `app/index.html`, update the FormSubmit `_next` URL to your live URL

---

## ✏️ Customization Guide

### Update Personal Info
Edit in both `index.html` and `app/index.html`:
- Name, title, description
- Social media links
- Email address

### Add/Edit Projects
In `app/index.html`, find the `.projects-grid` section and edit/add `.project-card` blocks.

### Update Skills
Find the `.skills-grid` section in `app/index.html` and modify skill tags.

### Change Profile Photo
Replace `images/profile.jpg` with your photo (keep the same filename, or update the `src` in both HTML files).

### Colors
Edit CSS variables at the top of `css/style.css`:
```css
:root {
  --primary: #16a34a;       /* Main green */
  --primary-light: #22c55e; /* Lighter green */
  --accent: #4ade80;        /* Accent green */
}
```

---

## 📬 Contact Form Setup

The contact form uses **FormSubmit** (no backend needed):

1. The form already points to `abid27016@gmail.com`
2. First time it's submitted, FormSubmit will send a confirmation email
3. Click the confirmation link, then the form will work automatically

**Alternative — EmailJS:**
```javascript
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form, 'YOUR_PUBLIC_KEY');
```

**Fallback — Mailto:**
```html
<form action="mailto:abid27016@gmail.com" method="post" enctype="text/plain">
```

---

## ⚡ Performance & Accessibility

- ✅ Semantic HTML5 with ARIA labels
- ✅ Lazy-loaded images
- ✅ IntersectionObserver for scroll animations
- ✅ CSS custom properties for theming
- ✅ Keyboard navigation support
- ✅ Screen reader friendly
- ✅ Mobile-first responsive design
- ✅ Optimized fonts via Google Fonts
- ✅ No unnecessary JS frameworks

---

## 🌍 Browser Support

| Browser | Support |
|---------|---------|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## 📄 License

MIT License — Free to use and modify for personal portfolios.

---

**Made with ♥ in Dhaka, Bangladesh by Md. Abid Hossain**
