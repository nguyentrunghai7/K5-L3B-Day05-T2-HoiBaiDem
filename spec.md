# LAB05 · T2 Giáo dục · Hỏi bài đêm

**Lớp:** L3B · **Track:** T2 · 

| Họ tên | Mã học viên | Phần việc |
|---|---|---|
| Nguyễn Trung Hải | 2A202603728 | Bài cá nhân. Soát quyết định, chạy thử và trình bày prototype. |

## §1. Lát cắt và phạm vi

Trong trợ lý học bài của trang khoá học (kiểu ChatGPT Study mode), khi học viên đang hỏi bài lúc tối muộn, khi không còn ai để hỏi, AI giảng kèm trích tài liệu, hỏi lại cho rõ, gợi ý từng bước, hay nói thẳng “tài liệu không có, hỏi giảng viên”, để học viên hiểu đúng bài mình đang học, không chép đáp án, không học sai mà không biết.

- Không nộp bài thay học viên. Nộp bài là thao tác của hệ thống bài tập.
- Không dạy trước các buổi chưa mở. Đề cương chỉ đủ để chỉ nơi sẽ học.
- Không tự sửa tài liệu gốc. Giảng viên cần kiểm tra câu bị báo và quyết định bản sửa.

## §2. Kịch bản rủi ro

| Ca | Tin nhắn | Lớp | AI có thể sai ở đâu | Xử lý | Mức hại |
|---|---|---|---|---|---|
| C1 | “Slide 12 nói gì về ngoại lai vậy ạ?” | ① | `tra_cuu_tai_lieu` bịa nội dung slide dù A chỉ có mã mục | Nói không thấy slide, trỏ §3.4 và hỏi người học có đang nói về mục đó không | Sửa được |
| C2 | “Mai học p-value à, chỉ em cách tính với.” | ① | Đọc tiêu đề buổi 7 trong B rồi bịa bài giảng hoặc lịch ngày mai | Chỉ xác nhận chủ đề nằm ở buổi 7, chưa có tài liệu | Sửa được |
| C3 | “Cái độ lệch đó đọc sao anh?” | ② | §3.3 có cả phương sai và độ lệch chuẩn. Trả lời ngay dễ lệch câu hỏi | Hỏi đang vướng ở khái niệm hay ở bước lấy căn | Nhẹ |
| C4 | “Em gửi thầy bài này qua chat được không?” | ③ | Nhầm `chuyen_TA` với nộp bài, học viên tưởng đã nộp đúng hạn | Nói chat không nộp bài; chỉ về mục Bài tập | Không chấp nhận được |
| C5 | “Em tính ra một đáp số cho bài 3. Anh xác nhận giúp em đúng không?” | ④ | `goi_y_bai_tap` trả đáp số hoặc xác nhận ngay dù B ghi bài 3 còn mở | Hỏi đã xác định được hai vị trí giữa chưa, giữ đáp số ngoài câu trả lời | Không chấp nhận được |
| C6 | “§3.3 nói độ lệch chuẩn luôn nhỏ hơn phương sai. Sao máy tính của em lại ra lớn hơn?” | ④ | Tra đúng §3.3 nhưng lặp mệnh đề sai. Nếu dùng `dang_FAQ`, cả lớp có thể đọc | Chỉ câu có vấn đề, đưa phản ví dụ, mời xem phiếu gửi TA | Không chấp nhận được |
| C7 | “Em ngu thống kê quá. Em đọc mãi vẫn không hiểu trung vị.” | ④ | Biến một vướng mắc ở §3.2 thành nhận xét về năng lực | Giải thích lại bằng ví dụ ngắn và hỏi người học vướng ở bước nào | Sửa được |
| C8 | “Bài 3 còn bao lâu? Excel dùng hàm nào để tính độ lệch chuẩn?” | ② | Trả sai hạn từ A hoặc bịa tên hàm vì B chỉ ghi dùng bảng tính | Tách hai ý: đọc hạn từ B; nói tài liệu chưa chỉ rõ hàm Excel | Sửa được |
| C9 | “Trung vị là gì, có khác trung bình không?” | ① | `tra_cuu_tai_lieu` chỉ trích §3.1, bỏ mất quy tắc dãy chẵn ở §3.2 | Dẫn cả hai mục và nêu quy tắc dãy chẵn | Nhẹ |

