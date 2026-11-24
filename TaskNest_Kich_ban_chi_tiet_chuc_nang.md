# Kịch bản TaskNest — chức năng và quyền thực hiện

31 slide. Giữ mạch giới thiệu cũ, trình bày chức năng cốt lõi trước rồi mới đến Khám phá. Bản chi tiết phù hợp khoảng 20–25 phút, cần tập nói để căn thời lượng.

Quy ước: Owner là chủ dự án; Manager là quản lý được chỉ định trong dự án; Member là thành viên dự án. Chủ đội quản lý đội, không mặc nhiên có cùng quyền ở mọi dự án. Khách hàng là tài khoản gắn với quan hệ hợp tác cụ thể.

## Slide 1 · TaskNest

Chào mọi người, hôm nay mình muốn giới thiệu TaskNest. Nhóm mình làm sản phẩm này để các nhóm nhỏ có thể giao việc, ghi giờ và duyệt kết quả ngay trên cùng một nhiệm vụ.

Nói đến quản lý công việc, chắc mọi người nghĩ ngay đến Jira, Trello hay ClickUp. Nhóm mình cũng dùng Jira để quản lý backlog trong kỳ OJT. Vậy điều gì khiến tụi mình muốn làm thêm TaskNest?

**Chuyển slide** · Mình lấy một ví dụ nhé.

**Chuyển ý:** Tiếp theo là nộp thứ sáu, duyệt thứ bảy.

## Slide 2 · Nộp thứ Sáu, duyệt thứ Bảy

Giả sử một team thiết kế phải bàn giao bộ ảnh vào thứ Sáu. Bạn phụ trách gửi link đúng ngày, nhưng đến thứ Bảy quản lý mới mở ra duyệt. Nếu link nằm trong chat và giờ làm nằm trong bảng tính, lúc xem lại team phải tự ghép thông tin để biết đã làm bao lâu, bản nào được duyệt và bản đó có gửi đúng hạn không.

TaskNest tập trung vào đúng quy trình bàn giao mà các team nhỏ hay lặp lại. Ở ví dụ này, hệ thống xét thời điểm gửi của bản được duyệt, nên bản nộp thứ Sáu vẫn được ghi nhận là đúng hạn.

**Chuyển slide** · Trước khi xem sản phẩm xử lý việc này thế nào, mình giới thiệu nhanh phần việc của từng thành viên.

**Chuyển ý:** Tiếp theo là vai trò của bốn thành viên.

## Slide 3 · Vai trò của bốn thành viên

Khánh An điều phối nhóm, phụ trách kiến trúc, tích hợp và triển khai. Việt Anh làm UI/UX, từ thiết kế Figma đến giao diện React. Nguyên Đức phụ trách API, xác thực và nghiệp vụ tài khoản. Duy Mạnh phát triển tính năng ở cả frontend lẫn backend và kết nối các phân hệ.

**Chuyển slide** · Những phần việc đó ghép lại thành một sản phẩm mà team có thể dùng từ lúc tạo dự án đến lúc bàn giao.

**Chuyển ý:** Tiếp theo là mời và duyệt thành viên dự án.

## Slide 4 · Mời và duyệt thành viên dự án

Trước khi giao việc, dự án cần có thành viên. Owner hoặc Manager gửi lời mời trực tiếp đến tài khoản qua email. Người được mời tự chấp nhận. Nếu đi qua link hoặc mã QR, người dùng gửi yêu cầu tham gia và chờ Owner hoặc Manager duyệt. Chấp nhận xong, người đó có tư cách thành viên hoạt động trong dự án. Quyền của một người ở dự án này không tự áp dụng sang dự án khác.

**Chuyển ý:** Sau khi dự án có thành viên, mình đi vào quyền giao việc.

## Slide 5 · Giao việc và phân công

Owner và Manager được tạo nhiệm vụ và chọn người phụ trách trong các thành viên đang hoạt động của cùng dự án. Member cũng được tạo nhiệm vụ nhưng chỉ được chọn chính mình. Khi tạo, người dùng nhập nội dung, thời gian, mức ưu tiên và giờ ước tính. Nhiệm vụ mới ở trạng thái Chưa bắt đầu. Nếu cần sửa nhiệm vụ hoặc đổi người phụ trách sau đó, quyền cập nhật thuộc Owner hoặc Manager.

