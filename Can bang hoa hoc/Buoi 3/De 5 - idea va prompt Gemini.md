# Đề 5. Nhật ký vận hành lò tổng hợp methanol (Buổi 3, kiểm tra 30 phút đầu buổi)

Số liệu đã tính kiểm bằng code (Kc = 0,25/(0,50 × 1,0²) = 0,50; thêm CO: Q = 0,25; rút CH₃OH: Q = 0,25; nén: Q = 0,125, bằng Kc/4).

## IDEA (D2)

```
5. Nhật ký lò tổng hợp methanol
Chủ đề: Tác động lên Q và lên Kc trong tổng hợp methanol (Hóa học)
Loại: A (bảng thao tác – kết quả) · Tier: M2

* Mục tiêu: HS phân biệt tác động làm lệch Q (hệ quay về Kc cũ) với tác động làm dời Kc (hệ đi tới Kc mới), rồi suy ra chiều phản ứng.
* Hệ: CO(g) + 2H₂(g) ⇌ CH₃OH(g), chiều thuận tỏa nhiệt, xúc tác Cu/ZnO. Kc = [CH₃OH]/([CO][H₂]²).
* Trạng thái gốc (cân bằng ở 250 °C, bình V lít): [CO] = 0,50 M; [H₂] = 1,0 M; [CH₃OH] = 0,25 M; Kc(250 °C) = 0,50.
* Biến độc lập (mỗi thao tác làm riêng, đều xuất phát từ trạng thái gốc):
  1. Bơm thêm CO đến [CO] = 1,00 M, giữ thể tích và nhiệt độ.
  2. Rút bớt CH₃OH còn 0,125 M, giữ thể tích và nhiệt độ.
  3. Nén giảm thể tích còn một nửa, giữ nhiệt độ (ngay sau nén: 1,00 / 2,0 / 0,50 M).
  4. Nâng nhiệt độ lên 300 °C, giữ thể tích; Kc(300 °C) = 0,20.
  5. Thay lớp xúc tác cũ bằng lớp xúc tác mới hoạt tính cao hơn, giữ thể tích và nhiệt độ.
* Biến phụ thuộc: Q ngay sau thao tác, Kc sau thao tác, chiều phản ứng, lượng CH₃OH khi cân bằng mới, thời gian đạt cân bằng.
* Biến kiểm soát: mỗi lần chỉ đổi một yếu tố; các thao tác không nối tiếp nhau.
* Dữ liệu dự kiến: Bảng 1 nhật ký 5 thao tác (nồng độ ngay sau thao tác, nhiệt độ, Kc tại nhiệt độ đó). Bảng 2 Kc theo nhiệt độ: 250 °C – 0,50; 300 °C – 0,20.
* Lỗi nhầm lẫn điển hình:
  L1. Tưởng thêm chất hoặc nén làm Kc thay đổi.
  L2. Tưởng nâng nhiệt độ thì phản ứng chạy chiều thuận (không xét dấu ΔH).
  L3. Tưởng sau khi hệ "bù lại", nồng độ chất vừa thêm trở về đúng giá trị cũ.
  L4. Tưởng xúc tác mới làm tăng lượng CH₃OH lúc cân bằng.
  L5. Nhầm chiều so sánh: Q < Kc lại cho là chạy nghịch.
* Câu hỏi TSA gợi ý:
  * "Thao tác nào làm thay đổi Kc?"
  * "Ngay sau khi nén, Q bằng bao nhiêu lần Kc?"
  * "Ghép mỗi thao tác với kết quả đúng."
```

## PROMPT GEMINI (D3)

