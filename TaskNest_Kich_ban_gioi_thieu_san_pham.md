# Kịch bản giới thiệu sản phẩm TaskNest

## Phân công bốn người

- **Bạn:** slide **1–3, 12–18**. Giới thiệu sản phẩm, lý do thực hiện, nhóm và toàn bộ phần Khám phá.
- **Người 2:** slide **4–7, 19–21**. Thành viên dự án, giao việc, nộp và duyệt kết quả, mốc bàn giao và nghiệm thu mốc.
- **Người 3:** slide **8–11, 22–24**. Ghi giờ, báo cáo, AI, trao đổi, nghiệm thu toàn dự án và đánh giá.
- **Người 4:** slide **25–31**. Kiến trúc, dữ liệu, công nghệ, bảo vệ tài khoản, định hướng thương mại hoá và kết bài.

Lời nói dưới đây là gợi ý để tập theo từng ý. Các đoạn bàn giao chỉ dùng khi đổi người; không cần đọc thêm tên chức năng hay các điều kiện thành từng mục.

## Lời nói theo slide

### Slide 1 · TaskNest

**Người nói: Bạn — giới thiệu và Khám phá**

Chào mọi người, hôm nay nhóm mình giới thiệu TaskNest, sản phẩm hỗ trợ quản lý công việc và phối hợp trong nhóm.

Khi đã có những công cụ như Jira hay Trello, lý do nhóm vẫn chọn làm TaskNest là muốn tập trung vào quy trình từ giao việc đến kiểm tra kết quả: một công việc giao cho ai, đã dành bao nhiêu thời gian và cuối cùng bản nào được chấp nhận. Nhóm cũng mở rộng thêm phần tìm người, tìm đội để kết nối trước khi bắt đầu dự án.

Mình bắt đầu từ nhu cầu mà nhóm chọn giải quyết.

### Slide 2 · Giao việc xong, đội còn cần biết điều gì?

**Người nói: Bạn — giới thiệu và Khám phá**

Một danh sách công việc cho biết cần làm gì. Trong quá trình thực hiện, đội còn cần nhìn được tiến độ, thời gian đã dùng và kết quả thực tế được gửi lên.

TaskNest tập trung gắn những thông tin đó vào cùng nhiệm vụ. Người quản lý xem được nội dung bàn giao và lịch sử phản hồi; người thực hiện biết phần nào đã được chấp nhận, phần nào cần làm tiếp. Khi xét đúng hạn, hệ thống dựa trên thời điểm gửi của bản được chấp nhận.

Trước khi đi vào các chức năng, mình giới thiệu nhanh phần việc của bốn thành viên trong nhóm.

### Slide 3 · Bốn thành viên cùng xây dựng TaskNest

**Người nói: Bạn — giới thiệu và Khám phá**

Khánh An phụ trách điều phối, kiến trúc, tích hợp và triển khai. Việt Anh làm UI/UX và giao diện React. Nguyên Đức phụ trách API, xác thực và nghiệp vụ tài khoản. Duy Mạnh phát triển frontend, backend và kết nối các phân hệ.

Các phần việc được ghép lại quanh những luồng sử dụng của sản phẩm.

**Bàn giao:** Mình mời bạn [Người 2] giới thiệu trước cách các thành viên phối hợp trong dự án.

### Slide 4 · Đưa đúng người vào dự án

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Để bắt đầu làm cùng nhau, người quản lý đưa thành viên vào dự án bằng lời mời qua email hoặc chia sẻ link, mã QR để người dùng gửi yêu cầu tham gia.

Với lời mời trực tiếp, người nhận tự chấp nhận. Với yêu cầu qua link, Owner hoặc Manager xem và duyệt trước khi người đó tham gia. Sau bước này, thành viên mới có thể được phân công công việc trong dự án. Quyền được quản lý riêng ở từng dự án.

### Slide 5 · Mỗi việc có một người phụ trách

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Khi tạo một nhiệm vụ, người dùng xác định nội dung cần làm, người phụ trách, thời hạn và thời gian ước tính. Những thông tin này giúp cả người giao lẫn người nhận biết trách nhiệm của mình ngay từ đầu.

