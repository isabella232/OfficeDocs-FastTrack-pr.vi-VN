---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 12/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: 5a64bcbecffa3fd78f54b9a5e0f3f07e76d0b316
ms.sourcegitcommit: d69d3e1e478a817f8279e9da98880499e9302665
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 12/01/2020
ms.locfileid: "49525371"
---
# <a name="data-migration"></a>Di chuyển dữ liệu

FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).

Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:

  - **Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu. Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.
  - **Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn. Bạn tạo và lên lịch các sự kiện di chuyển của bạn. Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.

> [!NOTE]
> Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu. Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.

### <a name="considerations"></a>Nhắc

  - Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365. Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.
  - Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.
  - Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt. Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).
  - Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.
  - Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.
  - Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.

### <a name="migration-service-availability"></a>Tính khả dụng của dịch vụ di chuyển

  - **Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).
  - **Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).

## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online

Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn. Bạn tạo và lên lịch các sự kiện di chuyển của bạn. Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái. Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.

### <a name="considerations"></a>Nhắc

  - Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;
      - Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết. Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.
  - FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.
  - Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở. Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.
  - Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.
  - Danh sách phân phối (đối tượng *Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng *Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư. Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD). 

## <a name="source-environments"></a>Môi trường nguồn

Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:

  - Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).
  - Một môi trường email có khả năng IMAP đơn.
  - Môi trường G Suite (Gmail, danh bạ và lịch chỉ).

Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
<th><strong>Môi trường nguồn</strong></th>
<th><strong>Kiểu di chuyển</strong></th>
<th><strong>Những thao động nào</strong></th>
<th><strong>Những điều không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Lưu ý:</strong> Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</td>
<td>Di chuyển với triển khai kết hợp</td>
<td><ul>
<li>Điện</li>
<li>Quy tắc hộp thư</li>
<li>Đại diện</li>
<li>Liên hệ hộp thư </li>
<li> Ba </li>
<li> Môùi </li>
<li> Các email được quản lý bằng quyền </li>
<li> Email đã mã hóa </li>
<li> Ký </li>
<li> Lưu trữ cá nhân được di chuyển với hộp thư của người dùng </li>
<li> Các mục có thể phục hồi </li>
</ul></td>
<td><ul>
<li> Thư mục công cộng </li>
<li> Bất kỳ email nào vượt quá giới hạn kích cỡ thư </li>
<li> Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST) </li>
<li> Các mục bị lỗi </li>
<li> Hộp thư không hoạt động </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong><br />
<br />
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</td>
<td>Chuyển giao hoặc theo giai đoạn</td>
<td><ul>
<li> Điện </li>
<li> Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển) </li>
<li> Ba </li>
<li> Mác </li>
</ul></td>
<td><ul>
<li> Tắc </li>
<li> Đại diện </li>
<li> Ký </li>
<li> Môùi </li>
<li> Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault) </li>
<li> Các email được quản lý hoặc mã hóa quyền </li>
<li> Các mục bị lỗi </li>
<li> Google Hangouts * * </li>
<li> Google Groups </li>
<li> Hộp thư tài nguyên </li>
<li> Hộp thư không hoạt động </li>
<li> Thiết đặt nghỉ phép và thiết đặt trả lời tự động </li>
<li> Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện </li>
</ul>
* * Hangout hội thoại được lưu dưới dạng nhãn được di chuyển. </td>
</tr>
<tr class="odd">
<td><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></td>
<td>Di chuyển bằng công cụ IMAP4 bản địa</td>
<td><li>Điện </li></td>
<td><ul>
<li> Tắc </li>
<li> Đại diện </li>
<li> Danh sách phân phối </li>
<li> Liên hệ bên ngoài </li>
<li> Người dùng hỗ trợ thư </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Liên hệ hộp thư </li>
<li> Ba </li>
<li> Ký </li>
<li> Môùi </li>
<li> Bất kỳ email nào vượt quá giới hạn kích cỡ thư </li>
<li> Lưu trữ dữ liệu </li>
<li> Email đã mã hóa </li>
<li> Các mục bị lỗi </li>
<li> Hộp thư không hoạt động </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Các trách nhiệm FastTrack

Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.

Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:

  -  Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.

Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:

  - Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online. Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết. Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.
  -  Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365. Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.
  -  Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở. Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.
  -  Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.
  -  Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.
  -  Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích. Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.
  -  Di chuyển dữ liệu phía máy khách nếu muốn. Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.
  -  Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.

## <a name="migration-to-sharepoint-online"></a>Di chuyển sang SharePoint Online

Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn. Bạn tạo và lên lịch các sự kiện di chuyển của bạn. Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái. Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.

## <a name="considerations"></a>Nhắc

  - Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online. Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.
  - Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).

