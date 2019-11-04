---
title: Di chuyển dữ liệu
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/02/2019
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack chuyên gia cung cấp hướng dẫn về các bước để di chuyển dữ liệu sang Office 365. Điều này có sẵn cho tất cả các khách hàng hợp lệ với Office 365 dịch vụ dành cho Exchange Online, OneDrive dành cho doanh nghiệp và SharePoint Online.
ms.openlocfilehash: 011ac6cd7a6f53872bf9545cb837700418415566
ms.sourcegitcommit: f8d7e570b60a55c244af0eceb6fbb0e591257f11
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/01/2019
ms.locfileid: "37921252"
---
# <a name="data-migration"></a>Di chuyển dữ liệu

FastTrack chuyên gia cung cấp hướng dẫn về các bước để di chuyển dữ liệu sang Office 365. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng kết hợp các công cụ và tài liệu và thực hiện các tác vụ cấu hình nếu áp dụng và khả thi. Điều này có sẵn cho tất cả các khách hàng hợp lệ với Office 365 dịch vụ dành cho Exchange Online, OneDrive dành cho doanh nghiệp và SharePoint Online.
  
Dịch vụ di chuyển dữ liệu được nêu trong bảng sau có sẵn cho Office 365 thuê với 500 hoặc nhiều giấy phép. \* Ví dụ: bạn có thể có dữ liệu trong môi trường nguồn mà bạn muốn di chuyển sang Office 365. Lợi ích Trung tâm FastTrack bao gồm cung cấp hướng dẫn tích hợp môi trường nguồn để tạo điều kiện di chuyển nội dung.
  
\*Nếu bạn mua hoặc gia hạn kế hoạch thương mại trước 9/1/2017, 150 ghế là yêu cầu về chỗ ngồi tối thiểu trong suốt thời gian đăng ký hiện tại của bạn để nhận được lợi ích di chuyển. Đối với các kế hoạch giáo dục, chỉ có các giấy phép khoa và nhân viên trả phí đều đủ điều kiện nhận dịch vụ di chuyển. 
  
> [!NOTE]
> Dữ liệu di chuyển qua các dịch vụ FastTrack có thể được truyền đến, lưu trữ và xử lý bất cứ nơi nào mà Microsoft duy trì cơ sở (trừ khi được cung cấp khác cho sự tham gia của FastTrack cụ thể của bạn). Các dịch vụ FastTrack không được thiết kế hoặc dành cho dữ liệu theo yêu cầu pháp lý hoặc quy định đặc biệt. 
  
> [!NOTE]
> Các vấn đề bất khả kháng (bao gồm nhưng không giới hạn trong các mục không thể đọc được hoặc bị hỏng trong môi trường nguồn) có khả 
  
> [!NOTE]
> Hỗ trợ di cư có sẵn trong tiếng Trung Phồn thể và tiếng Trung giản thể (tài nguyên nói Mandarin chỉ), Anh, Pháp, Đức, ý, Nhật, Bồ Đào Nha (Brazil), và Tây Ban Nha. 
  
> [!NOTE]
> Nếu cần tích hợp, môi trường nguồn của bạn phải ở mức tối thiểu cho ứng dụng đó. 
  
Bảng sau mô tả những gì mong muốn di chuyển trong môi trường nguồn hiện tại của bạn.
  

