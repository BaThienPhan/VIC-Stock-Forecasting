# VIC-Stock-Forecasting
# Dự báo giá cổ phiếu VIC (Vingroup) sử dụng mô hình LTSF-Linear

Dự án này thực hiện dự đoán giá đóng cửa (Close Price) của cổ phiếu VIC trong 7 ngày tiếp theo bằng cách sử dụng các mô hình Long-Term Time Series Forecasting (LTSF) tuyến tính: **Linear, DLinear, và NLinear**.

## 📂 Cấu trúc dữ liệu
Dữ liệu được lấy từ file `VIC.csv`, bao gồm lịch sử giao dịch với các trường:
- Date, Open, High, Low, Close, Volume.

## 🛠 Yêu cầu hệ thống
- Python 3.8+
- Các thư viện: PyTorch, Scikit-learn, Pandas, Numpy, Matplotlib.

## 🚀 Cài đặt & Chạy dự án

1. Clone repository:
   ```bash
   git clone [https://github.com/BaThienPhan/VIC-Stock-Forecasting.git](https://github.com/username-cua-ban/VIC-Stock-Forecasting.git)
   cd VIC-Stock-Forecasting
