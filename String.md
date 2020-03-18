## Xử lý chuỗi

Viết chương trình xử lý một chuổi ký tự (String)

1. Liệt kê các câu. (Các câu cách nhau bởi dấu chấm `.`, chấm hỏi `?`, chấm than `!` và xuống dòng `\n`)

2. Kiểm tra chuỗi ký tự có đối xứng hay không. (Ví dụ abcdcba là đối xứng)

3. Tính tổng của các số nguyên trong chuỗi. Ví dụ `abc 123 def 33 mn 3.221` sẽ in ra 380 với 380 = 123+33+3+221

4. Viết chương trình kiểm tra một chuỗi string có phải là sự lặp lại của một chuỗi string bất kỳ nào đó hay không:

Ví dụ: 
- abab --> true vì ab lặp lại 2 lần
- abc --> false

5. Tìm các từ xuất hiện trên 2 lần trong chuỗi (chuỗi đầu vào chỉ có các ký tự chữ cái và khoảng trắng)

6. Nhận vào một chuổi ký tự chứa toàn các chữ cái (a-z, A-Z). Rút gọn chuỗi bằng cách ở những nơi chữ cái lặp lại, ta viết số lần lặp. Ví dụ `abcccceeeeeefd` sẽ viết thành `abc4e6fd`, `abbbbbbbbbbbbbc` viết là `ab13c`

7. Nhận vào chuổi đã được viết gọn ở câu 9, dịch nó thành chuỗi lúc đầu.

8. Một [Barcode EAN 13](https://vi.wikipedia.org/wiki/EAN-13) có 13 con số được coi là hợp lệ nếu: tổng của các số ở vị trí lẻ + 3*(tổng các số ở vị trí chẳn) là một số chia hết cho 10.

Ví dụ mã barcode `8938505974194` ta có (8+3+5+5+7+1+4) + 3 * (9+8+0+9+4+9) = 150. 150 chia hết cho 10 nên mã `8938505974194` là hợp lệ.

Viết chương trình kiểm tra tính hợp lệ của một barcode.

9. Một Barcode EAN 13 có 13 số như trên thì con số đầu tiên bên phải qua là số verify. Viết chương trình nhận vào chuỗi số gồm 12 chữ số. Trả về kết quả là chữ số verify để có thể tạo thành một barcode gồm 13 số hợp lệ.

10. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính cộng 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

11. Viết chương trình nhận vào 2 chuổi string biểu diễn 2 số nguyên, thực hiện phép tính trừ 2 chuổi string đó và trả về kết quả. Yêu cầu không được chuyển string về dạng số hoặc dùng bất kỳ thư viện nào khác.

12. Viết chương trình nhận vào mảng các số nguyên. Tìm số nguyên lớn nhất có thể được tạo ra bằng cách viết liên tiếp các số nguyên kia theo một thứ tự nào đó.

Ví dụ:
- [10, 2] --> 210
- [46, 461] --> 46461

