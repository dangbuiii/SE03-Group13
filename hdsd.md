Toàn bộ code trong thu mục resource
Luu ý: nên cho toàn bộ code trong thu mục resource ra thu mục gốc (htdocs nếu dùng xampp, www nếu dùng appserv,...) khi dó file index.php và install.php sẽ nằm trong thu mục htdocs (www, public_html,...) và chạy theo đường dẫn localhost, không nên đặt trong thư mục con và chạy localhost/resource hoặc domain.com/resource để tránh lỗi.
Chạy domain/install.php để tiến hành cài đặt và cấu hình hệ thống. Nếu quá trình cài đặt xảy ra lỗi, vui lòng kiểm tra các nguyên nhân dưới: 
1, Cấp quyền ghi cho thư mục cài đặt (htdocs, www, ...) 
2, Xem lỗi kết nối tới database, ví dụ tên user, tên database, mật khẩu...
Sửa URL trang web trong config/config.php
Sửa tài khoản gửi email quên mật khẩu tại /controllers/controller_login.php dòng 127, 128
Tài khoản mặcc định: tài khoản: admin 
                     mật khẩu: 123456
