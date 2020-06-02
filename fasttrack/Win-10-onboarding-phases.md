---
title: Các giai đoạn triển khai
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 6/01/2020
ms.audience: ITPro
ms.topic: overview
ms.service: windows-10-administration
localization_priority: Priority
ms.collection: FastTrack
description: Windows 10 bộ nhớ ngoài có bốn giai đoạn chính — bắt đầu, đánh giá, remediate và Enable.
ms.openlocfilehash: c42792ea21b0c8d08ba9fa5e225882fa540a792a
ms.sourcegitcommit: 826f140cc0ddee32005f74e5d995073af1dc3fa2
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 06/01/2020
ms.locfileid: "44472075"
---
# <a name="onboarding-phases"></a>Các giai đoạn triển khai

Windows 10 bộ nhớ ngoài có bốn giai đoạn chính — bắt đầu, đánh giá, remediate và Enable.

## <a name="initiate"></a>Bắt đầu

Trong giai đoạn này, chúng tôi thảo luận về quá trình bộ nhớ ngoài, xác minh dữ liệu của bạn, và thiết lập một cuộc họp kickoff. Điều này bao gồm làm việc với bạn để hiểu ý định Windows 10 của bạn.

## <a name="assess"></a>Đánh giá

FastTrack chuyên gia làm việc với bạn để đánh giá môi trường nguồn của bạn và các yêu cầu. Đảm bảo rằng Microsoft Endpoint Configuration Manager được nâng cấp lên mức yêu cầu hỗ trợ triển khai Windows 10. 

Chúng tôi cung cấp các tùy chọn được đề xuất để bạn đánh giá ứng dụng Windows 10 của mình. FastTrack cung cấp hướng dẫn để cho phép sử dụng phân tích màn hình và hướng dẫn bạn tạo kế hoạch triển khai Analytics trên máy tính để bàn.

FastTrack cũng có thể hướng dẫn đánh giá tương thích Microsoft 365 ứng dụng của bạn bằng cách tận dụng bảng điều khiển sẵn sàng Office 365 trong trình quản lý cấu hình hoặc với bộ công cụ sẵn sàng độc lập cho Office. Để biết thêm thông tin về các dịch vụ có sẵn, xem [FastTrack Trung tâm lợi ích cho Office 365](O365-fasttrack-benefit-for-office-365.md). 

FastTrack cũng đánh dấu các chiến lược quản lý hiện đại cho bạn, bao gồm quản lý cấu hình gắn đám mây với Microsoft InTune hoặc triển khai InTune là giải pháp quản lý đám mây duy nhất.

## <a name="remediate"></a>Khắc phục

Bạn thực hiện tác vụ khắc phục dựa trên môi trường nguồn của bạn để bạn đáp ứng các yêu cầu cho onboarding. Chúng tôi cung cấp một danh sách kiểm tra khắc phục để chuẩn bị môi trường của bạn và xác nhận rằng các yếu tố này có sẵn để đưa môi trường nguồn của bạn đến các yêu cầu tối thiểu để triển khai thành công. 

## <a name="enable"></a>Sử dung

FastTrack cung cấp hướng dẫn để nâng cấp thiết bị hiện có của bạn lên Windows 10 Enterprise miễn là chúng đáp ứng các yêu cầu phần cứng thiết bị cần thiết. Hướng dẫn nâng cấp được cung cấp hỗ trợ chuyển động triển khai hiện tại của bạn. FastTrack khuyến nghị và cung cấp hướng dẫn để nâng cấp tại chỗ lên Windows 10. Hướng dẫn cũng có sẵn cho Windows cài đặt hình ảnh sạch và [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot) triển khai kịch bản. 

Chúng tôi cung cấp hướng dẫn triển khai Microsoft 365 ứng dụng bằng cách sử dụng trình quản lý cấu hình như là một phần của việc triển khai Windows 10. Xem [Microsoft 365 ứng dụng](O365-onboarding-and-migration.md#microsoft-365-apps) để biết thêm chi tiết về các dịch vụ liên quan.

Chúng tôi cung cấp hướng dẫn để giúp tổ chức của bạn để ở được up-to-date với Windows 10 Enterprise và Microsoft 365 ứng dụng bằng cách sử dụng môi trường quản lý cấu hình hiện tại của bạn hoặc Microsoft 365.

Trong trường hợp cần thiết, FastTrack có thể hướng dẫn khách hàng để cho phép quản lý hiện đại của trình quản lý cấu hình gắn đám mây để InTune hoặc bằng cách triển khai độc lập InTune. Xem [quy trình lợi ích Trung tâm FastTrack dành cho doanh nghiệp di động + bảo mật (EMS)](EMS-fasttrack-process.md) để biết thêm chi tiết về các dịch vụ liên quan.

> [!NOTE]
> Nếu bạn không có kế hoạch hoặc quy trình hiện có để triển khai và bảo trì, chúng tôi có thể cung cấp hướng dẫn thực hành tốt nhất dựa trên kịch bản nâng cấp tại chỗ (được khuyến nghị) hoặc [Windows Autopilot](EMS-onboarding-phases.md#windows-autopilot).

## <a name="out-of-scope"></a>Phạm vi

FastTrack không cung cấp hướng dẫn cho:

- Nâng cấp trình quản lý cấu hình cho nhánh hiện tại.
- Tạo hình ảnh tùy chỉnh cho việc triển khai Windows 10.
- Tạo và hỗ trợ các kịch bản triển khai để triển khai Windows 10.
- Chuyển đổi hệ thống Windows 10 từ BIOS để Unified có khả mở rộng phần mềm Interface (UEFI).
- Kích hoạt tính năng bảo mật Windows 10. 
- Cấu hình dịch vụ triển khai Windows (WDS) khởi động môi trường thực hiện Preboot (PXE).
- Sử dụng công cụ triển khai Microsoft (MDT) để chụp và triển khai hình ảnh Windows 10.
- Sử dụng công cụ di chuyển trạng thái người dùng (USMT).

  > [!NOTE]
  > Liên hệ với [đối tác của Microsoft](https://go.microsoft.com/fwlink/?linkid=2080150) để cung cấp hỗ trợ với các dịch vụ được xác định là phạm vi.

 