---
title: Phụ lục A - Lợi ích bổ sung của Trung tâm FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: None
description: Những khách hàng mua ít nhất 20.000 giấy phép cho người thuê Exchange Online đủ điều kiện cho các dịch vụ bổ sung của Trung tâm FastTrack. Xem các dịch vụ và gói đủ điều kiện để biết thêm chi tiết.
ms.openlocfilehash: a2b136b7d7bdae2a8f70bb0c9781e63140f9fa2b
ms.sourcegitcommit: ca476a4195477d43a6f3a212bf27bfe473cc1ffa
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/02/2020
ms.locfileid: "48827076"
---
# <a name="appendix-a---fasttrack-center-additional-benefit"></a>Phụ lục A - Lợi ích bổ sung của Trung tâm FastTrack

> [!CAUTION]
> Nội dung này không còn hiện tại và được lên lịch để loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Những khách hàng mua ít nhất 20.000 giấy phép cho người thuê Exchange Online đủ điều kiện cho các dịch vụ bổ sung của Trung tâm FastTrack. Xem [Thêm](eligibility.md) thông tin chi tiết. 
  
## <a name="onboarding-and-migration-phases"></a>Các giai đoạn onboarding và di chuyển

## <a name="core"></a>Core

Bổ sung dịch vụ Core triển khai bao gồm hướng dẫn cấu hình cho dịch vụ liên kết Active Directory dư thừa (AD FS) và các chính sách truy nhập máy khách AD FS cho dịch vụ đó. 
  
## <a name="exchange-online"></a>Exchange Online

Đối với Exchange Online, chúng tôi cung cấp hướng dẫn cấu hình cho những điều sau đây:
- Thiết lập nhắn tin hợp nhất (UM) với Exchange Online.
- Cấu hình cùng tồn tại giữa Exchange Online và các thư mục công cộng tại cơ sở.
- Tích hợp ứng dụng hỗ trợ thư. 
- Lập kế hoạch di chuyển hộp thư và nhóm.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

Đối với Skype for Business Online, chúng tôi cung cấp hướng dẫn cho Lync tại cơ sở và di chuyển người dùng Skype for Business sang Skype for Business Online.
  
## <a name="microsoft-365-apps"></a>Ứng dụng Microsoft 365

Đối với ứng dụng Microsoft 365, chúng tôi cung cấp hướng dẫn cho các tùy chọn sau: 
- Đánh giá và lập kế hoạch tập trung vào việc chuẩn bị môi trường cho việc triển khai ban đầu và quản lý các bản Cập Nhật được căn chỉnh theo cách thực hành tốt nhất của Microsoft. 
- Phát triển cấu hình triển khai và cài đặt Cập Nhật bằng công cụ triển khai Office 365 và công cụ tùy chỉnh Office. 
- Gói triển khai bằng trình quản lý cấu hình Microsoft Endpoint.  
- Cho phép sử dụng bộ công cụ sẵn sàng cho Office để xác định các vấn đề tương thích tiềm ẩn với các macro của Microsoft Visual Basic for Applications (VBA) và các phần bổ trợ mà bạn sử dụng với Office.
    
## <a name="fasttrack-responsibilities"></a>Các trách nhiệm FastTrack

Các chuyên gia FastTrack có các trách nhiệm sau trong onboarding. Những điều này có thể được thêm vào hoặc thay thế các hoạt động được xác định trong [quy trình và mong đợi](process-and-expectations.md).
  
## <a name="general"></a>Thống

- Cung cấp hỗ trợ từ xa cho bạn trong việc lập kế hoạch phát triển thành công, thực hiện và các hoạt động cấu hình bắt buộc càng chi tiết trong các [sản phẩm và chức năng](products-and-capabilities.md).
    
## <a name="assess-phase"></a>Đánh giá giai đoạn

- Giữ cuộc gọi lên kế hoạch thành công để cung cấp hướng dẫn cho người dùng thành công. 
- Đánh giá môi trường của bạn để hỗ trợ cấu hình của AD FS dư thừa địa lý.  
- Chạy đánh giá để xác định các yêu cầu của bạn để truy nhập ứng dụng khách AD FS.
    
## <a name="enable-phase"></a>Bật giai đoạn

### <a name="geo-redundant-ad-fs-guidance"></a>Hướng dẫn AD FS dư thừa địa lý

- Cung cấp thiết kế kiến trúc tham chiếu tiêu chuẩn cho các trung tâm dữ liệu dư thừa địa lý được bao trùm hai (2). Kiến trúc tiêu chuẩn cung cấp:
  - Đã liên kết xác thực cho các dịch vụ trong phạm vi cho lợi ích của Trung tâm FastTrack. 
  - Trang đơn Resiliency.  
  - Mức độ sẵn sàng cao và chuyển đổi chuyển đổi.  
  - Hướng dẫn đổi cỡ. 
- Cung cấp hướng dẫn sử dụng cơ sở dữ liệu nội bộ Windows và SQL Server làm ví dụ cơ sở dữ liệu cho Farm FS.   
- Xác nhận việc thiết lập xác thực liên kết cho từng rừng trong phạm vi.  
- Xác nhận chức năng xác thực liên kết cho tối đa 10 người dùng.
    
> [!NOTE]
> Triển khai AD FS nằm trong phạm vi cho các khách hàng có lợi ích bổ sung đủ điều kiện với nhiều cấu hình rừng Active Directory. 
  
### <a name="ad-fs-client-access-policy-guidance"></a>Hướng dẫn về chính sách truy nhập máy khách AD FS

