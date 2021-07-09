---
layout: post
title:  "PMI ACP - Chapter 2 - Value Driven Delivery"
author: hiepvh
categories: [ PMI ACP ]
tags: [ pmi-acp, pm ]
image: assets/images/valuedrivendelivery.jpg
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: true
hidden: false
# rating: 4.5
---

<!-- Title Block -->
<div id="titleBlock" style="text-align: center;">
  <h4 style="margin-bottom: 0px;"> CHAPTER 2 </h4>
  <hr style="width: 50%;">
  Value-Driven Delivery <br/> Phân phối định hướng giá trị
</div>

{:#tblContent}
| Contents |
|-----|
| [ Tổng hợp kiến thức domain II]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#summary) |
| [ Phân phối hướng giá trị là gì? ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#whatvaluedrivendelivery) |
| [  - Mang lại giá trị sớm (Eat your dessert First!) ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#delivervalueearly) |
| [  - Tối thiểu lãng phí ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#minimizevalue) |
| [ Đánh giá giá trị ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#assessingvalue) |
| [  - Các chỉ số đánh giá tài chính ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#financialAssessmentMetrics) |
| [　&#9;・　Return on Investment - Lợi tức đầu tư (ROI) ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#roi) |

| [  - SPRINT ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#sprint) |
| [　&#9;・　Vai trò trong nhóm dự án Scrum ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#scrumRoles) |


<br/>
{:#summary}
# Tổng hợp kiến thức domain II

Domain II này thảo luận về vùng kiến thức phân phối hướng giá trị trong bài exam, có khoảng 20% câu hỏi, hoặc khoảng 24 câu.

Domain này giải quyết tối đa hóa giá trị kinh doanh, bao gồm cả độ ưu tiên, phân phối tiến triển, kiểm thử và kiểm định.

<div id="titleBlock" style="font-size: 12px;">
  <h5>Chủ đề chính</h5>

  <li>Agile contracting - Hợp đồng Agile</li>

  <li>Agile project accounting principle - Nguyên tắc kế toán dự án Agile</li>

  <li>Agile risk management - Quản lý rủi ro Agile</li>

  <li>Agile tooling - Công cụ Agile</li>

  <li>Compliance/regulatory compliance - Tuân thủ/Tuân thủ quy định </li>

  <li>Cumulative flow diagrams (CFDs) - Sơ đồ luồng tích lũy</li>

  <li>Customer-valued prioritization - Ưu tiên giá trị khách hàng</li>

  <li>Earned value management (EVM) for agile projects - Quản lý giá trị đạt được trong dự án Agile</li>

  <li>Frequent verification and validation - Xác minh và xác thực thường xuyên</li>

  <li>Incremental delivery - Phân phối gia tăng   </li>

  <li>Managing with agile KPIs - Quản lý Agile KPIs  </li>

  <li>Minimal viable product (MVP) - Sản phẩm khả thi tối thiểu  </li>
    <ul>> Minimal marketable feature (MMF) - Tính năng tối thiểu có thể bán trên thị trường</ul>

  <li>Prioritization schemes  - Các kế hoạch ưu tiên </li>
    <ul>> Phân tích Kano</ul>
    <ul>> MoSCoW</ul>

  <li>Relative prioritization/ ranking - Mức độ ưu tiên/xếp hạng tương đối  </li>

  <li>ROI/NPV/IRR  </li>

  <li>Software development practices - Thực hành phát triển phần mềm   </li>
    <ul>> Continuous integration - Tích hợp liên tục</ul>
    <ul>> Exploratory and usability testing - KHám phá và kiểm thử khả năng sử dụng</ul>
    <ul>> Red, Green, Refactor</ul>
    <ul>> TDD/TFD/ATDD</ul>

  <li>Task/Kanban boards - Bảng Kanban/ Nhiệm vụ </li>

  <li>Value-driven delivery - Phân phối hướng giá trị   </li>

  <li>Work in progress (WIP) - Công việc đang thực thi  </li>

  <br/>
  <h5>Task - Nhiệm vụ</h5>
  <li>Lập kế hoạch công việc từng bước.</li>
  <li>Đạt được sự đồng thuận về các tiêu chí chấp nhận trong thời gian.</li>
  <li>Điều chỉnh quy trình cho tổ chức, nhóm và dự án</li>
  <li>Phát hành các sản phẩm khả thi tối thiểu (MVP)</li>
  <li>Làm việc theo từng gói nhỏ.</li>
  <li>Đánh giá thường xuyên.</li>
  <li>Tinh chỉnh thường xuyên.</li>
  <li>Tối ưu hóa các yếu tố môi trường, vận hành và cơ sở hạ tầng.</li>
  <li>Xem xét và kiểm tra thường xuyên.</li>
  <li>Cân bằng giá trị gia tăng và giảm thiểu rủi ro.</li>
  <li>Định kỳ tái đánh giá độ ưu tiên để tối đa hóa giá trị.</li>
  <li>Ưu tiên các yêu cầu phi chức năng.</li>
  <li>Xem xét và cải tiến quy trình và sản phẩm tổng thể.</li>

</div>

Phân phối giá trị, đặc biệt là giá trị kinh doanh, là thành phần cốt lõi của phương thức Agile. Khái niệm này được thêu dệt vào Agile DNA trong cả hai giá trị trong Tuyên bố Agile (Working software over comprehensive documentation - Phần mềm làm việc được hơn là tài liệu đầy đủ) và trong nguyên tắc của tuyên bố Agile (Develiver working software frequently - Phân phối phần mềm làm việc liên tục, Working software is the primary measure of progress - Phần mềm làm việc là đo lường cơ sở của quy trình).

Trong chương này, chúng ta sẽ tổ chức các thực hành Agile trong domain này vào 5 chủ đề: assessing value (đánh giá giá trị), prioritizing value (độ ưu tiên giá trị), delivering incrementally (phân phối tăng dần), agile contracting (hợp đồng agile), và cuối cùng, verifying and validating value (đánh giá và thẩm định giá trị).

Các chủ đề được sử dụng để sắp xếp các chủ đề trong mỗi chương không phải là thuật ngữ chính thức và sẽ không xuất hiện trong bài kiểm tra; chúng ta chỉ đơn giản là sử dụng các danh mục này để tổ chức và thiết lập bối cảnh cho việc thảo luận về các khái niệm, công cụ và thực hành Agile được đề cập trong mỗi chương.


{:#whatvaluedrivendelivery}
# Phân phối hướng giá trị là gì?

Hãy bắt đầu bằng việc định nghĩa phân phối hướng giá trị. Lý do các dự án được thực hiện đó là sinh ra giá trị kinh doanh, để nó cung cấp lợi ích hoặc cải thiện dịch vụ. Ngay cả những dự án tuân thủ quy định và an toàn cũng có thể được thể hiện bằng giá trị kinh doanh bằng cách xem xét rủi ro kinh doanh và tác động của việc không thực hiện chúng. Vì vậy, nếu phân phối giá trị là lý do để thực hiện các dự án, thì phân phối hướng giá trị phải là trọng tâm của chúng ta trong suốt dự án.

Trong chương I, chúng ta đã trả lời cho câu hỏi: Tại sao sử dụng Agile? trong một bối cảnh lịch sử, dựa trên sự khác nhau giữa công việc công nghiệp và công việc tri thức. Nhưng chúng ta có thể cũng trả lời câu hỏi này từ khía cạnh của giá trị là phương pháp Agile có thể phân phối trong sự so sánh với phương pháp non-Agile. Cái này được gọi là "mệnh đề giá trị Agile", và nó thì được mô tả trực quan hơn, như hình dưới đây.

![agilevalueproposition]({{ site.baseurl }}/assets/images/agilevalueproposition.png)

Trong chương này, chúng ta sẽ thảo luận về việc phân phối sớm giá trị doanh nghiệp (dưới cùng bên trái trên sơ đồ đề xuất giá trị) và bắt đầu thảo luận về giảm thiểu rủi ro sớm (dưới cùng bên phải) sẽ được tiếp tục đề cập trong chương 6. Chúng ta sẽ đề cập đến khả năng hiển thị trong chương 3 và khả năng thích ứng trong chương 5.

Tối đa hóa gái trị là một chủ đề, hoặc thần chú bao quát, dành cho các nhóm Agile. Khi đứng trước một quyết định, chúng ta sẽ hỏi: Lựa chọn nào sẽ mang lại nhiều giá trị nhất cho khách hàng?

Việc tập trung cung cấp giá trị thúc đẩy nhiều hoạt động và quyết định trong dự án Agile và là mục tiêu cuối cùng của nhiều phương pháp thực hành trong bộ công cụ Agile.

Đây là một thành phần thiết yếu của các phương pháp Agile, trong số tất cả các domain, PMI đã cung cấp cho domain phân phối hướng giá trị có trọng lượng nhất đối với kỳ thi.

Vì vậy, đây là một trong những chủ đề Agile quan trọng nhất, gắn kết nhiều khái niệm Agile cơ bản với nhau, chẳng hạn như ưu tiên, phân phối gia tăng và phát triển theo hướng thử nghiệm.

{:#delivervalueearly}
## Mang lại giá trị sớm (Eat your dessert First!)

Một trong những cách quan trọng mà các nhóm Agile cố gắng tối đa hóa giá trị là phân phối giá trị sớm. Điều này có nghĩa là họ đặt mục tiêu cung cấp các phần có giá trị cao nhất của dự án càng sớm càng tốt. Có một số lý do quan trọng cho cách tiếp cận này.

Thứ nhất, cuộc sống ngắn ngủi, nhiều thứ xảy ra, và một dự án chạy càng lâu thì chân trời càng dài đối với những rủi ro có thể làm giảm giá trị như thất bại, giảm lợi ích, xói mòn cơ hội... Để tối đa hóa thành công, chúng ta phải cố gắng cung cấp càng nhiều giá trị cao càng sớm càng tốt, trước khi mọi thứ thay đổi hoặc đi ngang.

Lý do chính thứ hai để tập trung vào việc phân phối sớm là sự hài lòng của các bên liên quan đóng một vai trò quan trọng trong thành công của dự án. Các nhà đầu tư và Product owner gắn bó, cam kết là rất quan trọng để loại bỏ các trở ngại của dự án và tuyên bố thành công. Mỗi nhóm đều đang trong giai đoạn thử nghiệm khi dự án bắt đầu, bởi vì các nhà đầu tư có thể không chắc liệu nhóm có thực hiện nó hay không. Bằng cách cung cấp sớm các yếu tố có giá trị cao, nhóm thể hiện  sự hiểu biết về nhu cầu của các bên liên quan, cho thấy rằng họ nhận ra các khía cạnh quan trọng nhất của dự án và chứng minh khả năng của họ có thể thực hiện được. Kết quả hữu hình giúp nhóm nâng cao được lòng tin của các bên liên quan, xây dựng mối quan hệ với họ và đưa họ vào cuộc sớm, tạo ra mộ vòng kết nối hỗ trợ.

Nói tóm lại, phân phối theo định hướng giá trị có nghĩa là đưa ra các quyết định ưu tiên các hoạt động gia tăng giá trị và nỗ lực giảm thiểu rủi ro cho dự án, sau đó thực hiện dựa trên các ưu tiên này.

{:#minimizevalue}
## Tối thiểu lãng phí

Các hoạt động lãng phí làm giảm giá trị. Đây là lý do tại sao các phương pháp Agile đã áp dụng khái niệm tinh gọn để giảm thiểu lãng phí và các hoạt động bổ sung không có giá trị khác. Ví dụ, trong dự án đang được thực hiện, một nhóm Agile có thể giảm hoặc hoãn các hoạt động được tổ chức yêu cầu nhưng không trực tiếp tập trung vào việc cung cấp giá trị, chẳng hạn như theo dõi và báo cáo thời gian chính thức. Để tối đa hóa giá trị, sẽ hữu ích khi truy cập lại danh sách bảy lãng phí của Poppendiecks:

» Partially done work - Công việc hoàn thành một phần

» Extra processes - Quy trình bổ sung

» Extra features - Chức năng bổ sung

» Task switching - Thay đổi nhiệm vụ

» Waiting - Chờ đợi

» Motion - Chuyển động

» Defects - Khiếm khuyết

Bất cứ nơi nào nhận thấy có các hoạt động gây lãng phí trong dự án, chúng ta muốn cố gắng loại bỏ chúng.

{:#assessingvalue}
# Đánh giá giá trị

Giá trị kinh doanh thường được đánh giá về mặt tài chính, bắt đầu bằng việc đánh giá giá trị của các dự án tiềm năng trước khi chúng được chấp thuận để tiến hành. Đúng là một số dự án được thực hiện vì mục đích an toàn hoặc tuân thủ quy định và không có giá trị tiền tệ dễ dàng xác định. Để đánh giá giá trị của các dự án này, tổ chức có thể xem xét các phân nhánh tài chính của việc không thực hiện dự án, chẳng hạn như rủi ro doanh nghiệp sẽ bị đóng cửa, bị đánh giá phạt tiền hoặc bị kiện. Một lựa chọn khác là chỉ cần gắng nhãn dự án là bắt buộc và không dành thêm thời gian để cố gắng định lượng giá trị của nó.

{:#financialAssessmentMetrics}
# Các chỉ số đánh giá tài chính

Đối với các dự án kinh doanh, giá trị thường được ước tính bằng cách sử dụng các thước đo tài chính như lợi tức đầu tư (ROI), tỷ suất hoàn vốn nội bộ (IRR) và giá trị hiện tại ròng (NPV). Các số liệu này về cơ bản được sử dụng theo cùng một cách cho các dự án Agile cũng như cho các dự non-agile. Hãy bắt đầu bằng cách xem xét những lợi ích của các chỉ số này.

Sử dụng các công thức tài chính để đánh giá giá trị của một dự án loại bỏ thành kiến và cảm xúc cá nhân khỏi quá trình lựa chọn và biện minh cho các dự án. Thay vào đó, chúng ta có thể tập trung vào việc so sánh một biến chung (lợi nhuận tài chính) giữa các dự án. Mặc dù có thể có các yếu tố bổ sung để xem xét làm tăng giá trị theo những cách khác, nhưng ưu điểm của các công cụ tài chính này là kết quả của chúng "về mặt con số" (về lý thuyết) và khách quan hơn so với các mô hình lựa chọn dự án khác, (tuy nhiên trong thực tế, các đầu vào được sử dụng cho các tính toán có thể bị thao túng để thay đổi kết quả).

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Các chỉ số tài chính có thể không phải là một chủ đề lớn cho kỳ thi, vì vậy chúng ta có thể không thấy bất cứ câu hỏi nào về ROI, NPV hoặc IRR. Bất kỳ câu hỏi nào chúng ta thấy có khả năng liên quan đến việc giải thích ý nghĩa của các con số này trong một tình huống nhất định. Chúng ta sẽ không được yêu cầu xác định các thuật ngữ này hoặc thực hiện bất cứ phép tính nào. Trong cuộc thảo luận này, chúng ta sẽ hiển thị một số biểu đồ ví dụ để giúp mình họa những khái niệm này cho những người có thể không quen thuộc với chúng. Nhưng đừng để các ví dụ và hình ảnh của làm ta lo sợ; thông tin chúng ta cần biết cho kỳ thi rất đơn giản, như được chỉ ra trong các mẹo làm bài thi bên dưới.
      <br/>
    </h7>
  </div>
</div>

<br/>

{:#roi}
<div id="toolkitBox">
  <div id="toolkitIcon">T&T</div>
  <h2 id="toolkitContent">Return on Investment - Lợi tức đầu tư (ROI)<br/><hr/></h2>
</div>

<br/>

Lợi tức đầu tư, hay ROI, đo lường khả năng sinh lời của một khoản đầu tư bằng cách tính tỷ lệ giữa lợi ích nhận được từ khoản đầu tư đó so với số tiền đã đầu tư vào đó. ROI được biểu thị bằng tỷ lệ phần trăm và tỷ lệ phần trăm đó càng cao, lợi tức mà dự án dự kiến mang lại càng tốt.

> ROI = Tỷ lệ giữa lợi ích nhận được từ một khoản đầu tư so với số tiền đầu tư vào đó, được biểu thị bằng phần trăm.
