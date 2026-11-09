# Báo cáo cá nhân — 2A202604110_NguyenDuyHung

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Duy Hưng
- MSSV: 2A202604110
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Nhom11
- Link repo nhóm: https://github.com/lam2121/K5-L3B-Day02-Nhom11-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi sắp đến hạn chót nộp bài lab môn học trên LMS (trước 23h59), tôi muốn đối chiếu nhanh toàn bộ file báo cáo và cấu trúc repo với checklist yêu cầu, để nộp đúng quy cách và không bị trừ điểm vì thiếu file bắt buộc hoặc sai quy tắc đặt tên. | Bản thân và  bạn cùng nhóm làm bài lab. | Tần suất 2 lần/tuần vào các đợt nộp bài; mất trung bình 35–45 phút/lần ngồi rà thủ công từng file và tên thư mục; từng bị trừ 10% điểm bài lab tuần trước vì đặt sai tiền tố file báo cáo cá nhân (thông báo của trợ giảng trên Discord ngày 02/11/2026). |
| 2 | Lặp lại | Khi kết thúc ngày làm việc lúc 18h, tôi muốn tổng hợp các pull request, commit và đầu việc đã hoàn thành trong ngày từ nhiều công cụ, để gửi bản cập nhật tiến độ (daily standup) cho cả nhóm mà không bỏ sót công việc đang làm dở. | 4 thành viên trong nhóm phát triển dự án. | Diễn ra 5 ngày/tuần (thứ Hai đến thứ Sáu); mất 20–25 phút mỗi ngày ngồi mở lại git log, Notion task board và lịch sử tin nhắn; 2 lần trong tháng trước bị trưởng nhóm nhắc vì quên cập nhật task đang chờ review trên GitHub. |
| 3 | Tốn thời gian | Khi cần tiếp tục triển khai một tính năng đã được bàn bạc từ tuần trước, tôi muốn tìm lại chính xác kết luận và các yêu cầu cụ thể đã chốt trong luồng chat nhóm, để làm đúng thỏa thuận mà không phải hỏi lại gây phiền cho mọi người. | Bản thân và các bạn cùng nhóm kỹ thuật. | Xảy ra 3–4 lần/tuần; mất trung bình 25–40 phút lội ngược tin nhắn trong nhóm chat Zalo/Discord với hơn 300+ tin nhắn trao đổi mỗi ngày; 1 lần làm sai luồng phải viết lại mất 3 tiếng do nhớ nhầm quyết định thảo luận miệng. |
| 4 | Tốn thời gian | Khi vừa kết thúc buổi họp nhóm kéo dài hơn 1 tiếng, tôi muốn tổng hợp nhanh danh sách công việc (action items), người phụ trách và deadline từ bản ghi chép thô, để gửi cho các thành viên xác nhận và bắt tay vào việc ngay. | Người ghi chép cuộc họp (bản thân) và cả 4 thành viên trong nhóm. | 2 cuộc họp/tuần; mất 40–50 phút sau mỗi buổi họp để đọc lại ghi chú nháp, format lại bảng task trên Notion; ghi nhận 3 lần bị thành viên khiếu nại do ghi sót deadline hoặc nhầm người nhận việc. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi một chuỗi kiểm thử tích hợp (integration tests) bị lỗi với hàng trăm dòng log và stack trace dài, tôi muốn xác định nhanh nguyên nhân gốc rễ và module gây lỗi, để sửa đúng chỗ mà không phải đọc tuần tự từng dòng log hệ thống. | Developer / sinh viên phụ trách bài tập lớn kỹ thuật (2 người). | Xảy ra 4–5 lần mỗi đợt chạy test tích hợp hoặc nộp bài CI/CD; mất từ 45 đến 60 phút mỗi lần debug tìm file và dòng mã nguồn gặp vấn đề; file log kiểm thử thường dài hơn 1.200 dòng với nhiều exception lồng nhau. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi cần tích hợp một dịch vụ thư viện hoặc SDK bên ngoài vào dự án, tôi muốn so sánh nhanh các tham số đầu vào/đầu ra và mã lỗi giữa tài liệu chính thức và các phiên bản SDK, để cấu hình gọi API chính xác mà không gặp lỗi 400 Bad Request. | Lập trình viên phụ trách module backend (bản thân). | Tần suất 1–2 lần/tháng cho mỗi dự án môn học; mất từ 2 đến 3 tiếng đọc tài liệu dài 40+ trang và các forum hỗ trợ; thường mất thêm 2–3 lần chạy thử thất bại vì thiếu tham số ẩn. |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu viết chương tổng quan tài liệu cho báo cáo nghiên cứu đồ án, tôi muốn trích xuất các phương pháp, kết quả đo lường và hạn chế của 8–10 bài báo liên quan, để lập bảng so sánh đối sánh mà không phải đọc kỹ toàn bộ từng bài từ đầu đến cuối. | Sinh viên nghiên cứu / làm đồ án môn học (3 bạn trong nhóm). | 1 lần/tháng trong kỳ học; mất 6–8 tiếng đọc lướt 10 bài báo khoa học (mỗi bài 8–12 trang tiếng Anh); mất 2 buổi để kẻ bảng so sánh mà vẫn dễ nhầm lẫn số liệu giữa các tác giả. *(Ý được mở rộng từ gợi ý AI, đã viết lại theo số liệu thật của đợt làm đồ án)* |
| 8 | Pain từ người khác | Khi có bạn mới tham gia vào nhóm làm đồ án, tôi muốn cung cấp hướng dẫn cài đặt môi trường và các bước khắc phục lỗi phổ biến theo từng hệ điều hành, để bạn tự thiết lập được máy mà không cần tôi ngồi kèm chỉ tay từng bước. | Người hướng dẫn kỹ thuật (bản thân) và thành viên mới gia nhập nhóm. | Mỗi đầu kỳ hoặc khi có bài tập nhóm mới (1–2 lần/kỳ); mất 2–3 tiếng ngồi hỗ trợ trực tiếp qua màn hình cho 2 bạn cùng nhóm vì file README cũ bị thiếu bước thiết lập biến môi trường PATH. *(Ý được mở rộng từ gợi ý AI, đã viết lại theo bối cảnh nhóm)* |
| 9 | Pain từ người khác | Khi nhận được phản hồi của bạn học hoặc người dùng thử nghiệm báo lỗi với mô tả rất mơ hồ ('bị đơ không ấn được'), tôi muốn hướng dẫn họ cung cấp đủ thông tin kỹ thuật cần thiết (trình duyệt, ảnh chụp màn hình, thao tác trước đó), để tái hiện và xử lý lỗi mà không mất thời gian chat qua lại nhiều lần. | Người phụ trách sửa lỗi sản phẩm (bản thân) và người dùng thử nghiệm. | 5–7 phản hồi mỗi đợt demo thử nghiệm đồ án; mất trung bình 30 phút trao đổi qua lại cho mỗi lỗi chỉ để lấy lại ảnh chụp màn hình console; có 3 lỗi không thể tái hiện được vì thiếu ngữ cảnh. |
| 10 | Lặp lại | Khi các thành viên trong nhóm tạo nhiều issue với tiêu đề lộn xộn trên GitHub repo, tôi muốn phân loại đúng milestone, nhãn tính chất (bug/enhancement/documentation) và người phụ trách, để buổi họp sprint nắm được chính xác tiến độ mà không mất công dọn dẹp lại backlog. | Nhóm trưởng (bản thân) và 4 thành viên trong nhóm. | 1 lần/tuần vào tối Chủ nhật; mất 45 phút duyệt qua 15–20 issue mới mở; 2 lần bị trễ tính năng quan trọng do issue bị gắn sai nhãn ưu tiên và trôi xuống đáy danh sách. *(Ý được mở rộng từ gợi ý AI, gắn với quản trị repo)* |
| 11 | Tốn thời gian | Khi hoàn thiện bản thảo báo cáo dự án trước khi in/nộp, tôi muốn phát hiện nhanh các lỗi định dạng bảng biểu, thiếu số thứ tự hình vẽ và không đồng nhất về thuật ngữ dịch, để tài liệu đạt chuẩn học thuật mà không phải đọc dò từng trang. | Người chịu trách nhiệm xuất bản tài liệu báo cáo (bản thân). | 1 lần cuối mỗi đồ án/sprint; mất 3–4 tiếng đọc rà soát file tài liệu 30+ trang Word/Markdown; từng bị giảng viên trừ 0.5 điểm bài tập lớn do trích dẫn sai số thứ tự hình vẽ ở chương 3. *(Ý được mở rộng từ gợi ý AI)* |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- **Quá trình thực hiện:** Tôi đã tự scan trước 7 vấn đề (#1 đến #6 và #9) dựa trên trải nghiệm thực tế hàng ngày khi học tập, làm bài lab và lập trình đồ án nhóm. Sau đó, tôi dùng prompt hỏi AI để mở rộng thêm góc nhìn theo 4 lăng kính về các vấn đề thường gặp trong quản lý nhóm và xử lý văn bản học thuật.
- **Ý AI gợi ý mà tôi giữ lại:**
  1. *Trích xuất so sánh tài liệu nghiên cứu (Literature Review)* (vấn đề #7): Tôi giữ lại vì đây là việc tốn rất nhiều thời gian mỗi kỳ làm bài tập lớn môn chuyên ngành, nhưng tôi đã viết lại hoàn toàn theo đúng số liệu thực tế (10 bài báo, 6–8 tiếng đọc, bảng so sánh phương pháp/kết quả).
  2. *Hỗ trợ onboarding cài đặt môi trường cho thành viên mới* (vấn đề #8): Tôi giữ lại vì đầu kỳ học nào nhóm cũng có bạn gặp lỗi biến môi trường PATH hoặc xung đột phiên bản Node/Python, làm mất 2–3 tiếng hỗ trợ thủ công.
  3. *Phân loại và gán nhãn issue/task trên GitHub backlog* (vấn đề #10): Giữ lại và gắn liền với việc quản trị repo nhóm làm đồ án, nơi các bạn hay mở issue thiếu label.
  4. *Rà soát lỗi format, hình vẽ và thuật ngữ báo cáo* (vấn đề #11): Giữ lại vì bài học từng bị trừ 0.5 điểm đồ án do lệch số thứ tự hình vẽ.
- **Ý AI gợi ý mà tôi BỎ và lý do:**
  1. *Bỏ gợi ý "Trợ lý AI tự động trả lời email cho giảng viên/khách hàng":* Vì sinh viên không có lượng email dồn dập đến mức thành điểm nghẽn; đây không phải là pain thật hàng ngày của tôi.
  2. *Bỏ gợi ý "Công cụ tự động sinh mã nguồn từ mô tả người dùng":* Đây là giải pháp trá hình (solution-first), phạm vi quá rộng, vi phạm nguyên tắc "Problem first" và không có một quy trình cụ thể với các bước đo đạc được thời gian.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Rà soát checklist và cấu trúc nộp bài lab môn học trên LMS (#1) | Actor rất rõ (sinh viên/nhóm trưởng), quy trình kiểm tra cố định, bottleneck tốn thời gian rà từng file, số liệu đo lường cụ thể, vừa sức giải quyết triệt để. | Script/Rule có thể tự động hóa bao nhiêu phần trăm trước khi thực sự cần AI can thiệp vào ngữ nghĩa nội dung? |
| 2 | Soạn thảo biên bản họp và trích xuất action items sau thảo luận nhóm (#4) | Pain phổ biến trong mọi đồ án nhóm, ảnh hưởng trực tiếp đến cam kết tiến độ và phân công công việc. | Chất lượng transcript âm thanh từ Google Meet/Discord có đủ chuẩn tiếng Việt chuyên ngành để trích xuất chính xác không? |
| 3 | Phân tích log lỗi và stack trace khi chạy test tích hợp (#5) | Tốn nhiều thời gian và gây nghẽn tiến độ của cả nhóm lập trình mỗi khi tích hợp hệ thống. | Phạm vi stack trace quá đa dạng theo từng ngôn ngữ/framework, khó chuẩn hóa trong một buổi lab nếu không giới hạn phạm vi. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi sắp đến hạn chót nộp bài lab môn học trên LMS (trước 23h59), tôi muốn đối chiếu nhanh toàn bộ file báo cáo và cấu trúc repo với checklist yêu cầu, để nộp đúng quy cách và không bị trừ điểm vì thiếu file bắt buộc hoặc sai quy tắc đặt tên. |
| Actor | Sinh viên / Nhóm trưởng bài tập thực hành môn học phụ trách kiểm tra và nộp link bài lên LMS. |
| Thời điểm / bối cảnh | 22h30–23h30 tối ngày nộp bài lab, áp lực thời gian cận kề deadline 23h59 trên hệ thống LMS. |
| Quy trình hiện tại (3–7 bước) | 1. Tải và đọc lại checklist nộp bài từ file SUBMISSION.md và thông báo của trợ giảng.<br>2. So sánh cấu trúc thư mục local với cây thư mục chuẩn (tên repo, thư mục `report/individual`, `report/team`).<br>3. Mở từng file báo cáo cá nhân và nhóm để rà soát các trường bắt buộc, kiểm tra tên file theo cú pháp MSSV_HoTen.<br>4. Kiểm tra các liên kết hình ảnh trong `report/assets/` và sơ đồ Mermaid trên giao diện GitHub xem có bị lỗi hiển thị không.<br>5. Copy link repo fork dán vào ô nộp bài trên LMS và xác nhận trạng thái nộp thành công. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Mở đọc rà soát thủ công từng file báo cáo của 4 thành viên và file nhóm để tìm xem có trường nào bị bỏ trống, template chưa điền hay sai tên file: mất trung bình 15–20 phút/lần, mắt mỏi và rất dễ bỏ sót. |
| Impact (nếu không giải thì sao) | Tốn 45 phút/lần nộp bài; mỗi tuần nộp 1–2 lần; cả lớp có khoảng 10–12 nhóm (khoảng 40–50 sinh viên) đều gặp áp lực này; tuần trước nhóm từng bị trừ 10% điểm vì để sót file mẫu `MSSV_HoTen.md` chưa xóa và một bạn đặt sai dấu gạch nối trong tên file. |
| Success metric (baseline → target) | - Tổng thời gian rà soát trước khi nộp giảm từ 45 phút xuống dưới 10 phút/lần.<br>- Tỷ lệ phát hiện lỗi cấu trúc/tên file trước khi nộp đạt 100% (không còn lần nào bị trừ điểm do lỗi format trên LMS). |
| Phương án không dùng AI | Viết một shell script (.sh hoặc .bat) hoặc GitHub Action kiểm tra sự tồn tại của file, quy tắc đặt tên file bằng Regular Expression và đếm số lượng dòng tối thiểu trong file markdown. |
| Giả thuyết về AI (nếu có) | Kết hợp Rule-based script để kiểm tra cú pháp/tên file + Workflow AI đọc lướt nội dung các mục trong file markdown để phát hiện các đoạn text placeholder chưa được thay thế (ví dụ: 'Khi...', '[dán card]', 'Chưa biết') và cảnh báo người nộp bài. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 45 phút/lần nộp bài

[1. Tải & đọc checklist SUBMISSION.md: 5']
   │
   ▼
[2. Đối chiếu cây thư mục local & GitHub: 5']
   │
   ▼
[3. Mở rà soát từng file cá nhân & nhóm: 20']  ◄── BOTTLENECK CHÍNH (dễ sót template rỗng)
   │
   ▼
[4. Kiểm tra link ảnh & render Mermaid trên GitHub: 10']
   │
   ▼
[5. Copy link & submit lên LMS: 5']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi vừa kết thúc buổi họp nhóm kéo dài hơn 1 tiếng, tôi muốn tổng hợp nhanh danh sách công việc (action items), người phụ trách và deadline từ bản ghi chép thô, để gửi cho các thành viên xác nhận và bắt tay vào việc ngay. |
| Actor | Thư ký cuộc họp / Thành viên chịu trách nhiệm ghi biên bản họp nhóm (luân phiên giữa 4 người). |
| Thời điểm / bối cảnh | Ngay sau buổi họp nhóm đồ án kéo dài 60–90 phút trên Google Meet hoặc Discord (thường vào tối thứ Ba và thứ Năm). |
| Quy trình hiện tại (3–7 bước) | 1. Mở lại bản ghi chép nháp trong lúc họp trên Notion/Google Docs.<br>2. Nghe lại một số đoạn ghi âm cuộc họp ở những phần tranh luận kéo dài để xác định kết luận chốt.<br>3. Tóm tắt các quyết định chính và lập bảng Action Items (công việc, người chịu trách nhiệm, thời hạn).<br>4. Định dạng lại văn bản thành biên bản họp chuẩn.<br>5. Gửi đường link vào nhóm Zalo/Discord để các thành viên xác nhận. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2 — Nghe lại các đoạn thảo luận tranh cãi để xác nhận xem cuối cùng ai nhận việc gì và deadline ngày nào: mất 15–20 phút/buổi họp vì phải tua lại nhiều mốc thời gian. |
| Impact (nếu không giải thì sao) | Tốn 50 phút sau mỗi buổi họp; tần suất 2 buổi/tuần (tổng cộng 100 phút/tuần); từng xảy ra 3 lần thành viên hiểu nhầm deadline hoặc quên task dẫn đến chậm tiến độ sprint. |
| Success metric (baseline → target) | - Thời gian hoàn thiện và gửi biên bản họp giảm từ 50 phút xuống dưới 15 phút sau cuộc họp.<br>- 100% action items sau cuộc họp có người phụ trách và deadline rõ ràng được xác nhận trong vòng 24 giờ. |
| Phương án không dùng AI | Sử dụng template Notion cố định có sẵn bảng checklist; nhóm trưởng dành 5 phút cuối buổi họp tổng kết miệng từng task để thư ký gõ trực tiếp vào bảng mà không cần nghe lại ghi âm. |
| Giả thuyết về AI (nếu có) | AI nhận bản transcript tự động từ công cụ họp, trích xuất các câu có hàm ý giao việc/quyết định và tự động điền vào bảng Action Items; thư ký chỉ cần 5 phút duyệt lại trước khi gửi. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 50 phút/buổi họp

[1. Đọc lại ghi chép thô: 5']
   │
   ▼
[2. Nghe lại đoạn tranh luận trong file ghi âm: 20']  ◄── BOTTLENECK CHÍNH (phải tua tìm mốc thời gian)
   │
   ▼
[3. Trích xuất Action Items & deadline: 15']
   │
   ▼
[4. Format lại bảng task trên Notion: 5']
   │
   ▼
[5. Gửi link vào chat nhóm xác nhận: 5']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi một chuỗi kiểm thử tích hợp (integration tests) bị lỗi với hàng trăm dòng log và stack trace dài, tôi muốn xác định nhanh nguyên nhân gốc rễ và module gây lỗi, để sửa đúng chỗ mà không phải đọc tuần tự từng dòng log hệ thống. |
| Actor | Lập trình viên / Sinh viên phụ trách kiểm thử mã nguồn dự án. |
| Thời điểm / bối cảnh | Khi chạy kiểm thử cục bộ trước khi push code hoặc khi pipeline CI/CD trên GitHub Actions báo đỏ. |
| Quy trình hiện tại (3–7 bước) | 1. Đọc thông báo lỗi tóm tắt trên terminal hoặc console của GitHub Actions.<br>2. Tải hoặc cuộn màn hình tìm kiếm qua hơn 1.000 dòng log để định vị khối exception đầu tiên.<br>3. Đọc stack trace để xác định file mã nguồn của dự án và dòng lệnh phát sinh lỗi.<br>4. Tra cứu thông báo lỗi trên Google, StackOverflow hoặc tài liệu framework.<br>5. Mở file mã nguồn nghi vấn, kiểm tra logic và sửa đổi mã nguồn.<br>6. Chạy lại test suite để kiểm chứng kết quả. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 — Đọc stack trace lồng nhau qua hàng chục tầng thư viện bên thứ ba để tìm ra chính xác dòng code do nhóm viết gây ra lỗi: mất 15–20 phút mỗi lần. |
| Impact (nếu không giải thì sao) | Xảy ra 4–5 lần mỗi đợt chạy test tích hợp; mỗi lần debug tốn 60 phút; cả nhóm bị tắc nghẽn merge code vì pipeline CI bị chặn. |
| Success metric (baseline → target) | - Thời gian xác định vị trí dòng mã lỗi giảm từ 60 phút xuống dưới 20 phút/lần.<br>- Tỷ lệ khoanh vùng đúng module/file gây lỗi ngay trong lần phân tích đầu tiên đạt $\ge 80\%$. |
| Phương án không dùng AI | Cấu hình bộ lọc (filter) của trình ghi log (logger) để ẩn toàn bộ stack trace từ `node_modules` hoặc thư viện hệ thống, chỉ hiển thị dòng log thuộc source code nội bộ. |
| Giả thuyết về AI (nếu có) | AI nhận log lỗi kèm các commit diff gần nhất, phân tích và chỉ ra nghi can dòng code gây lỗi kèm gợi ý đoạn code sửa đổi; lập trình viên review và xác nhận. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — Tổng thời gian: 60 phút/lần debug

[1. Xem thông báo lỗi tóm tắt: 5']
   │
   ▼
[2. Cuộn tìm qua 1.000+ dòng log hệ thống: 10']
   │
   ▼
[3. Phân tích stack trace tìm dòng code gây lỗi: 20']  ◄── BOTTLENECK CHÍNH (lỗi lồng tầng thư viện)
   │
   ▼
[4. Tra cứu Google / StackOverflow: 10']
   │
   ▼
[5. Sửa mã nguồn nghi vấn: 10']
   │
   ▼
[6. Chạy lại test suite: 5']
```

### Card muốn pitch nhất

- Card số: **Problem Card #1 — Rà soát checklist và cấu trúc nộp bài lab môn học trên LMS**.
- Vì sao: Đây là vấn đề sát sườn, diễn ra ngay trong buổi học hôm nay và xuyên suốt cả khóa học; mọi sinh viên trong lớp đều thấm thía nỗi đau bị trừ điểm nặng vì những lỗi kỹ thuật/format ngớ ngẩn; quy trình và đầu ra có ranh giới rõ ràng, dễ đo lường thành công và vừa sức giải quyết triệt để.
- Câu hỏi muốn nhóm phản biện: *"Liệu một script kiểm tra tự động (như shell script hay GitHub Actions) đã đủ để bắt lỗi format chưa, và phần nào thực sự cần AI can thiệp (ví dụ: đánh giá ngữ nghĩa xem nội dung có bị điền tạm bợ hay bỏ trống placeholder không) mà script thông thường không làm được?"*

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| AI phản biện rằng bài toán này chỉ cần viết 1 file Python script hoặc Bash script chạy biểu thức chính quy (Regex) là giải quyết được 90%, không có lý do chính đáng để dùng AI. | Đồng ý một phần | Tôi đã phân định rõ ranh giới: Script/Rule sẽ phụ trách kiểm tra tên file, số lượng dòng, cây thư mục; còn AI chỉ can thiệp ở bước phân tích ngữ nghĩa nội dung (kiểm tra xem sinh viên có điền nội dung thật hay chỉ copy nguyên template/placeholder như 'Khi...', 'Job Story'). |
| AI cho rằng baseline 45 phút/lần là bị thổi phồng, thường sinh viên chỉ mất 5–10 phút kiểm tra trước khi nộp. | Không đồng ý | Tôi giữ nguyên con số 45 phút và bổ sung bằng chứng: với bài lab nhóm gồm 1 báo cáo chung và 4 báo cáo cá nhân với rất nhiều bảng biểu và link hình ảnh, việc trưởng nhóm mở từng file trên GitHub để đối chiếu từng tiêu chí rubric tuần trước đã ngốn chính xác 42 phút. |
| AI chỉ ra rằng success metric 'tỷ lệ lỗi format giảm về 0%' là phi thực tế vì sinh viên có thể commit nhầm sát giờ mà không chạy kiểm tra. | Đồng ý | Tôi đã điều chỉnh lại metric: 'Giảm thời gian rà soát từ 45 phút xuống dưới 10 phút/lần, phát hiện 100% lỗi cấu trúc/tên file trước khi nộp, và không có lần nào bị trừ điểm do lỗi format trên LMS'. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch chi tiết Problem Card #1 (Rà soát nộp bài lab LMS) và tóm tắt Card #2, #3. | Đưa bài toán nộp lab vào danh sách shortlist 3 candidate của nhóm. |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt:<br>1. Cho Lâm (bài chi phí phòng trọ): *"Hóa đơn điện nước chủ trọ thường viết tay nguệch ngoạc hoặc chụp ảnh mờ, OCR/Vision có đọc chuẩn được số không hay vẫn phải nhập tay?"*<br>2. Cho Minh (bài bot giải đáp spec cho Dev): *"AI có hiểu được các logic đan chéo phức tạp trong file PRD dài không, và Dev có chịu thay đổi thói quen chat trực tiếp với PM sang hỏi bot không?"* | 1. Giúp Lâm xác lập boundary bắt buộc phải có bước Human-in-the-loop để đối soát trước khi gửi tin nhắn cho phòng.<br>2. Giúp nhóm và Minh nhận ra rủi ro khó thay đổi hành vi người dùng và không thể kiểm chứng người thật tại hiện trường lớp học. |
| Nhận phản biện | Câu hỏi tôi nhận được từ Lâm: *"Tại sao không viết một shell script hoặc dùng Regex kiểm tra cấu trúc thư mục và tên file là xong, phần nào thực sự cần AI?"* | Tôi đã sửa gì: Tôi thừa nhận rằng việc kiểm tra tên file và cấu trúc chỉ cần dùng Rule/Bash script; phần AI can thiệp ngữ nghĩa quá hẹp, do đó tôi đã đồng thuận chuyển hướng sang bài toán chi phí phòng trọ có không gian ứng dụng AI rõ nét hơn. |
| Gom cluster / cây OST | Cùng nhóm gom 9 candidate thành 3 cluster; xây dựng cây OST rút gọn và gạch bỏ các solution trá hình (như app trừ tiền ngân hàng tự động, chatbot quản gia đòi nợ). | Xác lập đúng 1 outcome cốt lõi và 3 opportunity (pain) thực sự, không để giải pháp công nghệ lấn át bài toán. |
| Chọn candidate problem | Cùng nhóm chấm điểm shortlist 3 candidate trên 7 tiêu chí (thang điểm 1–5). | Thống nhất tuyệt đối chọn bài toán "Tính toán và phân bổ chi phí sinh hoạt phòng trọ" với 35/35 điểm. |
| Kiểm chứng / research | Trực tiếp thực hiện 2 phỏng vấn sâu (với bạn trưởng phòng ở Cầu Giấy và bạn đại diện tầng ở Thanh Xuân); hỗ trợ tổng hợp 22 phiếu khảo sát sinh viên và phân tích khoảng trống của Splitwise/Google Sheets. | Phát hiện insight then chốt: rủi ro đọc nhầm chữ viết tay số 1 thành số 7 rất nguy hiểm, từ đó nhóm thiết lập cơ chế Human-in-the-loop đối soát trước khi gửi. |
| Quy trình nhóm | Thiết kế và vẽ sơ đồ Mermaid cho quy trình Hiện tại và Tương lai; phân định rõ bước Rule, AI, Con người; xây dựng phương án quay về (Fallback) khi AI đọc sai. | Hoàn thiện quy trình trước/sau giúp giảm thời gian từ 90 phút xuống 10–12 phút, đảm bảo an toàn vận hành 100%. |
| Problem Statement | Soạn thảo Problem Statement v0 và nâng cấp lên v1 (bổ sung AI intervention point tại bước 2, boundary ngưỡng tự tin 85% và success metric đo lường sự đồng thuận). | Bản đặc tả bài toán rõ ràng, có tiêu chí đo lường định lượng và ranh giới an toàn cho hệ thống. |
| Mức can thiệp AI | Phân tích ma trận Mơ hồ x Phức tạp, đề xuất lựa chọn mức Workflow (kết hợp AI Vision bóc tách ảnh + Rule Engine tính toán); phản biện chống lại phương án dùng Agent tự hành. | Nhóm thống nhất chọn mức Workflow tối ưu, tránh được bẫy Agent tốn kém và rủi ro ảo giác tài chính. |
| Quyết định | Cùng nhóm đánh giá 4 rủi ro lớn (Value, Usability, Feasibility, Viability); đề xuất quyết định Go thử nghiệm pilot trên 3 phòng trọ và thiết lập ngưỡng dừng đo lường được (dưới 75% độ chính xác thì dừng). | Nhóm có quyết định thống nhất cao, pilot thực tế có thể bắt đầu ngay và có ranh giới rút lui an toàn. |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Mở rộng góc nhìn theo 4 lăng kính sau khi tự scan được 7 vấn đề. | Gợi ý thêm các khía cạnh về quản trị nhóm (onboarding, issue backlog) và xử lý văn bản học thuật (literature review). | Đưa ra các ý tưởng thiên về giải pháp (solution-first như 'công cụ tự viết code', 'chatbot trả lời email') và thiếu bối cảnh cụ thể, không có số liệu đo lường hành vi thật. | Lọc bỏ các ý tưởng giải pháp viển vông; chỉ chọn các vấn đề bản thân thực sự gặp và tự viết lại 100% dưới dạng Job Story kèm số liệu đo đạc thực tế (thời gian, tần suất, kênh bằng chứng). |
| CP2 Problem Card | Đóng vai một Product Manager hoài nghi để tìm ra lỗ hổng trong Problem Card #1. | Thách thức trực diện về việc tại sao không dùng script/rule đơn giản mà phải dùng AI, và chỉ ra metric 0% lỗi là phi thực tế. | Đánh giá thấp độ phức tạp thực tế khi cho rằng việc kiểm tra bài nộp nhóm chỉ mất 5–10 phút (không tính việc mở từng file đọc rà soát nội dung). | Giữ nguyên baseline 45 phút có căn cứ thực tế; phân tách rõ ranh giới: Rule kiểm tra cú pháp/tên file, AI chỉ hỗ trợ phát hiện placeholder rỗng; sửa lại metric thực tế hơn. |
| CP4 Research | Tra cứu và tổng hợp tính năng, giới hạn của Splitwise và Spendee. | Liệt kê nhanh các tính năng sẵn có và mô hình kinh doanh của đối thủ. | AI cho rằng Splitwise đã có OCR nhận diện tốt hóa đơn, nhưng thực tế qua kiểm nghiệm thì Splitwise Pro chỉ đọc được hóa đơn in tiếng Anh chuẩn, hoàn toàn không đọc được hóa đơn viết tay tiếng Việt đặc thù. | Tự mở web/app Splitwise kiểm tra thực tế, ghi rõ khoảng trống về hóa đơn viết tay tiếng Việt và giá điện bậc thang vào bảng research. |
| CP5 Quy trình | Chuyển đổi mô tả các bước quy trình thành cú pháp sơ đồ Mermaid. | Tạo cú pháp Mermaid nhanh, phân màu trực quan cho từng khối. | Ban đầu AI vẽ luồng tự động thẳng tuột từ OCR sang gửi tin nhắn, bỏ quên bước con người duyệt (HITL) và không có phương án quay về (Fallback) khi AI đọc sai. | Tự sửa lại sơ đồ Mermaid: thêm chốt chặn Trưởng phòng duyệt song song ảnh gốc và nhánh Fallback sửa tay trong 3 phút nếu OCR đọc sai. |
| CP5–6 Problem Statement | Đóng vai phản biện để tìm lỗ hổng trong Problem Statement v0. | Đặt câu hỏi chất vấn: "Tại sao không dùng bảng tính Google Sheets miễn phí mà phải dùng AI?" | AI gợi ý viết lại Problem Statement theo hướng quảng cáo tính năng AI. | Từ chối để AI viết lại; chỉ lấy câu hỏi phản biện để củng cố lập luận: đưa dữ liệu 86.4% người dùng ngại mở Sheets để chứng minh giá trị của AI ở khâu nhập liệu. |
| CP6 Mức can thiệp / quyết định | Thảo luận về ưu nhược điểm của mức Agent so với Workflow trong bài toán tài chính. | Phân tích rõ các rủi ro của Agent (chi phí API cao, khó kiểm soát rủi ro ảo giác khi tự động chuyển tiền). | AI gợi ý một số ngưỡng dừng chung chung ("nếu người dùng không thích thì dừng"). | Viết lại ngưỡng dừng cụ thể đo lường được: độ chính xác OCR dưới 75% hoặc thời gian sửa tay quá 20 phút thì dừng pilot quay về Google Form. |

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
