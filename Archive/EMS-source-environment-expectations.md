---
title: Kỳ vọng môi trường nguồn
description: Yêu cầu môi trường nguồn để sử dụng Lợi ích Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 7/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: None
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 285dee7b2372af0615673ecd330051fc50f49212
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283518"
---
# <a name="source-environment-expectations"></a>Kỳ vọng về môi trường nguồn
> [!CAUTION]
> Nội dung này không còn mới nhất và được lên lịch loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Khi bạn sử dụng Lợi ích Trung tâm FastTrack dành cho [Enterprise Mobility + Security (EMS)](EMS-fasttrack-benefit-for-EMS.md) để chuẩn bị cho Microsoft Azure Active Directory Premium, Microsoft Intune và Azure Information Protection sẵn sàng để sử dụng, môi trường của bạn cần phải đáp ứng những kỳ vọng được mô tả trong các mục sau.

Bạn có thể đã có Active Directory tại chỗ trong tổ chức của mình mà bạn muốn tích hợp với Enterprise Mobility + Security (EMS) hoặc bất kỳ dịch vụ cá nhân nào của dịch vụ sử dụng quản lý định danh phong phú từ một bảng điều khiển duy nhất. Lợi ích Trung tâm FastTrack dành cho Enterprise Mobility + Security (EMS) bao gồm việc giúp bạn tích hợp Azure Active Directory với môi trường Active Directory tại chỗ hiện có của bạn.

Bảng sau đây hiển thị kỳ vọng về môi trường nguồn hiện có của bạn khi triển năng.

|Hoạt động|Dự kiến về môi trường nguồn|
|------------|----------------------------------|
|Core on-boarding|Các rừng Active Directory có mức rừng chức năng được đặt Windows Server 2008 trở lên, với cấu hình rừng sau đây:<br /><br />- Rừng Active Directory Đơn<br />- Nhiều rừng Active Directory </br></br>**Lưu** ý: Đối với tất cả các cấu hình nhiều rừng, triển khai Dịch vụ Liên kết Active Directory (AD FS) không nằm trong phạm vi dành cho Lợi ích Trung tâm FastTrack.|
|Azure AD Premium đang nội bộ|Active Directory tại chỗ và môi trường của nó đã được chuẩn bị cho Azure AD Premium, bao gồm khắc phục các sự cố được xác định ngăn chặn việc tích hợp với các tính năng Premium Azure AD và Azure AD.|
|Intune đang nội bộ| Người quản trị CNTT cần có các cơ sở hạ tầng Certificate Authority, WiFi và VPN hiện đang hoạt động trong môi trường sản xuất của mình khi lên kế hoạch triển khai hồ sơ WiFi và VPN với Intune.<br /><br /> **Lưu ý**: Lợi ích dịch vụ không bao gồm hỗ trợ thiết lập hoặc cấu hình Cơ quan có thẩm quyền cấp Chứng chỉ, wiFi, VPN hoặc chứng chỉ đẩy MDM của Apple cho  |
|Trình quản lý Cấu hình đính kèm đám mây với Intune|Với tính năng đính kèm điện toán đám mây, người quản trị CNTT chịu trách nhiệm chuẩn bị môi trường tại chỗ, có thể bao gồm việc khắc phục sự cố ngăn bạn đính kèm đám mây vào môi trường Trình quản lý Cấu hình của mình với Intune.<br /><br />**Lưu** ý : Lợi ích dịch vụ FastTrack không bao gồm hỗ trợ thiết lập hoặc nâng cấp máy chủ site Trình quản lý Cấu hình hoặc máy khách Trình quản lý Cấu hình lên các yêu cầu tối thiểu cần thiết để hỗ trợ gắn trên đám mây. |
|Intune được tích hợp với Tính năng Chống Mối đe dọa Nâng cao của Bộ bảo vệ Microsoft (ATP)|**Lưu ý**: Lợi ích dịch vụ FastTrack cung cấp hỗ trợ về việc tích hợp Intune với ATP của Bộ bảo vệ Microsoft và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức rủi Windows 10 thiết bị. Lợi ích dịch vụ không cung cấp hỗ trợ cho việc mua hàng, cấp phép hoặc kích hoạt. |
|Windows Autopilot|Người quản trị CNTT chịu trách nhiệm đăng ký thiết bị của mình cho tổ chức của mình bằng cách thay mặt nhà cung cấp phần cứng tải lên ID phần cứng hoặc bằng cách tải thiết bị lên dịch vụ Autopilot của Windows. |
|Triển Outlook cho iOS và Android một cách bảo mật với Intune|<br /><br />- Danh tính người dùng được kích hoạt trong Azure AD cho Office 365.<br />- Định Exchange Online kết hợp Exchange hình với giấy phép người dùng được gán.<br />|
|Azure Information Protection (P2 hoặc EMS E5)|<br /><br />Khách hàng phải có: <br /> - Sử dụng Azure AD.<br />- Sử dụng Windows hoặc iOS (các OS khác không thuộc phạm vi).<br /> - Sử Office máy khách mới hơn Office 2010 SP2 và không dựa vào Office khách chính. <br /> - Có vị trí chia sẻ tệp chính.  <br /> - Đã nâng cấp từ Active Directory Rights Management Services (AD RMS). <br /> - Có phân loại phân loại được phê duyệt. <br /> - Hiểu rõ mọi hạn chế quy định đối với việc quản lý khóa được bảo vệ của trẻ. <br />|
|Trình quét Azure Information Protection|<br /><br /> Khách hàng phải có: <br /> - Sử dụng Windows Server 2012 R2 hoặc Windows Server 2016.<br /> - Có kết nối internet. <br /> - Chuyển Microsoft SQL Server 2012 trở đi trong phiên bản cục bộ hoặc từ xa.  <br /> - Có một tài khoản dịch vụ được tạo cho Active Directory tại chỗ của họ và được đồng bộ hóa với Azure AD.  <br /> - Đã tải xuống AzInfoProtection.exe. <br /> - Bạn đã đặt cấu hình nhãn cho Phân loại/Bảo vệ Tự động.<br />|

> [!NOTE]
> **Bạn muốn tìm hiểu thêm?** 
>  [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Các bước tiếp theo

[Lợi ích Trung tâm FastTrack dành cho các giai đoạn triển năng EMS](EMS-onboarding-phases.md)

