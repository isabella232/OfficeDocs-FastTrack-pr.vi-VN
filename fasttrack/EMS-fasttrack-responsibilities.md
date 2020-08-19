---
title: Các trách nhiệm FastTrack
description: Các trách nhiệm của FastTrack khi khách hàng sử dụng lợi ích Trung tâm FastTrack cho EMS
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
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b9af4c976df7f847643f0a833a0947f0a151e3dd
ms.sourcegitcommit: 1b2242be54dd0d000c6384f45f18e1951c31998b
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46800446"
---
# <a name="fasttrack-responsibilities"></a>Trách nhiệm của FastTrack

> [!CAUTION]
> Nội dung này không còn hiện tại và được lên lịch để loại bỏ. Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.

FastTrack có các trách nhiệm sau trong onboarding.

## <a name="general"></a>Thống

-   Cung cấp hỗ trợ từ xa cho bạn để có được các hoạt động cấu hình bắt buộc như được liệt kê trong mô tả giai đoạn chi tiết.

-   Cung cấp tài liệu hướng dẫn, công cụ phần mềm và bảng điều khiển quản trị để giúp bạn giảm hoặc loại bỏ các tác vụ cấu hình.

## <a name="initiate-phase"></a>Giai đoạn bắt đầu

-   Làm việc với bạn để bắt đầu onboarding.

-   Xác định những dịch vụ đủ điều kiện nào bạn muốn lên tàu.

## <a name="assess-phase"></a>Đánh giá giai đoạn

-   Cung cấp tổng quan về quản trị.

-   Cung cấp hướng dẫn về:

    -   Nhu cầu DNS, mạng và cơ sở hạ tầng.

    -   Nhu cầu máy khách (trình duyệt Internet, Hệ điều hành máy khách và nhu cầu của các dịch vụ).

    -   Nhận dạng và cung cấp người dùng.

    -   Cho phép các dịch vụ đủ điều kiện đã được mua và được xác định là một phần của onboarding.

-   Thiết lập đường thời gian cho các hoạt động khắc phục.

-   Cung cấp một danh sách kiểm tra đã khắc phục cho cả InTune và Azure AD Premium.

## <a name="remediate-phase"></a>Giai đoạn khắc phục

-   Giữ cuộc gọi hội thảo với bạn theo lịch biểu được thoả thuận để xem xét tiến độ của các hoạt động khắc phục sự cố, ví dụ: hướng dẫn bạn thông qua các site trước khi cài đặt trước khi triển khai một dịch vụ điện toán đám mây Microsoft.

## <a name="enable-phase"></a>Bật giai đoạn
Cung cấp hướng dẫn về:

-   Kích hoạt đăng ký hoặc thuê bao dịch vụ Microsoft Online của bạn.

-   Cấu hình giao thức TCP/IP và cổng tường lửa.

-   Cấu hình DNS cho các dịch vụ đủ điều kiện.

-   Xác thực kết nối với các dịch vụ trực tuyến của Microsoft.

-   Đối với một môi trường rừng đơn:

    -   Cài đặt máy chủ đồng bộ hóa thư mục giữa các dịch vụ miền Active Directory (AD DS) và các dịch vụ Microsoft Online đủ điều kiện (chỉ có hướng dẫn nếu cần thiết).

    -   Cấu hình xác thực được quản lý (đồng bộ hóa hash mật khẩu hoặc thông qua xác thực) với công cụ Azure Active Directory Connect. (chỉ hướng dẫn nếu bắt buộc).

        > [!NOTE]
        > Phát triển và thực thi các phần mở rộng quy tắc tùy chỉnh nằm ngoài phạm vi.

-   Đối với một rừng đơn khi các danh tính được liên kết: cài đặt và cấu hình dịch vụ liên kết Active Directory (AD FS) để xác thực tên miền cục bộ với InTune trong một site đơn, cấu hình không khoan dung, nếu cần thiết.

    > [!NOTE]
    > Đối với tất cả các cấu hình rừng, triển khai AD FS bị hết phạm vi.

