__机密文件，仅允许获得授权的 W.S.C 高级别成员阅读。本文件内容使用基于模因的保密机制进行保护，未经授权阅读本文件，可致心脏骤停。__

__你已经被警告过了。__

__如果你没有权限，但碰巧看到了这份文件，请不要阅读，并将其上交 W.S.C 管理部门。__

__从这一行开始，如果你未被授权，你的思维活动开始受到监视。__

__最后一次警告。__

# 《Psychic Dominator Enhanced》

- 作者：Chuigda - ICEYSELF <!-- 想不到吧是同一个人 -->
- 发表日期：2017.1
- 收录于：W.S.C 机密数据库

## 摘要
革命的时刻到了。为了使 W.S.C 在世界范围内能更容易且隐秘地达成一些目标，魔法一侧必须开发一系列小规模的、隐秘的、战术性的 Kuiter 法术<sup>[1][2][3][5]</sup>。这些法术通常仅仅需要较少的能耗，并且借助现代科技的能力，能掩盖自己属于法术的事实<sup>[3][5][6]</sup>。相比于其他破坏性法术<sup>[3][5]</sup>，由于其悄无声息渗透敌对机构的潜力，精神类法术近年来格外受到重视<sup>[1]</sup>。本文提出了一种新型的精神控制法术，能使用非常低且便于隐藏的 Kuiter 功耗控制少部分人的心智，并在表面上维持其人格基本不发生改变。

## 1. 简介
自“严重事件”以来数百年，尽管魔法侧事实上拥有远超科学侧的能力，但我们仍然处于科学一侧的压制之下 —— 这种趋势在近年以来达到了一种全新的高度<sup>[8][9]</sup>。我们迫切需要一种将世界转交至我们手中的能力，同时保证这个过程平稳且可控，避免不必要的武力冲突。精神控制设备 Psychic Dominator<sup>[10]</sup> 一定程度上可以办到这一点，并且目前我们已经稳定地使用将精神控制移植到以 Kuiter 为基础的技术栈上<sup>[13]</sup>。尽管如此，这种精神控制仍不完美，主要是由于受控者的记忆和情感完全消失，思维模式接近麻木的纯粹理性，只能依据简单的命令和固定的逻辑<sup>[13]</sup>。如果使用这种技术进行渗透，很容易就会被发觉。针对这一问题，本文提出了相应的解决方案，并且构建了可用的原型机。

## 2. 精神控制原理简述
根据 Yuri 等人早期的研究<sup>[10]</sup>，精神控制技术具有点对点和群体控制两个分支，但是殊途同归，本质都是首先利用强大的冲击使受控者陷入某种类似于自闭<sup>[7][12]</sup>的状态，借机摧毁大脑中正在运行的自我意识，并安装一组控制程序，使受控者按遵从特定的指令或者按照特定的规则行动。点对点控制技术依赖于基于心灵控制波的语音加密，而群体控制技术则直接使用心灵冲击波。然而，点对点控制技术十分耗费控制者的精神力量，容易引起控制者神经衰弱甚至精神崩溃；而群体控制技术则极度费电<sup>[17]</sup>。在使用 Kuiter 技术重塑<sup>[13]</sup>后，以上两项缺点得到了克服，但受控者的心智问题仍然无法解决。

## 3. 我们的解决方案
简单来说，问题的根源在于心灵控制时我们仅仅恢复了受控者简单的行为逻辑，却没有恢复受控者的记忆和情感。为此，我们尝试过针对人类情感分析问题进行建模，并查阅了相关文献，了解情感的处理由专门的脑区进行<sup>[4][11][12][16]</sup>。受制于神经科学和计算机技术的发展，目前尚没有机构有能力彻底解析大脑的结构，故而此路不通。

在进行调查分析时我们注意到，一些阿斯伯格综合征患者，其情感处理功能几乎完全不活动，但他们仍然能识别别人的情绪，并且依据不同的情况进行适当的响应<sup>[12][15][16]</sup>。研究表明，这些患者利用他们在长期生活中习得的经验，配合逻辑分析，从而模拟“感情”的存在。这为我们的研究提供了思路。

在 Yuri 发布的精神控制程序<sup>[10]</sup>的基础上，我们对其功能进行了增补，使用 BCC 代码编写了一个简单的情感处理虚拟层。增加此虚拟层后，受控者能够明显明确感受其接触到的人和事件中隐含的情绪和情感，并且作出适当的相应。但问题在于，尽管能处理情感，但受控者仍然不具有自己的人格。人格在一定程度上由基因编码，也与后天的成长有关<sup>[16]</sup>。此外，如果没有受控者的记忆，受控者将无法回答许多关于自己、家人和朋友的问题，显而易见，这还是会让我们的渗透迅速暴露。

通过对人类记忆模型的研究<sup>[20][21][22]</sup>，利用我们对长短期记忆的认知，我们成功建立了一个只读的脑文件系统。该文件系统区分高速缓存（下丘脑、海马区域）和长期存储区（神经元之间的连接）<sup>[20][22]</sup>，依据不同的存储类型采用不同的读取方式。由于对人脑的数据持久化机制缺乏了解<sup>[19]</sup>，我们没有建立可写的文件系统，而是在大脑后台持续运行两个保存进程，两个进程互为守护进程，以“循环播放”的形式储存受到精神控制之后的记忆。利用记忆中包含的数据，受控者人格的重塑得以基本完成。受控者不但记得自己的经历，也能依照之前的人格处理事件，甚至能模仿自己之前的语调。在 176 名最终被成功控制的受试者中，162 人的家属表示受试者和接受测试之前并无区别，12 人认为受试者可能接受了某种心理治疗，2 人认为受试者和之前的行为有一定差异，这表明技术具有了相当高的实用价值。

