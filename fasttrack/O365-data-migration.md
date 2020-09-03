---
title: Di chuyển dữ liệu
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: FastTrack chuyên gia cung cấp hướng dẫn về các bước di chuyển dữ liệu sang Office 365. Điều này sẵn dùng cho tất cả khách hàng đủ điều kiện với các dịch vụ Office 365 dành cho Exchange Online, OneDrive for Business và SharePoint Online.
ms.openlocfilehash: c7878e96557650a6dd340a08fb6348e2d60ab302
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338600"
---
# <a name="data-migration"></a>Di chuyển dữ liệu
> [!CAUTION]
> Nội dung này không còn hiện tại và được lên lịch để loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Bạn có thể có dữ liệu trong môi trường nguồn mà bạn muốn di chuyển sang Office 365.

**Đối với đối tượng thuê Office 365 với 150-499 giấy phép:** Chúng tôi cung cấp hướng dẫn bằng cách sử dụng tổ hợp các công cụ và tài liệu để di chuyển của bạn diễn ra suôn sẻ và hiệu quả. 

**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép \* :** dịch vụ di chuyển dữ liệu sẵn dùng cho Exchange Online, SharePoint Online và onedrive for Business. Lợi ích FastTrack của bạn bao gồm việc cung cấp hướng dẫn với tích hợp môi trường nguồn và di chuyển dữ liệu cho bạn.
  
\*Nếu bạn đã mua hoặc gia hạn một gói thương mại trước 9/1/2017, 150 ghế là yêu cầu chỗ ngồi tối thiểu trong suốt thời gian đăng ký hiện tại của bạn để nhận được lợi ích di chuyển. Đối với các gói giáo dục, chỉ các giấy phép giảng viên và nhân viên đủ điều kiện để di chuyển các dịch vụ. 
  
> [!NOTE]
> Dữ liệu được di chuyển qua các dịch vụ FastTrack có thể được chuyển đến, được lưu trữ và xử lý bất kỳ đâu mà Microsoft duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho sự cam kết FastTrack cụ thể của bạn). Các dịch vụ FastTrack không được thiết kế hoặc dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt. 
  
> [!NOTE]
> Các vấn đề về không lường trước (bao gồm nhưng không giới hạn ở các mục không thể đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho một số mục được di chuyển. 
  
> [!NOTE]
> Hỗ trợ di chuyển sẵn dùng trong tiếng Trung cổ truyền thống và tiếng Trung giản thể (các tài nguyên nói tiếng Mandarin), tiếng Anh, tiếng Pháp, tiếng Đức, tiếng ý, tiếng Nhật, tiếng Bồ Đào Nha (Brazil) và tiếng Tây Ban Nha. 
  
> [!NOTE]
> Nếu yêu cầu tích hợp, môi trường nguồn của bạn phải ở mức tối thiểu cho ứng dụng đó. 

Bảng sau đây mô tả những điều mong muốn cho việc di chuyển trong môi trường nguồn hiện có của bạn.
  

|**Hoạt động**|**Kỳ vọng môi trường nguồn**|
|:-----|:-----|
|**Di chuyển Exchange Online**  <br/> | Microsoft di chuyển bất kỳ sự kết hợp nào của các môi trường nguồn được liệt kê dưới đây, mỗi lần một. Chúng tôi có thể di chuyển hệ thống nhắn tin onup bằng cách dùng Trung tâm FastTrack hoặc nếu nó được thông qua kiểm tra Trung tâm FastTrack. Điều này bao gồm:  <br/>  Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange, nếu một kết hợp dựa trên Exchange 2010 được thực hiện trong mỗi tổ chức và hệ thống thư Exchange là 2003 trở đi.  <br/>  Một môi trường email có khả năng IMAP đơn.  <br/>  Môi trường G Suite (Gmail, danh bạ và lịch chỉ). <br/> <br/> **Lưu ý** *Exchange Online triển khai phải được hoàn thành trước khi di chuyển.* <br/> <br/> **Ghi chú** *fasttrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.* <br/> <br/> **Lưu ý** *đối với phụ thuộc Exchange tại cơ sở, hãy xem điều [kiện tiên quyết về triển khai](https://go.microsoft.com/fwlink/?LinkId=787528)* kết hợp. <br/><br/> **Lưu ý** *khi di chuyển nhiều môi trường nhắn tin nguồn (như nhiều tổ chức Exchange hoặc nhiều tên miền Domino), những di chuyển này sẽ xảy ra theo tuần tự.*| 
|**Di chuyển SharePoint Online**  <br/> | Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi). <br/> Môi trường Single G Suite (chỉ dành cho Google Drive).<br/>  Box (Starter, Business, doanh nghiệp).  <br/> Dropbox cho các nhóm (tiêu chuẩn và nâng cao).<br/> |
|**Di chuyển OneDrive for Business**  <br/> | Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).  <br/>  Môi trường Single G Suite (chỉ dành cho Google Drive).  <br/>  Box (Starter, Business, doanh nghiệp). <br/> Dropbox cho các nhóm (tiêu chuẩn và nâng cao).<br/><br/> **Ghi chú** *fasttrack chỉ di chuyển đến ổ đĩa Office 365 hiện hoạt.*|
   
## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online
''
### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển email của mình, chúng tôi cung cấp hướng dẫn để cho phép cả Exchange Online và môi trường nguồn cho việc di chuyển. Tùy thuộc vào môi trường nguồn, chúng tôi có thể thực hiện nhiều bước cho phép. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng tổ hợp các công cụ và tài liệu và thực hiện các tác vụ cấu hình khi có thể áp dụng và khả thi. Tùy thuộc vào tham số áp dụng, chúng tôi sau đó di chuyển các hộp thư, theo dõi công việc và cung cấp báo cáo trạng thái.
' ' Microsoft có thể yêu cầu truy nhập và quyền thích hợp cho hệ thống thư của bạn để thực hiện các hoạt động di chuyển.
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Khe thời gian di chuyển còn được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Quá trình di chuyển được thực hiện trên một prescheduled tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên tiêu chuẩn hóa prescheduled 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai: 00AM phối hợp thời gian tổng hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển đã lên lịch cuối cùng là thứ 8:00 UTC.
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau một lô di chuyển bao gồm:
- Dữ liệu từ các hộp thư đã lên lịch và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển đến Office 365. 
- Báo cáo sau khi di chuyển của lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả các di chuyển hoàn tất bao gồm:
- Dữ liệu từ các hộp thư nguồn đủ điều kiện được di chuyển đến Office 365 như được xác định trong bảng sau đây.
- Loại dữ liệu cần được di chuyển tùy thuộc vào môi trường nguồn như được mô tả trong bảng sau đây.
    
