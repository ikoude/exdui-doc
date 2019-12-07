Title: Ex_ResGetFileFromAtom
Date: 2019年8月4日11时52分22秒

### 声明


```table
动态库命令(-) | 返回值类型(-) |   库文件名(-) | 参数量(-) | 备注(-)

 Ex_ResGetFileFromAtom |  逻辑型 |  libexdui.dll | 4 |  获取资源文件 | 
```


### 参数列表

```table
参数名   |   类型(-)   |   传址(-)   |   数组(-)   |   可空（NULL）(-)   |   备注   |
hRes |  整数型 | - | - |  -| 
atomPath |  整数型 | - | - |  -| 
lpFile |  整数型 | ★ | - |  -|  [out]文件数据指针.用户不应该释放该内存.
dwFileLen |  整数型 | ★ | - |  -|  [out]文件尺寸.
```




### 示例
#### 易语言
```c

```