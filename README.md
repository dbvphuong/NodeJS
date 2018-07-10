# NodeJS  
# NodeJS introduction  
### NodeJs là gì ?  
NodeJS là 1 nền tảng phát triển độc lập dựa trên javascrip runtime.
### Điểm mạnh và điểm yếu của NodeJs ?  
- Không đồng bộ.  
- Chạy rất nhanh, tốn ít ram.  
- Ứng dụng thời gian thực.  
### V8 Engine là gì ?  
là trình thông dịch thực thi mã javascript.  
### Nêu mô hình client - server ?. Cụ thế mô hình client server ở trong web service  
Mô hình client-sever là mô hình 1 máy chủ liên kết với nhiều khách hàng, máy chủ đó sẽ nhận dữ liệu từ khách hàng và xử lí đáp lại khách hàng.  
### Thế nào là code js ở phía server ?  
Render react ở phía sever giúp trang web của bạn load 1 cách nhanh hơn.  
### Cài đặt node và kiểm tra phiên bản của node và npm ?  
ok
### Use node CLI to run js script ?  

### Viết script để lắng nghe cổng 3000 trả về Hello World ?  

# node packaged modules  

### NPM là gì ?. Nêu các lợi ích khi sử dụng trình quản lí package ?  
NPM(NodeJS Project Manager) là 1 thư viện quản lí các file, modul
### File package.json dùng để làm gì ? Cách tạo file và nêu chức năng của từng trường trong file package.json  
file package.json là 1 object dùng để lưu trữ thông tin thư mục.  
Cách tạo:  
- tạo 1 file .js  
- gõ lệnh npm init.  

name: Tên của Project  
version: Version của Project  
description: Mô tả cho Project  
main: File chạy chính (chạy đầu tiên) của Project  
scripts: Danh sách các khai báo cấu hình bổ sung cho npm. Như trong chuỗi trên thì giá trị của test chính là câu thông báo và dừng chương trình khi bị lỗi.  
author: Tên tác giả của Project  
license: License của Project, giá trị mặc định là ISC.    
### Dependency la gì ?, devDependencies là gì ?  
Dependency là dùng để chương trình chạy được các lệnh js.  
devDependencies là để khắc phục, hỗ trợ chương trình chạy nhanh hơn.  
### Tự tạo file package.json bằng npm init ?  

### Cài đặt thư viện bằng npm add dependencies trong file package.json  
npm install ten_file
### Xoá thư viện trong file package.json ?  
npm unstall ten_file
### Chạy lệnh Js trong script, nhận xét sự khác biệt giữa chạy code trong script và ngoài script  

### No SQL DB là gì ?   

### Trình bày sự khác nhau giữa DBMS và RDBMS ?  

### Mongo DB là gì ? Cách cấu hình Mongo BD trong express ?  
npm install express
### Thực hiện Connect node voi MongoBD ?  
