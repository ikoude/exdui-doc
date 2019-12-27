---
description: 字体_创建自字体名称
---

### Syntax / 函数原型

```C++
HFONT __stdcall 
_font_createfromfamily (
    LPCWSTR lpwzFontFace,
    DWORD   dwFontSize,
    DWORD   dwFontStyle
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _font_createfromfamily, 整数型, "libexdui.dll", "_font_createfromfamily", 公开, 
    .参数 lpwzFontFace, 整数型,  , 
    .参数 dwFontSize, 整数型,  , 
    .参数 dwFontStyle, 整数型,  , 
```

---

### Parameters / 参数

`lpwzFontFace`

Type: **LPCWSTR**

字体名称

`dwFontSize`

Type: **DWORD**

字体大小

`dwFontStyle`

Type: **DWORD**

字体风格

---

### Return Value / 返回值

Type: HBRUSH

创建成功 返回新的字体句柄
