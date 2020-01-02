---
description: 路径_关闭
---

### Syntax / 函数原型

```C++
int __stdcall 
_path_create (
    int    brushmode,
    DWORD  dwFlags,
    HPATH* hPath
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _path_create, 整数型, "libexdui.dll", "_path_create", 公开, 
    .参数 brushmode, 整数型,  , 
    .参数 dwFlags, 整数型,  , 
    .参数 hPath, 整数型, 传址 , 

```

---

### Parameters / 参数

`brushmode`

Type: **INT32**

刷子模式

`dwFlags`

Type: **DWORD**

参见 [EPF](../../const/EPF.md)

`hPath`

Type: **HPATH***

路径句柄

---

### Return Value / 返回值

Type: INT32

创建路径
