---
title: Giới thiệu về sự phát sóng hài bậc hai (SHG)
date: 2026-02-21
weight: 10 # bài đầu tiên của chương thì đánh 10, bài tiếp theo của chương đánh 20,...
type: book
bibliography: references-for-shg.bib
link-citations: true
nocite: '[@*]' #HIỂN THỊ TẤT CẢ TÀI LIỆU THAM KHẢO TRONG FILE .bib DÙ CÓ TRÍCH DẪN HAY KHÔNG
toc: true
commentable: true
draft: false
math: true
math_provider: 'mathjax' # doesnt work for this theme
image:
  caption: SHG (tia bất thường) ở tinh thể đơn trục âm
cover:
  filename: "featured.png" # Tên file ảnh (nếu để cùng thư mục với index.md)
  focal_point: "Smart" # Tự động căn giữa vào phần quan trọng của ảnh khi bị cắt
  preview_only: false # Đổi thành true nếu bạn CHỈ muốn hiện ảnh ngoài trang chủ, không hiện trong bài đọc
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: gradient
    opacity: 0.4
    gradient: bottom
  fade:
    enabled: true
    height: 80px
  icon:
    name: 
authors:
  - me
categories: 
  - Quang học đại cương
tags:
  - Quang học đại cương
  - Giới thiệu về quang học phi tuyến
content_meta:
  trending: false
---
{{< toc >}}
Trong sự phát sóng hài bậc hai (SHG), quá trình diễn ra như sau:
- Hai photon giống nhau (tần số $\omega$) gặp nhau và tự hủy lẫn nhau (annihilation) dưới sự xúc tác của nguyên tử.
- Chúng truyền năng lượng cho nguyên tử khiến đám mây electron "biến dạng đàn hồi".
- Nó phát ra photon mới có tần số $2\omega$ gấp đôi mỗi photon cũ (gần như ngay lập tức, trong thời gian cực ngắn cỡ ($\approx 10^{-16}s$)).
- Nguyên tử quay trở về trạng thái ban đầu.

Trong quá trình trên, nguyên tử không lấy năng lượng của các photon trường ngoài để chuyển thành động năng giật lùi hoặc động năng ban đầu khi electron bứt ra khỏi liên kết với nguyên tử. Hai dạng động năng này trong quá trình hấp thụ luôn xảy ra, và chính động năng vi mô của tập hợp rất lớn các nguyên tử này tạo nên năng lượng nhiệt ở cấp độ vĩ mô làm nóng khối tinh thể [^1].

Dưới tương tác với 2 photon trường ngoài, trong SHG thì hai photon không đủ cung cấp năng lượng để các electron bứt ra khỏi vùng cấm để chuyển lên vùng dẫn được nên đám mây electron bị biến dạng và hàm sóng của nó bị nhiễu loạn mạnh.

Xét quá trình biến dạng của đám mây electron
-
Khi hai photon hủy nhau rồi truyền năng lượng cho nguyên tử, thời gian nguyên tử phát ra photon mới là rất nhỏ $t\approx 10^{-16}-10^{-18}\text{s}$, khiến cho độ bất định về năng lượng trở nên đáng kể. Theo hệ thức bất định:
$$
\Delta E.\Delta t \ge \frac{\hbar}{2}
$$
Trong đó, đại lượng $\Delta t$ có hai cách diễn giải tương đương nhau: 
- Thời gian để đo đạc năng lượng hạt.
- Là thời gian đáp ứng của hạt dưới tác động của trường ngoài, sau khoảng thời gian $\Delta t$ kể từ lúc tương tác với trường ngoài (ở đây là các photon) thì trạng thái của hạt mới có sự thay đổi (đáng kể).

Và $\Delta E$ được diễn giải là độ bất định về năng lượng. Vấn đề xảy ra với sự bất định này: Sự vi phạm định luật bảo toàn năng lượng trong quá trình biến dạng. Thật vậy, electron dù chỉ nhận năng lượng của 2 photon là $2\hbar\omega$ nhưng trong quá trình biến dạng thì năng lượng này hoàn toàn có thể nhận giá trị bất kì trong khoảng $\hbar\omega\pm\Delta E$. Thiên nhiên dung túng cho định luật bảo toàn năng lượng trong thời gian rất ngắn ở cấp độ lượng tử.

