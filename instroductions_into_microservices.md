# Giới thiệu về microservices

Hầu hết mọi người nghĩ một kiến trúc microservices là tốt cho việc xây dựng 
các ứng dụng có thể mở rộng. Điều này không phải sai nhưng chúng ta nên có một 
cái nhìn sâu hơn ở đó kiến trúc này có chiếu hướng quy mô tốt nhất. 
Chiều hướng đi vào tâm trí con người đầu tiên là chiều hướng của tải trọng.
Điều này có nghĩa là có thể thêm các tài nguyên bổ sung để giữ hiệu suất tương 
tự khi khối lượng công việc tăng lên. Trong thực tế, đây không phải là những gì 
microservices là tốt ở nơi đầu tiên.

Chiều hướng của quy mô kiến trúc microservices là chiều hướng chức năng. 
Nói cách khác, rất dễ dàng để giới thiệu các chức năng và chất lượng mới ở bất kỳ
giai đoạn nào của sản phẩm. Điều này dẫn đến việc xem xét rằng nó chỉ đơn giản 
có thể làm để vấn đề tải sắp xảy ra với các yêu cầu mới.

Bài viết này giải thích mục đích và rủi ro của kiến trúc microservices. Nó còn 
đưa ra một vài gợi ý một kiến trúc phải đáp ứng các mục đích như thế nào. Tại một
số điểm nó cũng so sánh microservice với kiến trúc hướng dịch vụ truyền thông. 

### Mục đích 1: Giảm thiểu chi phí thay đổi

Giảm thiểu chi phí cho yêu cầu mới hoặc yêu cầu thay đổi 