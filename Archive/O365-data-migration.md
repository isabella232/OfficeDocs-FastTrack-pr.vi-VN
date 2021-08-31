---
title: Di chuyển dữ liệu
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
ms.localizationpriority: ''
ms.collection: FastTrack
description: FastTrack Các chuyên gia cung cấp hướng dẫn về các bước di chuyển dữ liệu Office 365. Tính năng này sẵn dùng cho tất cả khách hàng đủ điều kiện Office 365 các dịch vụ Exchange Online, OneDrive for Business và SharePoint Online.
ms.openlocfilehash: 76a00192672f65a56f12b82fe93639a7a23562b6
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710305"
---
# <a name="data-migration"></a>Di chuyển dữ liệu
> [!CAUTION]
> Nội dung này không còn mới nhất và được lên lịch loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Bạn có thể có dữ liệu trong môi trường nguồn mà bạn muốn di chuyển sang Office 365.

**Đối Office 365 thuê có 150-499 giấy phép:** Chúng tôi cung cấp hướng dẫn bằng cách sử dụng kết hợp các công cụ và tài liệu để quá trình di chuyển của bạn diễn ra suôn sẻ và hiệu quả. 

Đối với Office 365 thuê có 500 giấy phép trở **\* lên:** Dịch vụ di chuyển dữ liệu sẵn dùng cho Exchange Online, SharePoint Online và OneDrive for Business. Quyền lợi FastTrack quan của bạn bao gồm việc cung cấp hướng dẫn với tích hợp môi trường nguồn và di chuyển dữ liệu cho bạn.
  
\*Nếu bạn đã mua hoặc gia hạn gói thương mại trước ngày 01/09/2017, 150 chỗ là yêu cầu chỗ ngồi tối thiểu trong suốt thời gian đăng ký hiện tại của bạn để nhận được lợi ích di chuyển. Đối với các gói dành cho giáo dục, chỉ giấy phép giảng viên và nhân viên trả phí mới đủ điều kiện sử dụng các dịch vụ di chuyển. 
  
> [!NOTE]
> Dữ liệu được di chuyển thông qua các dịch vụ FastTrack có thể được chuyển tới, lưu trữ và xử lý ở bất kỳ nơi nào mà Microsoft duy trì cơ sở (ngoại trừ những điều khác được cung cấp cho sự tham gia FastTrack bạn). Dịch vụ FastTrack thiết kế không được thiết kế hoặc dành cho dữ liệu tuân theo các yêu cầu pháp lý hoặc quy định đặc biệt. 
  
> [!NOTE]
> Các sự cố bất ngờ (bao gồm nhưng không giới hạn trong phạm vi không đọc được hoặc hỏng các mục trong môi trường nguồn) có thể ngăn một số mục không được di chuyển. 
  
> [!NOTE]
> Hỗ trợ di chuyển có sẵn bằng tiếng Trung Giản thể và tiếng Trung Giản thể (các tài nguyên chỉ nói tiếng Quan thoại), tiếng Anh, tiếng Pháp, tiếng Đức, tiếng Ý, tiếng Nhật, tiếng Bồ Đào Nha (Brazil) và tiếng Tây Ban Nha. 
  
> [!NOTE]
> Nếu cần tích hợp, môi trường nguồn của bạn phải ở mức tối thiểu cho ứng dụng đó. 

Bảng sau đây mô tả những điều dự kiến cần có để di chuyển trong môi trường nguồn hiện có của bạn.
  

