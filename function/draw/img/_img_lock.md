Title: _img_lock
Date: 2019年8月4日11时52分21秒


### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 _img_lock |  整数型 |  libexdui.dll | 5 |  锁定图像.成功返回0. | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hImg |  整数型 | - | - |  -| 
lpRectL |  整数型 | - | - |  -|  锁定矩形指针，如果为0，则锁定整张图像。
flags |  整数型 | - | - |  -|  READ:1 / WRITE:2 / READ&WRITE:3
PixelFormat |  整数型 | - | - |  -|  参考:https://msdn.microsoft.com/en-us/library/ms534412(v=vs.85).aspx
lpLockedBitmapData |  EX_BITMAPDATA | - | - |  -|  BITMAPDATA
```




### 示例
#### 易语言
```c

```