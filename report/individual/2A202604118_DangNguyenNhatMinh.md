# Báo cáo cá nhân — 2A202604118_DangNguyenNhatMinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Đặng Nguyễn Nhật Minh
- MSSV: 2A202604118
- Email trường (không bắt buộc, repo có thể để public): 26ai.minhdnn@vinuni.edu.vn
- Tên nhóm: 11
- Link repo nhóm: https://github.com/lam2121/K5-L3B-Day02-Nhom11-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi đến thứ Hai hàng tuần để chuẩn bị họp giao ban, tôi muốn cập nhật trạng thái của tất cả các tính năng đang phát triển một cách tự động, để không phải đi nhắn tin hỏi từng dev xem việc đã xong chưa. | Tôi (PM) và 8 lập trình viên trong đội dự án. | Mất 1.5 tiếng mỗi sáng thứ Hai, nhắn tin hỏi 8 người khác nhau trên Slack, có tuần bị trễ giờ họp 15 phút vì chờ dev trả lời. |
| 2 | Lặp lại | Khi có nhân sự mới gia nhập đội ngũ product (onboarding), tôi muốn họ tự tìm hiểu và nắm rõ quy trình làm việc tiêu chuẩn, để tôi không phải trực tiếp hướng dẫn lại những kiến thức cơ bản từ đầu. | Tôi (PM) và nhân sự mới (trung bình 1-2 người/tháng). | Phải dành 3-4 buổi họp (khoảng 6 tiếng tổng cộng) mỗi lần có người mới, lặp lại cùng một nội dung về quy trình phát triển sản phẩm. |
| 3 | Tốn thời gian | Khi đến kỳ đánh giá sprint (2 tuần/lần), tôi muốn tổng hợp nhanh tất cả các task đã hoàn thành và còn tồn đọng trên Jira, để báo cáo tiến độ cho Giám đốc mà không phải tự tay lọc và xuất file Excel thủ công. | Tôi (PM) và Giám đốc Sản phẩm (PO). | Mất từ 2.5 đến 3 tiếng mỗi chiều thứ Sáu cuối sprint để lọc, kiểm tra dữ liệu và làm slide báo cáo, có ít nhất 40 task cần kiểm tra tay. |
| 4 | Tốn thời gian | Khi có lỗi (bug) phát sinh từ khách hàng, tôi muốn phân loại và giao việc ngay cho đúng nhóm dev chịu trách nhiệm, để giảm thời gian phản hồi mà không cần phải họp bàn rà soát qua lại. | Tôi, Đội CS (Chăm sóc khách hàng) và 2 nhóm Dev. | Mỗi ngày nhận 5-7 bug từ CS, mất trung bình 30-45 phút để đọc log, xác định lỗi thuộc về backend hay frontend, kéo dài thời gian sửa lỗi. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi cần viết tài liệu yêu cầu sản phẩm (PRD) cho một tính năng lớn, tôi muốn nhanh chóng tổng hợp tất cả các ý kiến đóng góp từ khách hàng, đội sales và đội vận hành, để viết được specs chuẩn xác nhất. | Tôi (PM) và toàn bộ đội ngũ phát triển (gồm designers, devs). | Phải đọc qua hơn 30+ feedback từ 3 nguồn (Zalo, Excel, Slack) và mất 1-2 ngày để phân tích, nhiều khi bỏ sót ý kiến dẫn đến phải sửa specs 2-3 lần. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi cần nghiên cứu đối thủ cạnh tranh định kỳ hàng tháng, tôi muốn có một báo cáo tóm tắt nhanh về các tính năng mới và chương trình ưu đãi của họ, để điều chỉnh lộ trình sản phẩm mà không phải tự tải app và trải nghiệm từng cái. | Tôi, Đội Product và Đội Marketing. | Mất ít nhất 4-5 tiếng mỗi tháng để lướt 5 app đối thủ, chụp ảnh màn hình, ghi chú vào file Docs dài hơn 15 trang. |
| 7 | Pain từ người khác | Khi đội lập trình bắt tay vào code, tôi muốn họ hiểu đúng 100% thiết kế và specs mà không hỏi lại những chi tiết đã có trong tài liệu, để tránh việc làm sai phải sửa lại. | Tôi, Designers và 8 Devs. | Hơn 10 câu hỏi mỗi ngày trên Slack hỏi về UI/UX hay logic dù đã viết rõ trong PRD, khiến tôi mất 1-2 tiếng ngắt công việc để giải thích lại. |
| 8 | Pain từ người khác | Khi khách hàng phàn nàn về lỗi hệ thống trên group hỗ trợ, tôi muốn đội Chăm sóc khách hàng nắm được ngay nguyên nhân và lộ trình khắc phục, để họ tự trấn an khách mà không cần liên tục giục tôi "Khi nào xong?". | Đội CS (5 người), Tôi (PM) và Khách hàng | CS nhắn tin dồn dập 5-10 tin nhắn/giờ mỗi khi có sự cố lớn, tôi phải vừa hỗ trợ tech vừa trả lời CS, gây áp lực và làm gián đoạn việc sửa lỗi. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp Feedback khách hàng | Nút thắt tốn nhiều thời gian nhất (120 phút). Việc xử lý, phân loại và tóm tắt dữ liệu chữ không có cấu trúc (unstructured text) là thế mạnh cốt lõi của LLM. | Lượng dữ liệu thô xuất ra từ các kênh có vượt quá giới hạn ngữ cảnh (context window) của mô hình không, và rủi ro AI tự bịa (hallucinate) thêm yêu cầu. |
| 2 | Bot Giải đáp Spec tài liệu cho Dev | Giải quyết "pain từ người khác", loại bỏ hoàn toàn việc context switching gây kiệt sức cho PM. Rất khả thi khi dùng các nền tảng tạo RAG Bot như Coze/Dify. | AI có hiểu được các logic đan chéo phức tạp trong file PRD dài hay không; khả năng thay đổi thói quen chat trực tiếp với PM của Dev. |
| 3 | Báo cáo Phân tích Đối thủ định kỳ | Tiết kiệm hàng giờ lao động chân tay. Impact tốt cho tư duy chiến lược và cập nhật roadmap nhanh nhạy. | Phải setup crawler khá phức tạp nếu website/app store đối thủ chặn bot; Vision AI có thể sót các thay đổi UI ẩn (animation nhỏ). |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần viết tài liệu yêu cầu sản phẩm (PRD) cho tính năng mới, tôi muốn nhanh chóng tổng hợp tất cả ý kiến từ nhiều nguồn, để viết specs chuẩn xác mà không bỏ sót insight. |
| Actor | Product Manager |
| Thời điểm / bối cảnh | Giai đoạn Research / Chuẩn bị viết specs cho Sprint mới (khoảng 1 tháng/lần). |
| Quy trình hiện tại (3–7 bước) | Gồm 5 bước (Chi tiết xem sơ đồ bên dưới). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 - Đọc, hiểu bối cảnh và lọc bỏ các feedback trùng lặp hoặc nhiễu (mất 120 phút đọc khô mắt). |
| Impact (nếu không giải thì sao) | Mất cả ngày làm việc; dễ bỏ sót yêu cầu quan trọng của khách hàng VIP; PM bị "quá tải thông tin" dẫn đến trì hoãn viết Docs. |
| Success metric (baseline → target) | Thời gian xử lý raw data (Bước 1+2+3): 270 phút → dưới 15 phút. |
| Phương án không dùng AI | Thuê Intern gom dữ liệu thủ công; Hoặc dùng Script (Regex) để bắt các từ khóa nhất định nhưng độ chính xác rất thấp. |
| Giả thuyết về AI (nếu có) | AI vô địch trong khoản xử lý text phi cấu trúc. Có thể ném toàn bộ lịch sử chat/file Excel thô vào LLM, yêu cầu rút trích ý chính, gom nhóm theo chủ đề (UI, Payment, Performance) và đếm tần suất lặp lại. |
| Cảm nhận nhanh | AI (Ứng dụng Text Summarization & Classification) |

