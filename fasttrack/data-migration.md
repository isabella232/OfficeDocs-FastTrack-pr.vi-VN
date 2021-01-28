---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/27/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: 0ecfdfab7c7f7ae8879ea6374c3560dcaeb2f283
ms.sourcegitcommit: cd8426ce64dda56439933576e7da75b1c27f5de1
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 01/27/2021
ms.locfileid: "50016478"
---
# <a name="data-migration"></a><span data-ttu-id="66e1f-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="66e1f-104">Data Migration</span></span>

<span data-ttu-id="66e1f-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="66e1f-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="66e1f-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="66e1f-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="66e1f-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="66e1f-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="66e1f-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="66e1f-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="66e1f-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="66e1f-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-111">You create and schedule your migration events.</span></span> <span data-ttu-id="66e1f-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="66e1f-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="66e1f-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="66e1f-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="66e1f-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-115">Considerations</span></span>

  - <span data-ttu-id="66e1f-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="66e1f-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="66e1f-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="66e1f-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="66e1f-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="66e1f-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="66e1f-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="66e1f-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="66e1f-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="66e1f-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="66e1f-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="66e1f-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="66e1f-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="66e1f-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="66e1f-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-124">Migration service availability</span></span>

  - <span data-ttu-id="66e1f-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="66e1f-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="66e1f-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="66e1f-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="66e1f-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="66e1f-127">Migration to Exchange Online</span></span>

