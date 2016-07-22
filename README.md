# Lời tựa 


Xin chào, mình là Nguyễn Xuân Khánh, một người đang học và nghiên cứu về Machine Learning. Lĩnh vực mình chuyên sâu cho đến bây giờ là Natural Language Processing (gọi tắt là NLP), tức là làm cho máy tính có khả năng hiểu được ngôn ngữ của con người. Mình không phải là một chuyên gia, kinh nghiệm còn khá non nếu so với các giáo sư đầu ngành nhưng mình rất muốn đem bộ môn này về giới thiệu với mọi người, nhất là các bạn còn đang loay hoay tìm câu trả lời cho câu hỏi: **học Tin học sau này làm được gì?**

Cuốn sách này được viết nhằm đưa ra một trong rất nhiều câu trả lời cho câu hỏi trên. Nội dung chủ yếu xoay quanh các khái niệm và ứng dụng cơ bản về **machine learning**. Hiện nay, machine learning là một lĩnh vực thu hút rất nhiều sự chú ý. Trong giới học thuật, mỗi năm có hàng ngàn bài báo khoa học về đề tài này. Trong giới công nghiệp, từ các công ty lớn như Google, Facebook, Microsoft đến các công ty khởi nghiệp đều đầu tư vào lĩnh vực này để không bị tụt hậu. Vậy thực chất, machine learning là gì?

Để giới thiệu về Machine Learning, mình xin dựa vào mối quan hệ của nó với ba khái niệm sau:
1. Machine Learning và **trí tuệ nhân tạo** (Artificial Intelligence hay AI)
2. Machine Learning và **Big Data**.
3. Machine Learning và **dự đoán tương lai**.

Trí tuệ nhân tạo, AI, một cụm từ vừa gần gũi vừa xa lạ đối với chúng ta. Gần gũi bởi vì thế giới đang phát sốt với những công nghệ được dán nhãn AI. Xa lạ bởi vì một AI thực thụ vẫn còn nằm ngoài tầm với của chúng ta. Nói đến AI, hẳn mỗi người sẽ liên tưởng đến một hình ảnh khác nhau. Các bạn có để ý rằng vài thập niên gần đây có một sự thay đổi về diện mạo của AI trong các bộ phim quốc tế. Trước đây, các nhà sản xuất phim thường xuyên đưa hình ảnh robot hoặc terminator vào phim, nhằm gieo vào đầu người xem suy nghĩ rằng trí tuệ nhân tạo như một phương thức nhân bản con người bằng máy móc. Tuy nhiên, trong những bộ phim gần đây nhất về đề tài này, ví dụ như Transcendence do Johny Depp vào vai chính, ta không thấy hình ảnh của một con robot nào cả. Thay vào đó là một bộ não điện toán khổng lồ chỉ huy hàng vạn con Nanobot, được gọi là Singularity. Tất nhiên cả hai hình ảnh đều là hư cấu và giả tưởng, nhưng sự thay đổi như vậy cũng một phần nào phản ánh sự thay đổi ý niệm của con người về AI. AI bây giờ được xem như vô hình vô dạng, hay nói các khác có thể mang bất cứ hình dạng nào.

Trong giới hàm lâm, theo hiểu biết chung, AI là một ngành khoa học được sinh ra với mục đích làm cho máy tính có được trí thông minh. Mục tiêu này vẫn khá mơ hồ vì không phải ai cũng đồng ý với một định nghĩa thống nhất về trí thông minh. Thế nên các nhà khoa học phải định nghĩa một số mục tiêu cụ thể hơn, một trong số đó là việc làm cho máy tính lừa được Turing Test. Turing Test được tạo ra bởi Alan Turing (1912-1954), người được xem là cha đẻ của ngành khoa học máy tính hiện đại, nhằm phân biệt xem người đối diện có phải là người hay không (xem phim The Imitation Game về nhân vật này, nhưng đừng tin hết những gì trong phim).