Ví dụ, ở sự SHG của tinh thể KTP, $\Delta t _{\text{max}}\approx 3,785.10^{-16}\text{s}$ thì:

$$
\Delta E\ge\frac{\hbar}{2.\Delta t}\ge\frac{\hbar}{2.\Delta t_\text{max}}\approx 0,869 \text{eV}
$$
Năng lượng mà nó nhận được từ hai photon hồng ngoại bước sóng $\lambda=1064\text{nm}$ là $2E_\omega\approx 2,331\text{eV}$. Cộng với độ bất định về năng lượng của nó thì ta được:
$$E+\Delta E=3,2\text{eV}$$

Vùng cấm năng lượng $E_g$ của KTP vào cỡ $3,2-3,5\text{eV}$. Tính toán thô ở trên cho ta nghi vấn là liệu có khả năng tồn tại một số ít electron chạm được tới đáy vùng dẫn để bắt đầu chuyển thành electron tự do không? Nếu điều này xảy ra, nó thực sự đã nuốt luôn hai photon vừa rồi (vì sau đó nó được tự do, electron tự do không thể tự phát ra photon).

Để trả lời câu hỏi này, ta tính toán như sau: Giả sử mạng tinh thể đang chịu tương tác của điện trường laser tần số $\omega$, gây ra quá trình kích thích hai photon (với năng lượng kích thích tổng cộng là $2\hbar\omega$). Theo đó thì mật độ xác suất để electron chuyển dời trực tiếp từ trạng $\ket{v,\vec{\mathbf k}}$ trong vùng hóa trị đến trạng thái $\ket{c,\vec{\mathbf k}}$ trong vùng dẫn được cho bởi định lý vàng Fermi:
$$
w_{v \to c}(\vec{\mathbf{k}})\propto |M(\vec{\mathbf k})|^2 \delta (E_c-E_v-2\hbar\omega)
$$
Với $\delta (E_c-E_v-2\hbar\omega)$ là hàm delta-Dirac:
$$
\delta (x)=
\begin{cases} 
0,\quad \text{nếu } x\ne 0\\
\infty,\quad \text{nếu } x=0
\end{cases}
$$
Và $|M(\vec{\mathbf k})|^2$ là một hàm phụ thuộc $\vec{\mathbf k}$ không phục vụ cho mục đích trả lời câu hỏi của chúng ta. Theo vật lý chất rắn, năng lượng vùng cấm $E_g$ là khoảng cách nhỏ nhất giữa vùng dẫn và vùng hóa trị $E_c-E_v$. Do đó, với mọi $\vec{\mathbf{k}}$ thuộc vùng dẫn BZ, ta luôn có bất đẳng thức:

$$
\begin{align*}
E_c(\vec{\mathbf{k}}) - E_v(\vec{\mathbf{k}}) \ge E_g
\tag{1}
\end{align*}
$$

Mà hai photo không đủ để cung cấp năng lượng để electron vượt qua khỏi vùng cấm để tiến vào được vùng dẫn BZ nên: 
$$
\begin{align*}
2\hbar\omega< E_g
\tag{2}
\end{align*} 
$$

Kết hợp $(1)$ với $(2)$, ta có: 
$$\begin{align*}
&\Delta E = E_c-E_v- 2\hbar\omega >0\\
\Leftrightarrow & \delta (E_c-E_v-2\hbar\omega) = 0, \quad \forall \vec{\mathbf k}\in BZ
\end{align*}$$

Vậy, ta khẳng định: electron có xác suất $w_{v\to c}$ chuyển dời lên vùng dẫn là **bằng không**, dù hàm sóng của nó nhiễu loạn mạnh. 

