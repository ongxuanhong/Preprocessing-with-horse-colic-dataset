# Phân tích sơ khởi
* Dữ liệu có 300 mẫu
* Dữ liệu có 28 thuộc tính
* Thông tin các thuộc tính nằm trong file attribute.csv

# Rời rạc hóa các thuộc tính và điền giá trị cho các ô bị thiếu dữ liệu
Sử dụng bộ lọc của  Weka Unsupervised/Attribute
* Normalize: chuẩn hóa các thuộc tính về đoạn 0,1
* ReplaceMissingValue: thay thế tất cả các giá trị thiếu cho các thuộc tính dạng nomial và numeric trong tập dữ liệu  với giá trị mode và mean từ tập huấn luyện
* Discretize: là bộ lọc dùng để rời rạc hóa một loạt các thuộc tính numeric trong tập dữ liệu thành các thuộc tính nomial. Việc rời rạc đơn giản chia giỏ (binning)  sau đó gán các giá trị numeric tương ứng vào từng giỏ đó.
* NumericToNominal: là bộ lọc dùng để chuyển các thuộc tính dạng numeric thành nomial. Không như discretization (rời rạc hóa), bộ lọc này lấy tất cả các giá trị numeric gán vào danh sách các giá trị nomial của thuộc tính đó.
