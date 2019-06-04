---
title: Trách nhiệm của FastTrack
description: Trách nhiệm của FastTrack khi khách hàng đang sử dụng lợi ích Trung tâm FastTrack cho EMS
keywords: ''
author: andredm7
ms.author: andredm
manager: ''
ms.date: 06/04/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: c8fd871e-f1bc-43ec-a5f3-ad025df9b026
ms.reviewer: ''
ms.suite: ems
ms.openlocfilehash: b4444aae990b064cf6b22921d897e0bd948f6ed1
ms.sourcegitcommit: 0e76ab0f36619dee923201098936573be14b4560
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/03/2019
ms.locfileid: "34673464"
---
# <a name="fasttrack-responsibilities"></a>Trách nhiệm FastTrack

FastTrack có trách nhiệm sau đây trong onboarding.

## <a name="general"></a>Tổng quát

-   Trợ giúp từ xa hỗ trợ cho bạn cho các hoạt động yêu cầu cấu hình được liệt kê trong các mô tả chi tiết giai đoạn.

-   Cung cấp tài liệu hướng dẫn có sẵn, phần mềm và quản trị console để giúp bạn làm giảm hoặc loại bỏ cấu hình nhiệm vụ.

## <a name="initiate-phase"></a>Bắt đầu giai đoạn

-   Làm việc với bạn để bắt đầu onboarding.

-   Xác định dịch vụ đủ điều kiện mà bạn muốn đến trên tàu.

## <a name="assess-phase"></a>Đánh giá giai đoạn

-   Cung cấp một tổng quan về quản trị.

-   Cung cấp hướng dẫn về:

    -   Nhu cầu DNS, mạng lưới, và cơ sở hạ tầng.

    -   Nhu cầu khách hàng (trình duyệt Internet, Hệ điều hành của khách hàng và nhu cầu dịch vụ).

    -   Nhận dạng người dùng và cung cấp.

    -   Cho phép Dịch vụ đủ điều kiện được mua và được xác định là một phần của onboarding.

-   Thiết lập thời gian cho các hoạt động khắc phục.

-   Cung cấp một danh sách kiểm tra khắc phục cho cả hai dành và Azure quảng cáo phí bảo hiểm.

## <a name="remediate-phase"></a>Remediate giai đoạn

-   Giữ cuộc gọi hội nghị với bạn theo thỏa thuận lịch để xem xét sự tiến bộ của các hoạt động khắc phục, ví dụ, hướng dẫn bạn thông qua các cài đặt trước requisites trước khi onboarding một dịch vụ đám mây của Microsoft.

## <a name="enable-phase"></a>Sử giai đoạn
Cung cấp hướng dẫn về:

-   Cách kích hoạt Microsoft dịch vụ trực tuyến người thuê hoặc thuê bao của bạn.

-   Cấu hình giao thức TCP/IP và các bức tường lửa cảng.

-   Cấu hình DNS cho các dịch vụ đủ điều kiện.

-   Phê chuẩn kết nối đến dịch vụ trực tuyến của Microsoft.

-   Cho một môi trường duy nhất-rừng:

    -   Cài đặt một máy chủ đồng bộ hóa thư mục giữa của bạn hoạt động dịch vụ miền Active Directory (AD DS) và các hội đủ điều kiện trực tuyến dịch vụ của Microsoft (chỉ hướng dẫn nếu cần thiết).

    -   Cấu hình xác thực được quản lý (Sync Hash mật khẩu hoặc xác thực ñöôïc) với công cụ Azure Active Directory kết nối. (chỉ hướng dẫn nếu cần thiết).

        > [!NOTE]
        > Phát triển và thực hiện quy tắc tuỳ tiện ích mở rộng ra khỏi phạm vi.

-   Cho một khu rừng duy nhất khi mục tiêu là đã liên kết bản sắc: cài đặt và cấu hình các dịch vụ liên bang Active Directory (AD FS) cho xác thực miền địa phương với dành trong một cấu hình trang web duy nhất, chịu lỗi, nếu cần thiết.

    > [!NOTE]
    > Đối với tất cả các cấu hình rừng nhiều, triển khai AD FS là ra khỏi phạm vi.

-   Kiểm tra đơn đăng nhập (SSO) chức năng, nếu được triển khai.

### <a name="enable-phase---microsoft-azure-active-directory-premium"></a>Sử giai đoạn - Microsoft Azure Active Directory Premium

