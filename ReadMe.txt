这是火狐浏览器的开发插件

需要下载的插件为greaseMonkey(油猴子)

其中test.user.js 为自己写的js脚本，可以通过插件嵌入到网页中去。

需要注意的地方：
	在本地调试的时候，需要在Apache服务器上进行运行，不然是没有效果的，原因 可能是greasemonkey嵌入界面时
只认URL地址的缘故吧，直接打开的html文件不是URL。