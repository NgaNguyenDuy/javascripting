---

# Vòng lặp FOR

Vòng lặp for sẽ trông như thế này:

```js
for (var i = 0; i < 10; i++) {
  // log the numbers 0 through 9
  console.log(i)
}
```

Biến `i` là được sử dụng để theo dõi xem vòng lặp đã chạy được bao nhiêu lần.

Câu lệnh `i < 10;` chỉ ra rằng giới hạn của vòng lặp.
Nó sẽ tiếp tục lặp nếu `i` vẫn còn nhỏ hơn `10`.

Câu lệnh `i++` để tăng giá trị `i` lên một sau mỗi vòng lặp.

## Bài tập:

Hãy tạo một tệp tin là `for-loop.js`.

Trong tệp tin đó hạy tạo một biến là `total` và khởi tạo nó với giá trị bằng `0`.

Định nghĩa một biến thứ hai là `limit` và khởi tạo nó với giá trị bằng `10`.

Tạo một vòng lặp bắt đầu với  biến `i` bằng 0 và tăng lên 1 sau mỗi vòng lặp. Vòng lặp sẽ chạy chừng nào `i` còn nhỏ hơn `limit`.

Trong mỗi bước lặp, hãy tăng giá trị của biến `total` lên một khoảng bằng giá trị `i`. Để làm điều này, bạn có thể sử dụng câu lệnh:

```js
total += i;
```

Sau vòng lặp for, hãy sử dụng câu lệnh `console.log()` để in ra giá trị của biến `total()` trên terminal..

Kiểm tra xem chương trình của bạn đã chạy đúng chưa bằng các sử dụng câu lệnh:

`javascripting-vi verify for-loop.js`

---
