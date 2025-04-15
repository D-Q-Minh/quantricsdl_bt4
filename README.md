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
![4](https://github.com/user-attachments/assets/0515d83a-c24e-43dd-b576-e23011ab053f)
###### Bảng phong:
![5](https://github.com/user-attachments/assets/accc263b-5f3e-4f55-b0b5-fb32f6017912)
###### Bảng tkb:
![6](https://github.com/user-attachments/assets/e013bb81-1b2c-4da5-a1f2-947a5edadeb5)

##### 2.Đặt các khóa chính, khóa ngoại
###### Bảng gv:
![pk 1](https://github.com/user-attachments/assets/42128a3c-de1d-482c-8d7a-9758e29e0518)
###### Bảng monhoc:
![pk 2](https://github.com/user-attachments/assets/831fe4ea-24d2-4907-b29f-b54431651f92)
###### Bảng lop:
![4](https://github.com/user-attachments/assets/dd3472aa-78d8-4fbb-9fd0-27cf0b7a9330)
###### Bảng phong:
![5](https://github.com/user-attachments/assets/fad1fe7b-1dbe-44aa-b224-c3fed63e077a)s
###### Bảng tkb:
![fk 1](https://github.com/user-attachments/assets/6a12efd4-4bdb-43a8-b3b5-518de168cef0)
![fk 2](https://github.com/user-attachments/assets/8ddefb09-f4c7-45c1-bc89-4b15f1ec4771)
![fk 3](https://github.com/user-attachments/assets/0d39c67e-31c2-41d7-8dad-2f489b85458a)
![fk 4](https://github.com/user-attachments/assets/8028c445-9f0b-434d-9c32-dee95ffbbb00)
![pk 5](https://github.com/user-attachments/assets/81b74eb2-5c4c-412b-bc90-498bafb5eb6b)

![pk 6](https://github.com/user-attachments/assets/1937c371-5551-4c65-a64f-68711bb2b6fc)

#### 3.Thêm dữ liệu từ tms.tnut.edu.vn
###### Copy dữ liệu từ nguồn TMS.tnut.edu.vn, patse vào Excel sau đó thực hiện dán các dữ liệu cần thiết vào các bảng ở mục
###### Bảng gv:
![dl 1](https://github.com/user-attachments/assets/e691e2ab-54c2-4b85-9b37-dc08e05ce8a9)
###### Bảng monhoc:
![dl 2](https://github.com/user-attachments/assets/4cf0c4c4-dfcf-4091-980c-dc0c0a55589b)
###### Bảng lop:
![dl 3](https://github.com/user-attachments/assets/37c3e662-fe71-40d3-98af-382e076f2d9d)
###### Bảng phong:
![dl 4](https://github.com/user-attachments/assets/e3f46181-3c2a-4bd8-a02a-ccb87fc5f5c0)
###### Bảng tkb:
