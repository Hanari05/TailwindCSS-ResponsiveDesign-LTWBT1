## 📝 ĐỀ BÀI

Mở file `index.html`, sử dụng các class Tailwind CSS để tạo một **Khung thông báo / Giới thiệu khóa học** hoàn chỉnh với các yêu cầu giao diện sau:

---

### 1. Nội dung văn bản (Tùy chọn hoặc dùng mẫu bên dưới)
* **Tiêu đề:** `Khóa Học Lập Trình Giao Diện Web`
* **Mô tả:** `Nắm vững tư duy Mobile-First và xây dựng website chuẩn Responsive cực nhanh với Tailwind CSS.`
* **2 Nút bấm hành động:**
  * Nút 1: `Bắt đầu ngay` (Màu nổi bật: xanh/tím/cam...)
  * Nút 2: `Tìm hiểu thêm` (Màu nền xám hoặc viền mỏng)

---

### 2. Yêu cầu giao diện Responsive

* **Màn hình Điện thoại (Mobile - Mặc định dưới 768px):**
  * Khung bao ngoài có màu nền (màu tùy chọn), bo góc (`rounded-xl`), có khoảng cách đệm (`p-6`).
  * Toàn bộ chữ căn giữa (`text-center`).
  * 2 nút bấm xếp theo **hàng dọc** (`flex flex-col gap-3`), mỗi nút chiếm trọn **100% chiều ngang** (`w-full`).

* **Màn hình Máy tính (Desktop - Breakpoint `md:` từ 768px trở lên):**
  * Đệm trong rộng hơn (`md:p-12`).
  * Chuyển sang căn lề trái (`md:text-left`).
  * 2 nút bấm tự động xoay sang **hàng ngang** (`md:flex-row`), bề rộng nút co lại vừa chữ (`md:w-auto`).
  * Nút bấm có hiệu ứng đổi màu nhẹ khi rê chuột (`hover:bg-... transition`).

<img src="https://github.com/user-attachments/assets/5cf13201-ca6e-47e4-94b4-95f41257161c" alt="Giao diện mẫu" width="100%" />

---

## 🛠️ HƯỚNG DẪN NỘP BÀI

1. Bấm **Fork** repo về tài khoản cá nhân.
2. Clone repo về máy và tạo nhánh làm bài:
   ```bash
   git clone link-repo-fork-cua-ban
   cd TailwindCSS-ResponsiveDesign
   git checkout -b submission/MSSV-HoTen
