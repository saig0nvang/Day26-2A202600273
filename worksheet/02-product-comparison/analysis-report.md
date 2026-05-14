# Phân tích Sản phẩm AI: Gemini vs ChatGPT trong Nghiên cứu Học thuật

**Nhóm thực hiện:** Phạm Việt Anh (2A202600273) & Hoàng Đức Nghĩa (2A202600371)
**Ngành:** A — Tìm kiếm

---

## S1 — PRODUCT MOMENT (Khoảnh khắc sản phẩm)

### 1.1. Bảng so sánh
| Yếu tố | Sản phẩm A: Gemini | Sản phẩm B: ChatGPT |
|---|---|---|
| **URL** | https://gemini.google.com | https://chat.openai.com |
| **Entry point** | Giao diện chat tích hợp hệ sinh thái Google | Giao diện chat tối giản, tập trung vào text |
| **Ý định user** | Tìm kiếm thông tin nhanh, cập nhật từ Google Search | Tổng hợp, phân tích sâu và tra cứu có nguồn |
| **Surface chính** | Web Chat interface | Web Chat interface |

### 1.2. Nhiệm vụ chung
- **Nhiệm vụ:** Đánh giá khả năng tìm kiếm, tổng hợp số liệu có dẫn nguồn phục vụ nghiên cứu học thuật.
- **Câu prompt chính xác:** "Yêu cầu: 1. Nêu ít nhất 5 số liệu hoặc sự kiện cụ thể. 2. Mỗi số liệu/sự kiện phải có nguồn và ngày. 3. So sánh vai trò của AI chatbot với Google Search truyền thống. 4. Chỉ ra 2 rủi ro khi dùng AI chatbot để tìm kiếm. 5. Kết luận: sinh viên nên dùng AI chatbot hay Google Search cho research học thuật?"

### 1.3. Bằng chứng tham chiếu
- Ảnh `product-A-1-entry.png`: Giao diện ban đầu của Gemini, gợi ý sử dụng prompt.
- Ảnh `product-B-1-entry.png`: Giao diện ban đầu của ChatGPT.

### 1.4. Nhận định
Cả hai sản phẩm đều chọn chat interface làm điểm chạm đầu tiên (entry point). Tuy nhiên, Gemini có xu hướng cá nhân hóa hiển thị tích hợp sẵn với tài khoản Google, trong khi ChatGPT giữ giao diện thuần túy tập trung vào hộp thoại prompt.

---

## S2 — WORKFLOW EVIDENCE (Bằng chứng quy trình)

### 2.1. Luồng người dùng
- **TRƯỚC:** Sinh viên có nhu cầu tổng hợp số liệu cho bài luận, thay vì dùng Google Search thủ công qua nhiều trang.
- **TRONG (Gemini):** Nhập prompt → Xử lý → Đưa ra text kết hợp định dạng (bullet points) nhanh chóng.
- **TRONG (ChatGPT):** Nhập prompt → Kích hoạt tìm kiếm web (Search) → Tổng hợp nội dung → Trả kết quả kèm trích dẫn (citations).
- **SAU:** Đọc kết quả, kiểm tra nguồn dẫn và copy vào báo cáo.

### 2.2. 3 Friction Areas (Vùng ma sát)
- **Physical load (Thao tác vật lý):** Cả hai đều thấp (chỉ 1 click để gửi). Tuy nhiên, để kiểm tra nguồn, ChatGPT tiện hơn vì có citation dạng click trực tiếp `[1]`, `[2]`.
- **Cognitive burden (Tải nhận thức):** Thấp. Không cần học prompt engineering phức tạp, câu hỏi tự nhiên vẫn xử lý được.
- **User workarounds (Mẹo khắc phục):** Với Gemini, người dùng thường phải dùng chức năng "Double-check response" (biểu tượng chữ G) để verify lại nguồn vì nó ít khi gắn link trực tiếp vào text như ChatGPT.

### 2.3. Bằng chứng tham chiếu
- Ảnh `product-A-2-input.png` & `product-A-3-output.png` (Gemini xử lý prompt).
- Ảnh `product-B-2-input.png` & `product-B-3-output.png` (ChatGPT xử lý prompt).

### 2.4. Nhận định
ChatGPT giảm friction tốt hơn cho tác vụ "nghiên cứu học thuật" vì cung cấp luồng kiểm chứng nguồn mượt mà hơn (tích hợp citation trực tiếp), trong khi Gemini đòi hỏi thêm thao tác double-check.

---

## S3 — OUTPUT & TRUST (Kết quả & Độ tin cậy)

### 3.1. Bảng chất lượng output
| Tiêu chí | Gemini (A) | ChatGPT (B) |
|---|---|---|
| **Đúng nội dung yêu cầu?** | Có đủ 5 phần | Có đủ 5 phần |
| **Độ chi tiết của số liệu** | Nêu số liệu cơ bản | Số liệu chi tiết kèm phân tích |
| **Đầy đủ/thiếu phần?** | Đầy đủ | Đầy đủ |

