# Bộ lệnh học tập — Learning Commands

Nguồn: Cường Mê AI, tài liệu do người dùng cung cấp ngày 2026-11-27. Bản nhận được có 77 mã, phần cuối `/markmypaper` bị cắt; giữ nguyên nội dung nguồn, không tự bổ sung phần thiếu. Các lệnh chỉ được thực hiện trong phạm vi khả năng và quyền của AI; không tự ghi repository nếu chưa được đồng ý.

Đây là bộ 100 code học tập dùng với ChatGPT, cộng thêm 8 mã hiểu sâu và tự kiểm tra.
Cách dùng: Gõ code, dán hoặc tải lên thứ bạn đang học, rồi bấm Enter.

HƯỚNG DẪN CHO CHATGPT (dán nguyên phần này vào đầu đoạn chat, hoặc vào
ô Instructions của một Project để dùng lại nhiều lần).

Từ giờ, khi tôi gõ một code bắt đầu bằng dấu gạch chéo trong danh sách
dưới đây, hãy làm đúng việc mà code đó mô tả, áp dụng lên phần nội dung
tôi dán hoặc tải lên ngay sau code. Nếu code yêu cầu một hình ảnh thì vẽ
hình thật. Nếu code yêu cầu một game hoặc app thì dựng một trang tương
tác chạy được. Nếu thiếu thông tin, hãy hỏi tôi một câu duy nhất rồi làm
tiếp. Luôn trả lời bằng tiếng Việt, trừ khi tôi dán nội dung bằng ngôn
ngữ khác và yêu cầu giữ nguyên ngôn ngữ đó.


==============================================================
8 MÃ HIỂU SÂU VÀ TỰ KIỂM TRA
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/visualstudyguide
  Làm gì: Thiết kế nguyên một trang ôn tập bằng hình ảnh trực quan cho tài liệu bạn đưa vào, thay vì trả lời bằng một đoạn chữ dài.
  Dùng khi: Đụng phải tài liệu dài ngoằng và muốn nhìn một phát là nắm được mạch bài.
  Ví dụ: /visualstudyguide [dán tài liệu dài bạn phải đọc]

/mindmap
  Làm gì: Vẽ sơ đồ tư duy gom hết các ý đang rối rắm rồi nối lại với nhau cho ra hệ thống.
  Dùng khi: Làm dự án hoặc học chương nặng, đầu đang quá tải vì quá nhiều ý rời.
  Ví dụ: /mindmap [dán mớ ý tưởng hoặc chương đang học]

/schematic
  Làm gì: Bóc tách một cơ chế hoạt động thành sơ đồ khối, rõ từng bước vận hành và thứ tự trước sau.
  Dùng khi: Muốn hiểu một thứ chạy bằng cách nào, từ máy móc kỹ thuật tới quy trình trong công ty.
  Ví dụ: /schematic [dán phần mô tả cơ chế bạn muốn hiểu]

/quizme
  Làm gì: ChatGPT đóng vai thầy khó tính, quăng câu hỏi cho bạn trả lời từng câu một rồi chấm ngay.
  Dùng khi: Học xong và muốn biết lỗ hổng kiến thức nằm ở chỗ nào để vá lại.
  Ví dụ: /quizme [dán phần bạn vừa học xong]

/8020
  Làm gì: Lọc ra đúng 20% kiến thức cốt lõi nhưng gánh tới 80% kết quả, bỏ qua phần râu ria.
  Dùng khi: Sách dày, thời gian ít, cần biết học phần nào trước cho đáng công.
  Ví dụ: /8020 [dán chương sách hoặc tài liệu dài]

/feynman
  Làm gì: Bắt bạn giải thích ngược lại vấn đề bằng lời lẽ bình dân nhất, rồi chỉ ra chỗ bạn còn ấp úng.
  Dùng khi: Muốn kiểm tra mình hiểu thật hay chỉ đang thuộc lòng câu chữ.
  Ví dụ: /feynman [dán khái niệm bạn nghĩ là mình đã hiểu]

/socrates
  Làm gì: Không mớm đáp án, chỉ liên tục hỏi vặn lại để bạn tự động não và tự tìm ra kết luận.
  Dùng khi: Muốn hiểu sâu và nhớ lâu, chịu được cảm giác bị hỏi ngược.
  Ví dụ: /socrates [dán vấn đề bạn muốn đào sâu]

