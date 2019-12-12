---
description: 画刷_置变换
---

### Syntax / 函数原型

```C++
int __stdcall 
_brush_settransform (
    HBRUSH hBrush,
    INT32 matrix
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _brush_settransform, 整数型, "libexdui.dll", "_brush_settransform", 公开, 
    .参数 hBrush, 整数型,  , 
    .参数 matrix, 整数型,  , 
```

---

### Parameters / 参数

`hBrush`

Type: **HBRUSH**

画刷句柄

`argb`

Type: **INT32**

矩阵

---

### Return Value / 返回值

Type: INT32

