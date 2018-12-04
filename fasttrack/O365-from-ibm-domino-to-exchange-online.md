---
title: Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online
ms.author: v-rberg
author: v-rberg-msft
manager: jimmuir
ms.date: 12/4/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-administration
localization_priority: Priority
ms.collection: FastTrack
ms.assetid: 7519ee6f-67e6-4064-b1b2-a26f35cdba0b
description: 'Di chuyển từ IBM Domino để trao đổi trực tuyến bao gồm một vài khía cạnh quan trọng, bao gồm cả những gì sẽ xảy ra vào giai đoạn sau đây:'
ms.openlocfilehash: 70151f726a2368d61262d540d77041cff21fa7c3
ms.sourcegitcommit: 3ecf2619868abc13716701393831dd0c24e00d9d
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 12/03/2018
ms.locfileid: "27133116"
---
# <a name="appendix-a---migration-from-ibm-domino-to-exchange-online"></a><span data-ttu-id="a909a-103">Phụ lục A - Di chuyển từ IBM Domino sang Exchange Online</span><span class="sxs-lookup"><span data-stu-id="a909a-103">Appendix A - Migration from IBM Domino to Exchange Online</span></span>

<span data-ttu-id="a909a-104">Di chuyển từ IBM Domino để trao đổi trực tuyến bao gồm một vài khía cạnh quan trọng, bao gồm cả những gì sẽ xảy ra vào giai đoạn sau đây:</span><span class="sxs-lookup"><span data-stu-id="a909a-104">Migration from IBM Domino to Exchange Online includes several important aspects, including what happens during the following phases:</span></span> 
- [<span data-ttu-id="a909a-105">Bắt đầu giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-105">Initiate phase</span></span>](#initiate-phase)   
- [<span data-ttu-id="a909a-106">Đánh giá giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-106">Assess phase</span></span>](#assess-phase)
- [<span data-ttu-id="a909a-107">Remediate giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-107">Remediate phase</span></span>](#remediate-phase)  
- [<span data-ttu-id="a909a-108">Sử giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-108">Enable phase</span></span>](#enable-phase)  
- [<span data-ttu-id="a909a-109">Di chuyển giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-109">Migrate phase</span></span>](#migrate-phase)
    
## <a name="identities"></a><span data-ttu-id="a909a-110">Danh tính</span><span class="sxs-lookup"><span data-stu-id="a909a-110">Identities</span></span>

<span data-ttu-id="a909a-p101">Bạn chịu trách nhiệm cho việc tạo và quản lý danh tính (đám mây duy nhất, đồng bộ, hoặc được liên kết với Active Directory tại chỗ của họ). Bạn phải hoàn thành lập bản đồ nhận dạng (nếu không đã trình bày) giữa Domino và Active Directory tại chỗ hoặc Azure AD trong giai đoạn đầu của onboarding.</span><span class="sxs-lookup"><span data-stu-id="a909a-p101">You are responsible for creating and managing the identities (cloud only, synchronized, or federated with their on-premises Active Directory). You must complete the mapping of identities (if not already present) between Domino and the on-premises Active Directory or Azure AD during the early stages of onboarding.</span></span>
  
## <a name="coexistence"></a><span data-ttu-id="a909a-113">Cùng tồn tại</span><span class="sxs-lookup"><span data-stu-id="a909a-113">Coexistence</span></span>

<span data-ttu-id="a909a-114">Lợi ích Trung tâm FastTrack cho Office 365 cung cấp hai chiều luồng thư giữa các môi trường Domino tại chỗ và Exchange Online cho mọi khách hàng.</span><span class="sxs-lookup"><span data-stu-id="a909a-114">The FastTrack Center Benefit for Office 365 provides bidirectional mail flow between the on-premises Domino environment and Exchange Online to all customers.</span></span>
  
## <a name="migration"></a><span data-ttu-id="a909a-115">Di chuyển</span><span class="sxs-lookup"><span data-stu-id="a909a-115">Migration</span></span>

<span data-ttu-id="a909a-p102">Quá trình FastTrack Trung tâm tiêu chuẩn cho di chuyển từ Domino để trao đổi trực tuyến liên quan đến trước dàn Domino dữ liệu Azure trước khi di chuyển đến hộp thư Exchange Online. Di cư FastTrack yêu cầu hoạt động được thực hiện ở các giai đoạn khác nhau của onboarding của nhân viên Trung tâm FastTrack và bạn. Chúng tôi bao gồm các hoạt động này trong các phần sau.</span><span class="sxs-lookup"><span data-stu-id="a909a-p102">The standard FastTrack Center process for migration from Domino to Exchange Online involves pre-staging Domino data to Azure before migration to Exchange Online mailboxes. FastTrack migrations require activities to be performed at different stages of onboarding by FastTrack Center personnel and you. We cover these activities in the following sections.</span></span>
  
> [!NOTE]
> <span data-ttu-id="a909a-p103">Dữ liệu di chuyển qua FastTrack dịch vụ có thể được chuyển đến, lưu trữ và xử lý tại Hoa Kỳ hoặc bất cứ nơi nào mà Microsoft vẫn duy trì các tiện nghi. Dịch vụ FastTrack không được thiết kế hoặc thiết kế cho dữ liệu đặc biệt yêu cầu pháp lý hoặc theo quy định.</span><span class="sxs-lookup"><span data-stu-id="a909a-p103">Data migrated through the FastTrack services may be transferred to, stored, and processed in the United States or anywhere that Microsoft maintains facilities. The FastTrack services aren't designed or intended for data subject to special legal or regulatory requirements.</span></span> 
  
## <a name="initiate-phase"></a><span data-ttu-id="a909a-121">Bắt đầu giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-121">Initiate phase</span></span>

 <span data-ttu-id="a909a-122">**Hành động quan trọng**</span><span class="sxs-lookup"><span data-stu-id="a909a-122">**Key actions**</span></span>
  
- <span data-ttu-id="a909a-123">Xác định các Domino như là nền tảng thư nguồn.</span><span class="sxs-lookup"><span data-stu-id="a909a-123">Identify Domino as the source mail platform.</span></span>   
- <span data-ttu-id="a909a-124">Xác định cho dù Trung tâm FastTrack thực hiện việc di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-124">Determine whether the FastTrack Center performs the migration.</span></span>
    
 <span data-ttu-id="a909a-125">**Trách nhiệm của khách hàng**</span><span class="sxs-lookup"><span data-stu-id="a909a-125">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="a909a-126">Cung cấp các thông tin cơ bản về nền tảng tin nhắn mã nguồn, và xác nhận ý định di chuyển với Trung tâm FastTrack.</span><span class="sxs-lookup"><span data-stu-id="a909a-126">Provide basic information about the source messaging platform, and confirm the migration intent with the FastTrack Center.</span></span> 
- <span data-ttu-id="a909a-127">Tham gia vào một hướng các quá trình FastTrack Trung tâm lợi ích.</span><span class="sxs-lookup"><span data-stu-id="a909a-127">Participate in a walkthrough of the FastTrack Center Benefit processes.</span></span>  
- <span data-ttu-id="a909a-128">Ký thỏa thuận dịch vụ FastTrack.</span><span class="sxs-lookup"><span data-stu-id="a909a-128">Sign the FastTrack Services Agreement.</span></span>
    
## <a name="assess-phase"></a><span data-ttu-id="a909a-129">Đánh giá giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-129">Assess phase</span></span>

 <span data-ttu-id="a909a-130">**Hành động quan trọng**</span><span class="sxs-lookup"><span data-stu-id="a909a-130">**Key actions**</span></span>
  
- <span data-ttu-id="a909a-131">Trung tâm FastTrack tiến hành một hội thảo di chuyển với khách hàng.</span><span class="sxs-lookup"><span data-stu-id="a909a-131">The FastTrack Center conducts a migration workshop with the customer.</span></span> 
- <span data-ttu-id="a909a-132">Bạn hoàn thành điều kiện tiên quyết di chuyển như các câu hỏi di chuyển và cung cấp các admin máy trạm.</span><span class="sxs-lookup"><span data-stu-id="a909a-132">You complete the migration prerequisites, like the migration questionnaire and the provisioning of admin workstations.</span></span>    
- <span data-ttu-id="a909a-133">Di chuyển đánh giá cho các Domino được thực hiện trong môi trường tại chỗ của bạn.</span><span class="sxs-lookup"><span data-stu-id="a909a-133">Migration assessment for Domino is performed in your on-premises environment.</span></span>
    
 <span data-ttu-id="a909a-134">**Trách nhiệm của khách hàng**</span><span class="sxs-lookup"><span data-stu-id="a909a-134">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="a909a-135">Cung cấp tài khoản admin máy trạm làm việc Trung tâm FastTrack sử dụng để quản lý tác vụ onboarding và di chuyển, như đánh giá, sáng tạo bản sao, kiểm định, thiết lập chuyển tiếp trong thời gian di chuyển, và như vậy.</span><span class="sxs-lookup"><span data-stu-id="a909a-135">Provision admin workstations that the FastTrack Center uses to administer onboarding and migration tasks, like assessment, replica creation, auditing, setting forwarding during migration, and so on.</span></span>
    > [!NOTE]
    > <span data-ttu-id="a909a-p104">Đánh giá là rất quan trọng cho thành công kế hoạch và thực hiện vận tốc di chuyển. Nó được thực hiện bởi một kiến trúc sư di chuyển những người cần truy cập cụ thể đến môi trường Domino. Yêu cầu admin máy trạm thành phần bao gồm một khách hàng ghi chú cấu hình để truy cập vào tất cả các máy chủ mail Domino nguồn và bản sao Azure Domino dàn máy chủ.</span><span class="sxs-lookup"><span data-stu-id="a909a-p104">Assessment is critical for successful planning and execution of velocity migrations. It's performed by a migration architect who needs specific access to the Domino environment. Required admin workstation components include a Notes client configured to access all source Domino mail servers and the Azure Domino replica staging server.</span></span> 
- <span data-ttu-id="a909a-p105">Cung cấp di chuyển đội truy cập từ xa để quản trị máy trạm, tài khoản và quyền để thực hiện các hoạt động đánh giá và di chuyển. Điều này bao gồm cung cấp nhiều tài khoản tại chỗ và trong Exchange Online với quyền quản trị cần thiết để di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-p105">Provide the migration team remote access to the admin workstations, accounts, and permissions for performing assessment and migration activities. This includes provisioning multiple accounts on-premises and in Exchange Online with administrative permissions needed for migration.</span></span>    
- <span data-ttu-id="a909a-p106">Cổng mở tường lửa. Cổng ra bên ngoài phải được mở giữa các máy chủ thư Domino nguồn và dàn dựng server Azure. Các cảng khác để liên lạc (như admin máy trạm, nguồn Domino máy chủ, và trao đổi máy chủ tại chỗ (nếu có)) phải cũng phải được mở.</span><span class="sxs-lookup"><span data-stu-id="a909a-p106">Open firewall ports. Outbound ports must be opened between the source Domino mail servers and the Azure staging server. Other ports for communication (like admin workstations, source Domino servers, and Exchange servers on-premises (if present)) must also must be opened.</span></span> 
- <span data-ttu-id="a909a-p107">Cho phép cấp giấy chứng nhận chéo giữa môi trường Domino nguồn và Azure Domino dàn máy chủ để tạo điều kiện mở rộng. Cross-chứng nhận nhiệm vụ phải phối hợp giữa các khách hàng Domino admin và Trung tâm FastTrack.</span><span class="sxs-lookup"><span data-stu-id="a909a-p107">Enable cross-certification between the source Domino environment and the Azure Domino staging server to facilitate replication. Cross-certification tasks are coordinated between the customer's Domino admin and the FastTrack Center.</span></span>  
- <span data-ttu-id="a909a-146">Hoàn thành bảng câu hỏi di trú, nắm bắt thông tin cần thiết để cấu hình môi trường di chuyển trong Azure (như công cụ, kịch bản và di chuyển máy chủ).</span><span class="sxs-lookup"><span data-stu-id="a909a-146">Complete the migration questionnaire, which captures information required to configure the migration environment in Azure (like tools, scripts, and migration servers).</span></span>   
- <span data-ttu-id="a909a-147">Đảm bảo mục tiêu các hộp thư trong Office 365 có giao thức nhắn tin ứng dụng chương trình giao diện (MAPI) được kích hoạt.</span><span class="sxs-lookup"><span data-stu-id="a909a-147">Ensure target mailboxes in Office 365 have Messaging Application Program Interface (MAPI) protocol enabled.</span></span>  
> [!NOTE]
> <span data-ttu-id="a909a-p108">Một số kế hoạch Office 365 không hỗ trợ giao thức MAPI. Để di chuyển dữ liệu, hộp thư từ những kế hoạch này cần phải được chuyển đổi sang một kế hoạch hỗ trợ MAPI trước các sự kiện di chuyển. Sau khi di chuyển, các kế hoạch này có thể được thay đổi trở lại.</span><span class="sxs-lookup"><span data-stu-id="a909a-p108">Some Office 365 plans don't support MAPI protocol. In order to migrate data, mailboxes from these plans need to be converted to a plan that supports MAPI ahead of the migration event. Following migration, these plans can be changed back.</span></span> 
  
## <a name="remediate-phase"></a><span data-ttu-id="a909a-151">Remediate giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-151">Remediate phase</span></span>

 <span data-ttu-id="a909a-152">**Hành động quan trọng**</span><span class="sxs-lookup"><span data-stu-id="a909a-152">**Key actions**</span></span>
  
- <span data-ttu-id="a909a-153">Trung tâm FastTrack đánh giá báo cáo đánh giá di chuyển và kiểm tra các chi tiết mà bạn cung cấp bằng cách sử dụng các câu hỏi.</span><span class="sxs-lookup"><span data-stu-id="a909a-153">The FastTrack Center reviews the migration assessment report and tests the details that you supply using the questionnaire.</span></span>   
- <span data-ttu-id="a909a-154">Túc mục được đề xuất bởi Trung tâm FastTrack phải được hoàn thành bởi bạn.</span><span class="sxs-lookup"><span data-stu-id="a909a-154">Remediation items suggested by the FastTrack Center must be completed by you.</span></span>
    
 <span data-ttu-id="a909a-155">**Trách nhiệm của khách hàng**</span><span class="sxs-lookup"><span data-stu-id="a909a-155">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="a909a-156">Remediate môi trường Domino dựa trên nguyên tắc Trung tâm FastTrack cung cấp (ví dụ, thiết lập bất kỳ điều khoản yêu cầu được xác định là mất tích trong các tập tin thư).</span><span class="sxs-lookup"><span data-stu-id="a909a-156">Remediate the Domino environment based on guidelines that the FastTrack Center provides (for example, setting any required permissions that are identified as missing in the mail files).</span></span>  
- <span data-ttu-id="a909a-157">Đảm bảo rằng hộp thư Domino dưới kích thước tối đa cho phép thông qua di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-157">Ensure that Domino mailboxes are below the maximum size allowed through migration.</span></span>
    > [!NOTE]
    >  <span data-ttu-id="a909a-158">Mặc dù FastTrack di chuyển hộp thư đến 85% của tổng số cho phép nhắm mục tiêu kích thước, cố gắng để di chuyển hộp thư lớn hơn 2 GB mang các rủi ro bổ sung như:</span><span class="sxs-lookup"><span data-stu-id="a909a-158">Although FastTrack migrates mailboxes up to 85% of the total allowable target size, attempting to migrate mailboxes larger than 2 GB carries additional risks like:</span></span>    <br/> <span data-ttu-id="a909a-p109">Kéo dài thời gian của quá trình di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-p109">Lengthened duration of migrations.    </span></span><br/> <span data-ttu-id="a909a-p110">Sử dụng các nguồn tài nguyên khác được sử dụng để di chuyển các hộp thư khác.</span><span class="sxs-lookup"><span data-stu-id="a909a-p110">Using resources otherwise used for migrating other mailboxes.    </span></span><br/> <span data-ttu-id="a909a-161">Sự gia tăng đáng kể trong tỷ lệ lỗi.</span><span class="sxs-lookup"><span data-stu-id="a909a-161">A considerable increase in error rates.</span></span> 
- <span data-ttu-id="a909a-p111">Chuẩn bị các thư trong cơ sở dữ liệu và kiểm soát truy cập danh sách (ACLs) cho di chuyển. Bạn phải thực hiện một số bước khắc phục thành công di chuyển thư trong cơ sở dữ liệu và quyền của mình để một hộp thư dùng chung trong Exchange Online. Một vài trong số các bước này là như sau:</span><span class="sxs-lookup"><span data-stu-id="a909a-p111">Prepare the mail-in databases and their access control lists (ACLs) for migration. You must perform some remediation steps to successfully migrate mail-in databases and their permissions to a shared mailbox in Exchange Online. A few of these steps are as follows:</span></span> 
  - <span data-ttu-id="a909a-165">Loại bỏ các mục thư trong cơ sở dữ liệu hiện có trong thư mục Domino và tạo hồ sơ người mới.</span><span class="sxs-lookup"><span data-stu-id="a909a-165">Remove existing mail-in database entries in the Domino directory and create new Person records.</span></span>
  - <span data-ttu-id="a909a-p112">Tạo nhóm bảo mật phổ quát kích hoạt thư trong Active Directory tại chỗ được đồng bộ hoá với Office 365 Azure quảng cáo và sử dụng để đặt cấu hình quyền truy cập vào hộp thư dùng chung trong Exchange Online. Này chuyển các quyền thiết lập trên cơ sở dữ liệu thư ở trên vào hộp thư dùng chung trong Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="a909a-p112">Create mail-enabled universal security groups in the on-premises Active Directory that are synchronized to Office 365 Azure AD and used to configure permissions on the shared mailbox in Exchange Online. This transfers the permissions set on the mail-in database over to the shared mailbox in Exchange Online.</span></span>
    
> [!NOTE]
> <span data-ttu-id="a909a-168">Người dùng cuối chuẩn bị sẵn sàng và đào tạo cho hệ thống mới nhắn tin và khách hàng có thể được bắt đầu bây giờ.</span><span class="sxs-lookup"><span data-stu-id="a909a-168">End-user readiness and training for the new messaging system and client can be started now.</span></span> 
  
## <a name="enable-phase"></a><span data-ttu-id="a909a-169">Sử giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-169">Enable phase</span></span>

 <span data-ttu-id="a909a-170">**Hành động quan trọng**</span><span class="sxs-lookup"><span data-stu-id="a909a-170">**Key actions**</span></span>
  
- <span data-ttu-id="a909a-171">Trung tâm FastTrack:</span><span class="sxs-lookup"><span data-stu-id="a909a-171">The FastTrack Center:</span></span> 
    - <span data-ttu-id="a909a-172">Thiết lập môi trường di chuyển trong Azure.</span><span class="sxs-lookup"><span data-stu-id="a909a-172">Sets up the migration environment in Azure.</span></span>  
    - <span data-ttu-id="a909a-173">Cấu hình công cụ di chuyển trên máy trạm admin tại chỗ.</span><span class="sxs-lookup"><span data-stu-id="a909a-173">Configures the migration tools on the on-premises admin workstations.</span></span> 
    - <span data-ttu-id="a909a-174">Cấu hình và chứng tỏ làm thế nào để sử dụng công cụ tự động nhập khẩu.</span><span class="sxs-lookup"><span data-stu-id="a909a-174">Configures and demonstrates how to use the Auto-Import tool.</span></span>  
    - <span data-ttu-id="a909a-175">Tiến hành xác nhận tất cả các thành phần di chuyển và thực hiện kiểm tra quá trình di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-175">Conducts validation of all migration components and performs test migrations.</span></span>
    
 <span data-ttu-id="a909a-176">**Trách nhiệm của khách hàng**</span><span class="sxs-lookup"><span data-stu-id="a909a-176">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="a909a-p113">Nhân sự của bạn phụ trách lập kế hoạch di chuyển hộp thư phải hiểu làm thế nào để sử dụng công cụ tự động nhập khẩu. Bạn sử dụng công cụ này để nhập lịch trình di chuyển vào cơ sở dữ liệu lập kế hoạch Trung tâm FastTrack sử dụng để thực hiện các hoạt động trước khi di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-p113">Your personnel in charge of scheduling mailbox migration must understand how to use the Auto-Import tool. You use this tool to import the migration schedule into the scheduling database which the FastTrack Center uses to perform pre-migration activities.</span></span> 
- <span data-ttu-id="a909a-179">Thực hiện các hoạt động trước khi di chuyển như nhập khẩu sử dụng lịch trình, phân tích các báo cáo kiểm toán, remediating bất kỳ vấn đề và reimporting tài khoản người dùng với các vấn đề.</span><span class="sxs-lookup"><span data-stu-id="a909a-179">Perform pre-migration activities like importing user schedules, analyzing audit reports, remediating any issues, and reimporting user accounts with problems.</span></span>
    
<span data-ttu-id="a909a-p114">Trước khi di chuyển hoạt động được phối hợp giữa bạn và Trung tâm FastTrack. Sao chép vào Azure bắt đầu sau khi lịch trình di chuyển của người dùng được nhập khẩu.</span><span class="sxs-lookup"><span data-stu-id="a909a-p114">Pre-migration activities are coordinated between you and the FastTrack Center. Replication to Azure begins after the user migration schedule is imported.</span></span> 
    
> [!NOTE]
> <span data-ttu-id="a909a-p115">Thời gian cần thiết để tái tạo phụ thuộc vào lượng dữ liệu. Trung tâm FastTrack sau đó thực hiện kiểm toán để xác định sự sẵn sàng di chuyển. Kết quả kiểm tra được cung cấp cho bạn với sự hiểu biết mà khắc phục sau đó được yêu cầu bình thường. Tất cả các bước được gọi là "T-trừ" hoạt động bởi vì họ phải bắt đầu trước di chuyển theo lịch trình của người dùng.</span><span class="sxs-lookup"><span data-stu-id="a909a-p115">The time required to replicate depends on the amount of data. The FastTrack Center then performs auditing to determine migration readiness. Audit results are provided to you with the understanding that subsequent remediation is normally required. All of these steps are called "T-minus" activities because they must begin in advance of the users' scheduled migration.</span></span> 
  
## <a name="migrate-phase"></a><span data-ttu-id="a909a-186">Di chuyển giai đoạn</span><span class="sxs-lookup"><span data-stu-id="a909a-186">Migrate phase</span></span>

 <span data-ttu-id="a909a-187">**Hành động quan trọng**</span><span class="sxs-lookup"><span data-stu-id="a909a-187">**Key actions**</span></span>
  
- <span data-ttu-id="a909a-188">Trung tâm FastTrack:</span><span class="sxs-lookup"><span data-stu-id="a909a-188">The FastTrack Center:</span></span>
    - <span data-ttu-id="a909a-189">Thực hiện thí điểm và tốc độ di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-189">Performs pilot and velocity migrations.</span></span>  
    - <span data-ttu-id="a909a-190">Thực hiện di chuyển các sự kiện và hoạt động T-trừ.</span><span class="sxs-lookup"><span data-stu-id="a909a-190">Performs migration events and T-minus activities.</span></span>
    - <span data-ttu-id="a909a-191">Cung cấp hỗ trợ sau khi di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-191">Provides post-migration assistance.</span></span>
    
 <span data-ttu-id="a909a-192">**Trách nhiệm của khách hàng**</span><span class="sxs-lookup"><span data-stu-id="a909a-192">**Customer responsibilities**</span></span>
  
- <span data-ttu-id="a909a-193">Xác định và nhập khẩu di chuyển lịch 21 ngày trước khi di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-193">Identify and import migration schedules 21 days prior to migration.</span></span>
    > [!NOTE]
    > <span data-ttu-id="a909a-p116">Nhiệm vụ này là rất quan trọng bởi vì các hoạt động di chuyển tiền liên quan đến khắc phục và retries có thể tạo ra bản sao ở các giai đoạn khác nhau trước ngày di cư thực tế (T-0). Trong khi một số hộp thư di chuyển, T-trừ các hoạt động đang được thực hiện trên những người khác. Điều này làm cho đúng kế hoạch và phối hợp phải.</span><span class="sxs-lookup"><span data-stu-id="a909a-p116">This task is critical because the pre-migration activities involve remediation and possible retries of replica creation at different stages before the actual migration day (T-0). While some mailboxes are migrating, T-minus activities are being performed on others. This makes proper planning and coordination a must.</span></span> 
- <span data-ttu-id="a909a-197">Khắc phục sự cố được xác định trong thời gian T-trừ các hoạt động.</span><span class="sxs-lookup"><span data-stu-id="a909a-197">Fix issues identified during T-minus activities.</span></span>
- <span data-ttu-id="a909a-198">Giải quyết và sửa chữa bất kỳ Domino server các vấn đề ảnh hưởng đến các hoạt động di chuyển.</span><span class="sxs-lookup"><span data-stu-id="a909a-198">Address and fix any Domino server issues that impact migration activities.</span></span> 
- <span data-ttu-id="a909a-199">Tiến hành các thông tin liên lạc của người dùng cuối về ngày di cư sắp tới.</span><span class="sxs-lookup"><span data-stu-id="a909a-199">Conduct end-user communications about the upcoming migration date.</span></span>
- <span data-ttu-id="a909a-200">Tiến hành các hoạt động sẵn sàng chiến đấu của người dùng cuối và đào tạo cho hệ thống mới nhắn tin và khách hàng.</span><span class="sxs-lookup"><span data-stu-id="a909a-200">Conduct end-user readiness activities and training for the new messaging system and client.</span></span>   
- <span data-ttu-id="a909a-p117">Xác định và báo cáo các vấn đề sau khi di chuyển. Trung tâm FastTrack cung cấp hỗ trợ sau khi di chuyển đến T + 5 ngày sau khi di chuyển, sau đó nó sẽ trở thành trách nhiệm của bạn. Bạn có thể đăng nhập sau khi di chuyển vé cho các vấn đề như mất email, các mục lịch và danh bạ, hoặc bản sao trong hộp thư.</span><span class="sxs-lookup"><span data-stu-id="a909a-p117">Identify and report post-migration issues. The FastTrack Center provides post-migration assistance until T+5 days after migration, after which it becomes your responsibility. You can log post-migration tickets for issues like missing emails, calendar items, and contacts, or for duplicates in the mailbox.</span></span>
    
<span data-ttu-id="a909a-204">Trung tâm FastTrack không bao gồm việc triển khai, học phí giấy phép, hoặc hỗ trợ liên quan đến chuẩn bị thư mục (bao gồm cả đồng bộ hoá thư mục đang hoạt động Domino Directory), cùng tồn tại phần mềm tiện ích cho khả năng tương tác ứng dụng ghi chú, tự phục vụ di chuyển hoặc di chuyển lưu trữ.</span><span class="sxs-lookup"><span data-stu-id="a909a-204">The FastTrack Center doesn't cover deployment, license fees, or assistance related to directory preparation (including Domino-to-Active Directory directory synchronization), coexistence software add-ons for Notes application interoperability, self-service migration, or archive migration.</span></span>
  

  

