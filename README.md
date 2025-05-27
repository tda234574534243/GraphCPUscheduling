# GraphCPUscheduling

## Giới thiệu
Dự án mô phỏng các thuật toán lập lịch CPU (FCFS, SJF, Priority, Round Robin, ...) với giao diện trực quan, hỗ trợ nhập tiến trình, xem Gantt chart, và các chỉ số thời gian.

## Yêu cầu hệ thống
- Visual Studio Code 
- Cài live preview extension (hoặc các công cụ hỗ trợ debug web)

## Hướng dẫn chạy chương trình

**Cách 1. Clone hoặc tải mã nguồn về máy:**
   - Clone qua git:
     ```
     git clone https://github.com/tda234574534243/GraphCPUscheduling.git
     ```
   - Hoặc tải file ZIP và giải nén.
   - Sau đó chạy debug web trong Visual Studio Code

**Cách 2. Chạy chương trình:**
   - Mở file `index.html` trong thư mục dự án bằng trình duyệt (double click hoặc chuột phải chọn "Open with...").
   - Không cần chạy server, chỉ cần mở file HTML.

3. **Sử dụng chương trình:**
   - Nhập danh sách tiến trình (Burst Time, Arrival Time, Priority, ...).
   - Chọn thuật toán lập lịch muốn mô phỏng.
   - Nhấn nút "Run" để xem kết quả, Gantt chart và các chỉ số thời gian.
   - Có thể thêm, sửa, xóa tiến trình trực tiếp trên giao diện.

## Tùy chỉnh & Build lại
- **Chỉnh sửa giao diện:** Sửa file CSS trong `css/style.css`.
- **Chỉnh sửa thuật toán:** Sửa file JS trong `js/`.
## Những issues cần cải thiện
- **Cập nhật thêm dữ liệu từ các tiến trình thật** 
- **Thêm yếu tố i/o time**
---