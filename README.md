# 🧙‍♂️ Persona Weaver (Trình tạo Hồ sơ User)

[Tiếng Việt] | [English](#english)

Một tiện ích mở rộng (extension) tự nhiên dành cho SillyTavern. Được thiết kế để sử dụng AI nhằm tạo, nhuận sắc chuyên sâu và quản lý Hồ sơ người dùng (User Persona) của bạn, hỗ trợ chỉnh sửa so sánh thông minh và tự động liên kết với World Info (Sách thế giới).

> **🔗 Link hữu ích:**
> * **Kho lưu trữ gốc (Original Repo):** [GitHub](https://github.com/sisisisilviaxie-star/st-persona-weaver)
> * **Discord thảo luận (Tác giả gốc):** [Tham gia tại đây](https://discord.com/channels/1291925535324110879/1452687095440343184)

## ✨ Tính năng cốt lõi

* **Tạo thông minh bằng AI**: Tự động tạo hồ sơ User có cấu trúc, chất lượng cao (định dạng YAML) dựa trên mô tả ngôn ngữ tự nhiên đơn giản hoặc các mẫu có sẵn.
* **Nhuận sắc chuyên sâu & So sánh thông minh**:
    * Không hài lòng với thiết lập hiện tại? Nhập ý kiến sửa đổi và AI sẽ viết lại một cách thông minh.
    * Cung cấp chế độ xem **Diff (So sánh khác biệt)**, hiển thị trực quan những thay đổi trước và sau khi sửa, cho phép bạn chọn giữ lại hoặc chỉnh sửa trực tiếp.
* **Hệ thống bản nháp**: Tự động hoặc lưu thủ công lịch sử tạo vào tab Bản nháp (Lịch sử). Không bao giờ mất ý tưởng, có thể khôi phục bất cứ lúc nào.
* **Liên kết World Info**: Tự động phát hiện World Info đang được gắn kết và cho phép lưu hồ sơ thành một mục (entry) chỉ với một cú nhấp chuột, giúp cốt truyện liên kết chặt chẽ hơn.
* **Hỗ trợ API độc lập**: Hỗ trợ cấu hình API riêng biệt (như OpenAI, DeepSeek, v.v.) để thực hiện tác vụ tạo ngầm, không chiếm dụng ngữ cảnh (context) và cấu hình model của cuộc trò chuyện chính.
* **Tối ưu cho di động**: Thiết kế giao diện UI được tối ưu hóa, hỗ trợ thao tác chạm vuốt và các nút nổi trên màn hình cảm ứng.

## 📦 Hướng dẫn cài đặt

1.  **Yêu cầu trước**: Khuyên dùng cài đặt và kích hoạt plugin [TavernHelper (JS-Slash-Runner)](https://github.com/n0vi028/JS-Slash-Runner) để có trải nghiệm thao tác World Info tốt nhất (không bắt buộc, nhưng khuyến nghị).
2.  Mở trang **Extensions (Tiện ích mở rộng)** trong SillyTavern.
3.  Nhấn vào **Install Extension**.
4.  Dán địa chỉ kho lưu trữ này vào ô URL: `https://github.com/ngongdaihiep123-del/st-persona-weaver-vietnamese`
5.  Nhấn **Save** (Lưu) và tải lại trang.

## 📖 Hướng dẫn sử dụng nhanh

1.  Sau khi cài đặt, một **Biểu tượng cây đũa thần** (<i class="fa-solid fa-wand-magic-sparkles"></i>) sẽ xuất hiện phía trên khung nhập liệu. Nhấn vào đó để mở bảng điều khiển.
2.  **Tạo**: Nhập yêu cầu của bạn vào trang soạn thảo và nhấn "Tạo thiết lập User".
3.  **Nhuận sắc**: Bôi đen một đoạn văn bản trong kết quả, nhấn vào nút "Sửa đoạn này" hiện ra, hoặc nhập ý kiến trực tiếp vào ô bên dưới để AI viết lại.
4.  **Lưu**: Nhấn "Lưu vào lịch sử" để lưu vào bản nháp, hoặc nhấn "Ghi đè hồ sơ hiện tại" để áp dụng ngay lập tức.

---

<a name="english"></a>
## English

**Persona Weaver** is a native extension for SillyTavern that uses AI to help create, refine, and manage User Personas, with automatic World Info synchronization.

### ✨ Features

* **AI Generation**: Automatically generate detailed, structured User Personas (YAML) based on simple prompts or templates.
* **Smart Refinement & Diff View**: 
    * Refine your persona with natural language instructions.
    * **Smart Contrast**: Visually compare the original vs. refined text side-by-side, allowing you to selectively apply changes or edit directly.
* **Drafts System**: Auto-save your generation history to the Drafts tab. Never lose an idea again.
* **World Info Sync**: Automatically detects bound World Info books and allows one-click saving of your persona as an entry.
* **Independent API**: Supports configuring a separate API (e.g., OpenAI, DeepSeek) for generation tasks, keeping your main chat context free.
* **Mobile Friendly**: Optimized UI for touch screens and mobile devices.

### 📦 Installation

1.  **Prerequisite**: [TavernHelper (JS-Slash-Runner)](https://github.com/n0vi028/JS-Slash-Runner) is recommended for full World Info features.
2.  Open **Extensions** in SillyTavern.
3.  Click **Install Extension**.
4.  Paste the repo URL: `https://github.com/ngongdaihiep123-del/st-persona-weaver-vietnamese`
5.  Click **Save** and reload.

## 📄 License

MIT License
