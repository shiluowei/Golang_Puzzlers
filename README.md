# Golang_Puzzlers

我在极客时间开设的专栏《Go语言核心36讲》的配套项目，也可以称之为“Go语言谜题”项目。其中几乎包含了此专栏涉及到的所有代码。

这个专栏的地址[在这里](https://time.geekbang.org/column/intro/112?code=ti58hl0Fap2y5S-OE0G-O-2CiCtjLT94OxcNaBDzI6k%3D)。本项目中的代码携带的信息相对较少，往往需要配合专栏的内容去看。欢迎大家到“极客时间”订阅我的专栏。

欢迎广大的专栏读者和Go语言爱好者们查阅和下载！如果此项目对你有所裨益，还请轻点鼠标、`Star`一下。谢谢！

## 项目结构说明

项目中会有很多像`article3`这样的代码包。这种代码包下面还会有像`q0`或`q2`这样的子代码包。对于这些代码包的层次和命名是有一套潜在的规则的。如下：

1. `article3`是第三篇正文的专属代码包。其他名称相似的代码包含义可类推。
2. 在每个文章代码包中，都可能会有`q0`、`q1`、`q2`、`q3`这类的子代码包。
3. 此专栏的主体文章是有固定的结构的。它们一般被分为几个部分：
	- 主问题提出之前的部分，也被称为前导部分。
	- 主问题部分，是文章主体内容的切入点。
	- 扩展问题部分，是切入点的延伸和深入，一般由若干个扩展问题组成，比如：扩展问题1、扩展问题2，等等。
	- 总结部分，是对前面的阐述和问题的总结。
	- 思考题部分，由一到两个思考题组成。这部分的题目没有答案，仅供大家思考和讨论。
4. 以上述文章结构为基础，`q0`子包中会包含与前导部分对应的示例代码，`q1`子包中会包含与主问题部分对应的代码，而`q2`子包中会包含与扩展问题部分的扩展问题1对应的代码，以此类推。总结部分和思考题部分一般没有与之对应的代码包。

一般只有像`q0`、`q1`、`q2`这样的代码包下才会包含源码文件。若文章的某个部分存在对应的代码则至少会有一个源码文件，并且总会有一个命令源码文件作为示例的入口，也就是示例入口文件。每个示例入口文件都会以`demoX.go`为名，其中的`X`代表序号。所有的示例入口文件的序号都是唯一的，并且从第一个出现的示例入口文件开始以自然数的顺序确定序号。这样做可以统计示例的总数量。

欢迎大家与我一起学习Go语言。如果你怀疑或确定本项目的代码有错误，请通过专栏找到我，我们一起讨论。谢谢！

## 项目状态更新

- `2018-11-09`：此专栏在此时已更新到了`39`讲，早已超过了原本约定的`36`讲。不过这还没完，预计它最终会达到`50`讲，并且一直更新到12月初。之后，我仍然会对专栏的内容进行专项增补，比如：补充配图、添加思考题的答案，等等。这些增补也同样都会被及时地更新到专栏的在线版中。这些工作都做完了恐怕要到明年的春节了。所以，专栏的读者们，你们赚到了；）。
- `2018-11-11`：我发现我与专栏的读者们在交流方面并不是那么的顺畅。当然了，很大一部分是我个人的身体原因导致的。但无论如何，我在[BearyChat](https://bearychat.com)上开设了一个名叫`GoHackers`的团队，并把它作为我们的`GoHackers`社群的重要分支。在这个团队中，我专门为此专栏的读者们建立了一个私密的讨论组，供答疑和交流之用。如果大家感兴趣，可以先通过[这里](https://gohackers.bearychat.com/signup/2d533429591347db9810f3f106596270)申请加入到这个`GoHackers`团队。
- `2018-11-20`：此专栏的全部文章都已经写作完成。全专栏共计52篇文章，其中正文50篇（包含36+2个主题）。

