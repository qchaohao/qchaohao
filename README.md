- [MarkDown语言](#markdown语言)
  - [教程链接](#教程链接)
    - [基本语法](#基本语法)
    - [扩展语法](#扩展语法)
    - [转义字符](#转义字符)
  - [标题](#标题)
  - [文本](#文本)
  - [区块引用](#区块引用)
  - [分割线](#分割线)
  - [列表](#列表)
    - [无序列表](#无序列表)
    - [有序列表](#有序列表)
    - [任务列表](#任务列表)
  - [链接](#链接)
  - [图片](#图片)
  - [段落换行](#段落换行)
  - [表格](#表格)
  - [代码块](#代码块)
  - [脚注](#脚注)

---

# MarkDown语言

  >- ***Markdown*** 是一种轻量级标记语言，由 ***约翰·格鲁伯（John Gruber）*** 于2004年创建。
  >- 它的目标是实现“易读易写”，通过少量简单的语法对文本进行样式化，使得文档更容易阅读和写作。
  >- Markdown的优点包括内容与格式分离，专注于文字内容而不是排版样式，可以轻松导出HTML、PDF等多种格式的文件。
  >- 它兼容所有的文本编辑器与文字处理软件，具有可读性高、学习成本低的特点，能够提升写作和编辑的效率。

## 教程链接

  - 语法分 ***基本语法*** 和 ***扩展语法***。
  - [Markdown‌教程](https://markdown.com.cn/intro.html "Markdown‌教程")
  - [GitHub文档](https://docs.github.com/zh "GitHub文档")

### 基本语法

  - 这些是 John Gruber 的原始设计文档中列出的元素，所有 Markdown 应用程序都支持这些元素。

  | 元素                             | Markdown 语法                     |
  | :------------------------------- | :-------------------------------- |
  | ***标题（Heading）***            | # H1<br> ## H2                    |
  | 斜体（Italic）                   | \*italicized text*                |
  | ***粗体（Bold）***               | \*\*bold text**                   |
  | ***区块引用（Blockquote）***     | > blockquote                      |
  | ***分隔线（Horizontal Rule）***  | ---                               |
  | ***无序列表（Unordered List）*** | - First item<br> - Second item    |
  | ***有序列表（Ordered List）***   | 1. First item<br> 2. Second item  |
  | ***链接（Link）***               | \[title](https://www.example.com) |
  | ***图片（Image）***              | !\[alt text](image.jpg)           |
  | 代码（Code）                     | \`code\`                          |

### 扩展语法

  - 这些元素通过添加额外的功能扩展了基本语法，但是并非所有 Markdown 应用程序都支持这些元素。

  | 元素                              | Markdown 语法                                           |
  | :-------------------------------- | :------------------------------------------------------ |
  | ***删除线（Strikethrough）***     | \~~The world is flat.~~                                 |
  | ***任务列表（Task List）***       | - [x] Check<br> - [ ] Uncheck                           |
  | ***表格（Table）***               | \| T1 \| T2 \|<br> \| --- \| --- \|<br> \| A1 \| A2 \|  |
  | ***代码块（Fenced Code Block）*** | \```<br> {<br> "K1": "V1",<br> "K2": V2<br> }<br> ```   |
  | ***脚注（Footnote）***            | Here's a footnote. [^1]<br> [^1]: This is the footnote. |
  | 定义列表（Definition List）       | term<br> : definition                                   |
  | 标题编号（Heading ID）            | ### My Great Heading {#custom-id}                       |

### 转义字符

  - 要显示原本用于格式化 Markdown 文档的字符，请在字符前面添加 ***反斜杠*** 字符 **\\** 。

  | Character | Name                                                  |
  | :-------- | :---------------------------------------------------- |
  | **\\**    | backslash ***反斜杠***                                |
  | **\`**    | backtick ***反引号***                                 |
  | **\***    | asterisk/star ***星号***                              |
  | **_**     | underscore/underline ***下划线***                     |
  | **{ }**   | curly braces ***大（花）括号***                       |
  | **[ ]**   | brackets ***中（方）括号***                           |
  | **( )**   | parentheses ***小（圆）括号***                        |
  | **#**     | pound sign/hash mark/number sign ***井号***           |
  | **+**     | plus sign ***加号***                                  |
  | **-**     | minus sign (hyphen) ***减号（连字符）***              |
  | **.**     | dot ***点***                                          |
  | **!**     | exclamation point/mark ***感叹号***                   |
  | **\|**    | pipe ***管道***                                       |
  | **\>**    | greater than sign ***大于号***                        |
  | **:**     | colon ***冒号***                                      |
  | **~**     | tilde ***波浪号***                                    |
  | **^**     | caret/up-arrow head, circumflex accent ***脱字符号*** |

## 标题

  >- 语法：使用最多6个 ***井号*** **（ # ）** 来表示 **（ 1-6 ）** 级标题，井号的数量代表了标题的级别。
  >- 说明：数量越多字体越小。
  >- 样例：
  >   - \# 一级标题
  >   - \## 二级标题
  >   - \### 三级标题
  >   - \#### 四级标题
  >   - \##### 五级标题
  >   - \###### 六级标题

## 文本

  >- 使用 ***N*** 个 ***符号*** 在两边紧贴中间的文本。
  >- ***字体*** 优先使用 ***星号***，***分割线*** 和 ***列表*** 优先使用 ***减号***。
  >- ***符号和数字*** 优先使用 ***双星号***，***文字*** 优先使用 ***三星号***。
  >- 斜体：使用 单星号 （\**文本‌*\*）或 单下划线 （\__文本_\_）。
  >- ***粗体***：使用 ***双星号*** （\*\*‌**文本‌**\*\*）或 双下划线 （\_\___文本__\_\_）。
  >- ***粗斜体***：使用 ***三星号*** （\*\*\*‌***文本‌***\*\*\*）或 三下划线 （\_\_\____文本___\_\_\_）。
  >- ***删除线***：使用 ***双波浪号*** （\~\~~~文本‌~~\~\~）。
  >- ***上标***：使用 ***标签 sup 包围*** （\<sup>上标\</sup>，**2<sup>10</sup>**）。
  >- ***下标***：使用 ***标签 sub 包围*** （\<sub>下标\</sub>，**H<sub>2</sub>O**）。

## 区块引用

  >- 语法：使用一个 ***大于号*** **（ > ）** 然后加上空格。
  >- 说明：多行的话每行都使用符号，理论上可以无限嵌套，嵌套一个加一个符号。
  >- 样例：
  >>    \>>这是引用嵌套样例
  >>>   \>>>引用嵌套理论上可无限嵌套

## 分割线

  >- 语法：使用至少 ***三个*** 或以上 ***减号*** **（ --- ）**、星号（***）或下划线（___）。
  >- 说明：行内不能有其他的字符，可以在标记符中间加上空格。
  >- 样例：

  ---

## 列表

  - 可以将多个条目组织成无序或有序列表。

### 无序列表

  >- 语法：使用一个 ***减号*** **（ - ）**、加号（+）或星号（*）然后加上空格。
  >- 说明：理论上可以无限嵌套，最好第一级间隔2空格，下面都是间隔4空格。
  >- 样例：

  - 这是无序第一层
      - 这是无序第二层
          - 这是无序第三层

### 有序列表

  >- 语法：使用一个 ***数字*** **（ 1 ）** 加上 ***点*** **（ . ）** 然后加上空格。
  >- 说明：理论上可以无限嵌套，最好第一级间隔2空格，下面都是间隔4空格。
  >- 样例：

  1. 这是有序第一层
     1. 这是有序第二层
        1. 这是有序第三层

### 任务列表

  >- 语法：使用一个 ***减号*** 空格和 ***中括号*** 空格 **（ - [ ] ）** 组合。
  >- 说明：中括号里写 ***x*** 表示 ***已完成***。
  >- 样例：

  - [x] 这是任务第一层
      - [ ] 这是任务第二层
          - [x] 这是任务第三层

## 链接

  >- 语法：***\[超链接显示名](超链接地址 "超链接Title")***。
  >- 说明：
  >     - ***超链接显示名***【必须写链接说明文字】。
  >     - ***超链接地址***【网页的地址链接】。
  >     - 超链接title【在鼠标悬停在链接上时显示的文字，可选】。

## 图片

  >- 语法：***!\[图片Alt](图片Link "图片Title")***。
  >- 说明：
  >     - ***方括号*** 前增加了一个 ***感叹号*** **（ ! ）**。
  >     - ***图片Alt***【必须写图片说明文字】。
  >     - ***图片Link***【图片存储的地址链接】。
  >     - 图片Title【在鼠标悬停在图片上时显示的文字，可选】。

## 段落换行

  - 要创建段落，请使用 ***空白行*** 将一行或多行文本进行分隔。
  - 要创建换行，在文本末尾添加标签 ***(\<br>)***。

## 表格

  >- 使用三个或多个 ***减号*** **（ --- ）** 创建每列的标题，并使用管道 **（ \| ）** 分隔每列。
  >- 在 ***减号*** 的左侧，右侧或两侧添加 ***冒号*** **（ : ）**，可将文本对齐到左侧，右侧或中心。
  >- 可以在表格中设置文本格式，但不能添加标题，块引用，列表，水平规则，图像或HTML标签。
  >- 样例：

  | Column 1              |     Column 2      |               Column 2 |
  | :-------------------- | :---------------: | ---------------------: |
  | left-aligned 文本居左 | centered 文本居中 | right-aligned 文本居右 |

## 代码块

  >- 单个代码使用一个 ***反引号*** **（ \` ）** 前后包围。
  >- 多行代码块使用三个 ***反引号*** **（ \``` ）** 或 ***波浪号*** **（\~~~）** 前后包围。
  >- ***语法突出显示*** 可以在前面的 ***反引号*** 旁边指定一种语言，例如 ***python***。
  >- 样例：

  ```python
    def function():
      print(1)
  ```

## 脚注

  >- 脚注可以添加 ***注释*** 和 ***参考***，而不会使文档正文混乱。
  >- 创建脚注在 ***方括号*** 内添加单个 ***脱字号*** 和 ***标识符*** **（ \[^1] ）**。
  >- 标识符可以是 ***数字*** 或 ***单词***，但不能包含 ***空格*** 或 ***制表符***。
  >- 脚注具体内容可以再次使用创建符号并后跟 ***冒号*** **（ \[^1]: ）**。
  >- 有些显示 1 不准，我们可以从 **2** 开始计数。
  >- 样例：

  测试脚注1，[^2] 测试脚注2。[^3]
  [^2]: 测试脚注1内容。
  [^3]: 测试脚注2内容。
