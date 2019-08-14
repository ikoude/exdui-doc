Title: _layout_absolute_lock
Date: 2019年8月4日11时52分23秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 _layout_absolute_lock |  逻辑型 |  libexdui.dll | 8 |  按当前位置锁定 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hLayout |  整数型 | - | - |  -| 
hObjChild |  整数型 | - | - |  -| 
tLeft |  整数型 | - | - |  -|  #ELCP_ABSOLUTE_XXX_TYPE 下同
tTop |  整数型 | - | - |  -| 
tRight |  整数型 | - | - |  -| 
tBottom |  整数型 | - | - |  -| 
tWidth |  整数型 | - | - |  -| 
tHeight |  整数型 | - | - |  -| 
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
ELCP_ABSOLUTE_TOP_TYPE|4|-|布局属性_绝对_顶部类型|
ELCP_ABSOLUTE_RIGHT_TYPE|6|-|布局属性_绝对_右侧类型|
ELCP_ABSOLUTE_BOTTOM_TYPE|8"|-|布局属性_绝对_底部类型|
ELCP_ABSOLUTE_WIDTH_TYPE|10|-|布局属性_绝对_宽度类型|
ELCP_ABSOLUTE_HEIGHT_TYPE|12|-|布局属性_绝对_高度类型|
ELCP_ABSOLUTE_OFFSET_H_TYPE|14|-|布局属性_绝对_水平偏移量类型|
ELCP_ABSOLUTE_OFFSET_V_TYPE|16|-|布局属性_绝对_垂直偏移量类型|

```


### 示例
#### 易语言
```c

```