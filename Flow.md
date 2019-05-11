## Các nguyên tắc:

### 1. Về working flow

    - Chỉ làm 1 bài trên 1 branch và có 1 pull request
    - Chỉ open pull request nếu CircleCI xanh và CodeCov báo 100%

### 2. Về unit test

    - Unit test cần đảm bảo đầy đủ các happy cases và unhappy cases
    - Tên unit test class luôn có dạng `<Tên class cần test>Test`. Ví dụ cần test cho lớp `Demo` thì tên class unit test sẽ là `DemoTest`
    - Tên unit test method luôn có dạng `test_<tên hàm cần hoặc thao tác>`. Ví dụ `test_get_ok`, `test_methodA`

### 3. Về code convention
    - Phải follow chuẩn convention https://www.oracle.com/technetwork/java/codeconventions-150003.pdf
    - Nếu không chắc chắn về một convention nào --> đặt câu hỏi, google ...

## Các bước làm bài

### 1. Về master tạo branch
Mở command line, đầu tiên hãy chắc chắn rằng mình đang ở master bằng cách chạy lệnh `git checkout master`

![Init](Images/Pl1.png)

Để chắc ăn hơn nữa, chạy `git pull` để đảm bảo mã nguồn được cập nhật với repository

Tạo một branch mới bằng lệnh `git checkout -b <tên branch mới>`

### 2. Làm bài, thêm mã nguồn, test case... ect

### 3. Đẩy code lên 

Kiểm tra lại code cần đẩy lên bằng lệnh `git status` hoặc dùng source tree để xem lại sự thay đổi.

Khi đã chắc chắn những gì mình đã thay đổi, đẩy code lên bằng các lệnh

```
git add *
git commit -m <Message>
git push
```

Nếu khi chạy `git push` mà git báo lỗi như hình dưới

![Init](Images/Pl2.png)

Chạy lại lệnh `git push` với command như được bôi hồng

### 4. Open pull request

Trước khi tiến hành tạo pull request, hãy đảm bảo code coverage đang là 100% bằng cách vào https://codecov.io và kiểm tra

![Init](Images/Pl4.png)

Trên trang repository, vào phần `Pull Request` chọn `Compare & Pull Request` nếu nó đang hiển thị cho branch mình đang làm

![Init](Images/Pl3.png)

Hoặc bấm `New pull request` rồi chọn branch ở bước sau

Review code lại lần nữa, thêm tiêu đề, description rồi bấm nút ..

### 5. Fix comments

Dựa vào comment, sửa lại code và đẩy lên. 

Sau đó:

- Trả lời ngắn gọn `Done`: nếu đã fix
- Câu hỏi: nếu có thắc mắc
- Thảo luận: nếu muốn cãi lộn nhiều hơn

!! Chỉ trả lời sau khi push code

### 6. Done

Task done nếu pull request được merge vào master.

Good luck!!
