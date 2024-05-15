# Kolmogorov Complexity

要想了解AIT，就要了解[柯氏复杂度](https://en.wikipedia.org/wiki/Kolmogorov_complexity)。

在上个世纪，有三位数学家（[所罗门诺夫](https://en.wikipedia.org/wiki/Ray_Solomonoff)，[柯尔莫戈洛夫](https://en.wikipedia.org/wiki/Andrey_Kolmogorov)，[柴廷](https://en.wikipedia.org/wiki/Gregory_Chaitin)）分别在不同的时间点上独立的发现了柯氏复杂度（全称为柯尔莫戈洛夫复杂度，Kolmogorov Complexity，或者称为算法复杂度、描述复杂度、所罗门诺夫复杂度、柴廷常数）这个算法信息论中最核心的概念。

这三位数学家的出发点各不相同，但是从柯尔莫戈洛夫的视角出发会更容易理解这个概念。

柯尔莫戈洛夫作为上世纪最伟大的苏联数学家，曾长久的为“信息的本质”这个问题所困扰。经过漫长的思考，柯尔莫戈洛夫在1963年左右得出了最终的结论，他认为我们可以从三种不同的角度定义和理解信息的本质:
1. 组合学
2. 概率论
3. 算法 

其中，从组合学和概率论的角度出发，我们可以得到香农的经典信息论，也即从不确定性的角度来度量信息。而从算法的角度出发，我们可以得到柯氏复杂度。柯尔莫戈洛夫认为这个角度实际上是从随机性的角度来定义信息。同时他也认为，从这个角度出发得到的信息的定义是最好的。

克劳德·香农在1948年发表了[《通信的数学原理》](https://en.wikipedia.org/wiki/A_Mathematical_Theory_of_Communication)，创立了经典信息论。从那个时刻开始，人们认识到信息不是一种虚无飘渺的东西。在香农的信息论中，信息就如同电压一样，是一种可以定量计算、有实际物理含义的物理量。香农认为，信息本质上是不确定性的一种体现。他用信息熵来定义信息。

$$
H(X):=-\sum_{x \in X}P(x)logP(x)
$$