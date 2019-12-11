---
description: Ex绘制主题数据
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_ThemeDrawControl (
    HANDLE hTheme,
    HANDLE hCanvas,
    float  dstLeft,
    float  dstTop,
    float  dstRight,
    float  dstBottom,
    int    atomClass,
    int    atomSrcRect,
    DWORD  dwAlpha
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeDrawControl, 逻辑型, "libexdui.dll", "Ex_ThemeDrawControl", 公开, 
    .参数 hTheme, 整数型,  , 
    .参数 hCanvas, 整数型,  , 
    .参数 dstLeft, 小数型,  , 
    .参数 dstTop, 小数型,  , 
    .参数 dstRight, 小数型,  , 
    .参数 dstBottom, 小数型,  , 
    .参数 atomClass, 整数型,  , 
    .参数 atomSrcRect, 整数型,  , 
    .参数 dwAlpha, 整数型,  , 
```

---

### Parameters / 参数

`hTheme`

Type: **HANDLE**

主题句柄

`hCanvas`

Type: **HANDLE**

画板句柄

`dstLeft`

Type: **FLOAT**

目标左边

`dstTop`

Type: **FLOAT**

目标顶边

`dstRight`

Type: **FLOAT**

目标右边

`dstBottom`

Type: **FLOAT**

目标底边

`atomClass`

Type: **INT32**

\-

`atomSrcRect`

Type: **INT32**

\-

`dwAlpha`

Type: **DWORD**

透明度 (0-255)

---

### Return Value / 返回值

Type: BOOL

绘制主题数据