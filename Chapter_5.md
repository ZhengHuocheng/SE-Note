# UML建模
## UML活动图(Activity Diagram)
>活动图是UML用于对系统的动态行为建模的另一种常用工具，用来描述活动的顺序，展现从一个活动到另一个活动的控制流。
### 活动图元素
1. 动作状态
   动作状态是指**原子**的，不可**中断**的状态，并在完成此动作后通过完成转换，转为另一个状态。状态图用平滑的圆角矩阵来表示。
   ![动作状态](./第五章图片/状态1.png)
   **动作状态的特点**
   * 动作状态必须是原子的，无法分解为更小的部分
   * 动作状态是不可中断的，一旦开始运行就不能中断，直到运行结束
   * 动作状态是瞬时的行为，它所占用的处理时间极短，有时甚至可以忽略
   * 动作状态可以有入转换，入转换可以是动作流，也可以是对象流；动作 状态至少有一条出转换，这条转换以内部的完成为起点，与外部事件无关
   * 动作状态与状态图中的状态不同，它不能有入口动作和出口动作，更不能有内部转移
2. 活动状态
   活动状态用于表示状态机中的非原子的运行。其图标在UML中与动作状态相同，但活动状态可以在图标中给出入口动作、出口动作等信息。
   ![活动状态](./第五章图片/活动状态.png)
   **活动状态的特点**
   * 活动状态可以分解成其他子活动或者动作状态
   * 活动状态的内部活动可以用另一个活动图来表示
   * 和动作状态不同，活动状态可以有入口动作和出口动作，也可以有内部转移
   * 动作状态是活动状态的一个特例，如果某个活动状态只包括一个动作，那么它就是一个动作状态
3. 开始点
   表示整个活动的开始
    ![开始点](./第五章图片/开始点.png)
4. 结束点
   表示整个活动的结束
    ![结束点1](./第五章图片/结束点1.png)
   子流程的结束
    ![结束点2](./第五章图片/结束点2.png)
5. 分支与合并
   分支：一入多出
   合并：多入一出
    ![分支合并](./第五章图片/分支合并.png)
6. 分叉与汇合
   分叉：用将控制流分为两个或者多个并发运行的分支
   汇合：用于同步这些并发分支，以达到共同完成一项事务的目的
   ![分叉汇合](./第五章图片/分叉与汇合.png)
7. 泳道
   ![泳道](./第五章图片/泳道.png)
8. 对象流
   * 可以把对象放置在活动图中并用一个依赖将其连接到进行创建、修改或撤销等动作状态或者活动状态上，对象的这种使用方法就构成了对象流
   * 对象流是动作状态或者活动状态与对象之间的依赖关系，表示动作使用对象或动作对对象的影响。
   * 可以理解为数据流
   ![泳道](./第五章图片/对象流.png)
## UML状态图
> 状态图（Statechart Diagram）主要用于描述一个对象在其生存期间的动态行为，表现为一个对象所经历的状态序列，引起状态转移的事件（Event），以及因状态转移而伴随的动作（Action）。一般可以用状态机对一个对象的生命周期建模，状态图用于显示状态机（State Machine Diagram），重点在与描述状态图的控制流。
>所谓状态机，它是一种行为，用于描述一个对象在其生命周期中的各种状态及状态的转换。
UML状态图主要由五种元素组成，分别是状态、转换、事件、动作和活动。
* 状态：表示对象的生命周期中的一种条件/情况，有初态和终态之分
   ![状态](./第五章图片/状态.png)
* 转换：表示两种状态间的一种关系
   ![转换](./第五章图片/转换.png)
* 事件：表示在某一时间与空间下所发生的有意义的事情
* 动作：表示一个可执行的原子操作，是UML能够表达的最小计算单元
* 活动：表示状态机中的非原子执行，一般由一系列动作组成
   ![示例](./第五章图片/示例.png)
## 状态图与活动图的关系
**联系**
活动图和状态图都可用来可视化状态机。
**区别**
状态图是描述某一对象的状态转化的，它主要是展示的是对象的状态。描述的是一个对象的事情。从状态图中我们可以看出，对象在接受了事件刺激后，会做出什么样的反应。
活动图是描述系统在执行某一用例时的具体步骤的，它主要表现的是系统的动作，描述的是整个系统的事情。

  
