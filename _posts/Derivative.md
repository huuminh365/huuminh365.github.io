# Đạo hàm là gì?

Trong quá trình học cấp 3 mình nhận ra là có 1 chủ đề khá hay nhưng có lẽ mọi người sẽ chỉ học công thức, áp dụng giải toán nhiều hơn là có thể hiểu rõ về nó, đó chính là ĐẠO HÀM, và trong quá trình học ML của mình thì lại liên quan khá nhiều về kiến thức này (cụ thể là các phương pháp backpropagation hay gradient descent), thế nên mình đã quyết định tìm hiểu kĩ về phần này để viết lại (một phần để quên có cái đọc lại thay vì phải SEARCH lại hêhe).

Chà, đầu tiên ta cần ôn lại một vài kiến thức cơ bản chút đã.

## 1. Hệ số góc(tiếng anh là gradient) là gì?
Trong mặt phẳng 0xy, hệ số góc đường thẳng (d) là a = $tan(\alpha)$, trong đó α là góc tạo bởi đường thẳng (d) và chiều dương của trục Ox:

Nếu a > 0 thì $0 <\alpha < 90$ 
Nếu a < 0 thì $90 < \alpha < 180$

<img src="/assets/derivative/alpha.png">

Bây giờ, ta chọn một hàm y(x) với đồ thị bất kì( để dễ nhìn thì ta sẽ chọn 1 hàm bậc 2 như hình), nhìn từ một góc nhìn khác thì đường trơn mượt y(x) đã được cấu tạo bởi nhiều đường thẳng nhỏ, mà mỗi đoạn là một tiếp tuyến với y(x).