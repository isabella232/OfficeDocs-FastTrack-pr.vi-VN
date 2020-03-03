---
title: Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 3/03/2020
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: 'Di chuyển từ IBM Domino sang Exchange Online bao gồm một số khía cạnh quan trọng, bao gồm những gì xảy ra trong các giai đoạn sau:'
ms.openlocfilehash: ac945137e7beee0d0813ce171fc7292d683e9cd9
ms.sourcegitcommit: 79a5b31863be3d554223f75ca866dcf40dd2c2dd
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 03/02/2020
ms.locfileid: "42347582"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online

Di chuyển từ IBM Domino sang Exchange Online bao gồm một số khía cạnh quan trọng, bao gồm những gì xảy ra trong các giai đoạn sau: 
- [Bắt đầu giai đoạn](#initiate-phase)   
- [Đánh giá giai đoạn](#assess-phase)
- [Giai đoạn remediate](#remediate-phase)  
- [Kích hoạt giai đoạn](#enable-phase)  
- [Di chuyển giai đoạn](#migrate-phase)
    
## <a name="identities"></a>Danh tính

Bạn có trách nhiệm tạo và quản lý danh tính (chỉ dành cho đám mây, đồng bộ hóa hoặc liên kết với Active Directory tại chỗ của họ). Bạn phải hoàn tất việc ánh xạ danh tính (nếu chưa có) giữa domino và Active Directory tại chỗ hoặc Azure Active Directory trong giai đoạn đầu của bộ nhớ ngoài.
  
## <a name="coexistence"></a>Cùng tồn tại

Lợi ích Trung tâm FastTrack cho Office 365 cung cấp luồng thư hai chiều giữa môi trường Domino tại chỗ và Exchange Online cho tất cả khách hàng.
  
## <a name="migration"></a>Di chuyển

Quá trình chuẩn FastTrack Trung tâm di chuyển từ Domino sang Exchange Online bao gồm trước giai đoạn Domino dữ liệu Azure trước khi di chuyển hộp thư Exchange Online. Fasttrack di chuyển yêu cầu hoạt động được thực hiện ở các giai đoạn khác nhau của bộ nhớ ngoài của fasttrack Trung tâm nhân sự và bạn. Chúng tôi bao gồm các hoạt động này trong các phần sau.
  
> [!NOTE]
> Dữ liệu di chuyển qua các dịch vụ FastTrack có thể được truyền đến, lưu trữ và xử lý tại Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft duy trì cơ sở. Các dịch vụ FastTrack không được thiết kế hoặc dành cho dữ liệu theo yêu cầu pháp lý hoặc quy định đặc biệt. 
  
## <a name="initiate-phase"></a>Bắt đầu giai đoạn

 **Hành động chính**
  
- Xác định domino là nền tảng thư nguồn.   
- Xác định xem Trung tâm FastTrack thực hiện việc di chuyển.
    
 **Trách nhiệm của khách hàng**
  
- Cung cấp thông tin cơ bản về nền tảng nhắn tin nguồn và xác nhận mục đích di chuyển với FastTrack Center. 
- Tham gia vào một Walkthrough của các quy trình FastTrack Trung tâm lợi ích.  
- Ký thỏa thuận dịch vụ FastTrack.
    
## <a name="assess-phase"></a>Đánh giá giai đoạn

 **Hành động chính**
  
- Trung tâm FastTrack tiến hành một hội thảo di cư với khách hàng. 
- Bạn hoàn tất điều kiện tiên quyết di chuyển, như bảng câu hỏi di chuyển và cung cấp máy trạm quản trị.    
- Đánh giá di chuyển cho Domino được thực hiện trong môi trường tại chỗ của bạn.
    
 **Trách nhiệm của khách hàng**
  
- Cung cấp quản trị trạm làm việc Trung tâm FastTrack sử dụng để quản lý các nhiệm vụ bộ nhớ ngoài và di chuyển, như đánh giá, tạo bản sao, kiểm tra, thiết lập chuyển tiếp trong quá trình di chuyển, và như vậy.
    > [!NOTE]
    > Đánh giá là rất quan trọng để lập kế hoạch thành công và thực hiện di cư vận tốc. Nó được thực hiện bởi một kiến trúc sư di cư cần truy cập cụ thể vào môi trường Domino. Cấu phần máy trạm quản trị bắt buộc bao gồm một khách hàng ghi chú được cấu hình để truy cập tất cả các máy chủ thư Domino nguồn và bản sao Azure Domino dàn máy chủ. 
- Cung cấp cho nhóm di chuyển quyền truy cập từ xa vào máy trạm quản trị, tài khoản và quyền để thực hiện hoạt động đánh giá và di chuyển. Điều này bao gồm cung cấp nhiều tài khoản tại chỗ và Exchange Online với quyền quản trị cần thiết để di chuyển.    
- Mở cổng tường lửa. Cổng bên ngoài phải được mở giữa các nguồn máy chủ thư domino và máy chủ dàn Azure. Cổng khác để giao tiếp (như trạm làm việc quản trị viên, máy chủ Domino nguồn và máy chủ Exchange tại chỗ (nếu có)) cũng phải được mở. 
- Kích hoạt chứng nhận chéo giữa các nguồn môi trường domino và Azure Domino dàn máy chủ để tạo điều kiện nhân bản. Các tác vụ chứng nhận chéo được phối hợp giữa quản trị viên Domino của khách hàng và Trung tâm FastTrack.  
- Hoàn tất bảng câu hỏi di chuyển, ghi lại thông tin cần thiết để định cấu hình môi trường di chuyển trong Azure (như công cụ, tập lệnh và máy chủ di chuyển).   
- Đảm bảo mục tiêu hộp thư trong Office 365 có giao thức nhắn tin ứng dụng chương trình giao diện (MAPI) cho phép.  
> [!NOTE]
> Một số gói Office 365 không hỗ trợ giao thức MAPI. Để di chuyển dữ liệu, hộp thư từ các kế hoạch này cần được chuyển đổi sang một kế hoạch hỗ trợ MAPI trước sự kiện di chuyển. Sau di chuyển, các kế hoạch này có thể được thay đổi trở lại. 
  
## <a name="remediate-phase"></a>Giai đoạn remediate

 **Hành động chính**
  
- Trung tâm FastTrack nhận xét báo cáo đánh giá di chuyển và kiểm tra các chi tiết mà bạn cung cấp bằng cách sử dụng bảng câu hỏi.   
- Các mục khắc phục được đề xuất bởi Trung tâm FastTrack phải được hoàn thành bởi bạn.
    
 **Trách nhiệm của khách hàng**
  
- Remediate môi trường Domino dựa trên hướng dẫn mà FastTrack Trung tâm cung cấp (ví dụ, thiết lập bất kỳ quyền cần thiết được xác định là thiếu trong các tập tin thư).  
- Đảm bảo rằng hộp thư Domino dưới kích thước tối đa được phép thông qua di chuyển.
    > [!NOTE]
    >  Mặc dù FastTrack di chuyển hộp thư lên đến 85% Tổng kích thước mục tiêu cho phép, cố gắng nhập các hộp thư lớn hơn 2 GB mang các rủi ro bổ sung như:    <br/> Kéo dài thời gian di chuyển.    <br/> Sử dụng tài nguyên khác được sử dụng để di chuyển các hộp thư khác.    <br/> Một sự tăng đáng kể tỷ lệ lỗi. 
- Chuẩn bị thư trong cơ sở dữ liệu và danh sách kiểm soát truy cập (ACLs) để di chuyển. Bạn phải thực hiện một số bước khắc phục thành công di chuyển thư trong cơ sở dữ liệu và quyền truy nhập vào hộp thư dùng chung trong Exchange Online. Một vài trong số các bước này là như sau: 
  - Loại bỏ hiện có thư trong cơ sở dữ liệu mục trong thư mục domino và tạo hồ sơ người mới.
  - Tạo nhóm bảo mật phổ quát kích hoạt thư trong Active Directory tại chỗ được đồng bộ hoá với Office 365 Azure Active Directory và được sử dụng để cấu hình quyền truy cập vào hộp thư dùng chung trong Exchange Online. Điều này chuyển quyền đặt trên cơ sở dữ liệu thư trong hộp thư dùng chung trong Exchange Online.
    
> [!NOTE]
> Người dùng cuối sẵn sàng và đào tạo cho hệ thống nhắn tin mới và khách hàng có thể được bắt đầu ngay bây giờ. 
  
## <a name="enable-phase"></a>Kích hoạt giai đoạn

 **Hành động chính**
  
- Trung tâm FastTrack: 
    - Thiết lập môi trường di chuyển trong Azure.  
    - Cấu hình công cụ di chuyển trên trạm làm việc quản trị tại chỗ. 
    - Cấu hình và giải thích cách sử dụng công cụ Auto-Import.  
    - Tiến hành xác nhận của tất cả các thành phần di chuyển và thực hiện kiểm tra di cư.
    
 **Trách nhiệm của khách hàng**
  
- Nhân viên phụ trách di chuyển hộp thư lên lịch phải hiểu cách sử dụng công cụ nhập tự động. Bạn sử dụng công cụ này để nhập lịch di chuyển vào cơ sở dữ liệu lập kế hoạch Trung tâm FastTrack sử dụng để thực hiện các hoạt động trước khi di chuyển. 
- Thực hiện các hoạt động trước khi di cư như nhập lịch sử dụng, phân tích báo cáo kiểm toán, khắc phục bất kỳ vấn đề, và nhập lại tài khoản người dùng có vấn đề.
    
Các hoạt động trước khi di chuyển được phối hợp giữa bạn và Trung tâm FastTrack. Sao chép vào Azure bắt đầu sau khi di chuyển người dùng lịch được nhập. 
    
> [!NOTE]
> Thời gian cần thiết để tái tạo phụ thuộc vào lượng dữ liệu. Trung tâm FastTrack sau đó thực hiện kiểm tra để xác định sự sẵn sàng di chuyển. Kết quả kiểm tra được cung cấp cho bạn với sự hiểu biết rằng việc khắc phục sau đó thường được yêu cầu. Tất cả các bước này được gọi là các hoạt động "T-Minus" vì họ phải bắt đầu trước việc di chuyển theo lịch trình của người dùng. 
  
## <a name="migrate-phase"></a>Di chuyển giai đoạn

 **Hành động chính**
  
- Trung tâm FastTrack:
    - Thực hiện thí điểm và vận tốc di chuyển.  
    - Thực hiện các sự kiện di chuyển và T-Minus hoạt động.
    - Cung cấp hỗ trợ sau di chuyển.
    
 **Trách nhiệm của khách hàng**
  
- Xác định và nhập lịch trình di chuyển 21 ngày trước khi di chuyển.
    > [!NOTE]
    > Nhiệm vụ này là rất quan trọng vì các hoạt động trước khi di chuyển liên quan đến việc khắc phục và có thể thử lại tạo bản sao ở các giai đoạn khác nhau trước ngày di chuyển thực tế (T-0). Trong khi một số hộp thư đang di chuyển, T-trừ hoạt động đang được thực hiện trên những người khác. Điều này làm cho kế hoạch đúng đắn và phối hợp phải. 
- Khắc phục sự cố được xác định trong các hoạt động T-trừ.
- Địa chỉ và khắc phục bất kỳ vấn đề máy chủ Domino ảnh hưởng đến hoạt động di chuyển. 
- Tiến hành truyền thông người dùng cuối về ngày di chuyển sắp tới.
- Tiến hành các hoạt động sẵn sàng cho người dùng cuối và đào tạo cho hệ thống nhắn tin mới và khách hàng.   
- Xác định và báo cáo sự cố sau di chuyển. Trung tâm FastTrack cung cấp hỗ trợ sau khi di chuyển đến T + 5 ngày sau khi di chuyển, sau đó nó sẽ trở thành trách nhiệm của bạn. Bạn có thể đăng nhập các vé sau di chuyển cho các vấn đề như thiếu email, mục lịch và danh bạ hoặc cho các bản sao trong hộp thư.
    
Trung tâm FastTrack không bao gồm việc triển khai, lệ phí giấy phép, hoặc hỗ trợ liên quan đến chuẩn bị thư mục (bao gồm Domino-to-Active Directory đồng bộ hóa thư mục), cùng tồn tại phần mềm tiện ích cho ghi chú ứng dụng tương tác, di chuyển tự dịch vụ hoặc di chuyển lưu trữ.
  

  

