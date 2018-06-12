# Finetune-pytorch
Finetune using pytorch

## Finetune [Food-101](https://www.vision.ee.ethz.ch/datasets_extra/food-101/) Dataset using ResNet

### Dependencies
- python 2.7
- pytorch 0.4

### Training
```
python resnet101_v3.py
```

### Prediction
reminder: change your own directory path
```
python resnet101_test.py
```

### Results

Network  | Test Accuracy |
:-------:|:-------------:|
ResNet50 |0.844|
ResNet101| 0.869|
ResNet152|0.868|

- Some prediction examples:
![examples](images/examples.png)

- state of art
reported from [Wide-Slice Residual Networks for Food Recognition](https://arxiv.org/abs/1612.06543)
![state of art](images/state_of_art.png)