- Xem lại các chính sách và cấu hình cần thiết để bảo mật tài nguyên Office 365.  
- Cung cấp hướng dẫn và trợ giúp với việc cấu hình chính sách truy nhập máy khách AD FS để xác định các kịch bản truy nhập máy khách trong ranh giới của các kịch bản được hỗ trợ. Để biết thêm thông tin, hãy xem [giới hạn quyền truy nhập vào dịch vụ Office 365 dựa trên vị trí của máy khách](https://go.microsoft.com/fwlink/?LinkID=525689). 
- Xác thực chức năng xác thực liên kết với các chính sách truy nhập khách hàng đã sửa đổi để xác định các kịch bản Access với cấu hình tối đa 10 người dùng.
    
## <a name="exchange-online"></a>Exchange Online

### <a name="exchange-unified-messaging-guidance"></a>Hướng dẫn gửi thư hợp nhất trong Exchange

- Cung cấp hướng dẫn về cấu hình bắt buộc trên Exchange Online để kích hoạt tối đa 10: 
  - Các kế hoạch quay số UM.   
  - Chính sách hộp thư UM. 
  - Tổng đài tự động.  
- Cung cấp hướng dẫn cho cấu hình môi trường Lync hoặc Skype for Business tại cơ sở để cho phép UM và mục tiêu cụ thể:  
  - Chính sách lưu trữ Exchange Online.  
  - Chính sách thư thoại được lưu trữ trong Exchange Online. 
  - Liên hệ tổng đài tự động UM và thư thoại trong Outlook để chuyển hướng người dùng đến Exchange Online. 
  - Hỗ trợ việc tạo bản ghi vị trí dịch vụ (SRV) theo yêu cầu cho liên kết.
> [!NOTE]
> Có thể cấu hình UM với cổng IP UM và bộ điều khiển viền phiên (SBC) được hỗ trợ. Để biết thêm thông tin, hãy xem [tích hợp hệ thống điện thoại với UM](https://go.microsoft.com/fwlink/?LinkID=809293). 
  
### <a name="public-folder-coexistence-guidance"></a>Hướng dẫn cùng tồn tại trong thư mục công cộng

- Cung cấp hướng dẫn về cùng tồn tại của một thư mục công cộng, bao gồm:  
  - Chuẩn bị thư mục công cộng trong Exchange 2007, Exchange 2010 và Exchange 2013. 
  - Cấu hình Exchange Online để chuyển hướng truy nhập thư mục công cộng đến các thư mục công cộng tại cơ sở.  
  - Cấu hình quyền truy nhập vào các thư mục công cộng từ Exchange Online đến một máy Exchange 2007, Exchange 2010 hoặc Exchange 2013 tại chỗ môi trường tại cơ sở.  
  - Hỗ trợ truy nhập xác thực đối với môi trường thư mục công cộng cho tối đa 10 người dùng trong Exchange Online.
    
### <a name="mail-enabled-application-integration-guidance"></a>Hướng dẫn tích hợp ứng dụng hỗ trợ thư

- Cung cấp các mẫu hướng dẫn cho:  
  - Ứng dụng gửi thư hàng loạt.  
  - Các ứng dụng định tuyến email thông qua Exchange.  
  - Các ứng dụng sử dụng hộp thư Exchange.  
  - Ứng dụng yêu cầu các cấu phần bên thứ ba hoặc tùy chỉnh được cài đặt trên máy chủ Exchange.
    
### <a name="mailbox-migration-planning-and-grouping"></a>Lập kế hoạch di chuyển hộp thư và nhóm

- Cung cấp hướng dẫn trong việc tạo một kế hoạch di chuyển, bao gồm:  
  - Nhóm người dùng và tài nguyên trong lô.
  - Phối hợp việc triển khai các gói phần mềm bắt buộc với lô di chuyển.   
  - Hướng dẫn để tạo một kế hoạch liên lạc để kết thúc người dùng. 
  - Điều phối kích cỡ lô di chuyển, tỷ lệ lỗi và hỗ trợ bộ phận trợ giúp dự kiến. 
- Cung cấp hướng dẫn trong việc nhóm các hộp thư người dùng và tài nguyên theo lô theo loại, hàm Business và quyền truy nhập đại diện dựa trên các thông tin có liên quan được cung cấp bởi khách hàng.
    
## <a name="skype-for-business-online"></a>Skype for Business Online

- Cung cấp hướng dẫn về việc di chuyển người dùng theo lô trong triển khai kết hợp Skype for Business (giữ lại danh sách liên hệ của người dùng).
    
## <a name="microsoft-365-apps"></a>Ứng dụng Microsoft 365

- Cung cấp hướng dẫn và trợ giúp cho:  
  - Đánh giá và lập kế hoạch căn chỉnh với các biện pháp tốt nhất của Microsoft để triển khai và quản lý các bản Cập Nhật ban đầu.
  - Cho phép sử dụng bộ công cụ sẵn sàng cho Office để xác định các vấn đề tương thích tiềm ẩn với macro Microsoft VBA và phần bổ trợ mà bạn sử dụng với Office.
  
## <a name="your-responsibilities"></a>Trách nhiệm của bạn

Bạn có các trách nhiệm sau trong khi onboarding. Ngoài ra, đây là những trách nhiệm được xác định trong [quy trình và mong đợi](process-and-expectations.md). 
  
- Gán và quản lý tài nguyên theo kế hoạch dự án.  
- Hành động kịp thời để giảm thiểu rủi ro và giải quyết các sự cố do khách hàng, người quản lý dự án đối tác và trình quản lý FastTrack đưa ra.   
- Xem lại báo cáo trạng thái và hành động phù hợp.   
- Gán một nhà tài trợ hoạt động hoặc dẫn đầu với một quyền quyết định để chạy Ủy ban điều khiển.  
- Gán một nhà tài trợ điều hành để làm việc với nhà tài trợ điều hành của Microsoft.  
- Thiết lập một cuộc họp Ban điều khiển hàng tháng.
