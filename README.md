# Personal-collection
【个人收藏】Personal collection

# 常用函数收集

| function                      | description                             |
|:----------------------------- |:----------------------------------------|
| locationReplace.js            | url覆盖
| compareVersion.js             | 比较版本号
| params2url.js                 | json参数转换url拼接
| getUrlParam.js                | 获取hash或query的参数
| isMobileNumber.js             | 判断运营商号码
| isIphonex.js                  | 判断iphonex
| SaferHTML.js                  | 安全模板
| cutstr.js                     | 字符串长度截取    |
| replaceAll.js                 | 替换全部      |
| trim.js                       | 清除空格      |
| startWith.js                  | 判断是否以某个字符串开头      |
| endWith.js                    | 判断是否以某个字符串结束      |
| HtmlEncode.js                 | 转义html标签      |
| dateFormat.js                 | 时间日期格式转换      |
| timeFormat.js                 | 时间个性化输出功能      |
| isDigit.js                    | 判断是否为数字类型      |
| setCookie.js                  | 设置cookie值      |
| getCookie.js                  | 获取cookie值      |
| addFavorite.js                | 加入收藏夹      |
| setHomepage.js                | 设为首页      |
| backTop.js                    | 返回顶部的通用方法      |
| scrollToTop.js                | 返回顶部的通用方法v2      |
| openWindow.js                 | 打开一个窗体通用方法      |
| loadStyle.js                  | 加载样式文件      |
| evalscript.js                 | 返回脚本内容      |
| stripscript.js                | 清除脚本内容      |
| appendscript.js               | 动态加载脚本文件      |
| addEventSamp.js               | 跨浏览器绑定事件      |
| delEvt.js                     | 跨浏览器删除事件      |
| ElementOn.js                  | 为元素添加on方法      |
| ElementTrigger.js             | 为元素添加trigger方法      |
| getUrlState.js                | 检验URL链接是否有效      |
| isURL.js                      | 判断是否为网址      |
| removeUrlPrefix.js            | 去掉url前缀      |
| getGet.js                     | 获得URL中GET参数值      |
| formatCss.js                  | 格式化CSS样式代码      |
| compressCss.js                | 压缩CSS样式代码      |
| currentPageUrl.js             | 获取当前路径      |
| isMobile.js                   | 判断是否移动设备      |
| isMobileUserAgent.js          | 判断是否是移动设备访问      |
| isAppleMobileDevice.js        | 判断是否苹果移动设备访问      |
| isAndroidMobileDevice.js      | 判断是否安卓移动设备访问      |
| isTouchScreen.js              | 判断是否Touch屏幕      |
| isViewportOpen.js             | 判断是否打开视窗      |
| isMouseOut.js                 | 判断鼠标是否移出事件      |
| getInitZoom.js                | 获取移动设备初始化大小      |
| getZoom.js                    | 获取移动设备最大化大小      |
| getScreenWidth.js             | 获取移动设备屏幕宽度      |
| getPageHeight.js              | 获取页面高度      |
| getPageViewHeight.js          | 获取页面可视高度      |
| getPageWidth.js               | 获取页面宽度      |
| getViewSize.js                | 获取窗体可见范围的宽与高      |
| getPageViewWidth.js           | 获取页面可视宽度      |
| getPageScrollLeft.js          | 获取页面scrollLeft      |
| getPageScrollTop.js           | 获取页面scrollTop      |
| getScrollXY.js                | 获取网页被卷去的位置      |
| resize.js                     | resize的操作      |
| uniqueId.js                   | 随机数时间戳      |
| chgCase.js                    | 全角半角转换      |
| toDBC.js                      | 半角转换为全角函数      |
| toCDB.js                      | 全角转换为半角函数      |
| checkKey.js                   | 确认是否是键盘有效输入值      |
| offsetX.js                    | 解决offsetX兼容性问题      |
| allURL.js                     | 提取页面代码中所有网址      |
| setSort.js                    | 按字母排序，对每行进行数组排序      |
| transform.js                  | 金额大写转换函数      |
| base64_decode.js              | 实现base64解码      |
| utf8_decode.js                | 实现utf8解码      |

# 常用正则表达式收集

