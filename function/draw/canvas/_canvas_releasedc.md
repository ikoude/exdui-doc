---
description: 画布_释放设备上下文
---

### Syntax / 函数原型

```C++
BOOL __stdcall 
_canvas_releasedc (
    HCANVAS hCanvas
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_releasedc, 逻辑型, "libexdui.dll", "_canvas_releasedc", 公开, 
    .参数 hCanvas, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

---

### Return Value / 返回值

Type: BOOL

释放设备上下文