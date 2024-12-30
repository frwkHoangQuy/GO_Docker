# GO_Docker

## Hướng dẫn cài đặt và khởi chạy

### 1. Clone code từ GitHub
Sử dụng lệnh sau để clone code về máy:

```bash
git clone https://github.com/frwkHoangQuy/GO_Docker
```

### 2. Tạo và kết nối cơ sở dữ liệu (Database)

Trong thư mục gốc của dự án GO_Intern_backend, tạo một file config.ini và điền thông tin kết nối cơ sở dữ liệu với nội dung sau:

```ini
[mysql]
host = mysql-cafdc83-frwk-6b12.h.aivencloud.com
user = avnadmin
password = AVNS_3nOZbGfFwT_jN908tKP
database = webdev_intern
port = 17302
```

### 3. Build Docker: 
Trong terminal của file dự án, chạy lệnh 2 sau: 
```bash
docker-compose build
```

```bash
docker-compose up
```

### 4. Kết quả: 

Mở http://localhost:3000/ và đợi ứng dụng hiển thị kết quả.
