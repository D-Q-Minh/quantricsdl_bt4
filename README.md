## Bài tập 04 của sv: k225480106047 - Dương Quang Minh - Môn Hệ quản trị csdl
### bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.
các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó
Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
deadline: 15/4/2025
## Bài làm:
##### 1.Tạo cơ sở dữ liệu
![1](https://github.com/user-attachments/assets/83fda984-b8cc-4176-bc5e-c0bd349781dc)
###### Tạo các bảng gv, monhoc, lop, phong, tkb
###### Bảng gv:
![2](https://github.com/user-attachments/assets/8617fe44-4b99-48a5-b779-39db12105d3c)
###### Bảng monhoc:
![3](https://github.com/user-attachments/assets/7bc09fe1-c0e6-46d1-9b15-b1c008dcc2b4)
###### Bảng lop:
![4](https://github.com/user-attachments/assets/ccb879f4-6731-43a6-9eff-e930a94b8143)
###### Bảng phong:
![5](https://github.com/user-attachments/assets/2492649a-9f2c-4b7f-b6ff-c7c8aba8cf2c)
###### Bảng tkb:
![image](https://github.com/user-attachments/assets/12784299-6255-4575-aabc-787dffe8df73)

##### 
