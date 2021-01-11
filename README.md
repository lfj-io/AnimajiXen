# AnimajiXen

<p align="center"><img src="https://github.com/lfj-io/AnimajiXen/raw/main/trailer.gif" /></p>
<p align="center"><img src="https://github.com/lfj-io/AnimajiXen/blob/main/sprite_59.png?raw=true" /> Không gif nhưng lại động.</p>


### Lưu ý :
- Bạn tự chịu những rủi ro phát sinh khi sử dụng.
- Mình đã config mọi thông số phù hợp sử dụng với bộ sticker của Zalo, và có sẵn 100 Emoji rồi, nếu không thích thì các bạn có thể tải thêm Sticker của zalo băng cách vào [chat.zalo.me](https://chat.zalo.me/) để bắt hình ảnh sticker cho nét nhất thì dùng DevTools có sẵn, hoặc mấy chương trình bên ngoài như Fiddler. Sau khi tải thì bạn chép vào thư mục `LFJAnimateEmoji` (theo dướng dẫn dưới) thì sticker mới hoạt động nhé. 
- Nếu muốn dùng sticker của facebook hoặc whatapp thì bạn phải biết chút chút code, để chỉnh lại thông số cho phù hợp, do mỗi bên làm 1 kiểu, chỉnh không đúng nó sẽ ... rất mắc cười.
- Nếu bạn muốn phát triển thêm cho nó hoàn chỉnh thành một plguin, mình hy vọng bạn sẽ chừa một chỗ để ghi credit dẫn đến git này.



## Installation

### CDN
-  
-`https://cdn.jsdelivr.net/gh/lfj-io/files/js/AnimajiXen.min.js` right before `</body>`

-`https://cdn.jsdelivr.net/gh/lfj-io/files/css/AnimajiXen.min.css` add to head of style `PAGE_CONTAINER`

- Download & import [smilies.xml](https://raw.githubusercontent.com/lfj-io/AnimajiXen/609c4538ad508d2ad40b070f4d5898ebf9452b4d/smilies.xml)

- Done~

### Selfhosting

- [Download](https://github.com/lfj-io/AnimajiXen/releases/latest) latest releases extract and upload folder `LFJAnimateEmoji` and 2 files is `StickerAnimate.css` & `StickerAnimate.min.js`, to your xenrofo `/sytle/` . Then go to Admin => Smilies, chosse import, type patch of `LFJAnimateEmoji` folder.

<img src="https://i.imgur.com/7qbmYCp.png" />

#### Add js and css to make it work

- Go to templates find  `PAGE_CONTAINER` . 
- add ` <link type="text/css" rel="stylesheet" href="./styles/StickerAnimate.css" />` in top of `PAGE_CONTAINER`

- CTRL+F to find `</body>`, add this one right before that:  `<script src="/styles/StickerAnimate.min.js"></script>` then save.

- Done
