---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: f518e8dbda9200318022bad2cc12d1ba68263df8
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188038"
---
# <a name="data-migration"></a><span data-ttu-id="a9ca5-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="a9ca5-104">Data Migration</span></span>

<span data-ttu-id="a9ca5-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="a9ca5-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="a9ca5-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="a9ca5-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="a9ca5-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="a9ca5-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="a9ca5-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-111">You create and schedule your migration events.</span></span> <span data-ttu-id="a9ca5-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="a9ca5-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="a9ca5-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="a9ca5-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-115">Considerations</span></span>

  - <span data-ttu-id="a9ca5-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="a9ca5-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="a9ca5-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="a9ca5-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="a9ca5-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="a9ca5-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="a9ca5-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="a9ca5-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="a9ca5-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-124">Migration service availability</span></span>

  - <span data-ttu-id="a9ca5-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="a9ca5-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="a9ca5-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a9ca5-127">Migration to Exchange Online</span></span>

<span data-ttu-id="a9ca5-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a9ca5-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="a9ca5-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-130">You create and schedule your migration events.</span></span> <span data-ttu-id="a9ca5-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a9ca5-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="a9ca5-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-133">Considerations</span></span>

  - <span data-ttu-id="a9ca5-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="a9ca5-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="a9ca5-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="a9ca5-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="a9ca5-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="a9ca5-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="a9ca5-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="a9ca5-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="a9ca5-141">Danh sách phân phối (đối tượng *Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng *Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="a9ca5-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="a9ca5-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-143">Source environments</span></span>

<span data-ttu-id="a9ca5-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="a9ca5-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="a9ca5-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="a9ca5-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="a9ca5-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a9ca5-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="a9ca5-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="a9ca5-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="a9ca5-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a9ca5-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="a9ca5-154">
<strong>Lưu ý:</strong> Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="a9ca5-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="a9ca5-156">Điện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-156">Emails</span></span></li>
<li><span data-ttu-id="a9ca5-157">Quy tắc hộp thư phía máy chủ</span><span class="sxs-lookup"><span data-stu-id="a9ca5-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="a9ca5-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-158">Delegates</span></span></li>
<li><span data-ttu-id="a9ca5-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="a9ca5-160">Ba</span><span class="sxs-lookup"><span data-stu-id="a9ca5-160">Calendar</span></span> </li>
<li> <span data-ttu-id="a9ca5-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-161">Tasks</span></span> </li>
<li> <span data-ttu-id="a9ca5-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="a9ca5-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="a9ca5-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="a9ca5-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="a9ca5-164">Ký</span><span class="sxs-lookup"><span data-stu-id="a9ca5-164">Signatures</span></span> </li>
<li> <span data-ttu-id="a9ca5-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="a9ca5-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-167">Public folders</span></span> </li>
<li> <span data-ttu-id="a9ca5-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a9ca5-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="a9ca5-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="a9ca5-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="a9ca5-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a9ca5-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="a9ca5-174">Quy tắc hộp thư phía máy khách</span><span class="sxs-lookup"><span data-stu-id="a9ca5-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-175"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="a9ca5-176">
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="a9ca5-177">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-178">Điện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-178">Emails</span></span> </li>
<li> <span data-ttu-id="a9ca5-179">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="a9ca5-180">Ba</span><span class="sxs-lookup"><span data-stu-id="a9ca5-180">Calendar</span></span> </li>
<li> <span data-ttu-id="a9ca5-181">Mác</span><span class="sxs-lookup"><span data-stu-id="a9ca5-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-182">Tắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-182">Rules</span></span> </li>
<li> <span data-ttu-id="a9ca5-183">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-183">Delegates</span></span> </li>
<li> <span data-ttu-id="a9ca5-184">Ký</span><span class="sxs-lookup"><span data-stu-id="a9ca5-184">Signatures</span></span> </li>
<li> <span data-ttu-id="a9ca5-185">Môùi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-185">Tasks</span></span> </li>
<li> <span data-ttu-id="a9ca5-186">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a9ca5-187">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-188">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="a9ca5-189">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="a9ca5-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="a9ca5-190">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a9ca5-191">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="a9ca5-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="a9ca5-193">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="a9ca5-194">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="a9ca5-195">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="a9ca5-196">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="a9ca5-197">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a9ca5-198"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-199">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="a9ca5-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="a9ca5-200">Điện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-201">Tắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-201">Rules</span></span> </li>
<li> <span data-ttu-id="a9ca5-202">Đại diện</span><span class="sxs-lookup"><span data-stu-id="a9ca5-202">Delegates</span></span> </li>
<li> <span data-ttu-id="a9ca5-203">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="a9ca5-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="a9ca5-204">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="a9ca5-204">External contacts</span></span> </li>
<li> <span data-ttu-id="a9ca5-205">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="a9ca5-206">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-207">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="a9ca5-208">Ba</span><span class="sxs-lookup"><span data-stu-id="a9ca5-208">Calendar</span></span> </li>
<li> <span data-ttu-id="a9ca5-209">Ký</span><span class="sxs-lookup"><span data-stu-id="a9ca5-209">Signatures</span></span> </li>
<li> <span data-ttu-id="a9ca5-210">Môùi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-210">Tasks</span></span> </li>
<li> <span data-ttu-id="a9ca5-211">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="a9ca5-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="a9ca5-212">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="a9ca5-212">Archive data</span></span> </li>
<li> <span data-ttu-id="a9ca5-213">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="a9ca5-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="a9ca5-214">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="a9ca5-215">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a9ca5-216">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a9ca5-216">FastTrack responsibilities</span></span>

<span data-ttu-id="a9ca5-217">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-218">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a9ca5-219">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="a9ca5-220">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a9ca5-221">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-221">Your responsibilities</span></span>

<span data-ttu-id="a9ca5-222">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-223">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a9ca5-224">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="a9ca5-225">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="a9ca5-226">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="a9ca5-227">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="a9ca5-228">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="a9ca5-229">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="a9ca5-230">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="a9ca5-231">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="a9ca5-232">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="a9ca5-233">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="a9ca5-234">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="a9ca5-235">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="a9ca5-236">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="a9ca5-237">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="a9ca5-238">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="a9ca5-239">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="a9ca5-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="a9ca5-240">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a9ca5-241">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="a9ca5-242">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-242">You create and schedule your migration events.</span></span> <span data-ttu-id="a9ca5-243">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a9ca5-244">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="a9ca5-245">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-245">Considerations</span></span>

 - <span data-ttu-id="a9ca5-246">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="a9ca5-247">Tham khảo các <a href="https://go.microsoft.com/fwlink/?LinkId=698855">giới hạn SharePoint</a> để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="a9ca5-248">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="a9ca5-249">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-249">Source environment details</span></span>

<span data-ttu-id="a9ca5-250">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="a9ca5-251">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="a9ca5-252">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="a9ca5-253">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="a9ca5-254">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="a9ca5-255">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="a9ca5-256"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="a9ca5-257"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="a9ca5-258"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-259"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a9ca5-260"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="a9ca5-261">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-262">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-262">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-263">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-264">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-265">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-266">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-267">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-268">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-268">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-269">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-269">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-270">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-270">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-271">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="a9ca5-272">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="a9ca5-273">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="a9ca5-274">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="a9ca5-275">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-276">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-277">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-278">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-279">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="a9ca5-280">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="a9ca5-281">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="a9ca5-282">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="a9ca5-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="a9ca5-283">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="a9ca5-284">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-285">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="a9ca5-286">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="a9ca5-287">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-288"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-289">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-290">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="a9ca5-291">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-292">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-293">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-294">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-295">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-296">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-296">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-297">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-297">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-298">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-298">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-299">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-300">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="a9ca5-301">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-302">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-303">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="a9ca5-304">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-305">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-306">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-307">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-308">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-309">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-310">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-311">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-312">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="a9ca5-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="a9ca5-313">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="a9ca5-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="a9ca5-314">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="a9ca5-315">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="a9ca5-316">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-317">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-318">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="a9ca5-319">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-320">Các tệp được đánh dấu là hạn chế hoặc không được copyable</span><span class="sxs-lookup"><span data-stu-id="a9ca5-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="a9ca5-321">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a9ca5-322"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-323">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-324">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-324">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-325">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-326">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-327">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-328">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-329">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-330">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-330">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-331">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-331">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-332">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-332">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-333">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-334">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="a9ca5-335">Ghi chú hộp (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-336">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-337">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-338">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-339">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-340">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-341">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-342">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-343">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-344">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-345">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-346">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="a9ca5-347">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="a9ca5-348">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-349">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-350">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-351"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-352">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-353">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-353">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-354">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-355">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-356">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-357">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-358">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-359">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-359">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-360">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-360">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-361">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-361">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-362">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-363">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="a9ca5-364">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-365">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-366">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-367">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-368">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-369">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-370">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-371">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-372">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-373">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-374">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="a9ca5-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="a9ca5-375">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="a9ca5-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="a9ca5-376">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="a9ca5-377">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="a9ca5-378">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="a9ca5-379">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-380">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="a9ca5-381">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a9ca5-382">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a9ca5-382">FastTrack responsibilities</span></span>

<span data-ttu-id="a9ca5-383">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-384">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="a9ca5-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a9ca5-385">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-385">Your responsibilities</span></span>

<span data-ttu-id="a9ca5-386">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-387">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="a9ca5-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="a9ca5-388">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="a9ca5-389">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="a9ca5-390">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="a9ca5-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="a9ca5-391">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a9ca5-392">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="a9ca5-393">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-393">You create and schedule your migration events.</span></span> <span data-ttu-id="a9ca5-394">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a9ca5-395">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="a9ca5-396">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-396">Considerations</span></span>

  - <span data-ttu-id="a9ca5-397">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="a9ca5-398">Tham khảo các <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> giới hạn SharePoint</a> để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="a9ca5-399">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="a9ca5-400">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="a9ca5-401">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-401">Source environment details</span></span>

<span data-ttu-id="a9ca5-402">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="a9ca5-403">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="a9ca5-404">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="a9ca5-405">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="a9ca5-406">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="a9ca5-407">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="a9ca5-408"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-409"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-410"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-411"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a9ca5-412"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="a9ca5-413">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-414">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-414">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-415">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-416">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-417">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-418">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-419">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-420">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-420">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-421">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-421">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-422">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-422">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-423">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="a9ca5-424">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="a9ca5-425">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="a9ca5-426">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="a9ca5-427">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="a9ca5-428">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-429">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-430">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-431">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="a9ca5-432">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="a9ca5-433">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="a9ca5-434">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="a9ca5-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="a9ca5-435">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="a9ca5-436">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-437">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="a9ca5-438">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="a9ca5-439">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-440"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-441">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-442">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="a9ca5-443">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-444">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-445">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-446">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-447">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-448">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-448">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-449">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-449">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-450">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-450">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-451">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-452">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="a9ca5-453">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-454">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-455">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="a9ca5-456">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-457">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-458">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-459">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-460">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-461">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-462">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-463">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-464">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="a9ca5-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="a9ca5-465">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="a9ca5-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="a9ca5-466">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="a9ca5-467">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="a9ca5-468">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-469">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-470">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="a9ca5-471">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-472">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a9ca5-473"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-474">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-475">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-475">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-476">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-477">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-478">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-479">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-480">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-481">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-481">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-482">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-482">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-483">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-483">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-484">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-485">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-486">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-487">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-488">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-489">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-490">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-491">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-492">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-493">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-494">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-495">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-496">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="a9ca5-497">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="a9ca5-498">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-499">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-500">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-501"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-502">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-503">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-503">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-504">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-505">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-506">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-507">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-508">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-509">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-509">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-510">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-510">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-511">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-511">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-512">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-513">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="a9ca5-514">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-515">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-516">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-517">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-518">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-519">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-520">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-521">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-522">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-523">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-524">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="a9ca5-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="a9ca5-525">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="a9ca5-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="a9ca5-526">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="a9ca5-527">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="a9ca5-528">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="a9ca5-529">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-530">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-531">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a9ca5-532">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a9ca5-532">FastTrack responsibilities</span></span>

<span data-ttu-id="a9ca5-533">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-534">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a9ca5-535">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-535">Your responsibilities</span></span>

<span data-ttu-id="a9ca5-536">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-537">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="a9ca5-538">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="a9ca5-539">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="a9ca5-540">Di chuyển sang nhóm Microsoft và Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="a9ca5-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="a9ca5-541">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang Microsoft Groups và các nhóm Microsoft 365, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="a9ca5-542">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và nhóm của bạn và nhóm Microsoft 365 và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="a9ca5-543">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-543">You create and schedule your migration events.</span></span> <span data-ttu-id="a9ca5-544">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="a9ca5-545">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến nhóm và Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="a9ca5-546">Các kênh nhóm và nhóm Microsoft 365 phải được khách hàng cung cấp sẵn trước khi họ có thể di chuyển dữ liệu vào các kiểu đích này.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="a9ca5-547">Nhóm và nhóm Microsoft 365 ảnh hưởng đến quyền của bạn trên vị trí đích tệp.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="a9ca5-548">Nhóm và nhóm Microsoft 365 được xây dựng để cho phép cộng tác.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="a9ca5-549">Kênh nhóm hoặc nhóm Microsoft 365 xác định ai có quyền truy nhập vào những tệp này khi di chuyển sang các điểm đến đó.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="a9ca5-550">FastTrack không thêm người dùng cuối hoặc nhóm vào bất kỳ kênh nhóm nào hoặc cho phép các nhóm Microsoft 365 trong quá trình di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="a9ca5-551">Nhắc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-551">Considerations</span></span>

- <span data-ttu-id="a9ca5-552">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="a9ca5-553">Tham khảo các <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> giới hạn SharePoint</a> để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="a9ca5-554">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="a9ca5-555">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-555">Source environment details</span></span>

<span data-ttu-id="a9ca5-556">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="a9ca5-557">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="a9ca5-558">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="a9ca5-559">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="a9ca5-560">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="a9ca5-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="a9ca5-561">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="a9ca5-562"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-563"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-564"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="a9ca5-565"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="a9ca5-566"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="a9ca5-567">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-568">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-568">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-569">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-570">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-571">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-572">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-573">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-574">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-574">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-575">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-575">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-576">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-576">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-577">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="a9ca5-578">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="a9ca5-579">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="a9ca5-580">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="a9ca5-581">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="a9ca5-582">Quyền bị ảnh hưởng bởi nhóm Microsoft 365 và/hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="a9ca5-583">Nếu đích là một nhóm Microsoft 365 hoặc kênh Microsoft nhóm, thì nhóm hoặc kênh này sẽ xác định hồ sơ cấp phép cuối cùng trên các tệp được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="a9ca5-584">Chúng tôi khuyên bạn không nên di chuyển các quyền trên các tệp di chuyển sang một nhóm Microsoft 365 hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-585">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-586">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-587">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="a9ca5-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="a9ca5-588">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="a9ca5-589">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="a9ca5-590">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="a9ca5-591">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="a9ca5-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="a9ca5-592">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="a9ca5-593">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-594">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="a9ca5-595">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="a9ca5-596">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-597"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-598">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-599">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="a9ca5-600">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-601">Quyền thư mục cấp độ người dùng \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-602">Quyền thư mục cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-603">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-604">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-605">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-605">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-606">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-606">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-607">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-607">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-608">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-609">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="a9ca5-610">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="a9ca5-611">\* Quyền bị ảnh hưởng bởi nhóm Microsoft 365 và/hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="a9ca5-612">Nếu đích là một nhóm Microsoft 365 hoặc kênh Microsoft nhóm, thì nhóm hoặc kênh này sẽ xác định hồ sơ cấp phép cuối cùng trên các tệp được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="a9ca5-613">Chúng tôi khuyên bạn không nên di chuyển các quyền trên các tệp di chuyển sang một nhóm Microsoft 365 hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="a9ca5-614">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-615">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="a9ca5-616">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-617">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-618">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-619">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-620">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-621">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-622">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-623">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-624">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="a9ca5-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="a9ca5-625">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="a9ca5-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="a9ca5-626">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="a9ca5-627">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="a9ca5-628">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-629">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-630">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="a9ca5-631">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-632">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="a9ca5-633"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-634">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-635">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-635">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-636">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-637">Quyền thư mục cấp độ người dùng \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-638">Quyền thư mục cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-639">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-640">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-641">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-641">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-642">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-642">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-643">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-643">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-644">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-645">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="a9ca5-646">Ghi chú hộp (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="a9ca5-647">\* Quyền bị ảnh hưởng bởi nhóm Microsoft 365 và/hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="a9ca5-648">Nếu đích là một nhóm Microsoft 365 hoặc kênh Microsoft nhóm, thì nhóm hoặc kênh này sẽ xác định hồ sơ cấp phép cuối cùng trên các tệp được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="a9ca5-649">Chúng tôi khuyên bạn không nên di chuyển các quyền trên các tệp di chuyển sang một nhóm Microsoft 365 hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="a9ca5-650">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-651">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-652">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-653">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-654">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-655">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-656">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-657">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-658">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-659">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="a9ca5-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="a9ca5-660">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="a9ca5-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="a9ca5-661">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="a9ca5-662">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-663">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-664">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="a9ca5-665"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="a9ca5-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="a9ca5-666">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="a9ca5-667">Liên</span><span class="sxs-lookup"><span data-stu-id="a9ca5-667">Documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-668">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="a9ca5-669">Quyền thư mục cấp độ người dùng \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-670">Quyền thư mục cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="a9ca5-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="a9ca5-671">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="a9ca5-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="a9ca5-672">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="a9ca5-673">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="a9ca5-673">Created date</span></span> </li>
<li> <span data-ttu-id="a9ca5-674">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-674">Modified date</span></span> </li>
<li> <span data-ttu-id="a9ca5-675">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-675">Created by</span></span> </li>
<li> <span data-ttu-id="a9ca5-676">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="a9ca5-677">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="a9ca5-678">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="a9ca5-679">\* Quyền bị ảnh hưởng bởi nhóm Microsoft 365 và/hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="a9ca5-680">Nếu đích là một nhóm Microsoft 365 hoặc kênh Microsoft nhóm, thì nhóm hoặc kênh này sẽ xác định hồ sơ cấp phép cuối cùng trên các tệp được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="a9ca5-681">Chúng tôi khuyên bạn không nên di chuyển các quyền trên các tệp di chuyển sang một nhóm Microsoft 365 hoặc kênh Microsoft nhóm.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="a9ca5-682">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="a9ca5-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="a9ca5-683">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="a9ca5-684">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-685">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="a9ca5-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="a9ca5-686">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="a9ca5-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="a9ca5-687">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="a9ca5-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="a9ca5-688">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="a9ca5-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="a9ca5-689">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="a9ca5-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="a9ca5-690">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="a9ca5-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="a9ca5-691">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="a9ca5-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="a9ca5-692">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="a9ca5-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="a9ca5-693">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="a9ca5-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="a9ca5-694">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="a9ca5-695">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="a9ca5-696">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="a9ca5-697">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="a9ca5-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="a9ca5-698">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="a9ca5-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="a9ca5-699">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="a9ca5-699">FastTrack responsibilities</span></span>

<span data-ttu-id="a9ca5-700">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-701">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="a9ca5-702">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="a9ca5-702">Your responsibilities</span></span> 

<span data-ttu-id="a9ca5-703">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="a9ca5-704">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="a9ca5-705">Bạn cũng sẽ thực hiện các hoạt động sau đây, đặc thù cho các nhóm Microsoft và các nhóm di chuyển Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="a9ca5-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="a9ca5-706">Cung cấp tất cả các kênh Microsoft Groups và các nhóm Microsoft 365 như mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="a9ca5-707">FastTrack không cung cấp sẵn các kênh Microsoft nhóm hoặc Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="a9ca5-708">FastTrack không thêm người dùng cuối hoặc nhóm vào kênh Microsoft nhóm hoặc nhóm Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="a9ca5-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="a9ca5-709">Bạn phải thêm người dùng hoặc nhóm cuối cùng của mình vào tất cả các kênh Microsoft Groups và nhóm Microsoft 365 trước khi di chuyển dữ liệu vào những đích đó để những người dùng cuối có quyền truy nhập vào những tài liệu mới được di chuyển</span><span class="sxs-lookup"><span data-stu-id="a9ca5-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>