<span data-ttu-id="66e1f-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="66e1f-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="66e1f-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-130">You create and schedule your migration events.</span></span> <span data-ttu-id="66e1f-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="66e1f-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="66e1f-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="66e1f-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="66e1f-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-133">Considerations</span></span>

  - <span data-ttu-id="66e1f-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="66e1f-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="66e1f-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="66e1f-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="66e1f-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="66e1f-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="66e1f-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="66e1f-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="66e1f-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="66e1f-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="66e1f-141">Danh sách phân phối (đối tượng *Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng *Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="66e1f-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="66e1f-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="66e1f-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="66e1f-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="66e1f-143">Source environments</span></span>

<span data-ttu-id="66e1f-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="66e1f-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="66e1f-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="66e1f-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="66e1f-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="66e1f-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="66e1f-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="66e1f-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="66e1f-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="66e1f-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="66e1f-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="66e1f-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="66e1f-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="66e1f-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="66e1f-154">
<strong>Lưu ý:</strong> Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="66e1f-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="66e1f-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="66e1f-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="66e1f-156">Điện</span><span class="sxs-lookup"><span data-stu-id="66e1f-156">Emails</span></span></li>
<li><span data-ttu-id="66e1f-157">Quy tắc hộp thư phía máy chủ</span><span class="sxs-lookup"><span data-stu-id="66e1f-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="66e1f-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="66e1f-158">Delegates</span></span></li>
<li><span data-ttu-id="66e1f-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="66e1f-160">Ba</span><span class="sxs-lookup"><span data-stu-id="66e1f-160">Calendar</span></span> </li>
<li> <span data-ttu-id="66e1f-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="66e1f-161">Tasks</span></span> </li>
<li> <span data-ttu-id="66e1f-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="66e1f-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="66e1f-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="66e1f-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="66e1f-164">Ký</span><span class="sxs-lookup"><span data-stu-id="66e1f-164">Signatures</span></span> </li>
<li> <span data-ttu-id="66e1f-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="66e1f-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="66e1f-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="66e1f-167">Public folders</span></span> </li>
<li> <span data-ttu-id="66e1f-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="66e1f-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="66e1f-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="66e1f-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="66e1f-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="66e1f-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="66e1f-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="66e1f-174">Quy tắc hộp thư phía máy khách</span><span class="sxs-lookup"><span data-stu-id="66e1f-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="66e1f-175"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="66e1f-176">
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="66e1f-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="66e1f-177">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-178">Điện</span><span class="sxs-lookup"><span data-stu-id="66e1f-178">Emails</span></span> </li>
<li> <span data-ttu-id="66e1f-179">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="66e1f-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="66e1f-180">Ba</span><span class="sxs-lookup"><span data-stu-id="66e1f-180">Calendar</span></span> </li>
<li> <span data-ttu-id="66e1f-181">Mác</span><span class="sxs-lookup"><span data-stu-id="66e1f-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-182">Tắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-182">Rules</span></span> </li>
<li> <span data-ttu-id="66e1f-183">Đại diện</span><span class="sxs-lookup"><span data-stu-id="66e1f-183">Delegates</span></span> </li>
<li> <span data-ttu-id="66e1f-184">Ký</span><span class="sxs-lookup"><span data-stu-id="66e1f-184">Signatures</span></span> </li>
<li> <span data-ttu-id="66e1f-185">Môùi</span><span class="sxs-lookup"><span data-stu-id="66e1f-185">Tasks</span></span> </li>
<li> <span data-ttu-id="66e1f-186">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="66e1f-187">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-188">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="66e1f-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="66e1f-189">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="66e1f-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="66e1f-190">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="66e1f-191">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="66e1f-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="66e1f-192">Google Groups</span><span class="sxs-lookup"><span data-stu-id="66e1f-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="66e1f-193">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="66e1f-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="66e1f-194">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="66e1f-195">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="66e1f-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="66e1f-196">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="66e1f-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="66e1f-197">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="66e1f-198"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="66e1f-199">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="66e1f-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="66e1f-200">Điện</span><span class="sxs-lookup"><span data-stu-id="66e1f-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="66e1f-201">Tắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-201">Rules</span></span> </li>
<li> <span data-ttu-id="66e1f-202">Đại diện</span><span class="sxs-lookup"><span data-stu-id="66e1f-202">Delegates</span></span> </li>
<li> <span data-ttu-id="66e1f-203">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="66e1f-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="66e1f-204">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="66e1f-204">External contacts</span></span> </li>
<li> <span data-ttu-id="66e1f-205">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="66e1f-206">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-207">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="66e1f-208">Ba</span><span class="sxs-lookup"><span data-stu-id="66e1f-208">Calendar</span></span> </li>
<li> <span data-ttu-id="66e1f-209">Ký</span><span class="sxs-lookup"><span data-stu-id="66e1f-209">Signatures</span></span> </li>
<li> <span data-ttu-id="66e1f-210">Môùi</span><span class="sxs-lookup"><span data-stu-id="66e1f-210">Tasks</span></span> </li>
<li> <span data-ttu-id="66e1f-211">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="66e1f-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="66e1f-212">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="66e1f-212">Archive data</span></span> </li>
<li> <span data-ttu-id="66e1f-213">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="66e1f-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="66e1f-214">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="66e1f-215">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="66e1f-216">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="66e1f-216">FastTrack responsibilities</span></span>

<span data-ttu-id="66e1f-217">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-218">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="66e1f-219">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="66e1f-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="66e1f-220">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="66e1f-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="66e1f-221">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-221">Your responsibilities</span></span>

<span data-ttu-id="66e1f-222">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-223">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="66e1f-224">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="66e1f-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="66e1f-225">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="66e1f-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="66e1f-226">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="66e1f-227">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="66e1f-228">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="66e1f-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="66e1f-229">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="66e1f-230">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="66e1f-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="66e1f-231">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="66e1f-232">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="66e1f-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="66e1f-233">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="66e1f-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="66e1f-234">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="66e1f-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="66e1f-235">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="66e1f-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="66e1f-236">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="66e1f-237">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="66e1f-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="66e1f-238">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="66e1f-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="66e1f-239">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="66e1f-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="66e1f-240">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="66e1f-241">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="66e1f-242">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-242">You create and schedule your migration events.</span></span> <span data-ttu-id="66e1f-243">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="66e1f-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="66e1f-244">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="66e1f-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="66e1f-245">Nhắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-245">Considerations</span></span>

  - <span data-ttu-id="66e1f-246">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="66e1f-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="66e1f-247">Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-247">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="66e1f-248">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="66e1f-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="66e1f-249">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="66e1f-249">Source environment details</span></span>

<span data-ttu-id="66e1f-250">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="66e1f-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="66e1f-251">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="66e1f-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="66e1f-252">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="66e1f-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="66e1f-253">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="66e1f-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="66e1f-254">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="66e1f-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="66e1f-255">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="66e1f-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="66e1f-256"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="66e1f-257"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="66e1f-258"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="66e1f-259"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="66e1f-260"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="66e1f-261">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-262">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-262">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-263">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-264">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="66e1f-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="66e1f-265">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="66e1f-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="66e1f-266">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-267">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-268">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-268">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-269">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-269">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-270">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-270">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-271">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="66e1f-272">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="66e1f-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="66e1f-273">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="66e1f-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="66e1f-274">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="66e1f-275">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="66e1f-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-276">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="66e1f-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="66e1f-277">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-278">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="66e1f-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="66e1f-279">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="66e1f-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="66e1f-280">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="66e1f-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="66e1f-281">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="66e1f-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="66e1f-282">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="66e1f-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="66e1f-283">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="66e1f-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="66e1f-284">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-285">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="66e1f-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="66e1f-286">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="66e1f-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="66e1f-287">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="66e1f-288"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="66e1f-289">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-290">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="66e1f-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="66e1f-291">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-292">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-293">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-294">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-295">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-296">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-296">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-297">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-297">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-298">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-298">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-299">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-300">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="66e1f-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="66e1f-301">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-302">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-303">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="66e1f-304">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-305">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-306">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-307">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-308">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-309">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-310">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-311">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-312">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="66e1f-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="66e1f-313">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="66e1f-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="66e1f-314">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="66e1f-315">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="66e1f-316">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-317">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-318">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="66e1f-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="66e1f-319">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-320">Các tệp được đánh dấu là hạn chế hoặc không được copyable</span><span class="sxs-lookup"><span data-stu-id="66e1f-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="66e1f-321">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="66e1f-322"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="66e1f-323">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-324">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-324">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-325">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-326">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-327">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-328">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-329">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-330">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-330">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-331">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-331">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-332">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-332">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-333">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-334">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="66e1f-335">Ghi chú hộp (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="66e1f-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-336">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-337">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="66e1f-338">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-339">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-340">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-341">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-342">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-343">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-344">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-345">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-346">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="66e1f-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="66e1f-347">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="66e1f-348">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-349">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-350">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="66e1f-351"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="66e1f-352">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-353">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-353">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-354">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-355">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-356">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-357">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-358">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-359">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-359">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-360">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-360">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-361">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-361">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-362">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-363">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="66e1f-364">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-365">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-366">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="66e1f-367">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-368">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-369">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-370">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-371">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-372">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-373">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-374">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="66e1f-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="66e1f-375">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="66e1f-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="66e1f-376">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="66e1f-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="66e1f-377">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="66e1f-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="66e1f-378">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="66e1f-379">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-380">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="66e1f-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="66e1f-381">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="66e1f-382">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="66e1f-382">FastTrack responsibilities</span></span>

<span data-ttu-id="66e1f-383">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-384">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="66e1f-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="66e1f-385">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-385">Your responsibilities</span></span>

<span data-ttu-id="66e1f-386">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-387">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="66e1f-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="66e1f-388">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="66e1f-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="66e1f-389">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="66e1f-390">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="66e1f-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="66e1f-391">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="66e1f-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="66e1f-392">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="66e1f-393">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-393">You create and schedule your migration events.</span></span> <span data-ttu-id="66e1f-394">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="66e1f-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="66e1f-395">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="66e1f-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="66e1f-396">Nhắc</span><span class="sxs-lookup"><span data-stu-id="66e1f-396">Considerations</span></span>

  - <span data-ttu-id="66e1f-397">Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="66e1f-397">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="66e1f-398">Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-398">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="66e1f-399">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="66e1f-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="66e1f-400">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="66e1f-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="66e1f-401">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="66e1f-401">Source environment details</span></span>

<span data-ttu-id="66e1f-402">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="66e1f-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="66e1f-403">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="66e1f-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="66e1f-404">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="66e1f-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="66e1f-405">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="66e1f-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="66e1f-406">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="66e1f-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="66e1f-407">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="66e1f-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="66e1f-408"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="66e1f-409"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="66e1f-410"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="66e1f-411"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="66e1f-412"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="66e1f-413">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-414">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-414">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-415">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-416">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="66e1f-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="66e1f-417">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="66e1f-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="66e1f-418">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-419">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-420">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-420">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-421">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-421">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-422">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-422">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-423">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="66e1f-424">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="66e1f-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="66e1f-425">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="66e1f-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="66e1f-426">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="66e1f-427">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="66e1f-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="66e1f-428">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="66e1f-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="66e1f-429">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-430">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="66e1f-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="66e1f-431">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="66e1f-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="66e1f-432">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="66e1f-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="66e1f-433">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="66e1f-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="66e1f-434">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="66e1f-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="66e1f-435">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="66e1f-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="66e1f-436">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-437">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="66e1f-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="66e1f-438">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="66e1f-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="66e1f-439">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="66e1f-440"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="66e1f-441">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-442">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="66e1f-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="66e1f-443">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-444">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-445">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-446">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-447">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-448">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-448">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-449">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-449">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-450">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-450">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-451">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-452">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="66e1f-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="66e1f-453">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-454">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-455">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="66e1f-456">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-457">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-458">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-459">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-460">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-461">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-462">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-463">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-464">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="66e1f-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="66e1f-465">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="66e1f-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="66e1f-466">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="66e1f-467">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="66e1f-468">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-469">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-470">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="66e1f-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="66e1f-471">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-472">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="66e1f-473"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="66e1f-474">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-475">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-475">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-476">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-477">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-478">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-479">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-480">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-481">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-481">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-482">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-482">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-483">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-483">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-484">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-485">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-486">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-487">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="66e1f-488">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-489">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-490">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-491">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-492">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-493">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-494">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-495">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="66e1f-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="66e1f-496">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="66e1f-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="66e1f-497">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="66e1f-498">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-499">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-500">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="66e1f-501"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="66e1f-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="66e1f-502">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="66e1f-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="66e1f-503">Liên</span><span class="sxs-lookup"><span data-stu-id="66e1f-503">Documents</span></span> </li>
<li> <span data-ttu-id="66e1f-504">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="66e1f-505">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-506">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-507">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="66e1f-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="66e1f-508">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="66e1f-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="66e1f-509">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="66e1f-509">Created date</span></span> </li>
<li> <span data-ttu-id="66e1f-510">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="66e1f-510">Modified date</span></span> </li>
<li> <span data-ttu-id="66e1f-511">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="66e1f-511">Created by</span></span> </li>
<li> <span data-ttu-id="66e1f-512">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="66e1f-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="66e1f-513">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="66e1f-514">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="66e1f-515">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="66e1f-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="66e1f-516">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="66e1f-517">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="66e1f-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-518">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="66e1f-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="66e1f-519">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="66e1f-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="66e1f-520">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="66e1f-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="66e1f-521">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="66e1f-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="66e1f-522">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="66e1f-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="66e1f-523">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="66e1f-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="66e1f-524">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="66e1f-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="66e1f-525">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="66e1f-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="66e1f-526">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="66e1f-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="66e1f-527">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="66e1f-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="66e1f-528">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="66e1f-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="66e1f-529">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="66e1f-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="66e1f-530">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="66e1f-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="66e1f-531">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="66e1f-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="66e1f-532">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="66e1f-532">FastTrack responsibilities</span></span>

<span data-ttu-id="66e1f-533">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-534">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="66e1f-535">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="66e1f-535">Your responsibilities</span></span>

<span data-ttu-id="66e1f-536">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="66e1f-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="66e1f-537">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="66e1f-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="66e1f-538">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="66e1f-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="66e1f-539">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="66e1f-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
