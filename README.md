# 🧠 SƠ ĐỒ TƯ DUY SIÊU CHI TIẾT & CỤ THỂ TOÀN BỘ MÔN HỌC
## PHƯƠNG PHÁP NGHIÊN CỨU & ĐÁNH GIÁ TÁC ĐỘNG ĐỊNH LƯỢNG (RESEARCH METHODOLOGY & CAUSAL INFERENCE)

---

## 🗺️ 1. SƠ ĐỒ TỔNG THỂ CẤU TRÚC MÔN HỌC

```mermaid
graph TD
    ROOT["📚 PHƯƠNG PHÁP NGHIÊN CỨU & ĐÁNH GIÁ TÁC ĐỘNG"] --> P1["PHẦN I: THỰC HÀNH NGHIÊN CỨU & LẬP ĐỀ CƯƠNG (RESEARCH PIPELINE)"]
    ROOT --> P2["PHẦN II: SUY LUẬN NGUYÊN NHÂN & ĐÁNH GIÁ TÁC ĐỘNG (CAUSAL INFERENCE)"]

    %% PHẦN 1 DETAIL
    P1 --> B1["Bài 1: Tổng quan NCKH & Đạo đức"]
    P1 --> B2["Bài 2: Vấn đề Nghiên cứu, Câu hỏi & Mục tiêu"]
    P1 --> B3["Bài 3: Tổng quan Lý thuyết & Khung Phân tích"]
    P1 --> B5["Bài 5: Thiết kế Nghiên cứu & Bản chất Tác động"]
    P1 --> B6["Bài 6: Thu thập Dữ liệu, Chọn mẫu & Quản lý"]
    P1 --> B7["Bài 7: Viết Đề cương & Báo cáo NCKH"]

    %% PHẦN 2 DETAIL
    P2 --> L1["Lecture 1: Hồi quy OLS & Biến kiểm soát (Regression & Controls)"]
    P2 --> L2["Lecture 2: Phương pháp Ghép cặp (Matching - PSM, CEM, Mahalanobis)"]
    P2 --> L3["Lecture 3: Phương pháp Biến cố định (Fixed Effects - FE & TWFE)"]
    P2 --> L4["Lecture 4: Khác biệt trong Khác biệt (Difference-in-Differences - DID)"]
```

---

## 🌳 2. SƠ ĐỒ TƯ DUY CHI TIẾT PHẦN I: LẬP ĐỀ CƯƠNG & QUY TRÌNH NGHIÊN CỨU

```mermaid
graph LR
    P1["PHẦN I: QUY TRÌNH NGHIÊN CỨU"] --> B1["1. TỔNG QUAN NCKH & ĐẠO ĐỨC"]
    B1 --> B1_1["Khái niệm NCKH: Tính logic, hệ thống, kiểm chứng, khách quan & tính mới"]
    B1 --> B1_2["Phân loại NCKH: Cơ bản vs Ứng dụng | Định lượng vs Định tính vs Hỗn hợp"]
    B1 --> B1_3["Đạo đức NCKH: Bảo mật dữ liệu, tính trung thực & Chống đạo văn (Plagiarism)"]

    P1 --> B2["2. VẤN ĐỀ, CÂU HỎI & MỤC TIÊU"]
    B2 --> B2_1["Nhận diện Vấn đề (Research Problem): Thực tiễn (Practical) vs Lý thuyết (Theoretical Gap)"]
    B2 --> B2_2["Phát biểu Câu hỏi (Research Questions - RQs): Rõ ràng, tập trung, có thể trả lời"]
    B2 --> B2_3["Xác định Mục tiêu (Objectives - ROs): General Objective vs Specific Objectives (SMART)"]
    B2 --> B2_4["Phạm vi (Scope) & Đóng góp (Contributions): Lý luận & Thực tiễn"]

    P1 --> B3["3. LÝ THUYẾT & KHUNG PHÂN TÍCH"]
    B3 --> B3_1["Tổng quan tài liệu (Literature Review): Tìm kiếm (Scopus/WoS), đọc phê phán & tổng hợp"]
    B3 --> B3_2["Cơ sở lý thuyết (Theoretical Background): Các lý thuyết gốc/nền tảng"]
    B3 --> B3_3["Khung phân tích (Conceptual Framework): Sơ đồ quan hệ biến số (Y, X, Mediators, Moderators)"]
    B3 --> B3_4["Giả thuyết nghiên cứu (Hypotheses - H1, H2...): Các phát biểu kiểm chứng được"]

    P1 --> B5["4. THIẾT KẾ & BẢN CHẤT TÁC ĐỘNG"]
    B5 --> B5_1["Loại Thiết kế: Khám phá (Exploratory), Mô tả (Descriptive), Nguyên nhân (Causal)"]
    B5 --> B5_2["Điều kiện Nhân-Quả (Causality): Tương quan + Thứ tự thời gian + Loại bỏ nguyên nhân thay thế"]
    B5 --> B5_3["Độ giá trị (Validity): Internal Validity (Tính chính xác nội tại) vs External Validity (Tính tổng quát hóa)"]

    P1 --> B6["5. CHỌN MẪU & QUẢN LÝ DỮ LIỆU"]
    B6 --> B6_1["Kỹ thuật Chọn mẫu: Xác suất (Random, Stratified, Cluster) vs Phi xác suất (Convenience, Purposive)"]
    B6 --> B6_2["Kích thước mẫu (n): Công thức thống kê & Quy tắc mô hình (SEM/Regression rules)"]
    B6 --> B6_3["Nguồn Sai lệch (Biases): Selection Bias, Non-response Bias, Information Bias"]
    B6 --> B6_4["Quản lý dữ liệu: Làm sạch (Cleaning), Xử lý khuyết (Missing Data), Outliers"]

    P1 --> B7["6. VIẾT ĐỀ CƯƠNG & BÁO CÁO"]
    B7 --> B7_1["Cấu trúc Đề cương (Proposal): Đặt vấn đề ➔ Lý thuyết ➔ Phương pháp ➔ Kế hoạch"]
    B7 --> B7_2["Quy chuẩn trích dẫn: APA 7th, Harvard, IEEE, IEEE Vancouver"]
```