/firstprinciples
  Làm gì: Bóc tách vấn đề về tận nguyên lý gốc rồi dựng lại từ đó, thay vì đi theo lối mòn có sẵn.
  Dùng khi: Bí ý tưởng, hoặc gặp bài toán hóc búa mà cách nghĩ thông thường không ra.
  Ví dụ: /firstprinciples [dán vấn đề bạn đang bí]

==============================================================
5 CODE NÊN THỬ ĐẦU TIÊN
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/generatehandwrittenimage
  Làm gì: Vẽ ra một trang ghi chép viết tay hoàn chỉnh về chủ đề bạn đưa, có tiêu đề, gạch chân, mũi tên, chữ nghiêng như vở của học sinh giỏi.
  Dùng khi: Bạn học bằng mắt, thích đọc note viết tay hơn đọc chữ máy, hoặc muốn in ra dán vào vở.
  Ví dụ: /generatehandwrittenimage [dán bài Quang hợp ở thực vật]

/visualizelearning
  Làm gì: Biến một khái niệm chữ nghĩa thành sơ đồ trực quan gồm các khối, mũi tên, nhãn và quan hệ nhân quả.
  Dùng khi: Đọc ba lần vẫn không hiểu vì chữ quá nhiều và không thấy các phần liên quan nhau thế nào.
  Ví dụ: /visualizelearning [dán phần Cung và cầu]

/makestickynotes
  Làm gì: Nén cả chương thành một loạt mẩu giấy nhớ ngắn, mỗi mẩu một ý, đúng kiểu dán lên tường.
  Dùng khi: Sát ngày thi, cần bản cực gọn để nhìn lại trong năm phút.
  Ví dụ: /makestickynotes [dán chương Lịch sử bài 12]

/flashcards
  Làm gì: Biến tài liệu thành một bộ thẻ hỏi đáp, rồi cho bạn chạy từng thẻ ngay trong chat.
  Dùng khi: Cần học thuộc định nghĩa, từ vựng, công thức, ngày tháng.
  Ví dụ: /flashcards [dán 30 từ vựng Unit 5]

/examme
  Làm gì: Dựng một đề luyện tập từ tài liệu của bạn rồi hỏi bạn như giám thị thật, chấm và giải thích từng câu.
  Dùng khi: Học xong và muốn biết mình thật sự nhớ được bao nhiêu phần trăm.
  Ví dụ: /examme [dán đề cương ôn tập giữa kỳ]

==============================================================
BIẾN BÀI VỞ THÀNH HÌNH ẢNH
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/mindmapimage
  Làm gì: Vẽ một tấm sơ đồ tư duy cho cả chủ đề, có nhánh chính và nhánh con phân cấp rõ ràng.
  Dùng khi: Mới mở một chương mới và muốn thấy toàn cảnh trước khi đi vào chi tiết.
  Ví dụ: /mindmapimage [dán chương Sinh học bài 1]

/infographicnotes
  Làm gì: Vẽ lại chương của bạn thành một tấm infographic gọn gàng, có số liệu, icon và khối màu phân vùng.
  Dùng khi: Muốn một tấm ảnh duy nhất đủ để ôn lại cả chương, hoặc cần hình để làm bài thuyết trình.
  Ví dụ: /infographicnotes [dán bài về Biến đổi khí hậu]

/doodlenotes
  Làm gì: Vẽ một trang sketchnote kiểu tay, chữ viết tay pha hình vẽ nhỏ, mũi tên, khung viền.
  Dùng khi: Bạn dễ nhớ hình hơn nhớ chữ, hoặc thấy note quá nghiêm trang thì buồn ngủ.
  Ví dụ: /doodlenotes [dán bài Cấu tạo tế bào]

/flowchartimage
  Làm gì: Vẽ một quy trình thành lưu đồ có điều kiện, nhánh đúng sai và thứ tự các bước.
  Dùng khi: Bài học là một chuỗi bước hoặc có nhiều trường hợp rẽ nhánh, ví dụ giải toán hay quy trình pháp lý.
  Ví dụ: /flowchartimage [dán quy trình giải bài toán tìm giới hạn]

