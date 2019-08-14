Title: Ex_ObjRegister
Date: 2019年8月4日11时52分21秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjRegister |  整数型 |  libexdui.dll | 8 |  注册组件.失败返回0 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
lptszClassName |  整数型 | - | - |  -|  组件类名.最大允许长度:MAX_CLASS_NAME_LEN
dwStyle |  整数型 | - | - |  -|  组件默认风格
dwStyleEx |  整数型 | - | - |  -|  组件默认扩展风格
dwTextFormat |  整数型 | - | - |  -|  相关常量 DT_
cbObjExtra |  整数型 | - | - |  -|  组件额外分配字节数(值可为0)
hCursor |  整数型 | - | - |  -|  组件默认鼠标指针句柄(值可为0)
dwFlags |  整数型 | - | - |  -|  类标志 #ECF_(值可为0)
pfnObjProc |  整数型 | - | - |  -|  组件默认回调
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
DT_LEFT|0|0|
DT_CENTER|1|1|
DT_RIGHT|2|2|
DT_TOP|0|0|
DT_VCENTER|4|4|
DT_BOTTOM|8|8|
DT_WORDBREAK|10|16|
DT_SINGLELINE|20|32|
DT_TABSTOP|80|128|
DT_NOPREFIX|800|2048|
DT_PATH_ELLIPSIS|4000|16384|
DT_WORD_ELLIPSIS|40000|262144|

```


### 示例
#### 易语言
```c

```