## <a name="source-environment-details"></a>Chi tiết môi trường nguồn

Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:

  - Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).
  - Một môi trường G Suite đơn (chỉ dành cho Google).
  - Box (Starter, Business, doanh nghiệp).
  - Dropbox cho các nhóm (tiêu chuẩn và nâng cao).

Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
<th><strong>Môi trường nguồn</strong></th>
<th><strong>Kiểu di chuyển</strong></th>
<th><strong>Những thao động nào</strong></th>
 <th><strong>Những điều không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Tệp cấp độ người dùng và quyền thư mục * </li>
<li> Các quyền thư mục và tệp cấp nhóm * </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
</ul>
* Yêu cầu cấu hình đồng bộ hóa thư mục. Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows. Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</td>
<td><ul>
<li> Lịch sử quyền sở hữu và các phiên bản trước </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Các phiên bản trước </li>
<li> Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn) </li>
<li> Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt: </li>
<li> Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ) </li>
<li> Cấu hình kiểm tra NTFS </li>
<li> Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI) </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Chia sẻ ẩn </li>
<li> Chia sẻ (như quyền cấp ở mức chia sẻ) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Các ổ đĩa chia sẻ (các thư mục và tệp) </li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục, màu thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác </li>
<li> Bản vẽ Google </li>
<li> Nội dung được chia sẻ bên ngoài tổ chức của bạn </li>
<li> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ. Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.) </li>
<li> Các tệp được đánh dấu là hạn chế hoặc không được copyable </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, doanh nghiệp)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển </li>
<li> Ghi chú hộp (được chuyển đổi thành định dạng tài liệu Word) </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Thẻ hộp và siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc </li>
<li> Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Thư mục nhóm chia sẻ và nội dung </li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Không gắn kết thư mục Dropbox </li>
<li> Người dùng đã xóa hoặc bị ngắt kết nối </li>
<li> Dropbox giấy, giới thiệu và khoảng trắng </li>
<li> Ứng dụng và mục yêu thích Dropbox (Pins/Stars) </li>
<li> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Các trách nhiệm FastTrack

Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết

Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:

  - Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.

## <a name="migration-to-onedrive-for-business"></a>Di chuyển sang OneDrive for Business

Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn. Bạn tạo và lên lịch các sự kiện di chuyển của bạn. Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái. Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.

## <a name="considerations"></a>Nhắc

  - Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business. Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.
  - Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).
  - FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.

## <a name="source-environment-details"></a>Chi tiết môi trường nguồn

Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:

  - Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).
  - Môi trường Single G Suite (chỉ dành cho Google Drive).
  - Box (Starter, Business, doanh nghiệp).
  - Dropbox cho các nhóm (tiêu chuẩn và nâng cao).

Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
 <th><strong>Môi trường nguồn</strong></th>
 <th><strong>Kiểu di chuyển</strong></th>
 <th><strong>Những thao động nào</strong></th>
 <th><strong>Những điều không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Tệp cấp độ người dùng và quyền thư mục * </li>
<li> Các quyền thư mục và tệp cấp nhóm * </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
</ul>
<br>
* Yêu cầu cấu hình đồng bộ hóa thư mục. Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows. Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB. </td>
<td><ul>
<li> Lịch sử quyền sở hữu và các phiên bản trước </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Các phiên bản trước </li>
<li> Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn) </li>
<li> Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt: </li>
<li> Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ) </li>
<li> Cấu hình kiểm tra NTFS </li>
<li> Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI) </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Chia sẻ ẩn </li>
<li> Chia sẻ (như quyền cấp ở mức chia sẻ) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB) </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Các ổ đĩa chia sẻ (các thư mục và tệp) </li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục, màu thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác </li>
<li> Bản vẽ Google </li>
<li> Nội dung được chia sẻ bên ngoài tổ chức của bạn </li>
<li> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ. Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, doanh nghiệp)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Thẻ hộp và siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc </li>
<li> Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></td>
<td>Một hoặc nhiều đèo</td>
<td><ul>
<li> Liên </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục cấp nhóm </li>
<li> Tệp dưới 15 GB </li>
<li> Cơ bản về tài liệu và thư mục siêu dữ liệu:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Được tạo bởi </li>
<li> Sửa đổi lần cuối bằng </li>
</ul></li>
<li> Thư mục nhóm chia sẻ và nội dung </li>
<li> Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp cấp độ người dùng </li>
<li> Quyền tệp cấp nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi URL nhúng trong nội dung </li>
<li> Trashed các mục </li>
<li> Không thể truy nhập hoặc tài liệu bị lỗi </li>
<li> Không gắn kết thư mục Dropbox </li>
<li> Người dùng đã xóa hoặc bị ngắt kết nối </li>
<li> Dropbox giấy, giới thiệu và khoảng trắng </li>
<li> Ứng dụng và mục yêu thích Dropbox (Pins/Stars) </li>
<li> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Các trách nhiệm FastTrack

Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển. Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.

Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:

  - Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.
