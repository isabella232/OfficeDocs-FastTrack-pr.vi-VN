---
title: Tổng quan về Lợi ích của Trung tâm FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Với lợi ích Trung tâm FastTrack cho Office 365, bạn làm việc từ xa với các chuyên gia FastTrack để nhận được môi trường Office 365 của bạn sẵn sàng để sử dụng và lập kế hoạch cho việc triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về đủ điều kiện, hãy xem mục lợi ích của Trung tâm FastTrack cho Office 365.
ms.openlocfilehash: 30d428cb5cc4e4fb8c9a267029a52618678c5ee1
ms.sourcegitcommit: de2cc20b4ab297633cb254d42532719022bb8d99
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/02/2020
ms.locfileid: "47338228"
---
# <a name="fasttrack-center-benefit-overview"></a>Tổng quan về Lợi ích của Trung tâm FastTrack

> [!CAUTION]
> Nội dung này không còn hiện tại và được lên lịch để loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Với lợi ích Trung tâm FastTrack cho Office 365, bạn làm việc từ xa với các chuyên gia FastTrack để nhận được môi trường Office 365 của bạn sẵn sàng để sử dụng và lập kế hoạch cho việc triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về đủ điều kiện, hãy xem mục [lợi ích của Trung tâm Fasttrack cho Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Chúng tôi bao gồm các chủ đề sau đây:
- [Quy trình FastTrack](O365-fasttrack-process.md) 
- [Kỳ vọng về môi trường nguồn](O365-source-environment-expectations.md)
- [Giai đoạn triển khai và di chuyển](O365-onboarding-and-migration.md)
- [Di chuyển dữ liệu](O365-data-migration.md)
- [Trách nhiệm của FastTrack](O365-fasttrack-responsibilities.md)
- [Trách nhiệm của bạn](O365-your-responsibilities.md) 
- [Phụ lục A - Lợi ích bổ sung của Trung tâm FastTrack](O365-fasttrack-additional-benefits.md)
- [Phụ lục B - Thỏa thuận Liên kết Kinh doanh HIPAA của Trung tâm FastTrack](O365-hipaa-business-associate-agreement.md)
- [Phụ lục C - Tổng quan về Lợi ích Trung tâm FastTrack dành cho Office 365 US Government](US-Gov-appendix-overview.md)
    
Đối tượng thuê Office 365 của bạn được tạo khi hoàn thành onboarding. Người dùng được cấp phép có thể truy nhập Office 365 bằng cách sử dụng một trong các tùy chọn định danh sau:
- Danh tính đám mây với các tài khoản Office 365 duy nhất.
- Các danh tính được đồng bộ với các tài khoản Office 365 được đồng bộ hóa từ Active Directory tại chỗ của bạn với Azure Active Directory Connect (mật khẩu Hash hoặc thông qua xác thực). Đây là những khách hàng có:
  - Môi trường rừng Active Directory duy nhất.
  - Tô pô Active Directory nhiều rừng được hỗ trợ. Đối với các topo được hỗ trợ, hãy xem mục [mong đợi môi trường nguồn](O365-source-environment-expectations.md).
- Liên kết các danh tính với các tài khoản Office 365 là:
  - Được đồng bộ hóa từ Active Directory với công cụ kết nối Azure Active Directory dành cho khách hàng với:
      - Một cấu hình rừng Active Directory đơn.
      - Một rừng tài khoản Active Directory đơn (còn được gọi là "rừng đăng nhập") và một cấu hình một tài nguyên Active Directory.
  - Cấu hình với cơ sở hạ tầng dịch vụ liên kết Active Directory tại cơ sở (AD FS) là:
      - Liên kết với vai trò AD FS của Windows Server 2012 R2 trở đi từ Active Directory tại chỗ của bạn.
      - Khi bắt buộc, một vai trò Windows Server 2012 R2 đã đi tiếp đến khi Windows Application proxy (WAP) được sử dụng để phát hành cơ sở hạ tầng AD FS tại cơ sở của bạn vào Internet.
    > [!NOTE]
    > AD FS và triển khai và cấu hình WAP được thực hiện bằng cách sử dụng trình [hướng dẫn cấu hình AZURE AD Connect](https://go.microsoft.com/fwlink/?linkid=844794) từ môi trường tại chỗ của bạn. 
  
- Người dùng được cấp phép có thể truy nhập các [dịch vụ và gói đủ điều kiện](M365-eligible-services-and-plans.md).

