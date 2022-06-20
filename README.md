# Cycle-Spinning-on-Batch-A-Vicinal-Risk-Minimization-Strategy-for-Automatic-Modulation-Classification

In this paper, we proposed a data augmentation (based on VRM stragtegy) for AMC under the condition of limited samples

We are sorting out the experimental results！

The simulation is based on RML2016A
![image](https://user-images.githubusercontent.com/107237593/173763008-76f95bcd-36f1-4442-a182-97d45fa88739.png)

![image](https://user-images.githubusercontent.com/107237593/173762938-ac2652fd-39a2-4ff0-9ec5-4d0bfb4ee400.png)

#**进度**
#20220615 准确率结果完成，论文主体架构基本完毕
100%的时候Rotate要好于CSoB,CSoB+Rotate，尤其是CSoB+Rotate比CSoB还差，猜测是CSoB+Rotate的是在训练前经过Rotate获得四倍数据，然后在训练中用CSoB导致欠拟合？

#20220616 绘制loss曲线

