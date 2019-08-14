Title: Ex_ObjHandleEvent
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjHandleEvent |  逻辑型 |  libexdui.dll | 3 |  挂接组件事件回调 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hObj |  整数型 | - | - |  -| 
nEvent |  整数型 | - | - |  -|  #NM_
pfnCallback |  整数型 | - | - |  -|  (Bool) Handler(hObj
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
NM_CREATE|FFFFFF9D| -99| 事件_创建
NM_DESTROY|FFFFFF9E| -98| 事件_销毁
NM_CALCSIZE|FFFFFF9F| -97| 事件_计算尺寸
NM_MOVE|FFFFFFA0| -96| 事件_鼠标移动
NM_SIZE|FFFFFFA1| -95| 事件_尺寸被改变
NM_ENABLE|FFFFFFA2| -94| 事件_禁止状态被改变
NM_SHOW|FFFFFFA3| -93| 事件_可视状态被改变
NM_LUP|FFFFFFA4| -92| 事件_左键被放开
NM_LEAVE|FFFFFFA5| -91| 事件_离开组件
NM_TIMER|FFFFFFA6| -90| 事件_时钟
NM_CHECK|FFFFFFA7| -89| 事件_选中
NM_TRAYICON|FFFFFFA8| -88| 事件_托盘图标
NM_INTDLG|FFFFFFA9| -87| 事件_对话框初始化完毕
NM_EASING|FFFFFFAA| -86| 事件_缓动
NM_CLICK|FFFFFFFE| -2| 事件_左键被单击
NM_DBLCLK|FFFFFFFD| -3| 事件_左键被双击
NM_RETURN|FFFFFFFC| -4| 事件_回车键被按下
NM_RCLICK|FFFFFFFB| -5| 事件_右键被单击
NM_RDBLCLK|FFFFFFFA| -6| 事件_右键被双击
NM_SETFOCUS|FFFFFFF9| -7| 事件_设置焦点
NM_KILLFOCUS|FFFFFFF8| -8| 事件_失去焦点
NM_CUSTOMDRAW|FFFFFFF4| -12| 事件_自定义绘制
NM_HOVER|FFFFFFF3| -13| 事件_进入组件
NM_NCHITTEST|FFFFFFF2| -14| 事件_点击测试
NM_KEYDOWN|FFFFFFF1| -15| 事件_按下某键
NM_RELEASEDCAPTURE|FFFFFFF0| -16| 事件_取消鼠标捕获
NM_CHAR|FFFFFFEE| -18| 事件_字符输入
NM_TOOLTIPSCREATED|FFFFFFED| -19| 事件_提示框即将弹出
NM_LDOWN|FFFFFFEC| -20| 事件_左键被按下
NM_RDOWN|FFFFFFEB| -21| 事件_右键被按下
NM_FONTCHANGED|FFFFFFE9| -23| 事件_字体被改变

```


### 示例
#### 易语言
```c

```