Cung cấp hướng dẫn về:

- Kích hoạt thuê nhà Azure quảng cáo phí bảo hiểm của bạn.

- Cấu hình tường lửa của cảng.

- Cấu hình DNS cho các dịch vụ đủ điều kiện.

- Phê chuẩn kết nối đến dịch vụ Azure quảng cáo đặc biệt.

- Cho một môi trường duy nhất-rừng:

  -   Cài đặt đồng bộ hóa thư mục giữa dịch vụ miền Active Directory (AD DS) và Azure quảng cáo kết nối, nếu cần thiết.

  -   Cấu hình một phương thức xác thực (Sync Hash mật khẩu hoặc xác thực ñöôïc) với công cụ Azure quảng cáo kết nối.

- Cho một môi trường rừng nhiều:

  -   Cài đặt đồng bộ hóa Azure quảng cáo kết nối, thiết lập cho kịch bản nhiều rừng.
- Cho môi trường rừng duy nhất và nhiều:
  - Cấu hình Azure Active Directory ñöôïc xác thực, nếu cần thiết.
  - Cấu hình Azure Active Directory liền mạch đơn đăng nhập (SSO), nếu cần thiết.
    > [!NOTE]
    > Azure Active Directory ñöôïc xác thực rừng nhiều môi trường được hỗ trợ nếu có tín thác rừng giữa rừng Active Directory của bạn và nếu tên hậu tố định tuyến được cấu hình đúng. Bổ sung các đại lý có thể được cài đặt trên nhiều máy chủ tại chỗ để cung cấp sẵn sàng cao cho các yêu cầu đăng nhập.

  - Để biết thêm thông tin, hãy xem [Azure Active Directory ñöôïc xác thực: nhanh chóng bắt đầu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-quick-start#step-1-check-prerequisites) và [Azure Active Directory liên tục đăng nhập đơn: nhanh chóng bắt đầu](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-sso-quick-start#step-1-check-prerequisites).
  - Để biết thêm chi tiết về giới hạn pass-through xác thực, hãy xem [Azure Active Directory ñöôïc xác thực: hạn chế hiện tại](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-pass-through-authentication-current-limitations).
  - Để biết thêm chi tiết về vấn đề này liền mạch SSO, hãy xem [Khắc phục sự cố Azure Active Directory liên tục đăng nhập đơn](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-troubleshoot-sso).

      > [!NOTE]
      > Đồng bộ hóa hash mật khẩu và mật khẩu writeback hỗ trợ nhiều rừng. Tuy nhiên, các trường hợp khác của writeback không được hỗ trợ.

  - Cấu hình đồng bộ hóa giữa rừng Active Directory tại chỗ và thư mục Microsoft Azure Active Directory Premium (Azure Active Directory).

    > [!NOTE]
    > Phát triển và thực hiện quy tắc tuỳ tiện ích mở rộng ra khỏi phạm vi.

- Đối với một khu rừng duy nhất khi mục tiêu là liên kết nhận dạng:

  -   Cài đặt và cấu hình các AD FS cho xác thực miền địa phương với Azure quảng cáo phí bảo hiểm trong một cấu hình trang web duy nhất, chịu lỗi (nếu cần).

  > [!NOTE]
  > Đối với tất cả các cấu hình rừng nhiều, triển khai AD FS là ra khỏi phạm vi.

- Thử nghiệm tính năng SSO (nếu triển khai).

### <a name="enable-phase---azure-ad-premium---with-azure-ad-connect-and-ad-fs"></a>Sử giai đoạn - Azure quảng cáo Premium - Azure quảng cáo kết nối và AD FS

Cung cấp hướng dẫn về thiết lập:

- Người sử dụng cung cấp, bao gồm cả cấp phép.

- Azure quảng cáo kết nối đồng bộ hoá directory (với mật khẩu writeback và mật khẩu băm sync).

  - Azure Active Directory tự vụ đặt lại mật khẩu (SSPR).

  - Azure nhiều yếu tố xác thực.

  - Đến ba (3) hoặc phần mềm như một dịch vụ (SaaS) ứng dụng tích hợp với các đơn đăng nhập (SSO) từ [Azure Active Directory Marketplace](https://azure.microsoft.com/marketplace/active-directory/).

  - Người sử dụng tự động cung cấp cho pre-tích hợp ứng dụng SaaS như được liệt kê trong [danh sách hướng dẫn ứng dụng tích hợp](https://docs.microsoft.com/en-us/azure/active-directory/saas-apps/tutorial-list), hạn chế để cung cấp ra bên ngoài chỉ.

  - Màn hình đăng nhập tùy chỉnh, bao gồm cả biểu tượng, văn bản và hình ảnh.

  - Năng động và tự phục vụ nhóm (nhóm).

  - Azure Active Directory ứng dụng Proxy.

  - Azure Active Directory kết nối y tế.

  - Azure Active Directory có điều kiện truy cập.

  - Azure Active Directory các điều khoản sử dụng.

  - Bảo vệ danh tính Azure Active Directory.

  - Azure Active Directory đặc quyền quản lý danh tính.

  - Các đánh giá truy cập vào Azure Active Directory.

### <a name="enable-phase---intune"></a>Sử giai đoạn - dành

> [!IMPORTANT]
> FastTrack không hỗ trợ quản lý Windows 10 PC cổ điển với dành. FastTrack chỉ hỗ trợ Windows 10 quản lý thông qua quản lý thiết bị di động dành (MDM).

Cung cấp hướng dẫn trên:

-   Cấu hình các danh tính được sử dụng bởi dành, hoặc tận dụng chỗ Active Directory hay đám mây danh tính của bạn (Azure Active Directory).

-   Cấp giấy phép người dùng cuối cùng của bạn.

-   Thêm người dùng để đăng ký của bạn dành, nó xác định vai trò quản trị, và tạo ra các nhóm người dùng và thiết bị.

-   Cấu hình của điện thoại di động thiết bị quản lý MDM) thẩm quyền, dựa trên nhu cầu quản lý của bạn, bao gồm:

    -   Thiết lập dành như thẩm quyền MDM của bạn.

    -   Cấu hình thử nghiệm nhóm sẽ được sử dụng để xác nhận MDM quản lý chính sách.

    -   Điều hướng cổng thông tin admin dành để định vị thông tin về người dùng và các thiết bị.

    -   Thiết lập vai trò dành (giúp bàn điều khiển, quản trị viên, vv)

    -   Cấu hình MDM quản lý chính sách và các dịch vụ như:

        -   Việc triển khai ứng dụng cho mỗi nền tảng được hỗ trợ thông qua các trang web liên kết, MSI và/hoặc liên kết sâu.

        -   Triển khai Office ProPlus lên thiết bị Windows 10.

        -   Khối lượng mua chương trình triển khai ứng dụng, bao gồm cả Apple VPP, Windows Store cho doanh nghiệp, và chơi của Google cho việc lưu trữ.

        -   Triển khai thư điện tử, mạng không dây và cấu hình VPN nếu bạn có một authority giấy chứng nhận hiện tại, cơ sở hạ tầng Wi-Fi hoặc VPN trong tổ chức của bạn.

        -   Lập trình Microsoft dành trao đổi kết nối (khi áp dụng).

        -   Điện thoại cấu hình cấu hình cho các nền tảng thiết bị được hỗ trợ.

    -   Thiết lập chính sách có điều kiện truy cập.

    -   Cấu hình và triển khai các chính sách bảo vệ app dành cho mỗi nền tảng được hỗ trợ.

    -   Chuẩn bị đường dây của doanh nghiệp (LOB) ứng dụng cho dành chính sách bảo vệ app, với sự hướng dẫn về tùy chọn có sẵn.

    -   Đăng ký các thiết bị của mỗi hỗ trợ nền tảng để dành hoặc cấu hình quản lý với Microsoft Intune dịch vụ của bạn.

    -   Kết nối với kho dữ liệu dành.

    -   Tích hợp dành với:
        -   Team Viewer để được hỗ trợ từ xa (Team Viewer đăng ký là bắt buộc).

        -   Giải pháp đối tác điện thoại di động đe dọa Quốc phòng (điện thoại di động đe dọa Quốc phòng đối tác giải pháp đăng ký là bắt buộc).

        -   Viễn thông giải pháp quản lý chi phí (viễn thông với chi phí quản lý giải pháp đăng ký là bắt buộc).

        -   Bảo vệ mối đe dọa nâng cao của Windows Defender (Windows E5 hoặc Microsoft 365 E5 giấy phép được yêu cầu).

    -   Cấu hình phần mềm Cập Nhật cho áp dụng các nền tảng được hỗ trợ.

    -   Tài nguyên cho người dùng thông qua kế hoạch.

- Thiết lập Windows Autopilot:

    - Cấu hình và thiết lập Microsoft Intune cho Windows Autopilot.

    - Đặt cấu hình nhóm năng động Azure quảng cáo

    - Thêm công ty của bạn, xây dựng thương hiệu vào Azure quảng cáo.

    - Tạo và gán cho các thiết bị để cấu hình Windows Autopilot (ví dụ như một hồ sơ Windows Autopilot hạn chế tạo tài khoản người quản trị của địa phương).

    - Tuỳ chỉnh Out-of-box-kinh nghiệm (OOBE) để phù hợp với yêu cầu của tổ chức.

    - Cấu hình MDM kết nạp tự động trong quảng cáo Azure và dành.

    > [!NOTE]
    > Thiết lập Windows lái tự động bên ngoài dành là ra khỏi phạm vi lợi ích FastTrack.

### <a name="enable-phase---co-management"></a>Sử giai đoạn - đồng quản lý

Cung cấp hướng dẫn trên:

-   Cấp giấy phép người dùng cuối cùng của bạn.

-   Thêm người dùng vào đăng ký dành của bạn, nó xác định vai trò quản trị, và tạo nhóm người dùng và thiết bị (nếu dành không được cài đặt).

-   Thiết lập Azure Active Directory cho MDM kết nạp tự động.

-   Thiết lập hybrid Azure Active Directory tham gia.

-   Thiết lập cổng quản lý đám mây.

-   Thêm người dùng để đăng ký của bạn dành, nó xác định vai trò quản trị, và tạo ra các nhóm người dùng và thiết bị.

-   Chuẩn bị dành (nếu dành không được cài đặt):

    -   Cấu hình của điện thoại di động thiết bị quản lý MDM) thẩm quyền, dựa trên nhu cầu quản lý của bạn, bao gồm:

    -   Thiết lập dành như thẩm quyền MDM của bạn.

    -   Cấu hình thử nghiệm nhóm sẽ được sử dụng để xác nhận MDM quản lý chính sách.

    -   Điều hướng cổng thông tin admin dành để định vị thông tin về người dùng và các thiết bị.

    -   Thiết lập vai trò dành (giúp bàn điều khiển, quản trị viên, vv)

    -   Cấu hình và triển khai các chính sách bảo vệ app dành cho mỗi nền tảng được hỗ trợ.

    -   Ghi các thiết bị Windows 10 để dành của bạn.

- Kích hoạt đồng quản lý trong giao diện điều khiển cấu hình quản lý.

- Chuyển đổi khối lượng công việc để dành.

- Giám sát các hoạt động hợp tác quản lý môi trường của bạn.

### <a name="enable-phase--azure-information-protection"></a>Sử giai đoạn-bảo vệ thông tin Azure

Cung cấp hướng dẫn trên: 

- Cách kích hoạt và đặt cấu hình người thuê nhà khách hàng.

- Tạo và thiết lập các chính sách và nhãn.

- Áp dụng bảo vệ thông tin tài liệu. 

- Tự động phân loại và ghi nhãn thông tin trong các ứng dụng văn phòng (như Word, PowerPoint, Excel và Outlook) chạy trên Windows và sử dụng các khách hàng bảo vệ thông tin Azure.

- Bằng cách sử dụng các tập tin ở phần còn lại với máy quét Azure bảo vệ thông tin.

- Giám sát email trong quá cảnh bằng cách sử dụng quy tắc dòng chảy thư Exchange Online.

Hướng dẫn cũng được cung cấp cho khách hàng những người muốn áp dụng bảo vệ bằng cách sử dụng dịch vụ quản lý quyền Microsoft Azure (Azure RMS), Office 365 thư mã hóa (OME) và ngăn ngừa mất dữ liệu (DLP).

> [!NOTE]
> **Muốn tìm hiểu thêm?** xem [doanh nghiệp di động + bảo mật](https://www.microsoft.com/cloud-platform/enterprise-mobility).

## <a name="next-steps"></a>Các bước tiếp theo

[FastTrack lợi ích cho EMS - trách nhiệm của bạn](EMS-your-responsibilities.md)
