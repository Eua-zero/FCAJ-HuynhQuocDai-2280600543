---
title: "Event 3"
date: 2026-06-20
weight: 3
chapter: false
pre: " <b> 4.3. </b> "
---

# BÀI THU HOẠCH: FCAJ - TUẦN LỄ XÂY DỰNG ĐẠI LÝ AI 

### I. Mục tiêu & Bối cảnh tổng quan
Vào sáng ngày 25/07/2026, tôi đã tham dự sự kiện **"FCAJ - Agentic AI Build Week"** tại Tầng 26, Tòa nhà Tài chính Bitexco. Đây không phải là hiện trường thi đấu, mà là một buổi sự kiện chia sẻ (sharing session) đầy cảm hứng nhằm tường thuật lại hành trình của những đội chiến thắng trong cuộc thi Buildathon về Agentic AI lớn nhất khu vực ASEAN. 

Với tinh thần **"Show Up. Build. Pitch. WIN!"**, các diễn giả và đội thi đã mở ra một bức tranh chân thực về việc AI đang bước ra khỏi giai đoạn chatbot thông thường để trở thành các "Đại lý" (Agent) tự trị, giải quyết trực tiếp các bài toán hạ tầng và nghiệp vụ doanh nghiệp khắt khe.

### II. Điểm nhấn Công nghệ & Giải pháp từ 5 Đội thi Tiêu biểu
Qua các bài thuyết trình tại sự kiện, tôi đã học hỏi được 5 mô hình kiến trúc thực tiễn đáng kinh ngạc được xây dựng chỉ trong 24 giờ:

**1. Đội OneTeam (Giải Nhất) - Dự án KFC Bot Agent**
- **Bài toán:** Trợ lý AI hỗ trợ đặt hàng qua hội thoại đa kênh, giúp chống "rớt đơn" bằng cách cho phép khách hàng đặt trực tiếp trên Zalo/WhatsApp thay vì phải tải app.
- **Kỹ thuật:** Ứng dụng Amazon Bedrock AgentCore để thay thế 60% mã nguồn hạ tầng, đạt độ trễ siêu thấp (3-5 giây) và tối ưu chi phí xuống mức cực rẻ: chỉ **0.006 USD/đơn hàng**. 

**2. Đội Signal Scout (Giải Nhì) - Nền tảng Trinh sát Tín hiệu Chiến lược**
- **Bài toán:** Giúp các nhóm chiến lược công ty thu thập thông tin phân mảnh từ đối thủ, xâu chuỗi thành phân tích trực quan.
- **Kỹ thuật:** Sử dụng công cụ TinyFish để vượt qua lớp tường đăng nhập (login wall) nhằm lấy dữ liệu báo cáo nội bộ, sau đó xuất ra Dashboard kèm theo bằng chứng cụ thể để hỗ trợ ra quyết định.

**3. Đội Blank - Dự án SA Professional AI Native App**
- **Bài toán:** Tự động hóa công việc cho Kiến trúc sư giải pháp (Solution Architect).
- **Kỹ thuật:** Đọc tài liệu yêu cầu (BRD/PRD) bằng ngôn ngữ tự nhiên, tự động vẽ sơ đồ đám mây trên Draw.io, bóc tách chi phí, sinh mã nguồn hạ tầng Terraform (IaC) và triển khai (deploy) thẳng lên AWS. Hệ thống tích hợp strict typing để kiểm soát AI không dùng các dịch vụ cấm.

**4. Đội 3K (3KA) - Dự án S.H.E.P.H.E.R.D**
- **Bài toán:** Hệ thống đánh giá, phát hiện rủi ro và điều phối luồng người thông minh tại sân bay, siêu thị.
- **Kỹ thuật:** Ứng dụng thị giác máy tính (YOLO, ByteTrack) kết hợp video trực tiếp (Kinesis Video Streams). Bedrock AgentCore liên tục tính toán mật độ, dự báo ùn tắc và đưa ra cảnh báo chủ động cho nhân viên.

