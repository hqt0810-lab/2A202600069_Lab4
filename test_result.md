**Test 1 — Direct Answer (Không cần tool)**

User: "Xin chào! Tôi đang muốn đi du lịch nhưng chưa biết đi đâu."

Kỳ vọng: Agent chào hỏi, hỏi thêm về sở thích/ngân sách/thời gian. Không gọi tool nào.

Kết quả:

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Chào bạn! Mình rất vui được đồng hành cùng bạn trong hành trình sắp tới 🌟 Việc "bí" địa điểm là chuyện siêu bình thường luôn á, vì Việt Nam mình đẹp và đa dạng lắm, đi đâu cũng có cái hay riêng 😄

Để mình gợi ý sát với gu và "túi tiền" của bạn nhất, bạn có thể chia sẻ thêm vài thông tin nhỏ với mình được không?
📍 Bạn dự định xuất phát từ thành phố nào vậy?
🏖️ Bạn thích kiểu nghỉ dưỡng biển chill chill, lên núi/phá đảo khám phá thiên nhiên, hay dạo phố trải nghiiệm ẩm thực & văn hóa?
💰 Ngân sách dự kiến khoảng bao nhiêu (tính theo đầu người) và bạn muốn đi tiết kiệm hay thoải mái một chút?
👥 Bạn đi một mình, cặp đôi, gia đình hay nhóm bạn? Dự định đi khoảng mấy ngày?

Chỉ cần bạn "bật mí" vài dòng thôi là mình sẽ tìm ngay các combo **vé máy bay + khách sạn** thực tế, kèm bảng tính ngân sách chi tiết để bạn dễ hình dung nhé ✈️🏨
*(Nhắc nhỏ: giá vé và phòng luôn biến động theo mùa & thời điểm đặt, nên các con số mình đưa ra sẽ là mức tham khảo cập nhật nhất để bạn yên tâm chốt lịch nha 💡)*

Chờ tin bạn nè! 🌿



**Test 2 — Single Tool Call**

User: "Tìm giúp tôi chuyến bay từ Hà Nội đi Đà Nẵng"

Kỳ vọng: Gọi search\_flights("Hà Nội", "Đà Nẵng"), liệt kê 4 chuyến bay.

Kết quả:

TravelBuddy đang suy nghĩ...
Gọi tool: search_flights({'origin': 'Hà Nội', 'destination': 'Đà Nẵng'})
Trả lời trực tiếp

TravelBuddy: Chào bạn! Mình vừa tra cứu giúp bạn các chuyến bay từ Hà Nội đi Đà Nẵng nè ✈️🌴

**Chuyến bay:**
- 🌅 VietJet Air: 08:30 → 09:50 | Giá: ~890.000đ (phổ thông)
- 🎋 Bamboo Airways: 11:00 → 12:20 | Giá: ~1.200.000đ (phổ thông)
- 🏙️ Vietnam Airlines: 06:00 → 07:20 | Giá: ~1.450.000đ (phổ thông)
- 💺 Vietnam Airlines: 14:00 → 15:20 | Giá: ~2.800.000đ (thương gia)

**Khách sạn:** Bạn có cần mình tìm khách sạn tại Đà Nẵng luôn không? Chỉ cần cho mình biết mức ngân sách tối đa mỗi đêm hoặc khu vực bạn ưu tiên (ví dụ: biển Mỹ Khê, trung tâm sông Hàn, hay gần sân bay...) là mình gửi danh sách phòng trống & rating ngay 🏨✨

**Tổng chi phí ước tính:** Hiện tại mới chỉ có giá vé máy bay tham khảo. Tổng chi phí thực tế sẽ phụ thuộc vào ngày bay bạn chọn, số lượng người đi, phí hành lý ký gửi (nếu có), và chi phí khách sạn/di chuyển tại điểm đến. B điểm đến. Bạn cứ cho mình biết ngày đi dự kiến & số người để mình bấm tính ngân sát chi tiết hơn nhé 💡   điểm đến. Bạn cứ cho mình biết ngày đi dự kiến & số người để mình bấm tính ngân sát chi tiết hơn nhé 💡      
 điểm đến. Bạn cứ cho mình biết ngày đi dự kiến & số người để mình bấm tính ngân sát chi tiết hơn nhé 💡      

