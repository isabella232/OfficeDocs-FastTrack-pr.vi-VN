---
title: Tổng quan về Lợi ích Trung tâm FastTrack
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 11/2/2018
ms.audience: ITPro
ms.topic: overview
f1_keywords:
- office-365-onboarding-benefit-process
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: ac467db0-3118-41fa-a93d-bb5de1e414d5
description: Với FastTrack Trung tâm lợi ích cho Office 365, bạn làm việc từ xa với FastTrack chuyên gia để có được môi trường Office 365 của bạn đã sẵn sàng cho việc sử dụng và kế hoạch triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về điều kiện, hãy xem FastTrack Trung tâm lợi ích cho Office 365.
ms.openlocfilehash: 0696e4b7f46b91123046c90a5297c22300a9bc0e
ms.sourcegitcommit: a8717ee240040292872bc0231f1fb2a22b846806
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 11/01/2018
ms.locfileid: "25895565"
---
# <a name="fasttrack-center-benefit-overview"></a>Tổng quan về Lợi ích Trung tâm FastTrack

Với FastTrack Trung tâm lợi ích cho Office 365, bạn làm việc từ xa với FastTrack chuyên gia để có được môi trường Office 365 của bạn đã sẵn sàng cho việc sử dụng và kế hoạch triển khai và sử dụng trong tổ chức của bạn. Để tìm hiểu thêm về điều kiện, hãy xem [FastTrack Trung tâm lợi ích cho Office 365](O365-fasttrack-benefit-for-office-365.md).
  
Chúng tôi bao gồm các chủ đề sau:
- [Quy trình FastTrack](O365-fasttrack-process.md) 
- [Kỳ vọng về môi trường nguồn](O365-source-environment-expectations.md)
- [Giai đoạn triển khai và di chuyển](O365-onboarding-and-migration.md)
- [Di chuyển dữ liệu](O365-data-migration.md)
- [Trách nhiệm của FastTrack](O365-fasttrack-responsibilities.md)
- [Trách nhiệm của bạn](O365-your-responsibilities.md) 
- [Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online](O365-from-ibm-domino-to-exchange-online.md)
- [Phụ lục B - Lợi ích bổ sung của Trung tâm FastTrack](O365-fasttrack-additional-benefits.md)
- [Phụ lục C - Thỏa thuận Liên kết Kinh doanh HIPAA của Trung tâm FastTrack](O365-hipaa-business-associate-agreement.md)
- [Phụ lục D - Tổng quan về Lợi ích Trung tâm FastTrack dành cho Office 365 US Government](US-Gov-appendix-overview.md)
    
Người thuê nhà Office 365 của bạn được tạo ra tại hoàn thành onboarding. Giấy phép người dùng có thể truy cập vào Office 365 bằng cách sử dụng một trong các tuỳ chọn nhận dạng sau:
- Đám mây các danh tính với duy nhất các tài khoản Office 365.
- Đồng bộ bản sắc với tài khoản Office 365 được đồng bộ hoá từ Active Directory tại chỗ của bạn với Azure Active Directory kết nối (đồng bộ hóa Hash mật khẩu hoặc xác thực ñöôïc). Đây là cho các khách hàng với:
  - Một môi trường rừng single Active Directory.
  - Hỗ trợ đa rừng Active Directory tô pô. Topo được hỗ trợ, xem các [Nguồn môi trường mong đợi](O365-source-environment-expectations.md).
- Danh tính đã liên kết với tài khoản Office 365:
  - Đồng bộ hoá từ thư mục hoạt động với công cụ Azure Active Directory kết nối cho các khách hàng với:
      - Một cấu hình Active Directory rừng duy nhất.
      - Một đơn tài khoản cụm nhánh Active Directory (còn được gọi là một "đăng nhập rừng") và một duy nhất hoạt động thư mục tài nguyên rừng cấu hình.
  - Cấu hình với một cơ sở hạ tầng dịch vụ liên bang Active Directory (AD FS) trên cơ sở đó là:
      - Liên kết với một vai trò trong Windows Server 2012 R2 trở đi AD FS từ Active Directory tại chỗ của bạn.
      - Khi cần thiết, Windows Server 2012 R2 trở đi cửa sổ ứng dụng Proxy (WAP) vai trò được sử dụng để xuất bản các chỗ của cơ sở hạ tầng AD FS Internet.
    > [!NOTE]
    > Triển khai AD FS và WAP và cấu hình được thực hiện bằng cách sử dụng [thuật sĩ cấu hình Azure quảng cáo kết nối](https://go.microsoft.com/fwlink/?linkid=844794) từ môi trường tại chỗ của bạn. 
  
- Giấy phép người dùng bây giờ có thể truy cập [dịch vụ đủ điều kiện và kế hoạch](O365-eligible-services-and-plans.md).
    

 
