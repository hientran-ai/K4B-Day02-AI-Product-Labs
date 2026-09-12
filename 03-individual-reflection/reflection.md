# 03 — Individual Reflection

> AI hỗ trợ soạn và biên tập từ phần 01–02 cùng trao đổi làm bài. Theo yêu cầu Phase 7, cá nhân cần đọc lại và diễn đạt phần phản tư bằng lời của mình, đúng trải nghiệm thực tế.

## Thông tin cá nhân

- Họ và tên: Trần Thị Thu Hiền
- Mã học viên: 2A202602737
- Nhóm: Nhóm 6 thành viên, Ngô Anh Tú phụ trách Leader / Facilitator; working concept: RecallAI.
- Vai trò: Workflow, cùng Bùi Phương Duy.
- Candidate problem nhóm chọn: Người dùng lưu quá nhiều nội dung để đọc sau nhưng khó xác định nội dung nào đáng ưu tiên, dẫn đến nhiều nội dung có giá trị bị bỏ quên và không được đọc lại — **Save & Forget**.

Tài liệu đối chiếu: [bài cá nhân phần 01](../01-individual-problem-scan/individual-report.md), [báo cáo nhóm phần 02](../02-group-problem-statement/group-report.md) và [nhật ký bằng chứng cá nhân](../01-individual-problem-scan/01-individual-problem-scan-evidence-log.md).

---

## 1. Tôi đã tham gia vào phần nào?

Đóng góp của tôi tập trung vào vấn đề từ trải nghiệm cá nhân và phần Workflow được phân công cùng Bùi Phương Duy.

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Tôi cung cấp 12 vấn đề và ba Problem Cards. Riêng Save & Forget: tôi ước tính lưu 15–20 tab/link mỗi tuần nhưng chỉ 20–30% được mở lại. | Đưa vào nhóm một candidate từ trải nghiệm cá nhân; số liệu chưa phải baseline đã đo và không cho biết link đã được đọc xong. |
| Pitch Problem Card | Tôi chuẩn bị nội dung ba bài: Save & Forget, Research Information Overload và Online Shopping Decision Overload, tương ứng #16–#18 trong báo cáo nhóm. | Có Problem Cards để trình bày vấn đề, điểm nghẽn và cách đo; bài Save & Forget trở thành candidate nhóm chọn. |
| Challenge bài của bạn khác | Góc phản biện tôi chuẩn bị là: “Nếu dùng tag, sắp xếp theo ngày và reminder đã đủ thì AI cần chứng minh thêm lợi ích gì?” Hiện chưa có ghi chép câu hỏi đã hỏi và phản hồi thực tế. | Đây là câu hỏi để kiểm tra nhu cầu dùng AI, chưa tính là một lượt challenge đã thực hiện. |
| Gom trùng / cluster | Hai candidate #16–#17 của tôi nằm trong cluster B — Saved knowledge overload; #18 thuộc cluster D — Decision/action overload theo bảng hội tụ chung. | Phân biệt được research khi đang tìm nguồn với ưu tiên nội dung sau khi đã lưu, tránh gom thành một bài toán quá rộng. |
| Chọn candidate problem | Tôi đóng góp Save & Forget từ trải nghiệm cá nhân; nhóm chấm bài này 34/35 và chọn sau khi so sánh shortlist. | Nhóm tập trung vào một điểm nghẽn: người dùng khó xác định nội dung nào đáng đọc trước sau khi lưu. |
| Validation / research | Với vai trò Workflow, tôi dùng kết quả tổng hợp của nhóm: 6/8 người được ghi nhận có pain, còn hai trường hợp lưu ít hoặc có deadline bắt buộc không thấy pain rõ. Research do Nguyễn Hải Nam và Lê Trung Kiên phụ trách. | Actor tạm được thu hẹp về người lưu nhiều nội dung không bắt buộc. Participant log và quote nguyên văn chưa có trong repo, nên đây chỉ là tín hiệu ban đầu. |
| Workflow nhóm | Theo phân công, tôi cùng Bùi Phương Duy phụ trách current/future workflow và kế hoạch pilot tracking: từ lưu → tích tụ → tự tìm/chọn sang URL + goal → Rule → AI summary/priority → người dùng review. | Mục 5.1–5.2 của phần 02 thể hiện bottleneck, bước bàn giao người–máy và fallback giữ URL/title khi AI lỗi. |
| Problem Statement | Phần Workflow chúng tôi phụ trách cung cấp đầu vào cho Writer: vị trí AI can thiệp, quyền quyết định của người dùng và phạm vi URL text công khai tiếng Việt/Anh dưới 3.000 từ. | PS v1 tách `opened` khỏi `read`, dùng target hai tuần cho pilot nhóm và giữ target bốn tuần như kế hoạch kiểm chứng cá nhân. |
| Rule / Workflow / Agent | Trong phần việc Workflow, phân biệt kiểm tra URL/trùng lặp bằng Rule với tóm tắt, đánh giá nội dung theo goal bằng AI; giữ bước người dùng review. | Luồng chính được chọn là Workflow, chưa cần Agent tự lập kế hoạch; Rule vẫn là phương án đối chứng khi pilot. |
| Decision | Tôi và Duy được phân công theo dõi workflow/pilot trong quyết định chung: dự kiến năm người, hai tuần, mỗi người 10–15 URL. | Nhóm Go cho manual validation pilot nhưng Not Yet cho build MVP/production. Pilot chưa được thực hiện. |