Sau một thời gian, nó sẽ có xác suất cao phát ra photon mới, chứ độ bất định này không tạo thêm xác suất để nó chuyển lên vùng dẫn. Điều này nghĩa biểu thức bảo toàn năng lượng $E_\text{sau}=E_\text{đầu}$ vẫn được đảm bảo ở trạng thái đầu và trạng thái cuối, nhưng trong quá trình biến dạng thì năng lượng không nhất thiết bảo toàn. Hệt như electron mượn năng lượng từ chân không, xong rồi nó trả lại lượng năng lượng này cho chân không vũ trụ.

Nghĩa là độ bất định này chỉ đủ để một số ít electron nguyên tử vừa chạm tới vùng dẫn chứ không thoát ra khỏi nguyên tử được. Vậy, trong bức xạ sóng hài bậc hai, hai photon của chùm tới (gọi là chùm ánh sáng bơm) với tần số $\omega$ hợp nhất để tạo ra một photon mới (tần số $2\omega$). Năng lượng của hệ được bảo toàn, không có sự chuyển năng lượng sáng thành động năng ban đầu của electron khi bị bứt khỏi vùng dẫn: 
$$\hbar(2\omega) = \hbar\omega + \hbar\omega$$

Điều kiện hợp pha
-
Để sự phát sóng hài bậc hai diễn ra tối ưu thì cần thỏa **điều kiện hợp pha (Phase Matching)** về số sóng của hai photon tới và photon phát ra giữa hai photon tới và photon phát ra:
$$\Delta \vec{\mathbf{k}} = \vec{\mathbf{k}}_{2\omega} - 2\vec{\mathbf{k}}_{\omega} = 0,\quad \text{(Điều kiện hợp pha)}$$

Điều này được chứng minh như thế nào?

**Định hướng chứng minh:** Vì số sóng liên hệ trực tiếp tới động lượng hạt photon, ta chứng minh điều kiện hợp pha dựa trên định luật bảo toàn động lượng cho các photon tham gia vào quá trình SHG.

**Chứng minh:** 
Để năng lượng được chuyển đổi hiệu quả nhất từ sóng cơ bản sang sóng hài trong toàn bộ chiều dài tinh thể phi tuyến, động lượng của hai photon tới phải bằng động lượng photo phát ra, nghĩa là không có sự hấp thụ động lượng của nguyên tử. Việc mạng tinh thể hấp thụ động lượng photon (ở cấp độ vi mô) chính là nguyên nhân của sự hấp thụ ánh sáng (ở cấp độ vĩ mô), điều cần loại trừ trong sự phát sóng hài bậc 2. Động lượng của một photon tỉ lệ với vectơ số sóng $\vec{\mathbf{k}}$ theo hệ thức $\vec{\mathbf{p}} = \hbar \vec{\mathbf{k}}$.
Phương trình bảo toàn động lượng như sau:
$$\hbar \vec{\mathbf{k}}_{2\omega} = \hbar \vec{\mathbf{k}}_{\omega} + \hbar \vec{\mathbf{k}}_{\omega}$$
$$\Rightarrow\vec{\mathbf{k}}_{2\omega} = 2\vec{\mathbf{k}}_{\omega}$$
Từ đó suy ra độ lệch pha (phase mismatch) phải bằng không:
$$\Delta \vec{\mathbf{k}} = \vec{\mathbf{k}}_{2\omega} - 2\vec{\mathbf{k}}_{\omega} = 0\tag{*}$$

**Ở cấp độ vĩ mô, điều này có ý nghĩa gì?**
- Khi điều kiện này được thỏa mãn, các sóng hài sinh ra tại các vị trí khác nhau trong tinh thể sẽ **giao thoa tăng cường**, làm cường độ chùm SHG đạt cực đại ở đầu ra.
- $k=\frac{n_\omega \times \omega}{c}$ nên từ $(*)$ suy ra chiết suất tại $2\omega$ phải bằng chiết suất tại $\omega$:
$$n_{2\omega}=n_\omega$$

