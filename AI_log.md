# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: [ Nguyễn Văn Thế ]
- Mã sinh viên – Lớp: [ 2071020170 - 20-02 ]
- Ngày thực hiện: [ 30/10/2026 ]
- Link repository: [ https://github.com/Coii22/K20-Portfolio-CNTT20-02]
- URL website: [ https://github.com/Coii22/K20-Portfolio-CNTT20-02.git ]
- Tình huống: [x] Website của tôi  [ ] Repo luyện của giảng viên

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: [ Cửa sổ dòng lệnh PowerShell khi chạy lệnh Git cấu hình tài khoản ]
- Mong muốn và hiện tượng thực tế: [ Mong muốn thiết lập tên người dùng Git (git config --global user.name) nhưng terminal báo lỗi không nhận diện lệnh git ]
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): [ Đã chạy lệnh git config --global user.name "coi22" và nhận thông báo lỗi CommandNotFoundException ]
- Tôi nghi nguyên nhân là: [ Máy tính chưa cài đặt Git hoặc chưa cấu hình biến môi trường PATH cho Git ]
- Vì sao tôi nhận định như vậy: [ Lỗi is not recognized as the name of a cmdlet thường xảy ra khi hệ thống Windows không tìm thấy file thực thi của chương trình trong đường dẫn hệ thống ]

## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: [ Gemini ]  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  [git : The term 'git' is not recognized as the name of a cmdlet... đây là lỗi gì?]

- Gợi ý chính của AI:

  [AI giải thích nguyên nhân do chưa cài Git, chưa mở lại terminal sau khi cài, hoặc thiếu biến môi trường PATH. AI hướng dẫn cách kiểm tra bằng file thực thi, cài đặt lại từ git-scm.com và thêm đường dẫn C:\Program Files\Git\bin hoặc cmd vào Environment Variables]

## 3. Quyết định của tôi

- [x] Chấp nhận gợi ý
- [ ] Chỉnh sửa gợi ý rồi áp dụng
- [ ] Bác bỏ gợi ý

- Tôi quyết định làm gì: [ Kiểm tra lại việc cài đặt Git, khởi động lại PowerShell/VS Code và thực hiện cấu hình lại biến môi trường PATH nếu cần thiết ]
- Lý do, dựa trên dữ kiện nào: [ Các bước hướng dẫn logic, đúng bản chất lỗi không tìm thấy chương trình dòng lệnh trên Windows ]

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): [Biến môi trường hệ thống,hoặc cài đặt lại Git trên máy tính]
- Nội dung thay đổi hoặc cách xử lý khác: [Tải và cài đặt Git,sau đó khởi động lại hoàn toàn cửa sổ PowerShell.]
- Commit của bản sửa, nếu có: [Chưa có commit]
- Bản sửa đã deploy: [ ] Có  [ ] Chưa  [x] Không phát sinh bản sửa

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | [Chưa kiểm tra] | [Chưa kiểm tra] |
| Giao diện/chức năng trên URL website | [CommandNotFoundException khi gõ lệnh git] | [Gõ git --version hiển thị đúng phiên bản Git, lệnh git config chạy thành công không báo lỗi] |

- Cách thử lại và kết quả thực tế: [Đóng Visual Studio Code, mở lại cửa sổ mới, gõ git --version thấy hiện phiên bản Git và chạy lại lệnh cấu hình user thành công]
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): [Kết quả hiển thị trực tiếp trên màn hình terminal không còn thông báo lỗi đỏ.]

## 5. Kết luận

- [x] Đã xử lý được  [ ] Xử lý được một phần  [ ] Chưa xử lý được
- Điều tôi rút ra hoặc việc cần làm tiếp: [Cần đảm bảo các công cụ lập trình (như Git) đã được cài đặt và tích hợp vào biến môi trường PATH trước khi bắt đầu thực hiện các thao tác dòng lệnh]

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