> [!NOTE]
> Tất cả các môi trường nguồn cần phải nằm trên mức bản Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn ở cuối giai đoạn bật. Dịch vụ di chuyển dữ liệu có thể tùy thuộc vào các yếu tố bên ngoài, như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API), điều này có thể dẫn đến những thay đổi, trì hoãn hoặc tạm dừng các dịch vụ này. Trong suốt thời gian của dịch vụ FastTrack, dữ liệu mà bạn sẵn dùng cho Microsoft có thể truy nhập và lưu trữ bất cứ nơi nào mà Microsoft và các nhà cung cấp của nó giữ nguyên cơ sở. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Kiểu di chuyển**|**Điều gì sẽ di chuyển từ hộp thư nguồn**|**Điều gì sẽ không di chuyển**|
|**Exchange 2003 trở đi**|Di| Điện <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Ba <br/> Môùi <br/> Các email được quản lý bằng quyền <br/> Email đã mã hóa| Thư mục công cộng <br/> Liên hệ cá nhân <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Ký <br/> Dumpster hộp thư <br/>  Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Các mục bị lỗi <br/>  Hộp thư không hoạt động |
|**Exchange 2003 và Exchange 2007**|Đoạn| Điện <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Ba <br/> Môùi <br/> Các email được quản lý bằng quyền <br/> Email đã mã hóa| Thư mục công cộng <br/> Liên hệ cá nhân <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Ký <br/> Dumpster hộp thư <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Các mục bị lỗi <br/> Hộp thư không hoạt động |
|**Exchange 2010, Exchange 2013, Exchange 2016 và Exchange 2019** <br/><br/> **Lưu ý** *đối với phụ thuộc Exchange tại cơ sở, hãy xem điều [kiện tiên quyết về triển khai](https://go.microsoft.com/fwlink/?LinkId=787528)* kết hợp.           |Di chuyển với triển khai kết hợp| Điện <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Ba <br/> Môùi <br/> Ký <br/> Lưu trữ cá nhân được di chuyển với hộp thư của người dùng <br/> Các mục có thể phục hồi <br/> Các email được quản lý bằng quyền <br/> Email đã mã hóa| Thư mục công cộng <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST) <br/> Các mục bị lỗi <br/> Hộp thư không hoạt động |
|**Môi trường G Suite (Gmail, danh bạ và lịch)** <br/> <br/> **Lưu ý** *môi trường G Suite của bạn phải có Google API và SDK của người quản trị Google được kích hoạt cho chức năng mở rộng.* <br/>          |Chuyển giao hoặc theo giai đoạn| Điện <br/> Liên hệ hộp thư\*  <br/> Ba <br/> Mác <br/> \*Đã di chuyển tối đa ba địa chỉ email cho mỗi liên hệ| Tắc <br/> Đại diện <br/> Ký <br/> Môùi <br/> Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault) <br/> Các email được quản lý hoặc mã hóa quyền <br/> Các mục bị lỗi <br/> Những Hangouts của Google\*\* <br/> Google Groups <br/> Hộp thư tài nguyên <br/> Hộp thư không hoạt động <br/> Thiết đặt nghỉ phép và thiết đặt trả lời tự động <br/> Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện <br/>\*\*Các cuộc hội thoại hangout được lưu dưới dạng nhãn được di chuyển |
|**Nguồn IMAP4 (chẳng hạn như Domino, GroupWise và Zimbra)** |Di chuyển bằng công cụ IMAP4 bản địa| Điện | Tắc <br/> Đại diện <br/> Danh sách phân phối <br/> Liên hệ bên ngoài <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Liên hệ hộp thư <br/> Ba <br/> Ký <br/> Môùi <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Email đã mã hóa <br/> Các mục bị lỗi <br/> Hộp thư không hoạt động |
   
