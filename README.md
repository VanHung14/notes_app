# Notes App With Firebase Database in Android Studio
Phân chia công việc:
- Nguyễn Hữu Dinh: design UI, tạo figma, tạo layout
- Đinh Văn Hùng: Xử lý chức năng đăng ký, đăng nhập, kết nối firebase.
- Đào Danh Thái: tạo Database, xử lý sửa note, đăng xuất
- Trần Long Duy: xử lý tạo note mới, view note ra giao diện.
- Lê Đình San: design UI, xử lý lấy lại mật khẩu.

Ứng dụng được viết bằng Java, giao diện tạo bằng file layout xml, sử dụng firebase để lưu trữ dữ liệu ghi chú bằng realtime database, authentication.
Xây dựng ứng dụng ghi chú với các chức năng cơ bản sau:
1. Đăng ký người dùng bằng email ( xác thực email bằng phương thức sendEmailVerification() của firebase, mail verification sẽ được gửi đến email đăng ký, sau khi xác nhận mail mới đăng nhập được).

![image](https://user-images.githubusercontent.com/79967686/175825513-d43ef106-6bd4-49f3-ae4a-e98b66ff37c4.png)

Verification mail: click vào đường dẫn để xác thực.

![image](https://user-images.githubusercontent.com/79967686/175825790-ba80d19b-8289-4f8f-bf9b-c9c801d70bae.png)

2. Đăng nhập người dùng bằng email đã xác thực ( kiểm tra email đã đăng ký và xác thực hay chưa)

![image](https://user-images.githubusercontent.com/79967686/175825502-e82d4c88-209a-484b-b053-ec59909158e7.png)

3. Lấy lại mật khẩu ( nhập email, firebase sẽ gửi 1 mail cho phép đổi mật khẩu bằng phương thức sendPasswordResetEmail().

![image](https://user-images.githubusercontent.com/79967686/175825521-559462a0-d882-4bce-8477-fe4f607e6944.png)

Reset password mail: nhập mật khẩu mới để thay đổi.

![image](https://user-images.githubusercontent.com/79967686/175825765-42881800-e540-4b08-b66c-6e66207f8e40.png)

4. Giao diện hiển thị ghi chú và button đăng xuất.

![image](https://user-images.githubusercontent.com/79967686/175826556-b0bbf4ed-670c-4d39-8fa7-75a2e44b6aab.png)

5. Giao diện thêm ghi chú.

![image](https://user-images.githubusercontent.com/79967686/175825894-459d06dd-4387-41b0-b59d-98ee0c77d7b7.png)

6. Sửa hoặc xóa ghi chú.

![image](https://user-images.githubusercontent.com/79967686/175825940-4b41bb51-e570-4c52-a677-0aa007243eff.png)
