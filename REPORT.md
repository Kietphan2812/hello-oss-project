# Báo cáo thực hành 7.8: Tài liệu và giấy phép OSS

**Sinh viên:** PHAN TẤN KIỆT 
**Repository:** https://github.com/Kietphan2812/hello-oss-project

## 1. Phân tích dự án OSS: psf/requests

- **README.md:** nêu rõ mục tiêu (thư viện HTTP đơn giản cho Python), cách cài
  đặt bằng pip, ví dụ gửi request, và liên kết tới tài liệu đầy đủ.
- **CONTRIBUTING.md:** có. Hướng dẫn báo lỗi qua Issue (nêu phiên bản, cách
  tái hiện) và gửi Pull Request (fork, tạo nhánh, thêm test, chạy kiểm tra style).
- **Giấy phép:** Apache License 2.0, thuộc nhóm permissive.
- **Nhận xét:** Tài liệu rõ ràng, ví dụ ngắn gọn, người mới bắt đầu nhanh.
  README gọn, chi tiết được tách sang tài liệu riêng. Apache 2.0 cho phép dùng,
  sửa, phân phối kể cả thương mại mà không phải công khai mã phái sinh, lại có
  điều khoản cấp quyền bằng sáng chế, nên doanh nghiệp yên tâm dùng. Quy trình
  đóng góp minh bạch giúp người ngoài dễ tham gia.

## 2. Các bước đã thực hiện

1. Tạo repository `hello-oss-project` trên GitHub.
2. Clone về máy bằng `git clone`, mở bằng VS Code.
3. Viết `main.c` in ra "Hello Open Source".
4. Soạn `README.md`, `CONTRIBUTING.md` bằng Obsidian.
5. Thêm `.gitignore` (loại `.obsidian/`) và file `LICENSE` (MIT).
6. Commit theo quy tắc `<loại>: <mô tả>` và push lên nhánh `main`.

## 3. Lý do chọn giấy phép MIT

Dự án là chương trình mẫu nhỏ dùng để học tập, nên cần giấy phép đơn giản,
ít ràng buộc. MIT cho phép mọi người dùng, sửa, phân phối, kể cả thương mại,
chỉ cần giữ thông báo bản quyền. MIT tương thích với hầu hết giấy phép khác
(kể cả GPL) nên dễ tích hợp vào dự án khác. Đối tượng sử dụng là sinh viên và
người mới học, MIT giúp họ tái sử dụng không vướng pháp lý.

## 4. Vai trò của tài liệu và giấy phép

- **README** là cửa ngõ: người dùng hiểu dự án làm gì và dùng thế nào.
- **CONTRIBUTING** hạ thấp rào cản tham gia, thống nhất cách làm việc.
- **LICENSE** quyết định người khác được làm gì với mã nguồn. Thiếu license
  thì mặc định mọi quyền thuộc tác giả và không ai được phép dùng lại.

