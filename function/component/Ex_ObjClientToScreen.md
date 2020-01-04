---
description: 控件_客户区坐标到屏幕坐标
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ObjClientToScreen (
    HOBJ hObj,
    int* x,
    int* y
);

```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjClientToScreen, 逻辑型, "libexdui.dll", "Ex_ObjClientToScreen", 公开, 
    .参数 hObj, 整数型,  , 
    .参数 x, 整数型, 传址 , 
    .参数 y, 整数型, 传址 , 
```

---

### Parameters / 参数

`hObj`

Type: **HOBJ**

控件句柄

`x`

Type: **INT32***

横坐标

`y`

Type: **INT32***

纵坐标

---

### Return Value / 返回值

Type: INT32

客户区坐标到屏幕坐标
