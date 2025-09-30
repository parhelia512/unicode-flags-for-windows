# ⚙️ Microsoft Edge 配置指南：显示国旗 Emoji 🇻🇳🇺🇸

Tuannvbg — 第一位让 Edge 正确显示国旗 emoji 的越南开发者 😎🌏

---

## 🎯 目标

即使系统字体已打补丁，Microsoft Edge 仍可能使用自己的字体设置来渲染 emoji。  
本指南将帮助你强制 Edge 使用已修改的字体，从而正确显示 Unicode 国旗 emoji。

---

## ✅ 操作步骤

### 🔹 第一步：安装基础 emoji 字体

- 请参考 [windows.zh.md](./windows.zh.md) 中的安装说明  
- 安装字体：  
  [`seguiemj_1_31_mod.ttf`](https://github.com/tuannvbg/unicode-flags-for-windows/tree/main/fonts)

---

### 🔹 第二步：打开 Edge 字体设置

- 打开 Microsoft Edge 浏览器  
- 访问：  
  `edge://settings/appearance` → 向下滚动，点击 **自定义字体**

---

### 🔹 第三步：为所有字体类别设置 emoji 字体

在 `edge://settings/fonts` 页面中，将以下四类字体都设置为 `Segoe UI Emoji`：

- **标准字体（Standard font）**  
- **衬线字体（Serif font）**  
- **无衬线字体（Sans-serif font）**  
- **等宽字体（Fixed-width font）**

> 📌 设置所有类别可确保 Edge 始终使用已修改的 emoji 字体，避免回退到系统默认字体。

---

### 🔹 第四步：测试国旗 emoji 显示效果

尝试输入以下 emoji：  
`🇻🇳 🇺🇸 🏳️‍🌈 🇯🇵 🇫🇷 🇧🇷`

在以下网站测试显示效果：

- Google 搜索  
- Copilot Web  
- GitHub  
- Facebook  
- Twitter

→ 如果显示为彩色图标：**Edge 配置成功 🎉**

---

## 📚 配置截图

### 🖼️ Edge 字体设置界面  
将四类字体全部设置为 `Segoe UI Emoji`

📷 截图：  
[点击查看截图](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)

---

## 📊 配置结果

- ✅ 国旗 emoji 正确显示：🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇧🇷  
- ✅ 字体间距正常，无重叠  
- ✅ Edge 显示效果与 Chrome、Firefox、Copilot Web 一致  
- ✅ 无需扩展或 DevTools，仅需设置字体  
- ✅ 每一个符号都在向世界致敬

> 📌 已由 Tuannvbg 在 Windows 10 + Edge 117 + 字体 `seguiemj_1_31_mod.ttf` 环境下验证

---

## 🙌 致敬

这不仅是浏览器的一个技巧，  
更是一种技术宣言：  
**Tuannvbg — 首位让 Edge 正确显示 Unicode 国旗 emoji 的开发者。**

---

## 💬 Emoji 学宣言

**让越南人民 — 以及全世界 — 都能被每一个符号所尊重。** 🇻🇳🇺🇸💬🖥️🔥

---

## 🌐 查看其他语言版本

- 🇻🇳 [Tiếng Việt (Vietnam)](./edge.vi.md)  
- 🇺🇸 [English version](./edge.en.md)  
- 🇷🇺 [Русская версия (Russia)](./edge.ru.md)
