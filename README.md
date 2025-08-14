# ✦ Zen Discord Theme ✦

[![Preview](https://img.shields.io/badge/Preview-5865F2?logo=Discord&style=for-the-badge&labelColor=black)](https://gibbu.github.io/ThemePreview/?file=https://amgt2302.github.io/Zen-Discord/Theme.css)

🎨 Un thème Discord épuré, personnalisé, avec fond d’écran.

---

## 📦 Installation

> ⚠️ Nécessite [Vencord](https://vencord.dev/download/) installé au préalable !

  1. Ouvre Discord. 
  2. Va dans les **"Paramètres utilisateur"** → **"vencord"** → **"Theme"** → **"Edit QuickCSS"**.
  3. Copie-colle **tout le contenu** ci-dessous :

```css
/*
╭───────── Zen Discord ─────────╮
│  Version: V1.0                │
│  Author : AMGT2302            │
│  GitHub : github.com/AMGT2302 │
╰───────────────────────────────╯
*/
@import url("https://amgt2302.github.io/Zen-Discord/Import.css");

:root {
  --background-image: url("https://amgt2302.github.io/Zen-Discord/asset/Default.jpg");
  --opacity: 0.25;
  --blur: 5px;
  --Color: rgba(0, 0, 0, 1);

  --animations-enabled: 1; /* 1 = ON, 0 = OFF */
}
```
Ou [clic ici](https://amgt2302.github.io/Zen-Discord/Theme.css).

---

## 🎨 Personnalisation

Dans `Theme.css`, tu peux modifier ces variables dans :

```css
:root {
  --background-image: url("https://amgt2302.github.io/Zen-Discord/asset/Default.jpg"); /*Background Url*/
  --opacity: 0.25; /*Default 0.25*/
  --blur: 5px; /*adjust blur*/
  --Color: rgba(0, 0, 0, 1); /*Filter Color*/

  --animations-enabled: 1; /* 1 = ON, 0 = OFF */
}
```