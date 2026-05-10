# SQA Test Script Repository

Đây là kho lưu trữ (repository) chứa các kịch bản kiểm thử (Test Scripts) và công cụ liên quan cho dự án SQA.

## Hướng dẫn nộp file (Commit & Push) lên Repository

Dưới đây là các bước cơ bản để các thành viên trong nhóm có thể đóng góp và nộp file lên repo này một cách chuẩn xác:

### 1. Clone repository về máy (Lần đầu tiên)
Nếu bạn chưa có repo trên máy tính, hãy clone repo về:
```bash
git clone <đường_dẫn_repository_trên_github/gitlab>
```
*(Thay `<đường_dẫn_repository_trên_github/gitlab>` bằng link remote repo thực tế của dự án).*

### 2. Cập nhật code mới nhất (Rất quan trọng)
Trước khi bắt đầu làm việc hoặc tạo nhánh mới, luôn đảm bảo repo của bạn được cập nhật mới nhất từ nhánh chính (`main` hoặc `master`):
```bash
git pull origin main
```

### 3. Lưu lại các thay đổi (Add & Commit)
Sau khi thêm hoặc chỉnh sửa các file code, thực hiện các lệnh sau:
```bash
# Kiểm tra trạng thái các file đã thay đổi
git status

# Thêm tất cả các file thay đổi (hoặc thay "." bằng tên file cụ thể)
git add .

# Tạo commit với thông điệp rõ ràng, dễ hiểu
git commit -m "Mô tả ngắn gọn về những gì bạn vừa làm"
# Ví dụ: git commit -m "Thêm script test chức năng đăng nhập"
```

### 4. Đẩy code lên Remote Repository (Push)
```bash
git push
```

### 💡 Một số lưu ý chung:
Đã chia folder riêng, cứ copy paste thẳng vào đúng folder là được.