Quy trình nháp hiện tại:

```HIỆN TẠI — 480 phút (1 ngày làm việc)

[1 Gom text thô từ Zalo/App Store/CS: 60'] → [2 Đọc & lọc trùng lặp: 120'] ← BOTTLENECK → [3 Phân nhóm theo component: 90'] → [4 Viết dàn ý Requirements: 180'] → [5 Review với Tech Lead: 30']

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi đội lập trình bắt tay vào code, tôi muốn họ hiểu đúng 100% specs mà không hỏi lại những chi tiết đã có trong tài liệu, để tôi không bị ngắt quãng công việc. |
| Actor | Product Manager và Đội Devs |
| Thời điểm / bối cảnh | Xuyên suốt quá trình dev (nhảy tin nhắn hỏi hằng ngày). |
| Quy trình hiện tại (3–7 bước) | Gồm 4 bước (Chi tiết xem sơ đồ bên dưới). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 - PM bị ngắt việc, mở lại Doc/Figma để tìm chính xác dòng quy định logic đó (mất 10 phút/lần, lặp lại nhiều lần/ngày). |
| Impact (nếu không giải thì sao) | PM mất tập trung (context switching) tốn hàng giờ mỗi ngày; Dev phải chờ PM rảnh mới dám code tiếp. |
| Success metric (baseline → target) | Thời gian trả lời 1 câu hỏi spec: 15 phút → ngay lập tức. Tần suất PM bị hỏi lặp: >10 lần/ngày → <2 lần/ngày. |
| Phương án không dùng AI | Ép Dev tuân thủ rule tự đọc kỹ tài liệu, quy định giờ Q&A cố định 15 phút cuối ngày. |
| Giả thuyết về AI (nếu có) | Tạo AI Bot (dạng RAG) nạp sẵn toàn bộ PRD, API docs. Dev chat hỏi bot trên Slack, bot tự trích xuất chính xác quy định kèm link tham chiếu. |
| Cảm nhận nhanh | AI (RAG / Knowledge Base Bot) |

Quy trình nháp hiện tại:

```HIỆN TẠI — 15 phút (cho 1 câu hỏi)

