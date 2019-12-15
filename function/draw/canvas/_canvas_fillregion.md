---
description: 画布_填充区域
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_fillregion (
    HCANVAS hCanvas,
    HRGN    hRgn,
    HBRUSH  hBrush,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_fillregion, 逻辑型, "libexdui.dll", "_canvas_fillregion", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hRgn, 整数型,  , 
    .参数 hBrush, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hRgn`

Type: **HRGN**

区域句柄

`hBrush`

Type: **HBRUSH**

画刷句柄

---

### Return Value / 返回值

Type: BOOL

填充区域