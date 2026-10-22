### **Bài 1. README.md**

Dưới đây là bảng kiểm tra các thành phần đã hoàn thành trực tiếp trên tệp `README.md` ở thư mục gốc:

-   Heading 1: tên dự án
    
-    Ít nhất 2 heading cấp 2
    
-   Mô tả ngắn có cả in đậm và in nghiêng
    
-   Bảng Thư mục | Nội dung, ít nhất 3 dòng dữ liệu
    
-   Danh sách đánh số ít nhất 3 bước
    
-   Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
    
-    Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
    
-   Blockquote nhắc không upload .env
# Smart Food Project

> **Lưu ý bảo mật:** Tuyệt đối **không upload** tệp thông tin cấu hình nhạy cảm (`.env`) lên kho lưu trữ mã nguồn công khai (GitHub/GitLab) để tránh rò rỉ dữ liệu hệ thống.

## 1. Tổng quan dự án
Ứng dụng **Smart Food** là giải pháp quản lý đặt cơm sinh viên, giúp tối ưu hóa quy trình gọi món, quản lý thực đơn và tự động hóa việc tính toán thù lao cho các tác giả tham gia hệ thống. Dự án được phát triển nhằm *nâng cao hiệu suất vận hành* và mang lại **trải nghiệm đặt món trực tuyến mượt mà**.

## 2. Cấu trúc thư mục hệ thống
Dưới đây là sơ đồ tổ chức thư mục chính của dự án:

| Thư mục / Tệp | Nội dung mô tả chi tiết |
| :--- | :--- |
| `src` | Chứa mã nguồn logic ứng dụng (Python/Node.js) |
| `docs` | Tài liệu kỹ thuật SRS và các biểu mẫu quy hoạch |
| `data` | Thư mục chứa các tệp cơ sở dữ liệu Excel (`.xlsx`) |

## 3. Hướng dẫn khởi tạo dự án qua Terminal
Thực hiện các bước sau để thiết lập môi trường làm việc trên máy tính cá nhân:

1. Mở cửa sổ dòng lệnh PowerShell (hoặc Terminal) và di chuyển đến thư mục muốn tạo dự án.
2. Khởi tạo thư mục gốc và các thư mục con bằng lệnh CLI chuyên dụng.
3. Kiểm tra lại toàn bộ cấu trúc cây thư mục của dự án vừa tạo.

```powershell
mkdir SmartFoodProject
cd SmartFoodProject
New-Item -ItemType Directory src, docs, data
Get-ChildItem -Recurse -Force


## 4. Danh sách nhiệm vụ (Task List)

-   Hoàn thiện cấu trúc thư mục và tệp README.md gốc
    
-    Xây dựng mô hình cơ sở dữ liệu Excel và hàm VLOOKUP
    
-    Viết tài liệu đặc tả yêu cầu phần mềm (SRS)
    

```

---

### **Bài 2. Excel**

- **Số dòng còn hiển thị sau khi lọc (câu d):** 
  *(Điền số lượng dòng kết quả thực tế sau khi bạn áp dụng bộ lọc AutoFilter trên file `data/hoc_phi_thang_10.xlsx`, ví dụ: `15` hoặc `24` dòng tùy theo bộ dữ liệu thực tế).*