[1 Dev chat hỏi spec trên Slack: 1'] → [2 PM ngắt việc hiện tại, mở PRD tìm thông tin: 10'] ← BOTTLENECK → [3 PM cap màn hình, chat giải thích lại: 3'] → [4 Dev xác nhận: 1']

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần nghiên cứu đối thủ định kỳ, tôi muốn có báo cáo tóm tắt nhanh tính năng mới của họ, để điều chỉnh lộ trình sản phẩm mà không phải tự tải app trải nghiệm tay. |
| Actor | Product Manager |
| Thời điểm / bối cảnh | Hàng tháng hoặc trước mỗi kỳ làm Roadmap quý. |
| Quy trình hiện tại (3–7 bước) | Gồm 5 bước (Chi tiết xem sơ đồ bên dưới). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 - Tự tải app, đăng nhập, trải nghiệm, cap màn hình và ghi chép thay đổi (mất 200 phút cho 5 app). |
| Impact (nếu không giải thì sao) | Ngốn gần 1 ngày làm việc; PM lười làm thường xuyên dẫn đến lỡ mất nhịp thị trường và tính năng trend. |
| Success metric (baseline → target) | Thời gian tổng hợp 5 đối thủ: 240 phút → dưới 20 phút. |
| Phương án không dùng AI | Theo dõi thủ công fanpage đối thủ; cử Intern làm task "mystery shopper" đi trải nghiệm viết lại. |
| Giả thuyết về AI (nếu có) | Workflow (kéo data) + AI (tóm tắt văn bản/hình ảnh) |

Quy trình nháp hiện tại:

```HIỆN TẠI — 240 phút

[1 Mở 5 app đối thủ: 10'] → [2 Tạo file Docs trắng: 5'] → [3 Trải nghiệm, cap màn hình, ghi chú thay đổi: 200'] ← BOTTLENECK → [4 Viết nhận xét & Action item: 20'] → [5 Gửi file cho team: 5']

```

### Card muốn pitch nhất

