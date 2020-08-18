---
title: Di chuyển dữ liệu
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: fc7f07aea6104fdc6f06b3d624778919b351b34d
ms.sourcegitcommit: 81ad135578a329f8b0a3325c4e43bb8f90648597
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/17/2020
ms.locfileid: "46777296"
---
# <a name="data-migration"></a><span data-ttu-id="a0873-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="a0873-104">Data Migration</span></span>

<span data-ttu-id="a0873-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="a0873-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="a0873-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="a0873-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="a0873-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="a0873-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="a0873-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="a0873-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="a0873-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="a0873-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-111">You create and schedule your migration events.</span></span> <span data-ttu-id="a0873-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a0873-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="a0873-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="a0873-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="a0873-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a0873-115">Considerations</span></span>

  - <span data-ttu-id="a0873-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="a0873-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="a0873-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="a0873-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="a0873-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="a0873-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="a0873-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="a0873-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="a0873-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="a0873-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="a0873-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="a0873-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="a0873-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="a0873-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="a0873-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-124">Migration service availability</span></span>

  - <span data-ttu-id="a0873-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="a0873-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="a0873-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="a0873-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="a0873-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a0873-127">Migration to Exchange Online</span></span>

<span data-ttu-id="a0873-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a0873-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="a0873-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-130">You create and schedule your migration events.</span></span> <span data-ttu-id="a0873-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a0873-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a0873-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a0873-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="a0873-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a0873-133">Considerations</span></span>

  - <span data-ttu-id="a0873-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="a0873-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="a0873-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="a0873-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="a0873-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="a0873-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="a0873-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="a0873-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="a0873-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="a0873-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="a0873-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="a0873-141">Danh sách phân phối (đối tượng*Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng*Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="a0873-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="a0873-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="a0873-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="a0873-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a0873-143">Source environments</span></span>

<span data-ttu-id="a0873-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a0873-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="a0873-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="a0873-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="a0873-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="a0873-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="a0873-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="a0873-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="a0873-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a0873-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a0873-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="a0873-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="a0873-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="a0873-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a0873-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="a0873-154">
<strong>Lưu ý:</strong>   Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="a0873-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="a0873-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="a0873-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="a0873-156">Điện</span><span class="sxs-lookup"><span data-stu-id="a0873-156">Emails</span></span></li>
<li><span data-ttu-id="a0873-157">Quy tắc hộp thư</span><span class="sxs-lookup"><span data-stu-id="a0873-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="a0873-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a0873-158">Delegates</span></span></li>
<li><span data-ttu-id="a0873-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="a0873-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="a0873-160">Ba</span><span class="sxs-lookup"><span data-stu-id="a0873-160">Calendar</span></span> </li>
<li> <span data-ttu-id="a0873-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="a0873-161">Tasks</span></span> </li>
<li> <span data-ttu-id="a0873-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="a0873-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="a0873-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="a0873-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="a0873-164">Ký</span><span class="sxs-lookup"><span data-stu-id="a0873-164">Signatures</span></span> </li>
<li> <span data-ttu-id="a0873-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="a0873-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="a0873-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="a0873-167">Public folders</span></span> </li>
<li> <span data-ttu-id="a0873-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a0873-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a0873-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="a0873-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="a0873-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="a0873-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="a0873-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a0873-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a0873-174"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="a0873-175">
<strong>Lưu ý:</strong>   Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="a0873-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="a0873-176">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a0873-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-177">Điện</span><span class="sxs-lookup"><span data-stu-id="a0873-177">Emails</span></span> </li>
<li> <span data-ttu-id="a0873-178">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="a0873-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="a0873-179">Ba</span><span class="sxs-lookup"><span data-stu-id="a0873-179">Calendar</span></span> </li>
<li> <span data-ttu-id="a0873-180">Mác</span><span class="sxs-lookup"><span data-stu-id="a0873-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-181">Tắc</span><span class="sxs-lookup"><span data-stu-id="a0873-181">Rules</span></span> </li>
<li> <span data-ttu-id="a0873-182">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a0873-182">Delegates</span></span> </li>
<li> <span data-ttu-id="a0873-183">Ký</span><span class="sxs-lookup"><span data-stu-id="a0873-183">Signatures</span></span> </li>
<li> <span data-ttu-id="a0873-184">Môùi</span><span class="sxs-lookup"><span data-stu-id="a0873-184">Tasks</span></span> </li>
<li> <span data-ttu-id="a0873-185">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a0873-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a0873-186">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-187">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="a0873-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="a0873-188">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="a0873-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="a0873-189">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a0873-190">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="a0873-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="a0873-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="a0873-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="a0873-192">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="a0873-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="a0873-193">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="a0873-194">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="a0873-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="a0873-195">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="a0873-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="a0873-196">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a0873-197"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="a0873-198">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="a0873-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="a0873-199">Điện</span><span class="sxs-lookup"><span data-stu-id="a0873-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="a0873-200">Tắc</span><span class="sxs-lookup"><span data-stu-id="a0873-200">Rules</span></span> </li>
<li> <span data-ttu-id="a0873-201">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a0873-201">Delegates</span></span> </li>
<li> <span data-ttu-id="a0873-202">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="a0873-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="a0873-203">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="a0873-203">External contacts</span></span> </li>
<li> <span data-ttu-id="a0873-204">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="a0873-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="a0873-205">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-206">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="a0873-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="a0873-207">Ba</span><span class="sxs-lookup"><span data-stu-id="a0873-207">Calendar</span></span> </li>
<li> <span data-ttu-id="a0873-208">Ký</span><span class="sxs-lookup"><span data-stu-id="a0873-208">Signatures</span></span> </li>
<li> <span data-ttu-id="a0873-209">Môùi</span><span class="sxs-lookup"><span data-stu-id="a0873-209">Tasks</span></span> </li>
<li> <span data-ttu-id="a0873-210">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a0873-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a0873-211">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="a0873-211">Archive data</span></span> </li>
<li> <span data-ttu-id="a0873-212">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="a0873-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="a0873-213">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a0873-214">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a0873-215">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a0873-215">FastTrack responsibilities</span></span>

