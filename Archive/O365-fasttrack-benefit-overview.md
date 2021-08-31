---
title: Tổng quan về Lợi ích của Trung tâm FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
ms.localizationpriority: ''
ms.collection: FastTrack
description: Với Lợi ích FastTrack Dành cho Trung tâm Office 365, bạn làm việc từ xa với Các chuyên gia FastTrack để môi trường Office 365 của bạn sẵn sàng sử dụng và lập kế hoạch triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về tính đủ điều kiện, hãy xem FastTrack Lợi ích Trung tâm Để biết Office 365.
ms.openlocfilehash: 59fa596eb91d50a9b3ea998a96d8eaea044cc9df
ms.sourcegitcommit: 3d086ab6c4743afbedebed55a3ddb65f05422a1b
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/30/2021
ms.locfileid: "58710301"
---
# <a name="fasttrack-center-benefit-overview"></a>Tổng quan về Lợi ích của Trung tâm FastTrack

> [!CAUTION]
> Nội dung này không còn mới nhất và được lên lịch loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Với Lợi ích FastTrack Dành cho Trung tâm Office 365, bạn làm việc từ xa với Các chuyên gia FastTrack để môi trường Office 365 của bạn sẵn sàng sử dụng và lập kế hoạch triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về tính đủ điều kiện, hãy [xem FastTrack lợi ích Trung tâm Để biết Office 365.](O365-fasttrack-benefit-for-office-365.md)
  
Chúng tôi đề cập đến các chủ đề sau:
- [Quy trình FastTrack](O365-fasttrack-process.md) 
- [Kỳ vọng về môi trường nguồn](O365-source-environment-expectations.md)
- [Giai đoạn triển khai và di chuyển](O365-onboarding-and-migration.md)
- [Di chuyển dữ liệu](O365-data-migration.md)
- [Trách nhiệm của FastTrack](O365-fasttrack-responsibilities.md)
- [Trách nhiệm của bạn](O365-your-responsibilities.md) 
- [Phụ lục A - Lợi ích bổ sung của Trung tâm FastTrack](O365-fasttrack-additional-benefits.md)
- [Phụ lục B - Thỏa thuận Liên kết Kinh doanh HIPAA của Trung tâm FastTrack](O365-hipaa-business-associate-agreement.md)
- [Phụ lục C - Tổng quan về Lợi ích Trung tâm FastTrack dành cho Office 365 US Government](US-Gov-appendix-overview.md)
    
Đối Office 365 của bạn sẽ được tạo sau khi hoàn tất triển thị. Người dùng được cấp phép có thể Office 365 nhập bằng cách sử dụng một trong các tùy chọn định danh sau đây:
- Định danh đám mây với các tài Office 365 riêng.
- Định danh được Đồng bộ với Office 365 khoản người dùng được đồng bộ hóa từ Active Directory tại chỗ của bạn với Azure Active Directory Kết nối (Đồng bộ Băm Mật khẩu hoặc Xác thực Thông qua). Những thông tin này dành cho khách hàng có:
  - Một môi trường rừng Active Directory duy nhất.
  - Cấu trúc đa rừng Active Directory được hỗ trợ. Để biết các tồn đọng được hỗ trợ, hãy xem [Kỳ vọng Môi trường Nguồn](O365-source-environment-expectations.md).
- Các danh tính được liên kết Office 365 khoản liên kết là:
  - Được đồng bộ hóa từ Active Directory với công Azure Active Directory Kết nối dành cho khách hàng có:
      - Một cấu hình rừng Active Directory đơn lẻ.
      - Một rừng tài khoản Active Directory duy nhất (còn được gọi là "rừng đăng nhập") và một cấu hình rừng tài nguyên Active Directory duy nhất.
  - Được cấu hình với cơ sở hạ tầng Dịch vụ Liên kết Active Directory (AD FS) tại cơ sở, vốn là:
      - Được liên kết với Windows vai trò AD FS tại chỗ của Windows Server 2012 R2.
      - Khi được yêu cầu, vai trò Windows Server 2012 R2 chuyển sang Windows Application Proxy (WAP) được dùng để phát hành cơ sở hạ tầng AD FS tại chỗ của bạn lên internet.
    > [!NOTE]
    > Việc triển khai và cấu hình AD FS và WAP được thực hiện bằng trình hướng dẫn cấu hình [Kết nối Azure AD](https://go.microsoft.com/fwlink/?linkid=844794) từ môi trường tại chỗ của bạn. 
  
- Người dùng được cấp phép giờ đây có thể truy [nhập các Gói và Dịch vụ Đủ điều kiện.](M365-eligible-services-and-plans.md)

