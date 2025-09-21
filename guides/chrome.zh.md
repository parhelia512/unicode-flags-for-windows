# ⚙️ 配置 Chrome 以正确显示 Unicode 国旗表情 🇨🇳

Tuannvbg —— 一位来自越南的开发者，让 Chrome 精准呈现国旗表情 😎🇻🇳🇺🇸

---

## 🎯 目标

即使系统字体已打补丁，Chrome 仍可能使用自己的字体设置来渲染表情。本指南将教你如何强制 Chrome 使用已修补的字体，以正确显示 Unicode 国旗表情。

---

## ✅ 操作步骤

### 🔹 步骤 1：确保系统字体已打补丁

- 按照 [windows.zh.md](windows.zh.md) 中的说明操作  
- 将系统字体 `Segoe UI Emoji` 替换为包含国旗表情的修补版本

---

### 🔹 步骤 2：打开 Chrome 字体设置页面

- 打开 Chrome 浏览器  
- 直接访问：

```
chrome://settings/fonts
```

或通过以下路径进入：

```
chrome://settings → 外观 → 自定义字体 → chrome://settings/fonts
```

---

### 🔹 步骤 3：为所有字体类别设置 emoji 字体

- 在 `chrome://settings/fonts` 页面中，将以下四个类别全部设置为 `Segoe UI Emoji`：

  - **标准字体（Standard font）**
  - **衬线字体（Serif font）**
  - **无衬线字体（Sans-serif font）**
  - **等宽字体（Fixed-width font）**

> 📌 设置所有类别可确保 Chrome 始终使用修补后的 emoji 字体，避免回退到系统默认字体。

---

### 🔹 步骤 4：测试国旗表情

尝试输入以下表情：

```
🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪
```

在以下网站测试：

- Google 搜索  
- Copilot Web  
- GitHub  
- Facebook  
- Twitter  

→ 如果显示正确：**Chrome 配置成功 🎉**

---

## 📚 示例截图

### 🖼️ Chrome 字体设置页面  
> 将 `Segoe UI Emoji` 设置为四个类别：Standard、Serif、Sans-serif、Fixed-width

![Chrome Font Settings](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)

---

### 🖼️ Chrome 成功显示国旗表情  
> 表情显示正确，间距流畅，无重叠问题

![Chrome Browser Result](../screenshots/Chrome.Browser.Show.Screenshot.2025-09-21.111129.jpg)

---

## 📊 配置结果

- ✅ 国旗表情显示正确：🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪  
- ✅ 无文字重叠，间距自然  
- ✅ Chrome 表现与 Firefox、Safari、Copilot Web 一致  
- ✅ 无需扩展插件，无需开发者工具，仅需字体设置  
- ✅ 越南用户与全球用户都能被每一个符号所尊重

> 📌 已在 Windows 11 + Chrome 117 + 字体 `seguiemj_1_33_mod.ttf` 上由 Tuannvbg 验证

---

## 🙌 致敬

> 这不仅是浏览器设置，更是一份技术宣言：  
> **Tuannvbg —— 第一个让 Chrome 正确显示 Unicode 国旗表情的开发者。**

---

## 💬 宣言

> **为了让越南人民，以及世界各地的人们，都能被每一个符号所尊重。** 🇻🇳 🇺🇸💬🖥️🔥

---

## 🌐 查看其他语言版本

- 🇻🇳 [Tiếng Việt](chrome.vi.md)
- 🇺🇸 [English version](chrome.en.md)
- 🇷🇺 [Русская версия](chrome.ru.md)
