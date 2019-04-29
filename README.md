# XiaoMi-Ruby-15.6-2019
## This is a repository of Hackintosh EFI/Clover files about the [MI laptop Ruby 2019](https://www.mi.com/mibook/ruby15-2019mx110/specs/).<br/>这是一个关于 [小米笔记本 Ruby 2019 款](https://www.mi.com/mibook/ruby15-2019mx110/specs/) 的 黑苹果 EFI/Clover 文件的存储库。

### 我的电脑配置

| 规格     | 详细信息                                   							  	|
| -------- | -----------------------------------------------------------				|
| 电脑型号 | 小米笔记本 Ruby 15.6" 2019款 独显款(UHD 620 + MX 110)      				|
| 处理器   | Intel(R) Core(TM) i5-8250U                      							|
| 内存     | SK hynix 16GB DDR4 2400MHz												|
| 硬盘     | KINGSTON MS80000058688  (238 GB)	M.2(SATA)								|
| 集成显卡 | Intel(R) UHD Graphics 620  (1 GB)           			   					|
| 显示器   | 中电熊猫 ID	NCP002A 1920x1080 IPS 15.6"									|
| 声卡     | Realtek ALC256 (M) (节点:13) 												|
| 网卡     | 无线：Qualcomm AR956x (DW1707)	有线：Realtek RTL 8168B						|
| 触控板   | I2C HID 																	|
| 照相机   | XiaoMi USB 2.0 WebCam 														|
| 读卡器   | Realtek USB 2.0 Card Reader 												|


## 介绍
系统版本 10.14.4

2019年4月26日
搞了一周时间，终于搞定了部分功能。  
实在是个人能力有限。 下面说一下 可以工作的部分  和  不能工作的部分。  
更换了无线网卡。  
最后希望有大佬能完善一下。  

2019年4月30日
有大佬帮忙完善了！ 再次谢谢大佬！  
欢迎各位反馈我没遇到的问题！

### 可以工作
#### 核显
双屏显示内屏不亮  （睡眠一次 内屏显示正常）  
驱动方法 仿冒 HD 620 即可
#### 蓝牙
从Windows / Linux 启动 可正常使用 冷启动无效
#### 无线
正常驱动 驱动方法见 (我的博客)[https://jxh98.github.io/2019/04/18/Hackintosh/]
#### 有线
正常驱动
#### 电量
电量显示正常 充电状态正常
#### 声卡
耳机麦克风 和  内置麦克风 正常
#### 开机 关机 重启
正常
#### 睡眠
可能不正常
#### 内置键盘触控板 正常
触控可以手势
#### USB接口 
大概正常

### 不能工作

#### 扬声器 ALC256 (M)
尝试驱动未成功




