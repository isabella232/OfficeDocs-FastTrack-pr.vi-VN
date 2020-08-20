---
title: Di chuyển dữ liệu
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: 6b2c9cc3afba415c200b14fe34e65f1c3286e450
ms.sourcegitcommit: d67bbe7e9f71c9983280cb3858a4fff0d7ac884b
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/20/2020
ms.locfileid: "46817719"
---
# <a name="data-migration"></a><span data-ttu-id="2373c-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="2373c-104">Data Migration</span></span>

<span data-ttu-id="2373c-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="2373c-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="2373c-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="2373c-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="2373c-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="2373c-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="2373c-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="2373c-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="2373c-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="2373c-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-111">You create and schedule your migration events.</span></span> <span data-ttu-id="2373c-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="2373c-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="2373c-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="2373c-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="2373c-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="2373c-115">Considerations</span></span>

  - <span data-ttu-id="2373c-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="2373c-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="2373c-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="2373c-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="2373c-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="2373c-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="2373c-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="2373c-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="2373c-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="2373c-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="2373c-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="2373c-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="2373c-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="2373c-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="2373c-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-124">Migration service availability</span></span>

  - <span data-ttu-id="2373c-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="2373c-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="2373c-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="2373c-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="2373c-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="2373c-127">Migration to Exchange Online</span></span>

<span data-ttu-id="2373c-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2373c-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="2373c-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-130">You create and schedule your migration events.</span></span> <span data-ttu-id="2373c-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="2373c-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2373c-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2373c-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="2373c-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="2373c-133">Considerations</span></span>

  - <span data-ttu-id="2373c-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="2373c-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="2373c-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2373c-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="2373c-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="2373c-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="2373c-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="2373c-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2373c-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="2373c-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="2373c-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="2373c-141">Danh sách phân phối (đối tượng*Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng*Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="2373c-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="2373c-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="2373c-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="2373c-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="2373c-143">Source environments</span></span>

<span data-ttu-id="2373c-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="2373c-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="2373c-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="2373c-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="2373c-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="2373c-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="2373c-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="2373c-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="2373c-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="2373c-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2373c-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2373c-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2373c-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="2373c-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2373c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="2373c-154">
<strong>Lưu ý:</strong>   Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="2373c-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="2373c-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="2373c-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="2373c-156">Điện</span><span class="sxs-lookup"><span data-stu-id="2373c-156">Emails</span></span></li>
<li><span data-ttu-id="2373c-157">Quy tắc hộp thư</span><span class="sxs-lookup"><span data-stu-id="2373c-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="2373c-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="2373c-158">Delegates</span></span></li>
<li><span data-ttu-id="2373c-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="2373c-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2373c-160">Ba</span><span class="sxs-lookup"><span data-stu-id="2373c-160">Calendar</span></span> </li>
<li> <span data-ttu-id="2373c-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="2373c-161">Tasks</span></span> </li>
<li> <span data-ttu-id="2373c-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="2373c-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="2373c-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="2373c-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="2373c-164">Ký</span><span class="sxs-lookup"><span data-stu-id="2373c-164">Signatures</span></span> </li>
<li> <span data-ttu-id="2373c-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="2373c-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="2373c-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="2373c-167">Public folders</span></span> </li>
<li> <span data-ttu-id="2373c-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="2373c-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2373c-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="2373c-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="2373c-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="2373c-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="2373c-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2373c-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2373c-174"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="2373c-175">
<strong>Lưu ý:</strong>   Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="2373c-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="2373c-176">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="2373c-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-177">Điện</span><span class="sxs-lookup"><span data-stu-id="2373c-177">Emails</span></span> </li>
<li> <span data-ttu-id="2373c-178">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="2373c-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="2373c-179">Ba</span><span class="sxs-lookup"><span data-stu-id="2373c-179">Calendar</span></span> </li>
<li> <span data-ttu-id="2373c-180">Mác</span><span class="sxs-lookup"><span data-stu-id="2373c-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-181">Tắc</span><span class="sxs-lookup"><span data-stu-id="2373c-181">Rules</span></span> </li>
<li> <span data-ttu-id="2373c-182">Đại diện</span><span class="sxs-lookup"><span data-stu-id="2373c-182">Delegates</span></span> </li>
<li> <span data-ttu-id="2373c-183">Ký</span><span class="sxs-lookup"><span data-stu-id="2373c-183">Signatures</span></span> </li>
<li> <span data-ttu-id="2373c-184">Môùi</span><span class="sxs-lookup"><span data-stu-id="2373c-184">Tasks</span></span> </li>
<li> <span data-ttu-id="2373c-185">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="2373c-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2373c-186">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-187">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="2373c-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="2373c-188">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="2373c-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="2373c-189">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2373c-190">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="2373c-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="2373c-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="2373c-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="2373c-192">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="2373c-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="2373c-193">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="2373c-194">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="2373c-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="2373c-195">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="2373c-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="2373c-196">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2373c-197"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="2373c-198">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="2373c-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="2373c-199">Điện</span><span class="sxs-lookup"><span data-stu-id="2373c-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="2373c-200">Tắc</span><span class="sxs-lookup"><span data-stu-id="2373c-200">Rules</span></span> </li>
<li> <span data-ttu-id="2373c-201">Đại diện</span><span class="sxs-lookup"><span data-stu-id="2373c-201">Delegates</span></span> </li>
<li> <span data-ttu-id="2373c-202">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="2373c-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="2373c-203">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="2373c-203">External contacts</span></span> </li>
<li> <span data-ttu-id="2373c-204">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="2373c-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="2373c-205">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-206">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="2373c-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="2373c-207">Ba</span><span class="sxs-lookup"><span data-stu-id="2373c-207">Calendar</span></span> </li>
<li> <span data-ttu-id="2373c-208">Ký</span><span class="sxs-lookup"><span data-stu-id="2373c-208">Signatures</span></span> </li>
<li> <span data-ttu-id="2373c-209">Môùi</span><span class="sxs-lookup"><span data-stu-id="2373c-209">Tasks</span></span> </li>
<li> <span data-ttu-id="2373c-210">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="2373c-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="2373c-211">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="2373c-211">Archive data</span></span> </li>
<li> <span data-ttu-id="2373c-212">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="2373c-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="2373c-213">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="2373c-214">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2373c-215">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="2373c-215">FastTrack responsibilities</span></span>

