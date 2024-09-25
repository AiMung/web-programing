# web programming
lập trình web của thầy Lê Gia Công -Trường đại học Đà Lạt
Thầy Lê Gia Công là một giảng viên nổi bật trong lĩnh vực lập trình web tại Trường Đại học Đà Lạt.
Sách của thầy không chỉ đơn thuần cung cấp kiến thức kỹ thuật mà còn mang lại cảm xúc và sự hứng thú cho người đọc. 
Thầy thường sử dụng phong cách giảng dạy và viết lôi cuốn, dễ tiếp cận, kết hợp giữa lý thuyết và thực hành một cách tinh tế.
Phong cách truyền cảm hứng: Thầy có khả năng truyền cảm hứng và động lực cho người học qua cách viết và giảng dạy của mình, khuyến khích người học không ngừng thử thách bản thân và phát triển kỹ năng.
Một số lý thuyết nên nhớ hihi
Trang web động

Trang web động (dynamic web page, live web page, hoặc interactive web page) là trang web mà nội dung của nó có thể thay đổi tùy thuộc vào ngữ cảnh và điều kiện khác nhau. Việc thay đổi có thể được thực hiện tại phía server (server-side), bằng các ngôn ngữ lập trình phía server, như C#, PHP, Java, Python, Ruby, JavaScript; hoặc tại phía client (client-side) bằng ngôn ngữ lập trình phía client, như JavaScript, hoặc kết hợp cả phía client và phía server bằng kĩ thuật Ajax.

1.1.2       Tạo liên kết
Trong HTML, sử dụng phần tử a để tạo các liên kết, a viết tắt của anchor (cái mỏ neo).

Muốn tạo liên kết cho một đoạn văn bản, chỉ việc bao đoạn văn bản đó bằng phần tử a, đi kèm là thuộc tính href cho biết nơi được liên kết đến, href là viết tắt của hypertext reference – tham chiếu tới siêu văn bản. Ví dụ,

[HTML]

<a href="http://www.google.com">Trang web của Google</a>

[Kết quả]

Đoạn mã HTML trên sẽ tạo ra liên kết cho chuỗi “Trang web của Google”, khi người dùng bấm vào chuỗi này, trình duyệt sẽ mở trang web có địa chỉ là “http://www.google.com”.
Để tạo liên kết cho hình ảnh, chỉ việc bao hình ảnh đó bằng phần tử a, đi kèm là thuộc tính href cho biết nơi được liên kết đến. Mà hình ảnh được tạo ra bằng phần tử img, do vậy thực tế là đặt phần tử img vào trong phần tử a. Ví dụ,

[HTML]

<a href="http://www.google.com"><img src="logo.gif" alt="logo cong ty"></a>

[Kết quả]

Khi người dùng bấm vào hỉnh ảnh trên giao diện trang web, trình duyệt sẽ mở trang web có địa chỉ là “http://www.google.com”.
