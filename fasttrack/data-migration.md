---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển dữ liệu thư và tệp trong môi trường nguồn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại hỗ trợ mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927004"
---
# <a name="data-migration"></a>Di chuyển dữ liệu

FastTrack có thể giúp bạn di chuyển dữ liệu thư và tệp trong môi trường nguồn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).

Loại hỗ trợ mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn:

  - **Đối với đối tượng thuê Office 365 có 150-499** giấy phép: FastTrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu. Chúng tôi hướng dẫn bạn thông qua tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.
  - **Đối với đối tượng thuê Office 365 có từ 500** giấy phép trở lên: FastTrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn. Bạn tạo và lên lịch cho các sự kiện di chuyển của mình. Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.

> [!NOTE]
> Nếu bạn đã mua hoặc gia hạn gói thương mại trước ngày 01/09/2017, bạn chỉ cần 150 giấy phép để đủ điều kiện sử dụng dịch vụ di chuyển dữ liệu. Đối với các gói dành cho giáo dục, chỉ giấy phép giảng viên và nhân viên trả phí mới đủ điều kiện sử dụng các dịch vụ di chuyển dữ liệu.

### <a name="considerations"></a>Những điều cần cân nhắc

  - Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365. Tham khảo [mục Sản phẩm và Khả](products-and-capabilities.md) năng để biết thêm thông tin về dự tính môi trường nguồn đối với Exchange, SharePoint và OneDrive for Business.
  - Chúng tôi yêu cầu quyền truy nhập và quyền thích hợp đối với môi trường nguồn của bạn và đối tượng thuê Office 365 để cung cấp các dịch vụ di chuyển dữ liệu.
  - Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng không dành cho dữ liệu tuân theo các yêu cầu pháp lý hoặc quy định đặc biệt. Khi chúng tôi di chuyển dữ liệu của bạn, dữ liệu đó có thể được chuyển sang, lưu trữ và xử lý ở bất kỳ nơi nào mà chúng tôi duy trì tiện ích (ngoại trừ những điều khác được cung cấp cho dự án di chuyển FastTrack của bạn).
  - Chúng tôi không thể đảm bảo tốc độ di chuyển thư hoặc tệp.
  - Các sự cố bất ngờ (như các mục không đọc được hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho chúng tôi di chuyển một số mục dữ liệu của bạn.
  - Các yếu tố bên ngoài nằm ngoài khả năng kiểm soát của chúng tôi (chẳng hạn như những thay đổi đối với giao diện lập trình ứng dụng (API) của bên thứ ba có thể dẫn đến thay đổi, trì hoãn hoặc tạm dừng các dịch vụ di chuyển dữ liệu của chúng tôi.

### <a name="migration-service-availability"></a>Tính khả dụng của dịch vụ di chuyển

  - **Dành cho khách hàng thương mại và Chính phủ Vương quốc Anh:** Chúng tôi cung cấp các dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).
  - **Đối với khách hàng chính phủ/DOD Hoa Kỳ:** Chúng tôi cung cấp các dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc mỗi tuần (24x5).

## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online

Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và Exchange Online cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn. Bạn tạo và lên lịch cho các sự kiện di chuyển của mình. Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng. Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi thư từ hộp thư nguồn được lên lịch và đủ điều kiện thích hợp của môi trường nguồn của bạn đã được di chuyển đến Exchange Online.

### <a name="considerations"></a>Những điều cần cân nhắc

  - Trước khi di chuyển, bạn phải hoàn thành triển năng cốt lõi FastTrack cho Exchange Online;
      - Nếu bạn đã tự mình thực hiện tự lập, bạn phải thông qua các kiểm tra và điều kiện tiên quyết bắt buộc. Hãy tham khảo [Sản phẩm và Khả năng](products-and-capabilities.md) để biết chi tiết.
  - FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.
  - Bạn phải thỏa mãn các yêu cầu cụ thể nếu bạn có ý định di chuyển từ môi trường Exchange tại chỗ. Tham khảo [Điều kiện tiên quyết triển khai kết hợp để biết](https://go.microsoft.com/fwlink/?LinkId=787528) chi tiết.
  - Mỗi môi trường nguồn phải nằm trên mức gói dịch vụ (SP) và tổng số (RU)/cập nhật tích lũy (CU) mới nhất cho sản phẩm tương ứng trong môi trường nguồn.
  - Danh sách phân phối ( đối tượng *MailEnabledGroup)* và liên hệ bên ngoài (đối tượng *MailEnabledContact)* tồn tại trong Active Directory tại chỗ của bạn không phải là một phần trong việc di chuyển dữ liệu hộp thư. Tuy nhiên, bạn có thể đồng bộ chúng bằng Azure Active Directory (Azure AD) Connect. 

## <a name="source-environments"></a>Môi trường nguồn

Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:

  - Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).
  - Một môi trường email có khả năng IMAP đơn lẻ.
  - Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch).

Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
<th><strong>Môi trường nguồn</strong></th>
<th><strong>Kiểu di chuyển</strong></th>
<th><strong>Những di chuyển</strong></th>
<th><strong>Những gì không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong><br />
<br />
<strong>Lưu ý:</strong> Đối với các phụ thuộc Exchange tại chỗ, hãy xem Điều kiện tiên quyết <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">triển khai kết hợp.</span></a></td>
<td>Di chuyển với triển khai kết hợp</td>
<td><ul>
<li>Email</li>
<li>Quy tắc hộp thư phía máy chủ</li>
<li>Đại diện</li>
<li>Liên hệ hộp thư </li>
<li> Lịch </li>
<li> Tác vụ </li>
<li> Email được quản lý bằng quyền </li>
<li> Email được mã hóa </li>
<li> Chữ ký </li>
<li> Đã di chuyển lưu trữ cá nhân cùng với hộp thư của người dùng </li>
<li> Các mục có thể khôi phục </li>
</ul></td>
<td><ul>
<li> Thư mục công cộng </li>
<li> Bất kỳ email nào vượt quá giới hạn kích cỡ thư </li>
<li> Lưu trữ ghi nhật ký hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Lưu trữ dữ liệu từ tệp Bảng Lưu trữ Cá nhân (PST) </li>
<li> Mục bị hỏng </li>
<li> Hộp thư không hiện hoạt </li>
<li> Quy tắc hộp thư phía máy khách</li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch)</strong><br />
<br />
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong Thực <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">hiện di chuyển G Suite.</a></td>
<td>Chuyển giao hoặc theo giai đoạn</td>
<td><ul>
<li> Email </li>
<li> Liên hệ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển) </li>
<li> Lịch </li>
<li> Nhãn </li>
</ul></td>
<td><ul>
<li> Quy tắc </li>
<li> Đại diện </li>
<li> Chữ ký </li>
<li> Tác vụ </li>
<li> Bất kỳ email hoặc tệp đính kèm nào vượt quá giới hạn kích cỡ thư </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Lưu trữ dữ liệu từ tệp PST hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào (ví dụ, Google Vault) </li>
<li> Email được quản lý hoặc mã hóa bằng quyền </li>
<li> Mục bị hỏng </li>
<li> Google Hangouts** </li>
<li> Nhóm Google </li>
<li> Hộp thư tài nguyên </li>
<li> Hộp thư không hiện hoạt </li>
<li> Thiết đặt kỳ nghỉ và thiết đặt trả lời tự động </li>
<li> Lịch dùng chung, tệp đính kèm đám mây, liên kết Google Hangout và màu sự kiện </li>
</ul>
**Cuộc hội thoại hangout được lưu dưới dạng nhãn sẽ được di chuyển. </td>
</tr>
<tr class="odd">
<td><strong>Nguồn IMAP4 (như Domino, GroupWise hoặc Zimbra)</strong></td>
<td>Di chuyển bằng công cụ IMAP4 gốc</td>
<td><li>Email </li></td>
<td><ul>
<li> Quy tắc </li>
<li> Đại diện </li>
<li> Danh sách phân phối </li>
<li> Liên hệ bên ngoài </li>
<li> Người dùng hỗ trợ thư </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Liên hệ hộp thư </li>
<li> Lịch </li>
<li> Chữ ký </li>
<li> Tác vụ </li>
<li> Bất kỳ email nào vượt quá giới hạn kích cỡ thư </li>
<li> Lưu trữ dữ liệu </li>
<li> Email đã mã hóa </li>
<li> Mục bị hỏng </li>
<li> Hộp thư không hiện hoạt </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.

