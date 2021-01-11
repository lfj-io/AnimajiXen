# AnimajiXen

<p align="center"><img src="https://github.com/lfj-io/AnimajiXen/raw/main/trailer.gif" /></p>
<p align="center"><img src="https://github.com/lfj-io/AnimajiXen/blob/main/sprite_59.png?raw=true" /> Không gif nhưng lại động.</p>


### Lưu ý :
- Bạn tự chịu những rủi ro phát sinh khi sử dụng.
- Mình đã config mọi thông số phù hợp sử dụng với bộ sticker của Zalo, và có sẵn 100 Emoji rồi, nếu không thích thì các bạn có thể tải thêm Sticker của zalo băng cách vào [chat.zalo.me](https://chat.zalo.me/) để bắt hình ảnh sticker cho nét nhất thì dùng DevTools có sẵn hoặc mấy chương trình bên ngoài như Fiddler.
- Nếu muốn dùng sticker của facebook hoặc whatapp thì bạn phải biết chút chút code, để chỉnh lại thông số cho phù hợp, do mỗi bên làm 1 kiểu, chỉnh không đúng nó sẽ ... rất mắc cười.


### Hướng dẫn nhanh

- Cái này không phải là plugin, do đó bạn phải thực hiện bằng tay, không có gì khó cả, download về giải nén, upload thư mục `LFJAnimateEmoji` cùng 2 `StickerAnimate.css` và `StickerAnimate.min.js`, để vào `/sytle/` . Sau đó vào Admin của XenfoXo => Smilies (Mặt cười). Để tiện quản lý thì các bạn tạo một Group cho smilies chuẩn bị nhập, rồi ghi đường dẫn vào nhập là xong

<img src="https://i.imgur.com/7qbmYCp.png" />

#### Chèn Script và CSS để nó hoạt động.

- Bạn vào chỗ giao diện, hoặc dùng thanh tìm kiếm trong Admin, tìm  `PAGE_CONTAINER` . 
- Thêm ` <link type="text/css" rel="stylesheet" href="./styles/StickerAnimate.css" />` ngay trên đầu
- Bấm CTRL+F tìm `</body>` và thêm `<script src="/styles/StickerAnimate.min.js"></script>` trước chữ `</body>`
- Save lại, và kích hoạt mặt cười. Nó đã hoạt động rồi đó.

