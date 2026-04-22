# ĐỒ ÁN 1: TIỀN XỬ LÝ DỮ LIỆU

**Môn học:** Khai thác dữ liệu và ứng dụng (CSC14004)  
**Nhóm:** Group_12

---

## 1. Thành viên nhóm

| STT | Họ và Tên         | MSSV     |
|-----|-------------------|----------|
| 1   | Nguyễn Đăng Khôi  | 23122037 |
| 2   | Lê Đức Phúc       | 23122045 |
| 3   | Nguyễn Xuân Quang | 23122047 |
| 4   | Nguyễn Tấn Tài    | 23122050 |
| 5   | Kpuih Thuing      | 23122054 |

---

## 2. Mô tả Tập dữ liệu (Datasets)

Nhóm lựa chọn thực hiện Tiền xử lý cho 3 loại dữ liệu: Ảnh, Bảng và Văn bản.

### Phần 1 - Dữ liệu Ảnh
- **Tên tập dữ liệu:** Chest X-Ray Images (Pneumonia)
- **Nguồn/Link:** [Kaggle - Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Mô tả ngắn:** Tập dữ liệu gồm 5.863 ảnh X-quang ngực, được sử dụng để phân loại 2 lớp: Pneumonia (Viêm phổi) và Normal (Bình thường). Dữ liệu được chia sẵn thành các tập train, test và val.

### Phần 2 - Dữ liệu Bảng
- **Tên tập dữ liệu:** Adult Census Income
- **Nguồn/Link:** [Kaggle - Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income)
- **Mô tả ngắn:** Dự đoán thu nhập (<=50K hoặc >50K) dựa trên các thông tin nhân khẩu học. Dữ liệu gồm khoảng 32.561 dòng và 15 thuộc tính.

### Phần 3 - Dữ liệu Văn bản
- **Tên tập dữ liệu:** IMDB Dataset of 50K Movie Reviews
- **Nguồn/Link:** [Kaggle - IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Mô tả ngắn:** Tập dữ liệu gồm 50.000 đánh giá phim (movie reviews) dùng cho bài toán phân loại cảm xúc nhị phân (positive/negative). Dữ liệu được chia sẵn thành tập train và test, mỗi tập khoảng 25.000 reviews.

> **🔗 Link tải Data & Tài nguyên ngoài (Google Drive):** [Thư mục data/](https://drive.google.com/drive/folders/1-G6CYi7OlpWdSerIffbqX4FHNaAgDatt?usp=drive_link)

---

## 3. Hướng dẫn cài đặt và chạy Notebook

### 3.1. Cài đặt môi trường

Hãy đảm bảo đã cài đặt Python 3.8+. Để cài đặt các thư viện cần thiết, hãy mở terminal tại thư mục gốc của đồ án và chạy lệnh sau:

```bash
pip install -r requirements.txt
```

### 3.2. Cấu trúc thư mục

```
Group_ID/
├── README.md               # Tổng quan đồ án và hướng dẫn
├── requirements.txt        # Danh sách thư viện cần thiết
├── data/
│   ├── raw/                # Dữ liệu gốc
│   └── processed/          # Dữ liệu sau khi tiền xử lý
├── notebooks/
│   ├── 01_EDA_image.ipynb
│   ├── 02_preprocessing_image.ipynb
│   ├── 03_EDA_tabular.ipynb
│   ├── 04_preprocessing_tabular.ipynb
│   └── 05_text_preprocessing.ipynb
└── docs/
    └── Report.pdf          # Báo cáo chi tiết của nhóm
```

### 3.3. Chạy Notebook

1. Khởi động Jupyter Notebook hoặc Jupyter Lab.
2. Mở tuần tự các file `.ipynb` trong thư mục `notebooks/`.
3. Nhấn **Kernel > Restart & Run All** để chạy lại toàn bộ quy trình.  

---

## 4. Bảng phân công công việc

| Thành viên        | Nhiệm vụ thực hiện          | Mức độ hoàn thành |
|-------------------|-----------------------------|-------------------|
| Nguyễn Đăng Khôi  | Preprocessing Text          | 100%              |
| Lê Đức Phúc       | EDA & Preprocessing Tabular | 100%              |
| Nguyễn Xuân Quang | Preprocessing Image         | 100%              |
| Nguyễn Tấn Tài    | EDA Image & Writing Report  | 100%              |
| Kpuih Thuing      | EDA Text & Writing Report   | 100%              |
