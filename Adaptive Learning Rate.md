# Adaptive Learning Rate
## Momentum
改变ηg为m，结合之前每一次g的方向
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210315173052976.png)
## Adagrad
引入σ变η
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319160639783.png)

## RMSProp
引入α
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319212301760.png)


## Adam: RMSProp + Momentum

## Learning Rate Scheduling

1. Learning Rate Decay
改变η为η(t)
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319221921888.png)
2. Warm Up (RAdam): \Residual network\ \Transformer\
![Transformer](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319222922951.png)
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319223155277.png)
σ告诉我们,某一个方向它到底有多陡,或者是多平滑,那这个统计的结果,要看得够多笔数据以后,这个统计才精準,所以一开始我们的统计是不精準的。
一开始learning rate比较小,是让它探索 收集一些有关error surface的情报,先收集有关σ的统计数据,等σ统计得比较精準以后,在让learning rate呢慢慢地爬升。

## Optimization
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210319223804064.png)
