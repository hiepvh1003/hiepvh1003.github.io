---
layout: post
title:  "Quản lý dự án - Planning"
author: hiepvh
categories: [ BrSE ]
tags: [ PM ]
image: assets/images/planning.jpg
description: "Quản lý dự án là nghề làm dâu trăm họ, nhưng niềm vui là được học hỏi mỗi ngày, mỗi giờ, mỗi thời điểm."
featured: false
hidden: false
# rating: 4.5
---

Khái niệm cơ bản về Project Planning là gì? Các công việc cần phải làm khi tạo Planning cho project.

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
## Basic concept of project planning
*(Khái niệm căn bản của project planning)*

Lập kế hoạch dự án là một trong những nhiệm vụ quan trọng của người quản lý dự án.

Trên thực tế, điều đầu tiên phải nói đến là ảnh hưởng to lớn của quy trình phát triển Waterfall.

Đây là một khái niệm được thiết lập đặc biệt trong ngành xây dựng.

Trong khi xây dựng, đặc biệt là các tòa nhà lớn, việc có những thay đổi lớn khi xây dựng theo tiến độ là không nên xảy ra.

Lý do là nếu xây dựng được nửa chừng, thay đổi một cái thì không chỉ những phần đã được tạo ra rồi mà kể cả những phần sắp tới được tạo cũng sẽ bị ảnh hưởng rất lớn và nguy hiểm.

Ví dụ, nếu đang xây một tòa nhà mà đột nhiên nhận được yêu cầu xây hồ bơi trên mái nhà, gần như là không thể thực hiện được điều này.

Không chắc chắn rằng kế hoạch ban đầu cho cấu trúc cơ cấu có thể không chịu đựng được hồ bơi.

Ngoài ra, không gian để lắp ống nước lớn và bể để chứa nước trong hồ bơi thì chắc là bất khả thi rồi.

Trong ngành công nghiệp không thể thay đổi này, lập kế hoạch planning ban đầu là rất quan trọng.

