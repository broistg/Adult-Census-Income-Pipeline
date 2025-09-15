# BÀI TẬP LỚN MÔN HỌC: HỌC MÁY (CO3117)

**Lớp:** TN01  
**Học kỳ:** 251  
**Năm học:** 2025-2026

## Giảng viên hướng dẫn (GVHD)

- Họ tên: TS. Lê Thành Sách
- Email: ltsach@hcmut.edu.vn

## Thông tin các thành viên nhóm

| Họ tên              | Mã số sinh viên | Email                          |
| ------------------- | --------------- | ------------------------------ |
| Cao Hữu Thiên Hoàng | 2311030         | hoang.cao2510@hcmut.edu.vn     |
| Lê Tiến Đạt         | 2310653         | dat.le2005@hcmut.edu.vn        |
| Trần Vĩnh Dũng      | 2310574         | dung.tranvinh2005@hcmut.edu.vn |

## Mục tiêu của bài tập lớn

- Vận dụng kiến thức đã học để xây dựng pipeline học máy truyền thống và học sâu nhằm xử lý và phân tích dữ liệu dạng bảng (Adult Census Income)
- Pipeline bao gồm quy trình xử lý dữ liệu, trích xuất đặc trưng, huấn luyện mô hình và đánh giá kết quả. Qua đó, sinh viên sẽ nắm vững các bước cơ bản trong việc triển khai một hệ thống học máy hiệu quả.

## Hướng dẫn chạy notebook

1. **Yêu cầu môi trường:**

   - Google Colab (khuyến nghị) hoặc môi trường Python 3.9+
   - Các thư viện cần thiết sẽ được cài tự động trong notebook:
     - scikit-learn
     - pandas
     - numpy
     - plotly
     - matplotlib
     - seaborn
     - torch, torchvision
     - pytorch-tabnet
     - wget

2. **Cách tải dữ liệu:**
   - Dữ liệu Adult Census Income được tải tự động từ UCI Machine Learning Repository:
     - adult.data (dùng để chia thành Train / Validation / Test)
     - Link gốc: [Adult Census Income](https://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data)
3. **Chạy notebook:**
   - Mở notebook trên Google Colab.
   - Chọn **Runtime** → **Run all**.
   - Toàn bộ quy trình (cài thư viện, tải dữ liệu, huấn luyện, đánh giá) sẽ chạy tự động.

## Cấu trúc thư mục dự án

```
Adult-Census-Income-Pipeline/
├── features/      # Xử lý đặc trưng, feature engineering
├── modules/       # Các module, script chính
├── notebooks/     # Notebook Jupyter cho phân tích và báo cáo
├── reports/       # Báo cáo, kết quả, hình ảnh
├── README.md      # Tài liệu này
```

## Báo cáo và notebook Colab

- [Link tới báo cáo PDF](https://link-den-bao-cao.pdf)
- [Link tới Colab notebook](https://colab.research.google.com/drive/link-den-notebook)
