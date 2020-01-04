---
description: 控件_开始绘制
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_ObjBeginPaint (
    HOBJ            hObj,
    EX_PAINTSTRUCT* lpPS
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjBeginPaint, 逻辑型, "libexdui.dll", "Ex_ObjBeginPaint", 公开, 
    .参数 hObj, 整数型,  , 
    .参数 lpPS, EX_PAINTSTRUCT,  , 
```

---

### Parameters / 参数

`hObj`

Type: **HOBJ**

控件句柄

`lpPS`

Type: **EX_PAINTSTRUCT***

绘图数据

---

### Return Value / 返回值

Type: BOOL

开始绘制
