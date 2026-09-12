# 02 — Group Problem Statement (Bản nộp nhóm)

> Làm chung 1 bản, mỗi thành viên copy vào repo cá nhân. Đi theo Phase 3 → 6 trong `01-worksheet.md`. Nhóm chỉ chọn **candidate problem** ở Phase 3, viết Problem Statement sau khi validate + vẽ workflow.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|-----|-----------|-------------|---------------------|
| 1 | Nguyễn Thanh Bình | 2A202602777 | Chủ đề (candidate được chọn là card của Bình), domain tài chính |
| 2 | Phạm Long Nhật | 2A202602844 | Workflow + writer bản nộp |
| 3 | Hoàng Đức Dũng | 202602798 | Rủi ro & ranh giới AI (góc nhìn vận hành hệ AI) |
| 4 | Trần Gia Khánh | 2A202602689 | Research giải pháp đã có |
| 5 | Nguyễn Đình Anh | 2A202602573 | Validation + facilitator |

**Candidate problem nhóm chọn (1 câu):**

Nhà đầu tư cổ phiếu cá nhân dễ bỏ lỡ thời điểm phản ứng với một tin tức hoặc sự kiện doanh nghiệp, vì tin mới nằm rải rác ở nhiều nguồn và phải tự đánh giá theo từng mã đang nắm.

> **Quy ước ký hiệu:** số không đánh dấu là số đã đếm/quan sát thật; `~` là ước lượng chưa bấm giờ; `(giả định)` là mục tiêu kỳ vọng chưa kiểm chứng; `[chờ validation]` là ô phải điền bằng dữ liệu thật thu ở Phase 4.

---

## Phase 3 — Group Convergence: từ 15 candidates về 1

### 3.1. Trình bày top 3 mỗi người

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---|---|---|---|---|---|
| 1 | Nhật | Gộp file đồ án tốt nghiệp 4 người thành 1 bản | Người gộp cuối | Chuẩn hoá format + hỏi lại tác giả | Workflow rất rõ, nhưng là việc nội bộ của 1 người |
| 2 | Nhật | Viết báo cáo intern 2 tuần/lần | Bản thân + mentor | Diễn đạt thành văn (25/30 phút) | Impact nhỏ, chính người pitch đã tự nhận Not Yet |
| 3 | Nhật | Họp nhóm xong không có bản chốt ai-làm-gì-hạn-nào | Cả nhóm | Không có bước chốt trước khi giải tán | 0 việc rơi thật → chưa có tác hại đo được |
| 4 | Dũng | Che thông tin nhạy cảm trước khi đưa vào prompt và log | Đội vận hành hệ AI | Quyết định cái gì là nhạy cảm | Bài hay, hai metric kéo ngược nhau; nhưng cả nhóm khó cùng hiểu domain |
| 5 | Dũng | Chốt ngưỡng cho model phân loại với bên vận hành | Hai bên: kỹ thuật + vận hành | Dịch bảng số sang hệ quả vận hành | Có mâu thuẫn lợi ích thật; chính người pitch nghi bảng tính là đủ |
| 6 | Dũng | Bug do QA báo không tái hiện được | QA + dev | Không có tiêu chí bao nhiêu lần chạy lại là đủ | Đặc thù hệ sinh ngôn ngữ, nhưng tiêu chí chưa thống nhất |
| 7 | Bình | Đánh giá tác động đa nguồn lên một mã | Nhà đầu tư cá nhân | Tổng hợp nhiều nguồn thành 1 kết luận nhất quán | Phạm vi rộng, dễ thành "làm agent phân tích" |
| 8 | **Bình** | **Bỏ lỡ thời điểm phản ứng với tin tức / sự kiện doanh nghiệp** | **Nhà đầu tư cá nhân** | **Phát hiện sớm tin liên quan tới mã + đánh giá tin đó có đủ quan trọng không** | **Nỗi đau cụ thể, có yếu tố thời gian đo được** |
| 9 | Bình | So sánh báo cáo tài chính nhiều quý | Nhà đầu tư cá nhân | Trích cùng nhóm chỉ tiêu, đặt cạnh nhau đúng kỳ | Rất rõ ràng nhưng gần như là bài trích xuất bảng, ít chỗ tranh luận |
| 10 | Khánh | Đọc hiểu và tóm tắt paper tiếng Anh 15-20 trang | Sinh viên | Đọc và rút ý chính | Đúng là tốn thời gian, nhưng 1 người, không handoff |
| 11 | Khánh | Viết email ứng tuyển thực tập gửi nhiều công ty | Sinh viên | Viết lại nội dung cho từng công ty | Lặp lại cao nhưng impact cá nhân, khó có metric ngoài thời gian |
| 12 | Khánh | Chuẩn hoá trích dẫn APA/IEEE cho đồ án | Sinh viên | Sửa định dạng thủ công | Chính người pitch đã tự nghi Zotero/Mendeley giải xong rồi |
| 13 | Đình Anh | AI Dispatcher lọt lưới khi gặp câu lệnh lách luật (jailbreak) | Đội vận hành + người dùng cuối | Bao phủ kịch bản tấn công mới | Có số thật (2/5 test case), nhưng chỉ 1 người trong nhóm nắm hệ thống |
| 14 | Đình Anh | Tự gõ test case thủ công để kiểm tra System Prompt | Người viết prompt | Soạn test case bằng tay (45-60 phút/lần) | Chính người pitch nói script tự động giải triệt để → không cần AI |
| 15 | Đình Anh | Người dùng gửi câu hỏi thiếu thông tin (thiếu % pin, vị trí) | Người dùng cuối + hệ thống | Thu thập đủ thông tin mà không làm hội thoại dài dòng | Chiếm 40% lượt chat, nhưng là bài thiết kế hội thoại hơn là bài chọn mức AI |