AI thể hiện một mục tiêu của con người. Machine Learning là một phương tiện được kỳ vọng sẽ giúp con người đạt được mục tiêu đó. Và thực thế thì Machine Learning đã mang nhân loại đi một quãng đường rất xa trên quãng đường chinh phục AI. Nhưng vẫn còn một quãng đường xa hơn cần phải đi. Machine Learning và AI có mối quan hệ chặt chẽ với nhau nhưng không hẳn là trùng khớp vì một bên là mục tiêu (AI), một bên là phương tiện (Machine Learning). Chinh phục AI mặc dù vẫn là mục đích tối thượng của Machine Learning, nhưng hiện tại Machine Learning tập trung vào những mục tiêu ngắn hạn hơn như:

1. Làm cho máy tính có những khả năng nhận thức cơ bản của con người như nghe, nhìn, hiểu được ngôn ngữ, giải toán, lập trình, …

và

2. Hỗ trợ con người trong việc xử lý một khối lượng thông tin khổng lồ mà chúng ta phải đối mặt hàng ngày, hay còn gọi là Big Data.

Big Data thực chất không phải là một ngành khoa học chính thống. Đó là một cụm từ dân gian và được giới truyền thông tung hô để ám chỉ thời kì bùng nổ của dữ liệu hiện nay. Nó cũng không khác gì với những cụm từ như "cách mạng công nghiệp", "kỉ nguyên phần mềm". Big Data là một hệ quả tất yếu của việc mạng Internet ngày càng có nhiều kết nối. Với sự ra đời của các mạng xã hội nhưng Facebook, Instagram, Twitter, nhu cầu chia sẻ thông của con người tăng trưởng một cách chóng mặt. Youtube cũng có thể được xem là một mạng xã hội, nơi mọi người chia sẻ video và comment về nội dung của video. Để hiểu được quy mô của Big Data, hãy xem qua nhũng con số sau đây:

