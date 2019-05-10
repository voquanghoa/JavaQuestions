1. Implement class `Triangle` với constructor chấp nhận 6 số nguyên là tọa độ 3 đỉnh. Class triangle phải có những hàm `getType()` trả về `Thuong`, `Can`, `Vuong`, `Vuong Can` hoặc `Deu`, hàm `getArea()` trả về diện tích và `getPerimeter()` trả về chu vi của tam giác. Viết chương trình nhập thông tin để test class

2. Viêt một chương trình nhập vào nhiều dòng, mỗi dòng có 3, 6 hoặc 8 số nguyên là thông tin của hình tròn, hình chữ nhật hoặc tứ giác như sau:

    - Hình tròn chứa x, y, r với tâm hình tròn (x, y) và bán kính r
    - Hình tam giác chứa 6 số x1, y1, x2, y2, x3, y3 tương ứng là tọa độ của 3 đỉnh
    - Hình tứ giác chứa 8 đỉnh

    Nhập vào số nguyên n và sau đó nhập n dòng như trên, mỗi dòng nhập thành một đối tượng hình học như trên. Cuối cùng, in ra thông tin danh sách đối tượng hình học đã chọn và in ra diện tích, chu vi của hình.

    Yêu cầu:
    - Viết `interface Shape` với các method `showInfo`, `getArea()`, `getPerimeter()`
    - Class `Circle`, `Triangle`, `Quadrilateral` implements `Shape`
    - Lưu danh sách đối tượng vào `ArrayList<Shape>`
    - Implement lớp ShapeFactory để khởi tạo đối tượng từ danh sách tham số

    TIP:
    - Khoảng cách giữa 2 điểm ![Khoảng cách giữa hai điểm](https://latex.codecogs.com/gif.latex?l=\sqrt{(x_{1}-x_{2})^{2}&plus;(y_{1}-y_{2})^{2}})
    - Diện tích hình tròn ![Diện tích hình tròn](https://latex.codecogs.com/gif.latex?S=\pi&space;r^{2})
    - Chu vi hình tròn ![Diện tích hình tròn](https://latex.codecogs.com/gif.latex?S=2&space;\pi&space;r)
    - Diện tích tam giác ![Diện tích tam giác](https://latex.codecogs.com/gif.latex?S=\sqrt{p(p-1)(p-b)(p-c)}) với p là nửa chu vi
    - Diện tích tứ giác: Nếu vẽ đường chéo của tứ giác thì sẽ tạo ra 2 tam giác --> Tính tổng diện tích của 2 tam giác đó. Có tới 2 cách vẽ đường chéo --> có 2 tổng diện tích --> lấy min.

3. Implement class TimeSpan có
- Fields
    - totalSeconds
- Methods
    - getDays
    - getHours
    - getMinutes
    - getSeconds
    - getTotalDays
    - getTotalHours
    - getTotalMinutes
    - getTotalSeconds

- Constructors:
    - TimeSpan (một đối tượng TimeSpan khác)
    - totalSeconds

3. Implement class DateTime
- Fields:
    - 
- Constructors:
    - DateTime (một đối tượng DateTime khác)
    - year, month, day (throw lỗi nếu số liệu sai)
    - year, month, day, hour, minute, second (throw lỗi nếu số liệu sai)

- Methods:
    - Lấy số ngày 
