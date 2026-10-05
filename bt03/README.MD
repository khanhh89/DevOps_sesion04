# Bài 3 - Cấu hình xác thực SSH và Đẩy dự án lên GitHub

## 1. Mục tiêu

- Khởi tạo cặp khóa SSH sử dụng thuật toán Ed25519.
- Cấu hình xác thực SSH với GitHub.
- Kiểm tra kết nối SSH tới GitHub.
- Cấu hình Git Remote sử dụng giao thức SSH.
- Đẩy mã nguồn và lịch sử commit lên GitHub bằng SSH.
- Không sử dụng HTTPS hoặc password/token khi push.

---

## 2. Môi trường thực hiện

- Hệ điều hành: Windows
- Git: Git for Windows
- GitHub: GitHub Repository
- Giao thức xác thực: SSH
- Thuật toán SSH: Ed25519

---

## 3. Tạo SSH Key Ed25519

Sử dụng lệnh:

```bash
ssh-keygen -t ed25519 -C "khanhabcabc0000@gmail.com"