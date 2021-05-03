---
layout: post
title:  "Quản lý dự án - Execution"
author: hiepvh
categories: [ BrSE ]
tags: [ PM ]
image: assets/images/execution.jpg
description: "Project Manager Execution"
featured: true
hidden: false
# rating: 4.5
---

Thực thi (Execution) là làm những công việc gì? Quản lý và control ra làm sao?

Cái notes này là bài tham khảo từ nội bộ công ty mình.

{:#tblContent}
| Contents |
|-----|
| [ Khái niệm căn bản của project planning]({{ site.baseurl }}/project-manager-planning/#basicconcept) |
| [ Project planning của phát triển phần mềm]({{ site.baseurl }}/project-manager-planning/#planningSoftware) |
| [ Chi tiết về Project Planning]({{ site.baseurl }}/project-manager-planning/#planningDetail) |
| [   　1.　Function List (include Estimation)]({{ site.baseurl }}/project-manager-planning/#functionlst) |
| [   　2.　Screen wireframe]({{ site.baseurl }}/project-manager-planning/#screenWire) |
| [   　3.　Screen specification]({{ site.baseurl }}/project-manager-planning/#screenspec) |
| [   　4.　Development process]({{ site.baseurl }}/project-manager-planning/#developProcess) |
| [ Resource Cost Estimation]({{ site.baseurl }}/project-manager-planning/#resourceEst) |
| [ Issue Management List]({{ site.baseurl }}/project-manager-planning/#issueMangeLst) |
| [Summary]({{ site.baseurl }}/project-manager-planning/#summary) |

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

