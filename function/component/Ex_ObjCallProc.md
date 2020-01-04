---
description: 控件_调用过程
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ObjCallProc (
    int  lpPrevObjProc,
    HWND hWnd,
    HOBJ hObj,
    int  uMsg,
    int  wParam,
    int  lParam,
    int* pvData
);

```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjCallProc, 整数型, "libexdui.dll", "Ex_ObjCallProc", 公开, 
    .参数 lpPrevObjProc, 整数型,  , 
    .参数 hWnd, 整数型,  , 
    .参数 hObj, 整数型,  , 
    .参数 uMsg, 整数型,  , 
    .参数 wParam, 整数型,  , 
    .参数 lParam, 整数型,  , 
    .参数 pvData, 整数型,  , 
```

---

### Parameters / 参数

`lpPrevObjProc`

Type: **INT32**

上一个组件的消息过程

`hWnd`

Type: **HANDLE**

窗口句柄

`hObj`

Type: **HOBJ**

控件句柄

`uMsg`

Type: **INT32**

消息

`wParam`

Type: **INT32**

附加参数一<br>
实际意义视消息而定

`lParam`

Type: **INT32**

附加参数二<br>
实际意义视消息而定

`pvData`

Type: **INT32**

\-

---

### Return Value / 返回值

Type: INT32

调用过程