|**Hoạt động**|**Dự kiến về môi trường nguồn**|
|:-----|:-----|
|**Exchange Online chuyển**  <br/> | Microsoft sẽ di chuyển mọi kết hợp môi trường nguồn được liệt kê bên dưới, mỗi môi trường một lần. Chúng tôi có thể di chuyển hệ thống nhắn tin được triển FastTrack bằng cách sử dụng Trung tâm FastTrack hoặc nếu đạt điều khoản kiểm tra FastTrack Center. Trong đó bao gồm:  <br/>  Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange, nếu triển khai kết hợp dựa trên Exchange 2010 trong mỗi tổ chức và hệ thống thư Exchange được triển khai 2003.  <br/>  Một môi trường email có khả năng IMAP duy nhất.  <br/>  Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch). <br/> <br/> **Lưu** *ý Exchange Online nhập trước khi di chuyển.* <br/> <br/> **Lưu** *ý FastTrack di chuyển sang hộp thư Office 365 động.* <br/> <br/> **Lưu** ý Đối với các phụ thuộc Exchange tại chỗ, hãy xem Điều kiện *tiên quyết triển khai kết [hợp.](https://go.microsoft.com/fwlink/?LinkId=787528)* <br/><br/> **Lưu** ý Khi di chuyển nhiều môi trường nhắn tin nguồn (như nhiều tổ chức Exchange hoặc nhiều tên miền *Domino),* những quá trình di chuyển này diễn ra tuần tự.| 
|**SharePoint Di chuyển trực tuyến**  <br/> | Chia sẻ tệp (chia sẻ tệp Chặn Thông báo Máy chủ (SMB) trên thiết bị hỗ trợ trở đi SMB 2.0). <br/> Môi trường G Suite Đơn (Google Drive riêng biệt).<br/>  Box (Starter, Business, Enterprise).  <br/> Dropbox dùng cho Teams (Tiêu chuẩn và Nâng cao).<br/> |
|**OneDrive for Business chuyển**  <br/> | Chia sẻ tệp (chia sẻ tệp SMB trên các thiết bị hỗ trợ SMB 2.0 trở đi).  <br/>  Môi trường G Suite Đơn (Google Drive riêng biệt).  <br/>  Box (Starter, Business, Enterprise). <br/> Dropbox dùng cho Teams (Tiêu chuẩn và Nâng cao).<br/><br/> **Lưu** *ý FastTrack di chuyển sang ổ đĩa Office 365 động.*|
   
## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online
''
### <a name="enable-to-migrate"></a>Cho phép di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển email của mình, chúng tôi sẽ cung cấp hướng dẫn để bật cả Exchange Online và môi trường nguồn để di chuyển. Tùy thuộc vào môi trường nguồn, chúng tôi có thể thực hiện các bước Bật khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng kết hợp các công cụ và tài liệu, đồng thời thực hiện các tác vụ cấu hình nếu có thể và khả thi. Theo các tham số có thể áp dụng, chúng tôi sẽ di chuyển các hộp thư, theo dõi công việc và cung cấp báo cáo tình trạng.
'' Microsoft có thể yêu cầu quyền truy nhập và quyền thích hợp đối với hệ thống thư của bạn để thực hiện các hoạt động di chuyển.
  
### <a name="migration-policy-and-steps"></a>Các bước và chính sách di chuyển
  
> [!NOTE]
> Khoảng thời gian di chuyển còn được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ Vương quốc Anh và Thương mại

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, bảy (7) ngày làm việc mỗi tuần (24x7) trong khoảng thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, năm (5) ngày làm việc một tuần (24x5) trên cơ sở thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ Thứ Hai 2:00AM Giờ Quốc tế Phối hợp (UTC) đến Thứ Sáu nửa đêm UTC. Điều này có nghĩa là di chuyển được lên lịch lần cuối là Thứ Sáu 8:00 CH UTC.
    
 ### <a name="end-state"></a>Trạng thái Kết thúc
  
Trạng thái kết thúc dự kiến sau khi một lô di chuyển bao gồm:
- Dữ liệu từ các hộp thư nguồn đủ điều kiện và được lên lịch phù hợp trong môi trường nguồn được di chuyển sang Office 365. 
- Báo cáo sau khi di chuyển cho lô di chuyển do Microsoft cung cấp.
    
Trạng thái kết thúc dự kiến sau khi hoàn thành tất cả di chuyển bao gồm:
- Dữ liệu từ hộp thư nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.
- Kiểu dữ liệu cần di chuyển phụ thuộc vào môi trường nguồn như mô tả trong bảng sau đây.
    
> [!NOTE]
> Tất cả các môi trường nguồn cần phải nằm trên mức gói dịch vụ (SP) và tổng số (RU)/cập nhật tích lũy (CU) cho sản phẩm tương ứng trong môi trường nguồn ở cuối giai đoạn Bật. Dịch vụ di chuyển dữ liệu phụ thuộc vào các yếu tố bên ngoài ngoài quyền kiểm soát của Microsoft, chẳng hạn như những thay đổi đối với giao diện lập trình ứng dụng (API) của bên thứ ba, điều này có thể dẫn đến thay đổi, trì hoãn hoặc tạm dừng các dịch vụ này. Trong khoảng thời gian của các dịch vụ FastTrack, bạn có thể truy nhập và lưu trữ dữ liệu khả dụng với Microsoft ở bất kỳ đâu mà Microsoft và các nhà cung cấp duy trì cơ sở. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Kiểu di chuyển**|**Những nội dung sẽ di chuyển từ hộp thư nguồn**|**Những gì sẽ không di chuyển**|
|**Exchange 2003 trở đi**|Chuyển giao| Email <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Lịch <br/> Tác vụ <br/> Email được quản lý bằng quyền <br/> Email được mã hóa| Thư mục công cộng <br/> Liên hệ cá nhân <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Ảnh kết xuất hộp thư <br/>  Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Mục bị hỏng <br/>  Hộp thư không hiện hoạt |
|**Exchange 2003 và Exchange 2007**|Theo giai đoạn| Email <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Lịch <br/> Tác vụ <br/> Email được quản lý bằng quyền <br/> Email được mã hóa| Thư mục công cộng <br/> Liên hệ cá nhân <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Ảnh kết xuất hộp thư <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Mục bị hỏng <br/> Hộp thư không hiện hoạt |
|**Exchange 2010, Exchange 2013, Exchange 2016 và Exchange 2019** <br/><br/> **Lưu** ý Đối với các phụ thuộc Exchange cơ sở, hãy xem Điều kiện tiên quyết *[triển khai kết hợp.](https://go.microsoft.com/fwlink/?LinkId=787528)*           |Di chuyển với triển khai kết hợp| Email <br/> Quy tắc hộp thư <br/> Đại diện <br/> Liên hệ hộp thư <br/> Lịch <br/> Tác vụ <br/> Chữ ký <br/> Đã di chuyển lưu trữ cá nhân cùng với hộp thư của người dùng <br/> Các mục có thể khôi phục <br/> Email được quản lý bằng quyền <br/> Email được mã hóa| Thư mục công cộng <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ ghi nhật ký hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ tệp Bảng Lưu trữ Cá nhân (PST) <br/> Mục bị hỏng <br/> Hộp thư không hiện hoạt |
|**Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch)** <br/> <br/> **Lưu** *ý Môi trường G Suite của bạn phải có Google API và SDK Quản* trị Google được bật để mở rộng chức năng. <br/>          |Chuyển giao hoặc theo giai đoạn| Email <br/> Liên hệ hộp thư\*  <br/> Lịch <br/> Nhãn <br/> \*Đã di chuyển tối đa ba địa chỉ email cho mỗi liên hệ| Quy tắc <br/> Đại diện <br/> Chữ ký <br/> Tác vụ <br/> Bất kỳ email hoặc tệp đính kèm nào vượt quá giới hạn kích cỡ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ tệp PST hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào (ví dụ, Google Vault) <br/> Email được quản lý hoặc mã hóa bằng quyền <br/> Mục bị hỏng <br/> Google Hangouts\*\* <br/> Nhóm Google <br/> Hộp thư tài nguyên <br/> Hộp thư không hiện hoạt <br/> Thiết đặt kỳ nghỉ và thiết đặt trả lời tự động <br/> Lịch dùng chung, tệp đính kèm đám mây, liên kết Google Hangout và màu sự kiện <br/>\*\*Cuộc hội thoại trên hangout được lưu dưới dạng nhãn sẽ được di chuyển |
|**Nguồn IMAP4 (như Domino, GroupWise và Zimbra)** |Di chuyển bằng công cụ IMAP4 gốc| Email | Quy tắc <br/> Đại diện <br/> Danh sách phân phối <br/> Liên hệ bên ngoài <br/> Người dùng hỗ trợ thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Liên hệ hộp thư <br/> Lịch <br/> Chữ ký <br/> Tác vụ <br/> Bất kỳ email nào vượt quá giới hạn kích cỡ thư <br/> Lưu trữ dữ liệu <br/> Email đã mã hóa <br/> Mục bị hỏng <br/> Hộp thư không hiện hoạt |
   
> [!NOTE]
> Nếu danh sách phân phối (đối tượng MailEnabledGroup) và liên hệ bên ngoài (đối tượng MailEnabledContact) nằm trong Active Directory tại chỗ thì chúng có thể được đồng bộ bằng Azure AD Kết nối. Tuy nhiên, chúng không phải là một phần của việc di chuyển dữ liệu hộp thư. Để biết thêm thông tin, hãy xem ví **dụ tích hợp** Danh tính trong [Core](O365-onboarding-and-migration.md#core). 
  
FastTrack Các chuyên gia thực hiện những việc sau trong quá trình di chuyển:
- Cung cấp mẫu tiêu chuẩn để lên lịch di chuyển hộp thư.
- Cung cấp thông tin về quyền bắt buộc cho Các FastTrack viên. 
- Thu thập lịch biểu di chuyển hộp thư định sẵn theo định dạng được xác định trước.
- Thử thực hiện di chuyển một hộp thư duy nhất đến hai lần trong một lô di chuyển trước khi báo cáo rằng hộp thư là di chuyển không thành công.
- Đối với môi trường nguồn dựa trên Exchange và IMAP4, hãy di chuyển nội dung hộp thư đến 85% giới hạn lưu trữ hộp thư người dùng (ví dụ: nếu giới hạn lưu trữ hộp thư là 50 GB, Microsoft sẽ di chuyển tới 85% giới hạn lưu trữ 50 GB). 
- Cho phép đồng tồn tại định tuyến thư SMTP giữa môi trường gửi thư nguồn và Office 365 Exchange Online trừ khi sử dụng di chuyển chuyển giao.
- Cung cấp báo cáo sau khi di chuyển.
- Cung cấp hỗ trợ sau khi di chuyển cho các sự cố quan trọng. Các sự cố sau được coi là rất quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn sẽ không sẵn dùng trong quá trình di chuyển.
  - Các hoạt động di chuyển dẫn đến sự cố trong môi trường nguồn.
    
Bạn thực hiện những thao tác sau đây trong quá trình di chuyển:
- Hoàn thành Exchange Online hoặc vượt qua kiểm tra bắt buộc bằng cách sử dụng Trung FastTrack Phát hành.
- Xử lý tất cả thông tin liên lạc với người dùng cuối.  
- Cài đặt mức độ thích hợp của phần mềm máy khách theo hướng Office 365 thích hợp. Để biết thêm thông tin, hãy xem [Nơi làm việc Hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg). 
- Xác thực đồng tồn tại định tuyến thư SMTP giữa môi trường gửi thư nguồn và phương Office 365 Exchange Online nếu có.
- Cung cấp lịch biểu theo phương pháp đã xác định và danh sách các hộp thư cụ thể cần di chuyển cho mỗi sự kiện di chuyển.
- Thả hộp thư từ lịch biểu cho đến 24 giờ trước lô di chuyển. 
- Lên lịch một số lượng hộp thư đích trung bình trong khoảng thời gian 24 giờ như được liệt kê trong bảng sau đây.
    
|||
|:-----|:-----|
|**Số lượng hộp thư đủ điều kiện di chuyển** <br/> |**Số lượng hộp thư tối thiểu trung bình trong khoảng thời gian 24 giờ** <br/> |
|150-1000  <br/> |25% của tổng số  <br/> |
|1001-5000  <br/> |20% của tổng số  <br/> |
|5001-10000  <br/> |15% của tổng số  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Những số này dựa trên cách thực hành tốt nhất. Tuy nhiên, số lượng hộp thư di chuyển mỗi ngày sẽ khác nhau tùy theo môi trường, tính sẵn sàng và ràng buộc kinh doanh. Microsoft không thể đảm bảo tốc độ di chuyển hộp thư. 
  
- Lên lịch tối thiểu 35 hộp thư trong một lô di chuyển. 
- Khắc phục các lỗi trước di chuyển (nếu áp dụng).  
- Cung cấp quyền truy nhập và quyền truy nhập môi trường nguồn cho Các FastTrack gia thực hiện các hoạt động di chuyển. 
- Mua và/hoặc cung cấp tài khoản quản trị được cấp phép trong Office 365 thực hiện các hoạt động di chuyển (khi thích hợp). 
- Hỗ trợ các sự cố di chuyển phía máy khách và chạy các thao tác sau khi di chuyển nếu cần. 
- Di chuyển dữ liệu phía máy khách nếu muốn. Điều này bao gồm, nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong tệp PST cục bộ, các quy Outlook quy tắc và thiết đặt Outlook địa phương.   
- Giảm kích cỡ hộp thư dưới 85 phần trăm so với giới hạn hộp Office 365 đích (nếu áp dụng).   
- Xử lý các hành động từ báo cáo sau khi di chuyển, bao gồm các hộp thư không di chuyển.  
- Khắc phục các lỗi sau khi di chuyển và lên lịch lại cho các hộp thư (nếu có).   
- Tham gia hỗ trợ sau khi di chuyển đối với các sự cố quan trọng. Các sự cố sau được coi là rất quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn sẽ không sẵn dùng trong quá trình di chuyển.
  - Các hoạt động di chuyển dẫn đến sự cố trong môi trường nguồn.
    
Bạn cần tuân theo quy trình di chuyển tiêu chuẩn và tương tác với Microsoft một cách phù hợp. Điều này bao gồm việc cung cấp quyền truy nhập và quyền truy nhập vào môi trường nguồn và Office 365, cung cấp lịch biểu di chuyển, sửa mọi nguyên nhân gây ra lỗi di chuyển, v.v.. Bạn cũng cần tham gia với người dùng cuối để liên lạc, lịch biểu di chuyển hộp thư và xử lý các sự cố liên quan đến di chuyển người dùng cuối.
  
> [!NOTE]
> Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong quá trình tích hợp. Nếu bạn không sử dụng những tài khoản này, bạn có thể gặp phải tình trạng chậm trễ khi di chuyển. 
  
## <a name="migration-to-sharepoint-online"></a>Di chuyển sang SharePoint Online

### <a name="enable-to-migrate"></a>Cho phép di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của mình, chúng tôi cung cấp hướng dẫn để bật cả SharePoint Online và môi trường nguồn để di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện các bước Bật khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng kết hợp các công cụ và tài liệu, đồng thời thực hiện các tác vụ cấu hình nếu có thể và khả thi.
  
Bạn cần cung cấp quyền truy nhập và quyền thích hợp đối với Microsoft để thực hiện một số hoạt động.
  
### <a name="migration-policy-and-steps"></a>Các bước và chính sách di chuyển
  
> [!NOTE]
> Khoảng thời gian di chuyển còn được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ Vương quốc Anh và Thương mại

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, bảy (7) ngày làm việc mỗi tuần (24x7) trong khoảng thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, năm (5) ngày làm việc một tuần (24x5) trên cơ sở thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ Thứ Hai 2:00AM Giờ Quốc tế Phối hợp (UTC) đến Thứ Sáu nửa đêm UTC. Điều này có nghĩa là di chuyển được lên lịch lần cuối là Thứ Sáu 8:00 CH UTC.

- Tất cả các di chuyển đều tuân theo hạn SharePoint Online được nêu trong SharePoint Online và các ranh [giới và giới OneDrive for Business phần](https://go.microsoft.com/fwlink/?LinkID=616612)mềm mới nhất.   
- Tổng lượng dữ liệu được di chuyển sẽ được ràng buộc với 75% hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau khi một lô di chuyển bao gồm: 
- Dữ liệu từ các nguồn đủ điều kiện và được lên lịch phù hợp trong môi trường nguồn được di chuyển SharePoint Online.   
- Báo cáo sau khi di chuyển cho lô di chuyển do Microsoft cung cấp.
    
Trạng thái kết thúc dự kiến sau khi hoàn thành tất cả di chuyển bao gồm: 
- Dữ liệu từ nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.  
- Kiểu dữ liệu cần di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau đây:
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn** <br/> |**Kiểu di chuyển** <br/> |**Những gì sẽ di chuyển** <br/> |**Những gì sẽ không di chuyển** <br/> |
|**Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền tệp và thư mục mức người dùng\*  <br/>  Quyền tệp mức nhóm và thư mục\*  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/><br/> \**Cần có cấu hình đồng bộ hóa thư mục. Chỉ có các quyền NTFS được chuyển Windows File Explorer mới được di chuyển. Không di chuyển được các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước đó  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Windows thuộc tính tệp và thư mục (như chỉ đọc và ẩn)  <br/>  Các quyền nâng Windows và cài đặt đặc biệt của NTFS và Hệ thống Tệp Công nghệ Mới (NTFS) và NTFS:  <br/>  Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ)  <br/>  Cấu hình kiểm tra NTFS  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI)  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ)  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Môi trường G Suite Đơn (chỉ Google Drive áp dụng)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | <br/>  Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng tệp Office tương đương), bao gồm các tệp có dung lượng trên 10 MB <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm <br/>  Các tệp dưới 15 GB  <br/> Siêu dữ liệu tài liệu cơ bản và thư mục: <br/> Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/> Ổ đĩa dùng chung (thư mục và tệp) <br/>  Nội dung chia sẻ thuộc sở hữu của tài Google Drive di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng Google Drive Quản trị để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục, màu thư mục  <br/>  Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm  <br/>  Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã đổ rác  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Ảnh, Biểu mẫu, Biểu mẫu và Bản đồ các ứng dụng được kết nối khác của Google  <br/>  Hình vẽ Google  <br/>  Nội dung chia sẻ bên ngoài tổ chức của bạn  <br/> Nội dung không thuộc sở hữu của tài Google Drive được di chuyển <br/>Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài  <br/> Quyền của thành viên Shared Drive\* <br/> Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Sử dụng Google Drive Quản trị để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/>|
|**Box (Starter, Business, Enterprise)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/>  Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo Box để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích <br/>  Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm  <br/>  Mô tả tệp và thư mục  <br/>  Thẻ Hộp và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã đổ rác  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Ghi chú Box (không hoạt động khi di chuyển mà không có chuyển đổi)  <br/>  Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản Box đã di chuyển (thư mục dùng chung)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/>\**Sử dụng Google Drive quản trị để xác định tư cách thành viên ổ đĩa dùng chung. Hướng dẫn người dùng cuối cấu hình thiết đặt tư cách thành viên theo mục tiêu trước khi di chuyển.* |
|**Dropbox dùng cho Teams (Tiêu chuẩn và Nâng cao)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/> Các thư mục nhóm dùng chung và nội dung <br/>  Nội dung chia sẻ thuộc sở hữu của Dropbox khoản người dùng sẽ được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/> <br/> \**Sử dụng Dropbox để xác định tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục <br/>  Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm    <br/> Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã đổ rác  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Thư mục chưa được Dropbox đổi <br/>  Đã xóa hoặc người dùng bị ngắt kết nối <br/>  Dropbox Giấy, Giới thiệu và Khoảng trống  <br/> Dropbox Ứng dụng và Yêu thích (Ghim/Sao) <br/> Nội dung không thuộc sở hữu của tài khoản Dropbox di chuyển  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Sử dụng Dropbox để xác định tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> |
   
