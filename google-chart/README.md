## Google Chart -- corechart packages离线版使用方法 ##

需要使用两个文件：api.js 和 tooltip.css

- api.js

下载到本地后把"GoogleApisBase"换成你的域名（域名结尾不要"/"），默认把"tooltip.css"放在"/static/modules/gviz/1.0/core/"路径下面。

- tooltip.css

默认把css文件放在/static/modules/gviz/1.0/core/下面。

这样，在页面中只要引用api.js 就可以离线状态下使用Google Charts的corechart packages工具了。

查看<a href="http://blog.littlebill.me/2013/04/google-corechart-package-introduced.html?utm_source=googlechart-git&utm_medium=readme" target="_blank">demo入口</a>