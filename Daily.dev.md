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
