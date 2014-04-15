# 航模 & 航拍
聂勇｜[nieyong](https://github.com/nieyong)



## 内容概述
飞行器基本原理

多轴飞行器（Multi-Rotor Copter）

航拍（Aerial Photography）



## 飞行器基本理论基础
* 伯努利原理
* 纳维－斯托克斯方程（Navier-Stokes equations，又叫做NS方程）



## 伯努利原理
等高流动时，流速大，压力就小。

<img src="img-lug/bernoulli_1.png" height="40%"/>
<img src="img-lug/bernoulli_2.png" height="40%"/>

题外话：上旋球／香蕉球



## NS方程
<img src="img-lug/ns.png"/>



## NS方程
NS方程是一组描述像液体和空气这样的流体物质的方程。这些方程建立了流体的粒子动量的改变率(加速度)和作用在液体内部的压力的变化和耗散粘滞力(类似于摩擦力)以及引力之间的关系。

<img src="img-lug/ns equation 02.png" width="75%"/>



## NS方程
处理厄尔尼诺全球性气象系统或机翼的升力等问题，NS方程的解必须借助计算机。这本身是一个科学领域，称为计算流体力学。

<img src="img-lug/ns equation 03.png" height="40%"/>
<img src="img-lug/ns equation 01.png" height="40%"/>



## Boeing
<img src="img-lug/plane.png" />

Boeing 767-300ER



## 直升机--单桨机
单桨机：主桨＋竖尾桨。竖尾桨用于抵消主桨的旋转扭力，以及机头的转向。

<img src="img-lug/wuzhi10.jpg" width="60%"/>

国产武直10（珠海航展／2012年11月）



## 直升机--双桨机
双桨机：上桨＋下桨＋平尾桨。平尾桨用于飞机的前进和后退。

<img src="img-lug/shuangjiangji.jpeg" width="70%"/>



## 二通／三通／三通半...
* 二通：只能上下飞
* 三通：上下，前后，左右砖头
* 三通半：大家称为伪四通，添加两个侧桨实现侧飞
* 四通：上下、前后、左右转头、左右侧飞
* ...



## 多轴飞行器的组成部分
* 主控模块
    * 传感器数据采集（加速度／角速度／GPS等）
    * 姿态控制算法
* 无刷电机/电调/电池/机架
* 遥控器组件
    * 遥控器，国内性价比高的是天地飞



## 主控模块（1）

开源的，DIY强的主控模

[arducopter](https://code.google.com/p/arducopter/)
[ardupilot](https://code.google.com/p/ardupilot/)

based on the Arduino open-source hardware platfor

<img src="img-lug/arduino.jpg" height="30%"/>
<img src="img-lug/arducopter_pcb1.jpg" height="30%"/>

