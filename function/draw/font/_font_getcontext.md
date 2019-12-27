---
description: 字体_取上下文
---

### Syntax / 函数原型

```C++
int* __stdcall 
_font_getcontext (
    HFONT hFont
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _font_getcontext, 整数型, "libexdui.dll", "_font_getcontext", 公开, 
    .参数 hFont, 整数型,  , 
```

---

### Parameters / 参数

`hFont`

Type: **HFONT**

字体句柄

---

### Return Value / 返回值

Type: INT32*

成功返回字体上下文指针
