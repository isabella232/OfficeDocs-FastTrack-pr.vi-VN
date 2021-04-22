---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 4/21/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển dữ liệu thư và tệp trong môi trường nguồn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại hỗ trợ mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: 07165233711d4d4931f8adac4809b56138078f5a
ms.sourcegitcommit: b8762897f4d286636a3dd4e2ff6473ab5346b232
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 04/21/2021
ms.locfileid: "51927004"
---
# <a name="data-migration"></a><span data-ttu-id="c0123-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-104">Data Migration</span></span>

<span data-ttu-id="c0123-105">FastTrack có thể giúp bạn di chuyển dữ liệu thư và tệp trong môi trường nguồn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="c0123-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="c0123-106">Loại hỗ trợ mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn:</span><span class="sxs-lookup"><span data-stu-id="c0123-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="c0123-107">**Đối với đối tượng thuê Office 365 có 150-499** giấy phép: FastTrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="c0123-108">Chúng tôi hướng dẫn bạn thông qua tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="c0123-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="c0123-109">**Đối với đối tượng thuê Office 365 có từ 500** giấy phép trở lên: FastTrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="c0123-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="c0123-111">Bạn tạo và lên lịch cho các sự kiện di chuyển của mình.</span><span class="sxs-lookup"><span data-stu-id="c0123-111">You create and schedule your migration events.</span></span> <span data-ttu-id="c0123-112">Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.</span><span class="sxs-lookup"><span data-stu-id="c0123-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="c0123-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước ngày 01/09/2017, bạn chỉ cần 150 giấy phép để đủ điều kiện sử dụng dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="c0123-114">Đối với các gói dành cho giáo dục, chỉ giấy phép giảng viên và nhân viên trả phí mới đủ điều kiện sử dụng các dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="c0123-115">Những điều cần cân nhắc</span><span class="sxs-lookup"><span data-stu-id="c0123-115">Considerations</span></span>

  - <span data-ttu-id="c0123-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="c0123-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="c0123-117">Tham khảo [mục Sản phẩm và Khả](products-and-capabilities.md) năng để biết thêm thông tin về dự tính môi trường nguồn đối với Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="c0123-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="c0123-118">Chúng tôi yêu cầu quyền truy nhập và quyền thích hợp đối với môi trường nguồn của bạn và đối tượng thuê Office 365 để cung cấp các dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="c0123-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng không dành cho dữ liệu tuân theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="c0123-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="c0123-120">Khi chúng tôi di chuyển dữ liệu của bạn, dữ liệu đó có thể được chuyển sang, lưu trữ và xử lý ở bất kỳ nơi nào mà chúng tôi duy trì tiện ích (ngoại trừ những điều khác được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="c0123-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="c0123-121">Chúng tôi không thể đảm bảo tốc độ di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="c0123-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="c0123-122">Các sự cố bất ngờ (như các mục không đọc được hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho chúng tôi di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="c0123-123">Các yếu tố bên ngoài nằm ngoài khả năng kiểm soát của chúng tôi (chẳng hạn như những thay đổi đối với giao diện lập trình ứng dụng (API) của bên thứ ba có thể dẫn đến thay đổi, trì hoãn hoặc tạm dừng các dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="c0123-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="c0123-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-124">Migration service availability</span></span>

  - <span data-ttu-id="c0123-125">**Dành cho khách hàng thương mại và Chính phủ Vương quốc Anh:** Chúng tôi cung cấp các dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="c0123-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="c0123-126">**Đối với khách hàng chính phủ/DOD Hoa Kỳ:** Chúng tôi cung cấp các dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc mỗi tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="c0123-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="c0123-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="c0123-127">Migration to Exchange Online</span></span>

<span data-ttu-id="c0123-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c0123-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và Exchange Online cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="c0123-130">Bạn tạo và lên lịch cho các sự kiện di chuyển của mình.</span><span class="sxs-lookup"><span data-stu-id="c0123-130">You create and schedule your migration events.</span></span> <span data-ttu-id="c0123-131">Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.</span><span class="sxs-lookup"><span data-stu-id="c0123-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c0123-132">Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi thư từ hộp thư nguồn được lên lịch và đủ điều kiện thích hợp của môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="c0123-133">Những điều cần cân nhắc</span><span class="sxs-lookup"><span data-stu-id="c0123-133">Considerations</span></span>

  - <span data-ttu-id="c0123-134">Trước khi di chuyển, bạn phải hoàn thành triển năng cốt lõi FastTrack cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="c0123-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="c0123-135">Nếu bạn đã tự mình thực hiện tự lập, bạn phải thông qua các kiểm tra và điều kiện tiên quyết bắt buộc.</span><span class="sxs-lookup"><span data-stu-id="c0123-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c0123-136">Hãy tham khảo [Sản phẩm và Khả năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="c0123-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="c0123-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="c0123-138">Bạn phải thỏa mãn các yêu cầu cụ thể nếu bạn có ý định di chuyển từ môi trường Exchange tại chỗ.</span><span class="sxs-lookup"><span data-stu-id="c0123-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c0123-139">Tham khảo [Điều kiện tiên quyết triển khai kết hợp để biết](https://go.microsoft.com/fwlink/?LinkId=787528) chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="c0123-140">Mỗi môi trường nguồn phải nằm trên mức gói dịch vụ (SP) và tổng số (RU)/cập nhật tích lũy (CU) mới nhất cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="c0123-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="c0123-141">Danh sách phân phối ( đối tượng *MailEnabledGroup)* và liên hệ bên ngoài (đối tượng *MailEnabledContact)* tồn tại trong Active Directory tại chỗ của bạn không phải là một phần trong việc di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="c0123-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="c0123-142">Tuy nhiên, bạn có thể đồng bộ chúng bằng Azure Active Directory (Azure AD) Connect.</span><span class="sxs-lookup"><span data-stu-id="c0123-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="c0123-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="c0123-143">Source environments</span></span>

