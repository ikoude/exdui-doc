---
description: 布局_置属性
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_getprop (
    int hLayout,
    int dwPropID,
    int pvValue
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_setprop, 逻辑型, "libexdui.dll", "_layout_setprop", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 dwPropID, 整数型,  , 
    .参数 pvValue, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`dwPropID`

Type: **INT32**

属性ID

`pvValue`

Type: **INT32**

传入的属性值

---

### Return Value / 返回值

Type: BOOL
