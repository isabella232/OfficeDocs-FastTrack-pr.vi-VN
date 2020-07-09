---
title: Mong đợi môi trường nguồn
description: Yêu cầu môi trường nguồn để sử dụng FastTrack Trung tâm lợi ích cho EMS
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
ms.sourcegitcommit: 850211891e549e582e649a1dacdc2aa79b520b39
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 07/01/2020
ms.locfileid: "45011028"
---
# <a name="source-environment-expectations"></a>Kỳ vọng về môi trường nguồn

Khi bạn sử dụng các [FastTrack Trung tâm lợi ích cho doanh nghiệp di động + bảo mật (EMS)](EMS-fasttrack-benefit-for-EMS.md) để có được Microsoft Azure Active Directory Premium, Microsoft InTune và bảo vệ thông tin Azure sẵn sàng để sử dụng, môi trường của bạn cần đáp ứng các mong đợi được mô tả trong các phần sau.

Bạn có thể đã có Active Directory tại chỗ trong tổ chức của bạn mà bạn muốn tích hợp với doanh nghiệp di động + bảo mật (EMS) hoặc bất kỳ dịch vụ cá nhân sử dụng quản lý danh tính phong phú từ một bảng điều khiển duy nhất. Lợi ích Trung tâm FastTrack dành cho doanh nghiệp di động + bảo mật (EMS) bao gồm giúp bạn tích hợp Azure Active Directory với môi trường Active Directory tại chỗ hiện tại của bạn.

Bảng sau hiển thị các kỳ vọng cho môi trường nguồn hiện tại của bạn cho việc lên máy bay.

|Hoạt động|Môi trường nguồn kỳ vọng|
|------------|----------------------------------|
|Lõi trên nội trú|Active Directory rừng với mức độ nhóm chức năng thiết lập Windows Server 2008 trở lên, với cấu hình nhóm sau:<br /><br />-Một nhóm Active Directory<br />-Nhiều khu rừng Active Directory </br></br>**Chú ý**: cho tất cả các cấu hình nhiều khu rừng, triển khai dịch vụ liên kết Active Directory (AD FS) nằm trong phạm vi cho lợi ích Trung tâm FastTrack.|
|Azure AD Premium trên máy bay|Active Directory tại chỗ và môi trường đã được chuẩn bị cho Azure AD Premium, bao gồm khắc phục các sự cố đã xác định ngăn tích hợp với Azure AD và các tính năng Azure AD Premium.|
|InTune on-Boarding| Quản trị viên CNTT cần có cơ sở hạ tầng chứng chỉ, WiFi và VPN hiện có đã hoạt động trong môi trường sản xuất khi lập kế hoạch triển khai các cấu hình WiFi và VPN với InTune.<br /><br /> **Lưu ý**: lợi ích Dịch vụ không bao gồm hỗ trợ để thiết lập hoặc cấu hình cơ quan chứng chỉ, WiFi, VPN hạ tầng, hoặc Apple MDM Push chứng chỉ cho  |
|Trình quản lý cấu hình đính kèm đám mây với InTune|Với đám mây đính kèm, quản trị viên CNTT có trách nhiệm chuẩn bị môi trường tại chỗ, có thể bao gồm khắc phục sự cố ngăn bạn từ đám mây gắn môi trường quản lý cấu hình của bạn với InTune.<br /><br />**Lưu ý**: Dịch vụ FastTrack lợi ích không bao gồm hỗ trợ để thiết lập hoặc nâng cấp máy chủ trang web quản lý cấu hình hoặc quản lý cấu hình máy khách yêu cầu tối thiểu cần thiết để hỗ trợ đám mây đính kèm. |
|InTune tích hợp với Microsoft Defender nâng cao Threat Protection (ATP)|**Lưu ý**: Dịch vụ FastTrack lợi ích cung cấp hỗ trợ tích hợp InTune với Microsoft Defender ATP và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức độ rủi ro Windows 10. Lợi ích Dịch vụ không cung cấp hỗ trợ về việc mua, cấp phép hoặc kích hoạt. |
|Cửa sổ Autopilot|Quản trị viên CNTT chịu trách nhiệm đăng ký thiết bị của họ cho tổ chức của họ bằng cách có nhà cung cấp phần cứng tải lên ID phần cứng thay mặt họ hoặc tải nó vào dịch vụ Windows Autopilot. |
|Triển khai Outlook cho iOS và Android một cách an toàn với InTune|<br /><br />-Người dùng nhận dạng được kích hoạt trong Azure AD cho Office 365.<br />-Exchange Online hoặc Exchange kết hợp cấu hình với giấy phép người dùng được chỉ định.<br />|
|Bảo vệ thông tin Azure (P2 hoặc EMS E5)|<br /><br />Khách hàng nên đã: <br /> -Sử dụng Azure AD.<br />-Sử dụng Windows hoặc iOS (các OSs khác ngoài phạm vi).<br /> -Sử dụng máy khách Office mới hơn Office 2010 SP2 không dựa trên Office là khách hàng chính. <br /> -Có địa điểm chia sẻ tập tin chính của họ.  <br /> -Đã nâng cấp từ dịch vụ quản lý quyền Active Directory (AD RMS). <br /> -Có phân loại được phê duyệt. <br /> -Hiểu bất kỳ hạn chế quy định nào về quản lý khóa được bảo vệ. <br />|
|Máy quét bảo vệ thông tin Azure|<br /><br /> Khách hàng nên đã: <br /> -Sử dụng Windows Server 2012 R2 hoặc Windows Server 2016.<br /> -Có kết nối Internet. <br /> -Có Microsoft SQL Server 2012 trở đi trong một phiên bản địa phương hoặc từ xa.  <br /> -Có một tài khoản Dịch vụ tạo ra cho Active Directory tại chỗ của họ và đồng bộ hoá với Azure AD.  <br /> -Đã tải về AzInfoProtection.exe. <br /> -Có nhãn được cấu hình để tự động phân loại/bảo vệ.<br />|

> [!NOTE]
> **Muốn tìm hiểu thêm?** 
>  [Doanh nghiệp di động + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Các bước tiếp theo

[FastTrack Trung tâm lợi ích cho EMS bộ nhớ ngoài giai đoạn](EMS-onboarding-phases.md)

