---
title: Giới thiệu về sự phát sóng hài bậc hai (SHG)
date: 2026-02-21
weight: 10 # bài đầu tiên của chương thì đánh 10, bài tiếp theo của chương đánh 20,...
type: book
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

Để trả lời câu hỏi này, ta tính toán như sau: Giả sử mạng tinh thể đang chịu tương tác của điện trường laser tần số $\omega$, gây ra quá trình kích thích hai photon (với năng lượng kích thích tổng cộng là $2\hbar\omega$). Theo đó thì mật độ xác suất để electron chuyển dời trực tiếp từ trạng $\ket{v,\vec{\mathbf k}}$ trong vùng hóa trị đến trạng thái $\ket{c,\vec{\mathbf k}}$ trong vùng dẫn là:
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
\begin{align}
2\hbar\omega< E_g
\tag{2}
\end{align} 
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

Ở cấp độ vĩ mô, điều này chỉ thỏa mãn với các photon laser có tần số $\omega$ ở xa vùng hấp thụ $\omega_p$ của tinh thể, vì ở gần vùng hấp thụ này thì các electron thực sự có thể hấp thụ photon mà không nhả ra đủ lượng photon ban đầu khiến cho tất cả đám mây electron duy trì được trạng thái dao động tập thể theo thời gian. **Tinh thể sẽ bị nóng lên (với laser công suất cao thì có thể làm vỡ tinh thể). Vậy để hiện tượng SHG xảy ra, nguyên tử phải ở cách xa vùng hấp thụ của nó.**

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
$$\Delta \vec{\mathbf{k}} = \vec{\mathbf{k}}_{2\omega} - 2\vec{\mathbf{k}}_{\omega} = 0$$

Ở cấp độ vĩ mô, điều này có ý nghĩa gì?

Khi điều kiện này được thỏa mãn, các sóng hài sinh ra tại các vị trí khác nhau trong tinh thể sẽ **giao thoa tăng cường**, làm cường độ chùm SHG đạt cực đại ở đầu ra.

[^1]: Nhiệt bản chất là sự chuyển động tập thể của cả khối vật chất gồm rất nhiều tỉ hạt, động năng **trung bình** của chúng là nhiệt năng.