<span data-ttu-id="c0123-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="c0123-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="c0123-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="c0123-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="c0123-146">Một môi trường email có khả năng IMAP đơn lẻ.</span><span class="sxs-lookup"><span data-stu-id="c0123-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="c0123-147">Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch).</span><span class="sxs-lookup"><span data-stu-id="c0123-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="c0123-148">Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="c0123-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c0123-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c0123-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c0123-151"><strong>Những di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="c0123-152"><strong>Những gì không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c0123-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="c0123-154">
<strong>Lưu ý:</strong> Đối với các phụ thuộc Exchange tại chỗ, hãy xem Điều kiện tiên quyết <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">triển khai kết hợp.</span></a></span><span class="sxs-lookup"><span data-stu-id="c0123-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="c0123-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="c0123-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="c0123-156">Email</span><span class="sxs-lookup"><span data-stu-id="c0123-156">Emails</span></span></li>
<li><span data-ttu-id="c0123-157">Quy tắc hộp thư phía máy chủ</span><span class="sxs-lookup"><span data-stu-id="c0123-157">Server-side mailbox rules</span></span></li>
<li><span data-ttu-id="c0123-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="c0123-158">Delegates</span></span></li>
<li><span data-ttu-id="c0123-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="c0123-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c0123-160">Lịch</span><span class="sxs-lookup"><span data-stu-id="c0123-160">Calendar</span></span> </li>
<li> <span data-ttu-id="c0123-161">Tác vụ</span><span class="sxs-lookup"><span data-stu-id="c0123-161">Tasks</span></span> </li>
<li> <span data-ttu-id="c0123-162">Email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="c0123-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="c0123-163">Email được mã hóa</span><span class="sxs-lookup"><span data-stu-id="c0123-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="c0123-164">Chữ ký</span><span class="sxs-lookup"><span data-stu-id="c0123-164">Signatures</span></span> </li>
<li> <span data-ttu-id="c0123-165">Đã di chuyển lưu trữ cá nhân cùng với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="c0123-166">Các mục có thể khôi phục</span><span class="sxs-lookup"><span data-stu-id="c0123-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="c0123-167">Public folders</span></span> </li>
<li> <span data-ttu-id="c0123-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="c0123-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c0123-169">Lưu trữ ghi nhật ký hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào</span><span class="sxs-lookup"><span data-stu-id="c0123-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="c0123-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-171">Lưu trữ dữ liệu từ tệp Bảng Lưu trữ Cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="c0123-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="c0123-172">Mục bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c0123-173">Hộp thư không hiện hoạt</span><span class="sxs-lookup"><span data-stu-id="c0123-173">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c0123-174">Quy tắc hộp thư phía máy khách</span><span class="sxs-lookup"><span data-stu-id="c0123-174">Client-side mailbox rules</span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-175"><strong>Môi trường G Suite (chỉ Gmail, Danh bạ và Lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-175"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="c0123-176">
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong Thực <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">hiện di chuyển G Suite.</a></span><span class="sxs-lookup"><span data-stu-id="c0123-176">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="c0123-177">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="c0123-177">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-178">Email</span><span class="sxs-lookup"><span data-stu-id="c0123-178">Emails</span></span> </li>
<li> <span data-ttu-id="c0123-179">Liên hệ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="c0123-179">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="c0123-180">Lịch</span><span class="sxs-lookup"><span data-stu-id="c0123-180">Calendar</span></span> </li>
<li> <span data-ttu-id="c0123-181">Nhãn</span><span class="sxs-lookup"><span data-stu-id="c0123-181">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-182">Quy tắc</span><span class="sxs-lookup"><span data-stu-id="c0123-182">Rules</span></span> </li>
<li> <span data-ttu-id="c0123-183">Đại diện</span><span class="sxs-lookup"><span data-stu-id="c0123-183">Delegates</span></span> </li>
<li> <span data-ttu-id="c0123-184">Chữ ký</span><span class="sxs-lookup"><span data-stu-id="c0123-184">Signatures</span></span> </li>
<li> <span data-ttu-id="c0123-185">Tác vụ</span><span class="sxs-lookup"><span data-stu-id="c0123-185">Tasks</span></span> </li>
<li> <span data-ttu-id="c0123-186">Bất kỳ email hoặc tệp đính kèm nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="c0123-186">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c0123-187">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-187">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-188">Lưu trữ dữ liệu từ tệp PST hoặc bất kỳ giải pháp lưu trữ bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="c0123-188">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="c0123-189">Email được quản lý hoặc mã hóa bằng quyền</span><span class="sxs-lookup"><span data-stu-id="c0123-189">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="c0123-190">Mục bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-190">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c0123-191">Google Hangouts\*\*</span><span class="sxs-lookup"><span data-stu-id="c0123-191">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="c0123-192">Nhóm Google</span><span class="sxs-lookup"><span data-stu-id="c0123-192">Google Groups</span></span> </li>
<li> <span data-ttu-id="c0123-193">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="c0123-193">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="c0123-194">Hộp thư không hiện hoạt</span><span class="sxs-lookup"><span data-stu-id="c0123-194">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="c0123-195">Thiết đặt kỳ nghỉ và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="c0123-195">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="c0123-196">Lịch dùng chung, tệp đính kèm đám mây, liên kết Google Hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="c0123-196">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="c0123-197">\*\*Cuộc hội thoại hangout được lưu dưới dạng nhãn sẽ được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-197">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c0123-198"><strong>Nguồn IMAP4 (như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-198"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="c0123-199">Di chuyển bằng công cụ IMAP4 gốc</span><span class="sxs-lookup"><span data-stu-id="c0123-199">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="c0123-200">Email</span><span class="sxs-lookup"><span data-stu-id="c0123-200">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="c0123-201">Quy tắc</span><span class="sxs-lookup"><span data-stu-id="c0123-201">Rules</span></span> </li>
<li> <span data-ttu-id="c0123-202">Đại diện</span><span class="sxs-lookup"><span data-stu-id="c0123-202">Delegates</span></span> </li>
<li> <span data-ttu-id="c0123-203">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="c0123-203">Distribution lists</span></span> </li>
<li> <span data-ttu-id="c0123-204">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="c0123-204">External contacts</span></span> </li>
<li> <span data-ttu-id="c0123-205">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="c0123-205">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="c0123-206">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-206">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-207">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="c0123-207">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="c0123-208">Lịch</span><span class="sxs-lookup"><span data-stu-id="c0123-208">Calendar</span></span> </li>
<li> <span data-ttu-id="c0123-209">Chữ ký</span><span class="sxs-lookup"><span data-stu-id="c0123-209">Signatures</span></span> </li>
<li> <span data-ttu-id="c0123-210">Tác vụ</span><span class="sxs-lookup"><span data-stu-id="c0123-210">Tasks</span></span> </li>
<li> <span data-ttu-id="c0123-211">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="c0123-211">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="c0123-212">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-212">Archive data</span></span> </li>
<li> <span data-ttu-id="c0123-213">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="c0123-213">Encrypted email</span></span> </li>
<li> <span data-ttu-id="c0123-214">Mục bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-214">Corrupted items</span></span> </li>
<li> <span data-ttu-id="c0123-215">Hộp thư không hiện hoạt</span><span class="sxs-lookup"><span data-stu-id="c0123-215">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c0123-216">Trách nhiệm của FastTrack</span><span class="sxs-lookup"><span data-stu-id="c0123-216">FastTrack responsibilities</span></span>

<span data-ttu-id="c0123-217">Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-217">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-218">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-218">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c0123-219">Các Chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, dành riêng cho việc di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="c0123-219">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="c0123-220">Cung cấp hướng dẫn để giúp bạn bật đồng tồn tại định tuyến thư SMTP giữa các môi trường nguồn của bạn và Exchange Online, nếu có.</span><span class="sxs-lookup"><span data-stu-id="c0123-220">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c0123-221">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-221">Your responsibilities</span></span>

<span data-ttu-id="c0123-222">Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-222">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-223">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-223">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c0123-224">Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="c0123-224">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="c0123-225">Triển thị cốt lõi FastTrack cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-225">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="c0123-226">Nếu bạn đã tự mình thực hiện tự lập, bạn phải thông qua các kiểm tra và điều kiện tiên quyết bắt buộc.</span><span class="sxs-lookup"><span data-stu-id="c0123-226">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="c0123-227">Hãy tham khảo [Sản phẩm và Khả năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-227">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="c0123-228">Cài đặt mức độ thích hợp của phần mềm máy khách theo hướng dẫn của Office 365.</span><span class="sxs-lookup"><span data-stu-id="c0123-228">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="c0123-229">Tham khảo Nơi [làm việc Hiện đại để](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-229">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="c0123-230">Thỏa mãn các yêu cầu cụ thể nếu bạn có ý định di chuyển từ môi trường Exchange tại chỗ.</span><span class="sxs-lookup"><span data-stu-id="c0123-230">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="c0123-231">Tham khảo [Điều kiện tiên quyết triển khai kết hợp để biết](https://go.microsoft.com/fwlink/?LinkId=787528) chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-231">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="c0123-232">Đảm bảo mỗi môi trường nguồn nằm trên mức gói dịch vụ (SP) và tổng số (RU)/cập nhật tích lũy (CU) mới nhất, nếu có.</span><span class="sxs-lookup"><span data-stu-id="c0123-232">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="c0123-233">Cấu hình và xác thực đồng tồn tại định tuyến thư SMTP giữa môi trường nguồn của bạn và Exchange Online, nếu có.</span><span class="sxs-lookup"><span data-stu-id="c0123-233">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="c0123-234">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn mức hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="c0123-234">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="c0123-235">Tùy theo nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn ở 85 phần trăm hạn mức hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="c0123-235">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="c0123-236">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="c0123-236">Migrate client-side data if desired.</span></span> <span data-ttu-id="c0123-237">Điều này bao gồm, nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong tệp PST cục bộ, quy tắc Outlook và thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="c0123-237">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="c0123-238">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="c0123-238">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="c0123-239">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="c0123-239">Migration to SharePoint Online</span></span>

<span data-ttu-id="c0123-240">Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-240">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c0123-241">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và SharePoint Online cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-241">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c0123-242">Bạn tạo và lên lịch cho các sự kiện di chuyển của mình.</span><span class="sxs-lookup"><span data-stu-id="c0123-242">You create and schedule your migration events.</span></span> <span data-ttu-id="c0123-243">Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.</span><span class="sxs-lookup"><span data-stu-id="c0123-243">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c0123-244">Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-244">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="c0123-245">Những điều cần cân nhắc</span><span class="sxs-lookup"><span data-stu-id="c0123-245">Considerations</span></span>

 - <span data-ttu-id="c0123-246">Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-246">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c0123-247">Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855">hạn của SharePoint để</a> biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-247">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855">SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="c0123-248">Chúng tôi khuyên bạn nên giới hạn tổng số tiền di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="c0123-248">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c0123-249">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="c0123-249">Source environment details</span></span>

<span data-ttu-id="c0123-250">Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="c0123-250">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c0123-251">Chia sẻ tệp (chia sẻ tệp Chặn Thông báo Máy chủ (SMB) trên thiết bị hỗ trợ trở đi SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="c0123-251">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c0123-252">Môi trường G Suite đơn (chỉ Google Drive).</span><span class="sxs-lookup"><span data-stu-id="c0123-252">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c0123-253">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c0123-253">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c0123-254">Dropbox for Teams (Tiêu chuẩn và Nâng cao).</span><span class="sxs-lookup"><span data-stu-id="c0123-254">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c0123-255">Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="c0123-255">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="c0123-256"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-256"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="c0123-257"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-257"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="c0123-258"><strong>Những di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-258"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c0123-259"><strong>Những gì không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-259"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c0123-260"><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-260"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c0123-261">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-261">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-262">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-262">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-263">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-263">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-264">Quyền đối với tệp và thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-264">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-265">Quyền tệp mức nhóm và thư mục\*</span><span class="sxs-lookup"><span data-stu-id="c0123-265">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-266">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-266">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-267">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-267">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-268">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-268">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-269">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-269">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-270">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-270">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-271">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-271">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="c0123-272">\*Bắt buộc phải có cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="c0123-272">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c0123-273">Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-273">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c0123-274">Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-274">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c0123-275">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-275">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-276">Lịch sử quyền sở hữu và các phiên bản trước đó</span><span class="sxs-lookup"><span data-stu-id="c0123-276">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-277">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-277">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-278">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="c0123-278">Previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-279">Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="c0123-279">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c0123-280">Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="c0123-280">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c0123-281">Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="c0123-281">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c0123-282">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="c0123-282">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c0123-283">Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="c0123-283">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c0123-284">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-284">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-285">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="c0123-285">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c0123-286">Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="c0123-286">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c0123-287">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-287">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-288"><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-288"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c0123-289">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-289">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-290">Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm các tệp có dung lượng trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="c0123-290">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="c0123-291">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-291">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-292">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-292">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-293">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-293">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-294">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-294">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-295">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-295">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-296">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-296">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-297">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-297">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-298">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-298">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-299">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-299">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-300">Ổ đĩa dùng chung (thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="c0123-300">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c0123-301">Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-301">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-302">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-302">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-303">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-303">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c0123-304">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-304">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-305">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-305">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-306">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-306">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-307">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-307">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-308">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-308">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-309">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-309">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-310">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-310">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-311">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-311">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-312">Ảnh, Biểu mẫu, Bản đồ và các ứng dụng được kết nối khác của Google</span><span class="sxs-lookup"><span data-stu-id="c0123-312">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c0123-313">Hình vẽ Google</span><span class="sxs-lookup"><span data-stu-id="c0123-313">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c0123-314">Nội dung chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-314">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c0123-315">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-315">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c0123-316">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-316">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-317">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-317">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-318">Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung.</span><span class="sxs-lookup"><span data-stu-id="c0123-318">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c0123-319">Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-319">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-320">Các tệp được đánh dấu là hạn chế hoặc không thể sao chép</span><span class="sxs-lookup"><span data-stu-id="c0123-320">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="c0123-321">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-321">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c0123-322"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-322"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c0123-323">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-323">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-324">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-324">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-325">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-325">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-326">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-326">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-327">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-327">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-328">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-328">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-329">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-329">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-330">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-330">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-331">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-331">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-332">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-332">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-333">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-333">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-334">Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-334">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="c0123-335">Ghi chú Box (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="c0123-335">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-336">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-336">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-337">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-337">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-338">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-338">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-339">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-339">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-340">Thẻ Hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-340">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-341">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-341">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-342">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-342">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-343">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-343">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-344">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-344">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-345">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-345">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-346">Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc</span><span class="sxs-lookup"><span data-stu-id="c0123-346">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c0123-347">Nội dung không thuộc sở hữu của tài khoản Box được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-347">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c0123-348">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-348">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-349">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-349">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-350">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-350">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-351"><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-351"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c0123-352">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-352">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-353">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-353">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-354">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-354">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-355">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-355">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-356">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-356">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-357">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-357">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-358">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-358">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-359">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-359">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-360">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-360">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-361">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-361">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-362">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-362">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-363">Các thư mục nhóm dùng chung và nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-363">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c0123-364">Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-364">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-365">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-365">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-366">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-366">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-367">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-367">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-368">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-368">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-369">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-369">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-370">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-370">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-371">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-371">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-372">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-372">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-373">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-373">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-374">Thư mục Dropbox chưa đóng tiền</span><span class="sxs-lookup"><span data-stu-id="c0123-374">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c0123-375">Đã xóa hoặc người dùng bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="c0123-375">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c0123-376">Giấy Dropbox, Giới thiệu và Khoảng trống</span><span class="sxs-lookup"><span data-stu-id="c0123-376">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c0123-377">Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao)</span><span class="sxs-lookup"><span data-stu-id="c0123-377">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c0123-378">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-378">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c0123-379">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-379">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-380">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="c0123-380">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="c0123-381">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-381">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c0123-382">Trách nhiệm của FastTrack</span><span class="sxs-lookup"><span data-stu-id="c0123-382">FastTrack responsibilities</span></span>

<span data-ttu-id="c0123-383">Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-383">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-384">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="c0123-384">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c0123-385">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-385">Your responsibilities</span></span>

<span data-ttu-id="c0123-386">Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-386">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-387">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="c0123-387">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="c0123-388">Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="c0123-388">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="c0123-389">Cung cấp tất cả các site nhóm SharePoint được mục tiêu bởi các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-389">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="c0123-390">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="c0123-390">Migration to OneDrive for Business</span></span>

<span data-ttu-id="c0123-391">Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-391">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c0123-392">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch di chuyển, đặt cấu hình môi trường nguồn và OneDrive for Business cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-392">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c0123-393">Bạn tạo và lên lịch cho các sự kiện di chuyển của mình.</span><span class="sxs-lookup"><span data-stu-id="c0123-393">You create and schedule your migration events.</span></span> <span data-ttu-id="c0123-394">Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.</span><span class="sxs-lookup"><span data-stu-id="c0123-394">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c0123-395">Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="c0123-395">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="c0123-396">Những điều cần cân nhắc</span><span class="sxs-lookup"><span data-stu-id="c0123-396">Considerations</span></span>

  - <span data-ttu-id="c0123-397">Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-397">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c0123-398">Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> hạn của SharePoint để</a> biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-398">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
  - <span data-ttu-id="c0123-399">Chúng tôi khuyên bạn nên giới hạn lượng dữ liệu tổng thể mà bạn di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="c0123-399">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="c0123-400">FastTrack chỉ di chuyển sang ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="c0123-400">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="c0123-401">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="c0123-401">Source environment details</span></span>

<span data-ttu-id="c0123-402">Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="c0123-402">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="c0123-403">Chia sẻ tệp (chia sẻ tệp SMB trên thiết bị hỗ trợ SMB 2.0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="c0123-403">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="c0123-404">Môi trường G Suite Đơn (chỉ Google Drive).</span><span class="sxs-lookup"><span data-stu-id="c0123-404">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="c0123-405">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c0123-405">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="c0123-406">Dropbox for Teams (Tiêu chuẩn và Nâng cao).</span><span class="sxs-lookup"><span data-stu-id="c0123-406">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="c0123-407">Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="c0123-407">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c0123-408"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-408"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c0123-409"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-409"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c0123-410"><strong>Những di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-410"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c0123-411"><strong>Những gì không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-411"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c0123-412"><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-412"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c0123-413">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-413">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-414">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-414">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-415">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-415">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-416">Quyền đối với tệp và thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-416">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-417">Quyền tệp mức nhóm và thư mục\*</span><span class="sxs-lookup"><span data-stu-id="c0123-417">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-418">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-418">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-419">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-419">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-420">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-420">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-421">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-421">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-422">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-422">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-423">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-423">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c0123-424">\*Bắt buộc phải có cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="c0123-424">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c0123-425">Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-425">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c0123-426">Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-426">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c0123-427">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-427">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c0123-428">Lịch sử quyền sở hữu và các phiên bản trước đó</span><span class="sxs-lookup"><span data-stu-id="c0123-428">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-429">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-429">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-430">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="c0123-430">Previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-431">Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="c0123-431">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c0123-432">Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="c0123-432">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c0123-433">Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="c0123-433">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c0123-434">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="c0123-434">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c0123-435">Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="c0123-435">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c0123-436">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-436">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-437">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="c0123-437">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c0123-438">Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="c0123-438">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c0123-439">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-439">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-440"><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-440"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c0123-441">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-441">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-442">Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm các tệp trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="c0123-442">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c0123-443">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-443">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-444">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-444">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-445">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-445">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-446">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-446">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-447">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-447">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-448">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-448">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-449">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-449">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-450">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-450">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-451">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-451">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-452">Ổ đĩa dùng chung (thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="c0123-452">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c0123-453">Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-453">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-454">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-454">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-455">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-455">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c0123-456">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-456">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-457">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-457">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-458">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-458">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-459">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-459">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-460">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-460">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-461">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-461">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-462">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-462">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-463">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-463">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-464">Biểu mẫu Ảnh, Bản đồ và các ứng dụng được kết nối khác của Google</span><span class="sxs-lookup"><span data-stu-id="c0123-464">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c0123-465">Hình vẽ Google</span><span class="sxs-lookup"><span data-stu-id="c0123-465">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c0123-466">Nội dung chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-466">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c0123-467">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-467">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c0123-468">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-468">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-469">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-469">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-470">Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung.</span><span class="sxs-lookup"><span data-stu-id="c0123-470">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c0123-471">Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-471">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-472">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-472">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c0123-473"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-473"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c0123-474">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-474">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-475">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-475">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-476">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-476">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-477">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-477">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-478">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-478">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-479">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-479">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-480">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-480">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-481">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-481">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-482">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-482">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-483">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-483">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-484">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-484">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-485">Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-485">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-486">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-486">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-487">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-487">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-488">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-488">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-489">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-489">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-490">Thẻ Hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-490">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-491">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-491">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-492">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-492">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-493">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-493">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-494">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-494">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-495">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-495">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-496">Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc</span><span class="sxs-lookup"><span data-stu-id="c0123-496">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c0123-497">Nội dung không thuộc sở hữu của tài khoản Box được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-497">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c0123-498">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-498">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-499">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-499">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-500">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-500">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-501"><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-501"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c0123-502">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-502">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-503">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-503">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-504">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-504">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-505">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-505">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-506">Quyền thư mục mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-506">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="c0123-507">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-507">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-508">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-508">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-509">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-509">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-510">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-510">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-511">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-511">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-512">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-512">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-513">Các thư mục nhóm dùng chung và nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-513">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c0123-514">Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-514">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="c0123-515">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-515">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-516">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-516">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-517">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-517">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-518">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-518">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-519">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-519">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-520">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-520">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-521">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-521">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-522">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-522">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-523">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-523">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-524">Thư mục Dropbox chưa đóng tiền</span><span class="sxs-lookup"><span data-stu-id="c0123-524">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c0123-525">Đã xóa hoặc người dùng bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="c0123-525">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c0123-526">Giấy Dropbox, Giới thiệu và Khoảng trống</span><span class="sxs-lookup"><span data-stu-id="c0123-526">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c0123-527">Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao)</span><span class="sxs-lookup"><span data-stu-id="c0123-527">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c0123-528">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-528">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c0123-529">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-529">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-530">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-530">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-531">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-531">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c0123-532">Trách nhiệm của FastTrack</span><span class="sxs-lookup"><span data-stu-id="c0123-532">FastTrack responsibilities</span></span>

<span data-ttu-id="c0123-533">Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-533">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-534">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-534">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c0123-535">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-535">Your responsibilities</span></span>

<span data-ttu-id="c0123-536">Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-536">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-537">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-537">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="c0123-538">Bạn cũng có thể thực hiện các hoạt động sau đây, dành riêng cho di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="c0123-538">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="c0123-539">Cung cấp tất cả các site OneDrive for Business mà sẽ được hướng mục tiêu bởi các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-539">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>

## <a name="migration-to-microsoft-teams-and-microsoft-365-groups"></a><span data-ttu-id="c0123-540">Di chuyển sang Microsoft Teams và Nhóm Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="c0123-540">Migration to Microsoft Teams and Microsoft 365 Groups</span></span>

<span data-ttu-id="c0123-541">Khi bạn chọn sử dụng FastTrack để di chuyển tệp sang Microsoft Teams và Nhóm Microsoft 365, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="c0123-541">When you choose to use FastTrack to migrate your files to Microsoft Teams and Microsoft 365 Groups, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="c0123-542">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển, đặt cấu hình môi trường nguồn cũng như Teams và Nhóm Microsoft 365, cũng như tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-542">We provide guidance to help you plan your migration, configure your source environments and Teams and Microsoft 365 Groups, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="c0123-543">Bạn tạo và lên lịch cho các sự kiện di chuyển của mình.</span><span class="sxs-lookup"><span data-stu-id="c0123-543">You create and schedule your migration events.</span></span> <span data-ttu-id="c0123-544">Chúng tôi sẽ khởi chạy các sự kiện di chuyển theo lịch biểu của bạn, theo dõi tiến độ của sự kiện và cung cấp báo cáo tình trạng.</span><span class="sxs-lookup"><span data-stu-id="c0123-544">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="c0123-545">Khi các sự kiện di chuyển của bạn hoàn tất, bạn có thể mong đợi các tệp từ các nguồn có lịch biểu và đủ điều kiện thích hợp từ môi trường nguồn của bạn đã được di chuyển sang Teams và Nhóm Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c0123-545">When your migration events are completed, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to Teams and Microsoft 365 Groups.</span></span> <span data-ttu-id="c0123-546">Các kênh Teams và Nhóm Microsoft 365 phải được khách hàng cung cấp trước trước khi có thể di chuyển dữ liệu vào các loại đích này.</span><span class="sxs-lookup"><span data-stu-id="c0123-546">Teams channels and Microsoft 365 Groups  must be pre-provisioned by the customer before they can migrate data into these destination types.</span></span> <span data-ttu-id="c0123-547">Teams và Nhóm Microsoft 365 ảnh hưởng đến quyền của bạn trên vị trí đích của tệp.</span><span class="sxs-lookup"><span data-stu-id="c0123-547">Teams and Microsoft 365 Groups impacts your permissions on the file destination location.</span></span> <span data-ttu-id="c0123-548">Teams và Nhóm Microsoft 365 được xây dựng để cho phép cộng tác.</span><span class="sxs-lookup"><span data-stu-id="c0123-548">Teams and Microsoft 365 Groups are built to allow collaboration.</span></span> <span data-ttu-id="c0123-549">Kênh Teams hoặc nhóm Microsoft 365 xác định ai có quyền truy nhập vào các tệp đó khi di chuyển vào các đích đó.</span><span class="sxs-lookup"><span data-stu-id="c0123-549">The Teams channel or Microsoft 365 group determine who has access to those files when migrating into those destinations.</span></span> <span data-ttu-id="c0123-550">FastTrack không thêm người dùng cuối hoặc nhóm vào bất kỳ kênh Teams hoặc quyền Nhóm Microsoft 365 nào trong quá trình di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-550">FastTrack doesn't add end users or groups to any Teams channel or Microsoft 365 Groups permission during migration.</span></span>

## <a name="considerations"></a><span data-ttu-id="c0123-551">Những điều cần cân nhắc</span><span class="sxs-lookup"><span data-stu-id="c0123-551">Considerations</span></span>

- <span data-ttu-id="c0123-552">Tất cả các di chuyển đều tuân theo hạn ngạch SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="c0123-552">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="c0123-553">Tham khảo giới <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> hạn của SharePoint để</a> biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-553">Refer to <a href="https://go.microsoft.com/fwlink/?LinkId=698855"> SharePoint limits</a> for details.</span></span> 
- <span data-ttu-id="c0123-554">Chúng tôi khuyên bạn nên giới hạn tổng số tiền di chuyển đến 75 phần trăm của hạn mức lưu trữ SharePoint Online tổng thể mà bạn được quyền (bao gồm dung lượng lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="c0123-554">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span> 


## <a name="source-environment-details"></a><span data-ttu-id="c0123-555">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="c0123-555">Source environment details</span></span>

<span data-ttu-id="c0123-556">Các dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ các môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="c0123-556">Our data migration services migrate data from these source environments:</span></span> 

- <span data-ttu-id="c0123-557">Chia sẻ tệp (chia sẻ tệp Chặn Thông báo Máy chủ (SMB) trên thiết bị hỗ trợ trở đi SMB 2.0).</span><span class="sxs-lookup"><span data-stu-id="c0123-557">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
-  <span data-ttu-id="c0123-558">Môi trường G Suite đơn (chỉ Google Drive).</span><span class="sxs-lookup"><span data-stu-id="c0123-558">A single G Suite environment (Google Drive only).</span></span> 
- <span data-ttu-id="c0123-559">Box (Starter, Business, Enterprise).</span><span class="sxs-lookup"><span data-stu-id="c0123-559">Box (Starter, Business, Enterprise).</span></span> 
- <span data-ttu-id="c0123-560">Dropbox for Teams (Tiêu chuẩn và Nâng cao).</span><span class="sxs-lookup"><span data-stu-id="c0123-560">Dropbox for Teams (Standard and Advanced).</span></span> 

<span data-ttu-id="c0123-561">Bảng sau đây trình bày chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="c0123-561">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="c0123-562"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-562"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="c0123-563"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-563"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="c0123-564"><strong>Những di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-564"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="c0123-565"><strong>Những gì không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-565"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="c0123-566"><strong>Mọi thiết bị chia sẻ tệp hỗ trợ SMB 2.0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-566"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="c0123-567">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-567">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-568">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-568">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-569">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-569">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-570">Quyền đối với tệp và thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-570">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-571">Quyền tệp mức nhóm và thư mục\*</span><span class="sxs-lookup"><span data-stu-id="c0123-571">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-572">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-572">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-573">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-573">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-574">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-574">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-575">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-575">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-576">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-576">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-577">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-577">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="c0123-578">\*Bắt buộc phải có cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="c0123-578">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="c0123-579">Chỉ những quyền NTFS được chuyển sang Windows File Explorer mới được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-579">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="c0123-580">Các quyền được quản lý trực tiếp trên thiết bị chia sẻ tệp sẽ không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-580">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="c0123-581">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2.0, các quyền tương đương NTFS mà giao thức SMB cung cấp sẽ được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-581">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> <span data-ttu-id="c0123-582">Quyền bị ảnh hưởng bởi Nhóm Microsoft 365 và/hoặc kênh Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-582">Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="c0123-583">Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-583">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="c0123-584">Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-584">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-585">Lịch sử quyền sở hữu và các phiên bản trước đó</span><span class="sxs-lookup"><span data-stu-id="c0123-585">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-586">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-586">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-587">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="c0123-587">Previous versions</span></span> </li>
<li> <span data-ttu-id="c0123-588">Thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="c0123-588">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="c0123-589">Hệ thống Tệp Công nghệ Mới Không phải Windows (NTFS) và các quyền nâng cao NTFS và cài đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="c0123-589">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="c0123-590">Các quyền từ chối rõ ràng (bị loại bỏ sau khi di chuyển, nội dung cần phải tuân theo các quyền song song hoặc các quyền trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="c0123-590">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="c0123-591">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="c0123-591">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="c0123-592">Siêu dữ liệu tệp bổ sung được cung cấp bởi Cơ sở hạ tầng Phân loại Tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="c0123-592">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="c0123-593">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-593">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-594">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="c0123-594">Hidden shares</span></span> </li>
<li> <span data-ttu-id="c0123-595">Chia sẻ (chẳng hạn như quyền được cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="c0123-595">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="c0123-596">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-596">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-597"><strong>Môi trường G Suite Đơn (chỉ Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-597"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="c0123-598">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-598">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-599">Tài liệu, Trang tính và Trang chiếu của Google (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm các tệp trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="c0123-599">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="c0123-600">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-600">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-601">Quyền thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-601">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-602">Quyền thư mục mức nhóm\*</span><span class="sxs-lookup"><span data-stu-id="c0123-602">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-603">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-603">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-604">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-604">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-605">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-605">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-606">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-606">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-607">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-607">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-608">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-608">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-609">Ổ đĩa dùng chung (thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="c0123-609">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="c0123-610">Nội dung chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-610">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="c0123-611">\*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-611">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="c0123-612">Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-612">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="c0123-613">Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-613">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> 
</td>
<td><ul>
<li> <span data-ttu-id="c0123-614">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-614">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-615">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-615">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="c0123-616">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-616">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-617">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-617">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-618">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-618">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-619">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-619">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-620">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-620">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-621">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-621">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-622">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-622">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-623">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-623">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-624">Biểu mẫu Ảnh, Bản đồ và các ứng dụng được kết nối khác của Google</span><span class="sxs-lookup"><span data-stu-id="c0123-624">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="c0123-625">Hình vẽ Google</span><span class="sxs-lookup"><span data-stu-id="c0123-625">Google Drawings</span></span> </li>
<li> <span data-ttu-id="c0123-626">Nội dung chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-626">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="c0123-627">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-627">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="c0123-628">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Sử dụng báo cáo Người quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-628">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-629">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-629">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-630">Quyền tư cách thành viên ổ đĩa dùng chung<strong>(Lưu</strong>ý: Sử dụng báo cáo Người quản trị Google Drive để xác định tư cách thành viên ổ đĩa dùng chung.</span><span class="sxs-lookup"><span data-stu-id="c0123-630">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="c0123-631">Hướng dẫn người dùng cuối cấu hình các thiết đặt tư cách thành viên này theo mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-631">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-632">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-632">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="c0123-633"><strong>Box (Starter, Business, Enterprise)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-633"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="c0123-634">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-634">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-635">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-635">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-636">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-636">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-637">Quyền thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-637">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-638">Quyền thư mục mức nhóm\*</span><span class="sxs-lookup"><span data-stu-id="c0123-638">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-639">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-639">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-640">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-640">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-641">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-641">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-642">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-642">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-643">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-643">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-644">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-644">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-645">Nội dung chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-645">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="c0123-646">Ghi chú Box (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="c0123-646">Box Notes (converted to Word document format)</span></span> </li>
</ul>
<br>
<span data-ttu-id="c0123-647">\*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-647">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="c0123-648">Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-648">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="c0123-649">Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-649">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="c0123-650">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-650">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-651">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-651">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-652">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-652">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-653">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-653">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-654">Thẻ Hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-654">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-655">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-655">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-656">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-656">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-657">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-657">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-658">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-658">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-659">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="c0123-659">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="c0123-660">Ứng dụng Box, Thẻ đánh dấu, Yêu thích và Dòng công việc</span><span class="sxs-lookup"><span data-stu-id="c0123-660">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="c0123-661">Nội dung không thuộc sở hữu của tài khoản Box được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-661">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="c0123-662">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Báo cáo Use Box để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-662">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-663">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-663">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-664">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-664">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="c0123-665"><strong>Dropbox for Teams (Tiêu chuẩn và Nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="c0123-665"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="c0123-666">Truyền một lần hoặc nhiều lần</span><span class="sxs-lookup"><span data-stu-id="c0123-666">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="c0123-667">Tài liệu</span><span class="sxs-lookup"><span data-stu-id="c0123-667">Documents</span></span> </li>
<li> <span data-ttu-id="c0123-668">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-668">File and folder structure</span></span> </li>
<li> <span data-ttu-id="c0123-669">Quyền thư mục mức người dùng\*</span><span class="sxs-lookup"><span data-stu-id="c0123-669">User-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-670">Quyền thư mục mức nhóm\*</span><span class="sxs-lookup"><span data-stu-id="c0123-670">Group-level folder permissions\*</span></span> </li>
<li> <span data-ttu-id="c0123-671">Các tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="c0123-671">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="c0123-672">Siêu dữ liệu tài liệu cơ bản và thư mục:</span><span class="sxs-lookup"><span data-stu-id="c0123-672">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="c0123-673">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-673">Created date</span></span> </li>
<li> <span data-ttu-id="c0123-674">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="c0123-674">Modified date</span></span> </li>
<li> <span data-ttu-id="c0123-675">Người tạo</span><span class="sxs-lookup"><span data-stu-id="c0123-675">Created by</span></span> </li>
<li> <span data-ttu-id="c0123-676">Sửa đổi lần cuối bởi</span><span class="sxs-lookup"><span data-stu-id="c0123-676">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="c0123-677">Các thư mục nhóm dùng chung và nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-677">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="c0123-678">Nội dung chia sẻ thuộc sở hữu của tài khoản Dropbox đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-678">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul>
<br>
<span data-ttu-id="c0123-679">\*Quyền bị ảnh hưởng bởi kênh Nhóm Microsoft 365 và/hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-679">\*Permissions are impacted by the Microsoft 365 Group and/or Microsoft Teams channel.</span></span> <span data-ttu-id="c0123-680">Nếu đích là kênh Nhóm Microsoft 365 hoặc Microsoft Teams, nhóm hoặc kênh đó sẽ xác định hồ sơ quyền cuối cùng trên các tệp đã di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-680">If the destination is a Microsoft 365 Group or Microsoft Teams channel, the group or channel determines the final permissions profile on migrated files.</span></span> <span data-ttu-id="c0123-681">Chúng tôi khuyên bạn không nên di chuyển quyền trên các tệp di chuyển sang kênh Nhóm Microsoft 365 hoặc Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="c0123-681">We recommend not migrating permissions on files migrating to a Microsoft 365 Group or Microsoft Teams channel.</span></span>
</td>
<td><ul>
<li> <span data-ttu-id="c0123-682">Lịch sử quyền sở hữu, các phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="c0123-682">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="c0123-683">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="c0123-683">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="c0123-684">Quyền tệp mức người dùng</span><span class="sxs-lookup"><span data-stu-id="c0123-684">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-685">Quyền tệp mức nhóm</span><span class="sxs-lookup"><span data-stu-id="c0123-685">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="c0123-686">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="c0123-686">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="c0123-687">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="c0123-687">File lock attributes</span></span> </li>
<li> <span data-ttu-id="c0123-688">Chuyển đổi các URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="c0123-688">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="c0123-689">Các mục đã đổ rác</span><span class="sxs-lookup"><span data-stu-id="c0123-689">Trashed items</span></span> </li>
<li> <span data-ttu-id="c0123-690">Tài liệu không thể tiếp cận hoặc bị hỏng</span><span class="sxs-lookup"><span data-stu-id="c0123-690">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="c0123-691">Thư mục Dropbox chưa đóng tiền</span><span class="sxs-lookup"><span data-stu-id="c0123-691">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="c0123-692">Đã xóa hoặc người dùng bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="c0123-692">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="c0123-693">Giấy Dropbox, Giới thiệu và Khoảng trống</span><span class="sxs-lookup"><span data-stu-id="c0123-693">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="c0123-694">Ứng dụng và Mục yêu thích Dropbox (Ghim/Sao)</span><span class="sxs-lookup"><span data-stu-id="c0123-694">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="c0123-695">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-695">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="c0123-696">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài ( Lưu<strong>ý:</strong>Dùng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="c0123-696">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="c0123-697">Hướng dẫn người dùng cuối chia sẻ lại nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="c0123-697">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="c0123-698">Tệp hoặc thư mục vượt quá giới hạn và giới hạn của <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">SharePoint Online hiện tại</span></a> </span><span class="sxs-lookup"><span data-stu-id="c0123-698">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="c0123-699">Trách nhiệm của FastTrack</span><span class="sxs-lookup"><span data-stu-id="c0123-699">FastTrack responsibilities</span></span>

<span data-ttu-id="c0123-700">Các Chuyên gia FastTrack của chúng tôi thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-700">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-701">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-701">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="c0123-702">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="c0123-702">Your responsibilities</span></span> 

<span data-ttu-id="c0123-703">Bạn thực hiện các hoạt động tiêu chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="c0123-703">You perform standard activities during the migration project.</span></span> <span data-ttu-id="c0123-704">Tham khảo thông tin về trách nhiệm di chuyển dữ liệu trong phần [Quy trình và Kỳ vọng](process-and-expectations.md) đối với các chi tiết.</span><span class="sxs-lookup"><span data-stu-id="c0123-704">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>
<span data-ttu-id="c0123-705">Bạn cũng có thể thực hiện các hoạt động sau, dành riêng cho di chuyển Nhóm Microsoft Teams và Microsoft 365:</span><span class="sxs-lookup"><span data-stu-id="c0123-705">You also perform the following activities, specific to Microsoft Teams and Microsoft 365 Groups migrations:</span></span> 

- <span data-ttu-id="c0123-706">Cung cấp tất cả các kênh Microsoft Teams và Nhóm Microsoft 365 làm mục tiêu theo các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="c0123-706">Provision all Microsoft Teams channels and Microsoft 365 Groups as targeted by your migration events.</span></span>

> [!NOTE]
><span data-ttu-id="c0123-707">FastTrack không cung cấp trước các kênh Microsoft Teams hoặc Nhóm Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c0123-707">FastTrack doesn't pre-provision Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="c0123-708">FastTrack không thêm người dùng cuối hoặc nhóm vào các kênh Microsoft Teams hoặc Nhóm Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="c0123-708">FastTrack doesn't add end users or groups to Microsoft Teams channels or Microsoft 365 Groups.</span></span> <span data-ttu-id="c0123-709">Bạn phải thêm người dùng cuối hoặc nhóm vào tất cả các kênh Microsoft Teams và Nhóm Microsoft 365 trước khi bạn di chuyển dữ liệu vào các đích đó để những người dùng cuối đó có quyền truy nhập vào những tài liệu mới được di chuyển</span><span class="sxs-lookup"><span data-stu-id="c0123-709">You must add your end users or groups to all Microsoft Teams channels and Microsoft 365 Groups before you migrate data into those destinations so those end users have access to those newly migrated documents</span></span>