|**Hoạt động**|**Môi trường nguồn kỳ vọng**|
|:-----|:-----|
|**Di chuyển Exchange Online**  <br/> | Microsoft di cư bất kỳ sự kết hợp của các môi trường nguồn được liệt kê dưới đây, mỗi một lần. Chúng tôi có thể di chuyển hệ thống nhắn tin onboarded bằng cách sử dụng trung tâm FastTrack hoặc nếu nó được thông qua Trung tâm FastTrack kiểm tra. Điều này bao gồm:  <br/>  Một hoặc nhiều khu rừng Active Directory với một hoặc nhiều tổ chức Exchange, nếu một Exchange 2010 dựa trên kết hợp trở đi được thực hiện trong mỗi tổ chức và hệ thống thư Exchange là 2003 trở đi.  <br/> Một IBM Domino 7.0.3 trở đi môi trường ([phụ lục A-di chuyển từ IBM Domino sang Exchange Online](O365-from-ibm-domino-to-exchange-online.md)).  <br/>  Một môi trường email có khả năng IMAP duy nhất.  <br/>  Môi trường G Suite (chỉ Gmail, danh bạ và lịch).  <br/>  Một Novell GroupWise 7.0.4 trở đi môi trường.  <br/> <br/> **Lưu ý** *Exchange Online bộ nhớ ngoài phải được hoàn thành trước khi di chuyển.* <br/> <br/> **Lưu ý** *FastTrack chỉ di chuyển đến hoạt động văn phòng 365 hộp thư.* <br/> <br/> **Lưu ý** để *phụ thuộc tại chỗ Exchange, xem điều [kiện tiên quyết triển khai kết](https://go.microsoft.com/fwlink/?LinkId=787528)hợp.* <br/><br/> **Lưu ý** *khi di chuyển nhiều môi trường nhắn tin nguồn (như nhiều tổ chức trao đổi hoặc nhiều tên miền Domino), các di chuyển xảy ra tuần tự.*| 
|**Di chuyển SharePoint trực tuyến**  <br/> | Chia sẻ tệp (máy chủ thư khối (SMB) chia sẻ tệp trên thiết bị hỗ trợ SMB 2,0 trở đi).  <br/>  Hộp (Starter, kinh doanh, doanh nghiệp).  <br/> |
|**OneDrive cho việc di chuyển**  <br/> | Chia sẻ tệp (SMB tệp chia sẻ trên thiết bị hỗ trợ SMB 2,0 trở đi).  <br/>  Một môi trường G Suite duy nhất (chỉ dành cho Google Drive).  <br/>  Hộp (Starter, kinh doanh, doanh nghiệp). <br/> <br/> **Lưu ý** *FastTrack chỉ di chuyển sang hoạt động văn phòng 365 ổ đĩa.*|
   
## <a name="migration-to-exchange-online"></a>Di chuyển sang Exchange Online

### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển email của bạn, chúng tôi cung cấp hướng dẫn để kích hoạt cả Exchange Online và môi trường nguồn cho di chuyển. Tùy thuộc vào môi trường nguồn, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng kết hợp các công cụ và tài liệu và thực hiện các tác vụ cấu hình nếu áp dụng và khả thi. Tùy thuộc vào thông số áp dụng, chúng tôi sau đó di chuyển các hộp thư, giám sát công việc và cung cấp báo cáo trạng thái.
  
Microsoft có thể yêu cầu quyền truy cập và quyền thích hợp cho hệ thống thư của bạn để thực hiện các hoạt động di chuyển.
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Di cư được thực hiện trên một các tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong các khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di cư được thực hiện trên các tiêu chuẩn 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 2:00AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển theo lịch trình cuối cùng là thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di cư được thực hiện trên tiêu chuẩn hóa các 9 giờ một ngày, năm (5) ngày làm việc một tuần (9x5) cơ sở trong khe thời gian di chuyển được xác định trước. Có một lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 12:00PM UTC đến thứ sáu 21:00PM UTC.
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau khi lô di chuyển bao gồm:
- Dữ liệu từ các hộp thư nguồn theo lịch trình và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển sang Office 365. 
- Báo cáo sau di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả di chuyển hoàn tất bao gồm:
- Dữ liệu từ hộp thư nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau.
    
> [!NOTE]
> Tất cả các môi trường nguồn phải trên các gói dịch vụ mới nhất (SP) và bản Cập Nhật (RU)/Cumulative Update (CU) cấp cho sản phẩm tương ứng trong môi trường nguồn ở cuối giai đoạn kích hoạt. Dịch vụ di chuyển dữ liệu phải tuân thủ các yếu tố bên ngoài ngoài tầm kiểm soát của Microsoft, như thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API), có thể dẫn đến thay đổi, trì hoãn hoặc tạm ngưng các dịch vụ này. Trong thời gian của các dịch vụ FastTrack, dữ liệu bạn cung cấp cho Microsoft có thể truy cập từ và lưu trữ bất cứ nơi nào mà Microsoft và các nhà cung cấp duy trì cơ sở. 
  
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Loại di chuyển**|**Điều gì sẽ di chuyển từ hộp thư nguồn**|**Điều gì sẽ không di chuyển**|
|**Exchange 2003 trở đi**|Đơn giản| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Danh bạ hộp thư <br/> Calendar <br/> Nhiệm vụ <br/> Email được quản lý quyền| Thư mục công cộng <br/> Danh bạ cá nhân <br/> Người dùng được kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Hộp thư Dumpster <br/>  Bất kỳ email nào vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Email được mã hóa <br/> Các mục bị hỏng <br/>  Hộp thư không hoạt động |
|**Trao đổi 2003 và Exchange 2007**|Tổ chức| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Danh bạ hộp thư <br/> Calendar <br/> Nhiệm vụ <br/> Email được quản lý quyền| Thư mục công cộng <br/> Danh bạ cá nhân <br/> Người dùng được kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Chữ ký <br/> Hộp thư Dumpster <br/> Bất kỳ email nào vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Email được mã hóa <br/> Các mục bị hỏng <br/> Hộp thư không hoạt động |
|**Trao đổi 2010, Exchange 2013 và Exchange 2016** <br/><br/> **Lưu ý** để *phụ thuộc tại chỗ Exchange, xem điều [kiện tiên quyết triển khai kết](https://go.microsoft.com/fwlink/?LinkId=787528)hợp.*           |Di chuyển với triển khai kết hợp| Email <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Danh bạ hộp thư <br/> Calendar <br/> Nhiệm vụ <br/> Chữ ký <br/> Lưu trữ cá nhân đã di chuyển với hộp thư của người dùng <br/> Mục có thể phục hồi <br/> Email được quản lý quyền| Thư mục công cộng <br/> Bất kỳ email nào vượt quá giới hạn kích thước thư <br/> Journaling lưu trữ hoặc bất kỳ giải pháp lưu trữ của bên thứ ba <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ cá nhân lưu trữ bảng (PST) tập tin <br/> Email được mã hóa <br/> Các mục bị hỏng <br/> Hộp thư không hoạt động |
|**Môi trường G Suite (chỉ Gmail, danh bạ và lịch)** <br/> <br/> **Lưu ý** *môi trường G Suite của bạn phải có API Google và SDK Google admin được kích hoạt để mở rộng chức năng.* <br/> <br/> **Lưu ý** *vị trí của dữ liệu: FastTrack có thể truyền, xử lý và lưu trữ dữ liệu di chuyển dựa trên vị trí của khách hàng thuê nhà ở Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft hoặc các nhà cung cấp bên thứ ba duy trì cơ sở. FastTrack xóa bất kỳ dữ liệu được lưu trữ nào trong vòng ba mươi ngày khi hoàn thành các dịch vụ hiện hành.*           |Cutover hoặc dàn dựng| Email <br/> Danh bạ hộp thư <br/> Calendar <br/> Nhãn | Quy tắc <br/> Đại biểu <br/> Chữ ký <br/> Nhiệm vụ <br/> Bất kỳ email hoặc tệp đính kèm nào lớn hơn 35 MB <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu từ các tập tin PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba (ví dụ, Google Vault) <br/> Quyền quản lý hoặc mã hóa email <br/> Các mục bị hỏng <br/> Google Hangouts <br/> Google Groups <br/> Hộp thư tài nguyên <br/> Hộp thư không hoạt động |
|**IBM Domino 7.0.3 trở** đi ([phụ lục A-di chuyển từ IBM Domino sang Exchange Online](O365-from-ibm-domino-to-exchange-online.md))|Tổ chức| Email-cuối 90 ngày <br/> Lịch-cuối 90 ngày và các mặt hàng trong tương lai <br/> Danh bạ hộp thư-tất cả <br/> Nhiệm vụ-tất cả <br/> Các phòng và tài nguyên-cung cấp chúng được thực hiện với tiêu chuẩn mẫu <br/> Tệp thư, bao gồm tệp thư dùng chung, phải sử dụng mẫu thư tiêu chuẩn | Chữ ký <br/> Quy tắc hộp thư <br/> Đại biểu <br/> Mục được mã hóa <br/> Liên kết tài liệu <br/> Văn phòng phẩm người dùng <br/> Bất kỳ email nào vượt quá giới hạn kích thước thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu <br/> Các mục bị hỏng <br/> Lịch cùng tồn tại <br/> Hộp thư không hoạt động |
|**Novell GroupWise 7.0.4 trở đi** <br/><br/> **Lưu ý** *vị trí của dữ liệu: FastTrack có thể truyền, xử lý và lưu trữ dữ liệu di chuyển dựa trên vị trí của khách hàng thuê nhà ở Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft hoặc các nhà cung cấp bên thứ ba duy trì cơ sở. FastTrack xóa bất kỳ dữ liệu được lưu trữ nào trong vòng ba mươi ngày khi hoàn thành các dịch vụ hiện hành.*           |Tổ chức| Email <br/> Calendar <br/> Danh bạ hộp thư <br/> Nhóm cá nhân <br/> Nhiệm vụ (có giới hạn) <br/> Tài liệu | Quy tắc <br/> Chuyển đổi danh sách (ACL) proxy/người đại diện/kiểm soát truy nhập <br/> Chữ ký <br/> Danh mục liên hệ <br/> Email được mã hóa <br/> Tìm thư mục <br/> Bất kỳ email hoặc tệp đính kèm nào lớn hơn 35 MB <br/> Người dùng bị chặn hoặc không hoạt động <br/> Lưu trữ dữ liệu <br/> Các mục được quản lý quyền hoặc mã hóa <br/> Các mục bị hỏng <br/> Lịch cùng tồn tại <br/> Hộp thư không hoạt động |
|**Nguồn IMAP4** |Di chuyển bằng công cụ gốc IMAP4| Email | Quy tắc <br/> Đại biểu <br/> Danh sách phân phối <br/> Số liên lạc bên ngoài <br/> Người dùng được kích hoạt thư <br/> Người dùng bị chặn hoặc không hoạt động <br/> Danh bạ hộp thư <br/> Calendar <br/> Chữ ký <br/> Nhiệm vụ <br/> Bất kỳ email nào vượt quá giới hạn kích thước thư <br/> Lưu trữ dữ liệu <br/> Email được mã hóa <br/> Các mục bị hỏng <br/> Hộp thư không hoạt động |
   
> [!NOTE]
> Nếu danh sách phân phối (MailEnabledGroup đối tượng) và liên hệ bên ngoài (MailEnabledContact đối tượng) trong Active Directory tại chỗ, họ có thể được đồng bộ hoá bằng cách sử dụng Azure AD kết nối. Tuy nhiên, chúng không phải là một phần của di chuyển dữ liệu hộp thư. Để biết thêm thông tin, hãy xem ví dụ về **tích hợp danh tính** trong [lõi](O365-onboarding-and-migration.md#core). 
  
FastTrack chuyên gia thực hiện như sau trong quá trình di chuyển:
- Cung cấp một mẫu chuẩn để lên lịch di chuyển hộp thư.
- Cung cấp thông tin về các quyền cần thiết cho FastTrack chuyên gia. 
- Thu thập lịch di chuyển hộp thư định sẵn ở định dạng đã xác định trước.
- Chia sẻ các công cụ trước chuyến bay với bạn, vì vậy bạn có thể chạy công cụ trước chuyến bay và chủ động khắc phục lỗi trước chuyến bay trước khi di chuyển các hộp thư không thành công.
- Cố gắng thực hiện di chuyển một hộp thư duy nhất đến hai lần trong một lô di chuyển trước khi báo cáo hộp thư đó là một di chuyển không thành công.
- Đối với môi trường nguồn dựa trên Exchange và IMAP4, di chuyển nội dung hộp thư lên đến 85% giới hạn lưu trữ hộp thư người dùng (ví dụ: nếu giới hạn lưu trữ hộp thư 50 GB, Microsoft di chuyển lên đến 85% giới hạn lưu trữ 50 GB). 
- Cho phép định tuyến thư SMTP cùng tồn tại giữa các môi trường nhắn tin nguồn và Office 365 Exchange Online trừ khi sử dụng di chuyển đơn giản.
- Cung cấp báo cáo sau di chuyển.
- Cung cấp hỗ trợ sau di chuyển cho các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn trở nên không khả dụng trong quá trình di chuyển.
  - Di chuyển hoạt động dẫn đến các vấn đề trong môi trường nguồn.
    
Bạn thực hiện như sau trong quá trình di chuyển:
- Hoàn thành Exchange Online bộ nhớ ngoài hoặc vượt qua các kiểm tra cần thiết bằng cách sử dụng trung tâm FastTrack.
- Xử lý tất cả các giao tiếp với người dùng cuối.  
- Cài đặt mức độ phù hợp của phần mềm khách hàng theo hướng dẫn 365 Office. Để biết thêm thông tin, xem [Office 365 dành cho doanh nghiệp](https://go.microsoft.com/fwlink/?linkid=2005429). 
- Xác thực SMTP thư định tuyến cùng tồn tại giữa nguồn nhắn tin môi trường và Office 365 Exchange Online nếu áp dụng.
- Cung cấp một lịch trình trong một phương pháp được xác định và một danh sách các hộp thư cụ thể để di chuyển cho mỗi sự kiện di chuyển ít nhất ba (3) ngày trước. Đối với ghi chú di chuyển, hãy chắc chắn để cung cấp lịch trình 21 ngày trước.
- Thả hộp thư từ lịch trình cho đến 24 giờ trước lô di chuyển. Điều này sẽ tương ứng với lô di chuyển cuối cùng.
- Lên lịch một số mục tiêu trung bình của hộp thư trong khoảng thời gian 24 giờ như được liệt kê trong bảng sau.
    
|||
|:-----|:-----|
|**Số lượng hộp thư đủ điều kiện di chuyển** <br/> |**Số lượng hộp thư tối thiểu trung bình trong khoảng thời gian 24 giờ** <br/> |
|150-1000  <br/> |25% tổng số  <br/> |
|1001-5000  <br/> |20% tổng số  <br/> |
|5001-10000  <br/> |15% tổng số  <br/> |
|\>10000  <br/> |1500  <br/> |
   
   > [!NOTE]
   > Những số này được dựa trên thực hành tốt nhất. Tuy nhiên, số lượng hộp thư di chuyển mỗi ngày sẽ thay đổi dựa trên môi trường, sự sẵn sàng và hạn chế về kinh doanh. Microsoft không thể đảm bảo tốc độ di chuyển hộp thư. 
  
- Lên lịch tối thiểu 35 hộp thư trong lô di chuyển. 
- Khắc phục lỗi trước khi di chuyển (nếu có).  
- Cung cấp quyền truy cập và cho phép môi trường nguồn FastTrack chuyên gia thực hiện các hoạt động di chuyển. 
- Procure và/hoặc cung cấp tài khoản quản trị được cấp phép trong Office 365 để thực hiện các hoạt động di chuyển (nếu thích hợp). 
- Hỗ trợ sự cố di chuyển phía máy khách và chạy thao tác sau khi di trú cần thiết. 
- Di chuyển dữ liệu phía máy khách nếu muốn. Điều này bao gồm, nhưng không giới hạn, sổ địa chỉ địa phương, dữ liệu trong các tập tin PST địa phương, quy tắc Outlook và cài đặt Outlook cục bộ.   
- Giảm kích thước hộp thư dưới 85 phần trăm mục tiêu Office 365 hộp thư giới hạn (nếu có).   
- Xử lý các hành động từ báo cáo di chuyển bài viết, bao gồm các hộp thư không di chuyển.  
- Khắc phục lỗi sau di chuyển và lịch lại hộp thư (nếu có).   
- Tham gia hỗ trợ sau di chuyển cho các vấn đề quan trọng. Các vấn đề sau đây được coi là quan trọng:
  - Mất dữ liệu trong quá trình di chuyển.
  - Môi trường nguồn trở nên không khả dụng trong quá trình di chuyển.
  - Di chuyển hoạt động dẫn đến các vấn đề trong môi trường nguồn.
    
Bạn cần thực hiện theo quy trình di chuyển chuẩn và tương tác với Microsoft một cách thích hợp. Điều này bao gồm cung cấp quyền truy cập và cho phép nguồn và Office 365 môi trường, cung cấp lịch trình di chuyển, điều chỉnh bất kỳ nguyên nhân lỗi di chuyển, và như vậy. Bạn cũng cần phải tương tác với người dùng cuối để truyền thông, lịch di chuyển hộp thư và xử lý các sự cố liên quan đến di chuyển người dùng cuối.
  
> [!NOTE]
> Di chuyển chỉ sử dụng tài khoản tuân theo yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản này, bạn có thể gặp sự chậm trễ di chuyển. 
  
## <a name="migration-to-sharepoint-online"></a>Di chuyển sang SharePoint trực tuyến

### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của bạn, chúng tôi cung cấp hướng dẫn để kích hoạt SharePoint trực tuyến và môi trường nguồn cho di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi cung cấp hướng dẫn cho bạn bằng cách sử dụng kết hợp các công cụ và tài liệu và thực hiện các tác vụ cấu hình nếu áp dụng và khả thi.
  
Bạn cần cung cấp quyền truy cập và quyền thích hợp cho Microsoft để thực hiện một số hoạt động.
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Di cư được thực hiện trên một các tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong các khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di cư được thực hiện trên các tiêu chuẩn 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 2:00AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển theo lịch trình cuối cùng là thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di cư được thực hiện trên tiêu chuẩn hóa các 9 giờ một ngày, năm (5) ngày làm việc một tuần (9x5) cơ sở trong khe thời gian di chuyển được xác định trước. Có một lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 12:00PM UTC đến thứ sáu 21:00PM UTC.

- Di chuyển tất cả tuân theo dung lượng SharePoint trực tuyến được nêu trong [SharePoint trực tuyến và OneDrive cho doanh nghiệp phần mềm ranh giới và giới hạn](https://go.microsoft.com/fwlink/?LinkID=616612).   
- Tổng lượng dữ liệu di chuyển sẽ bị ràng buộc đến 75% dung lượng lưu trữ SharePoint trực tuyến tổng thể mà bạn được hưởng (bao gồm bộ nhớ bổ sung mà bạn có thể đã mua riêng).
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau khi lô di chuyển bao gồm: 
- Dữ liệu từ các nguồn đã lên lịch và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển sang SharePoint Online.   
- Báo cáo sau di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả di chuyển hoàn tất bao gồm: 
- Dữ liệu từ nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.  
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau:
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn** <br/> |**Loại di chuyển** <br/> |**Điều gì sẽ di chuyển** <br/> |**Điều gì sẽ không di chuyển** <br/> |
|**Bất kỳ thiết bị chia sẻ tập tin hỗ trợ SMB 2,0 trở đi**  <br/> |Single hoặc Multi-Pass  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Cấp phép tệp và thư mục người dùng\*  <br/>  Quyền tập tin và thư mục cấp nhóm\*  <br/>  Tệp dưới 15 GB  <br/>  Siêu dữ liệu và thư mục cơ bản:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Tạo bởi  <br/>  Sửa đổi lần cuối bởi  <br/><br/> \**Cấu hình đồng bộ hóa thư mục yêu cầu. Chỉ quyền NTFS tiếp xúc với Windows File Explorer được di chuyển. Quyền quản lý trực tiếp trên thiết bị chia sẻ tệp không di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, tương đương NTFS quyền tiếp xúc với giao thức SMB được di chuyển.* <br/> | Lịch sử sở hữu và các phiên bản trước  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Thuộc tính tệp và cặp của Windows (như chỉ đọc và ẩn)  <br/>  Không-Windows công nghệ mới tệp hệ thống (NTFS) và NTFS nâng cao quyền và cài đặt đặc biệt:  <br/>  Rõ ràng từ chối quyền (loại bỏ sau khi di chuyển, nội dung đối  <br/>  NTFS kiểm tra cấu hình  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)  <br/>  Tài liệu không thể truy nhập hoặc bị hỏng  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (như quyền cấp cho cấp độ chia sẻ)  <br/>  Tệp hoặc cặp vượt quá giới hạn [và giới hạn SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Hộp (Starter, kinh doanh, doanh nghiệp)**  <br/> |Single hoặc Multi-Pass  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Quyền thư mục cấp người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Siêu dữ liệu và thư mục cơ bản:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Tạo bởi  <br/>  Sửa đổi lần cuối bởi  <br/>  Nội dung chia sẻ thuộc sở hữu tài khoản Box được di chuyển (nếu chia sẻ một cách rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo hộp để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và nhận xét <br/>  Quyền tập tin cấp người dùng  <br/>  Quyền tập tin cấp nhóm  <br/>  Mô tả tệp và cặp  <br/>  Hộp thẻ và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã trashed  <br/>  Tài liệu không thể truy nhập hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Hộp ghi chú (không có chức năng khi họ di chuyển mà không có chuyển đổi)  <br/>  Hộp ứng dụng, dấu trang, ưa chuộng và luồng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản hộp di chuyển (cặp chia sẻ)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc cặp vượt quá giới hạn [và giới hạn SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
   
FastTrack chuyên gia thực hiện như sau trong quá trình di chuyển: 
- Tiến hành một hội thảo Walkthrough di chuyển bao gồm các quá trình và phương pháp tiếp cận cho các kịch bản di chuyển đã chọn.
- Cung cấp điều kiện tiên quyết cho các công cụ đánh giá và di chuyển như áp dụng cho kịch bản.   
- Cung cấp điều kiện tiên quyết cho nhóm di chuyển truy cập vào môi trường nguồn và mục tiêu cho mục đích đánh giá và di chuyển. 
- Cung cấp các công cụ đánh giá để thực hiện việc thẩm định môi trường nguồn mục tiêu, hoặc cung cấp hướng dẫn về cách sử dụng các chức năng nền tảng nguồn gốc để tạo báo cáo đánh giá.   
- Hỗ trợ triển khai và chạy các công cụ đánh giá và di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho di chuyển nội dung (khi áp dụng).    
- Tiến hành di chuyển kiểm tra giới hạn để xác thực cơ sở hạ tầng di chuyển và điều kiện tiên quyết bắt buộc.   
- Cung cấp các trang web SharePoint trực tuyến mục tiêu out-of-Box là một phần của di chuyển.    
- Tiến hành một di chuyển thí điểm trước khi di chuyển vận tốc.   
- Cung cấp hướng dẫn về lịch trình di chuyển cho kịch bản đã chọn. 
- Tiến hành vận tốc di chuyển sóng của nội dung theo lịch trình di chuyển được cung cấp bởi khách hàng và xác nhận bởi FastTrack tài nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào các vấn đề di chuyển vận tốc phân loại và cung cấp hướng dẫn về các tùy chọn khắc phục tiềm năng.   
- Cung cấp báo cáo di chuyển cuối cùng cho mỗi cửa sổ di chuyển vận tốc.   
- Cung cấp hỗ trợ sau khi di chuyển trong quá trình kiểm tra người dùng chấp nhận tối đa năm ngày trước khi hoàn thành di chuyển.
    
Bạn thực hiện như sau trong quá trình di chuyển: 
- Cung cấp tài nguyên dự án được đề xuất cho hoạt động đánh giá và di chuyển. Chúng bao gồm: 
  - Quản lý dự án. 
  - Kiểm tra chấp nhận người dùng (UAT).  
  - Quản trị viên chịu trách nhiệm cho nền tảng nội dung nguồn và mục tiêu.  
- Cung cấp cơ sở hạ tầng điều kiện tiên quyết cho hoạt động đánh giá và di chuyển (nếu cần).  
- Cung cấp quyền truy cập và cho phép các môi trường nguồn và mục tiêu để FastTrack chuyên gia thực hiện các hoạt động di chuyển (nếu cần thiết).
    > [!NOTE]
    > Di chuyển chỉ sử dụng tài khoản tuân theo yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản này, bạn có thể gặp sự chậm trễ di chuyển. 
- Cung cấp điều kiện tiên quyết và thực hiện các hoạt động cần thiết để hỗ trợ đánh giá và di chuyển.   
- Cài đặt các công cụ đánh giá cung cấp FastTrack và hoàn thành đánh giá dữ liệu thu thập các hoạt động (nếu có).   
- Cài đặt phần mềm FastTrack cung cấp di chuyển tại chỗ (nếu có).   
- Hoàn thành các hoạt động khắc phục được nêu trong báo cáo khắc phục FastTrack cung cấp (nếu có).  
- Cung cấp lịch trình di chuyển sử dụng các mẫu và hướng dẫn FastTrack.   
- Tiến hành đảm bảo chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Tiến hành khắc phục di chuyển sau di chuyển (nếu có).
- Lập kế hoạch và thực hiện thay đổi quản lý và thông tin người dùng cuối (nếu có).   
- Quản trị và cấu hình bất kỳ thay đổi hệ thống nguồn và thiết bị cần thiết để hoàn thành công việc đánh giá và di chuyển hoạt động.
- Cung cấp một lịch trình theo một phương pháp được xác định và một danh sách các dữ liệu người dùng cụ thể để di chuyển cho mỗi sự kiện di chuyển ít nhất bảy (7) ngày trước.
- Thả dữ liệu người dùng từ lịch trình cho đến 24 giờ trước lô di chuyển. Điều này sẽ tương ứng với lô di chuyển cuối cùng.
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp.
    
## <a name="migration-to-onedrive-for-business"></a>Di chuyển sang OneDrive dành cho doanh nghiệp

 ### <a name="enable-to-migrate"></a>Bật để di chuyển
  
Nếu bạn sử dụng Microsoft để di chuyển dữ liệu của bạn, chúng tôi cung cấp hướng dẫn để kích hoạt cả OneDrive cho doanh nghiệp và môi trường nguồn để di chuyển. Tùy thuộc vào nguồn, chúng tôi có thể thực hiện các bước kích hoạt khác nhau. Chúng tôi giúp bạn với một số hoạt động bằng cách sử dụng kết hợp các công cụ, tài liệu và hướng dẫn và thực hiện các tác vụ cấu hình nếu áp dụng và khả thi.
  
Bạn có thể cần cung cấp quyền truy cập và quyền thích hợp cho Microsoft để thực hiện một số hoạt động. Nếu bạn không cung cấp quyền truy cập và/hoặc quyền, bạn cần phải thực hiện một số tác vụ được xác định chính mình với hướng dẫn từ Microsoft. 
  
### <a name="migration-policy-and-steps"></a>Chính sách và bước di chuyển
  
> [!NOTE]
> Một khe thời gian di chuyển cũng được gọi là lô di chuyển.

#### <a name="commercial-and-uk-government"></a>Chính phủ thương mại và Vương Quốc Anh

Di cư được thực hiện trên một các tiêu chuẩn 24 giờ một ngày, bảy (7) ngày làm việc một tuần (24x7) trong các khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển.

#### <a name="us-governmentdod"></a>Chính phủ Hoa Kỳ/DOD

Di cư được thực hiện trên các tiêu chuẩn 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5) trong khe thời gian di chuyển được xác định trước. Có ba lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 2:00AM giờ phối hợp (UTC) đến nửa đêm thứ sáu UTC. Điều này có nghĩa là di chuyển theo lịch trình cuối cùng là thứ sáu 8:00 PM UTC.

#### <a name="germany-microsoft-cloud-deutschland-mcd"></a>Đức Microsoft Cloud Deutschland (MCD)

Di cư được thực hiện trên tiêu chuẩn hóa các 9 giờ một ngày, năm (5) ngày làm việc một tuần (9x5) cơ sở trong khe thời gian di chuyển được xác định trước. Có một lô di chuyển cho mỗi ngày di chuyển. Có năm ngày di chuyển trong một tuần từ thứ hai 12:00PM UTC đến thứ sáu 21:00PM UTC.
    
- Di chuyển tất cả yêu cầu truy cập và quyền thích hợp cho môi trường nguồn.   
- Di chuyển tất cả đều phải tuân theo OneDrive cho doanh nghiệp hạn ngạch được nêu trong [SharePoint trực tuyến và onedrive cho doanh nghiệp: ranh giới phần mềm](https://go.microsoft.com/fwlink/?LinkId=698855).
    
 ### <a name="end-state"></a>Trạng thái kết thúc
  
Trạng thái kết thúc dự kiến sau khi lô di chuyển bao gồm:  
- Dữ liệu từ các nguồn đã lên lịch và đủ điều kiện phù hợp trong môi trường nguồn được di chuyển sang OneDrive for Business.  
- Báo cáo sau di chuyển cho lô di chuyển được cung cấp bởi Microsoft.
    
Trạng thái kết thúc dự kiến sau khi tất cả di chuyển hoàn tất bao gồm:
- Dữ liệu từ các nguồn đủ điều kiện được di chuyển sang Office 365 như được xác định trong bảng sau.  
- Loại dữ liệu được di chuyển phụ thuộc vào môi trường nguồn như được mô tả trong bảng sau.
    
|||||
|:-----|:-----|:-----|:-----|
|**Môi trường nguồn**|**Loại di chuyển**|**Điều gì sẽ di chuyển**|**Điều gì sẽ không di chuyển**|
|**Môi trường G Suite đơn (chỉ dành cho Google Drive)**  <br/> |Single hoặc Multi-Pass  <br/> | Google Docs, Sheets và Slides (các tập tin được chuyển đổi sang định dạng văn phòng tương đương)  <br/>  Cấu trúc tập tin và thư mục  <br/>  Quyền thư mục cấp người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Siêu dữ liệu và thư mục cơ bản:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Tạo bởi  <br/>  Sửa đổi lần cuối bởi  <br/>  Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển (nếu chia sẻ rõ ràng với người dùng hoặc nhóm)  <br/> | Lịch sử sở hữu, các phiên bản trước và nhận xét  <br/>  Mô tả tệp và cặp, màu thư mục  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Quyền tập tin cấp người dùng  <br/>  Quyền tập tin cấp nhóm  <br/> Mục trashed  <br/>  Tài liệu không thể truy nhập hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Nội dung chia sẻ bên ngoài tổ chức của bạn  <br/>  Google Photos. Biểu mẫu, bản đồ và các ứng dụng được kết nối khác  <br/>  Bản vẽ của Google  <br/>  Tệp hoặc cặp vượt quá giới hạn [và giới hạn SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Bất kỳ thiết bị chia sẻ tập tin hỗ trợ SMB 2,0 trở đi**  <br/> |Single hoặc Multi-Pass  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Cấp phép tệp và thư mục người dùng\*  <br/>  Quyền tập tin và thư mục cấp nhóm\*  <br/>  Tệp dưới 15 GB  <br/>  Siêu dữ liệu và thư mục cơ bản:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Tạo bởi  <br/>  Sửa đổi lần cuối bởi  <br/> <br/>\**Cấu hình đồng bộ hóa thư mục yêu cầu. Chỉ quyền NTFS tiếp xúc với Windows File Explorer được di chuyển. Quyền quản lý trực tiếp trên thiết bị chia sẻ tệp không di chuyển. Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, tương đương NTFS quyền tiếp xúc với giao thức SMB được di chuyển.* <br/> | Lịch sử sở hữu và các phiên bản trước  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các phiên bản trước  <br/>  Thuộc tính tệp và cặp của Windows (như chỉ đọc và ẩn)  <br/>  Không-Windows công nghệ mới tệp hệ thống (NTFS) và NTFS nâng cao quyền và cài đặt đặc biệt:  <br/>  Rõ ràng từ chối quyền (loại bỏ sau khi di chuyển, nội dung đối  <br/>  NTFS kiểm tra cấu hình  <br/>  Siêu dữ liệu tệp bổ sung được cung cấp bởi FCI  <br/>  Tài liệu không thể truy nhập hoặc bị hỏng  <br/>  Chia sẻ ẩn  <br/>  Chia sẻ (như quyền cấp cho cấp độ chia sẻ)  <br/>  Tệp hoặc cặp vượt quá giới hạn [và giới hạn SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
|**Hộp (Starter, kinh doanh, doanh nghiệp)**  <br/> |Single hoặc Multi-Pass  <br/> | Tài liệu  <br/>  Cấu trúc tập tin và thư mục  <br/>  Quyền thư mục cấp người dùng  <br/>  Quyền thư mục cấp nhóm  <br/>  Tệp dưới 15 GB  <br/>  Siêu dữ liệu và thư mục cơ bản:  <br/>  Ngày tạo  <br/>  Ngày sửa đổi  <br/>  Tạo bởi  <br/>  Sửa đổi lần cuối bởi  <br/>  Nội dung chia sẻ thuộc sở hữu tài khoản Box được di chuyển (nếu chia sẻ một cách rõ ràng với người dùng hoặc nhóm)\*  <br/><br/> \**Sử dụng báo cáo hộp để xác định các tài khoản bên ngoài. Hướng dẫn người dùng cuối chia sẻ lại nội dung của họ sau khi di chuyển.* <br/> | Lịch sử sở hữu, các phiên bản trước và nhận xét  <br/>  Mô tả tệp và cặp  <br/>  Quyền tập tin cấp người dùng  <br/>  Quyền tập tin cấp nhóm  <br/>  Hộp thẻ và siêu dữ liệu nâng cao  <br/>  Thuộc tính khóa tệp  <br/>  Chuyển đổi các URL nhúng trong nội dung  <br/>  Các mục đã trashed  <br/>  Tài liệu không thể truy nhập hoặc bị hỏng  <br/>  Người dùng bị chặn hoặc không hoạt động  <br/>  Hộp ghi chú (không có chức năng khi họ di chuyển mà không có chuyển đổi)  <br/>  Hộp ứng dụng, dấu trang, ưa chuộng và luồng công việc  <br/>  Nội dung không thuộc sở hữu của tài khoản hộp di chuyển (cặp chia sẻ)  <br/>  Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài\*  <br/>  Tệp hoặc cặp vượt quá giới hạn [và giới hạn SharePoint Online](https://go.microsoft.com/fwlink/?linkid=846724) hiện tại <br/> |
   
FastTrack chuyên gia thực hiện như sau trong quá trình di chuyển:  
- Tiến hành một hội thảo Walkthrough di chuyển bao gồm các quá trình và phương pháp tiếp cận cho các kịch bản di chuyển đã chọn.   
- Cung cấp điều kiện tiên quyết cho các công cụ đánh giá và di chuyển như áp dụng cho kịch bản.  
- Cung cấp điều kiện tiên quyết cho nhóm di chuyển truy cập vào môi trường nguồn và mục tiêu cho mục đích đánh giá và di chuyển.   
- Cung cấp các công cụ đánh giá để thực hiện việc thẩm định môi trường nguồn mục tiêu, hoặc cung cấp hướng dẫn về cách sử dụng các chức năng nền tảng nguồn gốc để tạo báo cáo đánh giá.    
- Cung cấp một lịch trình theo một phương pháp được xác định và một danh sách các dữ liệu người dùng cụ thể để di chuyển cho mỗi sự kiện di chuyển ít nhất bảy (7) ngày trước.
- Thả dữ liệu người dùng từ lịch trình cho đến 24 giờ trước lô di chuyển. Điều này sẽ tương ứng với lô di chuyển cuối cùng.
- Hỗ trợ triển khai và chạy các công cụ đánh giá và di chuyển (nếu có).   
- Cấu hình cơ sở hạ tầng di chuyển để chuẩn bị cho di chuyển nội dung (khi áp dụng).    
- Tiến hành di chuyển kiểm tra giới hạn để xác thực cơ sở hạ tầng di chuyển và điều kiện tiên quyết bắt buộc.    
- Cung cấp mục tiêu out-of-the-Box OneDrive cho các trang web kinh doanh như là một phần của di chuyển.    
- Tiến hành một di chuyển thí điểm trước khi di chuyển vận tốc.
- Cung cấp hướng dẫn về lịch trình di chuyển cho kịch bản đã chọn.   
- Tiến hành vận tốc di chuyển sóng của nội dung theo lịch trình di chuyển được cung cấp bởi khách hàng và xác nhận bởi FastTrack tài nguyên.   
- Cung cấp kết quả di chuyển sau mỗi cửa sổ di chuyển.   
- Tham gia vào các vấn đề di chuyển vận tốc phân loại và cung cấp hướng dẫn về các tùy chọn khắc phục tiềm năng. 
- Cung cấp báo cáo di chuyển cuối cùng cho mỗi cửa sổ di chuyển vận tốc.   
- Cung cấp hỗ trợ sau khi di chuyển trong quá trình kiểm tra người dùng chấp nhận tối đa năm ngày trước khi hoàn thành di chuyển.
   
Bạn thực hiện như sau trong quá trình di chuyển:
- Cung cấp tài nguyên dự án được đề xuất cho hoạt động đánh giá và di chuyển. Chúng bao gồm:
  - Quản lý dự án.
  - Uat.
  - Quản trị viên chịu trách nhiệm cho nền tảng nội dung nguồn và mục tiêu.
- Cung cấp cơ sở hạ tầng điều kiện tiên quyết cho hoạt động đánh giá và di chuyển (nếu cần).   
- Cung cấp quyền truy cập và cho phép các môi trường nguồn và mục tiêu để FastTrack chuyên gia thực hiện các hoạt động di chuyển (nếu cần thiết).  
    > [!NOTE]
    > Di chuyển chỉ sử dụng tài khoản tuân theo yêu cầu bảo mật được xác định trong onboarding. Nếu bạn không sử dụng các tài khoản này, bạn có thể gặp sự chậm trễ di chuyển. 
- Cài đặt các công cụ đánh giá cung cấp FastTrack và hoàn thành đánh giá dữ liệu thu thập các hoạt động (nếu có).
- Cài đặt phần mềm FastTrack cung cấp di chuyển tại chỗ (nếu có).  
- Hoàn thành các hoạt động khắc phục được nêu trong báo cáo khắc phục FastTrack cung cấp (nếu có).   
- Cung cấp lịch trình di chuyển sử dụng các mẫu và hướng dẫn FastTrack. 
- Tiến hành đảm bảo chất lượng di chuyển và kiểm tra chấp nhận người dùng.   
- Tiến hành khắc phục di chuyển sau di chuyển (nếu có).  
- Lập kế hoạch và thực hiện thay đổi quản lý và thông tin người dùng cuối (nếu có).  
- Quản trị và cấu hình bất kỳ thay đổi hệ thống nguồn và thiết bị cần thiết để hoàn thành công việc đánh giá và di chuyển hoạt động.
    
> [!NOTE]
> Microsoft không thể đảm bảo tốc độ di chuyển tệp.  