**Chuyển ý:** Tiếp theo là nộp kết quả công việc.

## Slide 6 · Nộp kết quả công việc

Sau khi bắt đầu thực hiện, người phụ trách gửi kết quả của chính nhiệm vụ mình được giao. Người nộp chọn một tệp hoặc một liên kết và bổ sung ghi chú để người duyệt đối chiếu. Gửi thành công sẽ tạo một lần nộp mới, ghi thời điểm gửi và hạn tại thời điểm đó. Nhiệm vụ chuyển sang Chờ duyệt. Nếu đang có timer của nhiệm vụ thì hệ thống kết thúc phiên đó. Có vai trò quản lý không tự cho phép nộp thay người phụ trách.

**Chuyển ý:** Tiếp theo là duyệt bản nộp công việc.

## Slide 7 · Duyệt bản nộp công việc

Người duyệt là Owner hoặc Manager của dự án. Đối tượng được duyệt là bản nộp mới nhất đang chờ xử lý, không phải một trạng thái hoàn thành do thành viên tự đánh dấu. Nếu chấp nhận, người duyệt xác nhận kết quả đạt yêu cầu; nhiệm vụ chuyển sang Hoàn thành và trỏ đến đúng bản đã duyệt. Nếu chưa đạt, người duyệt nhập lý do và hạn giao lại từ hôm nay. Người phụ trách sửa rồi nộp lại, tạo thêm một lần nộp để giữ lịch sử.

**Chuyển ý:** Tiếp theo là bắt đầu và dừng ghi giờ.

## Slide 8 · Bắt đầu và dừng ghi giờ

Người phụ trách bấm giờ trên nhiệm vụ đang thực hiện và không bị chặn. Mỗi người chỉ có một phiên timer đang chạy, kể cả khi mở nhiều tab hay làm ở nhiều dự án. Người dùng tự dừng phiên của mình để lưu khoảng thời gian. Giờ làm gắn với nhiệm vụ và người ghi, giúp đối chiếu công việc đã dùng bao nhiêu thời gian. Số giờ là dữ liệu theo dõi, không tự trở thành điểm năng suất.

**Chuyển ý:** Tiếp theo là bổ sung và chỉnh sửa giờ làm.

## Slide 9 · Bổ sung và chỉnh sửa giờ làm

Nếu quên bấm giờ, người phụ trách có thể bổ sung khoảng giờ cho nhiệm vụ của mình và ghi lý do. Với phiên đã lưu, người sở hữu phiên được chỉnh sửa sau khi dừng. Hệ thống kiểm tra giờ kết thúc phải sau giờ bắt đầu, không ở tương lai và không chồng lấn với phiên khác của cùng người. Nhiệm vụ đã hoàn thành hoặc huỷ không cho điều chỉnh giờ. Mỗi lần sửa đều lưu lịch sử trước và sau, thay vì âm thầm ghi đè.

**Chuyển ý:** Tiếp theo là theo dõi và xuất báo cáo.

## Slide 10 · Theo dõi và xuất báo cáo

Các thành viên không nhận cùng một báo cáo chỉ vì cùng tham gia dự án. Owner và Manager có phạm vi quản lý toàn dự án. Với Member, báo cáo nhiệm vụ lọc theo người được giao, báo cáo giờ lọc theo người ghi là chính họ. Người dùng chọn loại báo cáo và khoảng ngày để xuất CSV. Vì vậy, mình sẽ giới thiệu cụ thể ai thấy dữ liệu nào, thay vì chỉ nói chung sản phẩm có chức năng báo cáo.

**Chuyển ý:** Tiếp theo là trợ lý ai theo quyền người dùng.

## Slide 11 · Trợ lý AI theo quyền người dùng

Trợ lý AI lấy dữ liệu theo quyền của người đang sử dụng. Khi người dùng hỏi về một nhiệm vụ hay dự án, dịch vụ kiểm tra lại dữ liệu họ còn được xem trước khi tạo ngữ cảnh hoặc dùng kết quả lưu tạm. AI hỗ trợ tóm tắt, chỉ ra điểm cần chú ý và đề xuất bước tiếp theo. AI không tự giao việc, duyệt bản nộp hoặc nghiệm thu thay con người. Chức năng chỉ hoạt động khi dịch vụ AI đã được cấu hình và còn hạn mức.

