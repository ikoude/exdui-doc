---
description: 布局_绝对布局_锁定
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_absolute_lock (
    int hLayout,
    int hObjChild,
    int tLeft,
    int tTop,
    int tRight,
    int tBottom,
    int tWidth,
    int tHeight
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_absolute_lock, 逻辑型, "libexdui.dll", "_layout_absolute_lock", 公开, 按当前位置锁定
    .参数 hLayout, 整数型,  , 
    .参数 hObjChild, 整数型,  , 
    .参数 tLeft, 整数型,  ,
    .参数 tTop, 整数型,  , 
    .参数 tRight, 整数型,  , 
    .参数 tBottom, 整数型,  , 
    .参数 tWidth, 整数型,  , 
    .参数 tHeight, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`hObjChild`

Type: **HANDLE**

子组件句柄

`tLeft`

Type: **INT32**

`tTop`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP_ABSOLUTE.md)

`tRight`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP_ABSOLUTE.md)

`tBottom`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP_ABSOLUTE.md)

`tWidth`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP_ABSOLUTE.md)

`tHeight`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP_ABSOLUTE.md)

---

### Return Value / 返回值

Type: BOOL
