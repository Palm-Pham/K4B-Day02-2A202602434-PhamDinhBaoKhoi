# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Pham Dinh Bao Khoi
- Mã học viên: 2A202602434
- Nhóm: Capitalism
- Candidate problem nhóm chọn: Mọi người nhận nhiều tin nhắn và thông báo từ các hội nhóm nhưng khó xác định thông tin nào quan trọng và cần hành động, dẫn đến dễ bỏ sót deadline, lịch học hoặc các thay đổi quan trọng.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Liệt kê 3 pain point thực tế về quản lý thời gian cá nhân và khảo sát nhanh 5 sinh viên cùng khóa về tiêu chí họ dùng khi chọn bài tập để làm trước (deadline, điểm số môn học, độ khó, tâm lý ngại bắt đầu). |Cung cấp 3 dữ liệu thô định lượng (e.g., 80% sinh viên bị tê liệt quyết định khi có trên 3 deadline cùng tuần) làm đầu vào cho buổi gom ý tưởng.|
| Pitch Problem Card | Trình bày Problem Card: "Sinh viên quá tải vì thiếu framework tính toán thứ tự ưu tiên bài tập đa biến số (deadline, độ khó, thời lượng ước tính)". | Nhóm thống nhất đưa bài toán vào danh sách xem xét chính vì phạm vi rõ ràng và giải quyết được pain point có tần suất cao.|
| Challenge bài của bạn khác | Đặt câu hỏi phản biện cho đề xuất "Dùng AI cá nhân hóa toàn bộ lịch học": chỉ ra rủi ro over-engineering, chi phí xây dựng cao và thiếu dữ liệu đầu vào chuẩn hóa từ phía sinh viên. | Giúp nhóm loại bỏ hướng tiếp cận dùng GenAI phức tạp không cần thiết, chuyển hướng sang giải pháp thuật toán logic/rule-based thực tế hơn. |
| Gom trùng / cluster | Phân loại 8 problem cards thành 2 cụm chính: (1) Nhắc nhở deadline, (2) Chia nhỏ nhiệm vụ | Cấu trúc hóa bảng ý tưởng trực quan, giúp nhóm thấy rõ phần lớn vấn đề thực chất nằm ở khâu "ra quyết định ưu tiên" chứ không phải thiếu app nhắc việc. |
| Chọn candidate problem | Áp dụng ma trận định lượng Impact vs. Feasibility để chấm điểm 3 cụm bài toán; phân tích trade-off giữa độ phức tạp kỹ thuật và giá trị mang lại ngay cho người dùng. | Nhóm đạt đồng thuận 100% chọn bài toán của Phạm Thị Thùy Linh làm Candidate Problem đại diện cho nhóm. |
| Validation / research | So sánh các framework ưu tiên phổ biến (Eisenhower Matrix, RICE, WSJF) và phỏng vấn sâu 3 sinh viên về hành vi thực tế khi xử lý 3 task gần hạn cùng lúc. | Xác định 3 biến số cốt lõi tác động mạnh nhất đến quyết định thực tế: Thời gian còn lại ($T$), Trọng số môn học/điểm ($W$), và Thời lượng thực tế cần làm ($E$). |
| Workflow nhóm | Thiết lập bảng Notion Kanban chia rõ 4 giai đoạn làm việc (Discover, Define,Solution Logic, Pitch Prep). | Nhóm hoàn thành toàn bộ nội dung đúng tiến độ |
| Problem Statement |Chuẩn hóa lại Problem Statement theo cấu trúc User - Context - Pain Point - Impact: "Sinh viên đại học khi đối mặt với 3+ deadline/tuần không thể xác định thứ tự thực hiện tối ưu, dẫn đến trễ hạn bài quan trọng và stress kéo dài". | giúp đo lường (Success Metrics) phía sau.|
| Rule / Workflow / Agent |Xây dựng công thức tính điểm ưu tiên (Priority Score): $\text{Score} = \frac{W \times \text{Độ khó}}{\text{Thời gian còn lại}} + \text{Bonus cận hạn}$, kèm flowchart 4 bước xử lý từ lúc nhập bài tập đến khi trả ra danh sách To-Do theo thứ tự giảm dần. | Chuyển đổi bài toán trừu tượng thành logic nghiệp vụ |
| Decision |Đề xuất chốt MVP chỉ dùng Rule-based Scoring Engine kết hợp giao diện nhập liệu tối giản (Input Form + Ranked List) | công cụ này có giúp sinh viên ra quyết định nhanh hơn, đúng hơn hay ko |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
 thuyết trình, làm slide, bảo vệ ý tưởng của teamate.
Tôi là người trực tiếp thiết kế công thức tính điểm ưu tiên đa biến số (Priority Score) kết hợp thời gian còn lại, độ khó và trọng số môn học, đồng thời chuyển hóa logic này thành workflow 4 bước tự động xếp hạng bài tập cho bản MVP.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan |Không dùng vì vấn đề đơn giản, nhanh | | | |
| Problem Card |Không dùng vì mọi người thích tranh luận | | | |
| Workflow | Không dùng vì teamate đã nghĩ là trình bày ý tưởng| | | |
| Research | Không dùng vì brainstorm idea và phỏng vấn vài sinh viên xung quanh| | | |
| Problem Statement | Sinh 5 biến thể Problem Statement từ dữ liệu khảo sát và context đã chọn. | Đa dạng hóa cách hành văn | Viết câu quá dài dòng | viết ngắn lại, súc tích hơn |
| Rule / Workflow / Agent | Viết công thức toán học để tính điểm ưu tiên cho danh sách bài tập. | gần như toàn bộ phần này : làm hết | | |
| Decision | Không dùng do nhóm thích thảo luận| | | |

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
tôi thấy họ có góc nhìn đa chiều và thực tiễn. phần lớn mọi người đều mắc lỗi tư duy cơ bản về solution-first. Không thay đổi ý kiến sau khi bị challenge, sau đó tôi ủng hộ ý tưởng của bạn Linh để rút ngắn thời gian tranh luận và nhanh chóng suy nghĩ các bước tiếp theo cho Phase này.
Tôi đóng góp gì thật sự vào artifact cuối: cluster ý tưởng của bạn Linh, về cơ bản là tổng hợp, phân loại th.báo; cuối cùng, tôi làm slide và thuyết trình, bảo vệ ý tưởng của bạn Linh trước các câu hỏi của thành viên nhóm khác. Điều khó nhất khi viết Problem Statement là biến ý tưởng trừu tượng thành từ ngữ chọn lọc, súc tích. Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở: Rule / Workflow / Agent.


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
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