{:#planningSoftware}
## Project planning of software development
*(Project planning của phát triển phần mềm)*

Bây giờ, planing trong phát triển phần mềm thì thế nào?

Ngược lại với xây dựng, phát triển phần mềm mà đòi lập kế hoạch hoàn chỉnh một hệ thống khổng lồ ở giai đoạn đầu là vô cùng khó khăn, nếu không muốn nói là không thể.

Để hoàn thiện kế hoạch phát triển phần mềm ngay từ đầu mà không thay đổi nó thì phải tốn rất nhiều tiền (cost and resource).

Đó là bởi vì chúng ta phải lường trước tất cả những điều không chắc chắn có thể trở nên rõ ràng trong quá trình phát triển và đưa ra quyết định rõ ràng trước.

Ngoài ra, khi nói đến một dự án lớn, có nhiều khác biệt trong kỳ vọng của các bên liên quan. Tất cả nhu cầu khác nhau của các bên liên quan này phải được kết hợp với nhau.

Rắc rối xảy ra là kỳ vọng của các bên liên quan này thường không nhất quán và mâu thuẫn với nhau.

Nói cách khác, việc cưỡng cầu quyết định mọi thứ để thực hiện một planning ngay từ ban đầu là một vấn đề rất lớn.

Phải nói rằng, planning trong quá trình chờ đợi các bên liên quan xác nhận thật là một sự lãng phí thời gian.

Trước hết, trong hầu hết các trường hợp, công ty và các thành viên thực sự thực hiện và phát triển ngay từ khi chưa được quyết định ở giai đoạn planning.

Ở giai đoạn này, chúng ta có thể dự đoán đầy đủ chi phí phát triển là bao nhiêu và mất bao lâu để giải quyết mọi vấn đề nảy sinh trong quá trình phát triển?

Trong hoàn cảnh như thế thì Agile ra đời.

Cơ bản, Agile ra đời để **"thích ứng với sự thay đổi" (変化に対応する)** hơn là **"bắt đầu với dự đoán mọi thứ" (全てを予想しきってスタートする)**.

Nhưng đừng lầm tưởng với việc không thể lập planning trong phát triển phần mềm, chúng ta nên bắt đầu về nó và sau đó suy nghĩ về nó.

Có những mục cần phải được quyết định và scope nên được quyết định ngay từ step planning này.

{:#planningDetail}
## Project planning detail
*(Chi tiết về Project Planning)*

Vậy, chúng ta cùng làm rõ "Cái gì" và "mức độ chi tiết" nên được lên plan trong việc phát triển phần mềm.

Không phải tất cả các tài liệu đều phải được tạo ra trong giai đoạn Planning. Điều quan trọng là những người tham gia vào dự án phải nhận ra rằng "document nào phải được tạo ra" và "input của project này là cần phải có những thứ gì?".

{:#functionlst}
### 1. Function List (include Estimation)
*(Danh sách chức năng - bao gồm cả dự toán)*

Điều quan trọng nhất là danh sách các chức năng.

Sự phát triển của từng chức năng được quản lý chi tiết bằng một tool quản lý task nào đó, như redmine, backlog, jira.

Danh sách chức năng này là để mọi người hiểu rằng *"Từ bây giờ sẽ phải làm gì?"*

Các tính năng mô tả không được quá lớn hoặc quá chi tiết.

Nếu đơn vị chức năng quá lớn, độ chính xác estimate review và feedback sẽ bị giảm xuống.

Ngay từ đầu, một danh sách các chức năng chưa được chia thành nhiều phần nhỏ sẽ làm tăng nguy cơ không thể tìm ra những thiếu sót cần xem xét. Do đó, ngay cả khi nó đã được tạo ra, nó sẽ trở nên vô nghĩa.

Ngược lại, nếu đơn vị chức năng quá nhỏ, người đọc sẽ phải mất nhiều thời gian để hiểu danh sách và chi phí (effort) duy trì danh sách sẽ tăng lên.

Danh sách này phải dễ dàng cho cả những người liên quan đến dự án và quản lý dự án.

POINT thì gợi ý như bên dưới.

{:#tblPlan}
| # | Check items | Note |
|---|---|---|
| MUST |それぞれの機能については，誰が読んでもわかりやすいように名称を記載する．<br/>  Tên của chức năng được đưa ra để mọi người dễ dàng đọc chúng. | プロジェクトについて全く知識のないシニアレベルのエンジニアがひと目で概要を理解できる程度を目指す <br/> Hướng tới người cấp cao không có kiến thức về dự án để hiểu sơ lược về dự án. |
| MUST | 5 人日以下の粒度まで機能を分割する <br/> Từng chức năng nên chia ra để dưới 5 manday | 詳細な工数は，タスク管理ツールにて記録するので，ここでは正確な見積もりを記載しなくて良い <br/> １つ１つの機能が大きくなりすぎないようにする <br/> 工数が大きすぎる機能は，見積もりが大きくずれるリスクが増えるため <br/> 工数が大きすぎる機能は，作業完了を確認するまでの時間が長くなり，リカバリの時間が十分に取れないリスクが増えるため <br/> Manday chi tiết thì log lại bằng tool quản lý task nên không cần cung cấp thông tin chi tiết ở đây. <br/> Ngăn không cho các chức năng quá lớn <br/> Các chức năng yêu cầu quá nhiều thời gian làm tăng nguy cơ sai lệch trong estimate |
| MUST | バッファや遅延リスクの予測精度をあげるために，次の４点を評価する <br/>これは見積もりの際の計算のためのタスク難易度として利用する(task difficulty) <br/> - ロジックの複雑度 (Logic Complexity) <br/> - UI の複雑度 (UI Complexity) <br/> - チームにとって新しい技術を利用するか (New technique) <br/> - 仕様に不明点や不確定な部分が多いか (Specification Un-detailedness) <br/> Bốn điểm sau đây được đánh giá để cải thiện độ chính xác dự đoán và đánh giá <br/> Điều này được sử dụng như độ khó của estimate cho việc tính toán khi estimate <br/> - Độ phức tạp logic <br/> - Độ phức tạp của giao diện người dùng  <br/> Sử dụng công nghệ mới <br/> Có nhiều điều không chắc chắn trong spec | 機能ごとの複雑度 <br/> チームにとって新しい技術を使用するか？ <br/> 仕様の不明点はないか <br/> Độ phức tạp theo chức năng <br/> Chúng ta sẽ sử dụng công nghệ mới? <br/> Có điểm nào chưa rõ ràng trong spec |
| MUST | 機能ごとにそれぞれの工数を見積もり，時間[hour]で記入する  <br/> - Implement(includes System-design) <br/> - Unit test <br/> - QA test <br/> - Bug fix <br/> Estimate man hour |  Implement(includes System-design) <br/> - 機能ごとの開発にかかる時間 (Thời gian cần thiết để phát triển từng chức năng) <br/> - 設計する時間も含む (Bao gồm cả thời gian thiết kế) <br/> Unit test <br/> <br/> - 必ず枠を用意する (Cần phải chuẩn bị border) <br/> - プロジェクトで Unit test を実施しない場合は 0 と記入し，項目は削除してはいけない (Nếu không dùng Unit test thì nhập 0 và xóa các item) <br/> QA test <br/> - Bug fix した再テストを考慮に入れる (Tính đến các lần test lại sau khi fix bugs) |
| Recommended | Unit test や QA test や Bug fix については，係数を設定して時間を計算する <br/> Đối với Unit test, QA Test và Fix bug thì tính toán và đặt hệ số.  |  この際，task difficulty を利用する <br/> 計算のための係数が明らかになるように別表を作成する <br/> QA test については，QA で独自に見積もりをして時間を入れてもよい <br/> Tại thời điểm này, sử dụng Task Difficulty <br/> Tạo một bảng riêng biệt để các hệ số cho phép tính trở nên rõ ràng. <br/> Đối với QA Test, có thể thảo luận với QA và đưa ra hệ số để đưa ra thời gian. |
| MUST | 途中計算のために利用した読み手にとって意図のわからない数値をシート上に記載しない <br/> Không ghi trên sheet các giá trị số mà người đọc tính toán không hiểu. | - 為替のレートや工数計算のための係数は，しっかり何を目的としたものなのか説明を記載するか，数値自体を削除する <br/> - 意図のわからない数字は読み手の理解度をさげる <br/> - 途中計算として必要なものなのであれば，説明を書いておかないと，シートのメンテナンス性が下がり，後から編集する人が理解するための時間を無駄にする <br/> - Mục đích của tỷ giá hối đoái và hệ số tính theo man hour là gì hoặc xóa chính giá trị đó thì phải được giải thích rõ ràng <br/> - Những con số không làm giảm khả năng hiểu của người đọc chúng <br/> - Nếu cần thiết phép tính trung gian, nếu không viết giải thích, khả năng bảo trì sheet sẽ giảm và thời gian những người làm sau này sẽ tăng lên.|
| MUST | 入力した工数は，詳細な計画を作るための情報であり，コミットメントではないことを記入する <br/>  Ghi effort là thông tin để ghi vào bản kế hoạch chi tiết, không phải để commit. | 「これは全体スケジュールを策定するために，プロジェクト初期に想定した工数であり，作業をすすめるに従って増減する可能性があります． <br/> Đây là effort được giả định ban đầu để hình thành overview của dự án, có thể tăng hoặc giảm khi công việc tiến triển. |
| MUST | 入力した数字は，単位がわかるようにする <br/> Những con số đã nhập phải được hiểu cùng đơn vị tính  | 1h や 3md のように数字のそばに単位を書くという意味ではない <br/> 表のカラムの上部などに記載する <br/> 単位は [hour] などのように "[]" で囲む <br/> Không phải mang ý nghĩa là đơn vị số như 1h hay 3md <br/> Mô tả ở đầu cột bảng <br/> Đặt đơn vị trong duấ ngoặc như [hour] |
| MUST | 数値について，表示する小数点の桁数を揃える <br/> Chỉnh sửa giá trị số thập phân để có thể nhìn thấy được.  | 少数点２桁までを表示するとした場合 (Trường hợp 2 dấu thập phân) <br/> 1 → 1.00 hoặc 4.321 -> 4.32 |
| MUST | 数値の合計は，spreadsheet などの関数を利用し，手入力で計算した結果を入れてはいけない <br/> Đối với tổng các giá trị số, hãy sử dụng một hàm như bảng tính và không nhập kết quả được tính theo cách thủ công. | 後で各数値に変更があったときに，古い値が残り続けるリスクを排除する <br/> Loại bỏ rủi ro các giá trị cũ còn lại khi mỗi số thay đổi sau đó |
|  | 機能の数を数えやすいように，# をつけて序数を記入する <br/> Nhập số thứ tự bằng # để đếm số hàm dễ dàng hơn.  | タスクの全体量をプロジェクトに関わる人に大まかに理解させるため <br/> タスクについての話し合いをするときに「No.# のタスクについて」など，番号で呼ぶことで聞き手のストレスを軽減するため  <br/> 基本的なことだが重要 <br/> Cung cấp cho những người liên quan đến dự án hiểu biết sơ bộ về tổng khối lượng nhiệm vụ<br/> Để giảm căng thẳng cho người nghe bằng cách gọi theo số, chẳng hạn như "Về nhiệm vụ số #" khi thảo luận về nhiệm vụ <br/> Cơ bản nhưng quan trọng |
| MUST | 視認性をあげるために，機能名を表すために３段階ほどでカテゴリを分ける <br/>  Để cải thiện khả năng hiển thị, các danh mục được chia thành khoảng 3 giai đoạn để thể hiện tên chức năng. | 人間の脳は一度に大量の情報を見せても処理できない <br/>読み手の頭の中にきれいなフォルダ分けをしてあげるようにする <br/> カテゴリーの１つ目は，開発対象の画面やバッチの種類などを記入するのが良い <br/> Bộ não con người không thể xử lý ngay cả khi nó hiển thị một lượng lớn thông tin cùng một lúc <br/> Cố gắng giữ một thư mục sạch sẽ trong đầu người đọc <br/> Đối với loại đầu tiên, tốt để nhập màn hình được phát triển và loại hàng loạt. |
| MUST | 一覧に着色をする際は，目立つ色を最初から使わない <br/> Khi tô màu danh sách, đừng sử dụng các màu nổi bật ngay từ đầu  |  最初の機能一覧は，文字の色となる黒色の他に，薄い寒色を１つだけ使うことにする <br/> 赤や黄色などは，後から注目を引くために使い可能性があるので使用してはいけない <br/> 文字のフォントやポイントを統一し，読み手に不必要な情報を与えて，無駄な思考をさせないようにする <br/> 色が鮮やかすぎる蛍光の緑などは，シートを見づらくし，またその色に特別な意味があるように見えるので，基本的に使用しない <br/> Đối với danh sách chức năng đầu tiên, ngoài màu đen, là màu của các chữ cái, chúng tôi sẽ chỉ sử dụng một màu lạnh nhạt <br/> Không sử dụng màu đỏ, vàng, v.v. vì chúng có thể được sử dụng để thu hút sự chú ý sau này. <br/> Thống nhất phông chữ và điểm của các ký tự, cung cấp cho người đọc thông tin không cần thiết và tránh suy nghĩ không cần thiết <br/> Màu xanh lá cây huỳnh quang, là màu quá sáng, khó nhìn thấy tờ giấy và màu sắc dường như có ý nghĩa đặc biệt, vì vậy về cơ bản nó không được sử dụng. |
| MUST |なるべく省略したり短縮した表記を使わない．誰にでも理解できる状態を目指す <br/>  Không sử dụng ký hiệu viết tắt hoặc viết tắt càng nhiều càng tốt. Hướng đến trạng thái mà bất kỳ ai cũng có thể hiểu được |  Dev → Development, Developer <br/> UAT → User Acceptance Test|
| MUST | 空白の欄を作らない <br/> 入力しないなら "–" や "N/A" など明確に値が存在しないことを示す <br/> 0 であるならば，0 と入力する <br/> セルをマージするなどして，同じコンテンツをまとめる <br/> Không tạo field trống <br/> Nếu không nhập được thì dùng "-" hoặc N/A <br/> Nếu là 0 thì hãy nhập 0 <br/> Kết hợp cùng một nội dung, chẳng hạn như merge các ô lại.  |  何よりも作成者が，自分自身で入力漏れを発見する可能性を作る <br/> 自動計算で表示されるようにしているなら，そもそも 0 など入力しなくても良い状態である．0 と入力しなければならないのなら，そのことについて疑問をもつ <br/> 一覧を見る側にとっても，入力漏れなのかどうかの疑問を持たずに済む<br/> Trên hết, người tạo có thể tự mình phát hiện ra các thiếu sót đầu vào. <br/> Nếu nó được hiển thị bằng tính toán tự động, thì không cần nhập số 0 ngay từ đầu <br/> Ngay cả người xem danh sách cũng không phải đặt câu hỏi liệu đầu vào có bị thiếu sót hay không. |

Mỗi hệ số và trọng số không phải lúc nào cũng thực sự có. Tuy nhiên, tại sao người xem list này lại tốn nhiều thời gian?

Ở đây, estimate là theo Task Difficult và nó có thể được tính toán tự động. Nó áp dụng ý tưởng Planning Pocker được sử dụng để phát triển trong Agile.

cf. https://en.wikipedia.org/wiki/Planning_poker

Lập kế hoạch Poker là một phương pháp ước tính trọng số của mỗi nhiệm vụ bằng cách trao đổi các giá trị với các thẻ dựa trên ý tưởng rằng "Tôi nghĩ đó là về điều này" và làm cho sự công nhận trong các thành viên là đồng nhất.

Chúng ta cố gắng chia nhỏ ý tưởng thành từng bước một. Tại thời điểm estimate, chúng ta ước tính "khoảng chừng này!". Từ kinh nghiệm trong đầu và mức độ phức tạp của nhiệm vụ.

Và có nhiều người không thể giải thích được tại sao họ lại ước lượng nó tốt như vậy!

{: style="text-align: center;"}
Ví dụ về tính Task Difficult

![taskdifficult]({{ site.baseurl }}/assets/images/taskdifficult.png)

{:#tblFomula}
| Cách tính hệ số Effort - Effort Coefficient Fomula|
|-----|
|Effort Coefficient = <br/> Logic Complexity Score * Logic Complexity Weight <br/> + UI Complexity Score * UI Complexity Weight <br/> + New Technique Score * New Technique Weight <br/> + Spec Un-detailedness Score * Spec Un-detailedness Weight |

{:#tblFomula}
| Ước tính Effort phát triển - Estimated Development Effort Fomula |
|-----|
|Estimated Development Effort [Man-Hour] = Effort Coefficient / 2 |

{:#tblFomula}
|-----|
|Estimated QA Effort [Man-Hour] = Estimated Development Effort [Man-Hour] * 0.3 |

{:#screenWire}
### 2. Screen wireframe

Việc tạo wireframe cho các màn hình thì sẽ khác nhau tùy theo dự án, nhưng cơ bản là nên chuẩn bị sẵn thì tốt nhất.

Một wireframe có thể có nhiều thành phần được thiết kế. Tuy nhiên, nếu sử dụng Thiết kế hoàn chỉnh từ đầu Design Comprehension Layout thì sẽ rất khó khăn trong việc quản lý. Lý do là nếu có bất kỳ sự thay đổi nào thì sẽ dẫn đến thiết kế đó out of dates.

Design Comprehension Layout đòi hỏi rất nhiều effort của designer. Mặt khác, các designer thì chỉ thường join vào khoảng đầu dự án, trong khi vào giai đoạn development thì effort thường được giảm xuống có khi là không có.

Tuy nhiên, trong phát triển phần mềm thì việc sửa đổi và điều chỉnh là xảy ra rất nhiều.

Cho đến khi kết thúc dự án, không chắc chắn được rằng Design Comprehension Layout được cập nhật một cách chi tiết và đầy đủ nhất.

Điều gì xảy ra nếu chúng ta sử dụng tài liệu mà tốn quá nhiều effort quản lý và update như vậy?

Có một số cách tiếp cận để giải quyết vấn đề này, nhưng cũng có những rủi ro lớn là các tài liệu không được update ngay từ lúc đầu vẫn tiếp tục được công nhận là input của giai đoạn develop.

Là người quản lý dự án, chúng ta phải xác định cách xử lý các tài liệu có tính update thấp như vậy.

Quay lại với wireframe.

Chúng ta không nên develop mà chỉ dựa vào wireframe.

Nguyên nhân là do nhiều trường hợp không đủ thông tin khi thực sự áp dụng vào hệ thống. Như là các chuyển động animation, etc.

Do đó, tốt hơn hết là nên tập trung vào quản lý Screen specification được mô tả bên dưới đây thay vì tập trung vào wireframe.

{: style="text-align: center;"}
**Ví dụ Wireframe**

![wireframe]({{ site.baseurl }}/assets/images/wireframe.png)

{:#screenspec}
### 3. Screen specification

Đây là thông số kỹ thuật cho màn hình.

Giống như wireframe, cái gì có ở đâu, lấy data từ chỗ nào.

**Ví dụ trường hợp RDBS (Relationship database system) thì:**
- Database
- Table
- Column

**Đối với các fields input thì:**
- Required or not
- Minimum length
- Maximum length
- Allowed format
- etc...

**Giải thích về logic**

**Define các error messages**

{:#developProcess}
### 4. Development process

Quy định về process trong quá trình develop.

Chúng ta nên xây dựng dựa vào nhũng thế mạnh của chúng ta.

Dưới đây là mô tả về quy trình chung.


{: style="text-align: center;"}
**table example develop process**

![developprocess1]({{ site.baseurl }}/assets/images/developprocess.png)

![developprocess1]({{ site.baseurl }}/assets/images/developprocess2.png)

Bây giờ, chúng ta sẽ hình dung là quá trình phát triển theo plan thì sẽ có hai việc chính cần phải làm.

**1. Làm cho những người tham gia vào dự án hiểu được quy trình là gì, đặc biệt là input và output theo cấp độ.**

**2. Làm cho những người tham gia vào dự án hiểu được tại sao lại phải có quy trình như vậy.**

Với vấn đề đầu tiên, điều này thường được kiểm soát bằng việc quyết định format.

Có một số trường hợp, các process được quyết định khi mà các member lược bỏ bớt những phần output. Nhiều trường hợp Unit test và Technical review bị lược bỏ mà không được phép.

Chúng ta có thể thực hiện theo quy trình đã lập ra kết hoạch bằng cách đảm bảo rằng kết quả đầu ra KHÔNG ĐƯỢC cho phép thiếu Unit test và Review.

Ngoài ra, bằng cách trình bày theo format cho khách hàng, chúng ta có thể hiểu được loại input nào được yêu cầu.

Không phải khách hàng nào cũng có thể cung cấp input một cách chính xác và đầy đủ. Đối với những khách hàng như thế, chúng ta phải là người bổ sung nhung điều đó.

Ví dụ, khách hàng chưa thêm các message màn hình lỗi nhất thời, chúng ta phải là người thêm vào quy trình thực hiện.

{:#resourceEst}
## Resource Cost Estimation

Xem xét cách phân bổ nhân sự theo số giờ công ước tính.

{:#issueMangeLst}
## Issue Management List

Danh sách quản lý vấn đề.

Vấn đề issue ở đây được định nghĩa như sau:

> プロジェクトにおいて発生した，まだ解決方法がはっきりと検討されていないが， 現在問題となっている，または今後において問題となる可能性のあるもの

Có nghĩa là: Bất cứ điều gì xảy ra trong dự án và giải pháp vẫn chưa được xem xét rõ ràng, nhưng hiện tại là một issue hay tương lai có thể xảy ra.

Trong dự án thực tế, thay vì các issue, có một danh sách các báo cáo bugs nhận từ khách hàng.

Đây không phải là issue, đây chỉ là bug.

Dưới đây là một số issue được coi là phù hợp.

![issueLst]({{ site.baseurl }}/assets/images/issueList.png)


{:#summary}
## Summary
Tạm kết, Planning trong Quản lý dự án là một công việc quan trọng ngay từ lúc khởi tạo dự án.

>　**Project Planning**
> 1. Khái niệm căn bản của project planning
> 2. Project planning của phát triển phần mềm
> 3. Chi tiết về Project Planning
> 　・　Danh sách chức năng - bao gồm cả dự toán
> 　・　Screen wireframe
> 　・　Screen specification
> 　・　　Development process
> 4. Resource Cost Estimation
> 3. Issue Management List
