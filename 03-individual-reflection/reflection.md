# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Hoàng Đức Dũng
- Mã học viên: 2A202602798
- Nhóm: Fintecth-Zone C. Vai trò của tôi: rủi ro và ranh giới AI, góc nhìn vận hành hệ AI đang chạy.
- Candidate problem nhóm chọn: Nhà đầu tư cổ phiếu cá nhân dễ bỏ lỡ thời điểm phản ứng với một tin tức hoặc sự kiện doanh nghiệp, vì tin mới nằm rải rác ở nhiều nguồn và phải tự đánh giá theo từng mã đang nắm.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems từ công việc vận hành một hệ AI đang chạy: che dữ liệu nhạy cảm, chốt ngưỡng, bug không tái hiện, triage ticket, regression khi sửa prompt, chi phí token và các bài khác | Cụm A "vận hành và an toàn một hệ AI đang chạy" trong bảng cluster của nhóm được hình thành chủ yếu từ các bài của tôi và của Đình Anh |
| Pitch Problem Card | Pitch card #4 che thông tin nhạy cảm trước khi đưa vào prompt và log, nhấn vào chỗ hai metric che sót và che thừa kéo ngược nhau nên không lách được | Nhóm ghi nhận đây là bài hay nhất về mặt metric trong cụm A, nhưng loại vì chỉ 2/5 thành viên đủ nền để phản biện |
| Challenge bài của bạn khác | Hỏi nhóm bài nào buộc phải tranh luận về ranh giới AI được làm gì và người phải kiểm cái gì, khi #8 và #1 hoà điểm 31/35 | Đây là câu hỏi phá thế hoà. Nhóm chốt chọn #8 vì ở #1 ranh giới là hiển nhiên, còn ở #8 có tiền thật nên ranh giới phải được thiết kế |
| Gom trùng / cluster | Đề xuất tách cụm A theo tiêu chí đã có hệ AI chạy trong sản xuất, thay vì gom chung mọi bài có chữ AI | Bốn cụm A, B, C, D tách được rõ ràng, nhờ đó thấy ngay điểm yếu của cụm A là cả nhóm không cùng hiểu domain |
| Chọn candidate problem | Chủ động rút cả ba card của mình khỏi vòng chọn cuối, dù evidence chắc hơn bài #8, vì 3/5 thành viên không challenge được | Tránh cho bản nộp trở thành ý kiến của thiểu số được đóng dấu tập thể |
| Validation / research | Không phải phần việc chính của tôi. Tôi chỉ đề xuất thêm hai câu vào bộ câu hỏi: câu 5 phỏng vấn và câu 8 survey về việc nhà đầu tư có mở nguồn gốc trước khi hành động không | Hai câu này trở thành điều kiện bắt buộc số 3 để tầng AI được chuyển sang Go. Nếu đa số trả lời hiếm khi thì nhóm bỏ hẳn phần AI sinh văn bản |
| Workflow nhóm | Nhật dựng khung workflow trước và sau. Tôi bổ sung phần boundary sau bước 3, phần fallback khi nguồn thiếu hoặc mâu thuẫn, và thêm hàng Risk mới vào bảng before/after | Bảng before/after có thêm hàng rủi ro tóm tắt sai nhưng người dùng tin luôn, là hàng duy nhất nói về cái giá phải trả chứ không phải cái lợi thu được |
| Problem Statement | Viết phần Boundary theo dạng làm gì và không làm gì, và viết ô Rủi ro kèm người thật kiểm tra ở v1 | Boundary v1 liệt kê rõ không khuyến nghị mua bán, không dự báo giá, không đặt lệnh, không nêu con số tài chính mà nguồn không nói |
| Rule / Workflow / Agent | Phản đối việc đi theo gợi ý của ma trận. Tách khái niệm mơ hồ trong phán đoán nội dung của một bước ra khỏi mơ hồ trong lộ trình các bước | Nhóm giữ được mức Workflow dù ô ma trận là mơ hồ cao và phức tạp cao. Lập luận này thành phần Vì sao ở mục 6.0 của bản nộp |
| Decision | Chỉ ra hai kiểu sai không đối xứng: báo thừa thì người dùng thấy ngay, bỏ sót thì không ai phát hiện được. Đề xuất giữ chế độ xem toàn bộ feed chưa lọc và đối chiếu 20 tin bị hạ hạng mỗi tuần | Quyết định cuối tách đôi theo tầng: Rule Go ngay, AI Not Yet. Ba điều kiện rollback trong bản nộp đều xuất phát từ kiểu sai thứ hai |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Hàng "Risk mới" trong bảng before/after và ô "Rủi ro & người thật kiểm tra" ở Problem Statement v1
là phần tôi viết, trong đó có nhận định rằng rủi ro lớn nhất không phải tóm tắt sai
mà là bỏ sót một tin quan trọng, vì người dùng không thể phát hiện thứ mình không nhận được.
Cơ chế giữ feed chưa lọc để đối chiếu ngẫu nhiên mỗi tuần là cách tôi đề xuất để bắt được kiểu sai đó.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ AI gợi ý thêm điểm đau theo góc người vận hành hệ AI, soi theo bốn lăng kính | Giúp tôi tách bug không tái hiện được thành bài riêng thay vì gộp vào triage ticket chung | Đề xuất thêm thiếu chuẩn MLOps và chưa có văn hoá đo lường, cả hai đều không có actor chịu đau rõ và không đo được | Bỏ cả hai ý đó. Giữ nguyên tiêu chí mỗi dòng phải có người chịu và có số đếm được |
| Problem Card | Nhờ AI phản biện metric của card che dữ liệu nhạy cảm | Chỉ ra metric chỉ đo tỉ lệ che sót là metric một chiều, đạt được quá dễ bằng cách che mạnh tay hơn | Không tự phát hiện nghịch lý là muốn nhờ model tìm dữ liệu nhạy cảm thì phải đưa chính dữ liệu đó cho model, tôi phải hỏi thẳng nó mới thừa nhận | Thêm metric thứ hai là tỉ lệ che thừa để hai chỉ số kéo ngược nhau. Đưa ràng buộc chỉ dùng model nội bộ lên thành ranh giới cứng |
| Workflow | Không dùng | — | — | Khung workflow do Nhật dựng trong buổi làm chung. Phần tôi thêm là boundary và fallback, đều là nhận định về rủi ro nên tôi tự viết |
| Research | Không dùng | — | — | Đây là phần việc của Khánh. Tôi chỉ đọc lại bảng và đối chiếu xem khoảng trống nào thật sự cần model |
| Problem Statement | Nhờ AI soi các field còn mơ hồ ở v0 | Chỉ ra Impact chưa gắn với con số nào, và Success Metric đang đo tốc độ cung cấp thông tin trong khi vấn đề nhóm nêu là chất lượng thời điểm ra quyết định | Đề xuất gộp luôn chất lượng quyết định đầu tư vào metric cam kết, trong khi thứ đó không thể đo trong phạm vi lab | Tách metric chính mà nhóm cam kết khỏi metric kết quả mà nhóm không cam kết, và ghi thẳng phần không cam kết vào bản nộp |
| Rule / Workflow / Agent | Hỏi AI xem bài toán nằm ở ô nào trên ma trận độ mơ hồ và độ phức tạp | Xác nhận cả hai chiều đều ở mức cao, giúp nhóm không tự hạ thấp độ khó của bài | Từ ô đó AI kết luận ngay là nên làm Agent. Đây là chỗ AI hời hợt nhất trong cả buổi, vì nó đọc bảng chứ không đọc bài toán | Tách mơ hồ trong phán đoán nội dung của một bước ra khỏi mơ hồ trong lộ trình các bước. Lộ trình bài này cố định nên giữ mức Workflow |
| Decision | Không dùng | — | — | Quyết định tách đôi theo tầng là kết quả tranh luận trong nhóm. Riêng ba điều kiện rollback tôi tự đặt dựa trên kiểu sai không đối xứng |

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
Bốn câu tôi chọn: solution-first, đổi ý sau khi bị challenge, điều khó nhất khi viết
Problem Statement, và nếu làm lại sẽ challenge mạnh hơn ở đâu.

