# markdown用法详解~[2022.1.17]~

## 1、markdown介绍
```markdown
Markdown 是一种轻量级的标记语言，可用于在纯文本文档中添加格式化元素。Markdown
由John Gruber 于 2004 年创建，如今已成为世界上最受欢迎的标记语言之一。

1. 专注于文字内容；
2. 纯文本，易读易写，可以方便地纳入版本控制；
3. 语法简单，没有什么学习成本，能轻松在码字的同时做出美观大方的排版。
```

## 2、markdown用法详解

### 2.1、多级标题用法
```
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

### 2.2、语句操作
```
加粗:
    **xxxx**
斜体:
    *xxxx*
删除线:
    ~~xxxx~~
高亮
    ==xxxx==
```

### 2.3、列表
```
有序列表:
    1. 内容
    2. 内容
    3. 内容
    ...
无序列表:
    - 内容
    - 内容
    - 内容
    ...
多级列表:
    不同级别之间使用Tab键来分级
    如:
        1. 
            1. 
            2. 
        2. 
        3. 
    or:
        - 
            -
            -
        -
        -

```

### 2.4、引用
```
> 一级引用
>> 二级引用
>>> 三级引用
...
```

### 2.5、分隔符
```
第一种:
    ---
第二种:
    ***
```

### 2.6、代码
```
代码段:
    `code`
代码块:
    ```语言类型
        内容
```

### 2.7、脚注
```
下标:
    H~2~O
上标:
    X^2^
```

### 2.8、表格
```
    左对齐:        右对齐          居中对齐
|   xxxxx       |   xxxxx       |   xxxxx       |
| :------------ | ------------: | :-----------: |
|   xxxxx       |   xxxxx       |   xxxxx       |
|   xxxxx       |   xxxxx       |   xxxxx       |
|   xxxxx       |   xxxxx       |   xxxxx       |
```

### 2.9、链接
```
同文本跳转:
    [自定义名称](标题名)
网络地址跳转
    [自定义名称](网络地址)
```

### 2.10、插入图片
```
本地图片:
    ![自定义名称](相对路径/绝对路径)
网络图片:
    第一种:
        ![自定义名称](网络地址)
    第二种:
        <img src="网络地址" alt="自定义名称" style="zoom:百分比大小;" />
    插入方式:
        ![自定义名称](网络地址#插入位置)
            pic_center: 居中插入
            pic_left:   居左插入
            pic_right:  居右插入
        <img src="网络地址" alt="自定义名称" style="zoom:百分比大小;" align="插入位置" />
            center:    居中插入
            left:      居左插入
            right:     居右插入    
```

## 3、markdown官方文档
[<img src="https://w.wallhaven.cc/full/g7/wallhaven-g71y17.jpg" alt="官方手册" style="zoom:50%;">](https://markdown.com.cn/basic-syntax/)

## 4、VScode中markdown快捷键
|快捷键                     |响应                               |
| :-----------------------: | :-------------------------------: |
|Ctrl + k + s	            |查看与更改键盘快捷方式|
|Ctrl + b	                |加粗|
|Ctrl + m	                |放大|
|Ctrl + g	                |跳转到?行|
|Ctrl + h                   |查找与替换|
|Ctrl + j                   |调出电脑 cmd 控制终端|
|Ctrl + l	                |向下选中|
|Ctrl + w	                |关闭当前文件|
|Ctrl + i	                |斜体|
|Ctrl + o	                |打开文件|
|Ctrl + Tab	                |在不同工程之间切换|
|Ctrl + k + z	            |全屏显示当前工程|
|Ctrl + k + c	            |VScode 剪切板|
|Ctrl + k + m               |选择语言模式|
|Ctrl + k + d               |只读模式(会指示你未保存的更改)|
|Ctrl + k + f               |关闭当前实例的工作区或文件夹|
|Ctrl + k + e               |打开资源管理器|
|Ctrl + k + r	            |打开当前文件所在文件夹|
|Ctrl + k + u	            |关闭当前工程之外的所有工程|
|Ctrl + k + o	            |当前工程在新窗口开启|
|Ctrl + Shift + x           |扩展商店|
|Ctrl + Shift + c	        |进入当前工程文件目录下 cmd 控制终端|
|Ctrl + Shift + v	        |检视当前 Markdown 文件的预览|
|Ctrl + Shift + b	        |配置生成任务|
|Ctrl + Shift + n	        |打开新的 VScode 窗口|
|Ctrl + Shift + m	        |打开 VScode 的调试窗口 问题 一栏|
|Ctrl + Shift + d	        |打开 运行 和 调试 侧栏|
|Ctrl + Shift + g	        |打开 源代码管理 侧栏|
|Ctrl + Shift + h	        |搜索和替换|
|Ctrl + Shift + k	        |删除当前行|
|Ctrl + Shift + w	        |关闭 VScode|
|Ctrl + Shift + e	        |打开资源管理器|
|Ctrl + Shift + r	        |重构操作|
|Ctrl + Shift + y	        |打开 VScode 的调试窗口 调试控制台 一栏|
|Ctrl + Shift + u	        |打开 VScode 的调试窗口 输出 一栏|
|Ctrl + Shift + o	        |查看 Markdown 章节目录|
|Ctrl + Shift + p	        |搜索 VScode 功能|
|Ctrl + k + Ctrl + c/u/q	|注释 或 取消注释|
|Ctrl + k + Ctrl + b	    |一个类似于书签的东西|
|Ctrl + k + Ctrl + m	    |扩展商店|
|Ctrl + k + Ctrl + l        |展开或收起当前章节|
|Ctrl + k + Ctrl + e        |打开资源管理器|
|Ctrl + k + Ctrl + r        |打开键盘快捷方式 PDF|
|Ctrl + k + Ctrl + t	    |打开颜色主题|
|Ctrl + k + Ctrl + p	    |当前打开的文档|

***
