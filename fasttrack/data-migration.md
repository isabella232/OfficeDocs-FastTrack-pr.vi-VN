---
title: Di chuyển dữ liệu
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 1/4/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business). Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365 của bạn.
ms.openlocfilehash: ec7bc5cf9c25ef1e386c7fae42a5fd8e1716dee5
ms.sourcegitcommit: cf07b074931fd6877ba7e8938440dc7ebaf4ac69
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 01/04/2021
ms.locfileid: "49750049"
---
# <a name="data-migration"></a><span data-ttu-id="b5182-104">Di chuyển dữ liệu</span><span class="sxs-lookup"><span data-stu-id="b5182-104">Data Migration</span></span>

<span data-ttu-id="b5182-105">FastTrack có thể giúp bạn di chuyển thư và dữ liệu tệp trong môi trường nguồn của bạn sang Office 365 (Exchange Online, SharePoint Online và OneDrive for Business).</span><span class="sxs-lookup"><span data-stu-id="b5182-105">FastTrack can help you migrate mail and file data in your source environments to Office 365 (Exchange Online, SharePoint Online, and OneDrive for Business).</span></span>

<span data-ttu-id="b5182-106">Loại trợ giúp mà chúng tôi cung cấp phụ thuộc vào số lượng giấy phép Office 365:</span><span class="sxs-lookup"><span data-stu-id="b5182-106">The type of assistance we provide depends on your number of Office 365 licenses:</span></span>

  - <span data-ttu-id="b5182-107">**Đối với đối tượng thuê Office 365 với 150-499 giấy phép**: fasttrack chỉ cung cấp hướng dẫn di chuyển; bạn chịu trách nhiệm thực hiện di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-107">**For Office 365 tenants with 150-499 licenses**: FastTrack provides migration guidance only; you are responsible for performing the data migration.</span></span> <span data-ttu-id="b5182-108">Chúng tôi hướng dẫn bạn qua các tài liệu giúp bạn lập kế hoạch và sử dụng các công cụ miễn phí để thực hiện di chuyển tự phục vụ.</span><span class="sxs-lookup"><span data-stu-id="b5182-108">We guide you through documentation that helps you plan and use free tools to perform a self-service migration.</span></span>
  - <span data-ttu-id="b5182-109">**Đối với đối tượng thuê Office 365 với 500 hoặc nhiều giấy phép**: fasttrack cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-109">**For Office 365 tenants with 500 or more licenses**: FastTrack provides migration guidance and data migration services.</span></span> <span data-ttu-id="b5182-110">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và đối tượng thuê Office 365 và tận dụng dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-110">We provide guidance to help you plan your migration, configure your source environments and Office 365 tenant, and leverage our data migration services to migrate your data.</span></span> <span data-ttu-id="b5182-111">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-111">You create and schedule your migration events.</span></span> <span data-ttu-id="b5182-112">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="b5182-112">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span>

> [!NOTE]
> <span data-ttu-id="b5182-113">Nếu bạn đã mua hoặc gia hạn gói thương mại trước 9/1/2017, bạn chỉ cần có giấy phép 150 để đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-113">If you purchased or renewed a commercial plan prior to 9/1/2017, you need only 150 licenses to qualify for data migration services.</span></span> <span data-ttu-id="b5182-114">Đối với các gói giáo dục, chỉ giấy phép giảng viên và nhân viên đã thanh toán đủ điều kiện cho dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-114">For education plans, only your paid faculty and staff licenses are eligible for data migration services.</span></span>

### <a name="considerations"></a><span data-ttu-id="b5182-115">Nhắc</span><span class="sxs-lookup"><span data-stu-id="b5182-115">Considerations</span></span>

  - <span data-ttu-id="b5182-116">Môi trường nguồn của bạn phải đáp ứng các kỳ vọng cụ thể để di chuyển dữ liệu sang Office 365.</span><span class="sxs-lookup"><span data-stu-id="b5182-116">Your source environments must meet specific expectations in order to migrate data to Office 365.</span></span> <span data-ttu-id="b5182-117">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết thêm thông tin về các kỳ vọng môi trường nguồn cho Exchange, SharePoint và OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b5182-117">Refer to [Products and Capabilities](products-and-capabilities.md) for more information on the source environment expectations for Exchange, SharePoint, and OneDrive for Business.</span></span>
  - <span data-ttu-id="b5182-118">Chúng tôi yêu cầu truy nhập phù hợp và quyền cho môi trường nguồn và đối tượng thuê Office 365 của bạn để cung cấp dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-118">We require appropriate access and permissions to your source environments and Office 365 tenant to provide data migration services.</span></span>
  - <span data-ttu-id="b5182-119">Dịch vụ di chuyển dữ liệu của chúng tôi không được thiết kế cũng như dành cho dữ liệu theo các yêu cầu pháp lý hoặc quy định đặc biệt.</span><span class="sxs-lookup"><span data-stu-id="b5182-119">Our data migration services are neither designed nor intended for data subject to special legal or regulatory requirements.</span></span> <span data-ttu-id="b5182-120">Khi chúng tôi di chuyển dữ liệu của bạn, có thể được chuyển đến, lưu trữ và xử lý bất kỳ nơi nào mà chúng tôi duy trì các cơ sở (ngoại trừ là nếu không được cung cấp cho dự án di chuyển FastTrack của bạn).</span><span class="sxs-lookup"><span data-stu-id="b5182-120">As we migrate your data, it can be transferred to, stored, and processed anywhere that we maintain facilities (except as otherwise provided for your FastTrack migration project).</span></span>
  - <span data-ttu-id="b5182-121">Chúng tôi không thể đảm bảo tốc độ của việc di chuyển thư hoặc tệp.</span><span class="sxs-lookup"><span data-stu-id="b5182-121">We can’t guarantee the speed of mail or file migrations.</span></span>
  - <span data-ttu-id="b5182-122">Các vấn đề không lường trước (chẳng hạn như các mục không đọc hoặc bị hỏng trong môi trường nguồn) có thể ngăn không cho khả năng di chuyển một số mục dữ liệu của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-122">Unforeseen issues (like unreadable or corrupt items in the source environment) may prevent our ability to migrate of some of your data items.</span></span>
  - <span data-ttu-id="b5182-123">Các yếu tố bên ngoài ngoài điều khiển của chúng tôi (như những thay đổi đối với giao diện lập trình ứng dụng của bên thứ ba (API)) có thể dẫn đến các thay đổi, trì hoãn hoặc tạm ngừng dịch vụ di chuyển dữ liệu của chúng tôi.</span><span class="sxs-lookup"><span data-stu-id="b5182-123">External factors beyond our control (like changes to third-party application programming interfaces (APIs)) can result in changes to, delays in, or suspension of our data migration services.</span></span>

### <a name="migration-service-availability"></a><span data-ttu-id="b5182-124">Tính khả dụng của dịch vụ di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-124">Migration service availability</span></span>

  - <span data-ttu-id="b5182-125">**Đối với khách hàng của chính phủ thương mại và Vương Quốc Anh:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, bảy (7) ngày một tuần (24x7).</span><span class="sxs-lookup"><span data-stu-id="b5182-125">**For Commercial and UK Government customers:** We provide data migration services 24 hours a day, seven (7) days a week (24x7).</span></span>
  - <span data-ttu-id="b5182-126">**Đối với khách hàng của chính phủ Hoa Kỳ/DoD:** Chúng tôi cung cấp dịch vụ di chuyển dữ liệu 24 giờ một ngày, năm (5) ngày làm việc một tuần (24x5).</span><span class="sxs-lookup"><span data-stu-id="b5182-126">**For US Government/DOD customers:** We provide data migration services 24 hours a day, five (5) business days a week (24x5).</span></span>

