---
title: Quy trình FastTrack
ms.author: v-bermic@microsoft.com
author: rberg-steyer@microsoft.com-msft
manager: jimmuir
ms.date: 7/01/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: None
ms.collection: FastTrack
description: Quy trình FastTrack cung cấp các dịch vụ triển ngoài hệ thống và tiếp nhận người dùng.
ms.openlocfilehash: 6d13e6fc9247196c9a2e6cf7692abf3fa75152dc
ms.sourcegitcommit: ed3a1ad4b24b7b6b78070e21139b3a38f7a6ed69
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/08/2021
ms.locfileid: "52283557"
---
# <a name="the-fasttrack-process"></a><span data-ttu-id="22673-103">Quy trình FastTrack</span><span class="sxs-lookup"><span data-stu-id="22673-103">The FastTrack Process</span></span>

> [!CAUTION]
> <span data-ttu-id="22673-104">Nội dung này không còn mới nhất và được lên lịch loại bỏ.</span><span class="sxs-lookup"><span data-stu-id="22673-104">This content is no longer current and is scheduled for removal.</span></span> <span data-ttu-id="22673-105">Sử dụng mục lục trong dẫn hướng bên trái cho nội dung hiện tại.</span><span class="sxs-lookup"><span data-stu-id="22673-105">Use the table of contents in the left-hand navigation for current content.</span></span>

<span data-ttu-id="22673-106">Quy trình FastTrack cung cấp các dịch vụ triển ngoài hệ thống và tiếp nhận người dùng.</span><span class="sxs-lookup"><span data-stu-id="22673-106">The FastTrack process provides onboarding and user adoption services.</span></span> 
  
<span data-ttu-id="22673-107">Triển năng bao gồm:</span><span class="sxs-lookup"><span data-stu-id="22673-107">Onboarding consists of:</span></span>
  
- <span data-ttu-id="22673-108">*Triển thị cốt lõi* — Đây là các tác vụ bắt buộc cho cấu hình đối tượng thuê và tích hợp với Azure Active Directory (Azure AD) nếu cần thiết.</span><span class="sxs-lookup"><span data-stu-id="22673-108">*Core onboarding* — These are tasks required for tenant configuration and integration with Azure Active Directory (Azure AD) if needed.</span></span> <span data-ttu-id="22673-109">Triển năng cốt lõi cũng cung cấp đường cơ sở để triển thị các dịch vụ đủ điều kiện khác.</span><span class="sxs-lookup"><span data-stu-id="22673-109">Core onboarding also provides the baseline for onboarding other eligible services.</span></span> 
- <span data-ttu-id="22673-110">*Đưa vào và di chuyển dịch vụ* — Tác vụ tiếp thị dịch vụ cho phép kịch bản trong đối tượng thuê của bạn.</span><span class="sxs-lookup"><span data-stu-id="22673-110">*Service onboarding and migration* — Service onboarding tasks enable scenarios in your tenant.</span></span> <span data-ttu-id="22673-111">Di chuyển dữ liệu (bao gồm email và tệp) được đề cập trong [Di chuyển Dữ liệu](O365-data-migration.md).</span><span class="sxs-lookup"><span data-stu-id="22673-111">Data migration (including email and files) is covered in [Data Migration](O365-data-migration.md).</span></span> 
    
<span data-ttu-id="22673-112">Dịch vụ tiếp nhận của người dùng bao gồm các tác vụ cung cấp hướng dẫn để bạn đảm bảo người dùng của bạn biết các dịch vụ đủ điều kiện và có thể sử dụng chúng để thúc đẩy giá trị kinh doanh.</span><span class="sxs-lookup"><span data-stu-id="22673-112">User adoption services are comprised of tasks that provide guidance for you to ensure your users are aware of the eligible services and can use them to drive business value.</span></span> <span data-ttu-id="22673-113">Trợ giúp này xảy ra song song với các hoạt động triển trí.</span><span class="sxs-lookup"><span data-stu-id="22673-113">This assistance occurs in parallel to onboarding activities.</span></span>
  
