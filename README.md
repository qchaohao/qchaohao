# fronters

![Github图示](./imgs/logo.png)

[![GoDoc](https://godoc.org/github.com/gohugoio/hugo?status.svg)](https://godoc.org/github.com/gohugoio/hugo)
[![Tests on Linux, MacOS and Windows](https://github.com/gohugoio/hugo/workflows/Test/badge.svg)](https://github.com/gohugoio/hugo/actions?query=workflow%3ATest)
[![Go Report Card](https://goreportcard.com/badge/github.com/gohugoio/hugo)](https://goreportcard.com/report/github.com/gohugoio/hugo)

[![啊](https://img.shields.io/badge/hello_world-pyleo-blue)](https://www.baidu.com)

[Footers](#footers) | [返回章节](#chapters)

---

# contents
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> 1. [基本简介](#基本简介)
> 2. [语法分类](#语法分类)
>     1. [基本语法](#基本语法)
>     2. [扩展语法](#扩展语法)
>     3. [转义语法](#转义语法)
> 3. [文本定义](#文本定义)
>     1. [标题文本](#标题文本)
>     2. [强调文本](#强调文本)
>     3. [分割文本](#分割文本)
> 4. [写法规范](#写法规范)
>     1. [内容写法](#内容写法)
>     2. [标签写法](#标签写法)
>     3. [导图写法](#导图写法)
> 5. [列表分类](#列表分类)
>     1. [无序列表](#无序列表)
>     2. [有序列表](#有序列表)
>     3. [任务列表](#任务列表)
> 6. [链接定义](#链接定义)
>     1. [网页链接](#网页链接)
>     2. [图片链接](#图片链接)
>     3. [脚注链接](#脚注链接)
> 7. [区块规范](#区块规范)
>     1. [引用区块](#引用区块)
>     2. [表格区块](#表格区块)
>     3. [代码区块](#代码区块)
>
> [返回目录](#contents) | [返回章节](#chapters)

# chapters
## 基本简介
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - ***Markdown*** 是一种轻量级标记语言，由 **约翰·格鲁伯(John Gruber)<sup>!!!</sup>** 于2004年创建。
> - 目标是实现“易读易写”，通过简单语法对文本进行样式化，使文档更容易阅读，提升写作和编辑的效率。
> - 优点包括内容与格式分离，专注于文字内容而不是排版样式，可以轻松导出HTML、PDF等多种格式的文件。
> - ***基本语法*** 是原始设计文档中列出的元素，所有应用程序都支持这些元素。
> - ***扩展语法*** 通过添加额外的功能扩展基本语法，但并非所有应用程序都支持这些元素。
> - [Obsidian Helps](https://help.obsidian.md/syntax) :heart:
> - [Markdown‌ Docs](https://markdown.com.cn/intro.html)
> - [Github Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
> - [Github Shields](https://shields.io/)
> - https://shields.io/badges/static-badge
> - https://simpleicons.org/
> - [Github Emojis](https://gist.github.com/rxaviers/7360908) :smiley:
>
> [返回目录](#contents) | [返回章节](#chapters)

## 语法分类
### 基本语法
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> | 基本元素 | 标记语法 |
> | :--- | :--- |
> | **标题(Heading)** | # H1标题<br>## H2标题 |
> | **粗体(Bold)** | \*\*bold text** |
> | **粗斜体(Bold)** | \*\*\*bold italic text*** |
> | **分隔线(Horizontal Rule)** | --- |
> | **无序列表(Unordered List)** | - First item<br>- Second item |
> | **有序列表(Ordered List)** | 1. First item<br>2. Second item |
> | **链接(Link)** | \[title](https://www.example.com) |
> | **图片(Image)** | \!\[alt text](https://www.example.com/image.jpg) |
> | **引用(Quote)** | > quote text |
> | 斜体(Italic) | \*italicized text* |
> | 代码段(Code) | \`code\` |
> | 内嵌HTML标签 | \<em\>word\</em\> |
>
> [返回目录](#contents) | [返回章节](#chapters)

### 扩展语法
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
> 
> | 扩展元素 | 标记语法 |
> | :--- | :--- |
> | **删除线(Strikethrough)** | \~\~The world is flat.\~\~ |
> | **任务列表(Task List)** | - [x] Check<br>- [ ] Uncheck |
> | **脚注(Footnote)** | Here's a footnote. [\^a1]<br>[\^a1]: This is the footnote. |
> | **表格(Table)** | \| T1 \| T2 \|<br>\| --- \| --- \|<br>\| A1 \| A2 \| |
> | **代码块(Code Block)** | \```<br>{<br>&emsp;"K1": "V1",<br>&emsp;"K2": V2<br>}<br>\``` |
>
> [返回目录](#contents) | [返回章节](#chapters)

### 转义语法
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
> 
> | 可做转义 | 字符名称 |
> | :--- | :--- |
> | **\\** | backslash ***反斜杠*** |
> | **\`** | backtick ***反引号*** |
> | **\*** | asterisk ***星号*** |
> | **\_** | underscore/underline ***下划线*** |
> | **{ }** | curly braces ***大/花括号*** |
> | **[ ]** | brackets ***中/方括号*** |
> | **( )** | parentheses ***小/圆/括号*** |
> | **#** | pound sign/hash mark ***井号*** |
> | **+** | plus sign ***加号*** |
> | **-** | minus sign (hyphen) ***减号/连字符*** |
> | **.** | dot ***点*** |
> | **!** | exclamation point/mark ***感叹号*** |
> | **\|** | pipe ***管道*** |
> | **\>** | greater than sign ***大于号*** |
> | **:** | colon ***冒号*** |
> | **~** | tilde ***波浪号*** |
> | **^** | caret/up-arrow head, circumflex accent ***脱字符号*** |
>
> [返回目录](#contents) | [返回章节](#chapters)

## 文本定义
### 标题文本
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - ***语法：*** 使用最多6个 ***井号( # )*** 加一个空格来表示6级标题，数量越多字体越小。  
> - ***说明：*** 可以和网页链接组合跳转，标题需单独一行不能被包含。  
> - ***举例：***\
> \# 一级标题\
> \## 二级标题\
> \### 三级标题\
> \#### 四级标题\
> \##### 五级标题\
> \###### 六级标题
>
> [返回目录](#contents) | [返回章节](#chapters)

### 强调文本
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - ***粗体***：使用 ***双星号( \*\*‌ )*** 前后包围内容 **文本‌**。
> - ***粗斜体***：使用 ***三星号( \*\*\* )*** 前后包围内容 **‌*文本‌***。
> - ***删除线***：使用 ***双波浪号( \~\~ )*** 前后包围内容 ~~文本‌~~。 
> - ***上标***：使用标签 ***\<sup>上标\</sup>*** 包围，**2<sup>10</sup>**。
> - ***下标***：使用标签 ***\<sub>下标\</sub>*** 包围，**H<sub>2</sub>O**。
> - 代码：使用 ***单反引号(\`)*** 前后包围内容 `code`，转义需要 ***双反引号( \`\` )***。
>
> [返回目录](#contents) | [返回章节](#chapters)

### 分割文本
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 创建 ***分隔线(Horizontal Rule)*** 使用3个以上 ***减号( --- )*** ，行内不能有其他的字符。
> - 创建 ***段落(Paragraph)*** 使用空白行将一行或多行文本进行分隔。
> - 创建 ***换行(Line Break)*** 使用 ***反斜杠( \ )***，或2个以上空格。
> - 创建 ***空格*** 使用 ***\&nbsp;*** 实体字符。
> - 创建 ***缩进*** 使用 ***\&emsp;*** 实体字符。
> - 创建 区块(Block) 使用每行4个空格，但内容没有任何格式。
>
> [返回目录](#contents) | [返回章节](#chapters)

## 写法规范
### 内容写法
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 文件头部必须建立 ***主页图片和目录*** ，并以 ***分割线*** 区分。
> - 单独强调文本用 ***粗体***，混在普通文本里用 ***粗斜体***，前后空格隔开。
> - 使用 ***小括号*** 包围强调的 ***符号和数字***，和括号用空格隔开，避免看不清。
> - 使用 ***小括号*** 包围的文字不需要空格隔开。
> - ***强调文本使用星号标记，分割线和列表使用减号标记<sup>!!!</sup>***。
> - ***粗斜体的星号和括号不相连使用<sup>!!!</sup>***，有需要的话用中文括号。
> - 内容首先要建立 ***引用***，用于区别上下文不同的内容。
>
> [返回目录](#contents) | [返回章节](#chapters)

### 标签写法
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
>
> - **@@..>** 代表 ***NOTE*** 重要的提示或背景信息‌，**与众不同的**，使用粗体或粗斜体。
> - **@@..!** 代表 ***FOOL*** 不能忘记或不能更改的，**不能出错的<sup>!!!</sup>**，使用强调加三个叹号。
> - **@@..?** 代表 ***TODO*** 待完成的或要待实现的，**未想明白的<sup>???</sup>**，使用强调加三个问号。
> - **@@..+** 代表 ***DOIT*** 已知问题或需要修复的，**加急去做的<sup>+++</sup>**，使用强调加三个加号。
> - **@@..=** 代表 ***DEAD*** 有争议或有重启的价值，~~历史信息的~~，只使用删除线。
> - 写代码时标签颜色依次为 橙FF7F00，红FF0000，品FF00FF，青00FFFF，紫7F00FF。
>
> [返回目录](#contents) | [返回章节](#chapters)

### 导图写法
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 一定要有 ***标题和列表***，最好不要多行。
> - ***引用*** 的内容不被大部分识别。
> - ***列表*** 和 ***表格或代码块*** 同一级不能同时存在。
> - ***图片*** 最好切割大小并使用基本语法引用。
>
> [返回目录](#contents) | [返回章节](#chapters)

## 列表分类
### 无序列表
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> 1. ***语法：*** 使用一个 ***减号( - )*** 加上一个空格。
> 2. ***说明：*** 理论上可以无限嵌套，下层标记符应缩进在上层第一个文本字符的正下方。
> 3. ***举例：***
> - 这是无序列表第一层  
> - 这是第一层换行  
>    - 这是无序列表第二层 
>       - 这是无序列表第三层 
>       - 这是第三层换行
>    - 这是无序列表第二层  
>
> [返回目录](#contents) | [返回章节](#chapters)

### 有序列表
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - ***语法：*** 使用一个 ***数字( 1 ) + 点( . )*** 加上一个空格。
> - ***说明：*** 理论上可以无限嵌套，下层标记符应缩进在上层第一个文本字符的正下方。
> - ***举例：***
> 1. 这是有序列表第一层
> 2. 这是第一层换行
>     1. 这是有序列表第二层
>         1. 这是有序列表第三层
>         2. 这是第三层换行
>     2. 这是有序列表第二层
>
> [返回目录](#contents) | [返回章节](#chapters)

### 任务列表
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - ***语法：*** 使用一个 ***减号 + 中括号( - [ ] )*** 加上一个空格。
> - ***说明：*** 中括号里写 ***x*** 表示 ***已完成***。
> - ***举例：***
> - [ ] 这是任务列表第一层
> - [x] 这是第一层换行
>    - [ ] 这是任务列表第二层
>       - [ ] 这是任务列表第三层
>       - [x] 这是第三层换行
>    - [ ] 这是任务列表第二层
>
> [返回目录](#contents) | [返回章节](#chapters)

## 链接定义
### 网页链接
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 语法：**\[网页提示](网页链接)**。
> - 说明：
>    - ***网页提示：*** 【写网页提示文字】。
>    - ***网页链接：*** 【网页的链接地址】。
> - 举例：[Obsidian Help](https://help.obsidian.md/syntax)
>
> [返回目录](#contents) | [返回章节](#chapters)

### 图片链接
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 语法：**\!\[图片提示](图片链接)**。
> - 说明：
>    - ***图片提示：*** 【写图片提示文字】。
>    - ***图片链接：*** 【图片的链接地址】。
> - 举例：\
> ![GitHub图示](./imgs/logo.png)
>
> [返回目录](#contents) | [返回章节](#chapters)

### 脚注链接
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
>
> - 语法：**\[\^a1]，\[\^a1]:**。
> - 说明：
>    - ***标识符*** 可以是 ***数字或单词***，但不包含 ***空格或制表符***。
>    - 在内容后紧跟脚注标记，脚注的内容是要单独起一行加上 ***冒号***。
> - 举例：\
> 测试脚注1[^a1] ，测试脚注2[^a2]。  
>
> [^a1]: 测试脚注1的内容。 
> [^a2]: 测试脚注2的内容。
>
> [返回目录](#contents) | [返回章节](#chapters)

## 区块规范
### 引用区块
> [!NOTE]
> [Fronters](#fronters) | [Footers](#footers)
> 
> - 使用一个 ***大于号( > )*** 加上一个空格。
> - 理论上可以无限嵌套，嵌套一层加一个标记。
> - ***警报(alerts)*** 要单独一行，下行一定要紧跟内容，Github不支持改Title和嵌套。
> - ***[!NOTE]，[!TIP]，[!WARNING]*** 交替使用。
>
>> \>> 这是引用第二层  
>> 这是第二层换行
>>> \>>> 这是引用第三层   
>>> 这是第三层换行 
>
> [返回目录](#contents) | [返回章节](#chapters)

### 表格区块
> [!TIP]
> [Fronters](#fronters) | [Footers](#footers)
>
> - 使用 ***管道( \| )*** 分隔每一列的内容，两边各留一个空格即可。
> - 使用 ***分割线*** 在第二行分割表头和表身。
> - 使用 ***冒号*** 在 ***分割线*** 两侧放置，可以显示对齐。
> - 使用 ***\<br>*** 在表格内换行。
> - 可以在表格中设置文本格式，但不能添加标题，引用，列表，图像。
>
> | Column 1 | Column 2 | Column 2 |
> | :--- | :---: | ---: |
> | left-aligned 文本居左 | centered 文本居中 | right-aligned 文本居右 |
>
> [返回目录](#contents) | [返回章节](#chapters)

### 代码区块
> [!WARNING]
> [Fronters](#fronters) | [Footers](#footers)
>
> - 使用 ***三反引号(\`)*** 前后包围内容，转义需要 ***四反引号( \` )***。
> - 在第一个标记后加入具体语言名称，会具体对应。
>
> ```python
>  ---------- ---------- ---------- ---------- ---------- ---------- ---------- ----------
> 	# 多行代码块使用三个 反引号 ( ``` ) 前后包围。
> 	# 语法突出显示 可以在前面的 反引号 旁边指定一种语言，例如 python。
> 
> 	def function(n):
> 		print(n)
> 
> 		for i in range(10):
> 			print(i)
> 
> 		if True:
> 			print(2)
> 		else:
> 			print(3)
> 
> ```
>
> [返回目录](#contents) | [返回章节](#chapters)

# footers
[Fronters](#fronters) | [返回目录](#contents)
