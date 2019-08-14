Title: Ex_ObjCreateEx
Date: 2019年8月4日11时52分21秒


### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjCreateEx |  整数型 |  libexdui.dll | 14 |  创建组件. | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
dwStyleEx |  整数型 | - | - |  -|  组件扩展风格 相关常量 EOS_EX_
lptszClassName |  整数型 | - | - |  -|  组件类名
lptszObjTitle |  整数型 | - | - |  -|  组件标题
dwStyle |  整数型 | - | - |  -|  组件风格 相关常量 EOS_
x |  整数型 | - | - |  -|  左边
y |  整数型 | - | - |  -|  顶边
width |  整数型 | - | - |  -|  宽度
height |  整数型 | - | - |  -|  高度
hParent |  整数型 | - | - |  -|  父组件句柄
nID |  整数型 | - | - |  -| 
dwTextFormat |  整数型 | - | - |  -|  相关常量 DT_
lParam |  整数型 | - | - |  -|  附加参数
hTheme |  整数型 | - | - |  -|  主题句柄.0为默认
lpfnMsgProc |  整数型 | - | - |  -|  (BOOL)MsgProc(hWnd
```

### 常量列表(EOS)
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
EOS_DISABLENOSCROLL|2000000|33554432|组件风格_滚动条不可用时显示禁止状态
EOS_SIZEBOX|4000000|67108864|组件风格_可调整尺寸
EOS_DISABLED|8000000|134217728|组件风格_禁止
EOS_VISIBLE|10000000|268435456|组件风格_可视
EOS_BORDER|20000000|536870912|组件风格_边框
EOS_VSCROLL|40000000|1073741824|组件风格_水平滚动条
EOS_HSCROLL|80000000|-2147483648|组件风格_垂直滚动条
EOS_EX_AUTOSIZE|400000|4194304|组件风格_扩展_自适应尺寸
EOS_EX_TRANSPARENT|800000|8388608|组件风格_扩展_鼠标穿透
EOS_EX_DRAGDROP|2000000|33554432|组件风格_扩展_允许拖拽
EOS_EX_ACCEPTFILES|4000000|67108864|组件风格_扩展_接收文件拖放
EOS_EX_FOCUSABLE|8000000|134217728|组件风格_扩展_允许焦点
EOS_EX_TABSTOP|10000000|268435456|组件风格_扩展_允许TAB焦点
EOS_EX_TOPMOST|20000000|536870912|组件风格_扩展_总在最前
EOS_EX_COMPOSITED|40000000|1073741824|组件风格_扩展_背景混合
EOS_EX_CUSTOMDRAW|80000000|-2147483648|组件风格_扩展_自定义绘制
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