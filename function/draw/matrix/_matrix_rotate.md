---
description: 矩阵_旋转
---

### Syntax / 函数原型

```C++
bool __stdcall 
_matrix_rotate (
    int *pMatrix,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _matrix_rotate, 逻辑型, "libexdui.dll", "_matrix_rotate", 公开, 
    .参数 pMatrix, 整数型,  , 
    .参数 fAngle, 小数型,  , 
    .参数 order, 整数型,  , 
```

---

### Parameters / 参数

`pMatrix`

Type: **INT32***

矩阵指针

`fAngle`

Type: **FLOAT**

旋转角度

`order`

Type: **INT32**

顺序

---

### Return Value / 返回值

Type: BOOL

旋转矩阵