## <a name="migration-to-exchange-online"></a><span data-ttu-id="b5182-127">Di chuyển sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="b5182-127">Migration to Exchange Online</span></span>

<span data-ttu-id="b5182-128">Khi bạn chọn sử dụng FastTrack để di chuyển email của mình sang Exchange Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-128">When you choose to use FastTrack to migrate your email to Exchange Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b5182-129">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và Exchange Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển hộp thư của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-129">We provide guidance to help you plan your migration, configure your source environments and Exchange Online, and leverage our data migration services to migrate your mailboxes.</span></span> <span data-ttu-id="b5182-130">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-130">You create and schedule your migration events.</span></span> <span data-ttu-id="b5182-131">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="b5182-131">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b5182-132">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi thư từ các hộp thư được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b5182-132">When your migration events complete, you can expect mail from appropriately scheduled and eligible source mailboxes of your source environments to have been migrated to Exchange Online.</span></span>

### <a name="considerations"></a><span data-ttu-id="b5182-133">Nhắc</span><span class="sxs-lookup"><span data-stu-id="b5182-133">Considerations</span></span>

  - <span data-ttu-id="b5182-134">Trước khi di chuyển, bạn phải hoàn thành fasttrack Core triển khai cho Exchange Online;</span><span class="sxs-lookup"><span data-stu-id="b5182-134">Prior to migration, you must complete FastTrack core onboarding for Exchange Online;</span></span>
      - <span data-ttu-id="b5182-135">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-135">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b5182-136">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-136">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  - <span data-ttu-id="b5182-137">FastTrack chỉ di chuyển đến hộp thư Office 365 hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="b5182-137">FastTrack migrates only to active Office 365 mailboxes.</span></span>
  - <span data-ttu-id="b5182-138">Bạn phải đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="b5182-138">You must satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b5182-139">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-139">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  - <span data-ttu-id="b5182-140">Mỗi môi trường nguồn phải nằm trên cấp độ gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU) cho sản phẩm tương ứng trong môi trường nguồn.</span><span class="sxs-lookup"><span data-stu-id="b5182-140">Each source environment must be on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level for the respective product in the source environment.</span></span>
  - <span data-ttu-id="b5182-141">Danh sách phân phối (đối tượng *Mailenabledgroup* ) và liên hệ bên ngoài (đối tượng *Mailenabledcontact* ) tồn tại trong Active Directory tại chỗ của bạn không phải là một phần của di chuyển dữ liệu hộp thư.</span><span class="sxs-lookup"><span data-stu-id="b5182-141">Distribution lists (*MailEnabledGroup* objects) and external contacts (*MailEnabledContact* objects) that exist in your on-premises Active Directory aren’t a part of mailbox data migration.</span></span> <span data-ttu-id="b5182-142">Tuy nhiên, bạn có thể đồng bộ hóa chúng bằng cách kết nối Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="b5182-142">However, you can synchronize them using Azure Active Directory (Azure AD) Connect.</span></span> 

## <a name="source-environments"></a><span data-ttu-id="b5182-143">Môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="b5182-143">Source environments</span></span>

<span data-ttu-id="b5182-144">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="b5182-144">Our data migration service migrates data from these source environments:</span></span>

  - <span data-ttu-id="b5182-145">Một hoặc nhiều rừng Active Directory với một hoặc nhiều tổ chức Exchange (mỗi hệ thống thư Exchange phải là Exchange 2010 trở lên).</span><span class="sxs-lookup"><span data-stu-id="b5182-145">A single or multiple Active Directory forests with single or multiple Exchange organizations (each Exchange mail system must be Exchange 2010 or greater).</span></span>
  - <span data-ttu-id="b5182-146">Một môi trường email có khả năng IMAP đơn.</span><span class="sxs-lookup"><span data-stu-id="b5182-146">A single IMAP-capable email environment.</span></span>
  - <span data-ttu-id="b5182-147">Môi trường G Suite (Gmail, danh bạ và lịch chỉ).</span><span class="sxs-lookup"><span data-stu-id="b5182-147">G Suite environment (Gmail, Contacts, and Calendar only).</span></span>

