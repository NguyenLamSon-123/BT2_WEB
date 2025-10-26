### BT2_WEB
# HỌ VÀ TÊN: NGYỄN LAM SƠN 
# MSSV: K225480106076
## BÀI LÀM 
### Câu 1: Dowload APACHE
# <img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/20e97ec7-866f-4978-a179-f59db8b6f93b" /> <br>
# <img width="774" height="201" alt="image" src="https://github.com/user-attachments/assets/849a9916-18c2-4295-aaba-5ca6baa18b06" /> <br>
## - Tắt, vô hiêu hóa iis 
# <img width="1090" height="645" alt="image" src="https://github.com/user-attachments/assets/653b719c-49eb-4acd-8c0e-35e8653e06b0" /> <br>
## - Cấu hình Apache để chạy website với domain fullname.com
## - Sửa file httpd-vhost.conf
# <img width="839" height="341" alt="image" src="https://github.com/user-attachments/assets/b342e8b9-cc24-4d57-93b0-a331701dd13f" /> <br>
# <img width="661" height="257" alt="image" src="https://github.com/user-attachments/assets/083fd5e3-9b85-4042-94fe-e86f6169786b" /> <br>
## - fake ip cho domain 
# <img width="673" height="262" alt="image" src="https://github.com/user-attachments/assets/77b0ef51-4bf4-4cde-9181-a4e946914640" /> <br>
# <img width="1005" height="455" alt="image" src="https://github.com/user-attachments/assets/84910441-841d-470d-b09f-cf2b69f5d299" /> <br>
# <img width="670" height="460" alt="image" src="https://github.com/user-attachments/assets/887149d8-6322-44b4-abc0-8c9ac0395906" /> <br>
### Câu 2: Doaload not.red
# <img width="855" height="326" alt="image" src="https://github.com/user-attachments/assets/323b3e78-62a4-4f13-9764-59e67d2f411f" /> <br>
# <img width="1103" height="653" alt="image" src="https://github.com/user-attachments/assets/f03fe297-838b-477c-91ed-6683ac802a40" /> <br>
## - cài đặt noderd 
# <img width="867" height="592" alt="image" src="https://github.com/user-attachments/assets/35b8303a-0079-4928-81f8-d49f295e6805" /> <br>
## - sau đó copy file nssm sang thư mục noderd ( cấp quyền sử dụng )
# <img width="920" height="556" alt="image" src="https://github.com/user-attachments/assets/a95171ee-e105-4523-8553-08a8d4d1934d" /> <br>
# <img width="945" height="862" alt="image" src="https://github.com/user-attachments/assets/e574a763-ba19-471a-ae1c-e318d43d0bea" /> <br>
## - Với cmd chạy và kiểm tra trạng thái chạy 
# <img width="1108" height="666" alt="image" src="https://github.com/user-attachments/assets/faeb1ef0-d57a-42ce-a352-35601d2ac94a" /> <br>
### Câu 3: tạo csdl tùy ý trên sql nhớ các thông số kết nối: ip, port, username, password, db_name, table_name
# <img width="1630" height="776" alt="image" src="https://github.com/user-attachments/assets/165baaff-d1e4-40f9-b4c7-ccbe28e09de6" /> <br> 
## - cài đặt thư viện trên nodered
## - truy cập theo địa chỉ: http://127.0.0.1:1880/
# <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/d3577bba-6906-4fc0-987b-b6b5a7f9919e" /> <br>
## - cài đặt thư viện trên nodered theo yêu cầu 
# <img width="1000" height="791" alt="image" src="https://github.com/user-attachments/assets/ed985711-1cac-49fa-a17d-cc0ce09f540c" /> <br>
## - mẫ hóa password 
# <img width="1166" height="667" alt="image" src="https://github.com/user-attachments/assets/eddf2f5f-b084-4d8f-aacd-3ee1854d2b9c" /> <br>
## - khởi động lại nodered 
# <img width="695" height="367" alt="image" src="https://github.com/user-attachments/assets/a6705453-f0aa-4892-afe3-5a65715021ff" /> <br>
## - Đăng đăng nhập địa chỉ http://localhost:1880 sau khi khởi động lại 
# <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f1caac51-da0d-4570-8e60-2d5b171963bb" /> <br>
### Câu 4: Tạo api back-end bằng nodered
## - tại flow1 trên nodered, sử dụng node `http in` và `http response` để tạo api
# <img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/46b1c001-da14-4558-ac15-b07a01b7056c" /> <br>
## - Nhập các thông tin từ Database để deploy 
# <img width="1918" height="1072" alt="image" src="https://github.com/user-attachments/assets/56171838-4c81-481a-86e6-c2f4f7411eaa" /> <br>
# <img width="1918" height="1071" alt="image" src="https://github.com/user-attachments/assets/f533e90f-bfa6-42bf-b56b-1755939bbbe2" /> <br>
## -  http response: để phản hồi dữ liệu về client: Status Code=200, Header add : Content-Type = application/json
# <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f7965077-ccf2-4891-84a0-58ede8464740" /> <br>
## - code timf thông tin trong bảng đã tạo ( có thể edit ) 
# <img width="1812" height="989" alt="image" src="https://github.com/user-attachments/assets/56eaf25d-a62e-4c7a-a487-8be637f91feb" /> <br>
## - sau khi Hoàn Thành Và Deploy 
# <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/67796ff6-f56c-4f98-989b-542f165c3c02" /> <br>
## - Kết Quả Nhận Vê 
# <img width="688" height="372" alt="image" src="https://github.com/user-attachments/assets/9fc54ba0-bcbe-4c2e-8476-3b44030eeb28" /> <br>
### Câu 5: Tạo giao diện front-end:
## - html form gồm các file : index.html, fullname.js, fullname.css
## - cả 3 file này đặt trong thư mục: `D:\Apache24\fullname`
# <img width="907" height="851" alt="image" src="https://github.com/user-attachments/assets/ff3e6909-4589-4781-9cfc-9368fa5a94c3" /> <br>
## - sự dụng VisuaCode để mở Front-end thông qua sever
# <img width="1050" height="1025" alt="image" src="https://github.com/user-attachments/assets/d8965f8c-f6e5-4798-87d9-8ad9a467fae8" /> <br>
## - gọi API TỪ BE nodered và được kết quả 
# <img width="1742" height="997" alt="image" src="https://github.com/user-attachments/assets/8fdc76db-a67c-4670-82e4-ee19caeea4a3" /> <br?
## NHẬN XÉT VỀ BÀI LÀM CỦA MÌNH 
## 1. Hiểu quá trình cài đặt phần mềm và thư viện
Em đã thực hiện đầy đủ và chính xác các bước:
- Vô hiệu hóa IIS để tránh xung đột cổng với Apache
- Cài đặt Apache và cấu hình httpd.conf, httpd-vhosts.conf để tạo domain cá nhân hóa (nguyenlamson.com)
- Sử dụng file hosts để ánh xạ domain về 127.0.0.1 – rất chuyên nghiệp
- Cài đặt Node.js và Node-RED vào thư mục riêng, dùng nssm để tạo service – cho thấy em hiểu cách chạy nền ổn định
- Biết cách cài thư viện Node-RED qua giao diện và chỉnh sửa settings.js để bật bảo mật admin – đây là điểm cộng lớn
## Kết luận: Em đã hiểu rõ cách cài đặt và cấu hình môi trường phát triển web và backend
## 2. Hiểu cách sử dụng Node-RED để tạo API back-end
Em đã:
- Tạo flow gồm 4 node: http in → function → MSSQL → http response
- Biết cách dùng function để xử lý dữ liệu đầu vào
- Biết cách truy vấn CSDL SQL Server qua node MSSQL
- Thiết lập phản hồi JSON chuẩn với Content-Type: application/json
- Test API bằng URL có query string ( http://localhost:1880/nguyenlamson ) – rất thực tế
## Kết luận: Em đã hiểu rõ cách dùng Node-RED như một công cụ backend để tạo API RESTful, xử lý logic và kết nối cơ sở dữ liệu.
## 3. Hiểu cách front-end tương tác với back-end
Em đã:
- Tạo giao diện HTML, CSS, JS đặt đúng thư mục Apache
- Sử dụng JavaScript để gọi API Node-RED bằng fetch()
- Hiển thị dữ liệu JSON trả về lên giao diện bằng bảng HTML
- Biết cách xử lý lỗi kết nối, hiển thị thông báo, và làm đẹp giao diện
## Kết luận: Em đã hiểu cách front-end gửi yêu cầu đến API, nhận dữ liệu JSON và hiển thị kết quả một cách trực quan

































 

 


