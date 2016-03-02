##简介

GY-85九轴惯性传感器模块的使用，实时绘制加速度、角速度、方位数据。

##使用说明
+ 本程序为上位机的处理程序，从串口com2接收下位机的数据，进行数据还原与校准处理，绘制实时数据曲线。
+ 图1、2、3为加速度x、y、z的数据，图4、5、6为角速度x、y、z的数据，图7为磁力计的y、z计算出的角度（认为x轴与地面垂直），图8为方向的指示。
+ 本程序需要与下位机的采集配合使用，下位机可以使用单片机，控制GY-85模块数据的采集与传输，这方面的资料网上很多。
+ 本科毕业设计的的一小部分，调试无误，但写的比较乱，仅供参考，敬请谅解。