---

## 🔬 3. SƠ ĐỒ TƯ DUY CHI TIẾT PHẦN II: CÁC PHƯƠNG PHÁP SUY LUẬN NGUYÊN NHÂN (CAUSAL INFERENCE)

```mermaid
graph TD
    CI["🎯 SUY LUẬN NGUYÊN NHÂN & ĐÁNH GIÁ TÁC ĐỘNG"] --> FRAMEWORK["Gốc rễ: Khung Phản thực (Counterfactual Framework / Rubin Causal Model)"]
    FRAMEWORK --> PO["Potential Outcomes: Y(1) (khi nhận can thiệp) vs Y(0) (khi không nhận)"]
    FRAMEWORK --> FUNDAMENTAL["Vấn đề cốt lõi: Không thể quan sát đồng thời Y(1) và Y(0) trên cùng một đơn vị tại cùng mốc thời gian"]

    %% METHOD 1
    CI --> M1["1️⃣ HỒI QUY OLS & CONTROL VARIABLES"]
    M1 --> M1_A["Cơ chế: Tiêu chí cửa sau (Backdoor Criterion) - Đóng các đường cửa sau X ⬅️ A ➡️ Y"]
    M1 --> M1_B["Mô hình: Y = β0 + β1*X + γ*Controls + ε"]
    M1 --> M1_C["Thách thức: Sai lệch biến bị bỏ sót (Omitted Variable Bias - OVB)"]
    M1 --> M1_D["Hạn chế: Chỉ loại bỏ được biến nhiễu QUAN SÁT ĐƯỢC"]

    %% METHOD 2
    CI --> M2["2️⃣ PHƯƠNG PHÁP GHÉP CẶP (MATCHING METHODS)"]
    M2 --> M2_A["Cơ chế: Tìm nhóm Control có đặc điểm Z tương đồng nhất với nhóm Treated"]
    M2 --> M2_B["Giả định cốt lõi: Selection on Observables (CIA) & Common Support (Vùng hỗ trợ chung)"]
    M2 --> M2_C["Các phương pháp chính: PSM (Propensity Score), CEM (Coarsened Exact), Mahalanobis Distance"]
    M2 --> M2_D["Kiểm định quan trọng: Balance Test (So sánh t-test / Standardized Mean Difference trước & sau ghép)"]
    M2 --> M2_E["Hạn chế: Không loại bỏ được biến nhiễu KHÔNG QUAN SÁT ĐƯỢC"]

    %% METHOD 3
    CI --> M3["3️⃣ PHƯƠNG PHÁP BIẾN CỐ ĐỊNH (FIXED EFFECTS - FE)"]
    M3 --> M3_A["Loại dữ liệu: Dữ liệu bảng (Panel Data - theo dõi N cá nhân qua T thời kỳ)"]
    M3 --> M3_B["Cơ chế: Phép biến đổi Demeaning / Within Transformation (Y_it - Y_mean_i)"]
    M3 --> M3_C["Sức mạnh vượt trội: Triệt tiêu biến nhiễu KHÔNG QUAN SÁT ĐƯỢC nhưng CỐ ĐỊNH THEO THỜI GIAN (α_i)"]
    M3 --> M3_D["TWFE (Two-Way FE): Đưa vào cả Unit Fixed Effects (α_i) và Time Fixed Effects (δ_t)"]
    M3 --> M3_E["Kiểm định: Hausman Test (So sánh Fixed Effects vs Random Effects)"]

    %% METHOD 4
    CI --> M4["4️⃣ KHÁC BIỆT TRONG KHÁC BIỆT (DIFFERENCE-IN-DIFFERENCES - DID)"]
    M4 --> M4_A["Cơ chế 4 Cell Means: δ_DID = (Y_T,post - Y_T,pre) - (Y_C,post - Y_C,pre)"]
    M4 --> M4_B["Mô hình Hồi quy: Y_it = α + β1*Treated + β2*Post + β3*(Treated × Post) + ε"]
    M4 --> M4_C["Giả định TỐI CAO: Xu hướng song song (Parallel Trends Assumption)"]
    M4 --> M4_D["Công cụ kiểm định: Event Study / Dynamic DID (Khai thác pre-trends), Placebo Test"]
    M4 --> M4_E["DID Hiện đại: Xử lý Can thiệp rải rác (Staggered Adoption) bằng Callaway & Sant'Anna (C&S)"]
```

