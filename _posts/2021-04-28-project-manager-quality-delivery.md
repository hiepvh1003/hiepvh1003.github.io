---
layout: post
title:  "Quản lý dự án - Quality and Delivery"
author: hiepvh
categories: [ BrSE ]
tags: [ PM ]
image: assets/images/delivery.jpg
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: true
hidden: false
# rating: 4.5
---

Tổng thể thì Quality (chất lượng) là gì? Delivery (Bàn giao) là gì?

Cái notes này là bài tham khảo từ nội bộ công ty mình.

{:#tblContent}
| Contents |
|-----|
| [Quality]({{ site.baseurl }}/project-manager-quality-delivery/#quality) |
| [ - Khái niệm cơ bản của chất lượng phần mềm]({{ site.baseurl }}/project-manager-quality-delivery/#basic-concept-of-the-software-quality) |
| [ - Làm thế nào để định nghĩa chất lượng dự án?]({{ site.baseurl }}/project-manager-quality-delivery/#how-do-we-define-the-projects-quality) |
| [   ・　Tính nhất quán về chức năng]({{ site.baseurl }}/project-manager-quality-delivery/#functional-consistency) |
| [   ・　Tần suất review technical]({{ site.baseurl }}/project-manager-quality-delivery/#technical-review-frequency) |
| [   ・　Quan điểm review technical]({{ site.baseurl }}/project-manager-quality-delivery/#technical-review-perspective) |
| [   ・　Mật độ và phạm vi Unit test]({{ site.baseurl }}/project-manager-quality-delivery/#unit-test-coverage--density) |
| [   ・　Mật độ test QA]({{ site.baseurl }}/project-manager-quality-delivery/#qa-test-density) |
| [   ・　Mật độ bug UAT - User Acceptance Test]({{ site.baseurl }}/project-manager-quality-delivery/#uat-bug-density) |
| [Delivery]({{ site.baseurl }}/project-manager-quality-delivery/#delivery) |
| [ - Làm thế nào để quản lý việc phát hành]({{ site.baseurl }}/project-manager-quality-delivery/#how-can-we-manage-the-delivery) |
| [ - Cân bằng cho QCD+S - Quality Cost Delivery + Scope]({{ site.baseurl }}/project-manager-quality-delivery/#balance-for-qcds) |
| [Summary]({{ site.baseurl }}/project-manager-quality-delivery/#summary) |

<br/>

{:#quality}
## Quality

### Basic concept of the software quality
*(Khái niệm cơ bản của chất lượng phần mềm)*

Theo Wikipedia thì khái niệm **Software quality** được định nghĩa như sau:

> ソフトウェア品質（ソフトウェアひんしつ、英: Software quality）は、ソフトウェアの品質を指し、プログラマの観点からはソースコードの品質、エンドユーザーの観点からはアプリケーションソフトウェアの品質を意味する。

> Nghĩa là: chất lượng phần mềm là chất lượng của mã nguồn theo quan điểm của một lập trình viên, và là chất lượng của phần mềm ứng dụng từ quan điểm của enduser.

{: style="text-align: center;"}
**Bảng tiêu chuẩn chất lượng Quality**

{:#tblQuality}
| Tiêu chuẩn chất lượng | Nội dung |
|-----|---|
| 理解可能性(Understandability) Tính dễ hiểu | Sản phẩm phần mềm phải có mục đích rõ ràng và dễ hiểu. Yếu tố này không chỉ bao gồm mục đích mà còn bao gồm thực tế là tài liệu thiết kế và tài liệu người dùng được viết dễ hiểu. Đây là một yếu tố quan trọng đối với một số người dùng mong đợi. <br/>Ví dụ một số sản phẩm phần mềm dành cho developer thì không cần thiết người bình thường phải hiểu. |
| 完全性(Completeness) Tính hoàn thành | Nó có nghĩa là sản phẩm có thể hoạt động độc lập và chức năng của nó đủ cho mục đích sử dụng. <br/> Ví dụ nếu cần một thư viện bên ngoài, ít nhất phải chỉ ra cách lấy thư viện đó trong phụ lục, etc... và cũng hiển thị các thông tin cần thiết. |
| 簡潔性(Conciseness) Tính giản lược | Có nghĩa là không nên có thông tin dư thừa. Điều này quan trọng trong môi trường mà memory bị hạn chế. Giảm số lượng dòng code cũng quan trọng theo nhiều cách. Có thể cải thiện bằng cách tạo ra function/method cho chức năng xuất hiện nhiều lần. Điều này cũng quan trọng đối với tài liệu |
|移植性(Portability) Tính di động | Nó có nghĩa là hoạt động dễ dàng với các cấu hình máy tính khác nhau. Có tính di động đối với sự khác biệt phần cứng (PC và Mac, v.v.) và tính di động đối với sự khác biệt về hệ điều hành (Mac OS X và GNU / Linux, v.v.). |
|一貫性(Consistency) Tính nhất quán | Có nghĩa là cách ghi chép và điều khoản là nhất quán với nhau |
| 保守性(Maintainability) Khả năng bảo trì | Nó có nghĩa là dễ dàng cải tiến để đáp ứng nhu cầu mới. Một sản phẩm phần mềm có khả năng bảo trì tốt cần phải được lập thành tài liệu đầy đủ, không phức tạp và giá cả phải chăng về dung lượng bộ nhớ và hiệu suất. |
| 試験性(Testability) Khả năng kiểm thử | Có cách tiêu chí đánh giá/accept rõ ràng. Sự kết hợp ở giai đoạn thiết kế là rất quan trọng. Ngoài ra, thiết kế phức tạp làm giảm khả năng kiểm thử. |
|ユーザビリティ(Usability) Tính khả dụng  | Thuận tiện và thiết thực cho enduser. Giao diện người dùng cực kỳ quan trọng |
| 信頼性(Reliability) Độ tin cậy | Các chức năng phải được thực hiện đầy đủ việc ngăn chặn lỗi ảnh hưởng đến người dùng. Điều này cũng bao gồm khả năng thực hiện chức năng trong khoảng thời gian nhất định. Ngoài ra, khi được yêu cầu, nó được yêu cầu tiếp tục hoạt động không dừng lại ngay cả khi lỗi xảy ra. Đây cũng được gọi là độ bền. |
|構造化の度合い(Structuredness) Có cấu trúc  | Các thành phần phải đồng nhất với nhau. Phần mềm được viết bằng ngôn ngữ có cấu trúc đáp ứng thuộc tính này. |
| 効率性(Efficiency) Tính hiệu quả | Không lãng phí nguồn lực khi đạt được mục đích. Tài nguyên trong trường hợp này là mức sử dụng bộ nhớ và thời gian sử dụng bộ xử lý. |
| セキュリティ(Security) | Bảo vệ dữ liệu khỏi truy cập trái phép và chống lại các hoạt động độc hại. Nó liên quan đến hiện diện hay vắng mặt của cơ chế bảo mật như basic authen, kiểm soát truy cập và mã hóa |

{: style="text-align: center;"}
External and Internal Quality Defination

![ENIQD]({{ site.baseurl }}/assets/images/ENIQD.png)

**Quản lý dự án cần hiểu hết tất cả khái niệm này, suy nghĩ xem nên áp dụng cách đánh giá nào cho dự án và đề xuất nó với các bên liên quan.**


### How do we define the project's quality?
*(Làm thế nào để định nghĩa chất lượng dự án?)*

Tùy theo dự án mà khái niệm về chất lượng phần mềm sẽ khác nhau.

Những khái niệm dưới đây chỉ mang tính chất chung.

#### Functional consistency
*(機能の一致性 - Tính nhất quán về chức năng)*

Điều này cho biết chức năng có được phát triển theo đúng yêu cầu hay không?

Ngay từ ban đầu đã có sự hiểu lầm nghiêm trọng xảy ra trong giai đoạn đầu của quá trình phát triển và sự khác biệt trong nhận thức giữa client và team dev mặc dù đã có hướng dẫn rõ ràng.

Ngoài ra, trong quá trình phát triển có những phần mà nghĩ là nếu khách hàng không giải thích thì bên team dev cũng sẽ hiểu thôi thì "tính nhất quán về chức năng" sẽ thấp.

Nguyên nhân chính khiến chỉ số này thấp như sau:

- Có một lỗ hổng lớn về spec mà vẫn cứ tiếp tục develop (Cung cấp spec không chính xác).

- Người cung cấp spec không nhận thức được việc sai spec và giải thích nó làm cho nó được thực hiện sai.

- Có những phần chưa rõ ràng trong spec được cung cấp mà được bổ sung, thông báo bằng cách trao đổi miệng, và lập trình viên thì không nhớ điều đó. (Không hiểu biết về các thông tin liên quan)

- Trong quá trình phát triển, team dev cố tình triển khai một phương thức khác với spec nhưng không thông báo trước. (Lỗi giao tiếp)

Dự án bình thường thì khó xuất hiện những việc trên, tuy nhiên nếu tần suất 1 tháng xuất hiện 1 lần thì phải thực hiện một số biện pháp giải quyết.

Chúng ta phải nhận thấy điều không ổn nếu từ khách hàng có feedback là Spec không đúng như những gì đã yêu cầu.

Cụ thể, hãy kiểm tra xem có bao nhiêu trong số các pattern trên tồn tại để phân loại thuộc lỗi nào?

Việc này nên tự tay Quản lý dự án thực hiện hơn là để các thành viên trong team thực hiện.

Ngay từ đầu, có khả năng các thành viên đang phát triển thực sự chưa hiểu rõ yêu cầu dẫn đến nhầm lẫn, vì vậy, nếu để họ phân loại, có thể chúng ta sẽ nhận được kết quả sai.

Ngoài ra, phân tích này không thể được thực hiện nếu không có sự hiểu biết chính xác về những gì khách hàng đã yêu cầu.

Dưới đây là một ví dụ về Phân tích nguyên nhân

{: style="text-align: center;"}
**TABLE : Cause analysis sample**

{:#tblCauseIssues}
| # | Cause category of reported issues by the client |
|-----|---|
| 1 |Found out the issue is a new requirement, not a system defect. <br/>  完全な新規の要求事項|
| 2 |Wrong specification in a requirement <br/> 仕様に誤りがあった |
| 3 |Lack of specification in a requirement <br/> 仕様に不足があった |
| 4 | Misunderstanding specification by development team <br/> 仕様を開発チームが誤解した |
| 5 | Oversight of specification / Not written in a requirement, but easy to guess <br/> 仕様に記載はなかったが，予想できる範囲内だった |
|6  | Inappropriate system design by development team	<br/> 不適切なシステムデザインだった	 |
| 7 | Lack of impact range research by development team <br/>  影響範囲調査が不足していた|
| 8 | Skip Engineer Implement review <br/> コードレビューを怠った，バグを見過ごした |
| 9 | Lack of QA test items <br/> QA のテスト項目が足りていなかった |
| 10 |Skip QA Test / Out of a testing range for this release <br/> QA のテストをスキップした　対象範囲外だった |
| 11 | Insufficient testing environment to detect the issue on a test	<br/> 適切なテスト環境を構築することができなかった  |
|12  | Inappropriate server setting of production environment which was set by a client engineer<br/>	本番サーバの設定が正しくなかった  |
| 13 | Bug implemented in production code directly by a client engineer	<br/>本番サーバのコードをクライアントが直接変更した  |
| 14 | Withdraw issue / Found out the issue is not system defect, follows current specs.	<br/>障害だと思っていたが，そう  |
| 15 | Duplicated / Abort duplicated counts on a another category	<br/>既に報告していて重複しているのでカウントしない  |
| 16 | Others	<br/>その他  |


#### Technical review frequency
*(Tần suất review technical)*

Trường hợp phát sinh lỗi phổ biến là code của lập trình viên không đủ skill gây ra.

Đảm bảo là tất cả các ticket khi thực hiện phải được review một cách tốt nhất.

Trên thực tế, nếu chúng ta có đủ kỹ năng technical và đánh giá của các thành viên trong team không cao lắm, thì với tư cách là người quản lý dự án, hiệu quả nhất là chúng ta nên kiểm tra lần cuối việc review code để giữ chất lượng dự án một cách tốt nhất.

Tuy nhiên, thường thì chúng ta không có đủ thời gian đó, hoặc nếu tình trạng của team đang quá tải, thì các review có thể không đủ chất lượng.

Tìm hiểu bảng Đường trung bình động, chúng ta có thể hiểu được loại xu hướng tăng hay giảm đang xảy ra.

https://en.wikipedia.org/wiki/Moving_average


Ở giai đoạn Planning, hãy đặt giá trị mục tiêu cho tần suất các review sẽ được thực hiện.

![review]({{ site.baseurl }}/assets/images/review.png)

Bảng trên là một ví dụ về các mục tiêu cho những danh mục nào và tần suất bao nhiêu chúng được review.

#### Technical review perspective
*(Quan điểm review technical)*

Ngoài tần suất của các review thì xác định quan điểm review cũng rất quan trọng.

Nó định nghĩa những gì cần review.

Ví dụ:

> https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md


#### Unit test coverage & Density
*(Mật độ và phạm vi Unit test)*

Unit test ở đây được tạo bằng RSpec hoặc PHPUnit.

Việc test này phụ thuộc vào từng dự án nhất định.

Đầu tiên là Coverage (độ phủ), giải thích sẽ rất dài nên tham khảo link dưới nhé!

- https://en.wikipedia.org/wiki/Code_coverage

- https://www.slideshare.net/hiroppie/test-coverage

Điều quan trọng là xác định chắc chắn nên tạo ra Unit test ở level nào?

Unit test cũng mô tả bằng mật độ.

Bản thân mật độ kiểm tra là một khái niệm rất phức tạp, nhưng về cơ bản nó có thể được biểu thị bằng công thức sau.

> Test dentsity = Test case count / Line of Code (LOC)

Với con số này, chúng ta có thể biết được có bao nhiêu test case ứng với số lượng dòng code.

Giá trị này như thế nào là phù hợp thì tùy vào tình hình dự án và mục tiêu quality yêu cầu.

Nó cũng phụ thuộc vào ngôn ngữ lập trình sử dụng.

Đối với các dự án yêu cầu chất lượng cực cao, chẳng hạn product nhúng thì giá trị này có thể cao tới 10.

Nói cách khác, điều này có nghĩa là chúng ta phải viết hơn 10 test case cho mỗi dòng code.

Trên thực tế thì điều quan trọng là con số này nó thay đổi thế nào trong khi dự án đang phát triển, hơn là giá trị khi kết thúc dự án.

Nếu mật độ này giảm khi dự án tiến triển, nó có thể làm giảm các lỗi cần được phát hiện bằng các bài Unit test.

Ngoài ra, nếu mật độ này không thay đổi, nhưng mật độ lỗi được tìm thấy trong quá trình tiếp theo cao, có thể độ chính xác của Unit test đã giảm và nhiều test case vô ích đã được viết ra.

![density]({{ site.baseurl }}/assets/images/density.png)

#### QA test density
*(Mật độ test QA)*

Các danh mục QA Test có thể được phân loại như sau:

- Function test
  - Test chức năng có hoạt động bình thường không
  - Bao gồm cả hệ thống bình thường và bất thường.

- Layout test
  - Đây là một bài test kiểm tra xem có bất kỳ bất thường rõ ràng nào không
   Các thiết kế sai và hài hước cũng thuộc loại này

- Performance test
  - Kiểm tra xem liệu đủ hiệu suất được thể hiện trong điều kiện sử dụng bình thường hay không và nó có thể hoạt động chính xác không

- Stress test
  - Xác nhận xem hệ thống có hoạt động trong điều kiện khắc khe hơn bình thường hay không? Chẳng hạn như tải cao do mạng và khối lượng data và các điều kiện bất thường khác.

- Access & Security test
  - Hệ thống có thể chịu được truy cập có hại hoặc các nỗ lực xâm nhập vào hệ thống hay không

Những khái niệm chung này được áp dụng vào phát triển theo mô hình chữ V.

![Vimage]({{ site.baseurl }}/assets/images/Vimage.jpg)


#### UAT bug density
*(Mật độ bug UAT - User Acceptance Test)*

Số lượng bugs được tìm thấy trong bài test chấp nhận được của khách hàng.

Ngay từ đầu, các nội dung được UAT xác nhận có thể khác nhau rất nhiều giữa các dự án.

Trong mô hình chữ V ở trên, UAT xác minh rằng các yêu cầu nghiệp vụ được trình bày ban đầu được đáp ứng.

> Bug density = Bug count / Line of Code (LOC)

Cách tính thông thường mật độ bug theo công thức trên.

Mức độ mật độ lỗi được UAT cho phép cũng sẽ là một tiêu chí cho chất lượng.

Chúng ta nên chia quá trình phát triển sản phẩm một cách đại khái như sau và thiết lập những gì cần xem xét trong mỗi quá trình.

![sampleprocess]({{ site.baseurl }}/assets/images/sampleprocess.png)

{:#delivery}
## Delivery

### How can we manage the delivery?
*(Làm thế nào để quản lý việc phát hành)*

Delivery đơn giản có thể hiểu là giao hàng cái gì đó.

Vậy là thế nào để biết giao hàng đúng cách?

Có ba yếu tố chính tạo nên Delivery như sau:

- Delivery destination (Nơi giao hàng)
  - Quan điểm của "nơi" để giao hàng. 「どこに」
  - Nếu có nhiều môi trường cần delivery thì phải suy nghĩ phân phối cho từng môi trường khác nhau.
- Delivery deadline (Thời gian giao hàng)
  - Quan điểm là phải giao hàng cho tới thời điểm nào?　「いつまでに」
  - Đặt mục tiêu cho từng chức năng hoặc cho từng bản phát hành chính.
- Delivery frequency (tần suất giao hàng)
  - Tiến độ giao hàng như thế nào?
  - Theo quan điểm Agile thì phải "Chạm vào và xác nhận những thứ đang hoạt động".
    - "Working software over comprehensive documentation". Tham khảo: https://agilemanifesto.org/

### Balance for QCD+S
*(Cân bằng cho QCD+S - Quality Cost Delivery + Scope)*

Trước đây, chỉ được gọi là QCD cho Quality, Cost và Delivery. Nhưng bây giờ còn có thêm các khái niệm QCDS và QCDF (Feature).

https://en.wikipedia.org/wiki/Quality,_cost,_delivery

Nhưng tôi nghĩ là khái niệm quan trọng nhất là QCDS.

Mối quan hệ giữa QCDS như hình bên dưới.

![QCDS]({{ site.baseurl }}/assets/images/QCDS.png)

Delivery được thay thế bằng TIME.

Thời gian, Chi phí và Phạm vi, tương ứng với ba cạnh, được kết nối và nếu bạn thay đổi bất kỳ cạnh nào trong số chúng, diện tích của tam giác sẽ thay đổi.

Và đầu ra sẽ thay đổi tùy thuộc vào lượng Phạm vi được phân bổ cho Tính năng và Chất lượng.

Ví dụ ở đây là sắp phải release một tính năng không được triển khai kịp thời và chugn1 ta phải giảm phần trăm thời gian testing, chugn1 ta đang giảm Scope và Quality, dẫn đến nhiều lỗi hơn. Điều đó hoàn toàn có thể xảy ra.





















## Summary
Tạm kết, Quản lý dự án là một nghề cần nhiều thứ và Mindset là cái quan trọng nhất.

>　**Mindset của PM**
> 1. Tất cả đều là lỗi của người quản lý dự án.
> 2. Tận dụng hết thời gian
> 3. Cần truyền giáo, không cần gây chiến tranh
> 4. Hãy nhìn ra mặt biển mỗi ngày, mỗi giờ
> 5. Ở trong chiến trường đẫm máu nhất
> 6. Đừng là nút thắt cổ chai
> 7. Hành động như một người phục vụ
