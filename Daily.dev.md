- Theo kinh nghiệm của tôi, thường có ba loại nhà phát triển, bất kể chức danh công việc, có thể khác nhau rất nhiều.
# Type 1:
```
  Có siêu sao. Ban quản lý thậm chí còn nhận ra những người này giỏi đến mức nào…
  họ hoàn thành mã hoạt động theo các hướng dẫn chặt chẽ, không tạo ra nhiều lỗi và giải quyết các lỗi khó chịu nhất khi chúng xảy ra.
  Tôi ngưỡng mộ những người này, nhưng đôi khi lại ghen tị với kỹ năng của họ
```
# Type 2:
```
Sau đó là các lập trình viên cấp cao. Có nhiều kinh nghiệm, phải là lập trình viên giỏi, có khả năng tự định hướng.
Phải có khả năng đáp ứng các yêu cầu và tạo mã hoạt động, có thể tham khảo ý kiến ​​​​của các kỹ sư cấp cao khác và bất kỳ ai khác.
Hầu hết trong 10 năm qua, tất cả những người tôi làm việc cùng đều là cấp cao…với hơn 20 năm kinh nghiệm. Họ giỏi nhưng không bằng kiểu siêu sao
```
# Type 3:
```
Sau đó là những người khác. Hoặc là họ thiếu kinh nghiệm hoặc hơi yếu.
Họ thường cần các lập trình viên cấp cao và/hoặc trưởng nhóm để giám sát những gì họ đang làm.
Hoặc có thể họ được giao những nhiệm vụ dễ dàng hơn.
```
# Type 4:
https://creatoreconomy.so/p/40-life-lessons-i-know-at-40-i-wish-i-knew-at-20?ref=dailydev

