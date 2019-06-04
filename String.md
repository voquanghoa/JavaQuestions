## Xử lý chuỗi

Viết chương trình xử lý một chuổi ký tự (String)

1. Liệt kê các câu. (Các câu cách nhau bởi dấu chấm `.`, chấm hỏi `?`, chấm than `!` và xuống dòng `\n`)

2. Liệt kê các từ (một từ chỉ chứa a-z,0-9)

3. Kiểm tra chuỗi ký tự có đối xứng hay không. (Ví dụ abcdcba là đối xứng)

4. Tính tổng của các số nguyên trong chuỗi. Ví dụ `abc 123 def 33 mn 3.221` sẽ in ra 380 với 380 = 123+33+3+221

5. Tìm các từ xuất hiện trên 2 lần.

6. Xử lý chuỗi bằng cách biến các ký tự hoa thành ký tự thường, các ký tự thường thành ký tự hoa

7. Tìm vị trí một chuỗi con từ một chuỗi cha mà chỉ được dùng hàm `charAt`

8. Chuẩn hóa chuỗi bằng các thao tác
    - Viết hoa tất cả các chữ cái đầu câu
    - Viết thường tất cả các chữ cái không phải đầu câu
    - Bỏ tất cả các khoảng trống dư thừa
    - Thêm khoảng trắng vào sau các dấu `.,?!`

9. Nhận vào một chuổi ký tự chứa toàn các chữ cái (a-z, A-Z). Rút gọn chuỗi bằng cách ở những nơi chữ cái lặp lại, ta viết số lần lặp. Ví dụ `abcccceeeeeefd` sẽ viết thành `abc4e6fd`, `abbbbbbbbbbbbbc` viết là `ab13c`

10. Nhận vào chuổi đã được viết gọn ở câu 9, dịch nó thành chuỗi lúc đầu.

11. Nhận vào một chuổi string là một biểu thức có dạng `<số><phép tính><số>` trong đó `<số>` là số nguyên, `<phép tính>` có thể là +-*/^, >>, << trả về kết quả của biểu thức

12. Nhận tham một string, xóa các ký tự giống nhau liên tiếp và giữ lại một. 
    Ví dụ `abbbbbbccccd eeffffddbc` thành --> `abcd efdbc`

13. Implement method nhận tham số là hai string, kiểm tra 2 chuỗi đó có bộ ký tự giống nhau (có thể khác về thứ tự) hay không

14. Một [Barcode EAN 13](https://vi.wikipedia.org/wiki/EAN-13) có 13 con số được coi là hợp lệ nếu: tổng của các số ở vị trí lẻ + 3*(tổng các số ở vị trí chẳn) là một số chia hết cho 10.

Ví dụ mã barcode `8938505974194` ta có (8+3+5+5+7+1+4) + 3 * (9+8+0+9+4+9) = 150. 150 chia hết cho 10 nên mã `8938505974194` là hợp lệ.

Viết chương trình kiểm tra tính hợp lệ của một barcode.

15. Một Barcode EAN 13 có 13 số như trên thì con số đầu tiên bên phải qua là số verify. Viết chương trình nhận vào chuỗi số gồm 12 chữ số. Trả về kết quả là chữ số verify để có thể tạo thành một barcode hợp lệ.

16. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính cộng 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

17. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính trừ 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

18. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính nhân 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

19. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính chia lấy phần nguyên 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

