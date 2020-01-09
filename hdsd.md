Toàn b? code trong thu m?c resource
Luu ý: nên cho toàn b? code trong thu m?c resource ra thu m?c g?c (htdocs n?u dùng xampp, www n?u dùng appserv,...) khi dó file index.php và install.php s? n?m trong thu m?c htdocs (www, public_html,...) và ch?y theo du?ng d?n localhost ho?c domain.com, không nên d?t trong thu m?c con và ch?y localhost/resource ho?c domain.com/resource d? tránh l?i.
Ch?y domain/install.php d? ti?n hành cài d?t và c?u hình h? th?ng. N?u quá trình cài d?t x?y ra l?i, vui lòng ki?m tra các nguyên nhân du?i: 
1, C?p quy?n ghi cho thu m?c cài d?t (htdocs, www, ...) 
2, Xem l?i k?t n?i t?i database, ví d? tên user, tên database, m?t kh?u...
S?a URL trang web trong config/config.php
S?a tài kho?n g?i email quên m?t kh?u t?i /controllers/controller_login.php dòng 127, 128
Tài kho?n m?c d?nh: tài kho?n: admin m?t kh?u: 123456