```
//正整数
/^[0-9]*[1-9][0-9]*$/;
//负整数
/^-[0-9]*[1-9][0-9]*$/;
//正浮点数
/^(([0-9]+\.[0-9]*[1-9][0-9]*)|([0-9]*[1-9][0-9]*\.[0-9]+)|([0-9]*[1-9][0-9]*))$/;   
//负浮点数
/^(-(([0-9]+\.[0-9]*[1-9][0-9]*)|([0-9]*[1-9][0-9]*\.[0-9]+)|([0-9]*[1-9][0-9]*)))$/;  
//浮点数
/^(-?\d+)(\.\d+)?$/;
//email地址
/^[\w-]+(\.[\w-]+)*@[\w-]+(\.[\w-]+)+$/;
//url地址
/^[a-zA-z]+://(\w+(-\w+)*)(\.(\w+(-\w+)*))*(\?\S*)?$/;
或：^http:\/\/[A-Za-z0-9]+\.[A-Za-z0-9]+[\/=\?%\-&_~`@[\]\':+!]*([^<>\"\"])*$ 
//年/月/日（年-月-日、年.月.日）
/^(19|20)\d\d[- /.](0[1-9]|1[012])[- /.](0[1-9]|[12][0-9]|3[01])$/;
//匹配中文字符
/[\u4e00-\u9fa5]/;
//匹配帐号是否合法(字母开头，允许5-10字节，允许字母数字下划线)
/^[a-zA-Z][a-zA-Z0-9_]{4,9}$/;
//匹配空白行的正则表达式
/\n\s*\r/;
//匹配中国邮政编码
/[1-9]\d{5}(?!\d)/;
//匹配身份证
/\d{15}|\d{18}/;
//匹配国内电话号码
/(\d{3}-|\d{4}-)?(\d{8}|\d{7})?/;
//匹配IP地址
/((2[0-4]\d|25[0-5]|[01]?\d\d?)\.){3}(2[0-4]\d|25[0-5]|[01]?\d\d?)/;
//匹配首尾空白字符的正则表达式
/^\s*|\s*$/;
//匹配HTML标记的正则表达式
< (\S*?)[^>]*>.*?|< .*? />;
//sql 语句
^(select|drop|delete|create|update|insert).*$
//提取信息中的网络链接
(h|H)(r|R)(e|E)(f|F) *= *('|")?(\w|\\|\/|\.)+('|"| *|>)? 
//提取信息中的邮件地址
\w+([-+.]\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)* 
//提取信息中的图片链接
(s|S)(r|R)(c|C) *= *('|")?(\w|\\|\/|\.)+('|"| *|>)? 
//提取信息中的 IP 地址
(\d+)\.(\d+)\.(\d+)\.(\d+)
//取信息中的中国手机号码
(86)*0*13\d{9} 
//提取信息中的中国邮政编码
[1-9]{1}(\d+){5} 
//提取信息中的浮点数（即小数）
(-?\d*)\.?\d+ 
//提取信息中的任何数字
(-?\d*)(\.\d+)?
//电话区号
^0\d{2,3}$
//腾讯 QQ 号
^[1-9]*[1-9][0-9]*$ 
//帐号（字母开头，允许 5-16 字节，允许字母数字下划线）
^[a-zA-Z][a-zA-Z0-9_]{4,15}$ 
//中文、英文、数字及下划线
^[\u4e00-\u9fa5_a-zA-Z0-9]+$
```


<br/>
<p align="center">
<img src="https://i.imgur.com/bYwl7Vf.png" alt="Learn Regex">
</p><br/>

## 什么是正则表达式 ？

> 正则表达式是一种被用于从文本中检索符合某些特定模式的文本。

正则表达式是从左到右来匹配一个字符串的。"Regular Expression" 这个词太长了，我们通常使用它的缩写 "regex" 或者 "regexp"。
正则表达式可以被用来替换字符串中的文本、验证表单、基于模式匹配从一个字符串中提取字符串等等。
<br />

想象一下，您正在编写应用程序，并且您希望在用户选择用户名时设置规则。我们希望用户名可以包含字母，数字，下划线和连字符。
为了让它看起来不丑，我们还想限制用户名中的字符数量。我们可以使用以下正则表达式来验证用户名:

<p align="center">
<img src="https://i.imgur.com/UrDb9qc.png" alt="Regular expression">
</p>

上面这个正则表达式可以匹配 `john_doe`，`jo-hn\_doe` 和 `john12\_as`。但是它不能匹配 `Jo`，因为该字符串里面包含了大写字符，并且它太短了。

## 目录

- [基本匹配](#1-基本匹配)
- [元字符](#2-元字符)
  - [英文句号](#21-英文句号)
  - [字符集](#22-字符集)
    - [否定字符集](#221-否定字符集)
  - [重复](#23-重复)
    - [星号](#231-星号)
    - [加号](#232-加号)
    - [问号](#233-问号)
  - [花括号](#24-花括号)
  - [字符组](#25-字符组)
  - [分支结构](#26-分支结构)
  - [转义特殊字符](#27-转义特殊字符)
  - [定位符](#28-定位符)
    - [插入符号](#281-插入符号)
    - [美元符号](#282-美元符号)
- [简写字符集](#3-简写字符集)
- [断言](#4-断言)
  - [正向先行断言](#41-正向先行断言)
  - [负向先行断言](#42-负向先行断言)
  - [正向后行断言](#43-正向后行断言)
  - [负向后行断言](#44-负向后行断言)
- [标记](#5-标记)
  - [不区分大小写](#51-不区分大小写)
  - [全局搜索](#52-全局搜索)
  - [多行匹配](#53-多行匹配)
- [常用正则表达式](#常用正则表达式)

## 1. 基本匹配

正则表达式只是我们用于在文本中检索字母和数字的模式。例如正则表达式 `cat`，表示: 字母 `c` 后面跟着一个字母 `a`，再后面跟着一个字母 `t`。

<pre>
"cat" => The <a href="#learn-regex"><strong>cat</strong></a> sat on the mat
</pre>

正则表达式 `123` 会匹配字符串 "123"。通过将正则表达式中的每个字符逐个与要匹配的字符串中的每个字符进行比较，来完成正则匹配。
正则表达式通常区分大小写，因此正则表达式 `Cat` 与字符串 "cat" 不匹配。

<pre>
"Cat" => The cat sat on the <a href="#learn-regex"><strong>Cat</strong></a>
</pre>

## 2. 元字符

元字符是正则表达式的基本组成元素。元字符在这里跟它通常表达的意思不一样，而是以某种特殊的含义去解释。有些元字符写在方括号内的时候有特殊含义。
元字符如下:

|元字符|描述|
|:----:|----|
|.|匹配除换行符以外的任意字符。|
|[ ]|字符类，匹配方括号中包含的任意字符。|
|[^ ]|否定字符类。匹配方括号中不包含的任意字符|
|*|匹配前面的子表达式零次或多次|
|+|匹配前面的子表达式一次或多次|
|?|匹配前面的子表达式零次或一次，或指明一个非贪婪限定符。|
|{n,m}|花括号，匹配前面字符至少 n 次，但是不超过 m 次。|
|(xyz)|字符组，按照确切的顺序匹配字符xyz。|
|&#124;|分支结构，匹配符号之前的字符或后面的字符。|
|&#92;|转义符，它可以还原元字符原来的含义，允许你匹配保留字符 <code>[ ] ( ) { } . * + ? ^ $ \ &#124;</code>|
|^|匹配行的开始|
|$|匹配行的结束|

## 2.1 英文句号

英文句号 `.` 是元字符的最简单的例子。元字符 `.` 可以匹配任意单个字符。它不会匹配换行符和新行的字符。例如正则表达式 `.ar`，表示: 任意字符后面跟着一个字母 `a`，
再后面跟着一个字母 `r`。

<pre>
".ar" => The <a href="#learn-regex"><strong>car</strong></a> <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>

## 2.2 字符集

字符集也称为字符类。方括号被用于指定字符集。使用字符集内的连字符来指定字符范围。方括号内的字符范围的顺序并不重要。
例如正则表达式 `[Tt]he`，表示: 大写 `T` 或小写 `t` ，后跟字母 `h`，再后跟字母 `e`。

<pre>
"[Tt]he" => <a href="#learn-regex"><strong>The</strong></a> car parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>

然而，字符集中的英文句号表示它字面的含义。正则表达式 `ar[.]`，表示小写字母 `a`，后面跟着一个字母 `r`，再后面跟着一个英文句号 `.` 字符。

<pre>
"ar[.]" => A garage is a good place to park a c<a href="#learn-regex"><strong>ar.</strong></a>
</pre>

### 2.2.1 否定字符集

一般来说插入字符 `^` 表示一个字符串的开始，但是当它在方括号内出现时，它会取消字符集。例如正则表达式 `[^c]ar`，表示: 除了字母 `c` 以外的任意字符，后面跟着字符 `a`，
再后面跟着一个字母 `r`。

<pre>
"[^c]ar" => The car <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>

## 2.3 重复

以下元字符 `+`，`*` 或 `?` 用于指定子模式可以出现多少次。这些元字符在不同情况下的作用不同。

### 2.3.1 星号

该符号 `*` 表示匹配上一个匹配规则的零次或多次。正则表达式 `a*` 表示小写字母 `a` 可以重复零次或者多次。但是它如果出现在字符集或者字符类之后，它表示整个字符集的重复。
例如正则表达式 `[a-z]*`，表示: 一行中可以包含任意数量的小写字母。

<pre>
"[a-z]*" => T<a href="#learn-regex"><strong>he</strong></a> <a href="#learn-regex"><strong>car</strong></a> <a href="#learn-regex"><strong>parked</strong></a> <a href="#learn-regex"><strong>in</strong></a> <a href="#learn-regex"><strong>the</strong></a> <a href="#learn-regex"><strong>garage</strong></a> #21.
</pre>

该 `*` 符号可以与元符号 `.` 用在一起，用来匹配任意字符串 `.*`。该 `*` 符号可以与空格符 `\s` 一起使用，用来匹配一串空格字符。
例如正则表达式 `\s*cat\s*`，表示: 零个或多个空格，后面跟小写字母 `c`，再后面跟小写字母 `a`，再再后面跟小写字母 `t`，后面再跟零个或多个空格。

<pre>
"\s*cat\s*" => The fat<a href="#learn-regex"><strong> cat </strong></a>sat on the <a href="#learn-regex"><strong>cat</strong></a>.
</pre>

### 2.3.2 加号

该符号 `+` 匹配上一个字符的一次或多次。例如正则表达式 `c.+t`，表示: 一个小写字母 `c`，后跟任意数量的字符，后跟小写字母 `t`。

<pre>
"c.+t" => The fat <a href="#learn-regex"><strong>cat sat on the mat</strong></a>.
</pre>

### 2.3.3 问号

在正则表达式中，元字符 `?` 用来表示前一个字符是可选的。该符号匹配前一个字符的零次或一次。
例如正则表达式 `[T]?he`，表示: 可选的大写字母 `T`，后面跟小写字母 `h`，后跟小写字母 `e`。

<pre>
"[T]he" => <a href="#learn-regex"><strong>The</strong></a> car is parked in the garage.
</pre>
<pre>
"[T]?he" => <a href="#learn-regex"><strong>The</strong></a> car is parked in t<a href="#learn-regex"><strong>he</strong></a> garage.
</pre>

## 2.4 花括号

在正则表达式中花括号(也被称为量词 ?)用于指定字符或一组字符可以重复的次数。例如正则表达式 `[0-9]{2,3}`，表示: 匹配至少2位数字但不超过3位(0到9范围内的字符)。

<pre>
"[0-9]{2,3}" => The number was 9.<a href="#learn-regex"><strong>999</strong></a>7 but we rounded it off to <a href="#learn-regex"><strong>10</strong></a>.0.
</pre>

我们可以省略第二个数字。例如正则表达式 `[0-9]{2,}`，表示: 匹配2个或更多个数字。如果我们也删除逗号，则正则表达式 `[0-9]{2}`，表示: 匹配正好为2位数的数字。

<pre>
"[0-9]{2,}" => The number was 9.<a href="#learn-regex"><strong>9997</strong></a> but we rounded it off to <a href="#learn-regex"><strong>10</strong></a>.0.
</pre>

<pre>
"[0-9]{2}" => The number was 9.<a href="#learn-regex"><strong>99</strong></a><a href="#learn-regex"><strong>97</strong></a> but we rounded it off to <a href="#learn-regex"><strong>10</strong></a>.0.
</pre>

## 2.5 字符组

字符组是一组写在圆括号内的子模式 `(...)`。正如我们在正则表达式中讨论的那样，如果我们把一个量词放在一个字符之后，它会重复前一个字符。
但是，如果我们把量词放在一个字符组之后，它会重复整个字符组。
例如正则表达式 `(ab)*` 表示匹配零个或多个的字符串 "ab"。我们还可以在字符组中使用元字符 `|`。例如正则表达式 `(c|g|p)ar`，表示: 小写字母 `c`、`g` 或 `p` 后面跟字母 `a`，后跟字母 `r`。

<pre>
"(c|g|p)ar" => The <a href="#learn-regex"><strong>car</strong></a> is <a href="#learn-regex"><strong>par</strong></a>ked in the <a href="#learn-regex"><strong>gar</strong></a>age.
</pre>

## 2.6 分支结构

在正则表达式中垂直条 `|` 用来定义分支结构，分支结构就像多个表达式之间的条件。现在你可能认为这个字符集和分支机构的工作方式一样。
但是字符集和分支结构巨大的区别是字符集只在字符级别上有作用，然而分支结构在表达式级别上依然可以使用。
例如正则表达式 `(T|t)he|car`，表示: 大写字母 `T` 或小写字母 `t`，后面跟小写字母 `h`，后跟小写字母 `e` 或小写字母 `c`，后跟小写字母 `a`，后跟小写字母 `r`。

<pre>
"(T|t)he|car" => <a href="#learn-regex"><strong>The</strong></a> <a href="#learn-regex"><strong>car</strong></a> is parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>

## 2.7 转义特殊字符

正则表达式中使用反斜杠 `\` 来转义下一个字符。这将允许你使用保留字符来作为匹配字符 `{ } [ ] / \ + * . $ ^ | ?`。在特殊字符前面加 `\`，就可以使用它来做匹配字符。
例如正则表达式 `.` 是用来匹配除了换行符以外的任意字符。现在要在输入字符串中匹配 `.` 字符，正则表达式 `(f|c|m)at\.?`，表示: 小写字母 `f`、`c` 或者 `m` 后跟小写字母 `a`，后跟小写字母 `t`，后跟可选的 `.` 字符。

<pre>
"(f|c|m)at\.?" => The <a href="#learn-regex"><strong>fat</strong></a> <a href="#learn-regex"><strong>cat</strong></a> sat on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>

## 2.8 定位符

在正则表达式中，为了检查匹配符号是否是起始符号或结尾符号，我们使用定位符。
定位符有两种类型: 第一种类型是 `^` 检查匹配字符是否是起始字符，第二种类型是 `$`，它检查匹配字符是否是输入字符串的最后一个字符。

### 2.8.1 插入符号

插入符号 `^` 符号用于检查匹配字符是否是输入字符串的第一个字符。如果我们使用正则表达式 `^a` (如果a是起始符号)匹配字符串 `abc`，它会匹配到 `a`。
但是如果我们使用正则表达式 `^b`，它是匹配不到任何东西的，因为在字符串 `abc` 中 "b" 不是起始字符。
让我们来看看另一个正则表达式 `^(T|t)he`，这表示: 大写字母 `T` 或小写字母 `t` 是输入字符串的起始符号，后面跟着小写字母 `h`，后跟小写字母 `e`。

<pre>
"(T|t)he" => <a href="#learn-regex"><strong>The</strong></a> car is parked in <a href="#learn-regex"><strong>the</strong></a> garage.
</pre>

<pre>
"^(T|t)he" => <a href="#learn-regex"><strong>The</strong></a> car is parked in the garage.
</pre>

### 2.8.2 美元符号

美元 `$` 符号用于检查匹配字符是否是输入字符串的最后一个字符。例如正则表达式 `(at\.)$`，表示: 小写字母 `a`，后跟小写字母 `t`，后跟一个 `.` 字符，且这个匹配器必须是字符串的结尾。

<pre>
"(at\.)" => The fat c<a href="#learn-regex"><strong>at.</strong></a> s<a href="#learn-regex"><strong>at.</strong></a> on the m<a href="#learn-regex"><strong>at.</strong></a>
</pre>

<pre>
"(at\.)$" => The fat cat sat on the m<a href="#learn-regex"><strong>at.</strong></a>
</pre>

## 3. 简写字符集

正则表达式为常用的字符集和常用的正则表达式提供了简写。简写字符集如下:

|简写|描述|
|:----:|----|
|.|匹配除换行符以外的任意字符|
|\w|匹配所有字母和数字的字符: `[a-zA-Z0-9_]`|
|\W|匹配非字母和数字的字符: `[^\w]`|
|\d|匹配数字: `[0-9]`|
|\D|匹配非数字: `[^\d]`|
|\s|匹配空格符: `[\t\n\f\r\p{Z}]`|
|\S|匹配非空格符: `[^\s]`|

## 4. 断言

后行断言和先行断言有时候被称为断言，它们是特殊类型的 ***非捕获组*** (用于匹配模式，但不包括在匹配列表中)。当我们在一种特定模式之前或者之后有这种模式时，会优先使用断言。
例如我们想获取输入字符串 `$4.44 and $10.88` 中带有前缀 `$` 的所有数字。我们可以使用这个正则表达式 `(?<=\$)[0-9\.]*`，表示: 获取包含 `.` 字符且前缀为 `$` 的所有数字。
以下是正则表达式中使用的断言:

|符号|描述|
|:----:|----|
|?=|正向先行断言|
|?!|负向先行断言|
|?<=|正向后行断言|
|?<!|负向后行断言|

### 4.1 正向先行断言

正向先行断言认为第一部分的表达式必须是先行断言表达式。返回的匹配结果仅包含与第一部分表达式匹配的文本。
要在一个括号内定义一个正向先行断言，在括号中问号和等号是这样使用的 `(?=...)`。先行断言表达式写在括号中的等号后面。
例如正则表达式 `(T|t)he(?=\sfat)`，表示: 匹配大写字母 `T` 或小写字母 `t`，后面跟字母 `h`，后跟字母 `e`。
在括号中，我们定义了正向先行断言，它会引导正则表达式引擎匹配 `The` 或 `the` 后面跟着 `fat`。

<pre>
"(T|t)he(?=\sfat)" => <a href="#learn-regex"><strong>The</strong></a> fat cat sat on the mat.
</pre>

### 4.2 负向先行断言

当我们需要从输入字符串中获取不匹配表达式的内容时，使用负向先行断言。负向先行断言的定义跟我们定义的正向先行断言一样，
唯一的区别是不是等号 `=`，我们使用否定符号 `!`，例如 `(?!...)`。
我们来看看下面的正则表达式 `(T|t)he(?!\sfat)`，表示: 从输入字符串中获取全部 `The` 或者 `the` 且不匹配 `fat` 前面加上一个空格字符。

<pre>
"(T|t)he(?!\sfat)" => The fat cat sat on <a href="#learn-regex"><strong>the</strong></a> mat.
</pre>

### 4.3 正向后行断言

正向后行断言是用于获取在特定模式之前的所有匹配内容。正向后行断言表示为 `(?<=...)`。例如正则表达式 `(?<=(T|t)he\s)(fat|mat)`，表示: 从输入字符串中获取在单词 `The` 或 `the` 之后的所有 `fat` 和 `mat` 单词。

<pre>
"(?<=(T|t)he\s)(fat|mat)" => The <a href="#learn-regex"><strong>fat</strong></a> cat sat on the <a href="#learn-regex"><strong>mat</strong></a>.
</pre>

### 4.4 负向后行断言

负向后行断言是用于获取不在特定模式之前的所有匹配的内容。负向后行断言表示为 `(?<!...)`。例如正则表达式 `(?<!(T|t)he\s)(cat)`，表示: 在输入字符中获取所有不在 `The` 或 `the` 之后的所有单词 `cat`。

<pre>
"(?&lt;!(T|t)he\s)(cat)" => The cat sat on <a href="#learn-regex"><strong>cat</strong></a>.
</pre>

## 5. 标记

标记也称为修饰符，因为它会修改正则表达式的输出。这些标志可以以任意顺序或组合使用，并且是正则表达式的一部分。

|标记|描述|
|:----:|----|
|i|不区分大小写: 将匹配设置为不区分大小写。|
|g|全局搜索: 搜索整个输入字符串中的所有匹配。|
|m|多行匹配: 会匹配输入字符串每一行。|

### 5.1 不区分大小写

`i` 修饰符用于执行不区分大小写匹配。例如正则表达式 `/The/gi`，表示: 大写字母 `T`，后跟小写字母 `h`，后跟字母 `e`。
但是在正则匹配结束时 `i` 标记会告诉正则表达式引擎忽略这种情况。正如你所看到的，我们还使用了 `g` 标记，因为我们要在整个输入字符串中搜索匹配。

<pre>
"The" => <a href="#learn-regex"><strong>The</strong></a> fat cat sat on the mat.
</pre>

<pre>
"/The/gi" => <a href="#learn-regex"><strong>The</strong></a> fat cat sat on <a href="#learn-regex"><strong>the</strong></a> mat.
</pre>

### 5.2 全局搜索

`g` 修饰符用于执行全局匹配 (会查找所有匹配，不会在查找到第一个匹配时就停止)。
例如正则表达式 `/.(at)/g`，表示: 除换行符之外的任意字符，后跟小写字母 `a`，后跟小写字母 `t`。
因为我们在正则表达式的末尾使用了 `g` 标记，它会从整个输入字符串中找到每个匹配项。

<pre>
".(at)" => The <a href="#learn-regex"><strong>fat</strong></a> cat sat on the mat.
</pre>

<pre>
"/.(at)/g" => The <a href="#learn-regex"><strong>fat</strong></a> <a href="#learn-regex"><strong>cat</strong></a> <a href="#learn-regex"><strong>sat</strong></a> on the <a href="#learn-regex"><strong>mat</strong></a>.
</pre>

### 5.3 多行匹配

`m` 修饰符被用来执行多行的匹配。正如我们前面讨论过的 `(^, $)`，使用定位符来检查匹配字符是输入字符串开始或者结束。但是我们希望每一行都使用定位符，所以我们就使用 `m` 修饰符。
例如正则表达式 `/at(.)?$/gm`，表示: 小写字母 `a`，后跟小写字母 `t`，匹配除了换行符以外任意字符零次或一次。而且因为 `m` 标记，现在正则表达式引擎匹配字符串中每一行的末尾。

<pre>
"/.at(.)?$/" => The fat
                cat sat
                on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>

<pre>
"/.at(.)?$/gm" => The <a href="#learn-regex"><strong>fat</strong></a>
                  cat <a href="#learn-regex"><strong>sat</strong></a>
                  on the <a href="#learn-regex"><strong>mat.</strong></a>
</pre>

## 常用正则表达式

* **正整数**: `^\d+$`
* **负整数**: `^-\d+$`
* **电话号码**: `^+?[\d\s]{3,}$`
* **电话代码**: `^+?[\d\s]+(?[\d\s]{10,}$`
* **整数**: `^-?\d+$`
* **用户名**: `^[\w\d_.]{4,16}$`
* **字母数字字符**: `^[a-zA-Z0-9]*$`
* **带空格的字母数字字符**: `^[a-zA-Z0-9 ]*$`
* **密码**: `^(?=^.{6,}$)((?=.*[A-Za-z0-9])(?=.*[A-Z])(?=.*[a-z]))^.*$`
* **电子邮件**: `^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,4})*$`
* **IPv4 地址**: `^((?:(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)\.){3}(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?))*$`
* **小写字母**: `^([a-z])*$`
* **大写字母**: `^([A-Z])*$`
* **网址**: `^(((http|https|ftp):\/\/)?([[a-zA-Z0-9]\-\.])+(\.)([[a-zA-Z0-9]]){2,4}([[a-zA-Z0-9]\/+=%&_\.~?\-]*))*$`
* **VISA 信用卡号码**: `^(4[0-9]{12}(?:[0-9]{3})?)*$`
* **日期 (MM/DD/YYYY)**: `^(0?[1-9]|1[012])[- /.](0?[1-9]|[12][0-9]|3[01])[- /.](19|20)?[0-9]{2}$`
* **日期 (YYYY/MM/DD)**: `^(19|20)?[0-9]{2}[- /.](0?[1-9]|1[012])[- /.](0?[1-9]|[12][0-9]|3[01])$`
* **万事达信用卡号码**: `^(5[1-5][0-9]{14})*$`

## Contribution

* Report issues
* Open pull request with improvements
* Spread the word 

<div align="center">
  <p><img src="http://openlogos.org/logos/sage.jpg" /></p>
  <img src="https://img.shields.io/badge/branch-master-brightgreen.svg">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg">
  <img src="https://jaywcjlove.github.io/sb/lang/chinese.svg">
</div>

## 目录

- [邮箱](#邮箱)
- [电话](#电话)
- [域名](#域名)
- [IP](#ip)
- [帐号校验](#帐号校验)
- [字符校验](#字符校验)
  - [汉字](#汉字)
  - [英文和数字](#英文和数字)
  - [长度为3-20的所有字符](#长度为3-20的所有字符)
  - [英文字符](#由英文字符)
    - [由26个英文字母组成的字符串](#由26个英文字母组成的字符串)
    - [由26个大写英文字母组成的字符串](#由26个大写英文字母组成的字符串)
    - [由26个小写英文字母组成的字符串](#由26个小写英文字母组成的字符串)
    - [由数字和26个英文字母组成的字符串](#由数字和26个英文字母组成的字符串)
    - [由数字、26个英文字母或者下划线组成的字符串](#由数字26个英文字母或者下划线组成的字符串)
  - [中文、英文、数字包括下划线](#中文英文数字包括下划线)
  - [中文、英文、数字但不包括下划线等符号](#中文英文数字但不包括下划线等符号)
  - [禁止输入含有^%&',;=?$\"等字符](#禁止输入含有等字符)
  - [禁止输入含有~的字符](#禁止输入含有的字符)
- [数字正则](#数字正则)
  - [整数](#整数)
    - [正整数](#正整数)
    - [负整数](#负整数)
    - [非负整数](#非负整数)
    - [非正整数](#非正整数)
  - [浮点数](#浮点数)
    - [正浮点数](#正浮点数)
    - [负浮点数](#负浮点数)
    - [非负浮点数](#非负浮点数)
    - [非正浮点数](#非正浮点数)

## 邮箱

`gaozihang-001@gmail.com` 只允许英文字母、数字、下划线、英文句号、以及中划线组成

```regex
^[a-zA-Z0-9_-]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$
```

![email](images/email.png)

`高子航001Abc@bowbee.com.cn` 名称允许汉字、字母、数字，域名只允许英文域名

```regex
^[A-Za-z0-9\u4e00-\u9fa5]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$
```

![email](images/email2.png)

## 电话

`13012345678` 手机号

```regex
^1(3|4|5|6|7|8|9)\d{9}$
```

![phone](images/phone.png)

`XXX-XXXXXXX` `XXXX-XXXXXXXX` 固定电话

```regex
(\(\d{3,4}\)|\d{3,4}-|\s)?\d{8}
```

![email](images/phone2.png)

## 域名

`https://google.com/`

```regex
^((http:\/\/)|(https:\/\/))?([a-zA-Z0-9]([a-zA-Z0-9\-]{0,61}[a-zA-Z0-9])?\.)+[a-zA-Z]{2,6}(\/)
```

![domain-name](images/domain-name.png)

## IP

`127.0.0.1`

```regex
((?:(?:25[0-5]|2[0-4]\d|[01]?\d?\d)\.){3}(?:25[0-5]|2[0-4]\d|[01]?\d?\d))
```

![ip](images/ip.png)

## 帐号校验

`gaozihang_001` 字母开头，允许5-16字节，允许字母数字下划线

```regex
^[a-zA-Z][a-zA-Z0-9_]{4,15}$
```

![user](images/userid.png)

## 字符校验

### 汉字

`高子航`

```regex
^[\u4e00-\u9fa5]{0,}$
```

![chinese](images/chineses.png)

### 英文和数字

```regex
^[A-Za-z0-9]+$
```

![char](images/char1.png)

### 长度为3-20的所有字符

```regex
^.{3,20}$
```

![char](images/char2.png)

### 英文字符

#### 由26个英文字母组成的字符串

```regex
^[A-Za-z]+$
```

![char](images/char3.png)

#### 由26个大写英文字母组成的字符串

```regex
^[A-Z]+$
```

![char](images/char4.png)

#### 由26个小写英文字母组成的字符串

```regex
^[a-z]+$
```

![char](images/char5.png)

#### 由数字和26个英文字母组成的字符串

```regex
^[A-Za-z0-9]+$
```

![char](images/char6.png)

#### 由数字、26个英文字母或者下划线组成的字符串 

```regex
^\w+$
```

![char](images/char7.png)

### 中文、英文、数字包括下划线

```regex
^[\u4E00-\u9FA5A-Za-z0-9_]+$
```

![char](images/char8.png)

### 中文、英文、数字但不包括下划线等符号

```regex
^[\u4E00-\u9FA5A-Za-z0-9]+$
```

![char](images/char9.png)

### 禁止输入含有%&',;=?$\"等字符

```regex
[^%&',;=?$\x22]+
```

![char](images/char10.png)

### 禁止输入含有~的字符

```regex
[^~\x22]+
```

![char](images/char11.png)

## 数字正则

### 整数

```regex
^-?[1-9]\d*$
```

![num](images/num1.png)

#### 正整数

```regex
^[1-9]\d*$
```

![num](images/num2.png)

#### 负整数

```regex
^-[1-9]\d*$
```

![num](images/num3.png)

#### 非负整数

```regex
^[1-9]\d*|0$
```

![num](images/num4.png)

#### 非正整数

```regex
^-[1-9]\d*|0$
```

![num](images/num5.png)

### 浮点数

```regex
^-?([1-9]\d*\.\d*|0\.\d*[1-9]\d*|0?\.0+|0)$
```

![num](images/num6.png)

#### 正浮点数

```regex
^[1-9]\d*\.\d*|0\.\d*[1-9]\d*$
```

![num](images/num7.png)

#### 负浮点数

```regex
^-([1-9]\d*\.\d*|0\.\d*[1-9]\d*)$
```

![num](images/num8.png)

#### 非负浮点数

```regex
^[1-9]\d*\.\d*|0\.\d*[1-9]\d*|0?\.0+|0$
```

![num](images/num9.png)

#### 非正浮点数

```regex
^(-([1-9]\d*\.\d*|0\.\d*[1-9]\d*))|0?\.0+|0$
```

![num](images/num10.png)

## License

MIT License. See the [LICENSE](LICENSE) file.

**[⬆ top](#目录)**
