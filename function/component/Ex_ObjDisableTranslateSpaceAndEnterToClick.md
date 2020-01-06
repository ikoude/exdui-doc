---
description: 控件_禁止转换空格回车为单击
---

### Syntax / 函数原型

```C++
bool __stdcall 
Ex_ObjDisableTranslateSpaceAndEnterToClick (
    HOBJ hObj,
    bool fDisable
);

```

##### 易语言声明

```Elang
.版本 2

.DLL命令 Ex_ObjDisableTranslateSpaceAndEnterToClick, 逻辑型, "libexdui.dll", "Ex_ObjDisableTranslateSpaceAndEnterToClick", 公开, 
    .参数 hObj, 整数型,  , 
    .参数 fDisable, 逻辑型,  , 
```

---

### Parameters / 参数

`hObj`

Type: **HOBJ**

控件句柄

`fDisable`

Type: **BOOL**

是否禁止转换

---

### Return Value / 返回值

Type: BOOL

设置控件是否禁止转换空格和回车为单击事件
