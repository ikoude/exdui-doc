---
description: 区域_合并
---

### Syntax / 函数原型

```C++
int __stdcall 
_rgn_combine (
    HRGN hRgnSrc,
    HRGN hRgnDst,
    int  nCombineMode,
    int  dstOffsetX,
    int  dstOffsetY
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _rgn_combine, 整数型, "libexdui.dll", "_rgn_combine", 公开, 
    .参数 hRgnSrc, 整数型,  , 
    .参数 hRgnDst, 整数型,  , 
    .参数 nCombineMode, 整数型,  ,
    .参数 dstOffsetX, 整数型,  , 
    .参数 dstOffsetY, 整数型,  , 
```

---

### Parameters / 参数

`hRgnSrc`

Type: **HRGN**

源区域句柄

`hRgnDst`

Type: **HRGN**

目标区域句柄

`nCombineMode`

Type: **INT32**

合并模式 参见 [RGN_COMBINE]()

`dstOffsetX`

Type: **INT32**

目标位置横向偏移

`dstOffsetY`

Type: **INT32**

目标位置纵向偏移

---

### Return Value / 返回值

Type: INT32

区域合并
