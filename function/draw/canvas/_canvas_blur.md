---
description: 画布_模糊
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_blur (
    HCANVAS hCanvas,
    float   fDeviation,
    int*    lprc
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_blur, 逻辑型, "libexdui.dll", "_canvas_blur", 公开,
    .参数 hCanvas, 整数型,  , 
    .参数 fDeviation, 小数型,  , 
    .参数 lprc, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`fDeviation`

Type: **FLOAT**

xxx

`lprc`

Type: **INT32**

矩形


---

### Return Value / 返回值

Type: BOOL

模糊