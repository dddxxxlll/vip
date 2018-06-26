# 手把手教你怎么免费看爱奇艺等视频网站
<!--more-->
## 方法一：
直接下载VIP.html文档，双击打开。将视频地址输入，然后点击播放
ps：可以随手star我
easy！

### 不会下载？
0. PC端直接以下步骤，手机端先点击右下角Desktop version（ps：手机端还是别搞这个东西了）
1. 点击右上clone and download
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
    window.location = 'http://jx.aeidu.cn/index404.php?url='+window.location.href;
})();
```
刷新所要看的网页
easy！

## 方法三：（最简单，最方便，最优解，不用输入网址）
打开任意浏览器。
打开任意网页，ctrl+D保存为书签
修改该书签地址为以下代码：
```
javascript:window.location = 'http://jx.aeidu.cn/index404.php?url='+window.location.href
```
然后打开任意你想看的视频页面
点击该书签，完工！
easy！

## 2018年6月26日更新接口（第一个测试过能用，其他未知）
http://jx.aeidu.cn/index404.php?url=
http://000o.cc/jx/ty.php?url=
http://j.zz22x.com/jx/?url=
http://jx.vgoodapi.com/jx.php?url=
http://jiexi.92fz.cn/player/vip.php?url=
其实接口可以去嘀哩嘀哩上找。。。