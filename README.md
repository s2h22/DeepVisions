# DeepVisions_repo

## 1. DeepLabV3+
semantic segmentation \
tf2 \
bb, ResNet50 \
\+ Atrous Spatial Pyramid Pooling

### example
<p align="left">
    <img src="output.png" width=600></br>
</p>

### trained weights
[***model_v2***](https://drive.google.com/file/d/10EBMPQvXulhmMphpqLgsyVX_5YrDVRYs/view?usp=sharing): *top performance among 500 epochs below*
<p align="left">
    <img src="la.png" width=600></br>
</p>

### how to use
```
(1) upload png files to 'images' folder
(2) python main.py
    # add --eval to evaluate the model performance
(3) see the results in 'outputs' folder
```

### to do
- [ ] performance evaluation
- [ ] python packaging
- [ ] package upload
