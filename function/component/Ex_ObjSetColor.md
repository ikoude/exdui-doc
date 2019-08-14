Title: Ex_ObjSetColor
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjSetColor |  整数型 |  libexdui.dll | 4 |  设置组件相关颜色 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hObj |  整数型 | - | - |  -| 
nIndex |  整数型 | - | - |  -|  相关常量 COLOR_EX_
dwColor |  整数型 | - | - |  -| 
fRedraw |  逻辑型 | - | - |  -|  是否重画
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
COLOR_EX_BACKGROUND|0|0|背景颜色
COLOR_EX_BORDER|1|1|边框颜色
COLOR_EX_TEXT_NORMAL|2|2|文本颜色.正常
COLOR_EX_TEXT_HOVER|3|3|文本颜色.点燃
COLOR_EX_TEXT_DOWN|4|4|文本颜色.按下
COLOR_EX_TEXT_FOCUS|5|5|文本颜色.焦点
COLOR_EX_TEXT_CHECKED|6|6|文本颜色.选中
COLOR_EX_TEXT_SELECT|7|7|文本颜色.选择
COLOR_EX_TEXT_HOT|8|8|文本颜色.热点
COLOR_EX_TEXT_VISTED|9|9|文本颜色.已访问
COLOR_EX_TEXT_SHADOW|A|10|文本颜色.阴影
COLOR_EX_EDIT_CARET|1E|30|编辑框.光标原色
COLOR_EX_EDIT_BANNER|1F|31|编辑框.提示文本颜色

```


### 示例
#### 易语言
```c

```