> [!NOTE]
> <span data-ttu-id="22673-114">FastTrack cung cấp cho khách hàng một phương pháp tiếp cận, hướng dẫn và thực hành tốt nhất được đề xuất, được thiết kế để mang lại kết quả nhanh chóng và có thể dự đoán.</span><span class="sxs-lookup"><span data-stu-id="22673-114">FastTrack provides customers with a recommended approach, guidance, and best practices engineered to deliver quick and predictable outcomes.</span></span> <span data-ttu-id="22673-115">Nếu bạn chọn triển khai ngoài hướng dẫn này, trải nghiệm triển khai và việc sử dụng dịch vụ có thể bị ảnh hưởng.</span><span class="sxs-lookup"><span data-stu-id="22673-115">If you choose to deploy outside of this guidance, your onboarding experience and usage of the service may be impacted.</span></span> <span data-ttu-id="22673-116">Hướng dẫn được xác định là sự kết hợp giữa hỗ trợ bằng lời nói và bằng văn bản.</span><span class="sxs-lookup"><span data-stu-id="22673-116">Guidance is defined as a combination of verbal and written assistance.</span></span> <span data-ttu-id="22673-117">Khi Các chuyên gia FastTrack cung cấp hướng dẫn, nhân viên FastTrack không thể thay mặt bạn hành động.</span><span class="sxs-lookup"><span data-stu-id="22673-117">When FastTrack Specialists provide guidance, FastTrack personnel cannot act on your behalf.</span></span> <span data-ttu-id="22673-118">Bạn có thể sử dụng các dịch vụ FastTrack để triển năng và áp dụng mọi khối lượng công việc sản phẩm đủ điều kiện miễn là đăng ký của bạn là hiện thời.</span><span class="sxs-lookup"><span data-stu-id="22673-118">You can use FastTrack services to onboard and adopt any qualifying product workload as long as your subscription is current.</span></span> 
  
## <a name="the-onboarding-process"></a><span data-ttu-id="22673-119">Quy trình triển năng</span><span class="sxs-lookup"><span data-stu-id="22673-119">The onboarding process</span></span>

<span data-ttu-id="22673-120">Sơ đồ sau đây minh họa quy trình triển khai.</span><span class="sxs-lookup"><span data-stu-id="22673-120">The following diagram illustrates the onboarding process.</span></span>
  
![Đường thời gian để sử dụng lợi ích Onboarding](media/o365-onboarding-timeline-m365-apps.png)
  
