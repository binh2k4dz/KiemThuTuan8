# Báo Cáo Kiểm Thử API Bằng Postman

Ngày kiểm thử: 19/06/2025

Người kiểm thử: Vũ Duy Bình

1. Mục Tiêu Kiểm Thử: Sử dụng Postman để kiểm thử một API thực tế

2. Môi Trường Kiểm Thử: Postman.

3. Phương Pháp Kiểm Thử: Kiểm thử tự động và thủ công trên phần mềm Postman.

4. Kịch Bản Kiểm Thử Lần 1:

•	Tên Kịch Bản: Kiểm thử cơ bản của 1 URL

•	Mục đích: Test khả năng hoạt động của URL và phần mềm Postman

•	Phương thức HTTP (GET/POST/PUT/DELETE): GET

•	URL: https://pokeapi.co/api/v2/

•	Tham số: pokemon/ditto?size=4&is_xml=true

•	Kết quả mong đợi: Gửi yêu cầu thành công

•	Kết quả thực tế: Đã gửi yêu cầu thành công

•	Trạng thái: Thành công

•	Kết quả sau khi kiểm thử:

 ![image](https://github.com/user-attachments/assets/84815047-88e0-4f71-b904-b214f284edc5)

Kịch bản kiểm thử lần 2:

•	Tên kịch bản: Kiểm thử cơ bản của một URL với một tham số

•	Mục đích: Test khả năng hoạt động của URL và phần mềm Postman

•	Phương thức HTTP (GET/POST/PUT/DELETE): GET

•	URL: https://pokeapi.co/api/v2/

•	Tham số: beerType=light

•	Kết quả mong đợi: Gửi yêu cầu thành công

•	Kết quả thực tế: Gửi yêu cầu thất bại

•	Trạng thái: Không thành công

•	Kết quả sau khi kiểm thử:

 ![image](https://github.com/user-attachments/assets/50fdce65-fba8-4368-a609-ff50424b9263)

Kịch bản kiểm thử lần 3:

•	Tên Kịch Bản: Kiểm thử cơ bản của 1 URL với một tham số truyền vào

•	Mục đích: Test khả năng hoạt động của URL và phần mềm Postman

•	Phương thức HTTP (GET/POST/PUT/DELETE): GET

•	URL: https://pokeapi.co/api/v2/

•	Tham số: beerType=light

•	Kết quả mong đợi: Gửi yêu cầu thành công

•	Kết quả thực tế: Đã gửi yêu cầu thành công

•	Trạng thái: Thành công

•	Kết quả sau khi kiểm thử:

 ![image](https://github.com/user-attachments/assets/d3d8387e-0e61-4660-8311-047080f8a238)

5. Kết Quả Kiểm Thử: 

Tóm tắt kết quả kiểm thử, bao gồm số lượng kịch bản kiểm thử đã chạy, số lượng thành công, số lượng thất bại, và tỷ lệ thành công.

•	Số lượng kịch bản đã kiểm thử: 3

•	Số lần thành công: 2

•	Số lần thất bại: 1

•	Tỉ lệ thành công: 75%

6. Phát Hiện Lỗi: 

Chi tiết về lỗi, bao gồm:

•	ID Lỗi: 404 Not Found

•	Mô Tả Lỗi: Trang bạn đang tìm kiếm không tồn tại (404)

•	Mức Độ Ảnh Hưởng: Không

•	Ghi Chú/Đề Xuất: Sai URL và tham số
