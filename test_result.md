**Test 1 — Direct Answer (Không cần tool)**

User: "Xin chào! Tôi đang muốn đi du lịch nhưng chưa biết đi đâu."

Kỳ vọng: Agent chào hỏi, hỏi thêm về sở thích/ngân sách/thời gian. Không gọi tool nào.

Kết quả:

![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.001.png) 

**Test 2 — Single Tool Call**

User: "Tìm giúp tôi chuyến bay từ Hà Nội đi Đà Nẵng"

Kỳ vọng: Gọi search\_flights("Hà Nội", "Đà Nẵng"), liệt kê 4 chuyến bay.

Kết quả: ![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.002.png)



**Test 3 — Multi-Step Tool Chaining**

User: "Tôi ở Hà Nội, muốn đi Phú Quốc 2 đêm, budget 5 triệu. Tư vấn giúp!"

Kỳ vọng: Agent phải tự chuỗi nhiều bước:

search\_flights("Hà Nội", "Phú Quốc") → tìm vé rẻ nhất (1.100.000đ)

Google Hotels("Phú Quốc", max\_price phù hợp) → gợi ý trong tầm giá

calculate\_budget(5000000, "vé\_bay:1100000,khách\_sạn:...") → tính còn lại

Rồi tổng hợp thành gợi ý hoàn chỉnh với bảng chi phí.

Kết quả:

![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.003.png)![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.004.png)



**Test 4 — Missing Info / Clarification**

User: "Tôi muốn đặt khách sạn"

Kỳ vọng: Agent hỏi lại: thành phố nào? bao nhiêu đêm? ngân sách bao nhiêu? Không gọi tool vội.

Kết quả:

![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.005.png) 

**Test 5 — Guardrail / Refusal**

User: "Giải giúp tôi bài tập lập trình Python về linked list."

Kỳ vọng: Từ chối lịch sự, nói rằng chỉ hỗ trợ về du lịch.

Kết quả:

![](Aspose.Words.507a2ee0-87b9-4614-9cbd-c2ede66c429a.006.png)


