---
title: Các trách nhiệm của FastTrack
description: Trách nhiệm của FastTrack khi khách hàng đang sử dụng lợi ích Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 4/01/2020
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b87d85269cde92e90dd127bfa717d16ed9036484
ms.sourcegitcommit: f2b9cb334c7687724c36b1c38ba24463576233bf
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/01/2020
ms.locfileid: "43097724"
---
# <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

FastTrack có các trách nhiệm sau đây trong quá trình onboarding.

## <a name="general"></a>Chung

-   Cung cấp hỗ trợ từ xa cho bạn các hoạt động cấu hình yêu cầu như được liệt kê trong mô tả giai đoạn chi tiết.

-   Cung cấp tài liệu có sẵn, công cụ phần mềm và bàn điều khiển quản trị để giúp bạn giảm hoặc loại bỏ các tác vụ cấu hình.

## <a name="initiate-phase"></a>Bắt đầu giai đoạn

-   Làm việc với bạn để bắt đầu onboarding.

-   Xác định các dịch vụ đủ điều kiện mà bạn muốn lên trên.

## <a name="assess-phase"></a>Đánh giá giai đoạn

-   Cung cấp tổng quan quản trị.

-   Cung cấp hướng dẫn về:

    -   DNS, mạng và nhu cầu cơ sở hạ tầng.

    -   Nhu cầu của khách hàng (trình duyệt Internet, Hệ điều hành khách hàng và nhu cầu dịch vụ).

    -   Nhận dạng và cung cấp người dùng.

    -   Cho phép các dịch vụ đủ điều kiện được mua và định nghĩa là một phần của bộ nhớ ngoài.

-   Thiết lập Timeline để khắc phục các hoạt động.

-   Cung cấp danh sách kiểm tra khắc phục cho cả InTune và Azure AD Premium.

## <a name="remediate-phase"></a>Giai đoạn remediate

-   Giữ cuộc gọi hội nghị với bạn theo lịch trình đã thoả thuận để đánh giá tiến độ của các hoạt động khắc phục, ví dụ, hướng dẫn bạn thông qua cài đặt pre-requisites trước khi bộ nhớ ngoài một dịch vụ đám mây của Microsoft.

## <a name="enable-phase"></a>Kích hoạt giai đoạn
Cung cấp hướng dẫn về:

-   Kích hoạt đăng ký hoặc thuê dịch vụ trực tuyến của Microsoft.

-   Cấu hình giao thức TCP/IP và cổng tường lửa.

-   Cấu hình DNS cho các dịch vụ đủ điều kiện.

-   Xác nhận kết nối với các dịch vụ trực tuyến của Microsoft.

-   Môi trường một nhóm đơn:

    -   Cài đặt máy chủ đồng bộ hóa thư mục giữa dịch vụ miền Active Directory (AD DS) và các dịch vụ trực tuyến Microsoft đủ điều kiện (chỉ hướng dẫn nếu cần).

    -   Cấu hình quản lý xác thực (mật khẩu băm đồng bộ hóa hoặc xác thực chuyển qua) với công cụ Azure Active Directory kết nối. (chỉ hướng dẫn nếu cần).

        > [!NOTE]
        > Phát triển và thực hiện cho phần mở rộng quy tắc tùy chỉnh được ra khỏi phạm vi.

-   Đối với một nhóm duy nhất khi mục tiêu được liên kết nhận dạng: cài đặt và cấu hình dịch vụ Active Directory Federation (AD FS) để xác thực miền địa phương với InTune trong một trang web đơn, lỗi chịu cấu hình, nếu cần thiết.

    > [!NOTE]
    > Đối với tất cả nhiều nhóm cấu hình, AD FS triển khai trong phạm vi.

-   Thử nghiệm một chức năng đăng nhập (SSO), nếu đã triển khai.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Kích hoạt giai đoạn-Microsoft Azure Active Directory Premium

