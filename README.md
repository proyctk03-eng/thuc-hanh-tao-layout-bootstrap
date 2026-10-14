# [Thực hành] Tạo layout trong Bootstrap

Bài thực hành sử dụng các thành phần của Bootstrap để tạo bố cục và nội dung trang web thương mại điện tử (Online Shopping Mall) theo giáo trình CodeGym.

## Cấu trúc trang web (`layout.html`)
- **Header**: Banner `Online shopping mall` với lớp CSS tùy chỉnh `.shopping-mall` và hình ảnh đối tượng đẩy sang phải `.pull-right`.
- **Nav (`navbar-inverse`)**: Thanh điều hướng Bootstrap với các biểu tượng Glyphicons (`home`, `list-alt`, `earphone`, `envelope`, `question-sign`, `user`) và dropdown menu tài khoản.
- **Article (`col-sm-9`)**: Lưới sản phẩm responsive chia làm 3 cột trên mỗi hàng (`col-sm-4 poly-prod`), sử dụng Bootstrap Panels hiển thị tên sản phẩm, hình ảnh và đơn giá.
- **Aside (`col-sm-3`)**:
  - Khối giỏ hàng `.poly-cart` hiển thị số lượng mặt hàng và tổng tiền.
  - Form tìm kiếm từ khóa với `.form-control`.
  - Danh mục chủng loại hàng hóa sử dụng `.list-group`.
- **Footer**: Panel thông tin bản quyền CodeGym.

## Công nghệ sử dụng
- HTML5
- Bootstrap 3.3.7 (CSS & JS)
- jQuery 3.2.1
- Custom CSS (`css/poly.css`)
