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

# Main 6:
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
# Main 7:
- Phần mềm là một lĩnh vực thay đổi nhanh chóng. Các công cụ, ngôn ngữ và framework mới liên tục ra đời. So với những gì đang "hot" trên mạng, mã nguồn hiện tại thường trông lỗi thời. Tuy nhiên, các công ty thành công thường sở hữu những hệ thống với thư viện và mẫu thiết kế cũ — và điều đó có lý do: thành công cần thời gian, còn việc thay đổi công nghệ liên tục chỉ là một sự xao nhãng.
- Tất cả công nghệ rồi sẽ gặp lỗi, nhưng công nghệ cũ thì lỗi theo cách có thể đoán trước. Trong khi đó, công nghệ mới lại thường gặp lỗi theo cách bất ngờ. Do thiếu độ trưởng thành, công nghệ mới có cộng đồng nhỏ hơn, ít tài liệu hơn, ít ổn định hơn và không tương thích nhiều. Bạn sẽ khó tìm được câu trả lời trên Stack Overflow.

# Main 8:
```bash
đã đọc đến trang 58
```
- Code sẽ có những hành vi kỳ lạ khi đưa ra “thế giới thực”. Người dùng thì khó đoán, mạng thì không ổn định, và mọi thứ đều có thể trục trặc. Phần mềm chạy trong môi trường production phải luôn hoạt động ổn định. Việc viết code có khả năng vận hành (operable code) sẽ giúp bạn xử lý những tình huống không lường trước được.

- Code có khả năng vận hành là code có sẵn cơ chế bảo vệ, chẩn đoán và kiểm soát.
# Main 9:
```bash
Đã đọc đến trang 61
```
- Giải phóng tài nguyên đúng cách
- Hãy luôn chắc chắn rằng tất cả tài nguyên được giải phóng khi có lỗi xảy ra.
- Điều này bao gồm:
+ Giải phóng bộ nhớ
+ Xóa các cấu trúc dữ liệu không còn dùng
+ Đóng kết nối mạng (network sockets)
+ Đóng các file handle
- Hệ điều hành chỉ cấp một số lượng giới hạn file handle và network socket.
- Nếu bạn không đóng chúng sau khi sử dụng, hệ thống sẽ cạn kiệt tài nguyên, khiến các kết nối mới hoặc file mới không thể mở được.
*Thiết kế hệ thống mà luôn giải phóng tài nguyên dù có lỗi hay không là một phần quan trọng giúp ứng dụng ổn định, bền vững và dễ bảo trì.*

# Main 10:
```bash
Đã đọc đến trang 65
```
- Giữ log “nguyên tử” (atomic): gom đủ thông tin vào một dòng, tránh xuống dòng; không giả định thứ tự log; nếu buộc phải tách, gắn unique ID để ghép lại.

# Main 11:
```bash
Đã đọc đến trang 68 - Measure Everything
```
# Main 12:
```bash
Đã đọc đến trang 71
```
- Việc sáng tạo trong hệ thống cấu hình nghe có vẻ hấp dẫn. Cấu hình là thứ quen thuộc với mọi người, và những hệ thống cấu hình đơn giản thường thiếu đi các tính năng “hay ho” như thay thế biến, câu lệnh điều kiện if, v.v. Nhiều người sáng tạo và thiện chí đã tốn vô số thời gian để xây dựng những hệ thống cấu hình “hào nhoáng”. Nhưng đáng buồn là, càng “thông minh” thì lỗi phát sinh càng kỳ quặc. Đừng sáng tạo với cấu hình — hãy dùng cách đơn giản nhất có thể. Một file cấu hình tĩnh theo định dạng chuẩn duy nhất thường là lý tưởng nhất.

# Main 13:
```bash
Đã đọc đến trang 76
```
- Trong chương này, chúng ta sẽ đi qua các nguyên tắc cơ bản của quản lý dependency, và bàn về cơn ác mộng lớn nhất của mọi kỹ sư: dependency hell.

# Main 14:
```bash
Đã đọc đến trang 79
```
Phụ thuộc bắc cầu (Transitive Dependencies)

