---
description: 画布_清除
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_clear (
    HCANVAS hCanvas,
    int     lColor
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_clear, 逻辑型, "libexdui.dll", "_canvas_clear", 公开,
    .参数 hCanvas, 整数型,  , 
    .参数 lColor, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`lColor`

Type: **INT32**

清除颜色

---

### Return Value / 返回值

Type: BOOL

清除画布