### 3.2. Gom trùng / cluster

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A — Vận hành & an toàn một hệ AI đang chạy | 4, 5, 6, 13, 14, 15 | Đã có hệ AI trong sản xuất; nỗi đau là kiểm soát chất lượng, an toàn, ngưỡng và test | Cụm mạnh nhất về evidence, yếu nhất về "cả nhóm hiểu domain" — chỉ Dũng và Đình Anh nắm hệ thống |
| B — Thông tin tài chính rải rác → một kết luận | 7, 8, 9 | Nhiều nguồn rời rạc, người dùng phải tự gom và tự phán đoán mức độ quan trọng | Có actor bên ngoài nhóm, tiếp cận được để phỏng vấn |
| C — Cộng tác nhóm & bàn giao | 1, 2, 3 | Chi phí chuẩn hoá dồn vào một người ở cuối chuỗi handoff | Workflow rõ nhất, nhưng phạm vi ảnh hưởng hẹp |
| D — Xử lý văn bản lặp lại cho cá nhân | 10, 11, 12 | Một người, một văn bản, quy tắc tương đối rõ | Ba bài đều đã có tool sẵn giải phần lớn; ít chỗ để so sánh Rule/Workflow/Agent |

### 3.3. Shortlist

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| #8 Bỏ lỡ thời điểm phản ứng với tin tức (cluster B) | Actor ở ngoài nhóm nên validate được bằng người thật. Bottleneck nằm gọn ở một bước: phát hiện + đánh giá mức quan trọng. Có biến thời gian đo được (khoảng cách từ lúc tin xuất bản đến lúc nhà đầu tư biết). | Chưa định nghĩa được "thời điểm đẹp". Chưa chắc thông tin nhanh hơn dẫn tới quyết định tốt hơn. |
| #1 Gộp file đồ án (cluster C) | Workflow 7 bước rõ nhất trong cả 15 bài, có 3 số đo độc lập (~70 phút/lần, 5-6 lượt hỏi lại, 3 lần nộp sát giờ). Cả nhóm đều hiểu bối cảnh. | Phần lớn lợi ích đến từ Rule thuần (template + file chung), nên bài dễ kết thúc ở "process fix", ít đất để so sánh các mức AI. Ảnh hưởng gói trong 1 người. |
| #13 AI Dispatcher lọt lưới jailbreak (cluster A) | Có evidence định lượng sẵn (2/5 test case lọt). Hậu quả sai đắt và rõ. | Chỉ 1-2 người trong nhóm hiểu hệ thống; 3 người còn lại không challenge được. Khó làm gọn trong thời lượng lab. |

### 3.4. Score để đồng thuận (1-5)

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #8 Bỏ lỡ thời điểm phản ứng tin tức | 5 | 5 | 3 | 5 | 4 | 5 | 4 | **31** |
| #1 Gộp file đồ án | 5 | 5 | 4 | 3 | 4 | 5 | 5 | **31** |
| #13 AI Dispatcher jailbreak | 4 | 4 | 4 | 4 | 3 | 3 | 2 | **24** |

**Giải thích các mức cực trị (theo yêu cầu ép nói rõ vì sao cho 5 / cho 3):**

- #8 được **5 ở "Impact đo được"**: hậu quả không dừng ở thời gian mà chạm tới quyết định tài chính có tiền thật; và có một biến đo trực tiếp là độ trễ phát hiện tin.
- #8 chỉ được **3 ở "Pain có evidence"**: đến thời điểm chốt, nhóm mới có mô tả định tính từ chính người pitch, chưa có nhà đầu tư nào ngoài nhóm xác nhận. Đây là lỗ hổng lớn nhất và là lý do Phase 4 tồn tại.
- #1 chỉ được **3 ở "Impact đo được"**: ~70 phút/tuần dồn vào đúng một người, không lan ra ngoài nhóm.
- #13 chỉ được **2 ở "Nhóm hiểu domain"**: 3/5 thành viên không đủ nền để phản biện, nên nếu chọn bài này thì thực chất chỉ 2 người làm.
- #13 chỉ được **3 ở "So sánh R/W/A được"**: bài chống jailbreak gần như buộc phải có model tham gia, nên so sánh với Rule thuần trở nên hình thức.

**Candidate nhóm chọn (1 bài duy nhất):**

```text
#8 — Nhà đầu tư cổ phiếu cá nhân dễ bỏ lỡ thời điểm phản ứng với một tin tức hoặc
sự kiện doanh nghiệp, vì tin mới nằm rải rác ở nhiều nguồn và phải tự đánh giá
theo từng mã đang nắm.
```

**Vì sao chọn (4-5 câu):**

```text
Bài này tập trung vào nỗi đau "bỏ lỡ thời điểm đẹp", là hệ quả trực tiếp của việc
xử lý thông tin chậm, chứ không phải một mong muốn chung chung là "phân tích tốt hơn".
Workflow có bottleneck rõ ở bước phát hiện, liên kết tin với mã, và đánh giá mức
quan trọng — ba việc này xảy ra liên tiếp ở cùng một chỗ, nên can thiệp được vào
đúng một điểm. Có thể đo bằng khoảng cách thời gian từ lúc tin xuất hiện đến lúc
nhà đầu tư nhận được thông tin có liên quan tới mã mình nắm, là một con số khách
quan không phụ thuộc cảm nhận. Actor nằm ngoài nhóm nên nhóm buộc phải đi hỏi người
thật thay vì tự khai, và cũng dễ tìm người để phỏng vấn. Cuối cùng, bài này cho phép
so sánh sòng phẳng cả ba mức: lọc theo từ khoá là Rule, chuỗi cố định có model xếp
ưu tiên là Workflow, và tự đi tra thêm rồi tự quyết là Agent.
```

**Vì sao KHÔNG chọn các candidate còn lại:**

```text
#1 Gộp file đồ án — điểm số bằng #8 (31/35) và workflow thậm chí rõ hơn. Nhóm loại
vì hai lý do: ảnh hưởng gói trong đúng một người, và khi tách thời gian ra thì
khoảng 45/70 phút bị xoá bởi Rule thuần (template + file chung co-edit). Bài sẽ kết
thúc ở "process fix, gần như không cần AI" — đúng nhưng ít đất để nhóm luyện phần
so sánh và phần ranh giới AI.

#13 AI Dispatcher lọt lưới jailbreak — evidence tốt nhất trong ba bài shortlist
(2/5 test case lọt, hậu quả rõ). Loại vì chỉ 2/5 thành viên hiểu hệ thống, ba người
còn lại không thể challenge, nên bản nộp sẽ phản ánh ý kiến của thiểu số. Ngoài ra
phạm vi "bao phủ mọi kịch bản tấn công mới" quá rộng để gói trong lab.

Cluster A còn lại (#4, #5, #6, #14, #15) — đều là bài vận hành nội bộ một hệ AI đang
chạy. Riêng #5 và #14 đã bị chính người pitch tự nghi là không cần AI (một bảng tính
quy đổi, một script tự động). Nhóm ghi nhận đây là dấu hiệu tốt về tư duy nhưng
không chọn làm bài chính.

Cluster D (#10, #11, #12) — cả ba đều là việc một người, không có handoff, và đã có
tool sẵn giải phần lớn (Zotero/Mendeley cho #12). Metric dễ rơi vào "nhanh hơn".

#7 và #9 (cùng cluster với bài được chọn) — #7 quá rộng, dễ trượt thành "làm một
agent phân tích đầu tư", đúng kiểu solution-first mà lab cảnh báo. #9 rõ ràng nhưng
bản chất là bài trích xuất bảng, gần như chắc chắn ra kết luận Workflow, ít tranh luận.
```