# Main 15:
## Tránh “Dependency Hell”
- Bạn chắc chắn sẽ vấp phải dependency hell. Phụ thuộc (dependencies) là không thể tránh khỏi, nhưng mỗi dependency mới đều đi kèm với một cái giá. Hãy tự hỏi bản thân: giá trị của dependency đó có lớn hơn chi phí mà nó mang lại hay không?
- Bạn có thực sự cần chức năng đó không?
- Dependency đó được duy trì (maintain) tốt đến mức nào?
- Nếu có vấn đề, bạn (hoặc team) có dễ dàng sửa được dependency đó không?
- Dependency đó trưởng thành (mature) đến mức nào?
- Nó có thường xuyên giới thiệu các thay đổi không tương thích ngược không?
- Bạn, team của bạn, và tổ chức của bạn hiểu dependency đó đến đâu?
- Việc tự viết code thay thế có dễ không?
- Code đó có giấy phép (license) ra sao?
- Tỷ lệ code bạn thực sự sử dụng so với phần code thừa trong dependency là bao nhiêu?
- *Khi bạn quyết định thêm dependency, hãy tuân theo những best practice trên.*
# Main 16:
## Kiểm thử
- Việc viết, chạy và sửa lỗi test đôi khi có cảm giác như là việc làm thừa. Thực tế, test rất dễ biến thành việc làm thừa. Những test tệ hại sẽ tạo thêm gánh nặng cho lập trình viên mà không mang lại giá trị, thậm chí còn làm tăng sự bất ổn định của bộ test. Chương này sẽ dạy bạn cách kiểm thử hiệu quả. Chúng ta sẽ bàn về mục đích của test, các loại test khác nhau, các công cụ test khác nhau, cách kiểm thử có trách nhiệm, và cách xử lý tính không xác định (nondeterminism) trong test.

## Nhiều công dụng của test

- Hầu hết lập trình viên đều biết chức năng cơ bản của test: kiểm tra xem code có hoạt động không. Nhưng test còn có nhiều mục đích khác. Chúng bảo vệ code trước những thay đổi trong tương lai có thể vô tình làm thay đổi hành vi, khuyến khích viết code sạch, buộc lập trình viên phải sử dụng chính API của mình, ghi lại cách các thành phần nên được tương tác, và đóng vai trò như một sân chơi để thử nghiệm.

- Quan trọng nhất, test xác minh rằng phần mềm hoạt động đúng như mong đợi. Hành vi khó đoán sẽ gây rắc rối cho người dùng, lập trình viên và cả đội vận hành. Ban đầu, test cho thấy code hoạt động đúng như đặc tả. Sau đó, test được giữ lại để bảo vệ hành vi hiện có trước những thay đổi mới. Khi một test cũ bị fail, cần phải đưa ra quyết định: lập trình viên có thật sự muốn thay đổi hành vi, hay vừa tạo ra một bug?

- Việc viết test cũng buộc lập trình viên phải suy nghĩ về giao diện (interface) và cách cài đặt (implementation) của chương trình. Thông thường, lập trình viên lần đầu tương tác với code chính là trong test. Code mới thường có nhiều góc cạnh thô ráp; test sẽ làm lộ ra những thiết kế giao diện vụng về để có thể chỉnh sửa sớm. Test cũng làm lộ ra những cài đặt lộn xộn. Code spaghetti – code có quá nhiều phụ thuộc – sẽ rất khó để test. Viết test buộc lập trình viên phải tách bạch trách nhiệm rõ ràng và giảm sự phụ thuộc chặt chẽ.

- Ảnh hưởng phụ trong việc giữ code sạch từ test mạnh mẽ đến mức phát triển hướng kiểm thử (TDD) đã trở nên phổ biến. TDD là việc viết test trước khi viết code. Ban đầu test sẽ fail, rồi sau đó viết code để chúng pass. TDD buộc lập trình viên phải suy nghĩ về hành vi, thiết kế giao diện, và cách tích hợp trước khi "cày" ra một đống code.

- Test cũng đóng vai trò như một dạng tài liệu, minh họa cách code nên được sử dụng. Chúng là nơi đầu tiên mà một lập trình viên có kinh nghiệm sẽ tìm đến để hiểu một codebase mới. Bộ test cũng là một sân chơi tuyệt vời. Lập trình viên có thể chạy test cùng với debugger để bước qua code. Khi bug được phát hiện hoặc có thắc mắc về hành vi, có thể viết thêm test để hiểu rõ hơn.
# Main 17:
- Đã đọc hết trang 90
# Main 18:
- Đã đọc hết trang 95
*Write clean test*
