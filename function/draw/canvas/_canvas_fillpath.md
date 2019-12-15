---
description: 画布_填充路径
---

### Syntax / 函数原型

```C++
int __stdcall 
_canvas_fillpath (
    HCANVAS hCanvas,
    HPATH   hPath,
    HBRUSH  hBrush
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_fillpath, 整数型, "libexdui.dll", "_canvas_fillpath", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hPath, 整数型,  , 
    .参数 hBrush, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hPath`

Type: **HPATH**

路径句柄

`hBrush`

Type: **HBRUSH**

画刷句柄

---

### Return Value / 返回值

Type: INT32

填充路径