<span data-ttu-id="2373c-216">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-217">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2373c-218">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="2373c-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="2373c-219">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="2373c-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2373c-220">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="2373c-220">Your responsibilities</span></span>

<span data-ttu-id="2373c-221">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-222">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2373c-223">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="2373c-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="2373c-224">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="2373c-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="2373c-225">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="2373c-226">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="2373c-227">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="2373c-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="2373c-228">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="2373c-229">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="2373c-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="2373c-230">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="2373c-231">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="2373c-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="2373c-232">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="2373c-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="2373c-233">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="2373c-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="2373c-234">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="2373c-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="2373c-235">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="2373c-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="2373c-236">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="2373c-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="2373c-237">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="2373c-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="2373c-238">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="2373c-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="2373c-239">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2373c-240">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2373c-241">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-241">You create and schedule your migration events.</span></span> <span data-ttu-id="2373c-242">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="2373c-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2373c-243">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2373c-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="2373c-244">Nhắc</span><span class="sxs-lookup"><span data-stu-id="2373c-244">Considerations</span></span>

  - <span data-ttu-id="2373c-245">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="2373c-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="2373c-246">Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="2373c-247">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="2373c-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2373c-248">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="2373c-248">Source environment details</span></span>

<span data-ttu-id="2373c-249">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="2373c-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2373c-250">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="2373c-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2373c-251">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="2373c-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2373c-252">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="2373c-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2373c-253">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="2373c-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2373c-254">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="2373c-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="2373c-255"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="2373c-256"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="2373c-257"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2373c-258"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2373c-259"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2373c-260">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-261">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-261">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-262">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-263">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="2373c-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2373c-264">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="2373c-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2373c-265">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-266">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-267">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-267">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-268">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-268">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-269">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-269">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-270">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="2373c-271">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="2373c-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2373c-272">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="2373c-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2373c-273">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2373c-274">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="2373c-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-275">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="2373c-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2373c-276">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-277">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="2373c-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="2373c-278">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="2373c-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2373c-279">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="2373c-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2373c-280">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="2373c-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2373c-281">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="2373c-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2373c-282">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="2373c-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2373c-283">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-284">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="2373c-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2373c-285">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="2373c-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2373c-286">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2373c-287"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2373c-288">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-289">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="2373c-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="2373c-290">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-291">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-292">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-293">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-294">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-295">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-295">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-296">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-296">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-297">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-297">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-298">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-299">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="2373c-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2373c-300">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-301">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-302">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2373c-303">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-304">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-305">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-306">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-307">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-308">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-309">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-310">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-311">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="2373c-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2373c-312">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="2373c-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2373c-313">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="2373c-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2373c-314">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2373c-315">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-316">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-317">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="2373c-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2373c-318">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-319">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-319">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2373c-320"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-320"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2373c-321">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-321">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-322">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-322">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-323">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-323">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-324">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-324">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-325">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-325">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-326">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-326">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-327">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-327">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-328">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-328">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-329">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-329">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-330">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-330">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-331">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-331">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-332">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-332">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-333">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-333">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-334">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-334">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2373c-335">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-335">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-336">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-336">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-337">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-337">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-338">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-338">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-339">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-339">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-340">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-340">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-341">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-341">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-342">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-342">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-343">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="2373c-343">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2373c-344">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-344">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2373c-345">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-345">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-346">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-346">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-347">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-347">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2373c-348"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-348"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2373c-349">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-349">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-350">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-350">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-351">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-351">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-352">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-352">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-353">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-353">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-354">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-354">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-355">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-355">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-356">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-356">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-357">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-357">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-358">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-358">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-359">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-359">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-360">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-360">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2373c-361">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-361">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-362">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-362">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-363">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-363">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2373c-364">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-364">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-365">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-365">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-366">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-366">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-367">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-367">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-368">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-368">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-369">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-369">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-370">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-370">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-371">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="2373c-371">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2373c-372">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="2373c-372">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2373c-373">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="2373c-373">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2373c-374">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="2373c-374">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2373c-375">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-375">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2373c-376">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-376">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-377">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="2373c-377">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="2373c-378">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-378">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2373c-379">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="2373c-379">FastTrack responsibilities</span></span>

