# Batch Normalization
## Changing Landscape
### Feature Normalization
1. Method one
对feature vector做 normalization

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210426204629991.png)

最终x tilde的均值为0，方差为1，分布在0上下，就此制造一个比较好的error surface
这样在做Gradient Descent的时候，Loss收敛更快，训练更顺利。

前提：Batch Size比较大。
对每一层Neural network都进行Normalization：
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210427085228640.png)

### Batch Normalization - Testing
!7[](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210427101956211.png)
