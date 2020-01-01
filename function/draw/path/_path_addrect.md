---
description: 路径_添加矩形
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_addrect (
    HPATH hPath,
    float left,
    float top,
    float right,
    float bottom
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_addrect, 整数型, "libexdui.dll", "_path_addrect", 公开, 
    .参数 hPath, 整数型,  , 
    .参数 left, 小数型,  , 
    .参数 top, 小数型,  , 
    .参数 right, 小数型,  , 
    .参数 bottom, 小数型,  , 
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

---

### Return Value / 返回值

Type: INT32

添加矩形
