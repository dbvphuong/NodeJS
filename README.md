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
chạy trong script gõ: node + enter + nội dung cần gõ.  
chạy ngoài là mở file ở ngoài lên.  
### No SQL DB là gì ?   
cách cài đặt nosql: npm install nosql  
no sql là ứng dụng cơ sở dữ liệu.  
### Trình bày sự khác nhau giữa DBMS và RDBMS ?  
DBMS và RDBMS đều là hệ thống quản lí cơ sở dữ liệu.  
- DBMS lưu dữ liệu dưới dạng file.  RDBMS lưu dữ liệu dưới dạng bảng.  
-DBMS dùng cho tổ chức nhỏ,Vd là file system, xml,... RDBMS dùng cho tổ chức lớn, hỗ trợ nhiều người dùng,Vd là MySQL,Oracle hay SQL Server...  
### Mongo DB là gì ? Cách cấu hình Mongo BD trong express ?  
Mongo DB là 1 hệ quản trị cơ sở dữ liệu thuộc No SQL.  
npm install express  
### Thực hiện Connect node voi MongoBD ?  
trước tiên ta cài dặt thư viện mongoBD: npm install mongodb  

# Dev-tools  
### Tìm hiểu node debugger là gì ?  
debug là dừng việc thực thi chương trình tại 1 thời điểm nào đó để kiểm tra.  
### Debug một chương trình tính tích một mảng số dương, sử dụng các câu lệnh continue( c ), next( n ), repl( read eval print loop )  

### Phân biệt babel-cli, babel-presets-es2015, babel-presets-stage-2 ?  

### Sử dụng npm để install babel và các presets của babel  
cài đặt babel:  
npm install --save-dev babel-cli
### Webpack là gì ?. Ứng dụng của Webpack trong dự án NodeJS  
Webpack là một công cụ dùng để quản líc các module.  

###  Sử dụng NPM để cài đặt webpack ?. Cấu hình webpack trong file webpack.config.js.  
npm install webpack -g  

### Linter là gì ?, Cài đặt ES Lint bằng NPM  
Linter là từ chỉ chung một nhóm phần mềm có nhiệm vụ đọc code của bạn và cho bạn biết đoạn code đó có lỗi gì về cú pháp hoặc “phong cách” (code style) hay không.  
cài đặt ES LInt:  
eslint --init  
### Sử dụng ESLint test coding convention yourfile.js  

# Node core  

### Để trở thành một webserver thì hệ thống cần đảm bảo những tiêu chí gì ?  
Cần có phân cứng: cần có 1 file lưu trữ các file thành phần tạo nên 1 website(htlm,css,js,...)  
và phần mềm: URL(tên địa chỉ web), HTTP(tên phương thức để hiển thị trang web).  
### Module Pattern là gì ?  
là phương pháp triển khai code theo các module riêng biệt.  
### Các phương thức require, exports, module.exports dùng để làm gì ?  
dùng để xuất 1 file trong javascript.  
```
    var module = { exports: {} };
    var exports = module.exports;

    // your code

    return module.exports;
```
### So sánh require ES5 => import Es6, sử dụng Babel để convert từ ES6 về  ES5  

### So sánh require/import relative file, library  

### Node APIs là gì ?  

### Fs module trong NodeJS dùng để làm gì ?  
Fs module là module dùng để xử lý đọc ghi file trên Server  
### Viết  chương trình tạo, viết và đọc file ?  
Cách cài đặt module: --experimental-modules  
Cách ghi file: fs.writeFile(file, data, optionsObject, callback);  
file: đường dẫn file cần ghi  
data: nội dung cần ghi  
optionsObject: là một đối tượng gồm: encoding, mode, flag  
callback: hàm gọi sau khi ghi xong  