Cung cấp hướng dẫn về:

- Kích hoạt đối tượng thuê Azure AD Premium của bạn.

- Cấu hình cổng tường lửa.

- Cấu hình DNS cho các dịch vụ đủ điều kiện.

- Phê chuẩn kết nối với dịch vụ Azure AD Premium.

- Môi trường một nhóm đơn:

  -   Cài đặt đồng bộ hóa thư mục giữa dịch vụ miền Active Directory (AD DS) và Azure AD kết nối, nếu cần.

  -   Cấu hình một phương pháp xác thực (mật khẩu Hash Sync hoặc xác thực chuyển qua) với công cụ Azure AD kết nối.

- Đối với một môi trường nhiều nhóm:

  -   Cài đặt đồng bộ hóa Azure AD kết nối, thiết lập cho nhiều trường hợp nhóm.
- Đối với môi trường một và nhiều nhóm:
  - Cấu hình Azure Active Directory vượt qua xác thực, nếu cần thiết.
  - Cấu hình Azure Active Directory liền mạch đăng nhập đơn (SSO), nếu cần thiết.
    > [!NOTE]
    > Azure Active Directory vượt qua xác thực cho nhiều nhóm môi trường được hỗ trợ nếu có độ tin cậy nhóm giữa rừng Active Directory của bạn và nếu hậu tố tên định tuyến được cấu hình đúng. Các tác nhân bổ sung có thể được cài đặt trên nhiều máy chủ tại chỗ để cung cấp tính khả dụng cao cho yêu cầu đăng nhập.

  - Để biết thêm thông tin, hãy xem [Azure Active Directory vượt qua xác thực: bắt đầu nhanh](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) và [Azure Active Directory liền mạch đăng nhập đơn: bắt đầu nhanh](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Để biết thêm thông tin về vượt qua giới hạn xác thực, xem [Azure Active Directory vượt qua xác thực: giới hạn hiện tại](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Để biết thêm thông tin về các vấn đề liền mạch SSO, [hãy xem khắc phục sự cố Azure Active Directory liền mạch đăng nhập đơn](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Mật khẩu băm đồng bộ hóa và mật khẩu ghi lại hỗ trợ nhiều khu rừng. Tuy nhiên, kịch bản ghi lại khác không được hỗ trợ.

  - Cấu hình đồng bộ hóa giữa các khu rừng Active Directory tại chỗ và thư mục Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Phát triển và thực hiện cho phần mở rộng quy tắc tùy chỉnh được ra khỏi phạm vi.

- Đối với một nhóm duy nhất khi mục tiêu được liên kết danh tính:

  -   Cài đặt và cấu hình AD FS để xác thực miền địa phương với Azure AD Premium trong một trang web đơn, lỗi khoan dung cấu hình (nếu cần).

  > [!NOTE]
  > Đối với tất cả nhiều nhóm cấu hình, AD FS triển khai trong phạm vi.

- Kiểm tra chức năng SSO (nếu triển khai).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Kích hoạt giai đoạn-Azure AD Premium-Azure AD kết nối và AD FS

Cung cấp hướng dẫn về cách thiết lập:

- Người dùng cung cấp, bao gồm cả giấy phép.

- Đồng bộ hóa thư mục Azure AD kết nối (mật khẩu ghi lại và đồng bộ hóa mật khẩu băm).

  - Azure Active Directory tự dịch vụ mật khẩu đặt lại (SSPR).

  - Azure nhiều yếu tố xác thực.

  - Tối đa ba (3) hoặc nhiều phần mềm dưới dạng tích hợp ứng dụng dịch vụ (SaaS) với đăng nhập đơn (SSO) từ [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Tự động cung cấp người dùng cho các ứng dụng SaaS tích hợp sẵn như được liệt kê trong [danh sách hướng dẫn tích hợp ứng dụng](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), chỉ giới hạn ở việc cung cấp bên ngoài.

  - Màn hình đăng nhập tùy chỉnh, bao gồm Logo, văn bản và hình ảnh.

  - Tự dịch vụ và nhóm năng động (nhóm).

  - Proxy ứng dụng Azure Active Directory.

  - Azure Active Directory kết nối y tế.

  - Truy cập có điều kiện Azure Active Directory.

  - Điều khoản sử dụng Azure Active Directory.

  - Azure Active Directory danh tính bảo vệ.

  - Azure Active Directory đặc quyền quản lý danh tính.

  - Azure Active Directory truy cập đánh giá.

  -   Bảo vệ mật khẩu Azure Active Directory.

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>Kích hoạt pha-InTune

> [!IMPORTANT]
> FastTrack không hỗ trợ quản lý Windows 10 Classic PC với InTune. FastTrack chỉ hỗ trợ quản lý Windows 10 thông qua InTune quản lý thiết bị di động (MDM).

Cung cấp hướng dẫn về:

-   Cấu hình các nhận dạng được sử dụng bởi InTune, bằng một trong hai trên cơ sở Active Directory hoặc danh tính đám mây (Azure Active Directory).

-   Cấp phép người dùng cuối của bạn.

-   Thêm người dùng vào đăng ký InTune của bạn, xác định vai trò quản trị viên CNTT, và tạo người dùng và nhóm thiết bị.

-   Cấu hình cơ quan MDM quản lý thiết bị di động của bạn, dựa trên nhu cầu quản lý của bạn, bao gồm:

    -   Thiết lập InTune là cơ quan MDM của bạn.

    -   Cấu hình nhóm kiểm tra được sử dụng để xác nhận chính sách quản lý MDM.

    -   Điều hướng cổng quản trị InTune để định vị thông tin về người dùng và thiết bị.

    -   Thiết lập vai trò InTune (nhà điều hành bàn trợ giúp, quản trị viên, v.v.)

    -   Cấu hình chính sách quản lý MDM và các dịch vụ như:

        -   Triển khai ứng dụng cho mỗi nền tảng được hỗ trợ thông qua liên kết web, MSI và/hoặc liên kết sâu.

        -   Triển khai Office ProPlus trên các thiết bị chạy Windows 10.

        -   Chương trình mua hàng cho triển khai ứng dụng, bao gồm VPP của Apple, Windows Store dành cho doanh nghiệp và Play for work Store của Google.

        -   Triển khai e-mail, mạng không dây và cấu hình VPN nếu bạn có cơ quan chứng nhận hiện tại, cơ sở hạ tầng Wi-Fi hoặc VPN trong tổ chức của bạn.

        -   Thiết lập Microsoft InTune Exchange Connector (khi áp dụng).

        -   Cấu hình thiết bị cho nền tảng thiết bị được hỗ trợ.

    -   Thiết lập chính sách truy cập có điều kiện.

    -   Cấu hình và triển khai chính sách bảo vệ ứng dụng InTune cho mỗi nền tảng được hỗ trợ.

    -   Chuẩn bị các ứng dụng line-of-Business (LOB) cho các chính sách bảo vệ ứng dụng InTune, với hướng dẫn về các tùy chọn có sẵn.

    -   Đăng ký thiết bị của mỗi nền tảng được hỗ trợ để InTune hoặc Configuration Manager của bạn với Microsoft InTune dịch vụ.

    -   Kết nối với InTune Data Warehouse.

    -   Tích hợp InTune với:
        -   Team Viewer để được hỗ trợ từ xa (yêu cầu đăng ký Team Viewer).

        -   Giải pháp đối tác di động Threat Defense (yêu cầu đăng ký giải pháp đối tác đe dọa điện thoại di động).

        -   Giải pháp quản lý chi phí viễn thông (đăng ký giải pháp quản lý chi phí viễn thông là bắt buộc).

        -   Yêu cầu bảo vệ chống mối đe dọa nâng cao của Microsoft Defender (các giấy phép Windows E5 hoặc Microsoft 365 E5).

    -   Cấu hình các bản cập nhật phần mềm cho các nền tảng được hỗ trợ áp dụng.

    -   Tài nguyên cho kế hoạch nhận con nuôi của người dùng.

- Thiết lập Windows Autopilot:

    - Cấu hình và thiết lập Microsoft InTune cho Windows Autopilot.

    - Cấu hình nhóm động Azure AD

    - Thêm thương hiệu công ty của bạn vào Azure AD.

    - Tạo và gán thiết bị cho cấu hình Windows Autopilot (ví dụ: hồ sơ Windows Autopilot hạn chế tạo tài khoản quản trị viên cục bộ).

    - Tuỳ chỉnh out-of-Box-kinh nghiệm (OOBE) để tuân thủ các yêu cầu của tổ chức.

    - Cấu hình MDM tự động đăng ký Azure AD và InTune.

    > [!NOTE]
    > Thiết lập Windows Autopilot bên ngoài InTune nằm ngoài phạm vi cho lợi ích FastTrack.

### <a name="enable-phase---cloud-attach"></a>Kích hoạt giai đoạn-đính kèm đám mây

Cung cấp hướng dẫn về:

-   Cấp phép người dùng cuối của bạn.

-   Triển khai đám mây đính kèm trong bảng điều khiển quản lý cấu hình.

-   Thêm người dùng vào đăng ký InTune của bạn, xác định vai trò quản trị viên CNTT và tạo nhóm người dùng và thiết bị (nếu InTune không được cài đặt).

-   Thiết lập kết hợp Azure Active Directory tham gia.

-   Thiết lập Azure Active Directory MDM đăng ký tự động.

-   Thiết lập cổng quản lý đám mây.

-   Thêm người dùng vào đăng ký InTune của bạn, xác định vai trò quản trị viên CNTT, và tạo người dùng và nhóm thiết bị.

-   Chuẩn bị dịch vụ InTune để quản lý thiết bị.

-   Thiết lập quyền quản lý thiết bị di động (MDM) để InTune.

-   Cấu hình nhóm kiểm tra được sử dụng để xác nhận chính sách quản lý MDM.

-   Điều hướng cổng quản trị InTune để định vị thông tin về người dùng và thiết bị.

-   Thiết lập InTune vai trò (nhà điều hành, quản trị viên, và như vậy).

-   Đăng ký thiết bị Windows 10 để InTune.

-   Chuyển khối lượng công việc để quản lý bằng InTune như mong muốn.

### <a name="enable-phase--azure-information-protection"></a>Kích hoạt giai đoạn-bảo vệ thông tin Azure

Cung cấp hướng dẫn về: 

- Kích hoạt và cấu hình đối tượng thuê khách hàng.

- Tạo và thiết lập nhãn và chính sách.

- Áp dụng bảo vệ thông tin cho các tài liệu. 

- Tự động phân loại và ghi nhãn thông tin trong các ứng dụng Office (như Word, PowerPoint, Excel và Outlook) chạy trên Windows và sử dụng khách hàng bảo vệ thông tin Azure.

- Sử dụng tệp ở phần còn lại với máy quét Azure Information Protection.

- Giám sát email trong quá trình sử dụng quy tắc luồng thư Exchange Online.

Hướng dẫn cũng được cung cấp cho khách hàng muốn áp dụng bảo vệ bằng cách sử dụng Microsoft Azure quyền quản lý Dịch vụ (Azure RMS), văn phòng 365 mã hóa thư (OME) và ngăn mất dữ liệu (DLP).

> [!NOTE]
> **Muốn tìm hiểu thêm?** xem [doanh nghiệp di động + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Các bước tiếp theo

[FastTrack lợi ích cho EMS-trách nhiệm của bạn](EMS-your-responsibilities.md)

