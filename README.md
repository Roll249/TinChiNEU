# TinChiNEU

Hệ thống đăng ký tín chỉ cho sinh viên Đại học Kinh tế Quốc dân.

## Tính năng

- Đăng nhập, đăng xuất
- Xem, tìm kiếm, đăng ký học phần
- Lưu kế hoạch học tập cá nhân
- Xem lịch sử đăng ký, thời khóa biểu
- Tích hợp với Firebase Firestore để lưu trữ dữ liệu

## Cài đặt

1. **Clone repository:**
   ```powershell
   git clone https://github.com/Roll249/TinChiNEU.git
   cd TinChiNEU\project
   ```

2. **Cài đặt các package cần thiết:**
   ```powershell
   npm install
   ```

3. **Cấu hình Firebase:**
   - Đặt file `serviceAccountKey.json` vào thư mục `project/config/`.

4. **Chạy server:**
   ```powershell
   npm start
   ```
   Server sẽ chạy tại `http://localhost:3000`.

5. **Truy cập giao diện web:**
   - Mở trình duyệt và truy cập `http://localhost:3000/view/index.html` hoặc các file HTML trong thư mục `view/`.

## Lưu ý

- **Không commit thư mục `node_modules`**. Đã có file `.gitignore` để loại trừ thư mục này.
- Dữ liệu khóa học được lấy từ Firestore, có thể import từ file Excel bằng script `uploadExcel.js`.

## License

MIT