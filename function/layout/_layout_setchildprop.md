---
description: 布局_置组件属性
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_setchildprop (
    int hLayout,
    int hObj,
    int dwPropID,
    int pvValue
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_setchildprop, 逻辑型, "libexdui.dll", "_layout_setchildprop", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 hObj, 整数型,  , 
    .参数 dwPropID, 整数型,  , 
    .参数 pvValue, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`hObj`

Type: **HANDLE**

组件句柄

`dwPropID`

Type: **INT32**

属性ID

`pvValue`

Type: **INT32**

传入的属性值

---

### Return Value / 返回值

Type: BOOL
