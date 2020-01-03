---
description: 路径_命中测试
---

### Syntax / 函数原型

```C++
bool __stdcall 
_path_hittest (
    HPATH hPath,
    float x,
    float y
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_hittest, 逻辑型, "libexdui.dll", "_path_hittest", 公开, 
    .参数 hPath, 整数型,  , 
    .参数 x, 小数型,  , 
    .参数 y, 小数型,  , 
```

---

### Parameters / 参数

`hPath`

Type: **HPATH**

路径句柄

`x`

Type: **FLOAT**

横坐标

`y`

Type: **FLOAT**

纵坐标

---

### Return Value / 返回值

Type: BOOL

测试坐标是否在可见路径内
