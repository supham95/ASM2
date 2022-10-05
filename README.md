# ASSIGNMENT 2 - Test Grade Calculator
Test Grade Calculator là chương trình để tính toán điểm thi cho nhiều lớp với sĩ số hàng nghìn học sinh. Mục đích của chương trình giúp giảm thời gian chấm điểm.

## Điều kiện tiên quyết
*Trước khi tiếp tục, hãy đảm bảo bạn đáp ứng các yêu cầu sau:*
  * Bạn đã cài đặt phiên bản Python từ 3.9 trở lên
  * Bạn đã cài đặt các thư viện Python: pandas, re
  
## Cách sử dụng
*Chương trình sẽ áp dụng các functions (hàm) khác nhau trong Python để viết chương trình với các tác vụ sau*
### 1. Mở các tập tin văn bản bên ngoài được yêu cầu với exception-handling
* Tạo một chương trình Python mới có tên “lastname_firstname_grade_the_exams.py.” (*Đảm bảo tệp mã nguồn của bạn nằm trong cùng thư mục với tệp dữ liệu bạn vừa tải xuống*)
* Viết một chương trình cho phép người dùng nhập tên của một tệp và truy cập đọc.
* Nếu tệp tồn tại, bạn có thể in ra một thông báo xác nhận. Nếu tệp không tồn tại, bạn nên cho người dùng biết rằng không thể tìm thấy tệp và nhắc lại họ.
* Sử dụng try/except để thực hiện việc này.

### 2. Quét từng dòng của câu trả lời bài thi để tìm dữ liệu hợp lệ và cung cấp báo cáo tương ứng
* Phân tích dữ liệu có trong tệp vừa mở để đảm bảo đúng định dạng: 
    - Giá trị đầu tiên là số ID của sinh viên.
    - 25 chữ cái sau là câu trả lời của học sinh cho kỳ thi.
    - Tất cả các giá trị được phân tách bằng dấu phẩy.
* Báo cáo tổng số dòng dữ liệu được lưu trữ trong tệp.
* Báo cáo tổng số dòng dữ liệu không hợp lệ trong tệp, các dòng không hợp lệ sẽ in ra một thông báo lỗi.

### 3. Chấm điểm từng bài thi dựa trên tiêu chí đánh giá (rubric) được cung cấp và báo cáo
* Viết một chương trình để chấm điểm các bài thi cho một phần nhất định
* Đếm số lượng học sinh đạt điểm cao (>80).
* Điểm trung bình.
* Điểm cao nhất.
* Điểm thấp nhất.
* Miền giá trị của điểm (cao nhất trừ thấp nhất).
* Giá trị trung vị
* Trả về các câu hỏi bị học sinh bỏ qua nhiều nhất theo thứ tự: số thứ tự câu hỏi - số lượng học sinh bỏ qua -  tỉ lệ bị bỏ qua (nếu có cùng số lượng cho nhiều câu hỏi bị bỏ thì phải liệt kê ra đầy đủ).
* Trả về các câu hỏi bị học sinh sai qua nhiều nhất theo thứ tự: số thứ tự câu hỏi - số lượng học sinh trả lời sai - tỉ lệ bị sai (nếu có cùng số lượng cho nhiều câu hỏi bị sai thì phải liệt kê ra đầy đủ).

### 4. Tạo tập tin kết quả được đặt tên thích hợp
* Tạo một tệp “kết quả” chứa các kết quả chi tiết cho từng học sinh trong lớp của bạn.
* Mỗi dòng của tệp này phải chứa số ID của học sinh, dấu phẩy và sau đó là điểm của họ.
* Bạn nên đặt tên tệp này dựa trên tên tệp gốc được cung cấp — ví dụ: nếu người dùng muốn phân tích “class1.txt”, bạn nên lưu trữ kết quả trong tệp có tên “class1_grades.txt”.

## Nguồn tài liệu tham khảo
* [Funix](https://courses.funix.edu.vn/courses/course-v1:FUNiX+DSP301x_1.2-A_VN+2022_T2/info)
* [hocexcel.online](https://blog.hocexcel.online/68-dong-code-python-hay-su-dung-xu-ly-du-lieu-trong-pandas.html)

## Người đóng góp

## Thông tin liên lạc
* Email: *supcfx16803@funix.edu.vn*
