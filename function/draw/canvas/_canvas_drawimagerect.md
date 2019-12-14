---
description: 画布_画图片矩形
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawimagerect (
    HCANVAS hCanvas,
    HIMG    hImage,
    float   left,
    float   top,
    float   right,
    float   bottom,
    int     alpha
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_drawimagerect, 逻辑型, "libexdui.dll", "_canvas_drawimagerect", 公开,
    .参数 hCanvas, 整数型,  , 
    .参数 hImage, 整数型,  , 
    .参数 left, 小数型,  , 
    .参数 top, 小数型,  , 
    .参数 right, 小数型,  , 
    .参数 bottom, 小数型,  , 
    .参数 alpha, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hImage`

Type: **HIMG**

图像句柄

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

`alpha`

Type: **INT32**

透明度 0-255

---

### Return Value / 返回值

Type: BOOL

绘制图片