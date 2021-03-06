# Sublime-Text安装详解~[2022.1.15]~

## 1、Sublime-Text介绍
Sublime-Text 是一款流行的代码编辑器软件，也是HTML和散文先进的文本编辑器，

可运行在Linux，Windows和Mac OS X。也是许多程序员喜欢使用的一款文本编辑器

软件。

### 特点
```markdown
- Sublime-Text 自带一个cmake，可直接编译代码，快捷键Ctrl + B
- Sublime-Text 是一款跨平台代码编辑器，在Linux、OS X和Windows下均可使用。
- Sublime-Text 是可扩展的，并包含大量实用插件，我们可以通过安装自己领域的插件来成倍提高工作效率。
- Sublime-Text 分别是命令行环境和图形界面环境下的最佳选择，同时使用两者会大大提高工作效率。
- Sublime-Text 为收费软件，建议有能力的人付费使用，以支持开发者。不过不购买也可以一直使用。

关键字:轻量、界面简洁、支持多国语言、可用插件丰富、多平台下载使用、配置简单，适合新手学习使用
```

## 2、Windows中安装

### 2.1、下载
可直接到sublime-text官方网站下载
[英文官网](https://www.sublimetext.com/)
~~[中文官网](https://sublimetextcn.com/)~~~[2022.1.17]~
> 中文官网下载的和英文官网下载的不是同一个，可以忽略

### 2.1、安装
基本上直接点击下一步就OK了，也可以安按照下面步骤操作
```
    打开下载完成的安装包
==> 在弹出的界面选择安装位置，软件比较轻量，C盘或者其他盘均可，然后点击Next
==> 在弹出的界面中勾上"Add to explorer context menu"，这个选项可以让我们在右击文件时多个"Open with Sublime Test"选项,勾上之后点击Next
==> 在弹出的界面中直接点击Install，然后等待安装完成
```

### 2.3、配置
安装好的sublime-text在桌面是不会自动创建快捷方式的，我们需要在开始菜单栏

中找到sublime-text点击打开，或者鼠标右击某个文件，选择"Open with Sublime 

Test"选项打开。   

#### 软件界面
英文界面 ==> 中文界面

sublime-text初始界面默认是英文的，对于英文比较厉害的同学可以选择直接使用英文界面，

但对于英文不是很强的同学就可以跟着下面步骤将界面修改为中文界面方便使用。

```
步骤:
        在sublime-text打开的界面中按Ctrl + Shift + P 键打开sublime-text的"Command Palette"悬浮对话框
    ==> 在弹出的对话框中输入"install"，然后对话框下面会出现选项卡，选择"Install Package Control"
    ==> 上一步操作是给我们的sublime下载一个插件管理工具，所以我们等待片刻，等出现一个弹窗，即为下载成功
    ==> 重新按Ctrl + Shift + P 键，在弹出的对话框中重新输入"install"，选择"Package Control:Install Package"，会出现一个新的对话框
    ==> 在新弹出的对话框中输入"ChineseLocalizations"，选择相对应的选项卡，等待片刻，会弹出一个说明文档，弹出的文档可直接关闭，并且我们的sublime-text会变成中文界面
```

#### 实用插件
EasyClangComplete
```
一个实用的代码补全工具，能够自动对输入的部分代码进行联想，然后直接使用Tab键补全代码
```
SublimeAStyleFormatter
```
SublimeAStyleFormatter 是一个简单的Sublime-Text代码格式化插件。
它提供了格式化 C、C++、Cuda-C++、OpenCL、Arduino、C# 和 Java 文件的能力。

代码格式化:将乱七八糟的代码规范输出，使代码更美观

使用方法:
    快捷键:
        Ctrl + Shift + F: 格式化当前文件中所有代码，会与QQ快捷键冲突，建议关闭QQ冲突快捷键
        Ctrl+ K, Ctrl+ F: 格式化当前选择
    鼠标右键:
        在界面中点击鼠标右键
        ==> 选择"AStyleFormatter"
        ==> 弹出的两个选择中，"Format"是格式化当前文件，"Format selection"是格式化当前选择
```
Convert​To​UTF8
```
    使用该插件可以编辑和保存目前Sublime-Text不支持编码的文件，特别是CJK用户使用的文件，如GB2312、GBK、BIG5、EUC-KR、EUC-JP等
```

### 2.4、sublime-text使用
打开文件
```
鼠标右键点击需要打开的文件，选择"Open with Sublime Test"即可
```
打开文件夹
```
打开sublime-text应用，左上角文件中选择打开文件夹即可
```

### 2.5、卸载插件
如果觉得插件不好用也可以将插件卸载了
```
步骤:
    在sublime-text打开的界面中按Ctrl + Shift + P 键打开sublime-text的"Command Palette"悬浮对话框
    ==> 在弹出的对话框中输入"remove"，然后对话框下面会出现选项卡，选择"Package Control:Remove Package"
    ==> 然后就可以看到对话框下面有许多选项卡，这些都是我们下载的插件，选择点击即可卸载插件了
```

## 3、Linux安装

### 3.1、两种方法

#### 方法一
```
下载:
    打开虚拟机软件VMware Workstation，然后打开Ubuntu
    ==> 在Ubuntu中点击右下角的小方块(显示应用程序)
    ==> 在应用程序中找到一个叫"Ubuntu 软件"的应用，点击打开它
    ==> 在应用界面找到一个放大镜(搜索)，在搜索框中输入"sublime"
    ==> 在弹出的选项中选择"sublime-text"，然后直接点击安装
    ==> 安装完之后就可以在应用程序中找到sublime-text了，右键它将它添加到收藏夹就可以直接在终端旁边打开了
    ==> 其他操作如英文改中文或者安装插件同Windows一样

如果需要卸载sublime，直接在"Ubuntu 软件"中找到它移除即可
```

#### ~~方法二~~~[2022.1.17]~
```
下载:
    打开虚拟机软件VMware Workstation，然后打开Ubuntu
    ==> 打开Ubuntu终端(虚拟机下面哪个图案为 ">_" 的应用)
    ==> 在打开的终端中输入"sudo add-apt-repository ppa:webupd8team/sublime-text-3"  (添加sublime text 3的仓库)
    ==> 在新出现的"[sudo] (用户名) 的密码:"后面输入密码即可，密码不可见，默认密码为 123456
    ==> 做完上面步骤之后没有出现别的意外情况即可在终端中输入"sudo apt update"   (更新软件库)
    ==> 然后在终端中输入"sudo apt install sublime-text-installer"   (下载软件sublime-test)
    ==> 等待下载完成，其他操作同Windows一样

如果需要卸载sublime，可在终端中输入"sudo apt remove sublime-test-installer",等待卸载完成即可
```
> 由于个人没有尝试的原因，导致方法二并不能成功的更新软件源，这里表示非常抱歉，之后我也是试着做了一遍，并修改了一下方法

#### 方法二
```
    下载:
        打开虚拟机软件VMware Workstation，然后打开Ubuntu
        ==> 打开Ubuntu终端(虚拟机下面哪个图案为 ">_" 的应用)
        ==> 在打开的终端中输入"wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -"  (安装 GPG 密钥)
        ==> 在新出现的"[sudo] (用户名) 的密码:"后面输入密码即可，密码不可见，默认密码为 123456
        ==> 上面步骤做完后会出现"OK"两个字符，接着再终端输入"sudo apt-get install apt-transport-https"(确保 apt 设置为使用 https 源)
        ==> 等待上一步完成，输入"echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list"(稳定版)
        ==> 做完上面步骤之后没有出现别的意外情况即可在终端中输入"sudo apt-get update"   (更新软件库)
        ==> 然后在终端中输入"sudo apt-get install sublime-text"   (下载软件sublime-test)
        ==> 等待下载完成，其他操作同Windows一样
    
    如果需要卸载sublime，可在终端中输入"sudo apt-get remove sublime-test",等待卸载完成即可
```
==**备注:如果连接超时导致无法下载和部分索引文件下载失败，请重新输入指令再次更新；**==

==**如果出现无法获得锁，不说别的，重启即可**==

### 3.2、sublime-text使用

#### 利用鼠标点击
使用方法和Windows相同，可以直接找到应用点击打开软件，或者鼠标右击文件/文件夹打开软件

#### 利用指令打开^[强烈推荐]^
在终端中使用指令来使用sublime-test打开文件
```
使用绝对路径打开文件:
    打开终端 ==> 在任意文件夹中输入"subl (文件/文件夹绝对路径)"
    如:"subl /mnt/hgfs/share/test.c"
使用相对路径打开文件:
    打开终端 ==> 打开文件/文件夹所在文件夹，如:"cd /mnt/hgfs/share" ==> 在当前文件夹路径中输入"subl (文件名/文件夹名)"即可
    如:"subl test.c"
```
~~如果使用"subl"指令来打开文件夹太慢,可以在终端中执行下列操作~~~[2022.1.17]~
```
方法一对应操作:
    打开终端
    ==> 输入"sudo ln -s /snap/sublime-text/112/opt/sublime_text/sublime_text /usr/local/bin/subl"
    ==> 再使用"subl"指令就变快了

方法二对应操作
    打开终端
    ==> 输入"sudo ln -s /opt/sublime_test/sublime_test /usr/local/bin/subl"
    ==> 再使用"subl"指令就变快了
```
> 这一步可不做，新版的sublime-text会自动创建软连接