+ Khoảng 300 giờ video được upload trên youtube trong mỗi phút (theo https://www.youtube.com/yt/press/statistics.html)
+ Hơn 900 triệu người thật sự sử dụng Facebook mỗi ngày, 82.8% trong số đó ở ngoài Mỹ và Canada (theo http://newsroom.fb.com/company-info/)
+ Nhu cầu chia sẻ tăng đi đôi với việc nhu cầu tìm kiếm thông tin cũng tăng. Google phải xử lý 100 tỉ lượt tìm kiếm mỗi tháng, tức là 3,3 tỉ lượt mỗi ngày và 38.000 lượt mỗi giây (theo http://www.internetlivestats.com/google-search-statistics/).

Và những con số này đang tăng lên theo từng giây!

Bùng nổ thông tin không phải là lý do duy nhất dẫn đến sự ra đời của cụm từ Big Data. Nên nhớ rằng Big Data xuất hiện mới từ vài năm gần đây nhưng khối lượng dữ liệu tích tụ kể từ khi mạng Internet xuất hiện vào cuối thế kỉ trước cũng không phải là nhỏ. Thế nhưng, lúc ấy con người ngồi quanh một đống dữ liệu và không biết làm gì với chúng ngoài lưu trữ và sao chép. Cho đến một ngày, các nhà khoa học nhận ra rằng trong đống dữ liệu ấy thực ra chứa một khối lượng tri thức khổng lồ. Những tri thức ấy có thể giúp cho ta hiểu thêm về con người và xã hội. Từ danh sách bộ phim yêu thích của một cá nhân chúng ta có thể rút ra được sở thích của người đó và giới thiệu những bộ phim người ấy chưa từng xem, nhưng phù hợp với sở thích. Từ danh sách tìm kiếm của cộng đồng mạng chúng ta sẽ biết được vấn đề nóng hổi nhất đang được quan tâm và sẽ tập trung đăng tải nhiều tin tức hơn về vấn đề đó. Big Data chỉ thực sự bắt đầu từ khi chúng ta hiểu được gía trị của thông tin ẩn chứa trong dữ liệu, và có đủ tài nguyên cũng như công nghệ để có thể khai thác chúng trên quy mô khổng lồ. Và không có gì ngạc nhiên khi Machine Learning chính là thành phần mấu chốt của công nghệ đó. Ở đây ta có một quan hệ hỗ tương giữa machine Learning và Big Data: Machine Learning phát triển hơn nhờ sự gia tăng của khối lượng dữ liệu; ngược lại, thành công của Big Data phụ thuộc vào khả năng khai thác tri thức từ dữ liệu.

Ngược dòng lịch sử, machine Learning đã xuất hiện từ rất lâu trước khi mạng Internet ra đời. Một trong những thuật toán machine Learning đầu tiên là **thuật toán perceptron** được phát minh ra bởi *Frank Rosenblatt* vào năm 1957. Đây là một thuật toán kinh điển dùng để phân loại hai khái niệm. Một ví dụ đơn gỉan là phân loại thư rác (tam gíac) và thư bình thường (vuông). Chắc các bạn sẽ khó hình ra được làm thế nào để làm được điều đó. Đối với perceptron, điều này không khác gì với việc vẽ một đường thẳng trên mặt phẳng để phân chia hai tập điểm:

![](http://khanhxnguyen.com/wp-content/uploads/2015/08/Classification1.png)

Sơ lược quy trình phân loại thư được mô tả sau. Trước hết, ta cần một thuật toán để chuyển email thành những điểm dữ liệu. Công đoạn này rất rất quan trọng vì nếu chúng ta chọn được biểu diễn phù hợp, công việc của Perceptron sẽ nhẹ nhàng hơn rất nhiều. Tiếp theo, Perceptron sẽ đọc tọa độ của từng điểm và sử dụng thông tin này để cập nhật tham số của đường thẳng cần tìm. Các bạn có thể xem demo của perceptron tại đây(điểm xanh lá cây là điểm perceptron đang xử lý):

[![IMAGE ALT TEXT](http://img.youtube.com/vi/vGwemZhPlsA/0.jpg)](https://www.youtube.com/watch?v=vGwemZhPlsA "Video Title")

Những điểm tam giác và vuông đại diện cho những email chúng ta đã biết nhãn trước. Chúng được dùng để "huấn luyện" (train) perceptron. Sau khi vẽ đường thẳng chia hai tập điểm, ta nhận thêm các điểm chưa được dán nhãn, đại diện cho các email cần được phân loại (điểm tròn). Ta dán nhãn của một điểm theo nhãn của các điểm cùng nửa mặt phẳng với điểm đó. Vì là một thuật toán khá đơn giản, có rất nhiều vấn đề có thể nảy sinh với perceptron, ví dụ như điểm cần phân loại nằm ngay trên đường thẳng phân chia. Hoặc tệ hơn là với một tập dữ liệu phức tạp hơn, đường thẳng phân chia không tồn tại:

![](http://khanhxnguyen.com/wp-content/uploads/2015/08/Clasification-hard.png)

Lúc này, ta cần các loại đường phân chia "không thẳng". Nhưng đó lại là một câu chuyện khác.

Perceptron là một thuật toán "học có giám sát" (supervised learning): ta đưa cho máy tính hàng loạt các ví dụ cùng câu trả lời mẫu với hy vọng máy tính sẽ tìm được những đặc điểm cần thiết để đưa ra dự đoán cho những ví dụ khác chưa có câu trả lời trong tương lai. Ngoài ra, cũng có những thuật toán Machine Learning "không cần giám sát" (unsupervised learning): máy tính cố gắng khai thác ra cấu trúc ẩn của một tập dữ liệu mà không cần câu trả lời mẫu. Một loại machine Learning khác được gọi là "học củng cố" (reinforcement learning). Trong dạng này, cũng không hề có câu trả lời mẫu, nhưng thay vì đó máy tính nhận được phản hồi cho mỗi hành động. Dựa vào phản hồi tích cực hay tiêu cực mà máy tính sẽ điều chỉnh hoạt động cho phù hợp. Sau đây là một ví dụ minh họa:

[![IMAGE ALT TEXT](http://img.youtube.com/vi/m4J2WLOvrHg/0.jpg)](https://www.youtube.com/watch?v=m4J2WLOvrHg)
 
Mục tiêu của chiếc xe là leo lên được đỉnh đồi và lấy được ngôi sao. Chiếc xe có hai chuyển động tới và lui. Bằng cách thử các chuyển động và nhận được phản hồi là độ cao đạt được và thời gian để lấy được ngôi sao, chiếc xe dần trở nên thuần thục hơn trong việc leo đồi lấy sao.

Machine learning có mối quan hệ rất mật thiết đối với **thống kê** (statistics). Machine learning sử dụng các mô hình thống kê để "ghi nhớ" lại sự phân bố của dữ liệu. Tuy nhiên, không đơn thuần là thống kê dữ liệu, Machine Learning phải có **khả năng tổng quát hóa** những gì đã được nhìn thấy và đưa ra dự đoán cho những trường hợp chưa được nhìn thấy. Bạn có thể hình dung một mô hình machine learning không có khả năng tổng quát như một đứa trẻ học vẹt: chỉ trả lời được những câu trả lời mà nó đã học thuộc lòng đáp án. Khả năng tổng quát là một khả năng tự nhiên và kì diệu của con người: bạn không thể nhìn thấy tất cả các khuôn mặt người trên thế giới nhưng bạn có thể nhận biết được một thứ có phải là khuôn mặt người hay không với xác suất đúng gần như tuyệt đối. Đỉnh cao của machine learning sẽ là mô phỏng được khả năng tổng quát hóa và suy luận này của con người.

Như ta đã thấy, nói đến machine learning là nói đến "dự đoán": từ việc dự đoán nhãn phân loại đến dự đoán hành động cần thực hiện trong bước tiếp theo. Vậy machine learning có thể dự đoán tương lai hay không? Có thể có hoặc có thể không: machine learning có thể dự đoán được tương lai, nhưng chỉ khi tương lai có mối liên hệ mật thiết với hiện tại.

Để kết thúc, mình muốn cùng các bạn xem xét một ví dụ đơn giản sau. Giả sử bạn được đưa cho một đồng xu, rồi được yêu cầu tung đồng xu một số lần. Vấn đề đặt ra là: dựa vào những lần tung đồng xu đó, bạn hãy tiên đoán ra kết quả lần tung tiếp theo. Chỉ cần dựa vào tỉ lệ xấp/ngửa của những lần tung trước đó, bạn có thể đưa ra một dự đoán khá tốt. Nhưng nếu mỗi lần tung, người ta đưa cho bạn một đồng xu khác nhau thì mọi chuyện sẽ hoàn toàn khác. Các đồng xu khác nhau có xác suất xấp ngửa khác nhau. Lúc này việc dự đoán gần như không thể vì xác suất xấp ngửa của lần tung sau không hề liên quan gì đến lần tung trước. Điều tương tự cũng xảy ra với việc dự đoán tương lai bằng Machine Learning, nếu ta xem như mỗi ngày có một "đồng xu" được tung ra để xem một sự kiện có diễn ra hay không. Nếu "đồng xu" của ngày mai được chọn một cách tùy ý không theo phân bố nào cả thì machine learning sẽ thất bại. Rất may là trong nhiều trường hợp điều đó không hoàn toàn đúng, thế giới hoạt động theo những quy luật nhất định và machine learning có thể nhận ra những quy luật đó. Nhưng nói cho cùng, machine learning hoàn toàn không phải là một bà phủ thủy với quả cầu tiên tri mà cũng giống như chúng ta: phán đoán bằng cách tổng quát hóa những kinh nghiệm, những gì đã được học từ dữ liệu.