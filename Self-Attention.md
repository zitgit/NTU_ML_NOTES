# Self-Attention
信号（文字，图片，分子信息）处理的方法：
One-Hot Encoding：对于一个特征值的m种可能值，经过独热编码后就变成了m个二元特征。
用于分类器处理属性数据的问题；起到了扩充特征的作用
Word Embedding

## Self-Attention Structure
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210404202435331.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210404204458431.png)

### Attention Score

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210404212945356.png)
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210404213559086.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210409101331347.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210409102832459.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210409103622596.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210409105513608.png)

根据第A'这个矩阵裡面的每一个 column裡面每一个 element，做weighted sum
总体结构：
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210409110638357.png)
## Multi-head Attention
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210412194533453.png)
## Positional Encoding
## RNN VS Self-Attention
RNN无法平行处理所有的输入vector sequence；SA更有效率
## Self-Attention for Graph

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210413155347467.png)
