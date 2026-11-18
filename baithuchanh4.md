# Bài thực hành 4: Phân tích kết quả học tập và đề xuất giải pháp cải thiện

## 1. Prompt hoàn chỉnh


Bạn là chuyên viên phân tích dữ liệu giáo dục, chỉ dựa trên dữ liệu được cung cấp.

Điểm kiểm tra 3 tuần học lập trình:

| Sinh viên | Tuần 1 | Tuần 2 | Tuần 3 |
|---|---|---|---|
| An | 8 | 7 | 5 |
| Bình | 7 | 6 | 4 |
| Chi | 9 | 8 | 8 |
| Dũng | 6 | 5 | 3 |
| Hà | 8 | 8 | 7 |

Quy tắc:
- Chỉ dùng dữ liệu trên. KHÔNG suy diễn nguyên nhân giảm điểm; nếu cần nhắc đến, chỉ đưa vào mục "Cần giảng viên xác minh".
- Mọi nhận định phải kèm số liệu chứng minh và hiển thị phép tính.

Hãy suy luận từng bước (Chain-of-Thought):
Bước 1 – Tính toán: mức thay đổi T1→T2, T2→T3, tổng T1→T3 và điểm TB của từng sinh viên.
Bước 2 – So sánh: xếp hạng sinh viên theo tổng thay đổi và điểm TB.
Bước 3 – Nhận định: xác định nhóm sa sút (nêu tiêu chí dựa trên dữ liệu) và nêu 3 nhận định quan trọng.
Bước 4 – Xác minh: liệt kê điều giảng viên cần kiểm tra thêm.
Bước 5 – Đề xuất: 3 giải pháp hỗ trợ cụ thể, mỗi giải pháp gắn với một nhận định.
Bước 6 – Tự kiểm tra phép tính và xem có suy diễn nguyên nhân không.

Trả lời bằng tiếng Việt, theo đúng thứ tự các bước.


## 2. Bảng phân tích kết quả

| Sinh viên | T1 | T2 | T3 | T1→T2 | T2→T3 | Tổng T1→T3 | Điểm TB |
|---|---|---|---|---|---|---|---|
| An | 8 | 7 | 5 | −1 | −2 | **−3** | 6,67 |
| Bình | 7 | 6 | 4 | −1 | −2 | **−3** | 5,67 |
| Chi | 9 | 8 | 8 | −1 | 0 | **−1** | 8,33 |
| Dũng | 6 | 5 | 3 | −1 | −2 | **−3** | 4,67 |
| Hà | 8 | 8 | 7 | 0 | −1 | **−1** | 7,67 |

*Thay đổi = điểm tuần sau − điểm tuần trước.*

## 3. Nhóm có dấu hiệu sa sút

**Tiêu chí:** giảm liên tục 2 lần đo và tổng giảm từ 3 điểm trở lên.

- **Sa sút:** An, Bình, Dũng (đều giảm 3 điểm, tuần 3 giảm 2 điểm).
- **Giảm nhẹ, cần theo dõi:** Chi, Hà (tổng giảm 1 điểm).

## 4. Ba nhận định quan trọng

1. **Cả 5 sinh viên đều giảm điểm** từ tuần 1 đến tuần 3 (từ −1 đến −3).
2. **An, Bình, Dũng giảm ngày càng nhanh:** tuần 2 giảm 1 điểm, tuần 3 giảm 2 điểm.
3. **Dũng cần ưu tiên nhất:** điểm TB thấp nhất (4,67) và điểm tuần 3 thấp nhất (3). Chi ổn định nhất (TB 8,33, giữ nguyên 8 ở tuần 3).

## 5. Cần giảng viên xác minh thêm

- [ ] Độ khó và thang chấm của bài kiểm tra có đổi giữa các tuần không.
- [ ] Mức độ tham gia lớp và nộp bài của An, Bình, Dũng.
- [ ] Phần kiến thức các em làm sai (xem bài làm cụ thể).
- [ ] Cần thêm dữ liệu tuần 4 trở đi vì mẫu mới có 5 sinh viên, 3 lần đo.

*Dữ liệu hiện tại chưa đủ để kết luận nguyên nhân giảm điểm.*

## 6. Ba giải pháp hỗ trợ học tập

1. **Kèm cặp nhóm nhỏ cho An, Bình, Dũng** (theo nhận định 2, 3): ôn tập ngắn hằng tuần, ưu tiên Dũng.
2. **Phân tích lỗi sai trước khi can thiệp** (theo nhận định 1): rà bài tuần 2, 3 để tìm phần kiến thức hụt, rồi giao bài luyện đúng phần đó.
3. **Kiểm tra ngắn hằng tuần để theo dõi** (theo nhận định 1, 3): đo lại tuần 4, 5, xem Chi và Hà có tiếp tục giảm không và đánh giá hiệu quả giải pháp 1, 2.
