# 讲给Android程序员看的前端教程(01)——HTML5入门 

## 1. HTML、CSS、JavaScript的关系
  通常我们说的页面或者前端，一般都包括了：HTML、CSS、JavaScript。那么这三者在页面中分别承担什么角色呢？简单地来讲：

    1. HTML负责页面的结构和语义。比如，页面的标题，页面的区域划分，语义化标签等等都是由HTML来实现的。
    2. CSS负责页面的样式。比如，背景颜色，文本的大小，边框等等与样式相关的部分都由CSS承担。
    3. JavaScript负责页面的行为和交互。比如，点击按钮后改变文本颜色，计算两个数据的相加，存储数据等等；这些都是由JavaScript负责。

## 2. HTML5的特点及其优势
 
### 1. 至于HTML的发展历史，我们不再赘述；我们要了解的是HTML5有哪些特点和优势。HTML5是新一代开发Web富客户端应用程序整体解决方案 ，从广义上来讲：HTML5=HTML5+CSS3+JavaScript，也就是说HTML5是在原来的HTML，CSS，JavaScript基础上的整合和增强。

    1. HTML5解决跨浏览器问题。目前，各大浏览器厂商对HTML5表现出极大的热情，全力支持HTML5的广泛应用。假以时日，HTML5将改变HTML+CSS+JavaScript在跨浏览器时带来的各种诟病。

    2. HTML5定义了一系列新元素，比如：智能表单、新的语义标签、多媒体标签等，这些新元素有助于开发者创建富互联网应用

    3. HTML5提供一系列JavaScript API；比如：重力感应、文件访问、地理定位、硬件访问等等，这些API可以在浏览器内实现类原生应用

    4. HTML5提供Canvas元素用于游戏开发。

    5. HTML5提供操作多媒体的相关元素。以往，在HTML中实现音频、视频的播放往往需要借助第三方插件；现在，利用HTML5自身的元素就能实现视频，音频的基本操作。
 
### 2. 抛开具体的技术不谈，HTML5的出现也给开发人员带来了极大的便利。在此，主要谈三点。
    1. 迭代速度快
    相比IOS和Android的迭代速度，HTML5快了不是一点半点，简直都快飞起来了。变更后上线的时间极大缩短，用户也可毫无感知的情况下获取到最新的变化。
    2. HTML5兼容性强
    HTML5的兼容性主要体现在屏幕的大小和小部分极其殊的机型，发现Bug之后改起来也容易得多。这比起让人痛苦不堪的Android碎片化而言确实轻松了不少。
    3. 开发成本较低
    比如要做一个移动端应用程序，为了兼顾到大部分用户，那么一般都会分为Android和IOS两个APP。对于公司而言，势必增加开发成本。如果采用THML5开发呢？嗯哼，大部分工作都可以用HTML5完成，从而缩短开发周期，降低开发成本。
## 3. HTML5开发工具（详见sublime text 3安装插件）

目前，THML5的主流开发工具有：Adobe Dreamweaver、sublime text 3、 WebStorm。在本教程中，我们选用sublime text 3作为开发工具。

    1. 下载和安装
[sublime text 3](http://www.sublimetext.com/)
    该过程非常简单，按照官方文档进行即可，在此不再赘述。
		（注册码）
		—– BEGIN LICENSE —–
		TwitterInc
		200 User License
		EA7E-890007
		1D77F72E 390CDD93 4DCBA022 FAF60790
		61AA12C0 A37081C5 D0316412 4584D136
		94D7F7D4 95BC8C1C 527DA828 560BB037
		D1EDDD8C AE7B379F 50C9D69D B35179EF
		2FE898C4 8E4277A8 555CE714 E1FB0E43
		D5D52613 C3D12E98 BC49967F 7652EED2
		9D2D2E61 67610860 6D338B72 5CF95C69
		E36B85CC 84991F19 7575D828 470A92AB
		—— END LICENSE ——

    2. 为sublime text 3安装插件
    sublime text 3支持众多插件，可极大提高我们的开发效率；作为前端的学习者或者初级开发人员建议安装：Emmet、HTML-CSS-JS Prettify、SublimeCodeIntel
    3. 熟悉常用快捷键
    每个开发工具都有众多的快捷键，不必全部熟记；掌握常用的几个快捷键即可。

## 4. HTML5入门示例

在介绍完HTML5及其开发工具后，按照国际惯例，我们就要来写一个Hello World了。

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>title</title>
</head>
<body>
    <p>Hello World</p>
</body>
</html>

嗯哼，我们花了少许时间就写好了HTML5的入门示例，运行在浏览器中即可看到文字Hello World