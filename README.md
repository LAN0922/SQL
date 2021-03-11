# 《SQL基础教程》第2版读书笔记

## 前言

&emsp;&emsp;本书是畅销书[《SQL基础教程》第2版](sql基础教程（第2版）.pdf)，介绍了关系数据库以及用来操作关系数据库的SQL语言的使用方法。书中通过丰富的图示、大量示例程序和详实的操作步骤说明，让读者循序渐进地掌握SQL的基础知识和使用技巧，切实提高编程能力。每章结尾设置有练习题，帮助读者检验对各章内容的理解程度。另外，本书还将重要知识点总结为“法则”，方便读者随时查阅。第2版除了将示例程序更新为对应新版本的DB的SQL之外，还新增了一章，介绍如何从应用程序执行SQL。

&emsp;&emsp;这个项目记录了北京大学AFT协会对《SQL基础教程》第2版的学习笔记，同时也特别感谢Master_lisa为本书录制的[学习视频](https://www.bilibili.com/video/av62315714)

&emsp;&emsp;除了《SQL基础教程》第2版之外，我们也推荐其他一些学习资料：[《MySQL必知必会》](《MySQL必知必会》.pdf)，[W3school SQL教程](https://www.w3school.com.cn/sql/index.asp)，[哈佛CS50](https://b23.tv/KeJnxS)

>GitHub的markdown不再支持tex公式的解析显示，使用Chrome的同学可以安装[GitHub with MathJax](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima)添加MathJax的解析以对公式正常显示。

>如果需要直接阅读模式，可以移步至我们的github.io进行阅读：[《SQL基础教程》第2版读书笔记]()

## 目录

1. [绪论——搭建SQL的学习环境]()
    1. [PostgreSQL的安装和连接设置]()
    1. [通过PostgreSQL执行SQL语句]()
1. [数据库和SQL]()
    1. [数据库是什么]()
    1. [数据库的结构]()
    1. [SQL概要]()
    1. [表的创建]()
    1. [表的删除和更新]()
1. [查询基础]()
    1. [SELECT语句基础]()
    1. [算术运算符和比较运算符]()
    1. [逻辑运算符]()
1. [聚合排序]()
    1. [对表进行聚合查询]()
    1. [对表进行分组]()
    1. [为聚合结果指定条件]()
    1. [对查询结果进行排序]()
1. [数据更新]()
    1. [数据的插入（INSERT语句的使用方法）]()
    1. [数据的删除（DELETE语句的使用方法）]()
    1. [数据的更新（UPDATE语句的使用方法）]()
    1. [事务]()
1. [复杂查询]()
    1. [视图]()
    1. [子查询]()
    1. [关联子查询]()
1. [函数、谓词、CASE表达式]()
    1. [各种各样的函数]()
    1. [谓词]()
    1. [CASE表达式]()
1. [集合运算]()
    1. [表的加减法]()
    1. [联结（以列为单位对表进行联结）]()
1. [SQL高级处理]()
    1. [窗口函数]()
    1. [GROUPING运算符]()
1. [通过应用程序连接数据库]()
    1. [据库世界和应用程序世界的连接]()
    1. [Java基础知识]()
    1. [通过Java连接PostgreSQL]()

>持续更新中，欢迎贡献便于理解的优秀代码示例，推荐使用Python代码和Jupyter Notebook提交，并附上说明。

致谢
--------------------
我们分为两个类别的贡献者。
 - 负责人也就是对应的该章节案例维护者。
 - 贡献者对应于主要的案例开发者。

| 原书章节 | 对应案例  | 负责人 | 贡献者 |
| ------------ | ------------ | ------------ | ------------ |
| [第一章 绪论——搭建SQL的学习环境]() | [绪论——搭建SQL的学习环境](绪论——搭建SQL的学习环境/绪论——搭建SQL的学习环境.md) |  |  |
| [第二章 数据库和SQL]() | [数据库和SQL]() | | |
| [第三章 查询基础]() | [查询基础]() |  |  |
| [第四章 聚合排序]() | [聚合排序]() |  |  |
| [第五章 数据更新]() | [数据更新]() |  |  |
| [第六章 复杂查询]() | [复杂查询]() |  |  |
| [第七章 函数、谓词、CASE表达式]() | [函数、谓词、CASE表达式]() |  |  |
| [第八章 集合运算]() | [集合运算]() |  |  |
| [第九章 SQL高级处理]() | [SQL高级处理]() |  |  |
| [第十章 通过应用程序连接数据]() | [通过应用程序连接数据]() |  |  |
| 参考文献 | | |  |

还有很多同学提出了不少建议，我们都列在此处。

@CharlieSCC ...

如有遗漏，请务必通知我们，可以发邮件至`pkuscc@stu.pku.edu.cn`。
这是我们必须要感谢的，所以不要不好意思。