**Disagreement (ai lo gì, chốt ra sao):**

```text
Hai bài #8 và #1 hoà điểm 31/35, nhóm phải tranh luận thêm để chốt.

Nhật bảo vệ #1: workflow rõ nhất, số đo chắc nhất, cả nhóm hiểu bối cảnh nên ai
cũng challenge được. Rủi ro thấp nhất nếu mục tiêu là làm xong bài chắc tay.

Bình và Đình Anh phản đối: chính vì #1 chắc quá nên nó không còn gì để quyết định —
câu trả lời đã lộ từ đầu là Rule, phần AI còn lại quá nhỏ.

Dũng đặt câu hỏi quyết định: bài nào buộc nhóm phải tranh luận về ranh giới AI được
làm gì và người phải kiểm cái gì? Với #1, ranh giới hiển nhiên. Với #8, có tiền thật
và có rủi ro người dùng tin vào một bản tóm tắt sai — ranh giới phải được thiết kế.

Chốt: chọn #8. Nhật giữ bảo lưu rằng #8 yếu hơn ở phần evidence (3/5), và nhóm ghi
nhận bảo lưu này bằng cách đặt validation lên thành điều kiện bắt buộc trước khi
viết Problem Statement, thay vì làm cho có.
```

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation

> **Trạng thái: bộ công cụ đã dựng, dữ liệu chưa thu.** Nhóm chủ ý KHÔNG điền quote giả. Các ô `[chờ validation]` phải được thay bằng lời nguyên văn của người được hỏi. Mục tiêu tối thiểu: 3 phỏng vấn + 8 phản hồi survey.

**Bộ câu hỏi phỏng vấn (6 câu, ~7 phút/người — hỏi nhà đầu tư cá nhân, KHÔNG phải người trong nhóm):**

1. Lần gần nhất anh/chị biết một tin ảnh hưởng tới mã đang nắm — biết qua đâu, và biết sau bao lâu kể từ lúc tin ra?
2. Trong một ngày, anh/chị mở bao nhiêu nguồn tin, mỗi lần mất bao lâu?
3. Có lần nào biết tin muộn rồi thấy tiếc không? Kể lại cụ thể một lần.
4. Trong 10 tin nhắc tới mã anh/chị nắm, khoảng mấy tin thật sự đáng phản ứng?
5. Nếu có người tóm tắt sẵn tin cho anh/chị, anh/chị có đọc lại nguồn gốc không, hay tin luôn?
6. Điều gì làm anh/chị KHÔNG dùng một công cụ tóm tắt tin tự động?

> Câu 3 dùng để kiểm chứng nỗi đau có thật hay chỉ là phiền. Câu 4 đo tỉ lệ nhiễu. Câu 5 là câu quan trọng nhất — nó quyết định ranh giới AI ở Phase 6: nếu đa số trả lời "tin luôn, không mở nguồn", rủi ro của bản tóm tắt sai tăng vọt và thiết kế phải ép người dùng nhìn thấy nguồn.

**Bộ câu hỏi survey (8 câu, ~2 phút — gửi group đầu tư / lớp / Discord):**

1. Anh/chị đang theo dõi bao nhiêu mã? (1-3 / 4-10 / >10)
2. Thường biết tin mới qua đâu? (chọn nhiều: app công ty chứng khoán / CafeF / Vietstock / group Zalo-FB / X / khác)
3. Trung bình mất bao lâu từ lúc tin ra tới lúc anh/chị biết? (<15' / 15-60' / vài giờ / sang hôm sau / không biết)
4. Một ngày chủ động mở nguồn tin bao nhiêu lần? (<3 / 3-6 / >6)
5. Trong 3 tháng qua, có lần nào biết tin muộn và thấy ảnh hưởng tới quyết định không? (có / không / không rõ)
6. Nếu có, khoảng mấy lần?
7. Trong các tin nhắc tới mã đang nắm, bao nhiêu phần trăm là đáng phản ứng? (<10% / 10-30% / >30%)
8. Nếu nhận được tóm tắt tự động, anh/chị có bấm mở nguồn gốc trước khi hành động không? (luôn / thỉnh thoảng / hiếm khi)

| Nguồn | Số người / mẫu | Tín hiệu xác nhận (kèm quote nguyên văn) | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | [chờ validation] | [chờ validation] | [chờ validation] | [chờ validation] |
| Survey / poll | [chờ validation] | [chờ validation] | [chờ validation] | [chờ validation] |
| Log / ticket / review | — | Không áp dụng: nhóm không sở hữu log của nhà đầu tư | — | — |

**Insight sau validation:**

```text
[chờ validation — viết sau khi có tối thiểu 3 interview + 8 survey]

Hai điều cần trả lời dứt khoát trước khi viết Problem Statement v1:
(a) Độ trễ phát hiện tin hiện tại là bao nhiêu, và có phải là nguyên nhân thật
    của việc bỏ lỡ không — hay nguyên nhân thật là do dự khi ra quyết định?
(b) Nhà đầu tư có mở nguồn gốc trước khi hành động không? Câu trả lời quyết định
    ranh giới AI ở Phase 6.
```

Bằng chứng đính kèm (khi có): `02-group-problem-statement-survey.png`, `02-group-problem-statement-interview-notes.md`

### 4.2. Research giải pháp đã có

> Tất cả link dưới đây đã được kiểm HTTP 200 ngày 2026-09-12.