FastTrack Các chuyên gia thực hiện những việc sau trong quá trình di chuyển: 
- Tiến hành hội thảo hướng dẫn di chuyển bao gồm quy trình và phương pháp tiếp cận cho kịch bản di chuyển được chọn.
- Cung cấp các điều kiện tiên quyết để đánh giá và di chuyển các công cụ khi áp dụng cho kịch bản.   
- Cung cấp điều kiện tiên quyết để nhóm di chuyển truy nhập vào môi trường nguồn và đích cho mục đích đánh giá và di chuyển. 
- Cung cấp các công cụ đánh giá để thực hiện đánh giá môi trường nguồn mục tiêu hoặc cung cấp hướng dẫn về cách sử dụng các hàm nền tảng nguồn gốc để tạo báo cáo đánh giá.   
- Hỗ trợ triển khai và chạy các công cụ đánh giá và di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho việc di chuyển nội dung (nếu có).    
- Thực hiện di chuyển thử nghiệm có giới hạn để xác thực cơ sở hạ tầng di chuyển và các điều kiện tiên quyết bắt buộc.   
- Việc cung cấp đích ngay lập SharePoint Online như một phần trong quá trình di chuyển.    
- Thực hiện một di chuyển thí điểm trước khi di chuyển tốc độ.   
- Cung cấp hướng dẫn về việc lên lịch di chuyển cho kịch bản đã chọn. 
- Thực hiện làn sóng di chuyển nội dung theo lịch biểu di chuyển do khách hàng cung cấp và được xác thực bởi các FastTrack nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào phân loại sự cố di chuyển tốc độ và cung cấp hướng dẫn về các tùy chọn khắc phục tiềm tàng.   
- Cung cấp báo cáo di chuyển cuối cùng cho từng cửa sổ di chuyển tốc độ.   
- Cung cấp trợ giúp sau khi di chuyển trong quá trình kiểm tra chấp nhận người dùng tối đa năm ngày trước khi hoàn tất di chuyển.
    
