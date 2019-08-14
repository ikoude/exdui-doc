Title: Ex_ObjSetPos
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjSetPos |  逻辑型 |  libexdui.dll | 7 |  设置组件位置 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hObj |  整数型 | - | - |  -| 
hObjInsertAfter |  整数型 | - | - |  -| 
x |  整数型 | - | - |  -| 
y |  整数型 | - | - |  -| 
width |  整数型 | - | - |  -| 
height |  整数型 | - | - |  -| 
flags |  整数型 | - | - |  -|  相关常量 #SWP_
```


### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
SWP_NOSIZE|1|1|
SWP_NOMOVE|2|2|
SWP_NOZORDER|4|4|
SWP_NOREDRAW|8|8|
SWP_NOACTIVATE|10|16|
SWP_DRAWFRAME|20|32|
SWP_FRAMECHANGED|20|32|
SWP_SHOWWINDOW|40|64|
SWP_HIDEWINDOW|80|128|
SWP_NOCOPYBITS|100|256|
SWP_NOOWNERZORDER|200|512|
SWP_NOSENDCHANGING|400|1024|
SWP_ASYNCWINDOWPOS|4000|16384|
SWP_EX_UPDATEPATH|20000000|536870912|
SWP_EX_UPDATEOBJECT|40000000|1073741824|
SWP_EX_NODPISCALE|80000000|-2147483648|

```

### 示例
#### 易语言
```c

```