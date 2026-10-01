# Frontend Master

## Chương 1: HTML & CSS

`Đặt vấn đề`

1. Bạn có biết hết tất cả các thẻ HTML hay không?
2. Bạn có thể điều khiển được tất cả các thẻ HTML hay không?

`Các thẻ HTML thông dụng`

1. `html`: Thẻ mở đầu của 1 trang HTML - kiểu none
2. `head` Thẻ chứa các thẻ trong phần đầu của trang HTML - none
3. `title` Tiêu đề trang web - none
4. `meta` Mô tả tổng quát về nội dung trang web
5. `link` Dùng để nhúng các tập tin nào đó vào trang web
6. `script` Dùng để nhúng tập tin javascript
7. `style` Dùng để bao bọc nội dung CSS
8. `body` Thẻ chứa nội dung chính của website - block level
9. `h1->h6` Thẻ tiêu đề - block level
10. `div` Thẻ dùng để chứa nội dung - block level
11. `span` Thẻ chứa nội dung inline - inline level
12. `p` Thẻ chứa đoạn văn bản - block level
13. `center` Thẻ căn giữa đối tượng nằm bên trong - block level
14. `a` Thẻ tạo link - inline level
15. `ul` Thẻ kết hợp với thẻ `li` để tạo danh sách không thứ tự - block level
16. `img` Thẻ dùng để hiển thị nội dung hình ảnh - inline
17. `form` Thẻ form nhập liệu - block level
18. `br` Thẻ xuống hàng - block level
19. `hr` Thẻ tạo đường kẻ ngang - block level
20. `table` Thẻ tạo bảng - block level
21. `iframe` Thẻ nhúng frame - block level
22. `b` Tạo chữ đậm - inline
23. `i` Tạo chữ nghiêng - inline
24. `u` Tạo chữ gạch dưới - inline
25. `s` Tạo chữ gạch ngang <=> thẻ `del` - inline
26. `sub` `sup` Tạo kiểu chữ vd số mũ hoặc công thức hoá học - inline
27. `blockquote` Mô tả phần trích dẫn - block level
28. `tt` `code` Tạo kiểu chữ cho phần mô tả mã nguồn
29. `pre` Định dạng nội dung như trong code hiển thị - block level

`Phân loại thẻ HTML`

- None: Khối này không hiển thị nội dung bên trong
- Block level: Khối này hiển thị nội dung bên trong và có độ rộng full chiều dài của trình duyệt.
- Inline: Khối này hiển thị nội dung bên trong và có chiều ngang tuỳ thuộc độ dài(nội dung) bên trong khối, và nó sẽ không xuống hàng, nằm trên cùng một hàng nếu có nhiều thẻ inline cùng nhau

`Định dạng độ ưu tiên CSS`
inline style > # > class > slector> internal css > external css

## Chương 2: Phân nhóm định dạng

1. Type group: định dạng cho văn bản
2. background group: định dạng hình nền cho đối tượng.
3. block group: định dạng cho văn bản
4. border group: định dạng đường viền cho đối tượng
5. box group: định dạng kích thước vị trí cho khối
6. list group: định dạng cho các danh sách
7. position group: định toạ độ của một phần tử HTML nào đó.

`01 - Type group`

1. `font family`: Nhóm font được sử dụng cho một đối tượng HTML
2. `font-size`: Kích thước văn bản
3. `font-style`: Định kiểu cho font chữ nghiêng hay thẳng
4. `font-variant`: Định kiểu cho font chữ thường hoặc chữ hoa
5. `font-weight`: kiểu của chữ
6. `line-height`: Chiều cao giữa các dòng của văn bản
7. `text-transform`: Kiểu hiển thị của font chữ trong văn bản
8. `text-decoration`: Kiểu hiển thị của font chữ trong văn bản
9. `color`: Màu sắc của văn bản.

`02 - Background group`

1. `background-color`: màu nền của đối tượng
2. `background-image`: Sử dụng nền là một hình ảnh
3. `background-repeat`: Kiểu hiển thị hình nền cho đối tượng
4. `background-position`: Vị trí hiển thị của hình nền
5. `background-attachment`: Chế độ cố định hình nền

`03 - Block group`

1.`letter-spacing`: Khoảng cách giữa các ký tự 2. `word-spacing`: Khoảng cách giữa các từ trong đoạn văn bản 3. `text-align`: Vị trí của đoạn văn bản 4. `text-indent`: khoảng cách thụt đầu dòng của 1 đoạn văn 5. `white-spacing`: Định dạng cho khoảng trắng trong đoạn văn bản 6. `vertical-align`: vị trí của 1 phần tử 7. `display`: Các kiểu hiển thị theo kiểu block, inline

`04 - border group`

1. `border-width`: độ rộng của đường viền
2. `border-style`: kiểu đường viền
3. `border-color`: Màu sắc đường viền

`04 - box group`

1. `width`,`min-width`, `max-width`: Chiều rộng của đối tượng
2. `height`, `min-height`, `max-height`: Chiều cao của đối tượng
3. `margin`: Khoảng cách đối tượng với phần tử bên ngoài
4. `padding`: Khoảng cách đối với phần tử bên trong

