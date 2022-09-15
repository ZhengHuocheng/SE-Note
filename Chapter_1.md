# 第一章 软件工程引入
## 软件的定义 ##
  >软件工程，包括软件和工程两部分。**软件**是软件工程的研究对象，也是软件工程的产品形态和客观存在；**工程**是将理论和知识应用与实践的科学，其目的是经济有效地解决实际问题。

***软件 = 程序 + 数据 +文档***
* **程序**：计算机可以接受的一系列指令，运行时可以提供所要求的的功能和性能。
* **数据**：使得程序能够适当地操作信息的数据结构。
* **文档**：描述程序的研制过程、方法和使用的图文资料。
## 软件的本质特性 ##
软件具有 **复杂性** 、**一致性** 、 **可变性** 和 **不可见性**等固有的内在特性，这使得软件的开发过程难以控制，这也是造成软件开发难的根本原因。
![软件的修改与故障](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E7%9A%84%E4%BF%AE%E6%94%B9%E4%B8%8E%E6%95%85%E9%9A%9C.png)

## 软件开发的困难之处 ##
![软件的开发困难](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E5%BC%80%E5%8F%91%E7%9A%84%E5%9B%B0%E9%9A%BE.png)

**90年代至今的软件开发指南**
* 敏捷开发方法
* 更紧密的团队协作
* 有效应对需求变化
* 快速交付高质量软件
* 采用 **迭代**和 **增量**的开发过程
## 软件工程的概念
**工程**的过程涉及三个方面:
* 大规模的设计与建造
* 复杂问题与目标分解
* 团队协作与过程控制
**软件工程**是1、将系统化、规范化、可定量的方法应用于软件的开发、运行和维护，即工程化应用到软件上；2、对1中所用的放大的研究。
## 软件工程的基本要素
* **过程**：支持软件开发各个环节的控制和管理。
  ![软件工程过程](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E8%BF%87%E7%A8%8B.png)
* **方法**：完成软件开发任务的技术手段
  ![软件工程方法](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E6%96%B9%E6%B3%95.png)
* **工具**：为软件开发提供自动或半自动的软件支撑环境。
  ![软件工程工具](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B7%A5%E5%85%B7.png)
## 软件开发的基本策略
* **软件复用**：构造一个新的系统不必从零做起，直接复用已有的构件进行组装。构件是经过反复使用验证的，由其组成的新系统具有较高的质量。
  ![软件复用](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E8%BD%AF%E4%BB%B6%E5%A4%8D%E7%94%A8.png)
* **分而治之**：将一个复杂的问题分解为若干个简单的问题，然后逐个解决。这来源于人们的生活经验，也完全适用于技术领域。
  ![分而治之](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E5%88%86%E8%80%8C%E6%B2%BB%E4%B9%8B.png)
* **逐步演化**：软件开发是一个自底向上的逐步有序的生长过程。每实现一步再进行调整，并为下一步确定方向，直到终点。
  ![逐步演化](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E9%80%90%E6%AD%A5%E6%BC%94%E8%BF%9B.png)
* **优化折中**：优化软件的各个质量特性，如运行速度、资源利用、用户体验。并通过协调各个质量特性，实现整体的质量最优。
  ![优化折中](https://github.com/ZhengHuocheng/SE-Note/blob/main/Images/Chapter_1/%E4%BC%98%E5%8C%96%E6%8A%98%E4%B8%AD.png)
