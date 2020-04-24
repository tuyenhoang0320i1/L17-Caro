# L17-Caro

[Bài tập] Phát triển trò chơi cờ ca-ro
Mục tiêu
Luyện tập sử dụng các đối tượng đơn giản.

Mô tả
Phát triển trò chơi cờ Ca-ro với các tính năng đơn giản được mô tả như sau:

Hiển thị bàn cờ với 20 dòng và 20 cột
Có 2 người chơi
Khi nhấn vào các ô còn trống thì lần lượt hiện lên dấu 'X' hoặc 'O' tuỳ theo lượt của người chơi
Nếu có 5 ô liền nhau là X hoặc O thì người chơi sở hữu hàng đó sẽ thắng
Các hàng có thể là ngang, dọc hoặc chéo
Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub
Dán link của repository lên phần nộp bài trên CodeGymX
Hướng dẫn
Bước 1: Sử dụng thẻ div để vẽ 20 dòng và 20 cột

Các ô có thuộc tính position là absolute.
Sử dụng các thuộc tính left và top để quy định vị trí cho các ô
Dùng mảng 2 chiều để lưu giá trị của các ô
Bước 2: Xử lý sự kiện click chuột

Khi xảy ra sự kiện click chuột thì lấy về toạ độ chuột
Tính số thứ tự của dòng và cột vừa được click
Hiển thị dấu X hay O thay phiên nhau
Có thể dùng ảnh hoặc dùng chữ (X và O)
Bước 3: Tìm người thắng

Cứ mỗi lần có lượt chơi mới thì duyệt qua toàn bộ mảng 2 chiều để đếm
Nếu có 5 ô liền nhau cùng là X hoặc O thì thông báo người thắng cuộc và dừng trò chơi
Bước 4: Bổ sung và tuỳ chỉnh các tính năng khác theo ý muốn.

Xem demo ở đây: http://demo.codegym.vn/web/11/caro/