Lần nhóm suýt đi sai nhất không đến từ việc ai đó muốn làm Agent cho ngầu, mà đến từ
một cái bảng. Khi xếp bài tin tức vào ô mơ hồ cao và phức tạp cao, ma trận gợi ý mức
Agent, và trong một lúc cả nhóm gật theo vì bảng nói vậy. Tôi thấy gợn nên hỏi lại là
cái mơ hồ ở đây nằm ở đâu, và khi tách ra thì rõ rằng nó nằm trong phán đoán nội dung
của đúng một bước là tin này quan trọng đến đâu, còn trình tự các bước thì cố định và
biết trước. Điều làm tôi nhớ lâu là solution-first lần này đội lốt một công cụ phân
loại, nên nó khó nhận ra hơn nhiều so với việc ai đó nói thẳng là muốn làm agent.

Tôi cũng phải đổi ý về chính ba card của mình. Cả ba đều là bài vận hành hệ AI và có
evidence chắc hơn hẳn bài được chọn, nhưng chỉ hai trên năm người trong nhóm đủ nền để
phản biện, nên nếu tôi cố đẩy thì bản nộp sẽ là ý kiến của thiểu số được đóng dấu tập
thể. Riêng card chốt ngưỡng thì chính tôi phải thừa nhận một bảng tính quy đổi đã gần
như đủ, và tự khai điều đó hoá ra dễ hơn tôi tưởng khi đã quen nhìn theo hướng chọn mức
thấp nhất đủ dùng.

Phần khó nhất khi viết Problem Statement với tôi là boundary chứ không phải metric.
Metric chỉ cần chịu khó tách ra là xong, phần nhóm cam kết đo được trong một tuần và
phần nhóm không cam kết. Boundary khó vì phải tìm cho ra kiểu sai mà không ai phát hiện
được: báo thừa một tin thì người dùng thấy ngay và mất vài giây, còn chôn mất một tin
quan trọng thì họ không biết cái mình không nhận, nên lỗi đó im lặng và tích luỹ.

Nếu làm lại, tôi sẽ challenge mạnh hơn ở đúng một chỗ là validation. Nhóm tự chấm
evidence chỉ ba trên năm ngay từ Phase 3, tức là đã biết rõ đó là lỗ hổng lớn nhất,
vậy mà vẫn viết trọn cả Problem Statement v0 và v1 trước khi đi hỏi một nhà đầu tư thật
nào. Con số dưới mười phút đến giờ vẫn là mục tiêu chép lại từ card gốc chứ chưa phải
kết quả bấm giờ, và lẽ ra tôi nên ép nhóm dừng lại ngay tại chỗ đó thay vì để nó trôi
qua thêm ba phase nữa.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
