---
title: Quy trình FastTrack
description: Tổng quan về quy trình triển lý Lợi ích Trung tâm FastTrack
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
ms.assetid: dd221c87-6bf7-4af8-845a-dc4c3a4f2334
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b0ed1d991eef76713924cc668adc47cfaf9da593
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283519"
---
# <a name="fasttrack-center-benefit-process-for-enterprise-mobility--security-ems"></a>Quy trình Lợi ích của Trung tâm FastTrack dành cho Enterprise Mobility + Security (EMS)

> [!CAUTION]
> Nội dung này không còn mới nhất và được lên lịch loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

Nếu tổ chức của bạn đủ điều kiện nhận Lợi ích Trung tâm FastTrack cho EMS, bạn có thể làm việc từ xa với các Chuyên gia FastTrack để chuẩn bị sẵn sàng cho Microsoft Azure Active Directory Premium, Microsoft Intune và Azure Information Protection sẵn sàng để sử dụng. Bạn cũng có thể yêu cầu trợ giúp qua [site FastTrack](https://www.microsoft.com/fasttrack/microsoft-365/ems) dành cho Azure Information Protection và Microsoft Cloud App Security. Để tìm hiểu tổ chức của bạn có đủ điều kiện hay không, hãy xem [Dịch vụ và Gói Đủ điều kiện](M365-eligible-services-and-plans.md).


Đây là những điều chúng tôi sẽ đề cập đến về quy trình triển năng:

-   [Tổng quan về quy trình triển thiệu](EMS-fasttrack-benefit-overview.md)

-   [Kỳ vọng về môi trường nguồn của bạn](EMS-source-environment-expectations.md)

-   [Các giai đoạn của quy trình triển năng](EMS-onboarding-phases.md)

-   [Trách nhiệm của FastTrack đối](EMS-fasttrack-responsibilities.md) với từng giai đoạn

-   [Trách nhiệm của khách hàng](EMS-your-responsibilities.md) đối với từng giai đoạn

Đây là những gì bạn có thể mong đợi khi hoàn tất việc tích hợp:

-   Đối tượng thuê EMS cho các dịch vụ bạn chọn sẽ được tạo.

-   Người dùng được cấp phép có thể truy nhập Dịch vụ EMS bằng cách sử dụng một trong các tùy chọn định danh sau đây:

    -   Định danh đám mây (tài khoản EMS duy nhất).

    -   Danh tính được Đồng bộ: Tài khoản EMS được đồng bộ hóa từ Active Directory tại chỗ của bạn bằng cách sử dụng công cụ Azure Active Directory Kết nối (Đồng bộ Băm Mật khẩu hoặc Xác thực Chuyển qua). Tùy chọn này dành cho những khách hàng có một rừng duy nhất hoặc nhiều rừng Active Directory.

    -   Định danh có liên kết--với tài khoản Microsoft EMS là:

        -   Được đồng bộ hóa từ Active Directory với công cụ Azure AD Kết nối của bạn. Tùy chọn này dành cho những khách hàng chỉ có một cấu hình rừng Active Directory.

        -   Được liên kết với Windows 2012 R2 Active Directory Federation Services (AD FS) 2.0 trở lên từ Active Directory tại chỗ của bạn.

        -   Khả năng tự động phân loại và bảo vệ thông tin cả khi đang lưu trữ và đang truyền với Azure Information Protection. 

        -   Khả năng khám phá thông tin trong các chia sẻ tệp tại chỗ và sử SharePoint với Trình quét Bảo vệ Thông tin Azure. 

        -   Khả năng quản lý khóa đối tượng thuê Azure Information Protection của bạn trong Tín liệu Khóa Azure. 

