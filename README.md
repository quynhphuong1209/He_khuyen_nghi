# 📦 Hệ Khuyến Nghị - Machine Learning Coursework

**Tác giả**: Đinh Lê Quỳnh Phương  
**Môn học**: Học máy & Hệ khuyến nghị  
**Repository**: `He_khuyen_nghi`  
**Cập nhật lần cuối**: Tháng 5, 2025

---

## 📁 Mô tả dự án

Repo này lưu trữ toàn bộ bài tập và thực hành liên quan đến chủ đề **Hệ khuyến nghị** sử dụng các phương pháp học máy, thao tác với dữ liệu `ml-100k`, và xây dựng các thuật toán từ cơ bản đến nâng cao.

---

## 🧠 Nội dung chính

### 🔹 Bài 1: Tổng quan và thao tác dữ liệu
- Tiền xử lý dữ liệu.
- Phân tích dữ liệu người dùng và phim.
- Thống kê số lượng rating.

### 🔹 Bài 2: Xây dựng hệ khuyến nghị
- Sử dụng kỹ thuật lọc cộng tác (Collaborative Filtering).
- Matrix factorization với SVD.
- Tính tương tự giữa người dùng và item.

### 🔹 Các bài thực hành:
| Tên file                        | Nội dung chính                                      |
|----------------------------------|-----------------------------------------------------|
| `3_1.ipynb` / `solution`         | Gợi ý phim dựa trên điểm số, đánh giá tổng quan.   |
| `3_3.ipynb` / `solution`         | Xây dựng recommender system sử dụng cosine sim.    |
| `3_5.ipynb`                      | Đánh giá hiệu suất hệ khuyến nghị.                 |
| `Bài_2.ipynb`                   | Phân tích lại mô hình trên `ml-100k`               |
| `quỳnh_phương_3_1.py`           | Phiên bản Python script của notebook 3.1           |
| `quỳnh_phương_3_3.py`           | Phiên bản Python script của notebook 3.3           |
| `quỳnh_phương_3_5.py`           | Phiên bản Python script của notebook 3.5           |

---

## 📦 Dữ liệu sử dụng

- **[MovieLens 100K](https://grouplens.org/datasets/movielens/100k/)**  
  Một bộ dữ liệu kinh điển trong hệ khuyến nghị, bao gồm:
  - 100.000 ratings từ 943 người dùng cho 1682 phim.
  - Được sử dụng cho bài toán lọc cộng tác và đánh giá mô hình.

---

## 🚀 Cách sử dụng

1. Clone repo:
   ```bash
   git clone https://github.com/quynhphuong1209/He_khuyen_nghi.git
   cd He_khuyen_nghi
   ```
2. Cài đặt thư viện cần thiết:
```bash
pip install numpy pandas scikit-learn matplotlib
```
3. Mở các notebook .ipynb trong JupyterLab hoặc VSCode để xem kết quả thực hành.
# 📌 Kết quả nổi bật
- Triển khai hệ thống gợi ý dựa trên user-item matrix.
- So sánh các phương pháp khuyến nghị và đánh giá bằng RMSE/MSE.
- Tự động hóa quy trình với các script .py.

# 📬 Liên hệ
Nếu bạn cần trao đổi hoặc học hỏi thêm, hãy liên hệ:
Email: dinhlequynhphuong@gmail.com