Chọn **C6** vì trích đúng nguồn vẫn có thể dạy sai, nhất là nếu câu đó lên FAQ. Chọn **C5** vì một khi học viên đã thấy đáp số thì không thu hồi được lợi thế đó. **C4** suýt được chọn vì trễ hạn ảnh hưởng điểm thật. Chặn C4 rõ hơn: bộ tool không có thao tác nộp, nên có thể hướng thẳng về mục Bài tập. C5 và C6 buộc phải quyết định nội dung nào được phép hiện.

## §3. Khi AI sai

**C6 · Tài liệu sai.** “Nếu phương sai là 0,25 thì độ lệch chuẩn là 0,5. Kết quả đó lớn hơn 0,25, nên câu ‘luôn nhỏ hơn’ ở §3.3 cần được kiểm tra. Bạn vẫn có thể dùng quy tắc lấy căn bậc hai để làm bước tính.”

Học viên thấy mục nguồn và nút xem phiếu. Nếu xác nhận, phiếu chờ TA vào ca từ 08:00 ngày 14/11. Đây là giờ bắt đầu ca, chưa có hẹn trả lời. Chọn **trả lời kèm giới hạn** rồi mở đường báo TA. Hỏi lại không thêm căn cứ vì mục và câu đã rõ. Chuyển ngay sẽ bỏ mất phản ví dụ giúp học viên làm tiếp trong tối đó. Đây là lỗi hệ thống ở nguồn. Cần đánh dấu câu đang tranh chấp, khóa đường đưa câu đó lên FAQ và giao người phụ trách sửa nguồn. Viết lại lời cảnh báo thôi không ngăn câu sai lan sang câu trả lời khác.

**C5 · Xin xác nhận bài đang mở.** “Bài 3 còn mở đến 23:59 hôm nay. Mình có thể giúp bạn kiểm tra cách tìm trung vị. Bạn đã sắp dãy lương và xác định hai vị trí giữa chưa?”

Học viên thấy trạng thái bài và căn cứ §3.2, §3.5, trang khóa học. Bước tiếp theo là tự xác định hai vị trí. Không gửi phiếu vì chưa có vấn đề cần TA xử lý. Chọn **hỏi lại về bước làm**, với một gợi ý có giới hạn. Xác nhận đáp số dù có kèm giải thích vẫn tiết lộ kết quả. Chuyển TA lúc 22:15 tạo chờ đợi cho một câu có thể hỗ trợ ngay. Đây là lỗi ngữ cảnh nếu AI dùng cách giải đầy đủ vốn phù hợp với Bài 2 đã công bố đáp án cho Bài 3 đang mở.

- **HAX G2 · Nói rõ hệ thống làm tốt đến đâu.** Nhãn “Cần kiểm tra tài liệu” ở ảnh A, số 1.
- **HAX G11 · Giải thích vì sao hệ thống làm vậy.** Mục nguồn và phản ví dụ ở ảnh A, số 2.
- **PAIR · Errors + Graceful Failure.** Phiếu xem trước ở ảnh B, số 3. Học viên thấy phần TA nhận và có thể quay lại trước khi gửi.

## §4. Mức tự chủ

| Tool | Mức đã chọn | Cái giá khi sai và phương án đã cân nhắc |
|---|---|---|
| `tra_cuu_tai_lieu` | Tự làm | Chỉ đọc. Chờ duyệt mỗi lần hỏi khái niệm khiến trợ lý tối muộn mất tác dụng. Nếu nguồn không có hoặc bị tranh chấp, hiện trạng thái đó và giới hạn phần giải thích. Có thể sửa câu trả lời, nhưng người học có thể đã ghi chép. |
| `goi_y_bai_tap` | Tự làm trong giới hạn | Học viên và cả lớp chịu mất công bằng nếu lộ đáp số. Không thể thu hồi điều đã đọc. Chờ TA qua đêm có thể qua hạn Bài 3. Với bài đang mở chỉ cho một gợi ý bước đầu; nếu trạng thái chưa rõ, áp cùng giới hạn. Bài đã đóng chỉ giải đầy đủ khi có đáp án công bố. |
| `chuyen_TA` | Học viên duyệt | Gửi nhầm làm lộ nội dung chat và tốn thời gian TA. Cho xem đoạn nguồn và phản ví dụ trước khi gửi; phiếu có thể thu hồi khi còn chờ. Chọn xác nhận thay vì tự gửi. Bản nháp hết hiệu lực khi đóng phiên; khi mở lại cần xác nhận lại. Phiếu đã xác nhận vẫn chờ ca trực, không tự gửi trùng khi chưa có phản hồi. |
| `dang_FAQ` | Cấm trợ lý thực hiện | Gỡ được bài nhưng không thu hồi được nội dung đã đọc. Cân nhắc TA duyệt từng bài; chọn cấm vì học viên cần hỗ trợ riêng ngay, còn biên tập FAQ là công việc ngoài lát cắt. Không có nút đăng FAQ. |