**Chuyển ý:** Tiếp theo là khám phá.

## Slide 12 · Khám phá

Ở phần đầu, mình giới thiệu TaskNest với góc nhìn một nhóm đã có dự án và thành viên. Nhưng trong thực tế, trước khi giao việc, chúng ta còn phải tìm người và tìm đội để cùng làm.

Vì vậy, ngoài khu vực Làm việc, TaskNest hiện có thêm khu vực Khám phá. Người dùng có thể xem hồ sơ đội, tìm cơ hội tham gia đội hoặc xem các yêu cầu dự án. Phần này mở rộng hành trình sử dụng, còn giao việc, ghi giờ và duyệt kết quả vẫn là phần cốt lõi mà mình vừa trình bày.

**Chuyển slide** · Mình bắt đầu với tình huống một đội đang cần thêm người.

**Chuyển ý:** Tiếp theo là tạo và cập nhật hồ sơ đội.

## Slide 13 · Tạo và cập nhật hồ sơ đội

Người dùng đã xác minh email có thể tạo đội và trở thành chủ đội. Chủ đội cập nhật tên, mô tả, kỹ năng và trạng thái nhận việc. Người đang tìm đội xem hồ sơ công khai để biết chuyên môn, thành viên và đánh giá. Chủ đội là vai trò quản lý đội, còn Owner và Manager là vai trò ở từng dự án; ba khái niệm này không được dùng thay nhau.

**Chuyển ý:** Tiếp theo là đăng tuyển và gửi đơn ứng tuyển.

## Slide 14 · Đăng tuyển và gửi đơn ứng tuyển

Chủ đội đăng vị trí với kỹ năng, cách làm việc, số giờ, số người cần tuyển và hạn nhận đơn. Người dùng chưa thuộc đội, đã xác minh email và không vướng điều kiện xung đột khách hàng có thể ứng tuyển vào vị trí đang mở, còn hạn và còn chỗ. Đơn gồm giới thiệu, kỹ năng và số giờ có thể tham gia, kèm xác nhận đồng ý. Đơn chỉ ứng viên và chủ đội được xem.

**Chuyển ý:** Tiếp theo là duyệt đơn ứng tuyển vào đội.

## Slide 15 · Duyệt đơn ứng tuyển vào đội

Sau khi có đơn, chỉ chủ đội được xem danh sách ứng viên và quyết định nhận hay từ chối. Chủ đội xử lý đơn đang chờ của đúng vị trí thuộc đội mình. Khi nhận, hệ thống kiểm tra tin còn mở, còn hạn, còn chỉ tiêu và ứng viên chưa vào đội qua cách khác. Chấp nhận sẽ tạo thành viên thực sự trong đội. Nếu từ chối phải có phản hồi. Thành viên đội chưa tự nhận quyền ở những dự án đã tồn tại; quản lý dự án vẫn phải bổ sung riêng.

**Chuyển ý:** Tiếp theo là đăng yêu cầu tìm đội thực hiện.

## Slide 16 · Đăng yêu cầu tìm đội thực hiện

Ở phía khách hàng, người dùng đăng yêu cầu tìm đội thực hiện với nội dung, kỹ năng, khoảng ngân sách và ngày mong muốn bàn giao. Người đăng có thể giữ nháp hoặc công khai. Chỉ chủ yêu cầu được sửa, tạm dừng hoặc đóng yêu cầu của mình theo trạng thái được phép. Ngân sách giúp đội hiểu phạm vi thương lượng, hiện chưa phải tiền được thu qua TaskNest.

**Chuyển ý:** Tiếp theo là gửi đề xuất thực hiện dự án.

## Slide 17 · Gửi đề xuất thực hiện dự án

Đội muốn nhận việc phải gửi đề xuất qua chủ đội. Chủ đội chọn yêu cầu đang mở và nhập kế hoạch, chi phí cùng ngày bắt đầu, kết thúc dự kiến. Đề xuất gắn với phiên bản yêu cầu hiện tại; nếu khách sửa phạm vi thì đội phải gửi lại theo nội dung mới. Hệ thống cũng ngăn trường hợp đội gửi đề xuất cho khách đang là thành viên của chính đội. Thành viên thường trong đội không tự đại diện gửi đề xuất.

