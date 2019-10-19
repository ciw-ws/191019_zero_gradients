# 191019_zero_gradients
#### Description for this repo
*	example code of zeroing gradients

### Run commands
```
python main.py --workers 16 --epochs 30 --batch-size 256 --lr 0.0001 --arch resnet34 --gpu 0 --pretrained /path/to/imagenet/
```

### References
*   https://github.com/pytorch/examples/tree/master/imagenet