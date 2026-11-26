# ✦ Zen Discord Theme ✦

🎨 A clean Discord theme with a frosted-glass look and a custom wallpaper.

---

## 📦 Installation

> ⚠️ Requires [Vencord](https://vencord.dev/download/) or [Vesktop](https://vesktop.dev/install/) to be installed first!

> 🌙 This theme is made for Discord's dark themes. Go to **User Settings** → **Appearance** and choose **Ash** (recommended, best with the default settings). **Dark** and **Onyx** also work. Do not use **Light !**.

### Option A — Quick (default settings)

1. Open Discord.
2. Go to **User Settings** → **"Vencord Settings"** → **Themes** → **"Online Themes"**.
3. Paste this link and save:

```
https://amgt2302.github.io/Zen-Discord/Theme.css
```

### Option B — Customizable

1. Open Discord.
2. Go to **User Settings** → **"Vencord Settings"** → **Themes** → **"Local Themes"** → **Edit QuickCSS**.
3. Copy and paste **the whole block** below:

```css
@import url("https://amgt2302.github.io/Zen-Discord/Import.css");

:root {
  /* -- Appearance -- */
  --background-image: url("https://amgt2302.github.io/Zen-Discord/asset/Default.png");
  --opacity: 0.35;                  /* wallpaper visibility (0 to 1) */
  --Color: rgb(0, 0, 0);            /* tint of the overlay and menus */
  --Color2: rgba(25, 200, 220, 0.6);/* accent: text selection, RGB frozen if animations are OFF */

  /* -- Menus (0 = transparent, 1 = opaque) -- */
  --glass: 0.5;                     /* big menus: settings, profile, modals, GIF, apps */
  --glass-small: 0.3;               /* small menus: right click, audio, lists */
  --menu-blur: 10px;                /* blur behind menus (doubled in settings and profiles) */
  --blur: 5px;                      /* chat blur */

  /* -- Animations & RGB (1 = ON, 0 = OFF) -- */
  --animations-enabled: 1;
  --search-rgb: 1;                  /* RGB on the search and message bars */
  --rainbow-speed: 15s;             /* duration of one rainbow cycle */
}
```

---

## 🎨 Customization

With **Option B**, change the values in the `:root` block directly in your **QuickCSS**, then save. The theme updates right away.

For example, to make the wallpaper more visible, change `--opacity: 0.35;` to `--opacity: 0.5;`.

To use your own wallpaper, replace the `--background-image` link with the link of your image.

> ⚠️ If your image is hosted on another website, Discord may block it. In that case, Vencord asks you to **allow** the link: accept, then **restart Discord**.

## 📄 Credits & License

**Made by :** Amgt2302 — 2025

This project is licensed under [**CC BY-NC-ND 4.0**](LICENSE).

| | |
|---|---|
| ✅ | Use it and customize the settings (colors, animations...) for your own Discord |
| ✅ | Share the original project, with credit to **Amgt2302** and a link to this repo |
| ❌ | No republishing the code (modified or not) under another name or in another repo |
| ❌ | No selling, no commercial use, no profit made from it |
| | |

Have fun! 😄