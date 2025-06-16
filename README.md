# Beauty Services Booking & Management System

Hệ thống đặt lịch và quản lý dịch vụ làm đẹp đa nền tảng.

## Công nghệ sử dụng

- Frontend: HTML, CSS, JavaScript
- Database: Firebase Realtime Database
- Authentication: Firebase Authentication
- Storage: Firebase Storage

## Cấu trúc thư mục

```
booking-management-system/
├── src/                    # Source code chính
│   ├── js/                # JavaScript files
│   │   ├── auth/         # Authentication logic
│   │   ├── booking/      # Booking system
│   │   ├── services/     # Services management
│   │   ├── staff/        # Staff management
│   │   └── utils/        # Utility functions
│   ├── css/              # Stylesheets
│   └── images/           # Images
├── tests/                # Test files
│   └── firebase/        # Firebase connection tests
├── scripts/             # Python scripts for data processing
├── config/              # Configuration files
│   └── firebase_config.js  # Firebase configuration
└── index.html          # Main entry point
```

## Cài đặt

1. Clone repository:
```bash
git clone git@github.com:quanglong08/Multi-platform-Booking-Management-System-for-Beauty-Services.git
```

2. Cấu hình Firebase:
- Tạo project trên Firebase Console
- Cập nhật cấu hình trong `config/firebase_config.js`

3. Chạy ứng dụng:
- Mở file `index.html` trong trình duyệt
- Hoặc sử dụng local server

## Testing

Để test kết nối Firebase:
1. Mở file `tests/firebase/test_realtime.html` trong trình duyệt
2. Kiểm tra các chức năng:
   - Kết nối database
   - Ghi dữ liệu
   - Đọc dữ liệu
   - Real-time updates

## Đóng góp

Mọi đóng góp đều được hoan nghênh. Vui lòng tạo issue hoặc pull request để đóng góp.
