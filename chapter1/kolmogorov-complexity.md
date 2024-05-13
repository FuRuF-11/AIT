# Kolmogorov Complexity

在上个世纪，有三位数学家（[Solomonoff](https://en.wikipedia.org/wiki/Ray_Solomonoff)，[Kolmogorov](https://en.wikipedia.org/wiki/Andrey_Kolmogorov)，[Chaitin](https://en.wikipedia.org/wiki/Gregory_Chaitin)）独立的发现了算法信息论中最核心的概念算法复杂度（或者称为柯尔莫戈洛夫复杂度、柯氏复杂度，Kolmogorov Complexity）。

这三位数学家的出发点各不相同，我们这里首先从柯尔莫戈洛夫的视角出发来看看这个概念是如何得出的。

柯尔莫戈洛夫从“信息的本质是什么”这个问题出发，中得到柯氏复杂度。

柯尔莫戈洛夫认为我们可以从三种不同的角度定义信息:  
1. 组合学的角度
2. 概率论的角度
3. 算法的角度 