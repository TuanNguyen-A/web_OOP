*Clone dự án git 
để có thể clone được cả 2 submodule ta cần thêm --recursive
git clone --recursive

Cài đặt những thứ cần thiết để có thể chạy được dự án:
* cài đặt NodeJS về máy ở địa chỉ https://nodejs.org/en/
* mở dự án, bật terminal và chạy các lệnh sau:
    ** chạy dự án ở FE:
      - chạy: *cd FE_web* để chuyển đường dẫn sang thư mục client
      - chạy: *npm i* để khởi tạo thư mục node_modules ở client
      - chạy: *npm start* để chạy webside
    ** chạy dự án ở BE:
      - chạy: *cd BE_web* để chuyển đường dẫn sang thư mục vendor
      - chạy: *npm i* để khởi tạo thư mục node_modules ở vendor
      - chạy: *npm start* để chạy webside
