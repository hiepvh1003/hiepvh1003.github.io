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
| [ Phân phối hướng giá trị là gì?? ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#whatvaluedrivendelivery) |
| [  - Các dự án tri thức là khác nhau ]({{ site.baseurl }}/pmiacp-chapter-2-value-driven-delivery/#knowledgeWork) |
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

  <li>Cumulative flow diagrams (CFDs) - Sơ đổ luồng tích lũy</li>

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
