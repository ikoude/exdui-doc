---
description: 画刷_创建
---

### Syntax / 函数原型

```C++
HBRUSH __stdcall 
_brush_create (
    int argb,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _brush_create, 整数型, "libexdui.dll", "_brush_create", 公开, 
    .参数 argb, 整数型,  , 
```

---

### Parameters / 参数

`argb`

Type: **INT32**

ARGB颜色值

---

### Return Value / 返回值

Type: HBRUSH

创建成功 返回画刷句柄