Owner và Manager có thể phân công cho các thành viên đang hoạt động trong cùng dự án. Thành viên thường cũng tạo được công việc cho chính mình; việc giao cho người khác thuộc phạm vi quản lý dự án. Khi đã có nhiệm vụ, người phụ trách có thể bắt đầu thực hiện và cập nhật kết quả.

### Slide 6 · Gửi kết quả để cùng kiểm tra

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Khi đã có kết quả, người phụ trách gửi một tệp hoặc một liên kết, kèm ghi chú về phần mình đã làm. Như vậy, người kiểm tra có nội dung cụ thể để xem chứ không chỉ nhìn vào trạng thái công việc.

Mỗi lần gửi được lưu thành một bản nộp, có thời điểm gửi và hạn tại thời điểm đó. Nhiệm vụ chuyển sang chờ duyệt; người phụ trách vẫn chờ phản hồi trước khi công việc được ghi nhận hoàn thành. Nếu đang bấm giờ trên nhiệm vụ, hệ thống cũng kết thúc phiên khi gửi kết quả.

### Slide 7 · Chấp nhận kết quả hoặc phản hồi để sửa

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Owner hoặc Manager mở bản nộp mới nhất để kiểm tra tệp, liên kết và phần ghi chú. Nếu kết quả đạt yêu cầu, họ xác nhận hoàn thành và hệ thống lưu đúng bản đã được chấp nhận.

Nếu cần làm lại, người duyệt nêu nội dung cần sửa và đặt hạn mới từ hôm nay. Người phụ trách tiếp tục làm rồi gửi bản mới. Các lần nộp và phản hồi được giữ lại để sau này cả nhóm xem được công việc đã đi đến kết quả cuối như thế nào.

**Bàn giao:** Đó là cách đội gửi và kiểm tra kết quả. Mình mời bạn [Người 3] giới thiệu tiếp phần ghi giờ và theo dõi công việc.

### Slide 8 · Giờ làm gắn với công việc thực tế

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Ngay trên nhiệm vụ đang thực hiện, người phụ trách có thể bắt đầu và dừng ghi giờ. Thời gian được lưu cùng người thực hiện và công việc tương ứng, nên khi xem lại sẽ biết giờ đó dành cho việc gì.

Một tài khoản chỉ có một phiên đang chạy, kể cả khi mở nhiều tab. Dữ liệu này giúp người dùng nhìn lại thời gian thực tế và đối chiếu với ước tính ban đầu; sản phẩm không tự biến số giờ thành điểm đánh giá năng suất.

### Slide 9 · Quên bấm giờ? Có thể bổ sung lại

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Trong lúc làm việc, người dùng có thể quên bật bộ đếm hoặc ghi sai một khoảng thời gian. TaskNest cho phép bổ sung giờ của chính mình và chỉnh lại phiên đã dừng, kèm lý do thay đổi.

Lịch sử lưu lại thời gian trước và sau khi sửa để có thể đối chiếu. Hệ thống cũng kiểm tra các khoảng giờ không trùng nhau, không nằm trong tương lai. Việc điều chỉnh cần thực hiện trước khi nhiệm vụ hoàn thành hoặc bị huỷ.

### Slide 10 · Theo dõi tiến độ, xem lại thời gian

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Sau khi nhóm cập nhật công việc và ghi giờ, dữ liệu được tổng hợp để theo dõi tiến độ, trạng thái và thời gian thực hiện. Người dùng chọn khoảng ngày để xem hoặc xuất CSV khi cần làm báo cáo.

Với người quản lý, đây là góc nhìn toàn dự án. Với thành viên, báo cáo tập trung vào nhiệm vụ được giao và thời gian do chính họ ghi. Vì vậy, mỗi người có thể xem lại phần công việc thuộc phạm vi của mình.

### Slide 11 · Nắm việc nhanh hơn với trợ lý AI

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Ngoài việc tự xem danh sách và báo cáo, người dùng có thể hỏi trợ lý AI để nắm nhanh thông tin công việc, những điểm cần chú ý và gợi ý bước tiếp theo.

Trợ lý đọc dữ liệu trong phạm vi mà tài khoản đang được xem. Câu trả lời giúp người dùng tham khảo và xử lý công việc; việc giao nhiệm vụ, duyệt kết quả hay nghiệm thu vẫn do người có quyền thực hiện. Chức năng này cần dịch vụ AI đã được cấu hình và còn hạn mức.

