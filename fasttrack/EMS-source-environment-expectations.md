---
title: Sự mong đợi môi trường nguồn
description: Yêu cầu về môi trường nguồn cho việc sử dụng lợi ích Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 04/02/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.assetid: 9048f3e5-cc28-4744-bb5e-36f974abb261
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 0d0fa0415bc27013d7e035b75a5e5d9d9f9919c3
ms.sourcegitcommit: 8d1fbbfc6b05522ea1259149349548f072fefcac
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/01/2019
ms.locfileid: "31016774"
---
# <a name="source-environment-expectations"></a>Kỳ vọng về môi trường nguồn

Khi bạn sử dụng [FastTrack Trung tâm lợi ích cho doanh nghiệp vận động + bảo mật (EMS)](EMS-fasttrack-benefit-for-EMS.md) để có được Microsoft Azure Active Directory Premium và Microsoft Intune đã sẵn sàng để sử dụng, môi trường của bạn cần để đáp ứng sự mong đợi được mô tả trong các phần sau.

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

> [!NOTE]
> **Muốn tìm hiểu thêm?** 
>  [Enterprise Mobility + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility)

## <a name="next-steps"></a>Các bước tiếp theo

[FastTrack Trung tâm lợi ích cho EMS onboarding giai đoạn](EMS-onboarding-phases.md)
