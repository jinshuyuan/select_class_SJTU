# select_class_SJTU
javascript写的chrome插件，选课。
对javascript及异步编程没怎么了解，代码十分丑。

## 原理
chrome插件对目标网站注入javascript，对网页进行控制。也许比selenium+python要稍微方便一点？hhh

## 环境
google chrome浏览器

## 安装
- 可将该文件夹打包成.crx安装，不过貌似谷歌应用商店已经禁止了未上架插件的安装。。。
- 可在扩展程序界面打开开发者模式，点击`加载已解压的扩展程序...`，将该文件夹导入。

## 设置
* 在插件的设置界面进行设置。由于小学期界面变化，暂不支持小学期的选课。。。
* 其中通识课程需要输入相应的学科，如“人文学科”，限选课程需要输入相应的模块，如“基础选修课”。
* “课号”一栏中需要输入在点击“课程安排”后显示的表格中相应老师及时间所对应的课号栏内的文本，如“014-(2015-2016-1)CS902(行政班)”。

## 使用
成功安装插件后，打开教学信息服务网并成功登陆后，点击插件图标可看到开始按钮，点击即可开始。使用过程中可能会有一定概率跳转到其他课程界面（应该是学校服务器的原因），对于这种情况，能够在F12的开发者界面中看到“未发现课程”的输出，但并不影响使用。

## 效果
成功提交之后会弹出窗口提示并停止该过程。具体效果如何，emmmm...，只要坚持，效果还可以。
