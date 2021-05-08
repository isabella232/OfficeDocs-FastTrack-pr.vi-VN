---
title: Trách nhiệm của FastTrack
description: Trách nhiệm của FastTrack khi khách hàng sử dụng Lợi ích Trung tâm FastTrack cho EMS
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
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: 46d059e97dc2eae307fed2596cd339be11062ad2
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283524"
---
# <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

> [!CAUTION]
> Nội dung này không còn mới nhất và được lên lịch loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

FastTrack có trách nhiệm sau đây trong quá trình triển năng.

## <a name="general"></a>Chung

-   Cung cấp trợ giúp từ xa cho bạn về các hoạt động cấu hình bắt buộc như được liệt kê trong mô tả giai đoạn chi tiết.

-   Cung cấp hướng dẫn sử dụng, công cụ phần mềm và bảng điều khiển quản trị sẵn có để giúp bạn giảm hoặc loại bỏ các tác vụ cấu hình.

## <a name="initiate-phase"></a>Giai đoạn khởi tạo

-   Làm việc với bạn để bắt đầu onboarding.

-   Xác định những dịch vụ đủ điều kiện mà bạn muốn sử dụng.

## <a name="assess-phase"></a>Giai đoạn đánh giá

-   Cung cấp thông tin tổng quan quản trị.

-   Cung cấp hướng dẫn về:

    -   Các nhu cầu DNS, mạng và cơ sở hạ tầng.

    -   Nhu cầu máy khách (trình duyệt Internet, hệ điều hành máy khách và nhu cầu dịch vụ).

    -   Danh tính người dùng và cấp phép.

    -   Cho phép các dịch vụ đủ điều kiện đã được mua và xác định là một phần của triển thị.

-   Thiết lập đường thời gian cho các hoạt động khắc phục.

-   Cung cấp danh sách kiểm tra khắc phục cho cả Intune và Azure AD Premium.

## <a name="remediate-phase"></a>Giai đoạn khắc phục

-   Tổ chức các cuộc gọi hội thảo với bạn theo lịch trình đã nhất trí để xem lại tiến độ của các hoạt động khắc phục, ví dụ, hướng dẫn bạn về các điều kiện tiên quyết cài đặt trước khi triển khai một dịch vụ điện toán đám mây của Microsoft.

## <a name="enable-phase"></a>Cho phép giai đoạn
Cung cấp hướng dẫn về:

-   Kích hoạt đối tượng thuê hoặc đăng ký dịch vụ trực tuyến Microsoft của bạn.

-   Cấu hình giao thức TCP/IP và cổng tường lửa.

-   Đặt cấu hình DNS cho các dịch vụ đủ điều kiện.

-   Xác thực khả năng kết nối với các dịch vụ trực tuyến của Microsoft.

-   Đối với môi trường một rừng:

    -   Cài đặt máy chủ đồng bộ hóa thư mục giữa Dịch vụ Miền Active Directory (AD DS) và các dịch vụ trực tuyến đủ điều kiện của Microsoft (chỉ hướng dẫn nếu cần).

    -   Đặt cấu hình xác thực được quản lý (Đồng bộ Băm Mật khẩu hoặc Xác thực Thông qua) bằng công Azure Active Directory Kết nối mật khẩu. (chỉ hướng dẫn nếu cần thiết).

        > [!NOTE]
        > Việc phát triển và thực hiện đối với các phần mở rộng quy tắc tùy chỉnh không có phạm vi.

-   Đối với một rừng duy nhất khi đích được liên kết: Cài đặt và cấu hình Dịch vụ Liên kết Active Directory (AD FS) để xác thực miền cục bộ với Intune trong một cấu hình dung sai số trang, nếu cần.

    > [!NOTE]
    > Đối với tất cả các cấu hình nhiều rừng, triển khai AD FS không có phạm vi.

-   Kiểm tra chức năng đăng nhập đơn (SSO), nếu được triển khai.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Cho phép giai đoạn - Microsoft Azure Active Directory Premium

