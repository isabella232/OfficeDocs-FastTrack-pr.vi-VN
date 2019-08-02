---
title: Di chuyển dữ liệu
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 08/02/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack chuyên cung cấp hướng dẫn về các bước để di chuyển dữ liệu sang Office 365. Điều này là có sẵn cho tất cả các khách hàng đủ điều kiện với các dịch vụ Office 365 Beta dành cho Exchange Online, OneDrive cho doanh nghiệp, và SharePoint Online.
ms.openlocfilehash: 1b55fba1810cf730bee84357b8ed1d08f05154d1
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053637"
---
# <a name="data-migration"></a>Di chuyển dữ liệu

FastTrack chuyên cung cấp hướng dẫn về các bước để di chuyển dữ liệu sang Office 365. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng một sự kết hợp các công cụ và tài liệu hướng dẫn và thực hiện nhiệm vụ cấu hình nơi mà áp dụng và khả thi. Điều này là có sẵn cho tất cả các khách hàng đủ điều kiện với các dịch vụ Office 365 Beta dành cho Exchange Online, OneDrive cho doanh nghiệp, và SharePoint Online.
  
Dịch vụ di chuyển dữ liệu được nêu trong bảng sau đây có sẵn cho Office 365 người thuê nhà với 500 hoặc nhiều giấy phép. \* Ví dụ, bạn có thể có dữ liệu trong của bạn môi trường nguồn mà bạn muốn di chuyển đến Office 365. Lợi ích Trung tâm FastTrack bao gồm cung cấp hướng dẫn với hội nhập môi trường mã nguồn để tạo điều kiện di chuyển nội dung.
  
\*Nếu bạn mua hoặc gia hạn một kế hoạch thương mại trước khi 9/1/2017, 150 chỗ ngồi là yêu cầu tối thiểu phủ trong suốt thời gian đăng ký hiện tại của bạn để nhận được các lợi ích di chuyển. Đối với kế hoạch giáo dục, chỉ trả tiền giảng viên và nhân viên giấy phép là đủ điều kiện cho các dịch vụ di chuyển. 
  
> [!NOTE]
> Dữ liệu di chuyển qua FastTrack dịch vụ có thể được chuyển đến, lưu trữ và xử lý bất cứ nơi nào mà Microsoft duy trì nghi (ngoại trừ như nếu không cung cấp cho bạn tham gia FastTrack cụ thể). Dịch vụ FastTrack không được thiết kế hoặc thiết kế cho dữ liệu đặc biệt yêu cầu pháp lý hoặc theo quy định. 
  
> [!NOTE]
> Vấn đề không lường trước (bao gồm nhưng không giới hạn không thể đọc hoặc hỏng mục trong môi trường nguồn) có thể khiến một số mặt hàng đang được di chuyển. 
  
> [!NOTE]
> Hỗ trợ di chuyển có sẵn trong truyền thống Trung Quốc và tiếng Trung giản thể (tài nguyên nói tiếng quan thoại chỉ), tiếng Anh, Pháp, Đức, ý, tiếng Nhật, tiếng Bồ Đào Nha (Brazil), và tiếng Tây Ban Nha. 
  
> [!NOTE]
> Nếu hội nhập là cần thiết, môi trường mã nguồn của bạn phải ở mức độ tối thiểu cho các ứng dụng đó. 
  
Bảng sau mô tả những gì được dự kiến sẽ di chuyển trong môi trường mã nguồn hiện tại của bạn.
  