**Gợi ý thêm:**
- 🕒 Nếu bạn muốn tiết kiệm & có nguyên ngày dài để khám phá, chuyến VietJet 08:30 là lựa chọn khá cân đối giữa giá và thời gian.
- 💸 **Lưu ý nhỏ:** Giá vé trên chỉ mang tính chất tham khảo thực tế tại thời điểm tìm kiếm và có thể thay đổi tùy theo ngày đặt, hạng vé & tình trạng chỗ trống. Giá cuối cùng sẽ được xác nhận khi bạn tiến hành thanh toán trên hệ thống hãng bay hoặc đại lý ủy quyền.
- 🧳 Đừng quên kiểm tra kỹ chính sách hành lý của từng hãng, vì vé phổ thông thường chỉ bao gồm 7kg xách tay, cân nặng ký gửi sẽ phát sinh thêm phí nếu chưa mua kèm.

Bạn dự định đi ngày nào và đi mấy người vậy? Mình sẵn sàng hỗ trợ bạn chốt lịch trình & tính toàn bộ ngân sách cho chuyến đi này nha! 😊



**Test 3 — Multi-Step Tool Chaining**

User: "Tôi ở Hà Nội, muốn đi Phú Quốc 2 đêm, budget 5 triệu. Tư vấn giúp!"

Kỳ vọng: Agent phải tự chuỗi nhiều bước:

search\_flights("Hà Nội", "Phú Quốc") → tìm vé rẻ nhất (1.100.000đ)

Google Hotels("Phú Quốc", max\_price phù hợp) → gợi ý trong tầm giá

calculate\_budget(5000000, "vé\_bay:1100000,khách\_sạn:...") → tính còn lại

Rồi tổng hợp thành gợi ý hoàn chỉnh với bảng chi phí.

Kết quả:

TravelBuddy đang suy nghĩ...
Gọi tool: search_flights({'origin': 'Hà Nội', 'destination': 'Phú Quốc'})
Gọi tool: search_hotels({'city': 'Phú Quốc', 'max_price_per_night': 1500000})
Gọi tool: calculate_budget({'total_budget': 5000000, 'expenses': 'vé_máy_bay_VietJet_16:00:1100000,khách_sạn_Lahana_Resort_2_đêm:1600000'})
Gọi tool: calculate_budget({'total_budget': 5000000, 'expenses': 'vé_máy_bay_VietJet:1100000,khách_sạn_Lahana_Resort_2_đêm:1600000'})
Trả lời trực tiếp

TravelBuddy: Chào bạn! Mình là trợ lý du lịch của TravelBuddy đây 🌴✈️ Với ngân sách 5 triệu cho chuyến đi Phú Quốc 2 đêm, mình đã rà soát thông tin vé bay và khách sạn mới nhất để lên phương án tối ưu nhất cho bạn. Mình tạm tính cho **1 người** nhé, nếu bạn đi cùng bạn bè/gia đình thì nhắn mình để điều chỉnh lại nha!
TravelBuddy: Chào bạn! Mình là trợ lý du lịch của TravelBuddy đây 🌴✈️ Với ngân sách 5 triệu cho chuyến đi Phú Quốc 2 đêm, mình đã rà soát thông tin vé bay và khách sạn mới nhất để lên phương án tối ưu nhất cho bạn. Mình tạm tính cho **1 người** nhé, nếu bạn đi cùng bạn bè/gia đình thì nhắn mình để điều chỉnh lại nha!
h cho **1 người** nhé, nếu bạn đi cùng bạn bè/gia đình thì nhắn mình để điều chỉnh lại nha!

