---
description: 矩阵_缩放
---

### Syntax / 函数原型

```C++
bool __stdcall 
_matrix_scale (
    int *pMatrix,
    float scaleX,
    float scaleY,
    int order
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _matrix_scale, 逻辑型, "libexdui.dll", "_matrix_scale", 公开, 
    .参数 pMatrix, 整数型,  , 
    .参数 scaleX, 小数型,  , 
    .参数 scaleY, 小数型,  , 
    .参数 order, 整数型,  , 
```

---

### Parameters / 参数

`pMatrix`

Type: **INT32***

矩阵指针

`scaleX`

Type: **FLOAT**

横向缩放倍数

`scaleY`

Type: **FLOAT**

纵向缩放倍数

`order`

Type: **INT32**

顺序

---

### Return Value / 返回值

Type: BOOL

缩放矩阵
