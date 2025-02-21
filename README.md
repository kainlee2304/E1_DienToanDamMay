# E1:Git Tutorial for beginners 
****
# Hướng dẫn các bước Git đã thực hiện

1. **Tải và cà đặt git, github**
2. **Tạo kho lưu trữ git cục bộ**
    - `D:` :chuyển từ ổ c sang ổ D
    - `cd thu_muc_muon_luu`:di chuyển đến thư mục muốn lưu
    - coppy file vào thư mục
    - `git init`:Khởi tạo repository Git
    - `dir \b`:liệt kê tệp có trong repo
3. **Khởi tạo và commit lần đầu:**

   - `git status`: Kiểm tra trạng thái của thư mục.
   - `git add .`: Thêm tất cả các file vào staging area.
   - `git commit -m "first commit"`: Tạo commit đầu tiên với message "first commit".

4. **Thêm remote và đổi tên branch:**

   - `git remote add origin https://github.com/kainlee2304/DienToanDamMay.git`: Liên kết local repository với remote repository trên GitHub.
   - `git branch -M main`: Đổi tên branch hiện tại thành "main".

5. **Push code lên remote:**

   - `git push origin main`:Đẩy branch "main" lên GitHub,Gửi (push) code từ local repository lên remote repository trên GitHub, giúp lưu trữ code trực tuyến.

6. **Tạo và checkout branch mới:**

   - `git branch my-new-branch`:Tạo branch mới tên là "my-new-branch"
   - `git checkout my-new-branch`:Chuyển sang branch mới

7. **Commit và push lên branch mới:**

   - `git add .`:Thêm tất cả thay đổi vào staging area
   - `git commit -m "commit branch"`:Tạo commit với message "commit branch"
   - `git push origin my-new-branch`:Đẩy branch mới lên GitHub

8. **Checkout lại main và pull code từ remote:**

   - `git checkout main`:Chuyển về branch "main"
   - `git pull origin main`:Lấy code mới nhất từ GitHub về máy

9. **Kiểm tra log:**

   - `git log`:Hiển thị danh sách commit theo thứ tự thời gian, bao gồm ID commit, tác giả, ngày giờ và thông điệp commit.
