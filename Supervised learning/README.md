
Đa cộng tuyến (Multicollinearity) là hiện tượng các biến độc lập trong mô hình hồi quy tuyến tính có mối tương quan tuyến tính cao với nhau. Nói cách khác, một biến độc lập có thể được sử dụng để dự báo cho một hay nhiều biến độc lập khác.

Ảnh hưởng của đa cộng tuyến trong bài toán regression

Đa cộng tuyến có thể gây ra một số ảnh hưởng tiêu cực trong bài toán regression, bao gồm:

Tăng sai số chuẩn của các hệ số hồi quy: Sai số chuẩn của các hệ số hồi quy là thước đo mức độ tin cậy của các hệ số đó. Khi xảy ra đa cộng tuyến, sai số chuẩn của các hệ số hồi quy sẽ tăng lên, khiến chúng trở nên không đáng tin cậy.
Gây khó khăn trong việc ước lượng các hệ số hồi quy: Khi xảy ra đa cộng tuyến, các hệ số hồi quy thường không được ước lượng một cách chính xác.
Giảm độ chính xác của mô hình: Khi xảy ra đa cộng tuyến, mô hình hồi quy sẽ trở nên kém chính xác hơn trong việc dự báo giá trị của biến phụ thuộc.
Các phương pháp khắc phục đa cộng tuyến

Có một số phương pháp có thể được sử dụng để khắc phục đa cộng tuyến, bao gồm:

Xóa bỏ các biến độc lập có tương quan cao: Đây là phương pháp đơn giản nhất để khắc phục đa cộng tuyến. Tuy nhiên, việc loại bỏ các biến độc lập có thể làm giảm độ chính xác của mô hình.
Sử dụng phương pháp hồi quy Ridge hoặc Lasso: Phương pháp hồi quy Ridge và Lasso sử dụng các thuật toán để giảm thiểu độ lớn của các hệ số hồi quy, giúp giảm thiểu ảnh hưởng của đa cộng tuyến.
Sử dụng biến dummy: Biến dummy là biến có thể nhận hai giá trị là 0 hoặc 1. Sử dụng biến dummy có thể giúp giảm thiểu mối tương quan giữa các biến độc lập.
Ví dụ

Giả sử chúng ta có một mô hình hồi quy tuyến tính để dự đoán giá nhà, với các biến độc lập là diện tích nhà, số phòng ngủ và số tầng. Nếu diện tích nhà và số phòng ngủ có mối tương quan cao, thì sẽ xảy ra đa cộng tuyến. Trong trường hợp này, chúng ta có thể sử dụng các phương pháp trên để khắc phục đa cộng tuyến.

Chẳng hạn, chúng ta có thể loại bỏ một trong hai biến diện tích nhà hoặc số phòng ngủ. Hoặc, chúng ta có thể sử dụng phương pháp hồi quy Ridge hoặc Lasso để giảm thiểu ảnh hưởng của đa cộng tuyến.
