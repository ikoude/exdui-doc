---
description: 画布_画矩形
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawrect (
    HCANVAS hCanvas,
    HBRUSH  hBrush,
    float   left,
    float   top,
    float   right,
    float   bottom,
    float   strokeWidth,
    int     strokeStyle
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_drawrect, 逻辑型, "libexdui.dll", "_canvas_drawrect", 公开, ok
    .参数 hCanvas, 整数型,  , 
    .参数 hBrush, 整数型,  , 
    .参数 left, 小数型,  , 
    .参数 top, 小数型,  , 
    .参数 right, 小数型,  , 
    .参数 bottom, 小数型,  , 
    .参数 strokeWidth, 小数型,  , 
    .参数 strokeStyle, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HANDLE**

画布句柄

`hBrush`

Type: **HANDLE**

画刷句柄

`left`

Type: **FLOAT**

左边

`top`

Type: **FLOAT**

顶边

`right`

Type: **FLOAT**

右边

`bottom`

Type: **FLOAT**

底边

`strokeWidth`

Type: **FLOAT**

描线宽度

`strokeStyle`

Type: **INT32**

描线风格

---

### Return Value / 返回值

Type: BOOL

绘制矩形