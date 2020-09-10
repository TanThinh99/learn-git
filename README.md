 ============ Learn git ==================

Cac buoc tao mot git moi:

B1: Vào bên trong thư mục muốn tạo ta chạy lệnh này (chỉ cần làm một lần khi chọn nơi dùng git)
--> git init

B2: Để kiểm tra trạng thái các file bên trong thư mục, chạy lệnh này:
--> git status

B3: Để xác nhận file (được tạo mới, có thay đổi nội dung bên trong hoặc bị xóa) trong thư mục, ta chạy lệnh này
--> git add {Tên file}
VD: git add abc.txt
Để xác nhận nhiều file cùng lúc, dùng lệnh: git add .

B4: Để commit (đóng gói và lưu lên git -> lưu lại các thay đổi trong thư mục), ta chạy lệnh này:
--> git commit -m "câu mô tả cho sự thay đổi"

============= Một số thuật ngữ =============
Working dir: vùng làm việc với git trên máy (khu vực thư mục được chọn làm việc với git)

Staging area: Là khu vực chứa các file đã được xác nhận (khi người dùng dùng lệnh git add {tên file})

Git repository: khu vực lưu lại vào git sau khi người commit


=============== Một số lệnh git khác ================
git show   : dùng để xem những thay đổi của những file
git log    : xem lại nhật ký commit
git diff   : dùng để xem thay đổi của file (chỉ dùng được với file được thay đổi _ modified)
git checkout -- {tên file} : dùng để xóa bỏ những thay đổi đối với file đã được thay đổi nhưng chưa được xác nhận (file chưa được đưa vào staging area)
git reset  : dùng để bỏ xác nhận đối với file (đưa file ra khỏi staging area)
