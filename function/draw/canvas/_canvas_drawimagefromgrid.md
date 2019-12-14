---
description: 画布_画图像自网格
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_drawimagefromgrid (
    HCANVAS hCanvas,
    HIMG    hImage,
    float   dstLeft,
    float   dstTop,
    float   dstRight,
    float   dstBottom,
    float   srcLeft,
    float   srcTop,
    float   srcRight,
    float   srcBottom,
    float   gridPaddingLeft,
    float   gridPaddingTop,
    float   gridPaddingRight,
    float   gridPaddingBottom,
    DWORD   dwFlagsfloat
    DWORD   dwAlphafloat
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_drawimagefromgrid, 逻辑型, "libexdui.dll", "_canvas_drawimagefromgrid", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hImage, 整数型,  , 
    .参数 dstLeft, 小数型,  , 
    .参数 dstTop, 小数型,  , 
    .参数 dstRight, 小数型,  , 
    .参数 dstBottom, 小数型,  , 
    .参数 srcLeft, 小数型,  , 
    .参数 srcTop, 小数型,  , 
    .参数 srcRight, 小数型,  , 
    .参数 srcBottom, 小数型,  , 
    .参数 gridPaddingLeft, 小数型,  , 
    .参数 gridPaddingTop, 小数型,  , 
    .参数 gridPaddingRight, 小数型,  , 
    .参数 gridPaddingBottom, 小数型,  , 
    .参数 dwFlags, 整数型,  , 
    .参数 dwAlpha, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hImage`

Type: **HIMG**

图像句柄

`dstLeft`

Type: **FLOAT**

目标位置 左边

`dstTop`

Type: **FLOAT**

目标位置 顶边

`dstRight`

Type: **FLOAT**

目标位置 右边

`dstBottom`

Type: **FLOAT**

目标位置 底边

`srcLeft`

Type: **FLOAT**

源位置 左边

`srcTop`

Type: **FLOAT**

源位置 顶边

`srcRight`

Type: **FLOAT**

源位置 右边

`srcBottom`

Type: **FLOAT**

源位置 底边

`gridPaddingLeft`

Type: **FLOAT**

网格间隙 左边

`gridPaddingTop`

Type: **FLOAT**

网格间隙 顶边

`gridPaddingRight`

Type: **FLOAT**

网格间隙 右边

`gridPaddingBottom`

Type: **FLOAT**

网格间隙 底边

`dwFlags`

Type: **DWORD**

标识 参见 [BIF](../../../const/BIF.md)

`dwAlpha`

Type: **DWORD**

透明度 0-255

---

### Return Value / 返回值

Type: BOOL