- Card số: Card #7 — Tổng hợp feedback khách hàng để viết PRD
- Vì sao: Bài toán này thể hiện đúng sức mạnh cốt lõi của LLM trong việc xử lý khối lượng lớn văn bản phi cấu trúc (unstructured text). Nó trực tiếp đánh vào điểm nghẽn tốn đến 120 phút đọc, hiểu bối cảnh, lọc nhiễu và phân nhóm dữ liệu của một Product Manager, giúp giải quyết triệt để sự "quá tải thông tin"
- Câu hỏi muốn nhóm phản biện: AI có rủi ro bị "hallucinate" (ảo giác) tự ý bịa thêm hoặc làm méo mó các yêu cầu thật của khách hàng không? Làm thế nào để nhóm tìm được tập dữ liệu khách hàng thực tế để kiểm chứng giải pháp ngay tại lớp học?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Giới hạn Context Window: Lượng text raw gom từ nhiều kênh (Zalo, App Store, CS) quá lớn có thể vượt qua giới hạn ngữ cảnh của mô hình LLM, dẫn đến bỏ sót các insight quan trọng ở giữa văn bản. | Có | Bổ sung ý tưởng tiền xử lý dữ liệu: Chia nhỏ feedback theo từng cụm tính năng (UI, Payment, Performance) trước khi đưa vào prompt để AI tóm tắt từng phần, đảm bảo không bị quá tải thông tin đầu vào. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi nghe các candidate từ Hưng và Lâm (như bài toán cấu trúc nộp lab hay chia tiền trọ), tôi học được rằng một vấn đề giá trị để làm dự án không nhất thiết phải dùng công nghệ vĩ mô. Một bài toán xuất sắc phải có tính gần gũi, tần suất lặp lại định kỳ, nút thắt (bottleneck) đo lường được bằng phút, và quan trọng nhất là phải có khả năng kiểm chứng thực tế (Feasibility) ngay lập tức với tệp người dùng sẵn có.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Trong quá trình xây dựng cây Cơ hội - Giải pháp (OST), nhóm tôi đã rơi vào bẫy "solution-first" khi đề xuất ý tưởng "Chatbot AI siêu quản gia tự động nhắn tin đòi nợ vào Zalo". Chúng tôi sớm nhận ra đây chỉ là một công nghệ trá hình chứ không phản ánh đúng nỗi đau gốc rễ (sự mệt mỏi và nhầm lẫn khi cấn trừ hóa đơn). Nhóm đã xử lý bằng cách gạch bỏ hoàn toàn nhánh đó, lùi lại một bước để tập trung phân tích đúng quy trình thu thập dữ liệu thô và tính toán.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, tôi đã đổi ý hoàn toàn ở bước chọn Candidate (CP3). Ban đầu, tôi kiên quyết bảo vệ bài toán tổng hợp feedback PRD (Card #7) vì đây là nghiệp vụ tôi tâm đắc. Nhưng khi Lâm phản biện sắc bén về việc không có tập dữ liệu khách hàng thật và rủi ro bị trừ điểm cực nặng do fake data, tôi nhận ra sự cứng nhắc của mình. Tôi đã chủ động thừa nhận hạn chế này và đồng thuận chọn bài toán Chi phí phòng trọ của Lâm để đảm bảo tiến độ và chất lượng thực chứng cho cả nhóm.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Kết quả phỏng vấn The Mom Test khiến tôi rất bất ngờ. Ban đầu tôi mặc định phòng trọ nào cũng mệt mỏi với việc chia đều tiền nhà. Tuy nhiên, dữ liệu thực tế từ Interview #5 chỉ ra rằng ở phòng 2 người thân thiết, việc chia đôi 50-50 cực kỳ nhanh (chỉ 15 phút) và họ chẳng coi đó là nỗi đau. Pain point chí mạng và gây ức chế nhất lại nằm ở việc xử lý các "khoản ngoại lệ" như người về quê đòi giảm trừ tiền nước hay cấn trừ tiền mua nước giặt. Điều này giúp nhóm điều chỉnh lại Problem Statement, thu hẹp đúng đối tượng mục tiêu là nhóm 3-5 người có phát sinh mua đồ lặt vặt.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó khăn nhất là định nghĩa trường "Boundary" (Ranh giới an toàn). Việc áp dụng AI vào lĩnh vực liên quan đến tiền bạc cực kỳ nhạy cảm. Chúng tôi phải thảo luận rất kỹ để gạch ranh giới rõ ràng: AI chỉ làm nhiệm vụ trích xuất (Extraction), tuyệt đối không được tự ý tính toán hay tự động gửi tin nhắn quyết toán vào Zalo khi Trưởng phòng chưa bấm duyệt (Human-in-the-loop) để ngăn chặn thảm họa AI báo nhầm số tiền gây xích mích bạn bè.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu làm lại, tôi sẽ thiết kế bảng hỏi survey tập trung sâu hơn vào tâm lý e ngại của những "người bị đòi tiền" thay vì chỉ hỏi người giữ quỹ. Trong quá trình làm quy trình tương lai, tôi sẽ phản biện nhóm mạnh hơn về "Cơ chế Fallback". Hiện tại nhóm cho rằng Trưởng phòng có thể sửa tay trong 1-2 phút nếu OCR đọc hóa đơn bị sai. Tôi sẽ đặt vấn đề: nếu 10 hóa đơn chủ nhà viết tay quá xấu, AI sai đến 7 cái, thì thao tác sửa tay liên tục sẽ khiến Trưởng phòng chán nản và từ bỏ hệ thống; do đó cần phải siết chặt hơn nữa các chỉ số đầu ra của mô hình Vision.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Mọi dự án công nghệ thực chất phải bắt nguồn từ một problem (nỗi đau) có thật và đủ lớn để người dùng sẵn sàng thay đổi thói quen. Bằng cách vẽ lại bản đồ quy trình hiện trạng (as-is), chúng ta sẽ xác định được điểm nghẽn (bottleneck) tốn kém nhất để tập trung giải quyết. Từ nút thắt đó, ta thiết lập các metric (chỉ số đo lường) để lượng hóa giá trị giải pháp mang lại, đảm bảo hệ thống không bị sa đà vào các tính năng vô bổ. Vì AI luôn đi kèm rủi ro sai lệch xác suất, ta bắt buộc phải giăng ra các boundary (ranh giới an toàn) và cơ chế phòng vệ để khoanh vùng tác hại. Việc đánh giá độ mơ hồ của dữ liệu đầu vào và độ phức tạp của bài toán sẽ quyết định mức can thiệp AI (No AI, Rule, Workflow hay Agent) sao cho tối ưu và an toàn nhất. Sau khi xâu chuỗi toàn bộ sự thật và bằng chứng này lại, đối chiếu với 4 rủi ro cốt lõi (Value, Usability, Feasibility, Viability), ta mới chốt được quyết định dứt khoát là Go (triển khai), Not Yet hay No-Go.

---

## 7. Tài liệu tham khảo

Design Council (UK). Framework for Innovation: The Double Diamond design process. designcouncil.org.uk
Rob Fitzpatrick. The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you. momtestbook.com
Teresa Torres. Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value. Product Talk LLC, 2021. producttalk.org/opportunity-solution-trees
David Bland & Alexander Osterwalder. Testing Business Ideas: A Field Guide for Rapid Experimentation. Wiley, 2019. strategyzer.com
Marty Cagan. Inspired: How to Create Tech Products Customers Love (Silicon Valley Product Group). svpg.com/four-big-risks
Google PAIR. People + AI Guidebook: Designing human-centered AI products. pair.withgoogle.com
Anthropic. Building Effective Agents. Research Publication, 2024. anthropic.com/research/building-effective-agents
Ajay Agrawal, Joshua Gans, Avi Goldfarb. Prediction Machines: The Simple Economics of Artificial Intelligence. Harvard Business Review Press, 2018. hbr.org
Splitwise Inc. Splitwise Platform and Debt Simplification Documentation. splitwise.com
Money Lover. Sổ thu chi và quản lý tài chính cá nhân. moneylover.vn
-
