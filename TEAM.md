# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: Nhom11 (Lớp K5 · L3B)
- Candidate problem nhóm chọn (1 câu): Tính toán và phân bổ chi phí sinh hoạt phòng trọ hàng tháng từ ảnh chụp hóa đơn dịch vụ và tin nhắn chi tiêu chung.
- Quyết định cuối (Go / Not Yet / No-Go): Go (Pilot phạm vi nhỏ)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Duy Hưng | 2A202604110 | Người phản biện chính, phân tích quy trình, đối soát rubric | Hungnd1208 |
| 2 | Nguyễn Văn Lâm | 2A202604115 | Nhóm trưởng, điều phối thảo luận, chủ sở hữu candidate problem | lam2121 |
| 3 | Đặng Nguyễn Nhật Minh | 2A202604118 | Thư ký ghi chép, phụ trách nghiên cứu giải pháp và kiểm chứng giả định | MN-HD |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Nguyễn Văn Lâm | Nguyễn Duy Hưng, Đặng Nguyễn Nhật Minh | Bảng pitch, cluster, cây OST, bảng chấm điểm shortlist |
| CP4 — Kiểm chứng | Đặng Nguyễn Nhật Minh | Nguyễn Văn Lâm, Nguyễn Duy Hưng | Assumption map, interview snapshots, kết quả khảo sát |
| CP4 — Research | Đặng Nguyễn Nhật Minh | Nguyễn Duy Hưng | Bảng research 3 giải pháp kèm link kiểm chứng |
| CP5 — Quy trình trước/sau | Nguyễn Duy Hưng | Nguyễn Văn Lâm | Sơ đồ quy trình Hiện tại & Tương lai, bảng Before/After |
| CP5 — Problem Statement v0 | Nguyễn Duy Hưng | Nguyễn Văn Lâm, Đặng Nguyễn Nhật Minh | Bản mô tả bài toán Problem Statement v0 (6 trường) |
| CP6 — Mức can thiệp + Problem Statement v1 | Nguyễn Văn Lâm | Nguyễn Duy Hưng | Ma trận Mơ hồ x Phức tạp, AI Canvas, Eval criteria, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm | Cả nhóm | Đánh giá 4 rủi ro lớn, Quyết định Go/Not Yet/No-Go & Ngưỡng dừng |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenDuyHung-2A202604110

**Phần việc phụ trách:**

- Đóng vai trò phản biện chính trong CP3 (đặt câu hỏi thách thức cho bài toán của Lâm và Minh).
- Tham gia xây dựng Cluster C và đồng xây dựng cây OST nhóm.
- Đóng góp shortlist chấm điểm và cùng nhóm thống nhất lựa chọn candidate bài toán chi phí phòng trọ.
- Phụ trách chính phân tích và xây dựng Sơ đồ quy trình trước/sau (CP5) và soạn thảo Problem Statement v0 (CP5).
- Đồng hỗ trợ phân tích mức can thiệp AI và thiết lập ngưỡng dừng đo lường được (CP6).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp 3 candidate từ báo cáo cá nhân vào bảng Pitch nhóm.
- Đặt câu hỏi phản biện sắc bén về OCR hóa đơn viết tay cho Lâm và câu hỏi về tính khả thi kiểm chứng cho Minh.
- Cùng nhóm xây dựng cây OST rút gọn và gạch bỏ các giải pháp công nghệ trá hình.
- Phân tích chi tiết quy trình Hiện tại & Tương lai, thiết kế 2 sơ đồ quy trình trực quan (Hiện tại và Tương lai) cùng bảng Before/After so sánh 5 chỉ số và cơ chế Fallback (quay về sửa tay trong 3 phút khi OCR đọc sai).
- Soạn thảo bản mô tả bài toán Problem Statement v0 đủ 6 trường dữ liệu chuẩn Lean UX.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Bảng Pitch mục 2.1, Cây OST mục 2.3 và Bảng chấm điểm mục 2.4 trong `group_report.md`.
- Toàn bộ Mục 4 (Quy trình trước/sau) và Mục 5 (Problem Statement v0) trong `group_report.md`.
- Hai file hình ảnh sơ đồ quy trình thực tế trong thư mục `report/assets/`:
  - `report/assets/cp5-workflow-present.png` (Sơ đồ quy trình hiện tại - 6 bước thủ công, bottleneck 30 phút)
  - `report/assets/cp5-workflow-future.png` (Sơ đồ quy trình tương lai - kết hợp AI Vision, Rule Engine và chốt chặn Human-in-the-loop)

