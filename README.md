# btvn-react-2

## câu 1: Làm thế nào để viết ghi chú (comments) trong ReactJS?
1. Ghi chú trong JavaScript (JS):
- Bạn có thể sử dụng cú pháp JavaScript thông thường để viết ghi chú trong phần code JavaScript.
```js
// Đây là một ghi chú một dòng trong JavaScript

/*
 Đây là một ghi chú nhiều dòng trong JavaScript
*/
```
2. Ghi chú trong JSX:
- Trong JSX, bạn cần bọc ghi chú của mình trong {} và sử dụng cú pháp của JavaScript.
```js
return (
  <div>
    {/* Đây là một ghi chú trong JSX */}
    <h1>Hello, world!</h1>
  </div>
);
```
## câu 2: Ưu điểm của ReactJS là gì?
1. Virtual DOM:
- React sử dụng Virtual DOM để cải thiện hiệu suất ứng dụng. Thay vì cập nhật trực tiếp DOM thật, React tạo ra một bản sao của DOM gọi là Virtual DOM và chỉ cập nhật những phần thay đổi, giúp giảm thiểu số lượng thao tác trên DOM thật và cải thiện tốc độ.
2. Hiệu suất cao:
- Nhờ vào Virtual DOM, React có thể tối ưu hóa việc cập nhật và render UI, giúp ứng dụng chạy nhanh và mượt mà hơn.
3. Component-Based Architecture (Kiến trúc dựa trên component):
- React cho phép xây dựng UI bằng cách tạo ra các component độc lập và tái sử dụng được. Điều này giúp mã nguồn trở nên rõ ràng, dễ bảo trì và mở rộng.
4. JSX:
- JSX là một cú pháp mở rộng của JavaScript cho phép bạn viết mã HTML bên trong JavaScript. Điều này giúp code dễ đọc hơn và dễ dàng viết UI động.
5. Unidirectional Data Flow (Luồng dữ liệu một chiều):
- React sử dụng luồng dữ liệu một chiều, giúp dễ dàng theo dõi và quản lý trạng thái của ứng dụng. Điều này làm giảm nguy cơ lỗi và giúp debug dễ dàng hơn.
6. Ecosystem và Cộng đồng mạnh mẽ:
- React có một hệ sinh thái phong phú với nhiều thư viện và công cụ hỗ trợ như Redux, React Router, và nhiều thư viện UI khác. Cộng đồng React cũng rất lớn và năng động, giúp bạn dễ dàng tìm kiếm sự hỗ trợ và tài liệu học tập.
7. React Native:
- React có thể được sử dụng để phát triển ứng dụng di động thông qua React Native. Điều này giúp bạn tái sử dụng code giữa web và mobile, tiết kiệm thời gian và công sức phát triển.
8. SEO-friendly:
- Mặc dù React là một thư viện phía client, bạn có thể sử dụng các kỹ thuật như Server-Side Rendering (SSR) với Next.js để làm cho ứng dụng React của bạn thân thiện với SEO hơn.
9. Linh hoạt:
- React có thể tích hợp dễ dàng với các framework và thư viện khác, giúp bạn có thể sử dụng nó trong nhiều loại dự án khác nhau, từ các ứng dụng đơn giản đến các ứng dụng phức tạp.
10. Cập nhật và phát triển liên tục:
- React được duy trì và phát triển bởi Facebook cùng với một cộng đồng lớn, nên nó thường xuyên được cập nhật và cải thiện.
## câu 3: Các tính năng chính của ReactJS là gì?
1. Virtual DOM:
- React sử dụng Virtual DOM để cải thiện hiệu suất. Khi trạng thái của một component thay đổi, React cập nhật Virtual DOM trước, sau đó tính toán sự khác biệt và cập nhật DOM thật một cách hiệu quả.
2. JSX (JavaScript XML):
- JSX là một cú pháp mở rộng của JavaScript, cho phép bạn viết mã HTML trực tiếp trong JavaScript. JSX giúp mã React trở nên dễ đọc và viết hơn.
3. Component-Based Architecture:
- React cho phép xây dựng ứng dụng bằng cách tạo ra các component độc lập, có thể tái sử dụng. Mỗi component là một phần của UI và có logic riêng biệt.
4. Unidirectional Data Flow:
- React sử dụng luồng dữ liệu một chiều, giúp dễ dàng theo dõi và quản lý trạng thái của ứng dụng. Điều này làm giảm nguy cơ lỗi và giúp việc debug trở nên dễ dàng hơn.
5. State và Props:
- State là một đối tượng lưu trữ dữ liệu động của component và có thể thay đổi theo thời gian.
Props (properties) là các tham số được truyền vào component từ component cha, cho phép chia sẻ dữ liệu giữa các component.
6. Lifecycle Methods:
- React cung cấp các phương thức vòng đời (lifecycle methods) để kiểm soát và quản lý các giai đoạn khác nhau của component như componentDidMount, componentDidUpdate, và componentWillUnmount.
7. Hooks:
- Hooks là một tính năng mạnh mẽ được giới thiệu từ React 16.8, cho phép bạn sử dụng state và các tính năng khác của React mà không cần viết class. Các hooks phổ biến bao gồm useState, useEffect, useContext, và nhiều hooks khác.
8. Context API:
- Context API cho phép bạn truyền dữ liệu qua các component mà không cần phải truyền props qua từng cấp. Điều này rất hữu ích khi cần chia sẻ dữ liệu giữa nhiều component không có mối quan hệ cha-con trực tiếp.
9. React Router:
- React Router là một thư viện cho phép bạn quản lý điều hướng trong ứng dụng React, giúp tạo ra các ứng dụng single-page với khả năng điều hướng linh hoạt và mạnh mẽ.
10. Code Splitting:
- Code splitting là một kỹ thuật tối ưu hóa giúp tải ứng dụng nhanh hơn bằng cách chia nhỏ mã nguồn thành các phần nhỏ và chỉ tải khi cần thiết. React hỗ trợ code splitting thông qua dynamic import và các công cụ như Webpack.
11. Server-Side Rendering (SSR):
- React có thể kết hợp với các thư viện như Next.js để thực hiện Server-Side Rendering, giúp cải thiện SEO và tốc độ tải trang cho các ứng dụng React.
12. Portals:
- Portals cho phép bạn render một phần tử con vào một nút DOM khác ngoài cây DOM của component cha. Điều này hữu ích cho việc tạo modal, tooltip, hoặc các phần tử nổi khác.
13. Strict Mode:
- Strict Mode là một công cụ giúp phát hiện các vấn đề tiềm ẩn trong ứng dụng React của bạn. Nó giúp bạn nhận diện các phần của ứng dụng có thể gặp vấn đề trong tương lai.

## câu 4: Phân biệt Real DOM và Virtual DOM ?
### So sánh Real DOM và Virtual DOM
| Tiêu chí        | Real DOM                                     | Virtual DOM                                   |
|-----------------|----------------------------------------------|----------------------------------------------|
| **Định nghĩa**  | Mô hình đối tượng tài liệu thực được trình duyệt sử dụng | Bản sao nhẹ của DOM thực được lưu trữ trong bộ nhớ |
| **Cập nhật**    | Chậm, tốn kém hiệu suất khi có nhiều thay đổi | Nhanh, chỉ cập nhật những phần thay đổi       |
| **Hiệu suất**   | Chậm hơn khi có nhiều thay đổi nhỏ liên tục   | Tối ưu hóa hiệu suất, nhanh và mượt mà hơn     |
| **Sử dụng**     | Trình duyệt sử dụng trực tiếp để hiển thị trang web | Lớp trung gian giúp tối ưu hóa cập nhật lên Real DOM |