**Bàn giao:** Ngoài phần làm việc trong dự án, TaskNest còn có khu vực Khám phá. Mình xin chuyển lại cho bạn [Bạn] để giới thiệu phần này.

### Slide 12 · Một nơi để tìm người và tìm đội cùng làm

**Người nói: Bạn — giới thiệu và Khám phá**

Đến đây, mọi người đã thấy cách TaskNest hỗ trợ một nhóm khi đã có dự án. Phần tiếp theo là Khám phá, nơi người dùng có thể tìm đội để tham gia hoặc tìm đội thực hiện công việc của mình.

Tụi mình đưa phần này vào vì trước khi bắt đầu làm việc, đội còn cần tìm người phù hợp, còn khách hàng cần biết nên hợp tác với ai. Khi hai bên chọn được nhau, họ có thể tiếp tục làm việc ngay trong TaskNest.

Mình giới thiệu trước phần hồ sơ đội, là nơi người khác tìm hiểu đội có thể làm được gì.

### Slide 13 · Để người khác biết đội mình làm được gì

**Người nói: Bạn — giới thiệu và Khám phá**

Khi tìm một đội, điều mình muốn biết đầu tiên thường là đội đó làm về lĩnh vực gì, gồm những ai và đã có những đánh giá hợp tác như thế nào. Hồ sơ đội tập hợp những thông tin đó để người xem cân nhắc trước khi liên hệ.

Chủ đội có thể giới thiệu chuyên môn, cập nhật nội dung và cho biết đội có đang nhận dự án hay không. Với khách hàng, đây là chỗ để tìm hiểu năng lực. Với người muốn tham gia, đây là chỗ để xem mình có phù hợp với đội không.

Nếu đội đang cần thêm người, họ có thể đăng vị trí tuyển ngay từ đây.

### Slide 14 · Tìm thêm người phù hợp với đội

**Người nói: Bạn — giới thiệu và Khám phá**

Ở phần tuyển thành viên, chủ đội nêu rõ vị trí cần người, kỹ năng mong muốn và thời gian dự kiến tham gia. Người đang tìm đội có thể xem các vị trí còn mở rồi gửi đơn vào vị trí phù hợp.

Đơn ứng tuyển có phần giới thiệu, kỹ năng và số giờ có thể dành cho đội mỗi tuần. Nhờ vậy, chủ đội có thông tin cụ thể để xem xét, còn ứng viên cũng biết mình đang đăng ký làm công việc gì.

Sau khi nhận được đơn, chủ đội sẽ là người quyết định có nhận thành viên đó hay không.

### Slide 15 · Chủ đội quyết định ai sẽ cùng làm

**Người nói: Bạn — giới thiệu và Khám phá**

Chủ đội xem hồ sơ ứng tuyển và có thể chấp nhận hoặc từ chối. Nếu chưa phù hợp, chủ đội cần để lại phản hồi để ứng viên biết kết quả của mình.

Khi chấp nhận, hệ thống thêm ứng viên vào đội. Có một điểm cần phân biệt ở đây: trở thành thành viên của đội chưa tự động đưa người đó vào các dự án cũ. Quyền tham gia và phân công công việc vẫn được quản lý riêng trong từng dự án.

Đó là cách đội tìm thêm người. Còn với khách hàng đang có việc cần làm, họ có thể bắt đầu bằng một yêu cầu tìm đội.

### Slide 16 · Đăng nhu cầu, tìm đội thực hiện

**Người nói: Bạn — giới thiệu và Khám phá**

Ở phía khách hàng, người dùng có thể đăng nội dung công việc cần làm, khoảng ngân sách và thời điểm mong muốn nhận kết quả. Nếu có yêu cầu về kỹ năng hoặc công nghệ, họ cũng có thể bổ sung để các đội dễ xem mức độ phù hợp.

Người đăng có thể lưu nháp trước hoặc công khai khi đã sẵn sàng. Họ cũng quản lý và cập nhật yêu cầu của mình. Các đội dựa vào nội dung đó để cân nhắc có gửi đề xuất hay không.

