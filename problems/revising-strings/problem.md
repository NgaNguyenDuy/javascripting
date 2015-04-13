---

# SỬA ĐỔI CHUỖI

Đôi khi bạn sẽ cần phải thay đổi nội dung của một chuỗi.

Strings Object đã xây dựng sẵn một số chức năng mà cho phép bạn kiểm tra và sử lý nội dung của nó.

Dưới đây là một ví dụ sử dụng phương thức `.replace()`:

```js
var example = 'this example exists';
example = example.replace('exists', 'is awesome');
console.log(example);
```

Chú ý rằng, để thay đổi giá trị mà biến `example` tham chiếu đến, chúng ta cần__
phải sử dụng dấu bằng một lần nữa, lần này là gán với phương thức `example.replace()` ở__
bên phải dấu bằng.

## Thử thách:

Tạo một tệp tin là `revising-strings.js`.

Khởi tạo một biến là `pizza` mà tham chiếu đến giá trị: `pizza is alright`

Sử dụng method `.replace()` để thay đổi từ `alright` sang `wonderful`.

Sử dụng `console.log()` để in kết quả của phương thức `.replace()` ra màn hình terminal.

Kiểm tra xem chương trình của bạn đã chạy đúng chưa bằng cách:

`javascripting-vi verify revising-strings.js`

---
