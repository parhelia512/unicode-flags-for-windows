# Patch emoji quốc kỳ Unicode cho Windows 10 & 11 🇻🇳

Tuannvbg – người Việt Nam quyết tâm và làm bằng được emoji quốc kỳ phải hiển thị đúng trên Windows 😎🇻🇳🇺🇸

---

## 🎯 Mục tiêu

Hiển thị đúng emoji quốc kỳ Unicode (🇻🇳 🇺🇸 🇯🇵 🇫🇷 🇩🇪…) trên toàn hệ thống Windows: từ Notepad, VS Code, Copilot PC app đến trình duyệt Chrome, Edge, Firefox.

---

## ⚠️ Cảnh báo quan trọng

**Trước khi patch, hãy backup font gốc `Segoe UI Emoji` để có thể khôi phục nếu cần.**

### 🔄 Cách backup:

- Mở thư mục `C:\Windows\Fonts`
- Tìm file `seguiemj.ttf`
- Copy ra thư mục riêng (ví dụ: `E:\FontBackup\seguiemj_original.ttf`)

---

## ✅ Các bước thực hiện

### 🔹 Bước 1: Chọn đúng font đã patch

| Hệ điều hành     | Font sử dụng               |
|------------------|----------------------------|
| Windows 10       | `seguiemj_1_31_mod.ttf`    |
| Windows 11       | `seguiemj_1_33_mod.ttf`    |

> 📌 Dùng đúng phiên bản giúp emoji flags hiển thị chuẩn, spacing mượt, không lỗi glyph

---

### 🔹 Bước 2: Cài font

- Mở thư mục chứa font (ví dụ: `E:\FontEmoji`)
- Click chuột phải vào file `.ttf` → chọn **Install**
- 📌 Nếu không thấy “Install” → mở bằng Font Viewer → nhấn nút “Install” ở góc trên

---

### 🔹 Bước 3: Copy font vào thư mục hệ thống (nếu cần)

- Mở PowerShell với quyền Admin  
  → Nhấn `Win`, gõ `powershell`, chuột phải → **Run as administrator**

- Gõ lệnh:

```powershell
Copy-Item "E:\FontEmoji\seguiemj_1_33_mod.ttf" -Destination "$env:windir\Fonts" -Force
```

> Thay tên file tùy theo phiên bản Windows bạn đang dùng

---

### 🔹 Bước 4: Sửa Registry để Windows nhận font mới

1. Mở Registry Editor  
   → Nhấn `Win + R` → gõ `regedit` → Enter

2. Điều hướng đến:

```
HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Fonts
```

3. Tìm dòng:

```
Segoe UI Emoji (TrueType)
```

- Nếu có → nhấp đôi → sửa giá trị thành:

```
seguiemj_1_33_mod.ttf
```

- Nếu không có → chuột phải → `New > String Value`

  - Tên: `Segoe UI Emoji (TrueType)`  
  - Giá trị: `seguiemj_1_33_mod.ttf`

---

### 🔹 Bước 5: Khởi động lại máy

- Sau khi chỉnh xong → **restart máy** để font được áp dụng

---

### 🔹 Bước 6: Test emoji cờ

Gõ thử các emoji quốc kỳ:

```
🇻🇳 🇯🇵 🇺🇸 🇧🇷 🇿🇦
```

Trong các ứng dụng:

- Chrome
- Edge
- Discord
- VS Code
- Copilot PC app

→ Nếu hiển thị đúng: **patch thành công 🎉**

---

## 📚 Minh hoạ

### 🖼️ Copilot PC App
![Copilot PC App](Copilot.PC.app.Windows11.Screenshot.2025-09-21.103357.jpg)

### 🖼️ Notepad
![Notepad](screenshots/Notepad.Screenshot.2025-09-21.103618.jpg)

### 🖼️ Visual Studio Code
![VS Code](screenshots/VSC2.Screenshot.2025-09-21.104033.jpg)

### 🖼️ Chrome Browser
![Chrome](screenshots/Chrome.Browser.Show.Screenshot.2025-09-21.111129.jpg)

### 🖼️ Microsoft Edge
![Edge](screenshots/Edge.Browser.Show.Screenshot.2025-09-21.111408.jpg)

### 🖼️ Firefox Browser
![Firefox](screenshots/Firefox.Browser.Show.Screenshot.2025-09-21.111557.jpg)

---

## 🙌 Ghi nhận

> Đây không chỉ là một bản patch. Đây là một tuyên ngôn kỹ thuật:  
> **Tuannvbg – người đầu tiên khiến emoji quốc kỳ phải hiển thị đúng trên Windows.**

---

## 💬 Tuyên ngôn

> **Để người Việt Nam nói riêng và người dân thế giới nói chung được tôn vinh bằng từng biểu tượng.** 🇻🇳 🇺🇸💬🖥️🔥