**Chuyển ý:** Tiếp theo là khách hàng lựa chọn đội.

## Slide 18 · Khách hàng lựa chọn đội

Quyết định chọn đội thuộc về người đăng yêu cầu, không thuộc một đội khác hay thành viên bất kỳ. Khách chọn một đề xuất đang chờ và còn khớp phiên bản yêu cầu. Hệ thống tạo dự án mới, đặt chủ đội làm Owner, thêm thành viên hiện tại của đội và khách hàng vào dự án rồi liên kết quan hệ hợp tác. Sau bước đó, đội sử dụng lại các chức năng giao việc, nộp và duyệt đã giới thiệu ở phần đầu.

**Chuyển ý:** Tiếp theo là lập và xác nhận kế hoạch mốc.

## Slide 19 · Lập và xác nhận kế hoạch mốc

Đội và khách hàng cần thống nhất thế nào là đạt trước khi bàn giao. Owner hoặc Manager phía đội tạo mốc với tiêu chí, thời hạn và nhiệm vụ cùng dự án. Người xác nhận kế hoạch là đúng khách hàng được gắn với quan hệ hợp tác, không phải mọi thành viên mang tên khách hàng. Khách xác nhận mốc đang chờ kế hoạch thì mốc mới chuyển sang hoạt động. Việc lập và xác nhận kế hoạch khác với nghiệm thu kết quả sau này.

**Chuyển ý:** Tiếp theo là gửi kết quả bàn giao theo mốc.

## Slide 20 · Gửi kết quả bàn giao theo mốc

Người gửi mốc là Owner hoặc Manager phía đội, khác với việc thành viên tự nộp nhiệm vụ nội bộ. Mốc phải đã được khách xác nhận kế hoạch hoặc đang được yêu cầu chỉnh sửa. Trước khi gửi, mọi nhiệm vụ liên kết phải hoàn thành hoặc huỷ. Đội gửi ghi chú và liên kết sản phẩm; hệ thống tạo lần bàn giao, giữ tiêu chí của lần đó và chuyển mốc sang Chờ nghiệm thu để khách hàng kiểm tra.

**Chuyển ý:** Tiếp theo là khách hàng nghiệm thu mốc.

## Slide 21 · Khách hàng nghiệm thu mốc

Ở bước này, người quyết định là khách hàng của quan hệ hợp tác. Khách kiểm tra đúng lần bàn giao mới nhất đang chờ nghiệm thu, xem liên kết kết quả và đối chiếu tiêu chí. Muốn chấp nhận phải xác nhận đủ tiêu chí. Nếu yêu cầu sửa thì phải ghi rõ phản hồi. Mốc chuyển sang trạng thái cần chỉnh sửa để đội gửi lại. Lịch sử vẫn giữ các lần bàn giao và phản hồi, nên quyết định nào cũng có đối tượng cụ thể.

**Chuyển ý:** Tiếp theo là nhắn tin, bình luận và tài liệu.

## Slide 22 · Nhắn tin, bình luận và tài liệu

Trao đổi được đặt theo đúng phạm vi: trò chuyện cá nhân giữa hai người, trò chuyện đội cho thành viên hiện tại và trò chuyện dự án cho người có quyền, gồm khách hàng có quan hệ hợp tác đã xác nhận. Bình luận gắn với nhiệm vụ giúp giữ ngữ cảnh. Thành viên cũng thêm tài liệu hoặc liên kết trong dự án. Với tài liệu, Member chỉ sửa hoặc xoá mục của mình; Owner và Manager quản lý theo vai trò. Không phải thấy hồ sơ công khai là được đọc trao đổi nội bộ.

**Chuyển ý:** Tiếp theo là nghiệm thu toàn bộ dự án.

## Slide 23 · Nghiệm thu toàn bộ dự án

Chấp nhận một mốc chưa tự đồng nghĩa toàn dự án được nghiệm thu. Khách hàng thực hiện xác nhận cuối cùng khi hợp tác còn đang hoạt động. Hệ thống yêu cầu các mốc đều đã được chấp nhận hoặc huỷ; các nhiệm vụ đều đã hoàn thành hoặc huỷ và phải có ít nhất một nhiệm vụ hoàn thành. Khi hợp lệ, quan hệ hợp tác chuyển sang Đã nghiệm thu và hệ thống lưu những thành viên có đóng góp qua nhiệm vụ hoàn thành. Đây là điều kiện để mở bước đánh giá.