Điều kiện để SHG xảy ra
-
a. Trong suốt
--
Ở cấp độ vĩ mô, SHG chỉ thỏa mãn với các photon laser có tần số $\omega$ ở xa vùng hấp thụ $\omega_p$ của tinh thể, vì ở gần vùng hấp thụ này thì các electron thực sự có thể hấp thụ photon mà không nhả ra đủ lượng photon ban đầu. Điều này cưỡng bức các đám mây electron duy trì được trạng thái dao động nhiệt tập thể với cường độ lớn theo thời gian. Do đó, tia laser với đặc tính cường độ cao sẽ gia nhiệt cục bộ cho vị trí được chiếu laser của tinh thể thông qua sự hấp thụ bức xạ, phá vỡ tính hợp pha và gây giãn nở nhiệt cục bộ cho vị trí chiếu tia. Như một ly thủy tinh dày có thể bị nứt vỡ nếu ta đổ đột ngột nước nóng vào trong, **tinh thể sẽ bị nóng lên không đồng đều và với laser công suất cao thì có thể làm vỡ tinh thể. Vậy để hiện tượng SHG xảy ra, các tia laser chiếu tới ($\omega$) và phát ra ($2\omega$ or $\omega$) phải ở cách xa vùng hấp thụ của nó.**

**Ví dụ:**
- Giả sử mục đích của ta là chuyển ánh sáng xanh $532\text{nm}$ thành tia laser tử ngoại $266\text{nm}$ thông qua hiệu ứng SHG (vì laser ánh sáng xanh $532\text{nm}$ đã được chế tạo thành công).
- Ta không thể sử dụng tinh thể KDP vì vùng hấp thụ của KDP ngay khoảng $250\text{nm} - 260\text{nm}$. Tia $266\text{ nm}$ sinh ra nằm quá sát vùng cộng hưởng này, khiến KDP nóng ran lên và hỏng ngay lập tức nếu dùng laser công suất cao.
- BBO có vùng trong suốt rất rộng, kéo dài xuống tận $189\text{ nm}$. Nhờ vậy, bước sóng $266\text{ nm}$ nằm cách rất xa vùng hấp thụ của BBO, giúp tinh thể an toàn và cho ra hiệu suất SHG cực kỳ mạnh mẽ.

Với các môi trường đẳng hướng, trong cùng một vùng tán sắc thường (ở một phía so với vùng cộng hưởng $\omega=\omega_p$) thì điều kiện hợp pha không bao giờ xảy ra do hàm chiết suất theo tần số $n(\omega)$ là một hàm đơn điệu và hoàn toàn không phụ thuộc vào phương truyền bức xạ, suy ra:
$$
\begin{align*}
n_\omega\ne n_{2\omega}
\end{align*}
$$
Do đó, **trong thực tiễn người ta thường sử dụng các tinh thể dị hướng như là KDP, KTP, BBO,... để dễ dàng đạt được điều kiện hợp pha cho sự phát sóng hài bậc hai**, ngay trong cùng một vùng tán sắc thường (tức là trong suốt). Với các tinh thể dị hướng, chỉ cần xoay tinh thể hoặc phương truyền sáng một chút là chiết suất đã thay đổi nên có thể đạt được điều kiện hợp pha:
$$n_{2\omega}(\theta',\phi')=n_\omega(\theta,\phi)$$

b. Bất đối xứng tâm
--
Ngoài ra, như mọi sự phát sóng hài bậc chẵn mà SHG là một trường hợp, các tinh thể phù hợp để có hiện tượng SHG là các tinh thể không có đối xứng tâm (non-Centrosymmetric crystal). Điều này cũng có thể chứng minh nhờ một vài biến đổi toán học đơn giản. Vector phân cực điện môi theo phương thứ i trong hệ tọa độ x,y,z gắn với 3 trục chính quang học của tinh thể được khai triển dưới dạng:
$$
{P_i}=\epsilon_0(\sum_{j}\chi_{ij}E_j + \sum_{ij}\chi_{ijk}E_{j}E_{k}+...)
$$

