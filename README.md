# neurips2204

## Requirements

1. The project was implemented and tested in Python 3.5 and Pytorch 0.4. The higher versions should work after minor modification.
2. Other common modules like numpy, pandas and seaborn for visualization.
3. NVIDIA GPU and cuDNN are required to have fast speeds. For now, CUDA 8.0 with cuDNN 6.0.20 has been tested. The other versions should be working.

## Datasets

Our proposed Chinese Character dataset is accessible on [link]


## Implementation details

### data preparation

build train/validation/test sets,

```
make_letter_list.py
make_chinese_list.py
```


### training


### explanation generation



## Time and Space

All experiments were run on NVIDIA TITAN Xp 


model     | #GPUs | train time |
---------|--------|-----|
AlexNet-CNN-baseline     | 1 | ~50min    | 
VGG16-CNN-baseline     | 2 | ~70min    |
Res50-CNN-baseline     | 1 | ~60min    | 
VGG16-HardnessPredictor     | 4 | ~120min   |
Res50-HardnessPredictor     | 2 | ~100min    |