Khi thấy yêu cầu phù hợp với khả năng của đội, chủ đội sẽ gửi một phương án thực hiện cụ thể.

### Slide 17 · Thống nhất phương án trước khi hợp tác

**Người nói: Bạn — giới thiệu và Khám phá**

Đề xuất là lúc đội nói rõ mình sẽ thực hiện những gì, với chi phí và thời gian dự kiến ra sao. Chủ đội là người đại diện gửi những thông tin này cho khách hàng.

Khách hàng có thể xem các phương án nhận được để cân nhắc đội phù hợp. Nếu yêu cầu thay đổi sau khi đề xuất đã gửi, đội cần cập nhật theo nội dung mới. Như vậy, quyết định hợp tác dựa trên thông tin mà hai bên đang cùng xem.

Phần chi phí hiện là thông tin đề xuất để trao đổi; TaskNest chưa xử lý thanh toán.

Khi khách hàng đã lựa chọn, hai bên có thể chuyển sang thực hiện dự án.

### Slide 18 · Chọn đội và bắt đầu dự án

**Người nói: Bạn — giới thiệu và Khám phá**

Khi khách hàng chọn một đề xuất, hệ thống tạo dự án hợp tác tương ứng. Chủ đội trở thành Owner, còn khách hàng và các thành viên hiện tại của đội được thêm vào dự án.

Điểm nối của phần Khám phá nằm ở đây: sau khi tìm được người và chọn được đội, người dùng tiếp tục sử dụng các chức năng giao việc, ghi giờ và duyệt kết quả nhóm vừa giới thiệu. Các bước thực hiện nằm trong cùng một sản phẩm.

**Bàn giao:** Sau khi bắt đầu hợp tác, hai bên cần thống nhất đầu ra và cách xác nhận kết quả. Mình mời bạn [Người 2] giới thiệu tiếp phần mốc bàn giao và nghiệm thu.

### Slide 19 · Thống nhất đầu ra trước khi bàn giao

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Khi có dự án hợp tác, đội và khách hàng cần thống nhất trước kết quả mong muốn. Phía đội lập mốc bàn giao, ghi thời hạn, các tiêu chí để kiểm tra và liên kết những nhiệm vụ liên quan.

Khách hàng xem và xác nhận kế hoạch đó trước khi đội gửi kết quả. Nhờ vậy, đến lúc bàn giao hai bên có cùng căn cứ để đối chiếu. Đây là phần thống nhất đầu ra với khách hàng, tách khỏi việc duyệt từng nhiệm vụ trong nội bộ đội.

### Slide 20 · Bàn giao theo mốc, giữ lại từng phiên bản

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Khi đã hoàn thành các nhiệm vụ liên quan, Owner hoặc Manager phía đội gửi kết quả của mốc cho khách hàng. Nội dung gồm ghi chú và liên kết đến sản phẩm cần kiểm tra.

Mỗi lần gửi tạo một lần bàn giao riêng và chuyển mốc sang chờ nghiệm thu. Nếu khách hàng yêu cầu chỉnh sửa, đội có thể hoàn thiện rồi gửi lần tiếp theo. Quá trình bàn giao vì vậy vẫn có lịch sử để hai bên xem lại.

### Slide 21 · Khách hàng kiểm tra và quyết định nghiệm thu

**Người nói: Người 2 — phối hợp công việc và bàn giao theo mốc**

Khách hàng mở lần bàn giao mới nhất, xem kết quả và đối chiếu với các tiêu chí đã xác nhận từ trước. Nếu đạt, họ đánh dấu đủ tiêu chí và chấp nhận mốc.

Nếu còn nội dung cần sửa, khách hàng để lại phản hồi cụ thể để đội làm tiếp. Điểm cần phân biệt là một nhiệm vụ có thể đã được quản lý nội bộ chấp nhận, nhưng kết quả bàn giao vẫn cần khách hàng kiểm tra và quyết định nghiệm thu.

**Bàn giao:** Ngoài bàn giao, quá trình thực hiện còn có trao đổi và xác nhận cuối dự án. Mình mời bạn [Người 3] trình bày tiếp.

