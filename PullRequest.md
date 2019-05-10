## Các nguyên tắc:

- Về working flow

    - Chỉ làm 1 bài trên 1 branch và có 1 pull request
    - Chỉ open pull request nếu CircleCI xanh và CodeCov báo 100%

- Về unit test

    - Unit test cần đảm bảo đầy đủ các happy cases và unhappy cases
    - Tên unit test class luôn có dạng `<Tên class cần test>Tes`. Ví dụ cần test cho lớp `Demo` thì tên class unit test sẽ là `DemoTest`
    - Tên unit test method luôn có dạng `test_<tên hàm cần hoặc thao tác>`. Ví dụ `test_get_ok`, `test_methodA`

- Về code convention
    - Phải follow chuẩn convention https://www.oracle.com/technetwork/java/codeconventions-150003.pdf
    - Nếu không chắc chắn về một convention nào --> đặt câu hỏi, google ...

## Các bước làm bài

Mở command line, đầu tiên hãy chắc chắn rằng mình đang ở master bằng cách chạy lệnh `git checkout master`

![Init](Images/Pl1.png)

Tạo một branch mới bằng lệnh `git checkout -b <tên branch mới>`