Bạn thực hiện những thao tác sau đây trong quá trình di chuyển: 
- Cung cấp tài nguyên dự án được đề xuất cho các hoạt động đánh giá và di chuyển. Chúng bao gồm: 
  - Project quản lý. 
  - Kiểm tra Chấp nhận Người dùng (UAT).  
  - Người quản trị chịu trách nhiệm về các nền tảng nội dung nguồn và đích.  
- Cung cấp các điều kiện tiên quyết về cơ sở hạ tầng để đánh giá và di chuyển các hoạt động (nếu cần).  
- Cung cấp quyền truy nhập và quyền truy nhập đến môi trường nguồn và đích đến các Chuyên gia FastTrack công ty thực hiện các hoạt động di chuyển (nếu cần thiết).
    > [!NOTE]
    > Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong quá trình tích hợp. Nếu bạn không sử dụng những tài khoản này, bạn có thể gặp phải tình trạng chậm trễ khi di chuyển. 
- Cung cấp các điều kiện tiên quyết và thực hiện các hoạt động cần thiết để hỗ trợ đánh giá và di chuyển.   
- Cài đặt FastTrack đánh giá do nhà cung cấp và các hoạt động thu thập dữ liệu đánh giá hoàn chỉnh (nếu có).   
- Cài FastTrack phần mềm di chuyển được cung cấp tại chỗ (nếu có).   
- Hoàn thành các hoạt động khắc phục được nêu trong FastTrack cáo khắc phục được cung cấp trước đó (nếu có).  
- Cung cấp lịch biểu di chuyển bằng FastTrack mẫu và hướng dẫn.   
- Tiến hành kiểm tra chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Thực hiện khắc phục sau khi di chuyển (nếu có).
- Lập kế hoạch và triển khai việc quản lý thay đổi cũng như thông tin liên lạc của người dùng cuối (nếu có).   
- Quản trị và cấu hình mọi thay đổi đối với hệ thống nguồn và các thiết bị cần thiết để hoàn thành thành công các hoạt động đánh giá và di chuyển.
- Cung cấp một lịch trình theo phương pháp đã xác định và danh sách dữ liệu người dùng cụ thể cần di chuyển cho mỗi sự kiện di chuyển trước ít nhất ba (3) ngày.
- Thả dữ liệu người dùng từ lịch biểu cho đến 24 giờ trước lô di chuyển. Lô này sẽ tương ứng với lô di chuyển cuối cùng.
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp.
    