### Slide 22 · Trao đổi ngay trong ngữ cảnh công việc

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Trong quá trình thực hiện, người dùng có thể trao đổi trực tiếp, trò chuyện trong đội hoặc trong dự án. Những phản hồi liên quan đến một nhiệm vụ có thể để ngay tại nhiệm vụ đó để người đọc hiểu đang nói đến phần việc nào.

Tài liệu và liên kết cũng được tập hợp trong dự án để tiện tìm lại. Phạm vi trao đổi theo thành viên và quyền tham gia, gồm cả khách hàng khi đã có quan hệ hợp tác. Người dùng quản lý nội dung của mình; người quản lý dự án có quyền quản lý tài liệu theo vai trò.

### Slide 23 · Khép lại dự án khi đầu ra đã được xác nhận

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Sau khi các phần việc và mốc bàn giao đã được xử lý, khách hàng thực hiện bước nghiệm thu toàn bộ dự án. Đây là xác nhận cuối cùng cho kết quả hợp tác, riêng với việc chấp nhận từng mốc.

Hệ thống kiểm tra các nhiệm vụ đều hoàn thành hoặc được huỷ, trong đó phải có ít nhất một việc hoàn thành; các mốc cũng cần được chấp nhận hoặc huỷ. Sau nghiệm thu, sản phẩm lưu các thành viên có đóng góp để phục vụ bước đánh giá và ghi nhận tiếp theo.

### Slide 24 · Lưu lại đánh giá sau mỗi lần hợp tác

**Người nói: Người 3 — giờ làm, theo dõi và kết thúc hợp tác**

Sau nghiệm thu, khách hàng có thể đánh giá đội về chất lượng, tiến độ, giao tiếp và hỗ trợ bàn giao, kèm nhận xét và mong muốn hợp tác lại. Chủ đội có thể phản hồi đánh giá đó.

Khách hàng cũng có thể ghi nhận những thành viên có đóng góp đã được lưu từ dự án. Những đánh giá này gắn với một lần hợp tác thực tế trong hệ thống, để người xem hồ sơ có thêm thông tin cho các lần lựa chọn sau.

**Bàn giao:** Mình mời bạn [Người 4] giới thiệu ngắn về nền tảng kỹ thuật và định hướng tiếp theo của sản phẩm.

### Slide 25 · Các dịch vụ phối hợp để xử lý công việc

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Những chức năng vừa rồi được chia cho các dịch vụ theo trách nhiệm. Yêu cầu từ giao diện đi qua API Gateway; Work Service xử lý dự án, nhiệm vụ và các luồng hợp tác. Identity quản lý tài khoản và phiên đăng nhập.

Khi có sự kiện cần thông báo, hệ thống chuyển qua RabbitMQ để Notification xử lý. Phần AI nằm ở dịch vụ riêng và được bật theo cấu hình. Cách tổ chức này giúp nhóm giữ phần xử lý công việc và các tác vụ nền theo từng trách nhiệm rõ ràng.

### Slide 26 · Dữ liệu giữ lại quá trình thực hiện

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Ở thiết kế dữ liệu, nhiệm vụ là điểm liên kết giữa công việc, các phiên ghi giờ và những lần nộp kết quả. Một nhiệm vụ có thể được nộp nhiều lần, mỗi lần có phản hồi và quyết định riêng.

Hệ thống giữ thời điểm gửi cùng hạn nộp tại lúc đó, đồng thời chỉ rõ bản nào đã được chấp nhận. Nhờ vậy, khi xem lại, người dùng có thể đối chiếu quá trình thực hiện và biết bản được duyệt có gửi đúng hạn hay không.

### Slide 27 · Những công nghệ đằng sau TaskNest

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Giao diện dùng React, TypeScript và Tailwind CSS. Backend sử dụng Java 21, Spring Boot và Spring Cloud. MySQL lưu dữ liệu, còn Flyway quản lý các thay đổi cấu trúc database.

REST phục vụ các yêu cầu từ giao diện, WebSocket báo cập nhật, RabbitMQ chuyển sự kiện cho xử lý nền. Docker Compose dùng để chạy các dịch vụ; GitHub Actions hỗ trợ kiểm thử và đóng gói. Đây là những thành phần phục vụ các chức năng mà mọi người vừa xem.

