---
description: 画布_取宽高
---

### Syntax / 函数原型

```C++
HDC __stdcall 
_canvas_flush (
    HCANVAS hCanvas,
    int*    width,
    int*    height
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_getsize, 逻辑型, "libexdui.dll", "_canvas_getsize", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 width, 整数型, 传址 , 
    .参数 height, 整数型, 传址 , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`width`

Type: **INT32***

宽度

`height`

Type: **INT32***

高度


---

### Return Value / 返回值

Type: BOOL

取画布宽高