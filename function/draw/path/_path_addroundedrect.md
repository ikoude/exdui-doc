---
description: 路径_添加圆角矩形
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_addroundedrect (
    HPATH hPath,
    float left,
    float top,
    float right,
    float bottom,
    float radiusTopLeft,
    float radiusTopRight,
    float radiusBottomLeft,
    float radiusBottomRight,
    int unit
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_addroundedrect, 整数型, "libexdui.dll", "_path_addroundedrect", 公开, 
    .参数 hPath, 整数型,  , 
    .参数 left, 小数型,  , 
    .参数 top, 小数型,  , 
    .参数 right, 小数型,  , 
    .参数 bottom, 小数型,  , 
    .参数 radiusTopLeft, 小数型,  , 
    .参数 radiusTopRight, 小数型,  , 
    .参数 radiusBottomLeft, 小数型,  , 
    .参数 radiusBottomRight, 小数型,  , 
    .参数 unit, 整数型,  , 
```

---

### Parameters / 参数

`hPath`

Type: **HPATH**

路径句柄

`left`

Type: **FLOAT**

矩形左边

`top`

Type: **FLOAT**

矩形顶边

`right`

Type: **FLOAT**

矩形右边

`bottom`

Type: **FLOAT**

矩形底边

`radiusTopLeft`

Type: **FLOAT**

左上角圆角半径

`radiusTopRight`

Type: **FLOAT**

右上角圆角半径

`radiusBottomLeft`

Type: **FLOAT**

左下角圆角半径

`radiusBottomRight`

Type: **FLOAT**

右下角圆角半径

`unit`

Type: **INT32**

单位


---

### Return Value / 返回值

Type: INT32

添加圆角矩形