```
Bạn là người ra đề TSA (Đánh giá Tư duy, ĐHBK Hà Nội), phần Tư duy Khoa học / Giải quyết vấn đề. Đối tượng: học sinh lớp 11 vừa học xong nguyên lí chuyển dịch cân bằng, được dạy theo cách so sánh Q (tỉ số tính bằng công thức Kc tại thời điểm bất kỳ) với Kc: tác động làm lệch Q thì hệ quay về Kc cũ; chỉ nhiệt độ làm dời Kc.

IDEA (dùng đúng mọi số liệu, không đổi số):
5. Nhật ký lò tổng hợp methanol
Chủ đề: Tác động lên Q và lên Kc trong tổng hợp methanol (Hóa học)
Loại: A (bảng thao tác – kết quả) · Tier: M2

* Mục tiêu: HS phân biệt tác động làm lệch Q (hệ quay về Kc cũ) với tác động làm dời Kc (hệ đi tới Kc mới), rồi suy ra chiều phản ứng.
* Hệ: CO(g) + 2H₂(g) ⇌ CH₃OH(g), chiều thuận tỏa nhiệt, xúc tác Cu/ZnO. Kc = [CH₃OH]/([CO][H₂]²).
* Trạng thái gốc (cân bằng ở 250 °C, bình V lít): [CO] = 0,50 M; [H₂] = 1,0 M; [CH₃OH] = 0,25 M; Kc(250 °C) = 0,50.
* Biến độc lập (mỗi thao tác làm riêng, đều xuất phát từ trạng thái gốc):
  1. Bơm thêm CO đến [CO] = 1,00 M, giữ thể tích và nhiệt độ.
  2. Rút bớt CH₃OH còn 0,125 M, giữ thể tích và nhiệt độ.
  3. Nén giảm thể tích còn một nửa, giữ nhiệt độ (ngay sau nén: 1,00 / 2,0 / 0,50 M).
  4. Nâng nhiệt độ lên 300 °C, giữ thể tích; Kc(300 °C) = 0,20.
  5. Thay lớp xúc tác cũ bằng lớp xúc tác mới hoạt tính cao hơn, giữ thể tích và nhiệt độ.
* Biến phụ thuộc: Q ngay sau thao tác, Kc sau thao tác, chiều phản ứng, lượng CH₃OH khi cân bằng mới, thời gian đạt cân bằng.
* Biến kiểm soát: mỗi lần chỉ đổi một yếu tố; các thao tác không nối tiếp nhau.
* Dữ liệu dự kiến: Bảng 1 nhật ký 5 thao tác (nồng độ ngay sau thao tác, nhiệt độ, Kc tại nhiệt độ đó). Bảng 2 Kc theo nhiệt độ: 250 °C – 0,50; 300 °C – 0,20.
* Lỗi nhầm lẫn điển hình:
  L1. Tưởng thêm chất hoặc nén làm Kc thay đổi.
  L2. Tưởng nâng nhiệt độ thì phản ứng chạy chiều thuận (không xét dấu ΔH).
  L3. Tưởng sau khi hệ "bù lại", nồng độ chất vừa thêm trở về đúng giá trị cũ.
  L4. Tưởng xúc tác mới làm tăng lượng CH₃OH lúc cân bằng.
  L5. Nhầm chiều so sánh: Q < Kc lại cho là chạy nghịch.
* Câu hỏi TSA gợi ý:
  * "Thao tác nào làm thay đổi Kc?"
  * "Ngay sau khi nén, Q bằng bao nhiêu lần Kc?"
  * "Ghép mỗi thao tác với kết quả đúng."

NHIỆM VỤ 1: VIẾT NGỮ LIỆU
- Độ dài 300–400 từ, chia đoạn [1], [2], [3]: giới thiệu methanol và phản ứng tổng hợp; giới thiệu Kc, Q và quy tắc so sánh Q với Kc (Q < Kc chạy thuận, Q > Kc chạy nghịch, Q = Kc cân bằng); mô tả trạng thái gốc và cách ghi nhật ký.
- Bảng 1 "Nhật ký 5 thao tác": cột Thao tác | Nhiệt độ | [CO] ngay sau thao tác | [H₂] ngay sau thao tác | [CH₃OH] ngay sau thao tác. Bảng 2 "Kc theo nhiệt độ" (250 °C: 0,50; 300 °C: 0,20). Caption "Bảng N: ..." đặt TRÊN bảng.
- Chỉ ghi số liệu "ngay sau thao tác", KHÔNG ghi nồng độ ở cân bằng mới (để câu hỏi khai thác).
- Dòng cuối ngữ liệu: "Nguồn: P20 STUDY sưu tầm và tổng hợp".
- Không nhắc tới vòng tuần hoàn khí hay tách sản phẩm liên tục trong dây chuyền (đã dành cho đề khác).

NHIỆM VỤ 2: VIẾT ĐÚNG 15 CÂU HỎI theo ma trận sau, tier độ khó đề M2. Tính toán chỉ ở mức thay số vào Q, so sánh với Kc, nhân chia lũy thừa của 2. Câu mức 3–4 dùng thao tác mới không có trong bảng (ví dụ vừa thêm H₂ vừa hạ nhiệt độ, hoặc giãn thể tích gấp đôi).
| Dạng | Mức 1 | Mức 2 | Mức 3–4 | Tổng |
|------|-------|-------|---------|------|
| Trắc nghiệm 4 lựa chọn | 1 | 2 | 1 | 4 |
| Đúng–Sai | 1 | 1 | 1 | 3 |
| Điền khuyết | 0 | 2 | 1 | 3 |
| Ghép đôi | 1 | 0 | 2 | 3 |
| Kéo thả | 0 | 0 | 2 | 2 |
| TỔNG | 3 | 4 | 8 | 15 |

LỖI NHẦM LẪN ĐIỂN HÌNH (dùng làm nguyên liệu cho phương án nhiễu):
L1. Tưởng thêm chất hoặc nén làm Kc thay đổi.
L2. Tưởng nâng nhiệt độ thì phản ứng chạy chiều thuận (không xét dấu ΔH).
L3. Tưởng sau khi hệ "bù lại", nồng độ chất vừa thêm trở về đúng giá trị cũ.
L4. Tưởng xúc tác mới làm tăng lượng CH₃OH lúc cân bằng.
L5. Nhầm chiều so sánh: Q < Kc lại cho là chạy nghịch.

RÀNG BUỘC:
1. Mọi số liệu, năm, tên người, phương trình dùng trong ngữ liệu và câu hỏi phải lấy từ IDEA ở trên. Không bịa thêm năm, sự kiện, hằng số. Câu cần công thức không hiển nhiên thì ghi công thức ngay trong đề câu.
2. Các câu độc lập: đáp án hoặc kết quả tính của câu này không được xuất hiện trong đề câu khác.
3. Phương án nhiễu xây từ lỗi L1–L5; mỗi nhiễu phải đúng theo một cách đọc lệch ngữ liệu, không nhiễu ngớ ngẩn.
4. Câu mức 3–4 không trả lời được bằng cách tìm chữ trong bài: phải có tính toán, so sánh điều kiện, suy ngược hoặc áp nguyên lý vào tình huống mới không có trong ngữ liệu.
5. MCQ: 4 phương án dài xấp xỉ nhau, đáp án đúng không phải phương án dài nhất; phương án sai không dùng từ tuyệt đối (hoàn toàn, luôn luôn, không bao giờ).
6. Đúng–Sai: 4 mệnh đề, 2 Đúng 2 Sai, thứ tự Đ/S không lặp giữa các câu Đúng–Sai. Ghép đôi: 4–6 cặp, mỗi ý Cột B dùng đúng 1 lần, không ghi "có ý thừa". Kéo thả: kho có ít nhất 2 từ nhiễu cùng chủ đề. Điền khuyết: ghi rõ đơn vị và quy tắc làm tròn bằng chữ, mỗi ô 1 đáp án.
7. Câu dẫn chuẩn: Đúng–Sai "Các nhận định sau đúng hay sai?"; Điền "Điền từ/cụm từ (không quá 2 tiếng) hoặc số (làm tròn đến ...) vào chỗ trống:"; Ghép đôi "Ghép mỗi ý ở Cột A với một ý ở Cột B."; Kéo thả "Kéo các cụm từ trong kho vào chỗ trống cho phù hợp:".
8. Văn phong khoa học, khách quan. Không dùng dấu gạch ngang dài (—), không dùng mũi tên (→) thay từ nối trong câu chữ (được dùng trong phương trình hóa học). Không mở câu bằng "Đây là", "Tuy nhiên", "Vì vậy", "Như vậy".

FORMAT MỖI CÂU (bắt buộc, không bỏ dòng nào):
Câu [N]. [Dạng câu] | Độ khó [x,x]/5 | Mức tư duy [1/2/3/4] | [Kỹ năng nâng cao nếu mức ≥3] | [Lỗi khai thác: L?]
[Nội dung câu hỏi + phương án]
▸ Đáp án: [...]
▸ Giải thích: [căn cứ ở đoạn/bảng nào; MCQ giải thích cả 3 nhiễu sai vì sao; Đúng–Sai giải thích từng mệnh đề; Kéo thả không cần giải thích]

Dạng câu chỉ dùng 1 trong: Trắc nghiệm 4 lựa chọn / Đúng–Sai / Điền khuyết / Ghép đôi / Kéo thả.
Kỹ năng nâng cao chỉ dùng 1 trong: Mô hình hóa & Tỷ lệ / Bài toán ngược & Điều kiện biên / Chẩn đoán & Khắc phục / Giả định tình huống / Tối ưu hóa đa mục tiêu / Phân tích dữ liệu chéo.

CUỐI CÙNG: bảng tổng hợp | Câu | Dạng | Độ khó | Mức | Kỹ năng | Lỗi L | Đáp án | và 1 dòng tự đếm số câu theo từng dạng, từng mức để đối chiếu ma trận.
```