> [!NOTE]
> Nếu các danh sách phân phối (đối tượng MailEnabledGroup) và các liên hệ bên ngoài (đối tượng MailEnabledContact) đều nằm trong Active Directory tại chỗ, họ có thể được đồng bộ hóa bằng cách dùng Azure AD Connect. Tuy nhiên, họ không phải là một phần của di chuyển dữ liệu hộp thư. Để biết thêm thông tin, hãy xem ví dụ về **tích hợp danh tính** trong [lõi](O365-onboarding-and-migration.md#core). 
  
Các chuyên gia FastTrack thực hiện các thao tác sau đây trong quá trình di chuyển:
- Cung cấp mẫu tiêu chuẩn cho di chuyển hộp thư lập lịch biểu.
- Cung cấp thông tin về các quyền cần thiết cho các chuyên gia FastTrack. 
- Thu thập lịch di chuyển hộp thư định trước theo định dạng định trước.
- Cố gắng thực hiện di chuyển của một hộp thư duy nhất lên đến hai lần trong một lô di chuyển trước khi báo cáo hộp thư đó như một di chuyển không thành công.
- Đối với môi trường nguồn Exchange và nền tảng IMAP4, di chuyển nội dung hộp thư lên đến 85% giới hạn lưu trữ hộp thư người dùng (ví dụ, nếu giới hạn lưu trữ hộp thư là 50 GB, Microsoft di chuyển lên đến 85% giới hạn lưu trữ 50 GB). 
- Bật cùng tồn tại định tuyến thư SMTP giữa môi trường nhắn tin nguồn và Office 365 Exchange Online trừ khi sử dụng di chuyển chuyển giao.
- Cung cấp báo cáo sau khi di chuyển.
- Cung cấp hỗ trợ Post-di chuyển cho các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn trở nên không khả dụng trong quá trình di chuyển.
  - Các hoạt động di chuyển dẫn đến sự cố trong môi trường nguồn.
    
Bạn thực hiện các thao tác sau trong quá trình di chuyển:
- Hoàn thành Exchange Online triển khai hoặc vượt qua kiểm tra bắt buộc bằng cách dùng Trung tâm fasttrack.
- Xử lý tất cả các liên lạc với người dùng cuối.  
- Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365. Để biết thêm thông tin, hãy xem [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Xác thực kết hợp định tuyến thư SMTP giữa môi trường nhắn tin nguồn và Office 365 Exchange Online nếu có thể áp dụng.
- Cung cấp một lịch biểu trong phương pháp đã xác định và một danh sách các hộp thư cụ thể để di chuyển đối với mỗi sự kiện di chuyển.
- Thả các hộp thư từ lịch biểu đến 24 giờ trước lô di chuyển. 
- Lên lịch số lượng hộp thư trung bình trong một khoảng thời gian 24 giờ như được liệt kê trong bảng sau đây.
    
|||
|:-----|:-----|
|**Số lượng hộp thư đủ điều kiện di chuyển** <br/> |**Số lượng hộp thư tối thiểu trung bình trong một khoảng thời gian 24 giờ** <br/> |
|150-1000  <br/> |25% tổng số  <br/> |
|1001-5000  <br/> |20% tổng số  <br/> |
|5001-10000  <br/> |15% tổng số  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Các số này dựa trên thực hành tốt nhất. Tuy nhiên, số lượng hộp thư di chuyển mỗi ngày sẽ khác nhau dựa trên môi trường, sẵn sàng và các ràng buộc kinh doanh. Microsoft không thể đảm bảo tốc độ di chuyển hộp thư. 
  
- Lên lịch tối thiểu các hộp thư 35 trong lô di chuyển. 
- Sửa lỗi trước khi di chuyển (nếu có).  
- Cung cấp quyền truy nhập và quyền đối với môi trường nguồn để theo dõi các chuyên gia để thực hiện các hoạt động di chuyển. 
- Mua và/hoặc cung cấp các tài khoản quản trị được cấp phép trong Office 365 để thực hiện các hoạt động di chuyển (phù hợp). 
- Hỗ trợ các sự cố di chuyển của máy khách và chạy các hoạt động sau khi cần thiết. 
- Di chuyển dữ liệu phía máy khách nếu muốn. Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.   
- Giảm kích cỡ hộp thư bên dưới 85 phần trăm của giới hạn hộp thư đích trong Office 365 (nếu có).   
- Xử lý hành động từ báo cáo di chuyển bài đăng, bao gồm các hộp thư không di chuyển.  
- Sửa lỗi sau khi di chuyển và sắp lại hộp thư (nếu có).   
- Tham gia vào hỗ trợ sau khi di chuyển đối với các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn trở nên không khả dụng trong quá trình di chuyển.
  - Các hoạt động di chuyển dẫn đến sự cố trong môi trường nguồn.
    
Bạn cần làm theo quy trình di chuyển chuẩn và tham gia với Microsoft một cách phù hợp. Điều này bao gồm việc cung cấp quyền truy nhập và quyền đối với môi trường 365 nguồn và Office, cung cấp lịch trình di chuyển, sửa bất kỳ nguyên nhân nào cho lỗi di chuyển, v.v. Bạn cũng cần tham gia với người dùng cuối cho liên lạc, lịch trình di chuyển hộp thư và xử lý các sự cố liên quan đến việc di chuyển người dùng cuối.
  
> [!NOTE]
> Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong khi onboarding. Nếu bạn không sử dụng các tài khoản đó, bạn có thể gặp phải sự chậm trễ di chuyển. 
  
## <a name="migration-to-sharepoint-online"></a>Di chuyển sang SharePoint Online

### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của mình, chúng tôi cung cấp hướng dẫn để kích hoạt cả SharePoint Online và môi trường nguồn cho việc di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện nhiều bước cho phép. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng tổ hợp các công cụ và tài liệu và thực hiện các tác vụ cấu hình khi có thể áp dụng và khả thi.
  
Bạn cần cung cấp truy nhập phù hợp và quyền đối với Microsoft để thực hiện một số hoạt động.
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Khe thời gian di chuyển còn được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Quá trình di chuyển được thực hiện trên một prescheduled tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên tiêu chuẩn hóa prescheduled 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai: 00AM phối hợp thời gian tổng hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển đã lên lịch cuối cùng là thứ 8:00 UTC.

- Tất cả các di chuyển đều phải tuân theo hạn ngạch SharePoint Online được nêu trong các [ranh giới và giới hạn phần mềm SharePoint Online và OneDrive for Business](https://go.microsoft.com/fwlink/?LinkID=616612).   
- Số lượng tổng thể dữ liệu được di chuyển sẽ được liên kết với 75% của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau một lô di chuyển bao gồm: 
- Dữ liệu từ các nguồn được lên lịch và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển sang SharePoint Online.   
- Báo cáo sau khi di chuyển của lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả các di chuyển hoàn tất bao gồm: 
- Dữ liệu từ nguồn đủ điều kiện được di chuyển đến Office 365 như được xác định trong bảng sau đây.  
- Kiểu dữ liệu được di chuyển tùy thuộc vào môi trường nguồn như được mô tả trong bảng sau đây:
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn** <br/> |**Kiểu di chuyển** <br/> |**Điều gì sẽ di chuyển** <br/> |**Điều gì sẽ không di chuyển** <br/> |
|**Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Các quyền đối với tệp và thư mục cấp độ người dùng\*  <br/>  Cấp độ nhóm tệp và thư mục\*  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/><br/> \**Yêu cầu cấu hình đồng bộ hóa thư mục. Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows. Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)  <br/>  Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:  <br/>  Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)  <br/>  Cấu hình kiểm tra NTFS  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (như quyền cấp ở mức chia sẻ)  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Môi trường Single G Suite (chỉ dành cho Google Drive)**  <br/> |Một hoặc nhiều đèo  <br/> | <br/>  Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục cấp nhóm <br/>  Tệp dưới 15 GB  <br/> Cơ bản về tài liệu và thư mục siêu dữ liệu: <br/> Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/> Các ổ đĩa chia sẻ (các thư mục và tệp) <br/>  Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng Google Drive admin để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục, màu thư mục  <br/>  Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm  <br/>  Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Trashed các mục  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác  <br/>  Bản vẽ Google  <br/>  Nội dung được chia sẻ bên ngoài tổ chức của bạn  <br/> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển <br/>Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài  <br/> Quyền thành viên của ổ đĩa chia sẻ\* <br/> Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> <br/> \**Sử dụng Google Drive admin để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/>|
|**Box (Starter, Business, doanh nghiệp)**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục cấp độ người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/>  Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo hộp để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích <br/>  Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm  <br/>  Mô tả tệp và thư mục  <br/>  Thẻ hộp và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Trashed các mục  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Ghi chú hộp (không có chức năng khi họ di chuyển mà không cần chuyển đổi)  <br/>  Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển (các thư mục dùng chung)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> <br/>\**Sử dụng Google Drive admin để xác định tư cách thành viên ổ đĩa chia sẻ. Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên trên mục tiêu trước khi di chuyển.* |
|**Dropbox cho các nhóm (tiêu chuẩn và nâng cao)**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/> Thư mục nhóm chia sẻ và nội dung <br/>  Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/> <br/> \**Sử dụng báo cáo Dropbox để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục <br/>  Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm    <br/> Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Trashed các mục  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Không gắn kết thư mục Dropbox <br/>  Người dùng đã xóa hoặc bị ngắt kết nối <br/>  Dropbox giấy, giới thiệu và khoảng trắng  <br/> Ứng dụng và mục yêu thích Dropbox (Pins/Stars) <br/> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> <br/> \**Sử dụng báo cáo Dropbox để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> |
   
Các chuyên gia FastTrack thực hiện các thao tác sau đây trong quá trình di chuyển: 
- Tiến hành một hội thảo hướng dẫn di chuyển bao gồm quy trình và cách tiếp cận cho kịch bản di chuyển được chọn.
- Cung cấp điều kiện tiên quyết về đánh giá và công cụ di chuyển có thể áp dụng cho kịch bản.   
- Cung cấp điều kiện tiên quyết cho việc truy nhập nhóm di chuyển đến môi trường nguồn và đích cho mục đích đánh giá và di chuyển. 
- Cung cấp các công cụ đánh giá để thực hiện đánh giá của môi trường nguồn đích, hoặc cung cấp hướng dẫn về cách sử dụng các hàm nền tảng nguồn gốc để tạo báo cáo đánh giá.   
- Hỗ trợ triển khai và chạy các công cụ di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho việc di chuyển nội dung (khi áp dụng).    
- Tiến hành di chuyển kiểm tra giới hạn để xác thực cơ sở hạ tầng di chuyển và điều kiện tiên quyết cần thiết.   
- Cung cấp các site SharePoint Online trong hộp đích cung cấp như một phần của quá trình di chuyển.    
- Tiến hành một di chuyển thí điểm trước khi di chuyển tốc độ.   
- Cung cấp hướng dẫn về việc di chuyển lên lịch cho kịch bản đã chọn. 
- Tiến hành các làn sóng di chuyển tốc độ của nội dung theo lịch trình di chuyển được cung cấp bởi khách hàng và được xác nhận bởi tài nguyên FastTrack.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào các vấn đề di chuyển vận tốc và cung cấp hướng dẫn về các tùy chọn khắc phục sự cố tiềm ẩn.   
- Cung cấp báo cáo di chuyển cuối cùng cho mỗi cửa sổ di chuyển vận tốc.   
- Cung cấp hỗ trợ Post-di chuyển trong khi người dùng chấp nhận kiểm tra tối đa năm ngày trước khi hoàn thành di chuyển.
    
Bạn thực hiện các thao tác sau trong quá trình di chuyển: 
- Cung cấp tài nguyên dự án được đề xuất để đánh giá và di chuyển các hoạt động. Những hàm này bao gồm: 
  - Quản lý dự án. 
  - Kiểm tra chấp nhận người dùng (UAT).  
  - Người quản trị chịu trách nhiệm về nền tảng nội dung nguồn và đích.  
- Cung cấp điều kiện tiên quyết cơ sở hạ tầng để đánh giá và hoạt động di chuyển (nếu cần thiết).  
- Cung cấp quyền truy nhập và quyền đối với môi trường nguồn và mục tiêu đến các chuyên gia theo dõi để thực hiện các hoạt động di chuyển (nếu bắt buộc).
    > [!NOTE]
    > Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong khi onboarding. Nếu bạn không sử dụng các tài khoản đó, bạn có thể gặp phải sự chậm trễ di chuyển. 
- Cung cấp điều kiện tiên quyết và thực hiện các hoạt động cần thiết để hỗ trợ đánh giá và di chuyển.   
- Cài đặt công cụ đánh giá FastTrack-được cung cấp và hoàn tất việc đánh giá các hoạt động thu thập dữ liệu (nếu có).   
- Cài đặt phần mềm di chuyển đã cung cấp FastTrack-tại chỗ (nếu có).   
- Các hoạt động được khắc phục được liệt kê trong báo cáo khắc phục sự trợ có được cung cấp FastTrack (nếu có).  
- Cung cấp lịch trình di chuyển bằng cách sử dụng các mẫu và hướng dẫn về FastTrack.   
- Tiến hành đảm bảo chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Tiến hành việc áp dụng di chuyển sau khi được khắc phục (nếu có).
- Lập kế hoạch và thực hiện thay đổi quản lý và kết thúc liên lạc của người dùng (nếu có).   
- Quản lý và đặt cấu hình bất kỳ thay đổi nào đối với hệ thống nguồn và thiết bị cần thiết để hoàn thành các hoạt động đánh giá và di chuyển thành công.
- Cung cấp một lịch biểu trong phương pháp đã xác định và một danh sách dữ liệu người dùng cụ thể để di chuyển đối với mỗi sự kiện di chuyển ít nhất ba (3) ngày trước.
- Thả dữ liệu người dùng từ lịch biểu đến 24 giờ trước lô di chuyển. Điều này có thể tương ứng với lô di chuyển cuối cùng.
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp.
    
## <a name="migration-to-onedrive-for-business"></a>Di chuyển sang OneDrive for Business

 ### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của mình, chúng tôi cung cấp hướng dẫn để kích hoạt cả OneDrive for Business và môi trường nguồn cho việc di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện nhiều bước cho phép. Chúng tôi giúp bạn với một số hoạt động bằng cách sử dụng kết hợp các công cụ, tài liệu và hướng dẫn và bằng cách thực hiện các tác vụ cấu hình khi có thể áp dụng và khả thi.
  
Bạn có thể cần cung cấp quyền truy nhập và quyền phù hợp cho Microsoft để thực hiện một số hoạt động. Nếu bạn không cung cấp quyền truy nhập và/hoặc quyền, bạn cần thực hiện các tác vụ được xác định nhất định cho mình với hướng dẫn từ Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Khe thời gian di chuyển còn được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Quá trình di chuyển được thực hiện trên một prescheduled tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên tiêu chuẩn hóa prescheduled 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai: 00AM phối hợp thời gian tổng hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển đã lên lịch cuối cùng là thứ 8:00 UTC.
    
- Tất cả các di chuyển đều cần truy nhập phù hợp và các quyền đối với môi trường nguồn.   
- Tất cả các di chuyển đều phải chịu hạn ngạch trong OneDrive for Business được nêu trong [SharePoint Online và OneDrive for Business: ranh giới và giới hạn của phần mềm](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau một lô di chuyển bao gồm:  
- Dữ liệu từ các nguồn được lên lịch và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển đến OneDrive for Business.  
- Báo cáo sau khi di chuyển của lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả các di chuyển hoàn tất bao gồm:
- Dữ liệu từ các nguồn đủ điều kiện được di chuyển đến Office 365 như được xác định trong bảng sau đây.  
- Loại dữ liệu cần được di chuyển tùy thuộc vào môi trường nguồn như được mô tả trong bảng sau đây.
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Kiểu di chuyển**|**Điều gì sẽ di chuyển**|**Điều gì sẽ không di chuyển**|
|**Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Các quyền đối với tệp và thư mục cấp độ người dùng\*  <br/>  Cấp độ nhóm tệp và thư mục\*  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/> <br/>\**Yêu cầu cấu hình đồng bộ hóa thư mục. Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows. Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)  <br/>  Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:  <br/>  Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)  <br/>  Cấu hình kiểm tra NTFS  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi FCI  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (như quyền cấp ở mức chia sẻ)  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Môi trường Single G Suite (chỉ dành cho Google Drive)**  <br/> |Một hoặc nhiều đèo  <br/> | Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/> Các ổ đĩa chia sẻ (các thư mục và tệp) <br/> Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\* <br/> <br/>\**Sử dụng Google Drive admin để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích  <br/>  Mô tả tệp và thư mục, màu thư mục  <br/>   Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm  <br/> Siêu dữ liệu nâng cao <br/>  Thuộc tính khóa tệp <br/> Chuyển đổi URL nhúng trong nội dung  <br/> Trashed các mục <br/> Không thể truy nhập hoặc tài liệu bị lỗi <br/> Người dùng bị chặn hoặc không hoạt động <br/> Hình ảnh của Google <br/> Biểu mẫu, bản đồ và các ứng dụng được kết nối khác <br/> Bản vẽ Google <br/> Nội dung được chia sẻ bên ngoài tổ chức của bạn <br/> Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển <br/> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài<br/> Quyền thành viên của ổ đĩa chia sẻ\*<br/> Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/><br/> \**Sử dụng Google Drive admin để xác định tư cách thành viên ổ đĩa chia sẻ. Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên trên mục tiêu trước khi di chuyển.* <br/> |
|**Box (Starter, Business, doanh nghiệp)**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục cấp độ người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/>  Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo hộp để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích  <br/>  Mô tả tệp và thư mục  <br/>  Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm  <br/>  Thẻ hộp và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Trashed các mục  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Ghi chú hộp (không có chức năng khi họ di chuyển mà không cần chuyển đổi)  <br/>  Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển (các thư mục dùng chung)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Dropbox cho các nhóm (tiêu chuẩn và nâng cao)**  <br/> |Một hoặc nhiều đèo  <br/> | Liên  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Cơ bản về tài liệu và thư mục siêu dữ liệu:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Được tạo bởi  <br/>  Sửa đổi lần cuối bằng  <br/> Thư mục nhóm chia sẻ và nội dung <br/> Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/> <br/> \**Sử dụng báo cáo Dropbox để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục <br/>  Quyền tệp cấp độ người dùng  <br/>  Quyền tệp cấp nhóm    <br/> Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi URL nhúng trong nội dung  <br/>  Trashed các mục  <br/>  Không thể truy nhập hoặc tài liệu bị lỗi  <br/>  Không gắn kết thư mục Dropbox <br/>  Người dùng đã xóa hoặc bị ngắt kết nối <br/>  Dropbox giấy, giới thiệu và khoảng trắng  <br/> Ứng dụng và mục yêu thích Dropbox (Pins/Stars) <br/> Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Các tệp hoặc thư mục vượt quá [hạn chế và giới hạn của SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> <br/> \**Sử dụng báo cáo Dropbox để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> |
   
Các chuyên gia FastTrack thực hiện các thao tác sau đây trong quá trình di chuyển:  
- Tiến hành một hội thảo hướng dẫn di chuyển bao gồm quy trình và cách tiếp cận cho kịch bản di chuyển được chọn.   
- Cung cấp điều kiện tiên quyết về đánh giá và công cụ di chuyển có thể áp dụng cho kịch bản.  
- Cung cấp điều kiện tiên quyết cho việc truy nhập nhóm di chuyển đến môi trường nguồn và đích cho mục đích đánh giá và di chuyển.   
- Cung cấp các công cụ đánh giá để thực hiện đánh giá của môi trường nguồn đích, hoặc cung cấp hướng dẫn về cách sử dụng các hàm nền tảng nguồn gốc để tạo báo cáo đánh giá.    
- Hỗ trợ triển khai và chạy các công cụ di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho việc di chuyển nội dung (khi áp dụng).    
- Tiến hành di chuyển kiểm tra giới hạn để xác thực cơ sở hạ tầng di chuyển và điều kiện tiên quyết cần thiết.    
- Cung cấp các site OneDrive dành cho doanh nghiệp trong hộp mục tiêu.    
- Tiến hành một di chuyển thí điểm trước khi di chuyển tốc độ.
- Cung cấp hướng dẫn về việc di chuyển lên lịch cho kịch bản đã chọn.   
- Tiến hành các làn sóng di chuyển tốc độ của nội dung theo lịch trình di chuyển được cung cấp bởi khách hàng và được xác nhận bởi tài nguyên FastTrack.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào các vấn đề di chuyển vận tốc và cung cấp hướng dẫn về các tùy chọn khắc phục sự cố tiềm ẩn. 
- Cung cấp báo cáo di chuyển cuối cùng cho mỗi cửa sổ di chuyển vận tốc.   
- Cung cấp hỗ trợ Post-di chuyển trong khi người dùng chấp nhận kiểm tra tối đa năm ngày trước khi hoàn thành di chuyển.
   
Bạn thực hiện các thao tác sau trong quá trình di chuyển:
- Cung cấp tài nguyên dự án được đề xuất để đánh giá và di chuyển các hoạt động. Những hàm này bao gồm:
  - Quản lý dự án.
  - UAT.
  - Người quản trị chịu trách nhiệm về nền tảng nội dung nguồn và đích.
- Cung cấp điều kiện tiên quyết cơ sở hạ tầng để đánh giá và hoạt động di chuyển (nếu cần thiết).   
- Cung cấp quyền truy nhập và quyền đối với môi trường nguồn và mục tiêu đến các chuyên gia theo dõi để thực hiện các hoạt động di chuyển (nếu bắt buộc).  
    > [!NOTE]
    > Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong khi onboarding. Nếu bạn không sử dụng các tài khoản đó, bạn có thể gặp phải sự chậm trễ di chuyển. 
- Cài đặt công cụ đánh giá FastTrack-được cung cấp và hoàn tất việc đánh giá các hoạt động thu thập dữ liệu (nếu có).
- Cài đặt phần mềm di chuyển đã cung cấp FastTrack-tại chỗ (nếu có).  
- Các hoạt động được khắc phục được liệt kê trong báo cáo khắc phục sự trợ có được cung cấp FastTrack (nếu có).   
- Cung cấp lịch trình di chuyển bằng cách sử dụng các mẫu và hướng dẫn về FastTrack. 
- Cung cấp một lịch biểu trong phương pháp đã xác định và một danh sách dữ liệu người dùng cụ thể để di chuyển đối với mỗi sự kiện di chuyển.
- Thả dữ liệu người dùng từ lịch biểu đến 24 giờ trước lô di chuyển. Điều này có thể tương ứng với lô di chuyển cuối cùng.
- Tiến hành đảm bảo chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Tiến hành việc áp dụng di chuyển sau khi được khắc phục (nếu có).  
- Lập kế hoạch và thực hiện thay đổi quản lý và kết thúc liên lạc của người dùng (nếu có).  
- Quản lý và đặt cấu hình bất kỳ thay đổi nào đối với hệ thống nguồn và thiết bị cần thiết để hoàn thành các hoạt động đánh giá và di chuyển thành công.
    
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp. 


