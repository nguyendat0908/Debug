
# Phân loại bugs?

## 1. Lỗi cú pháp (syntax)
- Là lỗi do "gõ sai/code sai", đặc điểm của lỗi này:
  - IDE báo lỗi ngay tại chỗ sai trong quá trình code
  - Khi chạy chương trình, IDE thông báo lỗi tại dòng code đang sai
## 2. Lỗi logic
- Quá trình code IDE không thông báo lỗi
- Chạy chương trình bình thường không báo lỗi  
=> Kết quả kiểm tra lại trả ra kết quả không mong muốn

# Khái niệm Logs?
Logs là các "thông báo/message" được hiện ở terminal/file/browsers trong quá trình
chạy phần mềm.  

**1. Info**
- Thường hiển thị với màu xanh hoặc màu trắng
- Cung cấp thông tin về "trạng thái ứng dụng". Thông thường, loại logs này do
"developer" tạo ra với mục đích theo dõi ứng dụng  
Ví dụ: khi chạy ứng dụng react thành công => hiển thị thông báo ứng dụng đã chạy trên
port bao nhiêu...
- Với info, chúng ta chẳng cần làm gì cả (tức là ko cần fix bugs)

**2. Warning**
- Thường hiển thị với màu vàng
- Cung cấp các cảnh báo về ứng đang chạy
- Đa phần là do hệ thống tạo ra
- Không phải warning nào cũng có hại và phải fix ngay lập tức.  
Ví dụ: warning về hết RAM...  
=> Với warning, chúng ta có thể có hoặc không fix. Nếu fix được thì ứng dụng "perfect"

**3. Error**
- Thường hiển với màu đỏ
- Cung cấp lỗi về quá trình thực thi chương trình/ứng dụng
- Đa phần là do hệ thống tạo ra
- Nếu error làm hệ thống không chạy được => bắt buộc phải fix