<span data-ttu-id="a0873-216">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-217">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a0873-218">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="a0873-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="a0873-219">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="a0873-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a0873-220">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a0873-220">Your responsibilities</span></span>

<span data-ttu-id="a0873-221">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-222">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a0873-223">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="a0873-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="a0873-224">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a0873-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="a0873-225">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="a0873-226">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="a0873-227">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="a0873-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="a0873-228">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="a0873-229">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="a0873-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="a0873-230">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="a0873-231">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="a0873-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="a0873-232">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="a0873-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="a0873-233">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="a0873-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="a0873-234">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="a0873-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="a0873-235">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="a0873-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="a0873-236">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="a0873-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="a0873-237">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="a0873-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="a0873-238">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="a0873-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="a0873-239">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a0873-240">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="a0873-241">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-241">You create and schedule your migration events.</span></span> <span data-ttu-id="a0873-242">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a0873-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a0873-243">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a0873-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="a0873-244">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a0873-244">Considerations</span></span>

  - <span data-ttu-id="a0873-245">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a0873-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="a0873-246">Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="a0873-247">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="a0873-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="a0873-248">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a0873-248">Source environment details</span></span>

<span data-ttu-id="a0873-249">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a0873-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="a0873-250">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="a0873-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="a0873-251">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="a0873-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="a0873-252">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="a0873-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="a0873-253">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="a0873-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="a0873-254">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a0873-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a0873-255"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="a0873-256"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="a0873-257"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="a0873-258"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a0873-259"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="a0873-260">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-261">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-261">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-262">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-263">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="a0873-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a0873-264">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a0873-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a0873-265">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-266">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-267">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-267">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-268">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-268">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-269">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-269">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-270">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="a0873-271">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="a0873-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="a0873-272">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="a0873-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="a0873-273">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="a0873-274">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="a0873-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-275">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a0873-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="a0873-276">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-277">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a0873-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="a0873-278">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="a0873-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="a0873-279">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="a0873-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="a0873-280">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="a0873-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="a0873-281">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="a0873-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="a0873-282">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="a0873-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="a0873-283">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-284">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="a0873-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="a0873-285">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="a0873-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="a0873-286">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a0873-287"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="a0873-288">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-289">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="a0873-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="a0873-290">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-291">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-292">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-293">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-294">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-295">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-295">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-296">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-296">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-297">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-297">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-298">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-299">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="a0873-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="a0873-300">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-301">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-302">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="a0873-303">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-304">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-305">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-306">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-307">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-308">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-309">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-310">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-311">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="a0873-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="a0873-312">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="a0873-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="a0873-313">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="a0873-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="a0873-314">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="a0873-315">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-316">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-317">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="a0873-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="a0873-318">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-319">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a0873-320"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="a0873-321">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-322">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-322">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-323">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-324">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-325">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-326">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-327">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-328">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-328">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-329">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-329">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-330">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-330">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-331">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-332">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-333">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-334">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a0873-335">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-336">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-337">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-338">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-339">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-340">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-341">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-342">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-343">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="a0873-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="a0873-344">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="a0873-345">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-346">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-347">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a0873-348"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="a0873-349">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-350">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-350">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-351">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-352">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-353">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-354">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-355">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-356">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-356">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-357">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-357">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-358">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-358">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-359">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-360">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="a0873-361">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-362">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-363">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a0873-364">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-365">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-366">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-367">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-368">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-369">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-370">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-371">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="a0873-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="a0873-372">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="a0873-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="a0873-373">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="a0873-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="a0873-374">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="a0873-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="a0873-375">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="a0873-376">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-377">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="a0873-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="a0873-378">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a0873-379">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a0873-379">FastTrack responsibilities</span></span>

