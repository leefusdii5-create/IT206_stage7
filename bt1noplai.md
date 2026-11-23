# BÀI TẬP: XỬ LÝ TÀI LIỆU DÀI BẰNG KỸ THUẬT CHUNKING

## 1. Mục tiêu

Sử dụng kỹ thuật Chunking để chia tài liệu nội bộ của Công ty ABC Technology thành nhiều phần nhỏ, sau đó dùng AI tóm tắt và tổng hợp nội dung.

Cách làm này giúp AI xử lý tài liệu dài hiệu quả hơn, hạn chế bỏ sót thông tin và giữ được các quy định quan trọng trong tài liệu gốc.

## 2. Prompt xử lý từng phần tài liệu

```text
Bạn là trợ lý nhân sự của Công ty ABC Technology.

Tôi sẽ cung cấp tài liệu nội bộ theo từng chương hoặc từng phần.
Hãy đọc và tóm tắt nội dung theo các yêu cầu sau:

1. Xác định chủ đề chính của phần tài liệu.
2. Tóm tắt các quy định quan trọng.
3. Giữ nguyên số liệu, thời hạn, tỷ lệ và điều kiện áp dụng.
4. Ghi rõ các trường hợp ngoại lệ.
5. Không tự thêm thông tin hoặc suy đoán quy định.
6. Nếu tài liệu không đề cập nội dung nào, ghi rõ
   "Chưa được đề cập trong tài liệu".

Trình bày kết quả theo cấu trúc:

- Tên chương:
- Nội dung chính:
- Quy định quan trọng:
- Điều kiện áp dụng:
- Trường hợp ngoại lệ:
- Số liệu và thời hạn cần lưu ý:
- Vị trí nội dung trong tài liệu:

Chỉ sử dụng thông tin có trong phần tài liệu được cung cấp.
```

## 3. Prompt tổng hợp các phần tài liệu

```text
Bạn là trợ lý tổng hợp tài liệu nhân sự của Công ty ABC Technology.

Tôi sẽ cung cấp các bản tóm tắt đã được xử lý từ từng chương.

Hãy tổng hợp thành một tài liệu hoàn chỉnh theo yêu cầu:

1. Kết hợp nội dung của tất cả các chương.
2. Phân loại theo từng chủ đề nhân sự.
3. Phát hiện các quy định có liên quan giữa các chương.
4. Giữ nguyên số liệu, thời hạn, tỷ lệ và điều kiện.
5. Không bỏ qua các trường hợp ngoại lệ.
6. Không tự suy đoán hoặc bổ sung quy định ngoài tài liệu.
7. Phân biệt rõ thông tin đã có và thông tin chưa được đề cập.
8. Kiểm tra các nội dung trùng lặp hoặc có điểm khác nhau.

Đầu ra gồm:
- Bảng tổng hợp quy định.
- Bản tóm tắt hoàn chỉnh khoảng 1.000–1.500 từ.
- Những nội dung liên quan giữa các chương.
- Những thông tin còn thiếu hoặc chưa rõ.
- Danh sách câu hỏi kiểm tra kèm câu trả lời và vị trí
  trong tài liệu gốc.

Nếu không tìm thấy căn cứ trong tài liệu, hãy ghi rõ
"Không tìm thấy thông tin trong tài liệu gốc".
```

## 4. Quy trình thực hiện

| Bước | Công việc | Kết quả |
|---|---|---|
| 1 | Đưa file PDF/DOCX vào AI | Nhận tài liệu gốc |
| 2 | Chia tài liệu theo 5 chương | Các phần nội dung riêng |
| 3 | Dùng Prompt 1 xử lý từng chương | 5 bản tóm tắt |
| 4 | Lưu lại kết quả từng chương | Dữ liệu đã xử lý |
| 5 | Dùng Prompt 2 tổng hợp | Một bản tổng hợp chung |
| 6 | Kiểm tra lại với tài liệu gốc | Phát hiện nội dung thiếu hoặc sai |

## 5. Bảng tổng hợp các quy định

| Chủ đề | Quy định chính | Điều kiện áp dụng | Ngoại lệ |
|---|---|---|---|
| Nội quy lao động | Theo quy định tại chương 1 | Theo đối tượng và phạm vi áp dụng trong tài liệu | Ghi theo các trường hợp được nêu trong tài liệu |
| Nghỉ phép | Theo quy định tại chương 2 | Theo điều kiện nghỉ phép của nhân viên | Các trường hợp nghỉ phép đặc biệt |
| Làm thêm giờ | Theo quy định tại chương 3 | Theo điều kiện và thời gian làm thêm | Các trường hợp ngoại lệ được quy định |
| Đánh giá nhân viên | Theo quy định tại chương 4 | Theo tiêu chí và thời gian đánh giá | Các trường hợp đánh giá đặc biệt |
| Khen thưởng và kỷ luật | Theo quy định tại chương 5 | Theo điều kiện xét thưởng và xử lý vi phạm | Các trường hợp ngoại lệ tương ứng |

*Lưu ý: Bảng trên là khung phân loại theo đề bài. Khi thực hiện cần điền nội dung và số liệu chính xác từ tài liệu gốc, không tự tạo ra quy định.*

## 6. Bản tóm tắt nội dung tài liệu

### 6.1. Nội quy lao động

Chương 1 trình bày các quy định chung về nội quy lao động tại Công ty ABC Technology. Nội dung cần tập trung vào trách nhiệm của nhân viên, thời gian làm việc, tác phong và các yêu cầu phải tuân thủ trong quá trình làm việc.

