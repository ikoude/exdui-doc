---
description: 字体_取逻辑字体
---

### Syntax / 函数原型

```C++
bool __stdcall 
_font_getlogfont (
    HFONT hFont,
    int   *lpLogFont
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _font_getlogfont, 逻辑型, "libexdui.dll", "_font_getlogfont", 公开, 获取逻辑字体
    .参数 hFont, 整数型,  , 
    .参数 lpLogFont, 整数型,  , 
```

---

### Parameters / 参数

`hFont`

Type: **HFONT**

字体句柄

`lpLogFont`

Type: **INT32***

保存逻辑字体的指针

---

### Return Value / 返回值

Type: BOOL

获取逻辑字体
