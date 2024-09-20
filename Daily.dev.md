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
***
Microsoft Bob chính là một thảm họa không thể giải quyết được. 
Nhưng điều buồn cười về những thất bại là chúng thường dẫn đến những thành công sau này. Hãy lấy nó từ một người đã sống và hít thở dự án Bob:

Có bao nhiêu người biết rằng nhà phát triển chính của Bob 2.0 cũng là người đồng sáng lập Valve và là người đứng đầu phát triển Half-Life, 
trò chơi đã trở thành một hiện tượng trong ngành, 
giành được hơn 50 giải thưởng Trò chơi của năm và bán được hơn 10 triệu bản. ?
***
# Type 32:
  ***Bắt buộc phải đọc tối nay***
  ```https://muratbuffalo.blogspot.com/2024/07/advice-to-young.html?ref=dailydev```
# Type 33:
***Hình thành một thói quen thích hợp có thể giúp bạn đạt được mục tiêu của mình.Trong cuốn sách đầy ảnh hưởng của mình Thói quen nguyên tử, James Clear đã vạch ra một cách hùng hồn lý do tại sao:***
```
những hành động nhỏ, nhất quán lại có tác động mạnh mẽ hơn những nỗ lực hoành tráng chỉ diễn ra một lần.
```
# Type 34:
```
Vấn đề nhờ mọi người giúp đỡ đưa chúng ta đến chủ đề về kỹ năng con người, hay còn gọi là "kỹ năng mềm".
Tôi không hiểu những kỹ năng này có gì mềm, đây là những kỹ năng khó thành thạo nhất và quan trọng nhất để thành công.
Nhưng một lần nữa, hầu hết người trẻ không nhận ra tầm quan trọng của những điều này.
Heck, tôi vẫn còn sai lầm về những điều này.
```
# Type 35:
```
Các kỹ sư dày dạn kinh nghiệm gọi đây là Hội chứng Not Invented Here (NIH).
Và đó là một cạm bẫy dẫn đến việc sao chép công việc của người khác trong khi lại gánh thêm gánh nặng bảo trì mới.
Vì vậy, khi bạn thấy mình đang ở thời điểm mà bạn có thể chọn một thư viện hoặc công cụ có sẵn
nhưng bạn nghĩ rằng mình có thể làm điều đó tốt hơn, hãy tự hỏi bản thân xem bạn đam mê việc
duy trì mã đó như thế nào trong vài năm tới .
```
# Type 36:
***Some of the common problem-solving patterns are:***
![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_webp,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ff87e25d5-c74a-4b7a-b1d4-da91b6129132_2568x2280.png)
# Type 37:
```
Làm việc 8 giờ thậm chí còn hơi tùy tiện. Đối với những công việc giải quyết vấn đề sáng tạo như lập trình, tôi đoán con số lý tưởng là gần bằng 6
Cuối cùng, tôi khuyên bạn không nên tập trung vào tốc độ mà hãy tập trung vào tính hiệu quả.
Có thể mã hóa thuật toán nhanh là một chuyện, còn có thể cung cấp giải pháp chất lượng sản xuất một cách nhanh chóng là một chuyện.
```
# Type 38:
***- Dr Milan Milanović -***
```
How to become an expert in anything?
```
# Type 39:
***How to Create Software Architecture Diagrams Using the C4 Model***
```
https://www.structurizr.com
```
# Type 40:
```
Một phương pháp bổ sung có thể được sử dụng với Lặp lại ngắt quãng là phương pháp Thu hồi tích cực.
Nhớ lại tích cực là một chiến lược học tập liên quan đến việc tìm lại thông tin từ trí nhớ một cách có ý thức
thay vì chỉ xem lại hoặc đọc lại tài liệu.
Nó bắt đầu bằng việc tiếp xúc với tài liệu, tiếp theo là xem xét và sau đó là bước quan trọng - tích cực nhớ lại
thông tin mà không cần tham khảo nguồn. Sau khi nhớ lại, bạn xác minh lại câu trả lời của mình,
xác định lỗi và lặp lại quy trình cho đến khi bạn có thể nhớ lại thông tin một cách chính xác.
Để nâng cao hiệu quả của chiến lược này, nó thường được kết hợp với sự lặp lại ngắt quãng,
bao gồm việc tăng khoảng thời gian giữa mỗi lần nhớ lại.
Mặc dù tốn nhiều công sức hơn so với ôn tập thụ động, phương pháp này cải thiện đáng kể khả năng duy trì trí nhớ
dài hạn do sự tham gia tích cực mà nó đòi hỏi từ người học.
```
***Đó là lý do vì sao các bài thi, bài kiểm tra tồn tại xuyên suốt quảng đời đi học khi còn niên thiếu***
# Type 41:
```
Sự không hài lòng trong công việc cao giữa các nhà phát triển.
Khoảng 80% nhà phát triển bày tỏ sự không hài lòng với công việc của họ,
với một phần ba cực kỳ ghét công việc của họ. Nhiều người cho biết họ cảm
thấy bị áp lực phải đáp ứng những thời hạn không thực tế, dẫn đến kiệt sức.
Mặc dù có mức lương tốt và các lựa chọn công việc linh hoạt,
nhưng sự căng thẳng về nợ kỹ thuật và hệ thống công nghệ phức
tạp góp phần đáng kể vào sự bất hạnh của họ.
```
# Type 42:
```
Trên thực tế, tôi sẽ khẳng định rằng sự khác biệt giữa một lập trình viên tồi và một lập trình viên giỏi
là liệu anh ta có coi mã hoặc cấu trúc dữ liệu của mình quan trọng hơn hay không.

Khi tôi đọc câu trích dẫn này, tôi thực sự có thể nhận ra vô số ví dụ trong quá khứ về điều này.
Tôi đã từng làm việc trong một dự án mà chúng tôi đã dành khá nhiều thời gian để tối ưu hóa các thuật toán phức tạp,
chỉ để nhận ra rằng bằng cách tái cấu trúc dữ liệu, chúng tôi có thể loại bỏ toàn bộ các loại vấn đề.
Chúng tôi đã thay thế hàm 500 dòng bằng hàm 50 dòng và cấu trúc dữ liệu được thiết kế tốt.
Mã mới không chỉ nhanh hơn mà còn dễ hiểu và dễ bảo trì hơn nhiều.
(Tất nhiên, sau đó vấn đề cũng chuyển “xuống ngăn xếp” đến nơi mà phần lớn công việc vất vả là tái cơ cấu dữ liệu hiện có.)
```
# Type 44:
```
Đau đớn + suy ngẫm = tiến bộ.
Thất bại chỉ hữu ích nếu bạn học được từ nó.
Hãy ghi chép lại những lần thất bại và lý do bạn thất bại, bất kể nó đau đớn đến mức nào.
Mọi người đều có ít nhất một điểm yếu lớn kìm hãm họ; nhật ký của bạn sẽ giúp bạn phát hiện ra điểm yếu đó.
Nhiều lần thất bại của tôi xuất phát từ việc quá thiếu kiên nhẫn (tôi vẫn đang cố gắng cải thiện điều này!).
```
# Type 45:
***What happens when you type a URL into your browser?***
![](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fbf03dcf1-bf10-49cd-9616-3cfbef582983_2048x1448.jpeg)
# Type 46:
***Why is System Design so important?***
```
Thiết kế hệ thống giúp chúng tôi xác định giải pháp đáp ứng yêu cầu kinh doanh.
Đó là một trong những quyết định sớm nhất mà chúng ta có thể đưa ra khi xây dựng một hệ thống.
Thông thường, điều cần thiết là phải suy nghĩ ở cấp độ cao hơn vì những quyết định này rất khó sửa chữa sau này.
Nó cũng giúp việc lập luận và quản lý các thay đổi kiến ​​trúc dễ dàng hơn khi hệ thống phát triển.
```
# Type 47:
```
Nguồn gốc của cuốn sách này nằm ở sự nhận ra của tôi sau nhiều năm lãnh đạo các nhóm kỹ thuật:
Phải tồn tại một khoảng cách đáng kể giữa một kỹ sư giỏi và một nhà lãnh đạo kỹ thuật giỏi.
Tôi đã chứng kiến ​​những kỹ thuật viên xuất sắc gặp khó khăn
khi họ đảm nhận vai trò lãnh đạo và tôi đã trực tiếp trải qua những thử thách này.

Mục tiêu của tôi là tạo ra một nguồn tài nguyên toàn diện bao gồm mọi thứ,
từ xây dựng đội ngũ hiệu quả đến giải quyết các thách thức lãnh đạo phức tạp.
Tôi muốn chia sẻ những hiểu biết sâu sắc về việc thúc đẩy sự đổi mới,
quản lý các tính cách đa dạng và thúc đẩy hiệu suất cao trong các nhóm kỹ thuật.

Nhưng hơn thế nữa, tôi muốn nhấn mạnh khía cạnh con người của khả năng lãnh đạo.
Công nghệ phát triển nhanh chóng, nhưng các nguyên tắc cơ bản của khả năng lãnh đạo tốt—sự đồng cảm,
giao tiếp và tầm nhìn— vẫn không đổi.
Cuốn sách này là nỗ lực của tôi nhằm kết hợp những nguyên tắc vượt thời gian này
với những yêu cầu đặc biệt của việc dẫn đầu trong ngành công nghệ.
```
# Type 48:
***Thử thách: Khởi động 100 dự án (Điên rồ nhỉ? 😆)***
```
Nếu giả sử, tôi sẽ khởi chạy 100 dự án và ứng dụng trong 10 năm tới và trung bình mỗi ứng dụng kiếm được 100 đô la mỗi tháng, tổng cộng là 10 nghìn đô la mỗi tháng.
```
# Type 49:
***React Server Components***
![](https://www.robinwieruch.de/static/69e949750b3e4903d52d440ec36b4817/a9a89/full-stack-react.webp)
```
Nhìn lại, thật thú vị khi thấy nhận thức của các nhà phát triển trong giai đoạn từ 2010 đến 2020 khác nhau như thế nào tùy theo thời điểm họ bắt đầu sự nghiệp.

Các nhà phát triển bắt đầu trước năm 2010 nhận thấy mình đang làm việc trong môi trường kết xuất phía máy chủ (SSR)
và nhìn chung có vẻ thoải mái hơn với sự chuyển đổi gần đây trở lại các kỹ thuật phía máy chủ.
Ngược lại, nhiều người khác đã dành gần một thập kỷ chỉ làm việc với API REST trong các ứng
dụng được kết xuất phía máy khách (CSR). Bây giờ họ không biết phải làm gì với thế giới React full-stack mới.

Nhưng quay lại chủ đề ở đây! Trong những năm gần đây,
TypeScript đã nổi lên như một tiêu chuẩn công nghiệp,
cung cấp cho các nhà phát triển giao diện người dùng một ngôn ngữ lập trình mạnh mẽ và được đánh máy hơn.
Một khi các nhà phát triển đã chấp nhận TypeScript, họ sẽ không thể quay đầu lại.
Thật thú vị khi một thay đổi tương đối nhỏ trong mã có thể có tác động đáng kể đến cả cấp độ cá nhân và toàn ngành.
Tuy nhiên, tác động của TypeScript lên REST liên quan đến rất nhiều giải pháp tạm thời.
Mặc dù OpenAPI (trước đây là Swagger) đã tồn tại trước đây, cho phép các nhóm ghi lại API REST,
nhưng mục đích chính của nó giờ đây là tạo ra các giao diện API được gõ.
Mặc dù có khả năng tạo các giao diện được đánh máy hoàn hảo trong kiến ​​trúc máy khách-máy chủ,
nhưng nhiều dự án, theo kinh nghiệm của tôi với tư cách là nhà phát triển web tự do trong nhiều năm,
đã không triển khai nó đúng cách ngay từ đầu.
```
# Type 50:
```
Những nhân viên cảm thấy được hỗ trợ trong quá trình phát triển của mình
có nhiều khả năng đóng góp hiệu quả cho tổ chức và thể hiện lòng trung thành lớn hơn,
giảm tỷ lệ luân chuyển và thúc đẩy văn hóa cải tiến liên tục.
```
# Type 51:
```
Vì vậy, lần tới khi bạn định tra Google thứ gì đó, trước tiên bạn nên tích cực cố gắng ghi nhớ cú pháp.
Mặc dù lúc đó nó có thể không hiệu quả, nhưng hành động cố gắng ghi nhớ có thể củng cố trí nhớ của bạn và có thể giúp bạn ghi nhớ vào lần sau.
Nếu cách đó không hiệu quả, hãy tạo một flashcard và tích cực luyện tập.
```
# Type 52:
```
Không có thời hạn thì không làm được việc gì.
Đừng ngại dồn hết tâm huyết vào công việc để hoàn thành đúng thời hạn.
Khi có ý chí, có con đường.
Những nỗ lực tuyệt vọng của bạn để biến điều gì đó thành hiện thực thường sẽ dẫn đến công việc tập trung và hiệu quả nhất (và đôi khi là sáng tạo) của bạn
```
# Type 53:
```
Con ong không tạo ra mật chỉ là loài gây hại.
Sản xuất một lượng nhỏ mỗi tuần là chìa khóa để giữ cho cơ bắp của bạn không bị teo.
Hãy coi nó như việc đầu tư vào con heo đất kỹ năng của bạn mỗi tuần.
Bằng cách này, bạn cũng tích lũy được công việc mà sau này bạn có thể dựa vào để sáng tác một thứ gì đó lớn hơn
```
# Type 54:
```
Học cách giao tiếp tốt.
Hãy dành nhiều thời gian hơn bạn nghĩ là đủ để cải thiện khả năng viết và trình bày của bạn.
Không một giây nào của công việc này bị lãng phí.
Thực sự, chỉ cần đọc qua phần Viết/Trình bày ở đây.
```
# Type 55:
***Nuôi dưỡng sự tập trung sâu sắc thông qua thực hành có chủ ý***
```
Tôi đã viết về những điều này trước đó.
Điều quan trọng là trau dồi công việc sâu sắc thông qua thực hành.
Bộ não con người được lập trình để tiết kiệm năng lượng và tự thực hiện dễ dàng,
vì vậy nó thích những công việc nông cạn (chẳng hạn như xem TV, duyệt web, trả lời email)
và cố gắng tránh những buổi suy nghĩ căng thẳng cần thiết cho nhiều công việc sáng tạo như viết,
suy nghĩ về một bằng chứng. và thiết kế một thuật toán.
Kết quả là chúng ta tích lũy rất nhiều thói quen học tập không tốt:
tưởng chừng như đang làm việc nhưng lại học chậm, bị phân tâm bởi những suy nghĩ khác và mất tập trung.
Nói cách khác, trừ khi chúng ta cân nhắc kỹ lưỡng,
rất dễ chuyển sang chế độ làm việc nông cạn hời hợt thay vì chế độ làm việc sâu hiệu quả.
```
# Type 56:
```
Điểm yếu thực sự nghiêm trọng 
Nếu bạn có một vấn đề dai dẳng, chưa được giải quyết (“Tôi luôn có vấn đề với việc quản lý thời gian”)
thì thực ra bạn có hai điểm yếu.
Một là bản thân vấn đề.
Điểm yếu còn lại là bạn đã không làm gì để giải quyết, và có lẽ đó là điểm yếu nghiêm trọng hơn.

Rất có thể một quy trình tuyển dụng hiệu quả sẽ phát hiện ra điều này, bất kể bạn nói gì về nó.
```
# Type 57:
```
Những ứng viên tự tin, có kinh nghiệm và tin tưởng vào bản thân sẽ không bị cám dỗ chuyển sang các công cụ AI.
Những người ít chắc chắn về bản thân mới là người làm vậy, hy vọng nhận được một chút trợ giúp thêm

Nếu bạn không tin vào chính mình thì khó có thể mong đợi người khác tin vào bạn.
```
# Type 58:
```
Lẽ ra tôi nên phát triển những thói quen lành mạnh của “người già” sớm hơn.
```
# Type 59:
```
Tìm hiểu các quy tắc của nền kinh tế mới.
```
# Type 60:
```
Chỉ cần bắt đầu thôi. Cách tốt nhất để biết liệu điều gì đó có hiệu quả hay không là thử nó.
Đừng lãng phí thời gian lập những kế hoạch lớn lao hay suy nghĩ: “Một ngày nào đó, tôi sẽ làm được điều này”.
Thay vào đó, chỉ cần bắt đầu và nhận phản hồi thực sự.
Đi qua vòng lặp hiểu, xác định và thực hiện càng nhanh càng tốt.
```
# Type 61:
```
npm install reactflow
```
# Type 62:
***What are you doing this week? Feel free to share!***
```
$HOME:
Vẫn đang tập cho con gái ngồi bô, nhưng giờ đây nó giống một hoạt động thụ động hơn là chủ động. Cô ấy đang làm rất tốt.
Thời gian dành cho gia đình với cả hai đứa trẻ
Tiếp tục làm việc với trò chơi Nhàn rỗi của tôi, bất chấp tất cả những điều ác ý mà AI đã nói về kho lưu trữ của tôi

$WORK:
Tôi hiện đang dẫn đầu một quá trình di chuyển lớn từ AWS -> GCP,
vì vậy tôi hoàn toàn không biết thông tin chi tiết và nghiên cứu về cách chúng tôi sao chép nhiều luồng
dành riêng cho AWS trong tài nguyên GCP và những khoảng trống còn tồn tại.
Nhiều cái mới nhưng mình thấy khá thú vị.
```
# Type 63:
***Xây dựng một tính năng, và tìm ra 1 solution chưa tối ưu, 
nhưng vì không có thời gian, kỹ sư này quyết định dùng tạm solution này và comment để đánh dấu là nó chưa tối ưu và sẽ sửa sau này***
***Và đây là kết quả của cái đoạn comment và của cái tính năng "chưa hoàn hảo" đó:***
```
Và điều buồn cười là, tôi tưởng đoạn mã này sẽ chỉ là tạm thời (và trên thực tế, nhận xét TODO: vẫn coi nó như một "biện pháp tạm thời");
nhưng cuối cùng nó đã trở thành vĩnh viễn.
Bạn có thể lập luận rằng hiện tại tôi có mã chưa tối ưu trong ứng dụng sản xuất của mình.
Và bạn có thể lập luận rằng nhận xét đó gây hiểu nhầm ("biện pháp tạm thời").
Và bạn sẽ đúng ở cả hai khía cạnh.
Tuy nhiên, tôi có một giải pháp hiệu quả, chính xác và chưa tối ưu mà người dùng của tôi có thể sử dụng ngay hôm nay.
Đối với tôi, việc giải quyết vấn đề cho khách hàng được ưu tiên hơn việc tạo ra giải pháp hoàn hảo.
```
Rất ấn tượng:
***Tuy nhiên, tôi có một giải pháp hiệu quả, chính xác và chưa tối ưu mà người dùng của tôi có thể sử dụng ngay hôm nay.
Đối với tôi, việc giải quyết vấn đề cho khách hàng được ưu tiên hơn việc tạo ra giải pháp hoàn hảo.***
Suy nghĩ của riêng tôi về điều này: ***Khi có thời gian, sẽ có 1 tính năng hoàn hảo cho khách hàng, nhưng đứng trước bờ vực của sự đánh đổi "không còn thời gian" và "tính năng này chưa hoàn hảo"
tôi sẽ chọn triển khai tính năng ấy để người dùng có thể sử dụng ngay hôm nay.
Sau tất cả những khúc mắc vừa rồi. Đây là lựa chọn của tôi***
# Type 64:
```
Tham vọng không phải là một kỹ năng - đó là ý chí.
Bạn có nó hoặc bạn không.
Để phát triển, bạn cần có động lực bên trong thúc đẩy bạn tiến về phía trước.
Đôi khi, đó là một lựa chọn có ý thức, và những lúc khác,
bạn không thể làm được - điều gì đó bên trong bạn không chịu đứng yên,
thúc đẩy bạn tiếp tục học hỏi và tiến về phía trước.
Tôi nhớ ngày xưa đã tìm hiểu sâu về Python và CI/CD, dạy nó ngay cả khi tôi vẫn đang tự học.
```
Suy nghĩ của riêng tôi về điều này: ***Đúng, tôi có một nguồn động lực và một lí do vô cùng lớn
Đến mức khi đối mặt với khoảnh khắc cận kề cái chết, nó vẫn thế.
***
