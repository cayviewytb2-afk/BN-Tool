* **`bn_tool_windows.exe`**: Dành cho máy tính / laptop chạy Windows (64-bit).
* **`bn_tool_arm64`**: Dành cho điện thoại Android 64-bit (chạy qua Termux).
* **`bn_tool_arm32`**: Dành cho điện thoại Android 32-bit (chạy qua Termux).

---

## 💻 1. Hướng dẫn sử dụng trên Máy tính (Windows)

1. Tải file **`bn_tool_windows.exe`** về máy tính.
2. Click đúp chuột vào file **`bn_tool_windows.exe`** để khởi chạy.

---

## 📱 2. Hướng dẫn sử dụng trên Android (Dùng Termux)

### Bước 1: Chuẩn bị
1. Cài đặt ứng dụng **Termux** (Khuyến nghị tải từ F-Droid hoặc GitHub, không dùng bản CH Play đã cũ).
2. Dùng trình duyệt trên điện thoại tải file **`bn_tool_arm64`** (hoặc **`bn_tool_arm32`**) từ mục Releases về máy. File tải về sẽ nằm tại thư mục `Download` của máy.

### Bước 2: Cấp quyền bộ nhớ cho Termux
Mở Termux và gõ lệnh sau để cấp quyền truy cập bộ nhớ:

```bash
termux-setup-storage
```
> Khi hệ thống hiển thị thông báo yêu cầu cấp quyền, chọn **Cho phép** (Allow).

### Bước 3: Cài đặt và khởi chạy tool

Dán toàn bộ lệnh tương ứng với phiên bản chip máy bạn vào Termux rồi nhấn **Enter**:

* **Đối với máy Android 64-bit (`arm64`):**
  ```bash
  cd ~ && rm -f bn_tool_arm64 && cp -f /sdcard/Download/bn_tool_arm64* ~/bn_tool_arm64 && chmod +x ~/bn_tool_arm64 && cd /sdcard/Download && ~/bn_tool_arm64
  ```

* **Đối với máy Android 32-bit (`arm32`):**
  ```bash
  cd ~ && rm -f bn_tool_arm32 && cp -f /sdcard/Download/bn_tool_arm32* ~/bn_tool_arm32 && chmod +x ~/bn_tool_arm32 && cd /sdcard/Download && ~/bn_tool_arm32
  ```
## 3. Hướng dẫn sử dụng Tool
  Đối với PC: 
    - Dùng chuột phải click vào sẽ hiện dropdown tính năng
    - Dùng chuột trái rê vào để bôi đen để thao tác

  Đối với điện thoại: 
    - Ấn giữ một lúc rồi nhả ra hoặc click 2 lần vào cùng 1 vị trí sẽ hiện dropdown tính năng 
    - Dùng tay ở cột ô vuông tick từng tài khoản có thể ấn giữ vào ô vị trí mình muốn sau đó giữ đè vuốt xuống thẳng hàng sẽ tự bôi đen tài khoản để thao tác


---
