# Bài 3 : Xây dựng Không gian Cộng tác Doanh nghiệp

## 4.Ràng buộc & Bẫy dữ liệu:
+ Áp dụng giao tiếp bất đồng bộ Asynchronous Communication không bắt buộc thành viên phải trả lời ngay lập tức mà phản hồi tin nhắn phù hợp với thời gian lm việc của mình


## 5.Yêu cầu đầu ra 
          - sơ đồ kiến trúc kênh: 
  + bấm dấu ( + ) -> new group -> phần group type chọn topic -> create
 
         -quy định nội dung cho từng câu: 
+ Tính năng Reply in Thread được sử dụng để trả lời trực tiếp dưới một tin nhắn gốckhi nhắn giúp các nội dung thảo luận không bị trôi
+ Không gửi nhiều tin nhắn riêng lẻ liên tiếp làm trôi nội dung chính
+ Chỉ tạo tin nhắn mới khi có một chủ đề thảo luận hoàn toàn khác

         -Bản quy ước giao tiếp:3 quy tắc vàng để tránh
                  Hạn chế No-Hello Trap
+ thay vì nhắn có ai không rồi ngồi chờ người khác trả lời rồi mình mới nói thì mình có thể hỏi luôn hoặc nói luôn vấn đề của mình đang mắc phải và thắc mắc
                    Hạn chế spam @all
+ chỉ trưởng nhóm mới sử dụng @all khi có thông báo quan trọng , các thành viên không sử dụng @all để hỏi những vấn đề cá nhân tránh làm phiền những bạn khác 
+ dùng giao tiếp bất đồng bộ Không yêu cầu thành viên phải trả lời tin nhắn ngay lập tức 
