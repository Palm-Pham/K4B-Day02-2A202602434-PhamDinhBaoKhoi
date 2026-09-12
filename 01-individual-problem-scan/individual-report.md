# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Pham Dinh Bao Khoi
- Mã học viên: 2A202602434
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Hoàng, Nghiên cứu sinh (PhD Student) ngành Data Science, chuyên nghiên cứu ứng dụng Machine Learning và Computer Vision trong phân tích hình ảnh y tế.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): Mỗi chiều thứ Sáu, Hoàng phải rà soát các bài báo khoa học mới nhất trên ArXiv và IEEE, tải các file PDF, đọc lướt để trích xuất thủ công các thông số kỹ thuật (Dataset sử dụng, Kiến trúc Model, Độ chính xác/Accuracy) và nhập vào một file Google Sheets chung. Đây là tài liệu bắt buộc để báo cáo tiến độ trong buổi "Weekly Lab Meeting" với Giáo sư hướng dẫn (Advisor) và các thành viên khác trong lab.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại | Cập nhật file Literature Review trên Google Sheets mỗi thứ Sáu. | Hoàng, Giáo sư | Mất 3-4 tiếng/tuần. |
| 2 | Lặp lại | Format lại các trích dẫn (citations) theo đúng chuẩn IEEE khi viết nháp báo cáo. | Hoàng | Mất khoảng 30 phút/bài. |
| 3 | Tốn thời gian | Tải dataset hình ảnh y tế từ nhiều nguồn và dọn dẹp (clean/format) lại data. | Hoàng | Mất 1-2 ngày mỗi khi có project mới. |
| 4 | AI có thể tốt hơn | Đọc lướt 20 trang PDF chỉ để tìm xem bài báo dùng dataset nào và kết quả ra sao. | Hoàng | Dễ bị sót thông tin do mỏi mắt. |
| 5 | AI có thể tốt hơn | Tìm lại một đoạn code tiền xử lý dữ liệu cũ trên GitHub cá nhân. | Hoàng, Lab members | Mất 15-20 phút mò mẫm/lần tìm. |
| 6 | Pain từ người khác | Giáo sư khó chịu vì báo cáo tuần cập nhật thiếu các bài báo "State-of-the-art" vừa xuất bản. | Giáo sư, Hoàng | Hay bị nhắc nhở trong cuộc họp. |
| 7 | Pain từ người khác | Các bạn trong lab phải chờ Hoàng rảnh để xin link dataset vì note cá nhân quá lộn xộn. | Lab members | Hỏi đi hỏi lại 2-3 lần. |
| 8 | Tốn thời gian | Hàng tuần, Hoàng phải video call với bạn gái 3 lần, mỗi lần 3 tiếng nghe bạn gái than thở về cuộc sống, dramma, chuyện thường ngày| Hoàng | 3 tiếng mỗi ngày, 9 tiếng mỗi tuần. |
| 9 | | | | |
| 10 | | | | |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: "tôi đang học một khóa về products management. Dựa vào thông tin, bối cảnh mà tôi cung cấp. Hãy tạo mới một nhân vật ví dụ về nghiên cứu sinh đang gặp các vấn đề liên quan đến các nhiệm vụ Lặp lại mỗi tuần,  Tốn thời gian ,  AI có thể tốt hơn, Pain từ người khác. đây là một nhân vật giả tưởng để làm mẫu cho bài tập: Nhân vật ví dụ: Minh..."
- Ý dùng được: từ ý 1-->7
- Ý bỏ vì không phải pain thật: 0 vì prompt quá kĩ, AI dựa trên lịch sử chat để cá nhân hóa nên ý tưởng rất sát thực tiễn.

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Weekly Literature Review & Benchmarking | Workflow lặp lại hàng tuần rõ ràng, tốn 3–4 tiếng, bottleneck cụ thể ở khâu đọc PDF trích xuất thông số, metric thời gian đo lường rất sắc nét. | AI đề xuất nguồn chưa được kiểm chứng. Task phức tạp, AI bị quên, hallucination, hoặc sai hoàn toàn với kỳ vọng. |
| 2 | Tự động trích dẫn & chuẩn hóa Citation (IEEE/APA/BibTeX) | thủ công lặp lại nhiều lần, bottleneck ở việc tìm kiếm metadata chuẩn xác và sửa lỗi cú pháp thủ công. | Mức độ impact tổng thể có thể nhỏ hơn so với việc tổng hợp bài báo hàng tuần. |
| 3 | Dataset Curation & Document Indexing (Tìm kiếm dataset/code nội bộ lab) | Pain point ảnh hưởng trực tiếp đến các thành viên khác trong lab (pain từ người khác), workflow hiện tại lộn xộn. | Phân quyền truy cập dữ liệu và định dạng dataset đa dạng khiến việc thiết lập agent tổng quát hóa cần scoping kỹ. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Weekly Literature Review & Benchmarking]