### 3.2. Bảng 6 tín hiệu đáng tin
| Tín hiệu | Gemini (A) | ChatGPT (B) |
|---|---|---|
| **Citation (Dẫn nguồn)** | Yếu (Chỉ khi bấm double-check) | Tốt (Citations inline) |
| **Control (Sửa đổi)** | Có (Modify response, drafts) | Có (Edit prompt) |
| **Confidence indicator** | Có (Google search verification) | Không rõ ràng |

### 3.3. Bằng chứng tham chiếu
- `product-A-3-output.png`: Kết quả của Gemini thiếu citation cụ thể trên text.
- `product-B-4-source.png`: ChatGPT hiển thị rõ danh sách nguồn đã tham khảo.

### 3.4. Nhận định
Về độ tin cậy (Trust), ChatGPT vượt trội hơn hẳn nhờ khả năng trích dẫn nguồn (citation) rõ ràng, minh bạch - một yếu tố sống còn trong nghiên cứu học thuật. Gemini dù tốc độ sinh chữ nhanh nhưng tính "hộp đen" cao hơn, buộc người dùng tự kiểm chứng lại.

---

## S4 — BUSINESS / USAGE SIGNAL (Tín hiệu kinh doanh)

### 4.1. Mô hình giá
| Yếu tố | Gemini (A) | ChatGPT (B) |
|---|---|---|
| **Gói miễn phí** | Có (Model Gemini Flash/Pro) | Có (GPT-4o mini / GPT-4o giới hạn) |
| **Giá thấp nhất** | $20/tháng (Gemini Advanced) | $20/tháng (Plus) |
| **Quota / Limit** | Rộng rãi ở bản free | Giới hạn số tin nhắn GPT-4o |

### 4.2. Cost-Capability-Speed
- **Gemini:** COST $0 / CAPABILITY Tra cứu siêu nhanh / SPEED Cực cao.
- **ChatGPT:** COST $0 (có giới hạn) / CAPABILITY Suy luận, trích dẫn tốt / SPEED Trung bình.

### 4.3. Bằng chứng tham chiếu
- Ảnh `product-A-5-pricing.png`.
- Ảnh `product-B-5-pricing.png`.

### 4.4. Nhận định
Mô hình "Freemium" của cả hai tương tự nhau. Tuy nhiên, ChatGPT có sức mạnh định giá (Pricing Power) tốt hơn vì giới hạn người dùng ở model xịn (GPT-4o) để ép mua Plus, trong khi Gemini lấy lợi thế phân phối từ hệ sinh thái Google miễn phí.

---

## S5 — PRODUCT JUDGMENT (Đánh giá chiến lược)

### 5.1. Verdict tóm tắt
- **Gemini: PROMISING**. Tốc độ vô địch và hệ sinh thái khổng lồ, nhưng thiếu tính chuyên sâu về tra cứu tài liệu học thuật minh bạch.
- **ChatGPT: STRONG**. Khả năng lập luận sâu, cite nguồn tốt biến nó thành trợ lý nghiên cứu mạnh mẽ.

### 5.2. Moat phân tích (Lợi thế cạnh tranh)
| Loại moat | Gemini (A) | ChatGPT (B) |
|---|---|---|
| **Moat chủ đạo** | **Distribution** (Mặc định trên Android, Workspace) | **Brand & Network** (Đồng nghĩa với AI, word-of-mouth) |
| **Điểm yếu** | Rủi ro tự triệt tiêu (Cannibalize) Google Search | Phụ thuộc chi phí compute lớn |

### 5.3. Data Flywheel
- **Gemini:** Tích hợp với Gmail, Docs, Drive. Càng dùng, Google càng hiểu ngữ cảnh cá nhân của bạn.
- **ChatGPT:** Feedback từ hàng trăm triệu chat session hàng ngày liên tục train RLHF cho model.

### 5.4. Niche Down + AI Feature Map
- Cả hai đều là sản phẩm **General-purpose (Thiếu niche rõ ràng)**.
- **User Alignment:** ChatGPT cao hơn vì trả lời tập trung, đúng ý; Gemini đôi khi "trả bài" theo văn mẫu an toàn.

### 5.5. Spark → Loop → System
- **Gemini:** Đang ở giai đoạn **LOOP** (người dùng quay lại vì tiện, tích hợp sẵn).
- **ChatGPT:** Bắt đầu chuyển sang **SYSTEM** (trở thành công cụ làm việc mặc định hàng ngày của sinh viên/nghiên cứu sinh).

### 5.6. Liên hệ Lab 1 (Case Jasper AI)
- **Rủi ro Disruption:** Nếu Jasper AI ở Lab 1 chết vì là "AI wrapper", thì Gemini và ChatGPT chính là "kẻ hủy diệt". Tuy nhiên, với tác vụ học thuật chuyên sâu, nếu Gemini và ChatGPT không cung cấp nguồn uy tín (Peer-reviewed citations), chúng có rủi ro bị các công cụ ngách như **Perplexity** hay **Consensus** đánh bật (Niche Down).
- **Bài học từ Jasper:** AI tổng quát (như Gemini/ChatGPT) giải quyết tốt 80% nhu cầu bề mặt. Nhưng để thực sự làm "research học thuật", người dùng cần độ chính xác 100% thay vì tốc độ sinh từ. Nếu ChatGPT/Gemini không khắc phục được hallucination, họ sẽ để hổng thị trường cho các Vertical AI.
