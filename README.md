# WEB MÔI GIỚI VIỆC LÀM
## Trang web môi giới việc làm
### Dự án vì cộng đồng
Sơ đồ thực thể <br>
- Cơ sở dữ liệu

1. Đối tượng sử dụng
- Quản trị viên
- Nhà tuyển dụng
- Ứng viên
- Chức năng từng đối tượng <br>
## A. Quản trị viên

- Quản lý trang thông tin: banner, giới thiệu,…
- Quản lý người dùng
- Quản lý file: JD, CV
- Quản lý bài đăng công việc
- Quản lý báo cáo <br>
## B. Nhà tuyển dụng

- Quản lý bài tuyển dụng
- Tìm kiếm CV
- Chỉnh sửa thông tin cá nhân (thuộc công ty nào, thông tin liên hệ)<br>
## C. Ứng viên

- Tìm kiếm công việc (công ty, vị trí, mức lương, địa điểm, ngôn ngữ, trình độ, yêu cầu bằng cấp - chứng chỉ, số lượng)
- Đăng CV
- Xem danh sách công việc (có thể ghim và còn lại sắp xếp ngẫu nhiên)
- Báo cáo vi phạm: công ty, cá nhân (lừa đảo, spam, không liên hệ được, thông tin bài tuyển dụng sai)


### Phân tích chức năng 

- Đăng bài tuyển dụng

| Các tác nhân	| Nhà tuyển dụng |
| ----- | ----- |
| Mô tả	| Đăng bài tuyển dụng |
| Kích hoạt	| Người dùng ấn vào nút “Đăng bài tuyển dụng” trên thanh menu |
| Đầu vào	| Tên công ty <br> Tên công việc <br> Địa điểm: thành phố - quận (select2 - load về local) <br>
Có cho remote không? (checkbox) <br> Có cho parttime không? (radio) <br> Mức lương (slidebar) <br> Ngôn ngữ (Multiple select2) <br> Yêu cầu thêm (textarea) <br> Số lương<br> File JD|
| Trình tự xử lý | |	
| Đầu ra	| Đúng: Hiển thị trang người dùng và thông báo thành công<br>Sai: Hiển thị trang đăng nhập và thông báo thất bại |
| Lưu ý	| Kiểm tra ô nhập không được để trống bằng JavaScript |


## License
MIT
**Free Software, Hell Yeah!**
