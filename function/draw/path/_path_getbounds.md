---
description: 路径_取边界矩形
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_getbounds (
    HPATH hPath,
    RECT* lpBounds
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_getbounds, 整数型, "libexdui.dll", "_path_getbounds", 公开, 取路径边界矩形
    .参数 hPath, 整数型,  , 
    .参数 lpBounds, 整数型,  , 
```

---

### Parameters / 参数

`hPath`

Type: **HPATH**

路径句柄

`lpBounds`

Type: **RECT***

路径的边界矩形

---

### Return Value / 返回值

Type: INT32

取路径边界矩形
