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

- Nhóm trưởng điều phối thảo luận nhóm, quản lý tiến độ và kiểm soát chất lượng bàn giao bài nộp; chủ sở hữu Candidate Problem #4 được chọn.
- Phụ trách chính CP3: Chủ trì buổi pitch, phân loại Cluster B (Phân bổ tài nguyên & Quản lý sinh hoạt), điều phối chấm điểm shortlist 7 tiêu chí.
- Phối hợp thực hiện CP4: Trực tiếp thực hiện 2 phỏng vấn sâu The Mom Test (Snapshot #1 - Trưởng phòng tại Cầu Giấy và Snapshot #4 - Đại diện tầng tại Thanh Xuân); cùng Minh xử lý và phân tích dữ liệu micro-survey 22 sinh viên; xác định các sửa đổi cốt lõi của bài toán sau kiểm chứng (Mục 3.2).
- Phối hợp thực hiện CP5: Cùng Hưng phân tích quy trình tương lai, xác lập ranh giới an toàn Boundary (AI tuyệt đối không tự gửi tin hay đòi tiền) và cơ chế Fallback (sửa tay 1–2 phút).
- Phụ trách chính CP6: Xây dựng Ma trận Mơ hồ × Phức tạp (Mục 6.1), Bảng so sánh 4 mức can thiệp (Mục 6.2), AI Canvas rút gọn (Mục 6.3), Trả lời 2 câu hỏi Google PAIR (Mục 6.4).
- Phụ trách chính CP6: Hoàn thiện Bảng đặc tả Problem Statement v1 (Mục 7.1), xây dựng 4 Tiêu chí đánh giá bước AI (Mục 7.2) và giải thích sự khác biệt giữa v1 và v0 (Mục 7.3).
- Điều phối đánh giá 4 rủi ro lớn (Mục 8.1), chốt Quyết định GO Pilot phạm vi nhỏ trên 3 phòng trọ (Mục 8.2) và thiết lập Ngưỡng dừng đo lường được (Mục 8.3).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch chi tiết Problem Card #1 về chi phí phòng trọ, bảo vệ thành công bài toán với điểm số tuyệt đối 35/35 để trở thành candidate chính thức của nhóm.
- Tiếp thu phản biện của Hưng về rủi ro AI đọc sai số tiền từ hóa đơn viết tay, khởi xướng thiết lập chốt chặn an toàn Human-in-the-loop (Trưởng phòng đối soát và duyệt bảng nháp) cùng cơ chế Fallback (sửa tay nhanh trong 30 giây).
- Đóng góp 2 buổi phỏng vấn sâu chất lượng cao: Phỏng vấn #1 (Trưởng phòng 4 người tại Cầu Giấy) và Phỏng vấn #4 (Đại diện thu tiền tầng tại Thanh Xuân); cùng Minh làm rõ insight: điểm đau thực sự không nằm ở phép chia đều tiền nhà mà ở việc cấn trừ chi tiêu lắt nhắt và tính tiền nước người về quê.
- Phân tích và đưa ra 3 điều chỉnh quan trọng sau kiểm chứng: Thu hẹp đối tượng vào phòng 3–5 người (loại phòng 2 người và phòng trọn gói), thiết lập boundary nghiêm ngặt và bổ sung tính năng đính kèm ảnh gốc đối soát minh bạch.
- Xây dựng bảng đặc tả Problem Statement v1 chuẩn chỉnh với 8 trường dữ liệu; lượng hóa Success Metric đạt 100% đồng thuận trong 24 giờ và giảm thời gian quyết toán xuống dưới 12 phút.
- Hoàn thiện lập luận chọn mức can thiệp Workflow (kết hợp Vision AI bóc tách bill và Rule Engine tính toán tất định); phân tích Google PAIR chỉ ra lỗi Báo nhầm (False Positive) nguy hiểm hơn Bỏ sót.
- Thiết lập kế hoạch Pilot thực tế trên chính 3 phòng trọ của nhóm trong 2 tháng (11 & 12/2026) kèm Ngưỡng dừng (Stop threshold) cụ thể: nếu OCR đúng dưới 75% hoặc sửa tay quá 20 phút thì lập tức dừng dự án AI và quay về Google Form + Sheets.
- Trực tiếp chuẩn bị và đưa 5 ảnh biểu đồ Google Forms (`cp4-survey-result-1.png` đến `cp4-survey-result-5.png`) vào thư mục `report/assets/` chứng minh quy mô khảo sát $N=22 \ge 20$.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

 **Trong `group_report.md`:**
  - Mục 2.1 (dòng 4, 5, 6 bảng Pitch), Mục 2.2 (Cluster B), Mục 2.4 (Bảng chấm điểm shortlist và Quyết định chọn Candidate #4).
  - Mục 3.2: Interview Snapshot #1 (Trưởng phòng tại Cầu Giấy), Interview Snapshot #4 (Đại diện tầng tại Thanh Xuân), Bảng tổng hợp khảo sát 22 sinh viên và mục "Nhóm đã sửa problem thế nào sau kiểm chứng".
  - Mục 4.2 & 4.3: Thiết lập chốt chặn Human-in-the-loop, ranh giới an toàn Boundary và cơ chế Fallback trong quy trình tương lai.
  - Mục 6: Ma trận Độ mơ hồ × Độ phức tạp (Mục 6.1), Bảng so sánh 4 mức (Mục 6.2), AI Canvas rút gọn (Mục 6.3), Hai câu hỏi Google PAIR (Mục 6.4).
  - Mục 7: Bảng đặc tả Problem Statement v1 (Mục 7.1), 4 Tiêu chí đánh giá bước AI (Mục 7.2) và Phân tích khác biệt v1 vs v0 (Mục 7.3).
  - Mục 8: Đánh giá 4 rủi ro lớn (Mục 8.1), Quyết định GO Pilot (Mục 8.2), Ngưỡng dừng đo lường được (Mục 8.3) và Kế hoạch 4 bước tiếp theo (Mục 8.4).
- **Trong `report/assets/`:**
  - `report/assets/cp4-survey-result-1.png` đến `cp4-survey-result-5.png` (Bộ 5 ảnh chụp màn hình biểu đồ kết quả khảo sát 22 sinh viên từ Google Forms chứng minh $N=22 \ge 20$).
- **Commit:**
  - Commit `dca5d55` & `d758790`: Đẩy bộ 5 ảnh chụp màn hình kết quả khảo sát Google Forms dạng chuẩn `.png`.
  - Commit `b025d4b`: Cập nhật nội dung đóng góp trong `TEAM.md`.
  - Commit `240eb39` & `5a264f3`: Hoàn thiện báo cáo cá nhân `2A202604115_NguyenVanLam.md`.
  - Commit `ed71d47`: Merge pull request của Lâm vào nhánh main.
  - Commit `b200d7a`: Cập nhật thông tin học viên và cấu trúc báo cáo.
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
