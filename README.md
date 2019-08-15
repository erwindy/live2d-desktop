# live2d-desktop
使用electron构建的看板娘PC端桌面挂件，live2d以 https://github.com/fghrsh/live2d_demo 为基础修改（使用本地资源，不请求大佬的API了）
所以，大家可以直接下载使用。

在kbn文件中有打包好的exe文件，只能在windows64系统上运行。
若果想要其他平台的文件，需要安装electron以及electron-package两个包，然后修改主目录下的package.json文件中的packager字段，将electron-version的值换成你自己的electron版本（我的版本是6.0.2）。最后命令行cd到文件主目录里，运行命令 npm run-script packager即可得到更多平台的应用。

文件目录：
assets:live2d的相关文件。
kbn:打包输出文件。
Resources：寻找到的看板娘的资源文件。
index.html：主页面。
main.js：electron入口文件。
package。json：electron的配置文件。

依赖包：
electron
electron-package

有关于看板娘设置的内容请看 https://github.com/fghrsh/live2d_demo 。

