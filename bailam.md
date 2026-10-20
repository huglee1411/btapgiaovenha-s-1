
 # BÀI LÀM NGÀY 1

## Phần A – GUI

### A1

Đã bật hiển thị:

-   File ẩn (Hidden Items)
-   Đuôi mở rộng của file (File Name Extensions)

### A2

Đổi tên thư mục gốc:

```text
trung-tam-tieng-anh

```

### A3

Tạo 5 thư mục:

```text
docs
media
data
logs
archive

```

### A4

Đổi tên file theo snake_case:

```text
Logo Trung Tam.PNG -> logo_trung_tam.png
Anh Lop Hoc.JPG -> anh_lop_hoc.jpg
Lich Hoc.txt -> lich_hoc.txt
Hoc Vien Khoa 3.xlsx -> hoc_vien_khoa_3.xlsx
Access.log -> access.log

```

### A5

Di chuyển file:

```text
hoc_vien_khoa_3.xlsx -> data
access.log -> logs
logo_trung_tam.png -> media
anh_lop_hoc.jpg -> media

```

Giữ:

```text
lich_hoc.txt

```

ở thư mục gốc.

### A6

Sao chép:

```text
bai_lam_ngay1.md

```

vào thư mục:

```text
docs

```

Giữ:

```text
.env

```

ở thư mục gốc.

----------

# Phần B – CLI

## B1

Lệnh:

```bash
pwd

```

Kết quả:

```text
C:\Users\Student\Desktop\trung-tam-tieng-anh

```

## B2

Lệnh:

```bash
ls -Force

```

## B3

Lệnh:

```bash
mv lich_hoc.txt docs/

```

## B4

Lệnh:

```bash
cp media/logo_trung_tam.png archive/

```

## B5

Lệnh:

```bash
rm temp_201.tmp
rm temp_202.tmp

```

## B6

Lệnh:

```bash
cd logs
ls
cd ..

```

## B7

Lệnh:

```bash
cd docs
cp ../media/anh_lop_hoc.jpg ../archive/
cd ..

```

## B8

Lệnh:

```bash
ls -aR

```

Kết quả:

```text
trung-tam-tieng-anh
│
├── .env
├── bai_lam_ngay1.md
│
├── archive
│   ├── anh_lop_hoc.jpg
│   └── logo_trung_tam.png
│
├── data
│   └── hoc_vien_khoa_3.xlsx
│
├── docs
│   ├── bai_lam_ngay1.md
│   └── lich_hoc.txt
│
├── logs
│   └── access.log
│
└── media
    ├── anh_lop_hoc.jpg
    └── logo_trung_tam.png

```

----------

# Tự chấm điểm

Nội dung

Điểm

Phần A – GUI

38

Phần B – CLI

57

Nộp bài

5

Tổng cộng

100

**Tổng điểm: 100/100**


