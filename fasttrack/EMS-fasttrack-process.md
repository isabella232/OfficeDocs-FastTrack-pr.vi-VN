---
title: Quy trình FastTrack
description: Tổng quan về quy trình thu nhận triển khai của Trung tâm fasttrack
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
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 380ccc613301c1b85d59b232ec10194111f6c63b
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800494"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Quy trình Lợi ích của Trung tâm FastTrack dành cho Enterprise Mobility + Security (EMS)

> [!CAUTION]
> Nội dung này không còn hiện tại và được lên lịch để loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Nếu tổ chức của bạn đủ điều kiện cho lợi ích Trung tâm FastTrack cho EMS, bạn có thể làm việc từ xa với các chuyên gia FastTrack để tải Microsoft Azure Active Directory Premium, Microsoft InTune và Azure Information Protection đã sẵn sàng để sử dụng. Bạn cũng có thể yêu cầu trợ giúp thông qua [trang Fasttrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) cho Azure Information Protection và Microsoft Cloud App Security. Để tìm hiểu xem tổ chức của bạn có đủ điều kiện hay không, hãy xem các [dịch vụ và gói đủ điều kiện](M365-eligible-services-and-plans.md).


Sau đây là những gì chúng tôi đề cập về quy trình triển khai:

-   [Tổng quan về quy trình triển khai](EMS-fasttrack-benefit-overview.md)

-   [Các mong đợi cho môi trường nguồn của bạn](EMS-source-environment-expectations.md)

-   [Các giai đoạn của quy trình triển khai](EMS-onboarding-phases.md)

-   [Theo dõi trách nhiệm](EMS-fasttrack-responsibilities.md) cho từng giai đoạn

-   Các [trách nhiệm của khách hàng](EMS-your-responsibilities.md) cho từng giai đoạn

Đây là những gì bạn có thể mong đợi khi triển khai hoàn tất:

-   Đối tượng thuê EMS của bạn cho các dịch vụ được chọn của bạn sẽ được tạo.

-   Người dùng được cấp phép có thể truy nhập dịch vụ EMS bằng cách dùng một trong các tùy chọn định danh sau:

    -   Danh tính đám mây (tài khoản EMS duy nhất).

    -   Danh tính được đồng bộ: các tài khoản EMS được đồng bộ hóa từ Active Directory tại chỗ của bạn bằng cách sử dụng công cụ Azure Active Directory Connect (mật khẩu Hash hoặc thông qua xác thực). Tùy chọn này dành cho khách hàng có một rừng đơn hoặc nhiều rừng Active Directory.

    -   Danh tính được liên kết--với các tài khoản Microsoft EMS là:

        -   Được đồng bộ hóa từ Active Directory với công cụ Azure AD Connect. Tùy chọn này dành cho khách hàng có cấu hình rừng Active Directory đơn.

        -   Liên kết với Windows Server 2012 R2 Active Directory Services (AD FS) 2,0 hoặc phiên bản mới hơn từ Active Directory tại chỗ của bạn.

        -   Khả năng tự động phân loại và bảo vệ thông tin cả trong phần còn lại và trong quá trình chuyển đổi bằng Azure thông tin bảo vệ. 

        -   Khả năng phát hiện thông tin trong cổ phiếu tệp tại cơ sở và SharePoint Servers với máy quét bảo vệ thông tin Azure. 

        -   Khả năng quản lý các phím của đối tượng thuê thông tin Azure trong nút Azure Key Vault. 

