Title: Ex_TrackPopupMenu
Date: 2019年8月4日11时52分22秒

### 弹出菜单
> 在当前鼠标位置或指定坐标位置显示弹出式菜单

### 声明
```table
动态库命令(-)   |   返回值类型(-)   |   库文件名(-)   |   参数量(-)   |   备注(-)
Ex_TrackPopupMenu   |   逻辑型   |   libexdui.dll   |   9   |   弹出菜单
```

### 参数列表
```table
参数名(<)   |   类型(-)   |   参考(-)   |   可空（NULL）(-)   |   备注(-)
hMenu   |   整数型   |   -   |   ×   |   菜单句柄
uFlags   |   整数型   |   -   |   ×   |   消息类型，相关常量 TPM_
x   |   整数型   |   -   |   ×   |   水平显示位置，相对于屏幕位置
y   |   整数型   |   -   |   ×   |   垂直显示位置，相对于屏幕位置
nReserved   |   整数型   |   -   |   ×   |   保留参数，可忽略
handle   |   整数型   |   -   |   ×   |   组件句柄/引擎句柄/窗口句柄.(如果该值为窗口句柄且窗口未使用引擎渲染,则以默认菜单弹出)
lpRc   |   整数型   |   -   |   √   |   Rc资源，可忽略
pfnCallback   |   整数型   |   -   |   ×   |   回调函数，详见Callback说明
dwFlags   |   整数型   |   -   |   ×   |   标记，相关常量 EMNF_
```
### 回调函数 (Callback)
#### 函数原型
> (BOOL)MsgProc(hWnd,hExDui,uMsg,wParam,lParam,lpResult)

```table
回调函数(-)   |   返回值类型(-)   |   库文件名(-)   |   参数量(-)   |   备注(-)
MsgProc   |   逻辑型   |   libexdui.dll   |   6   |   消息回调函数
```
### 参数列表(MsgProc)
```table
参数名(<)   |   类型(-)   |   参考(-)   |   可空（NULL）(-)   |   备注(-)
hWnd   |   整数型   |   -   |   -   |   窗口句柄
hExDui   |   整数型   |   -   |   -   |   引擎句柄
uMsg   |   整数型   |   -   |   -   |   消息
wParam   |   整数型   |   -   |   -   |   附加参数一
lParam   |   整数型   |   -   |   -   |   附加参数二
lpResult   |   整数型   |   √   |   -   |   保留参数，可忽略
```
### 常量列表(TPM)
```table
常量名(-)   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注(-)
TPM_CENTERALIGN   |   0x0004L   |      |   相对于x参数指定的坐标水平居中快捷菜单
TPM_LEFTALIGN   |   0x0000L   |      |   定位快捷菜单，使其左侧与x参数指定的坐标对齐。
TPM_RIGHTALIGN   |   0x0008L   |      |   定位快捷菜单，使其右侧与x参数指定的坐标对齐
-   |   -   |   -   |   -
TPM_BOTTOMALIGN   |   0x0020L   |      |   定位快捷菜单，使其底部与y参数指定的坐标对齐。
TPM_TOPALIGN   |   0x0000L   |      |   定位快捷菜单，使其顶部与y参数指定的坐标对齐。
TPM_VCENTERALIGN   |   0x0010L   |      |   相对于y参数指定的坐标垂直居中快捷菜单
-   |   -   |   -   |   -
TPM_NONOTIFY|0x0080L||当用户单击菜单项时，该功能不会发送通知消息。
TPM_RETURNCMD|0x0100L||该函数在返回值中返回用户选择的菜单项标识符。
-   |   -   |   -   |   -
TPM_LEFTBUTTON|0x0000L||用户可以仅用鼠标左键选择菜单项。
TPM_RIGHTBUTTON|0x0002L||用户可以使用鼠标左键和右键选择菜单项。
TPM_HORNEGANIMATION | 0x0800L | |从右到左动画菜单。
TPM_HORPOSANIMATION | 0x0400L | | 从左到右动画菜单。
TPM_NOANIMATION|0x4000L||显示没有动画的菜单。
TPM_VERNEGANIMATION|0x2000L||从下到上动画菜单。
TPM_VERPOSANIMATION|0x1000L||从上到下动画菜单。
```
> 附：[Microsoft API DOCS](https://docs.microsoft.com/zh-cn/windows/win32/api/winuser/nf-winuser-trackpopupmenu)


### 常量列表(EMNF)

```table
常量名(-)   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注(-)
EMNF_NOSHADOW   |   -   |   -2147483648   |   不显示菜单阴影
```