<span data-ttu-id="b5182-148">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="b5182-148">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b5182-149"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-149"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b5182-150"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-150"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b5182-151"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-151"><strong>What migrates</strong></span></span></th>
<th><span data-ttu-id="b5182-152"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-152"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b5182-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-153"><strong>Exchange 2010, Exchange 2013, Exchange 2016, Exchange 2019</strong></span></span><br />
<br /><span data-ttu-id="b5182-154">
<strong>Lưu ý:</strong> Đối với phụ thuộc Exchange tại cơ sở, hãy xem điều <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">kiện tiên quyết về triển khai hỗn</span></a>hợp.</span><span class="sxs-lookup"><span data-stu-id="b5182-154">
<strong>Note:</strong> For on-premises Exchange dependencies, see <a href="https://go.microsoft.com/fwlink/?LinkId=787528"><span class="underline">Hybrid deployment prerequisites</span></a>.</span></span></td>
<td><span data-ttu-id="b5182-155">Di chuyển với triển khai kết hợp</span><span class="sxs-lookup"><span data-stu-id="b5182-155">Migration with hybrid deployment</span></span></td>
<td><ul>
<li><span data-ttu-id="b5182-156">Điện</span><span class="sxs-lookup"><span data-stu-id="b5182-156">Emails</span></span></li>
<li><span data-ttu-id="b5182-157">Quy tắc hộp thư</span><span class="sxs-lookup"><span data-stu-id="b5182-157">Mailbox rules</span></span></li>
<li><span data-ttu-id="b5182-158">Đại diện</span><span class="sxs-lookup"><span data-stu-id="b5182-158">Delegates</span></span></li>
<li><span data-ttu-id="b5182-159">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="b5182-159">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b5182-160">Ba</span><span class="sxs-lookup"><span data-stu-id="b5182-160">Calendar</span></span> </li>
<li> <span data-ttu-id="b5182-161">Môùi</span><span class="sxs-lookup"><span data-stu-id="b5182-161">Tasks</span></span> </li>
<li> <span data-ttu-id="b5182-162">Các email được quản lý bằng quyền</span><span class="sxs-lookup"><span data-stu-id="b5182-162">Rights-managed emails</span></span> </li>
<li> <span data-ttu-id="b5182-163">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="b5182-163">Encrypted emails</span></span> </li>
<li> <span data-ttu-id="b5182-164">Ký</span><span class="sxs-lookup"><span data-stu-id="b5182-164">Signatures</span></span> </li>
<li> <span data-ttu-id="b5182-165">Lưu trữ cá nhân được di chuyển với hộp thư của người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-165">Personal archive migrated with the user's mailbox</span></span> </li>
<li> <span data-ttu-id="b5182-166">Các mục có thể phục hồi</span><span class="sxs-lookup"><span data-stu-id="b5182-166">Recoverable items</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-167">Thư mục công cộng</span><span class="sxs-lookup"><span data-stu-id="b5182-167">Public folders</span></span> </li>
<li> <span data-ttu-id="b5182-168">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="b5182-168">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b5182-169">Ghi nhật ký lưu trữ hoặc giải pháp lưu trữ của bên thứ ba</span><span class="sxs-lookup"><span data-stu-id="b5182-169">Journaling archive or any third-party archive solution</span></span> </li>
<li> <span data-ttu-id="b5182-170">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-170">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-171">Lưu trữ dữ liệu từ các tệp bảng lưu trữ cá nhân (PST)</span><span class="sxs-lookup"><span data-stu-id="b5182-171">Archive data from Personal Storage Table (PST) files</span></span> </li>
<li> <span data-ttu-id="b5182-172">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-172">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b5182-173">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-173">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b5182-174"><strong>Môi trường G Suite (Gmail, danh bạ và lịch)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-174"><strong>G Suite environment (Gmail, Contacts, and Calendar only)</strong></span></span><br />
<br /><span data-ttu-id="b5182-175">
<strong>Lưu ý:</strong> Môi trường G Suite của bạn phải đáp ứng các điều kiện tiên quyết được mô tả trong <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">thực hiện di chuyển g Suite</a>.</span><span class="sxs-lookup"><span data-stu-id="b5182-175">
<strong>Note:</strong> Your G Suite environment must meet the prerequisites described in <a href="https://docs.microsoft.com/Exchange/mailbox-migration/perform-g-suite-migration">Perform a G Suite migration</a>.</span></span></td>
<td><span data-ttu-id="b5182-176">Chuyển giao hoặc theo giai đoạn</span><span class="sxs-lookup"><span data-stu-id="b5182-176">Cutover or staged</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-177">Điện</span><span class="sxs-lookup"><span data-stu-id="b5182-177">Emails</span></span> </li>
<li> <span data-ttu-id="b5182-178">Danh bạ hộp thư (tối đa 3 địa chỉ email cho mỗi liên hệ được di chuyển)</span><span class="sxs-lookup"><span data-stu-id="b5182-178">Mailbox contacts (a maximum of 3 email addresses per contact are migrated)</span></span> </li>
<li> <span data-ttu-id="b5182-179">Ba</span><span class="sxs-lookup"><span data-stu-id="b5182-179">Calendar</span></span> </li>
<li> <span data-ttu-id="b5182-180">Mác</span><span class="sxs-lookup"><span data-stu-id="b5182-180">Labels</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-181">Tắc</span><span class="sxs-lookup"><span data-stu-id="b5182-181">Rules</span></span> </li>
<li> <span data-ttu-id="b5182-182">Đại diện</span><span class="sxs-lookup"><span data-stu-id="b5182-182">Delegates</span></span> </li>
<li> <span data-ttu-id="b5182-183">Ký</span><span class="sxs-lookup"><span data-stu-id="b5182-183">Signatures</span></span> </li>
<li> <span data-ttu-id="b5182-184">Môùi</span><span class="sxs-lookup"><span data-stu-id="b5182-184">Tasks</span></span> </li>
<li> <span data-ttu-id="b5182-185">Bất kỳ email hoặc tệp đính kèm vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="b5182-185">Any email or attachment that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b5182-186">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-186">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-187">Lưu trữ dữ liệu từ các tệp PST hoặc bất kỳ giải pháp lưu trữ của bên thứ ba nào (ví dụ, Google Vault)</span><span class="sxs-lookup"><span data-stu-id="b5182-187">Archive data from PST files or any third-party archive solution (for example, Google Vault)</span></span> </li>
<li> <span data-ttu-id="b5182-188">Các email được quản lý hoặc mã hóa quyền</span><span class="sxs-lookup"><span data-stu-id="b5182-188">Rights managed or encrypted emails</span></span> </li>
<li> <span data-ttu-id="b5182-189">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-189">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b5182-190">Google Hangouts \* \*</span><span class="sxs-lookup"><span data-stu-id="b5182-190">Google Hangouts\*\*</span></span> </li>
<li> <span data-ttu-id="b5182-191">Google Groups</span><span class="sxs-lookup"><span data-stu-id="b5182-191">Google Groups</span></span> </li>
<li> <span data-ttu-id="b5182-192">Hộp thư tài nguyên</span><span class="sxs-lookup"><span data-stu-id="b5182-192">Resource mailboxes</span></span> </li>
<li> <span data-ttu-id="b5182-193">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-193">Inactive mailboxes</span></span> </li>
<li> <span data-ttu-id="b5182-194">Thiết đặt nghỉ phép và thiết đặt trả lời tự động</span><span class="sxs-lookup"><span data-stu-id="b5182-194">Vacation settings and automatic reply settings</span></span> </li>
<li> <span data-ttu-id="b5182-195">Lịch chia sẻ, tệp đính kèm đám mây, liên kết của Google hangout và màu sự kiện</span><span class="sxs-lookup"><span data-stu-id="b5182-195">Shared calendars, cloud attachments, Google Hangout links, and event colors</span></span> </li>
</ul>
<span data-ttu-id="b5182-196">\* \* Hangout hội thoại được lưu dưới dạng nhãn được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-196">\*\*Hangout conversations saved as label are migrated.</span></span> </td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b5182-197"><strong>Nguồn IMAP4 (chẳng hạn như Domino, GroupWise hoặc Zimbra)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-197"><strong>IMAP4 source (like Domino, GroupWise, or Zimbra)</strong></span></span></td>
<td><span data-ttu-id="b5182-198">Di chuyển bằng công cụ IMAP4 bản địa</span><span class="sxs-lookup"><span data-stu-id="b5182-198">Migration using native IMAP4 tools</span></span></td>
<td><li><span data-ttu-id="b5182-199">Điện</span><span class="sxs-lookup"><span data-stu-id="b5182-199">Emails</span></span> </li></td>
<td><ul>
<li> <span data-ttu-id="b5182-200">Tắc</span><span class="sxs-lookup"><span data-stu-id="b5182-200">Rules</span></span> </li>
<li> <span data-ttu-id="b5182-201">Đại diện</span><span class="sxs-lookup"><span data-stu-id="b5182-201">Delegates</span></span> </li>
<li> <span data-ttu-id="b5182-202">Danh sách phân phối</span><span class="sxs-lookup"><span data-stu-id="b5182-202">Distribution lists</span></span> </li>
<li> <span data-ttu-id="b5182-203">Liên hệ bên ngoài</span><span class="sxs-lookup"><span data-stu-id="b5182-203">External contacts</span></span> </li>
<li> <span data-ttu-id="b5182-204">Người dùng hỗ trợ thư</span><span class="sxs-lookup"><span data-stu-id="b5182-204">Mail-enabled users</span></span> </li>
<li> <span data-ttu-id="b5182-205">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-205">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-206">Liên hệ hộp thư</span><span class="sxs-lookup"><span data-stu-id="b5182-206">Mailbox contacts</span></span> </li>
<li> <span data-ttu-id="b5182-207">Ba</span><span class="sxs-lookup"><span data-stu-id="b5182-207">Calendar</span></span> </li>
<li> <span data-ttu-id="b5182-208">Ký</span><span class="sxs-lookup"><span data-stu-id="b5182-208">Signatures</span></span> </li>
<li> <span data-ttu-id="b5182-209">Môùi</span><span class="sxs-lookup"><span data-stu-id="b5182-209">Tasks</span></span> </li>
<li> <span data-ttu-id="b5182-210">Bất kỳ email nào vượt quá giới hạn kích cỡ thư</span><span class="sxs-lookup"><span data-stu-id="b5182-210">Any email that exceeds the message size limit</span></span> </li>
<li> <span data-ttu-id="b5182-211">Lưu trữ dữ liệu</span><span class="sxs-lookup"><span data-stu-id="b5182-211">Archive data</span></span> </li>
<li> <span data-ttu-id="b5182-212">Email đã mã hóa</span><span class="sxs-lookup"><span data-stu-id="b5182-212">Encrypted email</span></span> </li>
<li> <span data-ttu-id="b5182-213">Các mục bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-213">Corrupted items</span></span> </li>
<li> <span data-ttu-id="b5182-214">Hộp thư không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-214">Inactive mailboxes</span></span> </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b5182-215">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="b5182-215">FastTrack responsibilities</span></span>