## <a name="migration-to-onedrive-for-business"></a>Di chuyển sang OneDrive for Business

 ### <a name="enable-to-migrate"></a>Cho phép di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của mình, chúng tôi sẽ cung cấp hướng dẫn để bật cả dữ OneDrive for Business lẫn môi trường nguồn để di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện các bước Bật khác nhau. Chúng tôi giúp bạn trong một số hoạt động bằng cách sử dụng kết hợp các công cụ, tài liệu và hướng dẫn, đồng thời, bằng cách thực hiện các tác vụ cấu hình nếu có thể và khả thi.
  
Bạn có thể cần cung cấp quyền truy nhập và quyền thích hợp đối với Microsoft để thực hiện một số hoạt động. Nếu bạn không cung cấp quyền truy nhập và/hoặc quyền, bạn cần tự mình thực hiện một số tác vụ đã xác định với hướng dẫn từ Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Các bước và chính sách di chuyển
  
> [!NOTE]
> Khoảng thời gian di chuyển còn được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ Vương quốc Anh và Thương mại

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, bảy (7) ngày làm việc mỗi tuần (24x7) trong khoảng thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di chuyển được thực hiện trên cơ sở 24 giờ một ngày được lên lịch trước tiêu chuẩn, năm (5) ngày làm việc một tuần (24x5) trên cơ sở thời gian di chuyển được xác định trước. Có ba lô di chuyển mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ Thứ Hai 2:00AM Giờ Quốc tế Phối hợp (UTC) đến Thứ Sáu nửa đêm UTC. Điều này có nghĩa là di chuyển được lên lịch lần cuối là Thứ Sáu 8:00 CH UTC.
    
