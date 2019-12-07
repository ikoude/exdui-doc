---
description: 布局_创建
---

### Syntax / 函数原型

```C++
int __stdcall 
_layout_create (
    int nType,
    int hObjBind
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_create, 整数型, "libexdui.dll", "_layout_create", 公开, hLayout
    .参数 nType, 整数型,  ,
    .参数 hObjBind, 整数型,  ,
```

---

### Parameters / 参数

`nType`

Type: **INT32**

创建的布局类型, 参见  [ELT](../../const/ELT.md)

`hObjBind`

Type: **HANDLE**

布局绑定的组件句柄

---

### Return Value / 返回值

Type: HANDLE

布局句柄