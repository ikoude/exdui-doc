---
description: 控件_创建
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ObjCreate (
    LPCWSTR lptszClassName,
    LPCWSTR lptszObjTitle,
    DWORD   dwStyle,
    int     x,
    int     y,
    int     width,
    int     height,
    HOBJ    hParent
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjCreate, 整数型, "libexdui.dll", "Ex_ObjCreate", 公开, .
    .参数 lptszClassName, 整数型,  , 
    .参数 lptszObjTitle, 整数型,  , 
    .参数 dwStyle, 整数型,  , 
    .参数 x, 整数型,  , 
    .参数 y, 整数型,  , 
    .参数 width, 整数型,  , 
    .参数 height, 整数型,  , 
    .参数 hParent, 整数型,  , 

```

---

### Parameters / 参数

`lptszClassName`

Type: **LPCWSTR**

组件类名

`lptszObjTitle`

Type: **LPCWSTR**

组件标题

`dwStyle`

Type: **DWORD**

组件风格 参见 [EOS](../../const/EOS.md)

`x`

Type: **INT32**

组件左边

`y`

Type: **INT32**

组件顶边

`width`

Type: **INT32**

组件宽度

`height`

Type: **HANDLE**

组件高度

`hParent`

Type: **HOBJ**

父组件句柄

---

### Return Value / 返回值

Type: BOOL

创建组件
