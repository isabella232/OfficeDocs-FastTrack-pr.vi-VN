---
title: Sản phẩm và chức năng
ms.author: rberg@steyer.net
author: rberg@steyer.net
manager: jimmuir
ms.date: 8/17/2020
ms.audience: ITPro
ms.topic: conceptual
ms.service: m365-administration
localization_priority: Priority
ms.collection: FastTrack
description: Chủ đề này bao gồm chi tiết về các tình huống khối lượng công việc được hỗ trợ bởi FastTrack và các kỳ vọng của môi trường nguồn cần thiết trước khi chúng tôi có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo một kế hoạch khắc phục sự kiện sẽ giúp môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để onboarding thành công.
ms.openlocfilehash: 64aefb7d7c99265fe56842a61873c06055af77de
ms.sourcegitcommit: f41acab3a535f26d1ad460c4788a1dcb9f4d7cfc
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 08/18/2020
ms.locfileid: "46787931"
---
# <a name="products-and-capabilities"></a>Sản phẩm và chức năng

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Các dịch vụ và tình huống được hỗ trợ bởi FastTrack

Chủ đề này bao gồm chi tiết về các tình huống khối lượng công việc được hỗ trợ bởi FastTrack và các kỳ vọng của môi trường nguồn cần thiết trước khi chúng tôi có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo một kế hoạch khắc phục sự kiện sẽ giúp môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để onboarding thành công.

Fasttrack cung cấp hướng dẫn để giúp bạn đầu tiên với các khả năng cốt lõi (phổ biến cho tất cả các dịch vụ trực tuyến của Microsoft) và sau đó với triển khai từng dịch vụ đủ điều kiện.

