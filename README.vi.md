# Anki Power-Up Add-ons

Bộ sưu tập các add-on mạnh mẽ để nâng cao trải nghiệm học tập trên Anki của bạn, bao gồm một trình dịch tự động và các chế độ học kiểu Quizlet.

![Anki Power-Up Demo](https://github.com/user-attachments/assets/6a8c18ff-d936-442a-afae-de04c2469f6f)

---

## Mục lục

- [Tính năng](#tính-năng)
- [Cài đặt](#cài-đặt)
- [Sử dụng](#sử-dụng)
  - [Dịch tự động](#dịch-tự-động)
  - [Chế độ Học (Kiểu Quizlet)](#chế-độ-học-kiểu-quizlet)
- [Cấu hình](#cấu-hình)
- [Đóng góp](#đóng-góp)
- [Giấy phép](#giấy-phép)

---

## Tính năng

- **Dịch tự động**:

  - Thêm một tiện ích dịch thuật trực tiếp vào trình soạn thảo của Anki.
  - Tự động dịch nội dung từ trường "Front" sang trường "Back" khi bạn rời khỏi trường "Front".
  - Tăng tốc độ tạo thẻ flashcard song ngữ.

- **Chế độ Học (Kiểu Quizlet)**:
  - Thêm một menu "Learn Mode" mới vào Trình duyệt Thẻ (Card Browser).
  - **Chế độ Trắc nghiệm**: Tự kiểm tra với các câu hỏi trắc nghiệm được tạo tự động từ các thẻ bạn đã chọn.
  - **Chế độ Viết**: Luyện tập bằng cách gõ lại câu trả lời, giống như chế độ "Learn" hoặc "Write" của Quizlet.
  - Phiên học có thể tùy chỉnh: Chọn trường nào dùng cho câu hỏi/câu trả lời và số lượng thẻ để học.

![Auto Translate UI](https://github.com/user-attachments/assets/01734b52-4883-4097-83cf-9a8df73bf719)
---

## Cài đặt

1.  **Đóng Anki**: Đảm bảo Anki đã được đóng hoàn toàn trước khi cài đặt.

2.  **Mở thư mục Add-ons**:

    - Khởi động Anki, sau đó vào `Tools` > `Add-ons`.
    - Nhấp vào nút `View Files`.

3.  **Sao chép thư mục Add-on**:

    - Giải nén các tệp dự án nếu bạn chưa làm.
    - Sao chép các thư mục `anki_auto_translate` và `anki_learn_mode` vào thư mục `addons21` mà bạn vừa mở.

4.  **Khởi động lại Anki**: Khởi động lại Anki. Các add-on sẽ được tải và sẵn sàng để sử dụng.

---

## Sử dụng

### Dịch tự động

Tiện ích Dịch tự động hoạt động trong cửa sổ **Trình soạn thảo** của Anki (khi thêm hoặc chỉnh sửa thẻ).

1.  **Mở Trình soạn thảo**: Nhấp vào "Add" để tạo thẻ mới.
2.  **Nhập văn bản**: Gõ từ hoặc cụm từ bạn muốn dịch vào trường đầu tiên (ví dụ: "Front").
3.  **Rời khỏi trường**: Nhấp vào trường thứ hai (ví dụ: "Back") hoặc nhấn phím `Tab`.
4.  **Dịch tự động**: Văn bản đã dịch sẽ tự động xuất hiện trong trường thứ hai.

### Chế độ Học (Kiểu Quizlet)

Chế độ Học có thể truy cập từ **Trình duyệt Thẻ** (Card Browser) của Anki.

1.  **Mở Trình duyệt**: Từ cửa sổ chính của Anki, nhấp vào "Browse".
2.  **Chọn Thẻ**: Trong trình duyệt, chọn các thẻ bạn muốn học. Bạn phải chọn ít nhất **4 thẻ** để các chế độ hoạt động.
3.  **Mở Menu Chế độ Học**: Một menu mới có tên **"Learn Mode"** sẽ xuất hiện trên thanh menu trên cùng.
4.  **Chọn một Chế độ**:
    - Nhấp vào `Learn Mode` > `Learn: Multiple Choice...` để bắt đầu bài kiểm tra trắc nghiệm.
    - Nhấp vào `Learn Mode` > `Learn: Written...` để bắt đầu phiên luyện viết.
5.  **Cấu hình Phiên học**: Một hộp thoại sẽ xuất hiện, cho phép bạn:
    - Chọn trường cho **Câu hỏi** (ví dụ: "Front").
    - Chọn trường cho **Câu trả lời** (ví dụ: "Back").
    - Đặt số lượng thẻ cho phiên học.
6.  **Bắt đầu Học**: Nhấp "OK" để bắt đầu phiên học của bạn trong một cửa sổ mới.

![Learn Mode Menu](https://github.com/user-attachments/assets/b086358b-9e19-40a2-bdd0-71f36e96b8c4)


---

## Cấu hình

- **Dịch tự động**: Không cần cấu hình. Add-on sẽ tự động dịch từ tiếng Anh sang tiếng Việt.
- **Chế độ Học**: Cài đặt phiên học (trường, số lượng câu hỏi) được cấu hình mỗi khi bạn bắt đầu một phiên mới.

---

## Đóng góp

Chúng tôi hoan nghênh các đóng góp! Nếu bạn có ý tưởng cho các tính năng mới, cải tiến hoặc sửa lỗi, vui lòng:

1.  Fork kho lưu trữ này.
2.  Tạo một nhánh mới (`git checkout -b feature/YourAmazingFeature`).
3.  Commit các thay đổi của bạn (`git commit -m 'Add some YourAmazingFeature'`).
4.  Đẩy lên nhánh (`git push origin feature/YourAmazingFeature`).
5.  Mở một Pull Request.

---

## Giấy phép

Dự án này được cấp phép theo Giấy phép MIT - xem tệp [LICENSE.md](LICENSE.md) để biết chi tiết.
