---
description: 画布_调整大小
---

### Syntax / 函数原型

```C++
BOOL __stdcall 
_canvas_resize (
    HCANVAS hCanvas,
    int     width,
    int     height,
    bool    fCopy
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_resize, 逻辑型, "libexdui.dll", "_canvas_resize", 公开, 重新设置尺寸。
    .参数 hCanvas, 整数型,  , 
    .参数 width, 整数型,  , 
    .参数 height, 整数型,  , 
    .参数 fCopy, 逻辑型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`width`

Type: **INT32**

画布宽度

`height`

Type: **HANDLE**

画布高度

`fCopy`

Type: **逻辑型**

是否拷贝原图像

---

### Return Value / 返回值

Type: BOOL

调整画布大小