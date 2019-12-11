---
description: Ex取主题颜色
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ThemeGetColor (
    HANDLE hTheme,
    int    nIndex
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeGetColor, 整数型, "libexdui.dll", "Ex_ThemeGetColor", 公开, 
    .参数 hTheme, 整数型,  , 
    .参数 nIndex, 整数型,  , 
```

---

### Parameters / 参数

`hTheme`

Type: **HANDLE**

主题句柄

`nIndex`

Type: **INT32**

颜色索引 参见 [COLOR_EX](../../const/COLOR_EX)

---

### Return Value / 返回值

Type: INT32

获取主题相关颜色值