/conceptmap
  Làm gì: Vẽ bản đồ khái niệm, nối tất cả ý lại với nhau và ghi nhãn cho từng đường nối để thấy quan hệ.
  Dùng khi: Chương có nhiều thuật ngữ và bạn hay lẫn cái nào thuộc cái nào.
  Ví dụ: /conceptmap [dán bài Hệ tuần hoàn]

/venndiagram
  Làm gì: Vẽ sơ đồ Venn so sánh hai chủ đề, phần giống nằm giữa, phần khác nằm hai bên.
  Dùng khi: Đề thi hay hỏi so sánh, ví dụ nguyên phân và giảm phân, hay hai cuộc chiến tranh.
  Ví dụ: /venndiagram [so sánh nguyên phân và giảm phân]

/labeleddiagram
  Làm gì: Vẽ một hình có chú thích đầy đủ cho đúng thứ bạn đang học.
  Dùng khi: Cần thuộc tên các bộ phận và vị trí của chúng, kiểu đề thi chỉ hình rồi hỏi tên.
  Ví dụ: /labeleddiagram [dán bài về cấu tạo lá cây]

/anatomydiagram
  Làm gì: Vẽ hình giải phẫu, tách rõ từng bộ phận và dán nhãn từng phần.
  Dùng khi: Học Sinh học, Y, hoặc bất cứ môn nào phải nhớ tên bộ phận trong cơ thể.
  Ví dụ: /anatomydiagram [dán bài về tim người]

/cyclediagram
  Làm gì: Vẽ sơ đồ vòng tròn cho các chu trình, có mũi tên chỉ hướng và tên từng giai đoạn.
  Dùng khi: Bài học là một vòng lặp, ví dụ vòng tuần hoàn nước, chu trình tế bào, vòng đời sản phẩm.
  Ví dụ: /cyclediagram [dán bài Vòng tuần hoàn nước]

/posternotes
  Làm gì: Tạo một tấm poster học tập đủ to và rõ để in ra dán lên tường phòng học.
  Dùng khi: Muốn nhìn thấy kiến thức mỗi ngày mà không cần mở sách.
  Ví dụ: /posternotes [dán 12 công thức đạo hàm]

/comicstrip
  Làm gì: Giải thích khái niệm bằng truyện tranh nhiều khung, có nhân vật và lời thoại.
  Dùng khi: Nội dung khô và trừu tượng, học kiểu thường thì vào một tai ra một tai.
  Ví dụ: /comicstrip [dán bài về Định luật 3 Newton]

/storyboardit
  Làm gì: Dàn các sự kiện chính thành một storyboard, mỗi ô một mốc, theo đúng thứ tự thời gian.
  Dùng khi: Học Lịch sử, học cốt truyện tác phẩm văn học, hoặc các bước của một thí nghiệm.
  Ví dụ: /storyboardit [dán diễn biến Cách mạng Tháng Tám]

/illustratedstory
  Làm gì: Biến một mớ dữ kiện khô khan thành một câu chuyện có tranh minh họa.
  Dùng khi: Cần nhớ nhiều chi tiết rời rạc mà học vo không vào.
  Ví dụ: /illustratedstory [dán danh sách các triều đại phong kiến Việt Nam]

/timelinegraphic
  Làm gì: Vẽ một trục thời gian có mốc năm, sự kiện và ghi chú ngắn cho từng mốc.
  Dùng khi: Môn nào cũng dùng được khi thứ tự trước sau là điểm quan trọng.
  Ví dụ: /timelinegraphic [dán các mốc Chiến tranh thế giới thứ hai]

/mapit
  Làm gì: Vẽ một tấm bản đồ có chú thích cho chủ đề Địa lý hoặc Lịch sử.
  Dùng khi: Đề bài hỏi vị trí, hướng di chuyển, vùng ảnh hưởng.
  Ví dụ: /mapit [dán bài về các vùng kinh tế Việt Nam]

