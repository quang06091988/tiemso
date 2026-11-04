# Tiệm Số

Bán hàng, nhập hàng và tồn kho cho tiệm nhỏ. Một file `index.html`, không cần backend, dữ liệu lưu trong trình duyệt (IndexedDB).

- Tab: Bán, Nhập, Kho, Báo cáo, Cài đặt.
- Nhập file sao lưu JSON của Công cụ bán hàng (`ban-hang-local`) và Công cụ đặt hàng (`dat-hang-local`) ở Cài đặt.
- Triển khai: đẩy cả thư mục lên Vercel (static), không cần cấu hình build.
- Mỗi lần sửa `index.html`, tăng số phiên bản cache `V` trong `sw.js`.
