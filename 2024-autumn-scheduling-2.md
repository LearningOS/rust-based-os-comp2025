
# 2024年秋冬季开源操作系统训练营：第二阶段

## [专业阶段 - OS设计实现](https://opencamp.cn/os2edu/camp/2024fall/stage/2)

- [新闻与纪要](./news.md)
- [常见问题解答](./QA.md)
- [Learning Resource](./relatedinfo.md) (训练营学习资源)
- [直播教室](https://opencamp.cn/os2edu/camp/2024fall/stage/2)
- [视频回放与课件](https://opencamp.cn/os2edu/camp/2024fall/stage/2?tab=video)
- [实验指导书](https://learningos.cn/rCore-Camp-Guide-2024A/)

- Online Ranking （训练营在线排行榜）
  - [rCore Tutorial 晋级榜单](https://opencamp.cn/os2edu/camp/2024fall/stage/2?tab=rank)
- Classroom
  - [rCore Tutorial ClassRoom邀请链接](https://classroom.github.com/a/XCCbdobQ) （点击创建仓库）


## 相关信息：

- [参加2020--2022 OS训练营学生的blog](https://rcore-os.github.io/blog/)，鼓励参加2024 OS训练营的同学把自己在学习过程中的感悟/收获等写成blog，生成pr，并提交到 <https://github.com/rcore-os/blog> 上，让更多人看到你的进步！
- **注意** 为及时了解和指导同学的学习和实践情况并推动学生相互帮助，本次活动要求学生把每周学习实践的过程记录（Markdown格式）放在github上自己的公开repo中。可参见[每日学习实践的具体例子](https://github.com/GCYYfun/DailySchedule)和[2020年OS训练营同学的每日学习情况汇总](https://github.com/rcore-os/rCore-Tutorial/issues/18 ) 。请参加实习的同学把记录每天的进展的git repo网址 更新到[2024年OS训练营同学的每日学习情况汇总](https://github.com/LearningOS/rust-based-os-comp2023/issues/200) 中。要求每位同学在自己的git repo中记录自己的每周进展，其他同学也可以参考学习。
- **注意** 第二阶段学习中的技术问题，建议基于[开源操作系统社区-问答论坛](https://opencamp.cn/os2edu/bbs) 发出并讨论
- 常见问题 Q&A
    - [2024 秋冬季训练营常见问题](https://opencamp.cn/os2edu/bbs/1382)
    - [2024秋冬季训练营【专业阶段】群内问题汇总](https://opencamp.cn/os2edu/bbs/1396)
    - [训练营网站常见问题和故障](https://opencamp.cn/os2edu/bbs/1386)


## 第二阶段活动安排

### 第二阶段的训练步骤

基于Rust语言进行操作系统内核实验--based on qemu （三周时间）

前提条件：要求有操作系统的基础，基本理解RISC-V与OS相关的硬件特性

#### 课程参考
- [课程幻灯片](https://www.yuque.com/docs/share/4c39608f-3051-4445-96ca-f3c018cb96c7)
- 参考书
  - [Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)
  - [深入了解计算机系统](https://hansimov.gitbook.io/csapp/)
  - [RISC-V Reader中文版](http://riscvbook.com/chinese/RISC-V-Reader-Chinese-v2p1.pdf)
  - [rCore Tutorial Book v3](https://learningos.github.io/rCore-Tutorial-Book-v3/)

#### 基于Rust语言的rCore Tutorial实验指导 [rCore-Tutorial-Guide-2024A](https://learningos.github.io/rCore-Tutorial-Guide-2024A/)
- [API文档](https://github.com/LearningOS/rCore-Tutorial-Guide-2024A/#os-api-docs-of-rcore-tutorial-code-2022s) 
- [实验代码](https://github.com/LearningOS/rCore-Tutorial-Code-2024A)
- [测试用例](https://github.com/LearningOS/rCore-Tutorial-Test-2024A)


#### [rCore实验讲解视频](https://www.yuque.com/docs/share/1b5b9260-8a80-4427-a612-78ec72b37e5f)

#### 建立基于ClassRoom实验的具体步骤

**基于Rust语言的rCore Tutorial**
- [rCore Tutorial ClassRoom邀请链接](https://classroom.github.com/a/XCCbdobQ)：点击后按提示可以建立自己的rCore Tutorial实验专用仓库
- [rCore Tutorial ClassRoom排名页面](https://opencamp.cn/os2edu/camp/2024fall/stage/2?tab=rank)：可以查看自己的rCore Tutorial实验的排名情况

请根据各个实验的具体实验要求在自己的仓库中完成 ch[3,4,5,6,8] 5个实验。请在每完成一个实验（完成编码和实验报告文档）后，请通过执行 `git push` 命令来更新自己的实验专用 repos，来通过基于GitHub Classroom的CI测试。

### 总体学习要求和成绩考核方式

晋级要求：
1. 第二阶段排行榜满**500分**
2. 每个实验的总结报告 (`reports/lab[3,4,5,6,8].md`)
3. 第一、二阶段的学习blog （通过 PR 合并）

注意：需提供 **排行榜截图 + blog PR截图** 进行确认，通过检查后方可晋级第三阶段。

### 关于学习记录与 blog

每个阶段结束后需要写总结报告，第二阶段需要完成第一、二阶段的blog,请参照[2024 秋冬季训练营常见问题](https://opencamp.cn/os2edu/bbs/1382)第19问。

- [学习记录的标杆1](https://github.com/LearningOS/record)，浙江大学本科生徐文浩的2020开源操作系统训练营的过程记录，是大家学习的榜样，供大家学习参考。
- [学习记录的标杆2](https://kiprey.github.io/tags/uCore/)：湖南大学本科生肖政杭的自学ucore for x86的过程记录，是大家学习的榜样，供大家学习参考。

One More Thing：当你看到这，感觉第二阶段还没开始，还在想下一步要干啥时，我们的建议是：**Just Do It NOW!**
