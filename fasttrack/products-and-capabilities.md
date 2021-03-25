---
title: Các sản phẩm và chức năng
ms.author: v-bermic
author: rberg-steyer
manager: jimmuir
ms.date: 3/24/2021
ms.audience: ITPro
ms.topic: conceptual
ms.service: o365-administration
localization_priority: Normal
ms.collection: FastTrack
description: Chủ đề này bao gồm chi tiết về các tình huống khối lượng công việc được hỗ trợ bởi FastTrack và các kỳ vọng của môi trường nguồn cần thiết trước khi chúng tôi có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo một kế hoạch khắc phục sự kiện sẽ giúp môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để onboarding thành công.
ms.openlocfilehash: 2bfca103fd9c58d95d9ba4a750e446a6e93b5719
ms.sourcegitcommit: 31d2c36fd00f47330dc2c90a646f8ce8a9687e1d
ms.translationtype: MT
ms.contentlocale: vi-VN
ms.lasthandoff: 03/24/2021
ms.locfileid: "51188111"
---
# <a name="products-and-capabilities"></a>Các sản phẩm và chức năng

## <a name="services-and-scenarios-supported-by-fasttrack"></a>Các dịch vụ và tình huống được hỗ trợ bởi FastTrack 

Chủ đề này bao gồm chi tiết về các tình huống khối lượng công việc được hỗ trợ bởi FastTrack và các kỳ vọng của môi trường nguồn cần thiết trước khi chúng tôi có thể bắt đầu. Dựa trên thiết lập hiện tại của bạn, chúng tôi làm việc với bạn để tạo một kế hoạch khắc phục sự kiện sẽ giúp môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để onboarding thành công.

