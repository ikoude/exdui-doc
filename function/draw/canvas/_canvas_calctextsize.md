---
description: 画布_测量文本
---

### Syntax / 函数原型

```C++
bool __stdcall 
_canvas_calctextsize (
    HCANVAS hCanvas,
    HFONT   hFont,
    LPCWSTR lpwzText,
    DWORD   dwLen,
    DWORD   dwDTFormat,
    int     lParam,
    int     layoutWidth,
    int     layoutHeight,
    int*    lpWidth,
    int*    lpHeight,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _canvas_calctextsize, 逻辑型, "libexdui.dll", "_canvas_calctextsize", 公开, 
    .参数 hCanvas, 整数型,  , 
    .参数 hFont, 整数型,  , 
    .参数 lpwzText, 整数型,  , 
    .参数 dwLen, 整数型,  , 
    .参数 dwDTFormat, 整数型,  , 
    .参数 lParam, 整数型,  , 
    .参数 layoutWidth, 小数型,  , 
    .参数 layoutHeight, 小数型,  , 
    .参数 lpWidth, 整数型,  , 
    .参数 lpHeight, 整数型,  , 
```

---

### Parameters / 参数

`hCanvas`

Type: **HCANVAS**

画布句柄

`hFont`

Type: **HFONT**

字体句柄

`lpwzText`

Type: **LPCWSTR**

字符串指针

`dwLen`

Type: **DWORD**

字符串长度

`dwDTFormat`

Type: **DWORD**

\-

`lParam`

Type: **INT32**

附加参数

`layoutWidth`

Type: **FLOAT**

布局宽度

`layoutHeight`

Type: **FLOAT**

布局高度

`lpWidth`

Type: **INT32**

宽度指针

`lpHeight`

Type: **INT32**

高度指针

---

### Return Value / 返回值

Type: BOOL

测量文本