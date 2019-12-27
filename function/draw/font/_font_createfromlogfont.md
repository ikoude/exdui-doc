---
description: 字体_创建自逻辑字体
---

### Syntax / 函数原型

```C++
HFONT __stdcall 
_font_createfromlogfont (
    int *lpLogfont
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _font_createfromlogfont, 整数型, "libexdui.dll", "_font_createfromlogfont", 公开, 
    .参数 lpLogfont, 整数型,  , 
```

---

### Parameters / 参数

`lpLogfont`

Type: **INT32**

逻辑字体指针

---

### Return Value / 返回值

Type: HFONT

创建成功 返回新的字体句柄
