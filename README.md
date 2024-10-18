## SSNet: Spectral Supplementation Network for Multispectral Pedestrian Detection

### Train and Test

- Prerequisites

　	Basic Python(3.8) package installation.

-  Run test

```python
python test.py
```

- Run train

```python
python test.py
```

### Detection Performance

1. kaist dataset

#### color and thermal 

![image-20241018120048825.png](https://cdn-fusion.imgcdn.store/i/2024/d37d3841abb8b23d.png)

#### only color

![image-20241018120202565.png](https://s2.loli.net/2024/10/18/qf3V8tMiCvcwoXB.png)

#### only thermal

![image-20241018120229326.png](https://cdn-fusion.imgcdn.store/i/2024/df55a07bbc576718.png)

2. llvip dataset

#### only color

![image-20241018120330753.png](https://s2.loli.net/2024/10/18/1pabZAmGsqB6E7i.png)

#### only thermal
![image-20241018120339082.png](https://s2.loli.net/2024/10/18/Gmy5uMOtWceNIJx.png)

 Remarkably, our method surpasses the CFT method by 0.63\% in the mAP metric (mAP50: 97.5, mAP: 63.6), even though the CFT method utilizes both color and thermal modalities simultaneously during the inference phase.