```text
Problem 1 câu: Mỗi tuần phải mở đọc lướt hàng chục PDF để trích xuất thủ công các chỉ số (Dataset, SOTA Metric, Model Architecture) vào Sheets báo cáo Lab.

Actor:  Hoàng (NCS), Giáo sư hướng dẫn, Lab members.  

Thời điểm / bối cảnh: Chiều thứ Sáu hàng tuần khi chuẩn bị tài liệu tổng hợp và slide báo cáo tiến độ cho buổi Weekly Lab Meeting.

Current workflow 3-7 bước:
1. Tìm kiếm từ khóa theo đề tài trên ArXiv/IEEE.
2. Tải 10–15 file PDF bài báo mới về máy.
3. Mở từng PDF, dùng Ctrl+F đọc lướt các phần Experiments/Results để tìm thông số kỹ thuật.
4. Thủ công copy-paste tên Dataset, Model Architecture, SOTA Metric (Accuracy/IoU/Dice) vào Google Sheets.
5. Soạn slide tóm tắt các điểm đáng chú ý gửi Advisor.

Bottleneck: Đọc lướt & trích xuất bảng chỉ số từ file PDF (180–240 phút/tuần).

Impact: Chiếm dụng phần lớn thời gian làm thực nghiệm/coding của nghiên cứu sinh; dễ bỏ sót thông tin quan trọng hoặc cập nhật trễ các bài báo SOTA mới khiến tiến độ nghiên cứu bị chậm.

Success metric: Giảm thời gian tổng hợp từ ~210 phút/tuần xuống dưới 30 phút/tuần; độ chính xác trích xuất thông số kỹ thuật tăng

Non-AI alternative: Sử dụng RSS Feed kết hợp script Python parse metadata cơ bản (Title, Abstract, Authors) qua API của ArXiv/Semantic Scholar và xuất thẳng ra CSV/Sheets.

AI hypothesis: Nếu sử dụng LLM Agent kết hợp OCR/PDF parsing để đọc hiểu ngữ cảnh bài báo, hệ thống có thể tự động trích xuất chính xác JSON chứa {Dataset, Model, Metric, Key Findings} từ các bảng kết quả phức tạp và điền trực tiếp vào Google Sheets.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[x] Agent
[ ] Chưa biết
```



**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 210 phút

[1. Search ArXiv/IEEE: 15'] → [2. Tải 10–15 PDF: 15'] → [3. Đọc lướt & trích xuất số liệu: 150'] → [4. Nhập Sheets & làm Slide: 30']  <-- bottleneck

FUTURE STATE — 25 phút

