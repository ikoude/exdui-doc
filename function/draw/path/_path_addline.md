---
description: 路径_添加线
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_addline (
    int   hPath,
    float x1,
    float y1,
    float x2,
    float y2
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_addline, 整数型, "libexdui.dll", "_path_addline", 公开, 
    .参数 hPath, 整数型,  , 
    .参数 x1, 小数型,  , 
    .参数 y1, 小数型,  , 
    .参数 x2, 小数型,  , 
    .参数 y2, 小数型,  , 
```

---

### Parameters / 参数

`hPath`

Type: **HPATH**

路径句柄

`x1`

Type: **FLOAT**

起始坐标X

`y1`

Type: **FLOAT**

起始坐标Y

`x2`

Type: **FLOAT**

终点坐标X

`y2`

Type: **FLOAT**

终点坐标Y

---

### Return Value / 返回值

Type: INT32

添加线
