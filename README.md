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
- **Tên tập dữ liệu:** New Plant Diseases Dataset
- **Nguồn/Link:** [Kaggle - New Plant Diseases](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)
- **Mô tả ngắn:** [Bộ dữ liệu ảnh RGB chụp lá cây dưới điều kiện có kiểm soát, được xây dựng để
phục vụ bài toán nhận dạng và phân loại bệnh cây trồng]

### Phần 2 - Dữ liệu Bảng
- **Tên tập dữ liệu:** Adult Census Income
- **Nguồn/Link:** [Kaggle - Adult Census Income](https://www.kaggle.com/datasets/uciml/adult-census-income)
- **Mô tả ngắn:** Dự đoán thu nhập (<=50K hoặc >50K) dựa trên các thông tin nhân khẩu học. Dữ liệu gồm khoảng 32.561 dòng và 15 thuộc tính.

### Phần 3 - Dữ liệu Văn bản
- **Tên tập dữ liệu:** [Tên dataset, VD: IMDB Dataset of 50K Movie Reviews]
- **Nguồn/Link:** [Link tải dataset]
- **Mô tả ngắn:** [Số lượng dòng, mục tiêu phân loại...]

> **🔗 Link tải Data & Tài nguyên ngoài (Google Drive):** [Chèn link Drive chứa thư mục `data/` nếu file nén vượt quá 25MB]
**Link tải dataset New Plant Diseases (Dữ liệu ảnh)** [Google drive](https://drive.google.com/drive/folders/1bn02lomttKFASPSl-Bxry9fB4ktfjjlT?usp=sharing)
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