Các Chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, dành riêng cho việc di chuyển Exchange:

  -  Cung cấp hướng dẫn để giúp bạn bật đồng tồn tại định tuyến thư SMTP giữa các môi trường nguồn của bạn và Exchange Online, nếu có.

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.

Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển Exchange:

  - Triển thị cốt lõi FastTrack cho Exchange Online. Nếu bạn đã tự mình thực hiện tự lập, bạn phải thông qua các kiểm tra và điều kiện tiên quyết bắt buộc. Hãy tham khảo [Sản phẩm và Khả năng](products-and-capabilities.md) để biết chi tiết.
  -  Cài đặt mức độ thích hợp của phần mềm máy khách theo hướng dẫn của Office 365. Tham khảo Nơi [làm việc Hiện đại để](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) biết chi tiết.
  -  Thỏa mãn các yêu cầu cụ thể nếu bạn có ý định di chuyển từ môi trường Exchange tại chỗ. Tham khảo [Điều kiện tiên quyết triển khai kết hợp để biết](https://go.microsoft.com/fwlink/?LinkId=787528) chi tiết.
  -  Đảm bảo mỗi môi trường nguồn nằm trên mức gói dịch vụ (SP) và tổng số (RU)/cập nhật tích lũy (CU) mới nhất, nếu có.
  -  Cấu hình và xác thực đồng tồn tại định tuyến thư SMTP giữa môi trường nguồn của bạn và Exchange Online, nếu có.
  -  Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn mức hộp thư đích. Tùy theo nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn ở 85 phần trăm hạn mức hộp thư đích.
  -  Di chuyển dữ liệu phía máy khách nếu muốn. Điều này bao gồm, nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong tệp PST cục bộ, quy tắc Outlook và thiết đặt Outlook cục bộ.
  -  Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.

## <a name="migration-to-sharepoint-online"></a>Di chuyển sang SharePoint Online

Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và SharePoint Online cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn. Bạn tạo và lên lịch cho các sự kiện di chuyển của mình. Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng. Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.

## <a name="considerations"></a>Những điều cần cân nhắc

 - Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online. Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855">hạn của SharePoint để</a> biết chi tiết. 
  - Chúng tôi khuyên bạn nên giới hạn tổng số tiền di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).

