Title: _layout_absolute_lock

Date: 2019年8月4日11时52分23秒

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

### 易语言声明

```Elang
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

`hObjChild`

Type: **HANDLE**

`tLeft`

Type: **INT32**

`tTop`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP.md)

`tRight`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP.md)

`tBottom`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP.md)

`tWidth`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP.md)

`tHeight`

Type: **INT32**

请参阅 [ELCP_ABSOLUTE_XXX_TYPE](../../const/ELCP.md)