### Slide 28 · Bảo vệ tài khoản và phiên đăng nhập

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Với tài khoản, TaskNest dùng BCrypt để băm mật khẩu trước khi lưu. Khi đăng nhập, hệ thống kiểm tra mật khẩu dựa trên bản băm và cấp access token dạng JWT ký bằng RS256.

Refresh token đi qua cookie HttpOnly; database lưu bản băm SHA-256 của token đó và hệ thống thay token khi làm mới phiên. AES-256-GCM được dùng cho nội dung email nhạy cảm xếp hàng gửi. Mỗi kỹ thuật phục vụ một phần cụ thể của việc bảo vệ thông tin.

### Slide 29 · Giữ dữ liệu nhất quán khi nhiều người cùng thao tác

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Ngoài xác thực tài khoản, backend kiểm tra quyền trước khi xử lý những thao tác như giao việc hoặc duyệt kết quả. Các phiên ghi giờ cũng được kiểm soát để một người chỉ có một phiên đang chạy.

Với thông báo nền, sự kiện được lưu cùng thay đổi nghiệp vụ rồi mới chuyển qua RabbitMQ. Cách này giúp hệ thống giữ lại thông tin cần phát đi sau khi dữ liệu công việc đã lưu thành công.

### Slide 30 · Bắt đầu thương mại hoá từ các đội dịch vụ nhỏ

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Nếu phát triển tiếp, nhóm muốn thử TaskNest với các đội dịch vụ nhỏ như làm website, thiết kế hoặc nội dung. Đây là nhóm có quy trình giao việc, bàn giao và cần khách hàng xác nhận kết quả.

Bước đầu là dùng trên dự án thật và quan sát họ có tiếp tục dùng cho dự án sau không, bước nào thuận tiện và bước nào còn khiến họ phải chuyển sang công cụ khác. Từ phản hồi đó, nhóm hoàn thiện sản phẩm rồi thử gói thu phí theo đội hoặc số dự án đang hoạt động.

Các hướng như báo cáo nhiều dự án, duyệt nhiều cấp hoặc tích hợp thanh toán là những phần có thể phát triển tiếp. Đây là định hướng thương mại hoá, chưa phải mô hình đã được kiểm chứng.

### Slide 31 · TaskNest

**Người nói: Người 4 — nền tảng kỹ thuật, định hướng và kết bài**

Đó là phần giới thiệu TaskNest của nhóm mình. Trọng tâm của sản phẩm là giúp đội theo dõi công việc, thời gian thực hiện và kết quả đã được chấp nhận trong cùng một nơi.

Phần Khám phá hỗ trợ kết nối trước khi hợp tác, còn mốc bàn giao và nghiệm thu giúp đội làm việc với khách hàng đến khi xác nhận kết quả. Nhóm mong nhận được góp ý để tiếp tục hoàn thiện sản phẩm. Cảm ơn mọi người đã lắng nghe.

## Khi cần trả lời sâu hơn

**Member có giao việc cho người khác được không?** Không. Member chỉ được tạo nhiệm vụ cho chính mình. Owner hoặc Manager có thể giao cho thành viên đang hoạt động trong cùng dự án.

**Ai có quyền nộp thay?** Quyền nộp kiểm tra theo người phụ trách. Owner hoặc Manager chỉ nộp được khi chính họ là người phụ trách nhiệm vụ đó.

**Duyệt kết quả và nghiệm thu có giống nhau không?** Owner/Manager duyệt bản nộp nhiệm vụ nội bộ. Khách hàng xác nhận kết quả bàn giao theo mốc và nghiệm thu toàn dự án khi đủ điều kiện.

**Hệ thống có luôn buộc người nộp và người duyệt là hai người khác nhau không?** Hiện mã nguồn kiểm tra vai trò Owner/Manager và trạng thái chờ duyệt, chưa có quy tắc cấm quản lý duyệt nhiệm vụ do chính họ phụ trách. Không trình bày như tính năng đã có.

**Nhận vào đội có tự vào mọi dự án không?** Không. Duyệt ứng viên tạo thành viên của đội; quyền trong dự án được quản lý riêng. Khi khách chọn đội qua marketplace, hệ thống tạo dự án mới và thêm thành viên hiện tại của đội cùng khách hàng.
