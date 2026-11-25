# Soma & Signal

**同一个信号，为什么会因过去的经历而引发不同的行动？**

我们用小型神经网络研究这个问题。模型在可重放的世界中接收观察、做出选择。实验改变模型能保留的状态，再用对照任务检验哪些经历确实影响了下一次选择。

[探索模型](https://github.com/Brain-Soma-Signal/neural-dynamics) · [接入世界](https://github.com/Brain-Soma-Signal/world-api) · [阅读评测规范](https://github.com/Brain-Soma-Signal/cognitive-assays)

### 一次实验如何串起来

世界接口交付一帧观察。模型用当前输入和保留的状态选一个动作。评测可以在同一条件下擦除记忆，观察选择是否随之改变。这样的差异能检验模型是否使用了记忆；主观体验仍是开放问题。

| 仓库 | 可以从这里做什么 |
| --- | --- |
| [neural-dynamics](https://github.com/Brain-Soma-Signal/neural-dynamics) | 检查一个树突分支如何计算，或把普通投影层替换成能跨事件保留状态的层。 |
| [world-api](https://github.com/Brain-Soma-Signal/world-api) | 重放一条完整的观察与动作轨迹，为新环境实现同一套契约。 |
| [cognitive-assays](https://github.com/Brain-Soma-Signal/cognitive-assays) | 查阅 14 项功能检验的研究依据、对照条件，以及每项结果允许得出的结论。 |
