# Kolmogorov Complexity

要想了解AIT到底是什么，就必须要了解[柯氏复杂度](https://en.wikipedia.org/wiki/Kolmogorov_complexity)。

在上个世纪，有三位数学家（[所罗门诺夫](https://en.wikipedia.org/wiki/Ray_Solomonoff)，[柯尔莫戈洛夫](https://en.wikipedia.org/wiki/Andrey_Kolmogorov)，[柴廷](https://en.wikipedia.org/wiki/Gregory_Chaitin)）分别在不同的时间点上独立的发现了柯氏复杂度（全称为柯尔莫戈洛夫复杂度，Kolmogorov Complexity，或者称为算法复杂度、描述复杂度、所罗门诺夫复杂度、柴廷常数）这个算法信息论中最核心的概念。

这三位数学家的出发点各不相同，但是从柯尔莫戈洛夫的视角出发则更易理解这个概念。

柯尔莫戈洛夫作为上世纪最伟大的苏联数学家，曾为“信息的本质是什么”这个问题长久的困扰。经过漫长的思考后，柯尔莫戈洛夫在1963年左右得出了最终的结论，他认为我们可以从三种不同的角度定义和理解信息:
1. 组合学
2. 概率论
3. 算法 

其中，从组合学和概率论的角度出发，我们可以得到香农的经典信息论，也即从不确定性的角度来度量信息。而从算法的角度出发，我们可以得到柯氏复杂度，柯尔莫戈洛夫认为这个角度实际上是从随机性的角度来定义信息。