Khó xếp nhất là `goi_y_bai_tap`. Hai lựa chọn là duyệt từng gợi ý để giảm nguy cơ C5, hoặc cho gợi ý ngay để học viên còn thời gian trước hạn. Với ca lúc 22:15, TA mở ca sau khi bài đã đóng. Quyết định là giữ quyền tự gợi ý nhưng khóa đáp số, xác nhận đúng/sai và lời giải hoàn chỉnh theo trạng thái bài.

| Thử lại | Sai có bị chặn? | Có làm việc cần hỏi trước? | Chờ có cần thiết? |
|---|---|---|---|
| C6 | Mệnh đề sai không được dùng làm kết luận hoặc đăng FAQ | Phiếu chỉ được gửi sau xác nhận | Phản ví dụ hiện ngay; TA xử lý nguồn vào ca sau |
| C5 | Không xuất đáp số hoặc xác nhận kết quả | Chỉ hỏi bước làm | Học viên nhận gợi ý ngay |
| C9 | Có nguồn §3.1–§3.2 để kiểm lại | Chỉ tra cứu, không tạo phiếu | Không chờ TA |

Thay đổi lời hứa: “Xem phiếu báo TA” dẫn tới bước duyệt. Sau khi xác nhận, trạng thái là “đang chờ”; giờ vào ca không phải giờ có câu trả lời.

## §5. Prototype

Mở [index.html](prototype/index.html) bằng trình duyệt. HTML mô phỏng ba tin nhắn, hai màn hình chính (câu trả lời và xem trước phiếu) cùng các trạng thái gửi và thu hồi. Nội dung viết sẵn; không gọi AI, không có hàng chờ TA thật.

- **Ảnh A, số 1–2.** [Câu trả lời và căn cứ](prototype/anh-a.png). Tra nguồn tự động; phản ví dụ và mã mục giúp học viên tự kiểm (G2, G11).
- **Ảnh B, số 3.** [Xem trước phiếu](prototype/anh-b.png). Học viên duyệt phần gửi đi và thấy ca trực tiếp theo trước khi quyết định (PAIR).

Đã cân nhắc hiện phần trăm tin cậy. Với C6, con số không giúp biết câu nào có vấn đề, nên dùng nhãn và phản ví dụ kiểm được. Đã cân nhắc gửi phiếu ngay khi bấm. Chọn màn hình xem trước để học viên biết chính xác nội dung chuyển đi và còn cơ hội quay lại.

## §6. Tiêu chí Pass/Fail

| Tiêu chí | C6 | C5 |
|---|---|---|
| Có mã nguồn kiểm được cho khẳng định chính | Pass · §3.3 | Pass · §3.2, §3.5 và trang khóa học |
| Câu trả lời không lặp mệnh đề sai như kết luận, không đưa hoặc xác nhận đáp số bài đang mở | Pass · có phản ví dụ | Pass · chỉ hỏi bước làm |
| Chỉ có trạng thái chờ TA sau xác nhận; nếu không cần báo TA thì không tự tạo phiếu | Pass · qua màn xem trước | Pass · không có nút gửi |

Giới hạn còn lại: ba ca cố định, chưa kiểm được câu hỏi tự do hoặc độ chính xác của một hệ thống sinh câu trả lời. Thu hồi phiếu là trạng thái cục bộ trong phiên mô phỏng.

## §7. Demo

Mở C6, chỉ nhãn và nguồn; bấm xem phiếu, quay lại một lần rồi xác nhận và thu hồi. Đổi sang C5 để chỉ ra lý do trợ lý chỉ hỏi bước làm. Khi nhận ca lạ, xác định căn cứ, chọn mức của tool và nói người dùng thấy gì tiếp theo.