<span data-ttu-id="a0873-380">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-381">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="a0873-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a0873-382">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a0873-382">Your responsibilities</span></span>

<span data-ttu-id="a0873-383">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-384">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="a0873-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="a0873-385">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="a0873-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="a0873-386">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="a0873-387">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="a0873-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="a0873-388">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a0873-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a0873-389">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="a0873-390">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-390">You create and schedule your migration events.</span></span> <span data-ttu-id="a0873-391">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a0873-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a0873-392">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="a0873-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="a0873-393">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a0873-393">Considerations</span></span>

  - <span data-ttu-id="a0873-394">Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="a0873-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="a0873-395">Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="a0873-396">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="a0873-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="a0873-397">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="a0873-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="a0873-398">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a0873-398">Source environment details</span></span>

<span data-ttu-id="a0873-399">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a0873-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="a0873-400">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="a0873-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="a0873-401">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="a0873-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="a0873-402">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="a0873-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="a0873-403">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="a0873-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="a0873-404">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a0873-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="a0873-405"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="a0873-406"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="a0873-407"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="a0873-408"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a0873-409"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="a0873-410">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-411">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-411">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-412">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-413">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="a0873-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a0873-414">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a0873-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a0873-415">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-416">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-417">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-417">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-418">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-418">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-419">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-419">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-420">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="a0873-421">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="a0873-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="a0873-422">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="a0873-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="a0873-423">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="a0873-424">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="a0873-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="a0873-425">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a0873-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="a0873-426">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-427">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a0873-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="a0873-428">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="a0873-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="a0873-429">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="a0873-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="a0873-430">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="a0873-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="a0873-431">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="a0873-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="a0873-432">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="a0873-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="a0873-433">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-434">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="a0873-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="a0873-435">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="a0873-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="a0873-436">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a0873-437"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="a0873-438">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-439">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="a0873-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="a0873-440">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-441">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-442">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-443">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-444">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-445">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-445">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-446">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-446">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-447">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-447">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-448">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-449">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="a0873-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="a0873-450">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-451">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-452">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="a0873-453">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-454">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-455">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-456">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-457">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-458">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-459">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-460">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-461">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="a0873-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="a0873-462">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="a0873-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="a0873-463">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="a0873-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="a0873-464">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="a0873-465">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-466">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-467">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="a0873-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="a0873-468">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-469">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a0873-470"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="a0873-471">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-472">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-472">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-473">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-474">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-475">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-476">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-477">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-478">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-478">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-479">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-479">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-480">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-480">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-481">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-482">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-483">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-484">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a0873-485">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-486">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-487">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-488">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-489">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-490">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-491">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-492">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a0873-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a0873-493">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="a0873-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="a0873-494">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="a0873-495">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-496">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-497">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a0873-498"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="a0873-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="a0873-499">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a0873-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a0873-500">Liên</span><span class="sxs-lookup"><span data-stu-id="a0873-500">Documents</span></span> </li>
<li> <span data-ttu-id="a0873-501">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a0873-502">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-503">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a0873-504">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a0873-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a0873-505">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a0873-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a0873-506">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a0873-506">Created date</span></span> </li>
<li> <span data-ttu-id="a0873-507">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a0873-507">Modified date</span></span> </li>
<li> <span data-ttu-id="a0873-508">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a0873-508">Created by</span></span> </li>
<li> <span data-ttu-id="a0873-509">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a0873-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a0873-510">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="a0873-511">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a0873-512">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a0873-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a0873-513">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a0873-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a0873-514">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a0873-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-515">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a0873-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a0873-516">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a0873-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a0873-517">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a0873-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a0873-518">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a0873-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a0873-519">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a0873-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="a0873-520">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a0873-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a0873-521">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="a0873-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="a0873-522">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="a0873-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="a0873-523">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="a0873-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="a0873-524">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="a0873-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="a0873-525">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a0873-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="a0873-526">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a0873-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="a0873-527">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a0873-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a0873-528">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a0873-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a0873-529">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a0873-529">FastTrack responsibilities</span></span>

<span data-ttu-id="a0873-530">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-531">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a0873-532">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a0873-532">Your responsibilities</span></span>

<span data-ttu-id="a0873-533">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a0873-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a0873-534">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a0873-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a0873-535">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="a0873-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="a0873-536">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a0873-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
