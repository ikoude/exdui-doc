Title: Ex_ObjSetBackgroundImage
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjSetBackgroundImage |  逻辑型 |  libexdui.dll | 10 |  设置组件背景信息 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
handle |  整数型 | - | - |  -|  引擎句柄/组件句柄
lpImage |  整数型 | - | - |  -|  图片指针
dwImageLen |  整数型 | - | - |  -|  图片长度
X |  整数型 | - | - |  -|  偏移X
Y |  整数型 | - | - |  -|  偏移Y
dwRepeat |  整数型 | - | - |  -|  相关常量 BIR_
lpGird |  整数型 | - | - |  -|  九宫矩形指针 (值可为0)
dwFlags |  整数型 | - | - |  -|  相关常量 BIF_
dwAlpha |  整数型 | - | - |  -|  透明度(0-255)
fUpdate |  逻辑型 | - | - |  -|  是否立即刷新
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
BIF_PLAYIMAGE|1|1|播放动画
BIF_DISABLESCALE|2|2|禁用缩放
BIF_GRID_EXCLUSION_CENTER|4|4|九宫矩形-排除中间区域
BIF_POSITION_Y_PERCENT|8|8|X使用百分比单位
BIF_POSITION_X_PERCENT|10|16|Y使用百分比单位
BIR_DEFALUT|0|0|默认(缩放)
BIR_NO_REPEAT|1|1|平铺不重复
BIR_REPEAT|2|2|水平、垂直重复平铺
BIR_REPEAT_X|3|3|水平重复平铺
BIR_REPEAT_Y|4|4|垂直重复平铺

```


### 示例
#### 易语言
```c

```