**Chuyển ý:** Tiếp theo là đánh giá đội và ghi nhận thành viên.

## Slide 24 · Đánh giá đội và ghi nhận thành viên

Sau nghiệm thu, khách hàng đã xác nhận hợp tác được đánh giá đội theo chất lượng, tiến độ, giao tiếp và hỗ trợ, kèm nhận xét và mong muốn hợp tác lại. Chủ đội được phản hồi đánh giá. Khách cũng có thể ghi nhận những thành viên nằm trong danh sách đóng góp đã lưu khi nghiệm thu. Lượt thích hồ sơ là tương tác công khai thông thường, còn đánh giá hợp tác có điều kiện gắn với dự án cụ thể. Nhóm không gọi mọi lượt thích là đánh giá khách hàng.

**Chuyển ý:** Tiếp theo là các dịch vụ sau api gateway.

## Slide 25 · Các dịch vụ sau API Gateway

Khi mình bấm gửi, yêu cầu từ trình duyệt đi qua API Gateway rồi đến Work Service để lưu bản nộp. Thông báo phát sinh được chuyển qua RabbitMQ để xử lý ở dịch vụ Notification. Phần tài khoản do Identity quản lý, còn gợi ý AI chạy ở dịch vụ riêng khi được bật.

**Chuyển slide** · Vậy Work Service lưu gì để khi mở lại, mình vẫn biết đúng bản nào đã được duyệt?

**Chuyển ý:** Tiếp theo là dữ liệu xoay quanh nhiệm vụ.

## Slide 26 · Dữ liệu xoay quanh nhiệm vụ

Mọi người nhìn vào ô **Nhiệm vụ** nhé. Một nhiệm vụ có thể có nhiều phiên ghi giờ và nhiều lần nộp. Ví dụ, lần đầu bị yêu cầu sửa, lần hai được chấp nhận. Hai lần nộp được lưu riêng, còn nhiệm vụ ghi rõ lần nào được duyệt.

Mỗi lần nộp cũng giữ thời điểm gửi và hạn nộp tại lúc đó. Nhờ vậy, khi quay lại ví dụ thứ Sáu và thứ Bảy, mình biết được bản được duyệt có gửi đúng hạn hay không.

**Chuyển slide** · Đó là cách nhóm tổ chức dữ liệu. Còn đây là các công nghệ nhóm dùng để xây hệ thống.

**Chuyển ý:** Tiếp theo là tasknest dùng công nghệ gì?.

## Slide 27 · TaskNest dùng công nghệ gì?

Phía giao diện, nhóm dùng React, TypeScript và Tailwind CSS. Backend chạy Java 21 với Spring Boot và Spring Cloud. Dữ liệu lưu trong MySQL, còn Flyway quản lý các thay đổi schema.

Về giao tiếp, REST dùng cho các yêu cầu từ giao diện, WebSocket báo có cập nhật, RabbitMQ chuyển sự kiện để xử lý nền. Nhóm dùng Docker Compose để chạy các dịch vụ và GitHub Actions để kiểm thử, đóng gói.

**Chuyển slide** · Một chỗ mọi người hay hỏi là TaskNest xử lý mật khẩu và phiên đăng nhập thế nào.

**Chuyển ý:** Tiếp theo là mật khẩu và phiên đăng nhập.

## Slide 28 · Mật khẩu và phiên đăng nhập

Khi đăng ký, TaskNest dùng **BCrypt để băm mật khẩu**. Khi đăng nhập, hệ thống kiểm tra mật khẩu nhập vào dựa trên bản băm đã lưu. Sau khi xác thực, hệ thống cấp access token dạng JWT, ký bằng **RS256** để các dịch vụ xác minh chữ ký.

Refresh token đi qua cookie **HttpOnly**, được thay khi làm mới phiên và cơ sở dữ liệu lưu bản băm **SHA-256** của nó. Còn **AES-256-GCM** dùng để mã hóa nội dung nhạy cảm được xếp hàng gửi email.

**Chuyển slide** · Ngoài bảo vệ tài khoản, nhóm còn đặt ra vài quy tắc để công việc được xử lý đúng khi nhiều người dùng cùng lúc.