## GỢI Ý HÌNH ẢNH

| Hình | Đặt ở | Caption | Từ khóa tìm ảnh |
|---|---|---|---|
| Hình 1 | Sau đoạn [1] (giới thiệu phản ứng) | Hình 1: Viên xúc tác Cu/ZnO dùng trong tháp tổng hợp methanol. | `Cu/ZnO/Al2O3 methanol catalyst pellets`, `methanol synthesis catalyst` |
| Hình 2 (tùy chọn) | Sau đoạn [1] | Hình 2: Sơ đồ tháp tổng hợp methanol. | `methanol synthesis reactor diagram`, `fixed bed methanol reactor schematic` |

Lưu ý: sơ đồ dây chuyền methanol thường vẽ cả vòng khí tuần hoàn, trùng góc với Đề 2 (NH₃). Nếu dùng Hình 2, chọn sơ đồ chỉ có tháp phản ứng, hoặc cắt bỏ phần vòng tuần hoàn.

Nhãn tiếng Anh hay gặp và cách dịch (đưa vào lệnh Gemini khi Việt hóa ảnh):
- Syngas (CO + H2) → Khí tổng hợp (CO + H₂)
- Reactor → Tháp phản ứng
- Catalyst bed → Lớp xúc tác
- Cooling water in / out → Nước làm mát vào / ra
- Crude methanol → Methanol thô

Nguồn ghi dưới mỗi hình: một nguồn duy nhất (trang gốc của ảnh; ảnh Việt hóa ghi thêm "(Việt hóa)").
