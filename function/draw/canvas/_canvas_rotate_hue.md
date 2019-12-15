---
description: 画布_旋转色相
---

### Syntax / 函数原型

```C++
BOOL __stdcall 
_canvas_rotate_hue (
    HCANVAS hCanvas,
    float   fAngle
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_rotate_hue, 逻辑型, "libexdui.dll", "_canvas_rotate_hue", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 fAngle, 小数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`fAngle`

Type: **FLOAT**

HUE色相角度 0-360°

---

### Return Value / 返回值

Type: BOOL

旋转色相