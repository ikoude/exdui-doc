---
description: 区域_创建自圆角矩形
---

### Syntax / 函数原型

```C++
HRGN __stdcall 
_rgn_createfromroundrect (
    float left,
    float top,
    float right,
    float bottom,
    float radiusX,
    float radiusY
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _rgn_createfromroundrect, 整数型, "libexdui.dll", "_rgn_createfromroundrect", 公开, 
    .参数 left, 小数型,  , 
    .参数 top, 小数型,  , 
    .参数 right, 小数型,  , 
    .参数 bottom, 小数型,  , 
    .参数 radiusX, 小数型,  , 
    .参数 radiusY, 小数型,  , 
```

---

### Parameters / 参数

`left`

Type: **FLOAT**

区域左边

`top`

Type: **FLOAT**

区域顶边

`right`

Type: **FLOAT**

区域右边

`bottom`

Type: **FLOAT**

区域底边

`radiusX`

Type: **FLOAT**

圆角横向半径

`radiusY`

Type: **FLOAT**

圆角纵向半径

---

### Return Value / 返回值

Type: HRGN

区域创建自圆角矩形