| Nguồn / tool | Link | Họ giải bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Alerts | https://www.google.com/alerts | Bước 1-2: phát hiện tin chứa từ khoá (tên mã, tên doanh nghiệp) | Miễn phí, dựng trong 2 phút, đẩy về email, không cần code | Chỉ khớp từ khoá nên bỏ sót tin không nêu tên mã; độ trễ index không kiểm soát được; không xếp mức quan trọng nên nhiễu vẫn nguyên | Phần "phát hiện tin có nhắc mã X" coi như đã được giải, miễn phí. Nhóm không nên build lại bước này. |
| RSS nguồn tin trong nước + trình đọc | https://cafef.vn/thi-truong-chung-khoan.rss · https://vietstock.vn/rss · https://feedly.com | Bước 1: gom nhiều nguồn về một chỗ, có mốc thời gian xuất bản chuẩn | Đúng nguồn tiếng Việt; timestamp chuẩn nên đo được độ trễ phát hiện; ổn định, không phụ thuộc bên thứ ba | Không tự lọc theo mã; người dùng vẫn phải tự quét toàn bộ feed; không đánh giá mức quan trọng | Đây chính là hạ tầng để ĐO baseline. Nhóm dùng timestamp RSS làm mốc T0 cho metric độ trễ. |
| Nền tảng dữ liệu chứng khoán có gắn tin theo mã | https://fireant.vn · https://simplize.vn · https://finance.vietstock.vn | Bước 2-3: tin đã được gắn sẵn với mã, kèm dữ liệu giá để đối chiếu | Mapping tin ↔ mã đã có sẵn và do đơn vị chuyên trách làm; có luôn dữ liệu giá ở bước 4 | Vẫn là feed để người dùng tự vào đọc, không chủ động đẩy theo mức độ quan trọng; người dùng vẫn phải tự quét và tự phán đoán | Bước liên kết tin ↔ mã cũng đã được giải. Khoảng trống thật hẹp hơn nhóm tưởng ban đầu. |

**Research takeaway:**

```text
Ba trong năm bước của workflow hiện tại đã có tool sẵn giải tốt và gần như miễn phí:
gom nguồn (RSS), phát hiện theo từ khoá (Google Alerts), và liên kết tin với mã
(FireAnt / Simplize / Vietstock). Nhóm KHÔNG build lại ba bước này.

Khoảng trống thật chỉ còn hai chỗ. Một là tin không nêu tên mã nhưng ảnh hưởng tới
mã — ví dụ một tin về giá nguyên liệu hoặc chính sách ngành mà không nhắc tên doanh
nghiệp nào; lọc từ khoá bất lực ở đây. Hai là xếp mức độ quan trọng để cắt nhiễu,
vì công cụ hiện có đẩy hết mọi tin ngang nhau.

Đây là hai chỗ duy nhất đáng cân nhắc AI. Mọi thứ khác là lắp ghép tool có sẵn.
```

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản nhóm

```text
[1 mở lần lượt các nguồn tin/MXH: ~3'/lượt × 3-6 lượt/ngày - nhà đầu tư]
  → [2 đọc tiêu đề, tìm mã liên quan: ~5'/lượt]        <-- BOTTLENECK
  → [3 mở bài, kiểm nội dung + thời điểm xuất bản: ~3'/bài]
  → [4 đối chiếu diễn biến giá / sự kiện doanh nghiệp: ~5']
  → [5 quyết định phân tích sâu hay chỉ theo dõi tiếp: ~2']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---|---|---|---|---|---|
| 1 | Nhà đầu tư | Danh sách nguồn tự nhớ trong đầu | Một loạt tab/tiêu đề chưa lọc | ~3'/lượt × 3-6 lượt/ngày `[chờ validation]` | Không có handoff — toàn bộ chuỗi do một người tự làm. Tần suất là biến chi phí chính. |
| 2 | Nhà đầu tư | Tiêu đề chưa lọc | Tập tin nghi có liên quan tới mã đang nắm | ~5'/lượt `[chờ validation]` | **Bottleneck.** Phần lớn công sức đổ vào tin không liên quan. Tỉ lệ nhiễu chưa đo (survey câu 7). |
| 3 | Nhà đầu tư | Bài báo đầy đủ | Xác nhận tin có thật, biết mốc thời gian | ~3'/bài | Mốc xuất bản là dữ kiện quan trọng nhưng thường bị bỏ qua khi vội |
| 4 | Nhà đầu tư | Tin + bảng giá + lịch sự kiện DN | Nhận định sơ bộ về chiều hướng ảnh hưởng | ~5' | Bước này cần phán đoán, không tự động hoá được hoàn toàn |
| 5 | Nhà đầu tư | Nhận định sơ bộ | Quyết định: đào sâu / theo dõi / bỏ qua | ~2' | Quyết định cuối cùng luôn thuộc về người |

**Bottleneck chính:**

```text
Bước 1-2 — quét thủ công để phát hiện tin có liên quan, và phán đoán tin đó có đủ
quan trọng để phản ứng hay không.

Đây là bottleneck vì ba lý do. Thứ nhất, nó có tần suất cao nhất trong chuỗi: lặp
3-6 lần mỗi ngày, trong khi bước 3-5 chỉ chạy khi đã lọc ra được tin đáng đọc. Thứ
hai, phần lớn công sức bỏ vào tin không liên quan — đây là công sức bị vứt đi hoàn
toàn. Thứ ba, nó là bước duy nhất trong chuỗi mà độ trễ tích luỹ: nếu nhà đầu tư
không mở nguồn tin trong 2 tiếng, mọi bước sau đều trễ 2 tiếng, bất kể làm nhanh
đến đâu.

