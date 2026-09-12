# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân
    
- Họ và tên: Hoàng Đức Dũng
- Mã học viên: 2A202602798
- Vai trò / bối cảnh: AI Engineer, làm tính năng hỏi đáp dựa trên tài liệu nội bộ cho sản phẩm đã có người dùng thật
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
+ Xử lý dữ liệu đầu vào và che thông tin nhạy cảm trước khi đưa vào prompt và ghi log
+ Sửa, thử nghiệm và triển khai prompt cho tính năng đang chạy production
+ Trực ticket chất lượng do QA và người dùng báo về câu trả lời sai
+ Chạy eval, so sánh phiên bản, báo cáo kết quả cho team lead
+ Làm việc với bên vận hành để chốt ngưỡng và tiêu chí chấp nhận trước khi lên production

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Pain từ người khác | Che thông tin nhạy cảm trước khi đưa vào prompt và log; luật cứng chỉ bắt được dạng có khuôn, dạng theo ngữ cảnh vẫn lọt | AI engineer, pháp chế, khách hàng | Rà mẫu 100 bản ghi mất 60 phút, 2-3 vòng rà mỗi tháng; lần rà gần nhất còn khoảng 8% bản ghi che sót |
| 2 | Pain từ người khác | Chốt ngưỡng cho model phân loại với bên vận hành, hai bên nói hai ngôn ngữ khác nhau | AI engineer, trưởng nhóm vận hành, người phụ trách rủi ro | Trung bình 3 vòng họp mỗi lần chốt, khoảng 5 tiếng của tôi cộng thời gian của 3 người khác |
| 3 | AI có thể tốt hơn | Bug do QA báo không tái hiện được, chạy lại thì model trả lời đúng | AI engineer trực ticket, QA | 4-6 ca mỗi tuần, khoảng 40 phút mỗi ca; khoảng 1/5 ticket đóng dạng không tái hiện sau đó quay lại |
| 4 | Pain từ người khác | Triage ticket người dùng báo trả lời sai, phải lần lại log hội thoại để tìm nguyên nhân gốc | AI engineer, QA, support | 12-15 ticket mỗi tuần, 25-35 phút mỗi ticket để đọc log và kết luận |
| 5 | Lặp lại | Sửa prompt đang chạy production nhưng không biết có làm hỏng nhóm case vốn chạy tốt không | AI engineer, người dùng cuối | 3-4 lần sửa prompt mỗi tuần, mỗi lần chạy tay 15-20 case mất 30 phút; 2 lần regression lọt ra production trong quý gần nhất |
| 6 | Lặp lại | Giải thích cho PM và sales tại sao model lại trả lời như vậy trong một ca cụ thể | AI engineer, PM, sales | 3-5 lần hỏi mỗi tuần, 20-30 phút mỗi lần để mở trace và viết lại bằng ngôn ngữ thường |
| 7 | Tốn thời gian | Chạy lại thí nghiệm mà người khác trong team đã chạy từ vài tháng trước nhưng không ai ghi kết quả lại | AI engineer, người duyệt chi phí | 2-3 lần chạy trùng mỗi quý, mỗi lần tốn 1-2 ngày công cộng chi phí gọi API |
| 8 | AI có thể tốt hơn | Phát hiện chất lượng tụt dần theo thời gian, khó phân biệt tụt thật với dao động ngẫu nhiên | AI engineer, người dùng cuối | Lần tụt gần nhất mất 9 ngày mới phát hiện, do người dùng báo chứ không do hệ thống cảnh báo |
| 9 | Tốn thời gian | Đưa một nguồn tài liệu mới vào pipeline, nguồn nào cũng format và cấu trúc khác nhau | AI engineer, data engineer | 6-10 giờ mỗi nguồn, khoảng 4 nguồn mỗi quý |
| 10 | Tốn thời gian | Cắt chi phí token mà không được để chất lượng tụt | AI engineer, người duyệt ngân sách | Chi phí gọi model tăng khoảng 30% trong 2 tháng; mỗi vòng thử cắt context mất nửa ngày để đo lại |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "Với một AI engineer đang vận hành tính năng hỏi đáp trên tài liệu nội bộ, những điểm đau nào lặp lại hằng tuần và đo được bằng số, xét theo bốn lăng kính lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác?"
- Ý dùng được: Gợi ý tách riêng "bug không tái hiện được" khỏi nhóm triage ticket chung. Đây là dạng đặc thù của hệ thống sinh ngôn ngữ và có cách đo riêng, gộp chung vào triage sẽ làm mờ bottleneck.
- Ý bỏ vì không phải pain thật: AI đề xuất "thiếu chuẩn MLOps" và "chưa có văn hoá đo lường". Hai ý này không có workflow cụ thể, không có actor chịu đau rõ và không đo được bằng số nên tôi bỏ.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Che thông tin nhạy cảm trước khi đưa vào prompt và log (#1) | Hai metric kéo ngược nhau nên không lách được bằng cách siết chặt; luật cứng giải quyết phần lớn nên bắt buộc phải lập luận vì sao AI mới xứng đáng bước vào phần còn lại; hậu quả sai có giá thật là sự cố phải báo cáo | Muốn nhờ model tìm dữ liệu nhạy cảm thì phải cho nó xem chính dữ liệu đó, đây là nghịch lý chưa gỡ được nếu không có model chạy nội bộ |
| 2 | Chốt ngưỡng cho model phân loại với bên vận hành (#2) | Có hai bên mâu thuẫn lợi ích thật chứ không phải mình tôi tự khai; đo được bằng số vòng họp và số ngày trễ; bottleneck nằm gọn ở bước dịch bảng số sang hệ quả vận hành | Rất có thể một bảng tính quy đổi là đủ, nghĩa là bài này có thể không cần AI |
| 3 | Bug do QA báo không tái hiện được (#3) | Đặc thù riêng của hệ thống sinh ngôn ngữ, không trùng với bài toán phần mềm thường; có mặt sai đắt đo được là tỉ lệ ticket đóng nhầm quay lại | Chưa có tiêu chí thống nhất bao nhiêu lần chạy lại và tần suất lỗi bao nhiêu thì chấp nhận được |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Che thông tin nhạy cảm trước khi vào prompt và log

```text
Problem 1 câu:
Trước khi đưa nội dung người dùng vào prompt và ghi vào log, tôi phải che thông tin nhạy cảm,
nhưng luật cứng chỉ bắt được dạng có khuôn như số điện thoại và email,
còn dạng nhạy cảm theo ngữ cảnh thì lọt, nên mỗi vòng rà tôi phải đọc tay mẫu mà vẫn không chắc.

Actor:
AI engineer phụ trách pipeline xử lý đầu vào cho tính năng hỏi đáp,
là người ký chịu trách nhiệm trước mỗi vòng rà soát của pháp chế.

Thời điểm / bối cảnh:
Mỗi lần bổ sung nguồn dữ liệu hoặc mở tính năng cho nhóm người dùng mới,
và mỗi kỳ rà log định kỳ trong tháng.

Current workflow 3-7 bước:
1. Nhận nội dung thô từ người dùng qua API: tự động
2. Chạy bộ luật cứng che số điện thoại, email, số căn cước, số tài khoản: tự động
3. Đọc tay một mẫu ngẫu nhiên 100 bản ghi để tìm phần còn lọt: 60 phút
4. Với mỗi dạng lọt mới, viết thêm luật rồi chạy lại toàn bộ: 45 phút
5. Kiểm tra luật mới có che thừa làm hỏng câu trả lời không: 30 phút
6. Gửi mẫu cho pháp chế duyệt và chờ phản hồi: 1-2 ngày chờ

Bottleneck:
Bước 3. Đọc tay mẫu ngẫu nhiên là cách duy nhất hiện có để phát hiện dạng nhạy cảm theo ngữ cảnh,
ví dụ một câu kể bệnh tình hoặc một mô tả đủ chi tiết để nhận ra đúng một người.
Mẫu 100 bản ghi không đại diện được cho hàng chục nghìn bản ghi mỗi ngày,
nên tôi vừa tốn thời gian vừa không có cơ sở để nói là đã đủ an toàn.

Impact:
Khoảng 135 phút mỗi vòng rà, 2-3 vòng mỗi tháng.
Nặng hơn thời gian là rủi ro: một lần che sót lọt vào log là sự cố phải báo cáo,
và không sửa lại được vì log đã nhân bản sang hệ thống giám sát.

Success metric:
1. Tỉ lệ che sót trên tập kiểm 500 bản ghi đã gán nhãn: từ khoảng 8% xuống dưới 2%.
2. Tỉ lệ che thừa làm hỏng câu trả lời: giữ dưới 3%.
3. Thời gian mỗi vòng rà: từ 135 phút xuống dưới 45 phút.
Hai chỉ số đầu kéo ngược nhau nên không thể lách bằng cách che mạnh tay hơn.

Non-AI alternative:
Mở rộng bộ luật cứng và danh sách từ khoá, siết định dạng đầu vào,
giới hạn danh sách trường được phép ghi vào log.
Cách này rẻ, chạy tức thì, không có rủi ro sinh ngôn ngữ,
và giải quyết được phần lớn các dạng có khuôn. Phải làm trước, không được bỏ qua.

AI hypothesis:
Chỉ dùng model cho phần văn bản tự do mà luật cứng không bắt được.
Model gắn cờ đoạn nghi ngờ kèm lý do, tôi duyệt danh sách gắn cờ rồi mới quyết định che.
Model không tự quyết ghi hay xoá bất kỳ bản ghi nào.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 135 phút mỗi vòng rà, cộng 1-2 ngày chờ duyệt

[1 Nhận dữ liệu thô qua API: tự động]
→ [2 Luật cứng che dạng có khuôn: tự động]
→ [3 Đọc tay mẫu 100 bản ghi tìm phần lọt: 60 phút]  <-- bottleneck
→ [4 Viết thêm luật rồi chạy lại toàn bộ: 45 phút]
→ [5 Kiểm tra che thừa có hỏng câu trả lời không: 30 phút]
→ [6 Gửi pháp chế duyệt: chờ 1-2 ngày]

FUTURE STATE — 40 phút mỗi vòng rà

[1 Nhận dữ liệu thô qua API: tự động]
→ [2 Luật cứng che dạng có khuôn: tự động]           -- Rule, giữ nguyên, chạy trước
→ [3 Model gắn cờ đoạn nghi ngờ theo ngữ cảnh + lý do: tự động]  -- Workflow step
→ [4 Tôi duyệt danh sách gắn cờ, quyết che hay bỏ: 30 phút]      <-- human boundary
→ [5 Đo lại che sót và che thừa trên tập kiểm 500 bản ghi: 10 phút]
→ [6 Gửi pháp chế duyệt: chờ 1-2 ngày]

Fallback: nếu model gắn cờ quá nhiều gây nhiễu, hoặc bỏ sót dạng mà luật cứng vốn bắt được,
tôi tắt phần model và quay về luật cứng cộng đọc tay mẫu.
Luật cứng chạy độc lập nên trong mọi trường hợp không bao giờ tệ hơn hiện trạng.

Ranh giới cứng:
- Model chỉ gắn cờ và giải thích, không tự quyết ghi hay xoá log.
- Không gửi văn bản chưa qua vòng luật cứng ra model của nhà cung cấp bên ngoài.
- Bản ghi đã gắn cờ vẫn phải có người duyệt trước khi đổi trạng thái.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Chốt ngưỡng cho model phân loại với bên vận hành

```text
Problem 1 câu:
Mỗi lần đưa một model phân loại vào chạy thật, tôi và bên vận hành mất trung bình ba vòng họp mới chốt được ngưỡng,
vì tôi trình bày bằng bảng đánh đổi còn họ cần biết mỗi ngày phải xử lý thêm bao nhiêu ca oan và ai làm việc đó.

Actor:
AI engineer làm việc cùng trưởng nhóm vận hành và người phụ trách rủi ro.

Thời điểm / bối cảnh:
Trước mỗi lần đưa model mới hoặc bản cập nhật vào chạy production.

Current workflow 3-7 bước:
1. Chạy model trên tập kiểm, dựng bảng đánh đổi giữa báo nhầm và bỏ sót: 60 phút
2. Chuẩn bị slide giải thích cho người không làm kỹ thuật: 45 phút
3. Họp với vận hành, họ hỏi quy ra mỗi ngày bao nhiêu ca và ai xử lý: 60 phút
4. Về tính lại theo lưu lượng thật và đổi cách trình bày: 60 phút
5. Họp lại để chốt, hoặc lại lệch tiếp một vòng nữa: 60 phút

Bottleneck:
Bước 3 và 4, cụ thể là việc dịch bảng số sang hệ quả vận hành hằng ngày.
Tôi nói bằng tỉ lệ phần trăm, họ cần con số ca mỗi ngày và số người phải bố trí.

Impact:
Trung bình 3 vòng họp mỗi lần chốt ngưỡng, khoảng 5 tiếng của tôi cộng thời gian của 3 người khác.
Model bị chậm đưa vào chạy khoảng 1-2 tuần so với lúc đã sẵn sàng kỹ thuật.

Success metric:
Số vòng họp từ 3 xuống 1.
Thời gian từ khi có kết quả kiểm tới khi chốt ngưỡng từ 2 tuần xuống dưới 3 ngày.

Non-AI alternative:
Dựng sẵn một bảng tính quy đổi từ ngưỡng sang số ca mỗi ngày theo lưu lượng thật,
dùng lại cho mọi lần chốt sau. Thành thật mà nói, cách này gần như đã đủ
và nên làm trước khi nghĩ tới việc đưa AI vào.

AI hypothesis:
Model đọc bảng đánh đổi cộng số liệu lưu lượng, viết bản diễn giải theo ngôn ngữ vận hành,
kèm hai đến ba kịch bản ngưỡng và hệ quả cụ thể của từng kịch bản.
Tôi kiểm lại toàn bộ con số trước khi mang đi họp.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — khoảng 285 phút của tôi, trải qua 3 vòng họp, trễ 1-2 tuần

[1 Chạy tập kiểm, dựng bảng đánh đổi: 60 phút]
→ [2 Chuẩn bị slide: 45 phút]
→ [3 Họp vòng 1, vận hành hỏi quy ra ca mỗi ngày: 60 phút]  <-- bottleneck
→ [4 Về tính lại theo lưu lượng thật: 60 phút]
→ [5 Họp vòng 2 hoặc 3 để chốt: 60 phút]

FUTURE STATE — khoảng 95 phút, 1 vòng họp

[1 Chạy tập kiểm, xuất bảng đánh đổi: 60 phút]
→ [2 Bảng tính quy đổi ngưỡng sang số ca mỗi ngày: tự động]  -- Rule, dùng lại mọi lần
→ [3 Model viết diễn giải theo ngôn ngữ vận hành cho 3 kịch bản: 5 phút]  -- Workflow step
→ [4 Tôi kiểm lại toàn bộ con số trước khi gửi: 30 phút]  <-- human boundary
→ [5 Họp một vòng để chốt]

Fallback: nếu bản diễn giải của model sai lệch so với bảng tính,
tôi bỏ phần diễn giải và mang thẳng bảng quy đổi đi họp.
Bảng quy đổi mới là thứ tạo ra phần lớn giá trị ở đây, không phải model.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Bug do QA báo nhưng không tái hiện được

```text
Problem 1 câu:
Khi QA báo model trả lời sai, tôi chạy lại thì phần lớn lần ra kết quả đúng,
nên mất khoảng 40 phút mỗi ca mà vẫn không có cơ sở để quyết định đóng ticket hay để mở.

Actor:
AI engineer trực ticket chất lượng trong tuần.

Thời điểm / bối cảnh:
Mỗi khi QA hoặc người dùng báo một câu trả lời sai kèm ảnh chụp màn hình.

Current workflow 3-7 bước:
1. Đọc report và dựng lại đúng input ban đầu: 10 phút
2. Chạy lại một lần: 2 phút
3. Kết quả ra đúng, chạy thêm 5-10 lần nữa: 15 phút
4. Vẫn đúng, phân vân giữa đóng ticket và để mở: 10 phút
5. Ghi chú lại rồi đóng dạng không tái hiện: 5 phút

Bottleneck:
Bước 3 và 4. Không có tiêu chí chạy lại bao nhiêu lần là đủ,
và không có ngưỡng tần suất lỗi bao nhiêu thì coi là chấp nhận được.
Vì vậy quyết định cuối cùng phụ thuộc vào cảm tính của người trực hôm đó.

Impact:
Khoảng 40 phút mỗi ca, 4-6 ca mỗi tuần.
Nguy hiểm hơn là khoảng 1 trong 5 ticket đã đóng dạng không tái hiện
sau đó quay lại thành sự cố thật, lúc đó chi phí xử lý lớn hơn nhiều.

Success metric:
Tỉ lệ ticket đóng nhầm quay lại từ khoảng 20% xuống dưới 5%.
Thời gian mỗi ca từ 40 phút xuống dưới 15 phút.

Non-AI alternative:
Quy ước cứng: chạy lại đúng 20 lần, nếu lỗi xuất hiện từ 1 lần trở lên thì giữ ticket mở
và ghi lại tần suất thay vì ghi không tái hiện.
Cách này rẻ, làm được ngay trong tuần và đã xử lý được phần lớn vấn đề.

AI hypothesis:
Model đọc ticket cộng log, sinh ra một tập biến thể của input cùng ý định
thay vì chỉ lặp lại đúng một câu, để tăng khả năng chạm lại lỗi.
Tôi xem lại tập biến thể trước khi cho chạy, tránh việc nó tự đi lệch ý định ban đầu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 42 phút mỗi ca, kết luận dựa vào cảm tính

[1 Đọc report, dựng lại input: 10 phút]
→ [2 Chạy lại 1 lần: 2 phút]
→ [3 Chạy thêm 5-10 lần: 15 phút]  <-- bottleneck
→ [4 Phân vân đóng hay để mở: 10 phút]
→ [5 Ghi chú và đóng dạng không tái hiện: 5 phút]

FUTURE STATE — 14 phút mỗi ca, kết luận kèm tần suất

[1 Đọc report, dựng lại input: 5 phút]
→ [2 Model sinh tập biến thể cùng ý định: 1 phút]     -- Workflow step
→ [3 Tôi duyệt tập biến thể trước khi chạy: 3 phút]   <-- human boundary
→ [4 Chạy tự động 20 lần trên toàn bộ biến thể: tự động]  -- Rule
→ [5 Ghi kết luận kèm tần suất lỗi quan sát được: 5 phút]

Fallback: nếu tập biến thể do model sinh lệch khỏi ý định gốc của người báo lỗi,
tôi bỏ phần sinh biến thể và chỉ giữ quy ước chạy lại 20 lần trên đúng input ban đầu.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Che thông tin nhạy cảm trước khi vào prompt và log.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow sáu bước chạy 2-3 lần mỗi tháng, bottleneck nằm gọn ở đúng một bước là đọc tay mẫu 100 bản ghi.
Số đo có hai mặt kéo ngược nhau, che sót phải dưới 2% và che thừa phải dưới 3%,
nên không thể đạt metric bằng cách siết chặt cho an toàn.
Impact không chỉ là 135 phút mỗi vòng rà, mà là một lần che sót lọt vào log
đã thành sự cố phải báo cáo và không sửa lại được vì log đã nhân bản sang hệ thống giám sát.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Muốn nhờ model tìm dữ liệu nhạy cảm thì phải cho nó xem chính dữ liệu đó.
   Vậy bước nhờ model có tự nó đã là rò rỉ chưa, và nếu buộc phải dùng model chạy nội bộ
   thì chi phí đó có còn đáng so với việc chỉ mở rộng luật cứng không?
2. Tập kiểm 500 bản ghi đã gán nhãn lấy từ đâu và ai gán?
   Việc ngồi gán nhãn cho dữ liệu nhạy cảm liệu có tự tạo ra một rủi ro mới
   ngang với rủi ro mà tôi đang cố giảm?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Ban đầu tôi chỉ đặt một metric là giảm tỉ lệ che sót, mà chỉ số này đạt được quá dễ bằng cách che mạnh tay hơn, đổi lại câu trả lời mất ngữ cảnh và trở nên vô dụng. AI cũng chỉ ra tôi đang bỏ qua nghịch lý nằm ngay giữa giải pháp, là muốn nhờ model tìm dữ liệu nhạy cảm thì phải đưa chính dữ liệu đó cho model.
- Tôi sửa gì: Thêm metric thứ hai là tỉ lệ che thừa để hai chỉ số kéo ngược nhau. Ghi rõ ràng buộc chỉ dùng model chạy nội bộ, hoặc chỉ gửi ra ngoài phần văn bản đã qua vòng luật cứng, và đưa ràng buộc này lên thành ranh giới cứng trong phần workflow thay vì để trong ghi chú.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
