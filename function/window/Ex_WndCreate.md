---
description: Ex窗口创建
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_WndCreate (
    HWND hWndParent,
    LPCWSTR lpwzClassName,
    LPCWSTR lpwzWindowName,
    int x,
    int y,
    int Width,
    int Height,
    DWORD dwStyle,
    DWORD dwStyleEx
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_WndCreate, 整数型, "libexdui.dll", "Ex_WndCreate", 公开, 
    .参数 hWndParent, 整数型,  , 
    .参数 lpwzClassName, 整数型,  , 
    .参数 lpwzWindowName, 整数型,  , 
    .参数 x, 整数型,  , 
    .参数 y, 整数型,  , 
    .参数 Width, 整数型,  , 
    .参数 Height, 整数型,  , 
    .参数 dwStyle, 整数型,  , 
    .参数 dwStyleEx, 整数型,  , 
```

---

### Parameters / 参数

`hWndParent`

Type: **HWND**

父窗口句柄 如果没有可置 NULL

`lpwzClassName`

Type: **LPCWSTR**

窗口类名

`lpwzWindowName`

Type: **LPCWSTR**

窗口标题

`x`

Type: **INT32**

窗口左上角X坐标

`y`

Type: **INT32**

窗口左上角Y坐标

`Width`

Type: **INT32**

窗口宽度

`Height`

Type: **INT32**

窗口高度

`dwStyle`

Type: **DWORD**

窗口样式 参见  [Window Styles](https://docs.microsoft.com/en-us/windows/win32/winmsg/window-styles)

`dwStyleEx`

Type: **DWORD**

窗口扩展样式 参见  [Extended Window Styles](https://docs.microsoft.com/en-us/windows/win32/winmsg/extended-window-styles)

---

### Return Value / 返回值

Type: INT32

创建窗口