---
title: "Event 1"
date: 2026-05-23
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# BÀI THU HOẠCH: TỰ ĐỘNG HÓA CÔNG VIỆC VỚI TRỢ LÝ AI AMAZON Q VÀ MCP
### I. Mục tiêu & Bối cảnh tổng quan
Thông qua các sự kiện công nghệ (chủ đề về Amazon Q, giao thức MCP và Hội nghị cộng đồng FCAJ), tôi đã có cơ hội tiếp cận bức tranh toàn cảnh về cách AI đang tái định hình môi trường doanh nghiệp. Các nội dung không chỉ dừng lại ở bề nổi của các công cụ AI tạo sinh, mà còn đi sâu vào kiến trúc hệ thống, tư duy phát triển sản phẩm (product-driven) và các rào cản bảo mật khắt khe khi triển khai thực tế.

### II. Điểm nhấn Công nghệ & Kỹ thuật
### 1. Từ Single Agent đến Kiến trúc Multi-Agent

Các LLM hiện tại rất thông minh nhưng một Agent đơn lẻ sẽ bị giới hạn về Context Window và dễ quá tải trước các bài toán phức tạp.

Giải pháp tối ưu là xây dựng hệ thống Multi-Agent (như mô hình Hội đồng tín dụng), trong đó chia nhỏ thành các Agent chuyên biệt (Phân tích tài chính, Đánh giá rủi ro, Điều phối...). Việc phân chia này giúp hệ thống xử lý song song và có khả năng phản biện chéo.

### 2. Giao thức MCP và Khả năng Thực thi (Action)

Công thức cốt lõi: Agent = LLM + Action/Function (MCP).

Giao thức Model Context Protocol (MCP) chính là chiếc cầu nối kỹ thuật cho phép AI vượt ra khỏi ranh giới chat hỏi-đáp thông thường, kết nối trực tiếp với các ứng dụng bên ngoài (Jira, Gmail, Teams) để tự động hóa các quy trình thô (như trực quan hóa dữ liệu, gửi email phân công sau cuộc họp).

### 3. Kỹ nghệ Ngữ cảnh (Context Engineering)

Việc "bơm" kiến thức cho AI không phải là nhồi nhét hàng trăm trang PDF thô. Thay vào đó, cần trích xuất những "tinh túy" nghiệp vụ từ chuyên gia (Knowledge Transfer) để tạo ra ngữ cảnh chuẩn mực, giúp LLM xử lý chính xác và giảm thiểu tính bất định (Hallucination/Inference optimization).

### III. Tư duy Nghiệp vụ & Vận hành Doanh nghiệp (Enterprise-grade AI)
### 1. Giải quyết bài toán bằng ROI (Return on Investment)

Công nghệ chỉ là phương tiện. Bất kỳ giải pháp AI nào (dù tốn kém hàng tỷ đồng) đều phải trả lời được: Phục vụ ai? Tại sao phải dùng? và Lợi ích thu về là gì?

"Numbers speak louder than words" - Mọi đề xuất công nghệ lên cấp quản lý đều phải được chứng minh bằng con số thực tế về mức độ hồi vốn thay vì những lời hứa hẹn.

### 2. Bảo mật và Trách nhiệm (Audit & Compliance)

Trong môi trường doanh nghiệp (đặc biệt là tài chính), bảo mật là tối thượng. Việc cắm các công cụ ngoại vi phải được kiểm soát gắt gao.

Hệ thống cần thiết lập các rào chắn (Guardrails) kiểm tra Input/Output để chống Prompt Injection và quản lý chặt vòng đời API Key.

Con người là chốt chặn cuối cùng: Dù AI có tự hành đến đâu, người kỹ sư và người phê duyệt hệ thống vẫn là bên chịu trách nhiệm trước pháp luật về các quyết định được đưa ra (như duyệt khoản vay).

### IV. Định hướng ứng dụng và Bài học cá nhân
Vững nền tảng Software Engineering: AI không thay thế được các kiến thức cốt lõi (Backend, Database, Cloud Infrastructure, Security). Đây vẫn là yếu tố quyết định để đưa một project từ "chạy demo ở nhà" lên môi trường Production thực tế của ngân hàng/doanh nghiệp.

Thấu hiểu các bên liên quan (Stakeholders): Cần nắm rõ KPI của các phòng ban khác (Business, Security) để giao tiếp, xin cấp phép và phối hợp làm việc nhóm mượt mà hơn.

Thực hành tự động hóa: Áp dụng Amazon Q và tùy biến các MCP Server để tự động hóa quy trình cá nhân. Khi thiết kế hệ thống, sẽ ưu tiên chia nhỏ logic theo hướng Multi-Agent cho các tác vụ phức tạp.

### V. Trải nghiệm & Góc nhìn thực tế tại sự kiện
Các phần chia sẻ thực chiến từ các diễn giả (như anh Hải An, chị Cát Vy...) thực sự đã khai mở tư duy của tôi về khoảng cách giữa lý thuyết và thực tiễn triển khai "Enterprise-grade AI". Được tận mắt quan sát luồng xử lý tự động của Amazon Q hay bóc tách kiến trúc phân tích tín dụng cho Startup giúp tôi nhận ra sự khắt khe, tính kỷ luật cũng như trách nhiệm nặng nề của một kỹ sư phần mềm hiện đại. Sự kiện cũng là cơ hội tuyệt vời để giao lưu, học hỏi từ những người đi trước.

Nhìn chung, chuỗi sự kiện không chỉ cung cấp những nền tảng kỹ thuật chuyên sâu mà còn giúp tôi thay đổi hoàn toàn cách tư duy: Từ việc chỉ tập trung viết code, sang việc thiết kế các giải pháp tự động hóa an toàn, đáng tin cậy và thực sự mang lại giá trị đo lường được cho doanh nghiệp.

![Hình ảnh tham gia sự kiện](/images/4-EventParticipated/event_1.jpg)