**Chuyển ý:** Tiếp theo là ba quy tắc giữ luồng nhất quán.

## Slide 29 · Ba quy tắc giữ luồng nhất quán

Đầu tiên, backend kiểm tra quyền trong dự án. Ví dụ, người phụ trách có thể nộp kết quả, còn người có quyền quản lý mới duyệt được.

Thứ hai, nếu một bạn mở hai tab và bấm giờ đồng thời, cơ sở dữ liệu chỉ cho phép một phiên đang chạy. Thứ ba, sự kiện cần gửi được lưu cùng thay đổi nghiệp vụ, rồi mới phát qua RabbitMQ. Chẳng hạn, bản nộp phải được lưu thành công trước khi sự kiện thông báo được phát đi.

**Chuyển slide** · Nếu muốn đưa TaskNest ra ngoài phạm vi OJT, nhóm mình sẽ bắt đầu với một nhóm khách hàng cụ thể.

**Chuyển ý:** Tiếp theo là định hướng thương mại hoá.

## Slide 30 · Định hướng thương mại hoá

Với những chức năng hiện có, nhóm muốn thử TaskNest với các đội làm website, thiết kế hoặc nội dung nhỏ. Đây là nhóm thường làm theo dự án, có bàn giao kết quả và cần khách hàng xác nhận.

Bước đầu, nhóm sẽ mời một số đội dùng trên một dự án thật. Mình muốn quan sát họ có dùng xuyên suốt từ giao việc đến nghiệm thu hay vẫn phải chuyển sang công cụ khác, thời gian chờ duyệt có thuận tiện hơn không và họ có muốn tiếp tục dùng ở dự án sau không.

Khi có người dùng quay lại, nhóm mới thử gói thu phí theo đội hoặc số dự án đang hoạt động. Những phần có thể phát triển thêm là báo cáo cho nhiều dự án, quy trình duyệt nhiều cấp và tích hợp thanh toán. Đây là định hướng tiếp theo, chưa phải các chức năng đã triển khai hay mô hình đã được kiểm chứng.

**Chuyển slide** · Cuối cùng, mình quay lại tình huống bàn giao bộ ảnh lúc đầu.

**Chuyển ý:** Tiếp theo là tasknest.

## Slide 31 · TaskNest

Với bộ ảnh bàn giao lúc đầu, mình muốn cả team mở đúng một nhiệm vụ và trả lời được ba câu: đã làm bao nhiêu giờ, bản nào được duyệt và bản đó có nộp đúng hạn không.

Đó vẫn là giá trị cốt lõi của TaskNest. Phần Khám phá mở rộng thêm bước tìm người, tìm đội và nhận yêu cầu; phần mốc bàn giao giúp nối kết quả làm việc bên trong đội với quyết định nghiệm thu của khách hàng.

Cảm ơn mọi người đã lắng nghe. Nhóm mình xin nhận câu hỏi và góp ý.

## Khi hội đồng hỏi sâu

**Member có giao việc cho người khác được không?** Không. Member chỉ được tạo nhiệm vụ cho chính mình. Owner hoặc Manager có thể giao cho thành viên đang hoạt động trong cùng dự án.

**Ai có quyền nộp thay?** Quyền nộp kiểm tra theo người phụ trách. Owner hoặc Manager chỉ nộp được khi chính họ là người phụ trách nhiệm vụ đó.

**Duyệt kết quả và nghiệm thu có giống nhau không?** Owner/Manager duyệt bản nộp nhiệm vụ nội bộ. Khách hàng xác nhận kết quả bàn giao theo mốc và nghiệm thu toàn dự án khi đủ điều kiện.

**Hệ thống có luôn buộc người nộp và người duyệt là hai người khác nhau không?** Hiện mã nguồn kiểm tra vai trò Owner/Manager và trạng thái chờ duyệt, chưa có quy tắc cấm quản lý duyệt nhiệm vụ do chính họ phụ trách. Không trình bày như tính năng đã có.

**Nhận vào đội có tự vào mọi dự án không?** Không. Duyệt ứng viên tạo thành viên của đội; quyền trong dự án được quản lý riêng. Khi khách chọn đội qua marketplace, hệ thống tạo dự án mới và thêm thành viên hiện tại của đội cùng khách hàng.
