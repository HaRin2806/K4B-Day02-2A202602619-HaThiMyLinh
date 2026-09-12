# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Hà Thị Mỹ Linh
- Mã học viên: 2A202602619
- Nhóm: Nhóm gồm 6 thành viên — Nguyễn Viết Đức, Nguyễn Hoàng Anh, Dương Văn Thành, Hà Thị Mỹ Linh, Vũ Đức Thiện, Tống Trần Tiến Dũng
- Candidate problem nhóm chọn: #6 — Kiểm thử invoice phải đối chiếu ảnh JPG với JSON output, kiểm tra từng trường thông tin có khớp hay không

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tự scan 7 problems từ workflow Data Analyst của mình (Sapo, Google Sheets, research, insight, viết report), mỗi dòng ghi actor + số đo (VD: 5 lần/tuần, 30 phút/lần; 10 chỉ số đối chiếu, 5 giờ/tuần). | Có nguồn candidate #10, #11, #12 để đưa vào bàn tròn nhóm ở Phase 3. |
| Pitch Problem Card | Pitch Card #1 "Phân tích dữ liệu và viết insight cho Weekly Report" trong 2 phút, nêu rõ 120 phút/tuần, bottleneck ở bước research → insight → viết narrative. | Nhóm hiểu rõ pain của vai trò Data Analyst, dùng làm đối trọng so sánh với candidate #6 ở bước score. |
| Challenge bài của bạn khác | Đặt câu hỏi về cách đo "insight tốt" và độ chắc chắn của các số liệu ước lượng (baseline) cho candidate #16 của Dũng, vì việc phân loại Requirement/Action/Question phụ thuộc nhiều vào context cuộc họp. | Giúp nhóm nhận ra #16 khó kiểm tra đúng/sai hơn #6, góp phần vào quyết định không chọn #16. |
| Gom trùng / cluster | Đề xuất gom #10, #11 vào Cluster B (tổng hợp – viết lại – cấu trúc hóa thông tin) cùng với candidate của Thành và Dũng vì cùng pattern "biến dữ liệu/notes thô thành output có cấu trúc". | Cluster B rõ ràng hơn, giúp nhóm so sánh công bằng giữa các candidate cùng dạng. |
| Chọn candidate problem | Tham gia chấm điểm ở bảng Score (Phase 3.4), tự chấm candidate #10 của mình một cách khách quan (Impact đo được: 5, nhưng Làm trong lab: 4 vì scope rộng), không cố "vote hộ" bài mình. | Bảng điểm phản ánh đúng thực tế; nhóm hội tụ về #6 vì input/output rõ hơn cho lab. |
| Validation / research | Phụ trách phần Research giải pháp đã có (Phase 4.2): tìm và tổng hợp 3 nguồn — Amazon Textract AnalyzeExpense, Google Document AI Invoice Parser, Azure AI Document Intelligence — kèm link kiểm được và rút ra bài học "không tự build OCR từ đầu". | Giúp nhóm xác định đúng scope: chỉ làm workflow so sánh, không build lại OCR, tránh mất thời gian vào phần đã có giải pháp sẵn. |
| Workflow nhóm | Góp ý ước lượng thời gian cho từng bước trong bảng workflow trước/sau (Phase 5.1, 5.2) dựa trên kinh nghiệm ước lượng thời gian ở bài cá nhân của mình. | Bảng before/after impact có số đo hợp lý hơn thay vì chỉ áng chừng. |
| Problem Statement | Góp ý viết field "Success Metric" trong Problem Statement v0/v1, đề xuất đo bằng cả thời gian (25-40 phút → 8-15 phút/batch) và số mismatch bị bỏ sót, không chỉ đo tốc độ. | Success Metric của nhóm có cả góc độ tốc độ lẫn chất lượng, không chỉ nói "nhanh hơn". |
| Rule / Workflow / Agent | Góp ý trả lời câu hỏi "Rule có giải được 70-80% case không?" — chỉ ra rule chỉ đủ cho bước compare, không đủ cho bước đọc ảnh, dựa trên kinh nghiệm bài #12 của mình (đối chiếu Sapo/Sheets). | Củng cố lý do nhóm chọn mức Workflow thay vì chỉ Rule. |
| Decision | Đề xuất 3 số cần đo trong pilot nhỏ nhất (tổng thời gian/batch, số mismatch phát hiện, số mismatch bị bỏ sót) để quyết định Go/Not Yet rõ ràng hơn. | Phần pilot của nhóm có metric cụ thể thay vì chỉ nói "thử rồi xem". |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần Research giải pháp đã có (4.2) với 3 nguồn OCR/invoice có link kiểm được, và phần Success Metric trong Problem Statement — cả hai đều xuất phát từ thói quen "phải có số đo, không được nói chung chung" mà tôi rèn khi tự scan bài cá nhân của mình.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hỏi AI brainstorm 10 problems có thể xảy ra trong workflow Data Analyst của mình, yêu cầu chỉ rõ actor, bước workflow, dấu hiệu đo được và khả năng dùng AI. | AI giúp tách problem theo từng bước (collection → checking → analysis → research → insight → writing) và nhắc tôi để ý cả pain của Manager/CEO, không chỉ của tôi. | AI đề xuất vài ý kiểu "AI có thể tự động hóa toàn bộ công việc Data Analyst" hoặc "AI viết thay toàn bộ report" — quá rộng và không có actor/workflow cụ thể. | Tôi bỏ các ý không có actor/cách đo cụ thể, giữ lại 7 dòng đều có số đo thật (phút/tuần, số lần/tuần) dựa trên công việc thật của tôi. |
| Problem Card | Không dùng AI để viết Card — tôi tự điền workflow, bottleneck, success metric dựa trên số phút tôi tự ước lượng cho từng bước. | — | — | Tôi muốn số liệu trong Card phản ánh đúng công việc thật của mình, không muốn AI đoán hộ thời gian tôi chưa từng bấm giờ. |
| Workflow | Dùng AI để kiểm tra logic mũi tên trong sơ đồ mermaid (current/future) và gợi ý cách trình bày fallback cho Card #1, #2. | AI giúp diễn đạt fallback rõ ràng hơn ("nếu AI đưa insight không có evidence → Linh bỏ suggestion và tự phân tích lại"). | AI ban đầu vẽ future workflow không có bước "Linh review + edit", coi như AI tự động approve luôn. | Tôi thêm lại bước review/approve của con người vào future workflow trước khi chốt Card. |
| Research | Dùng AI để tìm nhanh tên các tool OCR/invoice extraction phổ biến (Textract, Document AI, Document Intelligence) trước khi tự tra link chính thức. | AI hữu ích ở việc gợi ý đúng hướng tìm kiếm, tiết kiệm thời gian so với tự search từ đầu. | AI đưa vài mô tả tính năng khá chung chung, không chắc đúng version/API hiện tại. | Tôi tự mở link chính thức của AWS/Google/Azure để xác nhận lại nội dung trước khi đưa vào bảng Research, không copy nguyên mô tả AI đưa ra. |
| Problem Statement | Dùng AI để phản biện Problem Statement v0 của nhóm (câu hỏi "field nào mơ hồ"). | AI chỉ đúng điểm yếu: "batch invoice" chưa định nghĩa rõ số lượng/field, khiến metric 25-40 phút/batch chưa công bằng. | AI chỉ dừng ở việc chỉ ra vấn đề, không tự đề xuất được cách đo cụ thể nào khả thi trong thời gian lab ngắn. | Tôi đề xuất pilot cố định 3-5 invoice/20-30 field để so sánh trước/sau công bằng hơn, thay vì để "batch" mơ hồ. |
| Rule / Workflow / Agent | Dùng AI để liệt kê ưu/nhược điểm nhanh của 3 mức Rule/Workflow/Agent áp cho bài invoice. | AI tổng hợp nhanh rủi ro của từng mức, giúp nhóm thảo luận nhanh hơn thay vì tự liệt kê từ đầu. | AI có xu hướng nghiêng về đề xuất Agent vì nghe "đầy đủ tính năng" hơn, dù workflow không cần agent tự lập kế hoạch. | Tôi cùng nhóm chốt Workflow vì các bước đi thẳng một đường, không cần AI tự quyết định bước tiếp theo — không chạy theo đề xuất "cho ngầu" của AI. |
| Decision | Không dùng AI ở bước chốt Decision — nhóm tự thảo luận dựa trên bảng 6 câu hỏi và bằng chứng đã có. | — | — | Quyết định Go/Not Yet cần sự đồng thuận thật của nhóm, không nên để AI gợi ý thay cho phần này. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Khi nghe top 3 của các bạn khác, tôi nhận ra bài của Thành (#6 — đối chiếu ảnh JPG invoice với JSON output) có input/output rõ hơn hẳn bài của tôi, dù cả hai đều đo được thời gian và đều là công việc lặp lại mỗi tuần/mỗi batch. Bài của tôi (#10 — Weekly Report) gom cả data collection, research và viết narrative vào một problem, nên khi nhóm hỏi "đo insight tốt bằng gì", tôi không trả lời được ngay, trong khi câu hỏi tương tự cho #6 lại rất dễ trả lời: mismatch khớp hay không khớp, đúng hoặc sai rõ ràng. Đó là lúc tôi thật sự bị challenge và phải thừa nhận scope của mình quá rộng cho một bài lab ngắn. Ban đầu tôi hơitiếc vì impact của #10 lên Manager/CEO nghe "quan trọng" hơn, nhưng sau khi nhóm chỉ ra rằng #6 dễ prototype, dễ đo bằng field/mismatch cụ thể và không phụ thuộc vào cảm nhận chủ quan như "insight tốt", tôi đồng ý đổi ý và ủng hộ chọn #6. Cái tôi học được là một problem nghe "impact lớn" chưa chắc đã là problem tốt để làm trong lab, nếu ranh giới đúng/sai của nó không rõ. Phần tôi đóng góp thật vào artifact cuối là mảng research (tìm 3 tool OCR có link kiểm được) và mảng metric — cả hai đều là thế mạnh tôi mang từ vai trò Data Analyst sang bài của nhóm, dù candidate gốc của tôi không được chọn. Điều khó nhất khi viết Problem Statement không phải là metric mà là boundary: xác định chính xác AI được làm gì và không được làm gì (không tự approve JSON, không tự sửa data gốc) mất nhiều thời gian tranh luận hơn tôi tưởng. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ngay từ vòng score, hỏi kỹ hơn về cách đo "mismatch bị bỏ sót" trước khi chốt candidate, thay vì chỉ đồng ý sau khi nghe lý lẽ của người khác.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ x] [15đ] Nhóm có workflow trước/sau
- [ x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