Fasttrack cung cấp hướng dẫn để giúp bạn đầu tiên với các chức năng cốt lõi (phổ biến cho tất cả các dịch vụ trực tuyến của Microsoft) và sau đó với triển khai từng dịch vụ đủ điều kiện:

  - [Thống](#general)
  - [Bảo mật và Tuân thủ](#security-and-compliance)
  - [Office 365](#office-365)
  - [Tính năng di động doanh nghiệp + bảo mật](#enterprise-mobility--security)
  - [Windows 10](#windows-10)
  - [Máy tính chạy Windows ảo](#windows-virtual-desktop)
  - [Đảm bảo cho ứng dụng](#app-assure)
  - [Microsoft Edge](#microsoft-edge)

> [!NOTE]
> Để biết thông tin về các kỳ vọng môi trường nguồn cho chính phủ Hoa Kỳ của Office 365, hãy xem các [kỳ vọng môi trường nguồn cho chính phủ office 365 US](https://docs.microsoft.com/fasttrack/us-gov-appendix-source-environment-expectations). 
 
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
<li> Việc chọn và bật trải nghiệm xác thực thuận tiện hơn cho người dùng của bạn có xác thực passwordless (nhanh chóng nhận dạng trực tuyến (FIDO) 2 hoặc ứng dụng Microsoft Authenticator).</li>
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
<li>  Nhiệm vụ được yêu cầu cho cấu hình đối tượng thuê và tích hợp với Azure Active Directory, nếu cần thiết.   </li>
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
<li>  Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.  </li>
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

## <a name="security-and-compliance"></a>Bảo mật và Tuân thủ

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

<td><strong>Azure Active Directory (Azure AD) và Azure AD Premium</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa để bảo vệ danh tính đám mây của bạn cho các kịch bản sau đây.  

 <br/>

<strong>Cơ sở hạ tầng tổ chức bảo mật</strong>  </ul>
<ul>
<li>  Cấu hình và bật xác thực mạnh cho các danh tính của bạn, bao gồm việc bảo vệ bằng Azure xác thực đa yếu tố (MFA) (chỉ dành cho điện toán đám mây), ứng dụng Microsoft Authenticator và đăng ký kết hợp cho Azure MFA và đặt lại mật khẩu tự phục vụ (SSPR).  </li>
<li> Triển khai ứng dụng FIDO2 hoặc Microsoft Authenticator. </li>
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
  Quản lý và kiểm soát quyền truy nhập vào các tài khoản quản trị đặc quyền bằng quản lý định danh Azure AD đặc quyền.  
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
<td><strong>Bảo vệ thông tin Azure </strong></td>
<td>  Để biết thêm thông tin về bảo vệ thông tin Azure, hãy xem mục <strong>bảo vệ thông tin của Microsoft</strong> trong bảng này.

  </td>
<td>  
  <tr class="odd">
<td><strong>Khám phá & trả lời</strong></td>
<td>  

<strong>Khám phá điện tử nâng cao</strong>
  
Chúng tôi cung cấp hướng dẫn từ xa cho: 
<ul>
<li>  Tạo một trường hợp mới.   </li>
<li>  Đặt giam giữ.  </li>
<li>  Đang thực hiện tìm kiếm. </li>
<li>  Thêm kết quả tìm kiếm vào tập hợp xem lại. </li>
<li>  Đang chạy phân tích trên bộ xem lại.  </li>
<li>  Xem lại và gắn thẻ tài liệu.  </li>
<li>  Xuất dữ liệu từ bộ xem lại. </li>
<li>  Nhập dữ liệu không phải của Office 365. </li>
</ul>

<strong>Kiểm toán nâng cao</strong> (chỉ được hỗ trợ trong E5)

Chúng tôi cung cấp hướng dẫn từ xa cho:  
<ul>
<li> Bật kiểm tra nâng cao.</li>
<li> Thực hiện một giao diện người dùng Nhật ký kiểm tra tìm kiếm và các lệnh PowerShell kiểm tra cơ bản.</li>
</ul>

<strong> Trình quản lý tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các kiểu vai trò.  </li>
<li> Thêm và cấu hình Các đánh giá.</li>
<li> Đánh giá việc tuân thủ bằng việc thực hiện hành động cải thiện và xác định cách thức làm ảnh hưởng đến điểm tuân thủ của bạn.</li>
<li> Xem lại ánh xạ điều khiển được dựng sẵn và đánh giá các điều khiển.</li>
<li> Tạo một báo cáo trong một đánh giá.</li>
</ul>

<strong>Sau đây là phạm vi </strong> 
<ul>
<li> Kịch bản tùy chỉnh hoặc mã hóa.</li>
<li> Khám phá điện tử API. </li>
<li> Kết nối dữ liệu. </li>
<li> Ranh giới tuân thủ và bộ lọc bảo mật.</li>
<li> Điều tra dữ liệu.</li>
<li> Các yêu cầu chủ đề dữ liệu.</li>
<li> Thiết kế, kiến trúc sư và xem xét tài liệu của bên thứ ba.</li>
<li> Tuân thủ các quy định và yêu cầu của khu vực.</li>
<li> Thực hiện các hành động cải thiện được đề xuất để đánh giá trong trình quản lý tuân thủ.</li>
</ul>
</td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>

<tr class="odd">
<td><strong>Quản lý rủi ro người dùng nội bộ</strong></td>

<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li> Tạo chính sách và xem lại thiết đặt.</li>
<li> Truy nhập báo cáo và cảnh báo.</li>
<li> Tạo trường hợp.</li>
<li> Tạo mẫu thông báo.</li>
<li> Hướng dẫn tạo đường kết nối tài nguyên nhân sự (HR).</li>
</ul>

<strong> Tuân thủ liên lạc </strong> 

Chúng tôi cung cấp hướng dẫn từ xa cho: 
<ul>
<li> Tạo chính sách và xem lại thiết đặt.</li>
<li> Truy nhập báo cáo và cảnh báo.</li>
<li> Tạo mẫu thông báo.</li>
</ul>

<strong> Trình quản lý tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các kiểu vai trò.  </li>
<li> Thêm và cấu hình Các đánh giá.</li>
<li> Đánh giá việc tuân thủ bằng việc thực hiện hành động cải thiện và xác định cách thức làm ảnh hưởng đến điểm tuân thủ của bạn.</li>
<li> Xem lại ánh xạ điều khiển được dựng sẵn và đánh giá các điều khiển.</li>
<li> Tạo một báo cáo trong một đánh giá.</li>
</ul>

<strong>Sau đây là phạm vi </strong> 
<ul>
<li> Tạo và quản lý dòng điện tự động hóa.</li>
<li> Các đường kết nối dữ liệu (ngoài trình kết nối nhân sự). </li>
<li> Cấu hình biểu thức thông thường tùy chỉnh (RegEx).</li>
<li> Thiết kế, kiến trúc sư và xem xét tài liệu của bên thứ ba.</li>
<li> Các rào cản thông tin.</li>
<li> Quản lý truy nhập đặc quyền.</li>
<li> Tuân thủ các quy định và yêu cầu của khu vực.</li>
<li> Thực hiện các hành động cải thiện được đề xuất để đánh giá trong trình quản lý tuân thủ.</li>
</ul></td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>
</td>
</tr>

<tr class="even">
<td><strong>Bảo vệ Microsoft 365</strong></td>

<td> <p> Microsoft 365 Defender là bộ bộ quốc phòng hợp nhất trước và sau khi có tính hợp nhất, có tính năng phát hiện, Phòng ngừa, điều tra và phản hồi qua các điểm cuối, danh tính, email và ứng dụng để cung cấp bảo vệ chống các cuộc tấn công phức tạp. Chúng tôi cung cấp hướng dẫn từ xa cho: </p> 
<ul>
<li>  Cung cấp tổng quan về Trung tâm bảo mật của Microsoft 365.  </li>
<li>  Việc xem xét các sự cố về sản phẩm, bao gồm việc tập trung vào những điều quan trọng bằng cách đảm bảo phạm vi tấn công đầy đủ, tài nguyên đã ảnh hưởng và các hành động khắc phục sự cố tự động được nhóm lại với nhau.  </li>
<li>  Chứng minh cách Microsoft 365 Defender có thể dàn cuộc điều tra tài sản, người dùng, thiết bị và hộp thư có thể đã bị xâm phạm thông qua tự động chữa bệnh. </li>
<li>  Giải thích và cung cấp các ví dụ về cách khách hàng có thể tìm kiếm chủ động săn lùng các nỗ lực xâm nhập và hoạt động vi phạm ảnh hưởng đến email, dữ liệu, thiết bị và tài khoản của bạn trên nhiều tập dữ liệu.   </li>
<li> Hiển thị khách hàng cách họ có thể xem xét và cải thiện các tư thế bảo mật của họ bằng cách sử dụng điểm số bảo mật của Microsoft.</li>
</ul>
<p><strong>Sau đây là phạm vi</strong></p>
<ul>
<li> Quản lý dự án các hoạt động khắc phục của khách hàng. </li>
<li> Quản lý đang diễn ra, phản hồi mối đe dọa và khắc phục. </li>
<li> Hướng dẫn triển khai hoặc giáo dục về:
<ul>
<li> Cách khắc phục hoặc diễn giải các kiểu cảnh báo khác nhau và theo dõi các hoạt động. </li>
<li> Cách điều tra một người dùng, máy tính, đường di chuyển bên hoặc tổ chức. </li>
<li> Săn bắn mối đe dọa tùy chỉnh.  </li>
</ul>
</li>
<li> Thông tin bảo mật và quản lý sự kiện (SIEM) hoặc tích hợp API.</li>
</td>
</tr>
<tr class="odd">
<td><strong>Bảo mật ứng dụng đám mây Microsoft</strong></td>
<td>  Microsoft Cloud App Security là một nhà môi giới bảo mật truy nhập đám mây (CASB) cung cấp khả năng hiển thị phong phú, kiểm soát việc du lịch dữ liệu và phân tích phức tạp để xác định và chống lại các mối đe dọa Cyber trên tất cả Microsoft và các dịch vụ điện toán đám mây của bên thứ ba. Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Cấu hình cổng thông tin, bao gồm:  </li>
<ul>
<li> Nhập nhóm người dùng.</li>
<li> Quản lý truy nhập và thiết đặt quản trị.  </li>
<li> Phạm vi triển khai của bạn để chọn một số nhóm người dùng nhất định để theo dõi hoặc loại trừ khỏi giám sát.</li>
<li> Thiết đặt dải IP và thẻ.</li>
<li> Cá nhân hóa trải nghiệm người dùng cuối với logo và nhắn tin tùy chỉnh của bạn.</li>
</ul>
<li> Thiết lập phát hiện đám mây để cung cấp bóng đổ bằng:</li>
<ul>
<li> Microsoft Defender cho điểm cuối.</li>
<li> Hàm zscaler.</li>
<li> iboss.</li>
</ul>
<li> Kết nối các <a href="https://docs.microsoft.com/cloud-app-security/enable-instant-visibility-protection-and-governance-actions-for-your-apps">ứng dụng nổi bật</a> bằng cách dùng bộ nối ứng dụng</li>
<li> Thiết lập điều khiển ứng dụng Access có điều kiện trong truy nhập và các cổng bảo mật ứng dụng đám mây có điều kiện để áp dụng các điều khiển phiên thời gian thực.</li>
<li> Triển khai các bảng điều khiển ứng dụng điện toán đám mây và bảng điều khiển đám mây.</li>
<li> Tùy chỉnh điểm số rủi ro ứng dụng dựa trên các ưu tiên của tổ chức bạn.</li>
<li> Tạo thẻ ứng dụng và thể loại.</li>
<li> Điều tiết và bỏ chọn các ứng dụng.</li>
<li> Sử dụng hoạt động và Nhật ký tệp.</li>
<li> Quản lý các ứng dụng OAuth.</li>
<li> Tìm hiểu về tương quan đến sự cố trong cổng thông tin Defender của Microsoft 365.</li>
<li> Cung cấp hỗ trợ cấu hình với các <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">trường hợp sử dụng 20 hàng đầu cho các trang</a> tính (bao gồm việc tạo hoặc cập nhật lên đến sáu chính sách (6), ngoại trừ: </li>
<ul>
<li> Kiểm tra cấu hình Internet của bạn dưới dạng môi trường dịch vụ (IaaS) (#18).</li>
<li> Giám sát hoạt động của người dùng để bảo vệ chống lại các mối đe dọa trong môi trường IaaS của bạn (#19).</li>
</ul>
</ul>
<p><strong>Sau đây là phạm vi</strong></p>
<ul>
<li> Quản lý dự án các hoạt động khắc phục của khách hàng.</li>
<li> Quản lý đang diễn ra, phản hồi mối đe dọa và khắc phục. </li>
<li> Thiết lập cơ sở hạ tầng, cài đặt hoặc triển khai tải lên Nhật ký tự động cho các báo cáo liên tục bằng cách dùng docker hoặc bộ thu đăng nhập. Xem <a href="https://go.microsoft.com/fwlink/p/?LinkID=2103991">20 trường hợp sử dụng hàng đầu cho</a> các chi tiết khác.</li>
<li> Tạo báo cáo tin tức phát hiện đám mây.</li>
<li> Việc sử dụng ngăn chặn sử dụng các tập lệnh chặn.</li>
<li> Kết nối các ứng dụng tùy chỉnh.</li>
<li> Tích hợp với nhà cung cấp căn cước của bên thứ ba (ISP) và các nhà cung cấp mất dữ liệu ().</li>
<li> Đào tạo hoặc hướng dẫn bao phủ săn bắn nâng cao.</li>
<li> Điều tra tự động và khắc phục sự trợ năng trong đó có Microsoft Power tự động phát sách.</li>
<li> Thông tin bảo mật và quản lý sự kiện (SIEM) hoặc tích hợp API (bao gồm Azure Sentinel).</li>
<li> Triển khai khám phá điện toán đám mây làm bằng chứng của khái niệm.</li>
</ul></td>
</tr>



<tr class="even">
<td><strong>Microsoft Defender cho điểm cuối</strong></td>
<td>  Microsoft Defender cho điểm cuối là một nền tảng được thiết kế để giúp các mạng doanh nghiệp ngăn chặn, phát hiện, điều tra và phản hồi các mối đe dọa nâng cao.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Triển khai công nghệ để bảo vệ điểm cuối của bạn.  </li>
<li>  Cấu hình bảo vệ điểm cuối và hồ sơ hạn chế thiết bị.  </li>
<li>  Đánh giá phiên bản hệ điều hành và quản lý thiết bị (bao gồm InTune, trình quản lý cấu hình Microsoft Endpoint, đối tượng chính sách Nhóm (GPOs) và các cấu hình của bên thứ ba cũng như trạng thái của dịch vụ AV bảo vệ Windows hoặc phần mềm bảo mật khác của điểm cuối.  </li>
<li>  Đánh giá trạng thái của các dịch vụ Windows AV hoặc phần mềm bảo mật điểm cuối khác của bạn.  </li>
<li>  Đánh giá proxy và tường lửa hạn chế lưu lượng mạng.  </li>
<li>  Cho phép Microsoft Defender cho dịch vụ điểm cuối bằng cách giải thích cách triển khai một hậu vệ cho hồ sơ đại diện Endpoint bằng điểm cuối trên máy tính.  </li>
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
<li>  Tích hợp Microsoft Defender cho Office 365 với Microsoft Defender cho điểm cuối.  </li>
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
  Phiên bản Windows Server Semi-Annual Channel (SAC) 1803.  
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
<li>  Onboarding hoặc cấu hình cho các đại diện Microsoft sau đây cho điểm cuối:
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
<li> Cơ sở hạ tầng máy tính bàn ảo (VDI) (liên tục hoặc không liên tục).  </li>
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
<li> Điều khiển thiết bị.</li>
<li>  
  Khai thác bảo vệ.  
  </li>
<li>  
  Tường lửa mạng.  
  </li>



</ul></li>
<li> Cấu hình hoặc quản lý các tính năng bảo vệ tài khoản như sau: </li>
<ul>

<li> Windows Xin chào</li>
<li> Bảo vệ chứng danh</li>
</ul>
<li> Cấu hình hoặc quản lý BitLocker.</li>
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

<tr class="odd">
<td><strong>Microsoft Defender cho định danh </strong></td>
<td>  Microsoft Defender cho Identity là một giải pháp bảo mật dựa trên nền tảng điện toán đám mây hỗ trợ các tín hiệu Active Directory tại cơ sở của bạn để xác định, phát hiện và điều tra các mối đe dọa nâng cao, danh tính bị xâm phạm và hành động người dùng nội bộ độc hại được hướng dẫn tại tổ chức của bạn. Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>   Tạo bản thể hiện của hậu vệ cho danh tính. </li>
<li>   Kết nối bảo vệ cho định danh đến Active Directory. </li>
<li>   Đánh giá sự sẵn sàng của môi trường để triển khai minh chứng cho bộ cảm biến căn cước trên bộ điều khiển tên miền của bạn, bao gồm:</li>   
<ul> 
<li>  Chạy công cụ chỉnh cỡ cho việc lập kế hoạch dung lượng tài nguyên. </li>
<li>  Chạy công cụ kiểm tra để đánh giá tính tương thích của bộ điều khiển tên miền của bạn với bộ cảm biến. </li>
</ul>
<li>  Triển khai bộ cảm biến để thu thập và phân tích mạng lưu lượng và các sự kiện Windows trực tiếp từ bộ điều khiển tên miền của bạn, bao gồm: </li>
<ul> 
<li>  Tải xuống gói Sensor. </li>
<li>  Cấu hình bộ cảm biến. </li>
<li>  Cài đặt bộ cảm biến trên bộ điều khiển tên miền của bạn. </li>
<li>  Triển khai bộ cảm biến cho môi trường nhiều rừng của bạn. </li>
</ul>
<li>  Tích hợp hậu vệ cho căn cước với Microsoft Cloud App Security (cấp phép bảo mật ứng dụng đám mây không bắt buộc). </li>
<li>  Cung cấp hướng dẫn triển khai, hỗ trợ cấu hình và giáo dục về: </li>
<ul>
<li> Điều chỉnh môi trường để giảm "tiếng ồn".  </li>
<li>  Tìm hiểu về báo cáo đánh giá tư thế bảo mật danh tính. </li>
<li>  Tìm hiểu về điểm ưu tiên của điều tra người dùng và báo cáo xếp hạng người dùng. </li>
<li> Tìm hiểu về báo cáo người dùng không hiện hoạt.  </li>
<li> Cung cấp các tùy chọn khắc phục trên một tài khoản bị xâm phạm.  </li>
</ul>
<li>  Tạo điều kiện di chuyển từ phân tích mối đe dọa nâng cao (ATA) để bảo vệ cho danh tính. </li>
</ul>
<p><strong>Sau đây là phạm vi</strong></p>
<ul>

<li> Quản lý dự án các hoạt động khắc phục của khách hàng. </li>
<li> Quản lý đang diễn ra, phản hồi mối đe dọa và khắc phục.  </li>
<li> Triển khai bảo vệ cho cảm biến danh tính, bao gồm: </li>
<ul>
<li> Lập kế hoạch dung lượng thủ công. </li>
<li> Triển khai các cảm biến trong một công suất độc lập. </li>
<li> Triển khai bộ cảm biến bằng cách dùng card giao diện mạng (NIC) Teaming. </li>
<li> Triển khai bộ cảm biến thông qua công cụ bên thứ ba. </li>
<li> Kết nối với dịch vụ bảo vệ cho Identity Cloud thông qua kết nối proxy web. </li>
</ul>
<li> Tạo và quản lý các thẻ Honey. </li>
<li> Hướng dẫn triển khai hoặc giáo dục về: </li>
<ul>
<li> Khắc phục hoặc diễn giải các kiểu cảnh báo khác nhau và theo dõi các hoạt động.  </li>
<li> Điều tra một người dùng, máy tính, đường dẫn di chuyển bên hoặc tổ chức. </li>
<li> Mối đe dọa hoặc săn bắn nâng cao. </li>
<li> Phản hồi sự cố. </li>
</ul>
<li> Cung cấp hướng dẫn về phòng thí nghiệm cảnh báo bảo mật cho minh họa cho định danh. </li>
<li> Việc cung cấp thông báo khi bảo vệ cho định danh phát hiện hoạt động đáng ngờ bằng cách gửi cảnh báo bảo mật cho máy chủ syslog của bạn thông qua một cảm biến được đề cử.  </li>
<li> Đặt cấu hình bảo vệ cho định danh để thực hiện các truy vấn bằng cách dùng giao thức quản lý tài khoản bảo mật từ xa (SAMR) để xác định người quản trị cục bộ trên máy cụ thể. </li>
<li> Cấu hình các giải pháp VPN để thêm thông tin từ kết nối VPN đến trang hồ sơ của người dùng.  </li>
<li> Thông tin bảo mật và quản lý sự kiện (SIEM) hoặc tích hợp API (bao gồm Azure Sentinel). </li>
<li> Triển khai bảo vệ bộ cảm biến căn cước như là một bằng chứng của khái niệm.</li>
</ul></td>
<td><ul>
<li>  Đã triển khai Active Directory.  </li>
<li>  Bộ điều khiển tên miền mà bạn định cài đặt Defender để cảm ứng căn cước có khả năng kết nối Internet với dịch vụ bảo vệ cho định danh trên điện toán đám mây.  </li>
<ul>
<li> Tường lửa và proxy của bạn phải được mở để liên lạc với bộ bảo vệ cho Identity Cloud Service (*. atp.azure.com cổng 443 phải được mở).</li>
</ul>
<li> Bộ điều khiển tên miền đang chạy trên một trong những thao tác sau:</li>
<ul>
<li> Windows Server 2008 R2 SP1.</li>
<li> Windows Server 2012.</li>
<li> Windows Server 2012 R2.</li>
<li> Windows Server 2016.</li>
<li> Windows Server 2019 với KB4487044 (OS bản dựng 17763,316).</li>
</ul>
</ul></td>
</tr>

<tr class="odd">
<td><strong>Microsoft Defender cho Office 365</strong></td>
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
<td><strong>Quản trị thông tin Microsoft</strong></td>

<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Tạo và phát hành các nhãn và chính sách duy trì (chỉ được hỗ trợ trong E5).  
</li>
<li>  Quản lý bản ghi (chỉ được hỗ trợ trong E5).  </li>
<ul><li>  Xem lại việc tạo lên kế hoạch tệp. </li>
<li>  Tạo và quản lý bản ghi (bao gồm các bản ghi dựa trên sự kiện).  </li>
<li>  Đang xem lại bố trí. </ul> </li>
</ul>

<strong> Trình quản lý tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các kiểu vai trò.  </li>
<li> Thêm và cấu hình Các đánh giá.</li>
<li> Đánh giá việc tuân thủ bằng việc thực hiện hành động cải thiện và xác định cách thức làm ảnh hưởng đến điểm tuân thủ của bạn.</li>
<li> Xem lại ánh xạ điều khiển được dựng sẵn và đánh giá các điều khiển.</li>
<li> Tạo một báo cáo trong một đánh giá.</li>
</ul>

  <strong>Sau đây là phạm vi </strong>  
<ul>
<li> Phát triển một kế hoạch tệp quản lý bản ghi.</li>
<li> Kết nối dữ liệu.</li>
<li> Phát triển kiến trúc thông tin trong SharePoint.</li>
<li> Kịch bản tùy chỉnh và mã hóa.</li>
<li> Thiết kế, kiến trúc sư và xem xét tài liệu của bên thứ ba.</li>
<li> Hỗ trợ E3.</li>
<li> Tuân thủ các quy định và yêu cầu của khu vực.</li>
<li> Thực hiện các hành động cải thiện được đề xuất để đánh giá trong trình quản lý tuân thủ.</li>
</ul>

</td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu.</td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ thông tin của Microsoft</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Phân loại dữ liệu (được hỗ trợ trong E3 và E5).  </li>
<li>  Các kiểu thông tin nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Tạo nhãn nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Áp dụng nhãn nhạy cảm (được hỗ trợ trong E3 và E5).  </li>
<li>  Trainable classifiers (được hỗ trợ trong E5).  </li>
<li>  Biết dữ liệu của bạn với nội dung Explorer và hoạt động Explorer (được hỗ trợ trong E5).  </li>
<li>  Phát hành nhãn bằng chính sách (thủ công và tự động) (được hỗ trợ trong E5).  </li>
<li>  Tạo các chính sách ngăn ngừa mất dữ liệu cho các thiết bị chạy Windows 10 (được hỗ trợ trong E5).  </li>
<li>  Tạo chính sách cho các cuộc trò chuyện và kênh Microsoft nhóm.  </li>
</ul>

<strong> Trình quản lý tuân thủ</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  

<ul> <li>Xem lại các kiểu vai trò.  </li>
<li> Thêm và cấu hình Các đánh giá.</li>
<li> Đánh giá việc tuân thủ bằng việc thực hiện hành động cải thiện và xác định cách thức làm ảnh hưởng đến điểm tuân thủ của bạn.</li>
<li> Xem lại ánh xạ điều khiển được dựng sẵn và đánh giá các điều khiển.</li>
<li> Tạo một báo cáo trong một đánh giá.</li>
</ul>

<strong> Bảo vệ thông tin Azure</strong>

Chúng tôi cung cấp hướng dẫn từ xa cho:  
<ul>
<li>  Kích hoạt và cấu hình đối tượng thuê của bạn.  </li>
<li>  Tạo và thiết lập nhãn và chính sách (được hỗ trợ trong P1 và P2).  </li>
<li>  Áp dụng bảo vệ thông tin cho tài liệu (được hỗ trợ trong P1 và P2).  </li>
<li>  Tự động phân loại và ghi nhãn thông tin trong các ứng dụng Office (chẳng hạn như Word, PowerPoint, Excel và Outlook) đang chạy trên Windows và sử dụng máy khách bảo vệ thông tin Azure (được hỗ trợ trong P2).  </li>
<li>  Phát hiện và ghi nhãn tệp tại phần còn lại bằng cách dùng máy quét bảo vệ thông tin Azure (được hỗ trợ trong P1 và P2).  </li>
<li>  Giám sát email trong quá cảnh bằng quy tắc dòng thư Exchange Online.  </li>
</ul>

  Chúng tôi cũng cung cấp hướng dẫn nếu bạn muốn áp dụng bảo vệ bằng cách sử dụng dịch vụ quản lý quyền Microsoft Azure (Azure RMS), mã hóa thư Office 365 (OME), và ngăn chặn mất dữ liệu ().

<strong>Sau đây là phạm vi </strong>  
<ul>
<li>Khóa khách hàng.</li>
<li>Phát triển biểu thức thông thường tùy chỉnh cho các kiểu thông tin nhạy cảm.</li>
<li>Tạo hoặc sửa đổi từ điển từ khóa.</li>
<li>Kịch bản tùy chỉnh và mã hóa.</li>
<li> Azure purview.</li>
<li> Thiết kế, kiến trúc sư và xem xét tài liệu của bên thứ ba.</li>
<li> Tuân thủ các quy định và yêu cầu của khu vực.</li>
<li> Thực hiện các hành động cải thiện được đề xuất để đánh giá trong trình quản lý tuân thủ.</li>
</ul>

<ul>

</td>
<td>Ngoài phần <strong>lõi triển khai</strong> <a href="#general">nói chung</a>, không có các yêu cầu hệ thống tối thiểu nào với ngoại lệ của Azure Information Protection.

<strong>Bảo vệ thông tin Azure</strong>

Trách nhiệm điều kiện khách hàng bao gồm:  
<ul>
<li>  Danh sách các vị trí chia sẻ tệp sẽ được quét.  </li>
<li>  Phân loại phân loại được phê duyệt. </li>
<li> Hiểu về bất kỳ giới hạn hoặc yêu cầu nào về quy định về quản lý khóa.  </li>
<li>  Tài khoản Dịch vụ được tạo cho Active Directory tại chỗ của bạn đã được đồng bộ hóa với Azure AD. </li>
<li>  Các nhãn được đặt cấu hình cho phân loại và bảo vệ. </li>
<li> Tất cả các điều kiện tiên quyết cho máy quét bảo vệ thông tin Azure được đặt ra. Để biết thêm thông tin, hãy xem <a href="https://docs.microsoft.com/azure/information-protection/deploy-aip-scanner-prereqs">điều kiện tiên quyết để cài đặt và triển khai máy quét ghi nhãn thông tin Azure hợp nhất</a>. </li>
<li>  Đảm bảo các thiết bị người dùng đang chạy hệ điều hành được hỗ trợ và có các điều kiện tiên quyết cần thiết được cài đặt. Xem các chi tiết sau đây để biết thêm chi tiết.</li>
<ul>
<li> <a href="https://docs.microsoft.com/azure/information-protection/rms-client/clientv2-admin-guide-install">Hướng dẫn quản trị: cài đặt máy khách gắn nhãn thông tin Azure hợp nhất cho người dùng</a>   </li>
<li>  <a href="https://docs.microsoft.com/azure/information-protection/rms-client/mobile-app-faq">Ứng dụng bảo vệ thông tin Azure cho iOS hoặc Android là gì?</a>  </li>
</ul>
<li> Cài đặt và cấu hình của trình kết nối Azure RMS và máy chủ bao gồm cả trình kết nối Active Directory RMS (AD RMS) cho hỗ trợ hỗn hợp.  </li>
<li> Thiết lập và cấu hình mang khóa của riêng bạn (BYOK), mã hóa phím kép (YKE) (chỉ dành cho máy khách gắn nhãn nhất quán), hoặc giữ phím của riêng bạn (HYOK) (chỉ dành cho khách hàng cổ điển), bạn nên yêu cầu một trong các tùy chọn này cho quá trình triển khai của bạn.  </li>
  </ul>
</ul>
</td>
</tr>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft InTune</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn từ xa về việc sẵn sàng để sử dụng InTune là nhà cung cấp dịch vụ thiết bị di động trên nền tảng điện toán đám mây (MDM) và cơ quan quản lý ứng dụng dành cho thiết bị di động (MAM) cho các ứng dụng và thiết bị Các bước chính xác tùy thuộc vào môi trường nguồn của bạn và dựa trên thiết bị di động của bạn và các nhu cầu quản lý ứng dụng di động. Các bước có thể bao gồm:
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
<li>  Triển khai email, mạng không dây và hồ sơ VPN nếu bạn có một cơ quan có chứng chỉ hiện có, mạng không dây hoặc cơ sở hạ tầng VPN trong tổ chức của bạn.  </li>
<li>  Kết nối với kho dữ liệu InTune.  </li>
<li>  Đang tích hợp InTune với:
<ul>
<li>  Trình xem nhóm để được hỗ trợ từ xa (đăng ký trình xem nhóm là bắt buộc).  </li>
<li>  Các giải pháp đối tác thoại di động Threat Defense (MTD) (một gói đăng ký MTD là bắt buộc).  </li>
<li>  Một giải pháp quản lý chi phí viễn thông (đăng ký giải pháp quản lý chi phí viễn thông là bắt buộc).  </li>

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
 
</li>
</ul>
  
<strong>Đám mây-đính kèm</strong>  

  Chúng tôi hướng dẫn bạn đến với việc sẵn sàng cho các môi trường trình quản lý cấu hình hiện có với InTune. Các bước chính xác tùy thuộc vào môi trường nguồn của bạn. Những bước này có thể bao gồm:  
<ul>
<li>  Cấp phép người dùng cuối của bạn.  </li>
<li>  Cấu hình các định danh được sử dụng bởi InTune bằng cách tận dụng Active Directory tại chỗ và danh tính đám mây của bạn.  </li>
<li>  Thêm người dùng vào thuê bao InTune của bạn, xác định vai trò quản trị CNTT và tạo nhóm người dùng và thiết bị.  </li>
<li>  Việc cung cấp hướng dẫn thiết lập kết hợp Azure AD join.  </li>
<li>  Cung cấp hướng dẫn về việc thiết lập Azure AD cho MDM tự động đăng ký.  </li>
<li>  Cung cấp hướng dẫn về cách thiết lập cổng kết nối quản lý đám mây khi được dùng làm giải pháp để đồng quản lý việc quản lý thiết bị Internet từ xa.  </li>
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
  </td>
<td>  Người quản trị CNTT cần có cơ quan cấp chứng chỉ hiện có, mạng không dây và hạ tầng VPN đã làm việc trong môi trường sản xuất của họ khi lập kế hoạch triển khai mạng không dây và hồ sơ VPN bằng InTune.  
  <strong>Lưu ý</strong>: lợi ích Dịch vụ fasttrack không bao gồm trợ giúp thiết lập hoặc cấu hình cơ quan cấp chứng chỉ, mạng không dây, hạ tầng VPN hoặc giấy chứng nhận đẩy táo MDM cho InTune.  
 
  <strong>Lưu ý</strong>: lợi ích của dịch vụ fasttrack không bao gồm trợ giúp thiết lập hoặc nâng cấp máy chủ site của trình quản lý cấu hình hoặc máy khách trình quản lý cấu hình đến các yêu cầu tối thiểu cần thiết để hỗ trợ đám mây-đính kèm. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.

  <strong>InTune tích hợp với Microsoft Defender cho điểm cuối</strong> 
 
  <strong>Lưu ý</strong>: chúng tôi cung cấp trợ giúp về việc tích hợp InTune với Microsoft Defender cho điểm cuối và tạo chính sách tuân thủ thiết bị dựa trên đánh giá mức rủi ro Windows 10 của nó. Chúng tôi không cung cấp trợ giúp về việc mua, cấp phép hoặc kích hoạt. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp về điều này.  
  
<strong>Windows Autopilot</strong> 
 
  Người quản trị CNTT chịu trách nhiệm đăng ký thiết bị của họ với tổ chức của họ bằng cách có nhà cung cấp phần cứng tải lên các ID phần cứng của họ thay mặt cho họ hoặc bằng cách tải nó vào dịch vụ Autopilot của Windows.  
  
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
<li>  Thiết lập tính năng của Microsoft Defender cho Office 365 nếu đó là một phần của dịch vụ đăng ký của bạn. Để biết thêm thông tin, hãy xem phần <strong>Microsoft Defender cho Office 365</strong> của bảng này.  </li>
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
Để biết thông tin về cách sử dụng lợi ích FastTrack để di chuyển dữ liệu sang Office 365, hãy xem <a href="https://docs.microsoft.com/fasttrack/data-migration">di chuyển dữ liệu</a>.   
<td>  Môi trường nguồn của bạn phải có một trong các mức tối thiểu sau đây:
<ul>
<li>  Một hoặc nhiều tổ chức Exchange với Exchange Server 2003 trở đi.  </li>
<li>  Môi trường email có khả năng truy nhập thông điệp Internet đơn (IMAP).  </li>
<li>  Một môi trường G Suite đơn (Gmail, danh bạ và lịch chỉ).  </li>
<li>  Để biết thông tin về các khả năng đa địa lý, hãy xem các chức <a href="https://go.microsoft.com/fwlink/?linkid=872776">năng đa địa lý trong Exchange Online</a>.  </li>
</ul>
Phần mềm máy khách trực tuyến như Project for Office 365, Outlook for Windows, Outlook for iOS và Android, OneDrive for Business Sync Client, Power BI trên máy tính và Skype for Business phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 Office</a>.  </td>
</tr>

<td><strong>Microsoft Defender cho Office 365</strong></td>
<td>  Để biết thêm thông tin, hãy xem mục <strong>Microsoft Defender cho Office 365</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>.  
</td>
<td></td>
</tr>


<tr class="even">
<td><strong>Quản trị thông tin Microsoft</strong></td>
<td>  Để biết thêm thông tin, hãy xem <strong> quản trị thông tin Microsoft</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>. 

</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ thông tin của Microsoft</strong></td>
<td>  
Để biết thêm thông tin, hãy xem <strong>bảo vệ thông tin của Microsoft </strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>.

</td>
<td>

</td>
</tr>
<tr class="even">
<td><strong>Microsoft Teams</strong></td>
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
<ul>
<li>  Tạo tài khoản trực tuyến cần thiết cho điện thoại được hỗ trợ và thiết bị phòng hội thảo được liệt kê trong <a href="https://go.microsoft.com/fwlink/?linkid=2066478">danh mục thiết bị nhóm</a>.  </li>
<li>  Hỗ trợ từ xa với cấu hình cạnh Dịch vụ của các thiết bị phòng Microsoft nhóm được chứng nhận.  </li>
<li>  Bật hội thảo âm thanh:  </li>
<li>  Thiết lập tổ chức thiết đặt mặc định cho cầu nối hội thảo.  </li>
<li>  Phân công cầu nối hội thảo cho người dùng được cấp phép.  </li>
</ul>
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
<li>  Hướng dẫn thiết lập tổ chức để thiết kế định tuyến trực tiếp các tình huống được lưu trữ đối tác hoặc các tình huống được triển khai của khách hàng cho tối đa 10 site.  </li>
<li> Xem lại cấu hình bộ điều khiển viền phiên (SBC). </li>

<li> Hỗ trợ từ xa với cấu hình kế hoạch quay số. </li>

<li> Cấu hình tuyến đường thoại.</li>

<li> Bỏ qua phương tiện và tối ưu hóa phương tiện cục bộ. </li>

</ul></li>
</ul></li>
<li>  Cho phép các sự kiện trực tiếp của nhóm.  </li>
<li>  Thiết lập và tích hợp tổ chức vào Microsoft Stream.  </li>
<li>  Hướng dẫn cho Skype for Business thành chuyển tiếp nhóm.  </li>
</ul></td>
<td><ul>
<li>  Các danh tính được kích hoạt trong Azure AD cho Office 365.  </li>
<li>  Người dùng được kích hoạt cho SharePoint Online.  </li>
<li>  Hộp thư Exchange đang trình bày (trực tuyến và tại cơ sở trong cấu hình Exchange hỗn hợp).  </li>
<li>  Đã bật cho các nhóm Office 365.  </li>
</ul>
  <strong>Lưu ý:</strong> Nếu người dùng không được gán và được bật với giấy phép SharePoint Online, họ sẽ không có OneDrive for Business lưu trữ trong Office 365. Chia sẻ tệp tiếp tục làm việc trong các kênh nhưng người dùng không thể chia sẻ tệp trong các cuộc trò chuyện mà không cần lưu trữ OneDrive for Business trong Office 365. Các nhóm không hỗ trợ SharePoint tại chỗ.  <br>
  <strong>Lưu ý:</strong> Trạng thái lý tưởng dành cho tất cả người dùng có hộp thư của họ được lưu trữ trên Exchange Online. Người dùng có hộp thư được định vị tại chỗ phải có các danh tính của họ được đồng bộ hóa với thư mục Office 365 thông qua Azure AD Connect. Đối với những khách hàng hỗn hợp Exchange này, nếu hộp thư của người dùng tại chỗ, người dùng không thể thêm hoặc cấu hình các đường kết nối.  
  Các bản cài đặt cho máy khách Microsoft nhóm Windows và máy Mac có thể được tải xuống từ đó <a href="https://go.microsoft.com/fwlink/?linkid=839411">https://go.microsoft.com/fwlink/?linkid=839411</a> .  </td>
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
<td>Phần mềm máy khách trực tuyến như Power BI trên máy tính phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
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
<td>Phần mềm máy khách trực tuyến như Project for Office 365 phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
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
<td>Phần mềm máy khách trực tuyến như Project for Office 365 phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
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
Để biết thông tin về cách sử dụng lợi ích FastTrack để di chuyển dữ liệu sang Office 365, hãy xem <a href="https://docs.microsoft.com/fasttrack/data-migration">di chuyển dữ liệu</a>.
</ul></td>
<td><br><strong>Đối với SharePoint Hybrid:</strong>  
<ul>
<li>  Cấu hình hỗn hợp SharePoint bao gồm cấu hình tìm kiếm hỗn hợp, site, phân loại, kiểu nội dung, onedrive for Business, công cụ khởi động ứng dụng mở rộng, site bên ngoài nơi và việc tạo trang tự phục vụ được kết nối từ tại chỗ đến môi trường SharePoint Online.  </li>
</ul>
  <strong>Lưu ý:</strong> Tạo trang web tự phục vụ không có trong phạm vi với máy chủ tại cơ sở chạy SharePoint 2013.  
<ul>
<li>  Để bật SharePoint Hybrid, bạn phải có một trong những môi trường SharePoint Server tại cơ sở sau: 2013, 2016, hoặc 2019.  </li>
</ul>
  <strong>Lưu ý:</strong> Nâng cấp môi trường SharePoint tại cơ sở sang SharePoint Server không nằm trong phạm vi. Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp. Để biết thêm thông tin, hãy xem các <a href="https://go.microsoft.com/fwlink/?linkid=853548">mức Cập Nhật công khai tối thiểu cho các tính năng của SharePoint Hybrid</a><em>.</em>  <br>
  <strong>Lưu ý:</strong> Để biết thông tin về các khả năng đa địa lý, hãy xem các chức <a href="https://go.microsoft.com/fwlink/?linkid=831056">năng đa địa lý trong OneDrive và SharePoint Online trong Office 365</a><em>.</em>  </td>
</tr>
<tr class="even">
<td><strong>Yammer Enterprise</strong></td>
<td>
Chúng tôi cung cấp hướng dẫn từ xa để cho phép Dịch vụ yammer Enterprise.  
</td>
<td>Phần mềm máy khách trực tuyến phải ở mức tối thiểu như được xác định trong <a href="https://go.microsoft.com/fwlink/?LinkID=723597">yêu cầu hệ thống đối với Microsoft 365 và Office</a>.</td>
</tr>
</tbody>
</table>

## <a name="enterprise-mobility--security"></a>Tính năng di động doanh nghiệp + bảo mật 

<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Azure Active Directory (Azure AD) và Azure AD Premium</strong></td>
<td>  Để biết thêm thông tin, hãy xem <strong> Azure Active Directory (AZURE AD) và AZURE AD Premium</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>.</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Bảo vệ thông tin Azure </strong></td>
<td>  Để biết thêm thông tin về việc bảo vệ thông tin Azure, hãy xem mục <strong>bảo vệ thông tin của Microsoft</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance"> bảo mật và tuân thủ.  </td>
<td>  
  
</td>
</tr>
<tr class="even">
<td><strong>Microsoft InTune</strong></td>
<td>  Để biết thêm thông tin, hãy xem <strong> Microsoft InTune</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>.
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
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Windows 10</strong></td>
<td>  Chúng tôi cung cấp hướng dẫn nâng cấp từ Windows 7 Professional và Windows 8,1 Professional sang Windows 10 Enterprise.  
  Chúng tôi cung cấp hướng dẫn từ xa cho:
<ul>
<li>  Hiểu rõ ý định về Windows 10 của bạn.  </li>
<li>  Đánh giá môi trường nguồn của bạn và các yêu cầu (đảm bảo rằng Microsoft Endpoint Configuration Manager được nâng cấp lên mức bắt buộc để hỗ trợ triển khai Windows 10).  </li>
<li>  Triển khai Windows 10 Enterprise và ứng dụng Microsoft 365 bằng Microsoft Endpoint Configuration Manager hoặc Microsoft 365.  </li>
<li>  Đề xuất các tùy chọn cho bạn để đánh giá các ứng dụng Windows 10 của bạn.  </li>
<li>  Cho phép sử dụng phân tích máy tính để bàn và hướng dẫn thông qua việc tạo kế hoạch triển khai phân tích máy tính bàn.  </li>
<li>  Đánh giá tương thích của Microsoft 365 bằng cách tận dụng bảng điều khiển sẵn sàng của Office 365 trong trình quản lý cấu hình hoặc với bộ công cụ sẵn sàng độc lập cho Office Plus hỗ trợ triển khai ứng dụng Microsoft 365.  </li>
<li>  Tạo danh sách kiểm tra khắc phục những gì bạn cần làm để mang đến môi trường nguồn của bạn lên đến các yêu cầu tối thiểu để triển khai thành công.  </li>
<li>  Cung cấp hướng dẫn nâng cấp cho các thiết bị hiện có của bạn vào Windows 10 Enterprise nếu họ đáp ứng các yêu cầu phần cứng thiết bị cần thiết.  </li>
<li>  Cung cấp hướng dẫn nâng cấp để hỗ trợ chuyển động triển khai hiện có của bạn. FastTrack Recommends và cung cấp hướng dẫn cho việc nâng cấp tại chỗ lên Windows 10. Hướng dẫn cũng sẵn dùng cho việc cài đặt Windows sạch ảnh và các kịch bản triển khai Windows Autopilot.  </li>
<li>  Triển khai ứng dụng Microsoft 365 bằng trình quản lý cấu hình như là một phần của triển khai Windows 10.   </li>
<li>  Cung cấp hướng dẫn để giúp tổ chức của bạn luôn Cập Nhật với Windows 10 Enterprise và ứng dụng Microsoft 365 bằng môi trường trình quản lý cấu hình hiện có của bạn hoặc Microsoft 365.  </li>
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
<li>  Phiên bản trình quản lý cấu hình phải được hỗ trợ bởi phiên bản Windows 10 target. Để biết thêm thông tin, hãy xem bảng hỗ trợ trình quản lý cấu hình tại <a href="https://docs.microsoft.com/sccm/core/plan-design/configs/support-for-windows-10">hỗ trợ cho Windows 10 trong trình quản lý cấu hình</a>.  </li>
</ul>

<tr class="odd">
<td><strong>Microsoft Defender cho điểm cuối</strong></td>
<td>  Để biết thêm thông tin, hãy xem mục <strong> Microsoft Defender cho điểm cuối</strong> trong <a href="https://docs.microsoft.com/fasttrack/products-and-capabilities#security-and-compliance">bảo mật và tuân thủ</a>.</td>
<td></td>

</tbody>
</table>

## <a name="windows-virtual-desktop"></a>Máy tính chạy Windows ảo

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
<td><strong>Máy tính chạy Windows ảo</strong></td>
<td><p>Chúng tôi cung cấp hướng dẫn triển khai cho triển khai vào Windows Virtual trên máy tính (một dịch vụ ảo hóa và ứng dụng trên máy tính). Windows Virtual Desktop sẽ lợi dụng trải nghiệm đa phiên Windows 10 và được tối ưu hóa cho các ứng dụng Microsoft 365 dành cho doanh nghiệp với tính bảo mật và quản lý tích hợp cho Microsoft 365.</p>
<p>Chúng tôi cung cấp hướng dẫn từ xa cho:</p>
<ul>
<li>Triển khai môi trường Windows Virtual trên máy tính của bạn với Windows 10 Enterprise Multi-session và ứng dụng Microsoft 365 dành cho doanh nghiệp bằng cách sử dụng như sau:
<ul>
<li>Ảnh Azure Marketplace.</li>
<li>Ảnh chia sẻ.</li>
<li>Bộ công cụ triển khai Office (ODT).</li>
</ul></li>
<li>Cấu hình FSLogix:
<ul>
<li>Triển khai đại diện FSLogix bằng bộ chứa hồ sơ.</li>
<li>Triển khai đại diện FSLogix với bộ chứa Office.</li>
<li>Cấu hình thư mục FSLogix với loại trừ nội dung.</li>
</ul></li>
<li>Triển khai Microsoft Edge.</li>
<li>Triển khai nhóm Microsoft.</li>
<li>Kết nối bằng máy khách của Windows Virtual Desktop.</li>
</ul>

<strong>Sau đây là phạm vi</strong>
<ul>
<li>Quản lý dự án triển khai Windows Virtual trên máy tính của khách hàng.</li>
<li>Ảo hóa và triển khai ứng dụng của bên thứ ba.</li>
<li>Hình ảnh tùy chỉnh.</li>
<li>Di chuyển và kịch bản liên quan đến VMware và Citrix.</li>
<li>Kịch bản trong Linux.</li>
<li>Chuyển đổi hoặc di chuyển của hồ sơ người dùng.</li>
</ul>
Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp với các dịch vụ này.</td>
<td>Bạn đã có thể có những điều sau đây:
<ul>
<li>Các <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#requirements">yêu cầu cấp phép Virtual trên máy tính chạy Windows</a>.</li>
<li>Lưới Azure:
<ul>
<li>Tạo mạng (VNET) ảo và lưới nhỏ.</li>
<li>Tường lửa và nhóm bảo mật mạng.</li>
<li>VPN và ExpressRoute.</li>
<li>Định tuyến đến Azure từ tại chỗ.</li>
<li>Các quy tắc tường lửa để cho phép kết nối với Windows Virtual trên máy tính.
</ul>
Để biết thêm thông tin, hãy xem mục <a href="https://docs.microsoft.com/azure/virtual-desktop/overview#supported-remote-desktop-clients"> hỗ trợ máy khách từ xa</a>.
</ul>
<ul><li>Thiết lập chung Azure AD:
<ul>
<li>Chiến lược <i>căn cước (bạn chỉ có thể sử dụng một trong ba tùy chọn sau đây):</i>
<ul>
<li>Active Directory với Azure AD Connect trong Azure.</li>
<li>Active Directory với Azure AD Connect tại cơ sở qua VPN hoặc ExpressRoute.</li>
<li>Dịch vụ miền Active Directory (AD DS).</li>
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
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Đảm bảo cho ứng dụng</strong></td>
<td>  Ứng dụng đảm bảo là một dịch vụ được thiết kế để giải quyết các sự cố với Windows 10 và ứng dụng Microsoft 365 ứng dụng tương thích. Khi bạn yêu cầu ứng dụng đảm bảo dịch vụ, chúng tôi sẽ làm việc với bạn để giải quyết các sự cố ứng dụng hợp lệ tại không có chi phí bổ sung cho bạn bằng một thuê bao đủ điều kiện. Chúng tôi cũng cung cấp hướng dẫn cho khách hàng những vấn đề tương thích khi triển khai Windows Virtual Desktop và Microsoft Edge và thực hiện tất cả các nỗ lực hợp lý để giải quyết các vấn đề tương thích. Chúng tôi cung cấp hỗ trợ khắc phục các ứng dụng được triển khai trên các sản phẩm Microsoft sau đây:
<ul>
<li>  <strong>Windows 10 </strong> (bao gồm các thiết bị ARM64)</li>
<li> <strong>Ứng dụng Microsoft 365</strong>  </li>
<li>  <strong>Microsoft Edge-</strong> Để được hướng dẫn triển khai, hãy xem <a href="https://docs.microsoft.com/DeployEdge/microsoft-edge-channels">tổng quan về các kênh Microsoft Edge</a>.  </li>
<li>  <strong>Máy tính</strong> - chạy Windows ảo Để biết thêm thông tin, hãy xem <a href="https://docs.microsoft.com/azure/virtual-desktop/windows-10-multisession-faq">câu hỏi thường gặp</a>về <a href="https://docs.microsoft.com/azure/virtual-desktop/overview">Windows Virtual Desktop là gì?</a> và Windows 10 Enterprise.  </li>
</ul>

<strong>Sau đây là phạm vi </strong>  
<ul>
<li>  Kiểm tra và thử nghiệm ứng dụng để xác định những điều không có và không hoạt động trên các ứng dụng Windows 10 và Microsoft 365. Để biết thêm hướng dẫn về quy trình này, hãy truy cập <a href="https://go.microsoft.com/fwlink/?linkid=2080140">Trung tâm triển khai màn hình máy tính</a>. Nếu bạn quan tâm đến việc đánh giá sẵn sàng nâng cấp chuyên sâu, hãy hoàn thành <a href="https://go.microsoft.com/fwlink/?linkid=2053818">yêu cầu khách hàng cho biểu mẫu đánh giá máy tính bàn hiện đại</a> .</li>
<li>  Nghiên cứu các ứng dụng ISV bên thứ ba dành cho tính tương thích và câu lệnh hỗ trợ của Windows 10. Để biết thêm thông tin, hãy xem <a href="https://docs.microsoft.com/sccm/desktop-analytics/overview">phân tích máy tính để bàn</a>.</li>
<li>Chỉ bao bì ứng dụng-các dịch vụ. Tuy nhiên, ứng dụng đảm bảo các ứng dụng gói nhóm mà chúng tôi đã khắc phục đối với Windows 10 để đảm bảo rằng chúng có thể được triển khai trong môi trường của khách hàng.</li>
</ul>

<strong>Các trách nhiệm của khách hàng bao gồm</strong>  
<ul>
<li>  Tạo hàng tồn kho ứng dụng.</li>
<li>  Phê chuẩn những ứng dụng này trên các ứng dụng Windows 10 và Microsoft 365.</li>
</ul>
<strong>Lưu ý:</strong>  Microsoft không thể thực hiện thay đổi đối với mã nguồn của bạn. Tuy nhiên, ứng dụng đảm bảo nhóm có thể cung cấp hướng dẫn cho nhà phát triển ứng dụng nếu mã nguồn sẵn dùng cho ứng dụng của bạn. 


  Liên hệ với một <a href="https://go.microsoft.com/fwlink/?linkid=2080150">đối tác Microsoft</a> để được trợ giúp với các dịch vụ này.  </td>

</td>
<td><strong>Ứng dụng Windows 10 và Microsoft 365</strong>
<ul>
<li>  
  Các ứng dụng đã làm việc trên Windows 7, Windows 8,1, Office 2010 và Office 2013 cũng hoạt động trên các ứng dụng Windows 10 và Microsoft 365.  
  </li>
</ul>
<strong>Windows 10 trên ARM</strong>
<ul>
<li>  
Các ứng dụng đã làm việc trên Windows 7, Office 2010 hoặc phiên bản mới hơn cũng hoạt động trên các ứng dụng Windows 10 và Microsoft 365 trên các thiết bị ARM64. 
  </li>
</ul>
  <strong>Yù</strong> 
<ul>
<li> Mô phỏng x64 (64 bit) sẵn dùng trong bản xem trước dành cho khách hàng tham gia <a href="https://insider.windows.com/">chương trình</a>người dùng nội bộ Windows.  </li>
<li>  
 Đối với khách hàng không phải cửa sổ người dùng nội bộ trên Windows 10 phiên bản 2004 (hoặc mới hơn), ARM64 Photoshop được hỗ trợ bằng cách sử dụng <a href="https://www.microsoft.com/p/opencl-and-opengl-compatibility-pack/9nqpsl29bfff?rtc=1&activetab=pivot:overviewtab">gói tương thích OpenCL và OpenGL</a>. 
  </li>
<li>  
  Khách hàng trong chương trình Windows Insider có thể tải xuống phiên bản người dùng nội bộ của gói tương thích OpenCL và OpenGL để sử dụng với các ứng dụng bổ sung.    
  </li>
</ul>
<strong>Microsoft Edge</strong>
<ul>
<li>  
  Nếu ứng dụng web hoặc site của bạn hoạt động trên Internet Explorer 11, các phiên bản Google Chrome được hỗ trợ, hoặc bất kỳ phiên bản nào của Microsoft Edge, họ cũng sẽ làm việc với Microsoft Edge.  
  </li>
<li>  
  Khi web không liên tục phát triển, hãy đảm bảo bạn xem lại danh sách <a href="https://docs.microsoft.com/microsoft-edge/web-platform/site-impacting-changes">đã phát hành của tính năng tương thích trang đã biết-các thay đổi tác động đối với Microsoft Edge</a>.  
  </li>
</ul>
  <strong>Máy tính chạy Windows ảo </strong>  
<ul>
<li>  
  Các ứng dụng ảo hóa chạy trên máy chủ lưu trữ phiên máy tính từ xa của Windows Server (RDSH) cũng chạy trên Windows 10 Enterprise Multi-session như một phần của Windows Virtual Desktop.  
  </li>
<li>  
  Các ứng dụng đang chạy trên bất kỳ môi trường cơ sở hạ tầng máy tính bàn ảo Windows 7 hoặc Windows 10 nào (VDI) cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như một phần của Windows Virtual trên máy tính.  
  </li>
<li>  
  Các ứng dụng đang chạy trên Windows 7 hoặc Windows 10 thiết bị khách cũng chạy trên Windows 7 Enterprise và Windows 10 Enterprise như một phần của Windows Virtual trên máy tính.  
  </li>
</ul>
  <strong>Lưu ý:</strong> Các loại trừ và giới hạn tương thích của Windows 10 Enterprise đa phiên bao gồm:
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
</tbody>
</table>

## <a name="microsoft-edge"></a>Microsoft Edge


<table>
<thead>
<tr class="header">
<th><strong>Service</strong></th>
<th><strong>Chi tiết hướng dẫn FastTrack</strong></th>
<th><strong>Mong đợi môi trường nguồn</strong></th>
</tr>
</thead>
<tbody>
<tr class="even">
<td><strong>Microsoft Edge</strong> </td>
<td>
Chúng tôi cung cấp hướng dẫn và trợ giúp về tính tương thích của từ xa cho: <ul> <li>Triển khai Microsoft Edge trên Windows 10 với Microsoft Endpoint Manager (Microsoft Endpoint Configuration Manager hoặc InTune).  </li>
<li>  Cấu hình Microsoft Edge (sử dụng chính sách nhóm hoặc cấu hình ứng dụng InTune và chính sách ứng dụng).  </li>
<li>  Phát minh ra danh sách các site có thể yêu cầu sử dụng trong chế độ Internet Explorer.  </li>
<li>  Bật chế độ Internet Explorer với danh sách site hiện có của doanh nghiệp. (Để biết thêm thông tin, hãy xem mục <a href="https://docs.microsoft.com/fasttrack/process-and-expectations#engaging-fasttrack">tham gia FastTrack</a>). Ngoài ra, nếu bạn có một ứng dụng web hoặc site hoạt động với Internet Explorer hoặc Google Chrome và bạn trải nghiệm các vấn đề tương thích, chúng tôi cung cấp hướng dẫn để giải quyết sự cố mà không cần phải có thêm chi phí. Để yêu cầu hỗ trợ tương thích cho ứng dụng đảm bảo, hãy đăng nhập vào <a href="https://fasttrack.microsoft.com/portal#/signin">cổng thông tin Fasttrack</a> để bắt đầu một cam kết.  </li>
<li> Hướng dẫn lập kế hoạch cho các hướng dẫn về việc áp dụng và cấu hình cạnh cho thẻ đánh dấu tìm kiếm.</li>
</ul>

<strong>Sau đây là phạm vi </strong>  
<ul>
<li>Quản lý dự án triển khai Microsoft Edge của khách hàng.</li>
<li>  Hỗ trợ trên site.</li>

</td>
<td></td>
</tr>
</tbody>
</table>
