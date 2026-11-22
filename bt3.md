# BÀI TẬP: XÂY DỰNG AI CHẤM ĐIỂM BÀI VIẾT BẰNG RUBRIC

## 1. Mục tiêu

Sử dụng AI để đánh giá bài viết của sinh viên theo bảng tiêu chí Rubric có sẵn. AI phải chấm điểm dựa trên nội dung thực tế, đưa ra minh chứng và đề xuất cách cải thiện bài viết.

## 2. Prompt thiết lập vai trò người chấm

```text
Bạn là giảng viên chấm bài viết của sinh viên đại học.

Hãy đánh giá bài viết với chủ đề:
"Vai trò của AI trong hoạt động học tập của sinh viên đại học".

Sử dụng đúng 5 tiêu chí và điểm tối đa sau:

1. Đúng chủ đề: 2 điểm.
2. Nội dung và lập luận: 3 điểm.
3. Ví dụ minh họa: 2 điểm.
4. Cấu trúc bài viết: 1.5 điểm.
5. Ngữ pháp và diễn đạt: 1.5 điểm.

Yêu cầu:
- Không thay đổi điểm tối đa của từng tiêu chí.
- Chấm dựa trên nội dung thực tế, không chấm cảm tính.
- Mỗi điểm số phải có minh chứng từ bài viết.
- Không đánh giá cao chỉ vì bài viết dài.
- Chỉ rõ lỗi và đề xuất cách sửa.
- Tính tổng điểm trên thang 10.

Trình bày kết quả gồm:
1. Bảng điểm từng tiêu chí.
2. Minh chứng cho từng điểm số.
3. Điểm mạnh và điểm yếu.
4. Đề xuất cải thiện.
5. Tổng điểm cuối cùng.

Nếu không có minh chứng phù hợp, không tự suy đoán
hoặc tự thêm nội dung vào bài viết.
```

## 3. Rubric chấm điểm

| Tiêu chí | Nội dung đánh giá | Điểm tối đa |
|---|---|---:|
| Đúng chủ đề | Bám sát chủ đề AI trong học tập | 2 |
| Nội dung và lập luận | Ý rõ ràng, có phân tích và lập luận hợp lý | 3 |
| Ví dụ minh họa | Có ví dụ thực tế, phù hợp | 2 |
| Cấu trúc bài viết | Có mở bài, thân bài, kết bài | 1.5 |
| Ngữ pháp và diễn đạt | Ít lỗi chính tả, câu văn rõ ràng | 1.5 |
| **Tổng** | | **10** |

## 4. Bài viết mẫu

### Vai trò của AI trong hoạt động học tập của sinh viên đại học

Hiện nay, trí tuệ nhân tạo (AI) đang phát triển mạnh mẽ và được sử dụng trong nhiều lĩnh vực, đặc biệt là giáo dục. Đối với sinh viên đại học, AI là một công cụ hỗ trợ học tập giúp tiết kiệm thời gian và nâng cao hiệu quả học tập.

Trước hết, AI giúp sinh viên tìm kiếm và tiếp cận kiến thức nhanh hơn. Khi gặp một bài học khó hiểu, sinh viên có thể sử dụng AI để giải thích lại bằng ngôn ngữ đơn giản. Ngoài ra, AI còn hỗ trợ tóm tắt tài liệu, dịch thuật và gợi ý cách giải quyết vấn đề. Nhờ đó, sinh viên có thể chủ động hơn trong quá trình học tập.

Ví dụ, khi học lập trình Java, sinh viên có thể hỏi AI về khái niệm Class, Object hoặc nhờ giải thích lỗi trong đoạn code. AI có thể đưa ra ví dụ cụ thể để người học dễ hiểu hơn. Đây là cách hỗ trợ khá hữu ích đối với những người mới bắt đầu học lập trình.

Tuy nhiên, việc sử dụng AI cũng có một số hạn chế. Nếu quá phụ thuộc vào AI, sinh viên có thể mất khả năng tự suy nghĩ và giải quyết vấn đề. Bên cạnh đó, AI đôi khi cung cấp thông tin chưa chính xác nên người học cần kiểm tra lại kiến thức từ tài liệu đáng tin cậy.

Tóm lại, AI mang lại nhiều lợi ích cho hoạt động học tập của sinh viên đại học. Tuy nhiên, sinh viên cần sử dụng AI hợp lý, xem đây là công cụ hỗ trợ chứ không phải thay thế hoàn toàn việc tự học.

## 5. Kết quả AI chấm điểm

| Tiêu chí | Điểm đạt | Điểm tối đa | Nhận xét |
|---|---:|---:|---|
| Đúng chủ đề | 2 | 2 | Bám sát chủ đề |
| Nội dung và lập luận | 2.5 | 3 | Có phân tích lợi ích và hạn chế |
| Ví dụ minh họa | 1.5 | 2 | Có ví dụ Java nhưng chưa đi sâu |
| Cấu trúc bài viết | 1.5 | 1.5 | Đủ mở bài, thân bài, kết bài |
| Ngữ pháp và diễn đạt | 1.5 | 1.5 | Câu văn rõ ràng, dễ hiểu |
| **Tổng điểm** | **9** | **10** | |

## 6. Bảng đối chiếu điểm số và minh chứng

| Tiêu chí | Minh chứng trong bài viết | Lý do trừ điểm |
|---|---|---|
| Đúng chủ đề | AI hỗ trợ sinh viên tìm kiếm kiến thức và học tập | Không trừ điểm |
| Nội dung và lập luận | Phân tích lợi ích, hạn chế và sự phụ thuộc vào AI | Chưa phân tích sâu cách khắc phục hạn chế |
| Ví dụ minh họa | Ví dụ sử dụng AI khi học Java | Chưa có tình huống cụ thể hoặc kết quả thực tế |
| Cấu trúc bài viết | Có 5 đoạn với mở bài, thân bài và kết bài rõ ràng | Không trừ điểm |
| Ngữ pháp và diễn đạt | Các câu văn dễ hiểu, liên kết hợp lý | Không trừ điểm |

## 7. Nhận xét và đề xuất cải thiện

### Điểm mạnh
- Bài viết đúng chủ đề và không bị lan man.
- Nội dung có đề cập cả lợi ích và hạn chế của AI.
- Có ví dụ liên quan đến việc học lập trình Java.
- Bố cục rõ ràng, dễ theo dõi.

### Điểm yếu
- Phần lập luận chưa phân tích sâu.
- Ví dụ minh họa còn chung chung.
- Chưa đưa ra cách sử dụng AI hiệu quả trong từng tình huống học tập.

### Đề xuất cải thiện
- Bổ sung ví dụ thực tế về việc dùng AI để sửa lỗi code hoặc ôn tập kiến thức.
- Phân tích rõ hơn tác hại của việc phụ thuộc vào AI.
- Đưa ra giải pháp như kiểm tra thông tin, tự làm bài trước khi hỏi AI và đối chiếu với giáo trình.

## 8. Kết quả đạt được

Qua bài tập, em hiểu rằng Rubric giúp việc chấm điểm có tiêu chí rõ ràng và thống nhất hơn. AI không chỉ đưa ra điểm số mà còn phải giải thích lý do chấm, trích dẫn minh chứng và chỉ ra những phần cần cải thiện.

Việc kết hợp AI với Rubric giúp sinh viên biết được điểm mạnh, điểm yếu của bài viết và có hướng sửa bài cụ thể hơn.