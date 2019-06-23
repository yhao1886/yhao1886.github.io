## 简答题

1. **用例的概念**

   > 用例就是外部可见的系统功能，对系统提供的服务进行描述。

2. **用例和场景的关系？什么是主场景或 happy path？**

   > - 场景是参与者和系统之间的一个特定的动作和交互序列（会话）；它也被称为用例实例。
   > - happy path测试是一个定义明确的测试用例，它使用已知输入，无异常执行并产生预期输出。

3. **用例有哪些形式？**

   > - Brief (high level)
   >   - Terse one-paragraph summary, usually of the main success scenario.
   >   - During early requirements analysis, to get a quick sense of subject and scope. May take only a few minutes to create.
   > - Casual（简便格式）
   >   - Informal paragraph format. Multiple paragraphs that cover various scenarios.
   >   - When? As above.
   > - Fully
   >   - dressed All steps and variations are written in detail, and there are supporting sections, such as preconditions and success guarantees.
   >   - After many use cases have been identified and written in a brief format, then during the first requirements workshop a few (such as 10%) of the architecturally significant and high-value use cases are written in detail.

4. **对于复杂业务，为什么编制完整用例非常难？**

   > 复杂业务的子用例非常多，流程复杂，且需要处理的场景很多。因此很难考虑完全所有子用例和场景，且绘制的用例图繁杂，容易出错。

5. **什么是用例图？**

   > 用例图主要用来描述角色以及角色与用例之间的连接关系。说明的是谁要使用系统，以及他们使用该系统可以做些什么。一个用例图包含了多个模型元素，如系统、参与者和用例，并且显示这些元素之间的各种关系，如泛化、关联和依赖。它展示了一个外部用户能够观察到的系统功能模型图。

6. **用例图的基本符号与元素？**

   > - 元素：
   >
   > 参与者(Actor)——与应用程序或系统进行交互的用户、组织或外部系统。用一个小人表示。
   >
   > 用例(Use Case)——用例就是外部可见的系统功能，对系统提供的服务进行描述。用椭圆表示。
   >
   > 子系统(Subsystem)——用来展示系统的一部分功能，这部分功能联系紧密。
   >
   > - 基本符号
   >
   > [![1555057660880](https://github.com/yhao1886/yhao1886.github.io/blob/master/swsad/picture/1555057660880.png?raw=true)]()

7. **用例图的画法与步骤**

   > 1. 确定参与者
   >    - 谁将使用该系统的主要功能。
   >    - 谁将需要该系统的支持以完成其工作。
   >    - 谁将需要维护、管理该系统，以及保持该系统处于工作状态。
   >    - 系统需要处理哪些硬件设备。
   >    - 与该系统交互的有什么系统。
   >    - 谁或什么系统对本系统产生的结果感兴趣。
   > 2. 识别用例
   >    在识别用例的过程中，通过回答以下几个问题，系统分析者可以获得帮助。
   >    - 特定参与者希望系统提供什么功能。
   >    - 系统是否存储和检索信息，如果是，由哪个参与者触发。
   >    - 当系统改变状态时，是否通知参与者。
   >    - 是否存在影响系统的外部事件。
   >    - 哪个参与者通知系统这些事情。
   >    - 哪个参与者通知系统这些事件。
   > 3. 确定用例间的关系
   >    - 包含关系
   >    - 泛化关系
   >    - 关联关系

8. **用例图给利益相关人与开发者的价值有哪些？**

   > - 对于利益相关者：
   >   - 可以直观看到系统的功能和操作过程，保证系统按用户的需求进行设计
   >   - 用例能够根据需要对复杂程度和形式化程序进行增减调节，即能够响应用户（利益相关者）提出的需求，而用例图则使得这种调节更加便利，可以通过修改修改用例图来实现。
   > - 对于开发者：
   >   - 明确系统的业务范围、服务对象（角色）、外部系统与设备
   >   - 帮助识别技术风险，提前实施关键技术原型攻关与学习
   >   - 易于评估项目工作量，合理规划迭代周期，规划人力需要
