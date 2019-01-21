# 如何进行系统框架（设计）评审、代码评审

该文档用于**前端职能组**进行前端框架（设计）评审以及代码评审。

## Author

@bqliu

## 目的

- 检查代码质量
- 在项目的早期发现问题缺陷，将之后的返工、维护等成本尽量减小
- 代码评审亦是重新梳理思路的过程，能加深系统开发人员以及参与评审的非系统开发成员对系统的理解
- 能促进团队的沟通、知识共享以及共同提高
- etc

## 评审范围

评审的内容可能为待评审系统的以下部分：

- 整体的框架、设计（系统框架（设计）评审）
- 某一个或者某几个功能模块（功能模块代码评审）
- etc

## 参会人员

- 主讲人。主讲人为待评审系统的开发人员。
- 参与人。参与人有很多，包含以下可能情况：
    - 待评审系统的其他开发人员（除去主讲人）（必选）
    - 项目经理（可选）
    - 项目其他职能开发人员（可选）
    - 职能组负责人（可选）
    - 职能组其他成员（可选）
    - etc
- 记录人员。记录人员可以为主讲人也可以为参与人，概要记录整个过程。

## 流程

### 系统框架（设计）评审

- 主讲人对照着原型介绍整个项目。视成员对需求的熟悉程度，熟悉可花比较少的时间
- 主讲人介绍自己的框架（设计）选型
- 主讲人介绍为什么要使用这样的框架（设计）选型
- 主讲人介绍优势和劣势（注意事项）
- 主讲人、参与人进行交流，交流设计的不合理、疑问或者可改进之处
- 记录人员需要简要的记录整个过程（包括问题）
- 会议结束后，主讲人依据记录人员的记录，发出会议纪要
- 如果评审过程中提出了问题，需要在会议纪要中写出修复计划
- 如果评审过程中提出了问题，在修复计划截止之前需要进行一次反馈（形式不限），用于反馈是否解决了问题。形成一个闭环

### 代码评审

- 主讲人对照着现在开发的系统进行一个系统的业务讲解
- 主讲人介绍相关的功能模块设计
- 然后较细致的讲解功能模块代码
- 主讲人、参与人进行交流，交流代码的不合理、疑问或者可改进之处
- 记录人员需要简要的记录整个过程（包括问题）
- 会议结束后，主讲人依据记录人员的记录，发出会议纪要
- 如果评审过程中提出了问题，需要在会议纪要中写出修复计划
- 如果评审过程中提出了问题，在修复计划截止之前需要进行一次反馈（形式不限），用于反馈是否解决了问题。形成一个闭环

## 时间

### 举办时间

代码评审的时间可以选择在快要下班前 1h 或者晚上加班时间 7:00 左右开始。

### 持续时间

持续时间控制在 1.5h 以内。

## 奖惩

代码评审和绩效部分相关。

## 注意事项

- 评审内容不要贪多，控制在 1-2 个复杂模块，且代码行数在 500行 左右
- 时间注意控制
- 简单的编码风格问题主讲人需要按照规范自己把控

## Refs

- [【译】如何用人类的方式进行 Code Review](https://zhuanlan.zhihu.com/p/31581735)

## 版本

- 0.1 initial version