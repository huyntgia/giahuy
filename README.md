<article class="markdown-body entry-content container-lg" itemprop="text"><div dir="auto"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Trình tải xuống phương tiện Telegram</font></font></h1><a id="user-content-telegram-media-downloader" class="anchor" aria-label="Permalink: Trình tải xuống phương tiện Telegram" href="#telegram-media-downloader"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-telegram-media-downloader" aria-label="Permalink: Trình tải xuống phương tiện Telegram" href="#telegram-media-downloader"></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tập lệnh Tampermonkey cho phép người dùng tải xuống hình ảnh, GIF và video trên ứng dụng web Telegram từ các kênh riêng tư, vô hiệu hóa việc tải xuống và hạn chế lưu nội dung.</font></font></p>
<p dir="auto"><a href="https://camo.githubusercontent.com/8056fcba8beddfaf7dd5b650a26f19c9138f60572450f9306b61a56c0c92ada1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f4e6565742d4e6573746f722f54656c656772616d2d4d656469612d446f776e6c6f61646572" rel="nofollow"><img src="https://camo.githubusercontent.com/8056fcba8beddfaf7dd5b650a26f19c9138f60572450f9306b61a56c0c92ada1/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f6c6963656e73652f4e6565742d4e6573746f722f54656c656772616d2d4d656469612d446f776e6c6f61646572" alt="Giấy phép GitHub" style="max-width: 100%;"></a>
<a href="https://camo.githubusercontent.com/06a1b3c84b437a5b803b15a040ba8e8871254f65c910623dcbe241522b4beac7/68747470733a2f2f696d672e736869656c64732e696f2f677265617379666f726b2f762f3434363334322d74656c656772616d2d6d656469612d646f776e6c6f61646572" rel="nofollow"><img src="https://camo.githubusercontent.com/06a1b3c84b437a5b803b15a040ba8e8871254f65c910623dcbe241522b4beac7/68747470733a2f2f696d672e736869656c64732e696f2f677265617379666f726b2f762f3434363334322d74656c656772616d2d6d656469612d646f776e6c6f61646572" alt="Phiên bản nĩa nhờn" style="max-width: 100%;"></a>
<a href="https://camo.githubusercontent.com/b0cbb317db6f524482ef63a36429fcbccc58349305d641f16c1c19409e9d55c3/68747470733a2f2f696d672e736869656c64732e696f2f677265617379666f726b2f64742f3434363334322d74656c656772616d2d6d656469612d646f776e6c6f61646572" rel="nofollow"><img src="https://camo.githubusercontent.com/b0cbb317db6f524482ef63a36429fcbccc58349305d641f16c1c19409e9d55c3/68747470733a2f2f696d672e736869656c64732e696f2f677265617379666f726b2f64742f3434363334322d74656c656772616d2d6d656469612d646f776e6c6f61646572" alt="Bản tải xuống Greasy Fork" style="max-width: 100%;"></a></p>
<div dir="auto"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cài đặt</font></font></h2><a id="user-content-installation" class="anchor" aria-label="Liên kết cố định: Cài đặt" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-installation" aria-label="Liên kết cố định: Cài đặt" href="#installation"></a></div>
<div dir="auto"><div class="markdown-heading" dir="auto"><h3 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Các bước cài đặt</font></font></h3><a id="user-content-greasy-fork" class="anchor" aria-label="Liên kết cố định: Ngã ba nhờn" href="#greasy-fork"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-greasy-fork" aria-label="Liên kết cố định: Ngã ba nhờn" href="#greasy-fork"></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cài đặt </font></font><a href="https://www.tampermonkey.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tampermonkey</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cài đặt tập lệnh này bằng cách truy cập Greasy Fork:
 </font></font><a href="https://greasyfork.org/en/scripts/446342-telegram-media-downloader" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://greasyfork.org/en/scripts/446342-telegram-media-downloader</font></font></a></li>
