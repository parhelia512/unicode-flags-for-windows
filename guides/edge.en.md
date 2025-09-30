# ⚙️ Guide to Configure Microsoft Edge for Unicode Flag Emoji Display 🇻🇳🇺🇸

Tuannvbg — the Vietnamese developer who made Edge render flag emojis pixel-perfect 😎🌏

---

## 🎯 Goal

Even after patching the system font, Microsoft Edge may still use its own font settings to render emoji.  
This guide shows how to force Edge to use the patched font so that Unicode flag emojis display correctly.

---

## ✅ Steps

### 🔹 Step 1: Ensure the system font is patched

- Follow the instructions in [windows.en.md](./windows.en.md)  
- The `Segoe UI Emoji` font should be replaced with the patched version:  
  [`seguiemj_1_31_mod.ttf`](https://github.com/tuannvbg/unicode-flags-for-windows/tree/main/fonts)

---

### 🔹 Step 2: Open Edge font settings

- Open Microsoft Edge  
- Go to:  
  `edge://settings/appearance` → scroll down to **Customize fonts**

---

### 🔹 Step 3: Assign emoji font to all categories

In `edge://settings/fonts`, set `Segoe UI Emoji` for all 4 categories:

- **Standard font**  
- **Serif font**  
- **Sans-serif font**  
- **Fixed-width font**

> 📌 Assigning all categories ensures Edge consistently uses the patched emoji font and avoids fallback to system defaults.

---

### 🔹 Step 4: Test flag emojis

Try typing these emojis:  
`🇻🇳 🇺🇸 🏳️‍🌈 🇯🇵 🇫🇷 🇧🇷`

On websites like:

- Google Search  
- Copilot Web  
- GitHub  
- Facebook  
- Twitter

→ If they render correctly: **Edge is successfully configured 🎉**

---

## 📚 Illustrations

### 🖼️ Font configuration in Edge Settings  
Set `Segoe UI Emoji` for all 4 categories:  
Standard, Serif, Sans-serif, Fixed-width

📷 Screenshot:  
[![Edge Font Settings](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)

---

## 📊 Results after configuration

- ✅ Flag emojis render correctly: 🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇧🇷  
- ✅ No text overlap, smooth spacing  
- ✅ Edge renders emojis like Chrome, Firefox, Copilot Web  
- ✅ No extensions or DevTools needed — just font settings  
- ✅ Vietnamese users and global citizens are honored by every symbol

> 📌 Verified by Tuannvbg on Windows 10 + Edge 117 + font `seguiemj_1_31_mod.ttf`

---

## 🙌 Credits

This isn’t just a browser tweak.  
It’s a technical declaration:  
**Tuannvbg — the first to make Edge render Unicode flag emojis correctly.**

---

## 💬 Manifesto

**So that the people of Vietnam — and the world — can be honored by every symbol.** 🇻🇳🇺🇸💬🖥️🔥

---

## 🌐 View this guide in other languages

- 🇻🇳 [Tiếng Việt (Vietnam)](./edge.vi.md)  
- 🇨🇳 [中文版本 (China)](./edge.zh.md)  
- 🇷🇺 [Русская версия (Russia)](./edge.ru.md)