<span data-ttu-id="22673-122">Bạn có thể nhận trợ giúp thông [qua trung Microsoft 365 quản trị Chính](https://go.microsoft.com/fwlink/?linkid=2032704) hoặc site [FastTrack.](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="22673-122">You can get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704) or the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 

<span data-ttu-id="22673-123">Để nhận trợ giúp thông qua [trung Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2032704)trị viên, người quản trị của bạn đăng nhập vào trung tâm quản trị, rồi bấm vào tiện ích Bạn **cần trợ** giúp?.</span><span class="sxs-lookup"><span data-stu-id="22673-123">To get help through the [Microsoft 365 admin center](https://go.microsoft.com/fwlink/?linkid=2032704), your admin signs into the admin center and then clicks the **Need help?** widget.</span></span> 

<span data-ttu-id="22673-124">Để được trợ giúp qua [site FastTrack:](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="22673-124">To get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698):</span></span> 
1.    <span data-ttu-id="22673-125">Đăng nhập vào [site FastTrack.](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="22673-125">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="22673-126">Chọn **Yêu cầu hỗ trợ Microsoft 365** lời từ các tác **vụ** nhanh ở đầu trang đích của bạn.</span><span class="sxs-lookup"><span data-stu-id="22673-126">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="22673-127">Hoàn thành biểu **mẫu Yêu cầu Hỗ Microsoft 365.**</span><span class="sxs-lookup"><span data-stu-id="22673-127">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
<span data-ttu-id="22673-128">Đối tác cũng có thể nhận trợ giúp [thông qua site FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) thay mặt cho khách hàng.</span><span class="sxs-lookup"><span data-stu-id="22673-128">Partners can also get help through the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) on behalf of a customer.</span></span> <span data-ttu-id="22673-129">Cách thực hiện:</span><span class="sxs-lookup"><span data-stu-id="22673-129">To do so:</span></span>
1.    <span data-ttu-id="22673-130">Đăng nhập vào [site FastTrack.](https://go.microsoft.com/fwlink/?linkid=780698)</span><span class="sxs-lookup"><span data-stu-id="22673-130">Sign in to the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698).</span></span> 
2.    <span data-ttu-id="22673-131">Chọn **Yêu cầu hỗ trợ Microsoft 365** lời từ các tác **vụ** nhanh ở đầu trang đích của bạn.</span><span class="sxs-lookup"><span data-stu-id="22673-131">Select **Request assistance with Microsoft 365** from the **quick actions** on the top of your landing page.</span></span>
3.    <span data-ttu-id="22673-132">Tìm kiếm khách hàng của bạn bằng cách nhập tên khách hàng, miền hoặc TPID.</span><span class="sxs-lookup"><span data-stu-id="22673-132">Search for your customer by entering the customer name, domain, or TPID.</span></span>
4.    <span data-ttu-id="22673-133">Chọn khách hàng từ kết quả tìm kiếm.</span><span class="sxs-lookup"><span data-stu-id="22673-133">Select customer from the search results.</span></span>
5.    <span data-ttu-id="22673-134">Hoàn thành biểu **mẫu Yêu cầu Hỗ Microsoft 365.**</span><span class="sxs-lookup"><span data-stu-id="22673-134">Complete the **Request Assistance with Microsoft 365** form.</span></span>
  
 <span data-ttu-id="22673-135">Bạn cũng có thể yêu cầu Trợ giúp Về Trung tâm FastTrack từ [site FastTrack](https://go.microsoft.com/fwlink/?linkid=780698) trong danh sách các dịch vụ sẵn có cho đối tượng thuê của mình.</span><span class="sxs-lookup"><span data-stu-id="22673-135">You can also ask for FastTrack Center help from the [FastTrack site](https://go.microsoft.com/fwlink/?linkid=780698) in the list of available services for your tenant.</span></span> 
    
 <span data-ttu-id="22673-136">Sau khi hỗ trợ triển năng bắt đầu, chúng tôi thiết lập lịch biểu cho các cuộc họp trực tuyến.</span><span class="sxs-lookup"><span data-stu-id="22673-136">Once onboarding assistance starts, we set up a schedule of online meetings.</span></span>

<span data-ttu-id="22673-137">Bảng sau đây liệt kê các vai trò và trách nhiệm đối với quy trình.</span><span class="sxs-lookup"><span data-stu-id="22673-137">The following table lists roles and responsibilities for the process.</span></span>
    
|||
|:-----|:-----|
|<span data-ttu-id="22673-138">**Vai trò**</span><span class="sxs-lookup"><span data-stu-id="22673-138">**Role**</span></span> <br/> |<span data-ttu-id="22673-139">**Trách nhiệm**</span><span class="sxs-lookup"><span data-stu-id="22673-139">**Responsibility**</span></span> <br/> |
|<span data-ttu-id="22673-140">**Chuyên gia FastTrack**</span><span class="sxs-lookup"><span data-stu-id="22673-140">**FastTrack Specialist**</span></span> <br/> |<span data-ttu-id="22673-141">Cung cấp tất cả các dịch vụ tiếp nhận, di chuyển và tiếp nhận người dùng từ xa.</span><span class="sxs-lookup"><span data-stu-id="22673-141">Provides all onboarding, migration, and user adoption services remotely.</span></span>  <br/> <span data-ttu-id="22673-142">Hỗ trợ bạn từ xa bằng cách sử dụng kết hợp các công cụ và tài liệu được phát hành.</span><span class="sxs-lookup"><span data-stu-id="22673-142">Assists you remotely by using a combination of tools and published documentation.</span></span> <br/> <span data-ttu-id="22673-143">Làm việc trực tiếp với bạn hoặc đại diện của bạn.</span><span class="sxs-lookup"><span data-stu-id="22673-143">Works directly with you or your representative.</span></span> <br/> <span data-ttu-id="22673-144">Cung cấp hướng dẫn di chuyển email và dữ liệu.</span><span class="sxs-lookup"><span data-stu-id="22673-144">Provides email and data migration guidance.</span></span>|
|<span data-ttu-id="22673-145">**Trung tâm FastTrack**</span><span class="sxs-lookup"><span data-stu-id="22673-145">**FastTrack Center**</span></span>  <br/> |<span data-ttu-id="22673-146">Cung cấp hướng dẫn cốt lõi và triển năng dịch vụ, đồng thời lên kế hoạch tiếp nhận thành công các dịch vụ đủ điều kiện.</span><span class="sxs-lookup"><span data-stu-id="22673-146">Provides guidance with core and service onboarding and planning successful adoption of eligible services.</span></span>  <br/> <span data-ttu-id="22673-147">Cung cấp hỗ trợ và khả dụng trong giờ làm việc bình thường cho một khu vực nhất định.</span><span class="sxs-lookup"><span data-stu-id="22673-147">Provides assistance and is available during normal business hours for a given region.</span></span> <br/> <span data-ttu-id="22673-148">Cung cấp hỗ trợ bằng tiếng Trung Truyền thống và tiếng Trung Giản thể (các tài nguyên chỉ nói tiếng Quan thoại), tiếng Anh, tiếng Pháp, tiếng Đức, tiếng Ý, tiếng Nhật, tiếng Hàn, tiếng Bồ Đào Nha (Brazil), tiếng Tây Ban Nha, tiếng Thái và tiếng Việt.</span><span class="sxs-lookup"><span data-stu-id="22673-148">Provides assistance in Traditional Chinese and Simplified Chinese (resources speak Mandarin only), English, French, German, Italian, Japanese, Korean, Portuguese (Brazil), Spanish, Thai, and Vietnamese.</span></span>|
