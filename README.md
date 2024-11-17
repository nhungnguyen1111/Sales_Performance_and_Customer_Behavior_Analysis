# Phân Tích Hiệu Suất Bán Hàng Online và Phân Khúc Khách Hàng của Contoso

## Mục lục

- [Tổng quan dự án](#tổng-quan-dự-án)
- [Mục tiêu](#mục-tiêu)
- [Dữ liệu](#dữ-liệu)
- [Phân tích dữ liệu](#phân-tích-dữ-liệu)
- [Insights](#insights)
- [Đề xuất](#đề-xuất)
- [Tài liệu tham khảo](#tài-liệu-tham-khảo)

### Tổng quan dự án

Contoso là một tập đoàn bán lẻ đa quốc gia có trụ sở tại Paris (Pháp) với danh mục sản phẩm hơn 100 nghìn loại khác nhau. Việc phân tích dữ liệu sẽ tập trung vào các chỉ số về bán hàng online như lợi nhuận, doanh thu, tăng trưởng doanh thu hàng năm và chỉ số liên quan đến khách hàng như CLV. Từ đó, dự án đề xuất giải pháp cho sales manager để cải thiện chiến lược bán hàng và tối ưu hóa doanh thu cho Contoso.

### Mục tiêu

- Xác định những mặt hàng bán chạy và cơ hội để triển khai hoạt động upselling và cross-selling
- Phân tích doanh thu, doanh số bán hàng online theo thời gian (2007-2009)
- Phân khúc khách hàng theo nhân khẩu học và xác định tệp khách hàng mang lại giá trị cao.

### Dữ liệu

Dự án sử dụng database được cung cấp bởi Microsoft, tham khảo tại [đây](https://www.microsoft.com/en-us/download/details.aspx?id=18279). Vì bộ dữ liệu này bao gồm thông tin từ nhiều phòng ban trong doanh nghiệp như C-level, Sales/Marketing, IT, Finance... nên dự án sẽ chỉ tập trung vào các bảng sau:

- **FactOnlineSales**: lưu dữ liệu bán hàng về doanh thu, doanh số, chi phí, lượng hàng trả về và giá trị mặt hàng giảm giá cho mỗi giao dịch online
- **DimDate**: mô tả thời gian diễn ra giao dịch theo năm, quý, tháng, tuần và ngày
- **DimProduct**: thông tin về sản phẩm như nhà sản xuất, thương hiệu, đặc điểm bên ngoài và chi phí, giá bán cho mỗi sản phẩm
- **DimProductCategory**: mô tả tên và key cho từng danh mục sản phẩm bao gồm: Audio, Computers, Cellphones...)
- **DimProductSubCategory**: Phân loại sản phẩm con (được chia nhỏ hơn so với danh mục sản phẩm) bao gồm: Televisions, VCD&DVD, Accessories...
- **DimCustomer**: thông tin nhân khẩu học của khách hàng (giới tính, thu nhập cả năm, học vấn, nghề nghiệp...) 
- **DimPromotion**: chi tiết về từng loại giảm giá và mức giảm giá
- **DimGeography**: thông tin địa lý theo từng quốc gia, từng vùng gắn với nơi khách hàng sinh sống

Database diagram được mô tả như hình dưới đây:
![](https://github.com/Toridotoji/Project-1/blob/main/database%20diagram.png?raw=true)

### Phân tích dữ liệu
Xem thêm tại file [Phương pháp phân tích dữ liệu](Project-1/

### Insights

### Đề xuất

### Tài liệu tham khảo