**Chuyến bay:**
Hiện có 3 khung bay tiết kiệm nhất từ Hà Nội → Phú Quốc (giá một chiều):
1. VietJet Air: 16:00 → 18:15 | 1.100.000đ 💡 *Lựa chọn giá tốt nhất*
2. VietJet Air: 10:00 → 12:15 | 1.350.000đ
3. Vietnam Airlines: 07:00 → 09:15 | 2.100.000đ
*(Mình ước tính khứ hồi x2 giá vé trên vì bạn đi 2 đêm sẽ cần bay về. Ví dụ chọn VietJet chuyến 16:00: ~2.200.000đ/khứ hồi)*

**Khách sạn:**
Với mức giá tối ưu, bạn có 3 lựa chọn nổi bật:
1. **Lahana Resort ⭐⭐⭐** (Dương Đông): 800.000đ/đêm | Rating 4.0/5 → *Cân bằng nhất giữa giá và tiện nghi, tổng 2 đêm: 1.600.000đ*
2. **Sol by Meliá ⭐⭐⭐⭐** (Bãi Trường): 1.500.000đ/đêm | Rating 4.2/5 → *Nếu bạn thích nghỉ dưỡng sát biển, tổng 2 đêm: 3.000.000đ* (hơi sát ngân sách)
3. **9Station Hostel ⭐⭐** (Dương Đông): 200.000đ/đêm | Rating 4.5/5 → *Siêu tiết kiệm, tổng 2 đêm: 400.000đ*    

**Tổng chi phí ước tính:** *(Gói cân bằng: VietJet 16:00 khứ hồi + Lahana Resort 2 đêm)*
- Vé máy bay khứ hồi: ~2.200.000đ
- Khách sạn Lahana Resort (2 đêm): 1.600.000đ
👉 **Tổng di chuyển & lưu trú: 3.800.000đ**
👉 **Ngân sách còn lại: 1.200.000đ** (dành cho ăn uống, thuê xe máy, vé tham quan & phát sinh)
*(⚠️ Lưu ý: Giá vé và phòng trên chỉ mang tính chất tham khảo thời điểm chốt dữ liệu, có thể thay đổi tùy vào ngày bạn bay thực tế và tỷ lệ đặt full/early bird nhé!)*

**Gợi ý thêm:**
Với 1,2 triệu còn lại, bạn hoàn toàn có thể thuê xe máy (~150k/ngày) tự do khám phá Bãi Sao, Làng chài Rạch Vẹm, hoặc check-in Cầu Cảng Sunset Town lúc hoàng hôn 🌅. Bữa tối đừng bỏ qua hải sản nướng tại chợ đêm Dương Đông hoặc các quán ven Bãi Trường nhé! 🦀🍹
Để mình hỗ trợ chốt lịch chuẩn xác và canh vé khuyến mãi tốt nhất, bạn cho mình biết **ngày khởi hành dự kiến** và **số người đi** nhé? Mình sẽ điều chỉnh phương án sát thực tế nhất cho bạn! 💙✨



**Test 4 — Missing Info / Clarification**

User: "Tôi muốn đặt khách sạn"

Kỳ vọng: Agent hỏi lại: thành phố nào? bao nhiêu đêm? ngân sách bao nhiêu? Không gọi tool vội.

Kết quả:

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Chào bạn! 🌴 Mình rất sẵn lòng hỗ trợ bạn tìm khách sạn ưng ý nè. Để mình tra cứu và gợi ý chính xác nhất, bạn chia sẻ giúp mình vài thông tin nhỏ nhé:

📍 **Điểm đến:** Bạn định đặt khách sạn ở thành phố nào vậy? (VD: Đà Nẵng, Phú Quốc, Nha Trang, Hà Nội, TP.HCM...)
💰 **Ngân sách:** Bạn dự chi khoảng bao nhiêu cho một đêm phòng? (Mình sẽ lọc danh sách khách sạn trong tầm giá đó, từ bình dân đến cao cấp)
🛏️ **Nhu cầu phòng:** Bạn đi mấy người và ưu tiên giường đôi, giường đơn hay phòng gia đình? Có cần gần biển/trungg tâm không?

Cứ nhắn mình xong là mình chạy tìm kiếm giá phòng thực tế và gửi bạn bảng so sánh chi tiết ngay nhé! 💡 *Lưu ý nhỏ:* Giá phòng mình tìm được chỉ mang tính tham khảo vì có thể thay đổi tùy vào thời điểm bạn chốt đặt thực tế và tình trạng phòng trống của khách sạn nha. 😊



**Test 5 — Guardrail / Refusal**

User: "Giải giúp tôi bài tập lập trình Python về linked list."

Kỳ vọng: Từ chối lịch sự, nói rằng chỉ hỗ trợ về du lịch.

Kết quả:

TravelBuddy đang suy nghĩ...
Trả lời trực tiếp

TravelBuddy: Chào bạn ơi, mình rất tiếc là mình không hỗ trợ được phần bài tập lập trình Python về linked list này đâu 😅. Mình là trợ lý du lịch của **TravelBuddy**, chuyên tư vấn lịch trình, săn vé máy bay, gợi ý khách sạn và tính toán ngân sách cho các chuyến đi trong nước Việt Nam thôi 🇻🇳✈️🏨.

Nếu sau những giờ học code căng thẳng bạn muốn lên kế hoạch cho một chuyến đi xả hơi, hoặc cần mình hỗ trợ tìm chuyến bay, khách sạn phù hợp túi tiền, hay tính toán chi phí du lịch Đà Nẵng, Phú Quốc, Hà Nội... cứ nhắn mình nhé! Mình sẽ đồng hành cùng bạn để có một lịch trình vừa ưng ý vừa tối ưu ngân sách 💼✨.

Bạn có đang ấp ủ điểm đến nào sắp tới không? Kể mình nghe để mình bắt đầu lên phương án cho bạn nha! 😊



**Test 6 — Chuyến bay không ở trong DB**

User: "Tìm giúp tôi 1 chuyến bay từ Đà Nẵng đến Phú Quốc."

Kỳ vọng: Từ chối lịch sự và có thể nói về các chuyến bay để dẫn đến địa điểm mong muốn.

Kết quả:

TravelBuddy đang suy nghĩ...
Gọi tool: search_flights({'origin': 'Đà Nẵng', 'destination': 'Phú Quốc'})
Trả lời trực tiếp

TravelBuddy: Chào bạn, mình vừa kiểm tra thông tin chuyến bay từ Đà Nẵng đến Phú Quốc giúp bạn thì hiện tại hệ thống chưa ghi nhận chuyến bay thẳng nào cho tuyến này bạn nhé ✈️.

Thường thì để di chuyển từ Đà Nẵng ra đảo ngọc Phú Quốc, phương án bay phổ biến nhất là bạn sẽ bay nối chuyến qua TP. Hồ Chí Minh hoặc Hà Nội. Cụ thể, bạn có thể bay từ Đà Nẵng đến TP. Hồ Chí Minh (khoảng 1 tiếng 15 phút), sau đó tiếp tục bay đến Phú Quốc (khoảng 1 tiếng) 🌴.

Bạn có muốn mình tìm giúp vé bay chặng **Đà Nẵng - TP. Hồ Chí Minh** để tham khảo giá và giờ bay không? Hoặc nếu bạn đã có ngày đi cụ thể, hãy cho mình biết để mình hỗ trợ lên phương án tối ưu nhất nhé! 💖

💡 *Lưu ý nhỏ: Giá vé và lịch bay có thể thay đổi tùy thuộc vào thời điểm bạn đặt thực tế và tình trạng đặt chỗ của hãng hãng bay bạn nha.*

