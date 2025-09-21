# ⚙️ Guide to Configure Chrome for Unicode Flag Emoji Display 🇺🇸

Tuannvbg — the Vietnamese developer who made Chrome render flag emojis pixel-perfect 😎🇻🇳🇺🇸

---

## 🎯 Goal

After patching the system font, Chrome may still use its own font settings to render emoji. This guide shows how to force Chrome to use the patched font so that Unicode flag emojis display correctly.

---

## ✅ Steps

### 🔹 Step 1: Ensure the system font is patched

- Follow the instructions in [windows.en.md](windows.en.md)
- The `Segoe UI Emoji` font should be replaced with the patched version containing flag emojis

---

### 🔹 Step 2: Open Chrome font settings

- Open Chrome
- Go directly to:

```
chrome://settings/fonts
```

Or navigate via:

```
chrome://settings → Appearance → Customize fonts → chrome://settings/fonts
```

---

### 🔹 Step 3: Assign emoji font to all categories

- In `chrome://settings/fonts`, set `Segoe UI Emoji` for all 4 categories:

  - **Standard font**
  - **Serif font**
  - **Sans-serif font**
  - **Fixed-width font**

> 📌 Assigning all categories ensures Chrome consistently uses the patched emoji font and avoids fallback to system defaults.

---

### 🔹 Step 4: Test flag emojis

Try typing these emojis:

```
🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪
```

On websites like:

- Google Search  
- Copilot Web  
- GitHub  
- Facebook  
- Twitter  

→ If they render correctly: **Chrome is successfully configured 🎉**

---

## 📚 Illustrations

### 🖼️ Font configuration in Chrome Settings  
> Set `Segoe UI Emoji` for all 4 categories: Standard, Serif, Sans-serif, Fixed-width

![Chrome Font Settings](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)

---

### 🖼️ Chrome rendering flag emojis after configuration  
> Flag emojis display correctly, with smooth spacing and no overlap

![Chrome Browser Result](../screenshots/Chrome.Browser.Show.Screenshot.2025-09-21.111129.jpg)

---

## 📊 Results after configuration

- ✅ Flag emojis render correctly: 🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪  
- ✅ No text overlap, smooth spacing  
- ✅ Chrome renders emojis like Firefox, Safari, Copilot Web  
- ✅ No extensions or DevTools needed — just font settings  
- ✅ Vietnamese users and global citizens are honored by every symbol

> 📌 Verified by Tuannvbg on Windows 11 + Chrome 117 + font `seguiemj_1_33_mod.ttf`

---

## 🙌 Credits

> This isn’t just a browser tweak. It’s a technical declaration:  
> **Tuannvbg — the first to make Chrome render Unicode flag emojis correctly.**

---

## 💬 Manifesto

> **So that the people of Vietnam — and the world — can be honored by every symbol.** 🇻🇳 🇺🇸💬🖥️🔥

---

## 🌐 View this guide in other languages

- 🇻🇳 [Tiếng Việt](chrome.vi.md)
- 🇨🇳 [中文版本](chrome.zh.md)
- 🇷🇺 [Русская версия](chrome.ru.md)