Ghi nhận về pitch/challenge ở trên dựa trên tài liệu chuẩn bị; việc trình bày và phản biện trực tiếp cần được cá nhân xác nhận bằng trải nghiệm thực tế.

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

Phần thể hiện rõ nhất vai trò của tôi cùng Duy là current/future workflow ở mục 5.1–5.2: đặt AI vào bước đọc lướt và đánh giá nội dung sau khi lưu, thay vì tự động hóa toàn bộ hành vi đọc. Người dùng luôn được mở link gốc, sửa hoặc bỏ gợi ý; hệ thống không tự xóa và không tự đánh dấu đã đọc.

---

## 2. Tôi đã dùng AI như thế nào?

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Hệ thống hóa vấn đề và số liệu tôi cung cấp thành bảng. | Làm rõ actor, tần suất và ảnh hưởng. | Dễ điền số liệu dù chưa có bằng chứng. | Tôi cung cấp mức 15–20 link/tuần, 20–30% mở lại; giữ nhãn ước tính, không nhận là đã đo. |
| Problem Card | Soạn và chỉnh ba cards theo nội dung được chọn. | Tách problem, bottleneck, metric và phương án không dùng AI. | Ranking tốt chưa chắc khiến người thiếu thời gian đọc nhiều hơn. | Tôi cung cấp lại nội dung candidate; cần giữ câu hỏi kiểm chứng về nguyên nhân không đọc, không mặc định là do thiếu ưu tiên. |
| Workflow | Mô tả flow trước/sau và phân vai người–máy. | Thể hiện điểm chèn AI, human review và fallback. | AI từng dùng nhầm nguồn; thời gian dự kiến trong các bảng cũng cần đối chiếu. | Tôi chỉ rõ file, yêu cầu hoàn tác và cung cấp lại báo cáo nhóm; không coi thời gian dự kiến là kết quả thử nghiệm. |
| Research | Tổng hợp validation và bảng giải pháp từ nội dung nhóm. | Liên kết tín hiệu xác nhận/phản bác với việc thu hẹp actor. | Con số 6/8 không thay thế quote; khoảng trống sản phẩm mới là nhận định cần kiểm chứng. | Tôi cung cấp đúng tài liệu nhóm; giữ nguồn “theo tổng hợp nhóm”, không thêm quote hoặc nhận mình trực tiếp phỏng vấn. |
| Problem Statement | Tổ chức PS v0/v1 theo các trường bắt buộc. | Liên kết vấn đề, workflow, metric và boundary. | Bản trước dùng lẫn `opened/read`, dễ đánh giá quá cao hiệu quả. | Tôi tách Saved-to-Reopen Rate khỏi Confirmed Read Rate; pilot nhóm dùng ngưỡng tăng 10 điểm phần trăm sau hai tuần, còn 55% sau bốn tuần là target cá nhân cần kiểm chứng. |
| Rule / Workflow / Agent | So sánh các mức tự động hóa. | Tách bước có quy tắc rõ khỏi bước cần hiểu nội dung. | Nhiều bước hoặc có reminder không có nghĩa phải dùng Agent. | Giữ lựa chọn Workflow theo báo cáo nhóm; Rule là đối chứng cần thử, không loại bỏ chỉ vì muốn dùng AI. |
| Decision | Trình bày quyết định và kế hoạch pilot. | Làm rõ bước thử nhỏ nhất, người review và điều kiện dừng. | Có pain chưa chứng minh sản phẩm hiệu quả; kế hoạch không phải kết quả. | Giữ Go-pilot, chưa Go-production; cần kiểm chứng lợi ích so với cách không dùng AI trước khi mở rộng. |

Các điểm “cần kiểm chứng” là việc còn phải làm, không phải kết quả đã được xác nhận trong lab.

