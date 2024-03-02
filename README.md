# 项目说明

这是一个简单迷你的测距模块，使用EPS32-PICO-D4这种全集成的芯片，借助淘宝上的小小传感器，实现一个比较迷你可爱的测距模块。

## 测距模块说明

给某宝上这种测距模块做的通用安装，价格大概十几块钱，一般是VL53LXX系列，走的是I2C协议，大家可以自己不同的测距模块改一下布局。我用的是VL53L0X，这是参数，我实际测试高精度模式下，最小距离只能到100mm。还有很多种不同的传感器，一般距离大概在50~5000mm之间。

## 软件说明

esp32走的Arduino，毕竟这种简单的需求给Arduino真是太方便了。安卓的话本来打算用熟悉的Flutter开发的，结果那个蓝牙库效果有点不理想，所以还是用的原生开发，还不是很熟悉🥲。

## 开源地址

[https://github.com/MeowHardware/Wireless-TOF](https://github.com/MeowHardware/Wireless-TOF)
[https://oshwhub.com/kjpig/wirelessds](https://oshwhub.com/kjpig/wirelessds)
