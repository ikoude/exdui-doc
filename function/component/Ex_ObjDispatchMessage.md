---
description: 控件_分发消息
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ObjDispatchMessage (
    HOBJ hObj,
    int  uMsg,
    int  wParam,
    int  lParam,
);

```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjDispatchMessage, 整数型, "libexdui.dll", "Ex_ObjDispatchMessage", 公开, 
    .参数 hObj, 整数型,  , 
    .参数 uMsg, 整数型,  , 
    .参数 wParam, 整数型,  , 
    .参数 lParam, 整数型,  , 
```

---

### Parameters / 参数

`hObj`

Type: **HOBJ**

控件句柄

`uMsg`

Type: **INT32**

消息ID

`wParam`

Type: **INT32**

参数一

`lParam`

Type: **INT32**

参数二

---

### Return Value / 返回值

Type: INT32

分发消息
