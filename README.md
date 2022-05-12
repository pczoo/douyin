# douyinshipinjiexi
抖音短视频解析
市面上存在很多视频解析接口，大多数都是收费的。教你一招，免费下载无水印的抖音小视频！

## 1.浏览器分析
从抖音短视频中分享一段视频。可以得到：

> #在抖音，记录美好生活#一起舞动一起摇摆 《Dance Monkey》音乐推荐  https://v.douyin.com/FPJTD63/ 复制此链接，打开【抖音短视频】，直接观看视频！

我将这段文字中的链接部分复制下来，在浏览器打开。并使用开发者工具调试。

![浏览器打开初始链接](https://s1.ax1x.com/2022/05/12/OwXCxf.png)

可以看到在video标签中存在三个视频链接，我们选择一个就可以了。
```
//v26-web.douyinvod.com/9cf60cf6e23fe18c44049d639def7a94/627c9862/video/tos/cn/tos-cn-ve-15c001-alinc2/5668db35480e403d932378dff85b44d4/?a=6383&ch=4&cr=0&dr=0&lr=all&cd=0%7C0%7C0%7C0&cv=1&br=2984&bt=2984&cs=0&ds=6&ft=X1nbLXvvBQOBULrZN8Z.wNnOYZlcsvBYF2bLcjCHTuZm&mime_type=video_mp4&qs=0&rc=NjM6NDozN2g2NzY0Z2hmM0BpMzRxdTg6Zm1vPDMzNGkzM0A0YTZjMTIvNWAxYy80YGA1YSNwby00cjRvZmlgLS1kLS9zcw%3D%3D&l=2022051212145301013516808349424BA5
```
复制该链接在浏览器打开：
![直接打开src链接](https://user-images.githubusercontent.com/79189521/167994048-d4a8cea1-41ff-4101-a7d5-eace948206ab.jpg)

这样就可以下载视频啦！学到了点个star吧~