## <a name="source-environment-details"></a>Chi tiết môi trường nguồn

Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:

  - Chia sẻ tệp (chia sẻ tệp Chặn Thông báo Máy chủ (SMB) trên thiết bị hỗ trợ trở đi SMB 2.0).
  - Môi trường G Suite đơn (chỉ Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox for Teams (Tiêu chuẩn và Nâng cao).

Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
<th><strong>Môi trường nguồn</strong></th>
<th><strong>Kiểu di chuyển</strong></th>
<th><strong>Những di chuyển</strong></th>
 <th><strong>Những gì không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền đối với tệp và thư mục mức người dùng* </li>
<li> Quyền tệp mức nhóm và thư mục* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
</ul>
*Bắt buộc phải có cấu hình đồng bộ hóa thư mục. Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển. Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.</td>
<td><ul>
<li> Lịch sử quyền sở hữu và các phiên bản trước đó </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các phiên bản trước </li>
<li> Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn) </li>
<li> Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt: </li>
<li> Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ) </li>
<li> Cấu hình kiểm tra NTFS </li>
<li> Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI) </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Chia sẻ ẩn </li>
<li> Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm các tệp có dung lượng trên 10 MB </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Ổ đĩa dùng chung (thư mục và tệp) </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục, màu thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Ảnh, Biểu mẫu, Bản đồ và các ứng dụng được kết nối khác của Google </li>
<li> Hình vẽ Google </li>
<li> Nội dung chia sẻ bên ngoài tổ chức của bạn </li>
<li> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung. Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.) </li>
<li> Các tệp được đánh dấu là hạn chế hoặc không thể sao chép </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển </li>
<li> Ghi chú Box (được chuyển đổi thành định dạng tài liệu Word) </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Thẻ Hộp và siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc </li>
<li> Nội dung không thuộc sở hữu của tài khoản Box được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Các thư mục nhóm dùng chung và nội dung </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Thư mục Dropbox chưa đóng tiền </li>
<li> Đã xóa hoặc người dùng bị ngắt kết nối </li>
<li> Giấy Dropbox, Giới thiệu và Khoảng trống </li>
<li> Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao) </li>
<li> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) để biết chi tiết

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) để biết chi tiết

Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển SharePoint Online:

  - Cung cấp tất cả các site nhóm SharePoint được mục tiêu bởi các sự kiện di chuyển của bạn.

## <a name="migration-to-onedrive-for-business"></a>Di chuyển sang OneDrive for Business

Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và OneDrive for Business cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn. Bạn tạo và lên lịch cho các sự kiện di chuyển của mình. Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng. Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang OneDrive for Business.

