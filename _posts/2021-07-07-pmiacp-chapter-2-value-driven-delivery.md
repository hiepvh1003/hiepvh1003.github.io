---
layout: post
title:  "PMI ACP - Chapter 2 - Value Driven Delivery"
author: hiepvh
categories: [ PMI ACP ]
tags: [ pmi-acp, pm ]
image: assets/images/valuedrivendelivery.jpg
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: false
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
| [　&#9;・　Present Value - Giá trị hiện tại ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#presentvalue) |
| [　&#9;・　Net Present Value (NPV) - Giá trị hiện tại ròng ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#netpresentvalue) |
| [　&#9;・　Internal Rate of Return (IRR) - Tỷ lệ hoàn vốn nội bộ ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#internalRateReturn) |
| [　&#9;・　Earned Value Management (EVM) - Quản lý giá trị nhận được ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#evm) |
| [　&#9;　Sử dụng EVM cho các dự án Agile ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#usingEVM) |
| [　&#9;　Xây dựng một công cụ giá trị nhận được Agile ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#earnedvaluetool) |


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

Mặc dù ROI là một số liệu hữu ích, nhưng nó có thể không cho chúng ta biết giá trị thực sự mà một dự án sẽ mang lại. Để biết lý do tại sao, chúng ta hãy xem một ví dụ. Hình dưới đây cho thấy một dự án sẽ chạy từ tháng Một đến tháng Sáu và sau đó đưa ra một giải pháp sẽ tạo ra một số lợi nhuận tài chính. Từ tháng Một đến tháng Sáu, chúng ta sẽ chi tiền cho dự án, trả tiền theo giờ cho các nguồn lực  (được thể hiện bằng tiền màu nhạt cho thấy dòng tiền tích lũy âm). Vào tháng Sáu,
chúng ta sẽ triển khai giải pháp của mình và bắt đầu có thu nhập kah3 quan (thể hiện bằng tiền dương).

![ROIEx]({{ site.baseurl }}/assets/images/ROIEx.png)

Khi chúng ta thêm thu nhập mới vào số liệu dòng chảy ra, chúng ta có thể thấy dòng tiền ròng (được hiển thị bên dưới bằng đường màu xám). Dựa trên biểu đồ này, bạn nghĩ khi nào tổng lợi nhuận của chúng ta bằng tổng đầu tư?

![nestcashflow]({{ site.baseurl }}/assets/images/nestcashflow.png)

Thật hấp dẫn để giả định rằng lợi nhuận của chúng ta sẽ bằng với khoản đầu tư của chúng ta vào tháng Bảy, khi dòng tiền ròng của chúng ta bằng không. Theo một cách nào đó, điều này là đúng; tại thời điểm đó, chúng ta sẽ nhận lại được số tiền bằng số tiền chúng ta bỏ ra. Tuy nhiên, chúng ta cần xem xét các tác động của lạm phát. Quy tắc cơ bản của tài chính là số tiền chúng ta mong đợi nhận được trong tương lai sẽ ít hơn giá trị số tiền chúng ta có sẵn để đầu tư ngày hôm nay. Điều này đặc biệt đúng nếu chúng ta phải vay tiền để tạo ra lợi tức trong tương lai, vì chúng ta sẽ cần phải trả lại số tiền vay với lãi suất. Vì vậy, khi xác định thời gian hoàn vốn, chúng ta cần có cách tính đến ảnh hưởng của lạm phát và chi phí vay tiền.

{:#presentvalue}
### Present Value - Giá trị hiện tại

Đây là nơi xuất hiện khái niệm giá trị hiện tại. Giá trị hiện tại là một cách tính giá trị của một khoản tiền trong tương lai theo các điều kiện hiện tại, với một tỷ lệ lãi suất và tỷ lệ lạm phát giả định. Hãy áp dụng khái niệm giá trị hiện tại cho dự án mẫu của chúng ta.

Trong hình bên dưới, đường màu xám đậm hơn với các điểm đánh dấu x cho biết giá trị hiện tại của số tiền mà chúng ta sẽ nhận được trong tương lai, dựa trên lãi suất dự kiến là 2% (đại diện cho lạm phát). Như chúng ta có thể thấy từ hình này, giá trị hiện tại của khoản đầu tư dự án không đi sâu vào âm hay dương như dòng tiền ròng, vì giá trị của nó được điều chỉnh theo tác động của lạm phát.

![presentvalue]({{ site.baseurl }}/assets/images/presentvalue.png)

{:#netpresentvalue}
<div id="toolkitBox">
  <div id="toolkitIcon">T&T</div>
  <h2 id="toolkitContent">Net Present Value (NPV) - Giá trị hiện tại ròng<br/><hr/></h2>
</div>

<br/>

Chúng ta có thể mở rộng khái niệm giá trị hiện tại để tìm giá trị hiện tại của lợi tức mong đợi cho một dự án. Số liệu này được gọi là giá trị hiện tại ròng hoặc NPV và nó có thể được định nghĩa như sau:

> NPV = Giá trị hiện tại của dòng doanh thu (thu nhập trừ chi phí) trong một khoảng thời gian.

Để đánh giá giá trị cảu một dự án theo quy mô tiền hiện tại, chúng ta tính NPV của dự án. Đây là giá trị hiện tại của dòng doanh thu hoặc thu nhập trừ đi chi phí trong một khoảng thời gian, chẳng hạn như tháng hoặc năm. Việc tính toán NPV của các dự án tiềm năng khác nhau cho phép một số công ty so sánh chúng ngang bằng nhau và chọn ra dự án tốt nhất.

Nói chung, bất cứ dự án nào có NPV dương đều là một khoản đầu tư tốt, vì chúng ta sẽ kiếm lại nhiều hơn số tiền chúng ta đã đầu tư theo thời gian hiện tại. Tuy nhiên, nếu đang sử dụng NPV để so sánh giá trị mong đợi từ nhiều dự án tiềm năng, thì NPV càng cao càng tốt.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Đối với bài kiểm tra, chúng ta nên hiểu định nghĩa của NPV và số liệu này khác với ROI và IRR như thế nào. Chúng ta nên biết rằng một dự án có NPV cao hơn kỳ vọng sẽ mang lại nhiều giá trị hơn so với một dự án tương đương có NPV thấp hơn. Số liệu này có thể được đề cập trong các câu hỏi tình huống liên quan đến việc đánh giá giá trị của dự án hoặc so sánh giá trị giữa các dự án. Chúng ta có thể được yêu cầu giải thích những con số này, nhưng chúng ta sẽ được yêu cầu tính toán chúng.
      <br/>
    </h7>
  </div>
</div>

<br/>

Các tổ chức đã nhận thấy NPV rất có giá trị để so sánh tiền ra và tiền vào đến nỗi chỉ số này được sử dụng rộng rãi để đánh giá lợi nhuận của dự án. Nó cho phép chúng ta đánh giá dòng chi phí và thu nhập của dự án và tìm thời gian hoàn vốn - sau khi điều chỉnh lạm phát - thực sự của dự án. Trong các dự án lớn nhiều năm, thời gian hoàn vốn thực sự có thể dài hơn đáng kể, đặc biệt nếu tiền để đầu tư vào các dự án này được vay với lãi suất cao.

NPV có thể đặc biệt hữu ích để so sánh các dự án có các khung thời gian khác nhau hoặc dự kiến sẽ bắt đầu mang lại giá trị vào các thời điểm khác nhau. Ví dụ: điều gì sẽ xảy ra nếu chúng ta đang cố gắng lựa chọn giữa một dự án mà chúng ta mong đợi sẽ mang lại ROI 2% trong 12 tháng và một dự án mà chúng ta mong đợi sẽ mang lại ROI 4% trong 36 tháng? Lạm phát và lãi vay trong một khoảng thời gian dài hơn có phủ nhận ROI cao hơn của dự án thứ hai không? Để tìm hiểu, chúng ta tính NPV của hai dự án và xem dự án nào mang lại nhiều giá trị hơn bằng tiền hiện nay. Trong trường hợp thế này, NPV của hai dự án sẽ cung cấp cho chúng ta nhiều thông tin hơn so với ROI của chúng. Tuy nhiên, hạn chế của việc tính toán NPV là chúng ta phải ước tính mức lạm phát và lãi suất trong tương lai - và những phỏng đoán đó có thể không chính xác.

{:#internalRateReturn}
<div id="toolkitBox">
  <div id="toolkitIcon">T&T</div>
  <h2 id="toolkitContent">Internal Rate of Return (IRR) - Tỷ lệ hoàn vốn nội bộ<br/><hr/></h2>
</div>

<br/>

Để xem cách các tổ chức giải quyết vấn đề phải đoán phạm phát và lãi suất trong tương lai, hãy chuyển sang khái niệm tỷ suất hoàn vốn nội bộ hay còn gọi là IRR. Để hiểu khái niệm này, chúng ta phải sử dụng thuật ngữ tài chính "lãi suất chiết khấu", có nghĩa là lãi suất cần kiếm được trên một số tiền nhất định ngày hôm nay để kết thúc với một số tiền nhất định trong tương lai.

Định nghĩa chính thức của IRR là tỷ lệ chiết khấu mà tại đó "dòng tiền vào của dự án (doanh thu) và dòng tiền ra của dự án (chi phí) bằng nhau". Một cách khác để nói điều này là hỏi: "Tỷ lệ chiết khấu sẽ chuyển thời gian hoàn vốn sang kết thúc của dự án?"

> IRR = Tỷ lệ chiết khấu mà tại đó dòng tiền vào của dự án (doanh thu) và dòng tiền ra của dự án (chi phí) bằng nhau.

Số liệu này giúp đơn giản hóa việc đánh giá các dự án, vì chúng ta không phải đoán lãi suất và tỷ lệ lạm phát trong tương lai, như chúng ta làm đối với NPV. Thay vì sử dụng lãi suất dự kiến và tỷ lệ lạm phát để tính toán giá trị của một dự án theo điều ngày nay, chúng ta sử dụng ước tính của chúng ta về thời gian và hoàn vốn của dữ án để tính lãi suất thực tế (hay còn gọi là "tỷ lệ chiết khấu" cho dự án).

Cách dễ nhất để nghĩ về IRR là so sánh nó với lãi suất trả bằng tài khoản tiết kiệm. Khi quyết định gửi tiền tiết kiệm vào đâu, nếu chúng ta hiểu biết, chúng ta sẽ mua sắm và cố gắng chọn tài khoản sẽ mang lại cho chúng ta lợi nhuận cao nhất. Theo cách tương tự, khi một công ty đang chọn đầu tư vào dự án nào đó, nó sẽ tính toán tỷ suất sinh lợi kỳ vọng cho từng dự án tiềm năng và chọn dự án được dự đoán sẽ mang lại IRR cao nhất.

Ở góc độ kinh tế, tỷ lệ này càng cao thì dự án càng tốt.

<div id="examTipbox">
  <div id="examTipIcon">
    <img src="/assets/images/icons-check.png" alt="check-icon">
  </div>
  <div id="examTipContent">
    <h5>EXAM TIP<br/><hr/></h5>
    <h7>
      Nếu một câu hỏi kiểm tra hỏi về "tỷ lệ hoàn vốn" hoặc "tỷ lệ chiết khấu" cho một dự án, thì nó đang đề cập đến IRR của dự án. Đối với bài kiểm tra, chúng ta nên hiểu định nghĩa về IRR và chỉ số này khác với NPV và ROI như thế nòa. Chúng ta nên biết rằng dự án có IRR cao hơn là khoản đầu tư tốt hơn so với dự án tương đương có IRR thấp hơn. Số liệu này có thể được đề cập trong các câu hỏi tình huống liên quan đến quyết định đầu tư vào dự án nào. Chúng ta có thể được yêu cầu giải thích những con số này, nhưng chúng ta không được yêu cầu tính toán chúng.

      Lưu ý rằng việc so sánh tỷ lệ ROI, NPV và IRR với nhau là không có ý nghĩa.

      Nếu câu trả lời cho một câu hỏi kiểm tra bao gồm nhiều hơn một trong các chỉ số này, đừng chỉ chọn tùy chọn có tỷ lệ cao nhất; thay vào đó, hãy đọc kỹ câu hỏi để xác định số liệu nào có liên quan đến tình huống được mô tả.
    <br/>
    </h7>
  </div>
</div>

<br/>

<div id="practises" style="font-size: 12px;">
  <h5>Bài tập - Hiểu về ROI, NPV và IRR</h5>
</div>

**1. Which of the following definitions best describes return on investment (ROI) ?**

 A. The point in time when the revenue received equals the costs expended for the project

 B. How much revenue the project will bring in once it is completed and operational, compared to its ongoing operating costs

 C. The ratio of the money we receive at the end of a project to the money we have invested in it

 D. The percentage of money the project will cost once all project expenditures are collected

**2. A sponsor is trying to determine which project has the greatest business value. One project returns $5 million in three years, and another project returns $6 million in four years. The cost of borrowing capital to fund the project is 4 percent. Which of the following is the best approach to determine the project with the greatest value?**

 A. Select the project that returns $6 million in four years, since it returns the highest amount.

 B. Select the project that returns $5 million in three years, since it has the shorter payback period.

 C. Calculate the NPV of the projects, and choose the project with the lowest cost.

 D. Calculate the NPV of the projects, and choose the project with the highest value.

**3. A sponsor is considering the business value of two projects. Which of the following definitions best describes the approach for assessing and applying the concept of internal rate of return (IRR) ?**

 A. Calculate the internal rate of return, and choose the project with the highest rate.

 B. Calculate the internal rate of return, and choose the project with the lowest cost.

 C. Calculate the internal rate of return, and choose the project with the highest revenue.

 D. Calculate the internal rate of return, and choose the project with the lowest revenue.

<h4>ĐÁP ÁN</h4>

**1. Answer: C.**

ROI is the ratio of the money we receive at the end of a project to the money we have invested in it, expressed as a percentage. Looking at the other options, choice A describes the project payback or breakeven point, not ROI (which doesn’t specify a point in time). Choice B focuses on revenue only, omitting any consideration of the money we have invested, and instead referring to operational costs after the project is over. Choice D describes project costs rather than ROI. Therefore, choice C is our best option.

**2. Answer: D.**

To evaluate the value of two projects that will be completed at different times, we can use net present value (NPV) to level the amounts into today’s values. So calculating the NPV and choosing the project with the highest NPV value is the way to go. Choice A points us to the project with the highest return, but the question is asking for the best approach. Likewise, options B and C do not address the best approach to take.

**3. Answer: A.**

Internal rate of return (IRR) shows the earning potential for a project.
Like comparing investment interest rates, the higher the rate, the better the investment proposition. So to use IRR to evaluate projects, we calculate the IRR for each and then select the project with the highest IRR value. Costs and revenue are rolled into the calculation of IRR and are not part of the final IRR evaluation.

{:#evm}
<div id="toolkitBox">
  <div id="toolkitIcon">T&T</div>
  <h2 id="toolkitContent">Earned Value Management (EVM) - Quản lý giá trị nhận được<br/><hr/></h2>
</div>

<br/>

Bây giờ, chúng ta đã thấy cách các tổ chức đánh giá giá trị của các dự án tiềm năng; hãy chuyển sang các công cụ mà họ có thể sử dụng để giám sát việc phân phối giá trị trong khi một dự án đang được tiến hành. Công cụ đầu tiên được đề cập là quảnl ý giá trị nhận được (EVM). Để hiểu được lợi của EVM, chúng ta sẽ bắt đầu bằng cách xem xét một số lựa chọn thay thế cho giá trị theo dõi.

Mong công cụ thường được sử dụng để theo dõi chi tiêu của dự án là "đường cong chữ S". Đây đơn giản là một biểu đồ theo dõi chi phí hoặc một số biến số khác theo thời gian. Những đồ thị này được gọi là đường cong S vì đường cong tăng trưởng thường có hình dạng chữ S, như trong ví dụ sau:

![scurvegraph]({{ site.baseurl }}/assets/images/scurvegraph.png)

Ưu điểm của đường cong chữ S là chúng dễ diễn giải và có thể nhanh chóng cho chúng ta biết liệu dự án của chúng ta đã hết hay còn dưới ngân sách. Tuy nhiên, các đường cong chữ S không cung cấp bất kỳ thông tin nào về lịch trình. Vì vậy, đường cong chữ S của chúng ta có thể cho thấy rằng chúng ta có đang chi tiêu khôn ngoan, nhưng chúng ta có thể bị chậm tiến độ và không biết điều đó.

Để theo dõi trạng thái của tiến độ dự án, người ta thường sử dụng biểu đồ Gantt, như ví dụ sau:

![ganttchart]({{ site.baseurl }}/assets/images/ganttchart.png)

Tuy nhiên, biểu đồ Gantt cũng có giới hạn, vì chúng thiếu thành phần chi tiêu của tình trạng dự án - giống như đường cong S thiếu thành phần lịch trình. Vì hầu hết, các dự án sẽ vượt trước hoặc chậm so với ngân sách và tiến độ vào một thời điểm nào đó, nên có thể khó đánh giá tình trạng tổng thể của các dự án. Ngoài ra, do tính chất lặp đi lặp lại  của các dự án Agile, các biểu đồ Gantt có thể trở nên chồng chéo nhau, khó hiểu.

Để đánh giá tình trạng tổng thể của một dự án, những gì chúng ta thực sự cần là một sơ đồ duy nhất có thể hiển thị trạng thái dự án cả về tiến độ và tổng giá trị được giao đến nay. Quản lý giá trị nhận được đã được tạo ra để giải quyết vấn đề này. Cách tiếp cận này kết hợp dữ liệu chi tiêu và lịch trình để tạo ra một bộ chỉ số dự án toàn diện, bao gồm giá trị theo kế hoạch (PV - Planned value), giá trị nhận được (EV - earned value), phương sai lịch trình (Schedule variance), phương sai chi phí (CV - cost variance), chỉ số hiệu suất lịch trình (SPI - schedule perfomance index), và chi phí chỉ số hiệu suất (CPI - cost perfomance index).

{:#usingEVM}
### Sử dụng EVM cho các dự án Agile: Ưu và nhược điểm

Mọi người hay hỏi rằng liệu có thể sử dụng số liệu giá trị nhận được cho các dự án Agile hay không? Câu trả lời là có. Nhưng trong khi toán học vẫn hoạt động theo cách tương tự như trên các dự án non-agile, chúng ta cần phải cẩn thận về những gì chúng ta đang đo lường. Giá trị nhận được so sánh hiệu suất thực tế của dự án với hiệu suất theo kế hoạch tại một thời điểm cụ thể. Vì vậy, chất lượng của kế hoạch cơ sở là một yếu tố thành công quan trọng trong việc sử dụng phương pháp này. Nếu kế hoạch ban đầu của chúng ta không còn chính xác, điều này có thể giống như theo dõi chuyến đi đường bộ từ Calgaray đến thành phố Salt Lake trên bản đồ của Pháp! Đối với các dự án Agile, chúng ta biết rằng kế hoạch ban đàu 6của chúng ta sẽ cẩn phải thay đổi, do đó, cơ sở cho EVM hiệu quả nhanh chóng bị xói mòn khi kế hoạch của chúng ta phát triển.

Một lưu ý khác về giá trị nhận được là nó không thực sự cho biết liệu dự án có mang lại giá trị thành công hay không? Chúng ta có thể đúng giờ, đúng ngân sách, nhưng phải xây dựng một sản phẩm chất lượng thấp, tồi tệ mà khách hàng không thích hoặc không cần. Chi phí và lịch trình không phải là bức tranh toàn cảnh - dự án của chúng ta có thể vẫn diễn ra tồi tệ ngay cả khi nó có vẻ tốt từ quan điểm giá trị kiếm được.

Sau khi đọc về những vấn đề này mà các đội agile cần phải cảnh giác, chúng ta có thể tự hỏi: Tại sao lại sử dụng EVM? Một trong những lợi ích chính của chỉ số giá trị kiếm được từ chúng là một chỉ số dẫn đầu. EVM rất được mong đợi để cố gắng dự đoán ngày hoàn thành và chi phí cuối cùng. Xét cho cùng, các chỉ số dẫn đầu không hoàn hảo thường có giá trị hơn các chỉ số cuối cùng, vì các chỉ số dẫn đầu thường cho chúng ta cơ hội xem lại kế hoạch và thay đổi cách tiếp cận của mình.

Một lợi ích khác của giá trị kiếm được là nó trực quan. Mọi người thường quên các biểu đồ EVM và chỉ tập trung vào các con số, nhưng trung tâm của kỹ thuật này là một số biểu đồ hữu ích. Các hình ảnh biểu diễn thông tin liên quan đến phần não phải của chúng ta, giúp chúng ta hiểu và diễn giải dữ liệu một cách trực quan để chúng ta có thể lập kế hoạch phản ứng thích hợp. Mô tả trực quan cũng tốt hơn để làm việc cộng tác, vì mọi người có thể dễ dàng đánh dấu, trỏ tới và ngoại suy từ hình ảnh hơn là chữ hoặc số.

{:#earnedvaluetool}
### Xây dựng một công cụ giá trị nhận được Agile

Làm thế nào để các đội agile có thể tận dụng các lọi ích dự báo và giao tiếp bằng hình ảnh của EVM, đồng thời giảm thiểu những mặt trái của phương pháp đó? Để xem cách thực hiện, chúng ta sẽ xây dựng một biểu đồ có tất cả các chỉ số mà chúng ta cần, từng bước một. Chúng ta sẽ bắt đầu với một đường cong chữ S kép, như sau:

![DoubleSVurve]({{ site.baseurl }}/assets/images/DoubleSVurve.png)

Ở đây, chúng ta có một đường chi tiêu quen thuộc, được hiển thị bằng màu đen, đang được theo dõi so với quy mô đô la ở phía bên phải của biểu đồ. Chúng ta cũng có một đường màu xanh lá cây cho phạm vi đã hoàn thành (các tính năng được xây dựng cho đến nay), đang được theo dõi dựa trên thang điểm câu chuyện ở phía bên trái.

Độ dốc của hình màu xám cho biết vận tốc của đội. Ở những nơi có độ dốc lớn, nhóm nghiên cứu có thể phát triển rất nhiều điểm câu chuyện (story point) trong một thời gian ngắn. Ở những nơi bằng phẳng, tiến độ của họ rất chậm. (các khái niệm agile về vận tốc và điểm câu chuyện sẽ được giải thích ở chương 4, 5.)

Đối với bước tiếp theo trong việc xây dựng biểu đồ của chúng ta, chúng ta sẽ thêm nền hiển thị các khu vực chức năng của dự án, như sau:

![ScopeCostSchedulePerformance]({{ site.baseurl }}/assets/images/ScopeCostSchedulePerformance.png)

Với nền hiển thị mới này, chúng ta có thêm rất nhiều thông tin. Chúng ta không chỉ có thể thấy rằng chỉ hơn 1000 điểm chức năng đã được hoàn thành, mà các thành phần cấu hình và kho của hệ thống cũng đã được xây dựng và nhóm hiện đang làm việc trên phần phạm vi của Bán hàng. Ngoài ra, chúng ta cũng có thể thấy dễ dàng rằng phạm vi đó được thêm vào phần Bán hàng của hệ thống vào tháng Hai. Vì sự thay đổi này đã làm tăng tổng phạm vi dự án (về điểm cốt truyện), tất cả các khu vực chức năng sau khi Bán hàng đều có một bước tiến để phản ánh sự thay đổi đó.

Bây giờ, chúng ta có một biểu đồ hiển thị phạm vi, lịch biểu và hiệu suất chi phí cho đến nay, nhưng những gì chúng ta đang thiếu là bất kỳ dự báo nào cho chúng ta biết liệu chúng ta đang đi trước hay chậm so với ngân sách và lịch trình dự đoán của mình. Vì vậy, trong bước tiếp theo, chúng ta sẽ thêm các phép chiếu vào biểu đồ, để nó trông như sau:

![ScopeCostSchedulePerformance&Projections]({{ site.baseurl }}/assets/images/ScopeCostSchedulePerformance&Projections.png)

Bày giờ, chúng ta có thể thấy tiến độ thực tế của dự án như thế nào so với hiệu suất dự kiến - hiện tại trong dự án mẫu của chúng ta, chúng ta đã suất một chút, nhưng chúng ta đang đi trước trong việc xây dựng phạm vi. Với bước này, bây giờ chúng ta có một biểu đồ có thể được sử dụng để quản lý giá trị kiếm được linh hoạt, vì nó cung cấp các giá trị và chỉ số giống như EVM, nhưng mô tả chúng một cách trực quan, như được hiển thị trong hình tiếp theo.

![visualToolForEVMMetrics&Projections]({{ site.baseurl }}/assets/images/visualToolForEVMMetrics&Projections.png)

Sơ đồ trên cho thấy các số liệu EVM truyền thống như chỉ số hiệu suất lịch trình (SPI) và chỉ số hiệu suất chi phí (CPI) có thể được dịch sang các thuật ngữ Agile như thế nào? Ví dụ:

- Chúng ta đã lên kế hoạch hoàn thành 30 điểm chức năng trong lần lặp cuối cùng, nhưng chúng ta chỉ hoàn thành 25 điểm. Để tìm SPI của chúng ta, chia 25 cho 30 thu được kết quả SPI = 0.83. Điều này cho chúng ta biết rằng chúng ta chỉ làm việc với mức 83% so với kế hoạch.

- CPI là giá trị nhận được (EV, hoặc giá trị của các tính năng đã hoàn thành) tính đến thời điểm hiện tại chia cho chi phí thực tế (AC) tính đến thời điểm hiện tại. Vì vậy, trong sơ đồ trên, CPI = $2,200,000 / $2,800,000 = 0.79. Điều này có nghĩa là chúng ta chỉ nhận được 79 xu trên 1$ so với những gì cũng đã dự đoán.
