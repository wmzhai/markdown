
### 1. MARKDOWN是*什么*？
**MARKDOWN**是一种轻量级**标记语言**，它以纯文本形式(_易读、易写、易更改_)编写文档，并最终以HTML格式发布。    
**MARKDOWN**也可以理解为将以MARKDOWN语言编写的语言转换成HTML内容的工具，最初是一个perl脚本_Markdown.pl_。    


### 2. _为什么_要使用它？ ###
- 它是易读（_看起开舒服_）、易写（_语法简单_）、易更改纯文本。处处体现着极简主义的影子。
- 兼容HTML。
- 可以转换为HTML格式发布。
- 跨平台使用。
- 越来越多的网站支持Markdown。
 
### 3. _怎么_使用？ ###
如果不算**扩展**，Markdown的语法绝对**简单**到让你爱不释手。

Markdown语法主要分为如下几大部分：
**标题**，**段落**，**区块引用**，**代码区块**，**强调**，**列表**，**分割线**，**链接**，**图片**，**反斜杠 `\`**，**符号'`'**。

#### 3.1 标题 ####
两种形式：  
1）使用`=`和`-`标记一级和二级标题。
>一级标题   
> `=========`   
> 二级标题    
> `---------`
  
效果：
>一级标题   
> =========   
> 二级标题
> ---------  

2）使用`#`，可表示1-6级标题。
>\# 一级标题   
>\## 二级标题   
>\### 三级标题   
>\#### 四级标题   
>\##### 五级标题   
>\###### 六级标题    

效果：
># 一级标题   
>## 二级标题   
>### 三级标题   
>#### 四级标题   
>##### 五级标题   
>###### 六级标题 

#### 3.2 段落 ####
段落的前后要有空行，所谓的空行是指没有文字内容。若想在段内强制换行的方式是使用**两个以上**空格加上回车（引用中换行省略回车）。

#### 3.3 区块引用 ####
在段落的每行或者只在第一行使用符号`>`,还可使用多个嵌套引用，如：
>\>区块引用  
>\>>嵌套引用  

效果：
>区块引用  
>>嵌套引用 

#### 3.4 代码区块 ####
代码区块的建立是在每行加上4个空格或者一个制表符（如同写代码一样）。如
普通段落：

void main()    
{    
    printf("Hello, Markdown.");    
}    

代码区块：

    void main()
    {
        printf("Hello, Markdown.");
    }

**注意**:需要和普通段落之间存在空行。

#### 3.5 强调 ####
在强调内容两侧分别加上`*`或者`_`，如：
>\*斜体\*，\_斜体\_    
>\*\*粗体\*\*，\_\_粗体\_\_

效果：
>*斜体*，_斜体_    
>**粗体**，__粗体__

#### 3.6 列表 ####
使用`·`、`+`、或`-`标记无序列表，如：
> \-（+\*） 第一项
> \-（+\*） 第二项
> \- （+\*）第三项

**注意**：标记后面最少有一个_空格_或_制表符_。若不再引用区块中，必须和前方段落之间存在空行。

效果：
> - 第一项
> - 第二项
> - 第三项

有序列表的标记方式是将上述的符号换成数字,并辅以`.`，如：
> 1 . 第一项   
> 2 . 第二项    
> 3 . 第三项    

效果：
> 1. 第一项
> 2. 第二项
> 3. 第三项

#### 3.7 分割线 ####
分割线最常使用就是三个或以上`*`，还可以使用`-`和`_`。

#### 3.8 链接 ####
链接可以由两种形式生成：**行内式**和**参考式**。
**行内式**：
>\[younghz的Markdown库\]\(https:://github.com/younghz/Markdown "Markdown"\)。

效果：
>[younghz的Markdown库](https:://github.com/younghz/Markdown "Markdown")。

**参考式**：
>\[younghz的Markdown库1\]\[1\]    
>\[younghz的Markdown库2\]\[2\]    
>\[1\]:https:://github.com/younghz/Markdown "Markdown"    
>\[2\]:https:://github.com/younghz/Markdown "Markdown"    

效果：
>[younghz的Markdown库1][1]    
>[younghz的Markdown库2][2]

[1]: https:://github.com/younghz/Markdown "Markdown"
[2]: https:://github.com/younghz/Markdown "Markdown"

**注意**：上述的`[1]:https:://github.com/younghz/Markdown "Markdown"`不出现在区块中。

#### 3.9 图片 ####
添加图片的形式和链接相似，只需在链接的基础上前方加一个`！`。
#### 3.10 反斜杠`\` ####
相当于**反转义**作用。使符号成为普通符号。
#### 3.11 符号'`' ####
起到标记作用。如：
>\`ctrl+a\`

效果：
>`ctrl+a`    

#### 4. 都_谁_在用？####
Markdown的使用者：

- GitHub
- 简书
- Stack Overflow
- Apollo
- Moodle
- Reddit
- 等等

#### 5. 感觉有意思？趁热打铁，推荐几个_工具_。 ####
Chrome下的stackedit插件可以离线使用，很爽。也不用担心平台受限。    
Windowns下的MarkdownPad也用过，不过免费版的效果不是很好。    
Mac下的Mou是国人贡献的，口碑很好。    
Linux下的ReText不错。    
在线的dillinger.io算是评价最好的了，可是不能离线使用。     


****   
**注意**：不同的Markdown解释器或工具对相应语法的解释效果不尽相同，具体可参见工具的使用说明。但是已经有人（包括GitHub和Reddit工作人员等）开始组织将Markdown进行标准化了，可以参见[standardmarkdown.com](http://standardmarkdown.com/)。
****

### 其它： ###
列表的使用(非traditonal markdown)：

用`|`表示表格纵向边界，表头和表内容用`-`隔开，并可用`：`进行对齐设置，两边都有`：`则表示居中，若不加`：`则默认左对齐。

|开源项目                              |链接                                |
|:------------------------------------:|------------------------------------|
|MarkDown                              |[https://github.com/younghz/Markdown](https://github.com/younghz/Markdown "Markdown")|
|moos-young                            |[https://github.com/younghz/moos-young](https://github.com/younghz/moos-young "tianchi")|
