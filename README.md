Lightning — 快速热区页面制作(移动端)解决方案 
=========

> 你是否被一大堆切图的重复劳动困恼？或是纠结如何快速生成一个手机页面么？或许你是时候尝尝Lightning了 :)

live demo：
----
#### [http://holyme.github.io/lightning/](http://holyme.github.io/lightning/)


特性：
----
- 简单、快速、免费。
- 你仅需要关注一张视觉图片。
- 适用于扁平的静态页面生成（如仅有区块超链接功能的运营页面）。
- 通过选区遮罩超链接方式快速生成页面。
- 选区可定制大小以及旋转定位，甚至为不规则形状。
- 生成的页面区块自动拉伸适应屏幕。
- 可定制模板进行二次开发。
- 生成代码可独立执行，可随意放置。
- 支持终端容器判断，同一点击热区可支持HTTP链接或APP URLSchema。

界面:
----
![demo it](https://raw.githubusercontent.com/holyme/lightning/master/_show/demo.gif)

安装说明：
----
1. 下载此git库中所有文件。
2. 放置于本地的HTTP服务环境（否则跨域无法获取模板）。
3. 访问站点根目录下的 index.html。


二次开发:
----

1. 模板存放于 tpls 下。
2. default 模板为最佳实践，具有简单的自适应特性，请注意所有JS脚本以及模板变量的移植($...)。
