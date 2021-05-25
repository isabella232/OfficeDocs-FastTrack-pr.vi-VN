---
title: Các sản phẩm và chức năng
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 5/19/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Chủ đề này bao gồm chi tiết về các kịch bản khối lượng công việc được FastTrack hỗ trợ và kỳ vọng môi trường nguồn cần thiết trước khi chúng ta có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo kế hoạch khắc phục, đưa môi trường nguồn của bạn đến các yêu cầu tối thiểu để triển năng thành công.
ms.openlocfilehash: 9a4546b248a739ee980f1300b9575e780e383c1a
ms.sourcegitcommit: 736a256276ead91385e1ec37b8a120b22259c4ea
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 05/24/2021
ms.locfileid: "52626691"
---
# <a name="products-and-capabilities"></a>Các sản phẩm và chức năng

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Dịch vụ và kịch bản được FastTrack hỗ trợ 

Chủ đề này bao gồm chi tiết về các kịch bản khối lượng công việc được FastTrack hỗ trợ và kỳ vọng môi trường nguồn cần thiết trước khi chúng ta có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo kế hoạch khắc phục, đưa môi trường nguồn của bạn đến các yêu cầu tối thiểu để triển năng thành công.

FastTrack cung cấp hướng dẫn để giúp bạn trước tiên với các chức năng cốt lõi (phổ biến với tất cả các Dịch vụ Trực tuyến của Microsoft), sau đó triển hành từng dịch vụ đủ điều kiện:

  - [Chung](#general)
  - [Bảo mật và Tuân thủ](#security-and-compliance)
  - [Office 365](#office-365)
  - [Enterprise Mobility + Security](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Windows Màn hình nền Ảo](#windows-virtual-desktop)
  - [Đảm bảo cho ứng dụng](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Để biết thông tin về các kỳ vọng về môi trường nguồn Office 365 Chính phủ Hoa Kỳ, hãy xem Kỳ vọng Môi trường [Nguồn Office 365 Chính phủ Hoa Kỳ.](/us-gov-appendix-source-environment-expectations) 
 
## <a name="general"></a>Chung

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Triển năng cốt lõi</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa về triển năng cốt lõi, bao gồm việc cung cấp dịch vụ, tích hợp đối tượng thuê và danh tính. Tài liệu cũng bao gồm các bước cung cấp nền tảng cho các dịch vụ triển tảng như Exchange Online, SharePoint Online và Microsoft Teams, bao gồm thảo luận về bảo mật, khả năng kết nối mạng và tuân <a href="/office365/enterprise/office-365-network-connectivity-principles">thủ.</a>   

Triển khai cho một hoặc nhiều dịch vụ đủ điều kiện có thể bắt đầu sau khi triển khai cốt lõi hoàn tất.
</li>
</ul>  

<strong> Tích hợp Định danh </strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>Chuẩn bị Định danh Active Directory tại chỗ để đồng bộ với Azure Active Directory (Azure AD) bao gồm cài đặt và đặt cấu hình Azure AD Kết nối (một rừng hoặc nhiều rừng) và cấp phép (bao gồm cấp phép dựa trên nhóm).</li>
<li>Tạo định danh trên đám mây bao gồm nhập và cấp phép hàng loạt, bao gồm sử dụng cấp phép dựa trên nhóm.</li>
<li>Chọn và bật phương pháp xác thực chính xác cho hành trình trên đám mây, Đồng bộ Băm Mật khẩu, Xác thực Chuyển qua hoặc Dịch vụ Liên kết Active Directory (AD FS).</li>
<li> Chọn và bật trải nghiệm xác thực thuận tiện hơn cho người dùng của bạn với xác thực không cần mật khẩu (Fast Identity Online (FIDO)2 hoặc Microsoft Authenticator App).</li>
<li>Cho phép AD FS cho khách hàng với một rừng Active Directory duy nhất và các định danh được đồng bộ hóa với công cụ azure AD Kết nối động. Điều này yêu Windows sử dụng Dịch vụ Liên kết Active Directory 2.0 trở lên Windows Server 2012 R2.</li>
<li>Di chuyển xác thực từ AD FS sang Azure AD bằng đồng bộ băm mật khẩu hoặc Xác thực thông qua.</li>
<li>Di chuyển các ứng dụng tích hợp sẵn (như ứng dụng phần mềm dưới dạng dịch vụ (SaaS) của bộ sưu tập Azure AD) từ AD FS sang Azure AD cho đăng nhập một lần (SSO).</li>
<li>Bật tích hợp ứng dụng SaaS với SSO từ bộ sưu tập Azure AD.</li>
<li>Cho phép cung cấp người dùng tự động cho các ứng dụng SaaS tích hợp sẵn như được liệt kê trong danh sách hướng dẫn tích hợp Ứng dụng <a href="/azure/active-directory/saas-apps/tutorial-list">(giới </a> hạn ở các ứng dụng SaaS bộ sưu tập Azure AD và chỉ cung cấp thư đi).  </li>

</td>

<td>  <strong>Bật mạng </strong>  
  <br>Như một phần của lợi ích FastTrack, chúng tôi khuyên bạn nên thực hành cách tốt nhất để kết nối với dịch vụ đám mây nhằm đảm bảo mức hiệu suất cao nhất của dịch vụ Microsoft 365.  
  
<strong>Rừng Active Directory</strong> Cấp độ rừng chức năng được đặt là Windows Server 2003 trở đi, với cấu hình rừng sau đây:
<ul>
<li>  Một rừng Active Directory duy nhất.  </li>
<li>  Một rừng tài khoản Active Directory và rừng tài nguyên duy nhất (Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business) .  </li>
<li>  Nhiều rừng tài khoản Active Directory và rừng tài nguyên (Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business) .  </li>
<li>  Nhiều rừng tài khoản Active Directory với một trong các rừng là một rừng tài khoản Active Directory tập trung bao gồm Exchange và/hoặc Lync 2010, Lync 2013 hoặc Skype for Business.  </li>
<li>  Nhiều rừng tài khoản Active Directory, mỗi rừng có tổ chức Exchange riêng của mình.  </li>
<li>  Các tác vụ cần thiết cho cấu hình đối tượng thuê và tích hợp với Azure Active Directory, nếu cần.   </li>
</ul>
  <strong>Quan trọng</strong>  <ul>
<li>  Đối với các kịch bản Active Directory nhiều rừng, nếu Lync 2010, Lync 2013 hoặc Skype for Business được triển khai, nó phải được triển khai trong cùng một rừng Active Directory như Exchange.  </li>
<li>  Khi thực hiện nhiều rừng Active Directory với nhiều tổ chức Exchange trong cấu hình đa kết hợp Exchange, các không gian tên chính của người dùng chung (UPN) giữa các rừng nguồn không được hỗ trợ. Không gian tên SMTP chính giữa các Exchange chính cũng cần được tách biệt. Để biết thêm thông tin, <a href="https://go.microsoft.com/fwlink/?linkid=845444">hãy xem mục Triển khai kết hợp với nhiều rừng Active Directory.</a>  </li>
<li>  Đối với tất cả các cấu hình nhiều rừng, triển khai Dịch vụ Liên kết Active Directory (AD FS) nằm ngoài phạm vi. Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về vấn đề này.  </li>
</ul></td>
</tr>
<tr class="even">
<td><strong>Ứng dụng Microsoft 365</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn triển khai từ xa cho:
<ul>
<li>  Giải quyết các vấn đề về triển khai.  </li>
<li>  Gán giấy phép dựa trên thiết bị và người dùng cuối bằng cách sử dụng trung Microsoft 365 quản trị chính và Windows PowerShell.  </li>
<li>  Cài Ứng dụng Microsoft 365 cài đặt từ Office 365 cổng thông tin Doanh nghiệp bằng Click-to-Run.  </li>
<li>  Cài Office Dành cho thiết bị di động (như Outlook Mobile, Word Mobile, Excel Mobile và PowerPoint Mobile) trên các thiết bị chạy iOS hoặc Android.  </li>
<li>  Đặt cấu hình thiết đặt cập nhật bằng cách sử Office 365 Công cụ Triển khai.  </li>
<li>  Lựa chọn và thiết lập bản cài đặt cục bộ hoặc điện toán đám mây.  </li>
<li>  Tạo XML cấu hình Office Công cụ Triển khai Dữ liệu bằng Office Công cụ Tùy chỉnh Office XML gốc để cấu hình gói triển khai.  </li>
<li>  Deployment using Microsoft Endpoint Configuration Manager, including assistance with the creation of Microsoft Endpoint Configuration Manager packaging.  
  Ngoài ra, nếu bạn có một macro hoặc phần bổ trợ làm việc với các phiên bản trước đó của Office và bạn gặp phải sự cố về tính tương thích, chúng tôi cung cấp hướng dẫn khắc phục sự cố tương thích mà không mất thêm chi phí thông qua chương trình Đảm bảo Ứng dụng. Hãy xem <strong>phần Đảm bảo</strong> của Ứng dụng trong <a href="#windows-10">Windows 10</a> thêm chi tiết. </li>
</ul></td>
<td><ul>
<li>  Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 và Office.</a>  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Tình trạng mạng</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa với việc nhận và diễn giải dữ liệu kết nối mạng then chốt từ môi trường của bạn cho thấy cách các site của tổ chức bạn được căn chỉnh như thế nào với các nguyên tắc kết nối <a href="/office365/enterprise/office-365-network-connectivity-principles">mạng</a>của Microsoft. Điều này nêu bật điểm số mạng của bạn ảnh hưởng trực tiếp đến tốc độ di chuyển, trải nghiệm người dùng, hiệu suất dịch vụ và độ tin cậy.  
  Chúng tôi cũng hướng dẫn bạn về bất kỳ bước khắc phục nào được tô sáng bằng dữ liệu này để giúp bạn cải thiện điểm số mạng của mình.  </td>
<td><ul>
<li>  Microsoft 365 Quyền truy nhập Trung tâm Quản trị.  </li>
<li>  Cần có phiên bản cập nhật của Microsoft 365 dụng Mới.  </li>
<li>  Dịch vụ vị trí được bật theo <a href="/Office365/Enterprise/office-365-network-mac-perf-overview">Đề xuất hiệu suất mạng trong Trung Microsoft 365 tâm Quản trị Máy tính (bản xem trước).</a>  </li>
</ul>
<h3 id="section"></h3></td>
</tr>
</tbody>
</table>

## <a name="security-and-compliance"></a>Bảo mật và Tuân thủ

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd"> 

<td><strong>Azure Active Directory (Azure AD) và Azure AD Premium</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa để bảo mật định danh trên đám mây của bạn đối với các kịch bản sau đây.  

 <br/>

<strong>Cơ sở hạ tầng nền tảng an toàn</strong>  </ul>
<ul>
<li>  Đặt cấu hình và bật xác thực mạnh cho định danh của bạn, bao gồm bảo vệ bằng Azure Multi-Factor Authentication (MFA) (chỉ dành cho điện toán đám mây), ứng dụng Microsoft Authenticator và kết hợp đăng ký Azure MFA và đặt lại mật khẩu tự phục vụ (SSPR).  </li>
<li> Triển khai FIDO2 hoặc Microsoft Authenticator App. </li>
<li>  Đối với khách hàng không phải của Azure AD Premium, hướng dẫn được cung cấp để bảo mật danh tính của bạn bằng các mặc định bảo mật.  </li>
<li>  Đối với khách hàng cao cấp của Azure AD, hướng dẫn được cung cấp để bảo mật danh tính của bạn bằng Quyền truy nhập có Điều kiện.  </li>
<li>  Phát hiện và chặn việc sử dụng mật khẩu yếu bằng Azure AD Password Protection.  </li>
<li>  Bảo mật truy nhập từ xa vào các ứng dụng web tại cơ sở bằng Azure AD Application Proxy.  </li>
<li>  Cho phép phát hiện và khắc phục dựa trên rủi ro bằng Azure Identity Protection.  </li>
<li>  Cho phép màn hình đăng nhập tùy chỉnh, bao gồm logo, văn bản và hình ảnh với thương hiệu tùy chỉnh.  </li>
<li>  Chia sẻ an toàn các ứng dụng và dịch vụ với người dùng khách bằng Azure AD B2B.  </li>
<li>  Quản lý quyền truy nhập cho người quản trị Office 365 bạn bằng cách sử dụng kiểm soát truy nhập dựa trên vai trò quản trị dựng sẵn (RBAC) và giảm số lượng tài khoản người quản trị đặc quyền.  </li>
<li>  Cấu hình kết hợp Azure AD kết hợp.  </li>
<li>  Đặt cấu hình cho kết nối Azure AD.  </li>
</ul>
  
<strong>Giám sát và báo cáo</strong>  
<ul>
<li>  
  Cho phép giám sát từ xa cho AD FS, Azure AD Kết nối và bộ điều khiển miền bằng Azure AD Kết nối Health.  
  </li>
</ul>
  
<strong>Quản trị</strong>  
<ul>
<li>  
  Quản lý định danh Azure AD và vòng đời truy nhập của bạn theo quy mô với quản lý quyền Azure AD.
  </li>
<li>  
  Quản lý tư cách thành viên nhóm Azure AD, quyền truy nhập ứng dụng doanh nghiệp và gán vai trò với các đánh giá về quyền truy nhập Azure AD.  
  </li>
<li>  
  Xem lại Điều khoản Sử dụng Azure AD.  
  </li>
<li>  
  Quản lý và kiểm soát quyền truy nhập vào các tài khoản quản trị đặc quyền bằng Azure AD Privileged Identity Management.  
  </li>
</ul>
  
<strong>Tự động hóa và hiệu quả </strong>  
<ul>
<li>  
  Bật Azure AD SSPR.  
  </li>
<li>  Cho phép người dùng tạo và quản lý bảo mật đám mây hoặc quản lý bảo mật đám mây Office 365 của riêng mình bằng quản lý nhóm tự phục vụ Azure AD.  </li>
<li>  Quản lý quyền truy nhập ủy nhiệm vào các ứng dụng doanh nghiệp bằng quản lý nhóm được ủy nhiệm của Azure AD.  </li>
<li>  Bật nhóm động Azure AD.  </li>
<li>  Sắp xếp các ứng dụng trong cổng thông tin Ứng dụng của Tôi bằng cách sử dụng các bộ sưu tập.  </li>
</ul></td>
<td>Active Directory tại chỗ và môi trường của nó đã được chuẩn bị cho Azure AD Premium, bao gồm khắc phục các sự cố được xác định ngăn chặn việc tích hợp với các tính năng Premium Azure AD và Azure AD.</td>
</tr>
<tr class="odd">
<td><strong>Azure Information Protection </strong></td>
<td>  Để biết thêm thông tin về Azure Information Protection, hãy <strong>xem mục Bảo vệ Thông tin</strong> của Microsoft trong bảng này.

  </td>
<td>  
  <tr class="odd">
<td><strong>Khám phá & phản hồi</strong></td>
<td>  

<strong>Advanced eDiscovery</strong>
  
Chúng tôi cung cấp hướng dẫn từ xa cho: 
<ul>
<li>  Tạo trường hợp mới.   </li>
<li>  Đưa người đứng ra bảo vệ.  </li>
<li>  Thực hiện tìm kiếm. </li>
<li>  Thêm kết quả tìm kiếm vào một tập xem lại. </li>
<li>  Chạy phân tích về một tập xem lại.  </li>
<li>  Xem lại và gắn thẻ tài liệu.  </li>
<li>  Xuất dữ liệu từ tập đánh giá. </li>
<li>  Nhập dữ liệu không Office 365 dữ liệu. </li>
</ul>

<strong>Kiểm tra Nâng</strong> cao (chỉ được hỗ trợ trong E5)

Chúng tôi cung cấp hướng dẫn từ xa cho:  
<ul>
<li> Bật tính năng kiểm tra nâng cao.</li>
<li> Thực hiện UI nhật ký kiểm tra tìm kiếm và các lệnh PowerShell kiểm tra cơ bản.</li>
</ul>

<strong> Trình quản lý Tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các loại vai trò.  </li>
<li> Thêm và cấu hình đánh giá.</li>
<li> Đánh giá tuân thủ bằng cách thực thi các hành động cải tiến và xác định xem điều này ảnh hưởng đến điểm số tuân thủ của bạn như thế nào.</li>
<li> Xem lại điều khiển ánh xạ và đánh giá điều khiển tích hợp sẵn.</li>
<li> Tạo báo cáo trong một đánh giá.</li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi </strong> 
<ul>
<li> Mã lệnh hoặc mã hóa tùy chỉnh.</li>
<li> API Khám phá Điện tử. </li>
<li> Đường kết nối dữ liệu. </li>
<li> Ranh giới tuân thủ và bộ lọc bảo mật.</li>
<li> Điều tra dữ liệu.</li>
<li> Yêu cầu chủ thể dữ liệu.</li>
<li> Thiết kế, kiến trúc sư và xem lại tài liệu của bên thứ ba.</li>
<li> Tuân thủ các quy định và yêu cầu của ngành và khu vực.</li>
<li> Thực hiện dựa trên thực tế các hành động cải thiện được đề xuất để đánh giá trong Trình quản lý Tuân thủ.</li>
</ul>
</td>
<td>Ngoài phần Triển năng <strong>cốt lõi trong Nói</strong> chung, không <a href="#general">có</a>yêu cầu hệ thống tối thiểu.</td>
</tr>

<tr class="odd">
<td><strong>Quản lý Rủi ro Người dùng Nội bộ</strong></td>

<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li> Tạo chính sách và xem lại thiết đặt.</li>
<li> Truy nhập báo cáo và cảnh báo.</li>
<li> Tạo trường hợp.</li>
<li> Tạo mẫu thông báo.</li>
<li> Hướng dẫn tạo bộ nối nhân sự (HR).</li>
</ul>

<strong> Tuân thủ Liên lạc </strong> 

Chúng tôi cung cấp hướng dẫn từ xa cho: 
<ul>
<li> Tạo chính sách và xem lại thiết đặt.</li>
<li> Truy nhập báo cáo và cảnh báo.</li>
<li> Tạo mẫu thông báo.</li>
</ul>

<strong> Trình quản lý Tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các loại vai trò.  </li>
<li> Thêm và cấu hình đánh giá.</li>
<li> Đánh giá tuân thủ bằng cách thực thi các hành động cải tiến và xác định xem điều này ảnh hưởng đến điểm số tuân thủ của bạn như thế nào.</li>
<li> Xem lại điều khiển ánh xạ và đánh giá điều khiển tích hợp sẵn.</li>
<li> Tạo báo cáo trong một đánh giá.</li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi </strong> 
<ul>
<li> Tạo và quản lý Power Automate lưu lượng mới.</li>
<li> Bộ nối dữ liệu (ngoài bộ nối Nhân sự). </li>
<li> Tùy chỉnh các cấu hình biểu thức thông thường (RegEx).</li>
<li> Thiết kế, kiến trúc sư và xem lại tài liệu của bên thứ ba.</li>
<li> Rào cản thông tin.</li>
<li> Quản lý truy nhập có đặc quyền.</li>
<li> Tuân thủ các quy định và yêu cầu của ngành và khu vực.</li>
<li> Thực hiện dựa trên thực tế các hành động cải thiện được đề xuất để đánh giá trong Trình quản lý Tuân thủ.</li>
</ul></td>
<td>Ngoài phần Triển năng <strong>cốt lõi trong Nói</strong> chung, không <a href="#general">có</a>yêu cầu hệ thống tối thiểu.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Microsoft 365 Bộ bảo vệ</strong></td>

<td> <p> Microsoft 365 Bộ bảo vệ là một bộ phòng vệ doanh nghiệp trước và sau vi phạm thống nhất, chủ yếu phối hợp việc phát hiện, ngăn chặn, điều tra và phản hồi giữa các điểm cuối, danh tính, email và ứng dụng nhằm cung cấp bảo vệ tích hợp trước các cuộc tấn công tinh vi. Chúng tôi cung cấp hướng dẫn từ xa cho: </p> 
<ul>
<li>  Cung cấp thông tin tổng quan Microsoft 365 tâm bảo mật.  </li>
<li>  Xem xét các sự cố chéo sản phẩm, bao gồm tập trung vào những điều quan trọng bằng cách đảm bảo phạm vi tấn công toàn bộ, tài sản bị ảnh hưởng và các hành động khắc phục tự động được nhóm lại với nhau.  </li>
<li>  Thể hiện cách Microsoft 365 bộ bảo vệ có thể phối hợp quá trình điều tra tài nguyên, người dùng, thiết bị và hộp thư có thể đã bị xâm phạm thông qua chế độ tự động hóa. </li>
<li>  Giải thích và cung cấp các ví dụ về cách khách hàng chủ động tìm kiếm các nỗ lực xâm nhập và hoạt động vi phạm tác động đến email, dữ liệu, thiết bị và tài khoản của bạn trên nhiều tập dữ liệu.   </li>
<li> Cho khách hàng thấy cách họ có thể xem lại và cải thiện tư thế bảo mật một cách toàn diện bằng cách sử dụng Điểm Bảo mật của Microsoft.</li>
</ul>
<p><strong>Sau đây là nằm ngoài phạm vi</strong></p>
<ul>
<li> Project lý hoạt động khắc phục của khách hàng. </li>
<li> Quản lý liên tục, ứng phó với mối đe dọa và khắc phục. </li>
<li> Hướng dẫn triển khai hoặc giáo dục về:
<ul>
<li> Cách khắc phục hoặc diễn giải các loại cảnh báo khác nhau và các hoạt động được theo dõi. </li>
<li> Cách điều tra người dùng, máy tính, đường di chuyển sau hoặc thực thể. </li>
<li> Tính năng chống mối đe dọa tùy chỉnh.  </li>
</ul>
</li>
<li> Tích hợp quản lý sự kiện và thông tin bảo mật (SIEM) hoặc API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Cloud App Security</strong></td>
<td>  Microsoft Cloud App Security là một Cloud Access Security Broker (CASB) cung cấp khả năng hiển thị phong phú, kiểm soát việc di chuyển dữ liệu và phân tích tinh vi để xác định và chống lại các mối đe dọa trên mạng trên tất cả các dịch vụ đám mây của Microsoft và bên thứ ba. Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Cấu hình cổng thông tin, bao gồm:  </li>
<ul>
<li> Nhập nhóm người dùng.</li>
<li> Quản lý quyền truy nhập và cài đặt quản trị.  </li>
<li> Kiểm tra triển khai của bạn để chọn nhóm người dùng nhất định để giám sát hoặc loại trừ khỏi việc giám sát.</li>
<li> Đặt dải IP và thẻ.</li>
<li> Cá nhân hóa trải nghiệm người dùng cuối bằng logo và nhắn tin tùy chỉnh của bạn.</li>
</ul>
<li> Thiết lập khám phá điện toán đám mây để cung cấp đổ bóng cho IT bằng:</li>
<ul>
<li> Bộ bảo vệ Microsoft dành cho Điểm cuối.</li>
<li> Zscaler.</li>
<li> iboss.</li>
</ul>
<li> Kết nối các <a href="/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps"> ứng dụng nổi</a> bật bằng trình kết nối ứng dụng.</li>
<li> Thiết lập Kiểm soát Ứng dụng Truy nhập có Điều kiện trong cổng thông tin Truy nhập có Điều kiện Cloud App Security cổng thông tin Để áp dụng điều khiển phiên làm việc theo thời gian thực.</li>
<li> Triển khai bảng điều Cloud App Security Cloud Discovery.</li>
<li> Tùy chỉnh điểm rủi ro của ứng dụng dựa trên ưu tiên của tổ chức bạn.</li>
<li> Tạo thẻ và danh mục ứng dụng.</li>
<li> Ứng dụng xử lý và không cấp phép.</li>
<li> Sử dụng hoạt động và nhật ký tệp.</li>
<li> Quản lý ứng dụng OAuth.</li>
<li> Hiểu rõ tương quan về sự cố trong cổng thông Microsoft 365 Bộ bảo vệ.</li>
<li> Cung cấp hỗ trợ cấu hình <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">với 20</a> trường hợp sử dụng hàng đầu cho CASBs (bao gồm việc tạo hoặc cập nhật tối đa sáu (6) chính sách) ngoại trừ: </li>
<ul>
<li> Kiểm tra cấu hình internet của bạn dưới dạng môi trường dịch vụ (IaaS) (#18).</li>
<li> Giám sát các hoạt động của người dùng để bảo vệ chống lại các mối đe dọa trong môi trường IaaS của bạn (#19).</li>
</ul>
</ul>
<p><strong>Sau đây là nằm ngoài phạm vi</strong></p>
<ul>
<li> Project lý hoạt động khắc phục của khách hàng.</li>
<li> Quản lý liên tục, ứng phó với mối đe dọa và khắc phục. </li>
<li> Thiết lập cơ sở hạ tầng, cài đặt hoặc triển khai các bản tải lên nhật ký tự động cho các báo cáo liên tục bằng Cách dùng Docker hoặc bộ thu thập nhật ký. Xem <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 trường hợp sử dụng hàng đầu cho CASBs để</a> biết thêm chi tiết.</li>
<li> Tạo báo cáo hiện trạng Khám phá Đám mây.</li>
<li> Chặn mức sử dụng ứng dụng bằng tập lệnh chặn.</li>
<li> Kết nối ứng dụng tùy chỉnh.</li>
<li> Tích hợp với nhà cung cấp nhận dạng bên thứ ba (ISP) và nhà cung cấp ngăn mất dữ liệu (DLP).</li>
<li> Nội dụng đào tạo hoặc hướng dẫn về phòng vệ nâng cao.</li>
<li> Điều tra và khắc phục tự động bao gồm các sách Power Automate Microsoft.</li>
<li> Quản lý thông tin bảo mật và sự kiện (SIEM) hoặc tích hợp API (bao gồm Azure Sentinel).</li>
<li> Triển khai Khám phá Ứng dụng Đám mây làm bằng chứng khái niệm.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Bộ bảo vệ Microsoft dành cho Điểm cuối</strong></td>
<td>  Bộ bảo vệ Microsoft dành cho Điểm cuối là một nền tảng được thiết kế để giúp các mạng doanh nghiệp ngăn chặn, phát hiện, điều tra và phản hồi các mối đe dọa nâng cao.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Triển khai các công nghệ để bảo mật điểm cuối của bạn.  </li>
<li>  Cấu hình bảo vệ điểm cuối và cấu hình hạn chế thiết bị.  </li>
<li>  Đánh giá phiên bản HĐH và quản lý thiết bị (bao gồm Intune, Trình quản lý Cấu hình Điểm cuối của Microsoft, Đối tượng Chính sách Nhóm (GPOs) và cấu hình của bên thứ ba) cũng như trạng thái của các dịch vụ Bộ bảo vệ Windows AV hoặc phần mềm bảo mật điểm cuối khác.  </li>
<li>  Đánh giá trạng thái dịch vụ Windows AV hoặc phần mềm bảo mật điểm cuối khác của bạn.  </li>
<li>  Đánh giá các proxy và tường lửa hạn chế lưu lượng truy nhập mạng.  </li>
<li>  Bật dịch vụ Điểm cuối của Bộ bảo vệ Microsoft bằng cách giải thích cách triển khai một Bộ bảo vệ cho hồ sơ tác vụ Điểm cuối bằng cách sử dụng điểm cuối triển khai.  </li>
<li>  Hướng dẫn triển khai, trợ giúp về cấu hình và giáo dục trên:
<ul>
<li>  
  Mối đe dọa và quản lý lỗ hổng.  
  </li>
<li>  
  Giảm bề mặt tấn công.  
  </li>
<li>  
  Bảo vệ thế hệ tiếp theo.  
  </li>
<li>  
  Phát hiện và phản hồi điểm cuối.  
  </li>
<li>  
  Điều tra và khắc phục tự động.  
  </li>
<li>  
  Điểm số an toàn.  
  </li>
</ul></li>
<li>  Xem lại mô phỏng và hướng dẫn (như các kịch bản thực hành, phần mềm xấu giả mạo và điều tra tự động).  </li>
<li>  Tổng quan về các tính năng báo cáo và phân tích mối đe dọa.  </li>
<li>  Tích hợp Bộ bảo vệ Microsoft dành cho Office 365 với Bộ bảo vệ Microsoft dành cho Điểm cuối.  </li>
<li>  Tiến hành các hướng dẫn về cổng Trung tâm Bảo mật của Bộ bảo vệ Microsoft tin.  </li>
<li>  Các hệ điều hành sau:
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
  Windows Server 2019 Core Edition.  
  </li>
<li>  
  Windows Server Semi-Annual Channel (SAC) phiên bản 1803.  
  </li>
<li>  
  macOS phiên bản 10.13, 10.14 và 10.15.  
  </li>
</ul>
</li>
</ul>
<strong>Lưu ý:</strong> Tất cả các phiên bản Windows Server phải được quản lý bởi phiên bản mới nhất của System Center Configuration Manager 2012 (phiên bản 1012 R2, 1511 hoặc 1602) hoặc Trình quản lý Cấu hình Điểm cuối của Microsoft (phiên bản 2002 trở lên). 

</li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li>  Project lý hoạt động khắc phục của khách hàng.  </li>
<li>  Hỗ trợ tại chỗ.  </li>
<li>  Quản lý liên tục và ứng phó với mối đe dọa.  </li>
<li>  Việc tích hợp hoặc cấu hình cho các tác nhân của Microsoft Defender dành cho Điểm cuối sau đây:
<ul>
<li>  
  Windows Server 2008.  
  </li>
<li>  
  Windows Server 2012.  
  </li>
<li>  
  Linux.  
  </li>
<li>  
  Thiết bị di động (Android và iOS).  
  </li>
<li> Cơ sở hạ tầng Máy tính Ảo (VDI) (liên tục hoặc không liên tục).  </li>
</ul></li>
<li>  Đang phát hành và cấu hình máy chủ:
<ul>
<li>  
  Cấu hình máy chủ proxy để liên lạc ngoại tuyến.  
  </li>
<li>  
  Cấu hình gói triển khai Trình quản lý Cấu hình trên phiên bản và phiên bản Trình quản lý Cấu hình xuống.  
  </li>
<li>  
  Các máy chủ triển năng cho Trung tâm Bảo mật Azure.  
  </li>
<li>  
  Máy chủ không được quản lý bởi Trình quản lý Cấu hình.  
  </li>
</ul></li>
<li>  Đang phát hành và cấu hình macOS:
<ul>
<li>  
  Triển khai dựa trên Intune thủ công.  
  </li>
<li>  
  Triển khai dựa trên JAMF.
  </li>
<li>  
  Triển khai dựa trên sản phẩm bằng quản lý thiết bị di động (MDM) khác.  
  </li>
<li>  
  Triển khai thủ công.  
  </li>
</ul></li>
<li>  Cấu hình các chức năng giảm bề mặt tấn công sau đây:
<ul>
<li>  
  Cách ly dựa trên phần cứng.  
  </li>
<li>  
  Điều khiển ứng dụng.  
  </li>
<li> Điều khiển thiết bị.</li>
<li>  
  Bảo vệ khai thác.  
  </li>
<li>  
  Tường lửa mạng.  
  </li>



</ul></li>
<li> Cấu hình hoặc quản lý các tính năng bảo vệ tài khoản như: </li>
<ul>

<li> Windows Xin chào</li>
<li> Bảo vệ thông tin xác thực</li>
</ul>
<li> Cấu hình hoặc quản lý BitLocker.</li>
<li>  Đăng ký hoặc cấu hình Chuyên gia về Mối đe dọa của Microsoft.  </li>
<li>  Cấu hình hoặc đào tạo xem lại API hoặc các kết nối quản lý sự kiện và quản lý sự kiện (SIEM).  </li>
<li>  Đăng ký hoặc cấu hình Bảo vệ chống Mối đe dọa của Microsoft (MTP).  </li>
<li>  Nội dụng đào tạo hoặc hướng dẫn về phòng vệ nâng cao.  </li>
<li>  Nội dung đào tạo hoặc hướng dẫn về cách sử dụng hoặc tạo truy vấn Kusto.</li>
</li>
</ul>
Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về các dịch vụ này.  
</ul></td>
<td></td>

<tr class="odd">
<td><strong>Bộ bảo vệ Microsoft cho Danh tính </strong></td>
<td>  Bộ bảo vệ Microsoft dùng danh tính là giải pháp bảo mật trên nền điện toán đám mây tận dụng các tín hiệu Active Directory tại chỗ của bạn để xác định, phát hiện và điều tra các mối đe dọa nâng cao, danh tính bị xâm phạm và các hành động người dùng nội bộ độc hại được chuyển hướng tới tổ chức của bạn. Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>   Tạo phiên bản Bộ bảo vệ cho Danh tính của bạn. </li>
<li>   Bộ bảo vệ Kết nối danh tính với Active Directory. </li>
<li>   Đánh giá mức độ sẵn sàng của môi trường để triển khai cảm biến Bộ bảo vệ cho Định danh trên bộ kiểm soát miền của bạn, bao gồm:</li>   
<ul> 
<li>  Chạy công cụ đổi cỡ để lập kế hoạch năng suất tài nguyên. </li>
<li>  Chạy công cụ kiểm tra để đánh giá tính tương thích của bộ điều khiển miền với cảm biến. </li>
</ul>
<li>  Triển khai cảm biến để chụp và phân tích lưu lượng truy cập mạng Windows các sự kiện trực tiếp từ bộ điều khiển miền của bạn, bao gồm: </li>
<ul> 
<li>  Tải xuống gói cảm biến. </li>
<li>  Đặt cấu hình cảm biến. </li>
<li>  Cài đặt cảm biến trên bộ điều khiển tên miền của bạn một cách im lặng. </li>
<li>  Triển khai cảm biến cho môi trường nhiều rừng của bạn. </li>
</ul>
<li>  Tích hợp Bộ bảo vệ cho Danh tính với Microsoft Cloud App Security định danh (Cloud App Security cấp phép mới không bắt buộc). </li>
<li>  Cung cấp hướng dẫn triển khai, trợ giúp về cấu hình và giáo dục trên: </li>
<ul>
<li> Điều chỉnh môi trường để giảm "tiếng ồn".  </li>
<li>  Hiểu rõ báo cáo đánh giá tư thế bảo mật định danh. </li>
<li>  Hiểu rõ điểm ưu tiên Điều tra của người dùng và báo cáo xếp hạng Điều tra người dùng. </li>
<li> Tìm hiểu về báo cáo người dùng không hiện hoạt.  </li>
<li> Cung cấp tùy chọn khắc phục trên tài khoản bị xâm phạm.  </li>
</ul>
<li>  Tạo điều kiện cho việc di chuyển từ Phân tích Mối đe dọa Nâng cao (ATA) sang Bộ bảo vệ để nhận dạng. </li>
</ul>
<p><strong>Sau đây là nằm ngoài phạm vi</strong></p>
<ul>

<li> Project lý hoạt động khắc phục của khách hàng. </li>
<li> Quản lý liên tục, ứng phó với mối đe dọa và khắc phục.  </li>
<li> Triển khai cảm biến Bộ bảo vệ cho Danh tính, bao gồm: </li>
<ul>
<li> Lập kế hoạch công suất thủ công. </li>
<li> Triển khai cảm biến ở công suất độc lập. </li>
<li> Triển khai cảm biến bằng bộ điều hợp Nhóm Thẻ Giao diện Mạng (NIC). </li>
<li> Triển khai cảm biến thông qua công cụ của bên thứ ba. </li>
<li> Kết nối với dịch vụ đám mây Bộ bảo vệ cho Danh tính thông qua kết nối proxy web. </li>
</ul>
<li> Tạo và quản lý honeytokens. </li>
<li> Hướng dẫn triển khai hoặc giáo dục về: </li>
<ul>
<li> Khắc phục hoặc diễn giải các loại cảnh báo khác nhau và các hoạt động được theo dõi.  </li>
<li> Đang điều tra người dùng, máy tính, đường di chuyển sau hoặc thực thể. </li>
<li> Mối đe dọa hoặc thời vụ bảo vệ nâng cao. </li>
<li> Ứng phó sự cố. </li>
</ul>
<li> Cung cấp hướng dẫn phòng cảnh báo bảo mật cho Bộ bảo vệ để biết danh tính. </li>
<li> Việc cung cấp thông báo khi Bộ bảo vệ cho Danh tính phát hiện các hoạt động đáng ngờ bằng cách gửi cảnh báo bảo mật đến máy chủ syslog của bạn thông qua cảm biến được chỉ định.  </li>
<li> Đặt cấu hình Bộ bảo vệ cho Danh tính để thực hiện truy vấn bằng giao thức từ xa của trình quản lý tài khoản bảo mật (SAMR) để xác định người quản trị cục bộ trên các máy cụ thể. </li>
<li> Đặt cấu hình các giải pháp VPN để thêm thông tin từ kết nối VPN vào trang hồ sơ của người dùng.  </li>
<li> Quản lý thông tin bảo mật và sự kiện (SIEM) hoặc tích hợp API (bao gồm Azure Sentinel). </li>
<li> Việc triển khai cảm biến Bộ bảo vệ cho Danh tính làm bằng chứng khái niệm.</li>
</ul></td>
<td><ul>
<li>  Active Directory đã triển khai.  </li>
<li>  Bộ kiểm soát miền mà bạn định cài đặt cảm biến Bộ bảo vệ cho Danh tính trên có kết nối internet với dịch vụ đám mây Bộ bảo vệ danh tính.  </li>
<ul>
<li> Tường lửa và proxy của bạn phải mở để liên lạc với dịch vụ đám mây Bộ bảo vệ cho Danh tính (*.atp.azure.com cổng 443 phải được mở).</li>
</ul>
<li> Bộ điều khiển miền chạy trên một trong các thiết bị sau:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 với KB4487044 (HĐH Bản dựng 17763.316).</li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Bộ bảo vệ Microsoft dành cho Office 365</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Bật Két sắt kết, Két sắt kèm và chống lừa đảo.  </li>
<li>  Đặt cấu hình tự động hóa, điều tra và phản hồi.  </li>
<li>  Sử dụng Phát sinh Tấn công.  </li>
<li>  Phân tích báo cáo và mối đe dọa.  </li>
</ul></td>
<td>Ngoài phần Triển năng <strong>cốt lõi trong Nói</strong> chung, không <a href="#general">có</a>yêu cầu hệ thống tối thiểu.</td>
</tr>


<tr class="even">
<td><strong>Quản trị Thông tin Microsoft</strong></td>

<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Tạo và phát hành nhãn duy trì và chính sách (chỉ được hỗ trợ trong E5).  
</li>
<li>  Quản lý bản ghi (chỉ được hỗ trợ trong E5).  </li>
<ul><li>  Xem lại việc tạo kế hoạch tệp. </li>
<li>  Tạo và quản lý bản ghi (bao gồm các bản ghi dựa trên sự kiện).  </li>
<li>  Xem lại bố trí. </ul> </li>
</ul>

<strong> Trình quản lý Tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các loại vai trò.  </li>
<li> Thêm và cấu hình đánh giá.</li>
<li> Đánh giá tuân thủ bằng cách thực thi các hành động cải tiến và xác định xem điều này ảnh hưởng đến điểm số tuân thủ của bạn như thế nào.</li>
<li> Xem lại điều khiển ánh xạ và đánh giá điều khiển tích hợp sẵn.</li>
<li> Tạo báo cáo trong một đánh giá.</li>
</ul>

  <strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li> Phát triển kế hoạch tệp quản lý bản ghi.</li>
<li> Đường kết nối dữ liệu.</li>
<li> Phát triển kiến trúc thông tin trong SharePoint.</li>
<li> Mã lệnh và mã hóa tùy chỉnh.</li>
<li> Thiết kế, kiến trúc sư và xem lại tài liệu của bên thứ ba.</li>
<li> Hỗ trợ cho E3.</li>
<li> Tuân thủ các quy định và yêu cầu của ngành và khu vực.</li>
<li> Thực hiện dựa trên thực tế các hành động cải thiện được đề xuất để đánh giá trong Trình quản lý Tuân thủ.</li>
</ul>

</td>
<td>Ngoài phần Triển năng <strong>cốt lõi trong Nói</strong> chung, không <a href="#general">có</a>yêu cầu hệ thống tối thiểu.</td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Phân loại dữ liệu (được hỗ trợ trong E3 và E5).  </li>
<li>  Các kiểu thông tin nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Tạo nhãn nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Áp dụng nhãn nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Lớp học có thể đào tạo (được hỗ trợ trong E5).  </li>
<li>  Biết được dữ liệu của bạn với trình khám phá nội dung và activity explorer (được hỗ trợ trong E5).  </li>
<li>  Phát hành nhãn bằng các chính sách (thủ công và tự động) (được hỗ trợ trong E5).  </li>
<li>  Tạo chính sách Ngăn mất dữ liệu điểm cuối (DLP) cho thiết Windows 10 thiết bị của bạn (được hỗ trợ trong E5).  </li>
<li>  Tạo chính sách DLP cho Microsoft Teams chuyện và kênh.  </li>
</ul>

<strong> Trình quản lý Tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các loại vai trò.  </li>
<li> Thêm và cấu hình đánh giá.</li>
<li> Đánh giá tuân thủ bằng cách thực thi các hành động cải tiến và xác định xem điều này ảnh hưởng đến điểm số tuân thủ của bạn như thế nào.</li>
<li> Xem lại điều khiển ánh xạ và đánh giá điều khiển tích hợp sẵn.</li>
<li> Tạo báo cáo trong một đánh giá.</li>
</ul>

<strong> Azure Information Protection</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  
<ul>
<li>  Kích hoạt và cấu hình đối tượng thuê của bạn.  </li>
<li>  Tạo và thiết lập nhãn và chính sách (được hỗ trợ trong P1 và P2).  </li>
<li>  Áp dụng bảo vệ thông tin cho tài liệu (được hỗ trợ trong P1 và P2).  </li>
<li>  Tự động phân loại và đánh nhãn thông tin trong các ứng dụng Office (như Word, PowerPoint, Excel và Outlook) chạy trên Windows và sử dụng Máy khách Azure Information Protection (được hỗ trợ trong P2).  </li>
<li>  Khám phá và ghi nhãn tệp khi còn lại bằng trình quét Azure Information Protection (được hỗ trợ trong P1 và P2).  </li>
<li>  Giám sát email khi truyền bằng Exchange Online tắc dòng thư.  </li>
</ul>

  Chúng tôi cũng cung cấp hướng dẫn nếu bạn muốn áp dụng bảo vệ bằng Microsoft Azure Rights Management Services (Azure RMS), Mã hóa Thư Office 365 (OME) và ngăn mất dữ liệu (DLP).

<strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li>Khóa khách hàng.</li>
<li>Phát triển biểu thức thông thường tùy chỉnh (RegEx) cho các loại thông tin nhạy cảm.</li>
<li>Tạo hoặc sửa đổi từ điển từ khóa.</li>
<li>Mã lệnh và mã hóa tùy chỉnh.</li>
<li> Azure Purview.</li>
<li> Thiết kế, kiến trúc sư và xem lại tài liệu của bên thứ ba.</li>
<li> Tuân thủ các quy định và yêu cầu của ngành và khu vực.</li>
<li> Thực hiện dựa trên thực tế các hành động cải thiện được đề xuất để đánh giá trong Trình quản lý Tuân thủ.</li>
</ul>

<ul>

</td>
<td>Ngoài phần Triển năng <strong>cốt lõi trong Tổng</strong> <a href="#general">quát,</a>không có yêu cầu hệ thống tối thiểu ngoại trừ Azure Information Protection.

<strong>Azure Information Protection</strong>

Trách nhiệm tiên quyết của khách hàng bao gồm:  
<ul>
<li>  Danh sách các vị trí chia sẻ tệp cần được quét.  </li>
<li>  Một phân loại phân loại được phê duyệt. </li>
<li> Hiểu về mọi hạn chế hoặc yêu cầu quy định về quản lý khóa.  </li>
<li>  Một tài khoản dịch vụ được tạo cho Active Directory tại chỗ của bạn đã được đồng bộ hóa với Azure AD. </li>
<li>  Nhãn được đặt cấu hình để phân loại và bảo vệ. </li>
<li> Tất cả điều kiện tiên quyết cho trình quét Azure Information Protection đều có sẵn. Để biết thêm thông tin, <a href="/azure/information-protection/deploy-aip-scanner-prereqs">hãy xem Điều kiện tiên</a>quyết để cài đặt và triển khai máy quét nhãn hợp nhất Azure Information Protection . </li>
<li>  Đảm bảo rằng thiết bị người dùng đang chạy hệ điều hành được hỗ trợ và đã cài đặt các điều kiện tiên quyết cần thiết. Xem phần sau để biết thêm chi tiết.</li>
<ul>
<li> <a href="/azure/information-protection/rms-client/clientv2-admin-guide-install">Hướng dẫn Quản trị: Cài đặt máy khách gắn nhãn hợp nhất Azure Information Protection cho người dùng</a>   </li>
<li>  <a href="/azure/information-protection/rms-client/mobile-app-faq">Ứng dụng Azure Information Protection dành cho iOS hoặc Android là gì?</a>  </li>
</ul>
<li> Cài đặt và cấu hình của bộ nối và máy chủ Azure RMS bao gồm bộ nối Active Directory RMS (AD RMS) để hỗ trợ kết hợp.  </li>
<li> Thiết lập và cấu hình Cho Khóa Riêng của Bạn (BYOK), Mã hóa Khóa Kép (DKE) (chỉ dành cho máy khách đánh nhãn hợp nhất) hoặc Giữ Khóa của Riêng Bạn (HYOK) (chỉ dành cho máy khách cổ điển) nếu bạn yêu cầu một trong các tùy chọn này cho việc triển khai.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa về việc chuẩn bị sẵn sàng sử dụng Intune làm nhà cung cấp quản lý thiết bị di động trên nền điện toán đám mây (MDM) và nhà cung cấp quản lý ứng dụng dành cho thiết bị di động (MAM) cho các ứng dụng và thiết bị của bạn. Các bước chính xác tùy thuộc vào môi trường nguồn của bạn và dựa trên nhu cầu quản lý thiết bị di động và ứng dụng dành cho thiết bị di động của bạn. Các bước có thể bao gồm:
<ul>
<li>  Cấp phép cho người dùng cuối của bạn.  </li>
<li>  Đặt cấu hình định danh để Intune sử dụng bằng cách tận dụng Active Directory tại chỗ hoặc định danh đám mây (Azure AD).  </li>
<li>  Thêm người dùng vào đăng ký Intune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.  </li>
<li>  Đặt cấu hình cho cơ quan MDM của bạn, dựa trên nhu cầu quản lý của bạn, bao gồm:
<ul>
<li>  Đặt Intune làm cơ quan MDM của bạn khi Intune là giải pháp MDM duy nhất của bạn.  </li>
</ul></li>
<li>  Cung cấp hướng dẫn về MDM cho:
<ul>
<li>  Cấu hình các nhóm kiểm tra được dùng để xác thực chính sách quản lý MDM.  </li>
<li>  Đặt cấu hình cho chính sách quản lý MDM và các dịch vụ như:
<ul>
<li>  Triển khai ứng dụng cho từng nền tảng được hỗ trợ thông qua liên kết web hoặc liên kết sâu.  </li>
<li>  Chính sách Truy nhập có Điều kiện.  </li>
<li>  Triển khai email, mạng không dây và cấu hình VPN nếu bạn hiện có cơ quan cấp chứng chỉ, mạng không dây hoặc cơ sở hạ tầng VPN trong tổ chức của mình.  </li>
<li>  Kết nối với Nhà kho Dữ liệu Intune.  </li>
<li>  Tích hợp Intune với:
<ul>
<li>  Trình xem Nhóm để được trợ giúp từ xa (bắt buộc phải có đăng ký Trình xem Nhóm).  </li>
<li>  Mobile Threat Defense (MTD) partner solutions (an MTD subscription is required).  </li>
<li>  A telecom expense management solution (a telecom expense management solution subscription is required).  </li>

</ul></li>
<li>  Đăng ký thiết bị của mỗi nền tảng được hỗ trợ vào Intune.  </li>
</ul></li>
</ul></li>
<li>  Cung cấp hướng dẫn bảo vệ ứng dụng về:
<ul>
<li>  Đặt cấu hình chính sách bảo vệ ứng dụng cho từng nền tảng được hỗ trợ.  </li>
<li>  Đặt cấu hình chính sách Truy nhập có Điều kiện cho ứng dụng được quản lý.  </li>
<li>  Hướng tới các nhóm người dùng thích hợp với các chính sách MAM đã được đề cập trước đó.  </li>
<li>  Sử dụng báo cáo sử dụng ứng dụng được quản lý.  </li>
</ul></li>
<li>  Cung cấp hướng dẫn di chuyển từ quản lý PC thừa tự sang MDM Intune.  </li>
</ul>
 
</li>
</ul>
  
<strong>Đính kèm đám mây</strong>  

  Chúng tôi hướng dẫn bạn cách chuẩn bị sẵn sàng đính kèm đám mây cho môi trường Trình quản lý Cấu hình hiện có với Intune. Các bước chính xác sẽ phụ thuộc vào môi trường nguồn của bạn. Các bước sau đây có thể bao gồm:  
<ul>
<li>  Cấp phép cho người dùng cuối của bạn.  </li>
<li>  Đặt cấu hình định danh để Intune sử dụng bằng cách tận dụng Active Directory và định danh điện toán đám mây tại chỗ của bạn.  </li>
<li>  Thêm người dùng vào đăng ký Intune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.  </li>
<li>  Cung cấp hướng dẫn thiết lập kết hợp Azure AD kết hợp.  </li>
<li>  Cung cấp hướng dẫn về việc thiết lập Azure AD cho tự động đăng ký MDM.  </li>
<li>  Cung cấp hướng dẫn về cách thiết lập cổng kết nối quản lý đám mây khi được sử dụng làm giải pháp để đồng quản lý quản lý thiết bị trên internet từ xa.  </li>
<li>  Đặt cấu hình khối lượng công việc được hỗ trợ mà bạn muốn chuyển sang Intune.  </li>
<li>  Cài đặt máy khách Bộ quản lý Cấu hình trên thiết bị được đăng ký Intune.  </li>
</ul> 

<strong>Triển khai Outlook di động cho iOS và Android một cách bảo mật</strong> Chúng tôi có thể cung cấp hướng dẫn để giúp bạn triển khai Outlook mobile for iOS và Android một cách an toàn trong tổ chức của bạn nhằm đảm bảo người dùng đã cài đặt tất cả các ứng dụng bắt buộc.  
  Các bước để triển khai bảo mật Outlook thiết bị di động cho iOS và Android với Intune tùy thuộc vào môi trường nguồn của bạn. Nó có thể bao gồm:
<ul>
<li>  Tải xuống ứng Outlook cho iOS và Android, Microsoft Authenticator và Intune Company Portal thông qua Apple App Store hoặc Google Play Store.  </li>
<li>  Cung cấp hướng dẫn thiết lập:
<ul>
<li>  Ứng Outlook cho iOS và Android, cũng như Microsoft Authenticator sẽ được triển Intune Company Portal với Intune.  </li>
<li>  Chính sách bảo vệ ứng dụng.  </li>
<li>  Chính sách Truy nhập có Điều kiện.  </li>
<li>  Chính sách cấu hình ứng dụng.  </li>
</ul></li>
</ul>  
  </td>
<td>  Người quản trị CNTT cần có các cơ sở hạ tầng Certificate Authority, mạng không dây và VPN hiện đang hoạt động trong môi trường sản xuất của mình khi lên kế hoạch triển khai mạng không dây và cấu hình VPN với Intune.  
  <strong>Lưu</strong>ý : Lợi ích dịch vụ FastTrack không bao gồm hỗ trợ thiết lập hoặc cấu hình Cơ quan cấp chứng chỉ, mạng không dây, cơ sở hạ tầng VPN hoặc chứng chỉ đẩy MDM của Apple cho Intune.  
 
  <strong>Lưu</strong>ý : Lợi ích dịch vụ FastTrack không bao gồm hỗ trợ thiết lập hoặc nâng cấp máy chủ site Trình quản lý Cấu hình hoặc máy khách Trình quản lý Cấu hình lên các yêu cầu tối thiểu cần thiết để hỗ trợ gắn trên đám mây. Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về vấn đề này.

  <strong>Intune được tích hợp với Microsoft Defender dành cho Điểm cuối</strong> 
 
  <strong>Lưu ý:</strong>Chúng tôi cung cấp hỗ trợ về việc tích hợp Intune với Bộ bảo vệ Microsoft dành cho Điểm cuối và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức rủi ro Windows 10 thiết bị. Chúng tôi không cung cấp hỗ trợ về việc mua hàng, cấp phép hoặc kích hoạt. Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về vấn đề này.  
  
<strong>Windows Autopilot</strong> 
 
  Người quản trị CNTT chịu trách nhiệm đăng ký thiết bị của mình cho tổ chức của mình bằng cách thay mặt nhà cung cấp phần cứng tải lên ID phần cứng hoặc bằng cách tải thiết bị lên dịch vụ Autopilot của Windows.  
  
</td>
</tr>


</tbody>
</table>

## <a name="office-365"></a>Office 365

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Exchange Online</strong></td>
<td>  Ví dụ Exchange Online, chúng tôi hướng dẫn bạn toàn bộ quy trình để tổ chức của bạn sẵn sàng sử dụng email. Các bước chính xác sẽ phụ thuộc vào môi trường nguồn và kế hoạch di chuyển email của bạn.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Thiết lập các Exchange Online Protection (EOP) cho tất cả các tên miền hỗ trợ thư được xác thực trong Office 365.  </li>
<li>  Trỏ bản ghi trao đổi thư (MX) của bạn đến một Office 365.  </li>
<li>  Thiết lập tính năng Bộ bảo vệ Microsoft Office 365 này nếu đây là một phần trong dịch vụ đăng ký của bạn. Để biết thêm thông tin, hãy xem <strong>mục Bộ bảo vệ Microsoft Office 365</strong> phần trong bảng này.  </li>
<li>  Thiết lập tính năng ngăn mất dữ liệu (DLP) cho tất cả các tên miền hỗ trợ thư được xác thực trong Office 365 như là một phần của dịch vụ đăng ký của bạn. Điều này được thực hiện sau khi bản ghi MX của bạn trỏ tới Office 365.  </li>
<li>  Thiết lập Mã hóa Thư Office 365 (OME) cho tất cả các miền hỗ trợ thư được xác thực trong Office 365 như một phần của dịch vụ đăng ký của bạn. Điều này được thực hiện sau khi bản ghi MX của bạn trỏ tới Office 365.  </li>
</ul>
  <strong>Lưu ý:</strong> Dịch vụ Nhân bản Hộp thư (MRS) tìm cách di chuyển email được Quản lý bằng Quyền Thông tin (IRM) từ hộp thư tại chỗ của bạn sang hộp thư Exchange Online tương ứng. Khả năng đọc nội dung được bảo vệ sau khi di chuyển phụ thuộc vào ánh xạ khách hàng và sao chép mẫu Dịch vụ Được quản lý bằng Quyền Active Directory (AD RMS) vào Azure Rights Management Service (Azure RMS).  
<ul>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Thiết lập DNS, bao gồm các bản ghi Tự động phát hiện, khung chính sách người gửi (SPF), thư được Xác định bởi DomainKeys (DKIM), Xác thực Thư dựa trên Miền, Báo cáo và Hợp chuẩn (DMARC) và bản ghi MX (nếu cần).  </li>
<li>  Thiết lập dòng email giữa môi trường nhắn tin nguồn và thư của Exchange Online (nếu cần).  </li>
<li>  Tiến hành di chuyển thư từ môi trường nhắn tin nguồn của bạn Office 365.  </li>
<li>  Đặt cấu hình cho máy khách hộp Outlook cho Windows, Outlook trên web và Outlook cho iOS và Android).  </li>
</ul>
  <strong>Di chuyển dữ liệu</strong>  <br>
Để biết thông tin về việc sử dụng lợi ích FastTrack cho việc di chuyển dữ liệu sang Office 365, hãy xem <a href="/fasttrack/data-migration">Di chuyển Dữ liệu</a>.   
<td>  Môi trường nguồn của bạn phải có một trong các mức tối thiểu sau đây:
<ul>
<li>  Một hoặc nhiều tổ Exchange trở lên Exchange Server 2003.  </li>
<li>  Một môi trường email duy nhất có thể sử dụng Giao thức Truy nhập Thông điệp Internet (IMAP).  </li>
<li>  Môi trường G Suite đơn (chỉ Gmail, Danh bạ và Lịch).  </li>
<li>  Để biết thông tin về Khả năng Đa Địa lý, <a href="https://go.microsoft.com/fwlink/?linkid=872776">hãy xem Mục Khả năng Đa Địa lý Exchange Online.</a>  </li>
</ul>
Phần mềm máy khách trực tuyến như Project for Office 365, Outlook for Windows, Outlook for iOS và Android, máy khách đồng bộ OneDrive for Business, Power BI Desktop và Skype for Business phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy khách Microsoft 365 Office <a href="https://go.microsoft.com/fwlink/?LinkID=723597">.</a>  </td>
</tr>

<td><strong>Bộ bảo vệ Microsoft dành cho Office 365</strong></td>
<td>  Để biết thêm thông tin, xem <strong>mục Bộ bảo vệ Microsoft để biết Office 365</strong> về Bảo mật và Tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>.  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Quản trị Thông tin Microsoft</strong></td>
<td>  Để biết thêm thông tin, hãy xem <strong> mục Quản trị Thông tin của Microsoft</strong> trong bảo mật và tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>. 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Microsoft Information Protection</strong></td>
<td>  
Để biết thêm thông tin, hãy xem <strong>mục Bảo vệ Thông tin của Microsoft </strong> trong bảo mật và tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>.

</td>
<td>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Xác nhận các yêu cầu tối thiểu Exchange Online nhóm, SharePoint Online, Office 365 và Azure AD để hỗ trợ Teams.  </li>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Thiết lập DNS.  </li>
<li>  Xác nhận Teams được bật trên đối tượng thuê Office 365 bạn.  </li>
<li>  Bật hoặc tắt giấy phép người dùng.  </li>
<li>  Đánh giá mạng cho Teams:
<ul>
<li>  Kiểm tra cổng và điểm cuối.  </li>
<li>  Kiểm tra chất lượng kết nối.  </li>
<li>  Ước tính băng thông.  </li>
</ul>
<ul>
<li>  Đặt cấu hình cho Teams dụng mới (Teams web app, Teams trên máy tính và Teams cho ứng dụng iOS và Android).  </li>
</ul>
Nếu có thể, chúng tôi cũng cung cấp hướng dẫn cho:
<ul>
<li>  Microsoft Teams Thiết bị Phòng:  </li>
<ul>
<li>  Việc tạo tài khoản trực tuyến cần thiết cho các thiết bị điện thoại và phòng hội thảo được hỗ trợ được liệt kê <a href="https://go.microsoft.com/fwlink/?linkid=2066478">trong danh mục Teams của thiết bị.</a>  </li>
<li>  Trợ giúp từ xa với cấu hình phía dịch vụ của các thiết Phòng họp Microsoft Teams được chứng nhận.  </li>
<li>  Cho phép Hội thảo Âm thanh:  </li>
<li>  Thiết lập tổ chức cho thiết đặt mặc định cầu nối hội thảo.  </li>
<li>  Gán cầu nối hội thảo cho người dùng được cấp phép.  </li>
</ul>
<li>  Hệ thống Điện thoại:
<ul>
<li>  Thiết lập tổ chức cho thiết đặt mặc định Cloud Voice.  </li>
<li>  Hướng dẫn Gói Gọi điện (thị<a href="https://go.microsoft.com/fwlink/?linkid=2066478">trường có sẵn</a>):
<ul>
<li>  Gán số cho người dùng được cấp phép.  </li>
<li>  Hướng dẫn nối cổng số nội bộ thông qua giao diện người dùng (UI) tối đa là 999.  </li>
<li>  Số lượng hỗ trợ yêu cầu dịch vụ nối cổng số nội bộ (SR) trên 999.  </li>
</ul></li>
<li>  Hướng dẫn Định tuyến Trực tiếp:
<ul>
<li>  Hướng dẫn thiết lập tổ chức dành cho thiết kế Định tuyến Trực tiếp các kịch bản do đối tác lưu trữ hoặc các kịch bản do khách hàng triển khai cho tối đa 10 site.  </li>
<li> Xem lại cấu hình Bộ điều khiển Đường viền Phiên (SBC). </li>

<li> Trợ giúp từ xa với cấu hình kế hoạch quay số. </li>

<li> Cấu hình định tuyến thoại.</li>

<li> Tối ưu hóa bỏ qua máy chủ trung gian và tối ưu hóa phương tiện cục bộ. </li>

</ul></li>
</ul></li>
<li>  Bật các Teams kiện trực tiếp.  </li>
<li>  Thiết lập và tích hợp tổ chức vào Microsoft Stream.  </li>
<li>  Hướng dẫn chuyển Skype for Business chuyển Teams trang.  </li>
</ul></td>
<td><ul>
<li>  Danh tính được bật trong Azure AD cho Office 365.  </li>
<li>  Người dùng được kích hoạt SharePoint Online.  </li>
<li>  Exchange hiện diện (trực tuyến và tại chỗ trong cấu hình Exchange kết hợp).  </li>
<li>  Được bật cho Office 365 Nhóm.  </li>
</ul>
  <strong>Lưu ý:</strong> Nếu người dùng chưa được gán và kích hoạt với giấy phép SharePoint Online, họ sẽ không có dung lượng OneDrive for Business lưu trữ Office 365. Tính năng chia sẻ tệp vẫn tiếp tục hoạt động trong Kênh, nhưng người dùng không thể chia sẻ tệp trong Trò chuyện mà không OneDrive for Business lưu trữ trong Office 365. Teams không hỗ trợ SharePoint tại chỗ.  <br>
  <strong>Lưu ý:</strong> Trạng thái lý tưởng là tất cả người dùng đều có hộp thư ở nhà trên Exchange Online. Người dùng có hộp thư tại cơ sở phải được đồng bộ hóa danh tính với thư mục Office 365 thông qua Azure AD Kết nối. Đối với những Exchange khách hàng kết hợp này, nếu hộp thư của người dùng là tại chỗ, người dùng không thể thêm hoặc cấu hình Trình kết nối.  
  Trình cài đặt cho máy khách Microsoft Teams Windows máy tính Mac và Máy Mac có thể được tải xuống từ <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
</tr>

<tr class="even">
<td><strong>Outlook cho iOS và Android</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Tải xuống Outlook cho iOS và Android từ Apple App Store và Google Play.  </li>
<li>  Cấu hình tài khoản và truy nhập hộp Exchange Online của bạn.  </li>
<li>  Bảo mật trên Outlook di động <a href="/exchange/clients-and-mobile-in-exchange-online/outlook-for-ios-and-android/secure-outlook-for-ios-and-android">(xem mục Bảo Outlook cho iOS</a> và Android trong Exchange Online để biết thêm thông tin).  </li>
</ul></td>
<td><ul>
<li>  Danh tính được bật trong Azure AD cho Office 365.  </li>
<li>  Exchange Online cấu hình và giấy phép đã gán.  </li>
</ul></td>
</tr>
<tr class="odd">
<td><strong>Power BI</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Gán giấy phép Power BI.  </li>
<li>  Triển khai ứng Power BI Desktop cụ thể.  </li>
</ul></td>
<td>Phần mềm máy khách trực Power BI Desktop phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 và Office.</a></td>
</tr>
<tr class="even">
<td><strong>Project Online</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Xác minh chức SharePoint cơ bản mà Project Online phụ thuộc.  </li>
<li>  Thêm dịch vụ Project Online vào đối tượng thuê của bạn (bao gồm thêm đăng ký cho người dùng).  </li>
<li>  Thiết lập Nhóm Tài nguyên Doanh nghiệp (ERP).  </li>
<li>  Tạo dự án đầu tiên của bạn.  </li>
</ul></td>
<td>Phần mềm máy khách trực Project for Office 365 phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 và Office.</a></td>
</tr>
<tr class="odd">
<td><strong>Project Online Professional và Premium</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Giải quyết các vấn đề về triển khai.  </li>
<li>  Gán giấy phép người dùng cuối bằng cách sử dụng Trung Microsoft 365 quản trị chính và Windows PowerShell.  </li>
<li>  Cài Project Online trên Máy khách trên máy tính từ Office 365 cổng thông tin bằng Click-to-Run.  </li>
<li>  Đặt cấu hình thiết đặt cập nhật bằng cách sử Office 365 Công cụ Triển khai.  </li>
<li>  Thiết lập một máy chủ phân phối tại chỗ duy nhất cho máy khách Project Online trên máy tính, bao gồm hỗ trợ tạo tệp configuration.xml để sử dụng với Công cụ Triển khai Office 365.  </li>
<li>  Kết nối Project Online trên Máy khách để bàn Project Online Professional hoặc Project Online Premium.  </li>
</ul></td>
<td>Phần mềm máy khách trực Project for Office 365 phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 và Office.</a></td>
</tr>
<tr class="even">
<td><strong>SharePoint Trực tuyến và Trực OneDrive for Business</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Thiết lập DNS.  </li>
<li>  Cấu hình cổng tường lửa.  </li>
<li>  Cấp phép và người dùng.  </li>
<li>Cho phép tạo site cho người quản SharePoint Online của bạn.</li>
<li>Lập kế hoạch tuyển tập site.</li>
<li>Bảo mật nội dung và quản lý quyền.</li>
<li>Đặt cấu hình SharePoint năng Online.</li>
<li>  Configuring SharePoint hybrid features, like hybrid search, hybrid sites, hybrid taxonomy, content types, hybrid self-service site creation (SharePoint Server 2013 only), extended app launcher, hybrid OneDrive for Business, and extranet sites.  </li>
<li>  Phương pháp di chuyển của bạn.  </li>
</ul>
Hướng dẫn bổ sung được cung cấp OneDrive for Business tùy thuộc vào phiên bản SharePoint của bạn, như:
<ul>
<li>  Xác định các tùy chọn tích hợp và xem lại cơ sở hạ tầng mạng và băng thông tại cơ sở cũng như trực tuyến.  </li>
<li>  Cài SharePoint Online 2013 SP1 (nếu có), lập kế hoạch và thực hiện các yêu cầu về đồng bộ hóa và danh tính cũng như xác định máy khách đồng bộ OneDrive for Business của bạn.  </li>
<li>  Lập kế hoạch và thực hiện một triển khai duy nhất cho tất cả người dùng (hoặc triển khai theo giai đoạn).  </li>
<li>  Gán giấy phép, chuyển hướng Site của Tôi và thư viện tài liệu cá nhân tới Office 365 (áp dụng cho SharePoint Online 2013), thiết lập khán giả để kiểm soát quyền truy nhập vào OneDrive (áp dụng cho SharePoint Online 2013).  </li>
<li>Chuyển hướng hoặc di chuyển thư mục đã biết đến OneDrive.</li>
<li>  Triển khai đồng bộ OneDrive for Business khách hàng mới.  </li>
</ul>
  <strong>Di chuyển dữ liệu</strong>  <br>
Để biết thông tin về việc sử dụng lợi ích FastTrack cho việc di chuyển dữ liệu sang Office 365, hãy xem <a href="/fasttrack/data-migration">Di chuyển Dữ liệu</a>.
</ul></td>
<td><br><strong>Đối với SharePoint kết hợp:</strong>  
<ul>
<li>  SharePoint cấu hình kết hợp bao gồm cấu hình tìm kiếm hỗn hợp, site, tư cách phân loại, kiểu nội dung, OneDrive for Business, công cụ khởi động ứng dụng mở rộng, các site mạng nội bộ mở rộng và tạo site tự phục vụ được kết nối từ môi trường tại chỗ đến một môi trường SharePoint Online đích duy nhất.  </li>
</ul>
  <strong>Lưu ý:</strong> Tính năng tạo site tự phục vụ không nằm trong phạm vi các máy chủ tại chỗ chạy SharePoint 2013.  
<ul>
<li>  Để bật SharePoint kết hợp, bạn phải có một trong các môi trường SharePoint Server tại chỗ sau: 2013, 2016 hoặc 2019.  </li>
</ul>
  <strong>Lưu ý:</strong> Nâng cấp môi trường SharePoint tại chỗ cho Máy SharePoint không có phạm vi. Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp. Để biết thêm thông tin, hãy xem <a href="https://go.microsoft.com/fwlink/?linkid=853548">Mức cập nhật công khai tối thiểu cho các SharePoint hợp khác.</a><em></em>  <br>
  <strong>Lưu ý:</strong> Để biết thông tin về Khả năng Đa Địa lý, hãy <a href="https://go.microsoft.com/fwlink/?linkid=831056">xem Mục Multi-Geo Capabilities trong OneDrive và SharePoint Online Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Chúng tôi cung cấp hướng dẫn từ xa để bật dịch Yammer Enterprise này.  
</td>
<td>Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong Yêu cầu hệ thống cho máy <a href="https://go.microsoft.com/fwlink/?LinkID=723597">Microsoft 365 và Office.</a></td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Enterprise Mobility + Security 

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) và Azure AD Premium</strong></td>
<td>  Để biết thêm thông tin, hãy <strong>xem Azure Active Directory (Azure AD) và Azure AD Premium</strong> mục Bảo mật và Tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>.</td>
<td></td>
</tr>
<tr class="odd">#security-and-compliance
<td><strong>Azure Information Protection </strong></td>
<td>  Để biết thêm thông tin về Azure Information Protection, hãy xem <strong>mục Bảo vệ Thông tin của Microsoft</strong> trong Bảo mật và Tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>.  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft Intune</strong></td>
<td>  Để biết thêm thông tin, hãy <strong>xem Microsoft Intune</strong> phần Bảo mật và <a href="/fasttrack/products-and-capabilities#security-and-compliance">Tuân thủ</a>.
  </td>
<td>  
  
</td>
</tr>
</tbody>
</table>

## <a name="windows-10"></a>Windows 10

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn nâng cấp từ Windows 7 Professional và Windows 8.1 Professional lên Windows 10 Enterprise.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Hiểu ý định Windows 10 của bạn.  </li>
<li>  Đánh giá môi trường nguồn và yêu cầu (đảm bảo rằng Trình quản lý Cấu hình Điểm cuối của Microsoft được nâng cấp lên mức bắt buộc để hỗ trợ triển khai Windows 10 này).  </li>
<li>  Triển khai và Windows 10 Enterprise sử dụng Ứng dụng Microsoft 365 Trình quản lý Cấu hình Điểm cuối của Microsoft Microsoft 365.  </li>
<li>  Đề xuất các tùy chọn để bạn đánh giá các Windows 10 dụng của mình.  </li>
<li>  Cho phép sử dụng Phân tích màn hình nền và hướng dẫn thông qua việc tạo kế hoạch triển khai Phân tích Màn hình nền.  </li>
<li>  Ứng dụng Microsoft 365 tính tương thích bằng cách tận dụng bảng điều khiển Office 365 sẵn sàng trong Trình quản lý Cấu hình hoặc Bộ công cụ Sẵn sàng độc lập cho Office cộng với hỗ trợ triển khai Ứng dụng Microsoft 365.  </li>
<li>  Tạo danh sách kiểm tra khắc phục về những điều bạn cần làm để đưa môi trường nguồn của bạn đến tối thiểu các yêu cầu tối thiểu để triển khai thành công.  </li>
<li>  Cung cấp hướng dẫn nâng cấp cho các thiết bị hiện có của bạn để Windows 10 Enterprise nếu chúng đáp ứng các yêu cầu về phần cứng thiết bị cần thiết.  </li>
<li>  Cung cấp hướng dẫn nâng cấp để hỗ trợ chuyển động triển khai hiện có của bạn. FastTrack đề xuất và cung cấp hướng dẫn nâng cấp tại chỗ cho máy Windows 10. Hướng dẫn cũng có sẵn để cài Windows đặt hình ảnh sạch và trong Windows năng triển khai Autopilot.  </li>
<li>  Triển khai Ứng dụng Microsoft 365 sử dụng Trình quản lý Cấu hình như là một phần của quá trình triển Windows 10 công việc.   </li>
<li>  Cung cấp hướng dẫn giúp tổ chức của bạn luôn cập nhật thông tin về Windows 10 Enterprise và Ứng dụng Microsoft 365 sử dụng môi trường Trình quản lý Cấu hình hiện có của bạn Microsoft 365.  </li>
</ul>
  
<strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li>  Nâng cấp Trình quản lý Cấu hình thành Nhánh Hiện tại.  </li>
<li>  Tạo hình ảnh tùy chỉnh để Windows 10 triển khai.  </li>
<li>  Tạo và hỗ trợ tập lệnh triển khai để Windows 10 triển khai.  </li>
<li>  Converting a Windows 10 system from BIOS to Unified Extensible Firmware Interface (UEFI).  </li>
<li>  Bật tính Windows 10 năng bảo mật.  </li>
<li>  Đặt cấu hình Windows lệnh Cho việc khởi động Môi trường Thực thi Trước (PXE) cho Môi trường Thực thi Tiền khởi động.  </li>
<li>  Sử dụng Bộ công cụ Triển khai Microsoft (MDT) để chụp và triển khai các Windows 10 ảnh.  </li>
<li>  Sử dụng Công cụ Di chuyển Trạng thái Người dùng (USMT).  </li>
</ul>
Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về các dịch vụ này.  </td>
<td>  Để nâng cấp PC, bạn phải đáp ứng các yêu cầu sau:
<ul>
<li>  HĐH Nguồn: Windows 7 Enterprise hoặc Professional, Windows 8.1 Enterprise Professional.  </li>
<li>  Thiết bị: Yếu tố biểu mẫu máy tính để bàn, sổ tay hoặc máy tính bảng.  </li>
<li>  HĐH Đích: Cửa sổ 10 Enterprise.  </li>
</ul>
Để nâng cấp cơ sở hạ tầng, bạn phải đáp ứng các yêu cầu sau:
<ul>
<li>  Trình quản lý Cấu hình Microsoft Endpoint.  </li>
<li>  Phiên bản Bộ quản lý Cấu hình phải được hỗ trợ bởi Windows 10 đích mới. Để biết thêm thông tin, hãy xem bảng hỗ trợ Trình quản lý Cấu <a href="/sccm/core/plan-design/configs/support-for-windows-10">hình tại Hỗ trợ cho Windows 10 trong Trình quản lý Cấu hình.</a>  </li>
</ul>

<tr class="odd">
<td><strong>Bộ bảo vệ Microsoft dành cho Điểm cuối</strong></td>
<td>  Để biết thêm thông tin, xem <strong> mục Bộ bảo vệ Microsoft dành cho điểm cuối trong</strong> mục Bảo mật và Tuân <a href="/fasttrack/products-and-capabilities#security-and-compliance">thủ</a>.</td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Windows Màn hình nền Ảo

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows Màn hình nền Ảo</strong></td>
<td><p>Chúng tôi cung cấp hướng dẫn triển khai để triển khai Windows trên Máy tính Ảo (dịch vụ ảo hóa máy tính và ứng dụng). Windows Màn hình nền Ảo tận dụng lợi thế của trải Windows 10 nhiều phiên và được tối ưu hóa cho Ứng dụng Microsoft 365 Enterprise với khả năng bảo mật và quản lý tích hợp Microsoft 365.</p>
<p>Chúng tôi cung cấp hướng dẫn từ xa cho:</p>
<ul>
<li>Triển khai môi trường Windows nền Ảo của bạn với Windows 10 Enterprise nhiều phiên và Ứng dụng Microsoft 365 cho Doanh nghiệp theo cách sau:
<ul>
<li>Hình ảnh Azure Marketplace.</li>
<li>Hình ảnh được chia sẻ.</li>
<li>Office Bộ công cụ Triển khai (ODT).</li>
</ul></li>
<li>Cấu hình FSLogix:
<ul>
<li>Triển khai Tác tử FSLogix với Bộ chứa Hồ sơ.</li>
<li>Triển khai Tác tử FSLogix với Office container.</li>
<li>Cấu hình thư mục FSLogix với loại trừ nội dung.</li>
</ul></li>
<li>Triển khai Microsoft Edge.</li>
<li>Triển khai Microsoft Teams.</li>
<li>Kết nối bằng cách Windows máy khách Màn hình Nền Ảo.</li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi</strong>
<ul>
<li>Project triển khai Máy tính Ảo của khách hàng Windows khách hàng.</li>
<li>Ảo hóa và triển khai ứng dụng của bên thứ ba.</li>
<li>Hình ảnh tùy chỉnh.</li>
<li>Di chuyển và kịch bản liên quan đến VMware và Citrix.</li>
<li>Kịch bản Linux.</li>
<li>Chuyển đổi hoặc di chuyển hồ sơ người dùng.</li>
</ul>
Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về các dịch vụ này.</td>
<td>Bạn nên có những nội dung sau:
<ul>
<li><a href="/azure/virtual-desktop/overview#requirements">Windows cầu cấp phép Máy tính Ảo.</a></li>
<li>Kết nối mạng Azure:
<ul>
<li>Tạo và làm con bằng mạng ảo (VNET).</li>
<li>Tường lửa và nhóm bảo mật mạng.</li>
<li>VPN và ExpressRoute.</li>
<li>Định tuyến đến Azure từ tại chỗ.</li>
<li>Quy tắc tường lửa để cho phép kết nối Windows Trên Máy tính Ảo.
</ul>
Để biết thêm thông tin, hãy xem Máy <a href="//azure/virtual-desktop/overview#supported-remote-desktop-clients">khách Từ xa được hỗ trợ</a>.
</ul>
<ul><li>Thiết lập chung Azure AD:
<ul>
<li>Chiến lược định <i>danh (bạn chỉ có thể sử dụng một trong ba tùy chọn sau):</i>
<ul>
<li>Active Directory với Azure AD Kết nối trong Azure.</li>
<li>Active Directory với Azure AD Kết nối tại chỗ qua VPN hoặc ExpressRoute.</li>
<li>Dịch vụ Miền Active Directory (AD DS).</li>
</ul></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="app-assure"></a>Đảm bảo cho ứng dụng


<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Đảm bảo cho ứng dụng</strong></td>
<td>  Đảm bảo Ứng dụng là một dịch vụ được thiết kế để giải quyết các sự cố về Windows 10 và Ứng dụng Microsoft 365 tương thích với ứng dụng. Khi bạn yêu cầu dịch vụ Đảm bảo ứng dụng, chúng tôi sẽ làm việc với bạn để giải quyết các sự cố ứng dụng hợp lệ mà không mất thêm chi phí cho bạn với đăng ký đủ điều kiện. Chúng tôi cũng cung cấp hướng dẫn cho những khách hàng gặp phải sự cố về tính tương thích khi triển khai Windows Màn hình nền Ảo và Microsoft Edge và nỗ lực hết sức hợp lý để giải quyết các sự cố về tương thích. Chúng tôi cung cấp trợ giúp khắc phục cho các ứng dụng được triển khai trên các sản phẩm Microsoft sau:
<ul>
<li>  <strong>Windows 10</strong> tính (bao gồm các thiết bị ARM64)</li>
<li> <strong>Ứng dụng Microsoft 365</strong>  </li>
<li>  <strong>Microsoft Edge -</strong> Để biết hướng dẫn triển khai, <a href="/DeployEdge/microsoft-edge-channels">hãy xem mục Tổng quan về Microsoft Edge kênh.</a>  </li>
<li>  <strong>Windows Nền Ảo</strong> - Để biết thêm thông tin, <a href="/azure/virtual-desktop/overview">hãy xem mục Máy tính Windows Ảo là gì?</a> và Câu Windows 10 Enterprise hỏi thường gặp nhiều <a href="/azure/virtual-desktop/windows-10-multisession-faq">phiên.</a>  </li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li>  Kiểm kê và kiểm tra ứng dụng để xác định xem ứng dụng nào và không hoạt động trên các Windows 10 và Ứng dụng Microsoft 365. Để biết thêm hướng dẫn về quy trình này, hãy truy nhập Trung tâm <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Triển khai Máy tính</a>để bàn . Nếu bạn quan tâm đến hoạt động đánh giá tính sẵn sàng của nâng cấp chuyên sâu, hãy hoàn thành biểu mẫu Yêu cầu Khách hàng <a href="https://go.microsoft.com/fwlink/?linkid=2053818">đối với Đánh giá Máy tính Hiện</a> đại.</li>
<li>  Nghiên cứu các ứng dụng ISV của bên thứ ba để Windows 10 các tuyên bố tương thích và hỗ trợ khác. Để biết thêm thông tin, hãy xem Phân <a href="/sccm/desktop-analytics/overview">tích Màn hình nền</a>.</li>
<li>Dịch vụ chỉ đóng gói ứng dụng. Tuy nhiên, các ứng dụng nhóm Đảm bảo rằng chúng tôi đã khắc phục các Windows 10 để đảm bảo chúng có thể được triển khai trong môi trường của khách hàng.</li>
</ul>

<strong>Trách nhiệm của khách hàng bao gồm</strong>  
<ul>
<li>  Tạo thư mục ứng dụng.</li>
<li>  Xác thực các ứng dụng đó trên Windows 10 và Ứng dụng Microsoft 365.</li>
</ul>
<strong>Lưu ý:</strong>  Microsoft không thể thực hiện thay đổi đối với mã nguồn của bạn. Tuy nhiên, nhóm Đảm bảo ứng dụng có thể cung cấp hướng dẫn cho các nhà phát triển ứng dụng nếu mã nguồn sẵn dùng cho các ứng dụng của bạn. 


  Liên hệ với Đối <a href="https://go.microsoft.com/fwlink/?linkid=2080150">tác của Microsoft để</a> được trợ giúp về các dịch vụ này.  </td>

</td>
<td><strong>Windows 10 và Ứng dụng Microsoft 365</strong>
<ul>
<li>  
  Các ứng dụng đã làm việc trên Windows 7, Windows 8.1, Office 2010 và Office 2013 cũng hoạt động trên Windows 10 và Ứng dụng Microsoft 365.  
  </li>
</ul>
<strong>Windows 10 trên ARM</strong>
<ul>
<li>  
Ứng dụng hoạt động trên Windows 7, Office 2010 hoặc phiên bản mới hơn cũng hoạt động trên thiết Windows 10 và Ứng dụng Microsoft 365 trên thiết bị ARM64. 
  </li>
</ul>
  <strong>Lưu ý:</strong> 
<ul>
<li> Tính năng mô phỏng x64 (64 bit) sẵn dùng trong bản xem trước dành cho khách hàng tham gia vào <a href="https://insider.windows.com/">Chương trình Người dùng nội bộ Windows .</a>  </li>
<li>  
 Đối với khách hàng Windows dùng nội bộ trên Windows 10 2004 (trở lên), ARM64 Photoshop được hỗ trợ sử dụng Gói Tương thích OpenCL và <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">OpenGL.</a> 
  </li>
<li>  
  Khách hàng trong Chương trình Người Windows Nội bộ của Office có thể tải xuống phiên bản Người dùng nội bộ của Gói Tương thích OpenCL và OpenGL để sử dụng với các ứng dụng bổ sung.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Nếu các ứng dụng web hoặc trang web của bạn hoạt động trên Internet Explorer 11, các phiên bản được hỗ trợ của Google Chrome hoặc bất kỳ phiên bản Microsoft Edge nào, các ứng dụng hoặc trang web đó cũng sẽ hoạt động với các ứng dụng Microsoft Edge.  
  </li>
<li>  
  Khi web không ngừng phát triển, hãy đảm bảo xem lại danh sách đã phát hành các thay đổi về tính tương thích đối với tính tương thích của trang <a href="/microsoft-edge/web-platform/site-impacting-changes">web Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Windows Màn hình nền Ảo</strong>  
<ul>
<li>  
  Các ứng dụng được ảo hóa chạy trên Windows Server Remote Desktop Session Host (RDSH) cũng chạy trên Windows 10 Enterprise nhiều phiên như là một phần của Windows Bàn làm việc Ảo.  
  </li>
<li>  
  Các ứng dụng chạy trên bất kỳ môi trường cơ sở hạ tầng máy tính ảo (VDI) Windows 7 hoặc Windows 10 nào cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như là một phần của Windows Bàn làm việc Ảo.  
  </li>
<li>  
  Ứng dụng chạy trên Windows 7 hoặc Windows 10 máy khách cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như một phần của ứng dụng Windows Bàn làm việc Ảo.  
  </li>
</ul>
  <strong>Lưu ý:</strong> Windows 10 Enterprise loại trừ và giới hạn tương thích nhiều phiên bao gồm:
<ul>
<li>  
  Chuyển hướng phần cứng hạn chế.  
  </li>
<li>  
  Các ứng dụng chuyên sâu A/V có thể thực hiện ở khả năng giảm.  
  </li>
<li>  
  Các ứng dụng 16-bit không được hỗ trợ cho phiên bản 64-bit Windows Bàn làm việc Ảo.  
  </li>
</ul></td>
</tr>
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Kỳ vọng môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Chúng tôi cung cấp hướng dẫn triển khai và tiếp nhận từ xa cũng như hỗ trợ tương thích cho: <ul> <li>Triển khai Microsoft Edge trên Windows 10 với Microsoft Endpoint Manager (Trình quản lý Cấu hình Điểm cuối của Microsoft hoặc Intune).  </li>
<li>  Đặt cấu hình cho Microsoft Edge (sử dụng chính sách nhóm hoặc cấu hình ứng dụng Intune và chính sách ứng dụng).  </li>
<li>  Kiểm kê danh sách các site có thể yêu cầu sử dụng trong chế độ Internet Explorer.  </li>
<li>  Bật chế độ Internet Explorer với Danh sách Site Doanh nghiệp hiện có. (Để biết thêm thông tin, hãy xem <a href="/fasttrack/process-and-expectations#engaging-fasttrack">mục Tham gia FastTrack.</a> Ngoài ra, nếu bạn có ứng dụng web hoặc trang web hoạt động với Internet Explorer hoặc Google Chrome và bạn gặp phải sự cố về tính tương thích, chúng tôi cung cấp hướng dẫn để giải quyết sự cố mà không mất thêm phí. Để yêu cầu hỗ trợ tương thích cho Đảm bảo Ứng dụng, hãy đăng nhập vào <a href="https://fasttrack.microsoft.com/portal#/signin">cổng thông tin FastTrack để</a> bắt đầu sự gắn kết.  </li>
<li> Hướng dẫn lập kế hoạch cho hướng dẫn tiếp nhận và cấu hình Microsoft Search dành cho thẻ đánh dấu Tìm kiếm của Microsoft.</li>
</ul>

<strong>Sau đây là nằm ngoài phạm vi </strong>  
<ul>
<li>Project lý hoạt động triển khai công việc của Microsoft Edge khách hàng.</li>
<li>  Hỗ trợ tại chỗ.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
