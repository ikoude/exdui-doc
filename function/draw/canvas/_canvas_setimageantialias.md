---
description: 画布_置图像抗锯齿
---

### Syntax / 函数原型

```C++
BOOL __stdcall 
_canvas_setimageantialias (
    HCANVAS hCanvas,
    bool    antialias
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_setimageantialias, 逻辑型, "libexdui.dll", "_canvas_setimageantialias", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 antialias, 逻辑型,  , 

```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`antialias`

Type: **BOOL**

是否抗锯齿

---

### Return Value / 返回值

Type: BOOL

设置画布图像抗锯齿