- Tất cả các di chuyển cần có quyền truy nhập và quyền thích hợp đối với môi trường nguồn.   
- Tất cả các di chuyển đều tuân theo OneDrive for Business hạn mức được nêu [trong SharePoint Online và các OneDrive for Business: ranh giới và giới hạn phần mềm.](https://go.microsoft.com/fwlink/?LinkId=698855)
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau khi một lô di chuyển bao gồm:  
- Dữ liệu từ các nguồn đủ điều kiện và được lên lịch phù hợp trong môi trường nguồn được di chuyển sang OneDrive for Business.  
- Báo cáo sau khi di chuyển cho lô di chuyển do Microsoft cung cấp.
    
Trạng thái kết thúc dự kiến sau khi hoàn thành tất cả di chuyển bao gồm:
- Dữ liệu từ các nguồn đủ điều kiện được di chuyển Office 365 như được xác định trong bảng sau đây.  
- Kiểu dữ liệu cần di chuyển phụ thuộc vào môi trường nguồn như mô tả trong bảng sau đây.
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Kiểu di chuyển**|**Những gì sẽ di chuyển**|**Những gì sẽ không di chuyển**|
|**Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền tệp và thư mục mức người dùng\*  <br/>  Quyền tệp mức nhóm và thư mục\*  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/> <br/>\**Cần có cấu hình đồng bộ hóa thư mục. Chỉ có các quyền NTFS được chuyển Windows File Explorer mới được di chuyển. Không di chuyển được các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước đó  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Windows thuộc tính tệp và thư mục (như chỉ đọc và ẩn)  <br/>  Các quyền nâng Windows Hệ thống Tệp Công nghệ Mới (NTFS) và NTFS nâng cao cũng như các cài đặt đặc biệt:  <br/>  Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ)  <br/>  Cấu hình kiểm tra NTFS  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi FCI  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ)  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Môi trường G Suite Đơn (Google Drive riêng)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm các tệp lớn hơn 10 MB)  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/> Ổ đĩa dùng chung (thư mục và tệp) <br/> Nội dung chia sẻ thuộc sở hữu của tài Google Drive di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\* <br/> <br/>\**Sử dụng Google Drive quản trị viên để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích  <br/>  Mô tả tệp và thư mục, màu thư mục  <br/>   Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm  <br/> Siêu dữ liệu nâng cao <br/>  Thuộc tính khóa tệp <br/> Chuyển đổi các URL nhúng trong nội dung  <br/> Các mục đã đổ rác <br/> Tài liệu không thể tiếp cận hoặc bị hỏng <br/> Người dùng bị chặn hoặc không hoạt động <br/> Ảnh của Google <br/> Biểu mẫu, Bản đồ và các ứng dụng được kết nối khác <br/> Hình vẽ Google <br/> Nội dung chia sẻ bên ngoài tổ chức của bạn <br/> Nội dung không thuộc sở hữu của Google Drive khoản người dùng đang được di chuyển <br/> Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài<br/> Các quyền của thành viên trong ổ đĩa dùng chung\*<br/> Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/><br/> \**Sử dụng Google Drive quản trị để xác định tư cách thành viên ổ đĩa dùng chung. Hướng dẫn người dùng cuối cấu hình thiết đặt tư cách thành viên theo mục tiêu trước khi di chuyển.* <br/> |
|**Box (Starter, Business, Enterprise)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/>  Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo Box để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích  <br/>  Mô tả tệp và thư mục  <br/>  Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm  <br/>  Thẻ Hộp và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã đổ rác  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Ghi chú Box (không hoạt động khi di chuyển mà không có chuyển đổi)  <br/>  Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản Box đã di chuyển (thư mục dùng chung)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Dropbox dùng cho Teams (Tiêu chuẩn và Nâng cao)**  <br/> |Truyền một lần hoặc nhiều lần  <br/> | Tài liệu  <br/>  Cấu trúc tệp và thư mục  <br/>  Quyền thư mục mức người dùng  <br/>  Quyền thư mục mức nhóm  <br/>  Các tệp dưới 15 GB  <br/>  Siêu dữ liệu tài liệu cơ bản và thư mục:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Người tạo  <br/>  Sửa đổi lần cuối bởi  <br/> Các thư mục nhóm dùng chung và nội dung <br/> Nội dung chia sẻ thuộc sở hữu của Dropbox khoản người dùng sẽ được di chuyển (nếu được chia sẻ rõ ràng với người dùng hoặc nhóm)\*  <br/> <br/> \**Sử dụng Dropbox để xác định tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và chú thích <br/>  Mô tả tệp và thư mục <br/>  Quyền tệp mức người dùng  <br/>  Quyền tệp mức nhóm    <br/> Siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã đổ rác  <br/>  Tài liệu không thể tiếp cận hoặc bị hỏng  <br/>  Thư mục chưa được Dropbox đổi <br/>  Đã xóa hoặc người dùng bị ngắt kết nối <br/>  Dropbox Giấy, Giới thiệu và Khoảng trống  <br/> Dropbox Ứng dụng và Yêu thích (Ghim/Sao) <br/> Nội dung không thuộc sở hữu của tài khoản Dropbox di chuyển  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc thư mục vượt quá giới [SharePoint Online và hạn chế](https://go.microsoft.com/fwlink/?linkid=846724) <br/> <br/> \**Sử dụng Dropbox để xác định tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> |
   
FastTrack Các chuyên gia thực hiện những việc sau trong quá trình di chuyển:  
- Tiến hành hội thảo hướng dẫn di chuyển bao gồm quy trình và phương pháp tiếp cận cho kịch bản di chuyển được chọn.   
- Cung cấp các điều kiện tiên quyết để đánh giá và di chuyển các công cụ khi áp dụng cho kịch bản.  
- Cung cấp điều kiện tiên quyết để nhóm di chuyển truy nhập vào môi trường nguồn và đích cho mục đích đánh giá và di chuyển.   
- Cung cấp các công cụ đánh giá để thực hiện đánh giá môi trường nguồn mục tiêu hoặc cung cấp hướng dẫn về cách sử dụng các hàm nền tảng nguồn gốc để tạo báo cáo đánh giá.    
- Hỗ trợ triển khai và chạy các công cụ đánh giá và di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho việc di chuyển nội dung (nếu có).    
- Thực hiện di chuyển thử nghiệm hạn chế để xác thực cơ sở hạ tầng di chuyển và các điều kiện tiên quyết bắt buộc.    
- Việc cung cấp các site đích sử dụng ngay OneDrive for Business như một phần trong di chuyển.    
- Thực hiện một di chuyển thí điểm trước khi di chuyển tốc độ.
- Cung cấp hướng dẫn về việc lên lịch di chuyển cho kịch bản đã chọn.   
- Tiến hành làn sóng di chuyển nội dung theo lịch biểu di chuyển do khách hàng cung cấp và được xác thực bởi các FastTrack nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào phân loại sự cố di chuyển tốc độ và cung cấp hướng dẫn về các tùy chọn khắc phục tiềm tàng. 
- Cung cấp báo cáo di chuyển cuối cùng cho từng cửa sổ di chuyển tốc độ.   
- Cung cấp trợ giúp sau khi di chuyển trong quá trình kiểm tra chấp nhận người dùng tối đa năm ngày trước khi hoàn tất di chuyển.
   
Bạn thực hiện những thao tác sau đây trong quá trình di chuyển:
- Cung cấp tài nguyên dự án được đề xuất cho các hoạt động đánh giá và di chuyển. Chúng bao gồm:
  - Project quản lý.
  - UAT.
  - Người quản trị chịu trách nhiệm về các nền tảng nội dung nguồn và đích.
- Cung cấp các điều kiện tiên quyết về cơ sở hạ tầng để đánh giá và di chuyển các hoạt động (nếu cần).   
- Cung cấp quyền truy nhập và quyền truy nhập đến môi trường nguồn và đích đến các Chuyên gia FastTrack năng Thực hiện các hoạt động di chuyển (nếu cần thiết).  
    > [!NOTE]
    > Di chuyển chỉ sử dụng các tài khoản tuân theo yêu cầu bảo mật được xác định trong quá trình tích hợp. Nếu bạn không sử dụng những tài khoản này, bạn có thể gặp phải tình trạng chậm trễ khi di chuyển. 
- Cài đặt FastTrack đánh giá do nhà cung cấp và các hoạt động thu thập dữ liệu đánh giá hoàn chỉnh (nếu có).
- Cài FastTrack phần mềm di chuyển được cung cấp tại chỗ (nếu có).  
- Hoàn thành các hoạt động khắc phục được nêu trong FastTrack cáo khắc phục được cung cấp trước đó (nếu có).   
- Cung cấp lịch biểu di chuyển bằng FastTrack mẫu và hướng dẫn. 
- Cung cấp lịch biểu theo phương pháp đã xác định và danh sách dữ liệu người dùng cụ thể cần di chuyển cho mỗi sự kiện di chuyển.
- Thả dữ liệu người dùng từ lịch biểu cho đến 24 giờ trước lô di chuyển. Lô này sẽ tương ứng với lô di chuyển cuối cùng.
- Tiến hành kiểm tra chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Thực hiện khắc phục sau khi di chuyển (nếu có).  
- Lập kế hoạch và triển khai việc quản lý thay đổi cũng như thông tin liên lạc của người dùng cuối (nếu có).  
- Quản trị và cấu hình mọi thay đổi đối với hệ thống nguồn và các thiết bị cần thiết để hoàn thành thành công các hoạt động đánh giá và di chuyển.
    
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp. 