Biến then chốt của cả bài toán: T_detect = khoảng cách từ mốc xuất bản của tin đến
lúc nhà đầu tư thực sự biết. Hiện chưa đo. `[chờ validation]`
```

### 5.2. Future workflow bản nhóm

```text
[1 RSS cố định + alert theo mã: MÁY (RULE) - 0' vận hành, dựng 1 lần ~30']
  → [2 khử trùng lặp + gắn tin với mã: MÁY (RULE)]
  → [3 xếp mức độ liên quan/quan trọng + tóm tắt 3 dòng CÓ LINK NGUỒN: AI - ~1']
  → [4 nhà đầu tư đọc thông báo, mở nguồn gốc nếu định hành động: ~3'] <-- BOUNDARY
  → [5 nhà đầu tư tự quyết: đào sâu / theo dõi / bỏ qua]

Năm thứ nhìn ra được:
- Bước máy (Rule): 1 và 2 — gom nguồn, khử trùng lặp, gắn mã theo từ khoá.
- Bước AI: chỉ bước 3 — xếp ưu tiên và tóm tắt. Đúng hai khoảng trống mà research
  chỉ ra, không hơn.
- Bước người: 4 và 5 — đọc nguồn gốc và ra quyết định.
- Boundary: sau bước 3, trước bước 5. AI dừng ở mô tả và xếp hạng; AI KHÔNG được
  khuyến nghị mua/bán, KHÔNG được nêu con số tài chính mà nguồn không nói.
- Fallback: thiếu nguồn hoặc các nguồn mâu thuẫn → hiển thị rõ nguồn nào thiếu,
  KHÔNG kết luận chắc chắn, yêu cầu nhà đầu tư mở nguồn gốc. Hệ thống chết → quay
  về quy trình cũ, không mất gì ngoài tiện lợi.
```

**Before/after impact:**

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---|---|---|
| T_detect (từ mốc xuất bản đến lúc nhà đầu tư biết) | `[chờ validation]` — giả thuyết: vài giờ đến sang hôm sau | < 10 phút (giả định — mục tiêu, lấy từ card gốc) | So mốc timestamp của RSS với mốc thông báo đến tay người dùng, trên 20 tin liên tiếp |
| Số lần chủ động mở nguồn tin/ngày | 3-6 lượt `[chờ validation]` | 0-1 lượt (giả định) | Đếm tự khai trong 5 ngày, trước và sau |
| Tỉ lệ tin nhận được mà đáng phản ứng | `[chờ validation]` — survey câu 7 | Tăng ít nhất gấp đôi (giả định) | Người dùng gắn nhãn đáng/không đáng cho từng thông báo trong 1 tuần |
| Số bước thủ công | 5/5 | 2/5 | Đếm trên sơ đồ |
| Bottleneck chính | Quét thủ công ở bước 1-2 | Chuyển sang bước 4: người đọc và kiểm nguồn | Quan sát |
| **Risk mới** | Không có | **Tóm tắt sai hoặc thiếu ngữ cảnh nhưng người dùng tin luôn, không mở nguồn** | Đếm số lần người dùng hành động mà không bấm vào link nguồn |

> Hàng cuối là rủi ro nhóm coi là nghiêm trọng nhất: quy trình cũ chậm nhưng người dùng luôn đọc bài gốc. Quy trình mới nhanh hơn nhưng chèn một lớp diễn giải vào giữa. Nếu người dùng bỏ qua bước mở nguồn, ta đã đổi "chậm" lấy "sai mà không biết".

### 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Nhà đầu tư cổ phiếu cá nhân, không chuyên, đang theo dõi một nhóm mã và có công việc chính khác nên không ngồi canh bảng liên tục. |
| **Workflow** | Mở lần lượt các nguồn tin → đọc tiêu đề tìm mã liên quan → mở bài kiểm nội dung và mốc thời gian → đối chiếu diễn biến giá và sự kiện doanh nghiệp → quyết định đào sâu hay theo dõi tiếp. |
| **Bottleneck** | Bước phát hiện tin liên quan và đánh giá tin đó có đủ quan trọng không. Tần suất cao nhất, phần lớn công sức đổ vào tin không liên quan, và là nơi độ trễ tích luỹ cho toàn chuỗi. |
| **Impact** | Biết tin muộn làm mất thời điểm theo dõi hoặc phản ứng; đồng thời dễ ưu tiên nhầm tin ít quan trọng. Mức độ định lượng `[chờ validation]`. |
| **Success Metric** | Giảm T_detect xuống dưới 10 phút, và mỗi thông báo phải có mốc thời gian, nguồn, mã liên quan, mức cần theo dõi. |
| **Boundary** | Làm: phát hiện, gắn mã, xếp ưu tiên, tóm tắt có dẫn nguồn. Không làm: khuyến nghị mua bán, dự báo giá, thực hiện lệnh. |

**Câu hỏi AI phản biện v0:**
- Field nào mơ hồ: **Impact** — "bỏ lỡ thời điểm" chưa gắn với con số nào, nên không kiểm chứng được. Và **Success Metric** đang đo tốc độ cung cấp thông tin, trong khi vấn đề nhóm nêu là chất lượng thời điểm ra quyết định. Hai thứ này không tự động bằng nhau.
- Nhóm sửa gì: Ở v1, tách rõ metric chính (đo được ngay: T_detect, tỉ lệ nhiễu) khỏi metric kết quả (chỉ kiểm được sau nhiều tháng: chất lượng quyết định), và ghi thẳng rằng nhóm chỉ cam kết metric thứ nhất. Đồng thời bổ sung ràng buộc chống rủi ro mới: mọi thông báo bắt buộc kèm link nguồn gốc.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp

- **Độ mơ hồ:** [ ] Thấp — [x] **Cao**. Vì sao: "tin này có quan trọng không" không có đáp án đúng/sai tuyệt đối; hai nhà đầu tư nắm cùng một mã có thể xếp hạng khác nhau tuỳ vị thế và khung thời gian của họ.
- **Độ phức tạp:** [ ] Thấp — [x] **Cao**. Vì sao: 3+ bước phụ thuộc nhau, nhiều nguồn không đồng nhất, và có yếu tố thời gian thực.

**Bài toán nhóm nằm ở ô nào:**

```text
Ô mơ hồ CAO + phức tạp CAO.
```

**Vì sao (2-3 câu):**

```text
Theo ma trận, ô này thường được gợi ý là địa hạt của Agent. Nhóm cố ý không đi theo
gợi ý đó, vì độ mơ hồ ở đây nằm trong PHÁN ĐOÁN NỘI DUNG của một bước duy nhất
(tin này quan trọng đến đâu), chứ không nằm trong LỘ TRÌNH các bước. Lộ trình của
bài này cố định và biết trước: gom nguồn, khử trùng lặp, gắn mã, xếp hạng, tóm tắt,
đẩy thông báo — không có nhánh nào cần hệ thống tự nghĩ ra bước tiếp theo.

Agent chỉ xứng đáng khi bản thân trình tự các bước là thứ không biết trước. Ở đây
ta biết trước, nên mức đúng là Workflow có một bước dùng model, đặt sau một tầng
Rule để cắt khối lượng đầu vào.
```

### 6.1. So sánh Rule / Workflow / Agent

| Mức | Phương án cho bài toán nhóm | Khi nào đủ | Rủi ro | Chọn? (Dùng cho bước nào?) |
|---|---|---|---|---|
| **Rule** | RSS cố định từ CafeF/Vietstock + Google Alerts theo mã + khử trùng lặp + gắn mã bằng khớp từ khoá và mã doanh nghiệp | Đủ nếu nhà đầu tư chỉ theo dõi vài mã lớn, tin luôn nêu đích danh tên mã, và họ chấp nhận tự đọc hết mọi tin khớp | Bỏ sót tin không nêu tên mã (tin ngành, tin chính sách, tin đối thủ). Không cắt được nhiễu — vẫn đẩy mọi tin ngang nhau, dễ gây mệt rồi bỏ dùng | **CÓ — bước 1 và 2.** Đây là tầng nền, chạy trước và luôn chạy |
| **Workflow** | Chuỗi cố định: fetch RSS → khử trùng lặp → model chấm mức liên quan và mức quan trọng theo danh mục người dùng → sinh tóm tắt 3 dòng kèm link → đẩy thông báo | Đủ khi các bước biết trước và không cần rẽ nhánh — đúng trường hợp này | Model chấm sai mức quan trọng: hạ nhầm một tin quan trọng thì người dùng vẫn bỏ lỡ. Tóm tắt lệch ngữ cảnh. Chi phí gọi model theo lượng tin | **CÓ — bước 3. Đây là mức nhóm chọn** |
| **Agent** | Hệ tự chọn nguồn, tự đi tra thêm khi thấy tin mơ hồ, tự quyết có báo hay không, tự đề xuất hành động | Chỉ đủ khi trình tự các bước không biết trước và phải tự lập kế hoạch theo tình huống | Không kiểm soát được đường đi nên khó tái hiện lỗi. Với tiền thật, một khuyến nghị sai có hậu quả trực tiếp. Chi phí và độ trễ cao hơn — nghịch lý với chính mục tiêu giảm độ trễ | **KHÔNG.** Các bước đã biết trước nên năng lực tự lập kế hoạch không được dùng đến, trong khi rủi ro thì gánh đủ |

**5 câu hỏi chốt:**

1. **Rule có giải được 70-80% case không?**
Giải được phần lớn bước phát hiện — với tin có nêu đích danh tên mã, lọc từ khoá bắt gần như trọn. Nhưng đó là 70-80% của một bước, không phải của bài toán. Rule không chạm được vào việc cắt nhiễu, mà nhiễu chính là thứ làm nhà đầu tư mệt và bỏ dùng công cụ. Nên Rule là điều kiện cần, chưa đủ.

2. **Các bước có đi thẳng một đường không hay phải rẽ nhánh?**
Đi thẳng một đường: gom → khử trùng lặp → gắn mã → chấm điểm → tóm tắt → đẩy. Không có nhánh nào mà kết quả bước trước làm đổi trình tự các bước sau. Đây là lý do kỹ thuật quan trọng nhất để không chọn Agent.

3. **Có thật sự cần Agent tự lập kế hoạch + gọi tool không?**
Không. Danh sách nguồn do người dùng khai báo, không cần hệ tự đi tìm. Không có bước nào cần quyết định "giờ nên làm gì tiếp". Cái khó nằm ở chất lượng phán đoán trong một bước, và đó là việc của một lần gọi model có prompt tốt, không phải của một vòng lặp tự trị.

4. **Nếu AI sai, ai phát hiện đầu tiên và sửa trong bao lâu?**
Có hai kiểu sai, và chúng không đối xứng. Sai kiểu báo nhầm tin không quan trọng: nhà đầu tư phát hiện ngay khi đọc, mất vài giây, vô hại. Sai kiểu **bỏ sót một tin quan trọng**: không ai phát hiện được, vì người dùng không biết cái mình không nhận. Kiểu sai thứ hai nguy hiểm hơn hẳn và là lý do phải giữ một chế độ xem toàn bộ feed chưa lọc, để người dùng đối chiếu định kỳ.

5. **Có hạ được từ Agent → Workflow → Rule không?**
Hạ được từ Agent xuống Workflow: đã hạ, vì lộ trình cố định. Hạ tiếp xuống Rule thuần thì không, vì hai khoảng trống mà research chỉ ra — tin không nêu tên mã, và xếp mức quan trọng — đều cần hiểu nội dung, không phải khớp chuỗi ký tự. Nhóm dừng ở Workflow và ghi rõ: nếu validation cho thấy nhà đầu tư chấp nhận đọc hết feed không lọc, thì hạ xuống Rule thuần và bỏ hẳn phần model.

**Mức chọn:**

```text
Workflow — với một tầng Rule chạy trước làm nền.
```

**Vì sao chọn (3-4 câu):**

```text
Lộ trình các bước cố định và biết trước, nên phần "tự lập kế hoạch" của Agent không
có việc để làm, trong khi rủi ro mất kiểm soát và chi phí độ trễ thì vẫn phải gánh —
mà độ trễ chính là thứ bài toán này đang cố giảm. Đồng thời Rule thuần không đủ, vì
hai khoảng trống thật (tin không nêu tên mã, và xếp mức quan trọng để cắt nhiễu) đều
đòi hiểu nội dung chứ không phải khớp từ khoá. Workflow đặt model vào đúng một bước
duy nhất, nơi nó thật sự thêm giá trị, và giữ mọi bước còn lại ở dạng máy hoặc người
— nên khi có lỗi, nhóm biết chắc phải nhìn vào đâu. Tầng Rule chạy trước cũng cắt
khối lượng đầu vào cho model, giảm chi phí và giảm bề mặt sai.
```

**Vì sao không chọn mức đơn giản hơn (2-3 câu):**

```text
Rule thuần đã được cân nhắc nghiêm túc chứ không phải hình thức: nó miễn phí, dựng
trong 30 phút, và không bao giờ bịa. Nhóm không dừng ở đó vì nó đẩy mọi tin ngang
nhau, nên không giải được nửa sau của bottleneck là "tin này có đáng phản ứng không"
— và theo research, chính phần nhiễu này là thứ làm người dùng bỏ công cụ sau vài
ngày. Nói cách khác, Rule thuần giải được vấn đề "không biết tin" nhưng tạo ra vấn
đề mới là "biết quá nhiều tin".
```

### 6.2. Problem Statement v1

| Field | Nội dung |
|---|---|
| **Actor** | Nhà đầu tư cổ phiếu cá nhân không chuyên, theo dõi khoảng 5-15 mã, có công việc chính khác nên chỉ mở nguồn tin được 3-6 lần/ngày `[chờ validation]`. Không phải trader chuyên nghiệp ngồi canh bảng. |
| **Workflow** | Mở lần lượt các nguồn tin và mạng xã hội tài chính → đọc tiêu đề để tìm mã liên quan → mở bài kiểm nội dung và mốc xuất bản → đối chiếu diễn biến giá và sự kiện doanh nghiệp → quyết định đào sâu, theo dõi tiếp hay bỏ qua. |
| **Bottleneck** | Hai bước đầu: phát hiện tin có liên quan tới mã đang nắm, và phán đoán tin đó có đủ quan trọng để phản ứng. Đây là bước tần suất cao nhất, có tỉ lệ công sức bị vứt đi lớn nhất, và là nơi độ trễ tích luỹ cho toàn chuỗi. |
| **Impact** | Độ trễ ở bước phát hiện đẩy lùi toàn bộ chuỗi, dẫn tới mất thời điểm theo dõi hoặc phản ứng; đồng thời sự thiếu xếp hạng làm nhà đầu tư dồn sự chú ý vào tin ít quan trọng. Mức định lượng `[chờ validation]` — survey câu 5 và 6. |
| **Success Metric** | **Metric chính (nhóm cam kết, đo được trong 1 tuần):** (a) T_detect từ mốc xuất bản đến lúc thông báo tới tay người dùng: `[chờ validation]` → dưới 10 phút, đo bằng so timestamp RSS với timestamp thông báo trên 20 tin liên tiếp; (b) tỉ lệ thông báo được người dùng gắn nhãn "đáng phản ứng": `[chờ validation]` → tăng ít nhất gấp đôi, đo bằng gắn nhãn thủ công trong 1 tuần. **Metric kết quả (KHÔNG cam kết):** chất lượng quyết định đầu tư — nhóm ghi rõ là không đo được trong phạm vi này và không nhận là mục tiêu. |
| **Boundary** | **Làm:** gom nguồn cố định do người dùng khai báo, khử trùng lặp, gắn tin với mã, chấm mức liên quan và mức quan trọng, sinh tóm tắt 3 dòng kèm link nguồn và mốc thời gian, đẩy thông báo. **Không làm:** khuyến nghị mua/bán/giữ, dự báo giá, đặt lệnh, nêu bất kỳ con số tài chính nào mà nguồn không nói, hay tổng hợp nhiều tin thành một kết luận đầu tư. |
| **AI intervention point** | Can thiệp **sau** bước khử trùng lặp và gắn mã (Rule), **trước** bước nhà đầu tư đọc thông báo. Đúng một bước: chấm điểm và tóm tắt. Mọi bước trước là máy, mọi bước sau là người. |
| **Mức chọn** | **Workflow**, có tầng Rule chạy trước — vì lộ trình các bước cố định nên không cần Agent, nhưng hai khoảng trống còn lại đòi hiểu nội dung nên Rule thuần không đủ. |
| **Rủi ro & người thật kiểm tra** | **Rủi ro lớn nhất không phải tóm tắt sai, mà là bỏ sót một tin quan trọng** — vì người dùng không thể phát hiện thứ mình không nhận được. Cách kiểm: giữ một chế độ xem toàn bộ feed chưa lọc, và mỗi cuối tuần người dùng đối chiếu ngẫu nhiên 20 tin bị hệ thống hạ hạng để xem có tin nào bị chôn nhầm không. **Rủi ro thứ hai:** người dùng tin tóm tắt mà không mở nguồn — chống bằng cách mọi thông báo đều bắt buộc kèm link gốc và mốc thời gian, và đo tỉ lệ bấm vào link. Người kiểm cuối cùng luôn là chính nhà đầu tư; hệ thống không có quyền quyết định nào. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | **Yes** | Actor cụ thể (nhà đầu tư cá nhân không chuyên, 5-15 mã, không canh bảng) và workflow 5 bước đã vẽ được với bottleneck nằm gọn ở bước 1-2. |
| Baseline + metric đo được chưa? | **Not Yet** | Metric đã định nghĩa chặt và có cách đo cụ thể, nhưng baseline T_detect và tỉ lệ nhiễu đều chưa có số thật. Đây là lỗ hổng lớn nhất của bài — đúng như điểm 3/5 mà nhóm tự chấm ở Phase 3. |
| Data/input đủ dùng chưa? | **Yes** | RSS của CafeF và Vietstock công khai, có timestamp chuẩn; Google Alerts miễn phí. Không cần dữ liệu độc quyền nào. |
| AI sai, hậu quả chấp nhận được không? | **Not Yet** | Sai kiểu báo thừa thì vô hại. Sai kiểu bỏ sót thì người dùng không phát hiện được, và đây là bài toán có tiền thật. Chỉ chấp nhận được nếu có cơ chế đối chiếu feed chưa lọc — cơ chế này chưa được thử. |
| Có người review/owner không? | **Yes** | Chính nhà đầu tư là người kiểm ở bước 4 và là người duy nhất ra quyết định. Hệ thống không có quyền hành động. |
| Có cách non-AI đơn giản hơn không? | **Yes — và đã được chọn làm bước đầu** | RSS + Google Alerts giải được phần phát hiện, miễn phí, dựng trong 30 phút. Nhóm làm cái này TRƯỚC chứ không xem là phương án thay thế bị loại. |

**Decision:**

```text
TÁCH ĐÔI THEO TẦNG:
- Tầng Rule (gom nguồn + alert theo mã + khử trùng lặp): GO — làm ngay.
- Tầng AI (chấm mức quan trọng + tóm tắt):              NOT YET — chờ validation.
```

**Lý do (3-4 câu dựa trên bằng chứng):**

```text
Tầng Rule được Go vì research đã xác nhận nó là thứ có sẵn, miễn phí, dựng trong
khoảng 30 phút, không bao giờ bịa nội dung, và đảo ngược được hoàn toàn — chi phí
sai gần bằng không. Quan trọng hơn, chính nó là hạ tầng để đo baseline: timestamp
của RSS cho nhóm mốc T0 mà nếu không có thì mọi metric về độ trễ đều là nói suông.

Tầng AI bị hoãn vì hai lý do có bằng chứng. Thứ nhất, nhóm chưa có baseline T_detect
nên không biết mình đang cải thiện từ mức nào — cam kết "dưới 10 phút" hiện là con
số lấy từ card gốc chứ chưa dựa trên đo đạc. Thứ hai, và nghiêm trọng hơn, nhóm
chưa biết nhà đầu tư có mở nguồn gốc trước khi hành động không (câu 5 phỏng vấn,
câu 8 survey). Nếu câu trả lời là "hiếm khi", thì việc chèn một lớp tóm tắt vào giữa
sẽ đổi vấn đề "chậm" lấy vấn đề "sai mà không biết" — một đánh đổi tệ hơn hiện trạng.
Quyết định làm AI khi chưa trả lời được câu đó sẽ là solution-first.
```

**Nếu Go — pilot nhỏ nhất (đang áp dụng cho tầng Rule):**

```text
Phạm vi: 3 mã, 2 nguồn (RSS CafeF thị trường chứng khoán + Google Alerts theo tên mã
và tên doanh nghiệp). Chạy tay hoàn toàn, không viết code: một thành viên mở feed
mỗi sáng và ghi lại, không tự động hoá gì cả.

Thời gian: 1 tuần.

Ba số phải ra khỏi tuần đó:
1. T_detect thật — với 20 tin liên tiếp, so mốc xuất bản trên RSS với mốc người trong
   nhóm thực sự đọc thấy. Đây là baseline mà cả bài toán đang thiếu.
2. Tỉ lệ nhiễu — trong toàn bộ tin khớp từ khoá, bao nhiêu phần trăm được người theo
   dõi mã đó đánh giá là đáng phản ứng. Con số này quyết định tầng AI có đáng làm không.
3. Tỉ lệ bỏ sót — trong 20 tin quan trọng lấy từ nguồn khác, bao nhiêu tin mà lọc từ
   khoá KHÔNG bắt được. Con số này đo trực tiếp khoảng trống mà research đã chỉ ra.
```

**Nếu Not Yet — cần validate gì trước (áp dụng cho tầng AI):**

```text
Ba điều kiện, phải đủ cả ba mới chuyển tầng AI sang Go:

1. Có baseline T_detect từ pilot tầng Rule (số 1 ở trên). Không có baseline thì không
   có gì để chứng minh cải thiện.
2. Tỉ lệ nhiễu đo được vượt 70% — tức là cứ 10 tin khớp từ khoá thì từ 7 tin trở lên
   là không đáng phản ứng. Dưới ngưỡng đó, người dùng tự lọc được và tầng AI không đủ
   đáng để gánh rủi ro bỏ sót.
3. Ít nhất 3 phỏng vấn xác nhận nhà đầu tư CÓ mở nguồn gốc trước khi hành động. Nếu
   đa số trả lời "hiếm khi", nhóm sẽ không làm tầng tóm tắt, chỉ làm tầng xếp hạng
   và đẩy thẳng tiêu đề gốc kèm link — bỏ hẳn phần AI sinh văn bản.
```

**Nếu No-Go — làm gì thay AI:**

```text
Dừng ở tầng Rule và hoàn thiện nó: mở rộng danh sách nguồn RSS, bổ sung từ khoá theo
ngành chứ không chỉ theo tên mã (ví dụ "giá thép", "lãi suất điều hành") để bắt phần
tin không nêu đích danh, và để nhà đầu tư tự gắn sao cho nguồn nào ưu tiên. Đây vẫn
là cải thiện thật so với hiện trạng, chi phí gần bằng không, và không tạo ra rủi ro
bỏ sót do máy chôn nhầm tin.
```

**Exit / rollback:**

```text
Dừng tầng AI và quay về tầng Rule thuần nếu xảy ra bất kỳ điều nào sau đây:

- Trong đối chiếu cuối tuần, phát hiện từ 2 tin quan trọng trở lên bị hệ thống hạ
  hạng và chôn mất, trong 2 tuần liên tiếp. Đây là kiểu lỗi người dùng không tự thấy
  nên phải chủ động đi tìm.
- Có bất kỳ lần nào hệ thống sinh ra một con số tài chính mà nguồn không hề nói.
  Không có ngưỡng chấp nhận cho lỗi này — một lần là đủ để dừng.
- Tỉ lệ người dùng bấm vào link nguồn gốc trước khi hành động tụt xuống dưới 50%,
  nghĩa là lớp tóm tắt đang thay thế việc đọc nguồn thay vì dẫn tới việc đọc nguồn.

Rollback tốn đúng một thao tác: tắt bước chấm điểm và tóm tắt, đẩy thẳng feed đã khử
trùng lặp. Không mất dữ liệu, không mất cấu hình nguồn, người dùng quay lại đúng
trạng thái của tầng Rule.
```

---

### Self-check nộp phần 02 (nhóm)
- [x] Có nhật ký hội tụ 15 → 1 (cluster 4 cụm + shortlist 3 + bảng score + ghi nhận disagreement)
- [ ] Có validation — **bộ câu hỏi đã dựng, dữ liệu chưa thu.** Phải điền mọi ô `[chờ validation]` bằng quote nguyên văn trước khi nộp
- [x] Có research 3 nhóm nguồn, link đã kiểm HTTP 200 ngày 2026-09-12
- [x] Có workflow trước/sau đủ thời gian, bottleneck, boundary, fallback, và có nêu risk mới
- [x] Có PS v0 → v1, metric tách rõ phần cam kết và phần không cam kết, boundary có làm/không làm
- [x] Có so sánh Rule/Workflow/Agent trên cùng một bài + 5 câu hỏi chốt trả lời đầy đủ
- [x] Có Decision tách theo tầng + pilot + điều kiện chuyển Go + exit/rollback