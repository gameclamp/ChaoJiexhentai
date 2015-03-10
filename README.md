# ChaoJiexhentai
### 脚本功能
*  在e-hentai和exhentai一页多图看漫画，并拥有人性化的缩略图导航功能。
*  利用浏览器的indexeddb存储图片，省去重复加载（长期使用请注意浏览器配置文件夹的大小）

### 如何安装
完整支持浏览器：[Firefox](http://sourceforge.net/projects/pcxfirefox/ "推荐pcx编译版")  
需要扩展：[Greasemonkey](https://addons.mozilla.org/zh-CN/firefox/addon/greasemonkey/?src=search)  
最后安装本脚本：[ChaoJiexhentai.user.js](https://github.com/gameclamp/ChaoJiexhentai/raw/master/ChaoJiexhentai.user.js)

### 详细功能介绍
*  点击画册内某一缩略图，会弹出多图看图器。  
*  然后从该图开始向后逐一加载，每三秒一页。加载成功的图片在显示的同时会被存放到浏览器的indexeddb中，留待以后查看的时候直接读取。而30秒后仍然未加载完成的图片会被自动更换服务器重载。  
*  看图器右上角的X可以关闭看图器，S可以停止向后加载。

###### 想撸哪里点哪里
*  任何时候都可以点击画册内的缩略图跳转到看图器浏览大图  
*  任何时候都可以点击看图器内的缩略图开始加载该大图（同时会从该图开始向后逐一加载）。

### QA
1.  如何删除所有存放图片？  
    关剩下一个ex的标签页，然后点击Report Gallery下面的del。

### To Do
indexeddb的管理
加载原图
