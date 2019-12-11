---
description: Ex释放主题
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_ThemeFree (
    HTHEME hTheme
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeFree, 逻辑型, "libexdui.dll", "Ex_ThemeFree", 公开, 
    .参数 hTheme, 整数型,  , 
```

---

### Parameters / 参数

`hTheme`

Type: **HTHEME**

需要释放的主题包句柄

---

### Return Value / 返回值

Type: BOOL

释放一个主题包文件