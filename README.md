# HỆ THỐNG QUẢN LÝ XƯỞNG SẢN XUẤT GIÀY (ADMIN DASHBOARD)

Dự án website đơn trang (Single-Page Application) hoàn chỉnh xây dựng bằng **HTML, CSS và JavaScript thuần (Vanilla JS)**, không phụ thuộc vào bất kỳ thư viện hoặc dịch vụ bên thứ ba nào.

---

## 🌟 Tính năng nổi bật (11 Phân hệ nghiệp vụ)

1. **Dashboard (Bảng điều khiển):** 4 thẻ KPI tính từ dữ liệu thực tế, 2 biểu đồ Canvas thuần (Doanh thu & Phân bổ NVL), danh sách cảnh báo thông minh có điều hướng nhanh.
2. **Quản lý danh mục:**
   - *Nguyên vật liệu:* Mã, tên, ĐVT, giá nhập ước tính, tồn kho thực tế, ngưỡng an toàn tối thiểu.
   - *Sản phẩm / SKU:* Mẫu giày, size, màu sắc, giá bán, tồn kho thành phẩm.
   - *Đối tác:* Nhà cung cấp và Khách hàng với lịch sử giao dịch & số dư công nợ.
3. **Quản lý định mức BOM:** Khai báo cấu trúc vật tư cho 1 đôi giày, công cụ tính nhu cầu NVL cho N sản phẩm, chốt phiên bản và **chống sửa BOM khi đã xuất kho**.
4. **Quản lý lệnh sản xuất:** Quy trình *Chờ duyệt* ➔ *Xuất NVL* ➔ *Đang sản xuất* ➔ *Hoàn thành & Nhập kho thành phẩm*. **Chặn tuyệt đối xuất kho âm**.
5. **Quản lý kho:** 2 tab tồn kho (Nguyên liệu & Thành phẩm), lập phiếu nhập/xuất kho, **lịch sử kho bất biến (không sửa/xóa)**.
6. **Quản lý bán hàng:** Lập đơn hàng, trừ kho tự động, kiểm soát công nợ khách hàng, tích hợp form **In hóa đơn bán hàng** chuẩn in trình duyệt (`Ctrl + P`).
7. **Quản lý thu chi:** Sổ quỹ theo dõi dòng tiền Thu / Chi thực tế, tự động tính chênh lệch quỹ tiền mặt.
8. **Báo cáo & Cảnh báo thông minh:**
   - Báo cáo tồn kho dưới ngưỡng an toàn.
   - Báo cáo tài chính & Lợi nhuận gộp (Doanh thu - Giá vốn NVL theo BOM).
   - Cảnh báo bất thường: Tự động phát hiện hao hụt nguyên vật liệu **vượt ngưỡng 5%**.
9. **Tài khoản & Phân quyền:** Giao diện mô phỏng vai trò *Chủ xưởng*, *Thủ kho*, *Bán hàng* và đổi mật khẩu.
10. **Trải nghiệm & Responsive:** Hoạt động mượt mà từ màn hình điện thoại 360px đến màn hình máy tính, cỡ chữ tối thiểu toàn hệ thống >= 16px.

---

## 🚀 Hướng dẫn chạy website

### Cách 1: Chạy trực tiếp trên máy tính (Offline)
- Mở thư mục chứa file: `index.html`.
- Nhấp đúp chuột vào file `index.html` để mở bằng bất kỳ trình duyệt nào (Chrome, Edge, Firefox, Cốc Cốc, Safari...).
- Website chạy ngay lập tức mà không cần cài thêm web server hay Internet.

### Cách 2: Chạy trực tuyến qua GitHub Pages
1. Tạo một Repository mới trên GitHub.
2. Tải file `index.html` và `README.md` lên branch `main`.
3. Vào **Settings** ➔ **Pages** ➔ Tại mục **Build and deployment**, chọn Source là **Deploy from a branch** ➔ Branch: `main` / `/(root)` ➔ Bấm **Save**.
4. Chờ 1-2 phút, GitHub Pages sẽ cấp đường link trực tiếp có dạng:
   ```
   https://<ten-tai-khoan-github>.github.io/<ten-repository>/
   ```
