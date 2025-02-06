# Git Commands Cheat Sheet

## 1. Cấu hình Git
```sh
git config --global user.name "Tên của bạn"
git config --global user.email "email@example.com"
```
*Cấu hình tên và email để commit được xác định danh tính.*

## 2. Khởi tạo và sao chép repo
```sh
git init
```
*Khởi tạo một kho Git mới trong thư mục hiện tại.*

```sh
git clone <URL>
```
*Sao chép một repository từ GitHub hoặc một nguồn khác về máy.*

## 3. Trạng thái và lịch sử
```sh
git status
```
*Kiểm tra trạng thái của các tệp trong repo.*

```sh
git log
```
*Xem lịch sử commit.*

## 4. Thêm và commit file
```sh
git add <tên_file>
```
*Thêm một tệp vào staging area.*

```sh
git add .
```
*Thêm tất cả các tệp đã chỉnh sửa vào staging.*

```sh
git commit -m "Thông điệp commit"
```
*Tạo một commit với thông điệp mô tả thay đổi.*

## 5. Làm việc với nhánh (Branch)
```sh
git branch
```
*Xem danh sách các nhánh hiện có.*

```sh
git branch <tên_nhánh>
```
*Tạo một nhánh mới.*

```sh
git checkout <tên_nhánh>
```
*Chuyển sang nhánh khác.*

```sh
git checkout -b <tên_nhánh>
```
*Tạo và chuyển sang nhánh mới cùng lúc.*

```sh
git merge <tên_nhánh>
```
*Gộp một nhánh vào nhánh hiện tại.*

## 6. Đẩy và kéo dữ liệu từ remote
```sh
git remote add origin <URL>
```
*Kết nối repo với remote trên GitHub/GitLab.*

```sh
git push -u origin <tên_nhánh>
```
*Đẩy nhánh lên remote lần đầu tiên.*

```sh
git push
```
*Đẩy các thay đổi lên remote.*

```sh
git pull
```
*Kéo các thay đổi mới nhất từ remote về.*

## 7. Khôi phục thay đổi
```sh
git reset --hard <commit_id>
```
*Quay lại một commit trước đó và mất mọi thay đổi.*

```sh
git revert <commit_id>
```
*Tạo một commit mới để hoàn tác commit trước đó.*

```sh
git stash
```
*Lưu tạm thay đổi mà không commit.*

```sh
git stash pop
```
*Khôi phục lại các thay đổi đã stash.*

## 8. Xóa file hoặc nhánh
```sh
git rm <tên_file>
```
*Xóa một file và thêm thay đổi vào staging.*

```sh
git branch -d <tên_nhánh>
```
*Xóa một nhánh (chỉ xóa được nếu nhánh đã merge).*

```sh
git branch -D <tên_nhánh>
```
*Xóa một nhánh ngay cả khi chưa merge.*

---

> Đây là những lệnh Git cơ bản giúp bạn làm việc hiệu quả hơn. 🚀