</ol>
<div dir="auto"><div class="markdown-heading" dir="auto"><h3 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hướng dẫn cài đặt</font></font></h3><a id="user-content-manual-installation" class="anchor" aria-label="Permalink: Cài đặt thủ công" href="#manual-installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-manual-installation" aria-label="Permalink: Cài đặt thủ công" href="#manual-installation"></a></div>
<ol dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cài đặt </font></font><a href="https://www.tampermonkey.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tampermonkey</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mở Bảng điều khiển Tampermonkey, kéo và thả src/tel_download.js vào đó rồi nhấp vào nút "cài đặt"</font></font></li>
</ol>
<div dir="auto"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Cách sử dụng</font></font></h2><a id="user-content-how-to-use" class="anchor" aria-label="Liên kết cố định: Cách sử dụng" href="#how-to-use"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-how-to-use" aria-label="Liên kết cố định: Cách sử dụng" href="#how-to-use"></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tập lệnh này chỉ hoạt động trên Telegram Webapp.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đối với các kênh và cuộc trò chuyện cho phép lưu nội dung, tập lệnh này sẽ không có hiệu lực. Thay vào đó, vui lòng chỉ sử dụng nút tải xuống chính thức do ứng dụng web telegram cung cấp.</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đối với các kênh và cuộc trò chuyện vô hiệu hóa tải xuống và hạn chế lưu nội dung, tập lệnh này sẽ thêm lại nút tải xuống cho hình ảnh, GIF và video.</font></font></p>
<p dir="auto"><a href="https://camo.githubusercontent.com/740da3f934f7325148481f22e3359cccbb1626d699db63a891d5ef1dde09f590/68747470733a2f2f6d65646961322e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45785932566a4e6d55325a444d305954466c4f57593459544d7a5a445a6d4e6a566c4d4445324f4451344f4759344e3245334d44466b4e535a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f6c714356637730704364325641337a716f452f67697068792e676966" rel="nofollow"><img src="https://camo.githubusercontent.com/740da3f934f7325148481f22e3359cccbb1626d699db63a891d5ef1dde09f590/68747470733a2f2f6d65646961322e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45785932566a4e6d55325a444d305954466c4f57593459544d7a5a445a6d4e6a566c4d4445324f4451344f4759344e3245334d44466b4e535a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f6c714356637730704364325641337a716f452f67697068792e676966" alt="Tải xuống hình ảnh" style="max-width: 100%;"></a>
      <span>
        <a href="https://camo.githubusercontent.com/740da3f934f7325148481f22e3359cccbb1626d699db63a891d5ef1dde09f590/68747470733a2f2f6d65646961322e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45785932566a4e6d55325a444d305954466c4f57593459544d7a5a445a6d4e6a566c4d4445324f4451344f4759344e3245334d44466b4e535a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f6c714356637730704364325641337a716f452f67697068792e676966" rel="nofollow">