Biểu thức trên thường được viết gọn như sau, là một sự lạm dụng kí hiệu (abuse of notation) không chuẩn chỉnh về mặt toán học nhưng tiện lợi và dễ hình dung hơn, rất thường gặp trong các giáo trình trong và ngoài nước:
$$
P=\epsilon_0(\chi^{(1)}E+\chi^{(2)}E^2+\chi^{(3)}E^3+...)\tag{3}
$$
Trong đó, $\chi^{(1)}$, $\chi^{(2)}$ là các tensor độ cảm điện. Sự đối xứng tâm sẽ dẫn tới việc biểu thức trên sẽ không đổi khi ta tưởng tượng nghịch đảo không gian qua một tâm đối xứng O nào đó (nghĩa là đổi x thành -x, y thành -y, z thành -z).

Nhìn chung, để khảo sát ảnh hưởng của sự đối xứng tâm lên các công thức Vật lí, ta thường xét phép biến đổi nghịch đảo không gian qua một tâm đối xứng O. 

Khi nghịch đảo như vậy, các thành phần của mọi vector sẽ bị nghịch đảo, nghĩa là:
$$
\begin{align*}
&P\to -P\\
&E\to -E\\
&E^2\to E^2, \quad (\text{Không đổi vì là số hạng bậc hai})\\
&...
\end{align*}
$$
Do đó, biểu thức $(3)$ sẽ trở thành:
$$
\begin{align*}
&&-&P = \epsilon_0(-\chi^{(1)}E+\chi^{(2)}E^2 - \chi^{(3)}E^3+...)\notag\\
\Rightarrow&&&P = \epsilon_0(\chi^{(1)}E-\chi^{(2)}E^2 + \chi^{(3)}E^3-...)\tag{4}
\end{align*}
$$

Nếu tinh thể có đối xứng tâm thì vector phân cực điện môi của nó phải bất biến đối với phép nghịch đảo không gian: 
$$
P \to P, \quad \text{khi}
\begin{cases}
x\to-x\\
y\to-y\\
z\to-z
\end{cases}
$$

Đồng nhất (3) và (4) ta được:
$$\begin{align*}
\chi^{(1)}&=\chi^{(1)}\quad \text{(Luôn đúng)}\\
\chi^{(2)} &= -\chi^{(2)} \Rightarrow \color{red} \boldsymbol{\chi^{(2)}=0}\\
\chi^{(3)}&=\chi^{(3)}\quad \text{(Luôn đúng)}\\
\chi^{(4)} &= -\chi^{(4)} \Rightarrow \color{red} \boldsymbol{\chi^{(4)}=0}\\
...&
\end{align*}$$
Vậy với tinh thể đối xứng tâm thì sự phát sóng hài bậc chẵn như SHG không thể xảy ra (do $\chi^{(2)}=\chi^{(4)}=...=0$), nhưng sự phát sóng hài bậc lẻ vẫn có thể xảy ra.

Các chất rắn vô định hình như thủy tinh có sự sắp xếp hỗn độn của các phân tử, ion. Điều này làm cho các moment lưỡng cực điện tí hon $\vec{\mathbf{p}}$ phân bố ngẫu nhiên mọi hướng (giống như vector vận tốc của các phân tử trong mẫu khí lí tưởng). Về mặt vĩ mô, sự hỗn loạn này là như nhau theo mọi phương, môi trường có tinh chất như nhau theo mọi phương được gọi là môi trường đẳng hướng. Sự hỗn loạn này khiến cho moment lưỡng cực tĩnh trung bình bằng không $\langle \vec{\mathbf{p}} \rangle = \vec{\mathbf{0}}$ dẫn đến độ phân cực tuyến tính bằng không $\vec{\mathbf P}^{(1)}=N.\langle\vec{\mathbf p}\rangle=\vec{\mathbf 0}$. Lưu ý: hoàn toàn hỗn loạn thì đẳng hướng, nhưng đẳng hướng không nhất thiết phải có nghĩa là hoàn toàn hỗn loạn. Các tinh thể có cấu trúc Zincblende (như GaAs, ZnTe) có mạng tinh thể đẳng hướng, tuần hoàn chứ không hề hỗn loạn.

