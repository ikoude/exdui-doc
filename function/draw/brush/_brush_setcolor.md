---
description: 画刷_置颜色
---

### Syntax / 函数原型

```C++
int __stdcall 
_brush_setcolor (
    HBRUSH hBrush,
    int argb
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _brush_setcolor, 整数型, "libexdui.dll", "_brush_setcolor", 公开, 
    .参数 hBrush, 整数型,  , 
    .参数 argb, 整数型,  , 
```

---

### Parameters / 参数

`hBrush`

Type: **HBRUSH**

画刷句柄

`argb`

Type: **INT32**

ARGB颜色

---

### Return Value / 返回值

Type: INT32

