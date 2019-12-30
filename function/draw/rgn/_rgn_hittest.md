---
description: 区域_命中测试
---

### Syntax / 函数原型

```C++
bool __stdcall 
_rgn_hittest (
    HRGN hRgn,
    float x,
    float y
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _rgn_hittest, 逻辑型, "libexdui.dll", "_rgn_hittest", 公开, 
    .参数 hRgn, 整数型,  , 
    .参数 x, 小数型,  , 
    .参数 y, 小数型,  , 
```

---

### Parameters / 参数

`hRgn`

Type: **HRGN**

区域句柄

`x`

Type: **FLOAT**

横向坐标

`y`

Type: **FLOAT**

纵向坐标


---

### Return Value / 返回值

Type: BOOL

命中测试<br>
如果坐标在区域内则返回 TRUE
