# 📊 Phân Tích Dữ Liệu E-commerce Brazil (Olist)

## 🔍 Giới Thiệu  
Dự án này phân tích dữ liệu từ nền tảng thương mại điện tử **Olist** để tìm hiểu xu hướng doanh thu, hành vi khách hàng, hiệu suất giao hàng và đề xuất chiến lược cải thiện hoạt động kinh doanh.

📌 **Mục tiêu chính**:
- Phân tích doanh thu & đơn hàng theo thời gian.
- Khám phá hành vi mua sắm theo giờ/ngày.
- Đánh giá hiệu suất giao hàng & tối ưu logistics.
- Phân cụm khách hàng theo đặc điểm mua sắm.
- Đề xuất chiến lược cải thiện kinh doanh.

---

## 📂 Dữ Liệu Sử Dụng  
Bộ dữ liệu đến từ **Olist Brazilian E-Commerce Dataset** trên Kaggle, bao gồm các bảng sau:

| 📁 **Tên Bảng**                     | 📄 **Mô Tả** |
|-------------------------------------|-------------|
| 🛍 **olist_customers_dataset.csv**  | Thông tin khách hàng (ID khách hàng, địa chỉ, mã vùng). |
| 🌍 **olist_geolocation_dataset.csv** | Dữ liệu vị trí địa lý (kinh độ, vĩ độ, mã bưu điện). |
| 📦 **olist_orders_dataset.csv**      | Thông tin đơn hàng (ID đơn hàng, ngày đặt, trạng thái đơn hàng). |
| 📊 **olist_order_items_dataset.csv** | Chi tiết sản phẩm trong từng đơn hàng (giá, phí vận chuyển, số lượng). |
| 💳 **olist_order_payments_dataset.csv** | Thông tin thanh toán (phương thức thanh toán, số lần thanh toán). |
| ⭐ **olist_order_reviews_dataset.csv** | Đánh giá của khách hàng về đơn hàng. |
| 🎁 **olist_products_dataset.csv**     | Thông tin sản phẩm (ID sản phẩm, danh mục, trọng lượng, kích thước). |
| 🏪 **olist_sellers_dataset.csv**      | Thông tin nhà bán hàng (ID nhà bán, vị trí cửa hàng). |
| 🔄 **product_category_name_translation.csv** | Dịch danh mục sản phẩm từ tiếng Bồ Đào Nha sang tiếng Anh. |

**🔗 Link dữ liệu:** [Kaggle - Brazilian E-commerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📊 Các Phân Tích Chính  
### 📈 1. Xu hướng doanh thu & số lượng đơn hàng  
- Doanh thu tăng mạnh vào các tháng cao điểm.
- Số lượng đơn hàng cao nhất vào **buổi tối (18h - 22h)**.

### 🚚 2. Hiệu suất giao hàng  
- Thời gian giao hàng có sự chênh lệch giữa các tháng.
- Một số khu vực có thời gian giao hàng **quá lâu**, cần tối ưu logistics.

### 👥 3. Phân cụm khách hàng  
- Nhóm khách hàng có hành vi mua sắm khác nhau.
- Thanh toán qua **Credit Card** có giá trị đơn hàng cao nhất.

---

## 🛠️ Cách Cài Đặt & Chạy Dự Án  

### 1️⃣ **Cài đặt thư viện cần thiết**  
```bash
pip install pandas numpy seaborn matplotlib scikit-learn streamlit
```

### 2️⃣ Chạy Notebook Phân Tích
```bash 
jupyter notebook analysis.ipynb
```

### 📌 Định Hướng Tương Lai
- ✅ Dự đoán doanh số bằng Machine Learning.
- ✅ Tối ưu thời gian vận chuyển dựa trên dữ liệu lịch sử.
- ✅ Xây dựng hệ thống gợi ý sản phẩm cá nhân hóa.

📩 Liên hệ & Đóng góp: Hãy tạo Pull Request nếu bạn muốn đóng góp cho dự án này!
🔗 GitHub của bạn: https://github.com/dnoug12
