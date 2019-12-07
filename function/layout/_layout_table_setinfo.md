---
description: 布局_置表格信息
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_table_setinfo (
    int hLayout,
    int aRowHeight,
    int cRows,
    int aCellWidth,
    int cCells
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_table_setinfo, 逻辑型, "libexdui.dll", "_layout_table_setinfo", 公开, 
    .参数 hLayout, 整数型,  , 
    .参数 aRowHeight, 整数型,  , 
    .参数 cRows, 整数型,  , 
    .参数 aCellWidth, 整数型,  , 
    .参数 cCells, 整数型,  , 
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`aRowHeight`

Type: **INT32**

行高度

`cRows`

Type: **INT32**

行数量

`aCellWidth`

Type: **INT32**

格宽度

`cCells`

Type: **INT32**

格数量

---

### Return Value / 返回值

Type: BOOL
