---
description: Ex取主题属性值指针
---

### Syntax / 函数原型

```C++
int __stdcall 
Ex_ThemeGetValuePtr (
    HANDLE hTheme,
    int    atomClass,
    int    atomProp
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ThemeGetValuePtr, 整数型, "libexdui.dll", "Ex_ThemeGetValuePtr", 公开, 
    .参数 hTheme, 整数型,  , 
    .参数 atomClass, 整数型,  , 
    .参数 atomProp, 整数型,  , 
```

---

### Parameters / 参数

`hTheme`

Type: **HANDLE**

主题句柄

`atomClass`

Type: **INT32**

\-

`atomProp`

Type: **INT32**

\-

---

### Return Value / 返回值

Type: INT32

获取组件属性值指针