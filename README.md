# ☕ Java Basic Learning

Repository này được tạo ra trong quá trình mình **học lập trình Java cơ bản**.
Mục tiêu của repo là lưu lại các **ví dụ, bài tập và kiến thức nền tảng của Java**.

Project giúp mình luyện tập:

* Cú pháp Java
* Tư duy lập trình
* Cấu trúc chương trình
* Lập trình hướng đối tượng (OOP)

---

# 📚 Nội dung đã học

Các kiến thức Java cơ bản trong repository bao gồm:

## 1. Cấu trúc chương trình Java

* Class
* Method `main`
* Cách chạy chương trình Java

Ví dụ:

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello Java!");
    }
}
```

---

## 2. Biến và kiểu dữ liệu

Các kiểu dữ liệu cơ bản:

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

---

## 3. Câu lệnh điều kiện

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

---

## 4. Vòng lặp

Các vòng lặp phổ biến:

* `for`
* `while`
* `do...while`

Ví dụ:

```java
for(int i = 1; i <= 5; i++){
    System.out.println(i);
}
```

---

## 5. Mảng (Array)

Ví dụ:

```java
int[] numbers = {1,2,3,4,5};

for(int n : numbers){
    System.out.println(n);
}
```

---

## 6. Hàm (Method)

Ví dụ:

```java
public static int sum(int a, int b){
    return a + b;
}
```

---

## 7. Lập trình hướng đối tượng (OOP)

Các khái niệm cơ bản:

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

---

# 🛠️ Công cụ sử dụng

Trong quá trình học mình sử dụng:

* **Java JDK**
* **VS Code / IntelliJ IDEA**
* **Terminal**

---

# ▶️ Cách chạy chương trình

### 1. Compile

```bash
javac Main.java
```

### 2. Run

```bash
java Main
```

---

# 📂 Cấu trúc repository

```
java-basic-learning
│
├── HelloWorld.java
├── Variables.java
├── Conditions.java
├── Loops.java
├── Arrays.java
└── OOP.java
```

---

# 🎯 Mục tiêu của repository

* Lưu lại quá trình **học Java từ cơ bản**
* Làm tài liệu tham khảo sau này
* Xây dựng nền tảng cho các project lớn hơn

---

# 👨‍💻 Tác giả

**Trần Gia Bảo**

Sinh viên ngành **Công Nghệ Thông Tin**

Định hướng phát triển:

* Web Development
* Mobile Development
* Artificial Intelligence

---

# 📜 License

Repository này được sử dụng cho mục đích **học tập và nghiên cứu**.
