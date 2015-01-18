---

# Biến

Một biết là một tên (định danh) mà có thể tham chiếu (reference) đến một giá trị nhất định. Một biến được khai báo bằng việc sử dụng từ khóa `var` theo sau là tên biến.

Sau đây là một ví dụ: 

```js
var example;
```

Biết `example` là đã được **khai báo**, nhưng nó chưa được định nghĩa. (Nó sẽ chưa tham chiếu đến một giá trị nhất định nào cả).

Dưới đây là một ví dụ của việc định nghĩa một biến, làm cho nó tham chiếu đến một giá trị nhất định.

```js
var example = 'some string';
```

Chú ý rằng biến trên đã được **khai báo** bằng việc sử dụng từ khóa `var` và sử dụng dấu = để `định nghĩa`  giá trị mà nó tham chiếu đến. Đây là một cách thông dụng được biết đến như là "Làm một biến bằng một giá trị".

Hãy tạo một file và đặt tên là `variables.js`

Bên trong file đó, chúng ta khai báo một biến tên là `example`.


**Làm cho biến `example` bằng giá trị `'some string'`.**

Sau đó các bạn sử dụng câu lệnh `console.log()` để biến `example` ra ngoài màn hình console.

Kiểm tra xem nếu chương trình của bạn chạy chính xác bằng việc thực hiện lệnh sau: 

`javascripting verify variables.js`
---
