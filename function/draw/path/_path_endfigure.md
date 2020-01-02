---
description: 路径_结束当前图形
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_endfigure (
    HPATH hPath,
    bool  fCloseFigure
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_endfigure, 整数型, "libexdui.dll", "_path_endfigure", 公开, 结束当前图形
    .参数 hPath, 整数型,  , 
    .参数 fCloseFigure, 逻辑型,  , 
```

---

### Parameters / 参数

`hPath`

Type: **HPATH**

路径句柄

`fCloseFigure`

Type: **BOOL**

是否需要闭合图形

---

### Return Value / 返回值

Type: INT32

结束当前图形
