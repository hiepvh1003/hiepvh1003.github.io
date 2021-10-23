---
layout: post
title:  "Quản lý dự án - Execution"
author: hiepvh
categories: [ BrSE ]
tags: [ PM ]
image: assets/images/execution.jpg
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: false
hidden: false
# rating: 4.5
---

Thực thi (Execution) là làm những công việc gì? Quản lý và control ra làm sao?

Cái notes này là bài tham khảo từ nội bộ công ty mình.

{:#tblContent}
| Contents |
|-----|
| [ Khái niệm căn bản của project execution]({{ site.baseurl }}/project-manager-execution/#basicconcept) |
| [ Management Target]({{ site.baseurl }}/project-manager-execution/#managementTarget) |
| [   　1.　Task progress]({{ site.baseurl }}/project-manager-execution/#taskProgress) |
| [   　2.　Bugs]({{ site.baseurl }}/project-manager-execution/#bugs) |
| [   　3.　Specification Change / Change Request : CR]({{ site.baseurl }}/project-manager-execution/#CR) |
| [Summary]({{ site.baseurl }}/project-manager-execution/#summary) |

<br/>

{:#basicconcept}
## Basic concept of project execution
*(Khái niệm căn bản của project execution)*

Nói một cách đơn giản, execution là giai đoạn thực thi những gì đã lên kế hoạch trong giai đoạn planning.

Đặc biệt trong phát triển theo mô hình Waterfall, trong giai đoạn planning thì mọi việc phải được lên kế hoạch chi tiết và rõ ràng. Vào giai đoạn execution, chỉ việc thực thi theo kế hoạch đã vạch ra ấy.

Điều tương tự cũng áp dụng cho hình thức dự án chạy theo sprint 1 hoặc 2 tuần trong Agile.

Trước khi sprint bắt đầu thì phải lên plan cho sprint và thực thi, kiểm soát plan trong sprint đó.

Chúng ta đã biết được là loại tài liệu nào quan trọng trong quá trình planning.

Ở giai đoạn Planning, chỉ những cái gì quan trọng cần phải được hoàn thành gọi là Planning Priority.

Mức độ ưu tiên (Planning priority) cao có thể trở thành vấn đề lớn sau này nếu có nhiều điểm chưa rõ ràng tại thời điểm lập kế hoạch.

Mặt khác, những plan có priority thấp thì phải được quản lý chặt chẽ trong giai đoạn thực thi.

{:#tblPlan}
| # | Items | Planning Priority |
|---|---|---|
| 1 |Function List| S |
| 2 |Screen Specification| S |
| 3 |Development Process	| A |
| 4 |Issue Management List| B |

Theo bảng trên thì các items có vẻ ít. Nhưng chúng ta chỉ tập trung vào Quality và Delivery nên các hạng mục trong Project Planning chỉ tập trung vào các điểm này.

Bây giờ, từ giai đoạn lập kế hoạch đến giai đoạn thực thi, chúng ta sẽ xem xét loại đối tượng nào cần quản lý và thay đổi phương pháp quản lý.

{:#managementTarget}
## Management Target

Khi dự án thực sực bước vào giai đoạn thực thi, có nhiều thứ bắt đầu vận hành.

「動き出す」có nghĩa là một cái gì đó đang tiến triển và việc vận hành đến khi hoàn thành.

Đồng thời, nội dung của công việc sẽ thay đổi liên tục, nên khó để nắm bắt được tình hình, có trường hợp còn trở thành vấn đề lớn.

Trong giai đoạn execution, điều quan trọng là phải trả lời được câu hỏi:
- "Điều gì đang xảy ra bây giờ?"

- "Nó đã thực thi được khoảng bao nhiêu?"

Ở giai đoạn Planning, ở một mức độ nào đó, có thể cho phép "những điều chưa rõ ràng chờ xác nhận TO BE DEFINE - TBD", nhưng ở giai đoạn thực thi này, số lượng những vấn đề không rõ ràng trực tiếp dẫn đến rủi ro của dự án.

Cùng xem lại thử xem những vấn đề nào sẽ được quản lý.

{:#taskProgress}
### 1. Task progress

Điều cơ bản nhất là "tiến độ của task đang là như thế nào?"

Chúng ta sử dụng tools quản lý task như redmine, backlog, jira.

Nói một cách đơn giản, điểm cần phải xác minh rõ ràng là trong giai đoạn Develop Process thì estimate effort có đang thực sự vận hành chính xác hay không?

{:#tblPlan}
| # | Point | Note | Execution Priority |
|---|---|---|---|
| 1 |Task input| Các input có thật sự được xác định chính xác trong quy trình phát triển, chẳng hạn như spec có được cung cấp chính xác không? | B |
| 2 |Task basic information| Các task được log trong các tools quản lý có đầy đủ thông tin? | A |
| 3 |Tiến triển của mỗi quy trình	| Các thứ tự trong process có bị thay đổi không? <br/> Chẳng hạn như Technical review xong rồi mới tới QA Test | A |
| 4 |Độ chính xác của cập nhật trạng thái| Status trong tools có được log đúng không? Task đã hoàn thành mà trên tools vẫn chưa chuyển status. <br/> Trong quy trình Develop mặc dù đã define of done rồi nhưng mà team dev vẫn phớt lờ quy tắc và cứ tiến hành công việc. | B |
| 5 |Tiến độ của task | Giả sử tổng tiến độ của task là 100% thì các mốc 25, 50,75% có đang như dự kiến hay không? <br/> Việc phát hiện sự chậm trễ của task ở các mốc này càng sớm thì càng tốt. <br/> Có thể phát hiện ra sự thay đổi này bằng các liên tục kiểm tra tiến độ thực hiện nhiệm vụ nhiều lần trong ngày. | B |
| 6 |Output của mỗi quá trình | Output được xác định trong Quy trình phát triển có đang tuân thủ đúng quy định đã đặt ra hay không? <br/> ・　Nếu quá trình estimate, các căn cứ xác định estimate có rõ ràng hay không? <br/> ・　Với output của Technical Review, nếu ở tool quản lý task đã chuyển đổi status thành Đã hoàn thành review thì việc comment có được liệt kê ra không?  | A |
| 7 |Actual hour với estimate hour có khớp nhau? | Công việc có được hoàn thành trước thời hạn đặt ra chưa? <br/> Điều quan trọng là không được trễ deadline, nhưng nếu hoàn thành trước Due Date thì đâu đó có thể xảy ra sơ sót trong công việc. | A |

Như chúng ta thấy ở trên, khi dự án bước vào giai đoạn thực thi, điều quan trọng là phải theo dõi xem các quy trình được xác định tại thời điểm planning có đang được tuân thủ hay không?

Tại thời điểm planning, chúng ta xác định quy trình để đảm bảo Quality và Delivery, đồng thời phát hiện vấn đề xảy ra với quy trình đó.

Do đó, nếu quy trình này không được tuân thủ trong giai đoạn thực thi, sẽ không thể đạt được Quality và Delivery theo kế hoạch.

Trong một số trường hợp, chúng ta có thể không hiểu các nhiệm vụ đã được hoàn thành và chúng ta không thể hiểu được mình đã phát triển tính năng này tới đâu.

{:#bugs}
### 2. Bugs

Việc quản lý bugs trong quá trình phát triển là hết sức cần thiết.

Quản lý bugs thì có thể dùng chung tools quản lý task như redmine, backlog, jira luôn cũng được.

Đối với bugs, hãy theo dõi xem task có được thực hiện theo đúng Quy trình phát triển không?

Vì bugs thường yêu cầu hành động khẩn cấp sau khi chúng được phát hiện, nên có những trường hợp task bị coi thường hơn bình thường.

Chúng ta có thể theo dõi những point dưới đây để nhận biết bugs.

{:#tblPlan}
| # | Point | Note |
|---|---|---|
| 1 | Cách tái hiện bugs | Mô tả cách tái hiện bugs trong tools quản lý bugs <br/> Kinh nghiệm trong việc test và fix bugs cũng rất quan trọng trong việc mô tả cách tái hiện bugs. <br/> Nếu cách tái hiện không được ghi chép đầy đủ, những member đảm nhiệm fix bugs sẽ tốn rất nhiều thời gian để tìm hiểu và điều tra xem bugs xảy ra như thế nào. <br/> Để tránh lãng phí thời gian cho team dự án, người Quản lý dự án nên theo dõi kỹ tester có log đủ thông tin hay không?|
| 2 | Môi trường và thời điểm xảy ra bugs (yyyy-MM-dd HH:ii) | Thông tin được cung cấp bao gồm: môi trường test, thời điểm xảy ra bugs. <br/> Trên thực tế, bản release mới nhất có thể đã kết thúc việc điều chỉnh. <br/> Hoặc là đã fix nhưng vẫn tái diễn <br/> Nếu không đủ thông tin về môi trường và thời gian xảy ra, việc phán đoán lỗi sẽ khó khăn và không thể fix một cách nhanh chóng được. <br/> Điều quan trọng là phải thống nhất các QA cần phải report kỹ chỗ này.|
| 3 | Source code version đã phát hiện ra bugs| Nhiều developer cùng phát triển thì sẽ xảy ra nhiều version, vì vậy, việc mô tả rõ ràng version của source code sẽ làm việc điều tra bugs càng nhanh chóng và rõ ràng hơn. <br/> Thông tin này cực kỳ quan trọng khi số lượng thành viên developer và độ phức tạp của dự án tăng lên. <br/> Nếu không có thông tin này, mỗi lần fix bugs thì phải kiểm tra lại source code mới nhất, và chắc chắn là không biết được liệu cuối cùng bugs đã được fix hay chưa. |
| 4 | Cách đối ứng bugs | Developer nên tránh đưa ra quyết định tùy tiện về việc fix bugs <br/> Senior Developer có thể đưa ra quyết định chính xác về phương pháp fix bugs. Nhưng vì nhiều lý do đã gây ra bugs nên không thể chọn phương pháp fix bugs mà không thống nhất rõ ràng.  <br/> Để quản lý dự án ổn định hơn, người ta cho rằng Project Manager và các senior developer nên quyết định phương pháp một cách hiệu quả trước tiên. |
| 5 | Độ ưu tiên, ảnh hưởng và tính khẩn cấp của bugs| Theo dõi mức độ ưu tiên của bugs có được liệt kê hay không? <br/> Đây có thể nói là đối ứng incident hơn là bugs. <br/> Chúng ta sẽ không thực sự phân biệt rõ ràng incident và bugs ở đây. <br/> Đặc biệt, nên mô tả riêng Impact (ảnh hưởng) và Urgency (Mức độ khẩn cấp) cho các mức Ưu tiên. <br/> Ví dụ, giả sử có 2 lỗi trên trang EC: <br/> Bug 1: Phiếu mua hàng lẽ ra được tặng khi mua sản phẩm A đã không được tặng. Có 0.1% người đã mua đang active. <br/> Bug 2: Đã xảy ra sự cố với chức năng log của máy chủ và lịch sử mua hàng của người dùng không được lưu từ hôm qua. Người dùng không biết về điều này. <br/> <br/> Bug 1: Dường như có mức độ ưu tiên cao hơn vì người dùng cuối trực tiếp nhận thức được hiện tượng. Tuy nhiên, có thông tin cho rằng số lượng người dùng mục tiêu ít. Mức độ khẩn cấp nên được coi là thấp, vì enduser có thể khiếu nại được. <br/> Bug 2: Nghiêm trọng hơn. Ngay từ đầu, có thể không thể điều tra lịch sử mua của bug 1 do lỗi này. Và ngay cả khi có một số bugs khác ngay từ đầu, cũng không còn logs để điều tra. <br/> Về impact thì Bug 2 lớn hơn bug 1. Và tất nhiên urgency sẽ cao hơn. <br/><br/> Tổng kết lại nó sẽ như thế này: <br/> - Bug 1: <br/> ・　Impact: Low <br/> ・　Urgency: High <br/> - Bug 2: <br/> ・　Impact: High <br/> ・　Urgency: High <br/><br/> Nhìn vào đây thì ta thấy rõ ràng Bug 2 cần được ưu tiên xử lý trước. <br/> Mà thường thì bug 1 bị khiếu nại trực tiếp từ enduser nên được vội vàng fix trước. Và điều này rất thường hay xảy ra. <br/><br/> Nó cũng xảy ra hầu hết với các lỗi đều đặt mức ưu tiên cao nhất chỉ dựa trên Urgency. <br/> Cuối cùng, người Quản lý dự án nên sắp xếp thứ tự ưu tiên cho công việc, nhưng điều quan trọng là phải theo dõi xem thông tin đóng vai trò tiêu chí được cung cấp có đầy đủ ngay từ đầu hay không? |

{:#CR}
### 3. Specification Change / Change Request : CR

Dùng Change Request ở đây thì nó mang ý nghĩa chỉ dành cho outsourcing nên ở đây, chúng ta dùng thêm thuật ngữ Specification Change (thay đổi spec).

Trong tiếng Nhật, thuật ngữ [仕様変更 - Specification Change] được sừ dụng phổ biến hơn.

Việc quản lý danh sách về thời điểm và cách thức spec change là cực kỳ quan trọng.

{:#tblPlan}
| # | Item | Initial Input | Description |
|---|---|---|---|
| 1 | Issue Date | ✔ | Spec Change được phát hành khi nào? Nó sẽ quan trọng sau này khi phân tích. |
| 2 | Issuer | ✔ | Ghi lại người đã yêu cầu thay đổi. Điều này quan trọng trong việc confirm lại spec sau này. |
| 3 | Target Screen / Target Function | ✔ | Mô tả màn hình nào, chức năng nào được thay đổi? <br/> Chỉ bằng từ ngữ, việc thay đổi cái gì ở đâu có thể dễ dẫn đến sự nhầm lẫn và thiếu sót. <br/> Có khả năng cao là người yêu cầu thay đổi spec hiểu rõ nhất mục tiêu của sự thay đổi này. |
| 4 | Detail | ✔ | Chi tiết nội dung thay đổi.|
| 5 | Priority | ✔ | Mức độ ưu tiên của spec change. Đây là mục để tham khảo để quyết định cái nào nên ưu tiên hơn. Nó được đặt thành 4 mức độ như dưới: <br/> ・　Urgency: Khẩn cấp. Cái này phải làm liền ngay lập tức, trì hoãn những công việc khác đang làm để ưu tiên làm cái này trước nhất. Thực tế, mức độ ưu tiên này có nghĩa là các kế hoạch khác có thể phải dừng lại. Vì thế, khuyến cáo là không dùng nhiều, tối đa 2 Spec change được tồn tại cùng lúc. <br/> ・　High: Khi công việc hiện tại được hoàn thành, member sẽ được ưu tiên hoàn thành công việc này càng sớm càng tốt. <br/> ・　Middle: Ưu tiên bình thường, hoàn thành trong vòng 1 đến 2 sprint. <br/> ・　Low: Mức độ ưu tiên thấp. Một số task khác có thể không được thực hiện trong một khoảng thời gian. |
| 6 | Desired Release Date <br/> Ngày release mong muốn | ✔ | Đôi khi dùng từ Due Date. Nhưng nó nên được hiểu là ngày Release hơn là ngày hoàn thành. <br/> Điều quan trọng là từ Desired - Mong muốn. Điền giá trị vào đây không có nghĩa là đến ngày đó là phải release bằng mọi giá. <br/> Nếu dùng từ Due Date thì mọi người tin rằng đến ngày đó là phải được release. <br/>  |
| 7 | Planned implementation Sprint | | Tất nhiên, không phải lên kế hoạch lại cho tất cả các tính năng, nhưng nó cũng đòi hỏi một cuộc điều tra hết sức chặt chẽ (緻な調査　ー　ちみつなちょうさ), và phải tốn rất nhiều chi phí cost nếu không thay đổi schedule. <br/> Tuy nhiên, vẫn nên có một số thông tin sơ bộ về thời điểm tính năng được phát hành. <br/> Nếu dự định thực thi không được ghi thì rất khó để người yêu cầu change spec nắm được khi nào chức năng sẽ được release. <br/> Giá trị này nên được update và thay đổi thường xuyên trong quá trình thực thi. <br/> Nên thông báo rõ ràng cho tất cả các bên liên quan nếu có bất cứ thay đổi nào trong mục này. |
| 8 | Status | ✔| Việc quản lý chi tiết trong tools quản lý task. Danh sách status càng rõ ràng và chi tiết càng tốt. Chẳng hạn như bên dưới: <br/> ・　New： Luôn bắt đầu ở status này. <br/> ・　In progress: Đang tiến hành: Chuyển sang status này nếu developer bắt đầu thực hiện nó. <br/>　・　Released: Đã phát hành: Status cho biết đã phát hành. Nếu không có vấn đề gì thì chuyển sang Closed. <br/> ・　Rejected: Từ chối: Nếu có issue xảy ra hay bugs chẳng hạn không đáp ứng được yêu cầu thì chuyển sang status này. Hãy giải thích rõ ràng tại sao reject. <br/> ・　Pending: Đang chờ: Nếu thay đổi là hợp lệ, nhưng vẫn còn đang suy nghĩ những việc phải làm hãy đặt chúng ở status này. <br/> ・　Closed: Đã đóng. Khi hoàn thành task và đã released thành công thì chuyển sang status này. |
| 9 | Task Ticket Link | | Điền thông tin link ticket tương ứng để biết thông tin chi tiết và tiến độ thực tế. |
| 10 | Note | | Trên thực tế, mục này có thể là quan trọng nhất trong việc quản lý. <br/> Làm thế nào mà sự thay đổi xảy ra ở đây. Hoặc ghi lại lịch sử khi có thêm thay đổi. Ví dụ: <br/> - Ngày tháng năm Tôi đã phải điều chỉnh thay đổi cho toàn màn hình, nhưng đã thay đổi thành tiêu đề. <br/> - Ngày tháng năm Xác nhận rằng infra cần phải thay đổi cấu hình của Database, vì vậy đang chờ bắt đầu. <br/> Ghi nhớ rằng phải ghi rõ ràng thời gian xảy ra. Vì trí nhớ con người có hạn, dễ quên. <br/> Loại thông tin nào hiện đang là thông tin mới nhất cho sự thay đổi spec, viết càng nhiều note càng tốt để thấy rõ sự thay đổi ấy. |

Cần phải phân biệt rõ ràng task và change spec. Những người không quen thuộc với lĩnh vực kỹ thuật có nhiều khả năng sẽ đưa ra yêu cầu không nhất quán hoặc không phù hợp với các spec hiện có.

Do đó, nếu danh sách yêu cầu và quản lý change spec được kết hợp với nhau, một lượng lớn thông tin sẽ không cần thiết và vô nghĩa.

Đây là kỹ thuật rất quan trọng, vì vậy hãy đảm bảo không kết hợp cả hai lại với nhau.

*Tham khảo ma trận mức độ ưu tiên*
![urgencymatrix]({{ site.baseurl }}/assets/images/urgencymatrix.png)

{:#summary}
## Summary

Sau khi Planning, trong giai đoạn thực thi Execution cần phải quản lý chặt chẽ những mục tiêu để có thể đưa ra đánh giá rõ ràng tình hình hiện tại của dự án và đưa ra những biện pháp cải thiện nhanh chóng.

- Task Progress : thông tin task, status, tiến độ, thời gian cam kết, etc.

- Bugs: thông tin bugs bao gồm: môi trường, thời gian, cách tái hiện, cách đối ứng, etc.

- Change specification: quản lý Change spec, đánh độ ưu tiên, quản lý thời gian thực thi và release, etc.