## 4. 存在的问题
首先的问题是，虚拟层会给大脑的运行带来额外的负担，而“循环播放”机制会加重大脑的负担。我们的一项针对 200 名受试者的实验中表明，受控者最多只能正常生活九个月左右，平均只能正常生活四个月，然后就会出现各种精神问题。我们使用了各种自动优化技术，包括让模拟层自动休眠、自动移除无用的记忆，这些措施被证实能提高受控者的生存时间，但均未能完全消除精神问题。

此外，具有强大心智的人类仍然可以免于控制，这是心灵控制的固有问题<sup>[17]</sup>，需要其他方面的技术变革来解决。在针对 30 名来自 NK地区 的受试者的实验中，有 18 人未能受到控制，他们仍然坚信某种思想。其他地区的受试者也存在不同程度的控制失败的情况。

最后，尽管启动心灵控制需要的 Kuiter 动力非常小，但对算力（以及电力）需求，由于增加虚拟层、文件系统和人格模块的缘故，甚至比前一代要高出两个数量级。我们的样机使用了 2 枚 AMD Threadripper 3990X<sup>[23]</sup> 和 4 路 Tesla V100<sup>[25]</sup> 才能一次性达成稳定的控制效果，而前代设备甚至可以使用 Atom 系列处理器<sup>[24]</sup>。这对我们设备的小型化是一个巨大的挑战。

## 5. 结论
本文提出了一种十分有前景的精神控制技术，倘若加以改进，将能成为我们征服世界的极大助力。我们已经在北美地区制造了一台样机用于实验用途，全部的代码和设计图纸目前存放在 W.S.C 在月球背面的数据库中，拥有权限的人可以下载这些内容。

## 参考文献
[1] 奥西里尔, 伊万. 论战术法术发展的必要性和重要性[C].W.S.C第四次高层峰会会议记录. 2016:53-66.

[2] 奥西里尔. 小型战术法术的发展趋势[D].W.S.C第一学院欧洲分院区, 2006.

[3] 约瑟夫. 一种小型的法术驱动的战术聚变武器[J].新地平线年报, 2008:15-18.

[4] Fodor J A.The modularity of mind[J].Philosophical Review, 1983, 8(1):73–77.

[5] 弗拉斯. 一种法术驱动的信号屏蔽器[J].新地平线年报, 2007:73-79

[6] 阿列克谢, 奥里西尔, 友川纪夫. 战术法术运用调查[N].Kuiter发展报. 2013, 90(2):1-2.

[7] Courchesne E. Brainstem, cerebellar and limbic neuroanatomical abnormalities in autism.[J].Current Opinion in Neurobiology, 1997, 7(2):269-278.

[8] Chuigda, 彼得, 约德尔. 法师人权调查报告[N].Kuiter发展报. 2015, 1(1):1-4.

[9] Chuigda, 奥西里尔. 法师人权调查报告[N].Kuiter发展报. 2016, 1(1):1-4.

[10] Yuri. Dissection of psychic technologies[J].Soviet Power Supreme. 1979, 3(1):55-72.

[11] J. W. M. Papez. A Proposed Mechanism of Emotion[J].Arch.neurol.psychiat, 1995, 7(1):103-112.

[12] Susan Folstein, Michael Rutter. INFANTILE AUTISM: A GENETIC STUDY OF 21 TWIN PAIRS[J].Journal of Child Psychology & Psychiatry, 2006, 18(4):297-321.

[13] Delxue. Kuiter empowered psychic dominator[C].W.S.C第二次高层峰会记录. 2012:11-15.

[14] Castelli Fulvia, Frith Chris, Happé Francesca, 等. Autism, Asperger syndrome and brain mechanisms for the attribution of mental states to animated shapes[J].Brain, 2002(8):8.

[15] 魏薇, 静进, 金宇, et al. 阿斯伯格综合征男童的眼动抑制缺陷对照研究[J]. 中国儿童保健杂志, 2010, 18(11):838-840.

[16] Hede Helfrich. Emotion[M].Kulturvergleichende Psychologie. 2014.

[17] Comrade general, et al. An inspection of usages of psychic devices[R].Soviet battleground report, 1984, 33(6):12-13.

[19] Chuigda. ScottDB: A write optimized database with novel reading performance[J].PLDI, 2020.

[20] Baddeley A. Human memory: theory and practice[J]. 1990.

[21] Spear N E. Retrieval of memory in animals[J]. 1973, 80(3):163-194.

[22] Wenjuan Wu, Shuwen Du, Wei Shi, 等. Inhibition of Rac1-dependent forgetting alleviates memory deficits in animal models of Alzheimer’s disease[J]. Protein & Cell, 2016, 10(10).

[23] AMD official. _www.amd.com_

[24] Intel official. _www.intel.com_

[25] Nvidia official. _www.nvidia.com_
