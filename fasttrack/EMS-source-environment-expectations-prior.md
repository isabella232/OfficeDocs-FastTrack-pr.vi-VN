---
title: Mong đợi môi trường nguồn
description: Các yêu cầu môi trường nguồn cho việc sử dụng lợi ích của Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: df1a9fc3bd1fc51936a3595f674b36ff66f442b5
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777264"
---
# <a name="source-environment-expectations"></a>Kỳ vọng về môi trường nguồn

Khi bạn sử dụng [lợi ích Trung tâm Fasttrack cho doanh nghiệp Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) để tải Microsoft Azure Active Directory Premium, Microsoft InTune và Azure Information Protection đã sẵn sàng để sử dụng, môi trường của bạn cần đáp ứng các kỳ vọng được mô tả trong các phần sau đây.

Bạn có thể đã có Active Directory tại cơ sở trong tổ chức của bạn mà bạn muốn tích hợp với tính năng di động của doanh nghiệp + bảo mật (EMS) hoặc bất kỳ dịch vụ riêng lẻ nào sử dụng quản lý định danh phong phú từ một bàn điều khiển duy nhất. Lợi ích của Trung tâm FastTrack for Enterprise Mobility + Security (EMS) bao gồm việc giúp bạn tích hợp Azure Active Directory với môi trường Active Directory tại cơ sở hiện tại của bạn.

Bảng sau đây Hiển thị các mong đợi cho môi trường nguồn hiện có của bạn cho nội trú tại chỗ.

|Hoạt động|Kỳ vọng môi trường nguồn|
|------------|----------------------------------|
|Căn phải tại chỗ|Rừng Active Directory với mức độ rừng chức năng được đặt thành Windows Server 2008 hoặc cao hơn, với cấu hình rừng sau đây:<br /><br />-Rừng Active Directory đơn<br />-Nhiều rừng dành cho Active Directory </br></br>**Lưu ý**: đối với tất cả các cấu hình rừng, Dịch vụ liên kết Active Directory (AD FS) sẽ vượt quá phạm vi cho lợi ích của Trung tâm fasttrack.|
|Azure AD Premium tại chỗ|Active Directory tại chỗ và môi trường của nó đã được chuẩn bị sẵn sàng cho Azure AD Premium, trong đó bao gồm việc khắc phục các vấn đề đã xác định ngăn chặn việc tích hợp với Azure AD và Azure AD Premium.|
|InTune trên máy bay| Người quản trị CNTT cần có cơ quan cấp chứng chỉ hiện có, WiFi và hạ tầng VPN đã làm việc trong môi trường sản xuất của họ khi lập kế hoạch triển khai các hồ sơ WiFi và VPN bằng InTune.<br /><br /> **Lưu ý**: lợi ích của dịch vụ không bao gồm trợ giúp thiết lập hoặc cấu hình cơ quan cấp chứng chỉ, WiFi, kết cấu hạ tầng VPN hoặc giấy chứng nhận đẩy táo MDM cho  |
|Trình quản lý cấu hình đám mây được đính kèm bằng InTune|Với đám mây-đính kèm, người quản trị CNTT có trách nhiệm chuẩn bị môi trường tại chỗ, có thể bao gồm khắc phục sự cố ngăn cản bạn từ đám mây-đính kèm môi trường trình quản lý cấu hình của bạn với InTune.<br /><br />**Lưu ý**: lợi ích của dịch vụ fasttrack không bao gồm trợ giúp thiết lập hoặc nâng cấp máy chủ site của trình quản lý cấu hình hoặc máy khách trình quản lý cấu hình đến các yêu cầu tối thiểu cần thiết để hỗ trợ đám mây-đính kèm. |
|InTune tích hợp với bảo vệ mối đe dọa nâng cao của Microsoft Defender (ATP)|**Lưu ý**: lợi ích Dịch vụ fasttrack cung cấp trợ giúp về việc tích hợp InTune với Microsoft Defender ATP và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức rủi ro Windows 10 của nó. Lợi ích của dịch vụ không cung cấp trợ giúp về việc mua, cấp phép hoặc kích hoạt. |
|Windows Autopilot|Người quản trị CNTT chịu trách nhiệm đăng ký thiết bị của họ với tổ chức của họ bằng cách có nhà cung cấp phần cứng tải lên các ID phần cứng của họ thay mặt cho họ hoặc bằng cách tải nó vào dịch vụ Autopilot của Windows. |
|Triển khai Outlook cho iOS và Android an toàn với InTune|<br /><br />-Các danh tính người dùng được kích hoạt trong Azure AD cho Office 365.<br />-Exchange Online hoặc cấu hình trao đổi hỗn hợp với giấy phép người dùng được gán.<br />|
|Bảo vệ thông tin Azure (P2 hoặc EMS E5)|<br /><br />Khách hàng phải là: <br /> -Sử dụng Azure AD.<br />-Sử dụng Windows hoặc iOS (các cửa khác nằm ngoài phạm vi).<br /> -Sử dụng máy khách Office mới hơn Office 2010 SP2 không dựa vào Office là máy khách chính. <br /> -Có vị trí chia sẻ tệp chính của họ.  <br /> -Đã nâng cấp từ dịch vụ quản lý quyền Active Directory (AD RMS). <br /> -Có phân loại phân loại được phê duyệt. <br /> -Hiểu mọi hạn chế về quy định về quản lý khóa được bảo vệ. <br />|
|Máy quét bảo vệ thông tin Azure|<br /><br /> Khách hàng phải là: <br /> -Sử dụng Windows Server 2012 R2 hoặc Windows Server 2016.<br /> -Có kết nối Internet. <br /> -Microsoft SQL Server 2012 trở đi trong một ví dụ địa phương hoặc từ xa.  <br /> -Có tài khoản Dịch vụ được tạo cho Active Directory tại cơ sở và được đồng bộ hóa với Azure AD.  <br /> -Đã tải xuống AzInfoProtection.exe. <br /> -Có các nhãn được đặt cấu hình để phân loại tự động/bảo vệ.<br />|

> [!NOTE]
> Bạn **muốn tìm hiểu thêm?** 
>  Tính năng [di động doanh nghiệp + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Các bước tiếp theo

[Lợi ích của Trung tâm fasttrack cho các giai đoạn EMS triển khai](EMS-onboarding-phases.md)

