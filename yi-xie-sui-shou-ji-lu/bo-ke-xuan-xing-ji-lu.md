# 博客选型记录

**需求**

* 需要选择国外的博客，减少审核风险
* 数据可备份

<mark style="color:orange;">****</mark>

<mark style="color:orange;">**OneNote**</mark>

优点：树形结构，逻辑清晰。

缺点：对浏览者来说界面复杂，尤其是手机端，开启界面连文章都看不到

大缺点：OneDrive 中新建的笔记本只在云端有，无法下载

不过可以导出pdf，先忍了。。



<mark style="color:orange;">**blogger**</mark>

系统老旧，样式太难调，备份只能备份xml文字。

网站文章列表有bug，有时候只能显示一条。

特殊：可以用来分享直播截图：[將圖片和影片新增到網誌](https://support.google.com/blogger/answer/41641)

> 系統可能會壓縮上傳至 Blogger 的圖片並進行網頁最佳化處理，如此一來即可減少讀者的數據用量並加快載入時間。這類圖片不會計入您的 Google 儲存空間配額。Blogger 目前不支援以原始畫質儲存大型圖片。



**wordpress**

缺点：自定义域名要收费，免费的版本限制比较多，或者需要自己搭建维护，比较麻烦。



**medium**

没有目录树



**gitbook + github pages**

npm 版的 gitbook：太老了，有很多坑，比如不支持比较高版本的 node，生成的静态页面无法跳转，而且没有全文搜索。



**gridea**

也有很多bug，好像也没有文章树



**gitbook.com（当前使用）**

缺点：checkbox 是假的，不能点击

致命缺点：

* 手机浏览器上有 bug，页面跳转会加载不出来，需要刷新一次。
* github 同步有严重 bug，会随机回滚到某个版本（github 中的 版本异常，gitbook.com 中的是正常的）
* 编辑器光标乱跳，非常抽风。

优点：格式丰富。内容可以完全备份到 github，实在不行可以迁移。网页端编辑，比较方便。



**notion**

墙内访问不稳定，没有目录树，只有面包屑导航



**Sphinx + Github + ReadTheDocs**

案例：[https://zhangzhenhu.github.io/blog/index.html](https://zhangzhenhu.github.io/blog/index.html)

教程：[https://blog.51cto.com/u\_15441270/4724717](https://blog.51cto.com/u\_15441270/4724717)

缺点：比较麻烦，而且也没有全文搜索



**Jekyll+GitHub Pages 有添加全文搜索的功能**

缺点：比较麻烦，等以后有空弄