Cung cấp hướng dẫn về:

- Kích hoạt đối tượng thuê Azure AD Premium của bạn.

- Cấu hình cổng tường lửa.

- Đặt cấu hình DNS cho các dịch vụ đủ điều kiện.

- Xác thực kết nối với các dịch vụ Premium Azure AD.

- Đối với môi trường một rừng:

  -   Cài đặt đồng bộ hóa thư mục giữa Dịch vụ Miền Active Directory (AD DS) và Azure AD Kết nối, nếu cần.

  -   Đặt cấu hình phương pháp xác thực (Đồng bộ Băm Mật khẩu hoặc Pass-Through Xác thực) bằng công cụ Azure AD Kết nối cụ.

- Đối với môi trường nhiều rừng:

  -   Cài đặt đồng bộ Kết nối Azure AD, thiết lập cho nhiều kịch bản rừng.
- Đối với các môi trường một rừng và nhiều rừng:
  - Cấu hình Azure Active Directory Xác thực Chuyển qua, nếu cần.
  - Nếu cần thiết, Azure Active Directory đặt cấu hình cho Sign-On Liền mạch Đơn (SSO).
    > [!NOTE]
    > Azure Active Directory Tính năng Xác thực Chuyển qua cho môi trường nhiều rừng được hỗ trợ nếu có tin cậy rừng giữa các rừng Active Directory của bạn và nếu định tuyến hậu tố tên được cấu hình đúng. Nhân viên bổ sung có thể được cài đặt trên nhiều máy chủ tại chỗ để cung cấp tính khả dụng cao cho các yêu cầu đăng nhập.

  - Để biết thêm thông tin, hãy xem Azure Active Directory Xác thực Chuyển [qua: Bắt](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) đầu nhanh Azure Active Directory Đăng nhập Một lần Liền [mạch: Bắt đầu nhanh](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Để biết thêm thông tin về giới hạn xác thực chuyển qua, hãy [xem Azure Active Directory Xác thực chuyển qua: Các giới hạn hiện tại](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Để biết thêm thông tin về các sự cố seamless SSO, hãy [xem Khắc phục Azure Active Directory đăng nhập một lần liền mạch.](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso)

      > [!NOTE]
      > Đồng bộ hóa băm mật khẩu và ghi lại hỗ trợ nhiều rừng. Tuy nhiên, các kịch bản ghi lại khác không được hỗ trợ.

  - Đặt cấu hình đồng bộ hóa giữa các rừng Active Directory tại chỗ và thư Microsoft Azure Active Directory Premium mục (Azure Active Directory).

    > [!NOTE]
    > Việc phát triển và thực hiện đối với các phần mở rộng quy tắc tùy chỉnh không có phạm vi.

- Đối với một rừng riêng lẻ khi đích được liên kết:

  -   Cài đặt và đặt cấu hình AD FS để xác thực miền cục bộ bằng Azure AD Premium trong một cấu hình dung sai số trên một site duy nhất (nếu cần).

  > [!NOTE]
  > Đối với tất cả các cấu hình nhiều rừng, triển khai AD FS không có phạm vi.

- Kiểm tra chức năng SSO (nếu đã triển khai).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Giai đoạn bật - Azure AD Premium - với Azure AD Kết nối VÀ AD FS

Cung cấp hướng dẫn về việc thiết lập:

- Cung cấp cho người dùng, bao gồm cấp phép.

- Đồng bộ hóa azure AD Kết nối mục (với ghi lại mật khẩu và đồng bộ hóa băm mật khẩu).

  - Azure Active Directory Tự đặt lại Mật khẩu Dịch vụ (SSPR).

  - Azure Multi-Factor Authentication.

  - Tối đa ba (3) phần mềm trở lên dưới dạng tích hợp ứng dụng Dịch vụ (SaaS) với Sign-On Đơn (SSO) [từ Azure Active Directory Marketplace.](https://azure.microsoft.com/marketplace/active-directory/)

  - Tự động cung cấp người dùng cho các ứng dụng SaaS tích hợp sẵn như được liệt kê trong danh sách hướng dẫn tích hợp Ứng [dụng,](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list)giới hạn chỉ cung cấp đi.

  - Màn hình đăng nhập tùy chỉnh, bao gồm logo, văn bản và hình ảnh.

  - Self-Service và Nhóm Linh động (Nhóm).

  - Azure Active Directory Proxy Ứng dụng.

  - Azure Active Directory Kết nối trạng.

  - Azure Active Directory Truy nhập có điều kiện.

  - Azure Active Directory Điều khoản Sử dụng.

  - Azure Active Directory Bảo vệ Định danh.

  - Azure Active Directory Privileged Identity Management.

  - Azure Active Directory Truy nhập Đánh giá.

  -   Azure Active Directory Bảo vệ bằng Mật khẩu.

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>Cho phép giai đoạn - Intune

> [!IMPORTANT]
> FastTrack không hỗ trợ quản Windows 10 PC cổ điển với Intune. FastTrack chỉ hỗ trợ quản Windows 10 thông qua quản lý thiết bị di động Intune (MDM).

Cung cấp hướng dẫn về:

-   Intune sẽ đặt cấu hình định danh để sử dụng, bằng cách tận dụng Active Directory tại chỗ hoặc danh tính đám mây của bạn (Azure Active Directory).

-   Cấp phép cho người dùng cuối của bạn.

-   Thêm người dùng vào đăng ký Intune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.

-   Đặt cấu hình thẩm quyền MDM Quản lý Thiết bị Di động của bạn, dựa trên nhu cầu quản lý của bạn, bao gồm:

    -   Đặt Intune làm cơ quan MDM của bạn.

    -   Cấu hình các nhóm kiểm tra được dùng để xác thực chính sách quản lý MDM.

    -   Dẫn hướng cổng thông tin quản trị Intune để định vị thông tin trên người dùng và thiết bị.

    -   Thiết lập vai trò Intune (người điều hành bộ phận trợ giúp, người quản trị, v.v.)

    -   Đặt cấu hình cho chính sách quản lý MDM và các dịch vụ như:

        -   Triển khai ứng dụng cho từng nền tảng được hỗ trợ thông qua các liên kết web, MSI và/hoặc liên kết sâu.

        -   Triển khai Office ProPlus trên thiết Windows 10 của bạn.

        -   Các chương trình mua hàng số lượng lớn cho việc triển khai ứng dụng, bao gồm VPP của Apple, Windows Store cho Doanh nghiệp và Play cho Work Store của Google.

        -   Triển khai email, mạng không dây và hồ sơ VPN nếu bạn hiện có cơ quan cấp chứng chỉ, cơ sở Wi-Fi hoặc VPN trong tổ chức của mình.

        -   Thiết lập Bộ nối Microsoft Intune Exchange nối Mới (nếu có).

        -   Cấu hình thiết bị cho nền tảng thiết bị được hỗ trợ.

    -   Thiết lập chính sách truy nhập có điều kiện.

    -   Đặt cấu hình và triển khai các chính sách bảo vệ ứng dụng của Intune cho từng nền tảng được hỗ trợ.

    -   Chuẩn bị các ứng dụng dòng nghiệp vụ (LOB) cho chính sách bảo vệ ứng dụng Intune, kèm theo hướng dẫn về các tùy chọn khả dụng.

    -   Đăng ký thiết bị của mỗi nền tảng được hỗ trợ vào Intune hoặc Trình quản lý Cấu hình Microsoft Intune vụ.

    -   Kết nối với Nhà kho Dữ liệu Intune.

    -   Tích hợp Intune với:
        -   Trình xem Nhóm để được trợ giúp từ xa (bắt buộc phải có đăng ký Trình xem Nhóm).

        -   Phần mềm Bảo vệ Mối đe dọa Di động (Yêu cầu phải có gói đăng ký giải pháp đối tác Chống Mối đe dọa Di động (Thuê bao giải pháp đối tác Chống Mối đe dọa Di động).

        -   Telecom expense management solutions (Telecom expense management solution subscription is required).

        -   Tính năng Chống Mối đe dọa Nâng cao của Bộ bảo vệ Microsoft (bắt Windows E5 hoặc Microsoft 365 E5 phải có giấy phép).

    -   Cấu hình Cập nhật phần mềm cho các nền tảng được hỗ trợ áp dụng.

    -   Tài nguyên cho việc lập kế hoạch tiếp nhận người dùng.

- Thiết lập Windows AutoPilot:

    - Đặt cấu hình và thiết Microsoft Intune cho Windows Autopilot.

    - Đặt cấu hình cho các nhóm động Azure AD

    - Thêm thương hiệu Công ty của bạn vào Azure AD.

    - Tạo và gán thiết bị cho Windows hồ sơ Autopilot (ví dụ: một hồ sơ Windows Autopilot giới hạn việc tạo tài khoản Người quản trị Cục bộ).

    - Tùy chỉnh trải nghiệm sử dụng ngay (OOBE) để tuân thủ các yêu cầu của tổ chức.

    - Đặt cấu hình Tự động đăng ký MDM trong Azure AD và Intune.

    > [!NOTE]
    > Việc thiết Windows Dụng Autopilot bên ngoài Intune không thuộc phạm vi dành cho lợi ích FastTrack.

### <a name="enable-phase---cloud-attach"></a>Cho phép giai đoạn - Đính kèm đám mây

Cung cấp hướng dẫn về:

-   Cấp phép cho người dùng cuối của bạn.

-   Triển khai việc đính kèm đám mây trong bảng điều khiển Trình quản lý Cấu hình.

-   Thêm người dùng vào đăng ký Intune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị (nếu chưa cài đặt Intune).

-   Thiết lập kết hợp Azure Active Directory Gia nhập.

-   Thiết lập đăng Azure Active Directory cho tự động đăng ký MDM.

-   Thiết lập Cổng kết nối Quản lý Đám mây.

-   Thêm người dùng vào đăng ký Intune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.

-   Chuẩn bị dịch vụ Intune để quản lý thiết bị.

-   Đặt thẩm quyền quản lý thiết bị di động (MDM) thành Intune.

-   Cấu hình các nhóm kiểm tra được dùng để xác thực chính sách quản lý MDM.

-   Dẫn hướng cổng thông tin quản trị Intune để định vị thông tin trên người dùng và thiết bị.

-   Thiết lập vai trò Intune (toán tử bộ trợ giúp, người quản trị, v.v.).

-   Đăng ký thiết Windows 10 của bạn vào Intune.

-   Chuyển đổi khối lượng công việc để quản lý bằng Intune như mong muốn.

### <a name="enable-phase--azure-information-protection"></a>Giai đoạn Bật – Azure Information Protection

Hướng dẫn được cung cấp về: 

- Kích hoạt và cấu hình đối tượng thuê khách hàng.

- Tạo và thiết lập nhãn và chính sách.

- Áp dụng bảo vệ thông tin cho tài liệu. 

- Tự động phân loại và đánh nhãn thông tin trong các ứng dụng Office (như Word, PowerPoint, Excel và Outlook) chạy trên Windows và sử dụng máy khách Azure Information Protection.

- Khi sử dụng tệp khi lưu trữ với trình quét Azure Information Protection.

- Giám sát email khi truyền bằng Exchange Online tắc dòng thư.

Hướng dẫn cũng được cung cấp cho khách hàng muốn áp dụng bảo vệ bằng microsoft Azure Rights Management Services (Azure RMS), Mã hóa Thư Office 365 (OME) và ngăn mất dữ liệu (DLP).

> [!NOTE]
> **Bạn muốn tìm hiểu thêm?** xem [Enterprise Mobility + Security](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Các bước tiếp theo

[Lợi ích FastTrack cho EMS - Trách nhiệm của bạn](EMS-your-responsibilities.md)