Tuy vậy, tính đẳng hướng vĩ mô này khiến cho vật liệu hành xử như một môi trường có đối xứng tâm. Khi có điện trường laser $\vec{\mathbf{E}}$ tác dụng, các thành phần phân cực phi tuyến bậc chẵn sẽ triệt tiêu lẫn nhau trên toàn thể tích, các thành phần phân cực bậc lẻ thì chỉ có bậc 1 (tuyến tính) bị triệt tiêu. Vì vậy, chất rắn vô định hình không thể tạo ra sóng hài bậc hai (SHG) hay các sóng hài bậc chẵn, nhưng chúng vẫn hoàn toàn có thể phát ra các sóng hài bậc lẻ (như sóng hài bậc ba - THG).

Ở chiều ngược lại, **sự phát sóng hài bậc chẵn phải xảy ra với môi trường không có đối xứng tâm**[^2]. 

Ứng dụng của SHG
-
(to be continued).

**Mời bạn góp ý, phản biện hoặc đặt câu hỏi trong comment section bên dưới cùng.**

## Tài liệu tham khảo
[1]   R. W. Boyd, *Nonlinear optics*, 4th ed., vol. 1–2. Academic Press, 2020. Accessed: Feb. 24, 2026. [Online]. Available: https://drive.google.com/file/d/1utLEO4wOLUjXiMjlr2mUOCiil9ipiSAe/view?usp=drive_link

[2]   “Sự phát sóng hài bậc II,” *SlideShare*. https://www.slideshare.net/slideshow/s-pht-sng-hi-bc-ii/45982843 (accessed Feb. 24, 2026).

[3]   P. Ngô Thị , “Advanced optics chap 1: Hiện tượng tán sắc ánh sáng,” *Slideshare*. https://www.slideshare.net/slideshow/advanced-optics-chap-1/29217512

[4]   P. Ngô Thị, “Chuyên đề quang học - advanced optics: Chương 2 - phân cực ánh sáng,” *Slideshare*. https://drive.google.com/file/d/1F34pamgv7OaNbEUZAVYGs8ObnuTgabFk/view (accessed Feb. 24, 2026).

[5]   P. Ngô Thị, “Chuyên đề quang học - advanced optics: Phần 2 - phân cực qua môi trường dị hướng,” *Google Drive*. https://drive.google.com/file/d/1u89lq94iof6hEWqycYwLjGYcEaTHN1_f/view (accessed Feb. 24, 2026).

[6]   P. Ngô Thị , “Chuyên đề quang học - advanced optics: Chương 3,” *Google Drive*. https://www.slideshare.net/slideshow/chng-3-make-by-ngo-thi-phuong/29217526 (accessed Feb. 24, 2026).

[7]   “Second-harmonic generation,” *Wikipedia*. https://en.wikipedia.org/wiki/Second-harmonic_generation (accessed Feb. 24, 2026).

## Chú thích
[^1]: Nhiệt bản chất là sự chuyển động tập thể của cả khối vật chất gồm rất nhiều tỉ hạt, động năng **trung bình** của chúng là nhiệt năng.
[^2]: Có đối xứng tâm hay không thì liên quan tới phép nghịch đảo không gian như đã trình bày, còn dị hướng hay đẳng hướng lại liên quan tới phép quay không gian: chính là phép biến đổi các tọa độ góc $\theta,\phi$ bất kì một lượng $\Delta\theta,\Delta\phi$ nào đó, trong khi biến tọa độ xuyên tâm $r$ lại bất biến. Mặt khác, ở phép nghịch đảo không gian thì các biến góc tăng hoặc giảm đi lượng $\pi$. Do đó, hai cặp khái niệm "đẳng hướng/dị hướng" và "có đối xứng tâm/bất đối xứng tâm" không tương đương với nhau.

<span style="display:none;">
[@boyd2020nonlinear; @slideshare_shg; @ngo_phuong_chap1; @ngo_phuong_chap2; @ngo_phuong_phan2; @ngo_phuong_chap3; @wiki_shg]
</span>