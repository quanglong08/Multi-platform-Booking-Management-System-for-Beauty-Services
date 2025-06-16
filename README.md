# Beauty Services Booking & Management System

Hệ thống đặt lịch và quản lý dịch vụ làm đẹp đa nền tảng.

## Công nghệ sử dụng

- Backend: Python (Flask)
- Frontend: HTML, CSS, JavaScript
- Database: Firebase Realtime Database

## Cài đặt

1. Clone repository:
```bash
git clone [repository-url]
```

2. Cài đặt các dependencies:
```bash
pip install -r requirements.txt
```

3. Cấu hình Firebase:
- Tạo project trên Firebase Console
- Tải file cấu hình và đặt vào thư mục `app/config/`

4. Chạy ứng dụng:
```bash
python app/__init__.py
```

## Cấu trúc thư mục

```
booking-management-system/
├── app/                    # Mã nguồn chính
│   ├── static/            # File tĩnh (CSS, JS, images)
│   ├── templates/         # HTML templates
│   ├── models/           # Models
│   ├── controllers/      # Controllers
│   └── config/           # Cấu hình
├── tests/                # Tests
└── docs/                 # Tài liệu
```

## Đóng góp

Mọi đóng góp đều được hoan nghênh. Vui lòng tạo issue hoặc pull request để đóng góp.
