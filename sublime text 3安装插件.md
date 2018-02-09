## 1. 下载和安装
[sublime text 3](http://www.sublimetext.com/)

### 1. 激活
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
### 2. 为sublime text 3安装插件
    sublime text 3支持众多插件，可极大提高我们的开发效率；作为前端的学习者或者初级开发人员建议安装：Emmet、HTML-CSS-JS Prettify、SublimeCodeIntel
	1. Package Control组件在线安装
    按Ctrl+`调出console（注：避免热键冲突）
    粘贴以下代码到命令行并回车：import urllib.request,os; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); open(os.path.join(ipp, pf), 'wb').write(urllib.request.urlopen( 'http://sublime.wbond.net/' + pf.replace(' ','%20')).read())
![](https://i.imgur.com/R7a2xCo.png)

	3. 重启Sublime Text 3。
	4. 如果在Perferences->package settings中看到package control这一项，则安装成功。

![](https://i.imgur.com/GJ8lVPW.png)

    5. 用Package Control安装插件的方法：
    按下Ctrl+Shift+P调出命令面板
    输入install 调出 Install Package 选项并回车，然后在列表中选中要安装的插件
![](https://i.imgur.com/E7JdkRT.png)
### 3. 熟悉常用快捷键