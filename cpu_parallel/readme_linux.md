# DPC-AKNN CPU (Linux)

### 1. Biên dịch (Compile)
Mở terminal tại thư mục này và chạy:
```bash
# Dọn dẹp các file build cũ
make clean

# Biên dịch chương trình
make
```

### 2. Chạy chương trình (Run)

**Cách 1: Chạy bằng cấu hình mặc định (được thiết lập trong file `config.h`)**
```bash
./dpc_aknn_cpu
```

**Cách 2: Chạy và truyền tham số trực tiếp từ dòng lệnh**
```bash
./dpc_aknn_cpu --input ../data/real/fashion-mnist/fashion_mnist_X.csv --labels ../data/real/fashion-mnist/fashion_mnist_y.csv --clusters 10 --k 15
```