**Điều mình học được từ phần nhóm:**

- Nhận ra rằng bài toán hay trên lý thuyết chưa chắc đã là bài toán phù hợp cho dự án nếu không thể tiếp cận người thật để kiểm chứng (The Mom Test). Việc chọn một vấn đề đời sống sinh viên tuy giản dị nhưng có dữ liệu thật và đo lường được giá trị hơn nhiều so với một đề tài vĩ mô mà phải đi bịa số liệu.
- Khi vẽ quy trình tương lai cho hệ thống có AI, việc thiết lập rõ ranh giới Boundary và phương án Fallback khi AI đọc sai quan trọng không kém gì việc chọn mô hình AI.

### NguyenVanLam-2A202604115

**Phần việc phụ trách:**

- Nhóm trưởng, chủ trì buổi pitch và thảo luận hội tụ CP3.
- Trình bày (pitch) Candidate #4 về tính toán và phân bổ chi phí phòng trọ.
- Tổng hợp phân loại Cluster B và bảng chấm điểm 7 tiêu chí.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch chi tiết Problem Card #1 về chi phí phòng trọ, làm rõ bottleneck cấn trừ chi tiêu lắt nhắt (30').
- Trả lời và tiếp thu phản biện của Hưng về rủi ro OCR hóa đơn viết tay, xác lập boundary Human-in-the-loop.
- Điều phối chấm điểm shortlist và chốt candidate chính thức của nhóm.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Mục 2.1 dòng 4, 5, 6; Mục 2.4 mục Candidate được chọn và Lý do chọn trong `group_report.md`.
- `report/assets/cp4-survey-result-1.png.` đến `cp4-survey-result-5.png.` (Bộ 5 ảnh chụp màn hình biểu đồ kết quả khảo sát 22 sinh viên từ Google Forms) trong `report/assets/`.
- **Commit:**
  - Commit `d758790`: Thêm bộ 5 ảnh chụp màn hình kết quả khảo sát Google Forms (`add survey result`).
  - Commit `240eb39` & `5a264f3`: Cập nhật hoàn thiện báo cáo cá nhân (`update final report`).
  - Commit `ed71d47`: Merge pull request của Lâm vào nhánh main (`Merge pull request #1 from lam2121/lam`).
  - Commit `b200d7a`: Cập nhật thông tin học viên và cấu trúc báo cáo (`Update student name and email in report`).
  - Commit `60aa072` & `a5873ed`: Cùng nhóm rà soát, hoàn thiện và đồng thuận toàn bộ nội dung Báo cáo nhóm (`group_report.md`).

**Điều mình học được từ phần nhóm:**

- Lắng nghe phản biện giúp nhận ra lỗ hổng lớn về công nghệ: không nên phó mặc hoàn toàn cho AI tự gửi tin nhắn chia tiền vì nếu sai lệch vài chục nghìn sẽ gây mất đoàn kết nội bộ phòng trọ.

### DangNguyenNhatMinh-2A202604118

**Phần việc phụ trách:**

- Pitch 3 candidate thuộc mảng Product/Software Development.
- Thư ký ghi chép các ý kiến phản biện và tổng hợp các câu hỏi chất vấn trong nhóm.
- Tham gia xây dựng cây OST và đối chiếu rủi ro kiểm chứng.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đóng góp 3 candidate (Tổng hợp feedback PRD, Bot giải đáp spec cho Dev, Phân tích đối thủ) vào bảng Pitch mục 2.1.
- Đặt câu hỏi chất vấn Hưng về chất lượng âm thanh tiếng Việt khi làm biên bản họp.
- Thẳng thắn thừa nhận hạn chế về khả năng phỏng vấn người dùng/PM doanh nghiệp tại hiện trường và đồng thuận chuyển hướng sang bài toán chi phí phòng trọ.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Dòng 7, 8, 9 bảng Pitch mục 2.1 và phần Xử lý bất đồng mục 2.4 trong `group_report.md`.

**Điều mình học được từ phần nhóm:**

- Học được cách buông bỏ "giải pháp nghe ngầu" (tổng hợp feedback PRD doanh nghiệp) để hướng tới "bài toán có bằng chứng thật và kiểm chứng được" (chi phí phòng trọ).
