---
description: 矩阵_变换
---

### Syntax / 函数原型

```C++
bool __stdcall 
_matrix_translate (
    int   *pMatrix,
    float offsetX,
    float offsetY,
    int   order
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _matrix_translate, 逻辑型, "libexdui.dll", "_matrix_translate", 公开, 
    .参数 pMatrix, 整数型,  , 
    .参数 offsetX, 小数型,  , 
    .参数 offsetY, 小数型,  , 
    .参数 order, 整数型,  , 

```

---

### Parameters / 参数

`pMatrix`

Type: **INT32***

矩阵指针

`offsetX`

Type: **FLOAT**

横向偏移

`offsetY`

Type: **FLOAT**

纵向偏移

`order`

Type: **INT32**

顺序

---

### Return Value / 返回值

Type: BOOL

变换矩阵
