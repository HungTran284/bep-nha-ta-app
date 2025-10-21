# Ứng dụng mô hình chuỗi thời gian (SARIMA, LSTM) để dự báo nhu cầu và tối ưu quyết định nhập hàng trong thương mại điện tử.
## Tổng quan
Đồ án thực hiện quy trình làm sạch dữ liệu, EDA, Pre-processing và dự đoán bằng 2 mô hình liên quan đến chuỗi thời gian khác nhau, qua đó cung cấp cái nhìn về hiệu quả của từng mô hình. Cuối cùng là đưa ra những phân tích và khuyến nghị trong vấn đề nhập hàng dựa tho dữ liệu đã dự đoán.
<a href="" target="_blank">Link tất cả file của đồ án</a>

## Files
### Source code
"251MI1701_Group04_SourceCode_FinalProject.ipynb": Source code này bao gồm toàn bộ quy trình thực hiện của nhóm bằng Python, bắt đầu từ EDA, Pre-processing đến triển khai 2 mô hình LSTM và SARIMA cuối cùng là so sánh 2 kết quả đánh giá mô hình với nhau.

## Trực quan hóa dữ liệu bằng Power BI
- <a href="" target="_blank">Link Power BI online</a>
- <a href="" target="_blank">Link file Power BI</a>
<br>
“251MI1701_Group04_Dashboard_FinalProject.pbix”: File PowerBI mô tả những dữ liệu và phân tích về doanh số và xu hướng thông qua những biểu đồ trong PowerBI


## Dataset
<a href="" target="_blank">Link Datasets</a>
- "Electronic_sales_Sep2023-Sep2024.csv": Dataset ban đầu để nhóm thực hiện việc xử lý
- Dataset sau khi đã tiền xử lý trước khi thực nghiệm mô hình.
- "forecast_12weeks_results.xlsx": Dataset dự đoán kết quả số lượng 12 tuần tiếp theo bằng 2 mô hình LSTM và SARIMA

## Other:
process.draw.io.jpg: hình ảnh toàn bộ quy trình thực hiện đồ án của nhóm

## Conclusion
Kết quả cho thấy hai mô hình chuỗi thời gian có mức độ dự đoán khác nhau về xu hướng nhập hàng. Mô hình LSTM cho độ chính xác cao hơn. Dựa trên kết quả này cùng với những phân tích và khuyến nghị, doanh nghiệp có thể điều chỉnh kế hoạch nhập hàng theo từng giai đoạn và từng nhóm hàng giúp tối ưu chi phí và hạn chế tình trạng tồn kho.
