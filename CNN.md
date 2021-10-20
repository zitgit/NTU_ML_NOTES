# CNN
## Image Classification
### Receptive field: 感受野
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210329155519341.png)
kernel size: 3×3
stride：步长
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210329164727908.png)
### Parameter Sharing: Filter
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210329191243099.png)

## Convolutional Layer
The Filters are used to detect the patterns.
one Filter corresponding to one Feature Map
64 Filters corrsponding to 64 channels
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210330161535127.png)

## Understanding
Neuron的通过Sharing Parameters感受不同的Receptive Field，这就是Filter
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210330164622894.png)

## Pooling: Max Pooling
Convolution后，对Feature Map进行Max Pooling：
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210330170700272.png)

# CNN structure
![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210330171219295.png)

![](https://gitee.com/unclestrong/deep-learning21_note/raw/master/imgbed/image-20210330184237888.png)
