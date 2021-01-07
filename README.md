本文由 TensorFlow 社区作者创作，文章已入选 “TensorFlow 开发者出道计划” 精选推荐，关注 TensorFlow 社区，参与社区共建，点击这里了解更多。 全能社区，一起建设！
![](https://img-blog.csdnimg.cn/20201228173459402.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3pvbmc1OTY1Njg4MjF4cA==,size_16,color_FFFFFF,t_70)


## **系列开篇语**

  

> 写深度学习博客有两年多了，从最初的做记录备忘到现在经验总结分享，积累了一些读者，也结识了不少想入门研究深度学习的朋友。有不少朋友私聊问小宋如何快速入门深度学习，我发现大部分小伙伴都是对这方面有兴趣面对网上丰富的资料却不知道如何选择与操作。从而让我萌发了写一个一步步手把手带大家如何从零开始学习，使得基础薄弱的人员能以更简单易懂的方式入门深度学习与实战开发系列教程——**《带你学AI与TensorFlow2实战》**。

![](https://img-blog.csdnimg.cn/img_convert/53b608e2d2f8cf520bb40adf164b59c4.png)


《带你学AI》包括对于深度学习原理的直白讲解与应用的开发实践，代码实现选择了易用性与部署性俱佳的TensorFlow2框架。系列教程通过对学习方法讲解以及环境手把手搭建，降低深度学习入门门槛，从而使小白用户也能利用深度学习，应用到实际的生活与生产中。

  

> 小宋说：《带你学AI》系列可能不是最专业严谨深奥的学习资料，而是希望要成为一个浅显易懂适合初学者的系列指南。私以为，告诉大家如何去做不如去做，不如教大家如何去思考，和大家一起深度思考总结远比教会一个技术更重要。

  

[《带你学AI》](https://github.com/xiaosongshine/Learn2Ai4TensorFlow2)系列教程将分为以下十一个部分：

**1. **章节一：初探AI（《带你学AI与TensorFlow2实战一之深度学习初探》）：（[已完成](https://xiaosongshine.blog.csdn.net/article/details/111505064)）****

**2. **章节二：环境搭建（《带你学AI与TensorFlow2实战二之多系统开发环境与工具搭建》）：（[Windows10篇完成](https://xiaosongshine.blog.csdn.net/article/details/112249592)；Ubuntu18进行中）****

**3. **章节三：CV项目分类实战（《带你学AI与TensorFlow2实战三之交通标志分类项目》）：****

**4. **章节四：CV项目目标检测实战（《带你学AI与TensorFlow2实战四之口罩检测项目》）：****

**5.** ****章节五：CV项目像素分割实战（《带你学AI与TensorFlow2实战五之人体抠图********分割》）：****

**6. **章节六：CV项目基于GAN实战图像生成（《带你学AI与TensorFlow2实战六之基于GAN生成卡通形象》）：****

**7. **NLP项目基于RNN+Attention文本分类（《带你学AI与TensorFlow2实战七之影评分类》）：****

****8.章节八：NLP项目基于Transformer中英翻译（《带你学AI与TensorFlow2实战八之Transformer中英翻译》）：****

****9.章节九：NLP项目基于BERT预训练模型实战（《带你学AI与TensorFlow2实战九之Bert中文文本摘要》）：****

****10.章节十：强化学习DQN实战走迷宫（《带你学AI与TensorFlow2实战十之基于DQN实战走迷宫》）：****

****11.章节十一：算法模型应用的部署（《带你学AI与TensorFlow2实战十一之算法模型工程化应用部署》）：****

  

旨在通过对原理的通俗讲解、学习方法的介绍培养、开发环境的手把手搭建、深度学习案例开发讲解以及算法模型应用部署使用。

**这是一个开源免费的教程，希望能和更多朋友一起分享贡献，不断完善。代码与文档将同步在GitHub：**[https://github.com/xiaosongshine/Learn2Ai4TensorFlow2](https://github.com/xiaosongshine/Learn2Ai4TensorFlow2)

  

现在正式开始AI学习之旅喽...

**Keep Fighting。。。**

![](https://img-blog.csdnimg.cn/img_convert/1d7ef3c3f998b1e25375d145b32e0bb3.png)

**同时推荐大家关注笔者公众号“极简AI”（ID：BriefAI），一起探讨学习深度学习理论与应用开发技术。**

> 欢迎大家关注小宋公众号**《极简AI》**带你学深度学习：
> 
> ![](https://img-blog.csdnimg.cn/img_convert/f4c0601fd8f86b2795e3d00928660bd9.png)
> 
> ​基于深度学习的理论学习与应用开发技术分享，笔者会经常分享深度学习干货内容，大家在学习或者应用深度学习时，遇到什么问题也可以与我在上面交流知无不答。
> 
> 出自[CSDN博客专家](https://xiaosongshine.blog.csdn.net/)&[知乎深度学习专栏作家](https://www.zhihu.com/people/xiaosongshine/activities)@小宋是呢
