Phần mềm quản lý thuốc và vật tư của nhà thuốc

1. Thông tin của sản bao gồm:
- ID
- Tên sản phẩm
- Số lượng sản phẩm
- Giá tiền sản phẩm
- Ngày nhập sản phẩm
- Nguồn nhập sản phẩm
- Phân loại sản phẩm (thuốc hoặc vật tư)

Trong đó có ID và phân loại không điền trực tiếp được. 
- ID sẽ được đánh tự động theo thứ tự sản phẩm được thêm vào bảng.
- Phân loại sẽ dùng nút chức năng để xác định loại sản phẩm nhập vào là thuốc hay vật tư y tế.

2. Các nút chức năng:
- Add: Thêm 1 sản phẩm vào bảng, các trường thông tin gồm tên, giá tiền, số lượng, ngày nhập và nguồn nhập cần được nhập vào và hợp lệ
- Edit: Sau khi nhấp vào một sản phẩm trong bảng và thay đổi thông tin của sản phẩm, có thể cập nhật lại bằng cách nhấn vào nút này
- Delete: Xoá sản phẩm được chọn
- Clear: Loại bỏ việc chọn một sản phẩm và làm sạch các TextField
- Phân loại: Để phân loại sản phẩm đó là thuốc hay là vật tư
- Refresh Table: Hiện toàn bộ các sản phẩm ở trong cơ sở dữ liệu
- Now: Chọn ngày hôm nay cho DatePicker tương ứng
- Phần các nút sắp xếp:
    + Xếp theo tên sản phẩm: Sắp xếp các sản phẩm trong bảng theo thứ tự tên (a-z)
    + Xếp theo số lượng: Sắp xếp các sản phẩm trong bảng theo số lượng
    + Xếp theo giá cả: Sắp xếp các sản phẩm trong bảng theo giá tiền
- Phần tìm kiếm:
    + Tìm theo tên sản phẩm: tìm kiếm các sản phẩm có tên chứa nội dung ở TextField bên cạnh
    + Tìm sản phẩm theo ngày: tìm kiếm các sản phẩm trong khoảng ngày được chọn
- Phần thống kê:
    + Nếu nhấn vào thống kê và chọn ngày, các sản từ ngày "From" đến ngày "To" sẽ được tổng hợp vào cho biết các thông tin như tổng số lượng sản phẩm hiện có và tổng loại thuốc và các sản phẩm đó sẽ được hiển thị trong bảng