# AIDEOM-VN 2026

## Tổng quan

AIDEOM-VN là hệ thống hỗ trợ ra quyết định phát triển kinh tế số Việt Nam giai đoạn 2026–2035.

Đồ án được xây dựng bằng Python và Streamlit, tích hợp nhiều mô hình tối ưu hóa, phân tích đa tiêu chí và trí tuệ nhân tạo để hỗ trợ hoạch định chính sách.

---

## Các mô hình được tích hợp

### B1. Cobb-Douglas & TFP
Dự báo tăng trưởng GDP dựa trên vốn, lao động và năng suất tổng hợp.

### B2. Linear Programming
Tối ưu phân bổ ngân sách quốc gia.

### B3. Chỉ số ưu tiên ngành
Xếp hạng ngành kinh tế theo trọng số chiến lược.

### B4. LP phân bổ 6 vùng
Phân bổ nguồn lực cho 6 vùng kinh tế Việt Nam.

### B5. Mixed Integer Programming
Lựa chọn danh mục dự án chuyển đổi số tối ưu.

### B6. TOPSIS
Xếp hạng mức độ sẵn sàng phát triển của các vùng.

### B7. NSGA-II
Tối ưu đa mục tiêu GDP – Phúc lợi – Môi trường.

### B8. Tối ưu động
Phân bổ đầu tư liên thời gian 2026–2035.

### B9. Lao động & AI
Đánh giá tác động của AI tới việc làm.

### B10. Stochastic Programming
Tối ưu trong điều kiện bất định.

### B11. Q-Learning
Mô hình học tăng cường hỗ trợ ra quyết định.

---

## Công nghệ sử dụng

- Python
- Streamlit
- Plotly
- NumPy
- Pandas
- SciPy
- CVXPY
- PuLP
- PyMOO

---

## Cấu trúc hệ thống

M1 – Dự báo kinh tế

M2 – Đánh giá sẵn sàng số

M3 – Tối ưu phân bổ

M4 – Mô phỏng lao động

M5 – Đánh giá rủi ro

M6 – Dashboard hỗ trợ ra quyết định

---

## Chạy chương trình

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## Tác giả

TÔ THỊ MINH OANH

Môn học: CÁC MÔ HÌNH RA QUYẾT ĐỊNH

ĐẠI HỌC KINH TẾ ĐẠI HỌC QUỐC GIA HÀ NỘI