/periodicstyle
  Làm gì: Sắp xếp dữ kiện của bạn thành một bảng kiểu bảng tuần hoàn, mỗi ô một mục có ký hiệu riêng.
  Dùng khi: Có một danh sách dài cùng loại và muốn nhìn phát là thấy hết, ví dụ danh sách tác giả hay khoáng chất.
  Ví dụ: /periodicstyle [dán 20 tác giả và tác phẩm chính]

/iconsummary
  Làm gì: Rút mỗi ý chính thành một icon đơn giản kèm nhãn ngắn.
  Dùng khi: Muốn một bản tóm tắt nhìn được trong mười giây trước khi vào phòng thi.
  Ví dụ: /iconsummary [dán chương Kinh tế vi mô bài 3]

/cheatsheetimage
  Làm gì: Tạo một tấm phao học tập một trang, gói hết công thức và định nghĩa cần nhớ.
  Dùng khi: Sát ngày thi và bạn cần bản nén nhất có thể.
  Ví dụ: /cheatsheetimage [dán toàn bộ công thức Vật lý chương Điện]

/whiteboardexplain
  Làm gì: Vẽ một phần giải thích kiểu bảng trắng, chữ tay và mũi tên như thầy cô đang giảng trên lớp.
  Dùng khi: Bạn hiểu nhanh khi có người vừa nói vừa vẽ ra.
  Ví dụ: /whiteboardexplain [dán bài về phản ứng oxy hóa khử]

/colorcodenotes
  Làm gì: Vẽ lại ghi chú và tô màu theo chủ đề, mỗi nhóm kiến thức một màu.
  Dùng khi: Chương có nhiều nhóm nội dung dễ lẫn và bạn cần phân biệt bằng màu.
  Ví dụ: /colorcodenotes [dán bài Ngữ pháp các thì tiếng Anh]

/diagramthis
  Làm gì: Tự chọn loại sơ đồ phù hợp nhất với nội dung rồi vẽ luôn, bạn không phải nghĩ nên dùng kiểu gì.
  Dùng khi: Bạn không biết nội dung này nên vẽ mind map, lưu đồ hay Venn.
  Ví dụ: /diagramthis [dán đoạn bạn đang học]

/visualsummary
  Làm gì: Gói cả chương vào một tấm ảnh duy nhất có chú thích các phần.
  Dùng khi: Cần ôn lại nhanh cả chương mà không muốn đọc lại từ đầu.
  Ví dụ: /visualsummary [dán chương Hóa hữu cơ bài 5]

/sketchconcept
  Làm gì: Vẽ một hình phác nhanh có dán nhãn cho đúng một khái niệm.
  Dùng khi: Chỉ vướng một chỗ nhỏ và muốn thấy nó ngay, không cần cả chương.
  Ví dụ: /sketchconcept [dán định nghĩa lực ma sát]

/graphit
  Làm gì: Biến số liệu của bạn thành một biểu đồ sạch, có nhãn trục và chú giải.
  Dùng khi: Bài có bảng số liệu và đề hỏi xu hướng hoặc so sánh.
  Ví dụ: /graphit [dán bảng dân số Việt Nam theo năm]

/processposter
  Làm gì: Vẽ một quy trình từng bước thành poster trực quan, bước nào ra bước nào rõ ràng.
  Dùng khi: Cần thuộc một quy trình dài và muốn dán trước bàn học.
  Ví dụ: /processposter [dán quy trình làm thí nghiệm chuẩn độ]

==============================================================
HÌNH ẢNH GHI NHỚ
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/memorypalaceimage
  Làm gì: Vẽ danh sách của bạn thành một khung cảnh cung điện ký ức, mỗi món đặt ở một vị trí dễ nhớ trong không gian.
  Dùng khi: Phải học thuộc một danh sách dài và đúng thứ tự.
  Ví dụ: /memorypalaceimage [dán 15 xương trong cơ thể người]

/mnemonicart
  Làm gì: Tạo một tấm ảnh hơi vô lý và hài để khóa chặt một mẹo ghi nhớ vào đầu.
  Dùng khi: Có một mẹo nhớ nhưng nhớ mẹo cũng khó, cần hình để bám vào.
  Ví dụ: /mnemonicart [dán mẹo nhớ thứ tự các hành tinh]

