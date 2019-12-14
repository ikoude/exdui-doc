---
description: 画布_画直线
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawline (
    HCANVAS hCanvas,
    HBRUSH  hBrush,
    float   X1,
    float   Y1,
    float   X2,
    float   Y2,
    float   strokeWidth,
    int     strokeStyle
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_drawline, 逻辑型, "libexdui.dll", "_canvas_drawline", 公开,
    .参数 hCanvas, 整数型,  , 
    .参数 hBrush, 整数型,  , 
    .参数 X1, 小数型,  , 
    .参数 Y1, 小数型,  , 
    .参数 X2, 小数型,  , 
    .参数 Y2, 小数型,  , 
    .参数 strokeWidth, 小数型,  , 
    .参数 strokeStyle, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hBrush`

Type: **HBRUSH**

画刷句柄

`X1`

Type: **FLOAT**

A点坐标 X

`Y1`

Type: **FLOAT**

A点坐标 Y

`X2`

Type: **FLOAT**

B点坐标 X

`Y2`

Type: **FLOAT**

B点坐标 Y

`strokeWidth`

Type: **FLOAT**

描线宽度

`strokeStyle`

Type: **INT32**

描线风格

---

### Return Value / 返回值

Type: BOOL

绘制直线