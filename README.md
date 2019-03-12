# myMLPro
>  作为一只机器学习小白，这里存放个人实战项目（toy-project）。主要目的是整理一下使用过的模型和一  > 些小念头
>
> 存放格式：
>
> 1. 文件夹按项目划分；
> 2. 每次添加新项目需要在下文用大标题区分，并简要说明，如简介，学习目的，模型结果；
> 3. 每次添加或者更新Readme时，加上日期，如 2019-02-26 14 : 38
> 4. 尽量用英语表达；
> 5. 若项目较小，直接注明项目概要 + 日期即可。



## Linear Model in PM2.5 Prediction

>  Date：from 2019-02-26 15：05 to 2019-02-28 00:04

### Introduction
In this project, I'm required to develop a linear model to finish the task -- PM2.5 Prediction. The project's description is from the hw1 in NTU 19-ML course. Click the [link](https://ntumlta2019.github.io/ml-web-hw1/) to get the detail.

### Goal
* master the data processing method with numpy and pandas
* extract the feature and label
* train linear regression model with gradient descent method
* visualize the data and show the correlation.
  

### Result
I design a linear regression class based on gradient descent method(GD). But it encoutered Nan data in train, it could not fit normal. 
Finaly, I use sklearn.linear_regression to train and predict. Maybe I think I have to check the sklearn source code. 
![](https://raw.githubusercontent.com/JoshuaQYH/blogImage/master/20190228002703.png)



----
## Some tutorials on pytorch's official site. On 5th, March, 2019
----
## Predict the house price in Boston with AdaBoost.  On 8th, March, 2019
----
## Monte carlo method. On 11st, March, 2019
With the monte carlo method, I calculate the value of pi/4, single and double integral. 
![](https://raw.githubusercontent.com/JoshuaQYH/blogImage/master/img/20190312001417.png)
![](https://raw.githubusercontent.com/JoshuaQYH/blogImage/master/img/20190312001458.png)
![](https://raw.githubusercontent.com/JoshuaQYH/blogImage/master/img/20190312001518.png)
