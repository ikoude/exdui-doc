---
description: 字体_复制
---

### Syntax / 函数原型

```C++
HFONT __stdcall 
_font_copy (
    HFONT hFont,
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _font_copy, 整数型, "libexdui.dll", "_font_copy", 公开,
    .参数 hFont, 整数型,  , 
```

---

### Parameters / 参数

`hFont`

Type: **HFONT**

欲复制的字体句柄

---

### Return Value / 返回值

Type: HFONT

复制成功 返回新的字体句柄
