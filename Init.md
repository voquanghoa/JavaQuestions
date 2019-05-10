# Tạo repository

## 1. Đăng nhập github, chọn New repository

![Init](Images/Init1.png)

Trong phần New repository, đặt tên Repository, chọn gitignore là java

![Init](Images/Init2.png)

## 2. Tạo project

Mở IntelliJ chọn New Project

![Init](Images/Init3.png)

Sau đó chọn Project kiểu Gradle và tick vào phần Java Libraries

![Init](Images/Init4.png)

Tiếp tục điền tên ứng dụng

![Init](Images/Init5.png)

![Init](Images/Init6.png)

Ở bước cuối cùng, chú ý chọn thư mục lưu trữ dự án vào nơi thích hợp rồi bấm Finish

![Init](Images/Init7.png)

## 3. Add sample code

Sau khi dự án được tạo, đợi một lúc để IDE đồng bộ cấu hình gradle từ template, ta sẽ được

![Init](Images/Init8.png)

Ta thêm class `Demo` vào gói main/java

![Init](Images/Init9.png)

Với nội dung


```java
public class Demo {
    public int sum(int x, int y){
        return x+y;
    }

    public int sub(int x, int y){
        return x-y;
    }

    public int multiple(int x, int y){
        return x*y;
    }
}
```

Thêm class `DemoTest` vào gói test/java với nội dung

```java
import org.junit.Test;

import static org.junit.Assert.assertEquals;

public class DemoTest {

    @Test
    public void test_sum(){
        assertEquals(new Demo().sum(2, 8), 10);
    }

    @Test
    public void test_sub(){
        assertEquals(new Demo().sub(8, 3), 5);
    }

    @Test
    public void test_multiple(){
        assertEquals(new Demo().multiple(8, 3), 24);
    }
}
```

Chạy test

![Init](Images/Init10.png)


Nếu kết quả nhận được toàn màu xanh là done

![Init](Images/Init11.png)

## 4. Cấu hình CircleCI và Codecov

Mở file build.gradle

Thay 

```
plugins {
    id 'java'
}
```

ở đầu file thành

```
apply plugin: 'java'
apply plugin: 'jacoco'
```

Thêm đoạn này vào cuối file

```
jacocoTestReport {
    reports {
        xml.enabled true
        html.enabled false
    }
}

check.dependsOn jacocoTestReport
```