Khi tổng hợp cần ghi rõ từng quy định, đối tượng áp dụng và hình thức xử lý nếu có vi phạm. Những trường hợp ngoại lệ phải được giữ nguyên theo tài liệu.

### 6.2. Quy định nghỉ phép

Chương 2 đề cập đến chính sách nghỉ phép dành cho nhân viên. Cần xác định số ngày nghỉ, điều kiện được nghỉ, quy trình xin phép và thời gian báo trước.

Đặc biệt, cần giữ nguyên các mốc thời gian và điều kiện hưởng phép. Nếu tài liệu có quy định riêng đối với nghỉ phép đột xuất hoặc các trường hợp đặc biệt thì phải trình bày đầy đủ.

### 6.3. Chính sách làm thêm giờ

Chương 3 quy định về việc làm thêm giờ của nhân viên. Các nội dung cần trích xuất gồm điều kiện làm thêm, thời gian làm thêm, cách đăng ký và tỷ lệ thanh toán nếu được đề cập.

Cần chú ý giữ nguyên các tỷ lệ tính lương, giới hạn thời gian và điều kiện áp dụng. Không tự bổ sung mức lương hoặc quyền lợi nếu tài liệu không có thông tin.

### 6.4. Quy định đánh giá nhân viên

Chương 4 trình bày cách công ty đánh giá kết quả làm việc của nhân viên. Cần xác định các tiêu chí đánh giá, thời gian thực hiện, đối tượng đánh giá và cách sử dụng kết quả đánh giá.

Các tiêu chí và điều kiện cần được ghi rõ để nhân viên hiểu cách công ty xem xét hiệu quả công việc.

### 6.5. Chính sách khen thưởng và kỷ luật

Chương 5 đề cập đến các hình thức khen thưởng và xử lý vi phạm. Nội dung cần làm rõ điều kiện được khen thưởng, các hình thức kỷ luật và quy trình thực hiện.

Cần phân biệt rõ từng hành vi vi phạm với hình thức xử lý tương ứng. Không được bỏ qua các trường hợp giảm nhẹ, ngoại lệ hoặc điều kiện đặc biệt nếu có.

### 6.6. Nội dung liên quan giữa các chương

Các chương có thể có những nội dung liên quan với nhau:

- Nội quy lao động liên quan đến việc xác định hành vi vi phạm và xử lý kỷ luật.
- Nghỉ phép liên quan đến thời gian làm việc và việc đánh giá nhân viên.
- Làm thêm giờ liên quan đến thời gian làm việc và quyền lợi của nhân viên.
- Kết quả đánh giá có thể liên quan đến chính sách khen thưởng.
- Khen thưởng và kỷ luật đều liên quan đến quá trình đánh giá ý thức và hiệu quả làm việc.

Các mối liên hệ trên cần được đối chiếu với tài liệu gốc trước khi kết luận là quy định chính thức của công ty.

## 7. Câu hỏi kiểm tra thông tin

| STT | Câu hỏi | Câu trả lời | Vị trí cần đối chiếu |
|---|---|---|---|
| 1 | Nhân viên phải tuân thủ những nội dung nào trong nội quy lao động? | Trích các nghĩa vụ được quy định trong tài liệu. | Chương 1 |
| 2 | Nhân viên được nghỉ phép theo những điều kiện nào? | Trích điều kiện và số ngày nghỉ trong tài liệu. | Chương 2 |
| 3 | Công ty quy định tỷ lệ thanh toán làm thêm giờ như thế nào? | Trích chính xác các tỷ lệ trong tài liệu. | Chương 3 |
| 4 | Nhân viên được đánh giá dựa trên những tiêu chí nào? | Trích các tiêu chí đánh giá được nêu. | Chương 4 |
| 5 | Công ty áp dụng những hình thức khen thưởng và kỷ luật nào? | Liệt kê các hình thức có trong tài liệu. | Chương 5 |
| 6 | Những trường hợp ngoại lệ nào được đề cập trong chính sách nghỉ phép? | Trích các trường hợp ngoại lệ tương ứng. | Chương 2 |

*Lưu ý: Đây là bộ câu hỏi mẫu. Khi có tài liệu gốc, cần điền câu trả lời cụ thể và số trang hoặc mục chính xác để bảo đảm không suy đoán.*

## 8. Kiểm tra và đánh giá kết quả

Sau khi AI hoàn thành việc tổng hợp, cần đối chiếu lại với 5 chương của tài liệu gốc theo các tiêu chí:

- Đã xử lý đầy đủ cả 5 chương.
- Không sai lệch số liệu, tỷ lệ và thời hạn.
- Không bỏ qua các điều kiện và trường hợp ngoại lệ.
- Các nội dung chưa được đề cập phải ghi rõ.
- Câu trả lời có vị trí đối chiếu cụ thể trong tài liệu.
- Các quy định liên quan giữa các chương được kiểm tra lại.

## 9. Kết quả đạt được

Việc sử dụng kỹ thuật Chunking giúp chia tài liệu dài thành các phần nhỏ để AI xử lý lần lượt. Sau đó, các bản tóm tắt được lưu lại và tổng hợp thành một tài liệu chung.

Phương pháp này giúp tiết kiệm thời gian đọc tài liệu, dễ quản lý thông tin và hạn chế tình trạng AI bỏ sót nội dung do giới hạn Context Window. Tuy nhiên, kết quả cuối cùng vẫn cần được đối chiếu với tài liệu gốc để bảo đảm độ chính xác.