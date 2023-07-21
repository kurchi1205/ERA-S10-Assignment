# ERA-S10-Assignment

# Objective
To train custom ResNet architecture for CIFAR10 using some augmentation strategies and One cycle LR Policy and achieving 90% accuracy.

# File Structure

```bash
  ├── __init__.py             
  ├── custom_resnet.py        # resnet model
  ├── data.py                 # train and test data formation
  ├── utils_train.py          # training and testing utilities
  ├── training.ipynb          # train the resnet model
  └── README.md
```

# Model
Parameters: 6,573,130

# Scheduler
- default lr = 0.01
- Max lr found = 1.59E-02
- min lr = Max lr/10

# Accuracy achieved:
- train acc: 99.30%
- val acc: 90.29%



