# Deep Learning Dictionary

Written by Yixiong Ding / YixiongDing@Gmail.com
June, 2022
_ _ _
## F
### Feature Pyramid Network (FPN) 特征金字塔网络
1. 目标检测卷积结构类型
2. 

## P

### Prymaid Network
1. 目标检测算法常用结构
2. 通过将输入图像缩放到不同尺度的大小构成了图像金字塔。然后将这些不同尺度的特征输入到网络中（可以共享参数也可以独立参数）
3. 得到每个尺度的检测结果，然后通过NMS等后处理手段进行预测结果的处理。
4. 图像金字塔最大的问题是推理速度慢了几倍，一个是因为要推理的图像数多了几倍，另一个原因是要检测小目标势必要放大图像。