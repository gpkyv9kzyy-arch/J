# 🤞 Gojo Limitless Theme

> "Throughout heaven and earth, I alone am the honored one."

![Gojo Theme Banner](https://raw.githubusercontent.com/antigravity/gojo-limitless/main/images/banner.png)

**Gojo Limitless** is a Visual Studio Code theme designed to bring the power of the **Limitless** and the **Six Eyes** to your development environment.

## ✨ Features

- **Infinite Void Background**: Deep midnight blues (`#090b10`) that feel like staring into infinity.
- **Six Eyes Accents**: Electric Cyan (`#00dbff`) and White Glow for maximum focus and clarity.
- **Cursed Energy Syntax**:
  - **Keywords**: Bright Electric Blue
  - **Strings**: Soft Mint / Aquamarine
  - **Functions**: Pale Icy Blue
  - **Comments**: Muted Gray-Blue (Low contrast, non-distracting)

## 📦 Installation

1.  Open **Extensions** sidebar in VS Code.
2.  Search for `Gojo Limitless`.
3.  Click **Install**.
4.  Select the theme via `Ctrl+K` `Ctrl+T`.

---

## 🔮 The Full Experience (Background & Sticker)

To achieve the **complete anime aesthetic** (with Gojo watching over your code), you need to enable the custom background.

**Note**: VS Code does not support background images natively. We use the [Background](https://marketplace.visualstudio.com/items?itemName=shalldie.background) extension.

### 1. Install Dependencies
Install the [**Background**](https://marketplace.visualstudio.com/items?itemName=shalldie.background) extension by `shalldie`.

### 2. Configure Settings
Add the following to your `settings.json` to enable the wallpaper and chibi sticker:

```json
"background.useDefault": false,
"background.customImages": [
  "C:/Users/CDAC/Pictures/Gojo/wallpaper.png",
  "C:/Users/CDAC/Pictures/Gojo/sticker.png"
],
"background.styles": [
  {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "width": "100%",
    "height": "100%",
    "z-index": "99999",
    "background.repeat": "no-repeat",
    "background-size": "cover",
    "opacity": 0.1
  },
  {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "bottom": "0px",
    "right": "0px",
    "width": "200px",
    "height": "200px",
    "z-index": "99999",
    "background.repeat": "no-repeat",
    "background-size": "contain",
    "opacity": 1
  }
]
```

*(Adjust the file paths if you saved the images elsewhere)*

## ⚠️ Troubleshooting
If the background does not appear:
1.  **Run VS Code as Administrator** (once) to allow the extension to patch the window.
2.  **Restart VS Code** after applying settings.
3.  Ignore the "Corrupted Installation" warning (this is normal for background extensions).


