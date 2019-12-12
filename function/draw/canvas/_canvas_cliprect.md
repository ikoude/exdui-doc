---
description: 画布_裁剪矩形
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_cliprect (
    HCANVAS hCanvas,
    int     left,
    int     top,
    int     right,
    int     bottom,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_cliprect, 逻辑型, "libexdui.dll", "_canvas_cliprect", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 left, 整数型,  , 
    .参数 top, 整数型,  , 
    .参数 right, 整数型,  , 
    .参数 bottom, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`left`

Type: **INT32**

左边

`top`

Type: **INT32**

顶边

`right`

Type: **INT32**

右边

`bottom`

Type: **INT32**

底边

---

### Return Value / 返回值

Type: BOOL

裁剪矩形