## Cấu trúc vòng lặp, hàm

1. Viết chương trình tìm ước số chung lớn nhất, bội số chung nhỏ nhất của hai số tự nhiên

2. Viết chương trình tìm tổng các chữ số của một số nguyên

3. Viết chương trình nhận vào một số nguyên và trả về cách phân tích số đó ra tích của thừa số nguyên tố. Ví dụ nhập vào 600 thì cần phải trả về `2 * 2 * 2 * 3 * 5 * 5`

4. Tương tự bài 3 nhưng cần in 600 thành `2^3 * 3 * 5^2`

5. Số fibonaci là dãy số bắt đầu từ 1 1 và sau đó, số tiếp theo bằng 2 số trước cộng lại. Tức là `1 1 2 3 5 8 ....`. Nhập vào số nguyên n, in ra danh sách những số fibonaci không lớn hơn n.

6. Viết phương trình giải phương trình bậc 2: 

    ![Phương trình bậc 2](https://latex.codecogs.com/gif.latex?ax^{2}&plus;bx&plus;c=0)

7. Viết phương trình nhập vào n và in ra tổng của dãy số
    ![Dãy số](https://latex.codecogs.com/gif.latex?1*2&plus;2*3&plus;3*4&plus;...&plus;n(n&plus;1))

8. Viết phương trình tính giai thừa `n!` của một số

9. Viết chương trình tính pi với độ sai số 0.0001 bằng công thức
    ![Pi](https://wikimedia.org/api/rest_v1/media/math/render/svg/e9e3959cd2d0ec735e7a6a1917df784842b76706)

10. Viết chương trình tính pi với độ sai số 0.00001 bằng công thức
    ![Pi](https://wikimedia.org/api/rest_v1/media/math/render/svg/fdafa8bd24ce2b6fd518a3cf253ad1ef409388a6)
11. Một ngân hàng trả lãi 100% sau 1 năm. Ví dụ mình gửi tiết kiệm 100 đồng thì sau 1 năm mình nhận về 200 đồng. Chia 1 năm thành n khoảng thời gian bằng nhau và tính lãi lũy tiến 100/n. Ví dụ n = 2 thì mình sẽ có mỗi khoảng thời gian là 6 tháng và lãi lũy tiến 50%. Lúc đó số tiền mình nhận được là 225 đồng. (Gốc 100 đồng, sau 6 tháng thành 100 + 50%= 150 đồng, sau 1 năm thành 150 + 50% = 225 đồng)


    Viết chương trình nhận vào số nguyên dương n là số khoảng thời gian, tính số tiền mình sẽ được nhận sau 1 năm.
12. Tính biểu thức sau đây với n nhập từ bàn phím
    ![Biểu thức](https://latex.codecogs.com/gif.latex?s=\frac{1}{0!}&plus;\frac{1}{1!}&plus;\frac{1}{2!}&plus;\frac{1}{3!}&plus;...&plus;\frac{1}{n!})

13. Tính e với độ chính xác 0.00001 với công thức
    ![E](https://wikimedia.org/api/rest_v1/media/math/render/svg/39a1c93d6f1fda7f20a9e45cd3e6f0c35a5eeb36)
14. Nhập vào a, tính căn bậc hai của a với độ chính xác 0.0001 bằng công thức
    ![Căn](https://latex.codecogs.com/gif.latex?%5Chuge%20f%28n%29%20%3D%20%5Cfrac%7Ba%7D%7B2f%28n%29%7D%20-%20%5Cfrac%7Bf%28n%29%7D%7B2%7D)

15. Nhập a, b, c là 3 cạnh của một tam giác. Kiểm tra tam giác có hợp lệ hay không, nếu tam giác hợp lệ thì in tiếp các thông tin:
    - Diện tích tam giác
    - Chu vi tam giác
    - Kiểu tam giác (vuông, cân hay bình thường)
16. Làm lại câu 15 nhưng đầu vào là x1, y1, x2, y2, x3, y3 là tọa độ 3 đỉnh.

17. Tìm những số nguyên n có m chữ số thỏa mãn điều kiện: tổng của các chữ số của n khi lũy thừa hệ số m thì đúng bằng n. Ví dụ n=153 là hợp lệ vì m=3, 1^3 + 5^3 + 3^3 = 153 (Giới hạn 2<=m<=5).

18. Số 23 khi viết nhị phân sẽ là 10111 khi viết ngược lại thành 11101 và nó thành số 29. Nhập số nguyên n và tìm số m bằng cách viết ngược thứ tự số binary như trên.

19. Nhập vào số nguyên n, in ra dòng thứ n của tam giác pascal [Tam giác pascal](https://vi.wikipedia.org/wiki/Tam_gi%C3%A1c_Pascal)

20. Nhập một số nguyên n, trả về kết quả là tổng của n số fibonacci đầu tiên.

Bài 21, 22, 23 viết về ngày tháng: cho biết rằng:

- Năm chỉ phù hợp nếu 1900 <= năm <= 3000
- Ngày tính từ 1 ~ (28, 29, 30, 31 tùy tháng)
- Tháng chỉ phù hợp nếu 1<= tháng <= 12
- Các tháng 1, 3, 5, 7, 8, 10, 12 có 31 ngày
- Các tháng 4, 6, 9, 11 có 30 ngày
- Tháng 2 có 28 ngày với năm thường, 29 ngày với năm nhuận
- Năm nhuận là năm thỏa mãn 1 trong 2 điều kiện sau
    - Chi hết cho 4 nhưng không chia hết cho 100
    - Chia hết cho 400

21. Implement method nhận tham số là ngày/tháng/năm. Trả về số ngày còn lại trong tháng đó hoặc throw RuntimeException với message là "Invalid date" nếu ngày/tháng/năm không phù hợp.

22. Implement method nhận tham số là ngày/tháng/năm. Trả về số ngày còn lại trong năm đó hoặc throw RuntimeException với message là "Invalid date" nếu ngày/tháng/năm không phù hợp.

23. Implement method nhận tham số là ngày/tháng/năm. Trả về kết quả là thứ trong ngày hoặc throw RuntimeException với message là "Invalid date" nếu ngày/tháng/năm không phù hợp.

24. Viết chương trình nhận số nguyên n, trả về kết quả là số lượng số fibonaci nhỏ hơn hoặc bằng n.

25. Viết chương trình nhận số nguyên m, n. Trả về số nguyên là lượng số fibonci x thỏa mãn `m<= x <= n`

26. Dãy số CrazyFibonacci được định nghĩa như sau.

- Xuất phát bởi 5 số nguyên có giá trị từ 0 đến 9 (chỉ có 1 chữ số)
- Số tiếp theo bằng tổng của 5 số trước mà chia lấy dư cho 10.

Ví dụ, nếu 5 số đầu tiên (tính từ 0) là `6 2 2 1 4`, số tiếp theo là `(6+2+2+1+4)%10 = 15%10 = 5`, số tiếp theo nữa sẽ là `(2+2+1+4+5)%10 = 4`

Viết chương trình nhận vào a0, a1, a2, a3, a4 là 5 số đầu tiên của dãy và n là một số nguyên, trả về số CrazyFibonacci thứ n.

27. Giai thừa của một số nguyên n là tích của 1*2*...*n. Viết chương trình nhận vào số nguyên n, trả về số lượng chữ số 0 của n!. Ví dụ: n = 10, ta có 10! = 3628800, ta cần trả về 2. Yêu cầu tính toán được với n = 1000000.

28. Viết chương trình tính căn bậc 2 của một số thực không âm bất kỳ bằng phương pháp chia đôi.

29. Viết chương trình dịch [số la mã](https://vi.wikipedia.org/wiki/S%E1%BB%91_La_M%C3%A3) thành số thập phân. Tham khảo http://thuthuatphanmem.vn/so-la-ma-huong-dan-cach-doc-va-viet-so-la-ma/

30. Viết chương trình dịch số thập phân thành số la mã