**5. Đội Six Pillar - Dự án Adaptive Workflow Engine (AML)**
- **Bài toán:** Hệ thống chống rửa tiền cho ngân hàng/sàn giao dịch, giảm thiểu tỷ lệ cảnh báo sai (lên tới 90-95%) của luồng xử lý truyền thống.
- **Kỹ thuật:** Xây dựng hệ thống Multi-agent chia thành 3 khâu: hồ sơ KYC, dòng tiền, và lệnh cấm vận. AI tổng hợp bằng chứng và đề xuất hành vi. Hệ thống áp dụng chuẩn bảo mật Enterprise Trust (KMS, GuardDuty, Security Hub) và kiểm duyệt qua Human-in-the-loop.

### III. Tiêu chuẩn Vận hành & Bảo mật Doanh nghiệp (Enterprise-grade)
- **Bài toán Chi phí và ROI:** Đội OneTeam đã chứng minh sự xuất sắc khi tối ưu chi phí AI xuống mức 0.006 USD/đơn hàng. Ngược lại, những sai lầm cũng phải trả giá đắt (có đội vọt lên 48 USD tiền SageMaker trong 3 tiếng). Một sản phẩm doanh nghiệp phải minh bạch chi phí (như bảng dự toán của Signal Scout) và không bị "cháy" token.
- **Bảo mật Chuẩn Doanh nghiệp:** Đội Six Pillar mang đến bài học lớn về bảo mật khi tích hợp hệ thống quản lý khóa KMS, GuardDuty và Security Hub để phát hiện tấn công mạng, khẳng định AI tài chính phải luôn đi kèm với phòng thủ vững chắc.
- **Hỗ trợ Quyết định (Human-in-the-loop):** Dù là hệ thống chống rửa tiền (AML) hay điều phối đám đông, AI chỉ đóng vai trò phân tích bằng chứng. Quyết định cuối cùng (Khóa tài khoản, điều phối an ninh) vẫn cần sự phê duyệt của con người.

### IV. Định hướng ứng dụng và Bài học cá nhân
- **Quản lý quy mô (Scope Management):** Khả năng demo thành công quyết định tới 70% cơ hội chiến thắng. Lời khuyên xương máu là áp dụng triệt để tư duy MVP: *"Một sản phẩm nhỏ nhưng hoàn thiện luôn tốt hơn những ý tưởng lớn lao nhưng hỏng hóc"*.
- **Cứ đăng ký đi (Just sign up):** Nỗi sợ "không đủ giỏi" hay "sợ thất bại" là rào cản lớn nhất. Việc dám dấn thân và có mặt đã là một nửa của sự thành công. 
- **Mở rộng mối quan hệ (Networking):** Giá trị cốt lõi không nằm ở giải thưởng, mà ở cơ hội giao lưu cùng các cố vấn (mentor) và các lập trình viên tài năng để mở rộng mạng lưới quan hệ.

### V. Trải nghiệm & Góc nhìn thực tế tại sự kiện
Lắng nghe màn tường thuật lại, tôi cảm nhận rõ "chuyến tàu lượn siêu tốc" về mặt cảm xúc của các đội thi trong 24 giờ Hackathon. Những bài học đắt giá nhất lại đến từ chính sự hỗn loạn:

- **Sự khắc nghiệt và những sự cố "để đời":** Các thí sinh đã phải thức đến 3-4 giờ sáng, sống sót nhờ bò húc (Red Bull) và gà rán. Trạng thái thiếu ngủ dẫn đến vô số sai lầm dở khóc dở cười: quên commit code, đẩy nhầm tệp chứa biến môi trường (`.env`) lên public GitHub.
- **Vượt qua rào cản và cái tôi:** Các đội thường là sự chắp vá từ nhiều sinh viên. Đội Quán quân OneTeam là một ví dụ kinh điển với 5 thành viên sở hữu đa dạng ngôn ngữ (tiếng Anh chuẩn Ấn Độ, Mỹ, tiếng Việt). Dù bất đồng hay cãi vã, họ đã học được cách hạ cái tôi cá nhân, phân chia công việc minh bạch để cùng nhau vô địch.
- **Tư duy kiến tạo tương lai:** Như ông Joseph Marazota chia sẻ, những người trẻ tham gia Hackathon hôm nay không bị giới hạn bởi những "hành trang cũ" của 20 năm trước. Họ đang nắm trong tay cơ hội mang đến những mô hình tư duy mới để kiến tạo tương lai công nghệ.

![Hình ảnh tham gia sự kiện](/images/4-EventParticipated/event_3.jpg)