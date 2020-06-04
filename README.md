# Transfer-Learning-with-Keras-and-Deep-Learning
Applying Inception V3 and ResNet-50 models on CIFAR-10 data.

**Accuracy for 10-class problem**

|     Model    | Training   Accuracy (%) | Validation   Accuracy (%) |
|:------------:|:-----------------------:|:-------------------------:|
| Inception V3 |          63.76          |           63.45           |
|   ResNet50   |           15.3          |            10.4           |


**Accuracy for 3-class problem**

| Optimizer | Divison factor | Dropout | Activation | Validation   Accuracy(%) |
|:---------:|:--------------:|:-------:|:----------:|:------------------------:|
|    Adam   |       255      |   0.2   |    Relu    |           93.07          |
|    Adam   |      1023      |   0.5   |    Relu    |           93.47          |
|    Adam   |      1023      |   0.2   |    Relu    |           91.8           |
|    sgd    |      1023      |   0.2   |    Relu    |           88.37          |
|    sgd    |      1023      |   0.2   |    tanh    |           86.77          |
|    Adam   |      1023      |   0.2   |    tanh    |           92.07          |