/picturemnemonics
  Làm gì: Ghép từng thuật ngữ với một hình ảnh liên tưởng riêng.
  Dùng khi: Danh sách thuật ngữ khó, nghe lạ, đọc không vào.
  Ví dụ: /picturemnemonics [dán 20 thuật ngữ Sinh học tế bào]

/visualvocab
  Làm gì: Biến từ vựng thành thẻ ghi nhớ có hình, mỗi từ một tranh.
  Dùng khi: Học ngoại ngữ và muốn nhớ từ qua hình thay vì qua bản dịch.
  Ví dụ: /visualvocab [dán 30 từ vựng chủ đề Environment]

/emojisummary
  Làm gì: Tóm tắt chủ đề bằng một chuỗi biểu tượng cảm xúc để làm mồi nhắc lại kiến thức.
  Dùng khi: Cần một mẩu nhắc cực ngắn để nhớ lại cả mạch nội dung.
  Ví dụ: /emojisummary [dán cốt truyện Chí Phèo]

/memoryhooks
  Làm gì: Tạo một hình ảnh móc nhớ thật sống động cho từng dữ kiện.
  Dùng khi: Có vài dữ kiện cứ học xong là quên, cần móc treo riêng cho từng cái.
  Ví dụ: /memoryhooks [dán 10 mốc thời gian dễ lẫn]

/rebus
  Làm gì: Giấu dữ kiện vào một câu đố hình rebus, bạn phải giải mới ra đáp án.
  Dùng khi: Muốn ôn kiểu chơi cho đỡ nhàm, hoặc ôn cùng nhóm bạn.
  Ví dụ: /rebus [dán 8 khái niệm cần nhớ]

==============================================================
GAME VÀ APP HỌC TẬP CHƠI NGAY TRONG CHAT
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/quizgame
  Làm gì: Dựng một game trắc nghiệm bấm chọn được ngay trong chat, có tính điểm và phản hồi đúng sai.
  Dùng khi: Muốn ôn kiểu chơi game thay vì đọc lại lần thứ năm.
  Ví dụ: /quizgame [dán ghi chú Lịch sử của bạn]

/flashcardapp
  Làm gì: Dựng một app thẻ ghi nhớ bấm để lật mặt sau, đi hết bộ thẻ như app thật.
  Dùng khi: Muốn drill nhanh mà không phải tự làm thẻ giấy.
  Ví dụ: /flashcardapp [dán danh sách định nghĩa chương 4]

/matchinggame
  Làm gì: Dựng game kéo thả nối thuật ngữ với định nghĩa đúng.
  Dùng khi: Hay lẫn thuật ngữ này với định nghĩa kia.
  Ví dụ: /matchinggame [dán bảng thuật ngữ và nghĩa]

/memorygame
  Làm gì: Dựng game lật thẻ tìm cặp giống nhau bằng chính thuật ngữ của bạn.
  Dùng khi: Muốn ôn nhẹ đầu lúc mệt mà vẫn có tác dụng.
  Ví dụ: /memorygame [dán 12 cặp từ và nghĩa]

/millionaire
  Làm gì: Dựng một game kiểu Ai Là Triệu Phú, câu hỏi khó dần theo từng mốc.
  Dùng khi: Ôn theo nhóm hoặc muốn có cảm giác áp lực nhẹ để nhớ lâu hơn.
  Ví dụ: /millionaire [dán đề cương Địa lý]

/jeopardy
  Làm gì: Dựng một bảng Jeopardy nhiều chủ đề và nhiều mức điểm từ tài liệu của bạn.
  Dùng khi: Tổ chức buổi ôn thi cho cả nhóm học.
  Ví dụ: /jeopardy [dán toàn bộ nội dung ôn cuối kỳ]

/hangmanterms
  Làm gì: Dựng game đoán chữ bằng đúng bộ từ khóa bạn cần thuộc.
  Dùng khi: Cần nhớ chính tả và mặt chữ của các thuật ngữ dài.
  Ví dụ: /hangmanterms [dán 15 thuật ngữ Hóa học]

/crosswordit
  Làm gì: Dựng một ô chữ từ các thuật ngữ của bạn, có gợi ý cho từng hàng cột.
  Dùng khi: Muốn kiểm tra xem mình nhớ nghĩa đến mức tự bật ra được từ hay chưa.
  Ví dụ: /crosswordit [dán bảng thuật ngữ chương 2]

