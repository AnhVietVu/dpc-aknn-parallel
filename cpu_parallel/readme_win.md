# DPC-AKNN CPU (Windows)

### 1. Biên dịch (Compile)
Mở PowerShell (hoặc Command Prompt có hỗ trợ `gcc`) tại thư mục này và chạy:
```powershell
# Dọn dẹp các file build cũ
mingw32-make clean

# Biên dịch chương trình
mingw32-make
```

### 2. Chạy chương trình (Run)

**Cách 1: Chạy bằng cấu hình mặc định (được thiết lập trong file `config.h`)**
```powershell
.\dpc_aknn_cpu.exe
```

**Cách 2: Chạy và truyền tham số trực tiếp từ dòng lệnh**
```powershell
.\dpc_aknn_cpu.exe --input ..\data\real\fashion-mnist\fashion_mnist_X.csv --labels ..\data\real\fashion-mnist\fashion_mnist_y.csv --clusters 10 --k 15
```
