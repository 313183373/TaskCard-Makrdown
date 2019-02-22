# 文化课培训

2019/1/19日在[ThoughtWorks](https://www.thoughtworks.com/cn/)进行了公司**文化**课培训，虽然我之前在公司实习过，但是这次培训依然让我受益匪浅。以下是本次培训的总结

1. 首先介绍了公司的历史以及发展，TW在1993年创立，凭借着优秀的文化理念从一个小小的工作室发展到在14国家拥有4000+位行业精英的企业。

2. 然后一个同样是一毕业就到ThoughtWorks工作的同事分享她的TW之旅，我感觉我的很多经历也是跟她类似的😂，很激动也有一些不安，怕自己不能够圆满的完成自己的工作，但是她的故事让我有一些心理准备，我现在也得加油学习。

3. 然后讲了一下**敏捷实践**

   > 敏捷(Agile)这个词用以概括**一套全新的软件开发价值观**

   所以敏捷其实是一种新的软件开发价值观，它提倡

   |      |  |      |
   | :--------------: | :----: | :--------------: |
   | 个体和交互     | 胜过 | 过程和工具     |
   | 可以工作的软件 | 胜过 | 面面俱到的文档 |
   | 客户合作       | 胜过 | 合同谈判       |
   | 相应变化       | 胜过 | 遵循计划       |
   |  ||**虽然右项有价值，但是我们认为左项的价值更大**|

   在一个敏捷团队中，各个角色和他们的职责如下图所示：

   ![image-20190220182053828](https://ws4.sinaimg.cn/large/006tKfTcly1g0d279ymipj31eo0n8aj1.jpg)

   一个敏捷团队的正常流程是这样的

   ![image-20190220182440609](https://ws3.sinaimg.cn/large/006tKfTcly1g0d2b7h9s3j31bg0d6whx.jpg)

   - Product Backlog: 指的是整产品全部待完成的需求清单，这里面的需求粒度比较大，需求比较模糊，这个清单会持续完善，按照优先级排序，由PM负责。
   - Iteration Backlog:指的是本次迭代的需求清单，它是从Product Backlog中选出来的，代表本次迭代需要完成的需求，它比Product Backlog更加具体，并且也是可变化，整个开发团队可能会动态的调整Iteration Backlog的内容，
   - Backlog Tasks:指的是把之前Iteration Backlog中的内容拆分为更加具体的任务，比如前后端任务分离等。
   - Iteration:就是迭代的过程，开发团队会选择Backlog Tasks中的任务，并完成。
   - Potentially Shippable Product Increment:指的是这个迭代完成的所有需求的总和，以及之前的所有迭代所产生的总和，也就是增量。

   上面说到了**Iteration（迭代）**似乎很多东西都跟迭代有关，那么一个迭代到底是什么？

   ![image-20190220190008242](https://ws2.sinaimg.cn/large/006tKfTcly1g0d3c286xyj31k20qu7wh.jpg)

   以上就是一个迭代的具体过程，在每一个迭代开始的时候，会进行一个IPM（Iteration Project Meeting），这个会议的作用是

   - **达成一致**

     由**BA**进行描述讲解，使团队成员对需求的理解达成一致，并熟知业务背景上下文

   - 可行性评估

     团队成员（Dev）对需求的可行性进行评估，发现不合理的需求并提出

   - 工作量评估

     Dev对需求的工作量进行估点，评价复杂度

   开完了这个会议，就进行到日常的开发工作了，每天都会进行**Daily Scrum**：

   ![image-20190220192049151](https://ws4.sinaimg.cn/large/006tKfTcly1g0d3xl0sq2j31ks0p2ndz.jpg)

   每天的第一件事就是**站会**，它需要全员参与，每个人轮流更新状态，也就是自己**昨天做了哪些工作**，以及**今天准备做哪些工作**，好让大家都了解各自的工作进度，以便相互合作，同时也可以**提出遇到的问题**，以便会下与有解决办法的人讨论。

   然后就是**开卡（kick off）**，这里的卡指的是**故事卡**，由BA在IPM会议之前就写好了，在敏捷开发中，所有的需求都是通过故事卡来描述的。开卡需要BA和QA还有DEV一起对卡片的细节进行同步，**保证每个成员对故事卡的理解是一致的**。

   在DEV完成故事卡之后，会进行**结卡（Desk Check）**，也就是看开发出来的功能是否和故事卡描述的一致。

   最后在每天的敏捷开发最后，有一个**Code Review**阶段，就是代码回顾，DEV会**一起**进行代码的讲解，因为团队中的DEV肯定不止一个，需要其他DEV成员了解你所写的代码逻辑。以上就是Daily Scrum的流程。

   故事卡到底是一个什么东西，它是怎么描述需求的？

   ![image-20190220193552612](https://ws1.sinaimg.cn/large/006tKfTcly1g0d4d8w0udj311k0mqwo1.jpg)

   类似于上图。然后还会用到一个工具来帮助我们可视化地管理故事卡，叫做**看板**。

   ![image-20190220191452230](https://ws3.sinaimg.cn/large/006tKfTcly1g0fl4or55lj31ci0ng491.jpg)

   可以看到看板中划分出来了很多列，每一列都有名字，用于描述处于当前列的故事卡的状态。

   之前我们一直在讲Daily Scrum是什么，现在我们跳出来，在经过了一个迭代周期（很多个Daily Scrum）之后，需要进行**Show Case（演示）**。

   ![image-20190220194201304](https://ws3.sinaimg.cn/large/006tKfTcly1g0d4jnkd4wj31ho0t41kx.jpg)

   在演示结束之后，会进行**Retro（迭代回顾）**![image-20190220194316787](https://ws1.sinaimg.cn/large/006tKfTcly1g0d4kxvcvaj31jy0rs4ms.jpg)

   一般有两种方式回顾，一个是心情曲线，另一个是指出迭代中的Well/Less Well/Suggestion部分，然后提出一些Action，用于在下一次迭代中扬长避短。

   以上就是敏捷团队工作的方式。我感觉非常的科学和高效，能够让团队中的各个成员很好的合作。

4. 然后是**提反馈**，这也是公司文化之一，公司鼓励提反馈，反馈不一定是提不好的东西，也可以提好的东西作为鼓励，这就是非常好的地方，我们就着今天的培训提反馈，也提出了一大堆很有意义的反馈，希望下次的培训能够做得更好。

![image-20190219160312435](https://ws2.sinaimg.cn/large/006tKfTcly1g0bslnxe9xj31400u04qp.jpg)

