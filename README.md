# tim_hieu_va_cai_dat_Apache_nodejs_nodered
##Bài tập 02: Lập trình web.
==============================
NGÀY GIAO: 19/10/2025
==============================
DEADLINE: 26/10/2025
==============================
#NỘI DUNG BÀI TẬP: 
1. Cài đặt Apache web server:<br>

   - em vô hiệu hóa IIS: mở cmd quyền admin để chạy lệnh: iisreset /stop<br>
   <img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/user-attachments/assets/d6648ce2-a140-44ff-b018-7546fa63a64d" /><br>
   
   - Em tải Apache:<br>
   <img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/acd5ab41-7f7d-43f7-9565-d8bbdf38c6e4" /><br>
   
   - Em cài và giải nén Apache sang ổ D của em:<br>
   <img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/8db75ed7-de76-46ad-abe4-eef6090a8f11" /><br>
   
   - Em đổi listen mặc định là 80:<br>
   <img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/2ba53ca5-120d-4743-a666-1761a6719b1d" /><br>
   
   - em đặt server naem.<br>
   <img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/64756bad-d5a1-44f1-b970-f955c2e50e85" /><br>
   
   - em Đảm bảo Include conf/extra/httpd-vhosts.conf không bị comment.<br>
   <img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/bce571bd-932d-40d2-970a-6d173eace785" /><br>
   
   - Sửa D:\Apache24\conf\extra\httpd-vhosts.conf — thêm VirtualHost cho domain<br>
  <img width="1920" height="1080" alt="Screenshot (13)" src="https://github.com/user-attachments/assets/856e9b39-97ec-44aa-88ab-9256f4599f8d" /><br>

   - em tạo thư mục web root:<br>
   <img width="1920" height="1080" alt="Screenshot (8)" src="https://github.com/user-attachments/assets/0d293e4c-cf7a-4442-a448-b1c04baabac4" /><br>
   
   - em tạo 1 file đuôii . html vào thu mục nguyentuananh:<br>
   <img width="1920" height="1080" alt="Screenshot (9)" src="https://github.com/user-attachments/assets/18fe2c4f-ef98-4817-b81b-0779da082109" /><br>
   
   - em cập nhật hosts file (c:\WINDOWS\SYSTEM32\Drivers\etc\hosts) bằng Notepad Run as administrator — thêm dòng:<br>
   <img width="1920" height="1080" alt="Screenshot (12)" src="https://github.com/user-attachments/assets/d66df32d-3cf9-4bd7-a744-819790c18e7f" /><br>

   - em cài và chạy Apache service (cmd admin):<br>
   <img width="1920" height="1080" alt="Screenshot (11)" src="https://github.com/user-attachments/assets/79d25f96-61b3-40c9-a8de-7403b06e1e39" /><br>
   
   - em đã cài Apache thành công!!<br>
   <img width="1920" height="1080" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/9aa5e753-60bf-4fe1-ac42-65f55eda0d81" /><br>
   
## 2. Cài đặt nodejs và nodered => Dùng làm backend:<br>

2.1 Cài đặt nodejs:<br>

   - em cài tiếp Node.js vào D:\nodejs<br>
   <img width="1920" height="1080" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/14985bbe-2f6b-4605-a4f7-d8d8e915bd31" /><br>
   
   - em kiểm tra xem có node.js chưa<br>
   <img width="1920" height="1080" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/6b2acb9b-87ee-4da1-898c-7425e944eaf3" /><br>
   
2.2 Cài đặt nodered:

   - em đã cài node-red thành công
   <img width="1920" height="1080" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/36f27ef1-779c-4177-8dfa-d4eafbf12936" />
   
   - em giải nén nssm.exe vào D:\nodejs\nodered\
   <img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/4ed93476-616e-4a3e-bb76-30eae1d18c91" />
   
   - em copy nssm.exe vào D:\nodejs\nodered\
   <img width="1920" height="1080" alt="Screenshot (20)" src="https://github.com/user-attachments/assets/7a560240-f197-44a9-b5c2-19d7a5943995" />
   
   - em đã cài và vào node-red thành công
   <img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/409e9d4a-8134-4c71-b7c7-59895ed5f443" />
   
2.3. Tạo csdl tuỳ ý trên mssql (sql server 2022)

   - Em tạo 1 database tùy ý trên sql server bằng tài khoản sa:
   <img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/f259ca9e-df87-4645-a71f-d4710d53407a" />
   
   - Em truy cập giao diện nodered bằng url: http://localhost:1880
    <img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/b0df8973-105d-4697-bc58-28ce57de643a" />
    
   - em cài đặt các thư viện theo thầy yêu cầu:
    <img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/6caa44ab-e6fb-4faf-ae06-126f26bc26c1" />
    
   - Em sửa file settings.js`
    <img width="1920" height="1080" alt="Screenshot (25)" src="https://github.com/user-attachments/assets/d886d72b-87dc-49b6-a17d-84a0c9188e5d" />
    
2.4. tạo api back-end bằng nodered:

     - em đã lôi ra được 4 node và đổi tên thành API tìm kiếm<br>
   <img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/69c1ba01-9739-4568-9b7b-b54c11b01d37" />
     
     - Cấu hình từng node:
       + cấu hình cho node http in 
   <img width="1920" height="1080" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/ddeb3b85-01c3-4946-a1e7-d2d960465fcb" />
       
       + cấu hình cho node function 
   <img width="1920" height="1080" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/86eed3b8-7104-4f0a-a915-c2ff64076f01" />
       
       * giải thích (Người dùng truy cập: http://localhost:1880/timkiem?q=VIP
         @q là tham số truyền vào câu lệnh SQL (giúp chống SQL injection)
         %VIP% giúp tìm mọi tên phòng chứa “VIP”

      + Cấu hình cho node MSSQL
   <img width="1920" height="1080" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/58a9b876-d157-4efa-a26c-3042145e2eec" />

      + Cấu hình cho node http response







   






   

   













