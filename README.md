# LSE-Net
A fast and approximated implementation of the proposed local semantic enhanced ConvNet

### Introduction
Local Semantic Enhanced ConvNet (LSE-Net) is one of our recent works, which aims to build a robust feature representation for aerial scene recognition.
Aerial scenes are usually more complicated in terms of the object distribution and spatial arrangement due to the bird view of sensors and the complexity of land covers.
Current convolutional neural networks (CNNs) are powerful to preserve the global semantic information for scenes, but are not sufficient enough to stress the contribution of key local regions (also known as region of interest, ROI).
This work aims to solve this bottleneck, and is under the second-round review for the IEEE Transactions on Image Processing. The technical contribution is summarized as follows.
  - We propose a local semantic enhanced ConvNet (LSE-Net) for aerial scene classification. This end-to-end framework has a larger receptive field to fully perceive the key local regions from different semantic categories, and boosts the aerial scene understanding capability.
  - We propose a local semantic perception module. After the convolutional feature extraction, it simultaneously highlights the high feature response of key local semantics and rates their importance on the aerial scene so that a more dedicated local semantic representation is built.
  - We propose a context-aware class peak response (CACPR) measurement to mimic the top-down human vision perception while taking the abundant context information into account.

### Network Structure
It will be updated depending upon acceptance.

### Effectiveness on highlighting the RoIs

Some visualized samples are offered as below.

![avatar](/Fig1.png)

![avatar](/Fig2.png)

### Development Environment
```
Python > 3.5

Tensorflow > 1.6

opencv>3

numpy>1.16
```

### How to run our code
It will be updated depending upon acceptance.

# Citation

If you find this project useful, or use the source code from this project, please consider citing our work as
```
@ARTICLE{Bi2021LSENet,
  author={Bi, Qi and Qin, Kun and Zhang, Han and Xia, Gui-Song},
  journal={IEEE Transactions on Image Processing}, 
  title={Local Semantic Enhanced ConvNet for Aerial Scene Recognition}, 
  year={2021},
  volume={30},
  number={},
  pages={6498-6511},
  doi={10.1109/TIP.2021.3092816}
  }
```


# Contact Information

Qi Bi

q_bi@whu.edu.cn   2009biqi@163.com
