# 📘 Machine Learning – Study README

## 1. Mục tiêu học tập

Tài liệu này được tạo ra để **ghi lại lộ trình, kiến thức và thực hành** trong quá trình học Machine Learning (ML). Mục tiêu không chỉ là *chạy được model*, mà là:

* Hiểu **bản chất dữ liệu** trước khi học thuật toán
* Nắm chắc **tư duy ML cơ bản** (data → feature → model → evaluation)
* Có thể **đọc – hiểu – chỉnh sửa** các notebook/tutorial ML phổ biến (đặc biệt từ Kaggle)

---

## 2. Công cụ & Thư viện sử dụng

### Ngôn ngữ

* **Python 3**

### Thư viện chính

* **NumPy** – xử lý mảng số học
* **Pandas** – khám phá và thao tác dữ liệu dạng bảng
* **Matplotlib / Seaborn** – trực quan hóa dữ liệu
* **Scikit-learn** – xây dựng và đánh giá mô hình ML

---

## 3. Quy trình học Machine Learning (Chuẩn)

### Bước 1: Làm quen với dữ liệu (Exploratory Data Analysis – EDA)

* Đọc dữ liệu từ file CSV
* Quan sát cấu trúc dữ liệu
* Phát hiện dữ liệu thiếu, dữ liệu sai

Công cụ chính: **Pandas**

Ví dụ lệnh thường dùng:

* `head()` – xem vài dòng đầu
* `describe()` – thống kê dữ liệu số
* `info()` – kiểm tra kiểu dữ liệu và giá trị thiếu

---

### Bước 2: Chuẩn bị dữ liệu

* Chọn **biến đầu vào (features)**
* Chọn **biến mục tiêu (target)**
* Xử lý giá trị thiếu
* Chuyển dữ liệu sang dạng số nếu cần

---

### Bước 3: Xây dựng mô hình

Các thuật toán sẽ học theo thứ tự từ dễ đến khó:

1. Linear Regression
2. Decision Tree
3. Random Forest
4. (Sau này) Gradient Boosting, XGBoost

Mục tiêu ở giai đoạn này:

* Hiểu **model học cái gì**
* Biết **khi nào model overfitting / underfitting**

---

### Bước 4: Đánh giá mô hình

* Chia dữ liệu train / validation
* Dùng các metric phù hợp:

  * MAE / MSE / RMSE (bài toán hồi quy)
  * Accuracy / Precision / Recall (bài toán phân loại)

---

## 4. Dataset sử dụng

### Dataset học tập

* **Melbourne Housing Dataset**
  → Dùng để học Pandas, EDA và Decision Tree

* **Iowa Housing Dataset**
  → Dataset chính trong khóa Kaggle Intro to ML

---

## 5. Nguyên tắc học tập

* Không học thuộc code, **học lý do tại sao dùng code đó**

* Mỗi notebook phải trả lời được 3 câu hỏi:

  1. Dữ liệu trông như thế nào?
  2. Model đang học từ đâu?
  3. Kết quả nói lên điều gì?

* Khi model cho kết quả tốt:

  * Phải nghi ngờ
  * Kiểm tra lại dữ liệu và cách chia tập

---

## 6. Ghi chú cá nhân

* ML không phải là "phép màu", mà là **thống kê + dữ liệu + tư duy logic**
* Pandas là nền móng: **không hiểu dữ liệu → model vô nghĩa**
* Hiểu chậm nhưng chắc quan trọng hơn chạy nhanh mà mù mờ

---

## 7. Kế hoạch tiếp theo

* [ ] Thành thạo Pandas cơ bản
* [ ] Hoàn thành Kaggle: Intro to ML
* [ ] Hiểu sâu Decision Tree & Random Forest
* [ ] Tự làm 1 project ML nhỏ từ đầu đến cuối

---

*README này sẽ được cập nhật liên tục trong quá trình học.*
