Title: _layout_absolute_setedge
Date: 2019年8月4日11时52分23秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 _layout_absolute_setedge |  逻辑型 |  libexdui.dll | 5 |  | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hLayout |  整数型 | - | - |  -| 
hObjChild |  整数型 | - | - |  -| 
dwEdge |  整数型 | - | - |  -|  #ELCP_ABSOLUTE_XXX
dwType |  整数型 | - | - |  -| 
nValue |  整数型 | - | - |  -| 
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
ELCP_MARGIN_LEFT|FFFFFFFF|-1|布局属性_通用_外间距_左
ELCP_MARGIN_TOP|FFFFFFFE|-2|布局属性_通用_外间距_顶
ELCP_MARGIN_RIGHT|FFFFFFFD|-3|布局属性_通用_外间距_右
ELCP_MARGIN_BOTTOM|FFFFFFFC|-4|布局属性_通用_外间距_底
ELP_LINEAR_DIRECTION|1|1|布局属性:方向
ELCP_LINEAR_SIZE|1|1|布局子属性:尺寸[-1或未填写为组件当前尺寸]
ELCP_LINEAR_ALIGN|2|2|布局紫属性:另外一个方向的对齐方式
ELP_LINEAR_DALIGN|2|2|布局属性:布局方向对齐方式
ELP_LINEAR_DALIGN_LEFT_TOP|0|0|
ELP_LINEAR_DALIGN_CENTER|1|1|
ELP_LINEAR_DALIGN_RIGHT_BOTTOM|2|2|
ELCP_LINEAR_ALGIN_FILL|0|0|
ELCP_LINEAR_ALIGN_LEFT_TOP|1|1|
ELCP_LINEAR_ALIGN_CENTER|2|2|
ELCP_LINEAR_ALIGN_RIGHT_BOTTOM|3|3|
ELP_DIRECTION_H|0|0|方向:水平
ELP_DIRECTION_V|1|1|方向:垂直
ELP_FLOW_DIRECTION|1|1|布局属性:方向
ELCP_FLOW_SIZE|1|1|布局子属性:尺寸[-1或未填写为组件当前尺寸]
ELCP_FLOW_NEW_LINE|2|2|布局子属性:组件强制换行
ELP_PAGE_CURRENT|1|1|布局属性:当前显示页面索引
ELCP_PAGE_FILL|1|1|布局子属性:是否填充整个布局
ELCP_TABLE_ROW|1|1|布局属性_表格_所在行
ELCP_TABLE_CELL|2|2|布局属性_表格_所在列
ELCP_TABLE_ROW_SPAN|3|3|布局属性_表格_跨行数
ELCP_TABLE_CELL_SPAN|4|4|布局属性_表格_跨列数
ELCP_TABLE_FILL|5|5|布局属性_表格_是否填满
ELCP_RELATIVE_LEFT_OF|1|1|布局属性_相对_左侧于(组件)
ELCP_RELATIVE_TOP_OF|2|2|布局属性_相对_之上于(组件)
ELCP_RELATIVE_RIGHT_OF|3|3|布局属性_相对_右侧于(组件)
ELCP_RELATIVE_BOTTOM_OF|4|4|布局属性_相对_之下于(组件)
ELCP_RELATIVE_LEFT_ALIGN_OF|5|5|布局属性_相对_左对齐于(组件)
ELCP_RELATIVE_TOP_ALIGN_OF|6|6|布局属性_相对_顶对齐于(组件)
ELCP_RELATIVE_RIGHT_ALIGN_OF|7|7|布局属性_相对_右对齐于(组件)
ELCP_RELATIVE_BOTTOM_ALIGN_OF|8|8|布局属性_相对_底对齐于(组件)
ELCP_RELATIVE_CENTER_PARENT_H|9|9|布局属性_相对_水平居中于父
ELCP_RELATIVE_CENTER_PARENT_V|A|10|布局属性_相对_垂直居中于父
ELCP_ABSOLUTE_LEFT|1|1|布局属性_绝对_左侧
ELCP_ABSOLUTE_LEFT_TYPE|2|2|布局属性_绝对_左侧类型
ELCP_ABSOLUTE_TOP|3|3|布局属性_绝对_顶部
ELCP_ABSOLUTE_TOP_TYPE|4|4|布局属性_绝对_顶部类型
ELCP_ABSOLUTE_RIGHT|5|5|布局属性_绝对_右侧
ELCP_ABSOLUTE_RIGHT_TYPE|6|6|布局属性_绝对_右侧类型
ELCP_ABSOLUTE_BOTTOM|7|7|布局属性_绝对_底部
ELCP_ABSOLUTE_BOTTOM_TYPE|8|8|布局属性_绝对_底部类型
ELCP_ABSOLUTE_WIDTH|9|9|布局属性_绝对_宽度（优先级低于右侧）
ELCP_ABSOLUTE_WIDTH_TYPE|A|10|布局属性_绝对_宽度类型
ELCP_ABSOLUTE_HEIGHT|B|11|布局属性_绝对_高度（优先级低于底部）
ELCP_ABSOLUTE_HEIGHT_TYPE|C|12|布局属性_绝对_高度类型
ELCP_ABSOLUTE_OFFSET_H|D|13|布局属性_绝对_水平偏移量
ELCP_ABSOLUTE_OFFSET_H_TYPE|E|14|布局属性_绝对_水平偏移量类型
ELCP_ABSOLUTE_OFFSET_V|F|15|布局属性_绝对_垂直偏移量
ELCP_ABSOLUTE_OFFSET_V_TYPE|10|16|布局属性_绝对_垂直偏移量类型
ELCP_ABSOLUTE_TYPE_UNKNOWN|0|0|布局属性_绝对_类型_未知(未设置或保持不变)
ELCP_ABSOLUTE_TYPE_PX|1|1|布局属性_绝对_类型_像素
ELCP_ABSOLUTE_TYPE_PS|2|2|布局属性_绝对_类型_百分比
ELCP_ABSOLUTE_TYPE_OBJPS|3|3|布局属性_绝对_类型_组件尺寸百分比，仅OFFSET可用

```


### 示例
#### 易语言
```c

```