## <a name="considerations"></a>Những điều cần cân nhắc

  - Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online. Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> hạn của SharePoint để</a> biết chi tiết. 
  - Chúng tôi khuyên bạn nên giới hạn lượng dữ liệu tổng thể mà bạn di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).
  - FastTrack chỉ di chuyển sang ổ đĩa OneDrive for Business hiện hoạt.

## <a name="source-environment-details"></a>Chi tiết môi trường nguồn

Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:

  - Chia sẻ tệp (chia sẻ tệp SMB trên thiết bị hỗ trợ SMB 2.0 trở đi).
  - Môi trường G Suite Đơn (chỉ Google Drive).
  - Box (Starter, Business, Enterprise).
  - Dropbox for Teams (Tiêu chuẩn và Nâng cao).

Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
 <th><strong>Môi trường nguồn</strong></th>
 <th><strong>Kiểu di chuyển</strong></th>
 <th><strong>Những di chuyển</strong></th>
 <th><strong>Những gì không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền đối với tệp và thư mục mức người dùng* </li>
<li> Quyền tệp mức nhóm và thư mục* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
</ul>
<br>
*Bắt buộc phải có cấu hình đồng bộ hóa thư mục. Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển. Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển. </td>
<td><ul>
<li> Lịch sử quyền sở hữu và các phiên bản trước đó </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các phiên bản trước </li>
<li> Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn) </li>
<li> Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt: </li>
<li> Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ) </li>
<li> Cấu hình kiểm tra NTFS </li>
<li> Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI) </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Chia sẻ ẩn </li>
<li> Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm các tệp trên 10 MB) </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Ổ đĩa dùng chung (thư mục và tệp) </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục, màu thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Biểu mẫu Ảnh, Bản đồ và các ứng dụng được kết nối khác của Google </li>
<li> Hình vẽ Google </li>
<li> Nội dung chia sẻ bên ngoài tổ chức của bạn </li>
<li> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung. Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Thẻ Hộp và siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc </li>
<li> Nội dung không thuộc sở hữu của tài khoản Box được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng </li>
<li> Quyền thư mục mức nhóm </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Các thư mục nhóm dùng chung và nội dung </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển </li>
</ul></td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Thư mục Dropbox chưa đóng tiền </li>
<li> Đã xóa hoặc người dùng bị ngắt kết nối </li>
<li> Giấy Dropbox, Giới thiệu và Khoảng trống </li>
<li> Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao) </li>
<li> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.

## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.

Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển OneDrive for Business:

  - Cung cấp tất cả các site OneDrive for Business mà sẽ được hướng mục tiêu bởi các sự kiện di chuyển của bạn.

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a>Di chuyển sang Microsoft Teams và Nhóm Microsoft 365

Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang Microsoft Teams và Nhóm Microsoft 365, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu. Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển, đặt cấu hình môi trường nguồn cũng như Teams và Nhóm Microsoft 365, cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn. Bạn tạo và lên lịch cho các sự kiện di chuyển của mình. Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng. Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn có lịch biểu và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang Teams và Nhóm Microsoft 365. Các kênh Teams và Nhóm Microsoft 365 phải được khách hàng cung cấp trước trước khi có thể di chuyển dữ liệu vào các loại đích này. Teams và Nhóm Microsoft 365 ảnh hưởng đến quyền của bạn trên vị trí đích của tệp. Teams và Nhóm Microsoft 365 được xây dựng để cho phép cộng tác. Kênh Teams hoặc nhóm Microsoft 365 xác định ai có quyền truy nhập vào các tệp đó khi di chuyển vào các đích đó. FastTrack không thêm người dùng cuối hoặc nhóm vào bất kỳ kênh Teams hoặc quyền Nhóm Microsoft 365 nào trong quá trình di chuyển.

## <a name="considerations"></a>Những điều cần cân nhắc

- Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online. Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> hạn của SharePoint để</a> biết chi tiết. 
- Chúng tôi khuyên bạn nên giới hạn tổng số tiền di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng). 


## <a name="source-environment-details"></a>Chi tiết môi trường nguồn

Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này: 

- Chia sẻ tệp (chia sẻ tệp Chặn Thông báo Máy chủ (SMB) trên thiết bị hỗ trợ trở đi SMB 2.0).
-  Môi trường G Suite đơn (chỉ Google Drive). 
- Box (Starter, Business, Enterprise). 
- Dropbox for Teams (Tiêu chuẩn và Nâng cao). 

Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:

