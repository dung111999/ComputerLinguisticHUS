# Kiến trúc hệ thống Yii2
 Các ứng dụng Yii được tổ chức dựa theo mẫu thiết kế MVC. Models chứa nghiệp vụ logic, truy xuất database và định nghĩa các quy tắc xác thực dữ liệu; views đảm nhận việc hiển thị thông tin của model và controllers có nhiệm vụ điều hướng các yêu cầu và chuyển các tương tác giữa models và views
 * common			Dùng chung cho frontend và backend
    * config/              Cấu hình được chia sẻ 
    * mail/                Các files cho email
    * models/              Các models
    * tests/               Các test cho các class

 * console			Dùng cho ứng dụng giao diện bảng điều khiển
    * config/              Cấu hình bảng điều khiển
    * controllers/         Bộ điều khiển giao diện sử dụng lệnh
    * migrations/          Database migrations
    * models/              Các lớp riêng cho bảng điều khiển
    * runtime/             Các file trong thời gian chạy

 * backend			Thư mục dùng cho admin
    * assets/              Các đường dẫn đến file JavaScript và CSS
    * config/              Cấu hình backend
    * controllers/         Chứa các class controller
    * models/              Chứa các lớp model
    * runtime/             Chứa các file được sinh ra trong quá trình chạy
    * tests/               Các test cho các class
    * views/               Chứa các files về view
    * web/                 Thư mục gốc ứng dụng web

 * frontend			Thư mục dùng cho người dùng
    * assets/              Các đường dẫn đến file JavaScript và CSS
    * config/              Cấu hình backend
    * controllers/         Chứa các class controller
    * models/              Chứa các lớp model
    * runtime/             Chứa các file được sinh ra trong quá trình chạy
    * tests/               Các test cho các class
    * views/               Chứa các files về view
    * web/                 Thư mục gốc ứng dụng web

 * vendor/                  Chứa các thư viện mở rộng của bên thứ ba

 * environments/            Chứa các môi trường được ghi đè(bao gồm dev và product)
