# 🚚 LoadMove — Home & Goods Transportation Website

A modern, mobile-friendly website concept for a local home and goods transport service. It features a scroll-driven story hero, an instant price estimator, and one-tap booking through WhatsApp or email.

Built with **only HTML, CSS, and JavaScript**: a single file, no frameworks, no libraries, no build step.

🔗 **Live demo:** https://loadmove.vercel.app/

> **Note:** LoadMove is a **demo / concept project** built to showcase front-end design and development skills. It is not an operating business, and the estimator prices are sample values only.

---

## ✨ Features

- **Scroll-story hero:** an animated journey (home → road → destination) that plays as you scroll, with a progress bar and chapter captions
- **How it works:** a clear step-by-step flow from request to delivery
- **Services:** home moving, furniture and appliances, goods delivery, material transport, point-to-point, and loading support
- **Owner section:** a personal, trust-focused introduction
- **Price estimator:** pick the load type and size to see an instant starting estimate (₹, Indian number formatting)
- **Booking form:** sends the filled-in details to WhatsApp or email as a ready-made message
- **Fully responsive:** designed mobile-first, with breakpoints for tablets and phones
- **Accessibility-minded:** respects `prefers-reduced-motion`
- **SEO basics:** page title and meta description included

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, flexbox/grid, animations, media queries) |
| Logic | Vanilla JavaScript (scroll handling with `requestAnimationFrame`, DOM events) |
| Hosting | Vercel |

## 📁 Project Structure

```
loadmove/
├── index.html    # the entire website (HTML + CSS + JS)
└── README.md
```

## 🚀 Run Locally

1. Clone the repository
   ```bash
   git clone https://github.com/Prathap2349/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` in your browser. That's it, no install needed.

## ⚙️ Customize

Contact details are kept in one config object near the bottom of the script in `index.html`:

```js
const CFG = { wa: '91XXXXXXXXXX', mail: 'you@example.com' };
```

Replace the WhatsApp number and email with your own. The phone link in the page (`tel:`) should be updated too.

## 🌐 Deploy

- **Vercel:** import the repo and deploy (no configuration required)
- **GitHub Pages:** Settings → Pages → deploy from the `main` branch

## 🔮 Possible Improvements

- Distance-based price estimation
- Multi-step booking flow
- Tamil / English language toggle
- Expanded SEO (Open Graph tags, structured data)

## 👨‍💻 Author

**Prathap**
B.Tech Artificial Intelligence & Data Science student

- GitHub: [@Prathap2349](https://github.com/Prathap2349)

---

⭐ If you like this project, consider giving it a star!