### Sự khác biệt giữa Fs và Fs synchronous là gì ?
hàm Fs(bất đồng bộ) cần callback khi gọi hàm xong.
### Http module trong NodeJS dùng để làm gì ?  
Tọa 1 cổng http sever kết nối với client
### Tạo một server đơn giản lẳng nghe ở cổng 8000, request trả lại "Hello world" sử dụng Http APIs  
```
// khai báo sử dụng module HTTP
var http = require('http');

//Khởi tạo server chạy cổng 8000
http.createServer(function (request, response) {
    //request: yêu cầu khách hàng. response: trả về khách hàng
    response.write('hello world!');
    response.end();
}).listen(8000);
```
### Event emitter trong nodejs là gì ?. Kể tên và nêu chức năng của các phương thức trong lớp Event emitter  
khi các đối tượng sinh ra sự kiện thì đối tượng đó chính là event emitter.  
Các chức năng của các phương thức trong lớp Event emitter:  
```
1	addListener(event, listener)
Thêm một Listener vào phần cuối của mảng các Listener cho một sự kiện cụ thể
2	on(event, listener)
Thêm một Listener vào phần cuối của mảng các Listener cho một sự kiện cụ thể
3	once(event, listener)
Thêm một One-Time Listener cho sự kiện. Listener dạng này sẽ chỉ được gọi khi sự kiện được kích hoạt, sau đó nó sẽ bị xóa
4	removeListener(event, listener)
Xóa một Listener ra khỏi mảng các Listener cho một sự kiện nào đó.
5	removeAllListeners([event])
Xóa tất cả Listener của một sự kiện
6	setMaxListeners(n)
Theo mặc định, lớp EventEmitters sẽ in một lời cảnh báo nếu bạn thêm nhiều hơn 10 Listener cho một sự kiện cụ thể. Việc này khá hữu ích, bởi vì nó sẽ giúp tìm ra các lỗi gây rò rỉ bộ nhớ. Tất nhiên, không phải tất cả các Emitters đều cần được giới hạn với con số là 10. Hàm này cho phép bạn tăng con số đó. Thiết lập nó về 0 để không giới hạn lượng Listener cần thêm
7	listeners(event)
Trả về một mảng bao gồm các Listener cho một sự kiện cụ thể nào đó
8	emit(event, [arg1], [arg2], [...])
Thực thi từng Listener với các tham số đã cho. Trả về true nếu sự kiện có các Listener, và false nếu không có
```
### Chức năng của Event Loop là gì ?.  Event loop trong nodeJs có giống Event loop trong engine V8 hay không ?  
là đọc tất cả các dòng code, sau đó thực thi lần lượt các dòng code JS trc, sau đó mới thực thi code trong engine V8.  
không khác gì.
###  Trình bày các khái niệm: Event Driven, Non - Blocking trong nodeJS  
mô hình event Driven là toàn bộ xử lí của sever sẽ bằng 1 vòng lặp event loop trung tâm.  
Non - blocking là kiểm tra những kết nối có sự kiện để trả về khách hàng, nếu không có dữ liệu thì thông báo lỗi cho khách hàng.  
### Phân biệt giữa asynchronous và Non - Blocking trong NodeJS ?  
Non-blocking socket là dạng kết nối asynchronous.  

# Express  
### Express là gì ?. Nếu chức năng của framework này ?  
express là 1 framework nhỏ , được xây dựng trên nền tảng nodejs, để cung cấp tính năng ptrien web.  
### WebServices la gi ? Có bao nhiêu loại: RESTfull, SOAP  
Web Serice là 1 ứng dụng client server giao tiếp với nhau qua giao tiếp HTTP/HTTPS.  
RESTful (REpresentational State Transfer) là một kiểu thực hiện Web Service được viết dựa trên kiến trúc REST.  
SOAP (stands for Simple Object Access Protocol) là kiểu thực hiện web Service.  

### Có các loại RESTFull method nào ?  

### Các bước tạo ra web server đơn giản bằng Express ?  

### Routing là gì ?  

### Nếu các khái niệm Route method, Route path, Route param ?  

### Template engine là gì ?, trình bày cách để tạo template trong express  

### Middleware là gì ?, Nếu các chức năng của middleware  

### Nêu tác dụng của phương thức use, all, next()  

