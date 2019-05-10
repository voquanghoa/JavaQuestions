## Xử lý chuỗi

Viết chương trình xử lý một chuổi ký tự (String)

1. Liệt kê các câu. (Các câu cách nhau bởi dấu chấm `.`, chấm hỏi `?`, chấm than `!` và xuống dòng `\n`)

2. Liệt kê các từ (một từ chỉ chứa a-z,0-9)

3. Kiểm tra chuỗi ký tự có đối xứng hay không. (Ví dụ abcdcba là đối xứng)

4. Tính tổng của các số nguyên trong chuỗi. Ví dụ `abc 123 def 33 mn 3.221` sẽ in ra 380 với 380 = 123+33+3+221

5. Tìm các từ xuất hiện trên 2 lần.

6. Xử lý chuỗi bằng cách biến các ký tự hoa thành ký tự thường, các ký tự thường thành ký tự hoa

7. Không sử dụng hàm tìm kiếm có sẵn, tìm vị trí một chuỗi con.

8. Chuẩn hóa chuỗi bằng các thao tác
    - Viết hoa tất cả các chữ cái đầu câu
    - Viết thường tất cả các chữ cái không phải đầu câu
    - Bỏ tất cả các khoảng trống dư thừa
    - Thêm khoảng trắng vào sau các dấu `.,?!`

9. Nhận vào một chuổi ký tự chứa toàn các chữ cái (a-z, A-Z). Rút gọn chuỗi bằng cách ở những nơi chữ cái lặp lại, ta viết số lần lặp. Ví dụ `abcccceeeeeefd` sẽ viết thành `abc4e6fd`, `abbbbbbbbbbbbbc` viết là `ab13c`

10. Nhận vào chuổi đã được viết gọn ở câu 22, dịch nó thành chuỗi lúc đầu.

11. Nhận vào một chuổi string là một biểu thức có dạng `<số><phép tính><số>` trong đó `<số>` là số nguyên, `<phép tính>` có thể là +-*/^, >>, << trả về kết quả của biểu thức

12. Nhận tham một string, xóa các ký tự giống nhau liên tiếp và giữ lại một. 
    Ví dụ `abbbbbbccccd eeffffddbc` thành --> `abcd efdbc`

13. Implement method nhận tham số là hai string, kiểm tra 2 chuỗi đó có bộ ký tự giống nhau (có thể khác về thứ tự) hay không