---
description: 画布_填充椭圆
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_fillellipse (
    HCANVAS hCanvas,
    HBRUSH  hBrush,
    float   x,
    float   y,
    float   radiusX,
    float   radiusY
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_fillellipse, 逻辑型, "libexdui.dll", "_canvas_fillellipse", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hBrush, 整数型,  , 
    .参数 x, 小数型,  , 
    .参数 y, 小数型,  , 
    .参数 radiusX, 小数型,  , 
    .参数 radiusY, 小数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

xxx

`hBrush`

Type: **HBRUSH**

画刷句柄

`x`

Type: **FLOAT**

椭圆圆心X坐标

`y`

Type: **FLOAT**

椭圆圆心Y坐标

`radiusX`

Type: **FLOAT**

椭圆X半径

`radiusY`

Type: **FLOAT**

椭圆Y半径

---

### Return Value / 返回值

Type: BOOL

填充椭圆