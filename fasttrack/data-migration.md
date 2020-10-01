---
title: Di chuyển dữ liệu
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 10/1/20
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: a8bb82e5a0409c52fe2603d33a4412182288f24a
ms.sourcegitcommit: c2bf382289217ef12913ef3419e6378716fd411a
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 09/30/2020
ms.locfileid: "48319954"
---
# <a name="data-migration"></a><span data-ttu-id="bc0b7-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="bc0b7-104">Data Migration</span></span>

<span data-ttu-id="bc0b7-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="bc0b7-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="bc0b7-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="bc0b7-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="bc0b7-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="bc0b7-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="bc0b7-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-111">You create and schedule your migration events.</span></span> <span data-ttu-id="bc0b7-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="bc0b7-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="bc0b7-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="bc0b7-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-115">Considerations</span></span>

  - <span data-ttu-id="bc0b7-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="bc0b7-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="bc0b7-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="bc0b7-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="bc0b7-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="bc0b7-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="bc0b7-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="bc0b7-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="bc0b7-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-124">Migration service availability</span></span>

  - <span data-ttu-id="bc0b7-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="bc0b7-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="bc0b7-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="bc0b7-127">Migration to Exchange Online</span></span>

<span data-ttu-id="bc0b7-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="bc0b7-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="bc0b7-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-130">You create and schedule your migration events.</span></span> <span data-ttu-id="bc0b7-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="bc0b7-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="bc0b7-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-133">Considerations</span></span>

  - <span data-ttu-id="bc0b7-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="bc0b7-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="bc0b7-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="bc0b7-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="bc0b7-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="bc0b7-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="bc0b7-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="bc0b7-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="bc0b7-141">Danh sách phân phối (đối tượng*Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng*Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="bc0b7-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="bc0b7-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-143">Source environments</span></span>

<span data-ttu-id="bc0b7-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="bc0b7-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="bc0b7-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="bc0b7-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="bc0b7-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bc0b7-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="bc0b7-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="bc0b7-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="bc0b7-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc0b7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="bc0b7-154">
<strong>Lưu ý:</strong>   Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="bc0b7-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="bc0b7-156">Điện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-156">Emails</span></span></li>
<li><span data-ttu-id="bc0b7-157">Quy tắc hộp thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="bc0b7-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-158">Delegates</span></span></li>
<li><span data-ttu-id="bc0b7-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="bc0b7-160">Ba</span><span class="sxs-lookup"><span data-stu-id="bc0b7-160">Calendar</span></span> </li>
<li> <span data-ttu-id="bc0b7-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-161">Tasks</span></span> </li>
<li> <span data-ttu-id="bc0b7-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="bc0b7-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="bc0b7-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="bc0b7-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="bc0b7-164">Ký</span><span class="sxs-lookup"><span data-stu-id="bc0b7-164">Signatures</span></span> </li>
<li> <span data-ttu-id="bc0b7-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="bc0b7-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-167">Public folders</span></span> </li>
<li> <span data-ttu-id="bc0b7-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="bc0b7-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="bc0b7-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="bc0b7-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="bc0b7-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="bc0b7-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc0b7-174"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="bc0b7-175">
<strong>Lưu ý:</strong>   Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="bc0b7-176">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-177">Điện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-177">Emails</span></span> </li>
<li> <span data-ttu-id="bc0b7-178">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="bc0b7-179">Ba</span><span class="sxs-lookup"><span data-stu-id="bc0b7-179">Calendar</span></span> </li>
<li> <span data-ttu-id="bc0b7-180">Mác</span><span class="sxs-lookup"><span data-stu-id="bc0b7-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-181">Tắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-181">Rules</span></span> </li>
<li> <span data-ttu-id="bc0b7-182">Đại diện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-182">Delegates</span></span> </li>
<li> <span data-ttu-id="bc0b7-183">Ký</span><span class="sxs-lookup"><span data-stu-id="bc0b7-183">Signatures</span></span> </li>
<li> <span data-ttu-id="bc0b7-184">Môùi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-184">Tasks</span></span> </li>
<li> <span data-ttu-id="bc0b7-185">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="bc0b7-186">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-187">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="bc0b7-188">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="bc0b7-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="bc0b7-189">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="bc0b7-190">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="bc0b7-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="bc0b7-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="bc0b7-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="bc0b7-192">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="bc0b7-193">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="bc0b7-194">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="bc0b7-195">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="bc0b7-196">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc0b7-197"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-198">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="bc0b7-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="bc0b7-199">Điện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-200">Tắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-200">Rules</span></span> </li>
<li> <span data-ttu-id="bc0b7-201">Đại diện</span><span class="sxs-lookup"><span data-stu-id="bc0b7-201">Delegates</span></span> </li>
<li> <span data-ttu-id="bc0b7-202">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="bc0b7-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="bc0b7-203">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="bc0b7-203">External contacts</span></span> </li>
<li> <span data-ttu-id="bc0b7-204">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="bc0b7-205">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-206">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="bc0b7-207">Ba</span><span class="sxs-lookup"><span data-stu-id="bc0b7-207">Calendar</span></span> </li>
<li> <span data-ttu-id="bc0b7-208">Ký</span><span class="sxs-lookup"><span data-stu-id="bc0b7-208">Signatures</span></span> </li>
<li> <span data-ttu-id="bc0b7-209">Môùi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-209">Tasks</span></span> </li>
<li> <span data-ttu-id="bc0b7-210">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="bc0b7-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="bc0b7-211">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="bc0b7-211">Archive data</span></span> </li>
<li> <span data-ttu-id="bc0b7-212">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="bc0b7-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="bc0b7-213">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="bc0b7-214">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="bc0b7-215">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="bc0b7-215">FastTrack responsibilities</span></span>

<span data-ttu-id="bc0b7-216">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-217">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="bc0b7-218">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="bc0b7-219">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="bc0b7-220">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-220">Your responsibilities</span></span>

<span data-ttu-id="bc0b7-221">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-222">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="bc0b7-223">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="bc0b7-224">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="bc0b7-225">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="bc0b7-226">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="bc0b7-227">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="bc0b7-228">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="bc0b7-229">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="bc0b7-230">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="bc0b7-231">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="bc0b7-232">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="bc0b7-233">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="bc0b7-234">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="bc0b7-235">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="bc0b7-236">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="bc0b7-237">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="bc0b7-238">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="bc0b7-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="bc0b7-239">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="bc0b7-240">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="bc0b7-241">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-241">You create and schedule your migration events.</span></span> <span data-ttu-id="bc0b7-242">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="bc0b7-243">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="bc0b7-244">Nhắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-244">Considerations</span></span>

  - <span data-ttu-id="bc0b7-245">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="bc0b7-246">Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="bc0b7-247">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="bc0b7-248">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-248">Source environment details</span></span>

<span data-ttu-id="bc0b7-249">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="bc0b7-250">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="bc0b7-251">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="bc0b7-252">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="bc0b7-253">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="bc0b7-254">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="bc0b7-255"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="bc0b7-256"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="bc0b7-257"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="bc0b7-258"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc0b7-259"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="bc0b7-260">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-261">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-261">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-262">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-263">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="bc0b7-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="bc0b7-264">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="bc0b7-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="bc0b7-265">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-266">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-267">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-267">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-268">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-268">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-269">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-269">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-270">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="bc0b7-271">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="bc0b7-272">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="bc0b7-273">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="bc0b7-274">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-275">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="bc0b7-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="bc0b7-276">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-277">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="bc0b7-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="bc0b7-278">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="bc0b7-279">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="bc0b7-280">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="bc0b7-281">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="bc0b7-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="bc0b7-282">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="bc0b7-283">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-284">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="bc0b7-285">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="bc0b7-286">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc0b7-287"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-288">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-289">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="bc0b7-290">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-291">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-292">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-293">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-294">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-295">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-295">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-296">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-296">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-297">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-297">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-298">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-299">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="bc0b7-300">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-301">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-302">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="bc0b7-303">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-304">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-305">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-306">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-307">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-308">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-309">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-310">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-311">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="bc0b7-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="bc0b7-312">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="bc0b7-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="bc0b7-313">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="bc0b7-314">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="bc0b7-315">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-316">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-317">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="bc0b7-318">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-319">Các tệp được đánh dấu là hạn chế hoặc không được copyable</span><span class="sxs-lookup"><span data-stu-id="bc0b7-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="bc0b7-320">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc0b7-321"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-322">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-323">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-323">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-324">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-325">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-326">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-327">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-328">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-329">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-329">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-330">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-330">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-331">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-331">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-332">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-333">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-333">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-334">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-334">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-335">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-335">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="bc0b7-336">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-336">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-337">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-337">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-338">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-338">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-339">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-339">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-340">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-340">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-341">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-341">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-342">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-342">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-343">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-343">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-344">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-344">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="bc0b7-345">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-345">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="bc0b7-346">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-346">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-347">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-347">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-348">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-348">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc0b7-349"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-349"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-350">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-350">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-351">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-351">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-352">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-352">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-353">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-353">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-354">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-354">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-355">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-355">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-356">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-356">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-357">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-357">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-358">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-358">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-359">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-359">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-360">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-360">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-361">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-361">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="bc0b7-362">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-362">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-363">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-363">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-364">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-364">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="bc0b7-365">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-365">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-366">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-366">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-367">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-367">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-368">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-368">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-369">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-369">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-370">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-370">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-371">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-371">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-372">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="bc0b7-372">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="bc0b7-373">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="bc0b7-373">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="bc0b7-374">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-374">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="bc0b7-375">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-375">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="bc0b7-376">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-376">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="bc0b7-377">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-377">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-378">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-378">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="bc0b7-379">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-379">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="bc0b7-380">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="bc0b7-380">FastTrack responsibilities</span></span>

<span data-ttu-id="bc0b7-381">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-381">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-382">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="bc0b7-382">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="bc0b7-383">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-383">Your responsibilities</span></span>

<span data-ttu-id="bc0b7-384">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-384">You perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-385">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="bc0b7-385">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="bc0b7-386">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-386">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="bc0b7-387">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-387">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="bc0b7-388">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="bc0b7-388">Migration to OneDrive for Business</span></span>

<span data-ttu-id="bc0b7-389">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-389">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="bc0b7-390">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-390">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="bc0b7-391">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-391">You create and schedule your migration events.</span></span> <span data-ttu-id="bc0b7-392">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-392">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="bc0b7-393">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-393">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="bc0b7-394">Nhắc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-394">Considerations</span></span>

  - <span data-ttu-id="bc0b7-395">Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-395">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="bc0b7-396">Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-396">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="bc0b7-397">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-397">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="bc0b7-398">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-398">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="bc0b7-399">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-399">Source environment details</span></span>

<span data-ttu-id="bc0b7-400">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-400">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="bc0b7-401">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-401">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="bc0b7-402">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-402">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="bc0b7-403">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-403">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="bc0b7-404">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="bc0b7-404">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="bc0b7-405">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-405">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="bc0b7-406"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-406"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="bc0b7-407"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-407"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="bc0b7-408"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-408"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="bc0b7-409"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-409"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="bc0b7-410"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-410"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="bc0b7-411">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-411">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-412">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-412">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-413">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-413">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-414">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="bc0b7-414">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="bc0b7-415">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="bc0b7-415">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="bc0b7-416">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-416">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-417">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-417">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-418">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-418">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-419">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-419">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-420">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-420">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-421">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-421">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="bc0b7-422">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-422">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="bc0b7-423">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-423">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="bc0b7-424">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-424">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="bc0b7-425">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-425">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="bc0b7-426">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="bc0b7-426">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="bc0b7-427">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-427">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-428">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="bc0b7-428">Previous versions</span></span> </li>
<li> <span data-ttu-id="bc0b7-429">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-429">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="bc0b7-430">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-430">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="bc0b7-431">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-431">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="bc0b7-432">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="bc0b7-432">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="bc0b7-433">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-433">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="bc0b7-434">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-434">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-435">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-435">Hidden shares</span></span> </li>
<li> <span data-ttu-id="bc0b7-436">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-436">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="bc0b7-437">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-437">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc0b7-438"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-438"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-439">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-439">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-440">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-440">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="bc0b7-441">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-441">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-442">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-442">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-443">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-443">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-444">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-444">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-445">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-445">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-446">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-446">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-447">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-447">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-448">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-448">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-449">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-449">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-450">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-450">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="bc0b7-451">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-451">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-452">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-452">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-453">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-453">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="bc0b7-454">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-454">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-455">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-455">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-456">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-456">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-457">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-457">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-458">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-458">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-459">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-459">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-460">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-460">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-461">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-461">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-462">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="bc0b7-462">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="bc0b7-463">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="bc0b7-463">Google Drawings</span></span> </li>
<li> <span data-ttu-id="bc0b7-464">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-464">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="bc0b7-465">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-465">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="bc0b7-466">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-466">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-467">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-467">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-468">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-468">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="bc0b7-469">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-469">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-470">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-470">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="bc0b7-471"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-471"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-472">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-472">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-473">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-473">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-474">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-474">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-475">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-475">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-476">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-476">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-477">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-477">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-478">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-478">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-479">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-479">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-480">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-480">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-481">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-481">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-482">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-482">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-483">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-483">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-484">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-484">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-485">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-485">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="bc0b7-486">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-486">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-487">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-487">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-488">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-488">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-489">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-489">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-490">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-490">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-491">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-491">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-492">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-492">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-493">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="bc0b7-493">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="bc0b7-494">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="bc0b7-494">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="bc0b7-495">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-495">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="bc0b7-496">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-496">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-497">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-497">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-498">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-498">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="bc0b7-499"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="bc0b7-499"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="bc0b7-500">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-500">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-501">Liên</span><span class="sxs-lookup"><span data-stu-id="bc0b7-501">Documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-502">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-502">File and folder structure</span></span> </li>
<li> <span data-ttu-id="bc0b7-503">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-503">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-504">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-504">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-505">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="bc0b7-505">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="bc0b7-506">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-506">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="bc0b7-507">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="bc0b7-507">Created date</span></span> </li>
<li> <span data-ttu-id="bc0b7-508">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-508">Modified date</span></span> </li>
<li> <span data-ttu-id="bc0b7-509">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-509">Created by</span></span> </li>
<li> <span data-ttu-id="bc0b7-510">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-510">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="bc0b7-511">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-511">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="bc0b7-512">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-512">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="bc0b7-513">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="bc0b7-513">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="bc0b7-514">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-514">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="bc0b7-515">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-515">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-516">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="bc0b7-516">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="bc0b7-517">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="bc0b7-517">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="bc0b7-518">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="bc0b7-518">File lock attributes</span></span> </li>
<li> <span data-ttu-id="bc0b7-519">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="bc0b7-519">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="bc0b7-520">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="bc0b7-520">Trashed items</span></span> </li>
<li> <span data-ttu-id="bc0b7-521">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="bc0b7-521">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="bc0b7-522">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="bc0b7-522">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="bc0b7-523">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="bc0b7-523">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="bc0b7-524">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="bc0b7-524">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="bc0b7-525">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-525">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="bc0b7-526">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="bc0b7-526">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="bc0b7-527">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-527">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="bc0b7-528">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="bc0b7-528">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="bc0b7-529">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="bc0b7-529">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="bc0b7-530">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="bc0b7-530">FastTrack responsibilities</span></span>

<span data-ttu-id="bc0b7-531">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-531">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-532">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-532">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="bc0b7-533">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="bc0b7-533">Your responsibilities</span></span>

<span data-ttu-id="bc0b7-534">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-534">You perform standard activities during the migration project.</span></span> <span data-ttu-id="bc0b7-535">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-535">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="bc0b7-536">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="bc0b7-536">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="bc0b7-537">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="bc0b7-537">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
