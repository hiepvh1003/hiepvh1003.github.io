---
layout: post
title:  "PMI ACP - Chapter 1 - Agile Principles and Mindset"
author: hiepvh
categories: [ PMI ACP ]
tags: [ pmi-acp, pm ]
image: assets/images/agilemindset.png
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: true
hidden: false
# rating: 4.5
---

<!-- Title Block -->
<div id="titleBlock" style="text-align: center;">
  <h4 style="margin-bottom: 0px;"> CHAPTER 1 </h4>
  <hr style="width: 50%;">
  Agile Principles and Mindset - Tư duy và nguyên tắc Agile
</div>

{:#tblContent}
| Contents |
|-----|
| [ Domain I Summary]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#summary) |
| [ Tại sao sử dụng Agile? ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#whyAgile) |
| [  - Các dự án tri thức là khác nhau ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#knowledgeWork) |
| [  - Quy trình xác định so với thực nghiệm ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#definevsEmpirical) |
| [  - Con người, nhóm và tổ chức mang tính Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#personAgility) |
| [  - Tam giác Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#agileTriangle) |
| [  - Bốn giá trị cốt lõi ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#fourValues) |
| [  - Mười hai nguyên tắc ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#twelvePrinciple) |
| [ SCRUM ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#scrum) |
| [  - Các giá trị và Trụ cột Scrum ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#valueScrum) |
| [  - SPRINT ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#sprint) |
| [　&#9;・　Vai trò trong nhóm dự án Scrum ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#scrumRoles) |
| [　&#9;・　Các hoạt động Scrum (Sự kiện, lễ hội) ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#scrumActivities) |
| [　&#9;・　Scrum artifacts - Hiện vật Scrum ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#scrumArtifact) |
| [  EXTREME PROGRAMMING (XP) ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#xp) |
| [  - Giá trị cốt lõi của XP ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#xpCoreValue) |
| [  - Các vai trò trong nhóm XP]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#XPRoles) |
| [  - Các thực hành cốt lõi XP]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#corepractices) |
| [ LEAN PRODUCT ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#leanProduct) |
| [  - Những khái niệm cốt lõi của LEAN ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#coreConcepts) |
| [  - Bảy lãng phí trong LEAN ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#7wastes) |
| [ KANBAN ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#kanban) |
| [  - Năm nguyên tắc của Kanban ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#fivePrinciples) |
| [  - Hệ thống kéo của kanban ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#kanbanpullsys) |
| [  - Giới hạn WIP trong Kanban ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#limitWIP) |
| [ Phát triển hướng chức năng (Feature-Driven Development - FDD) ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#featuredriven) |
| [  Phương pháp phát triển hệ thống động (DSDM - Dynamic Systems Development Method)]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#dsdm) |
| [  Crystal ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#crystal) |
| [  Tổng quan quy trình Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#agileprocessoverview) |
| [  Agile Leadership ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#agileleadership) |
| [  - Quản lý và Lãnh đạo ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#managervsleader) |
| [  - Lãnh đạo phục vụ ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#servantLeader) |
| [  - Mười hai nguyên tắc lãnh đạo dự án Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#twelvePrinciples) |
| [  - Bài tập thực hành lãnh đạo Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#agileLeaderPractise) |
| [  　・ Bài tập thực hành lãnh đạo Agile ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#modelDesiredBehavior) |
| [  　・ Truyền đạt tầm nhìn dự án ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#visionProject) |
| [  　・ Cho phép người khác hành động ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#enableothersAct) |
| [  　・ Sẵn sàng thách thức hiện trạng ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#willingchallenge) |
| [  - Nhiệm vụ của Lãnh đạo ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#leadershiptask) |
| [  　・ Thực hành tính minh bạch thông qua hình ảnh hóa ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#visualizePracticeTransparency) |
| [  　・ Tạo môi trường an toàn cho thử nghiệm ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#createasafeenv) |
| [  　・ Thử nghiệm với các kỹ thuật và quy trình mới ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#newtechnprocess) |
| [  　・ Chia sẻ kiến thức thông qua cộng tác ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#shareknowledge) |
| [  　・ Khuyến khích khả năng lãnh đạo nổi bật thông qua một môi trường an toàn ]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#encourageEmergentLeader) |
| [ Chapter Review]({{ site.baseurl }}/pmiacp-chapter-1-agile-principles-mindset/#chappterReview) |

<br/>
{:#summary}
# Domain I Summary

Chương này chiếm 16% trong bài exam, và có khoảng 19 câu hỏi.

Domain này tập trung vào agile mindset, những giá trị và nguyên tắc căn bản của nó, phương pháp agile và lãnh đạo theo phong cách agile.

<div id="titleBlock" style="font-size: 12px;">
  <h5>Chủ đề chính</h5>

  <li>Agile frameworks and terminology (Định nghĩa và khuôn khổ agile)</li>

  <li>Agile Manifesto (Tuyên ngôn Agile)</li>
    <ul>> 4 giá trị</ul>
    <ul>> 12 nguyên tắc</ul>

  <li>Agile process overview (Tổng quan quy trình agile)</li>

  <li>Kanban</li>
    <ul>> 5 nguyên tắc</ul>
    <ul>> Pull system (Hệ thống chứa)</ul>
    <ul>> WIP limits (Giới hạn WIP)</ul>

  <li>Leadership practices and principles (Nguyên tắc và bài tập lãnh đạo)</li>
    <ul>> Quản lý vs Lãnh đạo</ul>
    <ul>> Lãnh đạo phục vụ (4 duties - 4 nhiệm vụ)</ul>

  <li>Lean (Tối giản)</li>
    <ul>> Khái niệm cốt lõi</ul>
    <ul>> 7 wastes (7 lãng phí)</ul>

  <li>Scrum</li>
    <ul>> Activities</ul>
    <ul>> Artifacts (Đối tượng)</ul>
    <ul>> Team roles (Vai trò team)</ul>

  <li>XP</li>
    <ul>> Core practices (Bài tập cốt lõi)</ul>
    <ul>> Core values (Giá trị cốt lõi)</ul>
    <ul>> Team roles (Vai trò team)</ul>

  <br/>
  <h5>Task - Nhiệm vụ</h5>
  <li>Lý giải nguyên tắc và giá trị của agile để tạo ra tư duy chia sẻ.</li>
  <li>Đảm bảo rằng có hiểu biết chung về Agile.</li>
  <li>Hỗ trợ thay đổi bằng cách giáo dục và tạo ảnh hưởng.</li>
  <li>Thực hành tính minh bạch để nâng cao lòng tin.</li>
  <li>Tạo môi trường an toàn cho thử nghiệm</li>
  <li>Thử nghiệm các kỹ thuật và quy trình mới.</li>
  <li>Chia sẻ kiến thức bằng cách cộng tác.</li>
  <li>Khuyến khích lãnh đạo khẩn cấp thông qua môi trường an toàn.</li>
  <li>Thực hành lãnh đạo phục vụ.</li>

</div>

Chương này tổng hợp tư duy và phương pháp Agile, phác thảo các phương pháp Agile và khám phá bản chất lãnh đạo Agile khác với quản lý truyền thống như thế nào.

{:#whyAgile}
# Tại sao sử dụng Agile?

Hãy bắt đầu bằng một câu hỏi đơn giản: Tại sao chúng ta cần một cách tiếp cận khác để chạy dự án thay vì một phương pháp được đề cập trong PMBOK®?

Câu trả lời đơn giản là ứng với mỗi dự án khác nhau cần một phương pháp tiếp cận khác nhau. Trong cuộc sống hằng ngày, chúng ta liên tục điều chỉnh cách tiếp cận của mình tùy thuộc vào tình huống, thường là cách nhỏ và tinh tế. Ví dụ: Chúng ta chọn thông tin để truyền đạt và cách trình bày thông tin đó dựa trên đối tượng giao tiếp của chúng ta. Chúng ta không tiếp cận mọi vấn đề mà chúng ta gặp phải theo cùng một cách, giống như robot; thay vào đó, chúng ta điều chỉnh phương pháp của mình để có hiệu quả nhất cho từng tình huống.

Khái niệm tương tự này áp dụng cho các dự án - và một số dự án, đặc biệt là các dự án công việc tri thức trong môi trường phức tạp, chuyển động nhanh, yêu cầu cách tiếp cận linh hoạt.

{:#knowledgeWork}
## Các dự án tri thức là khác nhau

Trước tiên, chúc ta hãy thảo luận một chút về lịch sử không được đề cập trong exam nhưng sẽ giúp ta hiểu bối cảnh. Ban đầu, con người lang thang trên trái đất với tư cách là người săn bắt hái lượm. Khi mọi người bắt đầu trồng trọt và chăn nuôi gia súc, nó đã thay đổi xã hội và công việc. Đây là cuộc Cách mạng Nông nghiệp. Do đó, mọi người ít lang thang hơn, và họ sống làm việc tại một nơi.

Sự chuyển đổi lớn tiếp theo đến từ sự phát triển của máy móc và nhà máy khi mọi người rời trang trại và làng mạc của họ để chuyển đến thành phố. Đây là cuộc Cách mạng Công nghiệp, cuối cùng dẫn đến sự phát triển của nhiều công cụ và khái niệm quản lý dự án cổ điển, bao gồm Biểu đồ Gantt, phân rã chức năng và lao động bản địa. Đổi lại, những phát triển này dẫn đến việc tạo ra các công cụ quản lý dự án tiên tiến hơn, chẳng hạn như Cấu trúc phân tích công việc (WBS - Work Breakdown Structure).

Giai đoạn mới nhất - mà chúng ta đang ở hiện nay - được gọi là Cách mạng Công nghệ thông tin. Cuộc cách mạng này tập trung vào thông tin và cộng tác hơn là sản xuất. Nó đặt giá trị vào quyền sở hữu kiến thức và khả năng sử dụng kiến thức đó để tạo ra hoặc cải tiến hàng hóa và dịch vụ.

Cuộc cách mạng Thông tin dựa vào những người lao động tri thức. Đây là những người có chuyên môn riêng biệt, những người truyền đạt kiến thức của họ và tham gia vào các nỗ lực phân tích và phát triển. Công nhân tri thức không chỉ tìm thấy trong ngành Công nghệ thông tin; họ cũng là những kỹ sư, bác sĩ, giáo viên, nhà khoa học, luật sư, nhà văn và nhiều người khác. Trên thực tế, lao động tri thức đã trở thành bộ phận lớn nhất của lực lượng lao động Bắc Mỹ.

Vậy điều gì làm cho các dự án công việc tri thức khác với dự án sản xuất? Để tìm hiểu chúng ta hãy so sánh các đặc điểm chính của công việc công nghiệp và tri thức:

|Đặc điểm của công việc sản xuất| Đặc điểm của công việc tri thức|
|-----|-----|
|Công việc có thể nhìn thấy được | Công việc là vô hình|
|Công việc ổn định | Công việc đang thay đổi |
|Nhấn mạnh vào việc vận hành mọi thứ |Nhấn mạnh vào việc thay đổi mọi thứ |
|Cấu trúc nhiều hơn, quyết định ít hơn |Cấu trúc ít hơn, quyết định nhiều hơn |
|Tập trung vào các câu trả lời đúng |Tập trung vào các câu hỏi đúng |
|Xác định nhiệm vụ |Hiểu nhiệm vụ |
|Ra lệnh và kiểm soát |Trao quyền tự chủ |
|Tiêu chuẩn nghiêm ngặt | Đổi mới liên tục |
|Tập trung vào số lượng | Tập trung vào chất lượng |
|Đo lường hiệu suát theo các tiêu chuẩn nghiêm ngặt |Không ngừng học hỏi và giảng dạy |
|Giảm thiểu chi phí của người lao động cho mỗi nhiệm vụ | Đối xử với người lao động như tài sản, không phải chi phí |

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập</h5>

  <p>Hãy xem lại các mục dưới đây và đánh dấu mục mô tả công việc của bạn. Khi hoàn thành, hãy nhìn lại chủ yếu các đánh dấu nằm ở Công việc tri thức hay Công việc sản xuất</p>
</div>

|Công việc sản xuất| Công việc tri thức|
|-----|-----|
|☐　Công việc có thể nhìn thấy được |☐　 Công việc là vô hình|
|☐　Công việc ổn định |☐　 Công việc đang thay đổi |
|☐　Nhấn mạnh vào việc vận hành mọi thứ |☐　Nhấn mạnh vào việc thay đổi mọi thứ |
|☐　Cấu trúc nhiều hơn, quyết định ít hơn |☐　Cấu trúc ít hơn, quyết định nhiều hơn |
|☐　Tập trung vào các câu trả lời đúng |☐　Tập trung vào các câu hỏi đúng |
|☐　Xác định nhiệm vụ |☐　Hiểu nhiệm vụ |
|☐　Ra lệnh và kiểm soát |☐　Trao quyền tự chủ |
|☐　Tiêu chuẩn nghiêm ngặt |☐　 Đổi mới liên tục |
|☐　Tập trung vào số lượng | ☐　Tập trung vào chất lượng |
|☐　Đo lường hiệu suát theo các tiêu chuẩn nghiêm ngặt |☐　Không ngừng học hỏi và giảng dạy |
|☐　Giảm thiểu chi phí của người lao động cho mỗi nhiệm vụ | ☐　Đối xử với người lao động như tài sản, không phải chi phí |

<hr style="width: 50%; text-align: center;">

Khi các dự án công việc tri thức trở nên phổ biến hơn, mọi người nhận thấy rằng sự giao tiếp và công tác liên quan đến dự án này khiến công việc trở nên không chắc chắn và ít xác định hơn công việc sản xuất. Khi mọi người cố gắng áp dụng các kỹ thuật làm việc sản xuất vào các dự án công việc tri thức, sự thất vọng - và thất bại của dự án - tăng lên. Các phương pháp Agile đã được phát triển đễ giải quyết vấn đề này. Những người tiên phong trong lĩnh vực Agile đã thu thập các kỹ thuật hiệu quả nhất cho công việc tri thức và điều chỉnh chúng để sử dụng trong dự án, thử nghiệm để xem điều gì hiệu quả nhất. Sáng kiến mới này bắt đầu trong lĩnh vực phát triển phần mềm, nhưng bây giờ được sử dụng trong tất cả các loại dự án công việc tri thức.

Sự phát triển các phương pháp Agile này đã diễn ra trong nhiều năm và được thực hiện bởi những người khác nhau. Do đó, Agile có nhiều phương pháp sử dụng các thuật ngữ khác nhau.  Ví dụ: Scrum gọi efforts phát triển timeboxed là "sprint" trong khi XP gọi là "iteractions". Chương này sẽ thiết lập một framework để hiểu tư duy Agile và giải thích một số khái niệm cơ bản để làm tốt bài exam PMI-ACP.

{:#definevsEmpirical}
## Quy trình xác định so với thực nghiệm

Một cách khác để xem xét sự khác biệt giữa công việc tri thức và công việc sản xuất là xem xét các loại quy trình khác nhau mà chúng sử dụng. Công việc sản xuất thường dùng quy trình xác định, trong khi Tri thức dựa trên quy trình thực nghiệm.

Trong một quy trình xác định, như tên của nó, chúng ta có thể xác định trước các bước cấu thành của nó. Nếu chúng ta biết cách thắt dây giày tối ưu, chúng ta có thể làm theo quy trình tương tự mỗi lần. Đây thường là cách hiệu quả nhất để tiến hành một dự án được hiểu rõ trong một môi trường không thay đổi, chẳng hạn như các dự án xây dựng thường sử dụng các vật liệu và các phương pháp xây dựng được hiểu rõ. Trên thực tế, hầu hết các dự án sản xuất có thể được lập kế hoạch và quản lý bằng cách sử dụng một các tiếp cận xác định.

Các quy trình khác không được xác định rõ ràng. Khi đối mặt với một quy trình mới hoặc không chắc chắn, chẳng hạn như xây dựng một ngôi nhà dưới nước lần đầu tiên hoặc sử dụng ống nano-carbon thay vì thép, sẽ có nhiều điều chưa biết và không chắc chắn liên quan đến các rủi ro và giải pháp cần thiết cho môi trường hoặc vật liệu mới.

Khi đối mặt với sự không chắc chắn như vậy, cần phải có một quá trình thử nghiệm và xác định những gì hoạt động, các vấn đề bề mặt và từng bước xây dựng dựa trên những thành công nhỏ. Quá trình kết quả sẽ lặp đi lặp lại và gia tăng, với các đánh giá và điều chỉnh thường xuyên. Kết quả là một quá trình thực nghiệm. Các tiếp cận này bắt buộc đới với các dự án mà giai đoạn thực hiện được đặc trưng bởi sự không chắc chắn và rủi ro - nói cách khác, các dự án sẽ được hưởng lợi trực tiếp từ cách tiếp cận Agile.


<div id="toolkitBox">
  <div id="toolkitIcon">K&S</div>
  <h2 id="toolkitContent">Tư duy Agile<br/><hr/></h2>
</div>

<br/>
Mặc dù có rất nhiều tools, thực hành và khái niệm chúng ta cần biết cho kỳ thi PMI-ACP, mục tiêu cơ bản của các câu hỏi kiểm tra không thực sự là để kiểm tra kiến thức cụ thể - thay vào đó, kỳ thi muốn xem liệu chúng ta có nắm được toàn diện ý nghĩa của Agile hay không. Agile không chỉ đơn giản là vấn đề sử dụng một bộ công cụ hoặc phương pháp nhất định hoặc tuân thủ theo một phương pháp cụ thể. Sự nhanh nhẹn (agile) thực sự liên quan đến việc áp dụng một tư duy mới - một cách suy nghĩ mới - dựa trên các giá trị và nguyên tắc Agile.

Tuyên bố quan trọng nhất về các giá trị và nguyên tắc này là Agile Manifesto (Tuyên bố Agile), chúng ta sẽ xem xét chi tiết trong phần tiếp theo của chương này. Nhưng trước tiến, hãy xem xét một số đặc điểm chung của Agile mindset. Chúng ta sẽ bắt đầu với "Tuyên bố về sự phụ thuộc lẫn nhau" (Declaration of Interdependence - DOI) được viết vào năm 2005 bởi những đồng sáng lập của Mạng lưới lãnh đạo dự án Agile hiện nay. Tài liệu này nêu ra sáu giới luật:

1. Chúng ta **tăng lợi tức đầu tư** (increase return on investment) bằng cách làm cho dòng giá trị liên tục trở thành trọng tâm của chúng ta.

2. Chúng ta **mang lại kết quả đáng tin cậy** (deliver reliable results) bằng cách thu hút khách hàng tương tác thường xuyên và chia sẻ quyền sở hữu.

3. Chúng ta **mong đợi sự không chắc chắn** (expect uncertainty) và quản lý nó thông qua các lần lặp, dự đoán và thích ứng.

4. Chúng ta **giải phóng sự sáng tạo và đổi mới** (unleash creativity and innovation) bằng cách nhận ra rằng các cá nhân là nguồn lực giá trị và tạo ra một môi trường nơi họ có thể tạo sự khác biệt.

5. Chúng ta **thúc đẩy hiệu suất** (boost performance) thông qua trách nhiệm giải trình của team đối với kết quả và chia sẻ trách nhiệm hiệu quả của team.

6. Chúng ta **cải thiện hiệu quả và độ tin tưởng** (improve effectiveness and reliability) thông qua các chiến lược cụ thể theo tình huống, quy trình và thực hành.

Vì DOI hướng đến các leaders - nó tập trung vào khía cạnh quản lý của các dự án Agile - sáu nguyên tắc này có thể đóng vai trò như một dạng tóm tắt hàng đầu để giới thiệu cho chúng ta về tư duy Agile.

Hãy đọc lại sáu nguyên tắc này xem chúng ta có hiểu nó không. Chúng có ý nghĩa với chúng ta không? Nếu tư duy này có vẻ rất khác so với môi trường làm việc mà chúng ta quen thuộc, thì chúng ta sẽ cần phải học thật kỹ chương này. Đề thi yêu cầu phải nắm chắc "Agile mindset"; chúng không thể được trả lời đơn giản bằng cách ghi nhớ.

Tiếp theo, đây là một cách khác để tổng hợp các nguyên tắc cốt lõi của Agile:

- Welcoming change: welcome sự thay đổi
- Working in small value-added increments: làm việc với sự gia tăng giá trị nhỏ
- Learning through discovery: học hỏi thông qua khám phá
- Value-driven development: phát triển theo định hướng giá trị
- Failing fast with learning: thất bại sớm và học hỏi
- Continuous delivery: phân phối liên tục
- Continuous improvement: cải thiện liên tục

Danh sách này không phải chỉ la vấn đề của việc áp dụng các phương pháp này để đạt được kết quả. Chúng ta phải thực sự lấy agile mindset làm trọng tâm và sử dụng nó để định hướng cho cách tiếp cận của mình. Việc áp dụng các giá trị và nguyên tắc agile không chỉ thay đổi cách tiếp cận của chúng ta mà còn cả hiệu quả của các phương pháp. Đây là sự khác biệt giữa "being agile" (trở thành agile) với "doing agile" (làm agile).

![beingAgilevsDoingAgile]({{ site.baseurl }}/assets/images/beingAgilevsDoingAgile.png)

Hãy cùng phân tích sơ đồ này:

- Cách chính xác để áp dụng agile được hiển thị bên trái. Ở đây, chúng ta bắt đầu bằng cách nội tại hóa agile mindset (welcome change, small increments, etc.) và sau đó, chúng ta sử dụng các nguyên tắc để hướng dẫn lựa chọn và thực hiện các phương pháp agile. Chúng ta bắt đầu bằng việc hiểu rõ lý do tại sao chúng ta sử dụng các phương pháp này, từ đó, chúng ta hiểu cách sử dụng một cách hiệu quả.

- Mũi tên ở bên phải thể hiển một team quyết định áp dụng các phương pháp agile (chẳng hạn như các cuộc họp đứng hằng ngày và lặp lại) mà không cần dành thời gian để hiểu những phương pháp này được thiết kế để làm gì. Ở đây, chúng ta đi thẳng vào cách làm thế nào của agile mà không hiểu lý do tại sao. Đây là một vấn đề phổ biến trong việc áp dụng agile.

Dựa trên sơ đồ này, đôi khi mọi người sử dụng thuật ngữ "áp dụng từ trái sang phải" như một cách nói ngắn gọn của "dạy các giá trị agile trước tiên."

{:#personAgility}
## Con người, nhóm và tổ chức mang tính Agile

Trong một tổ chức, mọi người sẽ phát triển sự hiểu biết về tư duy agile theo các tỷ lệ khác nhau.

Đối với một số người, các giá trị linh hoạt sẽ dễ nắm bắt bằng trực giác - chúng dường như mô tả bằng niềm tin và kiểu hành vi quen thuộc.

Đối với một số người khác, những giá trị này sẽ phải được học hỏi một cách có ý thức và sau đó, tích cực thực hành trước khi chúng có thể được hiểu và chấp nhận. Bất kể sự hiểu biết này phát triển thế nào, càng có nhiều người trong một tổ chức chấp nhận và hành động theo các nguyên tắc nhanh nhẹn, thì các phương pháp thực hành agile sẽ có hiệu quả.

- Chỉ cần một thành viên của tổ chức áp dụng tư duy agile thì nó có thể giúp người đó trở nên hiệu quả hơn. Tuy nhiên, họ sẽ liên tục cảm thấy thất vọng khi những người khác trong tổ chức dường như không nhận ra điều gì là quan trọng hoặc tập trung vào các mục tiêu và chỉ số sai.

- Nếu một nhóm trong tổ chức áp dụng các nguyên tắc và thực hành agile, điều đó có thể giúp các thành viên trong team trở nên hiệu quả hơn trong việc thực hiện công việc dự án của họ. Tuy nhiên, họ sẽ cảm thấy bị ức chế hoặc hiểu lầm bởi các nhóm hoặc hệ thống khác trong tổ chức, chẳng hạn như văn phòng quản lý dự án (PMO) hoặc các bộ phận chức năng khác.

- Nếu toàn bộ tổ chức áp dụng lối suy nghĩ linh hoạt, thì mọi người sẽ làm việc cùng nhau để cải thiện agile và cung cấp giá trị. Bằng cách áp dụng các mục tiêu và giá trị chung, chẳng hạn như cải tiến liên tục và chào đón sự thay đổi, hiệu quả của mọi người sẽ được nâng cao.

Mặc dù tổ chức mang tính agile là mục tiêu lý tưởng, nhưng ngày nay hầu hết các tổ chức vẫn chưa đạt được mục tiêu đó. Vậy làm thế nào để chúng ta có thể giúp các tổ chức của mình đạt được điều đó? Cách các tổ chức thay đổi là thông qua ảnh hưởng của các cá nhân. Sơ đồ dưới đây mô tả các bước liên quan đến quá trình này như các lớp của vỏ hành tây.


![changeorganization]({{ site.baseurl }}/assets/images/changeorganization.png)

**Hãy cùng xem xét rõ hơn về từng lớp vỏ**

**THINK - SUY NGHĨ**

Đầu tiên, chúng ta cần phải suy nghĩ - điều này có nghĩa là học tập cá nhân và liên kết với các nguyên tắc của Agile. Mỗi một lần chúng ta hiểu cặn kẽ về tư duy Agile, chúng ta sẽ di chuyển dần lên tầng tiếp theo.

**DO - HÀNH ĐỘNG**

Hành động là thực hành agile. Ví dụ, nó có thể bao gồm đến việc hình dung các hạng mục công việc, sử dụng các bước lặp ngắn hoặc xây dựng các bước phản hồi và cải tiến. Một khi chúng ta hiểu và có thể tự thực hành các bước này, chúng ta có thể chuyển sang bước tiếp theo, nơi chúng ta bắt đầu tạo ảnh hưởng đến người khác.

**ENCOURAGE OTHERS - ẢNH HƯỞNG NGƯỜI KHÁC**

Bước cuối cùng nay liên quan đến việc ảnh hưởng tới người khác để BEING AGILE. Mặc dù điều này có vẻ khó đạt được theo cấp số nhân hơn so với hai bước đầu tiên, nhưng nó cũng đáng giá nhất khi hoàn thành. Đó là bởi vì việc thuyết phục người khác áp dụng tư duy agile và các phương pháp thực hành sẽ giúp tăng cường hiệu quả và học tập nhanh trong toàn bộ tổ chức. Ngoài ra, càng có nhiều người trong vòng tròn làm việc mà chúng ta có thể giáo dục thành công về giá trị của agile, chúng ta sẽ càng có nhiều đồng minh trong việc ủng hộ chính nghĩa. Kết quả cuối cùng của quá trình này có thể là một sự chuyển đổi hoàn toàn của tổ chức dựa trên các nguyên tắc Agile.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Cũng giống như mô hình "THINK - DO - ENCOURAGE OTHERS", chúng ta sẽ thấy được nhiều bước quy trình và danh sách đánh dấu trên phần tổng hợp đầu chương. Đừng tiếp cận tài liệu bằng cách nhồi nhét nó, như thể đang ôn thi đại học. Điều đó sẽ không hiệu quả vì bài kiểm tra PMI-ACP không kiểm tra thông tin - hầu hết sẽ là câu hỏi tình huống. Vì vậy, mục tiêu học tập của chúng ta, trước phải là phải tiếp thu được hoàn toàn tư duy agile và sau đó, nói chung là làm quen với các công cụ và thực hành agile. HÃY TẬP TRUNG vào bức tranh lớn:
      <li>Điều gì là quan trọng trong danh sách hoặc quy trình đối với agile?</li>
      <li>Làm thế nào để mỗi mục được liệt kê phù hợp với cách hành động agile?</li>
      <br/>
      Đây là những gì cần hiểu cho kỳ thi.
    </h7>
  </div>
</div>

<br/>

{:#agileTriangle}
## Tam giác Agile

Một điểm khác biệt chính nữa giữa tư duy Agile và quản lý dự án truyền thống là tam giác ràng buộc Agile hay tam giác "đảo ngược". Hình tam giác này, được hiển thị bên dưới, đã được giới thiệu trong ấn bản đầu tiên của Hướng dẫn sử dụng DSDM, xuất bản năm 1994.

![agiletriangle]({{ site.baseurl }}/assets/images/agiletriangle.png)

Sự đảo ngược của tam giác truyền thống này có nghĩa là các team Agile cho phép Scope (phạm vi) thay đổi trong các thông số cố định về Cost (chi phí) và Time (thời gian). Nói cách khác, chúng ta đặt mục tiêu mang lại giá trị cao nhất có thể vào ngày X trong phạm vi ngân sách Y. Mặc dù chúng ta sẽ bắt đầu với tầm nhìn cấp cao về sản phẩm cuối cùng, nhưng chúng ta có thể hoàn thành - điều này sẽ xuất hiện khi chúng ta đến gần mục tiêu.

Chúng ta có thể nghe thấy những lời chỉ trích rằng cách tiếp cận này không có ý nghĩa, vì nó sẽ không hiệu quả với các dự án công nghiệp hữu hình. Ví dụ: Nếu tôi đang trả tiền để sửa sang lại phòng tắm của mình, không phải phần lớn! Tuy nhiên, tu sửa phòng tắm phải là một quá trình xác định, có thể lặp lại với ít R&D hoặc không chắc chắn. Đó không phải là loại dự án đòi hỏi một cách tiếp cận Agile hoặc một tam giác ngược ràng buộc.

Mặt khác, các dự án công việc tri thức được đặc trưng bởi thử nghiệm và sự không chắc chắn - và sản phẩm cuối cùng sẽ có thể được tinh chế mãi mãi. Đây là lý do tại sao chúng ta cần xác định các ranh giới hoạt động có thể chấp nhận được, thường có dạng hạn chế về chi phí và thời gian.

Ví dụ: Giả sử chúng ta đang phát triển tài liệu đào tạo cho một khóa học về viết truyện ngắn. Đối với dự án như thế, chúng ta có thể tiếp tục bổ sung và chỉnh sửa tài liệu bài học và bài tập vô thời hạn. Thay vào đó, chúng ta cần đạt đến hiệu suất có thể chấp nhận được, và sau đó là quy định để dừng lại.


<div id="toolkitBox">
  <div id="toolkitIcon">K&S</div>
  <h2 id="toolkitContent">Tuyên ngôn Agile<br/><hr/></h2>
</div>

Tên của domain I - Agile Principles and Mindset không chỉ nêu bật tư duy Agile mà còn có các giá trị và nguyên tắc cơ bản. Đối với bài kiểm tra, chúng ta cần hiểu kỹ về tuyên bố quan trọng nhất về các giá trị và nguyên tắc Agile - một tài liệu có tên là Tuyên ngôn Agile (Agile Manifesto).


<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Bài kiểm tra PMI-ACP sẽ không hỏi về nguồn gốc của Agile Manifesto hoặc người tạo ra nó. Kỳ thi sẽ tập trung vào khả năng của chúng ta để áp dụng các giá trị và nguyên tắc được nêu trong tài liệu này trong các câu hỏi tình huống. Nó sẽ không hỏi:
      <li>Giá trị thứ tư là gì?</li>
      <li>Nguyên tắc thứ hai được diễn đạt như thế nào?</li>
    </h7>
  </div>
</div>

<br/>

{:#fourValues}
## Bốn giá trị cốt lõi

Tuyên ngôn Agile bao gồm một tuyên bố về 4 giá trị và 12 nguyên tắc cốt lõi.

<hr style="width: 50%; text-align: center;"/>
> **Individuals and interactions** over *processes and tools*

**Cá nhân và tương tác** hơn là *quy trình và công cụ*

<hr style="width: 80%; text-align: center;"/>

> **Working software** over *comprehensive documentation*

**Phần mềm hoạt động được** hơn là *tài liệu toàn diện*

<hr style="width: 80%; text-align: center;"/>

> **Customer collaboration** over *contract negotiation*

**Hợp tác với khách hàng** hơn là *thương thảo hợp đồng*

<hr style="width: 80%; text-align: center;"/>

> **Responding to change** over *following a plan*

**Đáp ứng sự thay đổi** hơn là *tuân theo một kế hoạch*

<hr style="width: 80%; text-align: center;"/>

Có nghĩa là, trong khi có các giá trị bên phải, chúng ta đánh giá các mục bên trái cần thiết hơn.

Mặc dù, tuyên ngôn Agile có cấu trúc đơn giản và ít ngôn từ, nhưng có rất nhiều điểm tốt trong bốn giá trị này. Việc hiểu những ý tưởng được truyền đạt trong các giá trị này là điều quan trọng không chỉ trong kỳ thi mà còn đối với việc tiếp cận linh hoạt vào bất cừ dự án tri thức nào.


<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Tuyên ngôn Agile được viếc bởi các chuyên gia phát triển phần mềm, vì vậy nó sử dụng các thuật ngữ từ lĩnh vực này để thể hiện ý tưởng của mình. Tuy nhiên, những ý tưởng đó có thể áp dụng cho bất cứ loại dự án tri thức nào. Vì vậy, mặc dù chúng ta có thể một số thuật ngữ riêng dành cho IT trong bài exam, chúng ta cũng cần có khả năng nhận ra những ý tưởng này trong các ngữ cảnh khác.
      <br/>
      Khi chúng ta đọc về Tuyên ngôn, hãy nhìn xa hơn các thuật ngữ cụ thể và suy nghĩ về cách những khái niệm này áp dụng cho các loại kiến thức khác.
      <br/>
      Ví dụ: Chúng ta có thể diễn đạt lại giá trị thứ hai là "Hệ thống làm việc hơn là tài liệu đầy đủ" thay thế "hệ thống" cho "phần mềm".
    </h7>
  </div>
</div>

<br/>

Định dạng của bốn giá trị cốt lõi là: A over B (A hơn là B) - đề cập đến ý định, trọng tâm và nỗ lực. Đây không phải chỉ nói thẳng ra là "Làm A thay vì B". Thay vào đó, nó thừa nhận rằng cả A và B sẽ là các thành phần trong dự án của chúng ta, nhưng chúng ta tập trung, nhấn mạnh và có ý định thực thi A hơn là B.

Tuyên ngôn Agile không phải là một bộ quy tắc yêu cầu chúng ta làm một việc thay vì một việc khác. Nó vừa tinh tế hơn vừa mạnh mẽ hơn - nó hướng dẫn chúng ta xem xét các dự án từ quan điểm dựa trên giá trị. vâng, chúng ta sẽ cần các quy trình, công cụ, tài liệu và kế hoạch cho các dự án của mình. Tuy nhiên, trong khi xử lý những tài sản này, chúng ta nên nhớ rằng trọng tâm của chúng ta phải là những người tương tác, sản phẩm chúng ta đang xây dựng, sự hợp tác và tính linh hoạt. Nhanh nhẹn là năng lực thực hiện các dự án trong khi tập trung nỗ lực của chúng ta vào các mục ở bên trái của các tuyên bố giá trị này, thay vì bên phải.

Với ý nghĩa này, chúng ta hãy xem xét bốn tuyên bố này chi tiết hơn.

**Giá trị 1: Cá nhân và tương tác hơn là Quy trình và công cụ**

Thông điệp ở đây là trong khi các quy trình và công cụ có thể sẽ cần thiết cho các dự án của chúng ta, chúng ta nên tập trung sự chú ý vào các cá nhân và các tương tác có liên quan. Điều này là do các dự án được thực hiện bởi con người, không phải công cụ và các vấn đề được giải quyết bởi con người chứ không phải quy trình. Tương tự như vậy, các dự án được mọi người chấp nhận, phạm vi được mọi người thảo luận, và định nghĩa dự án "đã hoàn thành" là do mọi người thương lượng. Tập trung sớm vào việc phát triển các cá nhân tham gia vào dự án và nhấn mạnh các tương tác năng suất và hiệu quả sẽ giúp thiết lập một dự án thành công.

Điều này không có nghĩa quy trình và công cụ không thể giúp hoàn thành dự án thành công. Chúng chắc chắn là tài sản quan trọng và đối với những người có nền tảng kỹ thuật, chúng ta có thể có xu hướng tự nhiên về tính logic và khả năng dự đoán của các quy trình và công cụ. Tuy nhiên, các dự án cuối cùng vẫn là về con người, vì vậy để thành công, chúng ta cần dành phần lớn thời gian của mình trong thế giới có thể ít thỏa mái hơn, lộn xộn và khó đoán của con người. Nếu chúng ta có hướng tới các quy trình hơn là ocn người, giá trị đầu tiên của "các cá nhân và sự tương tác hơn là quy trình và công cụ" là một lời nhắc nhở tuyệt vời về nơi tập trung thời gian, năng lượng và đam mê của chúng ta.

**Giá trị 2: Phần mềm hoạt động được hơn là tài liệu toàn diện**

Giá trị này nói lên sự cần thiết phải cung cấp. Như đã đề cập trước, nó có thể được hiểu rộng hơn là "Hệ thống hoạt động được hơn là tài liệu toàn diện", trong đó "Hệ thống" đề cập đến sản phẩm hoặc dịch vụ mà dự án đang cung cấp. Giá trị này nhắc nhở chúng ta tập trung vào mục đích hoặc giá trị kinh doanh đang cố gắng cung cấp, thay vì thủ tục giấy tờ. (Một số ngành được quản lý chặt chẽ, chẳng hạn như thiết bị y tế, yêu cầu nhiều tài liệu - đó chỉ là một phần của công việc cần được thực hiện. Giá trị này đề cập đến loại tài liệu không được bao gồm để hoàn thành công việc đúng cách.)

Cách tiếp cận Agile đối với tài liệu là “just enough, just in time— and sometimes, just because.”. Cụm từ này là cách viết tắt để nhắc nhở chúng ta ba khái niệm quan trọng:

- **JUST ENOUGH** : Tài liệu Agile nên vừa đủ - chỉ đủ để đáp ứng nhu cầu của chúng ta. Điều này khiến hầu hết các nỗ lực của chúng ta tập trung vào hệ thống khẩn cấp.

- **JUST IN TIME** : Tài liệu agile được thực hiện đúng lúc - còn được gọi là thời điểm chịu trách nhiệm cuối cùng. Vì vậy chúng ta không phải mất thêm thời gian để cập nhật tài liệu khi các yêu cầu và thiết kế của chúng ta thay đổi.

- **JUST BECAUSE** : Nhắc nhở chúng ta rằng đôi khi tài liệu được yêu cầu hoặc bắt buộc, chúng ta chỉ cần xuất trình nó sẽ dễ dàng hơn và thích hợp hơn là phải đối mặt với hậu quả của việc không làm như vậy.

Điểm cuối cùng đó không có nghĩa là chúng ta chỉ lướt qua các yêu cầu tài liệu không cần thiết. Ví dụ, phương pháp LEAN - tinh gọn - bao gồm khái niệm mạnh mẽ : 5 WHY để tìm ra những gì chúng ta thật sự cần.

Tuy nhiên, không ngoan cũng phải trả giá - với thời gian và efforts có giới hạn của dự án, chúng ta cần phải quyết định nơi nào để tập trung năng lượng tốt nhất của mình và theo đuổi trận chiến nào. Vì vậy, mặc dù chúng ta coi trọng việc nghiên cứu sản phẩm hơn là tài liệu, nhưng điều đó không có nghĩa là chúng ta từ bỏ giá trị đối lập.

Các dự án phần mềm thường được bắt đầu với mục tiêu tạo ra phần mềm có giá trị, chất lượng cao, nhưng chúng thường bị cuốn vào các phân phối tạm thời như tài liệu bổ sung, không hỗ trợ mục tiêu cuối cùng là phần mềm hoạt động. Phần mềm không có tài liệu chắc chắn có vấn đề và cản trở việc hỗ trợ và bảo trì. Nhưng tài liệu toàn diện mà không có phần mềm thì không có giá trị trong hầu hết các tổ chức.

Nhiều nhà phát triển phần mềm định hướng chi tiết và theo quy trình; mặc dù những đặc điểm này thường mang lại lợi ích cao, nhưng chúng cũng có thể có nghĩa là sự tập trung của developer có thể dễ dàng bị phân tán khỏi lý do thực sự mà họ đang thực hiện các dự án phần mềm - để viết phần mềm có giá trị. Vì vậy, việc nhấn mạnh vào đánh giá phần mềm hoạt động hơn là tài liệu toàn diện đóng vai trò như một nhắc nhở cần thiết và hữu ích về lý do tại sao những dự án này được thực hiện ngay từ đầu - để xây dựng một cái gì đó hữu ích. Chính tài liệu hay chi phí của phần mềm hoạt động mới là hữu ích.

**Giá trị 3: Hợp tác với khách hàng hơn là Thương thảo hợp đồng**

Giá trị này nhắc nhở chúng ta phải linh hoạt và thích nghi, thay vì cố định và bất hợp tác. Nó tương tự như sự khác biệt giữa **"đúng - BEING RIGHT"** và **"làm đúng _ DOING THE RIGHT THING"**. Chúng ta có thể xây dựng sản phẩm chính xác như đã chỉ định ban đầu, nhưng nếu sở thích hoặc mức độ ưu tiên của khách hàng thay đổi, tốt hơn hết là nên linh hoạt và hướng tới mục tiêu mới, trái ngược với mục tiêu đã nêu ra ban đầu.

Thật sự là rất khó để xác định được quan điểm một cách trực diện, không thay đổi tầm nhìn của những gì nên được xây dựng. Thách thức này bắt nguồn từ bản chất năng động của các sản phẩm công việc tri thức, đặc biệt là hệ thống phần mềm; phần mềm là vô hình và khó tham khảo, các công ty hiếm khi xây dựng hai hệ thống giống nhau, nhu cầu kinh doanh thay đổi nhanh chóng và công nghệ cũng vậy. Thay vì buộc khách hàng phải tuân theo một quy trình ngăn không cho thay đổi, chúng ta cần làm việc với khách hàng trong suốt dự án để đạt được định nghĩa của "DEFINE OF DONE". Điều này đòi hỏi một mối quan hệ tin cậy hơn và các mô hình hợp đồng linh hoạt hơn chúng ta thường thấy trong dự án. Nhưng - giống như giá trị trước - nó chuyển sự nhấn mạnh từ các hoạt động bổ sung phi giá trị (chẳng hạn như tranh luận về scope) sang làm việc năng suất.

**Giá trị 4: Đáp ứng sự thay đổi hơn là tuân theo một kế hoạch**

Trong các dự án tri thức, chúng ta biết rằng kế hoạch ban đầu là không đầy đủ vì chúng dựa trên những thông tin không đầy đủ về những gì cần hoàn thành dự án. Vì vậy, thay vì đầu tư efforts vào việc cố gắng đưa dự án trở lại đúng với kế hoạch ban đầu, chúng ta muốn dành nhiều công sức và sức lực hơn để đáp ứng những thay đổi chắc chắn sẽ phát sinh. Hiện tại, điều này không có nghĩa là chúng ta nên từ bỏ việc lập kế hoạch và chỉ phẩn ứng với những thay đổi. Chúng ta vẫn cần lập kế hoạch, nhưng chứng ta cũng cần phải thường nhận rằng kế hoạch ban đầu được thực hiện khi chúng ta biết ít nhất về dự án và sẽ cần phải cập nhật khi công việc tiến triển.

Tầm quan trọng của việc đáp ứng sự thay đổi so với việc tuân theo một kế hoạch đặc biệt đúng đối với các dự án phần mềm, nơi là tỷ lệ thay đổi cao là phổ  biến. Một lần nữa, thay vì đè nén những thay đổi và dành nhiều thời gian để quán lý và theo dõi một kế hoạch chủ yếu là tĩnh, chúng ta cần thừa nhận rằng mọi thứ sẽ luôn luôn thay đổi. Các dự án Agile có các hagn2 đợi công việc và kế hoạch rất dễ nhìn thấy dưới dạng các bản ghi và bảng ghi nhiệm vụ tồn đọng. Mục đích của giá trị này là mở rộng số lượng người có thể sẵn sàng tham gia vào quá trình lập kế hoạch bằng cách điều chỉnh các kế hoạch và thảo luận về tác động của những thay đổi.

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập</h5>

  <p>Vẽ mũi tên để kết nối những Tuyên ngôn Agile theo giá trị bên trái ứng với bên phải</p>

  <br/>
  <img src="/assets/images/agilemanifestoExercise.png" alt="agilemanifestoExercise">

  <br/>

  <br/>
  <p> ĐÁP ÁN </p>
  <img src="/assets/images/agileManifesAnswer.png" alt="agileManifesAnswer">

</div>

{:#twelvePrinciple}
## Mười hai nguyên tắc

Song song với 4 giá trị agile, các tác giả của Tuyên ngôn Agile cũng tạo ra 12 nguyên tắc hướng dẫn cho phương pháp Agile.

Phần này của tuyên ngôn Agile như bên dưới:

<div id="practises" style="font-size: 12px;">
  <h5>Những nguyên tắc phía sau Tuyên ngôn Agile</h5>

  <p>Chúng ta tuân theo những nguyên tắc:</p>

  <h6>①　Ưu tiên cao nhất của chúng ta là làm hài lòng khách hàng thông qua việc phân phối sớm và liên tục.</h6>
  <h6>②　Hoan nghênh sự thay đổi yêu cầu, ngay cả khi trễ trong phát triển. Các quy trình agile khai thác sự thay đổi vì lợi thế cạnh tranh của khách hàng.</h6>
  <h6>③　Cung cấp phần mềm hoạt động thường xuyên, từ vài tuần đến vài tháng, với ưu tiên cho những khoảng thời gian ngắn hơn.</h6>
  <h6>④　Doanh nhân và nhà phát triển phải làm việc cùng nhau hàng ngày trong suốt dự án.</h6>
  <h6>⑤　Xây dựng các dự án xung quanh những cá nhân có động lực. Cung cấp cho họ môi trường và sự hỗ trợ mà họ cần, tin tưởng để họ hoàn thành công việc.</h6>
  <h6>⑥　Phương pháp hiệu quả và ảnh hưởng nhất để truyền tải thông tin trong nhóm phát triển là trò chuyện liên tục.</h6>
  <h6>⑦　Phần mềm làm việc được là thước đo chính của sự tiến bộ.</h6>
  <h6>⑧　Các quy trình Agile thúc đẩy sự phát triển bền vững. Các nhà đầu tư, nhà phát triển và người dùng sẽ có thể duy trì tốc độ liên tục vô thời hạn.</h6>
  <h6>⑨　Liên tục chú ý đến sự xuất sắc về kỹ thuật và thiết kế giúp tăng cường sự linh hoạt và nhanh nhẹn.</h6>
  <h6>⑩　Đơn giản - nghệ thuật tối đa hóa khối lượng công việc chưa hoàn thành - là điều thiết yếu.</h6>
  <h6>⑪　Các kiến trúc, yêu cầu và thiết kế tốt nhất xuất hiện từ các nhóm tự tổ chức.</h6>
  <h6>⑫　Định kỳ, nhóm phản ánh về cách trở nên hiệu quả hơn, sau đó kiểm điểm và điều chỉnh hành vi của mình.</h6>
</div>

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
    Vì những giá trị và nguyên tắc này là cơ bản để hiểu Agile, hãy nghĩ đến chúng khi ta phải đối mặt với hai lựa chọn có vẻ đúng trong exam. Trong trường hợp như vậy, hãy tìm câu trả lời phù hợp nhất với các giá trị và nguyên tắc của Tuyên ngôn Agile.
    </h7>
  </div>
</div>

Chúng ta hãy xem xét kỹ hơn từng nguyên tắc trong mười hai nguyên tắc của Tuyên ngôn Agile. Một lần nữa, mặc dù các nguyên tắc có thể sử dụng các thuật ngữ phát triển phần mềm, khi ta đọc về chúng, hãy nghĩ về các khái niệm này áp dụng cho các loại dự án công việc tri thức khác.

**Nguyên tắc 1: Ưu tiên cao nhất của chúng ta là làm hài lòng khách hàng thông qua việc phân phối sớm và liên tục.**

Nguyên tắc này bao gồm 3 điểm chính. Đầu tiên là làm hài lòng khách hàng. Nếu chúng ta đưa ra các kế hoạch và tài liệu hoàn hảo, nhưng chỉ làm hài lòng bộ phận quản lý dự án (PMO) hoặc nhóm đảm bảo chất lượng (QA), chúng ta đã thất bại; trọng tâm phải là KHÁCH HÀNG.

Điểm thứ hai là phân phối sớm và liên tục. Chúng ta phải cấu trúc dự án và nhóm phát triển để cung cấp giá trị sớm và thường xuyên. Đây có thể là một cuộc đấu tranh nếu mọi người miễn cưỡng chia sẻ công việc chưa hoàn thành và cần có sự can đảm và hỗ trợ để mọi người trở nên thỏa mái với ý tưởng này. Tuy nhiên, chúng ta phải đạt được điểm này nếu chúng ta tìm hiểu các vấn đề trong khi chúng ta vẫn còn thời gian để khắc phục chúng. Tốt hơn là chúng ta nên phát hiện điều sai sớm và sửa chữa nó hơn là tìm ra vấn đề rất trễ sau khi đã xây dựng trên nền móng bị lỗi.

Điểm cuối cùng là những gì chúng ta đang cung cấp là phần mêm có giá trị (nghĩa là hệ thống), không phải danh sách công việc, hạng mục cấu trúc công việc, tài liệu hay là các kế hoạch. Chúng ta cần tập trung vào mục tiêu cuối cùng. Với dự án phần mềm, đây là phần mềm; đối với loại dự án khác, mục tiêu cuối cùng sẽ là sản phẩm hoặc dịch vụ mà dự án thực hiện để cung cấp hoặc cải thiện.

**Nguyên tắc 2: Hoan nghênh sự thay đổi yêu cầu, ngay cả khi trễ trong phát triển. Các quy trình agile khai thác sự thay đổi vì lợi thế cạnh tranh của khách hàng.**

Những thay đổi có thể rất tốt cho một dự án - ví dụ, nếu họ cho phép chúng ta cung cấp một tính năng ưu tiên cao, có tính đột phá. Tuy nhiên, trong các dự án phi Agile, các thay đổi thường được nhìn nhận theo hướng tiêu cực; chúng có thể bị coi là sai lệch phạm vi (Scope creep) hoặc bị đổ lỗi cho việc dự án đi chệch với kế hoạch. Nhiều dự án phi Agile có các quy trình kiểm soát thay đổi nghiêm ngặt đến mức chỉ những người có mức độ ưu tiên cao nhất mới thực hiện được. Trong các dự án như vậy, phần lớn thời gian và công sức được dành cho việc ghi nhật ký và quản lý các yêu cầu thay đổi.

Loại quản lý thay đổi nghiêm ngặt nyà là vấn đề đối với bất cứ dự án nào trong môi trường có tính thay đổi cao, chẳng hạn như phát triển phần mềm - vì vậy agile chấp nhận rằng các thay đổi sẽ xảy ra. Trên thực tế, phương pháp XP ủng hộ rằng chúng ta chấp nhận sự thay đổi.

Thay vì tạo ra một cơ chế chi phí cao để ngăn chặn hoặc xử lý các thay đổi, các phương pháp Agile sử dụng cách tiếp cận nhẹ, khả năng hữu hình cao - ví dụ: cập nhật liên tục và ưu tiên các thay đổi đối với công việc tồn đọng cần thực hiện. Các phương pháp xử lý thay đổi được hiểu rõ và có khả năng hữu hình cao của Agile giúp dự án luôn thích nghi và linh hoạt lâu nhất có thể. Bằng cách hoan nghênh sự thay đổi chắc chắn sẽ xảy ra và thiết lập hiệu quả cách để đối phó với chúng, chúng ta có thể dành nhiều thời gian hơn để phát triển sản phẩm cuối cùng.

**Nguyên tắc 3: Cung cấp phần mềm hoạt động thường xuyên, từ vài tuần đến vài tháng, với ưu tiên cho những khoảng thời gian ngắn hơn.**

Mặc dù thái độ và kiến thức tốt nhất của chúng ta là phản hồi sớm là có giá trị, nhưng bản chất của con người là muốn công việc của chúng ta hoàn thiện nhất trước khi có thể chia sẻ nó. Tuy nhiên, chúng ta đang tự làm mình thất vọng khi cố chấp vào công việc của mình quá lâu. Tốt hơn hết nên phản hồi sớm và thường xuyên, để tránh đi quá xa và sai hướng.

Nguyên tắc này nhấn mạnh tầm quan trọng của việc đưa công việc vào môi trường thử nghiệm và nhận phản hồi. Việc kiểm tra và phản hồi thường xuyên rất quan trọng đến mức các nhà phát triển phần mềm sử dụng các công cụ tích hợp liên tục để cung cấp phản hồi về bất cứ source code nào được viết. Các nhóm Agile cần phản hồi về những gì họ đã tạo cho đến nay để xem liệu họ có thể tiếp tục hay không, hoặc tất nhinê là có cần thay đổi hay không.

Phân phối trong khoảng thời gian ngắn cũng có lợi ích là giữ cho chủ sở hữu sản phẩm gắn bó và duy trì giao tiếp với dự án. Với việc phân phối thường xuyên, chúng ta sẽ thường xuyên có kết quả để hiển thị cho khách hàng và cơ hội nhận được phản hồi. Thông thường, tại cách buổi demo, chúng ta tìm hiểu các yêu cầu mới hoặc những thay đổi trong các mức độ ưu tiên của kinh doanh là những yếu tố inputs có giá trị trong việc lập kế hoạch.

**Nguyên tắc 4: Doanh nhân và nhà phát triển phải làm việc cùng nhau hàng ngày trong suốt dự án.**

Các bản demo thường xuyên được đề cập ở trên là một ví dụ về cách các đại diện doanh nghiệp và nhà phát triển làm việc cùng nhau trong suốt dự án. Tương tác trực tiếp hàng ngày với khách hàng là một trong những nguyên tắc khó đảm bảo nhất từ quan điểm thực tế, nhưng nó thực sự đáng được thúc đẩy. Văn bản, email, và thậm chí là điện thoại là những cách truyền thông tin kém hiệu quả hơn so với tương tác trực tiếp. (FACE-TO-FACE interactions)

Bằng cách làm việc với đại diện doanh nghiệp hàng ngày, chúng ta có thể tìm hiểu về doanh nghiệp theo cách vượt xa những gì mà một bộ tập hợp các cuộc họp thu thập yêu cầu có thể đạt được. Do đó, chúng ta có thể đề xuất các giải pháp và lựa chọn thay thế tốt hơn cho các yêu cầu kinh doanh. Các đại diện của doanh nghiệp cũng tìm hiểu những loại giải pháp đắt tiền và chậm phát triển, và những tính năng nào rẻ. Sau đó, họ có thể bắt đầu tinh chỉnh các yêu cầu của mình để đáp ứng.

Khi không thể có các tương tác hàng ngày giữa đại diện doanh nghiệp và nhóm phát triển, các phương pháp Agile sẽ cố gắng để hai nhóm làm việc cùng nhau thường xuyên theo một cách nào đó, có thể hai ngày một lần hoặc bất cứ hình thức tham gia thường xuyên nào hiệu quả. (Một số nhóm sử dụng "khách hàng ủy quyền", trong đó một nhà phân tích kinh doanh có kinh nghiệm [BA - business analysis] quen thuộc với các lợi ích kinh doanh đóng vai trò thay thế, nhưng đây không phải là một lựa chọn lý tưởng.)


**Nguyên tắc 5: Xây dựng các dự án xung quanh những cá nhân có động lực. Cung cấp cho họ môi trường và sự hỗ trợ mà họ cần, tin tưởng để họ hoàn thành công việc.**

Chúng ta sẽ thấy trong chương 4, dữ liệu ước tính phần mềm được thu thập bởi mô hình COCOMOII® đã phát hiện ra rằng việc có những người giỏi nhất nhất quan trọng hơn đáng kể đối với một dự án so với việc có các quy trình và công cụ tốt nhất - theo hệ số từ 10 đến 1. Vì vậy, đảm bảo rằng chúng ta có những người thông minh và năng động trong nhóm có khả năng tạo sự khác biệt lớn trong việc liệu dự án có được thực hiện thành công và hiệu quả hay không.

Mặc dù không phải lúc nào chúng ta cũng có thể chọn được nhóm trong mơ của mình, nhưng chúng ta có thể thúc đẩy và trao quyền cho các thành viên trong nhóm mà chúng ta có. Vì nhóm phát triển là một nhân tố quan trọng như vậy nên các phương pháp Agile thúc đẩy các nhóm được trao quyền. Mọi người làm việc tốt hơn khi họ được trao quyền tự chủ để tổ chức và lập kế hoạch công việc của riêng họ. Các phương pháp Agile ủng hộ việc giải phóng nhóm khỏi sự quản lý quy mô của vệc hoàn thành nhiệm vụ trên Biểu đồ Gantt. Thay vào đó, sự tập trung vào kỹ năng cá nhân, sự hợp tác đồng nghiệp và làm việc theo nhóm, dẫn đến tỷ lệ năng suất cao hơn.

Các dự án công việc tri thức liên quan đến các thành viên nhóm, những người có các lĩnh vực chuyên môn độc đáo. Những người như vậy làm việc tốt nhất của họ khi họ được phép đưa ra nhiều quyết định hàng ngày và lập kế hoạch nội bộ dự án. Đối với các nhà lãnh đạo, điều này không có nghĩa từ bỏ tham gia hay từ bỏ nhóm để nhóm tự chống đỡ; thay vào đó, chúng ta nhân ra rằng các thành viên trong của chúng là chuyên gia trong những gì họ làm và chúng ta cung cấp sự hỗ trợ cần thiết để đảm bảo họ thành công/

**Nguyên tắc 6: Phương pháp hiệu quả và ảnh hưởng nhất để truyền tải thông tin trong nhóm phát triển là trò chuyện liên tục.**

Các tài liệu dạng văn bản rất tốt để tạo một hồ sơ lâu dài về các sự kiện và quyết định, nhưng chúng chậm và tốn kém chi phí để tạo ra. Ngược lại, giao tiếp FACE-TO-FACE cho phép chúng ta nhanh chóng chuyển nhiều thông tin theo cách phong phú hơn bao gồm cả cảm xúc và ngôn ngữ cơ thể.

Trong cuộc giao tiếp face-to-face, câu hỏi có thể được trả lời ngay lập tức, thay vì "parked - đậu xe" với hy vọng sẽ có lời giải thích tiếp theo, hoặc câu trả lời sẽ rõ ràng sau này. Ví dụ: thay vì đọc cuốn sách này, chúng ta nói chuyện với nhau, chúng ta có thể nhanh chóng bỏ tất cả những điều đã biết và tập trung vào những vấn đề muốn tìm hiểu thêm. Các tài liệu viết phải có xuất phát điểm thấp hơn để không gây nhầm lẫn cho đối tượng rộng hơn của chúng.

Tất nhiên, đề xuất này cho các cuộc trò chuyện trực tiếp không thể được áp dụng cho tất cả các cuộc giao tiếp trong dự án, nhưng các nhóm Agile muốn làm theo đề xuất đó bất cứ khi nào có thể. Đây là một ví dụ về cách các phương thức Agile cần được tùy chỉnh hoặc mở rộng cho mỗi dự án. Khi quy mô nhóm càng ngày càng phát triển, việc dựa vào giao tiếp trực tiếp trở nên khó khăn hơn và chúng ta phải đưa ra mức tài liệu viết phù hợp.

**Nguyên tắc 7: Phần mềm làm việc được là thước đo chính của sự tiến bộ.**

Bằng cách sử dụng "Working software" làm thước đo tiến độ chính của chúng ta, chúng ta chuyển trọng tâm sang kết quả làm việc hơn là tài liệu và thiết kế. Trong Agile, chúng ta đánh giá tiến độ dựa trên sản phẩm hoặc dịch vụ mà chúng ta đang tạo ra. Những câu hỏi như: "Bao nhiêu giải pháp được thực hiện và được chấp nhận?", được ưu tiên hơn là "Thiết kế đã hoàn chỉnh chưa?". Vì chúng ta muốn tập trung vào khả năng sử dụng và tiện ích hơn là sự tiến bộ về mặt khái niệm.

Các biểu thức như: "Những đo lường nào sẽ được thực hiện?" và "Có lấy được kết quả gì từ những đo lường đó không?" áp dụng ở đây vì phép đo lường củng cố hoạt động. Nếu một tính năng không thể được đo lường hoặc kiểm tra - nói cách khác, nếu tính năng đó không "hoạt động" - thì tính năng đó không được coi là hoàn chỉnh. Sự nhấn mạnh này vào một sản phẩm đang hoạt động giúp đảm bảo rằng chúng ta nhận được các tính năng được khách hàng chấp nhận, thay vì đánh dấu các mục là "phát triển hoàn thiện - completed development" khi chúng chưa được chấp nhận là đã hoàn thành "DONE".

**Nguyên tắc 8: Các quy trình Agile thúc đẩy sự phát triển bền vững. Các nhà đầu tư, nhà phát triển và người dùng sẽ có thể duy trì tốc độ liên tục vô thời hạn.**

Các phương pháp agile cố gắng tối đa hóa giá trị trong dài hạn. MỘt số kỹ thuật pháp triển ứng dụng nhanh (RAD - Rapid application development) trước đó được thúc đẩy nhanh chóng - hoặc ít nhất là được chấp nhận - khoảng thời gian lâu, cường độ cao trước khi demo. Vấn đề với cách tiếp cận RAD của các nhóm làm việc trong nhiều giờ trong một thời gian dài là mọi người bắt đầu kiệt sức và mắc sai lầm. Đây không phải là một thực hành bền vững.

Thay vì thời gian phát triển kéo dài và cường độ cao, các phương pháp Agile nhận ra giá trị của tốc độ bền vững cho phép các thành viên trong nhóm duy trì sự cân bằng giữa công việc và cuộc sống. Tốc độ bền vững không chỉ tốt hơn cho nhóm, nó cũng mang lại lợi ích cho tổ chức. Ngày làm việc kéo dài dận đến việc nghỉ việc, có nghĩa là tổ chức mất đi tài năng và kiến thức lĩnh vực. Việc thuê và tích hợp các thành viên mới vào một nhóm là quá trình chậm và tốn kém.

Ngược lại, làm việc với tốc độ có thể được duy trì vô thời hạn dẫn đến một nhóm hạnh phúc và hiệu quả hơn. Các nhóm vui vẻ cũng hòa hợp với đại diện doanh nghiệp tốt hơn các nhóm làm việc quá sức. Có ít căng thẳng hơn và các mối quan hệ công việc được cải thiện. Một số phương pháp Agile như XP, trước đây đã khuyến nghị một tuần làm việc đều đặn 40 giờ như một nguyên tắc hướng dẫn. Ngày nay, hầu hết các phương pháp không thiết lập giới hạn cụ thể, nhưng họ khuyên chúng ta nên chú ý đến mức độ effort mà nhóm đang đưa ra để đảm bảo tốc độ bền vững.

**Nguyên tắc 9: Liên tục chú ý đến sự xuất sắc về kỹ thuật và thiết kế giúp tăng cường sự linh hoạt và nhanh nhẹn.**

Mặc dù chúng ta muốn nhóm phát triển làm việc chăm chỉ và mang lại giá trị, nhưng chúng ta cũng phải lưu ý đến việc giữ cho thiết kế sạch sẽ, hiệu quả và cởi mở với các thay đổi. Kỹ thuật xuất sắc và thiết kế tốt cho phép nhóm phát triển hiểu và cập nhật thiết kế một cách dễ dàng.

Một nhóm agile cần phải cân bằng effort của mình để cung cấp các tính năng có giá trị cao với sự chú ý liên tục đến việc thiết kế các giải pháp. Sự cân bằng này cho phép sản phẩm mang lại giá trị lâu dài mà không trở nên khó bảo trì, thay đổi hoặc kéo dài - việc làm sạch và bảo trì phòng ngừa được ưu tiên hơn là khắc phục sự cố. Điều này giúp dự án chạy trơn tru hơn và đẩy nhanh tiến độ của nhóm.

Trong thế giới phần mềm, một khi code trở nên rối rắm, tổ chức sẽ mất khả năng đáp ứng các nhu cầu thay đổi. Nói cách khác, nó mất đi sự linh hoạt. Vì vậy, chúng ta cần cho nhóm phát triển đủ thời gian để thực hiện tái cấu trúc. Tái cấu trúc là công việc quản lý, dọn dẹp và đơn giản hóa cần được thực hiện đối với mã nguồn để đảm bảo tính ổn định và duy trì lâu dài.

**Nguyên tắc 10: Đơn giản - nghệ thuật tối đa hóa khối lượng công việc chưa hoàn thành - là điều thiết yếu.**

Các tính năng đáng tin cậy nhất là những tính năng chúng ta không xây dựng - vì không có gì có thể xảy ra với chúng. Và, trong thế giới phần mềm, có tới 60% các tính năng được xây dựng mà không được thường xuyên hay không bao giờ sử dụng. Bởi vì các hệ thống phức tạp có khả năng trở nên không đáng tin cậy ngày càng tăng, các phương pháp Agile tập trung vào tính đơn giản. Điều này có nghĩa là chỉ rút gọn các yêu cầu của chúng ta xuống thành các yếu tố thiết yếu nhất.

Các dự án phức tạp mất nhiều thời gian hơn để hoàn thành, tiềm ẩn rủi ro dài hơn và có nhiều điểm thất bại tiềm ẩn hơn và cơ hội vụt mất. Do đó, các phương pháp Agile tìm kiếm điều "Đơn giản nhất là có thể hoạt động" và khuyến khích rằng giải pháp này nên được xây dựng trước. Cách tiếp cận này không nhằm mục đích loại trừ khả năng mở rộng và cải tiến thêm của sản phẩm - thay vào đó, nó chỉ đơn giản nói rằng: Hãy tạo phiên bản tinh gọn trước. Cách tiếp cận này không chỉ giảm thiểu rủi ro mà còn giúp tăng cường niềm tin của nhà đầu tư.

**Nguyên tắc 11: Các kiến trúc, yêu cầu và thiết kế tốt nhất xuất hiện từ các nhóm tự tổ chức.**

Nguyên tắc này nghe có vẻ kỳ quặc, tùy thuộc vào cách chúng ta đọc nó theo nghĩa đen. Về cơ bản, người ta nói rằng để khai thác tốt nhất con người, chúng ta phải để họ tự tổ chức. Người thích tự tổ chức, nó cho phép họ tìm ra cách tiếp cận phù hợp nhất với phương pháp, mối quan hệ của họ và môi trường của họ. Họ sẽ hiểu cặn kẽ và ủng hộ phương pháp này, bởi vì họ đã giúp tạo ra nó. Kết quả là họ sẽ tạo ra công việc tốt hơn.

Tuy nhiên, chúng ta cũng có thể hỏi tại sao nguyên tắc này nói rằng các kiến trúc, yêu cầu và thiết kế tốt nhất đến từ nhóm dự án - chứ không phải là các tổ chức kiến trúc sư, nhà phân tích kinh doanh và nhà thiết kế giỏi nhất, những người có thể không có trong nhóm. Theo kinh nghiệm thực tiễn, câu trả lời cho câu hỏi này là các kiến trúc, yêu cầu và thiết kế của chúng ta hoạt động tốt nhất khi chúng được thực hiện bởi những người tạo ra chúng. Mặc dù các khuyến nghị bên ngoài có thể có nhiều điểm kỹ thuật hơn trên giấy, nhưng nếu chúng được thực hiện khác với hình dung ban đầu hoặc không được nhóm thuyết phục, thì cuối cùng chúng sẽ kém thành công hơn.

Các nhóm tự tổ chức có quyền tự quyết đưa ra các quyết định nội bộ có mức độ sở hữu và niềm tự hào cao hơn về kiến trúc, yêu cầu và thiết kế mà họ tạo ra so với những nhóm bị ép buộc hoặc "gợi ý" bởi các nguồn bên ngoià. Các ý tưởng do nhóm tạo ra đã trải qua quá trình kiểm duyệt của nhóm để điều chỉnh và phê duyệt - vì vậy, chúng không cần phải được "bán" cho nhóm. Ngược lại, những ý tưởng đến từ các nguồn lực bên ngoài cần phải được truyền đạt cho nhóm để việc thực hiện được thành côngm và đây đôi khi là một nhiệm vụ đầy thách thức.

Một yếu tố khác hỗ trợ nguyên tắc này là các thành viên của nhóm dự án tự tổ chức là những người gần gũi nhất với các chi tiết kỹ thuật của dự án. Kết quả là, họ có thể phát hiện ra các vấn đề triển khai tốt nhất, cùng với các cơ hội cải tiến. Vì vậy, thay vì cố gắng giáo dục những người bên ngoài về cấu trúc đang phát triển của dự án, các phương pháp Agile tận dụng năng lực của nhóm để chẩn đoán và cải thiện tốt nhất kiến trúc, yêu cầu và thiết kế của dự án. Rốt cuộc, các thành viên trong nhóm là những người được thông báo nhiều nhất về dự án và có nhiều sự ủng hộ nhất.

**Nguyên tắc 12: Định kỳ, nhóm phản ánh về cách trở nên hiệu quả hơn, sau đó kiểm điểm và điều chỉnh hành vi của mình.**

Thành thật mà nói, thu thập các bài học kinh nghiệm khi kết thúc một dự án là quá ít, quá muộn. Thay vào đó, chúng ta cần thu thập các bài học kinh nghiệm của mình trong khi chúng vẫn có thể áp dụng và hành động được. Điều này có nghĩa là chúng ta cần thu thập chúng trong suốt dự án - và quan trọng nhất - đảm bảo rằng chúng ta làm điều gì đó về những gì đã học được để điều chỉnh cách chúng ta hoàn thành phần còn lại của dự án.

Các phương pháp Agile sử dụng phương pháp nhìn lại thường xuyên, được gọi là "Retrospectives - hồi tưởng", để phản ánh cách mọi thứ đang hoạt động trong dự án và xác định các cơ hội để cải tiến. Những công việc hồi tưởng này thường xuyên được thực hiện trong giai đoạn cuối của mỗi vòng lặp, đảm bảo rằng nhóm có cơ hội thường xuyên để xem xét quy trình của họ. Một lợi thế của việc kiểm tra lại thường xuyên là chúng ta không quên các vấn đề và sự cố. So sánh điều này với việc thực hiện một đánh giá rút ra bài học duy nhất vào cuối mỗi dự án, trong đó các thành viên trong nhóm được yêu cầu nghĩ lại hơn một năm hoặc hơn để nhớ lại những vấn đề đã diễn ra tốt đẹp và nơi họ gặp vấn đề.

Một nhược điểm khác của việc chỉ thu thập các bài học kinh nghiệm khi kết thúc một dự án là các bài học sẽ không thực sự hữu ích cho tổ chức cho đến khi một dự án khác với lĩnh vực kinh doanh hoặc kỹ thuật, hoặc động lực tương tự của nhóm xuất hiện. Và tại thời điểm đó, rất dễ dàng loại bỏ những bài học kinh nghiệm từ một dự án trước đó vì không áp dụng được vào tình hình hiện tại. Trong một dự án Agile, chúng ta nắm bắt các bài học kinh nghiệm khi dự án tiến triển, vì vậy chúng ta không thể giả vờ rằng chúng không thể áp dụng được. Chúng ta biết chúng có liên quan và chúng ta có động lực để điều chỉnh quy trình của mình cho phù hợp.

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập - Tóm tắt kỹ lưỡng</h5>

  <p>Để đảm bảo chúng ta hiểu mục đích đằng sau mỗi nguyên tắc trong Tuyên ngôn Agile, hãy rút ngắn chúng chỉ có năm từ hoặc ít hơn mô tả bản chất của ý tưởng. Có thể sử dụng những mô tả trước đó để hỗ trợ trí nhớ, giúp ta nhớ lại được những khái niệm này. Hai nguyên tắc đầu tiên được làm như là ví dụ.</p>
</div>

|Principle - Nguyên tắc| Shortened Version - Phiên bản ngắn gọn|
|-----|-----|
| Our highest priority is to satisfy the customer through
early and continuous delivery of valuable software. |  Satisfy  customer with great systems  |
| Welcome changing requirements, even late in
development. Agile processes harness change for the
customer’s competitive advantage. |  Welcome change  |
| Deliver working software frequently, from a couple of
weeks to a couple of months, with a preference to the
shorter timescale. | Deliver working software frequently   |
| Business people and developers must work together daily
throughout the project. |   Work together daily |
| Build projects around motivated individuals. Give them
the environment and support they need, and trust them to
get the job done. |  Empowerment for develop team  |
| The most efficient and effective method of conveying
information to and within a development team is face-to-face conversation. |  Face-to-Face conversation is the most efficient and effective  |
| Working software is the primary measure of progress. | Mesure progress by working software   |
|Agile processes promote sustainable development. The
sponsors, developers, and users should be able to maintain
a constant pace indefinitely  |  Agile promote sustainable development  |
|Continuous attention to technical excellence and good
design enhances agility  |  Continuous attention to technical and design  |
|Simplicity— the art of maximizing the amount of work not
done— is essential.  | Simplicity is essential   |
| The best architectures, requirements, and designs emerge
from self-organizing teams. |   Self-organizing teams  |
| At regular intervals, the team reflects on how to become
more effective, then tunes and adjusts its behavior
accordingly. |  Retrospectives  |

ĐÁP ÁN:

![shortPrinciple]({{ site.baseurl }}/assets/images/shortPrinciple.png)

<div id="toolkitBox">
  <div id="toolkitIcon">K&S</div>
  <h2 id="toolkitContent">Các phương pháp Agile<br/><hr/></h2>
</div>

<br/>

Có hàng tá phương phương pháp Agile được tích cực sử dụng. Các cách tiếp cận phổ biến nhất là Scrum, Lập trình cực hạn (Extreme Programming), phát triển sản phẩm tinh gọn (Lean product development), Kanban, Phát triển hướng tính năng (FDD - Feature-Driven Development), Phương pháp phát triển hệ thống động (DSDM - Dynamic Systems Development Method), và các phương pháp tinh thể.

Trong phần thảo luận sau đó, chúng ta sẽ mô tả từng phương pháp này ở mức độ chi tiết cần cho kỳ thi. Hai phương pháp Agile được sử dụng rộng rãi nhất là Scrum và XP, được giới thiệu nổi bật trong kỳ thi PMI-ACP. Khám phá kỹ lưỡng hai cách tiếp cận này một cách chi tiết nhất, bao gồm các khái niệm, nhóm, hoạt động và sản phẩm chính của chúng. Kỳ thi cũng có thể bao gồm nhiều câu hỏi về phương pháp tiếp cận tinh gọn và Kanban. Mặc dù các phần này không dài nhưng điều quan trọng là chúng ta phải hiểu tất cả thông tin được cung cấp về các phương pháp này. Cuối cùng, bài kiểm tra có thể không có bất kỳ câu hỏi nào về FDD (Feature-Driven Development), DSDM (Dynamic Systems Development Method), hoặc Crytal (tinh thể) - hoặc có lẽ chỉ một câu hỏi về chúng. Tuy nhiên, vẫn sẽ hữu ích nếu chúng ta hiểu rõ về các phương pháp này, vì chúng có thể xuất hiện dưới dạng các tùy chọn câu trả lời không chính xác mà cần phải loại trừ.

Chúng ta đã nói rằng Agile là một tư duy, không phải là một tập hợp các phương pháp cụ thể và nhiều phương thức Agile cho phù hợp với hoàn cảnh của riêng nó. Đây được gọi là điều chỉnh quy trình và chúng ta sẽ thảo luận chi tiết hơn về ưu và nhược điểm của nó trong chương 7. Tại thời điểm này, chỉ cần biết rằng một số phương pháp trong số này hoạt động tốt nhất khi được sử dụng "nguyên trạng" (đối với các nhóm mới làm quen với Agile), trong khi những người khác cho phép bản thân dễ dàng điều chỉnh và thích ứng.

Ví dụ, Kanban khuyến khích sửa đổi và thích ứng; Crytal cung cấp một loạt các phương pháp luận cho các loại dự án khác nhau và DSDM cung cấp các bộ lọc tính phù hợp để đánh giá mức độ phù hợp của một phương pháp tiếp cận một dự án. Mặt khác, cả Scrum và XP đều bao gồm một tập hợp các phương pháp cân bằng hoạt động tốt nhất khi được sử dụng "bên ngoài" như một hệ thống tích hợp, ít nhất là cho đến khi nhóm có đủ kinh nghiệm Agile để hiểu tất cả các mảnh ghép với nhau.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Các phương pháp Agile khác nhau, và tính linh hoạt vốn có của chúng, đã đưa ra một tình huống khó xử đối với PMI trong việc tạo kỳ thi, vì không có cách nào "đúng" để thực hiện Agile.
    </h7>
    <h7>
      Khi Ban chỉ đạo PMI-ACP ban đầu xây dựng đề cương nội dung kỳ thi, PMI đã nhận ra điều trớ trêu là phải tạo đề cương kỳ thi theo quy định cho một quy trình thích ứng, có thể mở rộng. Tuy nhiên, PMI phải đưa ra một số giả định về quy mô nhóm, thành phần và độ phức tạp của dự án sẽ được kiểm tra. Cuối cùng, PMI quyết định tập trung vào các phương pháp thường được áp dụng cho các dự án quy mô vừa và nhỏ. Vì vậy, nếu đang gặp khó khăn với bối cảnh của câu hỏi đề thi, hãy nghĩ đến một dự án có nhóm phát triển lên đến 12 người và đang sử dụng phương pháp tùy chọn hay thiết yếu.
    </h7>
  </div>
</div>

<br/>

Trong chương này, chúng ta sẽ mô tả từng phương pháp tiếp cận agile như một phương pháp luận độc lập, vì thông tin đó sẽ được kiểm tra trong kỳ thi. Tuy nhiên, không có gì lạ khi các nhóm agile sử dụng phương pháp tùy chỉnh kết hợp với các yếu tố từ nhiều phương pháp. Ví dụ, một nhóm có thể kết hợp một số phương pháp của XP, chẳng hạn như tái cấu trúc, lập trình cặp (pair programming), thiết kế đơn giản, với các tiếp cận Scrum để lập kế hoạch. Chúng ta sẽ nói thêm về các "mô hình kết hợp" này trong chương 7, cung cấp một số ví dụ về cách các phương pháp tiếp cận khác nhau có thể được sử dụng cùng nhau.


<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Có phản hồi rằng, những người am hiểu về phương pháp Scrum đang gặp khó khăn trong việc vượt qua kỳ thi PMI-ACP. Những sinh viên này tin rằng "Scrum là Agile" - và do đó, nói rộng ra, Agile là Scrum, và chỉ Scrum - và vì họ đã biết Scrum nên họ không học đúng cách cho kỳ thi.
    </h7>
    <h7>
      Ví dụ, họ giả định rằng tất cả các nhóm Agile đều có chủ sở hữu sản phẩm (Product Owner) và làm việc trong các sprints có hộp thời gian (timebox) theo sprint, sau đó là các cuộc họp đánh giá sprint. Tuy nhiên, bài kiểm tra PMI-ACP kiểm tra một bức tranh rộng hơn nhiều về Agile - nó cũng bao gồm các phương pháp Kanban và Lean không có Product Owner, timebox theo sprint, hoặc các cuộc họp. Các nguyên tắc cơ bản của tất cả phương pháp Agile vẫn đúng. Nhưng nếu hầu như đã quen thuộc với suy nghĩ về Agile, chúng ta sẽ cần phải suy nghĩ về Agile hơn và tìm hiểu về các phương pháp tiếp cận Agile khác để vượt qua kỳ thi.
    </h7>
  </div>
</div>

<br/>

{:#scrum}
# Scrum

Scrum là một mô hình Agile phổ biến, nhẹ nhàng và dễ hiểu - nhưng giống như tất cả phương pháp Agile rất khó để thành thạo. Phương pháp luận được ghi trong "Scrum framework" là một tập hợp các thực hành, vai trò, sự kiện, hiện vật (artifacts), và quy tắc được thiết kế để hướng dẫn nhóm thực hiện dự án.

{:#valueScrum}
## Các giá trị và Trụ cột Scrum

Lý thuyết đằng sau Scrum dựa trên ba trụ cột là Minh bạch, Kiểm tra và Thích ứng.

Các nguyên tắc này hướng dẫn tất cả các khía cạnh của phương pháp Scrum:

» **Transparency (Tính minh bạch)** : Điều này liên quan đến việc cung cấp tầm nhìn cho những người chịu trách nhiệm về kết quả. Một ví dụ về tính minh bạch sẽ tạo ra một định nghĩa chung về khái niệm "DEFINE OF DONE" (định nghĩa hoàn thành) là gì, để đảm bảo rằng tất cả các bên liên quan đều nhất trí.

» **Inspection (Kiểm tra)** : Điều này liên quan đến việc kiểm tra kịp thời xem dự án đang tiến triển như thế nào đối với mục tiêu của nó, tìm kiếm các sai lệch hoặc khác biệt có vấn đề so với các mục tiêu.

» **Adaptation (Thích ứng)** : Điều này liên quan đến việc điều chỉnh quy trình của nhóm để giảm thiểu các vấn đề tiếp theo nếu cuộc kiểm tra cho thấy có vấn đề hoặc xu hướng không mong muốn.

Ngoài ba trụ cột, Scrum cũng công nhận 5 giá trị cơ bản: TẬP TRUNG, CAN ĐẢM, CỞI MỞ, CAM KẾT và TÔN TRỌNG. Các giá trị này phản ánh các khái niệm được nêu trong Tuyên ngôn Agile và chúng cũng tương tự như các giá trị cốt lõi của XP (như chúng ta sẽ thấy khi tìm hiểu phương pháp đó.)

Quy trình Scrum được hiển thị trên sơ đồ dưới đây. Khi đọc tiếp tục về Scrum, hãy xem lại từng thành phần phù hợp với quy trình Scrum như thế nào.

![scrumProcess]({{ site.baseurl }}/assets/images/scrumProcess.png)

Trong phần này, chúng ta sẽ thảo luận về các điều khoản và thành  phần chính của Scrum, bao gồm các vai trò trong nhóm Scrum, các hoạt động xảy ra trong một sprint và các sản phẩm hoặc hiện vật của sprint. Chúng ta sẽ bắt đầu thỏa luận này bằng cách xem xét một khái niệm chính của Scrum - Sprint.

{:#sprint}
## SPRINT

Sprint là một vòng lặp thời gian (có giới hạn thời gian) kéo dài một tháng hoặc ít hơn, trong đó nhóm xây dựng một sản phẩm có khả năng phù hợp. (Thuật ngữ "SPRINT" trong Scrum tương đương với thuật ngữ "ITERATION - vòng lặp" trong agile tổng quan.). Hầu hết các sprints trong sprint kéo dài một hoặc hai tuần. Mỗi sprint giống như một dự án nhỏ. Trong một sprint, không có sự thay đổi nào được thực hiện có thể ảnh hưởng đến mục tiêu của sprint. Scope có thể được làm rõ hoặc bàn bạc lại khi có thông tin mới, nhưng nếu (ví dụ) phải thực hiện thay đổi đối với các thành viên của nhóm phát triển, thì điều đó sẽ không được thực hiện trong sprint.

Một sprint có thể bị hủy bỏ trước khi hết thời gian nếu mcụ tiêu sprint trở nên lỗi thời do thay đổi phương hướng kinh doanh hoặc điều kiện công nghệ. Tuy nhiên, chỉ Product Owner mới có thể hủy sprint. Khi điều đó xảy ra, các mục còn tồn đọng của sản phẩm chưa hoàn thành sẽ được estimate lại và trả về product backlogs (Tồn đọng của sản phẩm).

Trình tự các hoạt động của mỗi sprint bao gồm: kế hoạch sprint, giai đoạn phát triển bao gồm một bản tổng hợp hàng ngày, một cuộc họp đánh giá sprint và một cuộc họp Retrospectives (hồi tưởng) sprint.

{:#scrumRoles}
### Vai trò trong nhóm dự án Scrum

Scrum team được tạo thành bởi nhóm phát triển dự án, Product owner và Scrum Master. Hãy xem những vai trò ấy có trách nhiệm như thế nào trong dự án Scrum

**Nhóm phát triển dự án - Development Team**

Nhóm phát triển dự án là một nhóm những chuyên gia thực hiện xây dựng tiến triển của sản phẩm trong mỗi sprint. Các thành viên của nhóm phát triển tự tổ chức - có nghĩa là, họ được trao quyền để tự quản lý công việc.

Nhóm Scrum cũng đa chức năng (cross-functional); mỗi thành viên trong nhóm có thể hoàn thành nhiều hơn một trong các vai trò cần thiết để hoàn thành công việc (chẳng hạn như: phân tích, xây dựng, kiểm tra trong nhóm phát triển).

**Chủ sản phẩm - Product Owner**

Product owner có trách nhiệm tối đa hóa giá trị của sản phẩm bằng cách quản lý product backlog (tồn đọng sản phẩm), hoặc danh sách các công việc cần hoàn thành. Nó bao gồm cả việc đảm bảo các công việc trong backlog cần được cập nhật và đánh giá độ ưu tiên chính xác dự trên giá trị kinh doanh. Product owner cũng có trách nhiệm đảm bảo kinh doanh và nhóm Scrum có cùng sự chia sẻ hiểu biết về tầm nhìn của dự án, mục tiêu của dự án, và chi tiết các công việc cần hoàn thành, mà team cần phải lên kế hoạch và xây dựng đầu mục công việc.

Mặc dù, Product owner có quyền hạn tuyệt đối trong việc đánh giá độ ưu tiên và cập nhật backlog, nhưng Scrum Master và nhóm dự án cũng sẽ tham gia vào quy trình này với mục đích là cung cấp thông tin về ước tính, phụ thuộc, các kỹ thuật trong công việc, etc.

**Srum Master**

Scrum master có trách nhiệm đảm bảo rằng phương pháp Scrum được hiểu và sử dụng hiệu quả. Người này là lãnh đạo phục vụ cho nhóm dự án, loại bỏ các trở ngại ra khỏi quy trình của họ, điều phối các sự kiện (các cuộc họp - meetings), và giáo dục thành viên nhóm.

Scrum Master cũng tham gia cùng với Product Owner trong việc quản lý backlog và giao tiếp về tầm nhìn của dự án, mục tiêu dự án, và chi tiết các công việc trong backlog.

Cuối cùng, Scrum Master phục vụ tổ chức bằng cách điều phối tổ chức cùng thích nghi với Scrum, không chỉ một dự án, mà mở rộng ra toàn bộ tổ chức.

{:#scrumActivities}
### Các hoạt động Scrum (Sự kiện, lễ hội)

Phương thức Scrum định nghĩa ra 5 hoạt động meeting trực tiếp tập trung vào những mục đích cụ thể. Chúng bao gồm refinement (sàng lọc) backlog, meeting lên kế hoạch cho sprint, meeting hàng ngày, sprint reviews, và sprint retrospectives. Bốn meetings cuối là cơ hội cho nhóm Scrum có thể kiểm tra và thích ứng (2 trong số 3 trụ cột) với mỗi sprint.


<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Trong bài kiểm tra, có thể chúng ta sẽ thấy Scrum events, hoặc Scrume ceremonies.
    </h7>
    <h7>Chúng ta những khái niệm cũ của Scrum activities (meetings)</h7>
  </div>
</div>

<br/>

**Backlog refinement - Sàng lọc backlog**

Meeting sàng lọc backlog là nơi "groming the backlog" (xử lý các công việc tồn đọng) được hoàn thành. Nó có nghĩa cơ bản là mọi người cùng tham gia trong dự án cùng thảo luận và cập nhật những đầu mục trong backlog. (Nếu không chắc về ý nghĩa của nó, cứ đọc tiếp - chúng ta sẽ giải thích hoạt động này kỹ càng hơn khi miêu tả về product backlog.)

**Sprint planning meeting - Meeting lên kế hoạch cho sprint**

Trong cuộc họp kế hoạch sprint, mọi người cùng xác định cái gì sẽ được phân phối trong sprint sắp tới và làm thế nào để đạt được kết quả. Product owner đưa ra cập nhật cho các mục trong backlog, và nhóm sẽ thảo luận cùng nhau để đảm bảo có cùng một chia sẻ hiểu biết. Nhóm phát triển dự án dự đoán cái gì có thể phân phối được trong sprint, dựa trên ươc tính của họ, công suất dự kiến (projected capacity) và hiệu quả trong quá khứ. Với những dự án đoán của họ, họ định nghĩa ra là mục tiêu của sprint (sprint goal). Nhóm phát triển dự án sẽ xác định chức năng nào họ sẽ xây dựng và bằng cách nào họ sẽ tự tổ chức để phân phối được mục tiêu của sprint. (Sprint planning - hay iteration planning - được bao phủ đầy đủ trong chương 5)

**Daily Scrum - Meeting hàng ngày**

Meeting hàng ngày được gói gọn trong đúng 15 phút, được tổ chức cùng một thời điểm và địa điểm mỗi ngày, trong khi nhóm làm việc để hoàn thành mục tiêu sprint. Scrum master đảm bảo cuộc họp được diễn ra hàng ngày, và theo dõi chướng ngại vật bất thường. Daily meeting chủ yếu là để thành viên của nhóm phát triển dự án cùng đồng bộ công việc của họ và báo cáo bất cứ bất thường nào đang gặp phải. Phạm vi của cuộc họp này tuyệt đối nghiêm ngặt - mỗi thành viên phải trả lời đúng 3 câu hỏi vể cái họ đang làm trong mục tiêu sprint:

1. Cái gì đã hoàn thành kể từ cuộc họp hàng ngày hôm qua?
2. Kế hoạch sẽ thực hiện trong hôm nay?
3. Có vấn đề trở ngại gì trong tiến độ không?

Ba câu hỏi này giúp mỗi thành viên của nhóm phát triển đánh giá tiến độ để đạt được mục tiêu sprint. Trong câu trả lời các câu hỏi, họ cùng nhau liên kết và thảo luận hay giải quyết vấn đề trực tiếp với nhau. (Chúng ta sẽ bao phủ cuộc họp này chi tiết hơn trong chương 5, nơi chúng ta nói về đứng họp hằng ngày - trong agile gọi chung là Daily Scrum.)

Như những dự án Scrum lớn hơn, nhiều nhóm Scrum có thể cần làm việc với nhau. Để làm được việc ấy, họ hay có một cách tiếp cận phổ biến gọi là "Scrum of Scrums". Như cái tên gọi của nó, đây là một cuộc họp trong mỗi đại diện từ mỗi team sẽ báo cáo tiến độ của mỗi nhóm. Chỉ giống như cuộc họp hàng ngày bình thường, những người tham gia trả lời 3 câu hỏi, và họ có thể trả lời thêm câu hỏi thứ tư để giúp đối mặt với xung đột tiềm ẩn giữa các nhóm: **Bạn có làm cái gì đó có ảnh hưởng đến nhóm khác không? Are you about to put something in another team’s way?**

Quy trình này được biểu diễn bên dưới:

![scrumofScrums]({{ site.baseurl }}/assets/images/scrumofScrums.png)

Cũng như daily scrums, cuộc họp Scrum of Scrums diễn ra theo lịch bình thường, nhưng không cần thiết phải hàng ngày. Hãy để mỗi team họp với nhau hằng ngày vào 9h sáng. Sau cuộc họp đó, lúc 9h30 - có thể hàng ngày hoặc hai lần một tuần, nếu cần thiết - người đại diện của mỗi team sẽ tham gia vào cuộc họp Scrum of Scrums. Nếu những người tham gia tiếp thu được bất cứ vấn đề nào ảnh hưởng đến nhóm của họ, họ sẽ báo cáo chúng ngay lập tức cho nhóm của họ sau cuộc họp.

Nếu lớn hơn nữa thì thậm chí có thể tổ chức đến "scrum of scrum of scrums" nơi mà các nhóm sẽ lặp lại kiểu mẫu với ba tầng họp. Ở đây, đại diện từ mỗi scrum of scrums sẽ tham gia một cuộc họp "scrum of scrum of scrums" để điều phối công việc trong một nhóm dự án lớn.

![scrumofscrumofscrums]({{ site.baseurl }}/assets/images/scrumofscrumofscrums.png)

**Sprint review - đánh giá sprint**

Cuộc họp đánh giá sprint được tổ chức tại thời điểm kết thúc sprint và bao gồm nhóm phát triển dự án, Product owner và Scrum Master (và cũng có thể có sự tham gia của stakeholder khác). Trong cuộc họp này, nhóm demo những tiến triển, hoặc sản phẩm đang phát triển mà đã được họ xây dựng được trong sprint cho Product owner. Product owner sẽ thanh tra công việc để xem cái gì được chấp nhận - từ chối nếu nó "DONE" hoặc giải thích cái gì đang thiếu sót.

Nhóm phát triển và Product Owner thảo luận về tiến triển và những đầu mục còn lại trong product backlog. Cùng nhau, họ tạo những thay đổi cần thiết trong backlog và quyết định cái gì cần được làm tiếp theo.

**Sprint retrospectives - hồi tưởng sprint**

Sau đánh giá sprint, nhưng trước khi bắt đầu cuộc họp lên kế hoạch cho sprint mới, nhóm phát triển dự án tổ chức hoạt động cuối cùng của họ để "thanh tra và thích ứng" cho sprint vừa rồi - gọi là sprint retrospective. Mặc dù những người khác có thể được mời để tham gia, cuộc họp này chủ yếu dành cho nhóm phát triển.

Đây là cơ hội để học hỏi và nhìn thấy những điểm cần cải thiện. Thời gian của cuộc họp này - sau cuộc họp đánh giá sprint, nhưng trước cuộc họp lên kế hoạch sprint - cho phép họ xem xét lại những phản hồi của Product Owner từ cuộc họp đánh giá sprint trong sự cân nhắc của họ, và cũng vạch ra những cải thiện họ xác định trong suốt quá trình hồi tưởng để lên kế hoạch cho srint tiếp theo.

Kết quả phản chiếu trong toàn bộ cuộc họp retro có thể bao phủ bất cứ những gì xảy ra trong toàn bộ sprint, bao gồm cả khía cạnh con người, quy trình và sản phẩm. Thành viên của nhóm trình bày cái gì tốt, xem xét cơ hội cải thiện, và quyết định cái gì thay đổi để thực thi trong sprint tiếp theo.

{:#scrumArtifact}
### Scrum artifacts - Hiện vật Scrum

Chúng ta đã cùng thảo luận về các vai trò và hoạt động trong Scrum, giờ chúng ta sẽ chuyển sang các hiện vật Scrum.

Có ba mục hữu hình được cung cấp hay sử dụng bởi nhóm trong suốt sprint - product increment (tăng trưởng sản phẩm), product backlog (tồn đọng sản phẩm) và sprint backlog (tồn đọng sprint).

**Product increment - tăng trưởng sản phẩm**

Trong mỗi sprint, thành viên của nhóm phát triển xây dựng sự gia tăng của giải pháp (điểm kết thúc sản phẩm của dự án). Như chúng ta đã thấy, trong sprint review, họ sẽ demo bản tăng trưởng cuối cùng để nhận phản hồi từ Product owner và lọc ra những mục đã hoàn thành. Để tối đa hóa cơ hội sự tăng trưởng sản phẩm được chấp nhận, nhóm và Product owner cần phải cùng đồng ý một định nghĩa hoàn thành DEFINE OF DONE trước khi nhóm bắt đầu làm việc, điều này phải được chia sẽ hiểu biết chung giữa các thành viên về cái gì cần hoàn thành và sẽ được phản ánh vào sự tăng trưởng đó.

**Product backlog - tồn đọng sản phẩm**

Product backlog là một danh sách đã được đánh độ ưu tiên của toàn bộ công việc cần phải hoàn thành để xây dựng sản phẩm - nó phục vụ như là một nguồn cho toàn bộ yêu cầu của sản phẩm. Những mục trong backlog có thể bao gồm những đặc tính cần phải xây dựng, chức năng, yêu cầu, thuộc tính chất lượng (ví dụ yêu cầu phi chức năng), những sự tăng cường và những sửa lỗi. Danh sách này là động, nó tiến triển theo sự tiến triển của sản phẩm và cần phải cập nhật thường xuyên.

Các mục trong backlog thì được đánh độ ưu tiên bởi Product owner và sắp xếp theo thứ tự ưu tiên cao nhất ở đầu tiên trên backlog. Nhóm sẽ luôn cố gắng làm việc trong mục nằm đầu tiên về độ ưu tiên tiếp theo - hoặc sớm nhất có thể, các phụ thuộc đã đưa ra và các yếu tố khác. Các hạng mục công việc được tinh chỉnh dần dần khi chúng sắp được hoàn thiện, vì vậy, các hạng mục có mức độ ưu tiên cao nhất là chi tiết nhất và ước tính của nhóm cho các hạng mục đó chính xác hơn. Các hạng mục có mức độ ưu tiên thấp nhất có thể không được phát triển, vì chúng có thể liên tục bị trì hoãn để có lợi cho công việc có mức độ ưu tiên cao hơn.

Backlog thì liên tục được tinh chỉnh, và quy trình của việc thêm hạng mục chi tiết vào backlog, và tinh chỉnh những ước tính của chúng là sàng lọc backlog. Hoạt động Scrum được mô tả trước đó, còn được gọi là "tinh chỉnh công việc tồn đọng". Hoạt động này được hoàn thành bởi team phát triển và product owner làm việc cùng với nhau. Nhóm ước tính các hạng mục công việc, và product owner đánh độ ưu tiên của nó. Ví dụ, mỗi thời gian nhóm tinh chỉnh ước tính của họ với mức cao của chi tiết, product owner cũng cần điều chỉnh mức độ ưu tiên của những hạng mục trong backlog.

**Sprint backlog: Tồn đọng sprint**

Sprint backlog là một tập hợp con của các hạng mục trong product backlog mà được chọn lựa trong mục tiêu của sprint (sprint backlog không phỉa là một danh sách riêng biệt với product backlog). Cùng với sprint backlog, nhóm phát triển một kế hoạch về cách họ sẽ đạt được mục tiêu của sprint - đây là cam kết của họ về chức năng mà họ sẽ cung cấp trong sprint. Sprint tồn đọng đóng vai trò như một cái nhìn dễ thấy về công việc đang được thực hiện và chỉ có thể được cập nhật bởi nhóm phát triển.

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập: Quyền sở hữu và trách nhiệm Scrum</h5>

  <p>Trong bảng dưới đây, đánh dấu check vào cột thích hợp cho development team, hay Scrum Master hay Product owner để đánh giá ai chủ sở hữu hay chịu trách nhiệm cho mỗi mục.</p>
</div>

|Item - hạng mục| Development team | Product owner | Scrum master |
|-----|-----|-----|-----|
| Estimates - ước tính  | ✔  |   |   |
| Backlog priorities - đánh độ ưu tiên  |   |  ✔ |   |
| Agile coaching - đào tạo agile  |   |   |  ✔ |
| Coordination of work - Phối hợp làm việc  | ✔  |   |   |
| The definition of DONE - định nghĩa hoàn thành  | ✔  | ✔  | ✔  |
| Process adherence - Tuân thủ quy trình  |   |   | ✔  |
| Technical decisions - quyết định công nghệ  | ✔  |   |   |
| Sprint planning - lên kế hoạch sprint  | ✔  | ✔  | ✔  |

ĐÁP ÁN:

![scrumOwner]({{ site.baseurl }}/assets/images/scrumOwner.png)


{:#xp}
# EXTREME PROGRAMMING (XP)

Lập trình cực đại - được gọi với tên ngắn gọn là XP dựa trên cơ sở của eXtreme Programming - là một phương pháp Agile tập trung vào phát triển phần mềm. Trong khi Scrum tập trung vào quản lý dự án ở mức độ ưu tiên công việc và nhận phản hồi, thì XP tập trung vào thực hành tốt nhất để phát triển phần mềm. Vì vậy, sẽ có rất nhiều tài liệu tham khảo phần mềm trong thảo luận sau. Đối với các giá trị và nguyên tắc của Tuyên ngôn Agile, như chúng ta đã tìm hiểu trong phần trước, hãy xem liệu có thể nghĩ ra những cách mà các giá trị và thực hành của XP có thể ứng dụng cho các loại dự án công việc tri thức hay không.

{:#xpCoreValue}
## Giá trị cốt lõi của XP

Giá trị cốt lõi của XP là đơn giản, giao tiếp, phản hồi, can đảm và tôn trọng; những giá trị này tự thể hiện trong các hoạt động được thực hiện trong suốt vòng đời XP.

» **Simplicity - Đơn giản** : Giá trị này tập trung cào sự giảm thiểu phức tạp, các tính năng bổ sung, và lãng phí. Nhóm XP luôn ghi nhớ cụm từ "Tìm điều đơn giản nhất có thể hoạt động" và xây dựng giải pháp đó trước.

» **Communication - Giao tiếp** : Giá trị này tập trung vào việc đảm bảo toàn bộ nhóm dự án biết kỳ vọng của họ và cái gì người khác đang thực hiện. Ví dụ, cuộc họp đứng mỗi ngày là một công cụ giao tiếp chính (những cuộc họp này được miêu tả chi tiết trong chương 5)

» **Feedback - Phản hồi** : Nhóm dự án nên nhận ra sự phù hợp sớm. Thất bại sớm có thể hữu ích, đặc biệt nếu trong khi làm, chúng ta lấy được thông tin mới trong khi chúng ta vẫn có thời gian để cải thiện sản phẩm.

» **Courage - Can đảm** : Cần có sự can đảm mới có thể cho phép công việc của chúng ta được nhìn thấy bởi người khác. Trong lập trình cặp (pair programming), thành viên nhóm dự án chia sẽ mã nguồn với nhau và thường cần phải làm cho nó đơn giản. Được hỗ trợ bơi các bản dựng tự động và unit test, các nhà phát triển cần có sự tự tin để thực hiện các thay đổi quan trọng.

» **Respect - Tôn trọng** : Sự tôn trọng là điều cần thiết trong các dự án XP, nơi mọi người làm việc cùng nhau như một nhóm và mọi người đều phải chịu trách nhiệm về sự thành công hay thất bại của dự án. Giá trị này cũng liên quan đến pair programming; các thành viên trong nhóm cần nhận ra rằng mọi người làm việc là khác nhau và tôn trọng những khác biệt đó.

Hình dưới đây minh họa quy trình XP. Nếu một số thuật ngữ trên sơ này là tiếng Hy lạp đối với chúng ta; chúng ta sẽ xem xét lại các thuật ngữ kỹ thuật được sử dụng trong sơ đồ này và trong phần thảo luận về XP sẽ chi tiết hơn trong chương sau.

![xpprocess]({{ site.baseurl }}/assets/images/xpprocess.png)

Như thể hiện trong mô hình, nhóm dự án XP sử dụng yêu cầu nhẹ nhàng gọi là "User stories" để lên kế hoạch cho hoàn thành sản phẩm và các vòng lặp. Các lần lặp lại thường kéo dài hai tuần và các nhà phát triển làm việc theo cặp để viết mã trong các lần lặp này. Tất cả các phần mềm được phát triển đều qua quá trình kiểm tra nghiêm ngặt và thường xuyên. Sau đó, khi được khách hàng phê duyệt, phần mềm được phân phối dưới dạng các bản phát hành nhỏ.

"Spikes" (Nhịp đập) là những khoảng thời gian làm việc được thực hiện để giảm thiểu các mối đe dọa và vấn đề, các "Nhịp kiến trúc" là những lần lặp lại được sử dụng để chứng minh một cách tiếp cận công nghệ. Sự đột biến được kết hợp vào các quy trình lập kế hoạch phát hành.


{:#XPRoles}
## Các vai trò trong nhóm XP

XP định nghĩa các vai trò trong nhóm khác so với Scrum - Vai trò trong XP là Coach (Huấn luyện viên), khách hàng, lập trình viên và tester. Hãy xem mỗi vai trò tham gia trong dự án XP.

**Coach - huấn luyện viên**

Huấn luyện viên như là một người hướng dẫn cho nhóm, giới thiệu về quy trình và giúp cho thành viên của nhóm giữ vững lộ trình. Huấn luyện viên cũng là người điều phối - giúp nhóm trở nên hiệu quả hơn - và là một ống dẫn, tăng cường giao tiếp cả trong nhóm và giữa các nhóm với nhau. Vai trò này chia sẻ nhiều trách nhiệm với Scrum Master. Mặc dù định nghĩa chính thức của hai nhiệm vụ này khác nhau, nhưng chúng thường được dùng thay thế cho nhau.

Hơn nữa với vai trò huấn luyện, cũng là người quản lý, điều phối giao tiếp nội bộ và các hoạt động của nhóm, nhưng đây không phải là vai trò chính thức của XP.

**Customer - khách hàng**

Trong một nhóm XP, khách hàng là người đại diện doanh nghiệp cung cấp các yêu cầu, độ ưu tiên và điều hướng kinh doanh. Người này định nghĩa sản phẩm được sẽ xây dựng, xác định độ ưu tiên của các tính năngm và xác nhận rằng sản phẩm đang làm hoạt động đúng hay không. Vai trò này cũng tương tự như Product owner trong Scrum.

**Programmer - Lập trình viên**

Lập trình viên là những nhà phát triển trực tiếp xây dựng sản phẩm bằng cách viết và thực thi mã nguồn theo yêu cầu User stories.

**Tester - Nhà kiểm thử**

Tester cung cấp đảm bảo chất lượng và giúp khách hàng định nghĩa và viết những bài kiểm thử độ hài lòng cho user stories. Vai trò này cũng có thể được điền vào vị trí của Programmer nếu họ có yêu cầu kỹ năng.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Suy nghĩ về vai trò của nhóm dự án XP và Scrum - chúng ta có thể gặp một vài câu hỏi yêu cầu tái cơ cấu phương pháp dựa trên những yếu tố đang được sử dụng. Chúng ta cũng nên hiểu rằng quan điểm Agile, Product owner và Customer là những vai trò gần như tương đương, cũng như Scrum Master và Coach.
    </h7>
  </div>
</div>

<br/>


{:#corepractices}
## Các thực hành cốt lõi XP

Phương pháp XP dựa trên 13 phương pháp cốt lõi đơn giản nhưng mạnh mẽ, như được hiển thị bên dưới. Chúng ta xẽ xem xét từng phương pháp này chi tiết hơn, bắt đầu từ vòng ngoài.

![xpcore]({{ site.baseurl }}/assets/images/xpcore.png)

**Whole Team - Toàn nhóm**

Thực hành whole team là một ý tưởng mà toàn bộ mọi người đóng góp cho dự án XP ngồi cùng nhau ở cùng một vị trí, với tư cách là các thành viên của một nhóm duy nhất. XP nhấn mạnh khái niệm tổng quát hóa các chuyên gia, trái ngược với các chuyên gia riêng biệt. Nói cách khác, bất kỳ ai đủ điều kiện để thực hiện một vai trò đều có thể đảm nhận - vai trò này không dành riêng cho những người chuyên về một lĩnh vực cụ thể. Thực hành này giúp tối ưu hóa việc sử dụng các nguồn lực vì những người có thể thực hiện nhiều công việc có thể chuyển từ vai trò này sang vai trò khác khi nhu cầu phát sinh. Phương pháp này cũng cho phép chia sẻ thông tin hiệu quả hơn và giúp loại bỏ khả năng những người ở một số vai trò nhất định sẽ nhàn rỗi hoặc làm việc quá sức tại một số thời điểm nhất định trong dự án.

**Planning Games - Trò chơi kế hoạch**

XP có hai hoạt động kế hoạch hay là trò chơi kế hoạch cơ sở - đó là kế hoạch phát hành và kế hoạch lặp.

Phát hành là việc đẩy chức năng mới lên sản phẩm người dùng. Một dự án bình thường có một hoặc nhiều phát hành, với không nhiều hơn một hay hai phát hành trong một năm đơn lẻ. Trong kế hoạch phát hành, khách hàng phát thảo những yêu cầu chức năng, và các nhà phát triển ước tính độ khó của chức năng sẽ xây dựng. Đối với những ước tính này và độ ưu tiên, khách hàng thiết kế kế hoạch cho việc phân phối dự án. Kể từ những nỗ lực ban đầu ở ước tính sẽ không chính xác, quy trình này sẽ được xem xét lại thường xuyên và cải thiện như độ ưu tiên và ước tính tiến triển.

Các vòng lặp là một vòng tròn phát triển ngắn với một phát hành mà Scrum gọi là sprint. Kế hoạch vòng lặp hoàn thành ở bắt đầu mỗi vòng lặp. Khách hàng giải thích các chức năng họ muốn thấy trong vòng lặp tiếp theo, và rồi nhóm phát triển sẽ chia nhỏ những chức năng này thành các nhiệm vụ và ước tính công việc. Dựa trên những ước tính đó (cái mà được tinh chỉnh nhiều hơn so với ước tính kế hoạch phát hành) và tổng công việc đã hoàn thành trong vòng lặp trước, nhóm cam kết những danh mục công việc họ nghĩ sẽ có thể hoàn thành trong giai đoạn 2 tuần.

**Small release - phát hành nhỏ**

Thường xuyên, phát hành nhỏ vào môi trường kiểm thử được khuyến khích trong XP, bao gồm cả ở hai giai đoạn lặp lại, đến tiến trình demo, gia tăng hiển thị cho khách hàng, và tại giai đoạn phát hành, nhanh chóng triển khai phần mềm làm việc đến người dùng cuối. Chất lượng được bảo trì trong những khung thời gian phân phối ngắn bởi những kiểm thử nghiêm ngặt và đi qua những bài thực hành như kết hợp liên tục (continuous integration), trong các trường hợp kiểm thử chạy liên tục có thể.

**Customer Tests - khách hàng kiểm thử**

Một phần của xác định chức năng yêu cầu, khách hàng mô tả một hoặc nhiều tiêu chí kiểm thử mà sẽ được chỉ thị cho phần mềm hoạt động đúng dự tính. Nhóm rồi sẽ xây dựng kiểm thử tự động để chứng minh chúng đúng với tiêu chí của khách hàng đặt ra.

**Collective Code Ownership - Quyền sở hữu mã nguồn tập thể**

Trong XP, bất cứ cặp phát triển nào cũng có thể cải thiện và sửa đổi bất cứ mã nguồn nào. Có nghĩa là nhiều người sẽ cùng làm việc với toàn bộ mã nguồn, kết quả sẽ được tăng lên một cách hữu ích và kiến thức được mở rộng ra. Thực hành này dẫn dắt chất lượng dự án tăng lên múc độ cao hơn; với nhiều người cùng xem mã nguồn, có nhiều cơ hội hơn để phát hiện ra bất thường. Ảnh hưởng cũng sẽ tác động ít hơn nếu có bất cứ lập trình viên nào rời đi, kể từ khi kiến thức của người đấy đã được chia sẻ.

**Code standards - Tiêu chuẩn mã nguồn**

Mặc dù quyền sở hữu mã nguồn tập thể có nhiều lợi điểm của nó, cho phép bất kỳ ai sửa đổi mã nguồn có thể là kết quả là một vấn đề nếu các thành viên trong nhóm có cách tiếp cận khác nhau trong mã nguồn. Để giải quyết vấn đề này, nhóm dự án XP cùng tuân thủ theo một chuẩn mực mã nguồn thích hợp mà toàn bộ mã nguồn trông giống như chỉ một người lập trình viên có kiến thức đã viết. Tiêu chuẩn riêng biệt của mỗi team sử dụng không quan trọng; chỉ cần là nhóm có thể có cách tiếp cận thích hợp để viết mã nguồn.

**Sustainable Pace - Bước đi bền vững**

XP nhận ra rằng mức năng suất cao nhất do một nhóm hoạt động với tốc độ bền vững đạt được. Mặc dù thời gian làm thêm giờ có thể là cần htiết, nhưng thời gian làm việc lặp đi lặp lại không bền vững và phản tác dụng. Việc duy trì tốc độ phát triển bền vững sẽ tối ưu hóa việc mang lại giá trị lâu dài.

**Metaphor - Phép ẩn dụ**

XP sử dụng phép ẩn dụ và tương tự để trình bày thiết kế và tạo ra tầm nhìn công nghệ chung. Những miêu tả này thiết lập sự so sánh rằng toàn bộ những người liên quan có thể hiểu để trình bày hệ thống vận hành như thế nào. Ví dụ, "module thanh toán giống như một kế toán viên đảm bảo các giao dịch được nhập vào, các tài khoản và số dự thích hợp sẽ được tạo ra".

Cho dù nếu nhóm không thể tiếp cận với cách ẩn dụng để miêu tả vài thứ, họ có thể sử dụng tập những tên phổ biến để sử dụng cho những thành phần khác nhau để đảm bảo rằng mọi người hiểu ở đâu và tại sao những thay đổi nên được áp dụng.

**Continuous Integration - Tích hợp liên tục**

Tích hợp bao gồm mang mã nguồn kết hợp với nhau để đảm bảo rằng nó có thể thực thi và hoạt động được. Thực hành này là tiêu chí, bởi vì nó mang nhiều mặt vấn đề trước khi nhiều mã nguồn được xây dựng trên các lỗi và thiết kế không tương thích.

XP sử dụng tích hợp liên tục, có nghĩa là mọi lúc mà lập trình viên kiểm tra mã nguồn để đưa lên kho mã nguồn (thường là vài lần trong ngày), kiểm thử tích hợp sẽ tự động chạy. Như những bài kiểm thử nổi bật được những bản dựng bị hỏng hoặc các vấn đề tích hợp, để các vấn đề có thể được giải quyết ngay lập tức.

**Test-Driven Development - Phát triển định hướng kiểm thử**

Kiểm thử là một phần tiêu chí của phương pháp XP. Để đảm bảo sự bao phủ các kiểm thử tốt để các vấn đề có thể được làm nổi bật sớm trong quá trình phát triển, nhóm phát triển XP thường sử dụng thực hành của Phát triển định hướng kiểm thử. Với cách tiếp cận này, nhóm viết kiểm thử được chấp nhận trước khi phát triển mã nguồn mới.

Nếu các bài kiểm thử hoạt động đúng, mã nguồn ban đầu sẽ làm thất bại bài kiểm thử, từ khi chức năng yêu cầu chưa được phát triển. Mã nguồn sẽ được thông qua bài test khi nó được viết chính xác. Quy trình phát triển định hưởng kiểm thử cố gắng rút ngắn chu kỳ kiểm tra - phản hồi nhiều nhất có thể để nhận được lợi ích của phản hồi sớm.

**Refactoring - Sự tái cấu trúc**

Sự tái cấu trúc là quy trình cải thiện thiết kế của mã nguồn đã tồn tại mà không làm thay đổi hành vi bên ngoài của nó hay thêm chức năng mới. Bằng việc giữ cho thiết kế hiệu quả, sự thay đổi và chức năng mới có thể dễ dàng được áp dụng vào mã nguồn. Sự tái cấu trúc tập trung vào việc gỡ bỏ những trùng lặp mã nguồn, hạ thấp các mối nối liên kết (kết nối phụ thuộc giữa các modules), và tăng cường sự gắn kết.

**Simple design - Thiết kế đơn giản**

Bằng việc giữ cho thiết kế đơn giản nhưng vẫn thích nghi, nhóm XP có thể phát triển nhanh và thích nghi nếu cần thiết. Thiết kế được giữ phù hợp cho những gì dự án đang yêu cầu. Nó có thể được xem xét lại, lặp lại nhiều lần và cải thiện để đảm bảo nó còn lại những phần phù hợp.

XP tuân theo một triết lý thiết kế có chủ định: "What is the simplest thing that could work? - Cái gì đơn giản nhất thì có thể hoạt động được". trái ngược với các cấu trúc phức tạp đáp ứng tính linh hoạt có thể trong tương lai. Vì sự cồng kềnh và phức tạp của mã nguồn liên quan đến nhiều những dự án thất bại, thiết kế đơn giản cũng là một chiến lược giảm thiểu rủi ro.

**Pair Programming - Lập trình cặp**

Trong XP, mã nguồn sản phẩm được viết bởi hai nhà phát triển làm việc cặp với nhau. Trong khi một người viết mã nguồn, người còn lại sẽ đánh giá nó - và cả hai thay đổi vai trò liên tục. Thực hành này có thể bị xem là không hiệu quả, nhưng XP khẳng định rằng nó tiết kiệm thời gian, bởi vì cặp đôi làm việc chung với nhau sẽ tìm ra vấn đề sớm và lợi ích là cả hai sẽ mở rộng được kiến thức nền tảng. Làm việc theo cặp cũng giúp chênh lệch kiến thức về hệ thống trong team giảm đi.

Bằng cách tiếp cận có kỷ luật và nghiêm ngặt để áp dụng các phương pháp này, nhóm XP đã thành công trong việc cung cấp các hệ thồng phần mềm chất lượng cao.

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập - XP CHUNK (thực tế) or MADE-UP JUNK (rác)</h5>

  <p>Tách biệt các khái niệm và thực hành XP thực tế (XP CHUNKS) với MADE-UP JUNK trong bảng sau bằng cách đánh dấu vào cột thích hợp.</p>

  <br/>
  <img src="/assets/images/chunkjunk.png" alt="chunkjunk">

</div>

{:#leanProduct}
# LEAN PRODUCT

Nói một cách chính xác, LEAN không phải là một phương pháp Agile; tuy nhiên, cách tiếp cận LEAN được liên kết chặt chẽ với Agile, như chúng ta sẽ thấy. LEAN bắt nguồn từ hệ thống sản xuất Toyota được phát triển để cải tiến hệ thống sản xuất hàng loạt của Henry Ford để chế tạo ô tô. Vì vậy, Lean bắt đầu như một phương pháp sản xuất, sau đó được áp dụng cho phát triển phần mềm và cuối cùng được điều chỉnh cho các loại công việc kiến thức khác.

Khi đề cập đến Lean trong bối cảnh Agile, chúng ta thực sự đang nói về một tập hợp con của Lean được gọi là "Lean production development - sự phát triển sản phẩm tinh gọn". Trong khi các hệ thống sản xuất tinh gọn ban đầu xử lý các sản phẩm sản xuất, thì việc phát triển sản phẩm tinh gọn liên qua nđến việc phát triển các sản phẩm mới và tốt hơn. Các nguyên tắc cấp cao của phát triển sản phẩm tinh gọn bao gồm:

» Sử dụng các công cụ quản lý trực quan.

» Xác định giá trị định nghĩa bởi khách hàng.

» Xây dựng trong học hỏi và không ngừng cải thiện.

<div id="backgroundInfo" style="font-size: 12px;">
  <h5>Thông tin ẩn sau</h5>

  <hr/>

  <h6>Tại sao Agile và Lean lại liên quan đến nhau?</h6>

  <p>Các nguyên tắc Lean mức độ cao được liệt kê trên là chung cho Kanban và tất cả phương pháp Agile. Mặc dù các ý kiến khác nhau, nhưng có thể thấy Lean là một tập hợp các phương pháp Agile và Kanban. Từ quan điểm này, phát triển sản phẩm tinh gọn, Kanban và các phương pháp Agile đều là những thể hiện chuyên biệt của tư duy tinh gọn.</p>

  <p>
  Chúng là những nhánh bắt đầu với các nguyên tắc chung của Lean và bổ sung thêm hướng dẫn cho các lĩnh vực cụ thể của chúng. Mặc dù quan điểm này sẽ không được kiểm tra trong kỳ thi, nhưng có có thể giúp chúng ta hiểu mối quan hệ giữa các Lean và các phương pháp Agile, Kanban.
  </p>

  <img src="/assets/images/leanandagile.png" alt="leanandagile">
</div>

{:#coreConcepts}
## Những khái niệm cốt lõi của LEAN

Lean có tập trung vào 7 khái niệm cốt lõi như hình bên dưới:

![leancoreconcepts]({{ site.baseurl }}/assets/images/leancoreconcepts.png)

Hãy cùng xem xét 7 khái niệm cốt lõi chi tiết hơn:

» **Eliminate waste - Loại bỏ lãng phí**: Để tối ưu hóa giá trị, chúng ta cần tối thiểu hóa lãng phí. Trong công việc tri thức, lãng phí có thể ở dạng công việc được hoàn thành một phần, sự chậm trễ, quá trình xử lý, các tính năng không cần thiết, v.v. Do đó, để tăng giá trị mà chúng ta nhận được từ các dự án, chúng ta phải phát triển các cách để xác định và rồi loại bỏ chúng, sự lãng phí.


» **Empower the team - Trao quyền lực cho nhóm**: Thay vì áp dụng phương pháp quản lý vi mô, chúng ta nên tôn trọng kiến thức vượt trội của các thành viên trong nhóm về các bước kỹ thuật cần thiết trong dự án và để họ đưa ra các quyết định nội bộ sao cho công việc hiệu quả và thành công.

» **Deliver fast - Phân phối nhanh** : Chúng ta có thể tối đa hóa lợi tức đầu tư (ROI - return on investment) của dự án bằng cách nhanh chóng sản xuất các sản phẩm có giá trị và lặp lại thông qua thiết kế. Chúng ta sẽ tìm ra giải pháp tốt nhất thông qua sự phát triển nhanh chóng của các tùy chọn.

» **Optimize the whole - Tối ưu hóa tổng thể** : Chúng ta hướng tới việc xem hệ thống không chỉ là tổng thể các bộ phận của nó. Chúng ta vượt ra ngoài các phần của dự án và tìm cách điều chỉnh nó phù hợp với tổ chức. Là một phần của việc tối ưu hóa tổng thể, chúng ta cũng tập trung vào việc hình thành các mối quan hệ giữa các nhóm tốt hơn.

» **Build quality in - Xây dựng chất lượng** : Phát triển tinh gọn (lean) không cố gắng test chất lượng ở cuối cùng; thay vào đó, chúng ta xây dựng chất lượng vào sản phẩm và liên tục đảm bảo chất lượng trong suốt quá trình phát triển, sử dụng các kỹ thuật như tái cấu trúc, tích hợp liên tục và unit test.

» **Defer desicions - Trì hoãn quyết định** : Chúng ta cân bằng giữa việc lập kế hoạch sớm với việc đứa ra quyết định và cam kết càng muộn càng tốt. Ví dụ: Điều này có thể có nghĩa là ưu tiên công việc tồn đọng cho đến khi đến lúc thực hiện công việc hoặc tránh bị ràng buộc vào một giải pháp có giới hạn công nghệ ban đầu.

» **Amplify learning - Khuếch đại học tập** : Khái niệm này liên quan đến việc tạo điều kiện giao tiếp sớm và thường xuyênm nhận phản hồi càng sớm càng tốt và xây dựng dựa trên những gì chúng ta học được. Vì các dự án công việc tri thức là kinh nghiệm học tập kinh doanh và công nghệ, chúng ta bắt đầu học sớm và tiếp tục học hỏi.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Đề thi có thể trực tiếp hay gián tiếp hỏi về bảy khái niệm cốt lõi này. Tuy nhiên, ta nên biết rằng những ý tưởng này đã được truyền đạt theo nhiều cách khác nhau. Điều này có nghĩa là ta không thể chỉ ghi nhớ 7 cụm từ được liệt kê ở trên; ta phải hiểu những khái niệm này đủ tốt để nhẫn ra chúng ngay cả khi chúng được diễn đạt hơi khác một chút.
    </h7>
  </div>
</div>

<br/>

{:#7wastes}
## Bảy lãng phí trong LEAN

Mặc dù điều quan trọng là phải hiểu tất cả bảy khái niệm này, mục tiêu loại bỏ lãng phí là động lực chính cho phương pháp tiếp cận tinh gọn. Lean sử dụng thuật ngữ Muda 無駄 của Nhật Bản để chỉ bảy loại lãng phí cần được loại bỏ. Các chuyên gia tinh gọn Mary và Tom Poppendieck, những người đã viết nhiều về việc sử dụng Lean trong các dự án phần mềm, đã chuyển đổi bảy lãng phí trong sản xuất truyền thống thành bảy lãng phí trong phát triển phần mềm như bảng dưới đây.

|Lãng phí| Miêu tả | Ví dụ |
|-----|-----|-----|
| Partially done work - Công việc đã hoàn thành một phần | Công việc đã bắt đầu, nhưng chưa hoàn thành; một phần công việc hoàn thành có thể bị rối loạn     |  Mã nguồn đang chờ test <br/> Spec đang chờ phát triển     |
| Extra processes - Quá nhiều quy trình  | Quá nhiều công việc không thêm được giá trị     |   Tài liệu không sử dụng được <br/>   Phê duyệt không cần thiết  |
| Extra features - Chức năng bổ sung  | Các tính năng không bắt buộc hoặc được coi là "nice-to-haves"     | Gold-plating <br/> Tính năng công nghệ      |
| Task switching - Chuyển đổi công việc  | Đa tác vụ giữa các dự án khác nhau có nghĩa là phải chuyển đổi ngữ cảnh liên tục     | Những người được chỉ định cho nhiều dự án      |
| Waiting - Đợi chờ  | Chậm trễ trong chờ đợi reviews và quyết định    | Đợi đánh giá prototype <br/> Đợi quyết định tài liệu      |
| Motion - Chuyển động  | Effort cần thiết để giao tiếp và chuyển thông tin hoặc phân phối người hoặc một nhóm người sang nhóm khác; nếu các nhóm không cùng vị trí, effort này có thể cần phải lớn hơn.     |    Phân tán nhóm <br/> Bàn giao công việc   |
| Defects - khiếm khuyết  | Tài liệu hoặc phần mềm bị lỗi cần sửa     |   Khiếm khuyết yêu cầu <br/> Lỗi phần mềm    |

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập - Đánh mục lãng phí</h5>

  <p>Hãy dựa vào bảng Poppendieck để tham khảo, đánh nhãn cho bài tập lãng phí bên dưới.</p>
</div>

|Hoạt động | Loại lãng phí|
|-----|-----|
| Xếp hàng vào thang máy  | Waiting |
| Khởi động lại máy tính khi chương trình gặp sự cố | Defects |
| Lưu tài liệu ở định dạng cũ để tương thích | Extra features |
| Tạo thông báo bằng tiếng Pháp và tiếng Nga để tuân thủ các tiêu chuẩn của công ty, ngay cả khi không ai ở địa điểm của bạn nói ngôn ngữ này | Extra processes & Extra features |
| Gửi đơn đặt hàng văn phòng phẩm và giấy để được phê duyệt |  Extra processes |

ĐÁP ÁN:

![typeofwaste]({{ site.baseurl }}/assets/images/typeofwaste.jpg)

<p style="font-style: italic;">
Tất nhiên, những loại hoạt động này không phải lúc nào cũng lãng phí. Lãng phí chỉ xảy ra nếu không thu được bất kỳ lợi ích nào từ hoạt động này. Vì vậy, mặc dù các thông báo an toàn nên được cung cấp cho bất kỳ ai cần chúng, các bản dịch không cần thiết của các thông báo đó có thể bị coi là lãng phí. Tương tự như vậy, việc phê duyệt các đơn đặt hàng văn phòng phẩm và giấy có thể hữu ích để ngăn chặn việc lạm dụng hoặc trộm cắp vặt, nhưng đối với những người chỉ cần một số nugồn cung cơ bản, quá trình này không có giá trị gì và có thể bị coi là lãng phí.
</p>

Lean đã đóng góp các kỹ thuật và khái niệm quan trọng cho Agile, bao gồm 7 dạng lãng phí, hệ thống pull, ánh xạ dòng giá trị và công việc đang tiến hành, hay còn gọi là WIP (những khái niệm này sẽ được cung cấp tiếp theo.). Như chúng ta đã thấy, Lean cũng là nguồn gốc của phương pháp Kanban, sẽ được thảo luận tiếp theo. Tuy nhiên, trước khi tiếp tục, hãy làm thử bài tập dưới đây, bài tập này dùng để cũng cố sự hiểu biết về nguyên tắc của Lean.


<div id="practises" style="font-size: 12px;">
  <h5>Bài tập - Nối những thực hành Agile với những nguyên tắc của Lean</h5>
</div>

![matchleannAgile]({{ site.baseurl }}/assets/images/matchleannAgile.png)

ĐÁP ÁN:

![anwserofLeanNAgile]({{ site.baseurl }}/assets/images/anwserofLeanNAgile.png)

{:#kanban}
# KANBAN

Phương pháp Kanban đề ra từ hệ thống sản xuất tinh gọn được phát triển bởi Toyota. Kanban là một từ tiếng Nhật có nghĩa là "bảng chỉ dẫn". Bảng hiệu hay bảng Kanban đóng vai trò quan trọng trong phương pháp học Kanban. Bảng này hiển thị các hạng mục công việc trong từng giai đoạn của quá trình sản xuất, do nhóm xác định. Đây là một ví dụ đơn giản về một bảng như vậy:

![kanbanex]({{ site.baseurl }}/assets/images/kanbanex.png)

{:#fivePrinciples}
## Năm nguyên tắc của Kanban

Phát triển Kanban hoạt động dựa trên năm nguyên tắc cốt lõi:

» **Visualize the workflow - hiển thị hóa luồng công việc** : Những dự án công việc tri thức, theo định nghĩa, vận dụng tri thức, là bất khả xâm phạm và vô hình. Do đó, có một số cách để hiển thị hóa quy trình làm việc là rất quan trọng để tổ chức, tối ưu hóa và theo dõi quy trình đó.

» **Limit WIP (work in progress) - Giới hạn công việc đang thực hiện** : Hạn chế số lượng công việc đang thực hiện sẽ cải thiện năng suất, tăng khả năng hiển thị các vấn đề và tắc nghẽn, đồng thời tạo điều kiện cải tiến liên tục. Điều này giúp nhóm phát triển dễ dàng xác định các vấn đề hơn và giảm thiểu lãng phí và chi phí liên quan đến các thay đổi. Nó cũng dẫn đến một "lực kéo" công việc ổn định thông qua effort phát triển, vì công việc mới chỉ có thể được tiếp tục khi công việc hiện tại được hoàn thành.

» **Manage flow - Quản lý luồng** : Bằng cách theo dõi luồng của công việc thông qua dự án, các vấn đề có thể được xác định và các thay đổi có thể được đo lường về tính hiệu quả.

» **Make process policies explicit - Đưa ra các chính sách quy trình rõ ràng** : Điều quan trọng là phải giải thích rõ ràng cách mọi thứ hoạt động để nhóm có thể thảo luận cởi mở về những cải tiến theo hướng khách quan, thay vì cảm tính hoặc chủ quan.

» **Improve collaboratively - Cải thiện hợp tác** : Thông qua đo lường và thử nghiệm khoa học, nhóm nên sở hữu chung và cải tiến các quy trình mà nhóm sử dụng.

{:#kanbanpullsys}
## Hệ thống kéo của kanban

Kanban có một số tính năng khác biệt để phân biệt với Scrum, XP và Agile nói chung. Sự khác biệt chính mà chúng ta nên hiểu đối với kỳ thi là các nhóm Kanban sử dụng một "hệ thống kéo" để di chuyển công việc qua quá trình phát triển, thay vì lập kế hoạch công việc của họ theo các lần lặp lại hộp thời gian. Mỗi khi một nhóm Kanban hoàn thành một hạng mục công việc, nó sẽ kích hoạt một "lực kéo" để mang hạng mục tiếp theo mà họ sẽ làm.

Như chúng ta sẽ thấy, chỉ có một số ví dụ nhất định có sẵn cho mỗi cột trên Kanban và bất cứ khi nào có ô trống trên bảng, đó là tín hiệu cho nhóm kéo công việc từ giai đoạn trước, nếu có bất kỳ mục nào có sẵn. Vì vậy, công việc liên tục được kéo từ phía bên trái của bảng sang phía bên phải.

(*Lưu ý*: Điều này có thể trông giống như việc di chuyển các hạng mục công việc trong quá trình từ trái sang phải trên một bảng tác vụ Agile, nhưng không phải vậy. Trên bảng Kanban, năng lực là tín hiệu cho nhóm kéo các hạng mục công việc vào giai đoạn tiếp theo của quy trình. Trên bảng tác vụ Agile, nhóm chỉ cần di chuyển các hạng mục công việc từ trái sang phải để hiển thị trạng thái của chúng trong quy trình.)

Hệ thống kéo này có nghĩa là Kanban ít nhấn mạnh hơn vào các lần lặp so với các phương pháp Agile. Mặc dù nhóm Kanban có thể sử dụng các phép lặp họ muốn, nhưng cơ chế kéo vừa mô tả có nghĩa là không cần nó. Tất nhiên hầu hết các tổ chức muốn tăng thêm công việc sẽ có sẵn để tiêu thụ. Tuy nhiên, nhịp phát triển của nhóm không cần phải kết hợp với nhịp phân phối đó hoặc bất kỳ tổng hợp nào của nó.

Ví dụ, một nhóm agile có thể quyết định sử dụng hai tuần lặp lại các lần triển khai vào môi trường thử nghiệm cũng như triển khai trực tiếp cho khách hàng mỗi quý. Vì vậy, trong mỗi khung thời gian triển khai trực tiếp hàng quý (13 tuần), họ thường sẽ hoàn thành sáu lần lặp lại công việc. Vì vậy, nhóm biết rằng họ sẽ có sáu lần lặp lại giữa mỗi bản phát hành chính và sẽ lên kế hoạch cho các tính năng và story cho phù hợp.

Mặt khác, một nhóm Kanban vẫn có thể có các bản phát hành hàng quý cho khách hàng, nhưng họ sẽ không sử dụng bất kỳ lần lặp nội bộ nào. Thay vào đó, bất kỳ gói công việc nào được chấp nhận mà họ đã sẵn sàng sẽ là ứng cử viên cho bản phát hành tiếp theo. Họ vẫn có thể lập kế hoạch và theo dõi công việc của mình cho các bản phát hành, nhưng thay vì sử dụng các chỉ số vận tốc, chẳng hạn như điểm được chấp nhận trên mỗi lần lặp, họ sẽ sử dụng các chỉ số về thời gian chu kỳ, thời gian thực hiện và thông lượng được mô tả trong chương 6.


{:#limitWIP}
## Giới hạn WIP trong Kanban

Các giới hạn WIP sẽ được giải thích đầy đủ hơn trong chương tiếp theo - nhưng về cơ bản, thuật ngữ này đề cập đến việc giới hạn số lượng mục có thể ở trong một trạng thái tiến triển nhất định, như được xác định bởi các cột trên bảng Kanban của nhóm. Khi đạt đến giới hạn ở đầu cột, không có mục mới nào được chuyển vào cột đó cho đến khi mục khác được chuyển ra ngoài. Dưới đây là một ví dụ về bảng Kanban có giới hạn WIP:

![kanbanlimitWIP]({{ site.baseurl }}/assets/images/kanbanlimitWIP.png)

Nhìn vào ví dụ này, chúng ta thấy danh sách tồn động của nhóm là ở cột thứ nhất. Cột thứ hai cho biết rằng có 3 user stories hiện tại đang được chọn để phát triển, giới hạn WIP ở đầu cột thứ 4. Các cột Phát triển và Đồng ý cũng có giới hạn WIP - cột thứ ba và thứ hai, tương ứng.

Tại sao giới hạn WIP lại quan trọng? Lý do là giảm WIP thực tế là tăng tính hiệu quả của nhóm - nó tăng tốc độ tỉ lệ công việc hoàn thành. Nếu tuyên bố đó có vẻ còn gây tranh cãi, thì mối quan hệ giữa công việc đang thực hiện và năng suất đã thực sự được chính minh về mặt toán học bởi Littles Law, như minh họa bên dưới. Định luật này chứng minh rằng thời lượng của một hàng đợi (mất bao lâu để hoàn thành công việc) tỷ lệ thuận với quy mô của nó (bao nhiêu công việc được tiến hành). Nói cách khác, các nhóm giới hạn WIP sẽ hoàn thành công việc của họ nhanh hơn.

![littellaw]({{ site.baseurl }}/assets/images/littellaw.png)

Phương pháp Kanban đã giúp phổ biến các bảng nhiệm vụ với các giới hạn WIP và các hệ thống kéo tạo ra bằng cách giới hạn WIP. Nó cũng cho phpé và khuyến khích các thành viên trong nhóm thử các cách tiếp cận mới và thay đổi quy trình. Với mô hình kéo liên tục, có thể không cần lặp lại và do đó, các hoạt động như tạo ước tính có thể bị coi là lãng phí và được giảm bớt hoặc loại bỏ hoàn toàn.

{:#featuredriven}
# Phát triển hướng chức năng (Feature-Driven Development - FDD)

Phát triển theo hướng tính năng (FDD) là một cách tiếp cận đơn giản dễ hiểu nhưng lại mạnh mẽ để xây dựng sản phẩm hoặc giải pháp. Một nhóm dự án theo phương pháp FDD trước tiên sẽ phát triển một mô hình tổng thể cho sản phẩm, xây dựng danh sách tính năng và lập kế hoạch công việc. Sau đó, nhóm chuyển qua các bước thiết kế và xây dựng để phát triển các chức năng này.

![ffdprocess]({{ site.baseurl }}/assets/images/ffdprocess.png)

FFD đề xuất một loạt các thực hành, bắt nguồn từ kỹ thuật phần mềm. Những thực hành này bao gồm:

» **Domain object modeling - Mô hình đối tượng miền** : Trong thực hành này, nhóm dự án khám phá và giải thích miền (hoặc môi trường doanh nghiệp) của vấn đề cần giải quyết.

» **Developing by feature - Phát triển chức năng** : Này bao gồm việc chia nhỏ các chức năng thành các phần công việc nhỏ 2 tuần hay ngắn hơn và gọi chúng là các tính năng.

» **Individual class (code) ownership - Quyền sở hữu lớp (mã nguồn) cá nhân** : Với thực hành này, các mã nguồn có một chủ sở hữu duy nhất để đảm bảo tính nhất quán, hiệu suất và tính toàn vẹn của khái niệm (Điều này hoàn toàn trái ngược với ý tưởng sở hữu mã tập thể của XP nhằm mục đích truyền bá kiến thức cho thành viên khác trong nhóm.)

» **Feature teams - Nhóm tính năng** : Đây là các nhóm nhỏ, được thành lập động, có chức năng kiểm tra chức năng, thiết kế và cho phpé đánh giá nhiều phương án thiết kế trước khi chọn một. Nhóm tính năng giúp giảm thiểu rủi ro liên quan đến quyền sở hữu cá nhân.

» **Inspections - Thanh tra** : Đây là những đánh giá giúp đảm bảo thiết kế và mã nguồn có chất lượng cao.

» **Configuration management - Quản lý cấu hình** : Điều này liên quan đến việc gắn nhãn, theo dõi các thay đổi và quản lý mã nguồn.

» **Regular builds - Các bản build thường xuyên** : Thông qua các bản build thường xuyên, nhóm đảm bảo rằng mã mới tích hợp được với mã cũ. Thực hành này cũng cho phép tạo một bản demo.

» **Visibility of progress and results - Khả năng hiển thị tiến độ và kết quả** : Phương pháp này theo dõi tiến độ dựa trên công việc đã hoàn thành.

Phát triển hướng tính năng là phương pháp Agile đã phổ biến sơ đồ luồng tích lũy (được thảo luận trong chương 2) và sơ đồ bãi đậu xe, là những bản tóm tắt một trang về tiến độ dự án.

Cả hai đều là các công cụ theo dõi và chẩn đoán hữu ích hiện được sử dụng bởi các phương pháp tiếp cận Agile khác.

{:#dsdm}
# Phương pháp phát triển hệ thống động (DSDM - Dynamic Systems Development Method)

DSDM là một trong những phương pháp Agile, nó bắt đầu khá chi tiết và mang tính quy định. Phạm vi của nó về vòng đời của dự án khá rộng, bao gồm các khía cạnh của dự án Agile, từ tính khả thi và bài toán kinh doanh đến việc thực hiện.

Hình dưới đây minh họa vòng đời của DSDM:

![dsdm_life]({{ site.baseurl }}/assets/images/dsdm_life.png)

DSDM được tập trung dựa vào 8 nguyên tắc. Mặc dù những nguyên tắc này cũng được tạo trước khi Tuyên ngôn Agile được viết, chúng cũng gần với Tuyên ngôn. Tám nguyên tắc đấy là:

**1. Focus on the business need - Tập trung vào kinh doanh cần**

**2. Deliver on time - Phân phối liên tục**

**3. Collaborate - Hợp tác**

**4. Never compromise quality - Không bao giờ thỏa hiệp chất lượng**

**5. Build incrementally from firm foundations - xây dựng từng bước từ nền tảng vững chắc**

**6. Develop iteratively - Phát triển một cách lặp lại**

**7. Communicate continuously and clearly - Giao tiếp liên tục và rõ ràng**

**8. Demonstrate control - Thể hiện sự kiểm soát**

DSDM đã ảnh hưởng đến sự phát triển của Agile bằng cách giúp đỡ phổ biến các cân nhắc kiến trúc lần đầu, bộ lọc phù hợp nhanh và các hợp đồng Agile.

{:#crystal}
# Crystal

Crystal không chỉ là một phương pháp; nó bao gồm một nhóm các phương pháp tùy chỉnh, cụ thể theo tình huống được mã hóa bằng tên màu. Mỗi phương pháp được tùy chỉnh theo mức độ quan trọng và quy mô của nhóm, điều này cho phép Crystal bao gồm nhiều loại dự án, từ một nhóm nhỏ xây dựng hệ thống quan trọng thấp (Crystal Clear) đến một nhóm lớn xây dựng hệ thống quan trọng cao (Crystal Magenta).

Khung Crystal cung cấp một ví dụ tuyệt vời về cách các phương pháp Agile có thể được điều chỉnh để phù hợp với các đặc điểm cụ thể của một dự án. Ví dụ, hình bên dưới cho thấy năm "màu sắc" (phương pháp) đầu tiên của Crystal.

![crystalmethod]({{ site.baseurl }}/assets/images/crystalmethod.png)

Trong sơ đồ này, quy mô nhóm được hiển thị trên trục hoành và mức độ quan trọng của dự án được hiển thị trên trục tung. "Mức độ nghiêm trọng" của một dự án dựa trên tác động tiềm ẩn của lỗi sản phẩm - liệu nó có thể gây mất thỏa mái, quỹ thiết yếu hay cuộc sống. Ví dụ: chúng ta có thể thấy rằng Crystal Clear được thiết kế cho các dự án nhỏ với quy mô nhóm cốt lõi từ một đến sáu người, trong đó thất bại có htể dẫn đến mất thỏa mái (ví dụ, một sự cố trình xử lý văn bản dẫn đến mất thời gian kinh doanh). Khi các dự án thu hút nhiều người hơn và phát triển các ứng dụng ngày càng quan trọng, chúng ta cần mở rộng quy trình của mình ngoài giao dịch trực tiếp và đưa ra các biện pháp xác nhận và truy xuất nguồn bổ sung.

Đối với bài kiểm tra, chúng ta không cần phải hiểu chi tiết về cách hoạt động của các phương pháp crystal khác nhau, nhưng chúng ta nên hiểu cách crystal sử dụng các yếu tố quan trọng và quy mô nhóm để phân loại dự án, như được trình bày ở trên. Việc crystal sử dụng phương pháp chia tỷ lệ này để xác định phương pháp tốt nhất cho một dự án đã ảnh hưởng đáng kể đến tư duy Agile. Một khái niệm có ảnh hưởng khác mà Crystal đã góp phần vào Agile là khái niệm giao tiếp thẩm thấu (được đề cập trong chương 4). Các phương pháp Crystal cũng bao gồm và thúc đẩy nhiều nguyên tắc Agile khác.


{:#agileprocessoverview}
<div id="toolkitBox">
  <h2 id="toolkitContent">Tổng quan quy trình Agile<br/><hr/></h2>
</div>

<br/>

![agileprocessoverview]({{ site.baseurl }}/assets/images/agileprocessoverview.png)

Các chương còn lại giải thích các công cụ Agile, thực hành và khái niệm được đề cập trong lĩnh vực còn lại. Hình trên cung cấp chế độ xem dòng thời gian về thời điểm nhiều hoạt động chung ta sẽ thảo luận thường xuyên trong một dự án Agile đơn giản, bao gồm các hoạt động được lặp đi lặp lại. Khi đọc cuốn sách này, hãy xem lại sơ đồ này nếu cần để xem các khái niệm khác nhau phù hợp với quy trình Agile tổng thể như thế nào.

Tuy nhiên, có một điều cần ghi nhớ. Biểu đồ này cho thấy quy trình điển hình cho một dự án Agile chung chung, nhưng quy trình đó không giống với các dự án Lean và Kanban. Nhóm Lean và Kanban có thể không sử dụng lặp, thay vào đó sử dụng mô hình Kéo để chuyển công việc thông qua hệ thống. Họ vẫn sẽ sử dụng các bản trình diễn, đánh giá và review, nhưng họ sẽ không liên kết trực tiếp thời gian của các cuộc họp này với việc cung cấp một lượng lớn chức năng, như Agile chung thường làm ở mỗi cuối lần lặp.

{:#agileleadership}
<div id="toolkitBox">
  <div id="toolkitIcon">K&S</div>
  <h2 id="toolkitContent">Agile Leadership<br/><hr/></h2>
</div>

Agile mang tính chất nhân văn hơn là máy móc, bằng chứng là giá trị linh hoạt của "các cá nhân và sự tương tác qua các quy trình và công cụ". Khái niệm đánh giá con người qua các quy trình vượt ra ngoài cách chúng ta quản lý công việc được thực hiện trong dự án; nó cũng tác động đến cách chúng ta tổ chức và động viên các thành viên trong nhóm, cũng như cách chúng ta đảm nhận vai trò lãnh đạo của mình. Lãnh đạo là khai tahc1 các động lực nội tại của mọi người. Để trở thành nhà lãnh đạo hiệu quả, chúng ta cần khám phá lý do tại sao các thành viên trong nhóm muốn làm mọi việc, hiểu điều gì thúc đẩy họ, sau đó sắp xếp các nhiệm vụ và mục tiêu dự án của họ cho phù hợp. Chính bằng cách sắp xếp các mục tiêu dự án với các mục tiêu cá nhân mà chúng ta có thể đạt được mức năng suất cao hơn.

{:#managervsleader}
## Quản lý và Lãnh đạo

Các kỹ thuật lãnh đạo được sử dụng trong các dự án Agile liên quan đến việc thực hiện phương pháp tiếp cận giữa các cá nhân, thay vì các phương pháp chỉ đạo, ra lệnh và kiểm soát. Có một câu nói nổi tiếng của Warren Bennis nói lên sự khác biệt giữa hai cách tiếp cận này: "Quản lý là thúc đẩy mọi người làm những gì cần phải làm. Lãnh đạo là khiến mọi người muốn làm những gì cần phải làm".

Thay vì bảo mọi người phải làm gì, chúng ta cần tạo ra một môi trường nơi mọi người muốn làm những gì cần phải làm. Sự khác biệt giữa hai môi trường giống như sự khác biệt giữa kéo một sợi dây (khi mọi người muốn làm những gì cần phải làm) và đẩy dây (khi mọi người chỉ đơn giản là được cho biết phải làm gì).

Quản lý có trọng tâm cơ học hơn lãnh đạo; nó liên quan đến nhiệm vụ, kiểm soát và tốc độ. Ngược lại, lãnh đạo đặt trọng tâm nhân văn vào con người và mục đích; nó quan tâm nhiều hơn đến việc trao quyền, hiệu quả và làm những điều đúng đắn.

Bảng sau đây minh hoạt sự khác biệt giữa trọng tâm quản lý và trọng tâm lãnh đạo:

|Quản lý tập trung vào| Lãnh đạo tập trung vào|
|-----|-----|
| Công việc/ vấn đề  |  Con người  |
| Điều khiển | Trao quyền  |
| Effeciency (hiệu suất) | Effectiveness (hiệu quả)  |
| Làm đúng mọi thứ | Làm mọi thứ một cách đúng đắn  |
| Tốc độ | Phương hướng  |
| Thực hành | Nguyên tắc  |
| Chỉ huy | Giao tiếp  |

Vậy điều này có nghĩa là lãnh đạo tốt hơn quản lý? Chúng ta có thể chỉ có lãnh đạo mà không có quản lý? Không, chúng ta chắc chắn cần cơ chế quản lý tại chỗ. Nhưng để thực sự hiệu quả, chúng ta cần đặt vai trò lãnh đạo lên trên những cơ chế đó. Chúng ta có thể nâng cao năng suất của nhóm một cách tốt nhất thông qua sự kết hợp giữa quản lý và lãnh đạo.

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập</h5>

  <p>Hãy xem lại các mục dưới đây và đánh dấu mục mô tả công việc của bạn. Khi hoàn thành, hãy nhìn lại chủ yếu các đánh dấu nằm ở Công việc tri thức hay Công việc sản xuất</p>
</div>

|Hoạt động | Chính là lãnh đạo hay quản lý|
|-----|-----|
| Human resource management  | Management  |
| Career planning | Leader  |
| Team time tracking |  Management |
| Team member  (công nhận) |  Leader |
| Task assignment | Management  |
| Team brainstorming | Leader  |
| Planning workshops |  Leader |
| Creating Gantt charts | Management  |

ĐÁP ÁN:

![leaderormanager]({{ site.baseurl }}/assets/images/leaderormanager.png)

{:#servantLeader}
<div id="toolkitBox">
  <div id="toolkitIcon">T&T</div>
  <h2 id="toolkitContent">Lãnh đạo phục vụ<br/><hr/></h2>
</div>

<br/>

Agile thúc đẩy mô hình lãnh đạo phục vụ công nhận rằng chính các thành viên trong nhóm, không phải người lãnh đạo, huấn luyện viên hay Scrum Master, là những người hoàn thành công việc kỹ thuật và đạt được giá trị kinh doanh. Phương pháp lãnh đạo phục vụ xác định lại vai trò của người lãnh đạo trong mối quan hệ với nhóm. Nó tập trung người lãnh đạo vào việc cung cấp những gì các thành viên trong nhóm cần, loại bỏ những cản trở đối với sự tiến bộ của họ và thực hiện các nhiệm vụ hỗ trợ để tối đa hóa năng suất của họ.

Có bốn nhiệm vụ chính mà một nhà lãnh đạo thực hiện trong vai trò phục vụ nhóm:

**1. Shield the team from interruptions - Bảo vệ team khỏi những gián đoạn**

Các nhà lãnh đạo phục vụ cần phải cô lập và bảo vệ các thành viên trong nhóm khỏi sự luân chuyển, gián đoạn và yêu cầu đối với công việc không nằm trong dự án.

Khi các đại diện của doanh nghiệp tham gia chặt chẽ vào một dự án, họ có thể dễ dàng đưa ra các yêu cầu thay đổi hoặc cải tiến trực tiếp cho các nhà phát triển, điều này sẽ làm gián đoạn nỗ lực phát triển theo kế hoạch. Trong khi các dự án Agile khuyến khích tích cực những hiểu biết và yêu cầu kinh doanh này, chúng cần phải được thông qua các kênh giao tiếp thích hợp. Đại diện doanh nghiệp nên đưa ra các yêu cầu như vậy trong cuộc họp lập kế hoạch sprint hoặc gửi chúng cho Product Owner để đưa vào product backlog. Một phần của việc trở thành lãnh đạo phục vụ bao gồm việc nhắc nhở mọi người về các kênh được chỉ định để nhóm làm việc có thể duy trì sự tập trung của họ vào trong sprint và thiết lập tốc độ đáng tin cậy cho phép sử dụng tiến trình của nhóm giúp lập kế hoạch công việc trong tương lai.

Mặc dù điều quan trọng là phải che chắn cho đội khỏi các cuộc luân chuyển nội bộ, nhưng người lãnh đạo phải đặc biệt cảnh giác trong việc bảo vệ khỏi các cuộc luân chuyển bên ngoài. Việc khiến mọi người không tập trung vào công việc của dự án và luân chuyển qua lại sẽ làm giảm hiệu suất. Nếu người lãnh đạo có thể bảo vệ nhóm khỏi những yêu cầu phi lý từ bên ngoài, thì năng suất của họ sẽ được nâng cao. Các thành viên trong nhóm ngồi cùng vị trí về mặt vật lý là một cách hiệu quả để ngăn chặn sự can thiệp từ bên ngoài. Nếu mọi người vẫn đang ở trong các phòng ban chức năng hoặc không gian làm việc của họ, thì quá dễ dàng để bị lôi kéo vào các công việc ngoài dự án.

**2. Remove impediments to progress - Loại bỏ trở ngại để tiến bộ**

Những người lãnh đạo phục vụ cần phải dọn sạch những chướng ngại vật trên con đường của nhóm mà có thể gây ra sự chậm trễ hoặc lãng phí. Những trở ngại này có thể bao gồm tài liệu hoặc các hoạt động tuân thủ làm chệch hướng nhóm hoàn thành các mục tiêu của sprint. Theo thuật ngữ Lean, công việc tuân thủ đề cập đến những nỗ lực không trực tiếp góp phần mang lại giá trị kinh doanh. Điều này có thể bao gồm các nhiệm vụ ghi lại thời gian trùng lặp, các cuộc họp phi dự án và các hoạt động hành chính khác.

Tại cuộc họp trực tiếp hàng ngày, nơi nhóm báo cáo tiến độ, công việc đã lên kế hoạch và các vấn đề của mình, người lãnh đạo cần lưu ý các vấn đề và làm việc để giải quyết chúng trong ngày hôm đó, nếu có thể. Loại bỏ hoặc giảm bớt những trở ngại như vậy sẽ cho phép nhóm làm việc nhanh hơn và cuối cùng mang lại nhiều giá trị hơn cho doanh nghiệp.

Một số công cụ quản lý dự án Agile hiện nay hỗ trợ các công việc còn tồn đọng. Những tồn đọng này là một loại danh sách loại bỏ chướng ngại vật được ưu tiên. Các nhà lãnh đạo phục vụ có thể sử dụng các công cụ như vậy để theo dõi công việc loại bỏ trở ngại của họ.

**3. Communicate (and re-communicate) the project vision - Truyền đạt (và truyền đạt liên tục) tầm nhìn của dự án**

Đây có vẻ là một nhiệm vụ kỳ quặc đối với hạng mục lãnh đạo phục vụ, nhưng việc truyền đạt và truyền đạt liên tục tầm nhìn của dự án là rất quan trọng để lãnh đạo thành công một nhóm.

Chỉ khi các bên liên quan có hình ảnh rõ ràng về cách mục tiêu cho sản phẩm và dự án đã hoàn thành thì họ mới có thể điều chỉnh các quyết định của mình và hướng tới mục tiêu chung của dự án. Trong cuốn sách bán chạy nhất - Thử thách lãnh đạo - của James Kouzes và Barry Posner, họ nói rằng các nhà lãnh đạo cần tiết lộ một "hội nghị thượng đỉnh" để những người khác có thể "vạch ra lộ trình của họ". Nói các đơn giản, một tầm nhìn chung giúp thu hút tất cả mọi người cùng một hướng.

Các quan điểm khác nhau thường phát triển giữa các thành viên trong nhóm có thiện chí. Ví dụ: trong dự án phần mềm, mong muốn của nhà phát triển về sự đơn giản hoặc công nghệ mới có thể khiến công việc của họ khác với yêu cầu của người dùng. Mong muốn của nhà phân tích hoặc chuyên gia đảm bảo chất lượng về sự hoàn chỉnh và tuân thủ có thể khác với yêu cầu của nhà tài trợ về tiến độ và hoàn thành. Truyền đạt và truyền đạt liên tục lại tầm nhìn dự án giúp các bên liên quan nhận ra những khác biệt này và đưa chúng trở lại phù hợp với mục tiêu dự án.

Kouzes và Posner nhận thấy rằng những nhà lãnh đạo hiệu quả nhất dành phần trăm thời gian làm việc của họ để truyền đạt và truyền đạt liên tục lại tầm nhìn của dự án cũng như của công ty so với những người lãnh đạo thấp hơn. Họ tin rằng các nhà lãnh đạo hầu như không thể thông qua quá mức tầm nhìn của dự án và tuyên bố rằng đó là một bước quan trọng để lãnh đạo hiệu quả.

Vì vậy, các dự án Agile không nên chỉ có một thực hành tầm nhìn khi bắt đầu dự án hoặc khi phát triển các mục tiêu lặp lại. Tập trung hạn chế như vậy không đủ. Thay vào đó, các nhà lãnh đạo phục vụ cần liên tục tìm các cơ hội để truyền đạt tầm nhìn của dự án và tìm ra những cách mới để minh họa và củng cố tầm nhìn đó.

**4. Carry food and water - Cung cấp đầy đủ resource**

Thức ăn và nước uống ở đây không phải là hiểu đúng nghĩa đen của nó; đó là việc cung cấp các nguồn lực thiết yếu mà một nhóm cần để giúp họ được nuôi dưỡng và làm việc hiệu quả. Các nguồn lực như vậy có thể bao gồm các công cụ, bồi dưỡng và khuyến khích.

Những người được thúc đẩy bởi tính chuyên nghiệp và nghĩa vụ một mình không thể tiếp tục cống hiến hết khả năng của họ, hết lần này đến lần khác. Các nhà lãnh đạo cần tìm hiểu điều gì thúc đẩy các thành viên trong nhóm của họ với tư cách cá nhân và tìm cách khen thưởng cho họ khi làm việc tốt. Như một biện pháp đơn giản, một nơi tuyệt vời để bắt đầu là một lời "cảm ơn" chân thành đến ai đó vì họ đã làm việc chăm chỉ.

Các nhà lãnh đạo cũng cần ăn mừng những chiến thắng - tất nhiên là những chiến thắng lớn, nhưng cũng cần cho chiến thắng nhỏ - khi dự án tiến triển. Thông thường, việc lưu lại các kỷ niệm dự án cho đến cuối là điều thường bị hấp dẫn, nhưng nếu các thành viên trong nhóm không được thường xuyên công nhận, thì dự án có thể không bao giờ đạt được kết quả thành công. Lễ kỷ niệm và sự công nhận giúp xây dựng động lực và các nhà lãnh đạo cần thường xuyên nuôi dưỡng nhóm của họ bằng những phần thưởng như vậy để giữ cho dự án tiến lên một cách hiệu quả.

Các hoạt động đào tạo và phát triển chuyên môn khác cũng là những ví dụ về các nguồn lực mà nhóm có thể cần để hoạt động hiệu quả. Scrum Master hoặc huấn luyện viên nên quan tâm và sắp xếp đào tạo thích hợp cho các cá nhân trong nhóm. Bằng cách xây dựng kỹ năng của các thành viên trong nhóm, dự án sẽ thu được lợi ích kiến thức mới của họ. Những hành động như vậy cũng cho thấy rằng chúng ta không chỉ cố gắng khai thác công việc và thông tin từ các thành viên trong nhóm, chúng ta còn muốn tự bản thân họ cũng phát triển.

![servantleadership]({{ site.baseurl }}/assets/images/servantleadership.png)

{:#twelvePrinciples}
## Mười hai nguyên tắc lãnh đạo dự án Agile

Ngoài bốn nhiệm vụ cốt lõi mà chúng ta vừa thảo luận, có những hoạt động khác mà các nhà lãnh đạo phục vụ nên ghi nhớ. Jeffrey Pinto, trong Lãnh đạo dự án: từ lý thuyết đến thực hành, đưa ra danh sách các nguyên tắc tuyệt vời sau đây để các nhà lãnh đạo tuân theo:

» **Learn the team members’ needs - Tìm hiểu nhu cầu của các thành viên trong nhóm** : Tìm hiểu những gì thúc đẩy và là động lực của mọi người.

» **Learn the project’s requirements - Tìm hiểu yêu cầu dự án** : Nói chuyện với khách hàng và nhà đầu tư; tìm ra các ưu tiên của họ.

» **Act for the simultaneous welfare of the team - Hành động vì lợi ích đồng thời của nhóm lẫn dự án** : Cân bằng và thúc đẩy nhu cầu và mong muốn của cả nhóm và các bên liên quan khác của dự án.

» **Create an environment of functional accountability - Tạo ra một môi trường trách nhiệm theo chức năng** : Đảm bảo mọi người biết thành công và thất bại trông như thế nào, đồng thời trao quyền cho nhóm tự tổ chức để đạt được mục tiêu. Hãy tự hào về những thành tích đạt được, nhưng đừng che giấu hoặc né tránh những thất bại - thay vào đó, hãy kiểm tra chúng, học hỏi và thích nghi chúng.

» **Have a vision of the completed project - Có tầm về dự án hoàn thành** : Tạo một hội nghị thượng đỉnh để những người khác có thể lập biểu đồ cho khóa học của riêng họ. Khi chúng ta chìm trong đám cỏ dại, thật tốt khi biết chúng ta đang cố gắng đi đến đâu, vì vậy chúng ta có thể điều hướng đường đi của mình.

» **Use the project vision to drive your own behavior - Sử dụng tầm nhìn của dự án để định hướng hành vi của chính mình** : Mô hình hành động hướng tới các mục tiêu của dự án.

» **Serve as the central figure in successful project team development - Đóng vai trò trung tâm trong nhóm phát triển dự án thành công** : Mô hình hành vi mong muốn cho nhóm.

» **Recognize team conflict as a positive step - Nhận ra xung đột trong nhóm là một bước tích cực** : Cuộc tranh luận không được lọc tạo ra sự ủng hộ mạnh mẽ cho các chủ đề được thảo luận kỹ lưỡng.

» **Manage with an eye toward ethics - Quản với con mắt hướng tới đạo đức** : Hãy trung thực và có đạo đức, bởi vì mọi người không muốn gắn liền với các mục tiêu hoặc sứ mệnh mà họ cảm thấy là phi đạo đức.

» **Remember that ethics is not an afterthought, but an integral part of our thinking - Hãy nhớ rằng đạo đức không phải là một suy nghĩ sau cùng, mà là một phần không thể thiếu trong suy nghĩ của chúng ta** : Chúng ta không thể tin tưởng vào sau này - giống như chất lượng, nó phải là thành phần cốt lõi.

» **Take time to reflect on the project - Hãy dành thời gian để suy ngẫm về dự án** : Xem xét, chẩn đoán và điều chỉnh; cải thiện thông qua sự thay đổi và học hỏi tiến bộ.

» **Develop the trick of thinking backward - Phát triển thủ thuật của tư duy lạc hậu** : Điều này có nghĩa là tưởng tượng rằng chúng ta đã đạt được mục tiêu cuối cùng, sau đó làm việc ngược lại để xác định những gì phải xảy ra để đạt được điều đó và những vấn đề và rủi ro mà chúng ta có thể tránh được. Vì vậy, trước tiên hãy thảo luận và quyết định xem "hoàn thành" sẽ như thế nào; sau đó lập biểu đồ con đường đi đến đó và lập kế hoạch chúng ta sẽ tránh mọi chướng ngại vật cản đường mình như thế nào.

Chúng ta đã thảo luận vài thứ về những nguyên tắc này ở những phần khác của chương này, nhưng danh sách này cung cấp một cái nhìn tổng thể để chúng ta hiểu rõ về hiệu quả của nhà lãnh đạo phục vụ.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Chúng ta không cần nhớ những nguyên tắc lãnh đạo này, hoặc những bài tập thực hành lãnh đạo sẽ thảo luận tiếp sau đây - bài exam sẽ không kiểm tra trực tiếp những khái niệm. Thay vào đó, những hiểu biết này sẽ được mô tả ẩn sau những câu hỏi giải quyết tình huống, ngữ cảnh. Khi đọc phần này, hãy suy nghĩ về cách tiếp cận lãnh đạo, và kết hợp chúng trong tư duy Agile.
    </h7>
  </div>
</div>

<br/>

{:#agileLeaderPractise}
## Bài tập thực hành lãnh đạo Agile

Với tư cách lãnh đạo, chúng ta có thể giúp tạo ra một môi trường dự án hiệu quả bằng cách sử dụng các thực tiễn như mô hình hóa hành vi mà chúng ta muốn nhóm tuân theo, truyền đạt tầm nhìn dự án, khuyến khích các bên liên quan hành động và sẵn sàng thách thức.

{:#modelDesiredBehavior}
### Mô hình hành vi mong muốn

Trong Leadership Challenge, Kouzes và Posner mô tả một nghiên cứu kéo dài 10 năm bằng cách hỏi hơn 75,000 người: "Bạn tìm kiếm hoặc ngưỡng mộ những giá trị, đặc điểm cá nhân hoặc tính cách nào ở nhà lãnh đạo của mình?"

Những giá trị sau đây được xếp hạng cao nhất:

・　**Honesty - Trung thực** : Mọi người sẽ không làm theo những nhà lãnh đạo mà họ biết là lửa dối, vì làm như vậy sẽ làm giảm giá trị bản thân của họ. Vì vậy, chúng ta nên đặc biệt chú ý đến tính minh bạch và đảm bảo rằng chúng ta tuân theo những gì chúng ta đã nói. Chúng ta không nên che giấu những sai lầm của mình - chúng ta nên thừa nhận một cách công khai. Đây không chỉ là một cách tiếp cận lành mạnh đối với chúng ta với tư cách là nhà lãnh đạo, mà nó còn là tấm gương cho cách chúng ta muốn nhóm mình hoạt động. Chúng ta không nên làm những việc như hỏi các thành viên trong nhóm về ước tính và sau đó nói rằng chúng ta sẽ tăng gấp đôi trước khi giao cho ban quản lý. Những tuyên bố như vậy làm tổn hại đến uy tín của chúng ta với nhóm và khiến họ có lý do để nghi ngờ tính chính trực của chúng ta. (một cách tiếp cận tốt hơn là giải thích khái niệm thêm một khoản dự phòng vào các ước tính và thảo luận về cách căn cứ vào khoản dự phòng đó dựa trên những kỳ vọng thực tế về những rủi ro liên quan đến dự án).

・　**Forward-looking - Nhìn về phía trước** : Mọi người mong đợi những người dẫn dắt họ hiểu được nơi họ đang đi. Các nhà lãnh đạo nên có khả năng vẽ nên bức tranh cho cả nhóm để mọi người hiểu họ cuối cùng đang hướng tới điều gì.

・　**Competent - Có năng lực** : Người lãnh đạo không cần phải có kỹ năng kỹ thuật mạnh nhất trong nhóm, vì các thành viên trong nhóm thường sẵn lòng cung cấp kiến thức chuyên môn khi được yêu cầu. Tuy nhiên, các nhà lãnh đạo phải là người có năng lực và không phải là người xấu hổ hay trách nhiệm đối với nhóm.

・　**Inspiring - Truyền cảm hứng** : Mọi người muốn được truyền cảm hứng trong công việc của họ, thay vì bị bắt gặp mỗi ngày với cảm giác tiêu điều và u ám. Do đó, các nhà lãnh đạo cần phải tìm cách giải thích tầm nhìn và hành trình của dự án bằng sự nhiệt tình và tinh thần thực sự.

Khi thể hiện những đặc điểm này với tư cách là nhà lãnh đạo, chúng ta không chỉ khuyến khích mọi người làm theo mình mà còn mô hình hóa những hành vi mà chúng ta muốn các thành viên trong nhóm mình thi đua. Trên thực tế, chúng ta đã dẫn dắt bằng những ví dụ thực tiễn.

{:#visionProject}
### Truyền đạt tầm nhìn dự án

Trong cuộc thảo luận trước đây của chúng ta về lãnh đạo phục vụ, chúng ta đã nói về tầm quan trọng của việc truyền đạt và truyền đạt liên tục tầm nhìn dự án để giữ cho các bên liên quan có cùng tầm nhìn về mục tiêu dự án. Một nhà lãnh đạo có thể sử dụng nhiều phương pháp khác nhau để đạt được điều này, dựa trên những gì hiệu quả nhất cho nhóm cụ thể.

Ví dụ: nhóm XP sử dụng phép ẩn dụ, một số nhóm phát triển câu thần chú và các nhóm khác tạo quảng cáo chiêu hàng hoặc dự án Tweeets, trong đó họ giải thích mục đích dự án bằng 140 ký tự trở xuống.

Dù sử dụng phương pháp nào, điều quan trọng là phải thường xuyên truyền đạt các mục tiêu của dự án để đảm bảo rằng tất cả các bên liên quan đều nhận thức được và thích ứng với tầm nhìn.

{:#enableothersAct}
### Cho phép người khác hành động

Để cho phép các thành viên trong nhóm cảm thấy tự tin trong việc đưa ra quyết định và thực hiện các hành động nhằm thúc đẩy dự án một cách hiệu quả, chúng ta cần thúc đẩy một môi trường hợp tác. Điều này liên quan đến việc xây dựng lòng tin giữa các thành viên trong nhóm và củng cố những người khác bằng cách chia sẻ quyền lực. Chúng ta cũng cần tạo ra một môi trường làm việc an toàn, nơi mọi người không ngại hỏi những gì họ có thể nghĩ là câu hỏi ngớ ngẩn. Mọi người học nhanh hơn nhiều khi họ có thể đưa ra câu hỏi mà không sợ bị trả thù hay chế giễu.

Tăng cường sức mạnh cho những người khác bằng cách chia sẻ quyền lực có nghĩa là người quản lý dự án, Scrum Master hoặc người lãnh đạo không giữ kế hoạch hoặc ước tính của dự án cho chính mình. Thay vào đó, người lãnh đạo đảm bảo rằng thông tin và kiến thức được lan truyền trong cả nhóm.

Ví dụ: điều này có thể liên quan đến việc chuyển từ các công cụ lập kế hoạch như biểu đồ Gantt mà chỉ một hoặc hai người có thể cập nhật và duy trì sang sử dụng bảng nhiệm vụ mà cả nhóm có thể tham gia. Khi làm như vậy, thông tin về dự án và trạng thái công việc sẽ dễ tiếp cận hơn với nhóm và dự án sẽ được hưởng lợi vì nhiều người có thể kiểm tra, cập nhật và tối ưu hóa kế hoạch hơn.

![switchTooltochart]({{ site.baseurl }}/assets/images/switchTooltochart.png)

{:#willingchallenge}
### Sẵn sàng thách thức hiện trạng

Thách thức hiện trạng có nghĩa là chúng ta tìm kiếm những cách đổi mới để thay đổi, phát triển và cải thiện - sau đó, thử nghiệm và chấp nhận rủi ro bằng cách liên tục tạo ra những chiến thắng nhỏ và học hỏi từ những sai lầm của chúng ta. Lặp lại là mô hình thu nhỏ hoàn hảo để thử nghiệm. Chúng ta có thể thử những ý tưởng mới cho một hoặc hai lần lặp lại trước khi cam kết với chúng. Nếu các ý tưởng hoạt động, chúng ta có thể thể chế hóa chúng. Nếu chúng không hoạt động, nó không tổn thất lớn; ít nhất chúng ta đã cố gắng, và chúng ta đã học được điều gì đó từ kinh nghiệm.

Cho phép các bên liên quan đề xuất những ý tưởng mới để cải tiến và sau đó, cho họ một cơ hội thử những ý tưởng đó là một cách để củng cố khái niềm rằng ý tưởng của mọi người đều có giá trị. Không có gì thất vọng hơn việc có một ý tưởng tốt rơi vào tai người điếc. Nếu điều này xảy ra, mọi người sẽ sớm ngừng cố gắng đưa ra các đề xuất và sẽ không còn quan tâm đến dự án nữa. Vì vậy, để duy trì sự tham gia của các bên liên quan, chúng ta nên tận dụng các cơ hội mà các dự án Agile mang lại cho chúng ta để thực hiện các thử nghiệm nội bộ, quy mô nhỏ trong một môi trường hỗ trợ, ít rủi ro.

Với tư cách nhà lãnh đạo, chúng ta cần khuyến khích nhóm của mình tahch1 thức hiện trạng về cách chúng ta hoạt động, không chỉ vì các thành viên trong nhóm có vị trí tuyệt vời để đề xuất cải tiến quy trình, mà còn vì làm như vậy giúp thúc đẩy họ. Để đạt được thành công trong nỗ lực này, chúng ta cần có kỹ năng tư duy phân tích giúp nhóm của mình lên ý tưởng và giải pháp cũng như kỹ năng lắng nghe tích cực để đảm bảo chug1 ta hiểu chính xác các đề xuất của mọi người.

{:#leadershiptask}
## Nhiệm vụ của Lãnh đạo

Trước khi chuyển sang chương tiếp theo, chúng ta sẽ đúc kết lại thảo luận về các nguyên tắc và tư duy Agile bằng cách xem xét một số nhiệm vụ lãnh đạo trong đề cương nội dung kỳ thi cho lĩnh vực này. Mặc dù khái niệm này sẽ được thảo luận chi tiết hơn trong các chương sau, chúng ta sẽ giới thiệu chúng tở đây để giúp hiểu các nhiệm vụ cụ thể của vùng kiến thức này mà còn cả các mục tiêu và giá trị cơ bản của phương pháp tiếp cận Agile đối với lãnh đạo.

{:#visualizePracticeTransparency}
### Thực hành tính minh bạch thông qua hình ảnh hóa

"Minh bạch" có nghĩ là cởi mở và trung thực, không chỉ về tiến trình và thành tích của chúng ta, mà còn về các vấn đề và trở ngại của chúng ta.

Các nhóm Agile thể hiện sự minh bạch bằng cách hiển thị công khai công việc, tiến độ và kết quả đánh giá của họ cho các bên liên quan khác xem. Khi bước vào một phòng nhóm Agile, ta sẽ thấy các biểu đồ hiển thị vận tốc, tỷ lệ sai sót và kết quả của lần xem xét cuối cùng - bao gồm cả những gì đang hoạt động tốt và những gì cần cải thiện là điều bình thường.

Khi không có gì phải che giấu và mọi thứ được chia sẻ, các cuộc trò chuyện có thể thẳng thắn hơn và mọi người có thể bớt đề phòng hơn và tập trung vào việc cải thiện. Mọi người sẽ không sợ hãi hoặc miễn cưỡng thảo luận về các vấn đề hoặc sai lầm, bởi vì môi trường minh bạch xung quanh họ là tấm gương để họ được chấp nhận và mong đợi để nói về các vấn đề cũng như tiến bộ.

{:#createasafeenv}
### Tạo môi trường an toàn cho thử nghiệm

Khi mọi người tin rằng có thể thử các phương pháp tiếp cận mới và họ sẽ không bị chỉ trích nếu không thành công ngay lần đầu tiên, thì nhiều khả năng họ sẽ tiếp tục và thử những điều mới. Chính trong những thử nghiệm này, những sáng kiến và đột phá hữu ích nhất thường được tạo ra. Một mô hình phổ biến là khi mọi người ngày càng vững chắc trong sự nghiệp, họ càng lo lắng hơn về việc ngăn chặn thất bại và tỏ ra kém cỏi hơn so với đồng nghiệp của mình, điều này có thể hạn chế sự sẵn sàng thử nghiệm của họ.

Nếu một người bạn yêu cầu chúng ta giúp đỡ vào cuối tuần với tư cách là người giải trí cho buổi tiệc của trẻ em, chúng ta có thể thử một số trò chơi khác nhau và giúp bọn trẻ vui vẻ. Nếu bọn trẻ không thích cái đầu tiên, đó không phải là vấn đề lớn - chúng ta sẽ thử cái khác. Tuy nhiên, nếu chúng ta tình cờ có bằng tiến sĩ về tâm lý trẻ em, nhiều bài báo được xuất bản về hạnh phúc trẻ em và một hoạt động tư vấn với tỷ lệ giờ cao, thì nỗi lo về uy tín và danh tiếng của chúng ta có thể hạn chế sự sẵn sàng thử các cách tiếp cận mới của chúng ta.

Đối với nhóm Agile, chúng ta cần tạo ra môi trường an toàn để thử nghiệm. Điều này bao gồm việc khuyến khích các thử nghiệm và trải nghiệm, không tập trung vào các thử nghiệm đã thất bại và khuyến khích việc hình thành các ý tưởng mới. Ở Toyota, họ có hòm thư góp ý để nhân viên gửi ý kiến. Bây giờ, điều này không có gì mới; hầu hết các tổ chức có một hộp thư như vậy. Ở hầu hết công ty, ban lãnh đạo sẽ chọn ra một hoặc hai ý tưởng tốt nhất để thực hiện và sau đó thưởng cho người gửi một khoản tiền thưởng lớn nếu đề xuất của họ hoạt động hiệu quả. Tuy nhiên, Toyota dành phần thưởng nhỏ cho tất cả những ai gửi ý tưởng. Điều này dẫn đến rất nhiều đề xuất được đưa ra. Trong quyển sách của Matthew May, The Elegant Solution - Giải pháp thanh lịch, ông nói rằng Toyota thực hiện hơn một triệu đề xuất mỗi năm! Đó là 3,000 đề xuất hoặc thử nghiệm mỗi ngày. Khi chúng ta đang đổi mới với tốc độ đó, đổi thủ cạnh tranh sẽ thực sự khó bắt kịp.

{:#newtechnprocess}
### Thử nghiệm với các kỹ thuật và quy trình mới

Không phải tất cả các đề xuất cải tiến đều thành công. Một số ý tưởng nghe có vẻ thất bại và một số ý tưởng có vẻ hoạt động không được tốt lắm. Các thực sự duy nhất để tìm hiểu xem một quy trình hoặc kỹ thuật mới có hiệu quả với dự án của chúng ta hay không là thử nghiệm. Một yếu tố Agile quan trọng là hỗ trợ thử nghiệm qua những vòng lặp ngắn để xem những gì hiệu quả và nên được thể chế hóa, và những gì không và nên loại bỏ.

Các nhà di truyền học thích nghiên cứu các kiểu thừa kế ở ruồi bởi vì những loài côn trùng này sinh sản trong ngày nên chúng thu được kết quả nhanh chóng. Các lần lặp lại ngắn cung cấp các chu kỳ phản hồi ngắn giống nhau và cung cấp các khoảng thời gian thử nghiệm sẵn sàng cho các cách tiếp cận mới.

{:#shareknowledge}
### Chia sẻ kiến thức thông qua cộng tác

Điều quan trọng là các nhóm phải chia sẻ kiến thức về sản phẩm mà họ đang làm và cách mọi thứ hoạt động trong nhóm họ. Tuy nhiên, việc viết ra tất cả những điều này mất nhiều thời gian và mọi người thường không thích đọc nó.

Các kỹ sư cũng có một định kiến đáng có là không thích sản xuất tài liệu khi họ có thể đang "làm công việc thực" và thậm chí ít có xu hướng "đọc hướng dẫn" khi họ có thể mày mò.

Đây là lý do tại sao công việc hợp tác - thông qua việc ghép nối nhân viên hoặc chuyển giao kiến thức đặc biệt thông qua vị trí chung - đã nổi lên như một phương pháp hay nhất Agile. Bằng cách làm việc với mọi người, chúng ta học được những gì họ làm, cách họ giải quyết vấn đề và cách giúp họ hiệu quả nhất khi họ gặp khó khăn. Chỉ cần thay đổi người làm việc cùng, kiến thức dự án có thể được phân tán trong cả nhóm, giảm tác động của việc mất thông tin nếu một thành viên trong nhóm rời đi.

{:#encourageEmergentLeader}
### Khuyến khích khả năng lãnh đạo nổi bật thông qua một môi trường an toàn

Khả năng lãnh đạo xuất sắc là khi một thành viên trong nhóm chủ động và thử một cách tiếp cận mới sau khi được đồng ý của nhóm. Các thành viên trong nhóm Agile không chỉ được trao quyền để đưa ra quyết định mà còn có khả năng lãnh đạo các hoạt động cải tiến. Nếu ai đó xác định một quy trình hiệu quả hơn, họ được khuyến khích thử một thử nghiệm để chúng minh xem nó có thể hoạt động hay không.

{:#chappterReview}
# Chapter Review

**1. Which of the following is NOT an advantage of limiting work in progress? Cái nào dưới đây không phải là điểm mạnh của việc giới hạn công việc đang thực hiện?**

 A. It reduces the potential need to rework a large collection of flawed, partially completed items. (Giảm khả năng làm lại một lượng lớn công việc đã hoàn thành một phần hay những thiếu sót.)

 B. It helps optimize throughput to make processes work more efficiently. (Nó giúp tối ưu quy trình một cách hiệu quả.)

 C. It brings bottlenecks in the production process to the surface so they can be identified and resolved. (Nó đưa ra những nút thắt cổ chai trong quá trình sản xuất để có thể xác định và giải quyết.)

 D. It maximizes resource utilization to make processes work more efficiently. (Nó tối đa hóa việc sử dụng tài nguyên để làm cho các quy trình hoạt động hiệu quả hơn.)

**2. The relationship between leadership and management in agile methods is: (Mối quan hệ giữa quản lý và lãnh đạo là:)**

 A. Leadership replaces all aspects of management. (Lãnh đạo thay thế tất cả các khía cạnh của quản lý)

 B. Leadership is subsidiary to management. (Lãnh đạo là con của quản lý)

 C. Management and leadership are used together. (Quản lý và lãnh đạo được sử dụng cùng nhau)

 D. Management and leadership are incompatible. (Quản lý và lãnh đạo không tương thích với nhau)

**3. The core values of XP include: (Giá trị cốt lỗi của XP bao gồm:)**

 A. Courage, communication, input (Dũng cảm, giao tiếp, đầu vào)

 B. Simplicity, control, respect (Đơn giản, kiểm soát, tôn trọng)

 C. Feedback, simplicity, communication (Phản hồi, đơn giản, giao tiếp)

 D. Solutions, feedback, control (Giải pháp, phản hồi, kiểm soát)

**4. In the Agile Manifesto, what is valued more than processes and tools?**

  A. Customer collaboration

  B. Individuals and interactions

  C. Working software

  D. Responding to change

**5. The acronym WIP stands for:**

  A. Worth in performance

  B. Work in progress

  C. Waste in process

  D. Work is progressing

**6. The three pillars of Scrum are:**

  A. Transparency, Communication, Adaptation

  B. Inspection, Adaptation, Evolution

  C. Adaptation, Inspection, Communication

  D. Transparency, Inspection, Adaptation

**7. On a typical agile team, who has the best insight into task execution?**

  A. Project manager

  B. Team members

  C. ScrumMaster

  D. Agile coach

**8. Which of the following Agile Manifesto values deals most closely with WIP ?**

  A. Customer collaboration over contract negotiation

  B. Individuals and interactions over processes and tools

  C. Working software over comprehensive documentation

  D. Responding to change over following a plan

**9. What is one of the three questions that are addressed in the daily scrum?**

  A. What have I done since the last daily scrum?

  B. Why didn’t I get my work done yesterday?

  C. How will I do my work to day?

  D. What is my plan for the week?

**10. What are three of the seven lean core concepts?**

  A. Eliminate waste, empower the team, deter decisions

  B. Build quality in, exterminate waste, optimize learning

  C. Optimize the whole, defer decisions, amplify learning

  D. Deliver decisions, amplify the team, evaluate waste

**11. The four primary roles of a servant leader include :**

  A. Shielding team members from interruptions

  B. Resolving conflicts

  C. Determining which stories to include in an iteration

  D. Assigning tasks to the team members

**12. In Scrum, the definition of done is created with the input of everyone except the:**

  A. Development team

  B. Product owner

  C. ScrumMaster

  D. Process owner

**13. In the lean approach, which of the following wouldn’t be considered an example of one of the seven forms of waste?**

  A. The handoff between coding and testing

  B. Testing the code

  C. Code that is waiting for testing

  D. Assigning a developer to work on two projects at the same time

**14. The XP core practices include:**

  A. Whole team, planning games, small releases

  B. One team, process game, big releases

  C. Paired team, planning games, quick releases

  D. Build team, process game, incremental releases

**15. Which of the following is one of the planned opportunities for inspection and adaptation in the Scrum method?**

  A. Velo city review meeting

  B. Sprint risk meeting

  C. Daily scrum

  D. Retrospective planning meeting

**16. Which of the following is an Agile Manifesto value?**

  A. Individuals and interactions over following a plan

  B. Working software over processes and tools

  C. Responding to change over comprehensive documentation

  D. Customer collaboration over contract negotiation

**17. The agile triangle of constraints is said to be inverted from the traditional triangle because it allows:**

  A. Scope and time to vary instead of cost

  B. Cost and time to vary instead of scope

  C. Scope and cost to be fixed instead of time

  D. Scope to vary while time and cost are fixed

**18. Which of the following Agile Manifesto principles reflects the agile focus on team empowerment?**

  A. Working software is the primary measure of progress.

  B. Welcome changing requirements, even late in development.

  C. Simplicity—the art of maximizing the amount of work not done—is essential.

  D. Build projects around motivated individuals.

**19. The Kanban pull system means that:**

  A. Kanban team members “pull” work from each other, pairing up as needed.

  B. Each time a work item is completed, the next work item is “pulled” into that stage of the process.

  C. Iterations are “pulled” into the process as needed to keep the work organized.

  D. Kanban teams have shorter work queues, which means that the work takes longer to complete (as shown by Littles Law).

**20. Which of the following isn’t a core aspect of the agile mindset?**

  A. Welcome change

  B. Learn through discovery

  C. Respect the process

  D. Deliver value continuously

------------------- HẾT CHƯƠNG 1 -------------------

Giỡn chứ coi đáp án đã nha: Lười dịch với lại đọc cho hiểu để đi thi nên để nguyên tiếng Anh chỗ này. Tới hồi không hiểu thì sẽ dịch sau:

1. Answer: D

Explanation: Since this question is looking for the answer that is NOT an advantage of limiting work in progress (WIP), if an option is true, that means it is not the answer we are looking for. Limiting WIP does reduce the potential need for rework. It also improves process efficiency and helps us find production bottlenecks. The only option listed here that is NOT an advantage of limiting WIP is the one that refers to maximizing resource utilization. Limiting WIP focuses on optimizing throughput, not resources, and we may actually decrease resource optimization to get more throughput.

2. Answer: C

Explanation: Agile methods employ a combination of management and leadership. Leadership neither totally replaces nor is subsidiary to management—and since the two approaches can be used together, they aren’t incompatible.

3. Answer: C

Explanation: The correct XP core values from the options presented are feedback, simplicity, and communication. The options “input,” “solutions,” and “control” are not core values of XP.

4. Answer: B

Explanation: The first value of the Agile Manifesto is “Individuals and interactions over processes and tools.” Therefore, “individuals and interactions” is the correct choice.

5. Answer: B

Explanation: WIP stands for “work in progress” or “work in process,” not “worth in performance,” “waste in process,” or “work is progressing.”

6. Answer: D

Explanation: The three pillars are Transparency, Inspection, and Adaptation. Evolution and communication are both admirable goals, but they are not Scrum pillars.

7. Answer: B

Explanation: Agile’s servant leadership approach recognizes that the “doers” of the work, the team members, are closest to the work and therefore have the best insight into its execution. This is why agile project managers, ScrumMasters, and coaches defer to the team’s decisions about how best to execute the work.

8. Answer: C

Explanation: The second value of the Agile Manifesto—“Working software over comprehensive documentation”—is most closely related to WIP because it recommends that we focus on results and completed deliverables, rather than partially completed or in-progress work. If documentation efforts are slowing down the team’s ability to complete a deliverable (keeping a lot of work in progress), they should be reduced as much as possible to support the ultimate goal of creating a useful, functional product.

9. Answer: A

Explanation: The three questions addressed in the daily scrum are: “What have I done since the last daily scrum?” “What do I plan to do today?” and “Are there any impediments to my progress?” To keep the meeting focused and moving quickly the other questions listed in the answer choices are not discussed in the daily scrum.

10. Answer: C

Explanation: The valid lean core concepts on this list are optimize the whole, defer decisions, and amplify learning. (The remaining lean core concepts are eliminate waste, empower the team, build quality in, and deliver fast.) The remaining answer options all include at least one incorrect item— “deter decisions,” “exterminate waste,” “deliver decisions,” and “evaluate waste.” Be sure you read each answer choice carefully—“defer” looks very much like “deter,” especially when you are under pressure.

11. Answer: A

Explanation: The four primary roles of a servant leader are shielding the team from interruptions, removing impediments to progress, communicating the project vision, and “carrying food and water.” Although we haven’t discussed the other three answer options in chapter 1, we’ll see in later chapters that they aren’t correct. Servant leaders don’t take the lead in resolving conflicts—they first let the team try to resolve issues on their own. The team determines which stories to include in an iteration, rather than accepting the stories chosen by the team leader. Finally, task assignment isn’t a servant leadership role; agile teams are encouraged to select their own work.

12. Answer: D

Explanation: The whole team, including the development team, product owner, and ScrumMaster, is responsible for creating the shared definition of done. Since “process owner” is a made-up term, this is the correct choice for someone who would NOT be involved in defining done.

13. Answer: B

Explanation: Testing the code is the only one of these options that wouldn’t be considered waste in lean. The seven wastes of lean are partially done work, extra processes, extra features, task switching, waiting, motion, and defects. Handoffs are an example of motion, code that is waiting for testing is partially done work, and a developer who is working on multiple projects is an example of task switching.

14. Answer: A

Explanation: The XP core practices include whole team, planning games, and small releases. The choices “one team,” “process game,” “big releases,” “paired team,” “quick releases,” “build team,” and “incremental releases” are not XP core practices.

15. Answer: C

Explanation: The meetings that are Scrum’s planned opportunities for inspection and adaptation are the sprint planning meeting, daily scrum, sprint retrospective, and sprint review. Velocity review meetings, sprint risk meetings, and retrospective planning meetings are not recognized Scrum events.

16. Answer: D

Explanation: The third value of the Agile Manifesto is “Customer collaboration over contract negotiation.” While the other choices use terms from the other three agile values, they aren’t combined correctly.

17. Answer: D

Explanation: Unlike the traditional constraint triangle, in which scope is fixed and time and cost may need to bend to achieve that planned scope, agile teams typically allow scope to vary within fixed parameters of cost and time. In other words, they aim to deliver the most value they can by X date within X budget.

18. Answer: D

Explanation: Agile Manifesto principle five, “Build projects around motivated individuals” addresses the importance of giving teams the environment and support they need, and trusting them to get the job done. Supporting and trusting the team members means recognizing that they are experts at what they do, and that they can work most effectively if they are empowered to plan and organize their own work.

19. Answer: B

Explanation: In Kanbans “pull system,” each time the team completes an item of work, it triggers a “pull” to bring in the next item to that stage. The other answer options are all incorrect. Although Kanban teams do tend to have shorter work queues (due to the pull system and limiting WIP), Littles Law actually demonstrates that shorter queues reduce how long it takes to complete the work, rather than lengthening it.

20. Answer: C

Explanation: The concepts of welcoming change, learning through discovery, and continuous delivery of value are all core aspects of the agile mindset. That leaves the option “respect the process” as the outlier. Also, the first value of the Agile Manifesto—“individuals and interactions over processes and tools”—is another indication that “respect the process” isn’t part of the agile mindset.