---

## 3. Reflection câu hỏi mở

**Reflection — 12 câu:**

Tôi chọn Save & Forget từ thói quen ước tính lưu khoảng 15–20 tab/link mỗi tuần nhưng chỉ mở lại khoảng 20–30%, nên bài toán này có liên hệ rõ với việc học của tôi. Khi đối chiếu các candidate trong báo cáo nhóm, tôi nhận ra tìm tài liệu, đọc nhiều nguồn khi research và ưu tiên nội dung đã lưu là những điểm nghẽn khác nhau dù cùng liên quan đến thông tin. Tổng hợp nhóm ghi nhận sáu trong tám người có pain, nhưng do participant log và quote còn thiếu, tôi chỉ xem đây là tín hiệu ban đầu; hai trường hợp phản bác vẫn quan trọng vì cho thấy không phải ai lưu link cũng cần RecallAI. Bài học của tôi là cần chọn đúng người gặp vấn đề và đúng bước cần cải thiện trước khi nghĩ thêm tính năng.

Trong nhóm, tôi phụ trách Workflow cùng Bùi Phương Duy, tập trung vào luồng hiện tại, luồng đề xuất và điểm bàn giao giữa hệ thống với người dùng. Phần thể hiện rõ vai trò này là đặt AI ở bước tóm tắt và gợi ý ưu tiên sau khi lưu, còn quyết định đọc, bỏ qua hoặc sửa vẫn thuộc về người dùng. Một tình huống cụ thể khi làm bài là AI dùng nhầm nguồn báo cáo, khiến tôi phải chỉ rõ file, yêu cầu hoàn tác rồi cung cấp lại nội dung nhóm. Qua lần sửa đó, tôi thấy AI hữu ích để tổ chức và diễn đạt nhanh nhưng không thể thay tôi kiểm tra bài có đúng bối cảnh hay không.

Điểm khó nhất với tôi là metric, vì tỷ lệ mở lại 20–30% mới là ước tính cá nhân và mở link không đồng nghĩa đã thực sự đọc. Cách đo cần tách Saved-to-Reopen Rate khỏi Confirmed Read Rate trên cùng cohort và cùng khoảng thời gian; mức 55% sau bốn tuần là target cá nhân, còn pilot nhóm hai tuần chỉ kỳ vọng tăng ít nhất 10 điểm phần trăm so với baseline. Vì vậy, tôi hiểu quyết định của nhóm là Go cho pilot lấy dữ liệu nhưng Not Yet cho việc xây Agent hoặc sản phẩm hoàn chỉnh. Nếu làm lại, tôi sẽ ghi nhật ký link và nội dung pitch/challenge sớm hơn, đồng thời phản biện rõ hơn liệu AI có giúp người dùng đọc nhiều hơn so với chỉ dùng tag và reminder hay không.

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Phần 01 có 12 problems và top 3 Problem Cards.
- [ ] [12đ] Pitch + challenge trực tiếp: đã có tài liệu chuẩn bị, cần xác nhận phần thực hiện.
- [x] Nhóm có nhật ký hội tụ 18 candidates → cluster → shortlist → một candidate.
- [x] [15đ] Nhóm có workflow trước/sau, bottleneck, human review và fallback.
- [x] [20đ] Nhóm có PS v0/v1, boundary và định nghĩa tách `opened/read`; baseline thực tế vẫn cần thu trong pilot.
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent.
- [x] [10đ] Nhóm có quyết định Go-pilot, lý do và điều kiện dừng/quay về cách thủ công.
- [x] [10đ] Phần 03 đã có vai trò, bảng dùng AI và đoạn phản tư 12 câu; cá nhân cần đọc lại bằng lời của mình.
- [ ] [6đ] Tự nói lại mạch problem → workflow → metric → boundary → độ phù hợp AI trước khi xác nhận hiểu bài.

**Mạch tự giải thích:** Người lưu nhiều nội dung không bắt buộc gặp khó ở bước tìm và chọn bài → Rule xử lý URL, AI hỗ trợ summary/priority → người dùng kiểm tra và quyết định → đo riêng tỷ lệ mở lại, tỷ lệ xác nhận đã đọc và thời gian chọn → chỉ xử lý text công khai, giữ link gốc → chọn Workflow cho pilot và so sánh với cách không dùng AI trước khi quyết định build.

**Bằng chứng còn thiếu trong repo:** Hai quote phỏng vấn nguyên văn ở phần 02 và nhật ký quan sát thực tế ở phần 01. Checklist ghi nhận nội dung đã có, không tự xác nhận hoạt động hoặc kết quả chưa diễn ra.

