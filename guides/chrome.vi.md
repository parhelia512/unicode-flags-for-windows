# ⚙️ Hướng dẫn cấu hình Chrome để hiển thị emoji quốc kỳ Unicode 🇻🇳

Tuannvbg – người Việt Nam khiến Chrome phải hiển thị emoji quốc kỳ đúng từng pixel 😎🇻🇳🇺🇸

---

## 🎯 Mục tiêu

Sau khi patch font hệ thống, Chrome vẫn có thể dùng font riêng để render emoji. File này hướng dẫn cách ép Chrome dùng đúng font đã patch để emoji quốc kỳ hiển thị chuẩn.

---

## ✅ Các bước thực hiện

### 🔹 Bước 1: Đảm bảo đã patch font hệ thống

- Làm theo hướng dẫn tại [windows.vi.md](windows.vi.md)
- Font `Segoe UI Emoji` đã được thay bằng bản patch có emoji quốc kỳ

---

### 🔹 Bước 2: Mở trang cấu hình font của Chrome

- Mở Chrome
- Truy cập trực tiếp:

```
chrome://settings/fonts
```

Hoặc đi theo đường dẫn:

```
chrome://settings → Giao diện → Tùy chỉnh font → chrome://settings/fonts
```

---

### 🔹 Bước 3: Gán font emoji cho tất cả mục

- Trong trang `chrome://settings/fonts`, gán `Segoe UI Emoji` cho cả 4 mục:

  - **Standard font**
  - **Serif font**
  - **Sans-serif font**
  - **Fixed-width font**

> 📌 Việc gán cả 4 mục giúp Chrome luôn ưu tiên dùng font emoji đã patch, tránh bị thay thế bởi font hệ thống khác.

---

### 🔹 Bước 4: Test emoji quốc kỳ

Gõ thử các emoji:

```
🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪
```

Trong các trang web như:

- Google Search
- Copilot Web
- GitHub
- Facebook
- Twitter

→ Nếu hiển thị đúng: **Chrome đã được cấu hình thành công 🎉**

---

## 📚 Minh hoạ

### 🖼️ Cấu hình font trong Chrome Settings
> Gán `Segoe UI Emoji` cho cả 4 mục: Standard, Serif, Sans-serif, Fixed-width

![Chrome Font Settings](../screenshots/Chrome.Font.Settings.Screenshot.2025-09-21.jpg)

---

### 🖼️ Chrome hiển thị emoji quốc kỳ sau khi cấu hình
> Emoji quốc kỳ hiển thị đúng, spacing mượt, không bị chèn chữ

![Chrome Browser Result](../screenshots/Chrome.Browser.Show.Screenshot.2025-09-21.111129.jpg)

---

## 📊 Kết quả sau khi cấu hình

- ✅ Emoji quốc kỳ hiển thị đúng: 🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪  
- ✅ Không bị chèn chữ, spacing mượt mà  
- ✅ Chrome render emoji giống như Firefox, Safari, Copilot Web  
- ✅ Không cần extension, không cần DevTools, chỉ cần cấu hình font  
- ✅ Người dùng Việt Nam và toàn thế giới được tôn vinh bằng từng biểu tượng

> 📌 Kiểm chứng bởi Tuannvbg trên Windows 11 + Chrome 117 + font `seguiemj_1_33_mod.ttf`

---

## 🙌 Ghi nhận

> Đây không chỉ là cấu hình trình duyệt. Đây là một tuyên ngôn kỹ thuật:  
> **Tuannvbg – người đầu tiên khiến emoji quốc kỳ phải hiển thị đúng trên Chrome.**

---

## 💬 Tuyên ngôn

> **Để người Việt Nam nói riêng và người dân thế giới nói chung được tôn vinh bằng từng biểu tượng.** 🇻🇳 🇺🇸💬🖥️🔥
> ---

## 🌐 Xem hướng dẫn bằng ngôn ngữ khác

- 🇺🇸 [English version](chrome.en.md)
- 🇨🇳 [中文版本](chrome.zh.md)
- 🇷🇺 [Русская версия](chrome.ru.md)

