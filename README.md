# 🇻🇳 AIDEOM-VN 2026 — Dashboard Kinh Tế Số Việt Nam

> **AI-Driven Decision-making & Economics of Digital Markets — Vietnam**  
> 11 mô hình ra quyết định & tối ưu hóa cho phát triển kinh tế số Việt Nam 2026–2035

---

## 📌 Giới thiệu

**AIDEOM-VN** là một ứng dụng Streamlit tương tác trực quan hóa và phân tích **11 bài toán tối ưu hóa kinh tế số** áp dụng cho bối cảnh Việt Nam. Dự án bao gồm các mô hình từ kinh tế lượng cơ bản đến học tăng cường nâng cao.

---

## 🧩 Các mô hình trong dự án

### 📊 Nhóm 1 — Dự báo & Đo lường

| Bài | Tên | Nội dung |
|-----|-----|----------|
| B1 | Cobb-Douglas mở rộng | TFP, MAPE, Growth Accounting, dự báo GDP đến 2030 |
| B3 | Chỉ số ưu tiên ngành | Priority Score 10 ngành, phân tích độ nhạy |

### 🔧 Nhóm 2 — Tối ưu LP / MIP

| Bài | Tên | Nội dung |
|-----|-----|----------|
| B2 | LP Ngân sách 4 hạng mục | linprog, shadow price, phân tích B→Z* |
| B4 | LP 6 Vùng × 4 Hạng mục | PuLP, CVXPY, ràng buộc công bằng vùng |
| B5 | MIP 15 Dự án số | PuLP CBC, NPV, budget tích lũy |
| B6 | TOPSIS 6 vùng 8 tiêu chí | Entropy weights, phân tích độ nhạy w_AI |

### 🧠 Nhóm 3 — Mô hình Nâng cao

| Bài | Tên | Nội dung |
|-----|-----|----------|
| B7 | NSGA-II Pareto | pymoo, đa mục tiêu: GDP / Phúc lợi / Môi trường |
| B8 | Tối ưu động 2026–2035 | CVXPY log-linear, SLSQP, kịch bản sốc |
| B9 | Lao động & AI | LP phân bổ 30.000 tỷ, 8 ngành, chỉ số NetJob |
| B10 | Stochastic LP | Pyomo 4 kịch bản, so sánh EEV vs SP |
| B11 | Q-learning MDP | ε-greedy, 81 trạng thái, 10.000 episodes |

---

## 🚀 Hướng dẫn cài đặt & chạy

### 1. Clone repository

```bash
git clone https://github.com/<your-username>/aideom-vn.git
cd aideom-vn
```

### 2. Cài đặt thư viện

```bash
pip install -r requirements.txt
```

### 3. Chạy ứng dụng

```bash
streamlit run app.py
```

Ứng dụng sẽ mở tự động tại `http://localhost:8501`

---

## 📦 Yêu cầu hệ thống

- Python **3.9+**
- Các thư viện trong `requirements.txt`:

```
streamlit>=1.35.0
numpy>=1.26.0
pandas>=2.2.0
plotly>=5.22.0
```

---

## 📁 Cấu trúc dự án

```
aideom-vn/
├── app.py               # Mã nguồn chính
├── requirements.txt     # Danh sách thư viện
└── README.md            # Tài liệu dự án
```

---

## 📊 Dữ liệu kinh tế

Dự án sử dụng dữ liệu kinh tế Việt Nam giai đoạn **2020–2025** (GDP, kinh tế số, doanh nghiệp số, nhân lực) và xây dựng các kịch bản dự báo đến **2035**.

| Chỉ số | Giá trị 2025 | Mục tiêu 2030 |
|--------|-------------|---------------|
| GDP | 12.848 nghìn tỷ VND | — |
| Kinh tế số / GDP | 19,5% | 30% |
| Doanh nghiệp số | 80.100 | — |
| Nhân lực qua đào tạo | 29,2% | 35% |

---

## 🎨 Giao diện

- **Dark theme** Indigo-Emerald với font *Be Vietnam Pro*
- Sidebar điều hướng 12 trang
- Biểu đồ Plotly tương tác: scatter, bar, pie, heatmap, Pareto front, learning curve

---

## 📝 Môn học

> Môn: **Mô hình ra quyết định**  
> Nội dung: 11 bài toán tối ưu hóa kinh tế số Việt Nam


## Chạy chương trình

```bash
streamlit run app.py
```

---

## Tác giả

TÔ THỊ MINH OANH

Môn học: CÁC MÔ HÌNH RA QUYẾT ĐỊNH

ĐẠI HỌC KINH TẾ ĐẠI HỌC QUỐC GIA HÀ NỘI
