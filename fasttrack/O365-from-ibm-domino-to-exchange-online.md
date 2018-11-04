---
title: Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/2/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'Di chuyển từ IBM Domino để trao đổi trực tuyến bao gồm một vài khía cạnh quan trọng, bao gồm cả những gì sẽ xảy ra vào giai đoạn sau đây:'
ms.openlocfilehash: ed901d469d699f081f2ee2726b9e9b94e94cb3df
ms.sourcegitcommit: a8717ee240040292872bc0231f1fb2a22b846806
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/01/2018
ms.locfileid: "25895685"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a>Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online

Di chuyển từ IBM Domino để trao đổi trực tuyến bao gồm một vài khía cạnh quan trọng, bao gồm cả những gì sẽ xảy ra vào giai đoạn sau đây: 
- [Bắt đầu giai đoạn](#initiate-phase)   
- [Đánh giá giai đoạn](#assess-phase)
- [Remediate giai đoạn](#remediate-phase)  
- [Sử giai đoạn](#enable-phase)  
- [Di chuyển giai đoạn](#migrate-phase)
    
## <a name="identities"></a>Danh tính

Bạn chịu trách nhiệm cho việc tạo và quản lý danh tính (đám mây duy nhất, đồng bộ, hoặc được liên kết với Active Directory tại chỗ của họ). Bạn phải hoàn thành lập bản đồ nhận dạng (nếu không đã trình bày) giữa Domino và Active Directory tại chỗ hoặc Azure AD trong giai đoạn đầu của onboarding.
  
## <a name="coexistence"></a>Cùng tồn tại

Lợi ích Trung tâm FastTrack cho Office 365 cung cấp hai chiều luồng thư giữa các môi trường Domino tại chỗ và Exchange Online cho mọi khách hàng.
  
## <a name="migration"></a>Di chuyển

Quá trình FastTrack Trung tâm tiêu chuẩn cho di chuyển từ Domino để trao đổi trực tuyến liên quan đến trước dàn Domino dữ liệu Azure trước khi di chuyển đến hộp thư Exchange Online. Di cư FastTrack yêu cầu hoạt động được thực hiện ở các giai đoạn khác nhau của onboarding của nhân viên Trung tâm FastTrack và bạn. Chúng tôi bao gồm các hoạt động này trong các phần sau.
  
> [!NOTE]
> Dữ liệu di chuyển qua FastTrack dịch vụ có thể được chuyển đến, lưu trữ và xử lý tại Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft vẫn duy trì các tiện nghi. Dịch vụ FastTrack không được thiết kế hoặc thiết kế cho dữ liệu đặc biệt yêu cầu pháp lý hoặc theo quy định. 
  
## <a name="initiate-phase"></a>Bắt đầu giai đoạn

 **Hành động quan trọng**
  
- Xác định các Domino như là nền tảng thư nguồn.   
- Xác định cho dù Trung tâm FastTrack thực hiện việc di chuyển.
    
 **Trách nhiệm của khách hàng**
  
- Cung cấp các thông tin cơ bản về nền tảng tin nhắn mã nguồn, và xác nhận ý định di chuyển với Trung tâm FastTrack. 
- Tham gia vào một hướng các quá trình FastTrack Trung tâm lợi ích.  
- Ký thỏa thuận dịch vụ FastTrack.
    
## <a name="assess-phase"></a>Đánh giá giai đoạn

 **Hành động quan trọng**
  
- Trung tâm FastTrack tiến hành một hội thảo di chuyển với khách hàng. 
- Bạn hoàn thành điều kiện tiên quyết di chuyển như các câu hỏi di chuyển và cung cấp các admin máy trạm.    
- Di chuyển đánh giá cho các Domino được thực hiện trong môi trường tại chỗ của bạn.
    
 **Trách nhiệm của khách hàng**
  
- Cung cấp tài khoản admin máy trạm làm việc Trung tâm FastTrack sử dụng để quản lý tác vụ onboarding và di chuyển, như đánh giá, sáng tạo bản sao, kiểm định, thiết lập chuyển tiếp trong thời gian di chuyển, và như vậy.
    > [!NOTE]
    > Đánh giá là rất quan trọng cho thành công kế hoạch và thực hiện vận tốc di chuyển. Nó được thực hiện bởi một kiến trúc sư di chuyển những người cần truy cập cụ thể đến môi trường Domino. Yêu cầu admin máy trạm thành phần bao gồm một khách hàng ghi chú cấu hình để truy cập vào tất cả các máy chủ mail Domino nguồn và bản sao Azure Domino dàn máy chủ. 
- Cung cấp di chuyển đội truy cập từ xa để quản trị máy trạm, tài khoản và quyền để thực hiện các hoạt động đánh giá và di chuyển. Điều này bao gồm cung cấp nhiều tài khoản tại chỗ và trong Exchange Online với quyền quản trị cần thiết để di chuyển.    
- Cổng mở tường lửa. Cổng ra bên ngoài phải được mở giữa các máy chủ thư Domino nguồn và dàn dựng server Azure. Các cảng khác để liên lạc (như admin máy trạm, nguồn Domino máy chủ, và trao đổi máy chủ tại chỗ (nếu có)) phải cũng phải được mở. 
- Cho phép cấp giấy chứng nhận chéo giữa môi trường Domino nguồn và Azure Domino dàn máy chủ để tạo điều kiện mở rộng. Cross-chứng nhận nhiệm vụ phải phối hợp giữa các khách hàng Domino admin và Trung tâm FastTrack.  
- Hoàn thành bảng câu hỏi di trú, nắm bắt thông tin cần thiết để cấu hình môi trường di chuyển trong Azure (như công cụ, kịch bản và di chuyển máy chủ).   
- Đảm bảo mục tiêu các hộp thư trong Office 365 có giao thức nhắn tin ứng dụng chương trình giao diện (MAPI) được kích hoạt.  
> [!NOTE]
> Một số kế hoạch Office 365 không hỗ trợ giao thức MAPI. Để di chuyển dữ liệu, hộp thư từ những kế hoạch này cần phải được chuyển đổi sang một kế hoạch hỗ trợ MAPI trước các sự kiện di chuyển. Sau khi di chuyển, các kế hoạch này có thể được thay đổi trở lại. 
  
## <a name="remediate-phase"></a>Remediate giai đoạn

 **Hành động quan trọng**
  
- Trung tâm FastTrack đánh giá báo cáo đánh giá di chuyển và kiểm tra các chi tiết mà bạn cung cấp bằng cách sử dụng các câu hỏi.   
- Túc mục được đề xuất bởi Trung tâm FastTrack phải được hoàn thành bởi bạn.
    
 **Trách nhiệm của khách hàng**
  
- Remediate môi trường Domino dựa trên nguyên tắc Trung tâm FastTrack cung cấp (ví dụ, thiết lập bất kỳ điều khoản yêu cầu được xác định là mất tích trong các tập tin thư).  
- Đảm bảo rằng hộp thư Domino dưới kích thước tối đa cho phép thông qua di chuyển.
    > [!NOTE]
    >  Mặc dù FastTrack di chuyển hộp thư đến 85% của tổng số cho phép nhắm mục tiêu kích thước, cố gắng để di chuyển hộp thư lớn hơn 2 GB mang các rủi ro bổ sung như:    <br/> Kéo dài thời gian của quá trình di chuyển.<br/> Sử dụng các nguồn tài nguyên khác được sử dụng để di chuyển các hộp thư khác.<br/> Sự gia tăng đáng kể trong tỷ lệ lỗi. 
- Chuẩn bị các thư trong cơ sở dữ liệu và kiểm soát truy cập danh sách (ACLs) cho di chuyển. Bạn phải thực hiện một số bước khắc phục thành công di chuyển thư trong cơ sở dữ liệu và quyền của mình để một hộp thư dùng chung trong Exchange Online. Một vài trong số các bước này là như sau: 
  - Loại bỏ các mục thư trong cơ sở dữ liệu hiện có trong thư mục Domino và tạo hồ sơ người mới.
  - Tạo nhóm bảo mật phổ quát kích hoạt thư trong Active Directory tại chỗ được đồng bộ hoá với Office 365 Azure quảng cáo và sử dụng để đặt cấu hình quyền truy cập vào hộp thư dùng chung trong Exchange Online. Này chuyển các quyền thiết lập trên cơ sở dữ liệu thư ở trên vào hộp thư dùng chung trong Exchange Online.
    
> [!NOTE]
> Người dùng cuối chuẩn bị sẵn sàng và đào tạo cho hệ thống mới nhắn tin và khách hàng có thể được bắt đầu bây giờ. 
  
## <a name="enable-phase"></a>Sử giai đoạn

 **Hành động quan trọng**
  
- Trung tâm FastTrack: 
    - Thiết lập môi trường di chuyển trong Azure.  
    - Cấu hình công cụ di chuyển trên máy trạm admin tại chỗ. 
    - Cấu hình và chứng tỏ làm thế nào để sử dụng công cụ tự động nhập khẩu.  
    - Tiến hành xác nhận tất cả các thành phần di chuyển và thực hiện kiểm tra quá trình di chuyển.
    
 **Trách nhiệm của khách hàng**
  
- Nhân sự của bạn phụ trách lập kế hoạch di chuyển hộp thư phải hiểu làm thế nào để sử dụng công cụ tự động nhập khẩu. Bạn sử dụng công cụ này để nhập lịch trình di chuyển vào cơ sở dữ liệu lập kế hoạch Trung tâm FastTrack sử dụng để thực hiện các hoạt động trước khi di chuyển. 
- Thực hiện các hoạt động trước khi di chuyển như nhập khẩu sử dụng lịch trình, phân tích các báo cáo kiểm toán, remediating bất kỳ vấn đề và reimporting tài khoản người dùng với các vấn đề.
    
Trước khi di chuyển hoạt động được phối hợp giữa bạn và Trung tâm FastTrack. Sao chép vào Azure bắt đầu sau khi lịch trình di chuyển của người dùng được nhập khẩu. 
    
> [!NOTE]
> Thời gian cần thiết để tái tạo phụ thuộc vào lượng dữ liệu. Trung tâm FastTrack sau đó thực hiện kiểm toán để xác định sự sẵn sàng di chuyển. Kết quả kiểm tra được cung cấp cho bạn với sự hiểu biết mà khắc phục sau đó được yêu cầu bình thường. Tất cả các bước được gọi là "T-trừ" hoạt động bởi vì họ phải bắt đầu trước di chuyển theo lịch trình của người dùng. 
  
## <a name="migrate-phase"></a>Di chuyển giai đoạn

 **Hành động quan trọng**
  
- Trung tâm FastTrack:
    - Thực hiện thí điểm và tốc độ di chuyển.  
    - Thực hiện di chuyển các sự kiện và hoạt động T-trừ.
    - Cung cấp hỗ trợ sau khi di chuyển.
    
 **Trách nhiệm của khách hàng**
  
- Xác định và nhập khẩu di chuyển lịch 21 ngày trước khi di chuyển.
    > [!NOTE]
    > Nhiệm vụ này là rất quan trọng bởi vì các hoạt động di chuyển tiền liên quan đến khắc phục và retries có thể tạo ra bản sao ở các giai đoạn khác nhau trước ngày di cư thực tế (T-0). Trong khi một số hộp thư di chuyển, T-trừ các hoạt động đang được thực hiện trên những người khác. Điều này làm cho đúng kế hoạch và phối hợp phải. 
- Khắc phục sự cố được xác định trong thời gian T-trừ các hoạt động.
- Giải quyết và sửa chữa bất kỳ Domino server các vấn đề ảnh hưởng đến các hoạt động di chuyển. 
- Tiến hành các thông tin liên lạc của người dùng cuối về ngày di cư sắp tới.
- Tiến hành các hoạt động sẵn sàng chiến đấu của người dùng cuối và đào tạo cho hệ thống mới nhắn tin và khách hàng.   
- Xác định và báo cáo các vấn đề sau khi di chuyển. Trung tâm FastTrack cung cấp hỗ trợ sau khi di chuyển đến T + 5 ngày sau khi di chuyển, sau đó nó sẽ trở thành trách nhiệm của bạn. Bạn có thể đăng nhập sau khi di chuyển vé cho các vấn đề như mất email, các mục lịch và danh bạ, hoặc bản sao trong hộp thư.
    
Trung tâm FastTrack không bao gồm việc triển khai, học phí giấy phép, hoặc hỗ trợ liên quan đến chuẩn bị thư mục (bao gồm cả đồng bộ hoá thư mục đang hoạt động Domino Directory), cùng tồn tại phần mềm tiện ích cho khả năng tương tác ứng dụng ghi chú, tự phục vụ di chuyển hoặc di chuyển lưu trữ.
  

  