<span data-ttu-id="b5182-216">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-216">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-217">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-217">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b5182-218">Các chuyên gia FastTrack của chúng tôi cũng thực hiện các hoạt động sau đây, đặc biệt là di chuyển của Exchange:</span><span class="sxs-lookup"><span data-stu-id="b5182-218">Our FastTrack Specialists also perform the following activities, specific to Exchange migrations:</span></span>

  -  <span data-ttu-id="b5182-219">Cung cấp hướng dẫn để giúp bạn bật cùng tồn tại định tuyến thư SMTP giữa môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="b5182-219">Provide guidance to help you enable SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b5182-220">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="b5182-220">Your responsibilities</span></span>

<span data-ttu-id="b5182-221">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-221">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-222">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-222">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b5182-223">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là di chuyển Exchange:</span><span class="sxs-lookup"><span data-stu-id="b5182-223">You also perform the following activities, specific to Exchange migrations:</span></span>

  - <span data-ttu-id="b5182-224">Đã hoàn tất màn danh theo dõi nền tảng cho Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="b5182-224">Complete FastTrack core onboarding for Exchange Online.</span></span> <span data-ttu-id="b5182-225">Nếu bạn đã thực hiện triển khai chính mình, bạn phải thông qua các kiểm tra và điều kiện tiên quyết cần thiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-225">If you performed onboarding yourself, you must pass the required checks and prerequisites.</span></span> <span data-ttu-id="b5182-226">Tham khảo các [sản phẩm và chức năng](products-and-capabilities.md) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-226">Refer to [Products and Capabilities](products-and-capabilities.md) for details.</span></span>
  -  <span data-ttu-id="b5182-227">Cài đặt mức độ phù hợp của phần mềm máy khách như cho mỗi hướng dẫn về Office 365.</span><span class="sxs-lookup"><span data-stu-id="b5182-227">Install the appropriate level of client software as per Office 365 guidelines.</span></span> <span data-ttu-id="b5182-228">Tham khảo cách [làm việc hiện đại](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-228">Refer to [Modern Workplace](https://transform.microsoft.com/download?assetname=assets%2FMicrosoft%20365%20%20Security%20Group%20Marketing%20Field%20Advisory%20%20Renaming%20Office%20365%20SMB%20Products%20and%20Office%20365%20ProPlus.msg) for details.</span></span>
  -  <span data-ttu-id="b5182-229">Đáp ứng các yêu cầu cụ thể nếu bạn dự định di chuyển từ môi trường Exchange tại cơ sở.</span><span class="sxs-lookup"><span data-stu-id="b5182-229">Satisfy specific requirements if you intend to migrate from an on-premises Exchange environment.</span></span> <span data-ttu-id="b5182-230">Tham khảo các điều [kiện tiên quyết hỗn](https://go.microsoft.com/fwlink/?LinkId=787528) hợp để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-230">Refer to [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/?LinkId=787528) for details.</span></span>
  -  <span data-ttu-id="b5182-231">Đảm bảo mỗi môi trường nguồn nằm trên mức Cập Nhật gói dịch vụ (SP) mới nhất (SP) và Rollup (RU)/Cumulative Update (CU), nếu có.</span><span class="sxs-lookup"><span data-stu-id="b5182-231">Ensure each source environment is on the latest service pack (SP) and rollup (RU)/cumulative update (CU) level, if applicable.</span></span>
  -  <span data-ttu-id="b5182-232">Cấu hình và xác thực việc đồng bộ định tuyến thư SMTP giữa các môi trường nguồn và Exchange Online của bạn, nếu có.</span><span class="sxs-lookup"><span data-stu-id="b5182-232">Configure and validate SMTP mail routing coexistence between your source environments and Exchange Online, if applicable.</span></span>
  -  <span data-ttu-id="b5182-233">Đảm bảo kích cỡ hộp thư nguồn của bạn không vượt quá hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="b5182-233">Ensure your source mailbox size doesn’t exceed the target mailbox quota.</span></span> <span data-ttu-id="b5182-234">Tùy thuộc vào nền tảng nguồn, bạn có thể cần giới hạn dữ liệu nguồn của bạn thành 85 phần trăm hạn ngạch hộp thư đích.</span><span class="sxs-lookup"><span data-stu-id="b5182-234">Depending on the source platform, you may need to limit your source data to 85 percent of the target mailbox quota.</span></span>
  -  <span data-ttu-id="b5182-235">Di chuyển dữ liệu phía máy khách nếu muốn.</span><span class="sxs-lookup"><span data-stu-id="b5182-235">Migrate client-side data if desired.</span></span> <span data-ttu-id="b5182-236">Điều này bao gồm nhưng không giới hạn, sổ địa chỉ cục bộ, dữ liệu trong các tệp PST cục bộ, quy tắc Outlook và các thiết đặt Outlook cục bộ.</span><span class="sxs-lookup"><span data-stu-id="b5182-236">This includes, but isn’t limited to, local address books, data in local PST files, Outlook rules, and local Outlook settings.</span></span>
  -  <span data-ttu-id="b5182-237">Hỗ trợ người dùng cuối của bạn khắc phục sự cố di chuyển phía máy khách.</span><span class="sxs-lookup"><span data-stu-id="b5182-237">Assist your end-users with remediation of client-side migration issues.</span></span>

## <a name="migration-to-sharepoint-online"></a><span data-ttu-id="b5182-238">Di chuyển sang SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="b5182-238">Migration to SharePoint Online</span></span>

<span data-ttu-id="b5182-239">Khi bạn chọn sử dụng FastTrack để di chuyển tệp của mình sang SharePoint Online, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-239">When you choose to use FastTrack to migrate your files to SharePoint Online, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b5182-240">Chúng tôi cung cấp hướng dẫn để giúp bạn lập kế hoạch cho việc di chuyển của mình, đặt cấu hình môi trường nguồn và SharePoint Online và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-240">We provide guidance to help you plan your migration, configure your source environments and SharePoint Online, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b5182-241">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-241">You create and schedule your migration events.</span></span> <span data-ttu-id="b5182-242">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="b5182-242">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b5182-243">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lên lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển sang SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b5182-243">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to SharePoint Online.</span></span>

## <a name="considerations"></a><span data-ttu-id="b5182-244">Nhắc</span><span class="sxs-lookup"><span data-stu-id="b5182-244">Considerations</span></span>

  - <span data-ttu-id="b5182-245">Tất cả các di chuyển đều phải tuân theo hạn ngạch của SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="b5182-245">All migrations are subject to SharePoint Online quotas.</span></span> <span data-ttu-id="b5182-246">Tham chiếu đến [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-246">Refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="b5182-247">Chúng tôi khuyên bạn nên giới hạn số lượng di chuyển tổng thể đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có quyền (bao gồm lưu trữ bổ sung mà bạn đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="b5182-247">We recommend that you limit the overall amount of migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b5182-248">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="b5182-248">Source environment details</span></span>

<span data-ttu-id="b5182-249">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="b5182-249">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b5182-250">Chia sẻ tệp (khối tin nhắn máy chủ (SMB) chia sẻ tệp trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="b5182-250">File shares (Server Message Block (SMB) file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b5182-251">Một môi trường G Suite đơn (chỉ dành cho Google).</span><span class="sxs-lookup"><span data-stu-id="b5182-251">A single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b5182-252">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="b5182-252">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b5182-253">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="b5182-253">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b5182-254">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="b5182-254">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
<th><span data-ttu-id="b5182-255"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-255"><strong>Source environment</strong></span></span></th>
<th><span data-ttu-id="b5182-256"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-256"><strong>Type of migration</strong></span></span></th>
<th><span data-ttu-id="b5182-257"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-257"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b5182-258"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-258"><strong>What doesn’t migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b5182-259"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-259"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b5182-260">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-260">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-261">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-261">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-262">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-262">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-263">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="b5182-263">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b5182-264">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="b5182-264">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b5182-265">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-265">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-266">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-266">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-267">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-267">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-268">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-268">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-269">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-269">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-270">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-270">Last modified by</span></span> </li>
</ul></li>
</ul>
<span data-ttu-id="b5182-271">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="b5182-271">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b5182-272">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="b5182-272">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b5182-273">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-273">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b5182-274">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="b5182-274">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-275">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="b5182-275">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b5182-276">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-276">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-277">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="b5182-277">Previous versions</span></span> </li>
<li> <span data-ttu-id="b5182-278">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="b5182-278">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b5182-279">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="b5182-279">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b5182-280">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="b5182-280">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b5182-281">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="b5182-281">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b5182-282">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="b5182-282">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b5182-283">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-283">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-284">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="b5182-284">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b5182-285">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="b5182-285">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b5182-286">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-286">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b5182-287"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-287"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b5182-288">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-288">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-289">Google Docs, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương), bao gồm những người trên 10 MB</span><span class="sxs-lookup"><span data-stu-id="b5182-289">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format), including those over 10 MB</span></span> </li>
<li> <span data-ttu-id="b5182-290">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-290">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-291">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-291">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-292">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-292">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-293">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-293">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-294">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-294">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-295">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-295">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-296">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-296">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-297">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-297">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-298">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-298">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-299">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="b5182-299">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b5182-300">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-300">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-301">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-301">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-302">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-302">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b5182-303">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-303">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-304">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-304">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-305">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-305">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-306">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-306">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-307">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-307">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-308">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-308">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-309">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-309">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-310">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-310">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-311">Google ảnh, biểu mẫu, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="b5182-311">Google Photos, Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b5182-312">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="b5182-312">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b5182-313">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="b5182-313">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b5182-314">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-314">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b5182-315">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-315">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-316">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-316">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-317">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="b5182-317">Shared Drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b5182-318">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-318">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-319">Các tệp được đánh dấu là hạn chế hoặc không được copyable</span><span class="sxs-lookup"><span data-stu-id="b5182-319">Files marked as restricted or not copyable</span></span> </li>
<li> <span data-ttu-id="b5182-320">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-320">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b5182-321"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-321"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b5182-322">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-322">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-323">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-323">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-324">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-324">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-325">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-325">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-326">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-326">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-327">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-327">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-328">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-328">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-329">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-329">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-330">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-330">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-331">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-331">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-332">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-332">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-333">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-333">Shared content owned by the Box account being migrated</span></span> </li>
<li> <span data-ttu-id="b5182-334">Ghi chú hộp (được chuyển đổi thành định dạng tài liệu Word)</span><span class="sxs-lookup"><span data-stu-id="b5182-334">Box Notes (converted to Word document format)</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-335">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-335">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-336">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-336">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b5182-337">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-337">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-338">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-338">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-339">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-339">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-340">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-340">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-341">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-341">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-342">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-342">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-343">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-343">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-344">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-344">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-345">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="b5182-345">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b5182-346">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-346">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b5182-347">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-347">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-348">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-348">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-349">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-349">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b5182-350"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-350"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b5182-351">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-351">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-352">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-352">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-353">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-353">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-354">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-354">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-355">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-355">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-356">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-356">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-357">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-357">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-358">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-358">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-359">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-359">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-360">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-360">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-361">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-361">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-362">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-362">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b5182-363">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-363">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-364">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-364">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-365">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-365">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b5182-366">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-366">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-367">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-367">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-368">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-368">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-369">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-369">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-370">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-370">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-371">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-371">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-372">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-372">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-373">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="b5182-373">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b5182-374">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="b5182-374">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b5182-375">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="b5182-375">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b5182-376">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b5182-376">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b5182-377">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-377">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b5182-378">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-378">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-379">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển)</span><span class="sxs-lookup"><span data-stu-id="b5182-379">Instruct end users to reshare content with external users after migration)</span></span> </li>
<li> <span data-ttu-id="b5182-380">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-380">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b5182-381">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="b5182-381">FastTrack responsibilities</span></span>

<span data-ttu-id="b5182-382">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-382">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-383">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="b5182-383">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b5182-384">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="b5182-384">Your responsibilities</span></span>

<span data-ttu-id="b5182-385">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-385">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-386">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết</span><span class="sxs-lookup"><span data-stu-id="b5182-386">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details</span></span>

<span data-ttu-id="b5182-387">Bạn cũng thực hiện các hoạt động sau đây, cụ thể là di chuyển SharePoint Online:</span><span class="sxs-lookup"><span data-stu-id="b5182-387">You also perform the following activities, specific to SharePoint Online migrations:</span></span>

  - <span data-ttu-id="b5182-388">Cung cấp tất cả các site nhóm SharePoint được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-388">Provision all SharePoint team sites to be targeted by your migration events.</span></span>

## <a name="migration-to-onedrive-for-business"></a><span data-ttu-id="b5182-389">Di chuyển sang OneDrive for Business</span><span class="sxs-lookup"><span data-stu-id="b5182-389">Migration to OneDrive for Business</span></span>

<span data-ttu-id="b5182-390">Khi bạn chọn sử dụng FastTrack để di chuyển các tệp của mình vào OneDrive for Business, chúng tôi cung cấp hướng dẫn di chuyển và dịch vụ di chuyển dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="b5182-390">When you choose to use FastTrack to migrate your files to OneDrive for Business, we provide migration guidance and data migration services.</span></span> <span data-ttu-id="b5182-391">Chúng tôi cung cấp hướng dẫn để giúp bạn lên kế hoạch di chuyển của mình, đặt cấu hình môi trường nguồn và OneDrive for Business và tận dụng các dịch vụ di chuyển dữ liệu của chúng tôi để di chuyển tệp của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-391">We provide guidance to help you plan your migration, configure your source environments and OneDrive for Business, and leverage our data migration services to migrate your files.</span></span> <span data-ttu-id="b5182-392">Bạn tạo và lên lịch các sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-392">You create and schedule your migration events.</span></span> <span data-ttu-id="b5182-393">Chúng tôi khởi chạy các sự kiện di chuyển phù hợp với lịch biểu của bạn, theo dõi tiến độ của họ và cung cấp báo cáo trạng thái.</span><span class="sxs-lookup"><span data-stu-id="b5182-393">We launch migration events in accordance with your schedule, monitor their progress, and provide status reports.</span></span> <span data-ttu-id="b5182-394">Khi hoàn thành các sự kiện di chuyển, bạn có thể mong đợi các tệp từ các nguồn được lập lịch và đủ điều kiện phù hợp với các môi trường nguồn của bạn đã được di chuyển đến OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b5182-394">When your migration events complete, you can expect files from appropriately scheduled and eligible sources of your source environments to have been migrated to OneDrive for Business.</span></span>

## <a name="considerations"></a><span data-ttu-id="b5182-395">Nhắc</span><span class="sxs-lookup"><span data-stu-id="b5182-395">Considerations</span></span>

  - <span data-ttu-id="b5182-396">Tất cả các di chuyển đều phải tuân theo hạn ngạch của OneDrive for Business.</span><span class="sxs-lookup"><span data-stu-id="b5182-396">All migrations are subject to OneDrive for Business quotas.</span></span> <span data-ttu-id="b5182-397">Vui lòng tham khảo [<span class="underline">SharePoint Online và OneDrive for Business: ranh giới và giới hạn phần mềm</span>](https://go.microsoft.com/fwlink/?LinkId=698855) để biết thêm thông tin chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-397">Please refer to [<span class="underline">SharePoint Online and OneDrive for Business: software boundaries and limits</span>](https://go.microsoft.com/fwlink/?LinkId=698855) for details.</span></span>
  - <span data-ttu-id="b5182-398">Chúng tôi khuyên bạn nên giới hạn số lượng dữ liệu mà bạn di chuyển đến 75 phần trăm của hạn ngạch lưu trữ SharePoint Online tổng thể mà bạn có được hưởng (bao gồm lưu trữ bổ sung mà bạn có thể đã mua riêng).</span><span class="sxs-lookup"><span data-stu-id="b5182-398">We recommend that you limit the overall amount of data you migrate to 75 percent of the overall SharePoint Online storage quota to which you are entitled (including the additional storage you may have purchased separately).</span></span>
  - <span data-ttu-id="b5182-399">FastTrack chỉ di chuyển đến ổ đĩa OneDrive for Business hiện hoạt.</span><span class="sxs-lookup"><span data-stu-id="b5182-399">FastTrack migrates only to active OneDrive for Business drives.</span></span>

## <a name="source-environment-details"></a><span data-ttu-id="b5182-400">Chi tiết môi trường nguồn</span><span class="sxs-lookup"><span data-stu-id="b5182-400">Source environment details</span></span>

<span data-ttu-id="b5182-401">Dịch vụ di chuyển dữ liệu của chúng tôi di chuyển dữ liệu từ những môi trường nguồn này:</span><span class="sxs-lookup"><span data-stu-id="b5182-401">Our data migration services migrate data from these source environments:</span></span>

  - <span data-ttu-id="b5182-402">Chia sẻ tệp (SMB tệp chia sẻ trên các thiết bị hỗ trợ SMB 2,0 trở đi).</span><span class="sxs-lookup"><span data-stu-id="b5182-402">File shares (SMB file shares on devices supporting SMB 2.0 onward).</span></span>
  - <span data-ttu-id="b5182-403">Môi trường Single G Suite (chỉ dành cho Google Drive).</span><span class="sxs-lookup"><span data-stu-id="b5182-403">Single G Suite environment (Google Drive only).</span></span>
  - <span data-ttu-id="b5182-404">Box (Starter, Business, doanh nghiệp).</span><span class="sxs-lookup"><span data-stu-id="b5182-404">Box (Starter, Business, Enterprise).</span></span>
  - <span data-ttu-id="b5182-405">Dropbox cho các nhóm (tiêu chuẩn và nâng cao).</span><span class="sxs-lookup"><span data-stu-id="b5182-405">Dropbox for Teams (Standard and Advanced).</span></span>

<span data-ttu-id="b5182-406">Bảng sau đây trình bày các chi tiết di chuyển cụ thể cho từng môi trường nguồn:</span><span class="sxs-lookup"><span data-stu-id="b5182-406">The following table presents migration details specific to each source environment:</span></span>

<table>
<thead>
<tr class="header">
 <th><span data-ttu-id="b5182-407"><strong>Môi trường nguồn</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-407"><strong>Source environment</strong></span></span></th>
 <th><span data-ttu-id="b5182-408"><strong>Kiểu di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-408"><strong>Type of migration</strong></span></span></th>
 <th><span data-ttu-id="b5182-409"><strong>Những thao động nào</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-409"><strong>What migrates</strong></span></span></th>
 <th><span data-ttu-id="b5182-410"><strong>Những điều không di chuyển</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-410"><strong>What doesn't migrate</strong></span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><span data-ttu-id="b5182-411"><strong>Bất kỳ thiết bị chia sẻ tệp nào hỗ trợ SMB 2,0 trở đi</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-411"><strong>Any file share device supporting SMB 2.0 onward</strong></span></span></td>
<td><span data-ttu-id="b5182-412">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-412">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-413">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-413">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-414">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-414">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-415">Tệp cấp độ người dùng và quyền thư mục \*</span><span class="sxs-lookup"><span data-stu-id="b5182-415">User-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b5182-416">Các quyền thư mục và tệp cấp nhóm \*</span><span class="sxs-lookup"><span data-stu-id="b5182-416">Group-level file and folder permissions\*</span></span> </li>
<li> <span data-ttu-id="b5182-417">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-417">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-418">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-418">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-419">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-419">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-420">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-420">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-421">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-421">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-422">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-422">Last modified by</span></span> </li>
</ul></li>
</ul>
<br>
<span data-ttu-id="b5182-423">\* Yêu cầu cấu hình đồng bộ hóa thư mục.</span><span class="sxs-lookup"><span data-stu-id="b5182-423">\*Directory synchronization configuration required.</span></span> <span data-ttu-id="b5182-424">Chỉ các quyền NTFS được di chuyển vào File Explorer của Windows.</span><span class="sxs-lookup"><span data-stu-id="b5182-424">Only NTFS permissions exposed to the Windows File Explorer are migrated.</span></span> <span data-ttu-id="b5182-425">Quyền được quản lý trực tiếp trên các thiết bị chia sẻ tệp không được di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-425">Permissions managed directly on file share devices are not migrated.</span></span> <span data-ttu-id="b5182-426">Nếu dữ liệu được lưu trữ trên thiết bị SMB 2,0, các quyền tương đương với NTFS sẽ được di chuyển cho giao thức SMB.</span><span class="sxs-lookup"><span data-stu-id="b5182-426">If data is stored on an SMB 2.0 device, the NTFS-equivalent permissions exposed by the SMB protocol are migrated.</span></span> </td>
<td><ul>
<li> <span data-ttu-id="b5182-427">Lịch sử quyền sở hữu và các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="b5182-427">Ownership history and previous versions</span></span> </li>
<li> <span data-ttu-id="b5182-428">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-428">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-429">Các phiên bản trước</span><span class="sxs-lookup"><span data-stu-id="b5182-429">Previous versions</span></span> </li>
<li> <span data-ttu-id="b5182-430">Các thuộc tính tệp và thư mục Windows (như chỉ đọc và ẩn)</span><span class="sxs-lookup"><span data-stu-id="b5182-430">Windows file and folder attributes (like read-only and hidden)</span></span> </li>
<li> <span data-ttu-id="b5182-431">Hệ thống tệp công nghệ mới (NTFS) và NTFS nâng cao và các thiết đặt đặc biệt:</span><span class="sxs-lookup"><span data-stu-id="b5182-431">Non-Windows New Technology File System (NTFS) and NTFS advanced permissions and special settings:</span></span> </li>
<li> <span data-ttu-id="b5182-432">Rõ ràng từ chối quyền (bị loại bỏ sau khi di chuyển, chủ đề nội dung đối với quyền hoặc quyền song song trên thư mục mẹ)</span><span class="sxs-lookup"><span data-stu-id="b5182-432">Explicit deny permissions (removed after migration, content subject to parallel permissions or permissions on parent folder)</span></span> </li>
<li> <span data-ttu-id="b5182-433">Cấu hình kiểm tra NTFS</span><span class="sxs-lookup"><span data-stu-id="b5182-433">NTFS auditing configuration</span></span> </li>
<li> <span data-ttu-id="b5182-434">Siêu dữ liệu tệp bổ sung được cung cấp bởi cơ sở hạ tầng phân loại tệp (FCI)</span><span class="sxs-lookup"><span data-stu-id="b5182-434">Additional file metadata provided by File Classification Infrastructure (FCI)</span></span> </li>
<li> <span data-ttu-id="b5182-435">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-435">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-436">Chia sẻ ẩn</span><span class="sxs-lookup"><span data-stu-id="b5182-436">Hidden shares</span></span> </li>
<li> <span data-ttu-id="b5182-437">Chia sẻ (như quyền cấp ở mức chia sẻ)</span><span class="sxs-lookup"><span data-stu-id="b5182-437">Sharing (like permissions granted on the share level)</span></span> </li>
<li> <span data-ttu-id="b5182-438">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-438">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b5182-439"><strong>Môi trường Single G Suite (chỉ dành cho Google Drive)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-439"><strong>Single G Suite environment (Google Drive only)</strong></span></span></td>
<td><span data-ttu-id="b5182-440">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-440">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-441">Google Documents, trang tính và trang chiếu (tệp được chuyển đổi sang định dạng Office tương đương, bao gồm những người trên 10 MB)</span><span class="sxs-lookup"><span data-stu-id="b5182-441">Google Docs, Sheets, and Slides (files are converted to the equivalent Office format including those over 10 MB)</span></span> </li>
<li> <span data-ttu-id="b5182-442">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-442">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-443">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-443">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-444">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-444">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-445">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-445">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-446">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-446">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-447">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-447">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-448">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-448">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-449">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-449">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-450">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-450">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-451">Các ổ đĩa chia sẻ (các thư mục và tệp)</span><span class="sxs-lookup"><span data-stu-id="b5182-451">Shared drives (folders and files)</span></span> </li>
<li> <span data-ttu-id="b5182-452">Nội dung được chia sẻ thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-452">Shared content owned by the Google Drive account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-453">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-453">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-454">Mô tả tệp và thư mục, màu thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-454">File and folder descriptions, folder colors</span></span> </li>
<li> <span data-ttu-id="b5182-455">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-455">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-456">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-456">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-457">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-457">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-458">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-458">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-459">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-459">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-460">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-460">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-461">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-461">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-462">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-462">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-463">Biểu mẫu hình ảnh của Google, bản đồ và các ứng dụng được kết nối khác</span><span class="sxs-lookup"><span data-stu-id="b5182-463">Google Photos Forms, Maps, and other connected apps</span></span> </li>
<li> <span data-ttu-id="b5182-464">Bản vẽ Google</span><span class="sxs-lookup"><span data-stu-id="b5182-464">Google Drawings</span></span> </li>
<li> <span data-ttu-id="b5182-465">Nội dung được chia sẻ bên ngoài tổ chức của bạn</span><span class="sxs-lookup"><span data-stu-id="b5182-465">Shared content external to your organization</span></span> </li>
<li> <span data-ttu-id="b5182-466">Nội dung không thuộc sở hữu của tài khoản Google Drive đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-466">Content not owned by the Google Drive account being migrated</span></span> </li>
<li> <span data-ttu-id="b5182-467">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo quản trị Google Drive để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-467">Permissions and basic metadata of external users (<strong>Note</strong>: Use Google Drive Admin reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-468">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-468">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-469">Quyền thành viên ổ đĩa chia sẻ (<strong>ghi chú</strong>: dùng các báo cáo quản trị của Google Drive để xác định thành viên ổ đĩa chia sẻ.</span><span class="sxs-lookup"><span data-stu-id="b5182-469">Shared drive membership permissions (<strong>Note</strong>: Use Google Drive Admin reports to identify shared drive memberships.</span></span> <span data-ttu-id="b5182-470">Hướng dẫn người dùng cuối để cấu hình các thiết đặt thành viên này trên mục tiêu trước khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-470">Instruct end users to configure these membership settings on the target before migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-471">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-471">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="odd">
<td><span data-ttu-id="b5182-472"><strong>Box (Starter, Business, doanh nghiệp)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-472"><strong>Box (Starter, Business, Enterprise)</strong></span></span></td>
<td><span data-ttu-id="b5182-473">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-473">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-474">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-474">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-475">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-475">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-476">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-476">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-477">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-477">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-478">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-478">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-479">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-479">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-480">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-480">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-481">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-481">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-482">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-482">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-483">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-483">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-484">Nội dung được chia sẻ thuộc sở hữu của tài khoản Box đang được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-484">Shared content owned by the Box account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-485">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-485">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-486">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-486">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b5182-487">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-487">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-488">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-488">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-489">Thẻ hộp và siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-489">Box Tags and advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-490">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-490">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-491">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-491">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-492">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-492">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-493">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-493">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-494">Người dùng bị chặn hoặc không hoạt động</span><span class="sxs-lookup"><span data-stu-id="b5182-494">Blocked or inactive users</span></span> </li>
<li> <span data-ttu-id="b5182-495">Các ứng dụng hộp, thẻ đánh dấu, yêu thích và dòng công việc</span><span class="sxs-lookup"><span data-stu-id="b5182-495">Box Apps, Bookmarks, Favorites, and Workflows</span></span> </li>
<li> <span data-ttu-id="b5182-496">Nội dung không thuộc sở hữu của tài khoản hộp được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-496">Content not owned by the migrated Box account</span></span> </li>
<li> <span data-ttu-id="b5182-497">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo hộp để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-497">Permissions and basic metadata of external users (<strong>Note</strong>: Use Box reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-498">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-498">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-499">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-499">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
<tr class="even">
<td><span data-ttu-id="b5182-500"><strong>Dropbox cho các nhóm (tiêu chuẩn và nâng cao)</strong></span><span class="sxs-lookup"><span data-stu-id="b5182-500"><strong>Dropbox for Teams (Standard and Advanced)</strong></span></span></td>
<td><span data-ttu-id="b5182-501">Một hoặc nhiều đèo</span><span class="sxs-lookup"><span data-stu-id="b5182-501">Single or multi-pass</span></span></td>
<td><ul>
<li> <span data-ttu-id="b5182-502">Liên</span><span class="sxs-lookup"><span data-stu-id="b5182-502">Documents</span></span> </li>
<li> <span data-ttu-id="b5182-503">Cấu trúc tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-503">File and folder structure</span></span> </li>
<li> <span data-ttu-id="b5182-504">Quyền thư mục mức người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-504">User-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-505">Quyền thư mục cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-505">Group-level folder permissions</span></span> </li>
<li> <span data-ttu-id="b5182-506">Tệp dưới 15 GB</span><span class="sxs-lookup"><span data-stu-id="b5182-506">Files under 15 GB</span></span> </li>
<li> <span data-ttu-id="b5182-507">Cơ bản về tài liệu và thư mục siêu dữ liệu:</span><span class="sxs-lookup"><span data-stu-id="b5182-507">Basic document and folder metadata:</span></span>
<ul>
<li> <span data-ttu-id="b5182-508">Ngày tạo</span><span class="sxs-lookup"><span data-stu-id="b5182-508">Created date</span></span> </li>
<li> <span data-ttu-id="b5182-509">Ngày sửa đổi</span><span class="sxs-lookup"><span data-stu-id="b5182-509">Modified date</span></span> </li>
<li> <span data-ttu-id="b5182-510">Được tạo bởi</span><span class="sxs-lookup"><span data-stu-id="b5182-510">Created by</span></span> </li>
<li> <span data-ttu-id="b5182-511">Sửa đổi lần cuối bằng</span><span class="sxs-lookup"><span data-stu-id="b5182-511">Last modified by</span></span> </li>
</ul></li>
<li> <span data-ttu-id="b5182-512">Thư mục nhóm chia sẻ và nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-512">Shared team folders and content</span></span> </li>
<li> <span data-ttu-id="b5182-513">Nội dung được chia sẻ thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-513">Shared content owned by the Dropbox account being migrated</span></span> </li>
</ul></td>
<td><ul>
<li> <span data-ttu-id="b5182-514">Lịch sử quyền sở hữu, phiên bản trước và chú thích</span><span class="sxs-lookup"><span data-stu-id="b5182-514">Ownership history, previous versions, and comments</span></span> </li>
<li> <span data-ttu-id="b5182-515">Mô tả tệp và thư mục</span><span class="sxs-lookup"><span data-stu-id="b5182-515">File and folder descriptions</span></span> </li>
<li> <span data-ttu-id="b5182-516">Quyền tệp cấp độ người dùng</span><span class="sxs-lookup"><span data-stu-id="b5182-516">User-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-517">Quyền tệp cấp nhóm</span><span class="sxs-lookup"><span data-stu-id="b5182-517">Group-level file permissions</span></span> </li>
<li> <span data-ttu-id="b5182-518">Siêu dữ liệu nâng cao</span><span class="sxs-lookup"><span data-stu-id="b5182-518">Advanced metadata</span></span> </li>
<li> <span data-ttu-id="b5182-519">Thuộc tính khóa tệp</span><span class="sxs-lookup"><span data-stu-id="b5182-519">File lock attributes</span></span> </li>
<li> <span data-ttu-id="b5182-520">Chuyển đổi URL nhúng trong nội dung</span><span class="sxs-lookup"><span data-stu-id="b5182-520">Conversion of embedded URLs in content</span></span> </li>
<li> <span data-ttu-id="b5182-521">Trashed các mục</span><span class="sxs-lookup"><span data-stu-id="b5182-521">Trashed items</span></span> </li>
<li> <span data-ttu-id="b5182-522">Không thể truy nhập hoặc tài liệu bị lỗi</span><span class="sxs-lookup"><span data-stu-id="b5182-522">Inaccessible or corrupted documents</span></span> </li>
<li> <span data-ttu-id="b5182-523">Không gắn kết thư mục Dropbox</span><span class="sxs-lookup"><span data-stu-id="b5182-523">Unmounted Dropbox folders</span></span> </li>
<li> <span data-ttu-id="b5182-524">Người dùng đã xóa hoặc bị ngắt kết nối</span><span class="sxs-lookup"><span data-stu-id="b5182-524">Deleted or disconnected users</span></span> </li>
<li> <span data-ttu-id="b5182-525">Dropbox giấy, giới thiệu và khoảng trắng</span><span class="sxs-lookup"><span data-stu-id="b5182-525">Dropbox Paper, Showcases, and Spaces</span></span> </li>
<li> <span data-ttu-id="b5182-526">Ứng dụng và mục yêu thích Dropbox (Pins/Stars)</span><span class="sxs-lookup"><span data-stu-id="b5182-526">Dropbox Apps and Favorites (Pins/Stars)</span></span> </li>
<li> <span data-ttu-id="b5182-527">Nội dung không thuộc sở hữu của tài khoản Dropbox được di chuyển</span><span class="sxs-lookup"><span data-stu-id="b5182-527">Content not owned by the migrated Dropbox account</span></span> </li>
<li> <span data-ttu-id="b5182-528">Quyền và siêu dữ liệu cơ bản của người dùng bên ngoài (<strong>lưu ý</strong>: sử dụng báo cáo Dropbox để xác định nội dung được chia sẻ với người dùng bên ngoài.</span><span class="sxs-lookup"><span data-stu-id="b5182-528">Permissions and basic metadata of external users (<strong>Note</strong>: Use Dropbox reports to identify content shared with external users.</span></span> <span data-ttu-id="b5182-529">Hướng dẫn người dùng cuối để chia sẻ nội dung với người dùng bên ngoài sau khi di chuyển.)</span><span class="sxs-lookup"><span data-stu-id="b5182-529">Instruct end users to reshare content with external users after migration.)</span></span> </li>
<li> <span data-ttu-id="b5182-530">Các tệp hoặc thư mục vượt quá <a href="https://go.microsoft.com/fwlink/?linkid=846724"> <span class="underline">hạn chế và giới hạn của SharePoint Online</span> hiện tại</a> </span><span class="sxs-lookup"><span data-stu-id="b5182-530">Files or folders exceeding current <a href="https://go.microsoft.com/fwlink/?linkid=846724"><span class="underline">SharePoint Online restrictions and limitations</span></a> </span></span></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="fasttrack-responsibilities"></a><span data-ttu-id="b5182-531">Các trách nhiệm FastTrack</span><span class="sxs-lookup"><span data-stu-id="b5182-531">FastTrack responsibilities</span></span>

<span data-ttu-id="b5182-532">Các chuyên gia FastTrack của chúng tôi thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-532">Our FastTrack Specialists perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-533">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-533">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

## <a name="your-responsibilities"></a><span data-ttu-id="b5182-534">Trách nhiệm của bạn</span><span class="sxs-lookup"><span data-stu-id="b5182-534">Your responsibilities</span></span>

<span data-ttu-id="b5182-535">Bạn thực hiện các hoạt động chuẩn trong dự án di chuyển.</span><span class="sxs-lookup"><span data-stu-id="b5182-535">You perform standard activities during the migration project.</span></span> <span data-ttu-id="b5182-536">Tham khảo thông tin về các trách nhiệm di chuyển dữ liệu trong [quy trình và mong](process-and-expectations.md) muốn để biết chi tiết.</span><span class="sxs-lookup"><span data-stu-id="b5182-536">Refer to the data migration responsibilities information in [Process and Expectations](process-and-expectations.md) for details.</span></span>

<span data-ttu-id="b5182-537">Bạn cũng có thể thực hiện các hoạt động sau đây, đặc biệt là đối với di chuyển OneDrive for Business:</span><span class="sxs-lookup"><span data-stu-id="b5182-537">You also perform the following activities, specific to OneDrive for Business migrations:</span></span>

  - <span data-ttu-id="b5182-538">Cung cấp tất cả các site OneDrive for Business sẽ được mục tiêu theo sự kiện di chuyển của bạn.</span><span class="sxs-lookup"><span data-stu-id="b5182-538">Provision all OneDrive for Business sites that will be targeted by your migration events.</span></span>
