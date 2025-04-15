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

##### 2.Đặt các khóa chính, khóa ngoại
###### Bảng gv:
![pk 1](https://github.com/user-attachments/assets/42128a3c-de1d-482c-8d7a-9758e29e0518)
###### Bảng monhoc:
![pk 2](https://github.com/user-attachments/assets/831fe4ea-24d2-4907-b29f-b54431651f92)
###### Bảng lop:
![pk 3](https://github.com/user-attachments/assets/62dc0fe4-3951-46e2-a6aa-9254826ac2f0)
###### Bảng phong:
![pk 4](https://github.com/user-attachments/assets/f7ede3ea-c3f0-4c83-bddd-d32a5fbfebe3)
###### Bảng tkb:
![fk 1](https://github.com/user-attachments/assets/6a12efd4-4bdb-43a8-b3b5-518de168cef0)
![fk 2](https://github.com/user-attachments/assets/8ddefb09-f4c7-45c1-bc89-4b15f1ec4771)
![fk 3](https://github.com/user-attachments/assets/0d39c67e-31c2-41d7-8dad-2f489b85458a)
![fk 4](https://github.com/user-attachments/assets/8028c445-9f0b-434d-9c32-dee95ffbbb00)
![pk 5](https://github.com/user-attachments/assets/81b74eb2-5c4c-412b-bc90-498bafb5eb6b)
