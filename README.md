# ☕ Java Basic Learning

**Java Basic Learning** là repository được tạo ra trong quá trình học **lập trình Java cơ bản**, với mục tiêu lưu lại các **ví dụ, bài tập và kiến thức nền tảng của Java** trong giai đoạn bắt đầu làm quen với ngôn ngữ này.

Project đóng vai trò như một tài liệu học tập cá nhân, giúp hệ thống hóa những nội dung quan trọng trong Java và hỗ trợ quá trình luyện tập từng bước từ cú pháp cơ bản đến **lập trình hướng đối tượng (OOP)**.

Repository này đặc biệt phù hợp với:

* Người mới bắt đầu học Java
* Sinh viên ngành **Công Nghệ Thông Tin**
* Người muốn ôn lại kiến thức Java cơ bản
* Người cần một repository đơn giản để tham khảo cú pháp và cấu trúc chương trình Java

Trong quá trình thực hiện repository này, các nội dung được luyện tập tập trung vào:

* Cú pháp Java
* Tư duy lập trình cơ bản
* Cấu trúc chương trình Java
* Biến, điều kiện, vòng lặp và mảng
* Hàm và phương thức
* Những khái niệm nền tảng của **lập trình hướng đối tượng (OOP)**

---

# 📚 Nội dung đã học

Repository bao gồm các kiến thức Java cơ bản thường gặp trong giai đoạn nhập môn.

## 1️⃣ Cấu trúc chương trình Java

Đây là phần nền tảng đầu tiên khi học Java, giúp người học hiểu cách một chương trình Java được tổ chức và thực thi.

Bao gồm:

* `class`
* phương thức `main`
* cách biên dịch và chạy chương trình Java

Ví dụ:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello Java!");
    }
}
```

Phần này giúp người học hiểu được điểm bắt đầu của một chương trình Java và cách Java xử lý mã nguồn.

---

## 2️⃣ Biến và kiểu dữ liệu

Repository cũng lưu lại những ví dụ cơ bản về khai báo biến và sử dụng các kiểu dữ liệu phổ biến trong Java.

Các kiểu dữ liệu cơ bản bao gồm:

* `int`
* `double`
* `float`
* `char`
* `boolean`
* `String`

Ví dụ:

```java
int age = 20;
double gpa = 3.8;
String name = "Bao";
```

Đây là phần rất quan trọng vì biến và kiểu dữ liệu là nền tảng của mọi chương trình Java.

---

## 3️⃣ Câu lệnh điều kiện

Phần này giúp luyện tập tư duy rẽ nhánh trong lập trình thông qua các cấu trúc điều kiện cơ bản.

Bao gồm:

* `if`
* `if else`
* `switch`

Ví dụ:

```java
if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
```

Thông qua đó, người học có thể làm quen với cách chương trình đưa ra quyết định dựa trên điều kiện logic.

---

## 4️⃣ Vòng lặp

Repository cũng bao gồm các ví dụ về vòng lặp — một phần thiết yếu trong lập trình để xử lý các thao tác lặp lại.

Các vòng lặp phổ biến gồm:

* `for`
* `while`
* `do...while`

Ví dụ:

```java
for(int i = 1; i <= 5; i++){
    System.out.println(i);
}
```

Phần này giúp rèn luyện tư duy lặp, đếm, duyệt dữ liệu và xây dựng logic xử lý tuần tự.

---

## 5️⃣ Mảng (Array)

Mảng là cấu trúc dữ liệu cơ bản trong Java dùng để lưu nhiều giá trị cùng kiểu dữ liệu.

Ví dụ:

```java
int[] numbers = {1,2,3,4,5};

for(int n : numbers){
    System.out.println(n);
}
```

Qua phần này, người học có thể hiểu cách khai báo, truy cập và duyệt qua các phần tử trong mảng.

---

## 6️⃣ Hàm (Method)

Repository có các ví dụ liên quan đến việc tạo và sử dụng method trong Java.

Ví dụ:

```java
public static int sum(int a, int b){
    return a + b;
}
```

Phần này giúp người học hiểu cách chia chương trình thành các khối chức năng riêng biệt để tái sử dụng và tổ chức mã tốt hơn.

---

## 7️⃣ Lập trình hướng đối tượng (OOP)

Một trong những nội dung quan trọng nhất của Java là **lập trình hướng đối tượng**.

Các khái niệm cơ bản được luyện tập gồm:

* Class
* Object
* Constructor
* Encapsulation

Ví dụ:

```java
class Student{
    String name;
    int age;

    void display(){
        System.out.println(name + " " + age);
    }
}
```

Phần này giúp xây dựng nền tảng rất quan trọng cho việc học Java nâng cao, phát triển ứng dụng và tiếp cận các framework sau này.

---

# 🛠️ Công cụ sử dụng

Trong quá trình học và thực hành, repository sử dụng các công cụ cơ bản như:

* **Java JDK**
* **VS Code**
* **IntelliJ IDEA**
* **Terminal / Command Prompt**

Các công cụ này đủ để biên dịch, chạy và kiểm thử các chương trình Java cơ bản trong quá trình học tập.

---

# ▶️ Cách chạy chương trình

Để chạy các file Java trong repository, bạn có thể thực hiện theo các bước sau:

## 1️⃣ Compile

```bash
javac Main.java
```

## 2️⃣ Run

```bash
java Main
```

> Lưu ý: Tên file cần trùng với tên class public trong chương trình để việc biên dịch và thực thi diễn ra chính xác.

---

# 📂 Cấu trúc repository

```text
java-basic-learning
│
├── HelloWorld.java
├── Variables.java
├── Conditions.java
├── Loops.java
├── Arrays.java
└── OOP.java
```

| File | Mô tả |
| --- | --- |
| `HelloWorld.java` | Ví dụ chương trình Java đầu tiên |
| `Variables.java` | Thực hành biến và kiểu dữ liệu |
| `Conditions.java` | Ví dụ về câu lệnh điều kiện |
| `Loops.java` | Ví dụ về các vòng lặp |
| `Arrays.java` | Thực hành với mảng trong Java |
| `OOP.java` | Minh họa các khái niệm OOP cơ bản |

---

# 🎯 Mục tiêu của repository

* Lưu lại quá trình **học Java từ cơ bản**
* Hệ thống hóa các kiến thức nền tảng của ngôn ngữ **Java**
* Làm tài liệu tham khảo cho quá trình học tập sau này
* Rèn luyện tư duy lập trình và tổ chức chương trình
* Xây dựng nền tảng cho các project Java lớn hơn trong tương lai

---

# 👨‍💻 Tác giả

**Trần Gia Bảo** - **gibor06**

Sinh viên ngành **Công Nghệ Thông Tin** - **Trường Đại học Công Thương TP.HCM (HUIT)**

📍 TP.HCM, Việt Nam

# 📬 Liên hệ

📧 Email: [gibor06.dev@gmail.com](mailto:gibor06.dev@gmail.com)

🌐 Facebook: https://www.facebook.com/gibor06

---

# 📜 License

Repository này được sử dụng cho mục đích **học tập**, **nghiên cứu** và **tham khảo**.