# Type 5:
```
Learning by immersion works naturalistically when the material has a low enough complexity relative to your prior knowledge
that you can successfully process it on the fly, and when natural participation routinely reinforces everything important,
so that you build fluency. When those conditions aren’t satisfied—which is most of the time—you’ll need some support.
```
# Type 6:
```
“This section will help you understand how to think of signals in terms of frequency spectra.
That’s what low-pass filters manipulate.”
```
# Type 7:
```
But I think there’s a huge amount of value in shared canonical artifacts—in any given field,
there are key texts that everyone can refer to, and they form common ground for the culture. 
```
# Type 8:
```
There are some easier cases.
If you’re learning something new in a domain you know well, each new fact connects to lots of prior knowledge.
That creates more cues for recall and more opportunities for reinforcement.
And if you’re in some setting where you need that knowledge every single day,
you’ll find that your memory becomes reliable pretty quickly.
```
# Type 9:
```
App: Đất, bán cầu, bọc bằng kính, người trong đó, thảo luận, suy nghĩ, sinh sống, chỉ 1 bán cầu, tất cả mọi người phải vào đây.
```
# Type 10:
```
Hiểu rằng các tầng lớp xã hội khác nhau có những quan niệm khác nhau về cách thế giới vận hành.
Tôi lớn lên thuộc tầng lớp lao động, cổ xanh. Chúng tôi làm việc trong ngành công nghiệp cổ trắng.
Vì xuất thân của mình nên tôi nghĩ nếu chăm chỉ, làm tốt công việc thì mình sẽ thăng tiến.
Điều đó đúng với bố tôi, người đã thăng tiến từ vị trí quản lý nhà máy lên vị trí kiểm soát chất lượng, quản lý chất lượng và cuối cùng là giám đốc nhà máy.
Nhưng trong thế giới cổ trắng, vấn đề quan trọng hơn nhiều là các mối quan hệ và quyền lực hơn là công việc của bạn.
Tôi vẫn còn vật lộn với bài học này. Tôi vẫn muốn nó liên quan đến công việc của tôi.
Nhưng phải đến khi xây dựng được các mối quan hệ và quyền lực, tôi mới có thể đạt đến cấp độ Giám đốc.
Nếu tôi muốn đạt được cấp VP, tôi thậm chí còn có nhiều việc phải làm ở đó.
```
# Type 11:
***What are the key skills that someone designing software systems should have?***
```
Thiết kế hệ thống phần mềm không phải là về một bộ kỹ năng cụ thể - đó là kinh nghiệm giải quyết các vấn đề thực sự quan trọng
Bạn không có được trải nghiệm đó từ các chương trình đào tạo về mã, video trên youtube hoặc “lớp học” lập trình tự học.
Ngay cả một chương trình cấp bằng CS thực sự chỉ là một tập hợp các khóa học lịch sử về cách những người khác trước đây giải quyết các vấn đề phổ biến.
Không có kinh nghiệm đạt được
```
***Solution: Tham gia kiến trúc phần mềm và liên tục rút kinh nghiệm sau những lần thiết kế thử, thiết kế thất bại***
# Type 12:
```
One important criteria for good software design is, that it is future proof. Since technology changes fast, the separation of technology and application logic is important. It is a specialization of the separation of concern principal. During decomposition you have to keep an eye on the dependencies on technologies. If a component depends on a particular technology it should be encapsulated in a way that allows you to define pure application logic components. Replacing a technology should not cross package boundaries

Example:
if we store log messages in a database, the service must not be named “ILogDatabase” since it provides information about the technology used. Instead, name the service “ILogRepository” or “ILogServer” and add a sub package “logDatabase” which implements the connection to the DBMS. You can verify that your architecture fulfills this principal by asking the question “What do I need to change if I store the log data in an XML file in future?”. The answer should be “only this one particular technology depend package” and definitely no public interface.
```
# Type 13:
```
Become the go-to engineer in your organization
```
# Type 14:
![image](https://www.jointaro.com/blog/content/images/2024/06/Session-1.png)
```
Nhảy việc liên tục là một công thức để mãi mãi mắc kẹt ở cấp độ L5 (cấp cao) hoặc thấp hơn.
```
# Type 15:
```
Là nhà phát triển, chúng tôi rất quan tâm đến các công cụ và quy trình của mình.
Vì vậy, chúng ta nên luôn tìm kiếm những quy trình không cần thiết và loại bỏ chúng.
Tại Trunk, chúng tôi đã định cấu hình thiết lập Git của mình để không "enforce the arbitrary commit message required rule".
Điều này giúp chúng tôi tiết kiệm rất nhiều thời gian và chúng tôi đặc biệt khuyến khích mọi người cũng làm như vậy.

Với một nguồn sự thật duy nhất, phổ biến, lịch sử cam kết yêu cầu kéo của chúng tôi trở nên vô dụng.
Không ai quan tâm đến những gì chúng tôi đã viết trong thông điệp cam kết của mình, liệu chúng có tốt hay không.
Ngày nay, ngữ cảnh bổ sung được chia sẻ qua email, Slack hoặc tài liệu.
Khi chúng ta phát triển, chúng ta nên xác định nhiều cách hơn để cải thiện quy trình làm việc của mình và giảm thiểu chi phí tinh thần.

Trong GitHub, sẽ khó thực hiện bất kỳ điều gì khác ngoài việc hợp nhất các PR vào một nhánh chính —
sử dụng PR Tiêu đề và Mô tả làm thông báo cam kết mặc định.
Có một số lượng lớn các công ty mà chúng tôi nói chuyện về việc hợp nhất nhưng không sáp nhập chỉ vì họ không biết rõ hơn.
Sự phình to cực độ tích tụ là điều tồi tệ.
“Điểm lưu cục bộ” của mọi người sẽ làm ô nhiễm lịch sử chi nhánh chính của bạn mãi mãi.

Nó cũng phá vỡ một đặc tính thực sự quan trọng mà mọi người nên phấn đấu:
- Mọi cam kết về "main" phải có hiệu quả.
- Các cam kết cục bộ trên nhánh PR của bạn không cần phải hoạt động - trên thực tế, chúng thường bị hỏng.
- Ngoài ra, GitHub nên ngừng hiển thị các cam kết cục bộ trên nhánh PR hoặc làm cho việc tìm kiếm trở nên khó khăn hơn.
Đó chỉ là tiếng ồn mà không ai quan tâm
```
# Type 16:
*Đây là kinh nghiệm tuyển dụng của 1 Tech Lead*
```
Tôi nhớ mình đã ngồi vào bàn họp để đưa ra quyết định cuối cùng và
hơi ngạc nhiên khi nhận ra rằng kỹ năng chuyên môn của từng ứng viên được thảo luận rất ít.
Một phần là do họ là những ứng viên mới vào nghề
nên người ta cho rằng kỹ năng kỹ thuật của họ sẽ
không được phát triển và đây không phải là trọng tâm chính
của cuộc thảo luận.

Tuy nhiên, ngay cả đối với những vị trí tuyển dụng cao cấp hơn,
đặc biệt là các vị trí cấp cao, điều quan trọng là phải xem xét các kỹ năng như giao tiếp,
tài liệu, khả năng thích ứng, tính chủ động và các kỹ năng khác thường được đề cập.
Những kỹ năng mềm này là nền tảng và có thể quyết định sự thành công của vai trò này,
bên cạnh các kỹ năng kỹ thuật.
```
# Type 17:
![Dr Milan Milanović](https://milan.milanovic.org/authors/admin/avatar_hu6b2bc098fba5feccb4c6beb4e8cc5482_90406_250x250_fill_q90_lanczos_center.jpg) ***- Dr Milan Milanović -***
```
Trong khi việc ghi lại kiến ​​thức thường là một hoạt động thụ động thì việc chia sẻ lại là một hoạt động tích cực hơn.
Kèm cặp ngụ ý có một người hướng dẫn sẽ truyền đạt kiến ​​thức của mình cho người được cố vấn.
Kèm cặp là một kỹ thuật mạnh mẽ để chia sẻ kiến ​​thức, được chứng minh là hiệu quả nhất,
vì vậy nó rất quan trọng, đặc biệt đối với các nhà phát triển cấp dưới để tìm một người cố vấn khi bắt đầu dự án.
Người cố vấn sẽ giúp các thành viên mới làm quen với dự án,
đồng thời đánh giá mã và giới thiệu cho họ các loại kiến ​​thức ẩn giấu khác nhau trong mã nguồn dự án.
```
# Type 18:
***- Profile Social You Need -***
![Profile Social Links](https://res.cloudinary.com/daily-now/image/upload/s--94i2emXu--/f_auto/v1722252861/posts/7MoC0mdaQ)
# Type 19:
![Peter Yang](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F46680948-d2cb-4f7a-b2d2-c7e29b52b783_1280x720.png)
***- Peter Yang -***
```
To have a fulfilling career:
Follow your curiosity, push yourself to do hard things, and learn from failures.

Thành công không chỉ là sự nghiệp của bạn.
Đừng ràng buộc giá trị bản thân của bạn với một chức danh hay tên công ty hoa mỹ.
Xếp chồng các thông tin xác thực là một sự theo đuổi vô hồn.
Hàng năm, tôi xếp hạng những gì quan trọng nhất trong cuộc đời mình—ngăn xếp của năm nay: sức khỏe, gia đình, sự nghiệp, bạn bè và sở thích.
Cuộc sống luôn năng động - sở thích và ưu tiên của bạn sẽ thay đổi theo thời gian và điều đó hoàn toàn bình thường!
```
# Type 20:
```
Hầu hết các chương trình đều là hệ thống phức tạp;
do đó có sự phản kháng đối với kỹ thuật.
Chỉ cần chạy nó và chúng ta sẽ thấy.
Tuy nhiên, tất cả chúng đều chứa đựng những vấn đề tuyến tính đơn giản
mà nếu được giải quyết sẽ là lối tắt để hiểu liệu chúng có hợp lý để xây dựng hay không.
Một chi phí rất nhỏ có thể giúp bạn tiết kiệm được nhiều tháng làm việc.

Những vấn đề tuyến tính đó thường là một trong ba vấn đề:
Time: Nó sẽ chạy trong 10 mili giây hay 10 ngày? Đây là lĩnh vực phức tạp về thuật toán, tốc độ ánh sáng và độ trễ.
Space: Cần bao nhiêu bộ nhớ hoặc đĩa? Đây là vùng đất của mã hóa, nén và cấu trúc dữ liệu.
Money: Và cuối cùng, tôi có đủ khả năng chi trả không? Chào mừng bạn đến với đầm lầy tối ưu hóa, lạm dụng đám mây và tại sao cuối cùng tôi lại phải sống dưới một cây cầu.
```
***Và tất nhiên, cả ba đều có liên quan. Bạn thường có thể đánh đổi thời gian và không gian cho nhau, và tiền thường có thể mua được cả hai thứ đó.***
# Type 21:
***Sau những nỗ lực trong hàng ngàn năm lịch sử. Gần như chúng ta không thể hiểu được ý nghĩa của việc trở thành một con người***
# Type 22:
```
Giao tiếp là thứ kỳ lạ cho phép các nhóm xuất sắc làm việc cùng nhau một cách hiệu quả,
các cặp vợ chồng sống sót qua những thời điểm tồi tệ nhất và những người khác
không hoàn toàn phát điên khi thế giới quay lưng lại với họ
```
# Type 23:
```
Trong khi các phương pháp, thước đo và công cụ cung cấp một cấu trúc cần thiết
thì bản chất thực sự của khả năng lãnh đạo thường nằm ở nghệ thuật hướng dẫn
và truyền cảm hứng cho một nhóm.
```
# Type 24:
```
Đừng đánh giá thấp việc ghi chép. Tôi tự làm nó. Ngay cả khi chỉ nói chuyện với ai đó
Khi ghi chép, bạn không chỉ đảm bảo rằng mình không bỏ sót điều gì mà còn đảm bảo rằng bạn hiểu mọi thứ
Tôi là một người ham mê ghi chép. Tôi thích cách tôi không bao giờ quên hoặc bỏ qua bất cứ điều gì vì ghi chú
```
# Type 25:
```
Điều quan trọng là phải triển khai dự án của bạn ngay lập tức.
Bạn không muốn xây dựng một ứng dụng hoàn chỉnh cục bộ và sau đó gặp khó khăn trong việc triển khai.
Việc xác định lỗi sẽ khó khăn nếu điều đó xảy ra, theo kinh nghiệm của bản thân tôi.

Rất dễ bị phân tâm. Tập trung vào việc hoàn thành bước lặp đầu tiên của dự án.
Bạn luôn có thể thêm nhiều thứ hơn sau này. Sự hoàn hảo là kẻ thù của sự tiến bộ.
```
# Type 26:
```
Khi xảy ra lỗi hệ thống, điều quan trọng là phải giữ bình tĩnh.
Sự hoảng loạn có thể dẫn đến những quyết định vội vàng và có thể khiến vấn đề trở nên trầm trọng hơn.
Hãy hít một hơi thật sâu và đánh giá tình hình.
Thu thập càng nhiều thông tin càng tốt để hiểu phạm vi và tác động của thất bại.
```
# Type 27:
***- Life is Short, Use Dev Tools -***
![BeMySkill](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_lossy/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fa5e5b9d5-3426-42ab-b690-2413ab249270_1280x1565.gif)
# Type 28:
***A Crash Course on REST APIs***
![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fbd70ae0a-7b12-4bf7-a15d-ed5a3f4a9117_1600x1272.png)
# Type 29:
***API Security Best Practices***
![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F66e9dc1a-3ca4-40a6-9578-ee59e9ae0ef8_3000x3900.png)
# Type 30:
![Jordan Cutler](https://substackcdn.com/image/fetch/w_176,h_176,c_fill,f_webp,q_auto:good,fl_progressive:steep,g_auto/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F4fe86d99-af64-4285-b982-9466a4c58d63_1311x1312.jpeg)
***- Jordan Cutler -***
*** 
After receiving the message, I realized a powerful formula:
Hard work + Good mentorship = Multiplicative growth
***
***
Mặc dù tôi không phải là người nhập cư thế hệ đầu tiên nhưng tôi là người đầu tiên trong gia đình tốt nghiệp đại học. 
Thật không dễ dàng để tìm ra bối cảnh công nghệ trong công việc đầu tiên của tôi, 
đặc biệt là khi tôi nghiện trò chơi điện tử cho đến năm 18 tuổi và được bao quanh bởi một nền văn hóa cực kỳ khác biệt — đó là phiên bản “bình thường” của tôi.
***
# Type 31:
