Title: _rgn_combine
Date: 2019年8月4日11时52分21秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 _rgn_combine |  整数型 |  libexdui.dll | 5 |  | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hRgnSrc |  整数型 | - | - |  -| 
hRgnDst |  整数型 | - | - |  -| 
nCombineMode |  整数型 | - | - |  -|  #RGN_COMBINE_
dstOffsetX |  整数型 | - | - |  -| 
dstOffsetY |  整数型 | - | - |  -| 
```

### 常量列表
```table
常量名   |   常量值(十六进制)(-)   |   常量值(十进制)(-)   |   备注
RGN_COMBINE_UNION|0|0|并集.采用两个区域的并集来合并这两个区域
RGN_COMBINE_INTERSECT|1|1|交集.采用两个区域的交集来合并这两个区域
RGN_COMBINE_XOR|2|2|异或.采用两个区域的并集，且去除重叠区域
RGN_COMBINE_EXCLUDE|3|3|排除.从第一个区域中排除第二个区域

```


### 示例
#### 易语言
```c

```