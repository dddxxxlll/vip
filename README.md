# 手把手教你怎么免费看爱奇艺等视频网站
## 方法一：
直接下载VIP.html文档，双击打开。将视频地址输入，然后点击播放
easy！

### 不会下载？
1. 右上角clone and download
2. 选择download zip
3. 然后解压。

## 方法二：（没有上方的按钮组，看视频更美观）
chrome商店下载tampermonkey插件（一直在用的插件，如果没有的话就别用这个方法了）
添加新脚本，将下面代码完全覆盖（其中@match后面跟你要看的视频地址）
```
// ==UserScript==
// @name         New Userscript
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @match        http://v.youku.com/v_show/id_XMjQ4NTczNTE1Ng==.html
// @grant        none
// ==/UserScript==

(function() {
    'use strict';

    // Your code here...
    window.location = 'http://p2.api.47ks.com/webcloud/?v='+window.location.href;
})();
```
刷新所要看的网页
easy！

## 方法三：（最简单，最方便，最优解，不用输入网址）
打开任意网页，ctrl+D保存为书签
修改该书签地址为以下代码：
```
javascript:window.location = 'http://p2.api.47ks.com/webcloud/?v='+window.location.href
```
然后打开任意你想看的视频页面
点击该书签，完工！
easy！

# 如果有用，给我董某人一个面子，star我吧