# 🌱 Green Points — Netherlands

An interactive, story-driven proposal for a national waste-to-rewards program. Play as Anna's family as they learn, sort, deposit, and earn Green Points — and watch a whole city grow greener, cleaner, and richer together.

**Built as a single-file React app** (no build step). Uses React 18 UMD, Tailwind Play CDN, Babel standalone, and the Web Audio API. All sounds are synthesized in-browser — zero external audio files.

---

## 🎮 Play

Just open `index.html` in any modern browser, or visit the deployed link (added after first deploy).

### Controls

- **Click** any choice to advance
- **← / →** arrow keys for back / next
- **🔊** button (top-right) toggles sound

---

## 🖼️ Scenes

1. **Title** — warm welcome + start
2. **Problem** — 400 kg of food waste per household, 1.2M tonnes yearly
3. **Family** — meet Anna, Marco, Sofia, Luca
4. **Idea** — the 2¢-per-kg rewards pitch
5. **Sorting** — mini quiz: which bin?
6. **Deposit** — stars + euros rain in when Anna drops off her caddy
7. **Spread** — Anna's year-1 totals grow step by step
8. **Mayor** — yes/no moment that turns the whole city green
9. **Projection** — animated 5-year chart, €4.2M/year impact
10. **Winners** — everyone shares the gain
11. **Green City** — 340 trees grown from food scraps, a final celebration

---

## 🗂️ Files

```
green-points-game/
├── index.html           # The entire app (React + styles + logic)
├── images/              # 6 hand-illustrated scene backgrounds
│   ├── scene1_home.jpg
│   ├── scene2_problem.jpg
│   ├── scene3_caddy.jpg
│   ├── scene4_deposit.jpg
│   ├── scene5_mayor.jpg
│   └── scene6_park.jpg
├── vercel.json          # Static-hosting config for Vercel
└── README.md
```

---

## 🚀 Deploy

This is a pure static site — no build, no server, no env vars.

- **Vercel**: drop the folder and deploy (static, output directory is the root).
- **Netlify / Render / GitHub Pages**: same — point them at the folder root.

---

## 📱 QR code

After deploy, generate a QR pointing at the live URL so people can scan to play from any phone.

---

## 📄 License

MIT — feel free to remix for your own city.
