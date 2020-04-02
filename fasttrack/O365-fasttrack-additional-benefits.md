---
title: Phụ lục B - Lợi ích bổ sung của Trung tâm FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 4/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Priority
description: Khách hàng mua ít nhất 20.000 giấy phép cho một đối tượng thuê Exchange Online đủ điều kiện cho các dịch vụ bổ sung của FastTrack Center. Xem các dịch vụ và gói cước đủ điều kiện để biết thêm chi tiết.
ms.openlocfilehash: 1317992820ba385e70ccb5908c0eab3a2dd7c140
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/01/2020
ms.locfileid: "43098188"
---
# <a name="appendix-b---fasttrack-center-additional-benefit"></a>Phụ lục B - Lợi ích bổ sung của Trung tâm FastTrack

Khách hàng mua ít nhất 20.000 giấy phép cho một đối tượng thuê Exchange Online đủ điều kiện cho các dịch vụ bổ sung của FastTrack Center. Xem [các dịch vụ và gói cước đủ điều kiện](M365-eligible-services-and-plans.md) để biết thêm chi tiết. 
  
## <a name="onboarding-and-migration-phases"></a>Giai đoạn onboarding và di chuyển

## <a name="core"></a>Lõi

Lõi bộ nhớ ngoài Dịch vụ bổ sung bao gồm cấu hình hướng dẫn địa lý dự phòng Active Directory liên kết dịch vụ (AD FS) và AD FS khách hàng truy cập chính sách cho dịch vụ. 
  
## <a name="exchange-online"></a>Trao đổi trực tuyến

Đối với Exchange Online, chúng tôi cung cấp hướng dẫn cấu hình sau:
- Thiết lập nhắn tin hợp nhất (UM) với Exchange Online.
- Cấu hình cùng tồn tại giữa Exchange Online và thư mục công cộng tại chỗ hợp lệ.
- Tích hợp ứng dụng kích hoạt thư. 
- Di chuyển hộp thư lập kế hoạch và nhóm.
    
## <a name="skype-for-business-online"></a>Skype cho doanh nghiệp trực tuyến

Cho Skype dành cho doanh nghiệp trực tuyến, chúng tôi cung cấp hướng dẫn trên cơ sở Lync và Skype dành cho người dùng doanh nghiệp di chuyển sang Skype dành cho doanh nghiệp trực tuyến.
  
## <a name="office-365-proplus"></a>Văn phòng 365 ProPlus

Đối với Office 365 ProPlus, chúng tôi cung cấp hướng dẫn sau: 
- Đánh giá và lập kế hoạch tập trung vào việc chuẩn bị môi trường của bạn để triển khai và quản lý ban đầu các bản Cập Nhật phù hợp với các phương pháp hay nhất của Microsoft. 
- Phát triển triển khai cấu hình và Cập Nhật cài đặt bằng cách sử dụng công cụ triển khai Office 365 và công cụ Tuỳ chỉnh Office. 
- Triển khai bao bì bằng cách sử dụng trình quản lý cấu hình Endpoint Microsoft.  
- Cho phép sử dụng bộ công cụ sẵn sàng cho Office để xác định các vấn đề tương thích tiềm năng với Microsoft Visual Basic for Applications (VBA) macro và trình bổ sung mà bạn sử dụng với Office.
    
## <a name="fasttrack-responsibilities"></a>Các trách nhiệm của FastTrack

FastTrack chuyên gia có trách nhiệm sau đây trong onboarding. Đây có thể là thêm vào hoặc thay thế các hoạt động được định nghĩa trong [FastTrack trách nhiệm](O365-fasttrack-responsibilities.md).
  
## <a name="general"></a>Chung

