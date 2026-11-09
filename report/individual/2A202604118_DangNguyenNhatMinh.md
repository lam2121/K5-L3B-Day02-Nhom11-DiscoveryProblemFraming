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
| 1 | Tự động hóa Báo cáo Sprint | Quy trình có tính chuẩn hóa cao, là bài toán hoàn hảo để kết hợp giữa Workflow (tự động kéo số liệu) và AI (đọc comment viết narrative). | Các lập trình viên có thói quen cập nhật trạng thái và viết comment lý do trễ hạn chi tiết trên Jira để AI có đủ "nguyên liệu" tổng hợp hay không. |
| 2 | Phân loại và Điều phối Bug | Tần suất xảy ra hằng ngày, điểm nghẽn rõ ràng (15 phút/bug), có thể đo lường ngay bằng tỷ lệ gán đúng người (UI vs API). Mức độ tác động lớn đến cả Dev và CS. | AI có nhận diện đúng lỗi nếu CS mô tả quá chung chung (ví dụ: "app lag") hoặc ảnh chụp màn hình log bị mờ, thiếu thông tin hay không. |
| 2 | Tổng hợp Feedback khách hàng | Nút thắt tốn nhiều thời gian nhất (120 phút). Việc xử lý, phân loại và tóm tắt dữ liệu chữ không có cấu trúc (unstructured text) là thế mạnh cốt lõi của LLM. | Lượng dữ liệu thô xuất ra từ các kênh có vượt quá giới hạn ngữ cảnh (context window) của mô hình không, và rủi ro AI tự bịa (hallucinate) thêm yêu cầu. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi đến kỳ đánh giá sprint (2 tuần/lần), tôi muốn tổng hợp nhanh tất cả các task đã hoàn thành và còn tồn đọng trên Jira, để báo cáo tiến độ cho Giám đốc mà không phải tự tay lọc và xuất file Excel thủ công. |
| Actor | Product Manager |
| Thời điểm / bối cảnh | Chiều thứ Sáu cuối mỗi sprint. |
| Quy trình hiện tại (3–7 bước) | Gồm 6 bước (Chi tiết xem sơ đồ bên dưới). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 - Viết tóm tắt tình trạng (mất 60 phút do phải tự đọc comment trong các task trễ hạn để bịa ra lý do báo cáo sếp). |
| Impact (nếu không giải thì sao) | Chiếm nửa ngày làm việc của PM cho việc "data entry", dễ sai sót số liệu, sếp nhận báo cáo trễ vào sát giờ tan làm. |
| Success metric (baseline → target) | Thời gian làm báo cáo: 165 phút → dưới 20 phút. |
| Phương án không dùng AI | Setup sẵn Jira Dashboard; Dùng Automation rule tự động xuất webhook ra Google Sheets và dùng hàm Macro để vẽ chart. |
| Giả thuyết về AI (nếu có) | AI (LLM) có thể đọc danh sách các task "Doing" bị trễ, đọc các comment trao đổi của dev trong đó để tự động tóm tắt thành văn xuôi (narrative) giải thích lý do chậm trễ. |
| Cảm nhận nhanh | Workflow (cho khâu lấy số) + AI (cho khâu viết narrative) |

Quy trình nháp hiện tại:

```HIỆN TẠI — 165 phút

[1 Xuất dữ liệu Jira: 10'] → [2 Lọc task To-do/Doing/Done trên Excel: 20'] → [3 Đối chiếu chéo file plan: 30'] → [4 Viết tóm tắt lý do trễ hạn: 60'] ← BOTTLENECK → [5 Làm slide báo cáo: 40'] → [6 Gửi sếp: 5']

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi có lỗi (bug) phát sinh từ khách hàng, tôi muốn phân loại và giao việc ngay cho đúng nhóm dev chịu trách nhiệm, để giảm thời gian phản hồi mà không cần phải tự họp bàn rà soát. |
| Actor | Product Manager / QC |
| Thời điểm / bối cảnh | Hàng ngày, bất cứ khi nào CS báo lỗi lên hệ thống. |
| Quy trình hiện tại (3–7 bước) | Gồm 5 bước (Chi tiết xem sơ đồ bên dưới). |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 - Xác định lỗi thuộc Front-end hay Back-end (mất 15 phút, lặp lại 5-7 lần/ngày). |
| Impact (nếu không giải thì sao) | Trễ SLA xử lý lỗi với khách hàng; Dev bị tag nhầm người gây ức chế và chửi thề; PM tốn thời gian làm "tổng đài viên" chuyển line. |
| Success metric (baseline → target) | Thời gian định tuyến 1 bug: 20 phút → dưới 2 phút. Tỷ lệ assign đúng Dev: > 95%. |
| Phương án không dùng AI | Ép đội CS dùng một biểu mẫu (form) cứng nhắc, nếu tích ô A thì auto-assign cho Dev B (Rule-based). |
| Giả thuyết về AI (nếu có) | Có thể dùng LLM để phân tích ngữ nghĩa tin nhắn phàn nàn của user + OCR đọc ảnh chụp màn hình để AI tự chẩn đoán đây là lỗi giao diện hay lỗi logic server, sau đó auto-assign. |
| Cảm nhận nhanh | Agent (vừa phân tích văn bản, vừa có action gán quyền) |

Quy trình nháp hiện tại:

```HIỆN TẠI — 40 phút (tính cho 1 bug)

[1 Đọc chat báo lỗi từ CS: 5'] → [2 PM tự test tái hiện lỗi: 10'] → [3 Phân tích xem lỗi UI hay API & chọn Dev: 15'] ← BOTTLENECK → [4 Lên Jira tạo ticket & assign: 5'] → [5 Phản hồi lại CS: 5']

```

### Problem Card #3

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

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

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

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
