# Ứng dụng Flutter MVVM (Phiên bản DartPad)
## Chức năng chính
- Thêm dữ liệu mới
- Hiển thị danh sách dữ liệu ngay sau khi thêm
- Ứng dụng hoạt động hoàn toàn offline (không sử dụng mạng)

## Ghi chú về lưu trữ dữ liệu
Do môi trường **DartPad** không hỗ trợ các thư viện lưu trữ cục bộ như **Hive** hoặc **SQLite**,
bài làm sử dụng cơ chế lưu trữ tạm thời trong bộ nhớ (in-memory storage) để mô phỏng việc lưu trữ dữ liệu cục bộ.

Trong môi trường phát triển Flutter đầy đủ (Android Studio hoặc VS Code), 
có thể tích hợp **Hive** để lưu trữ dữ liệu vĩnh viễn trên thiết bị, đáp ứng hoàn toàn yêu cầu về lưu trữ cục bộ.

## Tác giả
Họ và tên: Võ Phúc Vinh
