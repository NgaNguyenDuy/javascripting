---

# CÂU LỆNH IF

Câu điều kiện được sử dụng để làm thay đổi dòng điều khiển của một chương trình, dựa trên một giá trị boolean xác định.

Một câu lệnh điều kiện sẽ có dạng như sau:

```js
if (n > 1) {
  console.log('the variable n is greater than 1.');
} else {
  console.log('the variable n is less than or equal to 1.');
}
```

Bên trong dấu ngoặc đơn, bạn phải truyền vào một điều kiện logic (logic statement), điều đó có nghĩa nó chỉ có giá trị đúng hoặc sai.

Nếu điều kiện trong dấu ngoặc là sai, đoạn mã trong block else sẽ được thực thi.

## Bài tập:

Đầu tiên, các bạn tạo một tệp tin tên là: `if-statement.js`.

Trong tệp tin đó, khai báo một biến là: `fruit`.

Khởi tạo biến `fruit` với giá trị **orange** với kiểu **String**.

Sau đó sử dụng câu lệnh `console.log()` để in ra **"The fruit name has more than  five characters."** nếu như độ dài của biến `fruit` là lớn hơn 5.

Nếu không, hãy in ra chuỗi: "**The fruit name has five characters or less.**"

Kiểm tra xem chương trình của bạn chạy đúng hay chưa bằng lệnh:

`javascripting-vi verify if-statement.js`

---