|**Hoạt động**|**Nguồn môi trường kỳ vọng**|
|:-----|:-----|
|**Di chuyển Exchange Online**  <br/> | Microsoft di chuyển bất kỳ kết hợp nào của các môi trường nguồn được liệt kê dưới đây, mỗi người một lúc. Chúng tôi có thể di chuyển onboarded các hệ thống nhắn tin bằng cách sử dụng trung tâm FastTrack hoặc nếu nó là thông qua Trung tâm FastTrack kiểm tra. Điều này bao gồm:  <br/>  Một hoặc nhiều thư mục hoạt động rừng với một duy nhất hoặc nhiều tổ chức Exchange, nếu một giống lai dựa trên Exchange 2010 trở đi được thực hiện trong mỗi tổ chức và trao đổi thư hệ thống là năm 2003 trở đi.  <br/> Một đơn IBM Domino 7.0.3 tiếp môi trường ([phụ lục A – di cư từ IBM Domino sang Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).  <br/>  Một môi trường thư điện tử IMAP có khả năng duy nhất.  <br/>  G bộ môi trường (Gmail, địa chỉ liên lạc và lịch chỉ).  <br/>  Một đơn Novell GroupWise 7.0.4 tiếp môi trường.  <br/> <br/> **Lưu ý** *Exchange Online onboarding phải được hoàn tất trước khi di chuyển.* <br/> <br/> **Lưu ý** *FastTrack chỉ di chuyển đến hộp thư hoạt động Office 365.* <br/> <br/> **Lưu ý** *Để phụ thuộc Exchange tại chỗ, hãy xem [điều kiện tiên quyết triển khai kết hợp](https://go.microsoft.com/fwlink/?LinkId=787528).* <br/><br/> **Lưu ý** *Khi di chuyển nhiều nguồn tin nhắn môi trường (như nhiều tổ chức Exchange hoặc nhiều Domino tên miền), những cuộc di cư xảy ra tuần tự.*| 
|**SharePoint Online di chuyển**  <br/> | Chia sẻ tập tin (máy chủ tin nhắn chặn (SMB) tập tin chia sẻ trên các thiết bị hỗ trợ SMB 2.0 trở đi).  <br/>  Hộp (Starter, kinh doanh, doanh nghiệp).  <br/> |
|**OneDrive cho doanh nghiệp di chuyển**  <br/> | Chia sẻ tập tin (SMB tập tin chia sẻ trên các thiết bị hỗ trợ SMB 2.0 trở đi).  <br/>  Một môi trường G mật duy nhất (Google Drive chỉ).  <br/>  Hộp (Starter, kinh doanh, doanh nghiệp). <br/> <br/> **Lưu ý** *FastTrack chỉ di chuyển hoạt động Office 365 ổ.*|
   
## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online

### <a name="enable-to-migrate"></a>Cho phép để di chuyển
  
Nếu bạn dùng Microsoft để di chuyển các email của bạn, chúng tôi cung cấp các hướng dẫn để cho phép cả hai Exchange Online và môi trường nguồn cho di chuyển. Tùy thuộc vào môi trường nguồn, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng một sự kết hợp các công cụ và tài liệu hướng dẫn và thực hiện nhiệm vụ cấu hình nơi mà áp dụng và khả thi. Đối tượng áp dụng các thông số, chúng ta sau đó di chuyển các hộp thư, giám sát các công việc và cung cấp báo cáo trạng thái.
  
Microsoft có thể yêu cầu truy nhập phù hợp và cho phép hệ thống mail của bạn để thực hiện các hoạt động di chuyển.
  
### <a name="migration-policy-and-steps"></a>Chính sách nhập cư và các bước
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Thương mại và chính phủ Vương Quốc Anh

Di chuyển được thực hiện trên một tiêu chuẩn prescheduled 24 giờ một ngày, bảy (7) ngày làm việc trong tuần (24 x 7) cơ sở xác định trước khe thời gian di chuyển. Hiện có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Bộ quốc phòng Mỹ/chính phủ Hoa Kỳ

Di chuyển được thực hiện trên chuẩn prescheduled 24 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (24 x 5) trong khe thời gian di chuyển được xác định trước. Hiện có ba lô di chuyển mỗi ngày di chuyển. Hiện có 5 di chuyển ngày trong một tuần từ thứ hai 2:00 AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa rằng việc di chuyển theo lịch trình cuối thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di chuyển được thực hiện trên chuẩn prescheduled 9 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (9 x 5) trong khe thời gian di chuyển được xác định trước. Đó là một lô di chuyển mỗi ngày di chuyển. Có năm di chuyển ngày trong tuần từ thứ hai 12:00 PM UTC Thứ sáu 21:00 PM UTC.
    
 ### <a name="end-state"></a>Cuối cùng
  
Nhà nước dự kiến sẽ kết thúc sau khi lô di chuyển bao gồm:
- Dữ liệu từ hộp thư nguồn theo lịch trình phù hợp và đủ điều kiện trong môi trường nguồn được di chuyển sang Office 365. 
- Một báo cáo sau khi di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Nhà nước dự kiến sẽ kết thúc sau khi tất cả di chuyển được hoàn chỉnh bao gồm:
- Dữ liệu từ hộp thư nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau.
    
> [!NOTE]
> Môi trường mã nguồn tất cả cần phải mới nhất gói dịch vụ (SP) và rollup (RU) / tích lũy Cập Nhật (CU) cấp cho các sản phẩm tương ứng trong môi trường nguồn vào cuối giai đoạn kích hoạt. Dịch vụ dữ liệu di chuyển phải tuân theo các yếu tố bên ngoài vượt ra ngoài kiểm soát, giống như thay đổi đối với bên thứ ba ứng dụng lập trình giao diện (API), có thể dẫn đến những thay đổi để, sự chậm trễ trong, hoặc đình chỉ các dịch vụ của Microsoft. Trong suốt thời gian của các dịch vụ FastTrack, bạn làm cho có sẵn cho Microsoft dữ liệu có thể truy cập từ và được lưu trữ ở bất cứ đâu mà Microsoft và các nhà cung cấp duy trì nghi. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Loại di chuyển**|**Những gì sẽ di chuyển từ hộp thư nguồn**|**Những gì sẽ không di chuyển**|
|**Exchange 2003 trở về trước**|Dứt điểm| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Hộp thư liên lạc <br/> Lịch <br/> Nhiệm vụ | Thư mục công cộng <br/> Danh bạ cá nhân <br/> Người dùng kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Hộp thư dumpster <br/>  Bất kỳ email vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Quyền quản lý hoặc được mật mã hóa email <br/> Khoản mục bị hỏng <br/>  Hộp thư không hoạt động |
|**Exchange 2003 và Exchange 2007**|Tổ chức| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Hộp thư liên lạc <br/> Lịch <br/> Nhiệm vụ | Thư mục công cộng <br/> Danh bạ cá nhân <br/> Người dùng kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Hộp thư dumpster <br/> Bất kỳ email vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Quyền quản lý hoặc được mật mã hóa email <br/> Khoản mục bị hỏng <br/> Hộp thư không hoạt động |
|**Exchange 2010, Exchange 2013 và đổi Ngoại 2016** <br/><br/> **Lưu ý** *Để phụ thuộc Exchange tại chỗ, hãy xem [điều kiện tiên quyết triển khai kết hợp](https://go.microsoft.com/fwlink/?LinkId=787528).*           |Di chuyển với triển khai kết hợp| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Hộp thư liên lạc <br/> Lịch <br/> Nhiệm vụ <br/> Chữ ký <br/> Lưu trữ cá nhân di chuyển với hộp thư của người dùng <br/> Các mục có thể phục hồi | Thư mục công cộng <br/> Bất kỳ email vượt quá giới hạn kích thước thư <br/> Journaling lưu trữ hoặc bất kỳ bên thứ ba lưu trữ giải pháp <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ các tập tin bảng lưu trữ cá nhân (PST) <br/> Quyền quản lý hoặc được mật mã email <br/> Khoản mục bị hỏng <br/> Hộp thư không hoạt động |
|**Môi trường G mật (Gmail, địa chỉ liên lạc và lịch chỉ)** <br/> <br/> **Lưu ý** *Môi trường của bạn G mật phải có API của Google và Google Admin SDK cho phép cho mở rộng chức năng.* <br/> <br/> **Lưu ý** *Vị trí của dữ liệu: FastTrack có thể chuyển giao, xử lý và lưu trữ dữ liệu di chuyển dựa trên vị trí của khách hàng thuê nhà ở Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft hoặc các nhà cung cấp bên thứ ba duy trì nghi. FastTrack xóa bất kỳ dữ liệu được lưu trữ trong vòng ba mươi ngày kể từ ngày hoàn thành dịch vụ áp dụng.*           |Dứt điểm hoặc theo giai đoạn| Email <br/> Hộp thư liên lạc <br/> Lịch <br/> Nhãn | Quy tắc <br/> Đại biểu <br/> Chữ ký <br/> Nhiệm vụ <br/> Bất kỳ email hoặc các tập tin đính kèm lớn hơn 35 MB <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ các dữ liệu từ PST các tập tin hoặc bất kỳ bên thứ ba lưu trữ giải pháp (ví dụ: Google Vault) <br/> Quyền quản lý hoặc được mật mã hóa email <br/> Khoản mục bị hỏng <br/> Google Hangouts <br/> Google Groups <br/> Hộp thư tài nguyên <br/> Hộp thư không hoạt động |
|**IBM Domino 7.0.3 trở đi** ([Phụ lục A – di cư từ IBM Domino trao đổi trực tuyến](O365-from-ibm-domino-to-exchange-online.md))|Tổ chức| Email - 90 ngày qua <br/> Lịch - 90 ngày qua và các mặt hàng trong tương lai <br/> Hộp thư liên hệ - tất cả <br/> Nhiệm vụ - tất cả <br/> Phòng tài nguyên - cung cấp và họ đang thực hiện với các mẫu tiêu chuẩn <br/> Tập tin thư, bao gồm cả các tập tin được chia sẻ thư, phải sử dụng các mẫu thư tiêu chuẩn | Chữ ký <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Mã hoá khoản mục <br/> Tài liệu liên kết <br/> Người dùng văn phòng phẩm <br/> Bất kỳ email vượt quá giới hạn kích thước thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu <br/> Khoản mục bị hỏng <br/> Lịch cùng tồn tại <br/> Hộp thư không hoạt động |
|**Novell GroupWise 7.0.4 trở đi** <br/><br/> **Lưu ý** *Vị trí của dữ liệu: FastTrack có thể chuyển giao, xử lý và lưu trữ dữ liệu di chuyển dựa trên vị trí của khách hàng thuê nhà ở Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft hoặc các nhà cung cấp bên thứ ba duy trì nghi. FastTrack xóa bất kỳ dữ liệu được lưu trữ trong vòng ba mươi ngày kể từ ngày hoàn thành dịch vụ áp dụng.*           |Tổ chức| Email <br/> Lịch <br/> Hộp thư liên lạc <br/> Nhóm cá nhân <br/> Nhiệm vụ (có hạn chế) <br/> Tài liệu | Quy tắc <br/> Đại biểu-proxy-access control list (ACL) chuyển đổi <br/> Chữ ký <br/> Liên hệ với thể loại <br/> Mã hóa email <br/> Thư mục tìm kiếm <br/> Bất kỳ email hoặc các tập tin đính kèm lớn hơn 35 MB <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu <br/> Quyền quản lý hoặc được mật mã khoản mục <br/> Khoản mục bị hỏng <br/> Lịch cùng tồn tại <br/> Hộp thư không hoạt động |
|**IMAP4 nguồn** |Di chuyển bằng cách sử dụng bản xứ IMAP4 cụ| Email | Quy tắc <br/> Đại biểu <br/> Danh sách phân phối <br/> Liên lạc bên ngoài <br/> Người dùng kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Hộp thư liên lạc <br/> Lịch <br/> Chữ ký <br/> Nhiệm vụ <br/> Bất kỳ email vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Mã hóa email <br/> Khoản mục bị hỏng <br/> Hộp thư không hoạt động |
   
> [!NOTE]
> Nếu danh sách phân phối (MailEnabledGroup đối tượng) và liên hệ bên ngoài (MailEnabledContact đối tượng) trong Active Directory tại chỗ, họ có thể được đồng bộ hóa bằng cách sử dụng Azure quảng cáo kết nối. Tuy nhiên, họ không phải là một phần của di chuyển dữ liệu hộp thư. Để biết thêm chi tiết, hãy xem ví dụ **Identity hội nhập** vào [lõi](O365-onboarding-and-migration.md#core). 
  
FastTrack chuyên gia thực hiện những điều sau đây trong quá trình di chuyển:
- Cung cấp một mẫu tiêu chuẩn cho lập kế hoạch di chuyển hộp thư.
- Cung cấp thông tin về yêu cầu cấp phép cho chuyên gia FastTrack. 
- Thu thập một lịch trình di chuyển hộp thư xác định trước trong định dạng định trước.
- Chia sẻ những công cụ trước khi chuyến bay với bạn, vì vậy bạn có thể chạy các công cụ trước khi chuyến bay và chủ động khắc phục những thất bại trước chuyến bay trước khi di chuyển các hộp thư không thành công.
- Cố gắng để thực hiện di chuyển của một hộp thư duy nhất đến hai lần trong một lô di chuyển trước khi báo cáo rằng hộp thư là một di chuyển không thành công.
- Cho trao đổi và IMAP4 dựa trên nguồn môi trường, di chuyển hộp thư nội dung lên đến 85% của giới hạn lưu trữ hộp thư của người dùng (ví dụ, nếu hộp thư lưu trữ giới hạn 50 GB, Microsoft di cư đến 85% giới hạn lưu trữ 50 GB). 
- Cho phép định tuyến thư SMTP chung sống giữa môi trường nhắn tin mã nguồn và Office 365 Exchange Online trừ khi sử dụng di chuyển.
- Cung cấp các báo cáo sau khi di chuyển.
- Trợ giúp sau di chuyển cho các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất mát dữ liệu khi di chuyển.
  - Môi trường nguồn trở thành không sẵn dùng trong khi di chuyển.
  - Di chuyển hoạt động dẫn đến các vấn đề trong môi trường nguồn.
    
Bạn thực hiện những điều sau đây trong quá trình di chuyển:
- Hoàn thành onboarding Exchange Online hoặc vượt qua kiểm tra yêu cầu sử dụng trung tâm FastTrack.
- Xử lý tất cả các thông tin liên lạc với người dùng cuối.  
- Cài đặt mức độ thích hợp của phần mềm khách hàng theo nguyên tắc Office 365. Để biết thêm thông tin, hãy xem [Office 365 Beta dành cho doanh nghiệp](https://go.microsoft.com/fwlink/?linkid=2005429). 
- Xác thực SMTP mail định tuyến cùng tồn tại giữa nguồn nhắn tin môi trường và văn phòng 365 Exchange Online nếu có.
- Cung cấp một lịch trình ở một phương pháp được xác định và một danh sách các hộp thư cụ thể để di chuyển cho từng sự kiện di chuyển tối thiểu là ba (3) ngày trước. Cho ghi chú quá trình di chuyển, hãy chắc chắn để cung cấp lịch trình 21 ngày trước.
- Thả hộp thư từ lịch trình cho đến 24 giờ trước các lô di chuyển. Điều này phải tương ứng với lô cuối cùng di chuyển.
- Lịch trình một mục tiêu trung bình số lượng hộp thư trong một khoảng thời gian 24 giờ như được liệt kê trong bảng sau.
    
|||
|:-----|:-----|
|**Số lượng hộp thư di chuyển đủ điều kiện** <br/> |**Trung bình tối thiểu số lượng hộp thư trong một khoảng thời gian 24 giờ** <br/> |
|150-1000  <br/> |25% trên tổng số  <br/> |
|1001-5000  <br/> |20% của tổng số  <br/> |
|5001-10000  <br/> |15% trên tổng số  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Những con số này được dựa trên thực hành tốt nhất. Tuy nhiên, một số hộp thư di chuyển mỗi ngày sẽ khác nhau dựa trên môi trường, sẵn sàng chiến đấu, và những hạn chế kinh doanh. Microsoft không thể đảm bảo tốc độ di chuyển hộp thư. 
  
- Lịch trình tối thiểu là 35 các hộp thư trong lô di chuyển. 
- Sửa chữa trước khi di chuyển thất bại (nếu có).  
- Cung cấp quyền truy cập và quyền truy cập vào môi trường nguồn FastTrack chuyên gia thực hiện các hoạt động di chuyển. 
- Mua và/hoặc cung cấp tài khoản quản trị được cấp phép trong Office 365 để thực hiện các hoạt động di chuyển (nếu thích hợp). 
- Hỗ trợ các vấn đề di chuyển phía khách hàng và chạy thao tác di chuyển sau khi cần thiết. 
- Di chuyển dữ liệu phía khách hàng nếu muốn. Điều này bao gồm, nhưng không giới hạn vào sổ địa chỉ địa phương, các dữ liệu địa phương tập tin PST, Outlook quy tắc và cài đặt Outlook địa phương.   
- Giảm kích cỡ hộp thư dưới 85 phần trăm của mục tiêu Office 365 giới hạn hộp thư (nếu có).   
- Xử lý các hành động từ báo cáo di chuyển bài, bao gồm cả hộp thư không di chuyển.  
- Sửa chữa di chuyển sau thất bại và lịch lại hộp thư (nếu có).   
- Tham gia vào thời hậu di chuyển hỗ trợ cho các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất mát dữ liệu khi di chuyển.
  - Môi trường nguồn trở thành không sẵn dùng trong khi di chuyển.
  - Di chuyển hoạt động dẫn đến các vấn đề trong môi trường nguồn.
    
Bạn cần phải tuân theo quy trình tiêu chuẩn di chuyển và tham gia với Microsoft một cách thích hợp. Điều này bao gồm cung cấp truy cập và quyền truy cập đến nguồn và Office 365 môi trường, cung cấp lịch trình di chuyển, điều chỉnh bất kỳ nguyên nhân lỗi di chuyển, và như vậy. Bạn cũng cần phải tham gia với các người dùng cuối cho thông tin liên lạc, lịch trình di chuyển hộp thư và xử lý các vấn đề liên quan đến di chuyển người dùng cuối.
  
> [!NOTE]
> Di chuyển chỉ sử dụng tài khoản Google tuân thủ các yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản như vậy, bạn có thể trải nghiệm di chuyển chậm trễ. 
  
## <a name="migration-to-sharepoint-online"></a>Chuyển đổi sang SharePoint Online

### <a name="enable-to-migrate"></a>Cho phép để di chuyển
  
Nếu bạn dùng Microsoft để di chuyển dữ liệu của bạn, chúng tôi cung cấp các hướng dẫn để kích hoạt SharePoint Online và môi trường nguồn cho di chuyển. Tùy thuộc vào nguồn gốc, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng một sự kết hợp các công cụ và tài liệu hướng dẫn và thực hiện nhiệm vụ cấu hình nơi mà áp dụng và khả thi.
  
Bạn cần cung cấp quyền truy cập thích hợp và cho phép cho Microsoft để thực hiện một số hoạt động.
  
### <a name="migration-policy-and-steps"></a>Chính sách nhập cư và các bước
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Thương mại và chính phủ Vương Quốc Anh

Di chuyển được thực hiện trên một tiêu chuẩn prescheduled 24 giờ một ngày, bảy (7) ngày làm việc trong tuần (24 x 7) cơ sở xác định trước khe thời gian di chuyển. Hiện có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Bộ quốc phòng Mỹ/chính phủ Hoa Kỳ

Di chuyển được thực hiện trên chuẩn prescheduled 24 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (24 x 5) trong khe thời gian di chuyển được xác định trước. Hiện có ba lô di chuyển mỗi ngày di chuyển. Hiện có 5 di chuyển ngày trong một tuần từ thứ hai 2:00 AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa rằng việc di chuyển theo lịch trình cuối thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di chuyển được thực hiện trên chuẩn prescheduled 9 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (9 x 5) trong khe thời gian di chuyển được xác định trước. Đó là một lô di chuyển mỗi ngày di chuyển. Có năm di chuyển ngày trong tuần từ thứ hai 12:00 PM UTC Thứ sáu 21:00 PM UTC.

- Di chuyển tất cả là tùy thuộc vào hạn ngạch SharePoint Online được nêu trong [trực tuyến SharePoint và OneDrive cho doanh nghiệp phần mềm ranh giới và giới hạn](https://go.microsoft.com/fwlink/?LinkID=616612).   
- Số lượng tổng thể di chuyển dữ liệu sẽ bị ràng buộc đến 75% của dung lượng lưu trữ tổng thể SharePoint Online mà bạn có quyền (bao gồm lưu trữ bổ sung, bạn có thể mua riêng).
    
 ### <a name="end-state"></a>Cuối cùng
  
Nhà nước dự kiến sẽ kết thúc sau khi lô di chuyển bao gồm: 
- Dữ liệu từ các nguồn theo lịch trình phù hợp và đủ điều kiện trong môi trường nguồn được di chuyển sang SharePoint Online.   
- Một báo cáo sau khi di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Nhà nước dự kiến sẽ kết thúc sau khi tất cả di chuyển được hoàn chỉnh bao gồm: 
- Dữ liệu từ các nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.  
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau:
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn** <br/> |**Loại di chuyển** <br/> |**Những gì sẽ di chuyển** <br/> |**Những gì sẽ không di chuyển** <br/> |
|**Bất kỳ thiết bị chia sẻ tập tin hỗ trợ SMB 2.0 trở đi**  <br/> |Pass duy nhất  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Quyền người dùng cấp tập tin và thư mục\*  <br/>  Quyền nhóm cấp tập tin và thư mục\*  <br/>  Tập tin nhỏ hơn 15 GB  <br/>  Cơ bản tài liệu và cặp siêu dữ liệu:  <br/>  Tạo ngày  <br/>  Sửa đổi ngày  <br/>  Tạo bởi  <br/>  Lần cuối bởi  <br/><br/> \**Cấu hình đồng bộ hóa thư mục yêu cầu. Chỉ NTFS cho phép tiếp xúc với cửa sổ File Explorer được di chuyển. Quyền quản lý trực tiếp trên các thiết bị chia sẻ tệp không di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, tương đương NTFS permissions tiếp xúc bằng giao thức SMB được di chuyển.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước đó  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Phiên bản trước  <br/>  Thuộc tính tập tin và thư mục Windows (như chỉ-đọc và ẩn)  <br/>  Cửa sổ phòng không mới công nghệ tập tin hệ thống (NTFS) và NTFS nâng cao quyền và đặc biệt cài đặt:  <br/>  Rõ ràng từ chối quyền (gỡ bỏ sau khi di chuyển, nội dung đối tượng song song quyền hoặc cấp phép trên cặp cha mẹ)  <br/>  NTFS kiểm định cấu hình  <br/>  Siêu dữ liệu tập tin bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tập tin (FCI)  <br/>  Tài liệu không truy nhập được hoặc bị hỏng  <br/>  Ẩn chia sẻ  <br/>  Chia sẻ (như quyền được cấp ở cấp độ chia sẻ)  <br/>  Các tập tin hoặc thư mục quá hiện tại [SharePoint Online hạn chế và giới hạn](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Hộp (Starter, kinh doanh, doanh nghiệp)**  <br/> |Đơn hoặc đa qua  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Người dùng thư mục cấp quyền  <br/>  Nhóm thư mục cấp quyền  <br/>  Tập tin nhỏ hơn 15 GB  <br/>  Cơ bản tài liệu và cặp siêu dữ liệu:  <br/>  Tạo ngày  <br/>  Sửa đổi ngày  <br/>  Tạo bởi  <br/>  Lần cuối bởi  <br/>  Chia sẻ nội dung thuộc sở hữu của tài khoản hộp được di chuyển (nếu chia sẻ một cách rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng hộp báo cáo để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để reshare nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước, và ý kiến <br/>  Người dùng tệp cấp phép  <br/>  Nhóm tệp cấp phép  <br/>  Mô tả tập tin và thư mục  <br/>  Hộp thẻ và siêu dữ liệu nâng cao  <br/>  Thuộc tính tệp khóa  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Mục vào thùng rác  <br/>  Tài liệu không truy nhập được hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Hộp ghi chú (không có chức năng khi họ di chuyển mà không cần chuyển đổi)  <br/>  Ứng dụng hộp, Bookmarks, Favorites, và quy trình công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản đã di chuyển hộp (cặp chia sẻ)  <br/>  Quyền hạn và cơ bản các siêu dữ liệu của người dùng bên ngoài\*  <br/>  Các tập tin hoặc thư mục quá hiện tại [SharePoint Online hạn chế và giới hạn](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
FastTrack chuyên gia thực hiện những điều sau đây trong quá trình di chuyển: 
- Tiến hành một hội thảo hướng di chuyển, bao gồm các quá trình và phương pháp tiếp cận cho kịch bản được lựa chọn di chuyển.
- Cung cấp điều kiện tiên quyết cho các công cụ đánh giá và di chuyển như được áp dụng cho các kịch bản.   
- Cung cấp các điều kiện tiên quyết để di chuyển đội truy cập mã nguồn và mục tiêu môi trường với mục đích đánh giá và di chuyển. 
- Cung cấp công cụ đánh giá để thực hiện đánh giá môi trường nguồn mục tiêu, hoặc cung cấp hướng dẫn về làm thế nào để sử dụng nguồn gốc nền tảng hàm để tạo báo cáo đánh giá.   
- Hỗ trợ triển khai và chạy công cụ đánh giá và di chuyển (nếu có).   
- Đặt cấu hình di chuyển cơ sở hạ tầng để chuẩn bị cho di chuyển nội dung (khi áp dụng).    
- Tiến hành một thử nghiệm hạn chế di chuyển để xác nhận di chuyển cơ sở hạ tầng và điều kiện tiên quyết cần thiết.   
- Cung cấp out-of-the-box tiêu SharePoint Online các trang web như là một phần của di chuyển.    
- Tiến hành một thí điểm di chuyển trước khi di chuyển tốc độ.   
- Cung cấp hướng dẫn về lập kế hoạch di chuyển cho các kịch bản đã chọn. 
- Tiến hành vận tốc di chuyển làn sóng của các nội dung theo lịch trình di chuyển do khách hàng cung cấp và xác nhận bởi FastTrack tài nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào vận tốc di chuyển vấn đề phân loại và cung cấp hướng dẫn về lựa chọn khắc phục tiềm năng.   
- Cung cấp một báo cáo cuối cùng di chuyển cho mỗi tốc độ di chuyển cửa sổ.   
- Trợ giúp sau khi di chuyển trong khi người dùng chấp nhận thử nghiệm lên đến 5 ngày trong quá khứ hoàn thành di chuyển.
    
Bạn thực hiện những điều sau đây trong quá trình di chuyển: 
- Cung cấp nguồn lực dự án khuyến khích cho các hoạt động đánh giá và di chuyển. Bao gồm: 
  - Quản lý dự án. 
  - Người dùng chấp nhận thử nghiệm (UAT).  
  - Quản trị viên chịu trách nhiệm về nguồn gốc và mục tiêu nền tảng nội dung.  
- Cung cấp các điều kiện tiên quyết cơ sở hạ tầng cho các hoạt động đánh giá và di chuyển (nếu cần).  
- Cung cấp quyền truy cập và quyền truy cập vào mã nguồn và mục tiêu môi trường FastTrack chuyên gia thực hiện các hoạt động di chuyển (nếu cần).
    > [!NOTE]
    > Di chuyển chỉ sử dụng tài khoản Google tuân thủ các yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản như vậy, bạn có thể trải nghiệm di chuyển chậm trễ. 
- Cung cấp các điều kiện tiên quyết và thực hiện các hoạt động cần thiết để hỗ trợ đánh giá và di chuyển.   
- Cài đặt công cụ cung cấp cho FastTrack đánh giá và hoàn thành đánh giá dữ liệu thu thập hoạt động (nếu có).   
- Cài đặt phần mềm cung cấp cho FastTrack di cư tại chỗ (nếu có).   
- Hoàn thành các hoạt động khắc phục được nêu trong báo cáo khắc phục FastTrack cung cấp (nếu có).  
- Cung cấp một lịch trình di chuyển bằng cách sử dụng FastTrack mẫu và hướng dẫn.   
- Đảm bảo chất lượng tiến hành di chuyển và người dùng chấp nhận thử nghiệm.   
- Tiến hành khắc phục sau di chuyển di chuyển (nếu có).
- Kế hoạch và thực hiện thay đổi thông tin người dùng cuối và quản lý (nếu có).   
- Quản trị và cấu hình bất kỳ thay đổi nào để hệ thống nguồn và các thiết bị cần thiết để hoàn thành các hoạt động đánh giá và di chuyển.
- Cung cấp một lịch trình trong một phương pháp được xác định và một danh sách các dữ liệu người dùng cụ thể để di chuyển cho từng sự kiện di chuyển ít nhất bảy (7) ngày trước.
- Thả người sử dụng dữ liệu từ lịch trình cho đến 24 giờ trước các lô di chuyển. Điều này phải tương ứng với lô cuối cùng di chuyển.
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển file.
    
## <a name="migration-to-onedrive-for-business"></a>Di chuyển đến OneDrive cho doanh nghiệp

 ### <a name="enable-to-migrate"></a>Cho phép để di chuyển
  
Nếu bạn dùng Microsoft để di chuyển dữ liệu của bạn, chúng tôi cung cấp các hướng dẫn để cho phép cả OneDrive cho doanh nghiệp và môi trường nguồn cho di chuyển. Tùy thuộc vào nguồn gốc, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi giúp bạn với một số hoạt động bằng cách sử dụng một sự kết hợp của các công cụ, tài liệu hướng dẫn và hướng dẫn, và bằng cách thực hiện cấu hình nhiệm vụ nơi mà áp dụng và khả thi.
  
Bạn có thể cần cung cấp quyền truy cập thích hợp và cho phép cho Microsoft để thực hiện một số hoạt động. Nếu bạn không cung cấp quyền truy cập và/hoặc cấp phép, bạn cần phải thực hiện một số nhiệm vụ được xác định với sự hướng dẫn từ Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Chính sách nhập cư và các bước
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là một lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Thương mại và chính phủ Vương Quốc Anh

Di chuyển được thực hiện trên một tiêu chuẩn prescheduled 24 giờ một ngày, bảy (7) ngày làm việc trong tuần (24 x 7) cơ sở xác định trước khe thời gian di chuyển. Hiện có ba lô di chuyển mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Bộ quốc phòng Mỹ/chính phủ Hoa Kỳ

Di chuyển được thực hiện trên chuẩn prescheduled 24 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (24 x 5) trong khe thời gian di chuyển được xác định trước. Hiện có ba lô di chuyển mỗi ngày di chuyển. Hiện có 5 di chuyển ngày trong một tuần từ thứ hai 2:00 AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa rằng việc di chuyển theo lịch trình cuối thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di chuyển được thực hiện trên chuẩn prescheduled 9 giờ một ngày, năm (5) ngày làm việc cơ sở tuần (9 x 5) trong khe thời gian di chuyển được xác định trước. Đó là một lô di chuyển mỗi ngày di chuyển. Có năm di chuyển ngày trong tuần từ thứ hai 12:00 PM UTC Thứ sáu 21:00 PM UTC.
    
- Di chuyển tất cả yêu cầu truy nhập phù hợp và cho phép để môi trường nguồn.   
- Di chuyển tất cả là tùy thuộc vào OneDrive cho doanh nghiệp hạn ngạch nêu trong [trực tuyến SharePoint và OneDrive cho doanh nghiệp: giới hạn và ranh giới phần mềm](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Cuối cùng
  
Nhà nước dự kiến sẽ kết thúc sau khi lô di chuyển bao gồm:  
- Dữ liệu từ các nguồn theo lịch trình phù hợp và đủ điều kiện trong môi trường nguồn được di chuyển đến OneDrive cho doanh nghiệp.  
- Một báo cáo sau khi di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Nhà nước dự kiến sẽ kết thúc sau khi tất cả di chuyển được hoàn chỉnh bao gồm:
- Dữ liệu từ nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.  
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau.
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Loại di chuyển**|**Những gì sẽ di chuyển**|**Những gì sẽ không di chuyển**|
|**Môi trường G mật duy nhất (Google Drive chỉ)**  <br/> |Đơn hoặc hai vượt qua  <br/> | Google Docs, Sheets và Slides (tập tin được chuyển đổi sang các định dạng văn phòng tương đương)  <br/>  Cấu trúc tập tin và thư mục  <br/>  Người dùng thư mục cấp quyền  <br/>  Nhóm thư mục cấp quyền  <br/>  Tập tin nhỏ hơn 15 GB  <br/>  Cơ bản tài liệu và cặp siêu dữ liệu:  <br/>  Tạo ngày  <br/>  Sửa đổi ngày  <br/>  Tạo bởi  <br/>  Lần cuối bởi  <br/>  Chia sẻ nội dung thuộc sở hữu của tài khoản Google Drive được di chuyển (nếu chia sẻ một cách rõ ràng với người dùng hoặc nhóm)  <br/> | Lịch sử quyền sở hữu, phiên bản trước, và ý kiến  <br/>  Mô tả tập tin và thư mục, thư mục màu sắc  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Người dùng tệp cấp phép  <br/>  Nhóm tệp cấp phép  <br/> Mục vào thùng rác  <br/>  Tài liệu không truy nhập được hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Chia sẻ nội dung bên ngoài tổ chức của bạn  <br/>  Hình ảnh Google. Hình thức, bản đồ, và các ứng dụng khác được kết nối  <br/>  Google bản vẽ  <br/>  Các tập tin hoặc thư mục quá hiện tại [SharePoint Online hạn chế và giới hạn](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Bất kỳ thiết bị chia sẻ tập tin hỗ trợ SMB 2.0 trở đi**  <br/> |Pass duy nhất  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Quyền người dùng cấp tập tin và thư mục\*  <br/>  Quyền nhóm cấp tập tin và thư mục\*  <br/>  Tập tin nhỏ hơn 15 GB  <br/>  Cơ bản tài liệu và cặp siêu dữ liệu:  <br/>  Tạo ngày  <br/>  Sửa đổi ngày  <br/>  Tạo bởi  <br/>  Lần cuối bởi  <br/> <br/>\**Cấu hình đồng bộ hóa thư mục yêu cầu. Chỉ NTFS cho phép tiếp xúc với cửa sổ File Explorer được di chuyển. Quyền quản lý trực tiếp trên các thiết bị chia sẻ tệp không di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, tương đương NTFS permissions tiếp xúc bằng giao thức SMB được di chuyển.* <br/> | Lịch sử quyền sở hữu và các phiên bản trước đó  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Phiên bản trước  <br/>  Thuộc tính tập tin và thư mục Windows (như chỉ-đọc và ẩn)  <br/>  Cửa sổ phòng không mới công nghệ tập tin hệ thống (NTFS) và NTFS nâng cao quyền và đặc biệt cài đặt:  <br/>  Rõ ràng từ chối quyền (gỡ bỏ sau khi di chuyển, nội dung đối tượng song song quyền hoặc cấp phép trên cặp cha mẹ)  <br/>  NTFS kiểm định cấu hình  <br/>  Siêu dữ liệu tập tin bổ sung được cung cấp bởi FCI  <br/>  Tài liệu không truy nhập được hoặc bị hỏng  <br/>  Ẩn chia sẻ  <br/>  Chia sẻ (như quyền được cấp ở cấp độ chia sẻ)  <br/>  Các tập tin hoặc thư mục quá hiện tại [SharePoint Online hạn chế và giới hạn](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
|**Hộp (Starter, kinh doanh, doanh nghiệp)**  <br/> |Đơn hoặc đa qua  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Người dùng thư mục cấp quyền  <br/>  Nhóm thư mục cấp quyền  <br/>  Tập tin nhỏ hơn 15 GB  <br/>  Cơ bản tài liệu và cặp siêu dữ liệu:  <br/>  Tạo ngày  <br/>  Sửa đổi ngày  <br/>  Tạo bởi  <br/>  Lần cuối bởi  <br/>  Chia sẻ nội dung thuộc sở hữu của tài khoản hộp được di chuyển (nếu chia sẻ một cách rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng hộp báo cáo để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối để reshare nội dung của họ sau khi di chuyển.* <br/> | Lịch sử quyền sở hữu, phiên bản trước, và ý kiến  <br/>  Mô tả tập tin và thư mục  <br/>  Người dùng tệp cấp phép  <br/>  Nhóm tệp cấp phép  <br/>  Hộp thẻ và siêu dữ liệu nâng cao  <br/>  Thuộc tính tệp khóa  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Mục vào thùng rác  <br/>  Tài liệu không truy nhập được hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Hộp ghi chú (không có chức năng khi họ di chuyển mà không cần chuyển đổi)  <br/>  Ứng dụng hộp, Bookmarks, Favorites, và quy trình công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản đã di chuyển hộp (cặp chia sẻ)  <br/>  Quyền hạn và cơ bản các siêu dữ liệu của người dùng bên ngoài\*  <br/>  Các tập tin hoặc thư mục quá hiện tại [SharePoint Online hạn chế và giới hạn](https://go.microsoft.com/fwlink/?linkid=846724) <br/> |
   
FastTrack chuyên gia thực hiện những điều sau đây trong quá trình di chuyển:  
- Tiến hành một hội thảo hướng di chuyển, bao gồm các quá trình và phương pháp tiếp cận cho kịch bản được lựa chọn di chuyển.   
- Cung cấp điều kiện tiên quyết cho các công cụ đánh giá và di chuyển như được áp dụng cho các kịch bản.  
- Cung cấp các điều kiện tiên quyết để di chuyển đội truy cập mã nguồn và mục tiêu môi trường với mục đích đánh giá và di chuyển.   
- Cung cấp công cụ đánh giá để thực hiện đánh giá môi trường nguồn mục tiêu, hoặc cung cấp hướng dẫn về làm thế nào để sử dụng nguồn gốc nền tảng hàm để tạo báo cáo đánh giá.    
- Cung cấp một lịch trình trong một phương pháp được xác định và một danh sách các dữ liệu người dùng cụ thể để di chuyển cho từng sự kiện di chuyển ít nhất bảy (7) ngày trước.
- Thả người sử dụng dữ liệu từ lịch trình cho đến 24 giờ trước các lô di chuyển. Điều này phải tương ứng với lô cuối cùng di chuyển.
- Hỗ trợ triển khai và chạy công cụ đánh giá và di chuyển (nếu có).   
- Đặt cấu hình di chuyển cơ sở hạ tầng để chuẩn bị cho di chuyển nội dung (khi áp dụng).    
- Tiến hành một thử nghiệm hạn chế di chuyển để xác nhận di chuyển cơ sở hạ tầng và điều kiện tiên quyết cần thiết.    
- Cung cấp out-of-the-box tiêu OneDrive cho trang web kinh doanh như là một phần của di chuyển.    
- Tiến hành một thí điểm di chuyển trước khi di chuyển tốc độ.
- Cung cấp hướng dẫn về lập kế hoạch di chuyển cho các kịch bản đã chọn.   
- Tiến hành vận tốc di chuyển làn sóng của các nội dung theo lịch trình di chuyển do khách hàng cung cấp và xác nhận bởi FastTrack tài nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào vận tốc di chuyển vấn đề phân loại và cung cấp hướng dẫn về lựa chọn khắc phục tiềm năng. 
- Cung cấp một báo cáo cuối cùng di chuyển cho mỗi tốc độ di chuyển cửa sổ.   
- Trợ giúp sau khi di chuyển trong khi người dùng chấp nhận thử nghiệm lên đến 5 ngày trong quá khứ hoàn thành di chuyển.
   
Bạn thực hiện những điều sau đây trong quá trình di chuyển:
- Cung cấp nguồn lực dự án khuyến khích cho các hoạt động đánh giá và di chuyển. Bao gồm:
  - Quản lý dự án.
  - UAT.
  - Quản trị viên chịu trách nhiệm về nguồn gốc và mục tiêu nền tảng nội dung.
- Cung cấp các điều kiện tiên quyết cơ sở hạ tầng cho các hoạt động đánh giá và di chuyển (nếu cần).   
- Cung cấp quyền truy cập và quyền truy cập vào mã nguồn và mục tiêu môi trường FastTrack chuyên gia thực hiện các hoạt động di chuyển (nếu cần).  
    > [!NOTE]
    > Di chuyển chỉ sử dụng tài khoản Google tuân thủ các yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản như vậy, bạn có thể trải nghiệm di chuyển chậm trễ. 
- Cài đặt công cụ cung cấp cho FastTrack đánh giá và hoàn thành đánh giá dữ liệu thu thập hoạt động (nếu có).
- Cài đặt phần mềm cung cấp cho FastTrack di cư tại chỗ (nếu có).  
- Hoàn thành các hoạt động khắc phục được nêu trong báo cáo khắc phục FastTrack cung cấp (nếu có).   
- Cung cấp một lịch trình di chuyển bằng cách sử dụng FastTrack mẫu và hướng dẫn. 
- Đảm bảo chất lượng tiến hành di chuyển và người dùng chấp nhận thử nghiệm.   
- Tiến hành khắc phục sau di chuyển di chuyển (nếu có).  
- Kế hoạch và thực hiện thay đổi thông tin người dùng cuối và quản lý (nếu có).  
- Quản trị và cấu hình bất kỳ thay đổi nào để hệ thống nguồn và các thiết bị cần thiết để hoàn thành các hoạt động đánh giá và di chuyển.
    
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển file.  

