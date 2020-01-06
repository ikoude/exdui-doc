---
description: 控件_创建扩展
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ObjCreateEx (
    DWORD   dwStyleEx,
    LPCWSTR lptszClassName,
    LPCWSTR lptszObjTitle,
    DWORD   dwStyle,
    int     x,
    int     y,
    int     width,
    int     height,
    HOBJ    hParent,
    int     nID,
    DWORD   dwTextFormat,
    int     lParam,
    HTHEME  hTheme,
    int*    lpfnMsgProc
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjCreateEx, 整数型, "libexdui.dll", "Ex_ObjCreateEx", 公开, 
    .参数 dwStyleEx, 整数型,  , 
    .参数 lptszClassName, 整数型,  , 
    .参数 lptszObjTitle, 整数型,  , 
    .参数 dwStyle, 整数型,  , 
    .参数 x, 整数型,  , 
    .参数 y, 整数型,  , 
    .参数 width, 整数型,  , 
    .参数 height, 整数型,  , 
    .参数 hParent, 整数型,  , 
    .参数 nID, 整数型,  , 
    .参数 dwTextFormat, 整数型,  , 
    .参数 lParam, 整数型,  , 
    .参数 hTheme, 整数型,  , 
    .参数 lpfnMsgProc, 整数型,  , 
```

---

### Parameters / 参数

`dwStyleEx`

Type: **DWORD**

组件扩展风格 参见 [EOS_EX](../../const/EOS_EX.md)

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

`nID`

Type: **INT32**

组件唯一ID

`dwTextFormat`

Type: **DWORD**

字符串默认格式 参见 [DT](../../const/DT.md)

`lParam`

Type: **INT32**

参数一

`hTheme`

Type: **HANDLE**

主题句柄<br>
NULL为默认

`lpfnMsgProc`

Type: **INT32***

窗口消息回调函数指针

---

### Return Value / 返回值

Type: INT32

创建组件扩展