-   Kiểm tra chức năng đăng nhập đơn (SSO), nếu được triển khai.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Cho phép giai đoạn-Microsoft Azure Active Directory Premium

Cung cấp hướng dẫn về:

- Kích hoạt Azure AD Premium đối tượng thuê của bạn.

- Cấu hình cổng tường lửa.

- Cấu hình DNS cho các dịch vụ đủ điều kiện.

- Xác nhận kết nối với Azure AD Premium Services.

- Đối với một môi trường rừng đơn:

  -   Cài đặt đồng bộ hóa thư mục giữa các dịch vụ miền Active Directory (AD DS) và Azure AD Connect, nếu được yêu cầu.

  -   Cấu hình phương pháp xác thực (đồng bộ hóa băm mật khẩu hoặc thông qua xác thực) bằng công cụ Azure AD Connect.

- Đối với một môi trường nhiều rừng:

  -   Cài đặt đồng bộ hóa Azure AD Connect, thiết lập cho nhiều kịch bản rừng.
- Đối với môi trường một và nhiều rừng:
  - Đặt cấu hình Azure Active Directory Pass-thông qua xác thực, nếu cần thiết.
  - Đặt cấu hình Azure Active Directory liền mạch đăng nhập đơn (SSO), nếu được yêu cầu.
    > [!NOTE]
    > Thông qua xác thực Azure Active Directory cho môi trường nhiều rừng được hỗ trợ nếu có tin cậy rừng giữa các khu rừng Active Directory và nếu định tuyến hậu tố tên được cấu hình đúng. Các đại diện bổ sung có thể được cài đặt tại nhiều máy chủ tại chỗ để cung cấp khả năng sẵn dùng cao cho các yêu cầu đăng nhập.

  - Để biết thêm thông tin, hãy xem mục [Azure Active Directory Pass-thông qua xác thực: bắt đầu nhanh](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) và [Azure Active Directory liền mạch Single đăng nhập: bắt đầu nhanh](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Để biết thêm thông tin về giới hạn xác thực Pass-through, hãy xem [Azure Active Directory Pass-thông qua xác thực: hạn chế hiện tại](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Để biết thêm thông tin về các vấn đề về SSO liền mạch, hãy xem [khắc phục sự cố trong Azure Active Directory liền mạch Single đăng nhập](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Đồng bộ hóa Hash và mật khẩu được hỗ trợ nhiều rừng. Tuy nhiên, các kịch bản không được hỗ trợ khác.

  - Đặt cấu hình đồng bộ giữa các khu rừng Active Directory tại cơ sở và thư mục Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Phát triển và thực thi các phần mở rộng quy tắc tùy chỉnh nằm ngoài phạm vi.

- Đối với một rừng đơn khi các danh tính được liên kết:

  -   Cài đặt và cấu hình AD FS để xác thực tên miền cục bộ với Azure AD Premium trong một site đơn, cấu hình không khoan dung (nếu bắt buộc).

  > [!NOTE]
  > Đối với tất cả các cấu hình rừng, triển khai AD FS bị hết phạm vi.

- Kiểm tra chức năng SSO (nếu được triển khai).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Kích hoạt hàm Phase-Azure AD Premium-với Azure AD Connect và AD FS

Cung cấp hướng dẫn về việc thiết lập:

- Cung cấp người dùng, bao gồm cấp phép.

- Đồng bộ hóa thư mục Azure AD Connect (với mật khẩu writeback và đồng bộ hash mật khẩu).

  - Đặt lại mật khẩu công cụ dịch vụ Azure Active Directory (SSPR).

  - Xác thực đa yếu tố Azure.

  - Tối đa ba (3) hoặc nhiều phần mềm dưới dạng tích hợp ứng dụng dịch vụ (SaaS) với đăng nhập đơn (SSO) từ [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Cung cấp người dùng tự động cho các ứng dụng SaaS được tích hợp sẵn như được liệt kê trong [danh sách hướng dẫn tích hợp ứng dụng](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list), chỉ giới hạn cung cấp đi.

  - Màn hình đăng nhập tùy chỉnh, bao gồm Logo, văn bản và hình ảnh.

  - Tự phục vụ và nhóm động (nhóm).

  - Dữ liệu ứng dụng Azure Active Directory.

  - Azure Active Directory kết nối tình trạng.

  - Truy nhập có điều kiện Azure Active Directory.

  - Điều khoản sử dụng Azure Active Directory.

  - Bảo vệ chứng danh Azure Active Directory.

  - Quản lý định danh Azure Active Directory đặc quyền.

  - Đánh giá truy nhập thư mục Azure Active Directory.

  -   Bảo vệ bằng mật khẩu Azure Active Directory.

  -   Azure Active Directory B2B.

### <a name="enable-phase---intune"></a>Bật giai đoạn-InTune

> [!IMPORTANT]
> FastTrack không hỗ trợ quản lý PC cổ điển của Windows 10 bằng InTune. FastTrack chỉ hỗ trợ quản lý Windows 10 thông qua quản lý thiết bị di động InTune (MDM).

Cung cấp hướng dẫn về:

-   Cấu hình các định danh được sử dụng bởi InTune, bằng cách tận dụng Active Directory tại chỗ của bạn hoặc danh tính đám mây (Azure Active Directory).

-   Cấp phép người dùng cuối của bạn.

-   Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.

-   Đặt cấu hình quyền quản lý thiết bị di động của bạn MDM), dựa trên nhu cầu quản lý của bạn, bao gồm:

    -   Đặt InTune làm cơ quan MDM của bạn.

    -   Cấu hình các nhóm kiểm tra để được dùng để xác thực các chính sách quản lý MDM.

    -   Dẫn hướng cổng thông tin quản trị InTune để định vị thông tin về người dùng và thiết bị.

    -   Thiết lập các vai trò InTune (toán tử bộ phận trợ giúp, người quản trị, v.v.)

    -   Cấu hình chính sách và dịch vụ quản lý MDM như:

        -   Triển khai ứng dụng cho từng nền tảng được hỗ trợ thông qua các nối kết web, MSI và/hoặc liên kết sâu.

        -   Triển khai Office ProPlus lên các thiết bị chạy Windows 10.

        -   Các chương trình mua âm lượng cho triển khai ứng dụng, bao gồm VPP, Windows Store for Business và Google Play for work Store.

        -   Triển khai email, mạng không dây và hồ sơ VPN nếu bạn có một cơ quan cấp chứng chỉ hiện có, Wi-Fi hoặc cơ sở hạ tầng VPN trong tổ chức của bạn.

        -   Thiết lập trình kết nối Exchange của Microsoft InTune (khi áp dụng).

        -   Hồ sơ cấu hình thiết bị cho nền tảng thiết bị được hỗ trợ.

    -   Thiết lập các chính sách truy nhập có điều kiện.

    -   Cấu hình và triển khai các chính sách bảo vệ ứng dụng InTune cho từng nền tảng được hỗ trợ.

    -   Chuẩn bị các ứng dụng line-of-Business (LOB) cho các chính sách bảo vệ ứng dụng InTune, với hướng dẫn về các tùy chọn sẵn có.

    -   Các thiết bị đăng ký của mỗi nền tảng được hỗ trợ vào trình quản lý InTune hoặc cấu hình với Microsoft InTune Service.

    -   Kết nối với kho dữ liệu InTune.

    -   Đang tích hợp InTune với:
        -   Trình xem nhóm để được hỗ trợ từ xa (yêu cầu đăng ký trình xem nhóm).

        -   Giải pháp đối tác phòng thủ đe dọa điện thoại di động (yêu cầu gói đăng ký giải pháp đối tác điện thoại di động).

        -   Các giải pháp quản lý chi phí viễn thông (yêu cầu đăng ký giải pháp quản lý chi phí viễn thông).

        -   Microsoft Defender Advanced Threat Protection (Windows E5 hoặc Microsoft 365 E5 giấy phép là bắt buộc).

    -   Cấu hình các bản cập nhật phần mềm cho các nền tảng được hỗ trợ.

    -   Lập kế hoạch cho việc áp dụng tài nguyên của người dùng.

- Thiết lập Autopilot Windows:

    - Cấu hình và thiết lập Microsoft InTune cho Windows Autopilot.

    - Đặt cấu hình cho các nhóm động của Azure AD

    - Thêm thương hiệu công ty của bạn vào Azure AD.

    - Tạo và gán các thiết bị cho các hồ sơ Autopilot của Windows (ví dụ hồ sơ Autopilot của Windows hạn chế tạo tài khoản người quản trị cục bộ).

    - Tùy chỉnh trải nghiệm vắng mặt (OOBE) để tuân thủ các yêu cầu của tổ chức.

    - Cấu hình MDM tự động đăng ký trong Azure AD và InTune.

    > [!NOTE]
    > Thiết lập bộ điều hợp Windows Autopilot ngoài InTune nằm ngoài phạm vi cho lợi ích FastTrack.

### <a name="enable-phase---cloud-attach"></a>Bật theo giai đoạn-điện toán đám mây

Cung cấp hướng dẫn về:

-   Cấp phép người dùng cuối của bạn.

-   Triển khai điện toán đám mây trong bảng điều khiển trình quản lý cấu hình.

-   Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị (nếu InTune không được cài đặt).

-   Thiết lập kết hợp Azure Active Directory gia nhập.

-   Thiết lập Azure Active Directory cho MDM tự động đăng ký.

-   Thiết lập cổng kết nối quản lý đám mây.

-   Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.

-   Chuẩn bị dịch vụ InTune để quản lý thiết bị.

-   Thiết đặt cơ quan quản lý thiết bị di động (MDM) để InTune.

-   Cấu hình các nhóm kiểm tra để được dùng để xác thực các chính sách quản lý MDM.

-   Dẫn hướng cổng thông tin quản trị InTune để định vị thông tin về người dùng và thiết bị.

-   Thiết lập các vai trò InTune (toán tử helpdesk, người quản trị, v.v.).

-   Đăng ký các thiết bị chạy Windows 10 thành InTune.

-   Chuyển đổi công việc để quản lý bằng cách InTune như mong muốn.

### <a name="enable-phase--azure-information-protection"></a>Cho phép bảo vệ thông tin giai đoạn – Azure

Đã cung cấp hướng dẫn về: 

- Kích hoạt và cấu hình đối tượng thuê khách hàng.

- Tạo và thiết lập nhãn và chính sách.

- Áp dụng bảo vệ thông tin cho tài liệu. 

- Tự động phân loại và ghi nhãn thông tin trong các ứng dụng Office (chẳng hạn như Word, PowerPoint, Excel và Outlook) đang chạy trên Windows và sử dụng máy khách bảo vệ thông tin Azure.

- Sử dụng tệp tại phần còn lại bằng máy quét bảo vệ thông tin Azure.

- Giám sát email trong quá cảnh bằng quy tắc dòng thư Exchange Online.

Hướng dẫn cũng được cung cấp cho những khách hàng muốn áp dụng bảo vệ bằng cách sử dụng dịch vụ quản lý quyền Microsoft Azure (Azure RMS), mã hóa thư Office 365 (OME), và ngăn chặn dữ liệu (maát).

> [!NOTE]
> Bạn **muốn tìm hiểu thêm?** Xem mục tính năng [di động doanh nghiệp + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Các bước tiếp theo

[Lợi ích FastTrack cho EMS-trách nhiệm của bạn](EMS-your-responsibilities.md)