</a></span></p><p dir="auto"><a href="https://camo.githubusercontent.com/f3bd875a7afde3c43f39105cdfecd59147bdc5b2515e62aca4c1f0310e465e01/68747470733a2f2f6d65646961302e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d7a59774d7a4d335a544d7a596d49314d7a41344d324579596d59304e54466c4f5467344f5746684e6a686a4e446b3559546b7a59695a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f776e597a5734767770506465756f36326e512f67697068792e676966" rel="nofollow"><img src="https://camo.githubusercontent.com/f3bd875a7afde3c43f39105cdfecd59147bdc5b2515e62aca4c1f0310e465e01/68747470733a2f2f6d65646961302e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d7a59774d7a4d335a544d7a596d49314d7a41344d324579596d59304e54466c4f5467344f5746684e6a686a4e446b3559546b7a59695a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f776e597a5734767770506465756f36326e512f67697068792e676966" alt="Tải xuống ảnh GIF" style="max-width: 100%;"></a>
<span>
<a href="https://camo.githubusercontent.com/f3bd875a7afde3c43f39105cdfecd59147bdc5b2515e62aca4c1f0310e465e01/68747470733a2f2f6d65646961302e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d7a59774d7a4d335a544d7a596d49314d7a41344d324579596d59304e54466c4f5467344f5746684e6a686a4e446b3559546b7a59695a6c634431324d563970626e526c636d35686246396e61575a7a583264705a6b6c6b4a6d4e305057632f776e597a5734767770506465756f36326e512f67697068792e676966" rel="nofollow"></a></span></p>
<p dir="auto"><a href="https://camo.githubusercontent.com/e079456f85034e9d809d262e9639c0511e26ebe2b87d7d52bee29cbdff154d07/68747470733a2f2f6d65646961312e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d586378596e4a7861584d7863573035595735725a32597a5a7a45306254553461544277595849314e33706d646e567a6244467264535a6c634431324d563970626e526c636d35686246396e61575a66596e6c666157516d593351395a772f45455062626c776d53707465416d774c6c732f67697068792e676966" rel="nofollow"><img src="https://camo.githubusercontent.com/e079456f85034e9d809d262e9639c0511e26ebe2b87d7d52bee29cbdff154d07/68747470733a2f2f6d65646961312e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d586378596e4a7861584d7863573035595735725a32597a5a7a45306254553461544277595849314e33706d646e567a6244467264535a6c634431324d563970626e526c636d35686246396e61575a66596e6c666157516d593351395a772f45455062626c776d53707465416d774c6c732f67697068792e676966" alt="Tải xuống video" style="max-width: 100%;"></a>
<span>
<a href="https://camo.githubusercontent.com/e079456f85034e9d809d262e9639c0511e26ebe2b87d7d52bee29cbdff154d07/68747470733a2f2f6d65646961312e67697068792e636f6d2f6d656469612f76312e59326c6b505463354d4749334e6a45784d586378596e4a7861584d7863573035595735725a32597a5a7a45306254553461544277595849314e33706d646e567a6244467264535a6c634431324d563970626e526c636d35686246396e61575a66596e6c666157516d593351395a772f45455062626c776d53707465416d774c6c732f67697068792e676966" rel="nofollow"></a></span></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đối với video, thanh tiến trình sẽ hiển thị ở phía dưới bên phải sau khi bạn bắt đầu tải xuống. Đối với hình ảnh và âm thanh, sẽ không có thanh tiến trình.</font></font></p>
<div dir="auto"><div class="markdown-heading" dir="auto"><h3 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Phiên bản ứng dụng web được hỗ trợ</font></font></h3><a id="user-content-supported-webapp-versions" class="anchor" aria-label="Permalink: Các phiên bản ứng dụng web được hỗ trợ" href="#supported-webapp-versions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-supported-webapp-versions" aria-label="Permalink: Các phiên bản ứng dụng web được hỗ trợ" href="#supported-webapp-versions"></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Có 2 phiên bản khác nhau của ứng dụng web telegram:</font></font></p>
<ul dir="auto">
<li><a href="https://webk.telegram.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://webk.telegram.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://web.telegram.org/k/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://web.telegram.org/k/</font></font></a></li>
<li><a href="https://webz.telegram.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://webz.telegram.org</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> / </font></font><a href="https://web.telegram.org/a/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://web.telegram.org/a/</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tập lệnh này sẽ hoạt động trên cả hai phiên bản webapp. Nếu bạn đang sử dụng một phiên bản ứng dụng web khác và thấy tập lệnh này không hoạt động, vui lòng nêu vấn đề lên </font></font><a href="https://github.com/Neet-Nestor/Telegram-Media-Downloader/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">kho lưu trữ GitHub</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> của chúng tôi .</font></font></p>
<div dir="auto"><div class="markdown-heading" dir="auto"><h3 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Kiểm tra tiến trình tải xuống</font></font></h3><a id="user-content-check-downloading-progress" class="anchor" aria-label="Permalink: Kiểm tra tiến trình tải xuống" href="#check-downloading-progress"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-check-downloading-progress" aria-label="Permalink: Kiểm tra tiến trình tải xuống" href="#check-downloading-progress"></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Thanh tiến trình sẽ hiển thị ở phía dưới bên phải màn hình cho video. Bạn cũng có thể kiểm tra </font></font><a href="https://developer.chrome.com/docs/devtools/open/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bảng điều khiển DevTools</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> để tìm nhật ký.</font></font></p>
<div dir="auto"><div class="markdown-heading" dir="auto"><h2 tabindex="-1" dir="auto" class="heading-element"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hỗ trợ tác giả</font></font></h2><a id="user-content-support-author" class="anchor" aria-label="Permalink: Tác giả hỗ trợ" href="#support-author"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div><a id="user-content-support-author" aria-label="Permalink: Tác giả hỗ trợ" href="#support-author"></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Nếu bạn thích kịch bản này, bạn có thể ủng hộ tôi qua </font></font><a href="https://venmo.com/u/NeetNestor" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Venmo</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> hoặc </font></font><a href="https://ko-fi.com/neetnestor" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">mua cho tôi một ly cà phê</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> :)</font></font></p>

</article>
