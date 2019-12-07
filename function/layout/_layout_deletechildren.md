---
description: 布局_删除组件集
---

### Syntax / 函数原型

```C++
bool __stdcall 
_layout_deletechildren (
    int hLayout,
    int dwObjClassATOM
);
```

##### 易语言声明

```Elang
.版本 2

.DLL命令 _layout_deletechildren, 逻辑型, "libexdui.dll", "_layout_deletechildren", 公开,
    .参数 hLayout, 整数型,  ,
    .参数 dwObjClassATOM, 整数型,  ,
```

---

### Parameters / 参数

`hLayout`

Type: **HANDLE**

布局句柄

`dwObjClassATOM`

Type: **INT32**

0或空为所有

---

### Return Value / 返回值

Type: BOOL