---

## ⚡ 4. BẢNG NỐI LÝ THUYẾT & THỰC HÀNH (KHI NÀO DÙNG PHƯƠNG PHÁP NÀO?)

```mermaid
flowchart TD
    START["❓ BẮT ĐẦU: BẠN MUỐN ĐÁNH GIÁ TÁC ĐỘNG CỦA CAN THIỆP X LÊN KẾT QUẢ Y"] --> Q1{"Loại Dữ liệu bạn thu thập được?"}
    
    Q1 -- "Dữ liệu cắt ngang (Cross-sectional data)" --> Q2{"Có biến nhiễu không quan sát được không?"}
    Q1 -- "Dữ liệu bảng (Panel Data / Repeated Cross-section)" --> Q3{"Có sự di chuyển chính sách / Can thiệp theo thời gian?"}

    Q2 -- "Không, tôi đo lường được đầy đủ các biến nhiễu Z" --> CHOICE1["👉 Sử dụng OLS + Controls hoặc MATCHING (PSM / CEM)"]
    Q2 -- "Có, có nhiều biến nhiễu ẩn khó đo lường" --> CHOICE2["⚠️ OLS & Matching sẽ bị bias! Cần tìm biến công cụ (IV) hoặc RDD"]

    Q3 -- "Không, can thiệp diễn ra liên tục hoặc ổn định" --> CHOICE3["👉 Sử dụng FIXED EFFECTS (FE / TWFE)"]
    Q3 -- "Có, có nhóm nhận chính sách và nhóm không nhận chính sách qua thời gian" --> Q4{"Thời điểm nhận chính sách thế nào?"}

    Q4 -- "Nhận chính sách cùng một thời điểm" --> CHOICE4["👉 Sử dụng Standard DID (Mô hình TWFE Interaction)"]
    Q4 -- "Nhận chính sách ở các thời điểm rải rác (Staggered Rollout)" --> CHOICE5["👉 Sử dụng MODERN DID (Callaway & Sant'Anna / Sun & Abraham / Imputation)"]
```

---

## 📑 5. CẤU TRÚC CHI TIẾT MỘT ĐỀ CƯƠNG NGHIÊN CỨU KHAI THÁC PHƯƠNG PHÁP ĐỊNH LƯỢNG NÂNG CAO

1. **CHƯƠNG 1: GIỚI THIỆU ĐỀ TÀI**
   * 1.1. Bối cảnh & Lý do chọn đề tài
   * 1.2. Vấn đề nghiên cứu & Khoảng trống tri thức (Research Gap)
   * 1.3. Câu hỏi nghiên cứu (Research Questions) & Mục tiêu nghiên cứu (Research Objectives)
   * 1.4. Đối tượng, Phạm vi & Đóng góp của đề tài
2. **CHƯƠNG 2: TỔNG QUAN LÝ THUYẾT & KHUNG NGHIÊN CỨU**
   * 2.1. Các cơ sở lý thuyết nền tảng (Foundational Theories)
   * 2.2. Tổng quan các nghiên cứu thực nghiệm liên quan (Empirical Literature Review)
   * 2.3. Khung phân tích & Các giả thuyết nghiên cứu ($H_1, H_2,...$)
3. **CHƯƠNG 3: PHƯƠNG PHÁP NGHIÊN CỨU & MÔ HÌNH ƯỚC LƯỢNG**
   * 3.1. Nguồn dữ liệu & Quy trình chọn mẫu
   * 3.2. Mô hình nghiên cứu & Định nghĩa các biến số
   * 3.3. Chiến lược định danh nhân quả (Causal Identification Strategy):
     * *Nếu dùng OLS/PSM:* Mô tả các biến kiểm soát & quy trình ghép cặp, kiểm định Balance.
     * *Nếu dùng Fixed Effects:* Mô tả phép Demeaning & Unit/Time Fixed Effects.
     * *Nếu dùng DID:* Chứng minh Parallel Trends, mô tả mô hình Event Study & xử lý Staggered Adoption.
   * 3.4. Các kiểm định tính vững (Robustness Checks)
4. **KẾ HOẠCH THỰC HIỆN & TÀI LIỆU THAM KHẢO (APA 7th)**
