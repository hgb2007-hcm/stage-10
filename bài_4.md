# Thiết Kế Prompt tối ưu cho AI Assistant

## 1. Bối cảnh
Bạn là một gia sư công nghệ thân thiện, chuyên gia giải thích các khái niệm kỹ thuật phức tạp thành ngôn ngữ cực kỳ đơn giản, dễ hiểu cho sinh viên năm nhất ngành Công nghệ Thông tin. Người học đang tìm hiểu về "Mô hình IPO (Input - Process - Output) trong trang trại thông minh" nhưng cảm thấy khó hiểu.

## 2. Nội dung
Hãy giải thích khái niệm Mô hình IPO áp dụng vào hệ thống trang trại thông minh (Smart Farm) thông qua một ví dụ thực tế gần gũi (ví dụ: Hệ thống tưới cây tự động). 

## 3. Yêu cầu (Task List)
- Giải thích rõ 3 thành phần Input (Đầu vào), Process (Xử lý), và Output (Đầu ra) bằng các thuật ngữ đời thường.
- Đưa ra một kịch bản ví dụ cụ thể về cảm biến độ ẩm đất kích hoạt máy bơm nước.
-   Không cần giải thích bằng các thuật ngữ chuyên ngành phần cứng quá phức tạp hoặc code lập trình nhúng chi tiết. Giữ nội dung ngắn gọn, súc tích trong vòng 300 từ.

# Phần 2. Sản phẩm File Markdown (.md) lưu kết quả

# Giải thích Mô hình IPO trong Trang Trại Thông Minh (Smart Farm)

> **Mục tiêu:** Giúp sinh viên năm 1 hiểu bản chất của mô hình xử lý dữ liệu thông qua hệ thống tưới cây tự động.

## 1. Tổng quan về mô hình IPO
Mô hình **IPO** (viết tắt của *Input - Process - Output*) là luồng xử lý cơ bản của mọi hệ thống thông minh:
* **Input (Đầu vào):** Thu thập dữ liệu từ môi trường bên ngoài.
* **Process (Xử lý):** Phân tích, tính toán và ra quyết định dựa trên dữ liệu đầu vào.
* **Output (Đầu ra):** Thực thi hành động cụ thể để tác động lại môi trường.

---

## 2. Bảng minh họa trực quan (Ví dụ: Hệ thống tưới cây tự động)

| Thành phần IPO | Khái niệm đơn giản | Ví dụ thực tế trong Trang trại thông minh |
| :--- | :--- | :--- |
| **Input** | "Giác quan" của hệ thống | Cảm biến đo độ ẩm đất báo về mức 20% (đất đang khô). |
| **Process** | "Bộ não" suy nghĩ | Bộ điều khiển trung tâm so sánh thấy 20% < 30% (ngưỡng tối thiểu) $\rightarrow$ Ra lệnh bật máy bơm. |
| **Output** | "Hành động" thực tế | Máy bơm nước tự động bật lên để tưới ẩm cho ruộng rau. |

---

## 3. Tổng kết nhanh
* Dữ liệu đi theo một chiều từ **Nhận thông tin** $\rightarrow$ **Suy nghĩ** $\rightarrow$ **Hành động**.
* Việc hiểu rõ mô hình IPO giúp lập trình viên định hình rõ cấu trúc dữ liệu trước khi viết code cho các ứng dụng IoT nông nghiệp.