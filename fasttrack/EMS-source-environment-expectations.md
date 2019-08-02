---
title: Sự mong đợi môi trường nguồn
description: Yêu cầu về môi trường nguồn cho việc sử dụng lợi ích Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 08/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: ffb9af7e6a0a4c2358a0bbe054469cf0caae11c4
ms.sourcegitcommit: 911b0d32a26eb068a2a94ebc48d9f8f2fc70e5a9
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/01/2019
ms.locfileid: "36053769"
---
# <a name="source-environment-expectations"></a>Kỳ vọng về môi trường nguồn

Khi bạn sử dụng [FastTrack Trung tâm lợi ích cho doanh nghiệp vận động + bảo mật (EMS)](EMS-fasttrack-benefit-for-EMS.md) để sẵn sàng cho việc sử dụng Microsoft Azure Active Directory Premium, Microsoft Intune và bảo vệ thông tin Azure, môi trường của bạn cần để đáp ứng sự mong đợi được mô tả trong các phần sau.

Bạn có thể đã có thư mục đang hoạt động tại chỗ trong tổ chức của bạn mà bạn muốn để tích hợp với các doanh nghiệp di động + bảo mật (EMS) hoặc bất kỳ các dịch vụ cá nhân sử dụng phong phú identity quản lý từ một bàn điều khiển duy nhất. FastTrack Trung tâm lợi ích cho doanh nghiệp vận động + bảo mật (EMS) bao gồm việc giúp bạn tích hợp Azure Active Directory môi trường Active Directory tại chỗ hiện có của bạn.

Bảng dưới đây cho thấy những kỳ vọng cho môi trường mã nguồn hiện tại của bạn cho ngày lên máy bay.

|Hoạt động|Nguồn môi trường kỳ vọng|
|------------|----------------------------------|
|Lõi vào nội trú|Hoạt động thư mục rừng với mức độ chức năng rừng đặt sang Windows Server 2008 hoặc ở trên, với cấu hình rừng sau:<br /><br />-Đơn cụm nhánh Active Directory<br />-Nhiều hoạt động thư mục rừng </br></br>**Lưu ý**: đối với tất cả các khu rừng nhiều cấu hình, triển khai dịch vụ liên bang Active Directory (AD FS) là ra khỏi phạm vi cho lợi ích Trung tâm FastTrack.|
|Azure quảng cáo phí bảo hiểm trên lên máy bay|Active Directory tại chỗ và môi trường đã được chuẩn bị cho Azure quảng cáo phí bảo hiểm, bao gồm khắc phục các vấn đề xác định ngăn ngừa tích hợp với Azure quảng cáo và các tính năng Azure quảng cáo phí bảo hiểm.|
|Dành ngày lên máy bay| Quản trị viên CNTT cần phải có sẵn có giấy chứng nhận quyền, WiFi và VPN kết cấu hạ tầng đã làm việc trong môi trường sản xuất của họ khi lập kế hoạch về việc triển khai hồ sơ VPN và WiFi với dành.<br /><br /> **Lưu ý**: những lợi ích Dịch vụ không bao gồm hỗ trợ cho việc thiết lập hoặc giấy chứng nhận quyền, WiFi, VPN kết cấu hạ tầng, cấu hình hoặc Apple MDM đẩy giấy chứng nhận cho  |
|Comanagement|Với Comanagement đó quản trị viên có trách nhiệm chuẩn bị môi trường tại chỗ, có thể bao gồm khắc phục các vấn đề ngăn cản bạn từ đồng thời quản lý các thiết bị Windows 10 bằng cách sử dụng trình quản lý cấu hình và dành.<br /><br />**Lưu ý**: The FastTrack dịch vụ lợi không bao gồm hỗ trợ cho việc thiết lập hoặc nâng cấp máy chủ trang web cấu hình quản lý và/hoặc khách hàng cấu hình quản lý các yêu cầu tối thiểu cần thiết để hỗ trợ cho Comanagement với các thiết bị Windows 10. |
|Dành tích hợp với Windows Defender nâng cao mối đe dọa bảo vệ (Windows Defender ATP)|Đăng ký Windows Defender ATP của bạn đã được kích hoạt và đặt cấu hình dựa trên yêu cầu an ninh công ty của bạn.<br /><br />**Lưu ý**: The FastTrack dịch vụ lợi ích cung cấp hỗ trợ về lồng ghép dành với Windows Defender ATP, và tạo ra thiết bị tuân thủ chính sách dựa trên của nó đánh giá mức độ rủi ro Windows 10. Lợi ích Dịch vụ FastTrack không hỗ trợ trên mua, cấp phép, kích hoạt hoặc bằng cách sử dụng Windows Defender ATP và giao diện điều khiển trung tâm bảo mật của nó. |
|Windows Autopilot|Quản trị viên CNTT có trách nhiệm đăng ký thiết bị của họ để tổ chức của họ bằng cách hoặc là nhà cung cấp phần cứng tải lên của phần cứng ID trên danh nghĩa của họ hoặc bằng cách tải lên nó bản thân mình vào dịch vụ Windows Autopilot. |
|Triển khai Outlook cho iOS và Android một cách an toàn với dành|<br /><br />-Nhận dạng người dùng được kích hoạt trong Azure quảng cáo cho Office 365.<br />-Trao đổi trực tuyến hoặc đổi ngoại lai, cấu hình với giấy phép người dùng được gán.<br />|
|Bảo vệ thông tin Azure (P2 hoặc EMS E5)|<br /><br />Khách hàng nên đã: <br /> -Sử dụng quảng cáo Azure.<br />-Sử dụng Windows hoặc iOS (khác OSs là ra khỏi phạm vi).<br /> -Sử dụng các khách hàng Office mới hơn Office 2010 SP2 không dựa vào các văn phòng là chính khách hàng. <br /> -Có tập tin chính chia sẻ vị trí.  <br /> -Đã nâng cấp từ dịch vụ quản lý quyền Active Directory (AD RMS). <br /> -Có một phân loại phân loại được chấp thuận. <br /> -Hiểu bất kỳ giới hạn quy định để quản lý chủ chốt bảo vệ của họ. <br />|
|Azure bảo vệ thông tin máy quét|<br /><br /> Khách hàng nên đã: <br /> -Sử dụng Windows Server 2012 R2 hoặc Windows Server năm 2016.<br /> -Có kết nối internet. <br /> -Có Microsoft SQL Server 2012 trở về trước trong một trường hợp địa phương hoặc từ xa.  <br /> -Có tài khoản Dịch vụ tạo ra cho Active Directory tại chỗ của họ và đồng bộ hoá với Azure quảng cáo.  <br /> -Đã tải về AzInfoProtection.exe. <br /> -Có nhãn được cấu hình để tự động phân loại/bảo vệ.<br />|

> [!NOTE]
> **Muốn tìm hiểu thêm?** 
>  [Enterprise Mobility + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Các bước tiếp theo

[FastTrack Trung tâm lợi ích cho EMS onboarding giai đoạn](EMS-onboarding-phases.md)
