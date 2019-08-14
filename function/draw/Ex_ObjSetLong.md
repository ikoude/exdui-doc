Title: Ex_ObjSetLong
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ObjSetLong |  整数型 |  libexdui.dll | 3 |  设置组件数值 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hObj |  整数型 | - | - |  -| 
nIndex |  整数型 | - | - |  -|  #EOL_
dwNewLong |  整数型 | - | - |  -| 
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
EOL_NODEID|FFFFFFFF|-1|组件节点ID
EOL_BLUR|FFFFFFFE|-2|组件模糊系数
EOL_OBJPROC|FFFFFFFC|-4|组件回调
EOL_ALPHA|FFFFFFFB|-5|组件透明度
EOL_LPARAM|FFFFFFF9|-7|自定义参数
EOL_OBJPARENT|FFFFFFF8|-8|父句柄
EOL_TEXTFORMAT|FFFFFFF5|-11|组件文本格式
EOL_ID|FFFFFFF4|-12|组件ID
EOL_STYLE|FFFFFFF0|-16|组件基本风格
EOL_HFONT|FFFFFFED|-19|组件字体句柄
EOL_EXSTYLE|FFFFFFEC|-20|组件扩展风格
EOL_USERDATA|FFFFFFEB|-21|用户数据
EOL_HCANVAS|FFFFFFEA|-22|画布句柄（不要乱改）
EOL_OWNER|FFFFFFE9|-23|控件数据（不要乱改）
EOL_STATE|FFFFFFE8|-24|组件状态
EOL_LPWZTITLE|FFFFFFE4|-28|组件标题内容指针
EOL_CURSOR|FFFFFFEF|-17|光标句柄

```


### 示例
#### 易语言
```c

```