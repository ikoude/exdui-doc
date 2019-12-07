---
description: 布局_取属性
---

### Syntax / 函数原型

```C++
int __stdcall 
_layout_getprop (
    int hLayout,
    int dwPropID
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_getprop, 整数型, "libexdui.dll", "_layout_getprop", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 dwPropID, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`dwPropID`

Type: **INT32**

属性ID

---

### Return Value / 返回值

Type: INT32

组件的属性值
