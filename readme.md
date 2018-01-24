### Vuajs Tutorial
- v-for có thể được dùng để trình bày một danh sách các item sử dụng dữ liệu từ một mảng
- v-model sử dụng cho gắn dữ liệu theo hai chiều view ↔ viewmodel ↔ mode, nó tự động lấy dữ liệu được nhập vào và cập nhật xuống model. 

- Các phương thức thao tác với mảng: push(), pop(), shift(), unshift(), splice(), sort(), reverse()
- key modifier: .enter, .tab .delete (dùng cho cả hai phím “Delete” và “←”), .esc, .space, .up, .down, .left, .right

## Note 
- Nếu truyền tham số vào trong template thì nhất định phải có pop 
- props: ['myMessage'] được viết theo kiểu camelCase sẽ được chuyển thành kebab-case trong HTML ( my-message)
