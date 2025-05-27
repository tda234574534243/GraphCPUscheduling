## Giới thiệu
Dự án mô phỏng các thuật toán lập lịch CPU (FCFS, SJF, Priority, Round Robin, ...) với giao diện trực quan, hỗ trợ nhập tiến trình, xem Gantt chart, và các chỉ số thời gian.

## Yêu cầu hệ thống
- Visual Studio Code 
- Cài live preview extension (hoặc các công cụ hỗ trợ debug web
- ![chương trình](images/cap1.JPG)

## Hướng dẫn chạy chương trình

**Cách 1. Clone hoặc tải mã nguồn về máy:**
   - Clone qua git:
     ```
     git clone https://github.com/tda234574534243/GraphCPUscheduling.git
     ```
   - Hoặc tải file ZIP và giải nén.
   - Sau đó chạy debug web trong Visual Studio Code.

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
## Nguồn gốc mã nguồn
- Dự án này sử dụng mã nguồn từ [Mukul Agrawal](https://github.com/mukul2310/cpu-scheduler-visualiser) theo giấy phép MIT.
## Chỉnh sửa mã nguồn
- Bổ sung giao diện tiếng Việt
- Sửa lỗi thuật toán chạy ưu tiên sai tiên trình ở Ready Queue.
- Tối ưu thuật toán, cải thiện giao diện mô phỏng.
- Cập nhật thêm thông số chi tiết từng tiến trình.
- Cập nhật xuất file pdf.
- Giao diện chỉnh sửa sao cho gọn gàng, xuất ra màn hình thuật toán cần thiết.
---
