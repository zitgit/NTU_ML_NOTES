# Transformer
## Encoder-Decoder
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210429210257652.png)

### Residual Connection
### Layer Normalization
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210429211313025.png)

但是要注意一下,batch normalization是对不同example,不同feature的同一个dimension,去计算mean跟standard deviation

但layer normalization,它是对同一个feature,同一个example裡面,不同的dimension,去计算mean跟standard deviation

### Encoder Structure
![](https://github.com/unclestrong/DeepLearning_LHY21_Notes/blob/master/Notes_pic/image-20210429212721750.png?raw=true)

### Decoder Autoregressive
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210505203437172.png)

在Decoder的结构里，运用的是Masked Self-attention
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210505204215642.png)

### Decoder Non-autoregressive (NAT)
优点：1. 并行化 一个步骤就产生完整的句子 2. 控制输出长度
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210505214728437.png)

### Encoder-Decoder Cross Attention
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210506105352521.png)

### Training: Teacher Forcing
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210506150925655.png)

