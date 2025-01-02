# Xây dựng thuật toán phân bổ vận chuyển cho tài xế

# Giới thiệu
Repo này là kết quả của đồ án cuối kỳ của môn Project I - IT3910E, được hướng dẫn bởi TS. Vũ Thị Hương Giang. Toàn bộ thuật toán được viết bằng ngôn ngữ Python.

# Cấu trúc
Repo này bao gồm các thư mục/tệp sau:
- `/data`: Thư mục này chứa các tệp đuôi `.csv`, bao gồm 4 tệp `distance.csv`, `order_small.csv`, `order_large.csv` và `truck.csv`. Đây là các dữ liệu về bài toán phân bổ vận chuyển cho tài xế, bao gồm các đơn hàng, các xe tải, khoảng cách giữa hai địa điểm bất kì. Toàn bộ dữ liệu và phát biểu của bài toán được tham khảo tại [đây](https://www.kaggle.com/datasets/mexwell/large-scale-route-optimization).
- `README.md`: Giới thiệu về repo.
- `requirements.txt`: Bao gồm những thư viện cần thiết để chạy thuật toán.
- `deep_q_learning.ipynb': Notebook chứa toàn bộ mã nguồn của thuật toán, bao gồm các bước tiền xử lý dữ liệu, huấn luyện mô hình Deep Q-Network và quá trình suy diễn để tìm ra phương án phân bổ vận chuyển tối ưu.

# Sử dụng
Để có thể chạy thuật toán, trước hết hãy clone repo sử dụng câu lệnh sau:

```.bash
git clone https://github.com/ahihidongok111/deep-q-learning-vrp.git
```

Sau đó hãy đổi working directory:

```.bash
cd deep-q-learning-vrp
```

Tiếp theo, tải về các thư viện cần thiết sử dụng câu lệnh sau:

```.bash
pip install -r requirements.txt
```

Như vậy là bạn đã có thể triển khai thuật toán rồi!
