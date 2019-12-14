---
description: 画布_画路径
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawpath (
    HCANVAS hCanvas,
    HPATH   hPath,
    HBRUSH  hBrush,
    float   strokeWidth,
    int     strokeStyle
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_drawpath, 整数型, "libexdui.dll", "_canvas_drawpath", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hPath, 整数型,  , 
    .参数 hBrush, 整数型,  , 
    .参数 strokeWidth, 小数型,  , 
    .参数 strokeStyle, 整数型,  , 
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

`strokeWidth`

Type: **FLOAT**

描线宽度

`strokeStyle`

Type: **INT32**

描线风格

---

### Return Value / 返回值

Type: BOOL

绘制路径