- Cung cấp hỗ trợ từ xa cho bạn trong việc lập kế hoạch thành công phát triển, thực hiện và các hoạt động cấu hình yêu cầu như chi tiết trong [giai đoạn Onboarding và di chuyển](#onboarding-and-migration-phases).
    
## <a name="assess-phase"></a>Đánh giá giai đoạn

- Giữ một cuộc gọi lập kế hoạch thành công để cung cấp hướng dẫn cho việc áp dụng thành công. 
- Đánh giá môi trường của bạn để hỗ trợ cấu hình AD FS dư địa lý.  
- Chạy một đánh giá để xác định các yêu cầu của bạn cho AD FS truy cập máy khách.
    
## <a name="enable-phase"></a>Kích hoạt giai đoạn

### <a name="geo-redundant-ad-fs-guidance"></a>Hướng dẫn địa lý dự phòng AD FS

- Cung cấp thiết kế kiến trúc tham chiếu chuẩn cho topo AD FS dự trữ địa lý bao trùm hai trung tâm dữ liệu (2). Kiến trúc tiêu chuẩn cung cấp cho:
  - Xác thực liên kết cho các dịch vụ trong phạm vi cho các FastTrack Trung tâm lợi ích. 
  - Duy nhất trang web khả năng phục hồi.  
  - Tính khả dụng cao và chuyển đổi dự phòng.  
  - Định cỡ hướng dẫn. 
- Cung cấp hướng dẫn về cách sử dụng cơ sở dữ liệu nội bộ của Windows và SQL Server là phiên bản cơ sở dữ liệu cho nhóm AD FS.   
- Xác nhận việc thiết lập xác thực liên kết cho mỗi nhóm trong phạm vi.  
- Xác nhận chức năng xác thực liên kết cho tối đa 10 người dùng.
    
> [!NOTE]
> Triển khai AD FS trong phạm vi cho lợi ích bổ sung khách hàng đủ điều kiện với nhiều cấu hình nhóm Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Hướng dẫn chính sách truy cập máy khách AD FS

- Đánh giá các chính sách và cấu hình cần thiết để bảo mật tài nguyên Office 365.  
- Cung cấp hướng dẫn và hỗ trợ cấu hình chính sách truy cập máy khách AD FS để xác định các tình huống truy cập máy khách trong ranh giới của các tình huống được hỗ trợ. Để biết thêm thông tin, hãy xem [hạn chế quyền truy cập vào Office 365 dịch vụ dựa trên vị trí của khách hàng](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Xác nhận chức năng xác thực liên kết với sửa đổi khách hàng truy cập chính sách trường hợp truy cập được xác định với cấu hình tối đa 10 người dùng.
    
## <a name="exchange-online"></a>Trao đổi trực tuyến

### <a name="exchange-unified-messaging-guidance"></a>Hướng dẫn trao đổi Unified Messaging

- Cung cấp hướng dẫn về cấu hình yêu cầu trên Exchange Online để cho phép lên đến 10: 
  - Kế hoạch quay số UM.   
  - Chính sách hộp thư UM. 
  - Tổng đài tự động.  
- Cung cấp hướng dẫn cho Lync tại chỗ hoặc Skype cho cấu hình môi trường kinh doanh để kích hoạt UM và đặc biệt nhắm mục tiêu:  
  - Exchange Online-lưu trữ chính sách.  
  - Chính sách thư thoại đã lưu trữ trên Exchange Online. 
  - Liên hệ tham dự tự động UM và thư thoại Outlook để chuyển hướng người dùng sang Exchange Online. 
  - Hỗ trợ việc tạo bản ghi vị trí dịch vụ (SRV) là bắt buộc đối với liên kết.
> [!NOTE]
> UM có thể được cấu hình với cổng IP UM được hỗ trợ và bộ điều khiển viền phiên (SBC). Để biết thêm thông tin, xem [tích hợp hệ thống điện thoại với UM](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Thư mục chung cùng tồn tại hướng dẫn

- Cung cấp hướng dẫn trên cùng một thư mục công cộng cây cùng tồn tại, bao gồm:  
  - Thư mục công cộng chuẩn bị trong Exchange 2007, Exchange 2010 và Exchange 2013. 
  - Cấu hình Exchange Online để chuyển thư mục công cộng truy cập vào thư mục công cộng tại chỗ.  
  - Cấu hình truy cập vào thư mục công cộng từ Exchange Online một Exchange 2007, Exchange 2010, hoặc môi trường Exchange 2013 tại chỗ.  
  - Hỗ trợ truy cập xác nhận môi trường thư mục công cộng cho tối đa 10 người dùng trong Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Hướng dẫn tích hợp ứng dụng kích hoạt thư

- Cung cấp các mẫu hướng dẫn cho:  
  - Các ứng dụng gửi thư hàng loạt.  
  - Ứng dụng tuyến email thông qua Exchange.  
  - Ứng dụng sử dụng hộp thư Exchange.  
  - Ứng dụng yêu cầu bên thứ ba hoặc tuỳ chỉnh cấu phần được cài đặt trên máy chủ Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Lập kế hoạch di chuyển hộp thư và nhóm

- Cung cấp hướng dẫn trong việc tạo kế hoạch di chuyển, bao gồm:  
  - Nhóm người dùng và tài nguyên theo lô.
  - Phối hợp triển khai các gói phần mềm cần thiết với các lô di chuyển.   
  - Hướng dẫn tạo ra một kế hoạch giao tiếp cho người dùng cuối. 
  - Điều phối kích thước lô di chuyển, tỷ lệ lỗi, và hỗ trợ bộ phận dự kiến. 
- Cung cấp hướng dẫn trong nhóm hộp thư người dùng và tài nguyên trong lô theo loại, chức năng kinh doanh và ủy quyền truy cập Dựa trên thông tin liên quan được cung cấp bởi khách hàng.
    
## <a name="skype-for-business-online"></a>Skype cho doanh nghiệp trực tuyến

- Cung cấp hướng dẫn về di chuyển người dùng theo lô trong Skype để triển khai kết hợp doanh nghiệp (giữ lại danh sách liên hệ của người dùng).
    
## <a name="office-365-proplus"></a>Văn phòng 365 ProPlus

- Cung cấp hướng dẫn và hỗ trợ cho:  
  - Đánh giá và lập kế hoạch phù hợp với các phương pháp hay nhất của Microsoft về triển khai và quản lý bản Cập Nhật ban đầu.
  - Cho phép sử dụng bộ công cụ sẵn sàng cho Office để xác định các vấn đề tương thích tiềm năng với Microsoft VBA macro và trình bổ sung mà bạn sử dụng với Office.
  
## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn có trách nhiệm sau đây trong quá trình onboarding. Ngoài các trách nhiệm được xác định trong phần [trách nhiệm của bạn](O365-your-responsibilities.md) . 
  
- Chỉ định và quản lý tài nguyên theo kế hoạch dự án.  
- Thực hiện hành động kịp thời để giảm thiểu rủi ro và giải quyết các vấn đề do khách hàng, đối tác quản lý dự án và FastTrack Manager nêu ra.   
- Đánh giá báo cáo trạng thái và hành động phù hợp.   
- Chỉ định một nhà tài trợ hoạt động hoặc dẫn đầu với một cơ quan ra quyết định để điều hành ban chỉ đạo.  
- Chỉ định một nhà tài trợ hành chính để làm việc với nhà tài trợ của Microsoft.  
- Thiết lập một cuộc họp Ban chỉ đạo hàng tháng.
