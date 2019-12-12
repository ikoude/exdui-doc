---
description: 画刷_创建自画布
---

### Syntax / 函数原型

```C++
HBRUSH __stdcall 
_brush_create (
    HCANVAS hCanvas,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _brush_createfromcanvas, 整数型, "libexdui.dll", "_brush_createfromcanvas", 公开, 
    .参数 hCanvas, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

---

### Return Value / 返回值

Type: HBRUSH

创建成功 返回画刷句柄
