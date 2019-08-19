# PHP Coding Conventions

### 1. Mô tả tính "bắt buộc" của các từ ngữ

Phần này mô tả tính bắt buộc của các từ ngữ (sau này được viết hoa để làm nổi bật) được sử dụng trong các tài liệu.

Theo thứ tự giảm dần của tính bắt buộc, ta có:

- (1) **MUST, REQUIRED, SHALL** hay **PHẢI**: thể hiện rằng quy ước này cần tuyệt đối tuân thủ, không thể thay đổi trong bất cứ hoàn cảnh nào.
- (2) **SHOULD, RECOMMENDED** hay **NÊN**: thể hiện rằng quy ước này được khuyến khích sử dụng như là một mặc định nếu như không có một yêu cầu cụ thể nào khác. Nếu như không tuân thủ thì cần cân nhắc cẩn thận cũng như cần đặt ra một quy tắc tương đương để thay thế.
- (3) **MAY, OPTIONAL** hay **TÙY CHỌN**: thể hiện rằng quy ước này không bắt buộc sử dụng, có thể lựa chọn dùng hoặc không dùng cũng không có vấn đề gì.

Một vấn đề lưu ý khác, đó là trong các trường hợp (2) và (3), nếu đã sử dụng thì cần thống nhất trong toàn bộ source code (bao gồm cả vendor, package, project code,..). Vì lí do đó, nếu như sử dụng một framework nào đó và codebase của framework đó tuân theo một quy ước (kể cả việc quy ước đó không bắt buộc) thì project code cũng NÊN tuân theo quy ước tương tự.

Theo nghĩa phủ định, ta có:

- (4) **MUST NOT, SHALL NOT** hay **KHÔNG ĐƯỢC**
- (5) **SHOULD NOT, NOT RECOMMENDED** hay **KHÔNG NÊN**