<span data-ttu-id="2373c-380">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-380">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-381">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="2373c-381">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2373c-382">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="2373c-382">Your responsibilities</span></span>

<span data-ttu-id="2373c-383">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-383">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-384">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="2373c-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="2373c-385">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="2373c-385">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="2373c-386">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-386">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="2373c-387">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="2373c-387">Migration to OneDrive for Business</span></span>

<span data-ttu-id="2373c-388">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="2373c-388">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="2373c-389">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-389">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="2373c-390">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-390">You create and schedule your migration events.</span></span> <span data-ttu-id="2373c-391">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="2373c-391">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="2373c-392">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="2373c-392">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="2373c-393">Nhắc</span><span class="sxs-lookup"><span data-stu-id="2373c-393">Considerations</span></span>

  - <span data-ttu-id="2373c-394">Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="2373c-394">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="2373c-395">Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-395">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="2373c-396">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="2373c-396">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="2373c-397">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="2373c-397">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="2373c-398">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="2373c-398">Source environment details</span></span>

<span data-ttu-id="2373c-399">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="2373c-399">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="2373c-400">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="2373c-400">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="2373c-401">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="2373c-401">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="2373c-402">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="2373c-402">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="2373c-403">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="2373c-403">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="2373c-404">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="2373c-404">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="2373c-405"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-405"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="2373c-406"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-406"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="2373c-407"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-407"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="2373c-408"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-408"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="2373c-409"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-409"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="2373c-410">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-410">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-411">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-411">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-412">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-412">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-413">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="2373c-413">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2373c-414">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="2373c-414">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="2373c-415">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-415">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-416">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-416">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-417">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-417">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-418">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-418">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-419">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-419">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-420">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-420">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="2373c-421">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="2373c-421">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="2373c-422">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="2373c-422">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="2373c-423">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-423">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="2373c-424">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="2373c-424">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="2373c-425">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="2373c-425">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="2373c-426">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-426">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-427">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="2373c-427">Previous versions</span></span> </li>
<li> <span data-ttu-id="2373c-428">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="2373c-428">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="2373c-429">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="2373c-429">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="2373c-430">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="2373c-430">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="2373c-431">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="2373c-431">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="2373c-432">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="2373c-432">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="2373c-433">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-433">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-434">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="2373c-434">Hidden shares</span></span> </li>
<li> <span data-ttu-id="2373c-435">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="2373c-435">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="2373c-436">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-436">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2373c-437"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-437"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="2373c-438">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-438">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-439">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="2373c-439">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="2373c-440">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-440">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-441">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-441">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-442">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-442">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-443">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-443">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-444">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-444">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-445">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-445">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-446">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-446">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-447">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-447">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-448">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-448">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-449">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="2373c-449">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="2373c-450">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-450">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-451">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-451">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-452">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-452">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="2373c-453">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-453">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-454">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-454">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-455">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-455">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-456">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-456">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-457">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-457">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-458">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-458">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-459">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-459">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-460">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-460">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-461">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="2373c-461">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="2373c-462">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="2373c-462">Google Drawings</span></span> </li>
<li> <span data-ttu-id="2373c-463">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="2373c-463">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="2373c-464">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-464">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="2373c-465">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-465">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-466">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-466">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-467">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="2373c-467">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="2373c-468">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-468">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-469">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-469">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="2373c-470"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-470"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="2373c-471">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-471">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-472">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-472">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-473">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-473">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-474">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-474">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-475">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-475">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-476">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-476">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-477">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-477">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-478">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-478">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-479">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-479">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-480">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-480">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-481">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-481">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-482">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-482">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-483">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-483">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-484">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-484">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2373c-485">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-485">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-486">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-486">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-487">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-487">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-488">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-488">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-489">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-489">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-490">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-490">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-491">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-491">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-492">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="2373c-492">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="2373c-493">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="2373c-493">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="2373c-494">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-494">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="2373c-495">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-495">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-496">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-496">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-497">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-497">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="2373c-498"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="2373c-498"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="2373c-499">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="2373c-499">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="2373c-500">Liên</span><span class="sxs-lookup"><span data-stu-id="2373c-500">Documents</span></span> </li>
<li> <span data-ttu-id="2373c-501">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-501">File and folder structure</span></span> </li>
<li> <span data-ttu-id="2373c-502">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-502">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-503">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-503">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="2373c-504">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="2373c-504">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="2373c-505">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="2373c-505">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="2373c-506">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="2373c-506">Created date</span></span> </li>
<li> <span data-ttu-id="2373c-507">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="2373c-507">Modified date</span></span> </li>
<li> <span data-ttu-id="2373c-508">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="2373c-508">Created by</span></span> </li>
<li> <span data-ttu-id="2373c-509">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="2373c-509">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="2373c-510">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-510">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="2373c-511">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-511">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="2373c-512">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="2373c-512">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="2373c-513">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="2373c-513">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="2373c-514">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="2373c-514">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-515">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="2373c-515">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="2373c-516">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="2373c-516">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="2373c-517">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="2373c-517">File lock attributes</span></span> </li>
<li> <span data-ttu-id="2373c-518">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="2373c-518">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="2373c-519">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="2373c-519">Trashed items</span></span> </li>
<li> <span data-ttu-id="2373c-520">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="2373c-520">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="2373c-521">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="2373c-521">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="2373c-522">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="2373c-522">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="2373c-523">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="2373c-523">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="2373c-524">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="2373c-524">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="2373c-525">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="2373c-525">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="2373c-526">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="2373c-526">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="2373c-527">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="2373c-527">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="2373c-528">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="2373c-528">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="2373c-529">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="2373c-529">FastTrack responsibilities</span></span>

<span data-ttu-id="2373c-530">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-530">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-531">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-531">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="2373c-532">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="2373c-532">Your responsibilities</span></span>

<span data-ttu-id="2373c-533">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="2373c-533">You perform standard activities during the migration project.</span></span> <span data-ttu-id="2373c-534">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="2373c-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="2373c-535">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="2373c-535">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="2373c-536">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="2373c-536">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
