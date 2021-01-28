# Reflections-module2

Buổi 2 ngày 26-1-2021

Hôm nay hạc được :
Chèm 1 file PHP a vào 1 file PHP b với Require / include
phân biệt 2 ông này
require và include đề để đưa 1 ông file PHP a vào bên trong ông PHP b
Khác nhau: Khi gặp lỗi trong quá trình thưc hiện ông require đưa ra cảnh báo lỗi và dừng luôn trương trình còn ông include sẽ tạo ra cảnh báo và chạy trương trình đến phần bị lỗi thì dừng
require_once : thực hiện require là thêm ông PHP a vào ông PHP b, chính vì vậy khi require lần 2(cái này do ông code quên ) tức thêm lần 2 sẽ có nhiều thứ bị trùng tiêu biểu tên hàm ---> lỗi!!! Do vậy ông require_once giúp check lần thực hiện require_once lần 2 lần 3 đều được hiểu là đã require rồi và không thực hiện lại nữa
include_once: Giống ông require_one include_once lần 2 -3 ... chỉ tính 1 lần
Ông nào hay quên thì xài require_once và include_once để nó kiểm tra hộ!
Mảng associative
Ta dùng vòng lặp "foreach" để duyệt mảng
foreach( $nameArry as $key => $v)




Buổi 3 ngày 27/1/2021

Từ khoá class được sử dụng để khai báo lớp
Từ khoá new được sử dụng để khởi tạo đối tượng
Phương thức khởi tạo (constructor) là phương thức giúp khởi tạo các đốitượng
Các phương thức cho phép thay đổi giá trị của thuộc tính được gọi là setter, các phương thức cho phép lấy về giá trị của thuộc tính được gọi là getter
Access modifier là các từ khoá được sử dụng để quy định mức độ truy cập đến lớp và các thành phần của lớp
Các mức truy cập:
public: có thể truy cập từ bất cứ đâu
private: các phương thức và thuộc tính chỉ được phép truy xuất trong cùng một lớp
protected: các phương thức và thuộc tính được phép truy xuất trong cùng một lớp và ở các lớp con (kế thừa)
Từ khoá this được sử dụng để đại diện cho đối tượng hiện tại