<table>
<thead>
<tr class="header">
 <th><strong>Môi trường nguồn</strong></th>
 <th><strong>Kiểu di chuyển</strong></th>
 <th><strong>Những di chuyển</strong></th>
 <th><strong>Những gì không di chuyển</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền đối với tệp và thư mục mức người dùng* </li>
<li> Quyền tệp mức nhóm và thư mục* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
</ul>
<br>
*Bắt buộc phải có cấu hình đồng bộ hóa thư mục. Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển. Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển. Quyền bị ảnh hưởng bởi Nhóm Microsoft 365 và/hoặc kênh Microsoft Teams. Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển. Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.</td>
<td><ul>
<li> Lịch sử quyền sở hữu và các phiên bản trước đó </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các phiên bản trước </li>
<li> Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn) </li>
<li> Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt: </li>
<li> Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ) </li>
<li> Cấu hình kiểm tra NTFS </li>
<li> Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI) </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Chia sẻ ẩn </li>
<li> Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm các tệp trên 10 MB) </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng* </li>
<li> Quyền thư mục mức nhóm* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Ổ đĩa dùng chung (thư mục và tệp) </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
</ul>
<br>
*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams. Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển. Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams. 
</td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục, màu thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Biểu mẫu Ảnh, Bản đồ và các ứng dụng được kết nối khác của Google </li>
<li> Hình vẽ Google </li>
<li> Nội dung chia sẻ bên ngoài tổ chức của bạn </li>
<li> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung. Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Box (Starter, Business, Enterprise)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng* </li>
<li> Quyền thư mục mức nhóm* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển </li>
<li> Ghi chú Box (được chuyển đổi thành định dạng tài liệu Word) </li>
</ul>
<br>
*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams. Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển. Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams. </td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Thẻ Hộp và siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Người dùng bị chặn hoặc không hoạt động </li>
<li> Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc </li>
<li> Nội dung không thuộc sở hữu của tài khoản Box được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></td>
<td>Truyền một lần hoặc nhiều lần</td>
<td><ul>
<li> Tài liệu </li>
<li> Cấu trúc tệp và thư mục </li>
<li> Quyền thư mục mức người dùng* </li>
<li> Quyền thư mục mức nhóm* </li>
<li> Các tệp dưới 15 GB </li>
<li> Siêu dữ liệu tài liệu cơ bản và thư mục:
<ul>
<li> Ngày tạo </li>
<li> Ngày sửa đổi </li>
<li> Người tạo </li>
<li> Sửa đổi lần cuối bởi </li>
</ul></li>
<li> Các thư mục nhóm dùng chung và nội dung </li>
<li> Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển </li>
</ul>
<br>
*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams. Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển. Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.
</td>
<td><ul>
<li> Lịch sử quyền sở hữu, các phiên bản trước và chú thích </li>
<li> Mô tả tệp và thư mục </li>
<li> Quyền tệp mức người dùng </li>
<li> Quyền tệp mức nhóm </li>
<li> Siêu dữ liệu nâng cao </li>
<li> Thuộc tính khóa tệp </li>
<li> Chuyển đổi các URL nhúng trong nội dung </li>
<li> Các mục đã đổ rác </li>
<li> Tài liệu không thể tiếp cận hoặc bị hỏng </li>
<li> Thư mục Dropbox chưa đóng tiền </li>
<li> Đã xóa hoặc người dùng bị ngắt kết nối </li>
<li> Giấy Dropbox, Giới thiệu và Khoảng trống </li>
<li> Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao) </li>
<li> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển </li>
<li> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.) </li>
<li> Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.

## <a name="your-responsibilities"></a>Trách nhiệm của bạn 

Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển. Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.
Bạn cũng có thể thực hiện các hoạt động sau, dành riêng cho di chuyển Nhóm Microsoft Teams và Microsoft 365: 

- Cung cấp tất cả các kênh Microsoft Teams và Nhóm Microsoft 365 làm mục tiêu theo các sự kiện di chuyển của bạn.

> [!NOTE]
>FastTrack không cung cấp trước các kênh Microsoft Teams hoặc Nhóm Microsoft 365. FastTrack không thêm người dùng cuối hoặc nhóm vào các kênh Microsoft Teams hoặc Nhóm Microsoft 365. Bạn phải thêm người dùng cuối hoặc nhóm vào tất cả các kênh Microsoft Teams và Nhóm Microsoft 365 trước khi bạn di chuyển dữ liệu vào các đích đó để những người dùng cuối đó có quyền truy nhập vào những tài liệu mới được di chuyển