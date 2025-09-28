## THÔNG TIN CÁ NHÂN
#### Họ và tên: Nguyễn Đức Việt
#### Mã sinh viên: K225480106075
#### Lớp: K58KTP
### TẠO SOLUTION GỒM CÁC PROJECT SAU: ###
1. DLL đa năng, keyword: c# window library -> **Class Library (.NET Framework)** bắt buộc sử dụng **.NET Framework 2.0**: giải bài toán bất kỳ, độc lạ càng tốt, phải có dấu ấn cá nhân trong kết quả, biên dịch ra DLL. DLL độc lập vì nó ko nhập, ko xuất, nó nhận input truyền vào thuộc tính của nó, và trả về dữ liệu thông qua thuộc tính khác, hoặc thông qua giá trị trả về của hàm. Nó độc lập thì sẽ sử dụng được trên app dạng console (giao diện dòng lệnh - đen sì), cũng sử dụng được trên app desktop (dạng cửa sổ), và cũng sử dụng được trên web form (web chạy qua iis).
2. Console app, bắt buộc sử dụng **.NET Framework 2.0**, sử dụng được DLL trên: nhập được input, gọi DLL, hiển thị kết quả, phải có dấu án cá nhân. keyword: c# window Console => **Console App (.NET Framework)**, biên dịch ra EXE
3. Windows Form Application, bắt buộc sử dụng **.NET Framework 2.0****, sử dụng được DLL đa năng trên, kéo các control vào để có thể lấy đc input, gọi DLL truyền input để lấy đc kq, hiển thị kq ra window form, phải có dấu án cá nhân; keyword: c# window Desktop => **Windows Form Application (.NET Framework)**, biên dịch ra EXE
4. Web đơn giản, bắt buộc sử dụng **.NET Framework 2.0**, sử dụng web server là IIS, dùng file hosts để tự tạo domain, gắn domain này vào iis, file index.html có sử dụng html css js để xây dựng giao diện nhập được các input cho bài toán, dùng mã js để tiền xử lý dữ liệu, js để gửi lên backend. backend là api.aspx, trong code của api.aspx.cs thì lấy được các input mà js gửi lên, rồi sử dụng được DLL đa năng trên. kết quả gửi lại json cho client, js phía client sẽ nhận được json này hậu xử lý để thay đổi giao diện theo dữ liệu nhận dược, phải có dấu án cá nhân. keyword: c# window web => **ASP.NET Web Application (.NET Framework)** + tham khảo link chatgpt thầy gửi. project web này biên dịch ra DLL, phải kết hợp với IIS mới chạy được.
### CHÚ Ý ###
1. ĐƯỢC THAM KHẢO AI
2. KO ĐƯỢC CLONE BÀI BẠN KHÁC VỚI BẤT KỂ LÝ DO GÌ
3. Thời gian trên github ko fake được, mọi thay đổi đều lưu vết thời gian và nội dung sửa đổi.
4. bắt buộc sử dụng **.NET Framework 2.0** cho cả 4 project.
5. mọi project đều phải có dấu ấn cá nhân (tự do sáng tạo dấu ấn cá nhân, ko có bất kỳ khuôn mẫu nào!)
6. deadline: 2025-09-28 (dấu thời gian sau ngày này là dead), cuối kì thầy sẽ tổng hợp link các repository này để chấm điểm.
7. mọi hình thức vi phạm, chỉ cần 1 lần: đều bị cấm thi, miễn thi lại.
### Bai lam
Tạo solution
<img width="1920" height="1080" alt="Ảnh chụp màn hình (450)" src="https://github.com/user-attachments/assets/3775282d-7ea9-4269-a966-803a82755962" />
tạo project
<img width="1920" height="1080" alt="Ảnh chụp màn hình (450)" src="https://github.com/user-attachments/assets/7b317e74-b736-4a24-ba53-29299b8aa506" />
<img width="1920" height="1080" alt="Ảnh chụp màn hình (454)" src="https://github.com/user-attachments/assets/a2ca6945-bc2e-4841-92c9-535909b801fc" />
<img width="1920" height="1080" alt="Ảnh chụp màn hình (455)" src="https://github.com/user-attachments/assets/8f7e131e-27e5-47c9-b018-4407fa7e5308" />
<img width="1920" height="1080" alt="Ảnh chụp màn hình (459)" src="https://github.com/user-attachments/assets/a023237c-5920-4bdf-bef8-adf4ee74889d" />

##### Tạo file index.html
Nháy chuột phải Project -> Add -> New Item -> HTML Page -> Đặt tên index.html  
Tạo file index.html với HTML + CSS để hiển thị giao diện, và JavaScript để xử lý sự kiện.
##### Tạo file api.aspx
Nháy chuột phải Project -> Add -> New Item -> WebForm -> Đặt tên api.aspx  
Mở api.aspx, để trống nội dung markup, thêm code cho file.
##### Cấu hình IIS và domain
Mở Control Panel -> Programs -> Turn Windows features on or off -> Tick Internet Information Services -> OK.  
Mở IIS Manager -> Add Website  
Thêm domain vào file hosts:
  - Notepad -> Run as Administrator
  - Open file C:\Windows\System32\drivers\etc\hosts
#### Chạy thử chương trình
<img width="1920" height="901" alt="Ảnh chụp màn hình (468)" src="https://github.com/user-attachments/assets/a3ed6c17-1d94-43f4-8ecb-d6b87e07d6e9" />