[1. Agent tự crawl PDF theo keyword: 0'] → [2. LLM trích xuất JSON thông số & điền Sheets: 5'] → [3. Review & duyệt số liệu: 20']  <-- human boundary

Fallback: Nếu AI trích xuất độ tin cậy thấp (Confidence Score < 80%) hoặc gặp bảng biểu quá phức tạp, hệ thống tự động bôi vàng dòng đó trên Sheets kèm link dẫn thẳng đến trang chứa kết quả trong file PDF để người dùng đối chiếu nhanh.


```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tự động trích dẫn & chuẩn hóa Citation]

```text
Problem 1 câu: Nghiên cứu sinh tốn nhiều thời gian tra cứu metadata, sửa lỗi cú pháp BibTeX và chuẩn hóa thủ công định dạng trích dẫn (IEEE/APA) khi viết bài báo khoa học.


Actor: Nghiên cứu sinh (Hoàng), Co-authors (đồng tác giả bài báo).


Thời điểm / bối cảnh: Mỗi khi viết bản thảo bài báo khoa học, hoàn thiện phần Literature Review, hoặc chuẩn bị nộp bài hội nghị/tạp chí định kỳ.


Current workflow 3-7 bước:
1. Đang viết bản thảo cần trích dẫn, mở trình duyệt tìm tên bài báo trên Google Scholar hoặc trang nhà xuất bản.
2. Sao chép đoạn text trích dẫn thô hoặc file BibTeX mặc định về máy.
3. Đối chiếu kiểm tra thấy thiếu thông tin chi tiết (DOI, số Volume, số trang, tên hội nghị viết tắt).
4. Mở trực tiếp paper gốc để tìm các trường thông tin còn thiếu và gõ sửa tay từng trường vào file .bib hoặc tài liệu Word/Overleaf.
5. Re-compile tài liệu LaTeX/Word để kiểm tra lỗi hiển thị và định dạng theo chuẩn IEEE/APA.

Bottleneck: Tra cứu thủ công các trường metadata bị thiếu (DOI, Volume, Pages) và gõ sửa từng dòng cú pháp BibTeX (mất 30–45 phút mỗi bản thảo).


Impact: Làm gián đoạn mạch viết bài nghiên cứu, dễ phát sinh lỗi cú pháp khiến file LaTeX không compile được hoặc bị ban biên tập/giáo sư trả lại bản thảo do trích dẫn sai quy cách.


Success metric: Thời gian chuẩn hóa và nhập trích dẫn giảm từ 30 phút xuống dưới 2 phút mỗi bản thảo; 0 lỗi compile do sai cú pháp trích dẫn.


Non-AI alternative: Sử dụng phần mềm quản lý trích dẫn truyền thống (như Zotero, Mendeley) kết hợp script Regex/API CrossRef để tự động kéo metadata từ mã DOI có sẵn.


AI hypothesis: Nếu dùng mô hình ngôn ngữ (LLM) để parse tự động các chuỗi trích dẫn thô/phi cấu trúc, hệ thống có thể nhận diện chính xác các thành phần (tác giả, năm, tên bài, hội nghị) và xuất ngay định dạng BibTeX/IEEE chuẩn chỉnh mà không cần người dùng chỉnh sửa tay.


Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 30–45 phút

[1. Tìm paper & copy text thô] → [2. Mở file paper gốc tìm DOI/Volume thiếu] → [3. Gõ sửa tay cú pháp .bib & Overleaf]  <-- bottleneck

FUTURE STATE — 2 phút

[1. Dán link / title / raw text] → [2. Workflow/LLM parse & fetch metadata chuẩn] → [3. Review nhanh & copy 1-click]  <-- human boundary

Fallback: Nếu paper không tìm thấy DOI/metadata chuẩn hoặc định dạng quá dị biệt, hệ thống giữ nguyên text thô và gắn cờ cảnh báo [Needs Manual Review] để người dùng sửa tay.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Dataset Curation & Document Indexing]

