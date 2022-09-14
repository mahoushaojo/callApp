### 🎗️通过浏览器唤起APP打开指定链接

#### 🔗DEMO：[https://mahoushaojo.github.io/callApp/index.html](https://mahoushaojo.github.io/callApp/index.html)

##### 🧰该工具的作用：

​	基于APP嵌入H5的项目，在安卓和ios不同型号机型的情况下，可能会出现各种`样式问题、兼容问题、APP_jsbridge对接问题`等，而目前没有成熟的`解决方案🗒️`，只能通过在本地进行改动之后 然后部署到指定的环境下，然后在APP中进行调试和验证，这样做不仅效率极低，而且非常耗费服务器资源、并且重复提交commit也使仓库代码记录显得混乱😥.

​	基于上面的问题，和`APP`端协商🦜，让客户端提供指定的协议，然后通过浏览器的方式来唤起`APP`打开指定的网页，这个网页可以是`本地服务🖥️`的地址，在本地进行修改后，可以立马就能在`APP`内部调试，节省了反复部署和提交的时间⏱️。并且使和`APP`对接`jsBridge`更加方便。能够有效的提升开发效率，节省调试成本😸.

##### ✨使用说明：

1. 在`手机📱`中安装指定版本的`助手APP`.
2. 如果需要调试`本地服务🖥️`,那么`手机📱`无线网需要和`本地服务🖥️`在同一个局域网内，并且可以通过`ping ip`的方式互相获取到对方.
3. 在`手机📱`默认浏览器中打开本项目`demo`地址，然后按照`demo`中的说明进行操作，即可在APP中打开指定的链接，然后进行调试.

##### ⚠️使用注意

​**使用**：使用 `pnpm run serve:<环境>`来开启服务,使用`Network`对应的`IP`地址来打开服务, 打开[工具](https://mahoushaojo.github.io/callApp/index.html) 安装工具中说明的操作

**环境**：dev、test、beta

**例子**：`pnpm run serve:dev`
