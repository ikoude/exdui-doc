---
description: 画布_取设备上下文
---

### Syntax / 函数原型

```C++
HDC __stdcall 
_canvas_getdc (
    HCANVAS hCanvas
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_getdc, 整数型, "libexdui.dll", "_canvas_getdc", 公开, 
    .参数 hCanvas, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

---

### Return Value / 返回值

Type: HDC

获取设备上下文 *DeviceContext*