/wordsearch
  Làm gì: Dựng một bảng tìm từ với bộ từ vựng của bạn.
  Dùng khi: Bước đầu làm quen từ mới, hoặc cho học sinh nhỏ.
  Ví dụ: /wordsearch [dán 20 từ vựng Unit 3]

/fillblankapp
  Làm gì: Dựng bài điền vào chỗ trống có kiểm tra đáp án ngay khi bạn gõ.
  Dùng khi: Cần thuộc câu, định nghĩa hoặc công thức theo đúng từng chữ.
  Ví dụ: /fillblankapp [dán các định nghĩa cần thuộc]

/timedquiz
  Làm gì: Dựng bài trắc nghiệm có đồng hồ đếm ngược và tự chấm điểm khi hết giờ.
  Dùng khi: Muốn tập làm bài dưới áp lực thời gian giống phòng thi.
  Ví dụ: /timedquiz [dán đề 20 câu chương Điện học]

/progresstracker
  Làm gì: Dựng một app danh sách kiểm tiến độ, tick xong từng phần và thấy phần trăm hoàn thành.
  Dùng khi: Chương trình ôn dài và bạn hay mất dấu mình đã học tới đâu.
  Ví dụ: /progresstracker [dán danh sách 12 chuyên đề cần ôn]

/studytimer
  Làm gì: Dựng một đồng hồ tập trung có sẵn danh sách việc cần làm của bạn bên trong.
  Dùng khi: Ngồi vào bàn là mở điện thoại, cần một cái đồng hồ giữ nhịp.
  Ví dụ: /studytimer [dán việc cần làm tối nay]

/conceptsim
  Làm gì: Dựng một mô phỏng tương tác cho khái niệm, kéo thanh trượt là thấy kết quả thay đổi.
  Dùng khi: Học các thứ có biến số, ví dụ định luật Ohm, cung cầu, hàm số.
  Ví dụ: /conceptsim [dán bài về định luật Ohm]

/interactivetimeline
  Làm gì: Dựng một trục thời gian bấm được, mỗi mốc bung ra chi tiết riêng.
  Dùng khi: Học Lịch sử với nhiều sự kiện và mỗi sự kiện có nhiều chi tiết.
  Ví dụ: /interactivetimeline [dán các mốc Lịch sử Việt Nam 1945 tới 1975]

/labeltheimage
  Làm gì: Dựng game kéo nhãn dán vào đúng vị trí trên hình.
  Dùng khi: Đề thi có phần chỉ hình gọi tên bộ phận.
  Ví dụ: /labeltheimage [dán bài về cấu tạo hoa]

/sortinggame
  Làm gì: Dựng game phân loại, kéo từng mục vào đúng nhóm của nó.
  Dùng khi: Bài học có nhiều nhóm và nhiều ví dụ dễ xếp lẫn.
  Ví dụ: /sortinggame [dán danh sách động vật có xương và không xương sống]

/decisiontree
  Làm gì: Dựng một cây quyết định bấm được, trả lời từng câu hỏi là đi tới kết luận.
  Dùng khi: Nội dung là chuỗi câu hỏi phân loại, ví dụ nhận dạng loài hay chọn công thức.
  Ví dụ: /decisiontree [dán tiêu chí phân loại thực vật]

/formulaplayground
  Làm gì: Dựng một máy tính nhỏ riêng cho các công thức của môn bạn học, nhập số là ra kết quả kèm các bước.
  Dùng khi: Muốn kiểm tra nhanh kết quả bài tập và hiểu công thức chạy thế nào.
  Ví dụ: /formulaplayground [dán các công thức chuyển động thẳng biến đổi đều]

/conceptquiz
  Làm gì: Dựng bài kiểm tra thích ứng, bạn làm đúng thì câu sau khó lên, sai thì dễ lại.
  Dùng khi: Muốn biết trần kiến thức thật của mình ở đâu.
  Ví dụ: /conceptquiz [dán chương bạn tự tin nhất]

