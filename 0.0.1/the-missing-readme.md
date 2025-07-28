# Main 1
```bash
Inertia, the characteristic that we’ve added to Ousterhout’s list, is software’s
tendency to stay in use. Easily discarded code used for a quick experiment has
low inertia. A service that powers a dozen business-critical applications has high
inertia. Complexity’s cost accrues over time, so high-inertia, high-change
systems should be simplified, while low-inertia or low-change systems can be
left complex (as long as you discard them or continue to leave them alone).
```
# Main 2
```bash
đã đọc đến trang 29
```
  NGÀY CHRIS XÓA TOÀN BỘ MÃ NGUỒN

  Trong một kỳ thực tập đầu tiên của Chris, anh ấy làm việc trong một dự án cùng với một kỹ sư cấp cao. Chris đã hoàn thành một số thay đổi và cần đưa chúng vào triển khai. Kỹ sư cấp cao đã hướng dẫn anh cách kiểm tra mã nguồn vào hệ thống quản lý phiên bản, cụ thể là CVS. Chris làm theo hướng dẫn một cách máy móc, lần lượt thực hiện các bước liên quan đến việc tạo nhánh, gắn thẻ và gộp nhánh.
  
  Sau đó, anh tiếp tục làm nốt công việc trong ngày rồi ra về. Sáng hôm sau, Chris vui vẻ bước vào văn phòng và chào mọi người. Họ cố gắng đáp lại anh một cách lịch sự, nhưng không khí thì u ám. Khi Chris hỏi có chuyện gì đang xảy ra, họ thông báo rằng anh đã làm hỏng toàn bộ kho mã CVS. Toàn bộ mã nguồn của công ty đã bị mất.
  
  Mọi người đã thức trắng đêm cố gắng phục hồi lại những gì có thể, và cuối cùng họ đã lấy lại được phần lớn mã nguồn (trừ các commit của Chris và một vài commit khác). Chris bị sốc nặng vì chuyện này. Quản lý của anh kéo anh ra nói chuyện riêng và bảo rằng đừng lo lắng: Chris đã làm đúng khi làm việc cùng kỹ sư cấp cao.
  
  Sai lầm là chuyện sẽ xảy ra. Mỗi kỹ sư đều có một phiên bản câu chuyện như vậy.
  Hãy cố gắng hết sức, và cố gắng hiểu những gì bạn đang làm — nhưng cũng hãy biết rằng, những chuyện như thế này là điều không thể tránh khỏi.

# Main 3
```bash
đã đọc hết trang 35
```
# Main 4:
```bash
đã đọc hết trang 45
```
# Main 5:
Đã đọc nữa đầu trang 46

Hãy Thực Dụng Khi Cần Refactoring
Refactoring không phải lúc nào cũng là lựa chọn khôn ngoan. Có những hạn chót và ưu tiên cạnh tranh. Việc refactoring tốn thời gian, và đội ngũ của bạn có thể quyết định bỏ qua cơ hội refactoring để kịp giao những tính năng mới. Những quyết định như vậy sẽ tích lũy “technical debt” (nợ kỹ thuật) – đôi khi đó là phương án đúng đắn. Chi phí cho việc refactor cũng có thể vượt quá giá trị thu được. Những đoạn mã cũ đã lỗi thời và sắp bị thay thế thì không cần phải refactor, cũng như những đoạn mã có rủi ro thấp hoặc hiếm khi được chỉnh sửa. Hãy thực dụng trong việc quyết định khi nào nên refactor.

# Main 47:
- Xong trang 47
- Tránh những sai lầm phổ biến
- Mã nguồn hiện tại thường đi kèm với nhiều "hành lý" quá khứ. Các thư viện, framework, và pattern đã được thiết lập sẵn. Một số tiêu chuẩn có thể khiến bạn khó chịu. Mong muốn làm việc với code sạch sẽ và tech stack hiện đại là điều tự nhiên, nhưng việc viết lại mã hoặc phớt lờ tiêu chuẩn là rất nguy hiểm.

- Việc viết lại mã nếu không được thực hiện đúng cách có thể làm mất ổn định toàn bộ codebase, và thường phải đánh đổi bằng việc không thể phát triển tính năng mới. Trong khi đó, các tiêu chuẩn mã nguồn giúp giữ cho code dễ đọc và dễ hiểu — đi lệch khỏi chúng sẽ khiến các lập trình viên khác khó tiếp cận hơn.

- Trong cuốn sách The Hard Thing About Hard Things của mình, Ben Horowitz nói:

- "Điều quan trọng nhất mà bất kỳ startup công nghệ nào cần làm là tạo ra một sản phẩm tốt hơn ít nhất mười lần so với cách làm hiện tại. Nếu chỉ tốt hơn hai hoặc ba lần thì sẽ không đủ sức khiến người dùng chuyển sang sản phẩm mới đủ nhanh hoặc đủ nhiều để tạo ra khác biệt."

- Dù Ben đang nói về sản phẩm startup, nhưng nguyên lý đó cũng áp dụng cho code:
Nếu bạn muốn viết lại mã hay thay đổi tiêu chuẩn, thì sự cải tiến phải thực sự đột phá.
Những cải tiến nhỏ không xứng đáng với cái giá phải trả.

- Hầu hết lập trình viên đánh giá thấp giá trị của việc tuân thủ quy ước, trong khi lại quá đánh giá cao việc tự ý thay đổi.

- Lời khuyên tổng kết:

- Cẩn thận với việc viết lại mã, phá vỡ quy ước, hoặc thêm công nghệ mới vào stack.

- Chỉ nên viết lại code trong những tình huống thật sự mang lại giá trị lớn.

- Hãy ưu tiên dùng công nghệ "nhàm chán" nhưng ổn định khi có thể.

- Đừng bỏ qua các quy chuẩn, ngay cả khi bạn không đồng ý với chúng.

- Tránh việc fork code trừ khi thực sự cần thiết.




