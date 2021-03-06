> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码， 原文地址 [www.paddlepaddle.org.cn](https://www.paddlepaddle.org.cn/tutorials/projectdetail/3465975)

> 飞桨致力于让深度学习技术的创新与应用更简单。

机器学习的实现可以分成两步：训练和预测，类似于归纳和演绎：

*   **归纳：** 从具体案例中抽象一般规律，机器学习中的 “训练” 亦是如此。从一定数量的样本（已知模型输入 X 和模型输出 Y）中，学习输出 Y 与输入 X 的关系（可以想象成是某种表达式）。
*   **演绎：** 从一般规律推导出具体案例的结果，机器学习中的 “预测” 亦是如此。基于训练得到的 Y 与 X 之间的关系，如出现新的输入 X，计算出输出 Y。通常情况下，如果通过模型计算的输出和真实场景的输出一致，则说明模型是有效的。