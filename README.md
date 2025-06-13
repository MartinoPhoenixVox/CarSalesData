# Phân tích dữ liệu của cửa hàng xe

## Giới thiệu

Dự án này tập trung vào việc phân tích dữ liệu bán hàng của một cửa hàng xe nhằm khám phá các xu hướng, insight quan trọng và xây dựng các mô hình dự đoán. Mục tiêu là giúp cửa hàng đưa ra các quyết định kinh doanh dựa trên dữ liệu, tối ưu hóa hiệu suất và nâng cao doanh thu.

## Mục lục

- [Giới thiệu](#giới-thiệu)
- [Mục lục](#mục-lục)
- [Tính năng chính](#tính-năng-chính)
- [Yêu cầu cài đặt](#yêu-cầu-cài-đặt)
- [Cách sử dụng](#cách-sử-dụng)
- [Kết quả nổi bật](#kết-quả-nổi-bật)
- [Thành viên thực hiện](#thành-viên-thực-hiện)

## Tính năng chính

- **Tiền xử lý dữ liệu:** Làm sạch, xử lý các giá trị thiếu và chuyển đổi dữ liệu để chuẩn bị cho phân tích.
- **Khám phá dữ liệu (EDA):** Phân tích thống kê và trực quan hóa dữ liệu để hiểu rõ hơn về các mối quan hệ và xu hướng.
- **Phân tích hồi quy:** Xây dựng mô hình hồi quy để dự đoán các biến quan trọng như "Commission Earned" dựa trên các yếu tố khác.
- **Gom cụm (Clustering):** Sử dụng các thuật toán gom cụm để phân loại dữ liệu và khám phá các nhóm tiềm ẩn.
- **Mô hình cây quyết định (Decision Tree):** Áp dụng mô hình cây quyết định để dự đoán và hiểu các quy tắc ẩn trong dữ liệu.

## Nguồn Dữ Liệu

Bộ dữ liệu "Car Sales Data" của tác giả Suraj.

* **Nguồn:** [https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005](https://www.sciencedirect.com/science/article/pii/S2352340918315191#t0005)

## Yêu cầu cài đặt

Để chạy dự án này, bạn cần cài đặt các thư viện Python được liệt kê trong file `requements.txt`. Bạn có thể cài đặt chúng bằng cách sử dụng pip:

```bash
pip install -r requements.txt
```

## Cách sử dụng

1.  **Clone repository:**
    ```bash
    git clone <URL_CUA_REPOSITORY_CUA_BAN>
    cd <ten_thu_muc_du_an>
    ```
2.  **Cài đặt các thư viện cần thiết:**
    ```bash
    pip install -r requements.txt
    ```
3.  **Mở các Jupyter Notebook:**
    Bạn có thể mở và chạy các file `.ipynb` bằng Jupyter Notebook hoặc JupyterLab để khám phá từng phần của dự án.
    ```bash
    jupyter notebook
    ```
    Sau đó, điều hướng đến các file `main.ipynb`, `cluster.ipynb`, `decision_tree.ipynb`, `train_model.ipynb` để xem và chạy code.

## Kết quả nổi bật

Dự án đã đạt được các kết quả sau:

* **Phân tích sâu sắc về doanh số bán hàng và hoa hồng:** Xác định các yếu tố ảnh hưởng đến "Commission Earned" như "Car Year", "Sale Price", và "Commission Rate" với mô hình hồi quy có độ chính xác cao (R-squared gần 1).
* **Phân nhóm khách hàng/xe:** Áp dụng gom cụm để phân loại dữ liệu, giúp hiểu rõ hơn về các đặc điểm của từng nhóm (ví dụ: nhóm khách hàng có "Commission Rate" cao/thấp).
* **Dự đoán hiệu quả:** Các mô hình đã xây dựng (Linear Regression, Decision Tree, và có thể cả Neural Network) cho thấy khả năng dự đoán tốt, hỗ trợ cửa hàng trong việc lập kế hoạch và tối ưu hóa chiến lược.

## Thành viên thực hiện:

* **Phạm Quốc Huy** (2151013028)
* **Hồ Hữu Tuấn** (2151010411)
* **Võ Huỳnh Thanh Phương** (2151013072)

Giảng viên hướng dẫn: **Nguyễn Văn Bảy**
