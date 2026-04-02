---
title: "问心 —— 我在ACM班的这四年"
abstract: "听父亲说，祖谱上我是“心”字辈。回望在ACM班度过的四年，以“问心”为题，自问自省。"
date: 2026-04-02
categories: [blogs]
---

## Welcome

进入大学初期的我是个不合格的小镇做题家。我除了眼前的课业，没有对未来的远见；“不合格”是因为我不会应试，刷题低效，大一的成绩一塌糊涂。我曾总结“大一在谋生存”，我没有计算机基础，甚至上大学前没怎么碰过电脑，大一花了大量时间在编程课上。我数学物理基础也弱，数学分析等等也是老大难，似乎一直在“拆东墙补西墙”。大一，尤其第一学期提高了我的抗挫能力：机考爆零，从emo自闭到平和接受，积极纠错补题；被ddl碾过，碾多了逐渐也跑得越来越快了；很多次竭尽全力依然无能为力，于是慢慢接受不可能完美的自己，我可以做不好，但要去试着做得更好一点。第二学期略好于第一学期，至少数据结构的作业都能在ddl前赶上了，也渐渐从大规模coding中能获得正反馈了。

我大学生活的重要转折点是大一暑假的编译。前期非常痛苦，但开发过程中因为一些契机好像就此开悟了。我其实偏离了主流的compilation flow实现，这给我带来了非常独特的开发体验。在遵照教程build llvm IR之后，我的codegen做得和大家不太一样。这种做法让我在写optimization之前在benchmark上有挺不错的performance，但在后续加optimization时暴露出大量问题。我后来反思发现我的做法相当于是在llvm IR之后又加了一层IR，而我在这层IR上破坏了SSA性质。这个试错、质疑主流做法、自我否定、反思的过程其实非常有意义（我的一条朋友圈评论区仍留存着我质疑mem2reg到appreciate mem2reg的有趣心路历程）。编译课让我能去design & build something，在这个过程中，我有很高的自由度去随心探索我在整个历程中遇到的兴趣点。我的学习态度在这门课之后有很多改变，从“这是课程任务，我需要完成”逐渐变成了“这听起来很好玩，好好玩玩！”

大二开始上正经系统课，阿磊老师上课讲得有些跳脱，记得有学长说觉得对system有基础认识，并且有一些工程经验的人听阿磊老师的课会收获很大。最初几节课听得云里雾里，后来就开始自己先啃课本补基础知识。听阿磊老师讲过好些漂亮的系统设计，有段时间每周的系统课都听得很开心，不是学了什么具体的知识点，更多是因为某些优雅的设计点感到兴奋。系统课的大作业更是对我胃口，系统一（architecture）的大作业选了Verilog实现简单的vector processor，这个任务比compiler的设计自由度更高了。以往的大作业基本是祖传的，多少可以参考学长们的架构设计，而这是全新的，完全由自己想要怎么做。启动成本很高：我们的目标ISA是RISCV的vector extension（RVV），那一学期零零散散啃了RVV的文档，锻炼了读文档的能力；也读了一些比较古早的paper。除去对参考资料研读、Verilog编程调试等等项目强相关的收获，我觉得这个课程项目给我带来更重要的精神收获：

> 学期中很“不自量力”地选择了挑战作业，没有可以参考的祖传代码，同行的同伴也越来越少，离ddl余下36小时，本以为勉强算是写完，却又发现一个设计上存在非常大的问题。很明确地认识到，必然是完不成了，但不后悔做这个高风险的选择。现阶段最让我感到不安的是这个作业中存在的大量不确定因子。没有具体的参考资料，我不知道我设计时做的每一个决定是否存在问题；之前没有人写过这项作业，我不知道我大致要花多少时间才能完成，甚至不知道我是否真的能完成这项任务。


## Links

You can include links like this: [My Homepage]({{ site.baseurl }}/) or external links like [GitHub](https://github.com).

## Images

Include images using standard markdown syntax:

![sample image]({{ site.baseurl }}/images/bio.jpg)

## Code

You can also include code blocks:

```python
print("Hello, World!")
```

## Lists

- Item one
- Item two
- Item three

---

*This is a sample post. Replace it with your own content!*