```text
Problem 1 câu:
Thành viên trong lab mất nhiều thời gian hỏi đi hỏi lại và mò mẫm tìm đường dẫn dataset, thông số tiền xử lý dữ liệu và source code nội bộ do tài liệu lưu trữ phân tán.

Actor:
Nghiên cứu sinh phụ trách dữ liệu (Hoàng), Lab members, Thành viên mới (Newcomers).

Thời điểm / bối cảnh:
Khi bắt đầu một đề tài/project mới, khi cần tái lập thực nghiệm (reproduce experiments), hoặc khi lab tiếp nhận sinh viên/nghiên cứu sinh mới.

Current workflow 3-7 bước:
1. Thành viên cần dataset/code mẫu để chạy thực nghiệm.
2. Tìm kiếm thủ công trên Google Drive hoặc cluster server nhưng không thấy do cấu trúc thư mục lộn xộn, thiếu quy ước.
3. Nhắn tin hỏi trên nhóm chat (Slack/Zalo/Discord) hoặc hỏi trực tiếp Hoàng.
4. Hoàng phải dừng việc đang làm, tìm lại đường dẫn file trên server/drive cá nhân và nhớ lại cách xử lý.
5. Hoàng soạn tin nhắn trả lời kèm link, thông số và lưu ý sử dụng.

Bottleneck:
Thành viên phải chờ đợi người phụ trách tìm lại tài nguyên, và Hoàng bị gián đoạn công việc để trả lời các câu hỏi lặp đi lặp lại (15–60 phút mỗi lần phát sinh).

Impact:
Gây context switching liên tục cho người cũ, làm chậm tiến độ onboarding thành viên mới, tăng nguy cơ sử dụng sai phiên bản dataset hoặc sai tiền xử lý dẫn đến kết quả thực nghiệm không chuẩn.

Success metric:
Thời gian tìm đúng dataset/code giảm từ 30 phút xuống dưới 1 phút; giảm 80% số tin nhắn hỏi đáp lặp lại trên kênh chat nội bộ.

Non-AI alternative:
Xây dựng tài liệu hướng dẫn cố định (Wiki/Notion page) và quy chuẩn hóa cấu trúc đặt tên thư mục trên server để mọi người tự tra cứu theo mục lục.

AI hypothesis:
Nếu triển khai một hệ thống hỏi đáp RAG (Retrieval-Augmented Generation) kết nối với kho tài liệu/code nội bộ, thành viên có thể đặt câu hỏi bằng ngôn ngữ tự nhiên và nhận ngay đường dẫn chính xác cùng đoạn code tiền xử lý tương ứng chỉ sau vài giây.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 30–60 phút

[1. Tự tìm trên Drive/Server thất bại] → [2. Nhắn tin hỏi lab & chờ người trả lời] → [3. Người phụ trách mò link & gõ hướng dẫn thủ công]  <-- bottleneck

FUTURE STATE — 1–2 phút

[1. Gõ câu hỏi tự nhiên vào Internal Lab Bot] → [2. RAG Workflow truy vấn & trích xuất đúng link/code] → [3. User kiểm tra nhanh & truy cập tài nguyên]  <-- human boundary

Fallback: Nếu hệ thống không tìm thấy tài liệu liên quan với độ tin cậy cao, bot tự động tag người phụ trách dataset kèm câu hỏi để hỗ trợ thủ công và gợi ý cập nhật tài liệu đó vào kho tri thức.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
tôi muốn pitch Weekly Literature Review & Benchmarking. đây là một trong những vấn đề gây nhức nhối khi làm nghiên cứu khoa học. phải đọc lướt qua rất nhiều report, paper, tìm các paper mới, đã được kiểm chứng từ các nguồn như ResearchGate, Springer...


```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow tổng hợp báo cáo paper lặp lại cố định mỗi chiều thứ Sáu nhưng ngốn tới 210 phút chỉ vì phải mở từng PDF đọc lướt bảng kết quả thủ công. 
Giải pháp: cắt giảm hơn 85% th.gian --> 25 phút, loại bỏ hoàn toàn nút thắt trích xuất dữ liệu. 
Impact, giảm  3-4 tiếng nghiên cứu thực nghiệm mỗi tuần và đảm bảo lab luôn nắm bắt kịp thời các công trình SOTA mới nhất mà không sợ sót bài.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Làm thế nào để Agent xử lý và trích xuất chính xác số liệu từ các bảng benchmark phức tạp (nhiều hàng cột lồng nhau, định dạng ảnh/scan trong PDF) mà không bị hallucinate (bịa số)?
2. Chi phí API và độ phức tạp khi xây dựng một pipeline Agent tự động cào và parse hàng chục paper mỗi tuần có thực sự tối ưu hơn so với việc dùng workflow bán tự động (Rule + script API)?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Điểm yếu AI chỉ ra: Rủi ro ảo giác (hallucination) của LLM khi đọc các bảng biểu kỹ thuật dày đặc và nguy cơ người dùng tin tưởng hoàn toàn vào dữ liệu trích xuất mà không kiểm chứng.
- Tôi sửa gì: thêm fallback, confident score <70%> - đây là con số tương đối, tạo deep-link dẫn thẳng tới số trang/bảng gốc trong PDF, và  Human Review ở bước cuối cùng.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