Những điều này rơi vào bốn thể loại:

  - [Thống](#general)
  - [Office 365](#office-365)
  - [Bảo mật & di động của doanh nghiệp](#enterprise-mobility--security)
  - [Windows 10](#windows-10)

> [!NOTE]
> Để biết thông tin về các kỳ vọng môi trường nguồn cho chính phủ Hoa Kỳ của Office 365, hãy xem các [kỳ vọng môi trường nguồn cho chính phủ office 365 US](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations).
 
## <a name="general"></a>Thống

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Căn phải triển khai</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa trên Core onboarding, liên quan đến việc cung cấp dịch vụ, đối tượng thuê và tích hợp danh tính. Nó cũng bao gồm các bước để cung cấp nền tảng cho các dịch vụ triển khai như Exchange Online, SharePoint Online và nhóm Microsoft, bao gồm một <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">cuộc thảo luận về bảo mật, kết nối mạng và tuân thủ</a>.  
  Triển khai cho một hoặc nhiều dịch vụ đủ điều kiện có thể bắt đầu sau khi hoàn tất việc triển khai.
</li>
</ul>  

<strong> Tích hợp danh tính </strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>Việc chuẩn bị các danh mục Active Directory tại chỗ để đồng bộ hóa với Azure Active Directory (Azure AD) bao gồm cài đặt và cấu hình Azure AD Connect (một hoặc nhiều-rừng) và cấp phép (bao gồm các cấp độ dựa trên nhóm).</li>
<li>Tạo các danh tính đám mây bao gồm nhập hàng loạt và cấp phép bao gồm sử dụng cấp phép dựa trên nhóm.</li>
<li>Chọn và bật phương pháp xác thực đúng cho cuộc hành trình đám mây, đồng bộ hóa hash mật khẩu, thông qua xác thực hoặc dịch vụ liên kết Active Directory (AD FS).</li>
<li>Bật AD FS cho khách hàng bằng một cụm máy chủ và danh mục Active Directory được đồng bộ hóa với công cụ Azure AD Connect. Điều này yêu cầu Windows Server 2012 R2 Active Directory Federation Services 2,0 hoặc cao hơn.</li>
<li>Di chuyển xác thực từ AD FS thành Azure AD bằng cách sử dụng đồng bộ hóa hash mật khẩu hoặc thông qua xác thực.</li>
<li>Di chuyển các ứng dụng được tích hợp sẵn (chẳng hạn như các ứng dụng của Azure AD Gallery-as-a-Service (SaaS) từ AD FS vào Azure AD cho đăng nhập đơn (SSO).</li>
<li>Bật tính năng tích hợp ứng dụng SaaS với SSO từ bộ sưu tập Azure AD.</li>
<li>Kích hoạt tính năng cung cấp người dùng tự động cho các ứng dụng SaaS được tích hợp sẵn như được liệt kê trong <a href="https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list">danh sách hướng dẫn tích hợp ứng dụng</a> (giới hạn trong Azure AD bộ sưu tập các ứng dụng Saas và cung cấp lên ngoài).  </li>
</td>

<td>  <strong>Enablement mạng </strong>  
  <br>Là một phần của lợi ích FastTrack, chúng tôi khuyên bạn là cách thực hành tốt nhất để kết nối với các dịch vụ điện toán đám mây để đảm bảo mức hiệu suất cao nhất của Microsoft 365.  
  
<strong>Rừng Active Directory</strong> Những hàm này có mức độ rừng chức năng được đặt thành Windows Server 2003 trở đi, với cấu hình rừng sau đây:
<ul>
<li>  Một cụm nhánh Active Directory duy nhất.  </li>
<li>  Một khu rừng tài khoản Active Directory và rừng tài nguyên (Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business).  </li>
<li>  Nhiều rừng tài khoản Active Directory và rừng tài nguyên (Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business).  </li>
<li>  Nhiều rừng tài khoản Active Directory với một trong các khu rừng là một trong các khu rừng tài khoản Active Directory tập trung bao gồm Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business.  </li>
<li>  Nhiều rừng tài khoản Active Directory với tổ chức Exchange của riêng mình.  </li>
<li>  Nhiệm vụ được yêu cầu cho cấu hình đối tượng thuê và tích hợp với Azure Active Directory, nếu cần thiết.   </li>
</ul>
  <strong>Quan</strong>  <ul>
<li>  Đối với các kịch bản Active Directory nhiều rừng, nếu Lync 2010, Lync 2013 hoặc Skype for Business được triển khai, nó phải được triển khai trong cùng một khu vực Active Directory như Exchange.  </li>
<li>  Khi thực hiện nhiều rừng Active Directory với nhiều tổ chức Exchange trong một cấu hình đa hỗn hợp của Exchange, tên chính của người dùng được chia sẻ (UPN) không được hỗ trợ giữa các khu rừng nguồn không được hỗ trợ. Không gian tên SMTP chính giữa các tổ chức Exchange cũng nên được phân tách. Để biết thêm thông tin, hãy xem <a href="https://go.microsoft.com/fwlink/?linkid=845444">triển khai kết hợp với nhiều khu rừng Active Directory</a>.  </li>
<li>  Đối với tất cả các cấu hình rừng, Dịch vụ liên kết Active Directory (AD FS) sẽ vượt quá phạm vi. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ứng dụng Microsoft 365</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn triển khai từ xa cho:
<ul>
<li>  Giải quyết các vấn đề về triển khai.  </li>
<li>  Gán giấy phép người dùng cuối và dựa trên thiết bị bằng cách dùng Trung tâm quản trị Microsoft 365 và Windows PowerShell.  </li>
<li>  Cài đặt các ứng dụng Microsoft 365 từ cổng thông tin Office 365 bằng Click-to-run.  </li>
<li>  Cài đặt các ứng dụng Office Mobile (chẳng hạn như Outlook Mobile, Word Mobile, Excel Mobile và PowerPoint Mobile) trên thiết bị chạy iOS hoặc Android của bạn.  </li>
<li>  Cấu hình thiết đặt Cập Nhật bằng công cụ triển khai Office 365.  </li>
<li>  Lựa chọn và thiết lập một bản cài đặt cục bộ hoặc điện toán đám mây.  </li>
<li>  Tạo XML cấu hình công cụ triển khai Office với công cụ tùy chỉnh Office hoặc XML bản địa để cấu hình gói triển khai.  </li>
<li>  Triển khai bằng trình quản lý cấu hình Microsoft Endpoint, bao gồm hỗ trợ khi tạo gói trình quản lý Microsoft Endpoint Configuration Manager.  
  Ngoài ra, nếu bạn có một macro hoặc phần bổ trợ đã làm việc với các phiên bản trước của Office và bạn trải nghiệm các vấn đề tương thích, chúng tôi cung cấp hướng dẫn khắc phục sự cố tương thích mà không cần phải có chi phí bổ sung thông qua chương trình đảm bảo ứng dụng. Xem <strong>ứng dụng đảm bảo</strong> phần của <a href="#windows-10">Windows 10</a> để biết thêm chi tiết. </li>
</ul></td>
<td><ul>
<li>  Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Mạng lưới y tế</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa với việc thu thập và diễn giải các dữ liệu kết nối mạng quan trọng từ môi trường của bạn cho thấy cách căn chỉnh các site của tổ chức của bạn là các <a href="https://docs.microsoft.com/office365/enterprise/office-365-network-connectivity-principles">nguyên tắc kết nối mạng của</a>Microsoft. Thao tác này làm nổi bật điểm số mạng mà hiệu quả di chuyển vận tốc trực tiếp, trải nghiệm người dùng, hiệu suất dịch vụ và độ tin cậy.  
  Chúng tôi cũng hướng dẫn bạn qua mọi bước khắc phục được tô sáng bởi dữ liệu này để giúp bạn cải thiện điểm số mạng của bạn.  </td>
<td><ul>
<li>  Truy nhập trung tâm quản trị Microsoft 365.  </li>
<li>  Các phiên bản Cập Nhật của ứng dụng Microsoft 365 là bắt buộc.  </li>
<li>  Dịch vụ vị trí được kích hoạt theo <a href="https://docs.microsoft.com/Office365/Enterprise/office-365-network-mac-perf-overview">đề xuất hiệu suất mạng trong Trung tâm quản trị Microsoft 365 (bản xem trước)</a>.  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Đối với Exchange Online, chúng tôi hướng dẫn bạn qua quy trình để giúp tổ chức của bạn sẵn sàng sử dụng email. Các bước chính xác tùy thuộc vào môi trường nguồn của bạn và các kế hoạch di chuyển email của bạn.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Thiết lập các tính năng của Exchange Online Protection (EOP) cho tất cả các miền được hỗ trợ thư trong Office 365.  </li>
<li>  Chỉ định bản ghi thư Exchange (MX) của bạn vào Office 365.  </li>
<li>  Thiết lập tính năng Office 365 ATP nếu đó là một phần của dịch vụ đăng ký của bạn. Để biết thêm thông tin, hãy xem phần <strong>bảo vệ mối đe dọa nâng cao của Office 365</strong> của bảng này.  </li>
<li>  Thiết lập tính năng ngăn ngừa mất dữ liệu (cho tất cả các tên miền được hỗ trợ trong Office 365 như một phần của dịch vụ đăng ký của bạn. Việc này sẽ được thực hiện sau khi các bản ghi MX trỏ đến Office 365.  </li>
<li>  Thiết lập mã hóa thư Office 365 (OME) cho tất cả các miền hỗ trợ thư được xác nhận trong Office 365 như một phần của dịch vụ đăng ký của bạn. Việc này sẽ được thực hiện sau khi các bản ghi MX trỏ đến Office 365.  </li>
</ul>
  <strong>Lưu ý:</strong> Dịch vụ nhân bản hộp thư (MRS) nỗ lực để di chuyển email được quản lý quyền thông tin (IRM) từ hộp thư tại chỗ của bạn đến hộp thư Exchange Online tương ứng. Khả năng đọc nội dung được bảo vệ-di chuyển tùy thuộc vào ánh xạ khách hàng và sao chép các mẫu dịch vụ quản lý quyền Active Directory (AD RMS) vào dịch vụ quản lý quyền Azure (Azure RMS).  
<ul>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Thiết lập DNS, bao gồm tự động phát hiện tự động, khung chính sách người gửi (SPF), DomainKeys được xác định là thư (TKIM), xác thực thư dựa trên miền, báo cáo và phù hợp (trong các bản ghi DNS) và MX (nếu cần thiết).  </li>
<li>  Thiết lập dòng email giữa môi trường nhắn tin nguồn của bạn và Exchange Online (nếu cần thiết).  </li>
<li>  Thực hiện di chuyển thư từ môi trường nhắn tin nguồn của bạn sang Office 365.  </li>
<li>  Đặt cấu hình máy khách hộp thư (Outlook cho Windows, Outlook trên web và Outlook for iOS và Android).  </li>
</ul>
  <strong>Di chuyển dữ liệu</strong>  <br>
Để biết thông tin về cách sử dụng lợi ích FastTrack để di chuyển dữ liệu sang Office 365, hãy xem <a href="https://review.docs.microsoft.com/fasttrack/data-migration">di chuyển dữ liệu</a>.   
<td>  Môi trường nguồn của bạn phải có một trong các mức tối thiểu sau đây:
<ul>
<li>  Một hoặc nhiều tổ chức Exchange với Exchange Server 2003 trở đi.  </li>
<li>  Môi trường email có khả năng truy nhập thông điệp Internet đơn (IMAP).  </li>
<li>  Một môi trường G Suite đơn (Gmail, danh bạ và lịch chỉ).  </li>
<li>  Để biết thông tin về các khả năng đa địa lý, hãy xem các chức <a href="https://go.microsoft.com/fwlink/?linkid=872776">năng đa địa lý trong Exchange Online</a>.  </li>
</ul>
Phần mềm máy khách trực tuyến như Project for Office 365, Outlook for Windows, Outlook for iOS và Android, OneDrive for Business Sync Client, Power BI trên máy tính và Skype for Business phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 Office</a>.  </td>
</tr>
<tr class="even">
<td><strong>Quản trị thông tin Microsoft</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Quản trị thông tin.  </li>
<li>  Các nhãn và chính sách duy trì.  </li>
<li>  Quản lý bản ghi.  </li>
<li>  Xóa chính sách.  </li>
<li>  Tuân thủ liên lạc.  </li>
<li>  Quản lý rủi ro người dùng nội bộ.  </li>
<li>  Khám phá điện tử nâng cao.  </li>
</ul></td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ thông tin của Microsoft</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Phân loại dữ liệu.  </li>
<li>  Các kiểu thông tin nhạy cảm.  </li>
<li>  Tạo nhãn nhạy cảm.  </li>
<li>  Áp dụng nhãn nhạy cảm.  </li>
<li>  Ghi nhãn hợp nhất.  </li>
<li>  Trainable classifiers.  </li>
<li>  Biết dữ liệu của bạn với nội dung Explorer và hoạt động Explorer.  </li>
<li>  Phát hành nhãn bằng chính sách (thủ công và tự động).  </li>
<li>  Tạo các chính sách ngăn ngừa mất dữ liệu cho các cuộc trò chuyện và kênh của Microsoft.  </li>
</ul></td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>
<tr class="even">
<td><strong>Nhóm Microsoft</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Xác nhận yêu cầu tối thiểu trong Exchange Online, SharePoint Online, các nhóm Office 365 và Azure AD để hỗ trợ nhóm.  </li>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Thiết lập DNS.  </li>
<li>  Nhóm xác nhận được kích hoạt trên đối tượng thuê Office 365 của bạn.  </li>
<li>  Bật hoặc tắt giấy phép người dùng.  </li>
<li>  Đánh giá mạng cho các Nhóm:
<ul>
<li>  Cổng và kiểm tra điểm cuối.  </li>
<li>  Kiểm tra chất lượng kết nối.  </li>
<li>  Ước tính băng thông.  </li>
</ul>
<ul>
<li>  Cấu hình chính sách ứng dụng nhóm (nhóm Web App, ứng dụng các nhóm trên máy tính và nhóm cho ứng dụng iOS và Android).  </li>
</ul>
Nếu áp dụng, chúng tôi cũng cung cấp hướng dẫn cho:
<ul>
<li>  Thiết bị phòng Microsoft Nhóm:  </li>
</ul>
<ul>
<li>  Tạo tài khoản trực tuyến cần thiết cho điện thoại được hỗ trợ và thiết bị phòng hội thảo được liệt kê trong <a href="https://go.microsoft.com/fwlink/?linkid=2066478">danh mục thiết bị nhóm</a>.  </li>
</ul>
<ul>
<li>  Bật hội thảo âm thanh:  </li>
</ul>
<ul>
<li>  Thiết lập tổ chức thiết đặt mặc định cho cầu nối hội thảo.  </li>
<li>  Phân công cầu nối hội thảo cho người dùng được cấp phép.  </li>
</ul>
<ul>
<li>  Hệ thống điện thoại:
<ul>
<li>  Thiết lập tổ chức cho thiết đặt mặc định bằng giọng nói trên đám mây.  </li>
<li>  Hướng dẫn về hoạch định cuộc gọi (<a href="https://go.microsoft.com/fwlink/?linkid=2066478">thị trường hiện có</a>):
<ul>
<li>  Gán số cho người dùng được cấp phép.  </li>
<li>  Số nội bộ porting hướng dẫn thông qua giao diện người dùng (UI) lên đến 999.  </li>
<li>  Dịch vụ số nội bộ porting (SR) hỗ trợ qua 999.  </li>
</ul></li>
<li>  Hướng dẫn định tuyến trực tiếp:
<ul>
<li>  Hướng dẫn thiết lập tổ chức để thiết kế định tuyến trực tiếp các tình huống được lưu trữ đối tác hoặc các tình huống được triển khai của khách hàng cho một trang duy nhất.  </li>
</ul></li>
</ul></li>
<li>  Cho phép các sự kiện trực tiếp của nhóm.  </li>
<li>  Thiết lập và tích hợp tổ chức vào Microsoft Stream.  </li>
</ul></td>
<td><ul>
<li>  Các danh tính được kích hoạt trong Azure AD cho Office 365.  </li>
<li>  Người dùng được kích hoạt cho SharePoint Online.  </li>
<li>  Hộp thư Exchange đang trình bày (trực tuyến và tại cơ sở trong cấu hình Exchange hỗn hợp).  </li>
<li>  Đã bật cho các nhóm Office 365.  </li>
</ul>
  <strong>Lưu ý:</strong>   Nếu người dùng không được gán và được bật với giấy phép SharePoint Online, họ sẽ không có OneDrive for Business lưu trữ trong Office 365. Chia sẻ tệp tiếp tục làm việc trong các kênh nhưng người dùng không thể chia sẻ tệp trong các cuộc trò chuyện mà không cần lưu trữ OneDrive for Business trong Office 365. Các nhóm không hỗ trợ SharePoint tại chỗ.  <br>
  <strong>Lưu ý:</strong>   Trạng thái lý tưởng dành cho tất cả người dùng có hộp thư của họ được lưu trữ trên Exchange Online. Người dùng có hộp thư được định vị tại chỗ phải có các danh tính của họ được đồng bộ hóa với thư mục Office 365 thông qua Azure AD Connect. Đối với những khách hàng hỗn hợp Exchange này, nếu hộp thư của người dùng tại chỗ, người dùng không thể thêm hoặc cấu hình các đường kết nối.  
  Các bản cài đặt cho máy khách Microsoft nhóm Windows và máy Mac có thể được tải xuống từ đó  <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ mối đe dọa nâng cao của Office 365 (ATP)</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Bật các liên kết an toàn, tệp đính kèm an toàn và chống lừa đảo.  </li>
<li>  Cấu hình tự động hóa, điều tra và phản hồi.  </li>
<li>  Sử dụng trình mô phỏng tấn công.  </li>
<li>  Báo cáo và phân tích mối đe dọa.  </li>
</ul></td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>
<tr class="even">
<td><strong>Outlook for iOS và Android</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Tải xuống Outlook for iOS và Android từ Apple App Store và Google Play.  </li>
<li>  Cấu hình tài khoản và truy nhập vào hộp thư Exchange Online.  </li>
<li>  Bảo vệ Outlook Mobile (xem mục bảo <a href="https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">vệ Outlook for iOS và Android trong Exchange Online</a> để biết thêm thông tin).  </li>
</ul></td>
<td><ul>
<li>  Các danh tính được kích hoạt trong Azure AD cho Office 365.  </li>
<li>  Đã gán cấu hình và giấy phép Exchange Online.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Gán giấy phép Power BI.  </li>
<li>  Triển khai ứng dụng Power BI trên máy tính.  </li>
</ul></td>
<td>Phần mềm máy khách trực tuyến như Power BI trên máy tính phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
</tr>
<tr class="even">
<td><strong>Dự án trực tuyến</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Xác minh chức năng SharePoint cơ bản mà dự án trực tuyến dựa vào.  </li>
<li>  Thêm dịch vụ dự án trực tuyến vào đối tượng thuê của bạn (bao gồm thêm đăng ký cho người dùng).  </li>
<li>  Thiết lập hồ bơi tài nguyên doanh nghiệp (ERP).  </li>
<li>  Tạo dự án đầu tiên của bạn.  </li>
</ul></td>
<td>Phần mềm máy khách trực tuyến như Project for Office 365 phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional và Premium</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Giải quyết các vấn đề về triển khai.  </li>
<li>  Gán giấy phép người dùng cuối bằng cách dùng Trung tâm quản trị Microsoft 365 và Windows PowerShell.  </li>
<li>  Cài đặt máy khách trên máy tính Project Online từ cổng thông tin Office 365 bằng cách sử dụng click-to-run.  </li>
<li>  Cấu hình thiết đặt Cập Nhật bằng công cụ triển khai Office 365.  </li>
<li>  Thiết lập máy chủ phân phối trên site đơn cho máy khách Project Online trên máy tính, bao gồm hỗ trợ khi tạo tệp configuration.xml để dùng với công cụ triển khai Office 365.  </li>
<li>  Kết nối Project Online trên máy khách để dự án Online Professional hoặc Project Online Premium.  </li>
</ul></td>
<td>Phần mềm máy khách trực tuyến như Project for Office 365 phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
</tr>
<tr class="even">
<td><strong>SharePoint Online và OneDrive for Business</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Thiết lập DNS.  </li>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Cung cấp người dùng và giấy phép.  </li>
<li>Bật tính năng tạo trang cho người quản trị SharePoint Online của bạn.</li>
<li>Lập kế hoạch cho tuyển tập site.</li>
<li>Đảm bảo nội dung và quản lý quyền.</li>
<li>Cấu hình các tính năng của SharePoint Online.</li>
<li>  Cấu hình các tính năng hỗn hợp của SharePoint, như tìm kiếm hỗn hợp, các site hỗn hợp, phân loại hỗn hợp, kiểu nội dung, tạo kết hợp trang tự phục vụ (chỉ SharePoint Server 2013), công cụ khởi động ứng dụng mở rộng, kết hợp onedrive for Business và site bên ngoài nơi.  </li>
<li>  Phương pháp di chuyển của bạn.  </li>
</ul>
Hướng dẫn bổ sung được cung cấp cho OneDrive for Business tùy thuộc vào phiên bản SharePoint của bạn, chẳng hạn như:
<ul>
<li>  Xác định các tùy chọn tích hợp và rà soát cơ sở hạ tầng và mạng lưới trực tuyến và băng thông.  </li>
<li>  Cài đặt SharePoint Online 2013 SP1 (nếu có), lập kế hoạch và thực hiện các yêu cầu đồng bộ và danh tính và xác định máy khách đồng bộ OneDrive for Business của bạn.  </li>
<li>  Lập kế hoạch và triển khai một lần phát hành đơn cho tất cả người dùng (hoặc giới thiệu về giới hạn).  </li>
<li>  Gán giấy phép, chuyển hướng các site và thư viện tài liệu cá nhân của tôi sang Office 365 (áp dụng cho SharePoint Online 2013), thiết lập khán giả để kiểm soát quyền truy nhập vào OneDrive (áp dụng cho SharePoint Online 2013).  </li>
<li>Chuyển hướng hoặc di chuyển các thư mục đã biết đến OneDrive.</li>
<li>  Triển khai đồng bộ hóa máy khách OneDrive for Business.  </li>
</ul>
  <strong>Di chuyển dữ liệu</strong>  <br>
Để biết thông tin về cách sử dụng lợi ích FastTrack để di chuyển dữ liệu sang Office 365, hãy xem <a href="https://review.docs.microsoft.com/fasttrack/data-migration">di chuyển dữ liệu</a>.
</ul></td>
<td><br><strong>Đối với SharePoint Hybrid:</strong>  
<ul>
<li>  Cấu hình hỗn hợp SharePoint bao gồm cấu hình tìm kiếm hỗn hợp, site, phân loại, kiểu nội dung, onedrive for Business, công cụ khởi động ứng dụng mở rộng, site bên ngoài nơi và việc tạo trang tự phục vụ được kết nối từ tại chỗ đến môi trường SharePoint Online.  </li>
</ul>
  <strong>Lưu ý:</strong> Tạo trang web tự phục vụ không có trong phạm vi với máy chủ tại cơ sở chạy SharePoint 2013.  
<ul>
<li>  Để bật SharePoint Hybrid, bạn phải có một trong những môi trường SharePoint Server tại cơ sở sau: 2013, 2016, hoặc 2019.  </li>
</ul>
  <strong>Lưu ý:</strong> Nâng cấp môi trường SharePoint tại cơ sở sang SharePoint Server không nằm trong phạm vi. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp. Để biết thêm thông tin, hãy xem các <a href="https://go.microsoft.com/fwlink/?linkid=853548">mức Cập Nhật công khai tối thiểu cho các tính năng của SharePoint Hybrid</a><em>.</em>  <br>
  <strong>Lưu ý:</strong> Để biết thông tin về các khả năng đa địa lý, hãy xem các chức <a href="https://go.microsoft.com/fwlink/?linkid=831056">năng đa địa lý trong OneDrive và SharePoint Online trong Office 365</a><em>.</em>  </td>
</tr>
<tr class="odd">
<td><strong>Skype for Business Online</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Cấu hình cổng tường lửa.  </li>

<li>  Thiết lập DNS.  </li>
<li>  Đánh giá mạng:
<ul>
<li>  Cổng và kiểm tra điểm cuối.  </li>
<li>  Kiểm tra chất lượng kết nối.  </li>
<li>  Ước tính băng thông.  </li>
</ul></li>
<li>  Tạo tài khoản cho bất kỳ thiết bị hệ thống phòng nào.  </li>
<li>  Triển khai ứng dụng khách Skype for Business Online được hỗ trợ.  </li>
<li>  Thiết lập cấu hình máy chủ tên miền giữa các Lync 2010 tại cơ sở của bạn, Lync 2013, hoặc Skype for Business 2015 môi trường máy chủ và Skype for Business Online đối tượng thuê (nếu có), gọi các gói, Skype Meeting Broadcast và hệ thống điện thoại và gọi kế hoạch (trong thị trường sẵn có).  
  Nếu có thể áp dụng, FastTrack cũng hướng dẫn bạn qua:  </li>
<li>  Cấu hình thiết bị hệ thống phòng:
<ul>
<li>  Việc tạo tài khoản trực tuyến cần thiết cho các thiết bị phòng hội thảo được hỗ trợ được liệt kê trên tab Hệ thống phòng họp trong <a href="https://go.microsoft.com/fwlink/?LinkId=615775">danh mục các giải pháp Skype for Business</a>.  </li>
</ul></li>
<li>  Cấu hình máy chủ tên miền hỗn hợp và phân tách.  </li>
<li>  Cấu hình hội thảo âm thanh:
<ul>
<li>  Thiết lập tổ chức thiết đặt mặc định cho cầu nối hội thảo.  </li>
<li>  Phân công cầu nối hội thảo cho người dùng được cấp phép.  </li>
</ul></li>
<li>  Cấu hình thiết đặt mặc định hệ thống điện thoại:
<ul>
<li>  Các gói đang gọi:
<ul>
<li>  Gán số cho những người dùng giấy phép.  </li>
<li>  Số nội bộ porting hướng dẫn thông qua giao diện người dùng lên đến 99  </li>
<li>  Dịch vụ số nội bộ porting hỗ trợ qua 999  </li>
</ul></li>
</ul></li>
<li>  Đặt cấu hình phát rộng cuộc họp Skype for Business:
<ul>
<li>  Thiết lập tổ chức cho liên kết với dịch vụ phát rộng cuộc họp.  </li>
</ul></li>
</ul></td>
<td>  <strong>Đối với Lync Hybrid:</strong>  
<ul>
<li>  Một cụm nhánh Active Directory tại cơ sở.  </li>
<li>  Môi trường máy chủ Lync 2010 với công cụ quản trị Lync 2013 hoặc công cụ quản trị Skype for Business 2015 và vai trò máy chủ Lync 2010 Edge.  </li>
<li>  Môi trường máy chủ Lync 2013 và vai trò máy chủ Lync 2013 Edge.  </li>
</ul>
  <strong>Đối với Skype for Business Hybrid:</strong>  
<ul>
<li>  Một cụm nhánh Active Directory tại cơ sở.  </li>
<li>  Một tài khoản một Active Directory Forest đã trở đi và rừng tài nguyên (Exchange và/hoặc Skype for Business).  </li>
<li>  Nhiều rừng tài khoản Active Directory, với một khu rừng là một khu rừng tài khoản Active Directory tập trung với Exchange và/hoặc Skype for Business trong đó.  </li>
<li>  Môi trường máy chủ Skype for Business 2015 bao gồm vai trò máy chủ Skype for Business Edge.  </li>
</ul>
  <strong>Lưu ý:</strong> Dịch vụ bổ sung này là để cấu hình và phê chuẩn các nhiệm vụ của miền tách (hỗn hợp) và không đưa vào các cấu phần tại cơ sở (ví dụ, công cụ quản trị Lync 2013 hoặc Lync 2013/Skype dành cho các máy chủ trực tuyến, hoặc Lync 2010, Lync 2013 hoặc Skype for Business Edge Servers).  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td><ul>
Chúng tôi cung cấp hướng dẫn từ xa để cho phép Dịch vụ yammer Enterprise.  
</ul></td>
<td>Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Bảo mật & di động của doanh nghiệp

<table>
<thead>
</tr>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) và Azure AD Premium</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa để bảo vệ danh tính đám mây của bạn cho các kịch bản sau đây.  

</ul> 
 
<strong>Cơ sở hạ tầng tổ chức bảo mật</strong>  </ul>
<ul>
<li>  Cấu hình và bật xác thực mạnh cho các danh tính của bạn, bao gồm việc bảo vệ bằng Azure xác thực đa yếu tố (MFA) (chỉ dành cho điện toán đám mây), ứng dụng Microsoft Authenticator và đăng ký kết hợp cho Azure MFA và đặt lại mật khẩu tự phục vụ (SSPR).  </li>
<li>  Đối với khách hàng không phải Azure AD Premium, hướng dẫn được cung cấp để bảo mật danh tính của bạn bằng cách sử dụng mặc định bảo mật.  </li>
<li>  Đối với khách hàng Azure AD Premium, hướng dẫn được cung cấp để bảo vệ danh tính của bạn với quyền truy nhập có điều kiện.  </li>
<li>  Phát hiện và ngăn chặn việc sử dụng mật khẩu yếu với bảo vệ bằng mật khẩu Azure AD.  </li>
<li>  Việc truy nhập từ xa vào các ứng dụng web tại cơ sở với Azure AD Application proxy.  </li>
<li>  Cho phép phát hiện và khắc phục dựa trên khả năng bảo vệ căn cước Azure.  </li>
<li>  Bật màn hình đăng nhập tùy chỉnh, bao gồm Logo, văn bản và hình ảnh với thương hiệu tùy chỉnh.  </li>
<li>  Các ứng dụng và dịch vụ chia sẻ an toàn với người dùng khách bằng cách sử dụng Azure AD B2B.  </li>
<li>  Quản lý quyền truy nhập cho người quản trị Office 365 của bạn bằng cách sử dụng các vai trò quản trị dựa trên vai trò (RBAC) được dựng sẵn và giảm số lượng tài khoản quản trị đặc quyền.  </li>
<li>  Cấu hình kết hợp Azure AD join.  </li>
<li>  Đặt cấu hình Azure AD join.  </li>
</ul>
  
<strong>Giám sát và báo cáo</strong>  
<ul>
<li>  
  Bật giám sát từ xa cho AD FS, Azure AD Connect và bộ điều khiển tên miền với Azure AD Connect Health.  
  </li>
</ul>
  
<strong>Nhà</strong>  
<ul>
<li>  
  Quản lý danh tính Azure AD của bạn và vòng đời Access với Thang quản lý lợi quyền Azure AD.
  </li>
<li>  
  Quản lý tư cách thành viên nhóm Azure AD, truy nhập ứng dụng doanh nghiệp và gán vai trò với Azure AD Access.  
  </li>
<li>  
  Xem lại các điều khoản sử dụng của Azure AD.  
  </li>
<li>  
  Quản lý và kiểm soát quyền truy nhập vào các tài khoản quản trị đặc quyền có quản lý căn cước có đặc quyền Azure AD.  
  </li>
</ul>
  
<strong>Tự động hóa và hiệu quả </strong>  
<ul>
<li>  
  Bật Azure AD SSPR.  
  </li>
<li>  Cho phép người dùng tạo và quản lý các nhóm điện toán đám 365 mây riêng của họ với Azure AD self-quản lý nhóm dịch vụ.  </li>
<li>  Quản lý quyền truy nhập được ủy nhiệm cho các ứng dụng doanh nghiệp với Azure AD được ủy nhiệm quản lý nhóm.  </li>
<li>  Kích hoạt các nhóm động Azure AD.  </li>
<li>  Tổ chức các ứng dụng trong cổng thông tin ứng dụng của tôi bằng bộ sưu tập.  </li>
</ul></td>
<td>Active Directory tại chỗ và môi trường của nó đã được chuẩn bị sẵn sàng cho Azure AD Premium, bao gồm việc khắc phục các vấn đề đã xác định ngăn chặn việc tích hợp với Azure AD và Azure AD Premium.</td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ thông tin Azure (P2 hoặc EMS E5)</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn về cách:
<ul>
<li>  Kích hoạt và cấu hình đối tượng thuê của bạn.  </li>
<li>  Tạo và thiết lập nhãn và chính sách.  </li>
<li>  Áp dụng bảo vệ thông tin cho tài liệu.  </li>
<li>  Tự động phân loại và thông tin nhãn trong các ứng dụng Office (chẳng hạn như Word, PowerPoint, Excel và Outlook) đang chạy trên Windows và sử dụng máy khách bảo vệ thông tin Azure.  </li>
<li>  Sử dụng tệp tại phần còn lại bằng cách dùng máy quét bảo vệ thông tin Azure.  </li>
<li>  Theo dõi email trong quá cảnh bằng quy tắc dòng thư Exchange Online.  </li>
</ul>
Chúng tôi cũng cung cấp hướng dẫn nếu bạn muốn áp dụng bảo vệ bằng cách sử dụng dịch vụ quản lý quyền Microsoft Azure (Azure RMS), mã hóa thư Office 365 (OME), và ngăn chặn mất dữ liệu ().  </td>
<td>  Bạn đã phải:
<ul>
<li>  Sử dụng Azure AD.  </li>
<li>  Sử dụng Windows hoặc iOS (các hệ điều hành khác nằm ngoài phạm vi).  
  </ul>
<strong>Lưu ý</strong>: máy tính và thiết bị di động phải chạy trên một <a href="https://docs.microsoft.com/azure/information-protection/requirements#client-devices">hệ điều hành</a> có hỗ trợ bảo vệ thông tin Azure.  
<li>  Có vị trí chia sẻ tệp chính của bạn.  </li>
<strong>Lưu ý</strong>: hỗ trợ hỗn hợp yêu cầu trình kết nối AD RMS. 
<li>  Có phân loại phân loại được phê duyệt.  </li>
<li>  Hiểu mọi hạn chế về quy định cho việc quản lý khóa được bảo vệ của bạn.  </li>
</ul>
  
<strong>Máy quét bảo vệ thông tin Azure</strong>  
  
Bạn đã phải:  
<ul>
<li>  Sử dụng Windows Server 2012 R2 hoặc Windows Server 2016.  </li>
<li>  Có kết nối Internet.  </li>
<li>  Có Microsoft SQL Server 2012 trở đi trong một ví dụ địa phương hoặc từ xa.  </li>
<li>  Có tài khoản Dịch vụ được tạo cho Active Directory tại cơ sở của bạn và được đồng bộ hóa với Azure AD.  </li>
<li>  Đã tải xuống AzInfoProtection.exe.  </li>
<li>  Có các nhãn được đặt cấu hình để phân loại tự động/bảo vệ.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Microsoft InTune</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn về việc sẵn sàng để sử dụng InTune là nhà cung cấp dịch vụ thiết bị di động trên nền tảng điện toán đám mây (MDM) và cơ quan quản lý ứng dụng di động (MAM) cho các ứng dụng và thiết bị của bạn. Các bước chính xác tùy thuộc vào môi trường nguồn của bạn và dựa trên thiết bị di động của bạn và các nhu cầu quản lý ứng dụng di động. Các bước có thể bao gồm:
<ul>
<li>  Cấp phép người dùng cuối của bạn.  </li>
<li>  Cấu hình các định danh được sử dụng bởi InTune bằng cách tận dụng một trong các Active Directory tại chỗ của bạn hoặc danh tính đám mây (Azure AD).  </li>
<li>  Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.  </li>
<li>  Đặt cấu hình cơ quan MDM của bạn, dựa trên nhu cầu quản lý của bạn, bao gồm:
<ul>
<li>  Thiết đặt InTune làm cơ quan MDM của bạn khi InTune là giải pháp MDM duy nhất của bạn.  </li>
</ul></li>
<li>  Cung cấp hướng dẫn MDM cho:
<ul>
<li>  Cấu hình các nhóm kiểm tra để được dùng để xác thực các chính sách quản lý MDM.  </li>
<li>  Cấu hình chính sách và dịch vụ quản lý MDM như:
<ul>
<li>  Triển khai ứng dụng cho từng nền tảng được hỗ trợ thông qua các nối kết web hoặc nối kết sâu.  </li>
<li>  Chính sách truy nhập có điều kiện.  </li>
<li>  Việc triển khai các hồ sơ email, mạng không dây và VPN) nếu bạn có một cơ quan cấp chứng chỉ hiện có, cơ sở hạ tầng mạng không dây hoặc VPN trong tổ chức của bạn.  </li>
<li>  Thiết lập trình kết nối Exchange của Microsoft InTune (khi áp dụng).  </li>
<li>  Kết nối với kho dữ liệu InTune.  </li>
<li>  Đang tích hợp InTune với:
<ul>
<li>  Trình xem nhóm để được hỗ trợ từ xa (đăng ký trình xem nhóm là bắt buộc).  </li>
<li>  Các giải pháp đối tác thoại di động Threat Defense (MTD) (một gói đăng ký MTD là bắt buộc).  </li>
<li>  Một giải pháp quản lý chi phí viễn thông (đăng ký giải pháp quản lý chi phí viễn thông là bắt buộc).  </li>
<li>  Microsoft Defender ATP (các giấy phép Windows E5 hoặc Microsoft 365 E5 là bắt buộc).  </li>
</ul></li>
<li>  Các thiết bị đăng ký của mỗi nền tảng được hỗ trợ để InTune.  </li>
</ul></li>
</ul></li>
<li>  Hướng dẫn về việc bảo vệ ứng dụng về:
<ul>
<li>  Cấu hình các chính sách bảo vệ ứng dụng cho từng nền tảng được hỗ trợ.  </li>
<li>  Cấu hình chính sách truy nhập có điều kiện cho ứng dụng được quản lý.  </li>
<li>  Nhắm vào các nhóm người dùng phù hợp với các chính sách không được đề cập trước đó.  </li>
<li>  Sử dụng báo cáo sử dụng ứng dụng được quản lý.  </li>
</ul></li>
<li>  Cung cấp hướng dẫn di chuyển từ quản lý PC kế thừa sang InTune MDM.  </li>
</ul>
  <strong>Lưu ý</strong>: quản lý PC kế thừa không còn được hỗ trợ từ ngày 15 tháng 10, 2020 trở đi.  
</li>
</ul>
  
<strong>Đám mây-đính kèm</strong>  

  Chúng tôi hướng dẫn bạn đến với việc sẵn sàng cho các môi trường trình quản lý cấu hình hiện có với InTune. Các bước chính xác tùy thuộc vào môi trường nguồn của bạn. Những bước này có thể bao gồm:  
<ul>
<li>  Giải thích về các lợi ích của trình quản lý cấu hình đám mây với InTune.  </li>
<li>  Cấp phép người dùng cuối của bạn.  </li>
<li>  Cấu hình các định danh được sử dụng bởi InTune bằng cách tận dụng Active Directory tại chỗ và danh tính đám mây của bạn.  </li>
<li>  Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.  </li>
<li>  Bật tính năng đám mây trong bảng điều khiển trình quản lý cấu hình.  </li>
<li>  Việc cung cấp hướng dẫn thiết lập kết hợp Azure AD join.  </li>
<li>  Cung cấp hướng dẫn về việc thiết lập Azure AD cho MDM tự động đăng ký.  </li>
<li>  Cung cấp hướng dẫn về cách thiết lập cổng kết nối quản lý điện toán đám mây.  </li>
<li>  Cấu hình các công việc được hỗ trợ mà bạn muốn chuyển sang InTune.  </li>
<li>  Cài đặt máy khách trình quản lý cấu hình trên thiết bị đã đăng ký InTune.  </li>
</ul> 

<strong>Triển khai Outlook Mobile for iOS và Android an toàn</strong> Chúng tôi có thể cung cấp hướng dẫn để giúp bạn triển khai Outlook Mobile for iOS và Android trong tổ chức của bạn để đảm bảo người dùng của bạn đã cài đặt tất cả các ứng dụng được yêu cầu.  
  Các bước để triển khai an toàn Outlook Mobile cho iOS và Android bằng InTune tùy thuộc vào môi trường nguồn của bạn. Nó có thể bao gồm:
<ul>
<li>  Tải xuống Outlook for iOS và Android, Microsoft Authenticator và InTune Company Portal Apps thông qua ứng dụng Apple App Store hoặc Google Play Store.  </li>
<li>  Hướng dẫn về việc thiết lập:
<ul>
<li>  Outlook for iOS và Android, Microsoft Authenticator và InTune Company Portal triển khai ứng dụng với InTune.  </li>
<li>  Các chính sách bảo vệ ứng dụng.  </li>
<li>  Chính sách truy nhập có điều kiện.  </li>
<li>  Các chính sách cấu hình ứng dụng.  </li>
</ul></li>
</ul>
  
  <strong>Lưu ý</strong>: fasttrack không hỗ trợ việc bảo mật Outlook for iOS và Android với chính sách hộp thư Exchange của thiết bị di động. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.  
  </td>
<td>  Người quản trị CNTT cần có cơ quan cấp chứng chỉ hiện có, mạng không dây và hạ tầng VPN đã làm việc trong môi trường sản xuất của họ khi lập kế hoạch triển khai mạng không dây và hồ sơ VPN bằng InTune.  
  <strong>Lưu ý</strong>: lợi ích Dịch vụ fasttrack không bao gồm trợ giúp thiết lập hoặc cấu hình cơ quan cấp chứng chỉ, mạng không dây, hạ tầng VPN hoặc giấy chứng nhận đẩy táo MDM cho InTune.  

<strong>Trình quản lý cấu hình đám mây được đính kèm bằng InTune</strong>  

 Với đám mây-đính kèm, người quản trị CNTT có trách nhiệm chuẩn bị môi trường tại cơ sở. Điều này có thể bao gồm các vấn đề khắc phục sự cố ngăn cản bạn từ điện toán đám mây-đính kèm môi trường trình quản lý cấu hình của bạn với InTune.  
  <strong>Lưu ý</strong>: lợi ích của dịch vụ fasttrack không bao gồm trợ giúp thiết lập hoặc nâng cấp máy chủ site của trình quản lý cấu hình hoặc máy khách trình quản lý cấu hình đến các yêu cầu tối thiểu cần thiết để hỗ trợ đám mây-đính kèm. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.

  <strong>InTune tích hợp với bảo vệ mối đe dọa nâng cao của Microsoft Defender (ATP)</strong> 
 
  <strong>Lưu ý</strong>: chúng tôi cung cấp trợ giúp về việc tích hợp InTune với Microsoft Defender ATP và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức độ rủi ro Windows 10 của nó. Chúng tôi không cung cấp trợ giúp về việc mua, cấp phép hoặc kích hoạt. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.  
  
<strong>Windows Autopilot</strong> 
 
  Người quản trị CNTT chịu trách nhiệm đăng ký thiết bị của họ với tổ chức của họ bằng cách có nhà cung cấp phần cứng tải lên các ID phần cứng của họ thay mặt cho họ hoặc bằng cách tải nó vào dịch vụ Autopilot của Windows.  
  
<strong>Triển khai Outlook cho iOS và Android an toàn với InTune </strong>  
<ul>
<li>  Các danh tính người dùng được kích hoạt trong Azure AD cho Office 365.  </li>
<li>  Cấu hình Exchange Online hoặc Exchange Online với giấy phép người dùng được gán.  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn để giúp bạn nâng cấp từ Windows 7 Professional và Windows 8,1 Professional sang Windows 10 Enterprise.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Hiểu rõ ý định về Windows 10 của bạn.  </li>
<li>  Đánh giá môi trường nguồn của bạn và các yêu cầu (đảm bảo rằng Microsoft Endpoint Configuration Manager được nâng cấp lên mức bắt buộc để hỗ trợ triển khai Windows 10).  </li>
<li>  Triển khai Windows 10 Enterprise và ứng dụng Microsoft 365 bằng Microsoft Endpoint Configuration Manager hoặc Microsoft 365.  </li>
<li>  Đề xuất các tùy chọn cho bạn để đánh giá các ứng dụng Windows 10 của bạn.  </li>
<li>  Cho phép sử dụng phân tích máy tính để bàn và hướng dẫn thông qua việc tạo kế hoạch triển khai phân tích máy tính bàn.  </li>
<li>  Đánh giá tương thích của Microsoft 365 bằng cách tận dụng bảng điều khiển sẵn sàng của Office 365 trong trình quản lý cấu hình hoặc với bộ công cụ sẵn sàng độc lập cho Office Plus hỗ trợ triển khai ứng dụng Microsoft 365.  </li>
<li>  Đánh giá các chiến lược quản lý hiện đại của bạn, bao gồm trình quản lý cấu hình đám mây với Microsoft InTune hoặc triển khai InTune là giải pháp quản lý đám mây duy nhất.  </li>
<li>  Tạo danh sách kiểm tra khắc phục những gì bạn cần làm để mang đến môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để triển khai thành công.  </li>
<li>  Cung cấp hướng dẫn nâng cấp cho các thiết bị hiện có của bạn vào Windows 10 Enterprise nếu họ đáp ứng các yêu cầu phần cứng thiết bị cần thiết.  </li>
<li>  Cung cấp hướng dẫn nâng cấp để hỗ trợ chuyển động triển khai hiện có của bạn. FastTrack Recommends và cung cấp hướng dẫn cho việc nâng cấp tại chỗ lên Windows 10. Hướng dẫn cũng sẵn dùng cho việc cài đặt Windows sạch ảnh và các kịch bản triển khai Windows Autopilot.  </li>
<li>  Triển khai ứng dụng Microsoft 365 bằng trình quản lý cấu hình như là một phần của triển khai Windows 10.   </li>
<li>  Cung cấp hướng dẫn để giúp tổ chức của bạn luôn Cập Nhật với Windows 10 Enterprise và ứng dụng Microsoft 365 bằng môi trường trình quản lý cấu hình hiện có của bạn hoặc Microsoft 365.  </li>
<li>  Cung cấp hướng dẫn để cho phép quản lý hiện đại bằng cách gắn kết với trình quản lý cấu hình điện toán đám mây vào InTune hoặc bằng cách triển khai InTune độc lập (khi bắt buộc).  </li>
</ul>
  <strong>Sau đây là phạm vi </strong>  
<ul>
<li>  Nâng cấp trình quản lý cấu hình cho nhánh hiện tại.  </li>
<li>  Tạo hình ảnh tùy chỉnh cho triển khai Windows 10.  </li>
<li>  Tạo và hỗ trợ các tập lệnh triển khai cho quá trình triển khai Windows 10.  </li>
<li>  Chuyển đổi hệ thống Windows 10 từ BIOS sang giao diện firmware được mở rộng hợp nhất (UEFI).  </li>
<li>  Bật tính năng bảo mật của Windows 10.  </li>
<li>  Cấu hình dịch vụ triển khai Windows (WDS) để khởi động môi trường thực thi Preboot (PXE).  </li>
<li>  Sử dụng bộ công cụ triển khai Microsoft (MDT) để chụp và triển khai hình ảnh Windows 10.  </li>
<li>  Sử dụng công cụ di chuyển trạng thái người dùng (USMT).  </li>
</ul>
Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp với các dịch vụ này.  </td>
<td>  Đối với bản nâng cấp PC, bạn phải đáp ứng các yêu cầu này:
<ul>
<li>  Nguồn OS: Windows 7 Enterprise hoặc Professional, Windows 8,1 Enterprise hoặc Professional.  </li>
<li>  Thiết bị: máy tính để bàn, máy tính xách tay hoặc yếu tố biểu mẫu máy tính bảng.  </li>
<li>  Hệ điều hành target: cửa sổ 10 doanh nghiệp.  </li>
</ul>
Để nâng cấp cơ sở hạ tầng, bạn phải đáp ứng các yêu cầu này:
<ul>
<li>  Trình quản lý cấu hình Microsoft Endpoint.  </li>
<li>  Phiên bản trình quản lý cấu hình phải được hỗ trợ bởi phiên bản Windows 10 target. Để biết thêm thông tin, hãy xem bảng hỗ trợ trình quản lý cấu hình tại <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">hỗ trợ cho Windows 10 trong trình quản lý cấu hình</a>.  </li>
</ul>
<h3 id="section-1"></h3></td>
</tr>
<tr class="even">
<td><strong>Đảm bảo cho ứng dụng</strong></td>
<td>  Ứng dụng đảm bảo là một dịch vụ được thiết kế để giải quyết các sự cố với Windows 10 và ứng dụng Microsoft 365 ứng dụng tương thích. Khi bạn yêu cầu ứng dụng đảm bảo dịch vụ, chúng tôi sẽ làm việc với bạn để giải quyết các sự cố ứng dụng hợp lệ tại không có chi phí bổ sung cho bạn bằng một thuê bao đủ điều kiện. Chúng tôi cũng cung cấp hướng dẫn cho khách hàng những vấn đề tương thích khi triển khai Windows Virtual Desktop và Microsoft Edge mới.  
  Chúng tôi cung cấp hỗ trợ khắc phục các ứng dụng được triển khai trên các sản phẩm Microsoft sau đây:
<ul>
<li>  <strong>Windows 10</strong> </li>
<li> <strong>Ứng dụng Microsoft 365</strong>  </li>
<li>  <strong>Microsoft Edge mới-</strong> Để được hướng dẫn triển khai, hãy xem <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">tổng quan về các kênh Microsoft Edge</a>.  </li>
<li>  <strong>Máy tính</strong> - chạy Windows ảo Để biết thêm thông tin, hãy xem <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop là gì?</a>    <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">câu hỏi thường gặp về Windows 10 Enterprise phiên</a>.  </li>
</ul></td>
<td><strong>Ứng dụng Windows 10 và Microsoft 365</strong>
<ul>
<li>  
  Các ứng dụng đã làm việc trên Windows 7, Windows 8,1, Office 2010 và Office 2013 cũng hoạt động trên các ứng dụng Windows 10 và Microsoft 365.  
  </li>
</ul>
<strong>Microsoft Edge mới</strong>
<ul>
<li>  
  Nếu ứng dụng web hoặc site của bạn hoạt động trên Internet Explorer 11, các phiên bản Google Chrome được hỗ trợ, hoặc bất kỳ phiên bản nào của Microsoft Edge, họ cũng sẽ làm việc với Microsoft Edge mới.  
  </li>
<li>  
  Khi web không liên tục phát triển, hãy đảm bảo bạn xem lại danh sách <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">đã phát hành của tính năng tương thích trang đã biết-các thay đổi tác động đối với Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Máy tính chạy Windows ảo </strong>  
<ul>
<li>  
  Các ứng dụng ảo hóa chạy trên máy chủ lưu trữ phiên máy tính từ xa của Windows Server (RDSH) cũng chạy trên Windows 10 Enterprise Multi-session như một phần của Windows Virtual Desktop.  
  </li>
<li>  
  Các ứng dụng đang chạy trên bất kỳ môi trường cơ sở hạ tầng máy tính bàn ảo Windows 7 hoặc Windows 10 nào (VDI) cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như một phần của Windows Virtual Desktop. * </li>
<li>  
  Các ứng dụng đang chạy trên Windows 7 hoặc Windows 10 thiết bị máy khách cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như một phần của Windows Virtual Desktop. * </li>
</ul>
* Các hạn chế về tính tương thích của Windows 10 Enterprise đa phiên, bao gồm:
<ul>
<li>  
  Chuyển hướng hạn chế của phần cứng.  
  </li>
<li>  
  Ứng dụng a/V-chuyên sâu có thể thực hiện trong công suất giảm đi.  
  </li>
<li>  
  Các ứng dụng 16 bit không được hỗ trợ cho máy tính chạy Windows ảo 64 bit.  
  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ chống mối đe dọa nâng cao của Microsoft Defender (ATP)</strong></td>
<td>  Microsoft Defender Advanced Threat Protection (ATP) là một nền tảng được thiết kế để giúp ngăn chặn các mạng doanh nghiệp, phát hiện, điều tra và phản hồi các mối đe dọa nâng cao.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Triển khai công nghệ để bảo vệ điểm cuối của bạn.  </li>
<li>  Cấu hình bảo vệ điểm cuối và hồ sơ hạn chế thiết bị.  </li>
<li>  Đánh giá phiên bản hệ điều hành và quản lý thiết bị (bao gồm InTune, trình quản lý cấu hình Microsoft Endpoint, đối tượng chính sách Nhóm (GPOs) và các cấu hình của bên thứ ba cũng như trạng thái của dịch vụ AV bảo vệ Windows hoặc phần mềm bảo mật khác của điểm cuối.  </li>
<li>  Đánh giá trạng thái của các dịch vụ Windows AV hoặc phần mềm bảo mật điểm cuối khác của bạn.  </li>
<li>  Đánh giá proxy và tường lửa hạn chế lưu lượng mạng.  </li>
<li>  Bật dịch vụ ATP của Microsoft Defender bằng cách giải thích cách triển khai hồ sơ đại diện ATP bằng điểm cuối trên máy tính.  </li>
<li>  Hướng dẫn triển khai, hỗ trợ cấu hình và giáo dục về:
<ul>
<li>  
  Quản lý mối đe dọa và lỗ hổng.  
  </li>
<li>  
  Giảm bề mặt tấn công.  
  </li>
<li>  
  Bảo vệ thế hệ mới.  
  </li>
<li>  
  Endpoint phát hiện và phản hồi.  
  </li>
<li>  
  Điều tra và khắc phục sự tự động.  
  </li>
<li>  
  Điểm số bảo mật.  
  </li>
</ul></li>
<li>  Xem lại mô phỏng và hướng dẫn (chẳng hạn như kịch bản thực hành, phần mềm độc hại giả và các điều tra tự động).  </li>
<li>  Tổng quan về các tính năng của báo cáo và phân tích mối đe dọa.  </li>
<li>  Tích hợp Office 365 ATP với Microsoft Defender ATP.  </li>
<li>  Tiến hành walkthroughs của cổng thông tin bảo mật Microsoft Defender.  </li>
<li>  Các hệ điều hành sau đây:
<ul>
<li>  
  Windows 10.  
  </li>
<li>  
  Windows Server 2016.  
  </li>
<li>  
  Windows Server 2019.  
  </li>
<li>  
  Phiên bản Windows Server 2019 Core.  
  </li>
<li>  
  Phiên bản Windows Server bán hàng năm (SAC) phiên bản 1803.  
  </li>
<li>  
  Phiên bản macOS 10,13, 10,14 và 10,15.  
  </li>
</ul>
</li>
</ul>
<strong>Lưu ý:</strong> Tất cả các phiên bản Windows Server phải được quản lý bởi phiên bản mới nhất của trình quản lý cấu hình Trung tâm hệ thống 2012 (Phiên bản 1012 R2, 1511 hoặc 1602) hoặc Microsoft Endpoint Configuration Manager (Phiên bản 2002 hoặc cao hơn). 

</li>
</ul>

<strong>Sau đây là phạm vi </strong>  
<ul>
<li>  Quản lý dự án các hoạt động khắc phục của khách hàng.  </li>
<li>  Hỗ trợ trên site.  </li>
<li>  Quản lý và trả lời mối đe dọa đang diễn ra.  </li>
<li>  Onboarding hoặc cấu hình cho các đại diện ATP sau đây của Microsoft Defender:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Windows.  
  </li>
<li>  
  Thiết bị di động (Android và iOS).  
  </li>
</ul></li>
<li>  Máy chủ triển khai và cấu hình:
<ul>
<li>  
  Cấu hình máy chủ proxy cho liên lạc ngoại tuyến.  
  </li>
<li>  
  Cấu hình các gói triển khai trình quản lý cấu hình trên các phiên bản trình quản lý cấu hình xuống cấp.  
  </li>
<li>  
  Máy chủ onboarding đến Azure Security Center.  
  </li>
<li>  
  Máy chủ không do trình quản lý cấu hình quản lý.  
  </li>
</ul></li>
<li>  cài đặt và cấu hình macOS triển khai:
<ul>
<li>  
  Triển khai dựa trên thủ công theo hướng dẫn sử dụng.  
  </li>
<li>  
  Triển khai dựa trên JAMF.
  </li>
<li>  
  Triển khai dựa trên sản phẩm quản lý thiết bị di động khác (MDM).  
  </li>
<li>  
  Triển khai thủ công.  
  </li>
</ul></li>
<li>  Cấu hình các chức năng giảm bề mặt sau đây:
<ul>
<li>  
  Phân tách dựa trên phần cứng.  
  </li>
<li>  
  Điều khiển ứng dụng.  
  </li>
<li>  
  Khai thác bảo vệ.  
  </li>
<li>  
  Tường lửa mạng.  
  </li>
</ul></li>
<li>  Đăng ký hoặc cấu hình của chuyên gia đe dọa Microsoft.  </li>
<li>  Cấu hình hoặc đào tạo duyệt lại API hoặc thông tin bảo mật và quản lý sự kiện (SIEM).  </li>
<li>  Đăng ký hoặc cấu hình của Microsoft Threat Protection (MTP).  </li>
<li>  Đào tạo hoặc hướng dẫn bao phủ săn bắn nâng cao.  </li>
<li>  Đào tạo hoặc hướng dẫn bao gồm việc sử dụng hoặc tạo ra các truy vấn Kusto.</li>
</li>
</ul>
Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp với các dịch vụ này.  
</ul></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Microsoft Edge</strong> (dành cho khách hàng Windows 10 Enterprise)</td>
<td><ul>
<li>  Chúng tôi cung cấp hướng dẫn triển khai từ xa và trợ giúp tương thích cho: triển khai Microsoft Edge mới trên Windows 10 Enterprise với Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager hoặc InTune).  </li>
<li>  Cấu hình Microsoft Edge (sử dụng chính sách nhóm hoặc cấu hình ứng dụng InTune và chính sách ứng dụng).  </li>
<li>  Kiểm kê danh sách các site có thể yêu cầu dùng trong chế độ Internet Explorer.  </li>
<li>  Bật chế độ Internet Explorer với danh sách site hiện có của doanh nghiệp.  
  Ngoài ra, nếu bạn có một ứng dụng web hoặc site hoạt động với Internet Explorer hoặc Google Chrome và bạn trải nghiệm các vấn đề tương thích, chúng tôi cung cấp hướng dẫn để giải quyết sự cố mà không cần phải có thêm chi phí. Xem <strong>ứng dụng đảm bảo</strong> phần của bảng này để biết thêm chi tiết.  </li>
</ul></td>
<td></td>
</tr>
</tbody>
</table>