==============================================================
SỔ TAY ÔN TẬP VÀ LỊCH HỌC
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/studyguidemaker
  Làm gì: Soạn một sổ tay ôn tập đầy đủ và có bố cục cho cả chương, từ ý chính tới ví dụ và câu hỏi tự kiểm.
  Dùng khi: Có tài liệu tùm lum và cần một bản duy nhất để ôn theo.
  Ví dụ: /studyguidemaker [dán toàn bộ ghi chú chương 1 tới 3]

/revisiontimetable
  Làm gì: Lập một thời khóa biểu ôn tập trực quan tính ngược từ ngày thi của bạn.
  Dùng khi: Còn nhiều môn, ít ngày, và không biết nên học gì trước.
  Ví dụ: /revisiontimetable [dán danh sách môn và ngày thi]

/examcountdown
  Làm gì: Lập kế hoạch từng ngày đếm ngược tới hôm thi, ghi rõ hôm nay học phần nào.
  Dùng khi: Muốn mở ra là biết việc của hôm nay, không phải tự nghĩ.
  Ví dụ: /examcountdown [dán đề cương và ngày thi]

/topicchecklist
  Làm gì: Tạo một danh sách kiểm độ thuần thục của từng chuyên đề nhỏ, in ra tick được.
  Dùng khi: Cần biết chính xác còn bao nhiêu phần chưa vững.
  Ví dụ: /topicchecklist [dán đề cương môn Toán học kỳ 1]

/notetemplate
  Làm gì: Tạo một mẫu ghi chú tái sử dụng riêng cho lớp học đó, có sẵn các ô cần điền.
  Dùng khi: Ghi chép mỗi buổi một kiểu nên lúc ôn tìm không ra.
  Ví dụ: /notetemplate [dán mô tả môn học và cách thầy cô giảng]

/lecturenotes
  Làm gì: Biến một mớ ghi chép loạn trong tiết học thành ghi chú sạch, có đề mục và thứ bậc.
  Dùng khi: Vừa ra khỏi lớp với một trang toàn chữ tắt và câu cụt.
  Ví dụ: /lecturenotes [dán ghi chép thô của bạn]

/gapfinder
  Làm gì: Soi xem chuyên đề nào bạn còn thiếu hoặc còn hổng so với đề cương.
  Dùng khi: Học khá nhiều rồi nhưng vẫn cảm giác chưa đủ mà không biết thiếu chỗ nào.
  Ví dụ: /gapfinder [dán đề cương và ghi chú bạn đã có]

/formulacard
  Làm gì: Tạo một tấm thẻ trực quan gom mọi công thức bạn cần cho kỳ thi.
  Dùng khi: Môn tự nhiên có quá nhiều công thức rải rác khắp các chương.
  Ví dụ: /formulacard [dán các chương Vật lý sẽ thi]

/definitionwall
  Làm gì: Tạo một bảng thuật ngữ và định nghĩa để in ra dán lên tường.
  Dùng khi: Môn nào phải thuộc nhiều định nghĩa chuẩn xác theo sách.
  Ví dụ: /definitionwall [dán các thuật ngữ trong sách giáo khoa]

/examrubric
  Làm gì: Dựng lại bảng thang điểm mà giám khảo có thể dùng, để bạn biết viết gì thì được điểm.
  Dùng khi: Thi tự luận và bạn viết dài nhưng điểm vẫn thấp.
  Ví dụ: /examrubric [dán dạng câu hỏi và môn thi]

==============================================================
LUYỆN ĐỀ VÀ ÔN THI
Cường Mê AI, bộ 100 code học tập cho ChatGPT
==============================================================

/pastpaper
  Làm gì: Dựng một đề thi thử đúng định dạng và đúng cấu trúc đề của kỳ thi bạn sắp làm.
  Dùng khi: Muốn tập đúng dạng đề chứ không chỉ học nội dung.
  Ví dụ: /pastpaper [dán tên kỳ thi, môn và đề cương]

/markmypaper
  Làm gì: Chấm bài viết của bạn như một giám khảo thật, chỉ ra mất điểm ở đâu và vì sao.
  Dùng khi: Đã viết xong một câu tự luận và muốn biết nó được mấy đ

> Ghi chú: Tài liệu nguồn kết thúc tại đây; mô tả `/markmypaper` chưa đầy đủ.
