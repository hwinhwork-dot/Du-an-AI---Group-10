# 🚀 Dự án AI: EchoMind thuộc Công ty Mindconnect Lab
_Nhóm 11 - Dự án Trí tuệ nhân tạo (UEH)_

[Brochure Dự án](https://heyzine.com/flip-book/e34e5a1cf5.html)

## 1. Tổng quan (Overview)
**EchoMind** là dự án của **MindConnect Labs** nhằm trao lại tiếng nói cho người **mất khả năng nói** (do **đột quỵ**, **ALS**, **locked-in**). Hệ thống **đọc tín hiệu não** và **chuyển thành chữ** hiển thị **gần như tức thời**, để người bệnh có thể diễn đạt nhu cầu và cảm xúc một cách đơn giản, tự nhiên.

Nhóm đã dựng xong **pipeline dữ liệu** và **mô hình nguyên mẫu** trên bộ **Brain-to-Text (Kaggle)**, chạy thử trên **Colab** để **kiểm chứng tính khả thi**. Mục tiêu gần là có bản **demo ổn định** cho thí điểm tại **khoa Thần kinh/PHCN**, từ đó **hoàn thiện quy trình** sử dụng trong bệnh viện và tại nhà.

## 2. 🌐 Trung tâm Quản lý Dự án (Project Hub)
Tất cả các hoạt động lập kế hoạch, theo dõi tiến độ và tài liệu của dự án được quản lý tại:
* [Trang Github của Nhóm](https://github.com/hwinhwork-dot/Du-an-AI---Group-11)

## 3. 👨‍💻 Đội ngũ Phát triển (The Team)

| STT | Họ và Tên | MSSV | Vai trò trong dự án | GitHub |
|:---:|:---|:---|:---|:---|
| 1 | Nguyễn Hoàng Minh | 31221021575 | Scrum Master | @hwinhwork-dot |
| 2 | Nguyễn Huyền Diệu | 31221024865 | Product Owner | @douongcocon2004-hash |
| 3 | Vũ Thị Như Quỳnh | 31221023513 | Development Team | @quynhquynhneee |
| 4 | Lương Duy Minh Kiệt| 31221023817 | Development Team | @kietueh |
| 5 | Nguyễn Lê Huy | 31221021402 | Development Team | @huyangry |
| 6 | Nguyễn Thiên Ân | 31221022348 | Development Team | @beiuthichcamhoa |
| 7 | Vương Thị Như Quỳnh| 31221021890 | Development Team | @quynhhvuong |


## 4. 🗺️ Lộ trình Phát triển Dự án (Project Roadmap)
Dự án được thực hiện theo phương pháp **Agile/Scrum** kết hợp khung quản trị **CPMAI**, chia thành 7 Sprint chính với mục tiêu cụ thể:

| Sprint | Thời gian | Mục tiêu (Objective) | Kết quả đầu ra chính (Key Deliverables) |
| :--- | :--- | :--- | :--- |
| **Sprint 0**<br>*Khởi động* | 01/10 - 15/10 | **Project Kick-off**: Chọn đề tài, lập AI Canvas v1, phân vai trò, thiết lập công cụ. | 📄 AI Canvas (v1)<br>🛠️ GitHub Repo & Setup |
| **Sprint 1**<br>*Business* | 06/10 - 15/10 | **Business Understanding**: Phân tích nghiệp vụ, xác định ROI, hoàn thiện Business Case. | 📈 Báo cáo Phân tích Kinh doanh<br>📄 AI Canvas (v2) |
| **Sprint 2&3**<br>*Planning* | 15/10 - 19/10 | **Data & Modeling Planning**: Thiết kế kiến trúc hệ thống, kế hoạch dữ liệu và Mockups. | 📐 Tài liệu Thiết kế Giải pháp<br>🖥️ Mockups UI |
| **Sprint 4**<br>*Data Pipeline* | 15/10 - 19/10 | **Data Execution**: Thực thi EDA, xây dựng bộ từ điển (Vocab) và DataLoader. | ⚙️ DataLoader & Unit Tests<br>📦 File `vocab.pt` |
| **Sprint 5**<br>*Modeling V1* | 11/10 - 24/10 | **Modeling Baseline**: Xây dựng và huấn luyện mô hình Seq2Seq (LSTM) cơ bản. | 🧠 Checkpoint Model V1<br>📉 Training Logs |
| **Sprint 6**<br>*Eval & V2* | 25/10 - 03/11 | **Evaluation & Improvement**: Đánh giá V1 (WER), phát triển Model V2 (Attention). | 📊 Báo cáo WER (V1 vs V2)<br>🧠 Checkpoint Model V2 |
| **Sprint 7**<br>*Final Ops* | 04/01 - 30/11 | **Operationalization**: Đóng gói sản phẩm, Demo Gradio, Báo cáo cuối kỳ. | 🚀 Link Demo (Gradio)<br>🏆 Báo cáo & Brochure |

## 5. 🛠️ Công nghệ & Phương pháp luận (Tech Stack & Methodology)
* **Phương pháp luận:** CPMAI x Agile/Scrum
* **Công cụ Quản lý:** GitHub (Issues, Projects, Milestones).
* **Công cụ Phân tích (đề xuất):** Python (Pandas, Scikit-learn), Google Colab, Figma.
* **Mô hình (đề xuất):** Sequence2Sequence, Transfomer.
* **Ma trận Trách nhiệm (RACI):** [Xem chi tiết tại đây](./docs/00_project_management/RACI_Matrix.md)
* **Google Colab V1:** [Xem chi tiết tại đây](https://colab.research.google.com/drive/1nksTekQb7kQcq6jTkB6aap5OwyQ7kKc4)
* **Google Colab V2:** [Xem chi tiết tại đây](https://colab.research.google.com/drive/10P9imS2j7Kb1LgN3jcAu5sJOS5usXXii#scrollTo=u-ayRBll8Uor)
* **Brochure Dự án:** [Xem chi tiết tại đây](https://heyzine.com/flip-book/e34e5a1cf5.html)

---
_Đây là dự án AI của Nhóm 11 do ThS **Tạ Việt Phương** làm Giảng viên hướng dẫn tại Đại học Kinh tế TP. Hồ Chí Minh (UEH)._
